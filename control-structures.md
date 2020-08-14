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

