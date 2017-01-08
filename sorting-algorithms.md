  Sorting algorithms (both comparison sorting and non-comparison sorting)
Que es un Algoritmo de clasifiación?

Es un algoritmo que pone elementos de una lista (o matriz) en cierto orden especifico en los cuales los mas usados son los numéricos y los lexicograficos. la clasificacion eficiente es clave para optimizar el uso de otros algoritmos que requieren que los datos de entrada estén en listas ordenadas.

Cuales son los Algoritmos no clasifiacados?

Bucket Sort.

Las condiciones especiales requeridas para el tipo de cubo son:
- Los valores a ordenar se distribuyen uniformemente en un rango de min a max.
- Es posible dividir el rango en N partes iguales, cada una de tamaño k.
- Dado un valor, es posible decir en qué parte del rango está.
- Tenga en cuenta que las condiciones 2 y 3 se mantienen para valores numéricos, pero no necesariamente para otros tipos de valores (como cadenas).

Counting Sort.

Las condiciones especiales requeridas para el conteo son:
Los valores a ordenar son números enteros en un rango de min a max. Llamaremos el número de valores en el rango (max-min + 1) k.
N> = k.
Hay dos versiones de ordenación de conteo, dependiendo de si el objetivo es simplemente ordenar N enteros o ordenar N enteros cada uno de los cuales tiene alguna información asociada que se llevará consigo.


Radix Sort.
Las condiciones especiales requeridas para el tipo de radix son:
Los valores a ordenar son secuencias de longitud k.
Cada elemento de las secuencias es en sí un valor en algún rango min a max. (Por ejemplo, los valores a ordenar podrían ser cadenas - secuencias de caracteres en el rango 'a' a 'z', o podrían ser enteros - secuencias de dígitos en el rango de 0 a 9).
N> = máx-min + 1.
