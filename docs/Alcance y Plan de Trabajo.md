# Alcance y Plan de Trabajo


## Pagina 1

Juego Practica de Lectura

Alcance y Plan de Trabajo

HECHO POR:

Igor Galvis

Mario Reyes

Juan Vargas

Electiva 1

Universidad Antonio Nariño

Bogotá D.C

2026

## Pagina 2

Introducción 2
1. Alcance del Software 2
a. Metas y Objetivos 2
b. Requisitos del Sistema 2
c. Entregables 3
d. Exclusiones 3
2. Plan de Trabajo 3
a. Desglose de Trabajo (Product Backlog / EDT) 3
b. Cronograma de Actividades 4
c. Asignación de Responsables y Recursos 4
d. Monitoreo y Control 5

Introducción

Este documento detalla dos procesos principales, uno es el alcance esperado y otro es el plan
de trabajo. Este proyecto lo desarrollaremos a lo largo de este semestre, expondremos metas
junto con objetivos, requisitos, entregables, sin olvidar las exclusiones y por supuesto las
restricciones basándonos en supuestos, todo esto hará parte del alcance. Así mismo
tendremos un desglose de trabajo, junto con un pequeño cronograma que va de la mano con
responsabilidades, asignación de recursos y tareas. Sin dejar de lado los monitoreos y
controles de todas las actividades previstas.

1. Alcance del Software
a. Metas y Objetivos

Buscamos desarrollar un videojuego móvil que ayude al desarrollo de la comprensión lectora
de los niños interactivamente.

El proyecto se centra en el desarrollo de un videojuego que permita a los usuarios
(principalmente niños) familiarizarse más fácilmente con la lectura mediante cuentos cortos
con los que pueden interactuar para ir formando la historia mientras leen.

b. Requisitos del Sistema
● Menú de inicio: Visualización de las opciones antes de iniciar el juego (iniciar el
juego, acceder a los ajustes y salir).
● Acceder a los ajustes: Permitir acceder a los ajustes desde el menú de inicio.

## Pagina 3

● Salir del juego: Cerrar el juego desde las opciones.
● Pausar el juego: Pausar el juego y continuar donde se encontraba cuando se
despausa.
● Ajustar el juego (mientras se juega): Permitir el acceso a los ajustes mientras se
juega.

c. Entregables
● Prototipo Funcional: Diseños interactivos de las pantallas antes de la codificación.
● Código Fuente: Repositorio en GitHub con la aplicación desarrollada en Unity
utilizando el lenguaje C#.
● Manual de Usuario y Sustentación: Documento PDF descriptivo de la arquitectura,
casos de uso probados y guía de navegación para la demo.
● Archivo APK: Ejecutable final empaquetado e instalable en dispositivos Android.

d. Exclusiones
● Pasarela de Pagos: No se procesarán transacciones monetarias ni cobros de
alquileres dentro de la aplicación.
● Sistema de Chat Interno: No se desarrollará infraestructura de mensajería en tiempo
real.
● Sanciones Automáticas o Notificaciones Push: No habrá notificaciones sobre
información del juego.

e. Restricciones y Supuestos
● Restricciones:
○ Tiempo: Desarrollo delimitado a un ciclo académico de 8 semanas.
○ Presupuesto: $0 USD, se utilizará exclusivamente la capa gratuita de Unity y
herramientas de código abierto.
○ Tecnología Obligatoria: Unity, lenguaje C#, y Android SDK 24+ (Android
7.0 en adelante).
● Supuestos:
○ Los estudiantes cuentan con un dispositivo Android y conexión a internet
móvil o Wi-Fi del campus.
2. Plan de Trabajo

a. Desglose de Trabajo (Product Backlog / EDT)
● FASE DE INICIACIÓN Y DISEÑO
○ Configuración del proyecto en Unity.
○ Vinculación del proyecto con la ventana integrada de Unity.
○ Creación de mockups y flujo de pantallas en Figma.

## Pagina 4

● FASE DE MENÚ DE INICIO
○ Maquetación de la pantalla de inicio.
● FASE DE DESARROLLO DE LA HISTORIA
○ Elección de la historia .
○ Ilustración de las imágenes a usar.
● FASE DE PRUEBA UI
○ Implementación y prueba del menú de inicio.
○ Implementación y funcionalidad de iconos.
● FASE DE PROGRAMACIÓN
○ Integrar las imágenes.
○ Programación de la interacción del juego.
○ Integración de sonidos.
● FASE DE CALIDAD Y ENTREGA
○ Manejo de excepciones (try-catch) y estados de carga (ProgressBar).
○ Pruebas y corrección de Bugs.
○ Generación del APK y documento de sustentación.

b. Cronograma de Actividades

Hito / Actividad Fecha de Inicio Fecha de Fin Duración

S1: Configuración y Mockups Semana 1 Semana 2 14 días
(1.1 - 1.3)

S2: Diseño (2.1 - 2.3) Semana 3 Semana 5 14 días

S3: Implementación y Semana 6 Semana 7 14 días
funcionalidad (3.1 - 3.4)

S4: Programación (4.1 - 5.3) Semana 8 Semana 12 28 días

S5: Detalles finales y extras Semana 13 Semana 13 7 días

c. Asignación de Responsables y Recursos

## Pagina 5

Rol Integrante Responsabilidades

Desarrollador Juan Vargas Configuración, lógica y navegación de menús
Navegación y datos e iconos, corrección de fallos.

Desarrollador UI Igor Galvis Diseño de prototipo, implementación de vistas
(Layouts) y menús, gestión del apartado visual, sonido y
colores.

Desarrollador de Mario Implementación de navegación, conectar los
Lógica Reyes componentes con la lógica del juego.

d. Monitoreo y Control
● Reunión Sincrónica de 15 Minutos (Semanal): Se realizará una revisión rápida al
inicio de cada semana para responder tres preguntas: ¿Qué se completó?, ¿En qué se
va a trabajar? y ¿Qué bloqueos técnicos existen?
● Gestión de Imprevistos: Si una tarea excede el tiempo estimado, se recortará alcance
secundario (ejemplo: si el filtro por facultad presenta problemas, se mantendrá
únicamente la búsqueda general por título/autor).
● Control de Versiones (Git): Cada funcionalidad se desarrollará en una rama
independiente, antes de fusionar a la rama principal realizaremos una previa
verificación de que el código no rompe la compilación.

## Requisitos tecnicos y seguimiento de entrega

Esta seccion complementa las restricciones tecnicas y las funcionalidades descritas en este documento. Los requisitos especifican lo que se debe cumplir; no certifican por si solos que el proyecto compile ni que las funciones esten implementadas.

### Plataforma y herramientas
- Motor: Unity 6000.6.3f1, segun ProjectSettings/ProjectVersion.txt.
- Lenguaje de programacion: C#, conforme al alcance del proyecto.
- Plataforma de entrega: Android; la version minima indicada en este documento es Android 7.0 (API 24).
- El equipo de desarrollo debe tener instalado Unity con Android Build Support y las herramientas SDK, NDK y OpenJDK compatibles con la version de Unity del proyecto. Se deben documentar o fijar sus versiones exactas para que las compilaciones sean reproducibles.
- El juego debe poder instalarse y ejecutarse en un dispositivo Android compatible y probarse en el dispositivo objetivo antes de la entrega.
- La conectividad a internet movil o Wi-Fi se mantiene como supuesto del proyecto; cualquier funcion que dependa de red debe indicar sus requisitos y comportamiento sin conexion.

### Compilacion automatica y entrega
- Cada cambio en main y cada pull request dirigido a main debe ejecutar la compilacion Unity para Android mediante GitHub Actions.
- El flujo debe usar la licencia de Unity y la configuracion segura requerida por el servicio de CI; las credenciales se guardan como secretos del repositorio y nunca en los archivos versionados.
- Una compilacion se considera correcta solo si la accion termina sin errores y genera el APK como artefacto descargable. La liberacion del APK no sustituye una compilacion automatica exitosa.
- La revision recibida informa que el proyecto no compila. Por tanto, este requisito sigue pendiente hasta corregir la causa y verificar una ejecucion exitosa del flujo Unity CI para Android. El repositorio contiene el flujo .github/workflows/unity.yml, pero su existencia no demuestra que la compilacion funcione.

### Estado de entregas segun revision y comprobacion del repositorio
- [x] Documentacion en Markdown: se encuentran las versiones .md en docs/ y los PDF originales fueron retirados de esa carpeta.
- [x] APK publicado: existe la seccion de Releases (https://github.com/CRiPTA22/juego-maricuentos/releases) con la version v1.0; la revision indica que alli se publico el APK.
- [ ] Compilacion automatica: pendiente, segun el error de compilacion reportado; requiere una ejecucion exitosa en GitHub Actions.
- [ ] Codigo fuente: la revision recibida marca esta observacion como atendida, pero en el arbol actual de main no aparece la carpeta Assets/ ni se identifican scripts C# del juego. Verificar la entrega y agregar el proyecto fuente completo si esta marca no corresponde a una correccion posterior.
- [ ] Funcionalidades de menu, ajustes, salida, pausa e interaccion con el texto: pendientes de implementacion o pruebas segun la retroalimentacion; consultar los criterios de aceptacion detallados en Historia de usuario (./Historia%20de%20usuario.md).
