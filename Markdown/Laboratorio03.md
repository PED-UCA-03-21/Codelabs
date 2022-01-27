author: DouglasHdezT
summary: Ejercicios de Pilas y Colas en C++
id: laboratorio-03
URL: https://ped-uca-03-21.github.io/Codelabs/
tags: laboratorio,diy
categories: C++
environments: Web
status: Published
feedback link: https://github.com/PED-UCA-03-21/Codelabs/issues

# Pilas y Colas - C++

## Introducción
Duration: 0:10:00

### Dinámica

Para esta práctica se realizarán ejercicios guiados donde, parte del ejercicio será realizado por el instructor y el resto por el estudiante.

Todos los ejercicios están acompañados por un ejemplo de salida por consola, con el fin de facilitar y aclarar el funcionamiento de cada programa.

### ¿Qué aprenderás?

Durante la realización de este laboratorio se reforzarán temas relacionados con:

- Listas dinámicas
- Listas con enlace simple
- Pilas
- Colas

### Requisitos

- Visual Studio Code / Cualquier editor de texto plano
- Compilador de c++ (g++ / MinGW)

<aside class="positive">
  Recuerda que cualquier duda puedes realizarla a través de los medios oficiales, la plataforma o el correo electrónico.
</aside>

## Ejercicios a realizar
Duration: 1:20:00

A continuación se listan los ejercicios a realizar durante la sesipon de laboratorio.

Una compañia de seguridad informática le ha solicitado que ponga a prueba su nuevo software de protección a la información, el cual consiste en *n* capas de protección sobre el sistema principal, una sobre la otra. Usted ha asegurado encontrar una vulnerabilidad en el sistema, y puede pasar sobre cada capa (1 por 1) en un tiempo *t* determinado a través de la metodología *bruteforce*. 

Cuando se pone a prueba el sistema, logras identificar que, luego de vulnerar la primera capa del sistema, cada 10 segundos se añade una nueva capa al inicio que se tarda entre 1 y 5 segundos en resolver y retomar el trabajo anterior.

Cree un programa que simule este escenerio donde, se posea una estructura que represente cada capa (id, tiempo de vida, etc), una pila o *stack* que represente la disposición del sistema de protección a la información, y una cola o *queue* donde se almacenen las capas vulneradas en el orden en las que se resuelvan. 

<aside class="negative">
  - Utiliza la función sleep de la librería stdlib.h (Windows.h para windows) para simular el contador del programa.
  - Ingresa de forma dinámica los valores iniciales de las primeras capas.
  - Al final de la ejecucuión muestra la lista de todas las capas en el orden en las que fueron vulneradas
</aside>

## Soluciones

Las soluciones propuestas de los ejercicios se encuentran en el siguiente enlace: [Repositorio](https://github.com/PED-UCA-03-21/Laboratorio-03)

<aside class="positive">
  Recuerda realizar los ejercicios por tu cuenta. Es la forma mas efectiva de aprender.
</aside>