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
```
Sol:  
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30 32 34 36 38 40 42 44 46 48 50 52 54 56 58 60 62 64 66 68 70 72 74 76 78 80 82 84 86 88 90 92 94 96 98 100 102 104 106 108 110 112 114 116 118 120
