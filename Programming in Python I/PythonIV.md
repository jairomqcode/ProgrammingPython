# Bucles en Python.

## Bucle For.
El **bucle for** es una estructura de control de flujo que se utiliza en programación para repetir un bloque de instrucciones un número determinado de veces. La sintaxis del bucle for en Python es la siguiente:

```python{
for variable in elemento_iterable:
    bloque de instrucciones
```

El iterable puede ser una lista, una tupla, un conjunto, un diccionario, etc. La variable se utiliza para iterar sobre los elementos del iterable. En cada iteración, la variable toma el valor del siguiente elemento del iterable. El bloque de instrucciones se ejecuta una vez por cada elemento del iterable.

El bucle for es una estructura de control muy versátil y se puede utilizar para realizar una gran variedad de tareas. Es una herramienta muy útil para recorrer colecciones de datos y realizar operaciones repetitivas.

Aquí hay algunos ejemplos de cómo se puede utilizar el bucle for en Python:  
* Recorrer una lista de números e imprimirlos en pantalla.
* Recorrer una lista de nombres y saludar a cada persona.
* Recorrer un diccionario y mostrar el valor de cada clave.
* Recorrer una matriz y calcular su suma.
* Recorrer una cadena de caracteres y contar el número de ocurrencias de cada letra.

Programa ejemplo donde una variable itera:
```python{
# Definimos una varible:
contador = 0
# Bucle:
for contador in range(0,3):
    print(f"Voy por el número: {contador}")
```
Sol:  
Voy por el número: 0  
Voy por el número: 1  
Voy por el número: 2

Programa que imprime la tabla de multiplicar del número (1 al 10) que desea el usuario:
```python{
# Entrada de datos:
numero_usuario = int(input("Introduce un número: "))

# Condicional:
if numero_usuario < 11:
    print(f"La tabla del número {numero_usuario}.")

    #Bucle For:
    for tabla_multiplicar in range(0, 11):
        #Operación matemática:
        valor = numero_usuario * tabla_multiplicar
        #Salida:
        print(f"{numero_usuario} * {tabla_multiplicar} = {valor}")

else:
    print("Número prohibido")
```
Sol:  
Introduce un número: 2  
La tabla del número 2.  
2 * 1 = 2  
2 * 2 = 4  
2 * 3 = 6  
2 * 4 = 8  
2 * 5 = 10  
2 * 6 = 12  
2 * 7 = 14  
2 * 8 = 16  
2 * 9 = 18  
2 * 10 = 20  

## Bucle While.  
Estructura de control que itera o repite la ejecución de una serie de instrucciones tantas veces como sea necesario, hasta que deje de cumplirse la condición.  

while condición:
    bloque de instrucciones
    actualización de contador
