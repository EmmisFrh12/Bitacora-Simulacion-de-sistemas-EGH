
https://emmisfrh12.github.io/Visualizer/

Mapa del sistema:

<img width="588" height="472" alt="image" src="https://github.com/user-attachments/assets/c35b2531-9982-43ae-b54d-ee67c224e4cb" />

2. Ficha de Fuerzas

El instrumento combina tres fuerzas centrales que actúan simultáneamente sobre cada partícula para generar un campo vectorial dinámico.

A. Atracción / Repulsión Multi-Foco
Descripción direccional: Fuerza central que atrae o repele las partículas en dirección a 8 puntos focales repartidos por el espacio 3D. 
La fuerza se intensifica a medida que la partícula se acerca al foco y pierde efecto al alejarse.

Parámetros:

radialStrength: Controla la magnitud y dirección (positivo = atrae, negativo = repele).

attractors[0..7]: Posiciones fijas o aleatorias de los 8 focos en el espacio.

softening: Distancia mínima de amortiguación para evitar que las partículas salgan disparadas al pasar muy cerca del centro.

Predicciones:

Magnitud positiva: Las partículas colapsan en 8 enjambres o nubes hiperdensas alrededor de los focos.

Magnitud negativa: Los focos actúan como repulsores, creando "burbujas" o huecos vacíos en la masa de partículas.

Decisiones de diseño: Usar 8 focos dispersos en lugar de uno solo permite fracturar la masa visual en múltiples núcleos durante los 
momentos de tensión de LesAlpx, imitando la multiplicidad de capas del sintetizador.

B. Campo de Vórtice Perpendicular

Descripción direccional: Fuerza tangencial que empuja las partículas de manera perpendicular a la línea que las une con el foco primario. 
Induce un giro circular o en espiral alrededor del centro.

Parámetros:

vortexStrength: Magnitud de la rotación (positivo = giro en un sentido, negativo = giro inverso).

vortexEnabled: Interruptor de activación del campo rotacional.

Predicciones:

Transforma el colapso lineal directo hacia los focos en órbitas fluidas y remolinos, generando una estructura similar a una galaxia en 
rotación.

Decisiones de diseño: Es el control clave para traducir el arpegiador rítmico continuo de la pieza. Evita que las partículas se queden 
estáticas en los focos y les otorga sustentación y movimiento orbital.

C. Amortiguamiento / Drag Fluidodinámico

Descripción direccional: Fuerza de fricción opuesta a la dirección actual de movimiento de cada partícula. Acts como un freno natural 
proporcional a la velocidad.

Parámetros:

dragCoefficient: Nivel de resistencia del medio (valores altos = medio viscoso/freno rápido; valores bajos = medio sin fricción/inercia alta).

Predicciones:

Drag alto: Las partículas frenan casi al instante al retirar otras fuerzas, dejando trazos rígidos o filamentos estáticos.

Drag bajo: Las partículas conservan su viada e inercia, realizando órbitas largas y cruzando todo el volumen antes de detenerse.

Decisiones de diseño: Permite regular la "memoria" del sistema. Un drag bajo genera caos acumulativo en los momentos de clímax, mientras que 
un drag alto permite "cristalizar" la masa visual en los cortes de batería o en la resolución final de la canción.

Plan de interpretación

El plan de interpretacion para LesAlpx arranca de 0:00 a 1:15 en un reposo azul cobalto de bajo drag; evoluciona de 1:15 a 2:30 introduciendo viento con Q/E y vortice con A/D para orquestar espirales moradas al ritmo del arpegiador; alcanza su climax de 2:30 a 4:00 con traccion radial maxima con W, baja friccion con Z y particulas ampliadas con F que encienden el espacio en rojo carmesi; de 4:00 a 4:45 destruye su nucleo en una dispersion por repulsion subita con S durante el corte ritmico; y de 4:45 al final concluye con un reinicio con R y alto amortiguamiento con X que cristaliza la masa en el silencio final.

BITACORA

Usando el codigo de base, quise eliminar la influencia del ratón para simplemente controlar el instrumento desde el teclado y no tener que estar moviendo el mouse, luego aumenté los puntos focales para espaciar y aumentar el impacto de los gestos, luego modifiqué el espaciado de los focos entre sí para llenar la pantalla
luego se implementaron más fuerzas aparte de la atracción, vortice, viento y repulsión, en las teclas "wasdqe"
y finalmente se añadió el control para aumentar y disminuir el número de particulas.

AUTOEVALUACIÓN

Trazabilidad y comprensión del sistema	25	Puedo señalar y explicar estado, fuerzas, integración, render y controles; además puedo ubicar qué partes produjo o modificó la IA. 5

Verificación del algoritmo de fuerzas	25	Estudié en detalle el proyecto y aunque no comprenda toda la sintaxis, puedo identificar su arquitectura, sus partes, puedo aislar una fuerza central, formular una predicción, la ejecuté ya analicé, comparé el resultado, cambié deliberadamente un signo o parámetro y expliqué la diferencia. 5

Diseño de fuerzas e intención	20	Las fuerzas y sus parámetros hacen perceptible una intención; el comportamiento surge de la dinámica y no de trayectorias previamente dibujadas. 5

Instrumento, score e interpretación	15	El score conecta la escucha con decisiones; escogí pocos controles expresivos y puedo conducir el sistema en vivo sin que el audio lo controle automáticamente. 5

Experimentación y criterio frente a la IA	10	Comparé alternativas, registré hallazgos y descartes, corregí propuestas de IA y puedo justificar por qué conservé la versión presentada. 5

Entrega técnica y documentación	5	la URL pública abre; la bitácora permite verificar el proceso. 5



