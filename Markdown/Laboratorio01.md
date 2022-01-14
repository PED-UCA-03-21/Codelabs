author: DouglasHdezT
summary: Ejercicios de repaso en C++
id: laboratorio-01
tags: laboratorio,diy
categories: C++
environments: Web
status: Published
feedback link: https://github.com/PED-UCA-03-21/Codelabs/issues

# Repaso de contenidos en C++

## Introducción
Duration: 0:15:00

### Dinámica

Para esta práctica se realizarán ejercicios guiados donde, parte del ejercicio será realizado por el instructor y el resto por el estudiante.

Todos los ejercicios están acompañados por un ejemplo de salida por consola, con el fin de facilitar y aclarar el funcionamiento de cada programa.

### ¿Qué aprenderás?

Durante la realización de este laboratorio se reforzarán temas relacionados con:

- Manejo de punteros
- Estructuras simples
- Recursión

### Requisitos

- Visual Studio Code / Cualquier editor de texto plano
- Compilador de c++ (g++ / MinGW)

<aside class="positive">
  Recuerda que cualquier duda puedes realizarla a través de los medios oficiales, la plataforma o el correo electrónico.
</aside>

## Ejercicios a realizar
Duration: 1:50:00

A continuación se listan los ejercicios a realizar durante la sesipon de laboratorio.

1. Cree un arreglo de n carácteres. Luego, haciendo uso de los conceptos de aritmética de punteros, recorra ese arreglo, y muestre por cada elemento la siguiente línea: **Elemento &lt;n&gt;: &lt;valor&gt;**. Realice el mismo procedimiento pero en reversa.

```console
NORMAL
Elemento 1: a
Elemento 2: b
Elemento 3: c
Elemento 4: d
Elemento 5: e

REVERSE
Elemento 5: e
Elemento 4: d
Elemento 3: c
Elemento 2: b
Elemento 1: a
```
   
2. Elabore una función de cuatro argumentos que calcule el cociente y el residuo de una división de números enteros. Los primeros dos argumentos recibirán el dividendo y el divisor, los otros dos argumentos corresponden a los dos valores calculados: cociente y residuo. Note que la función no debe devolver ningún valor. Imprima el cociente y el residuo en la función main.

```console
INGRESE EL VALOR DE A: 17
INGRESE EL VALOR DE B: 3

DIVISION
17 / 3
COCIENTE: 5
RESIDUO: 2
```

3. Cree una función que reciba dos números complejos y retorne la suma de ambos. Utilice una estructura para representar dichos números.

```console
INGRESE EL PRIMER COMPLEJO
REAL: 10
IMAGINARIA: 3 

INGRESE EL SEGUNDO COMPLEJO
REAL: 4
IMAGINARIA: 11

RESPUESTA: 14 + 14i
```

4. Cree un programa que permita almacenar 5 puntajes de un juego (nombre y puntuación). Luego muestre en pantalla el usuario con el mejor puntaje.

```console
INGRESE LOS DATOS DE LOS JUGADORES
JUGADOR 1
USERNAME: Douglas 
PUNTOS: 50

JUGADOR 2
USERNAME: Alejandra 
PUNTOS: 75

JUGADOR 3
USERNAME: Diego 
PUNTOS: 25

EL MEJOR JUGADOR ES: Alejandra - 75
```

5. Cree una estructura que represente un punto en un plano (Sólo “x” y “y” positivos), y otra que represente un rectángulo en ese plano (reutilice la estructura anterior para las esquinas). Cree dos funciones, una que calcule el perímetro y la otra el área de un rectángulo dado.

6. Cree una función que determine si un punto se encuentra dentro de un rectángulo. Reutilice las estructuras de punto y rectángulo del ejercicio anterior.

7. A partir del ejercicio anterior, crea una función que determine si un rectángulo se encuentra inscrito dentro de otro.


<aside class="negative">
Esta salida por consola es tanto del ejercicio 5, 6 y 7, ya que comparten la misma estructura y se reutilizan valores.
</aside>

```console
RECTANGULO 1 -> p1: 10, 10 p2: 1 ,1

PERIMETRO: 36
AREA: 81

PUNTO 1 -> 5 ,4
ESTA DENTRO DEL RECTANGULO 1

PUNTO 2 -> 15 ,1
ESTA AFUERA DEL RECTANGULO 1

RECTANGULO 2 -> p1: 3, 3 p2: 4 ,10

ESTA CONTENIDO EN EL RECTANGULO 1
```

1. Realice una función que, de forma recursiva, determine si una palabra es palíndroma o no.

```console
PALABRA 1: OREJERO - ES PALINDROMA
PALABRA 2: AGUA - NO ES PALINDROMA
PALABRA 3: SOLLOS - ES PALINDROMA
PALABRA 4: SOMETEMOS - ES PALINDROMA
PALABRA 5: ESTABLO - NO ES PALINDROMA
```
   
9.  Realice una función que, de forma recursiva, retorna el n-ésimo valor de la serie de fibonacci.

```console
VALOR DE N: 4
FIBONACCI: 3
```

10.  Realice una función que, de forma recursiva, retorne el producto de dos enteros positivos (incluyendo el 0). Recordar que la multiplicación se puede expresar como una suma abreviada.

```console
4x9 = 36
```

## Soluciones

Las soluciones propuestas de los ejercicios se encuentran en el siguiente enlace: [Repositorio](https://github.com/PED-UCA-03-21/Laboratorio-01)

<aside class="positive">
  Recuerda realizar los ejercicios por tu cuenta. Es la forma mas efectiva de aprender.
</aside>