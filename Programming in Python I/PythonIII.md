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

En Python existen ciertos tipos de operadores, llamados operadores de comparación, que se utilizan para trabajar con las condicionales if - else. Estos operadores los podemos observar a continuación:

| Operadores de Comparación |
| -------- | ----------- |
| Operador | Descripción |
