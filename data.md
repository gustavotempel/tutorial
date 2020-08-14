# DATOS

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