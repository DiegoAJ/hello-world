Los dos componentes principales de un sistema experto son una base de conocimientos y un motor de inferencias.

La base de conocimiento son la evolución de los sistemas de base de datos tradicionales, que tienen como fin no almacenar simples datos, sino elementos de conocimiento y como usar dicho conocimiento para que el Sistema realice sus funciones. Las bases de información tienen un gestor de administración equivalente a los DBMS (Database Management System) en los KBMS: Knowledge Base Management System. A diferencia de los DBMS, los KBMS no se encuentran estandarizados ni comercializados.

El motor de inferencia es el componente de un Sistema Experto, encargado de gerenciar y controlar logicamente el manejo y utilización del conocimiento almacenado en la base. El paradigma del motor de inferencia es la estrategia de búsqueda para producir el conocimiento demandado.

Entre los componentes mas detallados del sistema experto, encontramos al subsistema de control de coherencia (previene la entrada de información incoherente en la base de conocimiento),  el subsistema de adquisición de conocimiento (se asegura de que al almacenar información esta sea nueva para la base de datos y no redundante), el subsistema de demanda de información (completa el conocimiento necesario y reanuda el proceso de inferencia hasta obtener alguna conclusión válida), el subsistema de incertidumbre (almacena la información de tipo incierto y propaga la incertidumbre asociada a esta información), el subsistema de ejecución de tareas (permite realizar acciones al Sistema Experto basadas en el motor de inferencia) y finalmente el subsistema de explicación (juega papel cuando se le solicita al sistema experto una explicación de las conclusiones obtenidas por este).

Sin embargo, no podemos decir que existe una estructura común para los sistemas expertos. Muchos de los componentes previamente mencionados pueden encontrarse en estos, pero también pueden omitir algunos (pero siempre incluyendo un tipo de base de conocimientos y motor de inferencias). La base de conocimientos contiene el conocimiento especializado extraído del experto en el dominio, y como estos pueden quedar obsoletos o desactualizados, se pueden agregar a la base de conocimientos los nuevos datos sin afectar el motor de inferencias.

Para la elaboración de un sistema experto, se requiere de un equipo de personas en el que todos ejercen un papel distinto. Por ejemplo, habría necesidad de un experto para que este aporte a la base de conocimientos, un llamado experto del conocimiento que estructura e implementa los conocimientos del experto, y finalmente un usuario que aporta deseos e ideas que influyen en el diseño del SE.

La mayoría de los sistemas expertos utilizan el llamado encadenamiento regresivo para alcanzar sus conclusiones. Este método consiste en que, dado un objetivo, se busca una regla que permita establecer dicha conclusión. El proceso se repite hasta encadenar con la regla cuya conclusión satisfaga el objetivo propuesto, o se detecte que dicho problema no se puede resolver positivamente.

También tenemos sistemas expertos que utilizan el llamado encadenamiento progresivo. Este tipo de encadenamiento se produce cuando el objetivo propuesto hace que se ejecute una regla, y la conclusión obtenida permite que se ejecute otra, y así sucesivamente hasta llegar a una respuesta, positiva o negativa. El punto final se detecta cuando no se pueden producir más encadenamientos. 

Para la construcción de un sistema experto, destacamos dos metodologías principales: la de prototipos, y la orientada a objetos. La primera consiste un prototipo que debe ser construido en poco tiempo, usando los programas adecuados y no se debe utilizar muchos recursos. La segunda metodología involucra lo que es la programación orientada a objetos, siendo su principal ventaja el hecho que cualquier modificación o mantenimiento que se le quiera realizar a un determinado componente no afectará a otro.

En cuanto a que lenguajes de programación implementar para construir un Sistema Experto, podemos mencionar: LISP, CLIPS, Prolog, Smalltalk, C y C++. Además, a continuación listamos distintos "shells" para SE, siendo los llamados shells un tipo de Sistema Experto genérico sin base de conocimiento al que entonces podemos implementar una de nuestra propia elaboración. Los shells a mencionar son los siguientes: Gold Works II, ART, LOOPS, KEE, Humble y EMYCIN.

----------------------------------------------------------------------------------------------------------

Pasaremos a hablar de las aplicaciones que se le dan actualmente a los sistemas expertos. En general, las principales aplicaciones de los sistemas expertos son las relacionadas con el mundo empresarial. Esto se debe a que resultan muy útiles en funciones como la contabilidad, tesorería, gestiones internas. El campo que más aplicaciones de sistemas expertos esta realizando actualmente es el de la auditoría.

Según la clase de problemas hacia los que estén orientados, podemos clasificar los Sistemas Expertos en diversos tipos entre los que cabe destacar diagnosis, pronóstico, planificación, reparación e instrucción. 

Dentro del ámbito de interpretación, diagnostico y monitoreo, podemos decir que la interpretación consiste en encontrar el significado de los datos de entrada obtenidos por sensores o introducidos por el usuario. Existen dos tipos de interpretación, el análisis (donde la interpretación de datos se obtiene mediante la separación o distinción de las partes que los forman) y la síntesis (mediante la combinación de los datos).

Cuando hablamos de diagnostico, el mismo consiste en identificar las causas internas que provocan un problema partir de una serie de datos o síntomas que son consecuencia de la misma y que son observables. Por otro lado, la monitorización es un caso particular de la interpretación, y consiste en la comparación continua de los valores de las señales o datos de entrada y unos valores que actúan como criterios de normalidad o estándares.

Podemos definir el diseño como una traza o delineación con el fin de proyectar una obra u objeto de tal manera que este pueda cumplir con distintos requisitos planteados al idear este último. Los sistemas expertos de diseño, por su lado, reciben los requisitos de parte de un usuario y generan distintos diseños para verificar cual de estos cumplen con requerimientos solicitados por el usuario. 

La planificación, de manera sencilla, se podría definir como el proceso de establecer metas y elegir medios para alcanzar dichas metas. 




