# Errores y soluciones

Esta sección recopila errores, problemas de rendimiento y posibles soluciones al ejecutar el port nativo de Uncharted en Windows.

**Importante:** las soluciones marcadas como posibles todavía necesitan comprobarse. Se irán actualizando a medida que se realicen más pruebas.

## 1. El juego no inicia

**Síntoma:** al ejecutar `Uncharted.exe`, el juego no abre, se cierra o muestra un mensaje de error.

**Posibles causas:**
- Se seleccionó una carpeta incorrecta.
- Faltan archivos del juego o la extracción no terminó correctamente.
- El equipo no cumple con algún requisito del port.
- Existe un problema de compatibilidad o configuración.

**Qué comprobar:**
1. Verificá que seleccionaste la carpeta correcta.
2. Comprobá que los archivos necesarios estén presentes.
3. Anotá el mensaje de error exacto.
4. Si el error aparece en una consola o un registro, guardá el texto para poder analizarlo.

**Estado:** pendiente de recopilar casos y soluciones comprobadas.

## 2. Error `ErrorOutOfDeviceMemory`

**Síntoma:** el programa muestra un error relacionado con la falta de memoria del dispositivo gráfico.

**Posibles causas:**
- Memoria gráfica disponible insuficiente.
- Consumo elevado de memoria por el juego o el controlador gráfico.
- Algún problema de compatibilidad con el hardware o la configuración.

**Qué probar:**
1. Cerrá los programas que no estés utilizando.
2. Reducí la resolución y los ajustes gráficos.
3. Comprobá si el error vuelve a aparecer.
4. Guardá el registro completo del error para identificar su origen.

**Estado:** pendiente de confirmar una solución específica para este port.

## 3. Rendimiento bajo o FPS inestables

**Síntoma:** el juego funciona con pocos fotogramas por segundo (FPS), presenta tirones o tiene un rendimiento irregular.

**Posibles causas:**
- La GPU está trabajando cerca de su capacidad máxima.
- La resolución o los efectos gráficos son demasiado exigentes.
- Existen diferencias de rendimiento entre el juego y las cinemáticas.

**Qué registrar:**
- Procesador.
- GPU.
- Memoria RAM.
- Resolución utilizada.
- Configuración gráfica.
- FPS durante el juego y durante las cinemáticas.
- Temperaturas y porcentaje de uso de CPU y GPU.

Consultar `PRUEBAS.md` para ver las configuraciones y los resultados registrados.

## 4. El juego se cierra al cargar una partida o un nivel

**Síntoma:** el juego abre, pero se cierra durante la carga o al comenzar a jugar.

**Qué comprobar:**
1. Anotá en qué momento ocurre.
2. Comprobá si sucede siempre en el mismo punto.
3. Guardá el mensaje de error o el registro correspondiente.
4. Probá nuevamente sin cambiar varios ajustes al mismo tiempo.

**Estado:** pendiente de investigar.

## Cómo informar un error

Si encontrás un problema, intentá registrar:

- **Juego:** Uncharted 1, Uncharted 2 o Uncharted 3.
- **Error exacto:** mensaje completo o captura.
- **Hardware:** procesador, GPU y RAM.
- **Momento:** al iniciar, cargar una partida, jugar o ver una cinemática.
- **Qué intentaste:** cambios realizados y resultado.

No todas las soluciones funcionan en todos los equipos. La idea es registrar resultados reproducibles y evitar presentar suposiciones como soluciones definitivas.
