## v5.5.500
- Corregido el patrón de velocidad instantánea válida seguido por varios segundos en cero provocado por el reinicio de gpsMotionStreak.
- El filtro GPS mantiene gpsMoving hasta 5 s sin evidencia suficiente y conserva la última velocidad durante huecos breves de precisión.
- Se conserva el umbral anti-deriva para evitar sumar desplazamientos GPS falsos en reposo.
- Se elimina la reindexación redundante de música al iniciar si musicLibrary ya fue cargada o si la restauración inicial ya está en curso.
- El reproductor usa autoplay/canplay y Media Session para mejorar continuidad entre canciones y recuperación desde segundo plano.
- Se refuerza la recuperación de voz y música al retornar de visibilitychange.

## v5.5.400
- Se redujo a la mitad el espacio entre contenidos y bordes inferiores de tarjetas de Inicio.
- Se redujo a la mitad el espacio vertical dentro de selectores y campos de métricas.
- El nombre de la fase del plan pasó de 21 px a 16,8 px.
- Los textos de Nutrición y Técnica usan 17 px, igual que la etiqueta Objetivo.
- Todos los cambios están limitados a #homeView.

## v5.5.300
- Bloqueo global de pull-to-refresh mediante CSS y control táctil.
- El controlador reconoce el contenedor desplazable activo, incluidos formularios dentro de diálogos.
- Sólo se bloquea el arrastre hacia abajo cuando el contenedor ya está en su límite superior.
- Los gestos horizontales y el scroll normal permanecen disponibles.

## v5.5.200
- El GPS permanece actualizado durante la pausa, pero no suma kilómetros ni desnivel.
- El tiempo de velocidad promedio incluye fases y transiciones, y excluye pausas.
- Se evita sumar al reanudar el desplazamiento efectuado durante la pausa.
- Los registros guardan el tiempo activo usado para calcular la velocidad promedio.

## v5.5.100
- El GPS requiere desplazamiento confirmado antes de sumar distancia o mostrar velocidad.
- La velocidad promedio ya no promedia lecturas GPS espurias.
- Se evita iniciar varias veces mientras Android autoriza o indexa la carpeta musical.
- La transición a Entrenamiento continúa automáticamente después de conceder permiso.
- La barra de progreso de Acumulado se desplazó visualmente hacia arriba sin alterar la grilla.

## v5.5.000
- Voz descriptiva reforzada durante bloqueo de pantalla y eliminación de frases repetidas.
- Reproducción manual de la descripción al tocar la tarjeta Etapa.
- Reproductor musical persistente con reintentos y vigilancia en períodos largos.
- Cronómetro monotónico sin pérdida de intervalos durante suspensiones.
- Eliminación de los modos demostración e inspección.
- Desnivel positivo calculado con altitud filtrada y suma exclusiva de ascensos.

## v5.4.900
- Se añadió «Tiempo total» como rótulo superpuesto, sin desplazar el cronómetro ni modificar la tarjeta Acumulado.
- Se aumentó un 20 % la tipografía de Km recorridos y Km/h promedio en la Vista de carrera.
- No se modificaron alturas, posiciones ni estructura de las tarjetas.

## v5.4.800
- Botón rojo con X junto a la fecha de cada registro.
- Confirmación antes de eliminar.
- Se elimina únicamente el registro seleccionado y se actualizan estadísticas y progreso.

## v5.4.700
- Se verificó que la ventana real es configDialog y que se abre con openConfig().
- Se añadió acceso a Configuración desde Preparar entrenamiento.
- Los cambios guardados antes de iniciar quedan almacenados y se aplican a la nueva sesión.

## v5.4.600
- El estado manual de pausa/reproducción de música se conserva al completar, avanzar o retroceder etapas.
- El doble toque continúa cambiando de canción sin anular la pausa global.
- Nuevo botón AUTO junto al valor RPM para borrar la configuración manual.

## v5.4.500
- Biblioteca musical por carpeta con persistencia mediante IndexedDB cuando Chrome/Android lo permiten.
- Reindexado manual, recuperación automática, estado de permiso y compatibilidad con tarjeta SD.
- Selección manual de archivos conservada como alternativa.

## v5.4.500
- Vista de conducción reconstruida sobre sus componentes reales.
- Velocidad instantánea +20 %, blanco puro y sombra suave.
- Distancia y promedio +35 %, apilados verticalmente y diferenciados por color.
- Encabezado dividido en nombre de etapa y metadatos.
- Barra de progreso de 12 px.
- Sin cambios funcionales ni visuales en las demás pantallas.

## v5.4.500
- Botones flotantes para etapa anterior y siguiente, centrados en la fila de velocidad.
- Las etapas omitidas manualmente no cuentan como completadas.
- Nueva vista de conducción por deslizamiento horizontal.
- Vista de máxima legibilidad con etapa, duración, cadencia, velocidad, distancia y promedio.
- Indicador de páginas entre ambas vistas.

## 5.4.500

- Mejoras de accesibilidad visual, locuciones y música automática por fase.
- Corrección de presentación de cadencia libre.

## v4.3.000
- Motor: actualización de locuciones.
- Intento de sincronización de cadencia por fase.


## v4.2.002
- Ajuste de locuciones: se elimina el prefijo 'Trabajo'.
- Texto de reserva cambiado a 'Cadencia libre'.

# CHANGELOG

## v4.2.001

- Corrige la conmutación entre GPS y modo demostración.
- Evita respuestas HTML incorrectas para recursos offline.
- Añade instalación PWA desde el aviso disponible.
- Añade Wake Lock durante el entrenamiento.
- Valida la estructura básica del plan al cargar.
- Mejora la representación de fases menores a un minuto.

## v4.2.000
- Integración con GPS del celular mediante Geolocation API.
- Cálculo de distancia, velocidad actual/promedio y desnivel positivo.
- Voz descriptiva y transición de 10 segundos antes de cada fase.
- Avisos sonoros durante los cinco segundos finales.
- Pulso de cadencia con RPM y volumen configurables.
- Controles independientes de audio en Configuración.
- Editor acumulativo de períodos de entrenamiento.
- Caché offline actualizada.

# Changelog

## v4.1.006
- Aumentadas un 20 % las etiquetas de los recuadros de Objetivos.
- Duplicada la separación entre etiquetas y valores de Objetivos sin alterar la altura de los recuadros.
- Duplicado el espacio entre el tiempo acumulado y la barra de progreso.
- Aumentadas un 25 % las etiquetas de las métricas acumuladas.
- Duplicada la separación entre etiquetas y valores acumulados sin alterar la altura de los recuadros.
- Actualizada la caché offline a v4.1.006.
- Corregida la entrega anterior, que conservaba código y metadatos de v4.1.005.

## v4.1.005
- Asignados fondos oscuros suaves y diferenciados a Objetivos, Etapa actual y Acumulado.
- Aumentados aproximadamente un 30 % los textos, etiquetas y valores de la tarjeta Objetivos.
- Reducido aproximadamente un 15 % el cronómetro de etapa.
- Aumentada la altura útil de los recuadros de velocidad instantánea y pulsaciones.
- Cambiado el título “Tiempo acumulado” por “Acumulado”.
- Compactados los espacios internos de la tarjeta Acumulado.
- Duplicada la separación visual entre tarjetas.
- Conservadas todas las funciones y datos de la v4.1.004.

## v4.1.004
- Tarjeta Objetivos compactada a aproximadamente 13 % de la altura útil.
- Eliminado el título semanal de la segunda línea de la tarjeta Objetivos.
- Recuadros de objetivos reducidos en altura.
- Textos y valores de Etapa actual y Valores acumulados ampliados para mejorar su lectura durante la marcha.
- Espacios verticales entre encabezados, cronómetros y barras de progreso reducidos.
- El espacio recuperado se asignó a Valores acumulados.
- Botonera inferior reducida aproximadamente un 25 %.
- Modo demostración activado por defecto en instalaciones nuevas, con valores de ejemplo desde el inicio.
- Añadido Modo inspección opcional con alturas y tamaños reales de la pantalla.
- Corregida una referencia a un elemento eliminado que podía interrumpir el inicio del entrenamiento.

## v4.1.003
- Primera pantalla Entrenamiento en curso y motor básico por etapas.
- Cronómetros, progreso, pausa, finalización, configuración y simulación de métricas.

## v4.1.002
- Refinamientos de interfaz, nutrición semanal resuelta y persistencia de selección.

## 5.4.500
- Nuevo resumen de progreso del plan de 48 semanas con gráfico tipo dona.
- Historial de entrenamientos guardados con comparación entre objetivos y valores registrados.
- Nuevo diálogo de finalización con Cancelar, Guardar y Salir sin guardar.
- Configuración de hasta tres temas preferidos dentro de Editar período.
- Continuidad musical independiente para bloques repetidos de trabajo y recuperación.
- Reproducción automática de nuevas pistas compatibles en etapas largas, evitando repeticiones hasta agotar la biblioteca.
- Ajustes visuales de velocidad instantánea y kilómetros recorridos.
