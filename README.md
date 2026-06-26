# examen-Renata-Martinez

## Descripción del proyecto

¿Dónde está el perro? es un juego interactivo desarrollado en p5.js. El objetivo consiste en descubrir una imagen oculta del perro haciendo clic sobre la pantalla. Cada clic revela una parte de la imagen hasta completarla. Cuando la fotografía aparece completamente, el programa muestra un mensaje de felicitación y permite reiniciar el juego para volver a comenzar.

## Objetivo
el usuario tiene que participar activamente para encontrar el resultado 

## imagen usada

<img width="1179" height="786" alt="encuentra el perro" src="https://github.com/user-attachments/assets/3f56b4b7-d736-4bde-b406-a2d2b22107d7" />


## 1. Planificación

Primero se definió la idea del proyecto: crear un pequeño juego donde una imagen permaneciera oculta y fuera apareciendo poco a poco mediante la interacción del usuario.
Posteriormente se decidió dividir el programa en diferentes pantallas para hacer la experiencia más organizada.
## 2. Organización mediante estados

Se creó la variable

let estado = 0;

para controlar el flujo del programa.

Los estados quedaron definidos de la siguiente forma:

Estado 0

Menú principal.

Estado 1

Pantalla de preparación.

Estado 2
Juego.
Gracias a esta estructura el programa sabe qué debe mostrar en cada momento.
## 3. Carga de multimedia

Se utilizó la función

loadImage()

para cargar la fotografía del perro antes de iniciar el programa.

Esto asegura que la imagen esté completamente disponible cuando comienza el juego.

  ## 4. Diseño de la interfaz

En la función

setup()

se creó el lienzo y se definieron los colores principales del proyecto.

Se escogieron tonos verdes para el fondo y el texto con el fin de mantener una apariencia uniforme.

## 5. Creación de funciones

Para mantener el código organizado, cada pantalla fue construida mediante una función diferente.

dibujarMenu()
dibujarEspera()
dibujarJuegoRompecabezas()

Esto facilita la lectura y el mantenimiento del código.

## 6. Desarrollo del juego

La imagen fue dividida en cuatro cuadrantes utilizando la función

image()

Cada vez que el usuario hace clic, aumenta la variable

partesVisibles

y se muestra una nueva sección de la fotografía.

Cuando las cuatro partes están visibles aparece el mensaje

¡Encontrado!

 ## 7. Incorporación de interactividad

Toda la interacción ocurre mediante

mousePressed()

Cada clic realiza diferentes acciones dependiendo del estado actual del programa.

avanzar entre pantallas
revelar una nueva parte
reiniciar el juego
## 8. Uso de bucles

Se incorporaron dos ciclos

for

para dibujar una cuadrícula sobre el fondo del juego.

Estos bucles recorren horizontal y verticalmente el lienzo generando líneas de manera automática.

 ## 9. Uso de random()

Se utilizó la función

random()

para modificar ligeramente el color del fondo cada vez que aparece una nueva parte de la imagen.

Esto hace que la experiencia visual sea un poco diferente en cada clic.

## Diagrama de flujo

<img width="985" height="542" alt="Captura de pantalla 2026-06-26 000822" src="https://github.com/user-attachments/assets/e71ba414-ba76-4ada-8e15-a3c658bfeeb3" />


##links

https://editor.p5js.org/renata.martinez/full/WD-LdvqE8 

https://editor.p5js.org/renata.martinez/sketches/WD-LdvqE8
















