Reto de diseño 2

Tensión. 
Quiero explorar la tensión entre proliferación de civilizaciones y la disrupción predatoria que genera dispersión.

Espero que el sistema manifieste ciclos continuos donde las poblaciones Representadas por particulas verdes se agrupen apretadamente alrededor de Líderes respresentados por particulas amarillas,
formando Sociedaes estables que parecen proliferar, hasta que la llegada de una población predadora como saqueadores representados por las particulas rojas rompa la cohesión desde dentro,
obligando a la estructura a fragmentarse caóticamente hasta colapsar, para luego reiniciar el ciclo de reconstrucción o asimilación en otra sociedad adyacente.

quise tener una población de 840 para que hubiese una abundancia de población y proliferacion de sociedades grandes y pequeñas, 144 líderes pocos a comparación de la población para que la población no se disperse
mucho pero suficientes para que no se haga solo una sociedad y 216 predadores para que no abrumen al completo a las sociedades si no que apenas suficientes para quebrarlas y obligarlas a reorganizarse

una atracción media entre la población, para simbolizar la necesidad de sociedad
una alta atracción de la población al nucleo para hacer visible como los líderes comandan y organizan la población
los predadores son altamente atraidos por la población y moderadamente ante los líderes, mostrando su agresivida ante los debiles y el deseo menor de atacar oponentes más fuertes
repulsión alta de la población ante los predadores para mostrar pánico y huida ante peligro

un radio de interacción de 12px como rango de visión entre particulas, prevención de las poblaciónes y encuentro con objetivo de los predadores

Se seleccionó un coeficiente de fricción alto (0.85) para simular un medio denso y viscoso que requiera un esfuerzo constante para el movimiento. Esto hace perceptible la estabilidad de las sociedades cuando están 
en equilibrio. En contraste, se estableció una velocidad máxima extremadamente alta para los Predadores 9.0 px/frame frente a la baja velocidad de los Líderes 2.5 px/frame. Esta diferencia hace 
perceptible la agilidad superior del disruptor frente a la inercia de la masa colectiva, esperando que produzca persecuciones rápidas que fuercen la dispersión caótica de los Constructores.

Se seleccionó una distribución inicial aleatoria uniforme para hacer perceptible que el orden emergente del sistema "las sociedades" surgen únicamente de las leyes físicas de interacción y no de una pre-organización 
impuesta, esperando resultados variados en cada ejecución. Visualmente, se eligió un punto para los individuos de la población, un punto gordo para los líderes y un triangulo orientado según el movimiento para los 
Predadores para hacer perceptible su intencionalidad y dirección de ataque.


Proceso

Empecé con la generación de código solo para los líderes y la población

<img width="924" height="774" alt="Captura de pantalla 2026-08-05 021111" src="https://github.com/user-attachments/assets/c65548d8-0592-4932-bee6-8c3d702679de" />

tuve problemas de optimización al intentar crear lazos entre población por lo que terminé descartando la idea

<img width="1859" height="839" alt="Captura de pantalla 2026-08-05 012824" src="https://github.com/user-attachments/assets/01d6be8d-b13b-4a71-82d1-f7a598316638" />

luego se añadieron los predadores y se ajustaron la atracción y repulsión de los líderes y población

<img width="914" height="772" alt="Captura de pantalla 2026-08-03 234514" src="https://github.com/user-attachments/assets/ab1b6e52-f17f-4036-880b-c9508445a471" />

añadí la matriz con interactividad para que diera un pequeño elemento de experimentación

<img width="953" height="797" alt="Captura de pantalla 2026-08-04 132636" src="https://github.com/user-attachments/assets/e6905b8e-f1ef-4705-8145-96d57e3e99b6" />




