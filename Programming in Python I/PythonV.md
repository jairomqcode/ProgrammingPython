# Bloques de ejercicios I.

## Ejercicio 1. 
```Python{
"""
- Crear variables una "pais" y otra "continente".
- Mostrar su valor por pantalla (imprimir).
- Poner un comentario diciendo el tipo de dato.
"""

# Creamos las variables:
pais = "España"              #Dato tipo string.
continente = "Europa"        #Dato tipo string.

print(f"Hola mi nombre es Jairo soy de {pais} que pertenece al continente de {continente}")
```
Sol:  
Hola mi nombre es Jairo soy de España que pertenece al continente de Europa  

## Ejercicio 2.
```Python{
"""
Escribir un script que nos muestre por pantalla todos los números pares del 0 al 120. 
"""
# Utilizamos el bucle for:
for n in range(0, 61):
    n = 2*n
    print(n)

# Otra manera de hacerlo:
for contador in range(0, 121):
    if contador%2 == 0
        print(contador)

```
Sol:  
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30 32 34 36 38 40 42 44 46 48 50 52 54 56 58 60 62 64 66 68 70 72 74 76 78 80 82 84 86 88 90 92 94 96 98 100 102 104 106 108 110 112 114 116 118 120

## Ejercicio 3.
```Python{
"""
- Escribir los cuadrados de los primeros 60 números naturales.
- Hacerlo por el bucle for y while.
"""
# Utilizando el bucle for.
# Definimos una variable:
n = 1
# Utilizamos el bucle for:
for n in range(1,11):
    cuadrado = n**2
    print(f"El cuadrado de {n} es igual a {cuadrado}")

#Utilizando el bucle while.
# Definimos una variable contador:
contador = 1
#Utilizamos el bucle while:
while contador <= 10:
    cuadrado = contador**2
    print(f"El cuadrado del número {contador} es {cuadrado}")

    #Actualizar:
    contador +=1
```
Sol:  
El cuadrado de 1 es igual a 1  
El cuadrado de 2 es igual a 4  
El cuadrado de 3 es igual a 9  
El cuadrado de 4 es igual a 16  
El cuadrado de 5 es igual a 25  
El cuadrado de 6 es igual a 36  
El cuadrado de 7 es igual a 49  
El cuadrado de 8 es igual a 64  
El cuadrado de 9 es igual a 81  
El cuadrado de 10 es igual a 100
