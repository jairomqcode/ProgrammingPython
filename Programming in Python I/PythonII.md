# Operadores Aritméticos.  
Los **operadores** son símbolos especiales que representan cálculos, como la suma o la multiplicación. Los valores a los cuales se aplican esos operadores reciben el nombre de **operandos**.

Los operadores aritméticos **se utilizan para realizar operaciones matemáticas** con números en Python. Se utilizan para realizar operaciones de suma, resta, multiplicación, división, exponenciación y módulo.  

| Operador | Nombre | Descripción |
| :------: | :----: | :---------: |
| + | Adición | Suma dos operandos juntos |
| - | Sustracción | Resta el segundo operando del primer operando |
| * | Multiplicación | Multiplica dos operandos juntos |
| / | División | Divide el primer operando por el segundo operando |
| % | Módulos | Devuelve el resto de la división del primer operando por el segundo operando |
| ** | Exponenciación | Eleva el primer operando a la potencia del segundo operando |

```python {
# Defino dos variables:
numero1 = 10        # Operador asignación = 
numero2 = 7

# Operaciones Aritméticas:
suma = numero1 + numero2
resta = numero1 - numero2
multiplicacion = numero1 * numero2
division = numero1 / numero2
modulo = numero1 % numero2
potencia = numero1 ** numero2

# Resultados:
print("***** Calculadora *****")
print(f"La suma es: {suma}")
print(f"La resta es: {resta}")
print(f" La multiplicación es: {multiplicacion}")
print(f" La división es: {division}")
print(f" El módulo o resto de la división es: {modulo}")
print(f" 10 elevada a la potencia 7 es: {potencia}")
```

Sol:  
***** Calculadora *****  
La suma es: 17  
La resta es: 3  
La multiplicación es: 70  
La división es: 1.4285714285714286  
El módulo o resto de la división es: 3  
10 elevada a la potencia de 7 es: 10000000  

# Operadores de Asignación.  
Los operadores de asignación **se utilizan para asignar valores a las variables** en Python. Son una herramienta poderosa que se puede usar para manipular variables en su código.  

La siguiente tabla muestra los operadores de asignación en Python, junto con sus nombres y descripciones:  

| Operador | Nombre | Descripción |
| :------: | :----: | :---------: |
| = | Asignación sencilla | Asigna el valor del operando derecho al operando izquierdo |
| += | Asignación de adición | Asigna el valor del operando derecho al operando izquierdo y luego le suma el valor del operando izquierdo |
| -= | Asignación de resta | Asigna el valor del operando derecho al operando izquierdo y luego le resta el valor del operando izquierdo |
| *= | Asignación de multiplicación | Asigna el valor del operando derecho al operando izquierdo y luego multiplica el valor del operando izquierdo por él |
| /= | Asignación de división | Asigna el valor del operando derecho al operando izquierdo y luego divide el valor del operando izquierdo por este |
| %= | Asignación de módulo | Asigna el valor del operando derecho al operando izquierdo y luego calcula el módulo del valor del operando izquierdo por él |
| **= | Asignación de exponenciación | Asigna el valor del operando derecho al operando izquierdo y luego eleva el valor del operando izquierdo a la potencia del valor del operando derecho |

Existen otros operadores de asignación que pueden ser estudiados luego.  
```python{
# Definimos una variable.
edad = 5          # Asignación sencilla.
# Asignación de adición:
edad += 5
#edad = edad + 5  # Equivalente a la anterior.
# Resultados:
print(edad)
```
Sol: 10  

```python{
# Definimos una variable.
edad = 5          # Asignación sencilla.
# Asignación de resta:
edad -= 5
#edad = edad - 5  # Equivalente a la anterior.
# Resultados:
print(edad)
```
Sol: 0  

# Entrada y Salida de datos.  
La función **input ()** en Python **se usa para recibir información del usuario**. Es una función incorporada, lo que significa que es parte del propio lenguaje Python.  

La función **print()** en Python **se usa para imprimir la salida en la pantalla**. Es una función incorporada, lo que significa que es parte del propio lenguaje Python. Ejemplo para aplicar las funciones input() y print(): 

```python{
# Entrada:
nombre = input("Introduce tu nombre: ")
edad = input("Cual es tu edad?: ")
# Salida:
print(f"Hola {nombre}, bienvenido. Tienes {edad} años")
```
Sol: Hola niclau, bienvenido. Tienes 38 años  

Programa de conversión de monedas.  

```python{
"""Hola bienvenidos al programa de conversión de monedas de EUROS a LIBRAS"""
# Valores de entradas.
valor_euro = float(input("Introduce el monto en Euro:"))

# Ecuación matemática para convertir moneda de euro a libra:
Valor_libras = valor_euro * 0.86

# Valores de salidas.
# Imprimir el valor de la moneda en libras:
print(f"El monto en Libras es: {Valor_libras}")
```

Sol:  
Introduce el monto en Euro: 10  
El  monto en Libras es: 8.6  

