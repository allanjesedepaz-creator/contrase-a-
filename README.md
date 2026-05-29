import random

# Caracteres posibles para la contraseña
caracteres = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"

# Pedir la longitud de la contraseña
longitud = int(input("Introduce la longitud de la contraseña: "))

# Variable donde se almacenará la contraseña generada
contrasena = ""

# Generar la contraseña
for i in range(longitud):
    contrasena += random.choice(caracteres)

# Mostrar la contraseña
print("Contraseña generada:", contrasena)
