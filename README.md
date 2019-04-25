# Práctica02
Implementación en C++ para el algoritmo CYK.

## Archivos:
El directorio se compone de los siguientes archivos fuente:

* main.cpp : El archivo principal, contiene la función principal y es el encargado de procesar la entrada del programa.
* cykTable.h : Archivo fuente que define una 'cykTable', una clase tabla de parseo que permite ejecutar el algoritmo CYK, y 
obtener la representación en cadena de dicha tabla.
* cyk.h : Archivo fuente donde se implementa el algoritmo CYK, y la función que permite derivar por la izquierda una cadena,
si es que esta es aceptada por una gramática dada, sus funciones principales son:
  * cyk : la implementación del algoritmo CYK.
  * leftmost : la implementación de la derivación más por la izquierda.
  
Además de los archivos fuente, el directorio contiene los siguientes archivos y un subdirectorio:
* Ejercicio2.pdf : El ejercicio 2 sobre la gramática en FNC de la práctica.
* salida.txt : La salida del programa para las cadenas dadas en el ejercicio 3 de la práctica.
* ejemplos : un directorio con gramáticas.
  * ejemplo1.txt : gramática ejemplo del archivo pdf donde se define la práctica 2 (ejecutar dando la entrada: "ejemplos/ejemplo1.txt" al programa).
  * ejemplo2.txt : gramática vista durante la clase de teoría (ejecutar dando la entrada: "ejemplos/ejemplo2.txt" al programa).
  * ejercicio2.txt : la gramática del ejercicio 2 de la práctica (ejecutar dando la entrada: "ejemplos/ejercicio2.txt" al programa).

### Compilación:
Para compilar, ejecute el siguiente comando:
```
    g++ -std=c++11 -o cyk main.cpp
```
el cual, genera el binario "cyk", el cual contiene el programa compilado,
éste se ejecuta mediante:
```
    ./cyk
```

### Ejecución:
El programa preguntará primeramente por un nombre de archivo, en el directorio donde se ejecuta:
```
    Archivo con la gramática : [su archivo de gramática va aquí]
```
seguido de la cadena que se desea verificar:
```
    Cadena a evaluar: [su cadena va aquí]
```

### Autores:
Arteaga Vázquez Alan Ernesto

Figueroa Sandoval Gerardo Emiliano
