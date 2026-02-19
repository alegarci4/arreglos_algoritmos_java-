# Parte 1 – Ingeniería Inversa del archivo .jar

## Herramienta utilizada
Para realizar la ingeniería inversa usé la herramienta **JD-GUI**, la cual permite descompilar archivos `.class` contenidos dentro de un `.jar` y visualizar el código fuente en Java.

## Clases encontradas

El archivo contiene los siguientes paquetes y clases:

### Paquete: `umg.edu.gt.data_structure.array`

- `BubbleSort`
- `MergeSortDemo`
- `QuickSort`
- `SumArray`

### Paquete: `umg.edu.gt.data_structure.introduction`

- `App`

En total se pude observar 5 clases organizadas en 2 paquetes.

## Operaciones realizadas sobre los arreglos

Al ver el código decompilado observé las siguientes operaciones:

- Recorrido de arreglos mediante ciclos `for`
- Comparaciones entre elementos (`if`)
- División de arreglos en subarreglos
- Suma acumulativa de elementos


## Algoritmos de ordenamiento identificados
Bubble Sort, Quick Sort, Merge Sort