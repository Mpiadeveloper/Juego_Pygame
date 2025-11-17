Juego de Aviones – Pygame (Consola / Ventana)

Un juego clásico de disparos desarrollado con Python y Pygame, donde el jugador controla un avión que debe esquivar enemigos y derribarlos antes de ser alcanzado.

 - Descripción del Juego

El juego consiste en controlar un avión que se mueve por la pantalla mientras aparecen enemigos desde distintos puntos.
El objetivo es derribar la mayor cantidad posible de enemigos sin ser golpeado.

El jugador pierde si es impactado por un enemigo.

Los enemigos se mueven de forma continua.

Se lleva un conteo del puntaje basado en enemigos eliminados.

Es un proyecto ideal para practicar:

Lógica de videojuegos 2D

Colisiones

Manejo de teclado

Carga de imágenes, sonidos y animaciones

Organización de módulos en Python

- Controles
Acción	Tecla
Mover hacia arriba --> Flecha arriba
Mover hacia abajo	--> Flecha abajo
Mover hacia la izquierda --> Flecha izquierda
Mover hacia la derecha	--> Flecha derecha
Disparar -->	Barra espaciadora


- Características Principales

Movimiento fluido del jugador

Generación dinámica de enemigos

Disparos y colisiones precisas

Sonidos y efectos visuales

Pantalla de Game Over

Sistema de puntaje

Proyecto modular organizado en carpetas:

/funciones

/configuraciones

Assets (imágenes, sonidos, etc.)



Requisitos

Python 3.10 o superior

Pygame

Instalación de Pygame:   (pip install pygame)

 ¿Cómo Ejecutarlo?

Cloná el repositorio:

git clone https://github.com/Mpiadeveloper/Juego_Pygame.git


Ingresá al directorio:

cd Juego_Pygame


Ejecutá el juego:

python main.py

Estructura del Proyecto
├── main.py
├── configuraciones/
│   ├── cargar_imagenes.py
│   ├── reproducir_sonidos.py
│   ├── configurar_pantalla.py
│   └── ...
├── funciones/
│   ├── mover_jugador.py
│   ├── generar_enemigos.py
│   ├── detectar_colisiones.py
│   └── ...
├── assets/
│   ├── imagenes/
│   └── sonidos/

 Objetivo del Proyecto

Este juego fue desarrollado como práctica de:

Programación orientada a objetos

Diseño de juegos 2D

Modularización en Python

Uso profesional de Pygame
