# Operadores ➕➗
Lo siguiente que se presenta son los operadores. Los operadores se utilizan para gestionar variables o valores para realizar operaciones sobre ellos. Hay diferentes tipos de  operadores y en esta sección se verán las diferencias y aplicaciones de estos.

## Operadores aritméticos
Los operadores más simple son los operadores aritméticos. Es muy probable que estos ya lo conozcas, pues son los más utilizados desde las matemáticas básicas. En la siguiente tabla
se presentan dichos operadores.

<div class="tg-wrap"><table><tbody><tr><td align="center" colspan="3"><b>Operadores aritméticos</b></td></tr><tr><td align="center"><b>Operador</b></td><td align="center"><b>Nombre</b></td><td align="center"><b>Descripción</b></td></tr><tr><td>+</td><td>Adición</td><td>Suma dos operandos.</td></tr><tr><td>-</td><td>Sustracción</td><td>Resta al operando de la izquierda el valor del operando de la derecha. Utilizado sobre un único operando, le cambia el signo.</td></tr><tr><td>*</td><td>Multiplicación</td><td>Producto/Multiplicación de dos operandos.</td></tr><tr><td>/</td><td>División</td><td>Divide el operando de la izquierda por el de la derecha (el resultado siempre es un float).</td></tr><tr><td>%</td><td>Modulo</td><td>Obtiene el resto de dividir el operando de la izquierda por el de la derecha.</td></tr><tr><td>**</td><td>Potencia</td><td>El resultado es el operando de la izquierda elevado a la potencia del operando de la derecha.</td></tr><tr><td>//</td><td>Cociente entero</td><td>Obtiene el cociente entero de dividir el operando de la izquierda por el de la derecha.</td></tr></tbody></table></div>

Veamos algunos ejemplos. 
```python
numeroUno = 12
numeroDos = 3

suma = numeroUno + numeroDos
resta = numeroUno - numeroDos
multiplicacion = numeroUno * numeroDos
division = numeroUno / numeroDos
modulo = numeroUno % numeroDos
potencia = numeroUno ** numeroDos
residuo = numeroUno // numeroDos

print(suma)
print(resta)
print(multiplicacion)
print(division)
print(modulo)
print(potencia)
print(residuo)
```

## Operadores de asignación
Otro tipo de operadores conocidos son los operadores de asignación. Como su nombre lo dice, estos operadores asignan valores a las variables. A continuación se presenta una tabla donde en la cual se muestran estos operadores utilizados en Python.

<div class="tg-wrap"><table><tbody><tr><td align="center" colspan="2"><b>Operadores de asignación</b></td></tr><tr><td align="center"><b>Operador</b></td><td align="center"><b>Descripción</b></td></tr><tr><td>=</td><td>Asigna un valor a una variable.</td></tr><tr><td>+=</td><td>Suma un valor a una variable.</td></tr><tr><td>-=</td><td>Resta un valor de una variable.</td></tr><tr><td>*=</td><td>Multiplica un valor de una variable.</td></tr><tr><td>/=</td><td>Divide la variable por un valor.</td></tr><tr><td>%=</td><td>Asigna el resto de una división.</td></tr><tr><td>**=</td><td>Asigna el resultado de una exponenciación.</td></tr><tr><td>//*</td><td>Asigna el resultado entero de una división.</td></tr></tbody></table></div>

Los operadores compuestos (+=, \*=, -=, etc.) realizan la operación que hay antes del signo igual, tomando como operandos la propia variable y el valor a la derecha del signo igual. A continuación se presenta un ejemplo de como utilizar estos operadores. 

```python
valorA = 3
valorB = 5

c = valorA + valorB
print ("Operador = | El valor de variable 'c' es: ", c)

#Su equivalencia seria c = c + 3
c += valorA
print ("Operador += | El valor de variable 'c' es: ", c)

#Su equivalencia seria c = c - 3
c -= valorA
print ("Operador -= | El valor de variable 'c' es: ", c)

#Su equivalencia seria c = c * 3
c *= valorA
print ("Operador *= | El valor de variable 'c' es: ", c)

#Su equivalencia seria c = c / 3
c /= valorA
print ("Operador /= | El valor de variable 'c' es: ", c)
```

## Operadores de comparación

