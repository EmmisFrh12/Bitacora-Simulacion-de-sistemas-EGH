# Bitacora-Simulacion-de-sistemas-EGH
Bitácora

Reto de diseño 1

https://editor.p5js.org/EmmisFrh12/full/xBItt387N

Crecimiento social
Se busca mostrar como las incertidubres influyen en la creación de sociedades mediante caminatas aleatorias, distribuciones probabilísticas y comportamientos influenciados por el usuario, los exploradores generan caminos y nuevos asentamientos que evolucionan de manera impredecible pero bajo ciertas reglas, creando diferentes tipos de asentamientos.

en este sistema, todas las direcciones de expansión son posibles, las tendencias son calculadas según las peregrinaciones generando un rumbo más especifico, la distribución gaussiana genera normalidad en las peregrinaciones las limitaciones de distancia y ciclo de vida de los exploradores hacen que la mayoría de las caminatas y calles se mantengan cerca de los valores habituales de la simulación cada asentamiento tiene una probabilidad especifica de nacer, una excepción en el sistema son las metropolis que apenas tienen el 2% de probabilidad de nacimiento. Finalmente el usuario puede ejercer su influencia en la rapidez y éxito de la peregrinación, afectando as su vez el nacimiento de nuevos exploradores, no le da control completo pero si influencia al acelerar el crecimiento de la sociedad.


Empecé pensando en un mapa de lineas de metro, rapidamente descarté el metro y me quedé solo con la idea del mapa, un mapa antiguo sobre civilizaciones nacientes así que comencé con el codigo del caminante y con IA se ajustó para que generara caminos con distintas direcciones.

<img width="675" height="529" alt="Captura de pantalla 2026-07-24 020500" src="https://github.com/user-attachments/assets/21d6078f-0288-4026-ba75-47635fe2182f" />

Luego decidí que los exploradores deberian nacer de asentamientos, asi que al ejecutar el código se generaria un asentamiento y de ahí saldrian los exploradores, tambien el usuario podria hacer click para generar un asentmaiento

<img width="802" height="662" alt="image" src="https://github.com/user-attachments/assets/df98713c-7b78-4c71-9e02-8f68cd3f5f47" />

Ahora los exploradores crearian nuevos asentamientos y de estos saldrian más exploradores para seguir expandiendo, tambien se agregaron los tipos de asentamientos y su respectiva probabilidad.

<img width="743" height="529" alt="image" src="https://github.com/user-attachments/assets/9e4825ba-fd7a-4d6a-b525-3de45ace2ad2" />

Ajuste de ciclo de vida de los exploradores y numero de exploradores por tipo de asentamiento

<img width="750" height="524" alt="image" src="https://github.com/user-attachments/assets/4393a0cc-f5da-4b69-86ca-023c3032adbb" />

finalmente modifiqué la interacción ya que era más dibujar directamente que modificar reglas, la IA sugirió terreno fertil que atrajera a los exploradores, pero pensé que seria mejor que ese terreno fertil aumentara la velocidad de expansión y la probabilidad de que el explorador que pasa termine estableciendo un asentamiento.

<img width="496" height="840" alt="image" src="https://github.com/user-attachments/assets/84bf9874-f05d-4cdc-b36b-a3b9448ae958" />




