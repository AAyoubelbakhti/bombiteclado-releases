# BombiTeclado

Teclado braille de pantalla para Android 15 o posterior. Cada punto va donde apoyas el dedo. Funciona directamente con JieShuo, y con TalkBack u otros lectores de pantalla mediante su servicio acompañante.

Este repositorio solo guarda las versiones publicadas: el APK y las tablas braille firmadas.

## Instalar

1. En [la última versión](https://github.com/AAyoubelbakhti/bombiteclado-releases/releases/latest), descarga `bombiteclado-<versión>.apk`.
2. Ábrelo en el móvil. Si Android lo pide, permite instalar apps desde esa fuente.
3. Abre BombiTeclado: la bienvenida guía para activarlo y elegirlo.

## Actualizaciones

La app busca una versión nueva al abrirse y cuando se le pide, en Inicio, con «Buscar actualizaciones». Antes de instalarla, comprueba que la descarga coincide con la publicada. Las tablas braille se actualizan aparte, con su propia firma.

## Gestos

BombiTeclado trae dos esquemas de gestos. En la app, en Ajustes › Gestos, se elige uno y se puede cambiar cualquier gesto; en el teclado también, desde su menú (tres dedos arriba), en Gestos.

- **Como TalkBack** (predeterminado): los deslizamientos cuentan los dedos, sean cuales sean, como el teclado braille de TalkBack.
- **Como ABK** (Advanced Braille Keyboard): importa desde qué punto se desliza. «Desde el punto 4» quiere decir que el dedo que desliza empieza en el punto 4, y «mantener 1», que el punto 1 se queda apoyado mientras otro dedo desliza. El modo acción de ABK es aquí el modo edición. No incluye las pulsaciones largas ni otras funciones propias de ABK.

En los dos, para calibrar, apoya todos los dedos dos segundos. Los gestos de tres dedos y el de ocultar el teclado, dos dedos abajo, funcionan en todos los modos. En el modo navegación, cada acorde es una tecla del ordenador, con la tabla de braille informático, y lleva los modificadores fijados; «mantener los modificadores fijados» los deja apretados para varias teclas, como Alt mientras se pulsa Tab o Insert para NVDA, hasta soltarlos.

<!-- gestures:es -->

### Al escribir, y los de todos los modos

| Orden | Como TalkBack (predeterminado) | Como ABK |
|---|---|---|
| modo siguiente | 3 dedos a la derecha | 3 dedos a la derecha |
| modo anterior | 3 dedos a la izquierda | 3 dedos a la izquierda |
| pasar a edición y volver | — | un dedo a la derecha desde el punto 3 |
| pasar a emoji y volver | — | un dedo a la izquierda desde el punto 5 |
| menú | 3 dedos arriba | 3 dedos arriba |
| cambiar de teclado | 3 dedos abajo | 2 dedos a la izquierda o 3 dedos abajo |
| ocultar el teclado | 2 dedos abajo | 2 dedos abajo |
| espacio | un dedo a la derecha | un dedo a la derecha desde el punto 4 o un dedo a la derecha desde el punto 5 |
| nueva línea | 2 dedos a la derecha | un dedo a la izquierda desde el punto 6 |
| enviar | 2 dedos arriba | 2 dedos a la derecha |
| borrar carácter | un dedo a la izquierda | un dedo a la izquierda desde el punto 4 |
| borrar palabra | 2 dedos a la izquierda | un dedo a la izquierda desde el punto 1 |
| deshacer | mantener 4 5 6, un dedo a la izquierda | mantener 6, un dedo a la izquierda desde el punto 3 |
| rehacer | mantener 4 5 6, un dedo a la derecha | mantener 6, un dedo a la derecha desde el punto 3 |
| cursor atrás | un dedo arriba | un dedo a la izquierda desde el punto 2 |
| cursor adelante | un dedo abajo | un dedo a la derecha desde el punto 2 |
| carácter anterior | mantener 6, un dedo arriba | mantener 1, un dedo a la izquierda desde el punto 4 |
| carácter siguiente | mantener 6, un dedo abajo | mantener 1, un dedo a la derecha desde el punto 4 |
| palabra anterior | mantener 5, un dedo arriba | mantener 1, un dedo a la izquierda desde el punto 5 o mantener 4, un dedo a la izquierda desde el punto 1 |
| palabra siguiente | mantener 5, un dedo abajo | mantener 1, un dedo a la derecha desde el punto 5 o mantener 4, un dedo a la derecha desde el punto 1 |
| línea anterior | mantener 4, un dedo arriba | mantener 2, un dedo a la izquierda desde el punto 4 |
| línea siguiente | mantener 4, un dedo abajo | mantener 2, un dedo a la derecha desde el punto 4 |
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
| seleccionar desde la marca | mantener 4, 2 dedos a la derecha | mantener 4, un dedo a la derecha desde el punto 3 |
| cortar | mantener 4, 3 dedos arriba | mantener 5, un dedo a la izquierda desde el punto 1 |
| copiar | mantener 4, 3 dedos abajo | mantener 5, un dedo a la derecha desde el punto 1 |
| pegar | mantener 4, 3 dedos a la derecha | mantener 5, un dedo a la izquierda desde el punto 2 |
| leer el carácter | mantener 6, un dedo a la derecha | — |
| leer el carácter con su palabra fonética | mantener 6, un dedo a la izquierda | — |
| leer la palabra | mantener 5, un dedo a la derecha | — |
| deletrear la palabra | mantener 5, un dedo a la izquierda | — |
| leer la línea | mantener 4, un dedo a la derecha | un dedo a la izquierda desde el punto 3 |
| leer el campo entero | mantener 4, un dedo a la izquierda | mantener 3, un dedo a la derecha desde el punto 5 o mantener 3, un dedo a la izquierda desde el punto 5 o mantener 4, un dedo a la derecha desde el punto 2 |
| leer la selección | — | mantener 5, un dedo a la derecha desde el punto 3 |
| borrar la selección o la unidad | — | mantener 5, un dedo a la derecha desde el punto 2 |
| tabla anterior | mantener 4 5, un dedo a la izquierda | — |
| tabla siguiente | mantener 4 5, un dedo a la derecha | un dedo a la derecha desde el punto 1 |
| 6 u 8 puntos | mantener 4 5, 2 dedos a la derecha | — |
| fijar o liberar la posición del teclado | mantener 4 5 6, un dedo arriba | mantener 6, un dedo a la derecha desde el punto 1 o mantener 6, un dedo a la izquierda desde el punto 1 |
| cambiar el eco al escribir | mantener 4 5 6, 2 dedos arriba | mantener 3, un dedo a la izquierda desde el punto 6 |
| dictado | mantener 4 5 6, un dedo abajo | 2 dedos arriba |
| inicio | — | mantener 2, un dedo a la izquierda desde el punto 5 |
| fin | — | mantener 2, un dedo a la derecha desde el punto 5 |
| tabulador | — | mantener 3, un dedo a la derecha desde el punto 4 |
| mayúsculas tabulador | — | mantener 3, un dedo a la izquierda desde el punto 4 |

### En el modo edición

| Orden | Como TalkBack (predeterminado) | Como ABK |
|---|---|---|
| pasar a edición y volver | — | un dedo a la derecha desde el punto 3 |
| pasar a emoji y volver | — | un dedo a la izquierda desde el punto 5 |
| cambiar de teclado | — | 2 dedos a la izquierda |
| espacio | — | un dedo a la derecha desde el punto 4 o un dedo a la derecha desde el punto 5 |
| nueva línea | — | un dedo a la izquierda desde el punto 6 |
| enviar | — | 2 dedos a la derecha |
| borrar carácter | — | un dedo a la izquierda desde el punto 4 |
| borrar palabra | — | un dedo a la izquierda desde el punto 1 |
| deshacer | mantener 4 5 6, un dedo a la izquierda o puntos 1 3 5 6 | mantener 6, un dedo a la izquierda desde el punto 3 |
| rehacer | mantener 4 5 6, un dedo a la derecha o puntos 1 3 4 5 6 | mantener 6, un dedo a la derecha desde el punto 3 |
| cursor atrás | — | un dedo a la izquierda desde el punto 2 |
| cursor adelante | — | un dedo a la derecha desde el punto 2 |
| carácter anterior | mantener 6, un dedo arriba | mantener 1, un dedo a la izquierda desde el punto 4 |
| carácter siguiente | mantener 6, un dedo abajo | mantener 1, un dedo a la derecha desde el punto 4 |
| palabra anterior | mantener 5, un dedo arriba | mantener 1, un dedo a la izquierda desde el punto 5 o mantener 4, un dedo a la izquierda desde el punto 1 o punto 1 o puntos 2 3 |
| palabra siguiente | mantener 5, un dedo abajo | mantener 1, un dedo a la derecha desde el punto 5 o mantener 4, un dedo a la derecha desde el punto 1 o punto 4 o puntos 5 6 |
| línea anterior | mantener 4, un dedo arriba | mantener 2, un dedo a la izquierda desde el punto 4 o puntos 1 4 |
| línea siguiente | mantener 4, un dedo abajo | mantener 2, un dedo a la derecha desde el punto 4 o puntos 2 5 |
| principio del texto | mantener 4 5, un dedo arriba o puntos 2 4 | mantener 2, un dedo a la izquierda desde el punto 6 o punto 3 |
| final del texto | mantener 4 5, un dedo abajo o puntos 1 2 4 | mantener 2, un dedo a la derecha desde el punto 6 o punto 6 |
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
| seleccionar desde la marca | mantener 4, 2 dedos a la derecha o puntos 1 2 5 | mantener 4, un dedo a la derecha desde el punto 3 o puntos 1 2 4 |
| cortar | mantener 4, 3 dedos arriba o puntos 1 3 4 6 | mantener 5, un dedo a la izquierda desde el punto 1 o puntos 1 2 3 4 |
| copiar | mantener 4, 3 dedos abajo o puntos 1 4 | mantener 5, un dedo a la derecha desde el punto 1 o puntos 1 2 3 5 |
| pegar | mantener 4, 3 dedos a la derecha o puntos 1 2 3 6 | mantener 5, un dedo a la izquierda desde el punto 2 o puntos 1 2 3 6 |
| leer el carácter | mantener 6, un dedo a la derecha | — |
| leer el carácter con su palabra fonética | mantener 6, un dedo a la izquierda | — |
| leer la palabra | mantener 5, un dedo a la derecha | — |
| deletrear la palabra | mantener 5, un dedo a la izquierda | — |
| leer la línea | mantener 4, un dedo a la derecha | un dedo a la izquierda desde el punto 3 |
| leer el campo entero | mantener 4, un dedo a la izquierda | mantener 3, un dedo a la derecha desde el punto 5 o mantener 3, un dedo a la izquierda desde el punto 5 o mantener 4, un dedo a la derecha desde el punto 2 o puntos 1 2 3 o puntos 1 2 4 5 o puntos 4 5 6 |
| leer la selección | 2 dedos arriba | mantener 5, un dedo a la derecha desde el punto 3 o puntos 1 5 |
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
| fijar o liberar la posición del teclado | mantener 4 5 6, un dedo arriba | mantener 6, un dedo a la derecha desde el punto 1 o mantener 6, un dedo a la izquierda desde el punto 1 |
| cambiar el eco al escribir | mantener 4 5 6, 2 dedos arriba | mantener 3, un dedo a la izquierda desde el punto 6 |
| dictado | mantener 4 5 6, un dedo abajo | 2 dedos arriba |
| inicio | — | mantener 2, un dedo a la izquierda desde el punto 5 o puntos 1 2 |
| fin | — | mantener 2, un dedo a la derecha desde el punto 5 o puntos 4 5 |
| tabulador | — | mantener 3, un dedo a la derecha desde el punto 4 o puntos 1 2 3 4 5 |
| mayúsculas tabulador | — | mantener 3, un dedo a la izquierda desde el punto 4 o puntos 1 2 4 5 6 |

### En el modo corrección

| Orden | Como TalkBack (predeterminado) | Como ABK |
|---|---|---|
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

| Orden | Como TalkBack (predeterminado) | Como ABK |
|---|---|---|
| flecha arriba | un dedo arriba | un dedo arriba |
| flecha abajo | un dedo abajo | un dedo abajo |
| flecha izquierda | un dedo a la izquierda | un dedo a la izquierda |
| flecha derecha | un dedo a la derecha | un dedo a la derecha |
| inicio | mantener 4, un dedo a la izquierda | mantener 4, un dedo a la izquierda |
| fin | mantener 4, un dedo a la derecha | mantener 4, un dedo a la derecha |
| retroceder página | mantener 4, un dedo arriba | mantener 4, un dedo arriba |
| avanzar página | mantener 4, un dedo abajo | mantener 4, un dedo abajo |
| control inicio | mantener 4 5, un dedo arriba | mantener 4 5, un dedo arriba |
| control fin | mantener 4 5, un dedo abajo | mantener 4 5, un dedo abajo |
| tabulador | 2 dedos arriba | 2 dedos arriba |
| mayúsculas tabulador | mantener 6, un dedo arriba | mantener 6, un dedo arriba |
| intro | 2 dedos a la derecha | 2 dedos a la derecha |
| retroceso | 2 dedos a la izquierda | 2 dedos a la izquierda |
| suprimir | mantener 6, un dedo a la derecha | mantener 6, un dedo a la derecha |
| escape | mantener 6, un dedo a la izquierda | mantener 6, un dedo a la izquierda |
| insert | mantener 5 6, un dedo abajo | mantener 5 6, un dedo abajo |
| bloq mayús | mantener 6, un dedo abajo | mantener 6, un dedo abajo |
| fijar control | mantener 5, un dedo a la derecha | mantener 5, un dedo a la derecha |
| fijar alt | mantener 5, un dedo a la izquierda | mantener 5, un dedo a la izquierda |
| fijar mayúsculas | mantener 5, un dedo arriba | mantener 5, un dedo arriba |
| fijar insert | mantener 5 6, un dedo a la derecha | mantener 5 6, un dedo a la derecha |
| fijar bloq mayús | mantener 5 6, un dedo a la izquierda | mantener 5 6, un dedo a la izquierda |
| mantener los modificadores fijados | mantener 5 6, un dedo arriba | mantener 5 6, un dedo arriba |
| quitar o soltar los modificadores | mantener 5, un dedo abajo | mantener 5, un dedo abajo |

### En el modo emoji

| Orden | Como TalkBack (predeterminado) | Como ABK |
|---|---|---|
| pasar a emoji y volver | — | un dedo a la izquierda desde el punto 5 |
| emoji anterior | un dedo a la izquierda | un dedo a la izquierda |
| emoji siguiente | un dedo a la derecha | un dedo a la derecha |
| categoría de emoji anterior | un dedo arriba | un dedo arriba |
| categoría de emoji siguiente | un dedo abajo | un dedo abajo |
| insertar el emoji | 2 dedos a la derecha | 2 dedos a la derecha |
| añadir o quitar de favoritos | 2 dedos arriba | 2 dedos arriba |
| borrar la búsqueda | 2 dedos a la izquierda | 2 dedos a la izquierda |

<!-- /gestures:es -->

## Licencias

BombiTeclado usa liblouis 3.39.0, sin modificar, y sus tablas, con licencia LGPL 2.1 o posterior. Su código fuente está en [la versión 3.39.0 de liblouis](https://github.com/liblouis/liblouis/releases/tag/v3.39.0). El tema de sonido TalkBack usa los sonidos de TalkBack, con licencia Apache 2.0. La app muestra todas las licencias en Ayuda, Licencias.

---

## English

BombiTeclado is an on-screen braille keyboard for Android 15 and later. Each dot goes where you rest a finger. It works with JieShuo without extra setup, and with TalkBack or other screen readers through its companion service.

This repository only holds the published versions: the APK and the signed braille tables. Download `bombiteclado-<version>.apk` from [the latest release](https://github.com/AAyoubelbakhti/bombiteclado-releases/releases/latest), open it on the phone, and follow the welcome screens. The app checks for a new version when it opens and on demand, from Home, with Check for updates, and verifies each download before installing it.

### Gestures

BombiTeclado ships two gesture schemes. In the app, under Settings › Gestures, you choose one and can change any gesture; on the keyboard too, from its menu (three fingers up), under Gestures.

- **Like TalkBack** (default): swipes count fingers, whichever they are, like the TalkBack braille keyboard.
- **Like ABK** (Advanced Braille Keyboard): the dot you swipe from matters. "From dot 4" means the swiping finger starts on dot 4, and "hold 1" means dot 1 stays down while another finger swipes. ABK's action mode is the editing mode here. Long presses and other ABK-only features are not included.

In both, to calibrate, rest all your fingers for two seconds. The three-finger gestures and hiding the keyboard, two fingers down, work in every mode. In navigation mode, each chord is a computer key, read with the computer braille table, and carries the latched modifiers; "hold the latched modifiers" keeps them down for several keys, such as Alt while pressing Tab or Insert for NVDA, until they are released.

<!-- gestures:en -->

#### While typing, and those of every mode

| Command | Like TalkBack (default) | Like ABK |
|---|---|---|
| next mode | 3 fingers right | 3 fingers right |
| previous mode | 3 fingers left | 3 fingers left |
| switch to editing and back | — | one finger right from dot 3 |
| switch to emoji and back | — | one finger left from dot 5 |
| menu | 3 fingers up | 3 fingers up |
| switch keyboard | 3 fingers down | 2 fingers left or 3 fingers down |
| hide keyboard | 2 fingers down | 2 fingers down |
| space | one finger right | one finger right from dot 4 or one finger right from dot 5 |
| new line | 2 fingers right | one finger left from dot 6 |
| send | 2 fingers up | 2 fingers right |
| delete character | one finger left | one finger left from dot 4 |
| delete word | 2 fingers left | one finger left from dot 1 |
| undo | hold 4 5 6, one finger left | hold 6, one finger left from dot 3 |
| redo | hold 4 5 6, one finger right | hold 6, one finger right from dot 3 |
| cursor back | one finger up | one finger left from dot 2 |
| cursor forward | one finger down | one finger right from dot 2 |
| previous character | hold 6, one finger up | hold 1, one finger left from dot 4 |
| next character | hold 6, one finger down | hold 1, one finger right from dot 4 |
| previous word | hold 5, one finger up | hold 1, one finger left from dot 5 or hold 4, one finger left from dot 1 |
| next word | hold 5, one finger down | hold 1, one finger right from dot 5 or hold 4, one finger right from dot 1 |
| previous line | hold 4, one finger up | hold 2, one finger left from dot 4 |
| next line | hold 4, one finger down | hold 2, one finger right from dot 4 |
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
| select from mark | hold 4, 2 fingers right | hold 4, one finger right from dot 3 |
| cut | hold 4, 3 fingers up | hold 5, one finger left from dot 1 |
| copy | hold 4, 3 fingers down | hold 5, one finger right from dot 1 |
| paste | hold 4, 3 fingers right | hold 5, one finger left from dot 2 |
| read character | hold 6, one finger right | — |
| read character phonetically | hold 6, one finger left | — |
| read word | hold 5, one finger right | — |
| spell word | hold 5, one finger left | — |
| read line | hold 4, one finger right | one finger left from dot 3 |
| read whole field | hold 4, one finger left | hold 3, one finger right from dot 5 or hold 3, one finger left from dot 5 or hold 4, one finger right from dot 2 |
| read selection | — | hold 5, one finger right from dot 3 |
| delete selection or unit | — | hold 5, one finger right from dot 2 |
| previous table | hold 4 5, one finger left | — |
| next table | hold 4 5, one finger right | one finger right from dot 1 |
| 6 or 8 dots | hold 4 5, 2 fingers right | — |
| fix or release keyboard position | hold 4 5 6, one finger up | hold 6, one finger right from dot 1 or hold 6, one finger left from dot 1 |
| change typing echo | hold 4 5 6, 2 fingers up | hold 3, one finger left from dot 6 |
| dictation | hold 4 5 6, one finger down | 2 fingers up |
| home | — | hold 2, one finger left from dot 5 |
| end | — | hold 2, one finger right from dot 5 |
| tab | — | hold 3, one finger right from dot 4 |
| shift tab | — | hold 3, one finger left from dot 4 |

#### In editing mode

| Command | Like TalkBack (default) | Like ABK |
|---|---|---|
| switch to editing and back | — | one finger right from dot 3 |
| switch to emoji and back | — | one finger left from dot 5 |
| switch keyboard | — | 2 fingers left |
| space | — | one finger right from dot 4 or one finger right from dot 5 |
| new line | — | one finger left from dot 6 |
| send | — | 2 fingers right |
| delete character | — | one finger left from dot 4 |
| delete word | — | one finger left from dot 1 |
| undo | hold 4 5 6, one finger left or dots 1 3 5 6 | hold 6, one finger left from dot 3 |
| redo | hold 4 5 6, one finger right or dots 1 3 4 5 6 | hold 6, one finger right from dot 3 |
| cursor back | — | one finger left from dot 2 |
| cursor forward | — | one finger right from dot 2 |
| previous character | hold 6, one finger up | hold 1, one finger left from dot 4 |
| next character | hold 6, one finger down | hold 1, one finger right from dot 4 |
| previous word | hold 5, one finger up | hold 1, one finger left from dot 5 or hold 4, one finger left from dot 1 or dot 1 or dots 2 3 |
| next word | hold 5, one finger down | hold 1, one finger right from dot 5 or hold 4, one finger right from dot 1 or dot 4 or dots 5 6 |
| previous line | hold 4, one finger up | hold 2, one finger left from dot 4 or dots 1 4 |
| next line | hold 4, one finger down | hold 2, one finger right from dot 4 or dots 2 5 |
| start of text | hold 4 5, one finger up or dots 2 4 | hold 2, one finger left from dot 6 or dot 3 |
| end of text | hold 4 5, one finger down or dots 1 2 4 | hold 2, one finger right from dot 6 or dot 6 |
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
| select from mark | hold 4, 2 fingers right or dots 1 2 5 | hold 4, one finger right from dot 3 or dots 1 2 4 |
| cut | hold 4, 3 fingers up or dots 1 3 4 6 | hold 5, one finger left from dot 1 or dots 1 2 3 4 |
| copy | hold 4, 3 fingers down or dots 1 4 | hold 5, one finger right from dot 1 or dots 1 2 3 5 |
| paste | hold 4, 3 fingers right or dots 1 2 3 6 | hold 5, one finger left from dot 2 or dots 1 2 3 6 |
| read character | hold 6, one finger right | — |
| read character phonetically | hold 6, one finger left | — |
| read word | hold 5, one finger right | — |
| spell word | hold 5, one finger left | — |
| read line | hold 4, one finger right | one finger left from dot 3 |
| read whole field | hold 4, one finger left | hold 3, one finger right from dot 5 or hold 3, one finger left from dot 5 or hold 4, one finger right from dot 2 or dots 1 2 3 or dots 1 2 4 5 or dots 4 5 6 |
| read selection | 2 fingers up | hold 5, one finger right from dot 3 or dots 1 5 |
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
| fix or release keyboard position | hold 4 5 6, one finger up | hold 6, one finger right from dot 1 or hold 6, one finger left from dot 1 |
| change typing echo | hold 4 5 6, 2 fingers up | hold 3, one finger left from dot 6 |
| dictation | hold 4 5 6, one finger down | 2 fingers up |
| home | — | hold 2, one finger left from dot 5 or dots 1 2 |
| end | — | hold 2, one finger right from dot 5 or dots 4 5 |
| tab | — | hold 3, one finger right from dot 4 or dots 1 2 3 4 5 |
| shift tab | — | hold 3, one finger left from dot 4 or dots 1 2 4 5 6 |

#### In spelling mode

| Command | Like TalkBack (default) | Like ABK |
|---|---|---|
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

| Command | Like TalkBack (default) | Like ABK |
|---|---|---|
| up arrow | one finger up | one finger up |
| down arrow | one finger down | one finger down |
| left arrow | one finger left | one finger left |
| right arrow | one finger right | one finger right |
| home | hold 4, one finger left | hold 4, one finger left |
| end | hold 4, one finger right | hold 4, one finger right |
| page up | hold 4, one finger up | hold 4, one finger up |
| page down | hold 4, one finger down | hold 4, one finger down |
| control home | hold 4 5, one finger up | hold 4 5, one finger up |
| control end | hold 4 5, one finger down | hold 4 5, one finger down |
| tab | 2 fingers up | 2 fingers up |
| shift tab | hold 6, one finger up | hold 6, one finger up |
| enter | 2 fingers right | 2 fingers right |
| backspace | 2 fingers left | 2 fingers left |
| delete | hold 6, one finger right | hold 6, one finger right |
| escape | hold 6, one finger left | hold 6, one finger left |
| insert | hold 5 6, one finger down | hold 5 6, one finger down |
| caps lock | hold 6, one finger down | hold 6, one finger down |
| latch control | hold 5, one finger right | hold 5, one finger right |
| latch alt | hold 5, one finger left | hold 5, one finger left |
| latch shift | hold 5, one finger up | hold 5, one finger up |
| latch insert | hold 5 6, one finger right | hold 5 6, one finger right |
| latch caps lock | hold 5 6, one finger left | hold 5 6, one finger left |
| hold the latched modifiers | hold 5 6, one finger up | hold 5 6, one finger up |
| clear or release modifiers | hold 5, one finger down | hold 5, one finger down |

#### In emoji mode

| Command | Like TalkBack (default) | Like ABK |
|---|---|---|
| switch to emoji and back | — | one finger left from dot 5 |
| previous emoji | one finger left | one finger left |
| next emoji | one finger right | one finger right |
| previous emoji category | one finger up | one finger up |
| next emoji category | one finger down | one finger down |
| insert emoji | 2 fingers right | 2 fingers right |
| add or remove from favorites | 2 fingers up | 2 fingers up |
| clear search | 2 fingers left | 2 fingers left |

<!-- /gestures:en -->

It uses liblouis 3.39.0, unmodified, and its tables, under the LGPL 2.1 or later; the source is at [liblouis 3.39.0](https://github.com/liblouis/liblouis/releases/tag/v3.39.0). The TalkBack sound theme uses TalkBack's sounds, under the Apache License 2.0. The app lists every license under Help, Licenses.
