# Hash_Function
# Ce travail est réalisé par les étudiants suivants:
# NIENZI MABIALA EDDY
# NGOY ILOKO MARDOCHEE
# MONINGA MAYENGE ISAAC
# TSHIBANGU KABONGO EXAUCEE
# IYANZA MPIA SHADRACK
# KUYANGISA KATEMBO
# MILOLO MANDE
# MULOKO MBUYI JOLIDA
# PHAKA MASIALA JENNY
# KONGA KABINDA BONHEUR

# Nous importons la bibliothèque standard de hachage disponible en python
import hashlib
data=input("entrer la donnée: ")
# nous utilisons SHA-256 comme algorithme de hachage
hash_object = hashlib.sha256(data.encode())
# conversion en hexadecimal
hashed_data = hash_object.hexdigest()
# resutat
hashed_result = hashed_data
print("resultat du hachage :", hashed_result)
