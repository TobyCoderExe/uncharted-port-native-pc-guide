# Instalación

[Volver al README](README.md)

### Antes de empezar

Esta guía documenta mi experiencia con el port comunitario de *Uncharted: The Nathan Drake Collection* en Windows.

**Proyecto original:** [Supermedo/uncharted_pc](https://github.com/Supermedo/uncharted_pc)

Antes de instalarlo:

1. Lee el README y las instrucciones de la versión del port que vas a utilizar.
2. Comprueba los requisitos de Windows, GPU, Vulkan y memoria indicados por el proyecto.
3. Asegúrate de disponer de los archivos del juego que tengas derecho a utilizar.
4. Anota la versión del port y las especificaciones de tu PC.

# Instalación de Uncharted en el port nativo para PC

Esta guía explica cómo preparar los archivos del juego y ejecutarlos mediante el port nativo de Windows.

## Requisitos

- Una PC con Windows 10 u 11.
- El port nativo de Uncharted para Windows.
- ShadPS4Plus PKG Extractor.
- Un paquete del juego que tengas derecho a utilizar. (.pkg)
- Espacio suficiente en el disco para extraer los archivos. Tené en cuenta que el paquete original puede ocupar aproximadamente 40 GB y que la extracción requiere espacio adicional.

## Paso 1: Descargar el extractor

Descargá ShadPS4Plus PKG Extractor desde su [repositorio oficial](https://github.com/AzaharPlus/shadPS4Plus/releases).

Se recomienda utilizar una versión reciente, ya que versiones anteriores tuvieron problemas al extraer determinados paquetes grandes.

**Importante:** ShadPS4Plus se utiliza únicamente para extraer los archivos. No es el programa que ejecuta el juego en este procedimiento.

## Paso 2: Extraer el archivo PKG

1. Localizá el archivo PKG del juego en tu PC.
2. Arrastrá el archivo PKG sobre el ejecutable del extractor, si la versión descargada admite esta función.
3. Se abrirá una ventana de CMD (símbolo del sistema) y comenzará el proceso de extracción.
4. Esperá hasta que finalice. No cierres la ventana mientras esté trabajando.
5. Al terminar, localizá la carpeta que contiene los archivos extraídos.

La extracción puede tardar bastante, dependiendo del tamaño del paquete, la velocidad del disco y el rendimiento de la PC.

## Paso 3: Comprobar los archivos extraídos

Antes de continuar, verificá que la carpeta generada contenga los archivos y directorios que necesita el port. Entre los nombres que pueden aparecer están:

- `eboot.bin`
- `big2-ps4_Shipping.elf`
- `big3-ps4_Shipping.elf`
- `sce_sys`
- `u1data`
- `u2data`
- `u3data`

Los archivos exactos pueden variar según el juego. Si faltan archivos, la extracción muestra errores o el port no reconoce la carpeta, revisá el resultado antes de seguir.

## Paso 4: Descargar y preparar el port

1. Entrá al [repositorio oficial del port nativo de Uncharted para PC](https://github.com/Supermedo/uncharted_pc).
2. Descargá una versión disponible desde la sección de lanzamientos, si corresponde.
3. Extraé el contenido descargado en una carpeta de tu PC.
4. Ejecutá `Uncharted.exe`.

## Paso 5: Seleccionar la carpeta del juego

1. Cuando se abra el programa, Tenes que ir al apartado "Game".
2. luego seleccionar el "Game Folder" en el cual deberíamos seleccionar la carpeta que contiene el archivo que nos devolvió el ShadPs4Plus.
3. Vuelve al apartado "Play" y selecciona el que quieras jugar.
4. Listo.

Si todo está correctamente preparado, el port debería intentar iniciar el juego.

## Solución de problemas

Si el juego no aparece, el programa no reconoce la carpeta o se cierra al iniciarlo:

- Comprobá que seleccionaste la carpeta correcta.
- Verificá que la extracción haya finalizado sin errores.
- Revisá que estén presentes los archivos requeridos.
- Consultá el archivo `ERRORES.md` de este repositorio para ver posibles soluciones.

## Aclaraciones

Este proyecto documenta el uso del port nativo y la preparación de archivos. No distribuye juegos, paquetes PKG ni archivos protegidos por derechos de autor.

Los nombres de los archivos y los pasos de la interfaz pueden cambiar según la versión del extractor o del port.
