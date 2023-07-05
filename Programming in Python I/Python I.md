# Salida por pantalla: la función print().

## Función print().

La función **print()** permite mostrar cadenas de caracteres en pantalla. Las **cadenas de caracteres** son una secuencia que puede contener caracteres especiales o alfanuméricos.
La cadena a mostrar se escribe como argumento de la función:

```python{
print("Hola")
```
Sol: Hola

```python{
print(7)
```
Sol: 7

Las cadenas se pueden delimitar tanto por comillas dobles (") como por comillas simples (').

```python{
print('Hola')
```
Sol: Hola

También, se admiten varios argumentos seguidos. En el programa, los argumentos deben separarse por comas. Los argumentos se muestran en el mismo orden y en la misma línea, separados por espacios:

```python{
print("Hola", "Nico")
```
Sol: Hola Nico

```python{
print("Hola", "Lau")
```
Sol: Hola Lau

Podemos escribir dos argumentos seguidos sin separarlos por coma, obteniendo como resultado las dos cadenas escritas sin separación de espacios (unidas).

```python{
print("Hola" "Nico")
```
Sol: HolaNico

```python{
print("Hola" "Lau")
```
Sol: HolaLau

Al final de cada print(), Python añade automáticamente un salto de línea:

```python{
print("Hola")
print("Nico")
```
Sol:   
Hola  
Nico

```python{
print("Hola")
print("Lau")
```
Sol:   
Hola  
Lau
     
Podemos generar una línea en blanco, escribiendo una orden print() sin argumentos.

```python{
print("Hola")
print()
print("Nico")
```
Sol:  
Hola

Nico

```python{
print("Hola")
print()
print("Lau")
```
Sol:  
Hola

Lau

Si se quiere que Python **no añada** un salto de línea al final de un print(), se debe añadir al final el argumento end="":

```python{
print("Hola", end="")
print("Nico")
```
Sol: HolaNico

```python{
print("Hola", end="")
print("Lau")
```
Sol: HolaLau

En el ejemplo anterior, las dos cadenas se muestran pegadas. Si se quieren separar los argumentos en la salida, hay que incluir los espacios deseados (bien en la cadena, bien en el argumento end):

```python{
print("Hola", end=" ")
print("Nico y Lau")
```
Sol: Hola Nico y Lau


# Comentarios.  

1. Comienzan con el carácter numeral, # , y se extienden hasta el final visible de la línea.
```python{
# Esto es un comentario.
```
2. Es una línea de texto no ejecutable.  
3. Sirven para dejar pequeñas explicaciones sobre qué es lo que hace el programa.  
```python{
# Este programa muestra por pantalla el mensaje Hola Nico y Lau:
print("Hola Nico y Lau")
```  
Sol: Hola Nico y Lau

4. También, se pueden utilizar triples comillas dobles, """ , al principio y final de un comentario multilínea.
```python{
""" 
Esto es un comentarios de varias líneas.
Comentario de linea 1.
Comentario de linea 2.
"""
```
5. Al colocar el símbolo de numeral, #, delante de una línea de código, este no se ejecutará.  
```python{
# print("Hola mundo")
```


# Variables.  
Es un contenedor de información que dentro guardará un dato, se pueden crear muchas variables y que cada una tenga un dato distinto.
Python interpreta el tipo de dato que esta dentro de la variable.

Crear variables y asignarles un valor:
```python{
texto = "Hola"
texto2 = "Nico y Lau"
numero = 8
decimal = 8.8
```
```python
#También, podemos redefinir o reasignar valores:
#numero = 4
#decimal = 4.4
```
Mostrar el valor de las variables:
```python
print(texto)
print(texto2)
print(numero)
print(decimal)
```
Sol:  
Hola  
Nico y Lau  
8  
8.8  

## Concatenar.  
Es el proceso de combinar (unir) dos o más cadenas para crear una sola cadena nueva.   
Podemos concatenar cadenas en Python de las siguientes formas:  
- Usando el operador +
- Usando la función f{}
- Usando el método .format()

### Concatenar usando el operador +.  
```python{
# Definimos tres variables:
nombre = "Jairo"
apellido = "Quintas"
correo = "jairomqcode@gmail.com"
# Concatenar usando el operador +, imprimimos en pantalla:
print(nombre + " " + apellido + " - " + correo)
```
Sol:  
Jairo Quintas - jairomqcode@gmail.com

### Concatenar usando la función f{}.
```python{
print(f"{nombre}{apellido} - {correo}")
```
Sol:  
Jairo Quintas - jairomqcode@gmail.com

### Concatenar usando el método .format().
```python{
print("Hola me llamo {} {} y mi correo es: {}".format(nombre, apellido, correo))
```
Sol:  
Mi nombre es Jairo Quintas y mi correo es: jairomqcode@gmail.com


# Tipos de datos.
* **Dato tipo None**:  
Denota falta de valor.

```python{
# Definimos la variable:
nada = "None"
# Imprimimos dato:
print(nada)
# Imprimimos el tipo de dato:
print(type(nada))
```
Sol:  
None  
<class 'NoneType'>  

* **Dato tipo String**:  
Son un tipo de datos compuestos por **secuencias de caracteres** que representan texto. Estas cadenas de texto **son de tipo str** y se delimitan mediante el uso de comillas simples o dobles.  
```python{
# Definimos la variable:
cadena = "Hola Nico y Lau"
# Imprimimos dato:
print(cadena)
# Imprimimos el tipo de dato:
print(type(cadena))
```
Sol:  
Hola Nico y Lau  
<class 'str'>

* **Dato tipo entero**:  
Los números enteros son aquellos que **no tienen decimales**, tanto positivos como negativos (además del cero). En Python se pueden representar mediante el tipo int (de integer, entero) o el tipo long (largo). La única diferencia es que el tipo long permite almacenar números más grandes.

```python{
# Definimos la variable:
entero = 84
# Imprimimos dato:
print(entero)
# Imprimimos el tipo de dato:
print(type(entero))
```
Sol:  
84  
<class 'int'>  

* **Dato tipo flotante**:  
Los números reales son los que **tienen decimales**. En Python se expresan mediante el tipo float.  

```python{
# Definimos la variable:
flotante = 84
# Imprimimos dato:
print(flotante)
# Imprimimos el tipo de dato:
print(type(flotante))
```
Sol:  
8.4  
<class 'float'>

* Dato tipo Booleano:  
Sólo **puede tener dos valores: True (verdadero) y False (falso)**. Estos valores son especialmente importantes para las expresiones condicionales y los bucles.

```python{
# Definimos la variable:
booleano = True
# Imprimimos dato:
print(booleano)
# Imprimimos el tipo de dato:
print(type(booleano))
```
Sol:  
True  
<class 'bool'>

* **Dato tipo Lista**:  
La lista en Python **son variables que almacenan arrays**, internamente cada posición puede ser un tipo de datos distinto.

Las listas en Python son:  
- **heterogéneas**: pueden estar conformadas por elementos de distintos tipo, incluidos otras listas.
- **mutables**: sus elementos pueden modificarse.  

Una lista en Python **es una estructura de datos formada por una secuencia ordenada de objetos**.

```python{
# Definimos la variable:
lista = [38, 8, 4, 2023]
# Imprimimos dato:
print(lista)
# Imprimimos el tipo de dato:
print(type(lista))
```
Sol:  
[38, 8, 4, 2023]  
<class 'list'>

* Dato tipo listaString:
```python{
# Definimos la variable:
listaString = [18, "treinta", 38, "cuarenta"]
# Imprimimos dato:
print(listaString)
# Imprimimos el tipo de dato:
print(type(listaString))
```
Sol:  
[18, "treinta", 38, "cuarenta"]  
<class 'list'>

* **Dato tipo Tupla**:  
Las tuplas **son objetos de tipo secuencia, específicamente es un tipo de dato lista inmutable**. Esta **no puede modificarse** de ningún modo después de su creación.

```python{
# Definimos la variable:
tuplaNoCambia = ("programación", "en", "python")
# Imprimimos dato:
print(tuplaNoCambia)
# Imprimimos el tipo de dato:
print(type(tuplaNoCambia))
```
Sol:  
("programación", "en", "python")  
<class 'tuple'>

* **Dato tipo Diccionario**:  
Define una **relación uno a uno entre claves y valores**. Un objeto mapping mapea valores hashable a objetos arbitrariamente. Los objetos Mapeos son objetos mutable. El diccionario es el único tipo de mapeo estándar actual.

Los diccionarios **pueden ser creados colocando una lista separada por coma de pares «key:value» entre {}**.  

```python{
# Definimos la variable:
diccionario = {
    "nombre": "Jairo",
    "apellido": "Quintas"
}
# Imprimimos dato:
print(diccionario)
# Imprimimos el tipo de dato:
print(type(diccionario))
```
Sol:  
{'nombre': 'Jairo', 'apellido': 'Quintas'}  
<class 'dict'>

* Dato tipo Rango:
```python{
# Definimos la variable:
rango = range(9)
# Imprimimos dato:
print(rango)
# Imprimimos el tipo de dato:
print(type(rango))
```
Sol:  
range(0, 9)  
<class 'range'>  

Existen muchos otros tipos de datos en Python que se deben investigar.


# Convertir tipos de Datos.

En Python, los tipos de datos se utilizan para clasificar un tipo específico de datos, determinar los valores que puede asignar al tipo y las operaciones que puede realizar en el mismo. Cuando realice tareas de programación, a veces, deberá aplicar conversiones de valores entre tipos para manipular los valores de forma diferente. No se puede concatenar diferentes tipos de datos, debemos utilizar los distintos métodos que posee python para convertir tipos de datos, y poder igualar un tipo de dato con otro, de esta manera poder contatenarlos.  

```python{
# Definimos dos variables:
texto = "Hola nico y lau"
numero = 7
# Concatenar las dos variables:
print(texto + " " + numero)
```
Sol: TypeError: can only concatenate str (not "int") to str.

Para convertir una variable de tipo integer a string, utilizamos el método **str()** de la siguiente manera:

```python{
# Definimos dos variables:
texto = "Hola nico y lau"
# Utilizamos el método str, para convertir la variable de tipo integer a string:
numero1 = str(8)
numero2 = str(4)
# Concatenar las dos variables:
print(texto + " " + "tienen " + numero1 + " y " + numero2 + " años.")
```
Sol: Hola, nico y lau tienen 8 y 4 años.

En python la suma de un número entero y un número decimal (flotante), simpre dará como resultado un número con decimales. 

```python{
# Definimos dos variables:
numero3 = 4
numero4 = 7.99
print(numero3 + numero4)
```
Sol: 11.99  

Para que la suma de un número entero y otro flotante me de un valor entero, el tipo de variable flotante debo convertirlo a entero.

```python{
numero5 = 7
numero6 = int(7.99)
print(numero5 + numero6)
```
Sol: 14
