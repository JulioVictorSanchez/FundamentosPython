# Tipos de datos 💯🅰✔
En programación, una variable es un **espacio reservado en la memoria de nuestro ordenador para almacenar un dato** que puede ser usado o modificado N veces. Como punto muy importante, las variables deben tener un nombre asociado al dato que almacena. Por ejemplo, podemos tener una variable llamada _Nombre_ para almacenar el nombre (dato) de una persona y otra variable llamada _Edad_ que almacenara la edad de una persona.

⚠ **NOTA:** Como buena práctica de programación se recomienda crear variables con nombres intuitivos referentes al dato que almacenan. ⚠


## Datos numéricos
Es muy probable que este tipo de dato ya lo conozcas debido a tus clases de matemáticas. Sin embargo, hay diferentes tipos de datos numéricos que puedes utilizar en la programación, los cuales se muestran en la siguiente tabla:

<div class="tg-wrap"><table><tbody><tr><td align="center" colspan="3"><b>Tipos de datos numéricos</b></td></tr><tr><td align="center"><b>Tipo de dato</b></td><td align="center"><b>Palabra clave</b></td><td align="center"><b>Descripción</b></td></tr><tr><td>Entero</td><td><i>int</i></td><td>Corresponde a número enteros, es decir, sin parte decimal.</td></tr><tr><td>Flotante</td><td><i>float</i></td><td>Corresponde con números reales con parte decimal.&nbsp;&nbsp;El separador decimal en Python es el punto (.)</td></tr><tr><td>Complejo</td><td><i>complex</i></td><td>Los números complejos tienen una parte real y otra imaginaria y cada una de ellas se representa como un float.</td></tr></tbody></table></div>

Como se puede observar es muy simple. Un entero es solo un número entero regular, con el que podemos hacer cálculo básico. Un número flotante extiende el rango de los enteros y permite posiciones decimales. Y un número complejo es aquel que tiene un componente real y uno imaginario.

⚠ **NOTA:** Los números complejos no suelen utilizarse a menudo en la programación. Por el momento no se utilizarán. ⚠


## Cadena de caracteres o Strings
Una cadena es una secuencia básica de caracteres, es decir, un texto. El texto que mandamos a imprimir en la [sección pasada](https://github.com/JulioVictorSanchez/FundamentosPython/blob/main/IntroPython.md) era una cadena. Las cadenas siempre deben de ir dentro de comillas, ya sean **dobles ("") o simples ('')**, de lo contrario el intérprete no lo tomara como un texto. En Python la palabra clave para una cadena es **str**.

## Valores booleanos 
Los booleanos son el tipo de dato más simple en Python. Estos solo puede almacenar dos valores, _True_ o _False_ (Verdadero o Falso). Es un tipo de dato binario y se utilizan mucho cuando se trabaja con condiciones o ciclos. La palabra clave de este tipo de dato es **bool**.

## Secuencias
Una secuencia almacena datos y permite el acceso a una parte determinada de su información utilizando índices (estas se verán más a detalle en otra sección). Los tipos de secuencia se muestran a continuación:

<div class="tg-wrap"><table><tbody><tr><td align="center" colspan="3"><b>Tipos de secuencias</b></td></tr><tr><td align="center"><b>Tipo de dato</b></td><td align="center"><b>Palabra clave</b></td><td align="center"><b>Descripción</b></td></tr><tr><td>Listas</td><td><i>list</i></td><td>Una lista es una estructura de datos que contiene una colección o secuencia de datos. Los datos o elementos de una lista deben ir separados con una coma y todo el conjunto entre corchetes.</td></tr><tr><td>Tuplas</td><td><i>tuple</i></td><td>Permite tener agrupados un conjunto inmutable de elementos, es decir, en una tupla no es posible agregar ni eliminar elementos. Las tuplas se declaran separando los elementos por comas y éstos, opcionalmente, pueden ir entre paréntesis.</td></tr><tr><td>Diccionarios</td><td><i>dict</i></td><td>Son objetos que contienen una lista de parejas de elementos. De cada pareja un elemento es la clave, que no puede repetirse, y, el otro, un valor asociado. La clave que se utiliza para acceder al valor tiene que ser un dato inmutable como una cadena, mientras que el valor puede ser un número, una cadena, un valor lógico (True/False), una lista o una tupla.</td></tr></tbody></table></div>

# Creación de variables ⌨📑
Crear variables en Python es muy sencillo. Simplemente elegimos un nombre y le asignamos un valor. A continuación se muestra un ejemplo, se crearon dos variables: la primera de nombre _miNumero_ que almacena un dato entero de valor _10_ y la segunda de nombre _miTexto_ que almacena un dato tipo cadena con valor _"Hola Mundo"_.

```python
miNumero = 10
miTexto = "Hola Mundo"
```
⚠ **NOTA:** Se puede elegir el nombre que desee para nombrar sus variables. Sin embargo, no puede utilizar las palabras reservadas por el lenguaje (Por ejemplo. _int_, _dict_, etc.) Otro punto a destacar es que no se permite que el nombre de una variable comience con un **número** o **carácter especial** que no sea el **guion bajo (_)** ⚠





