# Condicionales ✅❎
Esta sección trata sobre un concepto que hara que nuestros códigos sean más interesantes. Hasta ahora el intérprete solo ejecutaba una instrucción tras otra, con las condiciones esto cambia.

## Condiciones IF, ELIF, ELSE
Estas construcciones permiten condicionar la ejecución de uno o varios bloques de sentencias al cumplimiento de una o varias condiciones. Estas condicionales permiten que un 
programa ejecute unas instrucciones cuando se cumplan una condición. A continuación se presenta un ejemplo de como se puede implementar la condicional IF (Si).

```python
numero = int(input("Ingrese un número: "))

if numero >10:
    print("El número es mayor que 10")
elif numero < 10:
    print("El número es menor que 10")
else:
    print("El número es 10")
```
