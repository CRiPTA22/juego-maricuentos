# Historia de usuario


## Pagina 1

Juego Practica de Lectura

Historia de usuario

HECHO POR:

Igor Galvis

Mario Reyes

Juan Vargas

Electiva 1

Universidad Antonio Nariño

Bogotá D.C

2026

## Pagina 2

1. INTRODUCCIÓN 3
2. OBJETIVOS 3
2.1. Objetivo general 3
2.2. Objetivos específicos 3
3. DESCRIPCIÓN DEL PROYECTO 3
Jugador 3
HU-02 – Acceder a los ajustes 4
HU-03 – Salir del juego 4
HU-04– Pausar el juego 4
HU-05 – Interactuar con el texto 4
6. RESUMEN DE FUNCIONALIDADES 5
7. CONCLUSIONES 5

## Pagina 3

1. INTRODUCCIÓN
Este documento detalla las historias de usuario para el proyecto del desarrollo de un
videojuego móvil que ayude al desarrollo de la comprensión lectora de los niños
interactivamente. El objetivo principal es ver y documentar las necesidades y funcionalidades
clave desde la perspectiva de los diferentes usuarios del sistema.
Las historias de usuario aquí presentadas sintetizan los requerimientos funcionales esenciales,
abarcando el poder iniciar el juego y elegir entre las distintas historias (Para el desarrollo de
esta entrega se trabajará con una historia), acceder a los ajustes y salir del juego. Este
documento servirá como hoja de ruta técnica para las fases de análisis, diseño y validación
del sistema, garantizando que el equipo mantenga una visión clara de los objetivos.

2. OBJETIVOS

2.1. Objetivo general
Definir las historias de usuario necesarias para el desarrollo de un videojuego móvil que
ayude al desarrollo de la comprensión lectora de los niños interactivamente para manejar de
manera organizada el uso del videojuego.

2.2. Objetivos específicos
● Identificar los perfiles de los jugadores.
● Definir las funcionalidades críticas para cada perfil.
● Describir los requerimientos del sistema desde el punto de vista del usuario.
● Establecer criterios de aceptación claros para cada historia de usuario.
● Priorizar las funcionalidades para optimizar el proceso de desarrollo.
● Proporcionar una base sólida para el diseño y construcción del videojuego.

3. DESCRIPCIÓN DEL PROYECTO
El proyecto se centra en el desarrollo de un videojuego que permita a los usuarios
(principalmente niños) familiarizarse más fácilmente con la lectura mediante cuentos cortos
con los que pueden interactuar para ir formando la historia mientras leen.

4. ACTORES DEL SISTEMA

Jugador
El jugador podrá navegar entre el menú de inicio, dónde podrá elegir entre iniciar el juego,
elegir la historia deseada y jugarlo, acceder a los ajustes o salir del juego.

5. HISTORIAS DE USUARIO
HU-01 – Menú de inicio
Actor: Jugador

## Pagina 4

Historia: Como usuario del sistema, quiero poder elegir entre iniciar el juego y elegir entre las
historias, acceder a los ajustes o salir.
Prioridad: Alta.
Criterios de aceptación:
- Visualizar y acceder al inicio del juego.
- Visualizar y acceder a los ajustes del juego.
- Visualizar y acceder a una opción para salir.
-

HU-02 – Acceder a los ajustes
Actor: Jugador
Historia: Como jugador quiero acceder a los ajustes para que el juego se adapte a mis
preferencias.
Prioridad: Media.
Criterios de aceptación:
- Subir y bajar el sonido de la música.
- Subir y bajar el sonido de los efectos de sonido.

HU-03 – Salir del juego
Actor: Jugador
Historia: Como jugador deseo tener una opción para salir fácilmente del juego.
Prioridad: Alta.
Criterios de aceptación:
- Opción para salir del juego.

HU-04– Pausar el juego
Actor: Jugador
Historia: Como jugador deseo una opción para pausar el juego.
Prioridad: Media.
Criterios de aceptación:
- Opción para pausar el juego.

HU-05 – Interactuar con el texto
Actor: Jugador
Historia: Como usuario quiero poder interactuar con el texto y entenderlo correctamente.
Prioridad: Alta.
Criterios de aceptación:
- Texto legible.
- Interacción con el texto.

## Pagina 5

6. RESUMEN DE FUNCIONALIDADES
De acuerdo con las historias de usuario definidas, el sistema deberá dejar hacer
principalmente:

- Menú de inicio
- Elección de la historia
- Acceder a los ajustes
- Salir del juego
- Interactuar con el texto

Estas funcionalidades nos dejarán llevar un control organizado de las funciones que se desean
implementar en el juego.

7. CONCLUSIONES
Las historias de usuario nos dejan identificar de manera clara las necesidades de los
jugadores, para así establecer las funcionalidades que deberá tener el juego.
A partir de las historias definidas se pueden ver las principales actividades del juego, cómo
funcionará y cuales son las expectativas de este.
La definición de criterios de aceptación permite establecer las condiciones que debe cumplir
cada funcionalidad para considerarse correctamente implementada. Además, la priorización
permite al equipo ver cuáles funcionalidades deben ser desarrolladas primero.
En conclusión, este documento sirve como una base para las siguientes etapas del proyecto de
software, facilitando la planificación, el desarrollo y la posterior validación del videojuego.

## Requisitos detallados de las funcionalidades

Los criterios siguientes describen el comportamiento esperado; no significan que la funcionalidad ya este implementada. Segun la retroalimentacion recibida, estas funciones estan pendientes de implementacion o validacion.

### HU-01 - Menu de inicio
**Historia:** Como jugador, quiero encontrar las opciones principales en una pantalla inicial para iniciar una historia, ajustar preferencias o salir.

**Criterios de aceptacion:**
- Al abrir la aplicacion se muestra el menu de inicio.
- El menu presenta opciones identificables para iniciar el juego, abrir ajustes y salir.
- Iniciar el juego abre la historia disponible en esta entrega; si hay mas de una historia, permite elegirla antes de comenzar.
- Cada opcion abre la pantalla correspondiente y no deja botones sin respuesta.

### HU-02 - Ajustes de audio y controles
**Historia:** Como jugador, quiero ajustar el sonido y los controles para adaptar el juego a mis preferencias.

**Criterios de aceptacion:**
- Permite subir, bajar y silenciar el volumen de la musica y de los efectos de sonido por separado.
- Los cambios de volumen se aplican inmediatamente y se reflejan en los controles de la interfaz.
- Permite consultar y configurar los controles disponibles; ofrece una opcion para restaurar los valores predeterminados.
- Las preferencias se conservan al cerrar y volver a abrir el juego.
- Los ajustes son accesibles desde el menu de inicio y, cuando corresponda, desde la pausa.

### HU-03 - Salir del juego
**Historia:** Como jugador, quiero salir desde una opcion visible para cerrar la aplicacion de forma clara.

**Criterios de aceptacion:**
- La opcion Salir esta disponible desde el menu de inicio.
- Antes de cerrar, se muestra una confirmacion con opciones para continuar jugando o salir.
- Cancelar la confirmacion vuelve al menu sin perder el estado de la partida.

### HU-04 - Pausar y reanudar
**Historia:** Como jugador, quiero pausar y reanudar la partida para continuar leyendo cuando este listo.

**Criterios de aceptacion:**
- Durante la historia hay una opcion visible para pausar y otra para reanudar.
- Al pausar se detienen el avance de la historia y las interacciones de juego; la pantalla de pausa ofrece reanudar y abrir ajustes.
- Al reanudar se conserva la pagina o fragmento y las elecciones realizadas antes de la pausa.

### HU-05 - Interactuar con el texto
**Historia:** Como jugador, quiero leer texto legible y elegir opciones para participar en el desarrollo de la historia.

**Criterios de aceptacion:**
- El texto se presenta con tamano, contraste y distribucion que permitan leerlo en la pantalla del dispositivo.
- Las opciones de interaccion se muestran claramente cuando el relato requiere una eleccion.
- Al seleccionar una opcion, la historia avanza por la ruta correspondiente y muestra el resultado de la eleccion.
- La interfaz indica cuando no hay mas texto o decisiones disponibles en el fragmento actual.

## Estado de las observaciones de revision

- [x] La documentacion esta en Markdown y los PDF originales ya no estan en la carpeta docs del repositorio.
- [ ] Menu, ajustes, salida, pausa e interaccion con el texto: pendientes de implementacion o pruebas, de acuerdo con la revision recibida.
- [ ] Compilacion automatica: la revision reporta que el proyecto no compila; no se considera resuelta hasta obtener una ejecucion exitosa del flujo de Unity para Android.
- [x] APK publicado en Releases, segun la revision: [versiones del proyecto](https://github.com/CRiPTA22/juego-maricuentos/releases).
