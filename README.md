# Reto_10_viva_pdc

## Punto 1

Desarrollar un algoritmo que calcule el promedio de un arreglo de reales

```
a= float
nums = []
for i in range(1, n + 1):
    nums.append(int(input("Porfavor ingrese un numero cualquiera: ")))
total = sum(nums)
promedio = total / n
print("El prmedio es ", str(promedio))

```

## Punto 2

Desarrollar un algoritmo que calcule el producto punto de dos arreglos de números enteros (reales) de igual tamaño.

```

num1 = int(input("Ingresa tu primer numero: "))
num2 = int(input("Ingresa tu segundo número: "))
producto = 1
for i in range(len(num1)):
    for j in range(len(num2)):
        producto *= num1[i] * num2[j]

```

## Punto 3

Hacer un algoritmo que deje al final de un arreglo de números todos los ceros que aparezcan en dicho arreglo

Supongamos que tenemos un arreglo de: [1,0,1,0,3,0,4,0]

Si ejecutamos dicho codigo nos quedaria [1,1,3,4]. Un algortimo "general" que pueda jugar dicho rol seria:
```

num = len(arreglo)
for i in range(num):
    if nums[i] == 0:
        nums.remove(i)

```

## Punto 4

Revisar que son los algoritmos de sorting, entender bubble-sort 

Los algortimos sorting en Python son algunos algoritmos de ordenación muy comunes. Podemos ver los algoritmos de:
- Selección
- Inserción
- Selección en intercambio
- Selección en búsqueda
- Selección en búsqueda inversa
- Selección en búsqueda binaria

Y se usan principalmente para clasificar cualquier elemeno de una coleccion en forma ordenada. Un ejemplo seria utilizar el algoritmo de incesrion, ya que este tiene la funcionalidad de ordenar una coleccion de números desordenado. Y asi frente a cualquier situación que se requiera

Y el algorito bubble sort o algoritmo de burbuja es un algoritmo que recibe una colección de elementos y la ordena siguiendo el principio "compara y intercambia". El algoritmo funciona ordenando una colección paso a paso, intercambiando los elementos según sea necesario.

Un ejemplo puede ser que se tiene una lista con estos números: {5, 2, 8, 1, 4, 3, 6, 7}. El algoritmo de burbuja trabaja de la siguiente manera: primero, compara el primer elemento de la lista con el segundo. Si el primero es mayor que el segundo, intercambia ambos elementos. Luego, compara el tercer elemento con el cuarto. Todo esto para que cada uno de estos intercambios tenga un propósito: mover los elementos grandes hacia el final de la lista. En cada paso, la función de ordenación recorre la lista, ordenándola paso a paso. Los elementos más grandes van saliendo a la parte final de la lista. Y eso hace que los elementos más pequeños siempre estén en la parte más delantera de la lista.
