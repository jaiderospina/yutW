# yutW
Procedimiento para desarrollar los requisitos de un sistema software que satisfaga las necesidades de negocio
PROC-0020 (PROCEDIMIENTO)
Área: Desarrollo de requisitos de un sistema que satisfaga las necesidades de negocio
Carácter del procedimiento: Obligatorio
El objetivo principal de esta actividad es desarrollar una propuesta de sistema software como solución a las necesidades de negocio de clientes y usuarios, haciéndolo con la mayor calidad posible e intentando asegurar que coincide con las expectativas de clientes y usuarios.

Los ingenieros de requisitos deben elaborar la propuesta en forma de requisitos del sistema software a desarrollar (product requirements en terminología CMMI-DEV), usando como entrada la información que se va generando en el procedimiento Identificar las necesidades de negocio de clientes y usuarios. Lo habitual es comenzar por los aspectos más generales del sistema (su visión general), para ir avanzando en el nivel de detalle hasta que se considere suficiente como para que pueda continuarse el desarrollo sin tener que plantear preguntas continuas sobre la conducta del sistema a desarrollar.

Durante esta actividad es frecuente que en cualquier momento se identifiquen y registren diversos tipos de problemas en los requisitos, cuya solución debe gestionarse por la actividad de Gestionar los problemas en los requisitos dentro del procedimiento Gestionar los requisitos del sistema software a desarrollar.

Flujo de actividades
Imagen para representar el flujo de actividades
Detalle de las actividades
Desarrollar la visión general del sistema
Documentar los requisitos del sistema
Analizar los requisitos del sistema
Verificar la calidad de los requisitos del sistema
Validar los requisitos del sistema
Registrar problemas en los requisitos
Registrar la trazabilidad de los requisitos
Título	
Desarrollar la visión general del sistema
Descripción	
Su objetivo principal es comenzar a definir el sistema software (la solución) que satisfaga las necesidades de negocio de clientes y usuarios (el problema). Para ello, se definen los requisitos generales y se comienzan a especificar los casos de uso del sistema en su versión inicial. Conforme avance el proceso de ingeniería de requisitos, los requisitos generales se irán detallando en requisitos más específicos y los casos de uso que se considere oportuno irán evolucionando hacia su forma detallada.

Riesgos de no efectuar la actividad:

Esta tarea es esencial para el desarrollo de un sistema software, por lo que no se contempla la posibilidad de no realizarla.
Tareas	
Tareas:

Realizar un estudio de las situación inicial
Obtener los requisitos generales del subsistema
Definir los casos de uso del sistema
Técnicas:

Las principales técnicas que se suelen emplear para la realización de esta tarea son:

Especificación de requisitos (usando la plantilla para requisitos generales propuesta en MADEJA).
Especificación de casos de uso (usando la plantilla simplificada para casos de uso propuesta en MADEJA).
Responsable	
Tarea1, Director del Proyecto
Tarea2, Director del Proyecto
Tarea3, Director del Proyecto

Productos	
Entrada:

Pliego de Prescripciones Técnicas del proyecto, si existe. Puede contener información relevante sobre la visión general del sistema.
Oferta Seleccionada del proyecto, si existe. Puede contener información relevante sobre la visión general del sistema.
Estudio de Viabilidad del Sistema, si existe. Debe contener información relevante sobre la visión general del sistema.
Objetivos de negocio, que deben guiar el desarrollo de la visión general del sistema.
Modelo de negocio a implantar, que, junto con los objetivos de negocio, debe guiar el desarrollo de la visión general del sistema.
Salida:

Requisitos generales del sistema, principal producto resultante de esta tarea junto con la versión inicial de los casos de uso. Deben especificar las características principales del sistema a desarrollar.
Casos de uso del sistema (versión inicial), principal producto resultante de esta tarea junto con los requisitos generales. Deben comenzar a especificar cómo utilizarán los usuarios el futuro sistema a desarrollar para realizar sus tareas dentro de los procesos de negocio de la organización.
Volver al índice
Título	
Documentar los requisitos del sistema
Descripción	
Su objetivo principal es continuar con la definición del sistema software a desarrollar, tomando como punto de partida los requisitos generales y los casos de usos en su versión inicial, y considerando los objetivos de negocio y el modelo de negocio a implantar. Los casos de uso que se considere necesario, se van completando con más información y los requisitos generales se van detallando en requisitos funcionales, no funcionales, de integración y en restricciones técnicas.

Riesgos de no efectuar la actividad:

Esta tarea es esencial para el desarrollo de un sistema software, por lo que no se contempla la posibilidad de no realizarla.
Tareas	
Tareas:

Elaborar la documentación asociada a los requisitos cumplimentando el ERS
Técnicas:

Especificación de casos de uso (usando la plantilla detallada para casos de uso propuesta en MADEJA).
Especificación de requisitos de información (usando la plantilla para requisitos de información propuesta en MADEJA).
Especificación de reglas de negocio (usando la plantilla para reglas de negocio propuesta en MADEJA).
Especificación de requisitos de conducta (usando la plantilla para requisitos de conducta propuesta en MADEJA).
Especificación de requisitos de integración (usando la plantilla para requisitos de integración propuesta en MADEJA).
Especificación de requisitos no funcionales (usando la plantilla para requisitos no funcionales propuesta en MADEJA).
Especificación de restricciones técnicas(usando la plantilla para restricciones técnicas propuesta en MADEJA)
Responsable	
Tarea1, Ingeniero de requisitos

Productos	
Entrada:

Pliego de Prescripciones Técnicas del proyecto, si existe. Puede contener información relevante sobre los requisitos del sistema.
Oferta Seleccionada del proyecto, si existe. Puede contener información relevante sobre los requisitos del sistema.
Estudio de Viabilidad del Sistema, si existe. Debe contener información relevante sobre los requisitos del sistema
Objetivos de negocio. Aportan una visión general importante a la hora de especificar los requisitos.
Modelo de negocio a implantar. Junto con los objetivos de negocio, aportan una visión general importante a la hora de especificar los requisitos.
Requisitos generales del sistema. Constituyen la base para identificar requisitos de mayor nivel de detalle.
Casos de uso del sistema (versión inicial). Constituyen la base para identificar requisitos de mayor nivel de detalle, especialmente casos de uso detallados.
Salida:

Casos de uso del sistema (versión detallada), uno de los principales productos resultantes de esta tarea. Describen con detalle cómo debe interactuar el sistema con sus usuarios para que éstos puedan realizar sus tareas del modelo de negocio.
Requisitos funcionales, uno de los principales productos resultantes de esta tarea. Se deben enunciar a un nivel de detalle suficiente como para que a partir de ellos pueda implementarse una solución. Se clasifican en:
Requisitos de información, describen la información que debe almacenar y gestionar el sistema para dar soporte a los procesos de negocio.
Reglas de negocio, describen las reglas o restricciones por cuyo cumplimiento debe velar el sistema.
Requisitos de conducta, describen capacidades transversales o interacciones sencillas con el usuario.
Requisitos no funcionales, uno de los principales productos resultantes de esta tarea, describen características de calidad del sistema.
Requisitos de integración, uno de los principales productos resultantes de esta tarea, describen con qué servicios debe integrarse el sistema.
Restricciones técnicas, uno de los principales productos resultantes de esta tarea, describen restricciones normalmente de carácter tecnológico que debe cumplir el sistema.
Volver al índice
Título	
Analizar los requisitos del sistema
Descripción	
Su objetivo principal es mejorar los requisitos, normalmente mediante la elaboración de modelos que permitan identificar posibles problemas y que detallen más la solución propuesta para resolver las necesidades de negocio de clientes y usuarios, incluyendo la arquitectura lógica del sistema y sus interfaces de usuario y de servicios. En caso de identificar problemas en los requisitos, éstos deberán registrarse en la actividad Registrar problemas en los requisitos del sistema.

Riesgos de no efectuar la actividad:

Sobrecostes en el proyecto, El coste de solucionar un problema en los requisitos se dispara exponencialmente conforme avanza el desarrollo de un proyecto. Todo esfuerzo que se haga para mejorar la calidad de los requisitos reducirá el riesgo de sobrecostes posteriores.
Tareas	
Tareas:

Definir la arquitectura lógica del sistema
Elaborar el modelo estático del sistema
Elaborar el modelo dinámico
Técnicas:

Las principales técnicas que se suelen emplear para la realización de esta tarea son:

Diagramas de componentes UML
Diagramas de clases UML
Diagramas de estado UML
Diagramas de secuencia UML
Diagramas de navegación
Esquemas de pantallas e informes
Responsable	
Tarea1, Ingeniero de requisitos
Tarea3, Ingeniero de requisitos
Tarea2, Ingeniero de requisitos

Productos	
Entrada:

Especificación de Requisitos del Sistema. Principal entrada de la tarea, ya que contiene los requisitos a analizar mediante la construcción de los correspondientes modelos.
Salida:

Arquitectura lógica del sistema. Uno de los productos principales de esta tarea, con gran impacto en el resto del desarrollo.
Modelo estático. Junto con el modelo dinámico/funcional, constituye el modelo del sistema a desarrollar. Tiene gran importancia a la hora de detectar problemas en los requisitos y su impacto es muy importante en el diseño de bases de datos.
Modelo dinámico/funcional. Junto con el modelo estático, constituye el modelo del sistema a desarrollar. Tiene gran importancia a la hora de detectar problemas en los casos de uso y tiene gran impacto en el diseño de la capa de lógica de negocio en el caso de sistema con arquitectura en n-capas.
Interfaz de usuario. El producto más relevante para la validación de los requisitos con clientes y usuarios. Tiene gran importancia a la hora de detectar problemas en todos los requisitos y su impacto es muy importante en el diseño e implementación de la interfaz de usuario del sistema.
Interfaz de servicios. Producto relevante si el sistema va a exponer su funcionalidad mediante una interfaz de servicios.
Problemas en los requisitos. Uno de los principales productos de esta tarea son los problemas identificados en los requisitos al realizar el análisis de los mismos, especialmente de falta de información o de conflictos.
Volver al índice
Título	
Verificar la calidad de los requisitos del sistema
Descripción	
Su objetivo principal es verificar que la Especificación de Requisitos del Sistema (ERS) cumple el modelo de calidad de requisitos propuesto en MADEJA, que debería ser conocido por los ingenieros de requisitos para que lo tengan en cuenta durante la elaboración de los requisitos.

Riesgos de no efectuar la actividad:

Sobrecostes en el proyecto, El coste de solucionar un problema en los requisitos se dispara exponencialmente conforme avanza el desarrollo de un proyecto. Todo esfuerzo que se haga para mejorar la calidad de los requisitos reducirá el riesgo de sobrecostes posteriores.
Tareas	
Tareas:

Elaborar un informe de resultados de la verificación que defina los problemas detectados
Técnicas:

Las principales técnicas que se suelen emplear para la realización de esta tarea son:

Utilización de comprobaciónes para el cumplimiento de las pautas establecidas.
Responsable	
Tarea1, Ingeniero de requisitos

Productos	
Entrada:

Modelo de calidad de requisitos de MADEJA, que contiene las características de calidad que deben tener tanto la ERS en conjunto como los requisitos individuales. Se debe usar para aclarar posibles dudas que surjan al aplicar la comprobación de las pautas a través de las verificaciones.
Lista de comprobación de requisitos de MADEJA, que debe dirigir el proceso de verificación mediante un conjunto de preguntas sobre la calidad de los requisitos.
Especificación de Requisitos del Sistema, que es el objeto de la verificación de calidad. Se asume que ya está analizada y por tanto libre de conflictos y de faltas de información.
Salida:

Problemas en los requisitos. El principal producto de esta tarea son los problemas identificados en los requisitos al verificar la calidad de los mismos, especialmente defectos de tipo no conformidad.
Volver al índice
Título	
Validar los requisitos del sistema
Descripción	
Su objetivo principal es comprobar que el sistema software descrito por la Especificación de Requisitos del Sistema  (ERS) se corresponde con las necesidades de negocio de clientes y usuarios, obteniendo su aprobación y permitiendo generar una línea base de los requisitos en la actividad Gestionar las líneas base y las peticiones de cambio a los requisitos del sistema del procedimiento Gestionar los requisitos del sistema software a desarrollar.

Riesgos de no efectuar la actividad:

Producto final inadecuado, No validar el sistema software propuesto en la ERS suele provocar que el producto final no sea el esperado por clientes ni usuarios.
Baja usabilidad, No validar el sistema software propuesto en la ERS, especialmente la interfaz de usuario, suele provocar que el producto, aunque técnicamente correcto, tenga una usabilidad baja al no presentar a los usuarios una forma aceptada por ellos de realizar sus procesos de negocio.
Tareas	
Tareas:

Validar el prototipo Recogiendo información sobre posibles incumplimientos con respecto a los requisitos
Técnicas

Las principales técnicas que se suelen emplear para la realización de esta tarea son:

Prototipado de interfaz de usuario.
Recorridos de casos de uso.
Responsable	
Tarea1, Ingeniero de requisitos

Productos	
Entrada:

Prototipos de interfaz de usuario del sistema a desarrollar. Normalmente asociados a casos de uso, permiten a clientes y usuarios hacerse una idea bastante concreta del sistema software que se les está proponiendo en la Especificación de Requisitos del Sistema.
Especificación de Requisitos del Sistema, que es el objeto de la validación por parte de clientes y usuarios. Se asume que ya está analizada y verificada, por lo tanto libre de conflictos, faltas de información y defectos. Si clientes y usuarios aprueban los requisitos, se puede generar la primera línea base de la ERS.
Salida:

Actas de reuniones, deben recoger los resultados obtenidos en las sesiones de validación, incluyendo posibles no aceptaciones que luego deberán registrarse como problemas para ser gestionados oportunamente. En caso de aceptación por parte de clientes y usuarios, ésta deberá recogerse explícitamente en las actas. Para cumplimentar dichas actas se debe usar la plantilla definida por la Junta de Andalucía en cada momento.
Problemas en los requisitos. Junto con las actas de las reuniones, el principal producto de esta tarea son los problemas identificados en los requisitos al validarlos con clientes y usuarios, especialmente no aceptaciones.
Volver al índice
Título	
Registrar problemas en los requisitos
Descripción	
Su objetivo principal es asegurar que se registran las dependencias establecidas entre cada requisito del software y uno o más requisitos del usuario, u otras fuentes (trazabilidad hacia atrás) o una o varias partes del diseño o la implementación (trazabilidad hacia adelante)

Riesgos de no efectuar la actividad:

Fracaso del proyecto , No registrar los problemas en los requisitos, y por lo tanto no asegurar su solución, puede provocar numerosos problemas en el proyecto que provoquen sobrecostes y retrasos que lleven al fracaso del mismo.
Tareas	
Tareas:

Registar los problemas detectados
Técnicas:

Las principales técnicas que se suelen emplear para la realización de esta tarea son:

Utilización de un sistema de seguimiento de problemas.


Responsable	
Tarea1, Ingeniero de requisitos

Productos	
Entrada:

Problemas en los requisitos(PRQ). La entrada de esta tarea son los problemas en los requisitos identificados en cualquiera de las actividades del proceso de Desarrollar los requisitos de un sistema software que satisfaga las necesidades de negocio.
Salida:

Problemas en los requisitos (registrados). La salida de esta tarea son los mismos problemas de entrada registrados en algún sistema de seguimiento de problemas. Durante el registro puede que algunos problemas sufran alguna modificación para aclarar su significado o se supriman algunos si están duplicados.
Volver al índice
Título	
Registrar la trazabilidad de los requisitos
Descripción	
Su objetivo principal es registrar todos aquellos problemas en los requisitos identificados en cualquiera de las tareas de la actividad Desarrollar los requisitos de un sistema software que satisfaga las necesidades de negocio, de forma que puedan ser gestionados por la tarea Gestionar los problemas en los requisitos de la actividad Gestionar los requisitos del sistema software a desarrollar.

Riesgos de no efectuar la actividad:

Fracaso del proyecto , No registrar la trazabilidad de los requisitos provoca considerables dificultades para realizar las pruebas y validación en los requisitos que provocan sobrecostes y retrasos que pueden llevar al fracaso del proyecto.
Tareas	
Tareas:

Registrar la trazabilidad de los requisitos
Técnicas:

Las principales técnicas que se suelen emplear para la realización de esta tarea son:


Trazabilidad de requisitos, registrando al menos las siguientes dependencias:
Clases -> requisitos (especialmente requisitos de información y reglas de negocio)
Diagramas de secuencia -> requisitos (especialmente casos de uso y requisitos de conducta)
Pantallas e informes -> requisitos (especialmente casos de uso y requisitos de conducta)
Interfaces de servicios -> requisitos (especialmente requisitos de integración y restricciones técnicas)
Clases -> diagramas de secuencia
Pantallas e informes -> diagramas de secuencia
Pantallas e informes -> clases
Responsable	
Tarea1, Ingeniero de requisitos

Productos	
Entrada:

Especificación de Requisitos del sistema, que es el objeto de la validación por parte de clientes y usuarios. Se asume que ya está analizada y verificada, por lo tanto libre de conflictos, faltas de información y defectos. Si clientes y usuarios aprueban los requisitos, se puede generar la primera línea base de la ERS.
Salida:

Especificación de Requisitos del sistema (Matrices de trazabilidad requisitos registrados). La salida de esta tarea son las matrices de trazabilidad que reflejan las dependencias entre los requisitos y demás elementos que componen la ERS. Estas matrices quedan registradas dentro del ERS
