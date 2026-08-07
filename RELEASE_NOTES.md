# Río Pinto Coach v5.5.500

- GPS: el estado de movimiento permanece confirmado mientras la bicicleta continúa desplazándose; una lectura aislada no lleva inmediatamente la velocidad a cero.
- GPS: la velocidad instantánea se suaviza y se mantiene brevemente durante muestras de desplazamiento menores al umbral de precisión.
- Música: Iniciar entrenamiento ya no reindexa la carpeta cuando la biblioteca ya está disponible.
- Música: se reforzó el encadenamiento de pistas con autoplay del mismo elemento de audio, evento canplay y Media Session.
- Voz/música: al volver desde segundo plano se intenta recuperar inmediatamente la reproducción y la locución pendiente.

# Río Pinto Coach v5.5.400

- Pantalla Inicio más compacta, conservando el estilo actual.
- Reducción del 50 % de los espacios verticales internos indicados.
- Título de la fase del plan reducido un 20 %.
- Textos de Nutrición y Técnica igualados al tamaño de «Objetivo».

# Río Pinto Coach v5.5.300

- Se deshabilitó globalmente el gesto de actualización por arrastre descendente.
- La protección comprende Inicio, Preparar, Entrenamiento, Vista Ciclista, Configuración, Estadísticas y demás diálogos.
- Se conservan el desplazamiento interno y el gesto horizontal entre vistas de entrenamiento.

# Río Pinto Coach v5.5.200

- La distancia y el desnivel no se acumulan durante pausas manuales.
- Las transiciones siguen contabilizando tiempo y distancia.
- La velocidad promedio usa distancia de etapas y transiciones dividida por su tiempo activo, excluyendo pausas.
- Al reanudar, la siguiente posición GPS se toma como nueva referencia.

# Río Pinto Coach v5.5.100

- Filtro GPS de inmovilidad para evitar velocidad y distancia por deriva.
- Velocidad promedio calculada como distancia total dividida por tiempo total.
- Inicio de entrenamiento de una sola pulsación con estado visible durante autorización e indexado musical.
- Barra de progreso de Acumulado elevada sin mover los demás elementos.

# Río Pinto Coach v5.5.000
- Mejoras de continuidad de voz, música, cronometraje y cálculo de desnivel positivo.

# Río Pinto Coach v5.4.900

- Nuevo título «Tiempo total» dentro del espacio libre de la tarjeta Acumulado.
- Aumento del 20 % de títulos, valores y unidades de Km recorridos y Km/h promedio en Vista de carrera.
- Se preservan alturas, posiciones, grillas y distribución de las tarjetas.

# Río Pinto Coach v5.4.800

- Eliminación individual de registros guardados desde Estadísticas.
- Confirmación obligatoria antes de borrar.
- Recalculo automático del progreso del plan.

# Río Pinto Coach v5.4.700

- Nuevo botón CONFIGURACIÓN al final de Preparar entrenamiento, antes de INICIAR ENTRENAMIENTO.
- El acceso reutiliza el diálogo real configDialog y la función openConfig().

# Río Pinto Coach v5.4.600

- Pausa y reanudación musical persistente durante toda la sesión, incluso al cambiar de etapa.
- Botón AUTO junto al campo RPM para restablecer la cadencia automática sin usar el teclado.

# Río Pinto Coach v5.4.500

- Restaura y autoriza la carpeta musical al iniciar un entrenamiento para comenzar la reproducción automáticamente.
- El valor RPM configurado activa el pulso también en etapas de cadencia libre cuando el control está habilitado.
- Conserva la última posición GPS válida y recupera el seguimiento al volver de pantalla bloqueada o inactividad.
- Añade vigilancia del GPS y reacquisición automática del bloqueo de pantalla.
- Sustituye la cuenta regresiva por cinco avisos de cambio diferenciados en tono y duración.

# Río Pinto Coach 5.4.500

Esta versión incorpora seguimiento del progreso, historial de sesiones, guardado opcional al finalizar y música contextual configurable por período. En bloques repetitivos, las pistas de trabajo y recuperación conservan su posición entre repeticiones.
