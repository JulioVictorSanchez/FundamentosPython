# Entrada de datos 📝
Hasta este punto lo que haciamos solo era mostrar texto por consola. Pero tambien se pueden ingresar nuestros propios datos de manera manual al script. En esta sección veremos la entrada 
de datos por teclado y como utilizarla.

## Función Input()
En Python tenemos la función _input_, que nos permite obtener la entrada de datos por parte del usuario desde la consola. A continuación se presenta un ejemplo de como emplear esta función.

```python
nombre = input("Por favor, ingrese su nombre: ")
print(nombre)
```
En este ejemplo, el usuario puede ingresar su nombre y se guarda en la variable llamada _nombre_. Posteriormente, dentro de la función _print_ se llama a la variable para imprimirla en consola.

```python
numeroUno = input("Ingrese el primer numero: ")
numeroDos = input("Ingrese el segundo numero: ")

suma = numeroUno + numeroDos

print("Resultado: ", suma)
```
El ejemplo presentado anteriormente es un poco engañoso, pareciera que se están tomando dos números en la entrada e imprimiendo la suma. El problema radica en que la entrada de la función _input_ siempre devuelve una cadena. Entonces, cuando se ingresa el valor _10_, el valor de la variable es _"10"_ es decir, una cadena.

Entonces ¿Qué sucede cuando agregamos dos cadenas? Simplemente concatenamos uno al otro. Esto significa que la suma de _"15"_ y _"26"_ seria _"1526"_. Si queremos realizar una suma matemática lo que debemos de hacer es un _cast_ o conversión de tipos a nuestras variables. A continuación se presenta un ejemplo de esto, para ello se presentan dos formas de realizarlo.

```python
#Forma 1
numeroUno = input("Ingrese el primer numero: ")
numeroDos = input("Ingrese el segundo numero: ")

numeroUno = int(numeroUno) #Aquí se realiza la conversión de tipos, se le indica con la palabra clave "int" que la cadena se convertira a un entero
numeroDos = int(numeroDos)

suma = numeroUno + numeroDos

print("Resultado: ", suma)

#Forma 2
numeroUno = int(input("Ingrese el primer numero: ")) #La conversión de tipos se realiza de forma simultanea junto con la función "input"
numeroDos = int(input("Ingrese el segundo numero: "))

suma = numeroUno + numeroDos

print("Resultado: ", suma)
```
