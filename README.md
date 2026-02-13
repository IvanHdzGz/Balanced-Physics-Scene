# Balanced-Physics-Scene
Proyecto desarrollado en Unity basado en mecánicas de físicas y masas, donde el jugador debe interactuar con el entorno para avanzar a través de distintos niveles.

## Descripción del Proyecto
Balanced Physics Scene es un mini-juego/puzzle de físicas en el que el jugador controla un personaje cuya misión es empujar una esfera hasta el final de cada nivel.
El progreso no depende solo de mover la esfera, sino de resolver problemas físicos utilizando objetos del escenario con distintas masas.
El jugador debe observar, experimentar y manipular el entorno para abrirse camino.

### La idea central del juego es:
Resolver puzzles mediante el equilibrio de masas y la interacción física entre objetos.

## Mecánicas Principales
- Movimiento del jugador
- Empuje de objetos físicos
- Sistema de masas y peso
- Interacciones basadas en Rigidbody
- Resolución de puzzles físicos

## Tipos de Desafíos / Niveles
El juego se divide en 3 partes donde en todo momento se hace uso de fisicas de empuje:

1: Empuje de estructuras
El jugador debe empujar paredes u objetos grandes para desbloquear rutas o atravesar puertas.
- Ejemplo: Mover un cubo/pared para despejar una entrada.

<img width="611" height="416" alt="image" src="https://github.com/user-attachments/assets/0801565e-469d-4247-90c7-d5124e6dfef9" />

2: Puentes equilibrados
Puentes o plataformas que reaccionan al peso de los objetos colocados en sus extremos.
El jugador debe equilibrar correctamente las masas para obtener un ángulo adecuado y poder cruzar.
- Ejemplo: Colocar objetos de distintas masas en un extremo para evitar perder el balance y angulo correcto para completar el reto.

<img width="533" height="554" alt="image" src="https://github.com/user-attachments/assets/a0f46302-276b-4436-a039-46571f6f3142" />

3: Laberintos
La esfera que el jugador transporta se convierte en el elemento principal del puzzle.
El reto consiste en manipularla dentro de un laberinto o entorno complejo hasta llegar a un punto objetivo.
- Ejemplo: Empujar la esfera hacia un aro al final del laberinto.

<img width="603" height="535" alt="image" src="https://github.com/user-attachments/assets/f352c823-4f39-4755-936d-69275e7cd17b" />

## Retos presentados
Algunos de los retos y limiitaciónes que se presentaron durante el desarrollo de este proyecto:
- Limitación de estructuras complejas, tanto como la existencia de las mismas como la limitación de algunas herramientas como ProBuilder en situaciones específicas, como subdivisiones en caras de cubos.
- Por lo anterior se tuvo que improvisar la implementación de una escalera con cubos, ya que la subida de esferas para aplicar peso al puente equilibrado se complicaba con los bordes pequeños de una escalera convencional.

## Tecnologías Utilizadas
- Motor: Unity
- Sistema de físicas: Unity Physics (Rigidbody / Colliders)
