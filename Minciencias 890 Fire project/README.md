# Rúbrica para evaluar los software de simulación de incendios y explosiones
Se crearon unos criterios para evaluar las diferentes herramientas de modelación física (HsMF) en los diferentes escenarios donde se pueden dar incendios o explosiones. Si bien algunos de los criterios no los pudimos evaluar directamente dadas las limitaciones que tenemos respecto al uso de la herramienta, se trató en estos casos de valorar el criterio apoyados con una revisión de la literatura y la información del fabricante o distribuidor. En la Tabla 1 se muestran los criterios usados en la evaluación de las HsMF y la forma de valorar cada criterio.

**Tabla 1**. Criterios de evaluación usados para la rúbrica
| | | |Indicadores| | |
| --- |--- |--- |--- |--- |--- |
|Criterios | 1 | 2 | 3 |4 |5 |
|Instalación | Muy difícil | Difícil | Medianamente |Fácil |Muy fácil |
|Versión de (libre descarga) | No tiene versión estudiantil|  |  | |Tiene versión estudiantil |
|Sistemas operativos disponibles | Un solo S.O.  | Dos S.O. | Tres S.O.| |Varios S.O. |
|Modelos matemáticos | Modelos 1-D  | Modelo de compartimientos | Modelos CFD 2-D| CFD |CFD - LES |
|Tutoriales | No hay tutoriales  | Algunos problemas realizado por usuarios | Tutoriales realizados por usuarios| Tutoriales básicos oficiales |Tutoriales oficiales completos y de usuarios |
|Guía de usuario | No tiene guia de usuario | Guías de usuario no oficiales - tesis | |Guía de usuario - propia |Guia de usuario con material |
|Preproceso Malla|Requiere otro software de terceros|||Tiene su propio pre-procesador|Tiene su propio pre-procesador y de terceros|
| Preproceso de caso| | || | |
|Postproceso| | | |Post Proceso- requiere previamente definir zonas|Postprocesador fácil ,definir superficies, etc|
|Costo|Comercial - Costo alto|Comercial - Costo bajo|Software libre con costo||Software libre, sin costo|
|Guia teórica|No existe guía teórica|||Guía teórica de terceros-|Guía teórica propia del software|
|Fácil para enseñar|Difícil||||Muy fácil|
|IA aplicabilidad|Los datos no son aplicables IA|Genera pocos datos-poca aplicabilidad IA||genera gran cantidad Datos aplicables IA|Datos y Artículos que han demostrado aplicaciones IA|
|Costo computacional|Más de 4 semanas|Semanas|Días|horas|Minutos|
|Recursos en línea (Tesis-videos)|No hay recursos en línea|Poca información|Recursos en sitio web propio - desactualizados||Recursos en sitio web propio - actualizados|
|Posibilidad de incluir modelos propios|No es posible||Es posible pero la implementación es compleja||Es posible y fácil de incluir|
|Información de los métodos numéricos implementados|No se tiene información||||Información completa de los métodos de discretización usados|

Para el caso de incendios por compartimentos se realizó una simulación en los software FDS, CFAST y FireFoam dado que todos son de libre acceso y teníamos posibilidad de realizar una comparación basado en un caso base, el cual se describe en el anexo 2. La rúbrica para este caso se muestra en la Tabla 2, en donde se concluye que FDS es la mejor herramienta en este caso, sin embargo la diferencia con OpenFoam y CFAST no es muy marcada lo que nos indica que para este caso en concreto los 3 software se podrías usar en la enseñanza.

**Tabla 2**. Rúbrica para software de incendios en compartimientos
| | |Software incendios| | 
|---|---|---|---| 
|**Criterios**|**FDS**|**CFAST**|**FireFoam (OpenFoam)**| 
|Instalación|5|5|4| 
|Versión de (libre descarga)|5|5|5| 
|Sistemas operativo|4|4|4| 
|Modelos matemáticos|5|2|5| 
|Tutoriales|5|5|5| 
|Guía de usuario|5|5|4| 
|Preproceso Malla|5|5|5| 
|Preproceso Caso|5|5|5| 
|Postproceso|4|4|5| 
|Costo|5|5|5| 
|Guia teórica|5|5|4| 
|Fácil para enseñar|4|4|4| 
|IA aplicabilidad|5|4|5| 
|Costo computacional|4|5|4| 
|Recursos en línea (Tesis-videos)|5|3|5| 
|Posibilidad de incluir modelos propios|5|3|5| 
|Información de los métodos numéricos implementados|5|5|5| 
|**Total**|81|74|79| 

En el caso de los incendios en galerías se evaluó la rúbrica basado en la revisión de la literatura y la experiencia con estos software.

**Tabla 3**. Rúbrica para software de incendios en galerias
| | |Software incendios| | | 
|---|---|---|---| ---|
|**Criterios**|**MFIRE**|**VentFire**|**FDS**|**FireFoam (OpenFoam)**| 
|Instalación|5|5|5| 4| 
|Versión de (libre descarga)|5|1|5| 5| 
|Sistemas operativo|3|1|4| 4| 
|Modelos matemáticos|1|1|5| 5| 
|Tutoriales|3|3|3| 5| 
|Guía de usuario|4|3|5| 4| 
|Preproceso Malla|5|5|5| 5| 
|Preproceso Caso|5|5|5| 5| 
|Postproceso|1|4|5| 3| 
|Costo|5|2|4| 5| 
|Guia teórica|2|3|5| 4| 
|Fácil para enseñar|1|4|5|3| 
|IA aplicabilidad|3|3|5| 5| 
|Costo computacional|5|5|3| 3| 
|Recursos en línea (Tesis-videos)|1|3|5|5|  
|Posibilidad de incluir modelos propios|4|1|4|5|  
|Información de los métodos numéricos implementados|4|4|5|5|  
|**Total**|57|53|78|75| 

En el caso de los incendios en cobertura vegetal se evaluó la rúbrica basado en xxx

**Tabla 4**. Rúbrica para software de incendios en cobertura vegetal
| | |Software incendios| | 
|---|---|---|---| 
|**Criterios**|**WFDS**|**FDS**|**FireFoam (OpenFoam)**| 
|Instalación|5|5|4| 
|Versión de (libre descarga)|5|5|5| 
|Sistemas operativo|4|4|4| 
|Modelos matemáticos|5|4|4| 
|Tutoriales|4|3|3| 
|Guía de usuario|5|4|3| 
|Preproceso Malla|5|5|5| 
|Preproceso Caso|5|5|5| 
|Postproceso|4|4|5| 
|Costo|5|5|5| 
|Guia teórica|5|5|4| 
|Fácil para enseñar|4|4|4| 
|IA aplicabilidad|5|5|5| 
|Costo computacional|4|4|4| 
|Recursos en línea (Tesis-videos)|5|5|5| 
|Posibilidad de incluir modelos propios|5|5|5| 
|Información de los métodos numéricos implementados|5|5|5| 
|**Total**|80|77|75| 

En el caso de los incendios por empozamiento se evaluó la rúbrica basado en xxx

**Tabla 5**. Rúbrica para software de incendios por empozamiento
| | |Software incendios| | 
|---|---|---|---| 
|**Criterios**|**Ansys**|**FDS**|**FireFoam (OpenFoam)**| 
|Instalación|5|5|4| 
|Versión de (libre descarga)|4|5|5| 
|Sistemas operativo|4|4|4| 
|Modelos matemáticos|4|4|4| 
|Tutoriales|3|5|4| 
|Guía de usuario|4|4|3| 
|Preproceso Malla|5|5|5| 
|Preproceso Caso|5|5|5| 
|Postproceso|5|5|5| 
|Costo|3|5|5| 
|Guia teórica|5|5|4| 
|Fácil para enseñar|4|4|4| 
|IA aplicabilidad|5|5|5| 
|Costo computacional|4|4|4| 
|Recursos en línea (Tesis-videos)|5|5|5| 
|Posibilidad de incluir modelos propios|5|5|5| 
|Información de los métodos numéricos implementados|5|5|5| 
|**Total**|75|80|76| 

Para evaluar las explosiones se evaluó la rúbrica basado en un tutorial de OpenFoam en el cual se usa la librería de XiFoam. La simulación se realizó tanto en el software Ansys como en el software OpenFoam dado que se disponía de estas herramientas para su uso, en el caso de ExploCFD y FLACS se asignaron valores en la rúbrica basado en la información de publicaciones, información del vendedor y de tutoriales disponibles en la web.

**Tabla 6**. Rúbrica para evaluar una explosión de gases
| | |Software explosiones| | | 
|---|---|---|---| ---|
|**Criterios**|**FLACS**|**ExploCFD**|**Ansys**|**OpenFoam**| 
|Instalación|5|3|5| 4| 
|Versión de (libre descarga)|1|1|5| 5| 
|Sistemas operativo|4|1|4| 4| 
|Modelos matemáticos|5|3|5| 5| 
|Tutoriales|5|4|3| 5| 
|Guía de usuario|5|5|5| 4| 
|Preproceso Malla|5|2|5| 5| 
|Preproceso Caso|5|5|5| 5| 
|Postproceso|5|3|5| 3| 
|Costo|1|2|4| 5| 
|Guia teórica|3|1|5| 4| 
|Fácil para enseñar|4|4|5|3| 
|IA aplicabilidad|5|5|5| 5| 
|Costo computacional|5|5|3| 3| 
|Recursos en línea (Tesis-videos)|5|5|5|5|  
|Posibilidad de incluir modelos propios|1|1|4|5|  
|Información de los métodos numéricos implementados|1|1|5|5|  
|**Total**|65|51|78|75| 

