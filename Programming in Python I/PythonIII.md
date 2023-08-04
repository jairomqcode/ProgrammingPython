# Estructura de Control: if - else.  

La estructura de control **if-else** es una declaración condicional que le permite ejecutar diferentes bloques de código dependiendo de si una condición es verdadera o falsa. La sintaxis de una sentencia **if-else** es la siguiente:

```python{
"""
Si se_cumple_esta_condicion:
  # Ejecutar grupo de instrucciones

Si No:
  # Ejecutar otro grupo de instrucciones
"""
```

Expresado de otra manera:  
```python{
if condicion:
  instrucciones
else:
  Otras instrucciones
```

### Programa: Adivina mi color favorito.

```python{
# Definimos la variable, entrada de dato:
color = input("Adivina mi color favorito: ")

# Condicional: if - else.
if color == "azul":
    print("En hora buena")
    print("El color es azul")

else:
    print("El color es incorrecto")
}
```

En Python existen ciertos tipos de operadores, llamados operadores de comparación, que se utilizan para trabajar con las condicionales if - else. Estos operadores los podemos observar a continuación:


| Operador | Nombre | Descripción |
| :------: | :------: | :------: |
| == | Igual | devuelve **True** si los dos operandos son iguales, **False** en caso contrario |
| != | Distinto | devuelve **True** si los dos operandos no son iguales, **False** en caso contrario |
| < | Menor que | devuelve **True** si el operando izquierdo es menor que el operando derecho, **False** en caso contrario |
| > | Mayor que | devuelve **True** si el operando izquierdo es mayor que el operando derecho, **False** en caso contrario |
| <= | Menor o igual que | devuelve **True** si el operando izquierdo es menor o igual que el operando derecho, **False** en caso contrario |
| >= | Mayor o igual que | devuelve **True** si el operando izquierdo es mayor o igual que el operando derecho, **False** en caso contrario |

```python{
# Programa que nos indica si la variable year (que tiene un valor de 2021) es mayor o igual que el año actual 2023:
# Definimos la variable:
year = 2021
# Creamos las condiciones:
if yaer >= 2023:
  print("Estamos en 2023 en adelante!")
else:
  print("Es un año anterior a 2023")
```
Sol: Es un año anterior a 2023

```python{
# Programa que nos muestra si una persona es mayor de edad o no, si es así, nos muestra el continente y ciudad de la persona.
# Definimos las variables:
nombre = "Gian Nacci"
ciudad = "Roma"
continente = "Europeo"
edad = 20
mayoria_edad = 18

# Condicionales:
if edad >= mayoria_edad:
  print(f"{nombre} es mayor de edad!!")

  if continente == "Europeo":
    print(f"El usuario es Europeo y de la ciudad de {ciudad}")
  else:
    print("No es Europeo")

else:
   print(f"{nombre} no es mayor de edad")
```
Sol:  
Gian Nacci es mayor de edad!!  
El usuario es Europeo y de la ciudad de Roma  

## Condicional elif.  
La declaración **elif** en Python se usa para verificar condiciones adicionales después de la declaración **if**. Es la abreviatura de **"else if"** y se puede usar varias veces en un programa. La sintaxis de la instrucción **elif** es la siguiente:  

```python{
if condition1:
  # code to be executed if condition1 is True
elif condition2:
  # code to be executed if condition2 is True
elif condition3:
  # code to be executed if condition3 is True
else:
  # code to be executed if none of the conditions are True
```

```python{
# Programa que indica el dia de la semana.
dia = int(input("Introduce el número del día de la semana: "))

if dia == 1:
  print("Es lunes")
elif dia == 2:
  print("Es martes")
elif dia == 3:
  print("Es miércoles")
elif dia == 4:
  print("Es jueves")
elif dia == 5:
  print("Es viernes")   
else:
  print("Es fin de semana")
```
Sol:
Introduce el número del día de la semana: 2  
Es martes
