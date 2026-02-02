# PRESENTACIÓN DE LA ARQUITECTURA EN LA NUBE:
## INTRODUCCIÓN:
### Objetvivos del módulo:
- Definir la arquitectura en la nube.
- Describir cómo diseñar y evaluar arquitecturas con el Marco de AWS Well-Architected.
- Explicar las prácticas recomendadas para la creación de soluciones en AWS.
- Describir cómo tomar decisiones fundamentadas sobtr dónde colocar los recursos de AWS.
### Información general:
**Secciones:**
- Arquitectura en la nube
- Marco de AWS Well-Architected
- Prácticas recomendadas para crear soluciones en AWS.
- Infraestructura global de AWS.
**Evaluaciones:**
- Evaluación de conocimientos (10 preguntas).

## ARQUITECTURA EN LA NUBE:
### Computación en la nube y AWS:
--Inicios de AWS en la computación en la nube--
### Arquitectura en la nube:
**¿Qué es la arquitectura en la nube?**
Es la práctica de aplicar características de la nube a una solución que usa servicios y características de nube para satisfacer las necesidades técnicas de una organización y los casos prácticos empresariales.

Crear soluciones tecnológias es muy similar a construir un edificio físico. Si los cimientos no son sólidos, pueden causar problemas estrructurales que socavan la integridad y la función del edificio. 

Para crear un edificio sólido, el cliente describe las necesidades y requisitos, el arquitecto crea un diseño y planos, el equipoo de construcción convierte los planos en una estructura física.

En la arquitectura de la nube, el cliente o responsable de la toma de decisiones también describe los objetivos y requisitos empresariales, el arquitecto de la nube diseña una solución, el equipo de entregaa trabaja para implementar la solución.

### El rol de un arquitecto de nube:
El rol de los arquitectos de nubes es el siguiente:
- Interactúan con los responsables de la toma de decisiones para identificar los objetivos de nogocios y las capacidades que necesitan mejorar.
- Se aseguran de que haya una alineación entre las entregas de tecnología de una solución y los objetivos de su negocio.
- Trabajan con los equipos de entrega que están implementando la solución para asegurarse de que las características tecnológicas sean adecuadas.

Son los responsables de administrar la arquitectura de computación en la nube de una organización. Cuentan con conocimientos profundos sobre los principios de arquitectura y los servicios usados para realizar lo siguiente:
- Desarrollar la estrategia técnica de la nube basada en necesidades empresariales.
- Ayudar en los esfuerzos de migración a la nube.
- Revisar los requisitos de carga de trabajo.
- Proporcionar orientación sobre el modo de abordar los problemas de alto riesgo.

### Conclusiones clave:
- La arquitectura en la nube es la práctica de aplicar características de la nube a una solución que usa servicios de nube para satisfacer las necesidades técnicas de uina organización y los casos prácticos empresariales.
- Pueden usar los servicios de AWS para crear arquitecturas altamente disponibles, que sean escalables y fiables.
- Los arquitectos de la nube son los responsables de administrar la arquitectura de computación en la nube de una organización.

## Marco de AWS Well-Architected:
El Marco de AWS WellArchitected es una guía que ofrece un enfoque coherente para evaluar las arquitecturas en la nube. También proporciona orientación para ayudar a implementar los diseños.

Documenta una serie de preguntas básicas y prácticas recomendadas que le permiten comprender si una arquitectura determinada está bien alineada con las prácticas recomendadas de la nube.

El Marco de AWS Well-Architected se organiza en seis pilares.

### Pilar de excelencia operativa:
- Ejecute y supervise los sistemas que ofrecen calor empresarial.
- Mejore de manera constante los procesos y procesamientos de apoyo.
- Vasualice toda la carga de trabajo como código.

Aborda la capacidad de ejecutar sistemas y obtener información sobre sus operaciones para entregar valor empresarial. También aborda la capacidad de mejorar contínuamente los procesos y el procedimiento de apoyo.

Cuando Diseñe una carga de trabajo para operaciones, debe conocer cómo se implementará, actualizará y operará. Inplemente prácticas de ingeniería que estén alineadas con las reducciones de defectos y en las correcciones rápidas. Haga posible la observación con el registro, la instrumentalización y las métricas empresariales y t´ecnicas para que pueda obtener información sobre lo que sucede dentro de su arquitectura.

En AWS puede ver como código toda su carga de trabajo (de aplicaciones, infraestructura, políticas, gobernanza y operaciones). Puede definir y actualizar todas las partes de su carga de trabajo mediante código. Esto significa que es posible aplicar la misma disciplina de ingeniería que utiliza para el código de aplicación a cada elemento de su pila.

### Pilar de seguridad:
- Implemente una sólida base de identidad.
- Mantenga la trazabilidad.
- Aplique seguridad en todas las capas.
- Implemente estrategias de evaluación y mitigación de riesgos.

Aborda la capacidad de proteger la información, los sistemas y los activos, al tiempo que se obtiene valor empresarial mediante evaluaciones de riesgo y estrategias de mitigación.

Su arquitectura tendrá una presencia de seguridad más sólida si implementa una sólida base de identidad, usa y mantiene la trazabilidad, aplica seguridad en todas las capas, automaizar las prácticas recomendadas de seguridad y proteger los datos en tránsito y en reposo. La implementación de estps principios de seguridad le sirve para prepararse para los eventos de seguridad.

### Pilar de fiabilidad:
- Recuperar rápidamente.
- Satisfaga la demanda informatica de forma dinámica.
- Mitigue las interrupociones.

Abordala capacidad de un sistema para recuperarse de errores en la infraestructura o interrupciones de servicio y adquirir de manera dinámica recursos de cómputo para satisfacer la demanda. También aborda la capacidad de un sistema para mitigar las interrupciones como errores de configuración o problemas transitorios de la red.

Puede ser dificil asegurar la fiabilidad en un entorno tradicional. Los problemas surgen de puntos únicos de error, la falta de automatización y la falta de elasticidad. Al aplicar las prácticas recomendadas descritas en el pilar de fiabilidad, puede prevenir muchos de estos problemas.

Este pilar sirve para tener una arquitectura deiseñada adecuadamennte respecto a la alta disponibilidad, la tolerancia a errores y la redundancia en general.

### Pilar de eficiencia del rendimiento:
- Elija y mantenga recursos eficientes.
- Democratice las tecnologías avanzadas.
- Emplee la compatibilidad mecánica.

Cuando considere el rendimiento, querrá maximizar su rendimiento mediante el uso eficiente de recursos de compuitación. También es deseable que mantenga esa eficiencia a medida que cambie la demanda.

Igualmente, es importante democratizar las tecnologías avanzadas. En situaciones en las que le resulte dificil implementar la tecnología por usted mismo, considere recurrir a un proveedor. Al implementar la tecnología por usted, el proveedor se hace cargo de la complegidad y el conocimiento, con lo que libera a su equipo para concentrarse en el trabajo de más valor agregado.

La *compatibilidad mecánica* ocurre cuando utiliza una herramienta con conocimientos sobre cómo funciona mejor. Utilice el enfoque tecnológico que se adapte mejor a lo que intenta lograr.

### Pilar de optimización de costos:
- Mida la eficiencia.
- Elimine gastos innecesarios.
- Adopte el modelo de consumo correcto.
- Considere el uso de servicios administrados.

Es un requisito permanente de cualquier buen diseño de arquitectura. El proceso es iterativo (repetitivo) y debe perfeccionarse y mejorarse a lo largo del ciclo de vida de producción.

Adopte el modelo de consumo adecuado para su caso práctico. Es posibleque desee adoptar un modelo en el que pague solo por los recursos que utiliza.

### Pilar de sostenibilidad:
- Establecer objetivos de sostenibilidad.
- Maximice la utilización.
- Elija hardware y software eficientes.
- Reduzca el impacto posterior.

Aborda la capacidad para crear arquitecturas que maximicen la eficiencia y reduzcan el desperdicio. Aborda el impacto ambiental, económico y social a largo plazo. Debe comprender el impacto de sus cargas de trabajo y trabajar para reducir el impacto posterior.

La sostenibilidad en la nube es un esfuerzo contínuo. Se centra en la reducción y eficiencia energética en todos los componentes. Incluye la selección inicial de un lenguaje de programación, la adopción de algoritmos y el uso de técnicas de almacenamiento de datos. También puede incluir la implementación de una infraesctructura de cómputo eficiente y de tamaño correcto.

### Uso de la herramienta de AWS WA:
- Puede revisar el estado de las cargas de trabajo y compararlas con las prácticas recomendadas más recientes.
- Le permite acceder a los conocimientos y a las prácticas recomendadas que utilizan los arquitectos de AWS.
- Proporciona un plan de acción con una orientación paso a paso dobre cómo crear mejores cargas de trabajo para la nube.
- Proporcina un proceso coherente para revisar y medir su arquitectura en la nube.

Si se desea ayuda con el diseño, puede usar la Herramienta de AWS Well-Architected. Es uan herramienta de autoservicio que le proporciona acceso bajo demanda a las prácticas recomendadas actuales de AWS. Estas prácticas pueden ayudar a crear una infraestructura segura, de alto rendimiento, resiliente y eficiente en AWS.

Permite revisar el estado de las cargas de trabajo y compararlas con las prácticas recomendadas más eficientes. Da acceso a los conocimientos y las prácticas que utilizan los arquitectos de AWS.

Está disponible en la consola de administración. Se define la carga de trabajo y se responde a una serie de preguntas en las areas de excelencia operativa, seguridad, fiabilidad, eficiencia energética y optimización de costos. La herramienta le proporciona un plan de acción con la orientación paso a paso sobre cómo crear mejores cargas de trabajo.

Con la herramienta puede recopilar datos y obtener recomendaciones para hacer lo siguiente:
- Minimizar errores del sistema y costos operativos.
- Profundizar en los procesos empresariales y de infraestructura.
- Proporcionar guía sobre las prácticas recomendadas.
- Cumplir con la propuesta de valor de la computación en la nube.

Puede utilizar los resultados obtenidos para identificar próximos pasos a fin de mejorar, impulsar las decisiones sobre la arquitectura e integrar las consideraciones sobre la arquitectura a su plan de gobernanza corporativa.

### Conclusiones del Marco de AWS Well.Architected:
- Proporciona un enfoque coherente para evaluar las arquitecturas de nube y orientación para implementar diseños.
- Se organiza en 6 pilares (excelencia operativa, seguridad, fiabilidad, eficiencia del rendimiento, optimización de costos y sostenibilidad).
- Cada pilar documenta un conjunto de preguntas fundamentales que pueden utilizar para comprender si una arquitectura específica se alinea con las prácticas recomendables.
- Ayuda a revisar el estado de sis cargas de trabajo y compararlas con las prácticas recomendadas de arquitectura de AWS más recientes.

## PRACTICAS RECOMENDADAS PARA CREAR SOLUCIONES EN AWS:

### Compensaciones de diseño:
Al diseñar una solución, piensa en las ventajas y desventajas para poder seleccionar un enfoque óptimo:
- Evalúa las ventajas y desventajas para poder seleccionar un enfoque óptimo.
- Entre los ejemplos de ventajas y desventajas se incluyen los siguietnes:
    - Cambiar la consistencia, la durabilidad y el espacio por el tiempo y la latencia para ofrecer un rendimiento más alto.
    - Para las nuevas características, priorizar la velocidad de comercialización por encima del costo.
- Base a las decisiones de diseño en datos empíricos.

Las desventajas pueden incrementar el costo y la complejidad de una arquitectura. 
    Realizar pruebas de carga para asegurarse de obtener un beneficio medible del rendimiento.
    Realizar análisis comparativos para lograr la carga de trabajo con menores costos.

### Implementación de la escalabilidad:
- Los usuarios rara vezexperimentan una indterrupción del servicio.
- *Amazon EC2 Auto Scaling* recibe la alerta y escala.
- El nuevo servidor está listo antes de que se alcance la capacidad total.

Cuando ejecuta sus cargas de trabajo en la nube de AWS, puede escalar su infraestructura con rapidez y de manera proactiva.

Implementar la escalabilidad en cada capa de la infraestructura puede mejorar su diseño para anticipar la necesidad de más capacidad y entregarla antes de que sea demasiado tarde.

Ej:
> Usar Amazon *CloudWatch* para determinar si la carga todctal de todos los servidores alcanzó un umbral específico. El umbral puede ser cualquier magnitud siempre que esté relacionado con los recursos del servidor. Con *CloudWatch*, también puede diseñar métricas personalizadas basadas en aplicaciones específicas.

Cuando se invoca una alarma, *Amazon EC2 Auto Scaling* inicia una nueva instancia, de manera que esté lista antes de que se alcance el máximo de la capacidad.

### Automatización del entorno:
- El servidor de aplicaciones falla.
- Amazon CloudWatch detecta de manera automática la instancia en mal estado.
- Amazon EC2 Auto Scalling se inicia y configura un servidor idéntico.
- Una alarma notifica al administrador.
- CloudWatch registra la acción en una solución de administración de cambios.

AWS ofrece herramientas de suoervisión y automatización en casi todas las capas de su infraestructura. Estas herramientas evitan tener que detectar y comunicar errores en los servidores al administrador y tener que crear nuevas instancias.

### Uso de IaC:
- Aprovisione su infraestructúra mediante código en lñugar de procesos manuales.
    - Implemente rápidamente entornos duplicados.
    - Reduzca los errores de configuración derivados de la configuración manual.
    - Propague los cambios de forma coherente a todas las pilas.

La infraestrucura como código se utiliza para la automatización de la infraestructura con el fin de crear entornos. El uso más común es en el desarrollo de Software, para crear, probar e implmentar aplicaciones.

Implemente entornos duplicados con solo una plantilla.

### Tratamiento de los recursos como desechables:
- Aproveche la naturalezaa de aprovisionamiento dinámico de ka computación en la nube.
    - Automatice la implementación de recursos nuevos con configuraciones idénticas.
    - Detenga los recursos que no se utilizan.
    - Pruebe las actualizaciones en los recursos nuevos, luego, reemplace kis recursos viejos por los actualizados.

La práctica recomendada de tratar los recursos desechables se relaciona con la idea de considerar su infraestrucuta como software en lugar de como hardware.

    Con el hardware, se pueden comprar más componentes de los necesarios, pero hacer esto es caro e inflexible.

    Cuando se trata a los recursos como desechables, migrar entre instancias u otros recursos discretos es bastante sencillo.

### Uso de débilmente acoplados:
- Diseñe arquitecturas con comportamientos independientes.
- Práctica recomendada:
    - Servidores web.
    - Elastic Load Balancing (ELB).
    - Servidores de aplicaciones.
    > Servidores web desacoplados con Elastic Load Balancing (ELB),
- Práctica no recomendada:
    - Servidores web.
    - Servidores de aplicaciones.
    > Servidores web estrechamente acoplados a los servidores de aplicaciones.

Las infraestructuras tradicionales se basan en cadenas de servidores estrechamente integrados (cada uno con un propósito específico). El problema es que cuando uno de esos componentes o capas deja de funcinar, la interrupción del sistema puede ser crítica. También impide el escalado (si agrega o quita servidores en una capa, tabién debe desconectar los servidores de cada capa de conexión).

Con el acoplamiento debil, utiliza soluciones administradas como intermediarios entre capas de sus sistema.

### Diseño de servicios, no servidores:
- Use la variedad de servicios de AWS. No limite su infraesttructura a servidores.
    - Cuando corresponda, considere usar contenedores o una solución sin servidor.
    - Las colas de mensajes pueden gestionar la comunicación entre aplicaciones.
    - Los activos web estáticos se pueden almacenar fuera del servidor, como en Amazon Simple Storage Service (Amazon S3).
    - Los servicios adminstrados de AWS pueden gestionar la autenticación de los usuarios y el almacenamiento del estado de los usuarios.

La siguiente práctica recomendada e el uso de servicios, no servidores. Aunque Amazon EC2 ofrece flexibilidad, no siempre debe ser la primera opción. Los contenedores o una solución sin servidor pueden ser más adecuados para algunas situaciones.

Con las soluciones sin servidor no es necesario configurar y administra toda una instancia de EC2.

Las soluciones administradas tienen un perfil más bajo y un mejor rendimiento. Pueden reempazar soluciones basadas en servidor por un menor costo. Ejemplos: Lambda, SQS, DynamoDB, ELB, SES...

### Elección de la base de datos adecuada:
- Adapte la tecnología a la carga de trabajo:
    - Las necesidades de lectura y escritura.
    - Los requisitos de almacenamiento totales.
    - El tamaño habitual de los objetos y cómo se accede a ellos.
    - Los requisitos de durabilidad.
    - Los requisitos de latencia.
    - El número máximo de usuarios conectados al mismo tiempo.
    - La naturaleza de las consultas.
    - La intensidad necesaria de los controles de integridad.

Es importante escoger una solución de base de datos adecuada. En los centros de datos tradicionales y los entornos en las instalaciones, los límites sobre el hardware y las licencias disponibles pueden resultar una restricción al momento de elegir una solución.

### Evitación de los púntos únicos de error:
Cuando sea posible, elimine los puntos únicos de error en su arquitectura. Esto no quiere decir que deba duplicar siempre cada componente. Dependiendo de sus acuerdos de nivel de servicio de tiempo de inactividad, puede usar soluciones automáticasque solo inician componentes cuando es neceesario. También puede usar un servicio administrado para que AWS sustituya el hardware que no funcinoa correctamente.

Si hay dos servidores de aplicaciones conectados a un único servidor de base de datos, el servidor de base de datos representa un punto único de error. Una forma común de evitar los puntos únicos de error es crear un serbidor de base de datos secundario y replicar los datos. 

### Optimización de costos:

### Uso de almacenamiento en caché:

### Protección de toda su infraestructura:

### Conclusiones de las prácticas recomendadas para crear soluciones en AWS:

## INFRAESTRUCTURA GLOBAL DE AWS:

### Temas de la infraestructura de AWS:

### Selección de las regiones:

### Selección de zonas de disponibilidad:

### Uso de zonas locales:

### Rol de los centros de datos de AWS:

### PoP de AWS:

### Conclucioens de la infraestructura global de AWS:

##