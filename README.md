# BombiTeclado

Teclado braille de pantalla para Android 12 o posterior. Cada punto se escribe donde se apoya el dedo. Funciona con varios lectores de pantalla y está probado con JieShuo, TalkBack y Backtalk.

Cada ajuste ofrece su explicación con la acción «Ayuda» del lector de pantalla, y la pestaña Ayuda las reúne todas.

Este repositorio solo guarda las versiones publicadas: los APK y las tablas braille firmadas.

## Instalar

1. Descargar el APK según la versión de Android. Los dos enlaces dan siempre la última versión:
   - Android 15 o posterior: [bombiteclado.apk](https://github.com/AAyoubelbakhti/bombiteclado-releases/releases/latest/download/bombiteclado.apk).
   - Android 12, 13 y 14: [bombiteclado-tostadora.apk](https://github.com/AAyoubelbakhti/bombiteclado-releases/releases/latest/download/bombiteclado-tostadora.apk), la tostadora edition, la misma app para Android antiguos.
2. Abrirlo en el móvil. Si Android lo pide, permitir instalar apps desde esa fuente.
3. Abrir BombiTeclado: la bienvenida guía la activación y la elección del teclado.

## Actualizaciones

La app busca una versión nueva al abrirse y cuando se le pide, en Inicio, con «Buscar actualizaciones». Antes de instalarla, comprueba que la descarga coincide con la publicada. Las tablas braille se actualizan aparte, con su propia firma.

## Gestos

BombiTeclado trae dos esquemas de gestos. En la app, en Ajustes › Gestos, se elige uno y se puede cambiar cualquier gesto; en el teclado también, desde su menú (tres dedos arriba), en Gestos.

- **Predeterminado**: los deslizamientos cuentan los dedos, sean cuales sean, como en el teclado braille de TalkBack.
- **Alternativo**: importa desde qué punto se desliza. «Desde el punto 4» quiere decir que el dedo que desliza empieza en el punto 4, y «mantener 1», que el punto 1 se queda apoyado mientras otro dedo desliza. Al escribir y en edición, los deslizamientos de dos dedos tienen que ser largos: abajo envía, arriba cambia de teclado, a la derecha oculta el teclado y a la izquierda dicta. Al escribir, algunos acordes ejecutan una orden con una pulsación larga.

En los dos, para calibrar, se apoyan todos los dedos dos segundos. Un deslizamiento «largo» recorre algo más de un tercio del lado corto de la pantalla, y una «pulsación larga» es un acorde que se mantiene quieto medio segundo antes de soltarlo; el tiempo se cambia en Ajustes › Tacto y calibración. Una pulsación larga sin orden se escribe como el acorde, y un deslizamiento largo sin orden propia hace lo del normal. Los gestos de tres dedos funcionan en todos los modos, y ocultar el teclado es dos dedos abajo, salvo en escritura y edición con el esquema alternativo, donde es dos dedos a la derecha, largo. Las abreviaturas se expanden solas al acabar la palabra con un espacio o un salto de línea; si se desactiva «Reemplazar automáticamente», en Ajustes › Escritura › Lista de abreviaturas, solo con su gesto. En el modo navegación, cada gesto es una sola tecla o un modificador, y cada acorde, una tecla del ordenador con la tabla de braille informático. Las combinaciones se hacen fijando los modificadores para la tecla siguiente, como Mayúsculas y luego Tab; «mantener los modificadores fijados» los deja apretados para varias teclas, como Alt mientras se pulsa Tab o Insert para NVDA, hasta soltarlos.

En el modo emojis y otros símbolos, los acordes escriben lo que se busca, que se encuentra en el nombre o en las palabras clave de cada emoji o símbolo, sin distinguir mayúsculas ni tildes. La lista se filtra con cada letra y dice cuántos resultados hay y cuál es el primero. Tras los emojis vienen, por categorías, los símbolos que no son emoji, para los signos que la tabla braille en uso no tiene.

<!-- gestures:es -->

### Al escribir, y los de todos los modos

| Orden | Predeterminado | Alternativo |
|---|---|---|
| modo siguiente | 3 dedos a la derecha | 3 dedos a la derecha |
| modo anterior | 3 dedos a la izquierda | 3 dedos a la izquierda |
| pasar a edición y volver | — | un dedo a la derecha desde el punto 3 |
| pasar a emojis y otros símbolos y volver | — | un dedo a la izquierda desde el punto 5 |
| menú | 3 dedos arriba | 3 dedos arriba |
| cambiar de teclado | 3 dedos abajo | 2 dedos arriba, largo, o 3 dedos abajo |
| ocultar el teclado | 2 dedos abajo | 2 dedos a la derecha, largo |
| espacio | un dedo a la derecha | un dedo a la derecha desde el punto 4 o pulsación larga del punto 4 |
| espacio, expandiendo la abreviatura | — | un dedo a la derecha desde el punto 5 |
| expandir la abreviatura | mantener 5, 2 dedos a la derecha | pulsación larga del punto 1 |
| nueva línea | 2 dedos a la derecha | un dedo a la izquierda desde el punto 6 o pulsación larga de los puntos 1 5 |
| enviar | 2 dedos arriba | 2 dedos abajo, largo, o pulsación larga de los puntos 1 3 |
| borrar carácter | un dedo a la izquierda | un dedo a la izquierda desde el punto 4 o pulsación larga de los puntos 1 2 |
| borrar palabra | 2 dedos a la izquierda | un dedo a la izquierda desde el punto 1 o pulsación larga de los puntos 1 4 |
| deshacer | mantener 4 5 6, un dedo a la izquierda | mantener 6, un dedo a la izquierda desde el punto 3 |
| rehacer | mantener 4 5 6, un dedo a la derecha | mantener 6, un dedo a la derecha desde el punto 3 |
| bloqueo de mayúsculas | mantener 4 6, un dedo a la derecha | un dedo a la derecha desde el punto 6 o pulsación larga del punto 6 |
| cursor atrás | un dedo arriba | un dedo a la izquierda desde el punto 2 |
| cursor adelante | un dedo abajo | un dedo a la derecha desde el punto 2 |
| carácter anterior | mantener 6, un dedo arriba | — |
| carácter siguiente | mantener 6, un dedo abajo | — |
| palabra anterior | mantener 5, un dedo arriba | mantener 1, un dedo a la izquierda desde el punto 5 |
| palabra siguiente | mantener 5, un dedo abajo | mantener 1, un dedo a la derecha desde el punto 5 |
| frase anterior | — | mantener 1, un dedo a la izquierda desde el punto 6 |
| frase siguiente | — | mantener 1, un dedo a la derecha desde el punto 6 |
| línea anterior | mantener 4, un dedo arriba | mantener 2, un dedo a la izquierda desde el punto 4 |
| línea siguiente | mantener 4, un dedo abajo | mantener 2, un dedo a la derecha desde el punto 4 |
| principio de la línea | — | mantener 2, un dedo a la izquierda desde el punto 5 |
| final de la línea | — | mantener 2, un dedo a la derecha desde el punto 5 |
| principio del texto | mantener 4 5, un dedo arriba | mantener 2, un dedo a la izquierda desde el punto 6 |
| final del texto | mantener 4 5, un dedo abajo | mantener 2, un dedo a la derecha desde el punto 6 |
| seleccionar el carácter anterior | mantener 6, 2 dedos arriba | — |
| seleccionar el carácter siguiente | mantener 6, 2 dedos abajo | — |
| seleccionar la palabra anterior | mantener 5, 2 dedos arriba | — |
| seleccionar la palabra siguiente | mantener 5, 2 dedos abajo | — |
| seleccionar hasta la línea anterior | mantener 4, 2 dedos arriba | — |
| seleccionar hasta la línea siguiente | mantener 4, 2 dedos abajo | — |
| seleccionar hasta el principio | mantener 4 5, 2 dedos arriba | — |
| seleccionar hasta el final | mantener 4 5, 2 dedos abajo | — |
| seleccionar todo | mantener 4, 3 dedos a la izquierda | mantener 4, un dedo a la izquierda desde el punto 2 |
| marcar el inicio de la selección | mantener 4, 2 dedos a la izquierda | mantener 4, un dedo a la izquierda desde el punto 3 |
| seleccionar desde la marca | mantener 4, 2 dedos a la derecha | — |
| seleccionar lo recorrido | — | mantener 4, un dedo a la derecha desde el punto 3 |
| cortar | mantener 4, 3 dedos arriba | mantener 5, un dedo a la izquierda desde el punto 1 |
| copiar | mantener 4, 3 dedos abajo | mantener 5, un dedo a la derecha desde el punto 1 |
| pegar | mantener 4, 3 dedos a la derecha | mantener 5, un dedo a la izquierda desde el punto 2 |
| leer el carácter | mantener 6, un dedo a la derecha | — |
| leer el carácter con su palabra fonética | mantener 6, un dedo a la izquierda | — |
| leer la palabra | mantener 5, un dedo a la derecha | — |
| deletrear la palabra | mantener 5, un dedo a la izquierda | pulsación larga de los puntos 1 2 3 |
| leer la palabra antes del cursor | — | mantener 4, un dedo a la izquierda desde el punto 1 |
| leer la palabra tras el cursor | — | mantener 4, un dedo a la derecha desde el punto 1 |
| leer la línea | mantener 4, un dedo a la derecha | — |
| leer el campo entero | mantener 4, un dedo a la izquierda | mantener 4, un dedo a la derecha desde el punto 2 |
| leer hasta el cursor | — | mantener 3, un dedo a la izquierda desde el punto 5 |
| leer desde el cursor | — | mantener 3, un dedo a la derecha desde el punto 5 |
| leer la frase hasta el cursor | — | un dedo a la izquierda desde el punto 3 |
| leer la selección | — | mantener 5, un dedo a la derecha desde el punto 3 |
| leer el portapapeles | — | mantener 5, un dedo a la izquierda desde el punto 3 |
| borrar la selección o la unidad | — | mantener 5, un dedo a la derecha desde el punto 2 |
| tabla anterior | mantener 4 5, un dedo a la izquierda | — |
| tabla siguiente | mantener 4 5, un dedo a la derecha | un dedo a la derecha desde el punto 1 o pulsación larga del punto 3 |
| 6 u 8 puntos | mantener 4 5, 2 dedos a la derecha | — |
| fijar o liberar la posición del teclado | mantener 4 5 6, un dedo arriba | — |
| fijar la posición del teclado | — | mantener 6, un dedo a la derecha desde el punto 1 |
| liberar la posición del teclado | — | mantener 6, un dedo a la izquierda desde el punto 1 |
| cambiar el eco al escribir | mantener 4 5 6, 2 dedos arriba | mantener 3, un dedo a la izquierda desde el punto 6 |
| dictado | mantener 4 5 6, un dedo abajo | 2 dedos a la izquierda, largo |
| subir el volumen | — | pulsación larga de los puntos 5 6 |
| bajar el volumen | — | pulsación larga de los puntos 2 3 |
| tabulador | — | mantener 3, un dedo a la derecha desde el punto 4 |
| mayúsculas tabulador | — | mantener 3, un dedo a la izquierda desde el punto 4 |

### En el modo edición

| Orden | Predeterminado | Alternativo |
|---|---|---|
| pasar a edición y volver | — | un dedo a la derecha desde el punto 3 |
| pasar a emojis y otros símbolos y volver | — | un dedo a la izquierda desde el punto 5 |
| cambiar de teclado | 3 dedos abajo | 2 dedos arriba, largo, o 3 dedos abajo |
| ocultar el teclado | 2 dedos abajo | 2 dedos a la derecha, largo |
| espacio | — | un dedo a la derecha desde el punto 4 |
| espacio, expandiendo la abreviatura | — | un dedo a la derecha desde el punto 5 |
| expandir la abreviatura | mantener 5, 2 dedos a la derecha | — |
| nueva línea | — | un dedo a la izquierda desde el punto 6 |
| enviar | — | 2 dedos abajo, largo |
| borrar carácter | — | un dedo a la izquierda desde el punto 4 |
| borrar palabra | — | un dedo a la izquierda desde el punto 1 |
| deshacer | mantener 4 5 6, un dedo a la izquierda o puntos 1 3 5 6 | mantener 6, un dedo a la izquierda desde el punto 3 |
| rehacer | mantener 4 5 6, un dedo a la derecha o puntos 1 3 4 5 6 | mantener 6, un dedo a la derecha desde el punto 3 |
| bloqueo de mayúsculas | mantener 4 6, un dedo a la derecha | un dedo a la derecha desde el punto 6 |
| cursor atrás | — | un dedo a la izquierda desde el punto 2 |
| cursor adelante | — | un dedo a la derecha desde el punto 2 |
| carácter anterior | mantener 6, un dedo arriba | — |
| carácter siguiente | mantener 6, un dedo abajo | — |
| palabra anterior | mantener 5, un dedo arriba | mantener 1, un dedo a la izquierda desde el punto 5 o punto 1 |
| palabra siguiente | mantener 5, un dedo abajo | mantener 1, un dedo a la derecha desde el punto 5 o punto 4 |
| frase anterior | — | mantener 1, un dedo a la izquierda desde el punto 6 o punto 2 |
| frase siguiente | — | mantener 1, un dedo a la derecha desde el punto 6 o punto 5 |
| línea anterior | mantener 4, un dedo arriba | mantener 2, un dedo a la izquierda desde el punto 4 o puntos 1 4 |
| línea siguiente | mantener 4, un dedo abajo | mantener 2, un dedo a la derecha desde el punto 4 o puntos 2 5 |
| principio de la línea | — | mantener 2, un dedo a la izquierda desde el punto 5 o puntos 1 2 |
| final de la línea | — | mantener 2, un dedo a la derecha desde el punto 5 o puntos 4 5 |
| principio del texto | mantener 4 5, un dedo arriba o puntos 2 4 | mantener 2, un dedo a la izquierda desde el punto 6 o punto 3 |
| final del texto | mantener 4 5, un dedo abajo o puntos 1 2 4 | mantener 2, un dedo a la derecha desde el punto 6 o punto 6 |
| volver a la posición anterior | — | puntos 1 3 5 6 |
| seleccionar el carácter anterior | mantener 6, 2 dedos arriba | — |
| seleccionar el carácter siguiente | mantener 6, 2 dedos abajo | — |
| seleccionar la palabra anterior | mantener 5, 2 dedos arriba | — |
| seleccionar la palabra siguiente | mantener 5, 2 dedos abajo | — |
| seleccionar hasta la línea anterior | mantener 4, 2 dedos arriba | — |
| seleccionar hasta la línea siguiente | mantener 4, 2 dedos abajo | — |
| seleccionar hasta el principio | mantener 4 5, 2 dedos arriba | — |
| seleccionar hasta el final | mantener 4 5, 2 dedos abajo | — |
| seleccionar todo | mantener 4, 3 dedos a la izquierda o punto 1 | mantener 4, un dedo a la izquierda desde el punto 2 o puntos 2 3 5 6 |
| quitar la selección | puntos 2 3 4 | — |
| marcar el inicio de la selección | mantener 4, 2 dedos a la izquierda o puntos 1 3 4 | mantener 4, un dedo a la izquierda desde el punto 3 o puntos 1 4 5 |
| seleccionar desde la marca | mantener 4, 2 dedos a la derecha o puntos 1 2 5 | — |
| seleccionar lo recorrido | — | mantener 4, un dedo a la derecha desde el punto 3 o puntos 1 2 4 |
| cortar | mantener 4, 3 dedos arriba o puntos 1 3 4 6 | mantener 5, un dedo a la izquierda desde el punto 1 o puntos 1 2 3 4 |
| copiar | mantener 4, 3 dedos abajo o puntos 1 4 | mantener 5, un dedo a la derecha desde el punto 1 o puntos 1 2 3 5 |
| pegar | mantener 4, 3 dedos a la derecha o puntos 1 2 3 6 | mantener 5, un dedo a la izquierda desde el punto 2 o puntos 1 2 3 6 |
| leer el carácter | mantener 6, un dedo a la derecha | — |
| leer el carácter con su palabra fonética | mantener 6, un dedo a la izquierda | — |
| leer la palabra | mantener 5, un dedo a la derecha | — |
| deletrear la palabra | mantener 5, un dedo a la izquierda | — |
| leer la palabra antes del cursor | — | mantener 4, un dedo a la izquierda desde el punto 1 o puntos 2 3 |
| leer la palabra tras el cursor | — | mantener 4, un dedo a la derecha desde el punto 1 o puntos 5 6 |
| leer la línea | mantener 4, un dedo a la derecha | — |
| leer el campo entero | mantener 4, un dedo a la izquierda | mantener 4, un dedo a la derecha desde el punto 2 o puntos 1 2 4 5 |
| leer hasta el cursor | — | mantener 3, un dedo a la izquierda desde el punto 5 o puntos 1 2 3 |
| leer desde el cursor | — | mantener 3, un dedo a la derecha desde el punto 5 o puntos 4 5 6 |
| leer la frase hasta el cursor | — | un dedo a la izquierda desde el punto 3 |
| leer la selección | 2 dedos arriba | mantener 5, un dedo a la derecha desde el punto 3 o puntos 1 5 |
| leer el portapapeles | — | mantener 5, un dedo a la izquierda desde el punto 3 o puntos 2 4 |
| decir la fecha y la hora | — | puntos 1 6 |
| unidad anterior | un dedo a la izquierda | — |
| unidad siguiente | un dedo a la derecha | — |
| tipo de unidad anterior | un dedo arriba | — |
| tipo de unidad siguiente | un dedo abajo | — |
| ampliar la selección hacia atrás | 2 dedos a la izquierda | — |
| ampliar la selección hacia delante | 2 dedos a la derecha | — |
| borrar la selección o la unidad | puntos 1 2 | mantener 5, un dedo a la derecha desde el punto 2 o puntos 1 3 4 6 |
| tabla anterior | mantener 4 5, un dedo a la izquierda | — |
| tabla siguiente | mantener 4 5, un dedo a la derecha | un dedo a la derecha desde el punto 1 |
| 6 u 8 puntos | mantener 4 5, 2 dedos a la derecha | — |
| fijar o liberar la posición del teclado | mantener 4 5 6, un dedo arriba | — |
| fijar la posición del teclado | — | mantener 6, un dedo a la derecha desde el punto 1 |
| liberar la posición del teclado | — | mantener 6, un dedo a la izquierda desde el punto 1 |
| cambiar el eco al escribir | mantener 4 5 6, 2 dedos arriba | mantener 3, un dedo a la izquierda desde el punto 6 |
| dictado | mantener 4 5 6, un dedo abajo | 2 dedos a la izquierda, largo |
| tabulador | — | mantener 3, un dedo a la derecha desde el punto 4 o puntos 1 2 3 4 5 |
| mayúsculas tabulador | — | mantener 3, un dedo a la izquierda desde el punto 4 o puntos 1 2 4 5 6 |

### En el modo corrección

| Orden | Predeterminado | Alternativo |
|---|---|---|
| ocultar el teclado | 2 dedos abajo | 2 dedos abajo |
| error ortográfico anterior | un dedo arriba | un dedo arriba |
| error ortográfico siguiente | un dedo abajo | un dedo abajo |
| sugerencia anterior | un dedo a la izquierda | un dedo a la izquierda |
| sugerencia siguiente | un dedo a la derecha | un dedo a la derecha |
| sustituir por la sugerencia | 2 dedos a la derecha | 2 dedos a la derecha |
| deshacer la corrección | 2 dedos a la izquierda | 2 dedos a la izquierda |
| ignorar esta palabra | 2 dedos arriba | 2 dedos arriba |
| ignorar la palabra en todo el texto | puntos 2 3 4 5 | puntos 2 3 4 5 |
| añadir al diccionario | puntos 1 4 5 | puntos 1 4 5 |

### En el modo navegación

| Orden | Predeterminado | Alternativo |
|---|---|---|
| ocultar el teclado | 2 dedos abajo | 2 dedos abajo |
| flecha arriba | un dedo arriba | un dedo arriba |
| flecha abajo | un dedo abajo | un dedo abajo |
| flecha izquierda | un dedo a la izquierda | un dedo a la izquierda |
| flecha derecha | un dedo a la derecha | un dedo a la derecha |
| inicio | mantener 4, un dedo a la izquierda | mantener 4, un dedo a la izquierda |
| fin | mantener 4, un dedo a la derecha | mantener 4, un dedo a la derecha |
| retroceder página | mantener 4, un dedo arriba | mantener 4, un dedo arriba |
| avanzar página | mantener 4, un dedo abajo | mantener 4, un dedo abajo |
| tabulador | 2 dedos arriba | 2 dedos arriba |
| intro | 2 dedos a la derecha | 2 dedos a la derecha |
| retroceso | 2 dedos a la izquierda | 2 dedos a la izquierda |
| espacio | mantener 6, un dedo abajo | mantener 6, un dedo abajo |
| suprimir | mantener 6, un dedo a la derecha | mantener 6, un dedo a la derecha |
| escape | mantener 6, un dedo a la izquierda | mantener 6, un dedo a la izquierda |
| aplicaciones | mantener 6, un dedo arriba | mantener 6, un dedo arriba |
| insert | mantener 4 5, un dedo a la derecha | mantener 4 5, un dedo a la derecha |
| bloq mayús | mantener 4 5, un dedo a la izquierda | mantener 4 5, un dedo a la izquierda |
| fijar control | mantener 5, un dedo a la derecha | mantener 5, un dedo a la derecha |
| fijar alt | mantener 5, un dedo a la izquierda | mantener 5, un dedo a la izquierda |
| fijar mayúsculas | mantener 5, un dedo arriba | mantener 5, un dedo arriba |
| fijar windows | mantener 5, un dedo abajo | mantener 5, un dedo abajo |
| fijar insert | mantener 5 6, un dedo a la derecha | mantener 5 6, un dedo a la derecha |
| fijar bloq mayús | mantener 5 6, un dedo a la izquierda | mantener 5 6, un dedo a la izquierda |
| mantener los modificadores fijados | mantener 5 6, un dedo arriba | mantener 5 6, un dedo arriba |
| quitar o soltar los modificadores | mantener 5 6, un dedo abajo | mantener 5 6, un dedo abajo |

### En el modo emojis y otros símbolos

| Orden | Predeterminado | Alternativo |
|---|---|---|
| pasar a emojis y otros símbolos y volver | — | un dedo a la izquierda desde el punto 5 |
| ocultar el teclado | 2 dedos abajo | 2 dedos abajo |
| emoji o símbolo anterior | un dedo a la izquierda | un dedo a la izquierda |
| emoji o símbolo siguiente | un dedo a la derecha | un dedo a la derecha |
| categoría anterior | un dedo arriba | un dedo arriba |
| categoría siguiente | un dedo abajo | un dedo abajo |
| insertar el emoji o símbolo | 2 dedos a la derecha | 2 dedos a la derecha |
| añadir o quitar de favoritos | 2 dedos arriba | 2 dedos arriba |
| borrar la última letra de la búsqueda | mantener 6, un dedo a la izquierda | mantener 6, un dedo a la izquierda |
| borrar la búsqueda | 2 dedos a la izquierda | 2 dedos a la izquierda |

<!-- /gestures:es -->

## Licencias

BombiTeclado usa liblouis 3.39.0, sin modificar, y sus tablas, con licencia LGPL 2.1 o posterior. Su código fuente está en [la versión 3.39.0 de liblouis](https://github.com/liblouis/liblouis/releases/tag/v3.39.0). El tema de sonido TalkBack usa los sonidos de TalkBack, con licencia Apache 2.0. La app muestra todas las licencias en Ayuda, Licencias.

---

## English

BombiTeclado is an on-screen braille keyboard for Android 12 and later. Each dot is typed where a finger rests. It works with several screen readers and has been tested with JieShuo, TalkBack and Backtalk. Each setting offers its explanation through the screen reader action Help, and the Help tab gathers them all.

This repository only holds the published versions: the APKs and the signed braille tables. Download [bombiteclado.apk](https://github.com/AAyoubelbakhti/bombiteclado-releases/releases/latest/download/bombiteclado.apk) for Android 15 and later, or [bombiteclado-tostadora.apk](https://github.com/AAyoubelbakhti/bombiteclado-releases/releases/latest/download/bombiteclado-tostadora.apk), the tostadora edition, for Android 12, 13 and 14; both links always give the latest version. Open it on the phone and follow the welcome screens. The app checks for a new version when it opens and on demand, from Home, with Check for updates, and verifies each download before installing it.

### Gestures

BombiTeclado ships two gesture schemes. In the app, under Settings › Gestures, a scheme is chosen and any gesture can be changed; on the keyboard too, from its menu (three fingers up), under Gestures.

- **Default**: swipes count fingers, whichever they are, as in the TalkBack braille keyboard.
- **Alternative**: the dot a swipe starts from matters. "From dot 4" means the swiping finger starts on dot 4, and "hold 1" means dot 1 stays down while another finger swipes. While typing and editing, two-finger swipes have to be long: down sends, up switches keyboard, right hides the keyboard and left dictates. While typing, some chords run a command on a long press.

In both, to calibrate, rest all fingers for two seconds. A "long" swipe goes a little over a third of the short side of the screen, and a "long press" is a chord held still for half a second before it is lifted; the time is changed under Settings › Touch and calibration. A long press with no command types as its chord, and a long swipe with no command of its own does what the plain one does. The three-finger gestures work in every mode, and hiding the keyboard is two fingers down, except in typing and editing with the alternative scheme, where it is two fingers right, long. Abbreviations expand by themselves when their word ends with a space or a line break; with "Replace automatically" off, under Settings › Writing › Abbreviation list, only with their gesture. In navigation mode, each gesture is a single key or a modifier, and each chord is a computer key, read with the computer braille table. Combinations come from latching the modifiers for the next key, such as Shift and then Tab; "hold the latched modifiers" keeps them down for several keys, such as Alt while pressing Tab or Insert for NVDA, until they are released.

In emoji and other symbols mode, chords type the search, matched against the name and keywords of each emoji or symbol, ignoring case and accents. The list narrows with each letter and says how many results there are and which one comes first. After the emoji come the symbols that are not emoji, by category, for signs the braille table in use lacks.

<!-- gestures:en -->

#### While typing, and those of every mode

| Command | Default | Alternative |
|---|---|---|
| next mode | 3 fingers right | 3 fingers right |
| previous mode | 3 fingers left | 3 fingers left |
| switch to editing and back | — | one finger right from dot 3 |
| switch to emoji and other symbols and back | — | one finger left from dot 5 |
| menu | 3 fingers up | 3 fingers up |
| switch keyboard | 3 fingers down | 2 fingers up, long, or 3 fingers down |
| hide keyboard | 2 fingers down | 2 fingers right, long |
| space | one finger right | one finger right from dot 4 or long press of dot 4 |
| space, expanding abbreviation | — | one finger right from dot 5 |
| expand abbreviation | hold 5, 2 fingers right | long press of dot 1 |
| new line | 2 fingers right | one finger left from dot 6 or long press of dots 1 5 |
| send | 2 fingers up | 2 fingers down, long, or long press of dots 1 3 |
| delete character | one finger left | one finger left from dot 4 or long press of dots 1 2 |
| delete word | 2 fingers left | one finger left from dot 1 or long press of dots 1 4 |
| undo | hold 4 5 6, one finger left | hold 6, one finger left from dot 3 |
| redo | hold 4 5 6, one finger right | hold 6, one finger right from dot 3 |
| capitals lock | hold 4 6, one finger right | one finger right from dot 6 or long press of dot 6 |
| cursor back | one finger up | one finger left from dot 2 |
| cursor forward | one finger down | one finger right from dot 2 |
| previous character | hold 6, one finger up | — |
| next character | hold 6, one finger down | — |
| previous word | hold 5, one finger up | hold 1, one finger left from dot 5 |
| next word | hold 5, one finger down | hold 1, one finger right from dot 5 |
| previous sentence | — | hold 1, one finger left from dot 6 |
| next sentence | — | hold 1, one finger right from dot 6 |
| previous line | hold 4, one finger up | hold 2, one finger left from dot 4 |
| next line | hold 4, one finger down | hold 2, one finger right from dot 4 |
| start of line | — | hold 2, one finger left from dot 5 |
| end of line | — | hold 2, one finger right from dot 5 |
| start of text | hold 4 5, one finger up | hold 2, one finger left from dot 6 |
| end of text | hold 4 5, one finger down | hold 2, one finger right from dot 6 |
| select previous character | hold 6, 2 fingers up | — |
| select next character | hold 6, 2 fingers down | — |
| select previous word | hold 5, 2 fingers up | — |
| select next word | hold 5, 2 fingers down | — |
| select to previous line | hold 4, 2 fingers up | — |
| select to next line | hold 4, 2 fingers down | — |
| select to start | hold 4 5, 2 fingers up | — |
| select to end | hold 4 5, 2 fingers down | — |
| select all | hold 4, 3 fingers left | hold 4, one finger left from dot 2 |
| mark selection start | hold 4, 2 fingers left | hold 4, one finger left from dot 3 |
| select from mark | hold 4, 2 fingers right | — |
| select what the cursor went over | — | hold 4, one finger right from dot 3 |
| cut | hold 4, 3 fingers up | hold 5, one finger left from dot 1 |
| copy | hold 4, 3 fingers down | hold 5, one finger right from dot 1 |
| paste | hold 4, 3 fingers right | hold 5, one finger left from dot 2 |
| read character | hold 6, one finger right | — |
| read character phonetically | hold 6, one finger left | — |
| read word | hold 5, one finger right | — |
| spell word | hold 5, one finger left | long press of dots 1 2 3 |
| read word before cursor | — | hold 4, one finger left from dot 1 |
| read word after cursor | — | hold 4, one finger right from dot 1 |
| read line | hold 4, one finger right | — |
| read whole field | hold 4, one finger left | hold 4, one finger right from dot 2 |
| read up to cursor | — | hold 3, one finger left from dot 5 |
| read from cursor | — | hold 3, one finger right from dot 5 |
| read sentence up to cursor | — | one finger left from dot 3 |
| read selection | — | hold 5, one finger right from dot 3 |
| read clipboard | — | hold 5, one finger left from dot 3 |
| delete selection or unit | — | hold 5, one finger right from dot 2 |
| previous table | hold 4 5, one finger left | — |
| next table | hold 4 5, one finger right | one finger right from dot 1 or long press of dot 3 |
| 6 or 8 dots | hold 4 5, 2 fingers right | — |
| fix or release keyboard position | hold 4 5 6, one finger up | — |
| fix keyboard position | — | hold 6, one finger right from dot 1 |
| release keyboard position | — | hold 6, one finger left from dot 1 |
| change typing echo | hold 4 5 6, 2 fingers up | hold 3, one finger left from dot 6 |
| dictation | hold 4 5 6, one finger down | 2 fingers left, long |
| volume up | — | long press of dots 5 6 |
| volume down | — | long press of dots 2 3 |
| tab | — | hold 3, one finger right from dot 4 |
| shift tab | — | hold 3, one finger left from dot 4 |

#### In editing mode

| Command | Default | Alternative |
|---|---|---|
| switch to editing and back | — | one finger right from dot 3 |
| switch to emoji and other symbols and back | — | one finger left from dot 5 |
| switch keyboard | 3 fingers down | 2 fingers up, long, or 3 fingers down |
| hide keyboard | 2 fingers down | 2 fingers right, long |
| space | — | one finger right from dot 4 |
| space, expanding abbreviation | — | one finger right from dot 5 |
| expand abbreviation | hold 5, 2 fingers right | — |
| new line | — | one finger left from dot 6 |
| send | — | 2 fingers down, long |
| delete character | — | one finger left from dot 4 |
| delete word | — | one finger left from dot 1 |
| undo | hold 4 5 6, one finger left or dots 1 3 5 6 | hold 6, one finger left from dot 3 |
| redo | hold 4 5 6, one finger right or dots 1 3 4 5 6 | hold 6, one finger right from dot 3 |
| capitals lock | hold 4 6, one finger right | one finger right from dot 6 |
| cursor back | — | one finger left from dot 2 |
| cursor forward | — | one finger right from dot 2 |
| previous character | hold 6, one finger up | — |
| next character | hold 6, one finger down | — |
| previous word | hold 5, one finger up | hold 1, one finger left from dot 5 or dot 1 |
| next word | hold 5, one finger down | hold 1, one finger right from dot 5 or dot 4 |
| previous sentence | — | hold 1, one finger left from dot 6 or dot 2 |
| next sentence | — | hold 1, one finger right from dot 6 or dot 5 |
| previous line | hold 4, one finger up | hold 2, one finger left from dot 4 or dots 1 4 |
| next line | hold 4, one finger down | hold 2, one finger right from dot 4 or dots 2 5 |
| start of line | — | hold 2, one finger left from dot 5 or dots 1 2 |
| end of line | — | hold 2, one finger right from dot 5 or dots 4 5 |
| start of text | hold 4 5, one finger up or dots 2 4 | hold 2, one finger left from dot 6 or dot 3 |
| end of text | hold 4 5, one finger down or dots 1 2 4 | hold 2, one finger right from dot 6 or dot 6 |
| back to previous position | — | dots 1 3 5 6 |
| select previous character | hold 6, 2 fingers up | — |
| select next character | hold 6, 2 fingers down | — |
| select previous word | hold 5, 2 fingers up | — |
| select next word | hold 5, 2 fingers down | — |
| select to previous line | hold 4, 2 fingers up | — |
| select to next line | hold 4, 2 fingers down | — |
| select to start | hold 4 5, 2 fingers up | — |
| select to end | hold 4 5, 2 fingers down | — |
| select all | hold 4, 3 fingers left or dot 1 | hold 4, one finger left from dot 2 or dots 2 3 5 6 |
| clear selection | dots 2 3 4 | — |
| mark selection start | hold 4, 2 fingers left or dots 1 3 4 | hold 4, one finger left from dot 3 or dots 1 4 5 |
| select from mark | hold 4, 2 fingers right or dots 1 2 5 | — |
| select what the cursor went over | — | hold 4, one finger right from dot 3 or dots 1 2 4 |
| cut | hold 4, 3 fingers up or dots 1 3 4 6 | hold 5, one finger left from dot 1 or dots 1 2 3 4 |
| copy | hold 4, 3 fingers down or dots 1 4 | hold 5, one finger right from dot 1 or dots 1 2 3 5 |
| paste | hold 4, 3 fingers right or dots 1 2 3 6 | hold 5, one finger left from dot 2 or dots 1 2 3 6 |
| read character | hold 6, one finger right | — |
| read character phonetically | hold 6, one finger left | — |
| read word | hold 5, one finger right | — |
| spell word | hold 5, one finger left | — |
| read word before cursor | — | hold 4, one finger left from dot 1 or dots 2 3 |
| read word after cursor | — | hold 4, one finger right from dot 1 or dots 5 6 |
| read line | hold 4, one finger right | — |
| read whole field | hold 4, one finger left | hold 4, one finger right from dot 2 or dots 1 2 4 5 |
| read up to cursor | — | hold 3, one finger left from dot 5 or dots 1 2 3 |
| read from cursor | — | hold 3, one finger right from dot 5 or dots 4 5 6 |
| read sentence up to cursor | — | one finger left from dot 3 |
| read selection | 2 fingers up | hold 5, one finger right from dot 3 or dots 1 5 |
| read clipboard | — | hold 5, one finger left from dot 3 or dots 2 4 |
| say date and time | — | dots 1 6 |
| previous unit | one finger left | — |
| next unit | one finger right | — |
| previous unit type | one finger up | — |
| next unit type | one finger down | — |
| extend selection backward | 2 fingers left | — |
| extend selection forward | 2 fingers right | — |
| delete selection or unit | dots 1 2 | hold 5, one finger right from dot 2 or dots 1 3 4 6 |
| previous table | hold 4 5, one finger left | — |
| next table | hold 4 5, one finger right | one finger right from dot 1 |
| 6 or 8 dots | hold 4 5, 2 fingers right | — |
| fix or release keyboard position | hold 4 5 6, one finger up | — |
| fix keyboard position | — | hold 6, one finger right from dot 1 |
| release keyboard position | — | hold 6, one finger left from dot 1 |
| change typing echo | hold 4 5 6, 2 fingers up | hold 3, one finger left from dot 6 |
| dictation | hold 4 5 6, one finger down | 2 fingers left, long |
| tab | — | hold 3, one finger right from dot 4 or dots 1 2 3 4 5 |
| shift tab | — | hold 3, one finger left from dot 4 or dots 1 2 4 5 6 |

#### In spelling mode

| Command | Default | Alternative |
|---|---|---|
| hide keyboard | 2 fingers down | 2 fingers down |
| previous misspelling | one finger up | one finger up |
| next misspelling | one finger down | one finger down |
| previous suggestion | one finger left | one finger left |
| next suggestion | one finger right | one finger right |
| use suggestion | 2 fingers right | 2 fingers right |
| undo correction | 2 fingers left | 2 fingers left |
| ignore word | 2 fingers up | 2 fingers up |
| ignore the word in the whole text | dots 2 3 4 5 | dots 2 3 4 5 |
| add to dictionary | dots 1 4 5 | dots 1 4 5 |

#### In navigation mode

| Command | Default | Alternative |
|---|---|---|
| hide keyboard | 2 fingers down | 2 fingers down |
| up arrow | one finger up | one finger up |
| down arrow | one finger down | one finger down |
| left arrow | one finger left | one finger left |
| right arrow | one finger right | one finger right |
| home | hold 4, one finger left | hold 4, one finger left |
| end | hold 4, one finger right | hold 4, one finger right |
| page up | hold 4, one finger up | hold 4, one finger up |
| page down | hold 4, one finger down | hold 4, one finger down |
| tab | 2 fingers up | 2 fingers up |
| enter | 2 fingers right | 2 fingers right |
| backspace | 2 fingers left | 2 fingers left |
| space | hold 6, one finger down | hold 6, one finger down |
| delete | hold 6, one finger right | hold 6, one finger right |
| escape | hold 6, one finger left | hold 6, one finger left |
| applications | hold 6, one finger up | hold 6, one finger up |
| insert | hold 4 5, one finger right | hold 4 5, one finger right |
| caps lock | hold 4 5, one finger left | hold 4 5, one finger left |
| latch control | hold 5, one finger right | hold 5, one finger right |
| latch alt | hold 5, one finger left | hold 5, one finger left |
| latch shift | hold 5, one finger up | hold 5, one finger up |
| latch windows | hold 5, one finger down | hold 5, one finger down |
| latch insert | hold 5 6, one finger right | hold 5 6, one finger right |
| latch caps lock | hold 5 6, one finger left | hold 5 6, one finger left |
| hold the latched modifiers | hold 5 6, one finger up | hold 5 6, one finger up |
| clear or release modifiers | hold 5 6, one finger down | hold 5 6, one finger down |

#### In emoji and other symbols mode

| Command | Default | Alternative |
|---|---|---|
| switch to emoji and other symbols and back | — | one finger left from dot 5 |
| hide keyboard | 2 fingers down | 2 fingers down |
| previous emoji or symbol | one finger left | one finger left |
| next emoji or symbol | one finger right | one finger right |
| previous category | one finger up | one finger up |
| next category | one finger down | one finger down |
| insert emoji or symbol | 2 fingers right | 2 fingers right |
| add or remove from favorites | 2 fingers up | 2 fingers up |
| delete the last letter of the search | hold 6, one finger left | hold 6, one finger left |
| clear search | 2 fingers left | 2 fingers left |

<!-- /gestures:en -->

It uses liblouis 3.39.0, unmodified, and its tables, under the LGPL 2.1 or later; the source is at [liblouis 3.39.0](https://github.com/liblouis/liblouis/releases/tag/v3.39.0). The TalkBack sound theme uses TalkBack's sounds, under the Apache License 2.0. The app lists every license under Help, Licenses.
