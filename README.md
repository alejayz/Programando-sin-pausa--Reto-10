# Programando-sin-pausa--Reto-10
# Hiii :grin:

Para este repo tenemos como reto:

**1.** Desarrollar un algoritmo que calcule el promedio de un arreglo de reales.

```python
def Reales(a:float, b:float, c:float, d:float)-> float:  #se indican los elementos de la lista
    lista=[a, b, c, d]
    suma = 0  #inicia la suma en cero
    for i in lista:
        suma += i #suma todos los elementos de la lista
    return suma / len(lista) # divide la suma entre el total de elememtos para hallar el promedio

if __name__ == "__main__":
    a = float(input("ingresar un número real: "))
    b = float(input("ingresar un número real: "))
    c = float(input("ingresar un número real: "))
    d = float(input("ingresar un número real: "))
    PromArreglo = Reales(a,b,c,d) # se evalúa la función en los valores ingresados
    print("el promedio de " + str(a) + ', ' + str(b) + ', ' + str(c) +', ' + str(d) + " es: " + str(PromArreglo))
```


