author: DouglasHdezT
summary: Ejercicios de Listas con enlace simple en C++ - II
id: laboratorio-03
URL: https://ped-uca-03-21.github.io/Codelabs/
tags: laboratorio,diy
categories: C++
environments: Web
status: Published
feedback link: https://github.com/PED-UCA-03-21/Codelabs/issues

# Listas lineales simples - C++ - II

## Introducción
Duration: 0:10:00

### Dinámica

Para esta práctica se realizarán ejercicios guiados donde, parte del ejercicio será realizado por el instructor y el resto por el estudiante.

Todos los ejercicios están acompañados por un ejemplo de salida por consola, con el fin de facilitar y aclarar el funcionamiento de cada programa.

### ¿Qué aprenderás?

Durante la realización de este laboratorio se reforzarán temas relacionados con:

- Listas dinámicas
- Listas con enlace simple

### Requisitos

- Visual Studio Code / Cualquier editor de texto plano
- Compilador de c++ (g++ / MinGW)

<aside class="positive">
  Recuerda que cualquier duda puedes realizarla a través de los medios oficiales, la plataforma o el correo electrónico.
</aside>

## Ejercicios a realizar
Duration: 1:20:00

A continuación se listan los ejercicios a realizar durante la sesión de laboratorio.

1. Cree la estructura (Estructura y clase) necesaria para manipular una lista con enlaces simples. Además, añada los siguientes métodos para la manipulación de las mismas:
   - Insertar un valor al principio
   - Insertar al final
   - *toString*

2. Cree una función que retorne un valor booleano que represente si la lista está vacía o no.  

3. Cree una función que busque un valor (pedido por el usuario) en la lista, y devuelva la posición en la que se encuentra la primera aparición en la lista.
   
4. Cree una función que elimine un nodo de la lista, a partir de un valor ingresado por el usuario.

5. Cree una variante de la clase principal de la lista, con la diferencia que tendrá un único método para insertar, y este ingresará nodos de forma que ningún valor dentro de la lista se repita. Si se inserta un valor repetido, la lista simplemente no se alterará.


## Tarea de laboratorio

Solucione el siguiente problema y envielo a través de la plataforma virtual del curso en el tiempo indicado:

Cree una variante de la clase principal de la lista, con la diferencia que tendrá un único método para insertar, y este ingresará los nodos de forma que, un nuevo valor se insertará tanto al incio como al final de la lista.

```console
Lista: 

Insertar: 3
Lista: 3

Insertar: 1
Lista: 1 -> 3 -> 1

Insertar: 5
Lista: 5 -> 1 -> 3 -> 1 -> 5

Insertar: 8
Lista: 8 -> 5 -> 1 -> 3 -> 1 -> 5 -> 8

Insertar: 0
Lista: 0 -> 8 -> 5 -> 1 -> 3 -> 1 -> 5 -> 8 -> 0
```

<aside class="negative">
  Recuerda implementar algún método para mostrar los elementos de la lista de forma ordenada.
</aside>

<aside class="positive">
  Puedes implementar y utlizar funciones vistas en clases, o en otras sesiones de laboratorio. E.G. getTail, getHead, toString, etc
</aside>

## Soluciones

Las soluciones propuestas de los ejercicios se encuentran en el siguiente enlace: [Repositorio](https://github.com/PED-UCA-03-21/Laboratorio-03)

<aside class="positive">
  Recuerda realizar los ejercicios por tu cuenta. Es la forma mas efectiva de aprender.
</aside>