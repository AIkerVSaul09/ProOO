# Paradigma en la Programacion
Un paradigma de programación es una manera o estilo de programación de software. Existen diferentes formas de diseñar un lenguaje de programación y varios modos de trabajar para obtener los resultados que necesitan los programadores.  Se trata de un conjunto de métodos sistemáticos aplicables en todos los niveles del diseño de programas para resolver problemas computacionales.

# Programación Orientada a Objetos
La programación orientada a objetos es un modelo de programación en el que el diseño de software se organiza alrededor de datos u objetos, en vez de usar funciones y lógica. Se enfoca en los objetos que los programadores necesitan manipular, en lugar de centrarse en la lógica necesaria para esa manipulación.

## ¿Cuál fue el primer lenguaje orientado a objetos, quienes y en dónde lo propusieron? 

El primer lenguaje de programación que se utilizó para seguir este paradigma fue SmallTalk. Los orígenes de este lenguaje se encuentran en las investigaciones realizadas por Alan Kay, Dan Ingalls, Ted Kaehler, Adele Goldberg y otros durante los años setenta en el Palo Alto Research Center de Xerox (conocido como Xerox PARC), para la creación de un sistema informático orientado a la educación. Xerox PARC es una compañia creada con el fin de la investigación tecnológica.

En Smalltalk se interactúa entre objetos mediante el envío de mensajes Es multiplataforma y puede compilar en tiempo de ejecución o interpretado. Smalltalk tuvo gran influencia en la creación de otros lenguajes como Java o Ruby.

Todo en smalltalk es un objeto que puede hacer 3 cosas: --Mantener un estado. --Recibir mensajes de si mismo o de otros objetos. --En el curso de procesar un mensaje, enviarse un mensaje el mismo o a los demás objetos.

Características de los objetos en smalltalk: --Tienen una memoria propia. --Poseen capacidad para comunicarse con otros objetos. --Poseen la capacidad de heredar características de objetos ancestros. --Tienen capacidad de procesamiento.

# Abstraccion
En programación, una abstracción es una manera de reducir la complejidad y permitir un diseño e implementación más eficientes en sistemas de software complejos. Es el proceso por el cual se descarta toda aquella información que no resulta relevante en un contexto en particular enfatizando algunos de los detalles o propiedades de los objetos. Basicamnete hace que el codigo no sea muy repetitivo y no utilice mucha memoria dentro la consola.

# Encapsulamiento
La encapsulación es un mecanismo para reunir datos y métodos dentro de una estructura ocultando la implementación del objeto, es decir, impidiendo el acceso a los datos por cualquier medio que no sean los servicios propuestos.

Es el proceso de almacenar en una misma sección los elementos de una abstracción que constituyen su estructura y su comportamiento; sirve para separar el interfaz contractual de una abstracción y su implantación.

![Imagen](https://ferestrepoca.github.io/paradigmas-de-programacion/poo/poo_teoria/images/classpython.png)

(Podemos decir que este codigo no esta Encapsulado, ya que su variables estan declaradas directamente en el dato)

![Imagen2](https://www.ciberaula.com/imagenes/enc_1.PNG)

(Podemos decir que este codigo si esta encapsulado, ya que las variables o datos estan declarados como publicos y  el acceso público es un nivel de acceso del encapsulamiento)

# Herencia

La herencia, junto con la encapsulación y el polimorfismo, es una de las tres características principales de la programación orientada a objetos. La herencia permite crear clases que reutilizan, extienden y modifican el comportamiento definido en otras clases.

![Imagen3](https://lh3.googleusercontent.com/nVpYEGH-S9y40tn0tB0rafK3_6i3ZLlYDyfNbsP_C7v3a7yshiyrP8SrLdnUZ2UR1fpGyVaR9Wf-uE9lEtqjeCRhk9HsIkd4wtLATpt4ZCOyNdrUl09sPf37YqIoDZnJAh9k5TeqTr5oYJx3QlnR4cKLAGEDxh6POk5DP2QW175Npo7G-KBf3-NGwwLWupOBokuOZRGn6wgT_35oXlCWwlc_4UjPG6zZqGDSdzZ63wLE4Aba0u1pnZ-6MwPosyGfA_3T0omLcdjh82EP6lBiHvRlNWiSa9d9Qac_teYv7Ww4gT-uP0KcLYUx2qdMO7JPp7y2t4S7NcbSfGsk7SLb7AH-zwcExNjHTsQVu2YG7tMlkwTljAP6BxWlLXOXiOpZAJr4gbx1xgBj-7gBSv4DGZdnWrkdcbWSa6IqTjaKB1YI7QStAwRk_zyri2CKrVWelbW_Hy_tcL2V4okgZgD-oVSEUFb9FYQEw9_MN9j3N36m1JaJEXb6d5YSQPfOq0kVUnZttw4wVCmx61e_QIrIguoVrlM2CmxOR_mmnx4AFMAoajfWStMyDe9B32moLCfJj0lJK1janDX5BFVKqj-uHHubjtqm3xLg_AXam4hFAWVzVbbDhdF2=w634-h463-no)

(La herencia es la transmisión del código entre unas clases y otras. Para soportar un mecanismo de herencia tenemos dos clases: la clase padre y la/s clase/s hija/s. La clase padre es la que transmite su código a las clases hijas. En muchos lenguajes de programación se declara la herencia con la palabra "extends".)


# UML: Diagrama de clases

El diagrama de distribución UML muestra la arquitectura física de un sistema informático. Puede representar a los equipos y a los dispositivos, y también mostrar sus interconexiones y el software que se encontrará en cada máquina. La asociación se refiere a la conexión física entre los nodos, como por ejemplo Ethernet.

--El modelo funcional, representado en UML, con diagramas de caso de uso, describe la funcionalidad del sistema desde el punto de vista del usuario.

--El modelo de objetos, representado en UML con diagramas de clase, describe la estructura de un sistema desde el punto de vista de objetos, atributos, asociaciones y operaciones.

--El modelo dinámico, representado en UML con diagramas de secuencia, diagramas de estado y diagramas de actividad, describen el comportamiento interno del sistema. Los diagramas de secuencia describen el comportamiento como una secuencia de mensajes intercambiados entre un conjunto de objetos, mientras que los diagramas de gráfica de estado describen el comportamiento desde el punto de vista de estados de un objeto individual y las transiciones posibles entre estados.

Actualmente el UML es muy utilizado por empresas grandes que se dedican o utilizan algun software por la gran facilidad de entender el objetivo de los programas por medio de un recurso visual, más que nada para darlo a entender a las personas que no estan familiarizadas con el tema de la programación. Por ejemplo APPLE, AMAZON, SPACE X, TESLA MOTORS, NVIDIA, etc.

Ya que el UML es un modelo a seguir, consta de herramientas con significados especiales como lo son sus conexiones o conectores. Dentro de estas herramientas, los conectores más comúnes son:

-Las Asociaciones representan relaciones generales entre clases, y puede haber cardinalidad entre estas, es decir, tal clase puede tener un número de clases pero otra clase solo puede tener tal número de clases. Esta propiedad de represanta por rango, por ejemplo: #..# o #..* (el numero mínimo, luego se separa con dos puntos y luego el número máximo. En caso de que sea un límite infinito se pone *).
