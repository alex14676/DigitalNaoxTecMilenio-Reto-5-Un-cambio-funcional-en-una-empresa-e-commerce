# DigitalNaoxTecMilenio-Reto-5-Un-cambio-funcional-en-una-empresa-e-commerce
Un cambio funcional en una empresa e-commerce

Evidencia

Un cambio funcional en una empresa e-commerce

Actividad

Ernesto Herrera es un empresario joven que incursionó en el e-commerce, desde hace ya 3 años, el desarrollo de su empresa ha ido bastante bien, con crecimiento constante, de acuerdo a su experiencia, Ernesto, considera que todos los negocios con base en las tecnologías deben mantenerse en vanguardia. 
Por lo anterior Ernesto está en búsqueda constante de herramientas tecnológicas que le permitan ofrecer un servicio plus a sus clientes y ha decidido implementar un panel de administración para su tienda on line, con el objetivo adicional de eficientar costos y tiempos, por lo que contactó a SoftSolutions para que desarrollen su proyecto.
SoftSolutions es una empresa líder en la creación, diseño, despliegue y compatibilidad de herramientas tecnológicas, caracterizada por brindar a sus clientes, productos totalmente personalizados y adecuados a sus necesidades. Han aceptado desarrollar el proyecto de Ernesto, y asignar como líder del mismo a David López, experto en desarrollo de software, quien ha formado parte de la empresa desde hace 8 años, cuyas habilidades comunicativas, le han traído bastantes éxitos en el desarrollo, presentación y finalización de los proyectos.
En la reunión, Ernesto, queda bastante impresionado por la forma en que David se desenvuelve, y considera que es una persona muy profesional, a pesar de acabar de conocerlo, por lo que rápidamente genera confianza en él y le externa que estaría dispuesto a invertir en el proyecto, dada la importancia que tiene para su empresa la concreción exitosa de la aplicación, por lo que esa es justamente la única condición, que el prototipo presentado sea funcional.
Una vez finalizada la reunión, David, haciendo gala de su habilidad para gestionar el tiempo y eficientar los procesos, rápidamente elabora un Gantt, y toma la decisión de asignar a Sara, quien forma parte de su equipo de trabajo desde hace 2 años, es una colaboradora muy joven que tiene talento en el desarrollo y maquetación Web.
David confía plenamente en Sara por su dinamismo y flexibilidad y decide no perder tiempo para pedirle que lo apoye en el desarrollo del producto, ya que solo disponen de tres días para construir y presentar el prototipo. Asomándose por la puerta de su oficina, alza el brazo para indicarle a Sara que se aproxime.

—Hola Sara, buenos días.

—Buenos días David, dime que hay buenas noticias—comenta esbozando una gran sonrisa.

—Me alegra ver tu entusiasmo y efectivamente hay buenas noticias. Sara, te presento el trabajo que vamos a desarrollar los próximos tres días, es un proyecto que implica el diseño y desarrollo de un panel de administración para una tienda e-commerce, el cliente es bastante exigente con la funcionalidad.

—¡Hey! Por eso me gusta trabajar contigo, siempre el reto por delante, justamente tengo algunas ideas que quería plantearte y me parece que será el proyecto adecuado, aunque tres días, ¡wow!, estaremos súper ocupados.

—Así es Sara, pero ya sabes lo que dicen, el tiempo es oro, afortunadamente, tu y yo ya hemos hecho sinergia en los proyectos anteriores y sé que en esta ocasión tendremos éxito nuevamente, además, siempre me gustan tus propuestas, con gusto te escucho, acompáñame para comentarte los pormenores. Mira Sara, te comento los detalles, el panel lateral (SideBar) debe contener una lista de todas las secciones, que permita navegar entre ellas. Aún están por establecerse algunos componentes pero dejaremos una sección principal para colocarlos después, entre ellos, habrá un gráfico que demuestra el número total de clientes y uno que demuestre el total de las ventas de la campaña actual.

—De acuerdo David, y me gustaría proponer un recurso gráfico que muestre los productos más vendidos y el listado de ventas recientes; además como es e-commerce será de gran ayuda para el cliente incluir un gráfico tipo mapa que demuestra de qué países vienen las ventas.

—Por supuesto, además no debemos perder de vista al usuario de la aplicación, incluiremos un formulario para crear nuevas cuentas para esos usuarios. Sara, ¿te parece si, con estos elementos iniciales comenzamos con el diseño?

—Claro que sí, comenzaré y nos reunimos hoy más tarde para ver los avances.

Ya en la soledad de su oficina, Sara repasa rápidamente su check lista mental de las acciones que le ayudarán a realizar el diseño inicial de forma rápida, por lo que garabatea en su cuaderno creativo algunas ideas; para iniciar decide utilizar una plantilla Figma para diseñar el dashboard, ya que es más fácil modificar un archivo de diseño en lugar de modificar el código.
Sara, además, es experta en CSS, por lo que también incluirá una librería CSS moderna, Tailwind CSS, para desarrollar el diseño inicial sin funcionalidad de la aplicación, lo más rápido posible.

—Son demasiados pendientes, será mejor anotarlos para no perderme, bien, número uno, verificar la instalación de React, Tailwind CSS y Daisy UI. OK, en las secciones voy a incluir como propuesta una para ver los recibos de todas las ventas y poder filtrarlas usando diferentes parámetros, y para darle una vista de cada sección en versión grande completa.

Para Sara es muy importante esbozar el primer diseño, es decir, crear la Ficha de Diseño de página, ya que al utilizar el código con Figma, la estructura y el diseño son muy importantes para darle funcionalidad, además de incluir los nombres de las diferentes secciones.
Son las tres en punto y Sara ha terminado el diseño inicial de la aplicación, pero aún le falta comprobar la funcionalidad. Se ha vuelto a reunir con David, para la revisión de avances y se percatan de que deben revisar otras librerías a la aplicación, Sara propone Formik y Yup para ayudar a crear formularios eficientes, y también la librería Nivo Charts que le ayudará a mostrar los datos de la API. Acuerdan encontrarse a primera hora para delimitar los pendientes.
Al día siguiente, como cada día de trabajo David llega puntualmente a la oficina, y para su sorpresa se encuentra con Sara en la sala de espera de su piso, la saluda cordialmente. Se siente aliviado de poder comenzar inmediatamente con la revisión de pendientes para poner manos a la obra.

—¡Hola, Sara! comencemos para no perder tiempo, ¿te parece?

—Buenos días, David, por supuesto, ayer añadí algunas bibliotecas, las vamos a utilizar para el formulario de nuevo usuario.

—¡Ah!, muy bien, hoy voy a trabajar en la habilitación de Redux, ¿cómo vas con el enrutamiento al SidePanel?

—Bien, solo me hace falta probar la navegación entre las distintas secciones. También te comento que decidí utilizar Fetch para obtener y guardar datos utilizando React Hooks, para que además, se muestren en varios gráficos en la aplicación web.

—Perfecto, realizaremos las primeras pruebas alrededor de medio día, recuerda que de acuerdo al plan de actividades que te plantee inicialmente, mañana nos concentraremos en realizar las pruebas de funcionalidad. Aún nos faltan varios detalles, hagamos lo posible por realizar la primera prueba el día de hoy, también vamos a distribuir las tareas restantes para que no te satures y lo logremos.

—¡Sí, por supuesto!, para las primeras pruebas crearé un mock API para similar data en el app usando JSON Server.

—Bien, entonces a medio día tendré listo el Insomnia y correremos Nivo Charts para verificar la parte gráfica.

Conforme a lo acordado, realizaron las primeras pruebas, que resultaron buenas, aunque David le comenta a Sara que deben mejorar la vista general de los datos, y reducir la cantidad de información que se muestra al usuario, podría paginar los datos para mejorar el manejo de los mismos.
Aunque ha sido un trabajo muy detallado, David se alegra de haber confiado en Sara para este proyecto, ya que su proactividad le permite proponer y solucionar los inconvenientes a tiempo. Solo falta un día más para realizar la entrega del prototipo y han avanzado conforme a lo planeado.

—Sin duda lo lograremos, si seguimos coordinados, mañana realizaremos las últimas pruebas, justo a tiempo. Sara es un gran elemento cuando se trata de trabajar bajo presión, comenta David para sí mismo, y tratando de tranquilizar sus pensamientos.

Al tercer día y último del proyecto, el prototipo está totalmente funcional y tiene muy buen aspecto. Sin embargo, David no está seguro si está funcionando como se pretendía, por ello, decide realizar algunas pruebas utilizando React Testing Library y Cypress para pruebas E2E. No les queda mucho tiempo ya que tienen que reunirse con el cliente esa misma tarde.
Sara termina aún con algunos detalles, busca una solución de alojamiento rápida y fácil para el prototipo y desplegar el código tan pronto como pase las pruebas requeridas. Decide usar Netlify como una solución rápida.
Después de unas horas de trabajo intenso, el equipo de SoftSolutions finalmente tiene el prototipo completamente probado y listo para presentar al cliente. David, con la ayuda de Sara, ha logrado implementar todas las funcionalidades requeridas, la aplicación se ve bien y funciona de manera fluida.
Ambos están emocionados de presentar su trabajo al cliente y explicarle las características de la solución que han creado. David y Sara están confiados en su capacidad para obtener una respuesta positiva del clientey están entusiasmados por lo que el futuro puede depararles.
Al presentar el prototipo al licenciado Herrera, éste se muestra muy contento con la presentación y considera que la reunión es exitosa, ya que está muy conforme con el prototipo funcional que SoftSolutions ha creado.
Impresionado por la habilidad del equipo para satisfacer sus necesidades y presentar una propuesta de alta calidad, el licenciado Herrera está decidido a trabajar con este equipo en el futuro para llevar su tienda en línea al siguiente nivel.
