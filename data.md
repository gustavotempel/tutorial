# TIPOS DE DATOS

Para comenzar, es importante definir qué son los **datos** desde el punto de vista de la programación.
Los datos son los nombres con los que se almacenan ciertos valores en la memoria y que pueden ser utilizados durante la ejecución de un programa. Para poder utilizarlos, hay que realizar ciertos procesos, por ejemplo, hay que declararlos, asignarles espacio de memoria, asignarles valores, llamarlos, etc. Estos procesos varían según el nivel de abstracción de cada lenguaje, ya que en algunos todos esos pasos se pueden resumir en uno solo.

## Clasificación

Los datos se pueden clasificar según varios criterios, pero por el momento vamos a empezar con unos pocos.
Un criterio de clasificación posible es si el dato es **Constante** o **Variable**.
Si el valor del dato puede cambiar durante la ejecución del programa, se llama **Variable**. Por otro lado, si el valor del dato no debe cambiar durante la ejecución del programa, se llama **Constante**.

Otra clasificación importante es acerca del tipo de valor que almacenan los datos.
Existen muchos tipos de datos y dependen mucho de los lenguajes, pero una buena clasificación podría ser la siguiente:

- **Valores únicos**
  - **Número**: Representa valores numéricos (1, 1.41, 2, 2.78, 3, 3.14, 4)
  - **Caracter**: Representa letras, números y símbolos ('a', 'b', 'c', '1', '2', '@', '*')
  - **Booleano**: Representa valores lógicos (verdadero/falso, true/false)
- **Valores múltiples**
  - **Texto**: Representa cadenas de caracteres ("El murciélago volaba en la oscuridad")
  - **Lista**: Representa una secuencia de entidades ordenadas posicionalmente ( \[38, "Argentina", 'M', true\] )
  - **Diccionario**: Representa una secuencia de entidades ordenadas por clave-valor ( {"edad": 38, "nacionalidad": "Argentina", "genero": 'M', "alta": true} )
- **Otros**
  - **Fecha**: Representa una fecha ("31/12/1999", "01/01/2000")

Los textos son considerados históricamente como cadenas de caracteres, por eso están clasificados como de valores múltiples, aunque en algunos lenguajes de más alto nivel podrían considerarse como de valores únicos.

Tipo | Java | Python | JavaScript
--- | --- | --- | ---
Numero | byte, short, int, long, float, double | int, float |
Caracter | char | - |
Booleano | boolean | bool |
Texto | String | str |
Lista | Array, ArrayList | tuple, list |
Diccionario | | dict |


# ESTRUCTURAS DE CONTROL

## Estructura Condicional
La estructura condicional es una de las más simples que podemos encontrar, pero a la vez, es muy potente y es una de las más usadas por su gran versatilidad.
En su forma más básica la estructura contiene dos partes principales: la **condición** y la **acción** que se ejecuta en caso de que la condición sea verdadera.
Se utiliza una sentencia con la forma **if** condición **then**, aunque esta sintaxis varía según el lenguaje. En el caso de que la condición no se cumpla, simplemente no se ejecuta la acción y el programa continúa normalmente.

Ejemplo VisualBasic:
```vb
If condition Then
  do_something
End If
```

Ejemplo Java:
```java
if (condition) {
  do_something;
}
```

Ejemplo Python:
```python
if condition:
  do_something
```

A esta estructura de control, además se le puede agregar otra acción para el caso en el que la condición sea falsa, es decir que no se cumpla. Para esta expresión, generalmente se utiliza la expresión **else**, la sintaxis varía según el lenguaje y en algunos su utilización es obligatoria. Una vez que el programa llega a una estructura **if then else**, no le queda otra alternativa que ejecutar una de las dos acciones. 

Ejemplo VisualBasic:
```vb
If condition Then
  do_something
Else
  do_something_else
End If
```

Ejemplo Java:
```java
if (condition) {
  do_something;
} else {
  do_something_else;
}
```

Ejemplo Python:
```python
if condition:
  do_something
else:
  do_something_else
```

Además de la expresión **else** se puede agregar la expresión del tipo **else if** con la que se podría adicionar una o más condiciones y acciones que se ejecutarán en el caso de que no se cumplan las condiciones anteriores. 

Ejemplo VisualBasic:
```vb
If condition Then
  do_something
Else if other_condition Then
  do_anything
End If
```

Java example:
```java
if (condition) {
  do_something;
} else if (other_condition) {
  do_anything;
}
```

Python example:
```python
if condition:
  do_something
elif other_condition:
  do_anything
```


## Bucle

## Bucle condicional

