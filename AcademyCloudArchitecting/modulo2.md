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


### Implementación de la escalabilidad:

### Automatización del entorno:

### Uso de IaC:

### Tratamiento de los recursos como desechables:

### Uso de débilmente acoplados:

### Diseño de servicios, no servidores:

### Elección de la base de datos adecuada:

### Evitación de los púntos únicos de error:

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