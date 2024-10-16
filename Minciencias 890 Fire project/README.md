# Comparación de herramientas de simulación física con aplicación en seguridad contra incendios y explosiones
Se crearon unos criterios para evaluar las diferentes herramientas de modelación física (HsMF) en los diferentes escenarios donde se pueden dar incendios o explosiones. Si bien algunos de los criterios no los pudimos evaluar directamente dadas las limitaciones que tenemos respecto al uso de la herramienta, se trató en estos casos de valorar el criterio apoyados con una revisión de la literatura y la información del fabricante o distribuidor. En la Tabla 1 se muestran los criterios que se usaron para comparar diferentes Herramientas de Modelamiento Físico (HsMF).

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

**Incendios por compartimentos:** Para el caso de incendios por compartimentos se realizaron simulaciones con las HsMF FDS, CFAST y FireFoam. La rúbrica para este escenario se apoyo en una simulación común en las 3 herramientas. La rúbrica para este caso se muestra en la Tabla 2, en donde se concluye que FDS es la mejor herramienta en este caso, sin embargo la diferencia con OpenFoam y CFAST no es muy marcada lo que nos indica que para este caso en concreto los 3 software se podrías usar en la enseñanza.

<table style="width: 100%; text-align: center;">
  <caption>Tabla 2. Rúbrica para software de incendios en compartimientos</caption>
  <thead>
    <tr>
      <th width="40%"></th>
      <th colspan="3" width="20%">Software</th>
    </tr>
    <tr>
      <th scope="col">Criterios</th>
      <th scope="col" width="20%">FDS</th>
      <th scope="col" width="20%">CFAST</th>
      <th scope="col" width="20%">FireFoam (OpenFoam)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td scope="row">Instalación</td><td>5</td><td>5</td><td>5</td>
    </tr>
    <tr>
      <td scope="row">Versión de libre descarga</td><td>5</td><td>5</td><td>5</td>
    </tr>
    <tr>
      <td scope="row">Sistema operativo</td><td>4</td><td>4</td><td>4</td>
    </tr>
    <tr>
      <td scope="row">Modelos matemáticos</td><td>5</td><td>2</td><td>5</td>
    </tr>
    <tr>
      <td scope="row">Tutoriales</td><td>5</td><td>5</td><td>5</td>
    </tr>
    <tr>
      <td scope="row">Guía de usuario</td><td>5</td><td>5</td><td>4</td>
    </tr>
    <tr>
      <td scope="row">Preproceso de malla</td><td>5</td><td>5</td><td>5</td>
    </tr>
    <tr>
      <td scope="row">Preproceso de caso</td><td>5</td><td>5</td><td>5</td>
    </tr>
    <tr>
      <td scope="row">Postproceso</td><td>4</td><td>4</td><td>5</td>
    </tr>
    <tr>
      <td scope="row">Costo</td><td>5</td><td>5</td><td>5</td>
    </tr>
    <tr>
      <td scope="row">Guía teórica</td><td>5</td><td>5</td><td>4</td>
    </tr>
    <tr>
      <td scope="row">Fácil de enseñar</td><td>4</td><td>4</td><td>4</td>
    </tr>
    <tr>
      <td scope="row">Aplicabilidad de IA</td><td>5</td><td>4</td><td>5</td>
    </tr>
    <tr>
      <td scope="row">Costo computacional</td><td>4</td><td>5</td><td>4</td>
    </tr>
    <tr>
      <td scope="row">Recursos en línea (Tesis - videos)</td><td>5</td><td>3</td><td>5</td>
    </tr>
    <tr>
      <td scope="row">Posibilidad de incluir modelos propios</td><td>5</td><td>3</td><td>5</td>
    </tr>
    <tr>
      <td scope="row">Información de los métodos numéricos implementados</td><td>5</td><td>5</td><td>5</td>
    </tr>
    <tr>
      <th scope="row">Total</th><td>81</td><td>74</td><td>79</td>
    </tr>
  </tbody>
</table>

Las HsMF MFIRE, VentFire, FDS y OpenFoam se evaluaron para determinar la herramienta más adecucada para educar en la prevención y mitigación cuando se presentan incendios en espacios subterraneos y tuneles. Si bien se observa que FDS presenta la mejor calificación para simular este tipo de incendios, es importante resaltar que el uso de esta herramienta se puede ver seriamente limitada si la geometría a simular tiene dimensiones muy grandes que puede ocurrir en minas subterráneas que presentan extensiones de kilómetros, bajo estos escenarios herramientas que usan modelos 1D como MFIRE y VentFire son recomendados.

**Tabla 3**. Rúbrica para software de incendios en espacios subterraneos y túneles
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

En el caso de los incendios en cobertura vegetal se evaluó la rúbrica para las herramientas Wildland-Urban Interface Fire Dynamics Simulator (WFDS), FDS y OpenFoam. La evaluación de estas herramientas sugiere que WFDS es la más adecuada para la enseñanza de este tipo de incendios. sin embargo es importante resaltar que en la evaluación de este tipo de incendio no se encontró una diferencia muy marcada entre las herramientas evaluadas que sugiere que cualquiera podría usarse para simular este proceso.

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

En el caso de los incendios por empozamiento se evaluó el desempeño que podría tener los software Ansys Fluent, FDS y OpenFoam en la enseñanza de este fenómeno. Dadas las caracteristicas de Fluent y OpenFoam que son software CFD multipropositos estos presentan unas mínimas desventajas en comparación con FDS que fue diseñado especificamente para simular incendios, sin embargo las capacidades de Ansys en el postproceso y la interfaz gráfica con la que cuenta para la construcción del caso la hace una herramienta muy atractiva y con mucho potencial en la enseñanza de este tipo de incendios.

**Tabla 5**. Rúbrica para software de incendios por empozamiento
| | |Software incendios| | 
|---|---|---|---| 
|**Criterios**|**Ansys Fluent**|**FDS**|**FireFoam (OpenFoam)**| 
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

Para evaluar las explosiones de gases se evaluó las herramientas ExploCFD, FLACS, XiFoam y Fluent. De acuerdo a la evaluación realizada las herramientas Fluent y OpenFoam serían una muy buena opción para la enseñanza de este fenómeno.

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

Para evaluar las explosiones de sprays y nieblas se evaluaron herramientas ExploCFD, FDS, OpenFoam y Fluent. De acuerdo a la evaluación realizada Fluent y OpenFoam serían las herramientas que presentan la mejor calificación para educar.

**Tabla 7**. Rúbrica para evaluar una explosión de sprays y nieblas
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
|Guia teórica|3|1|4| 4| 
|Fácil para enseñar|4|4|5|3| 
|IA aplicabilidad|5|5|5| 5| 
|Costo computacional|5|5|3| 3| 
|Recursos en línea (Tesis-videos)|5|2|4|5|  
|Posibilidad de incluir modelos propios|1|1|4|5|  
|Información de los métodos numéricos implementados|1|1|5|5|  
|**Total**|65|50|76|75| 

Para evaluar las explosiones de polvos combustibles se evaluaron las herramientas ExploCFD, FDS, OpenFoam y Fluent. De acuerdo a la evaluación realizada las herramientas Fluent y OpenFoam son las más adecuadas dada la posibilidad de usar versiones libres y de presentar información abundante tanto de los modelos implementados como de estudios realizados en estas herramientas.

**Tabla 8**. Rúbrica para evaluar una explosión de polvos combustibles
| | |Software explosiones| | | 
|---|---|---|---| ---|
|**Criterios**|**FLACS**|**ExploCFD**|**Ansys**|**OpenFoam**| 
|Instalación|5|3|5| 4| 
|Versión de (libre descarga)|1|1|5| 5| 
|Sistemas operativo|4|1|4| 4| 
|Modelos matemáticos|5|3|5| 5| 
|Tutoriales|5|4|4| 5| 
|Guía de usuario|5|5|5| 4| 
|Preproceso Malla|5|2|5| 5| 
|Preproceso Caso|5|5|5| 5| 
|Postproceso|5|3|5| 3| 
|Costo|1|2|4| 5| 
|Guia teórica|3|1|5| 4| 
|Fácil para enseñar|4|4|5|3| 
|IA aplicabilidad|5|5|5| 5| 
|Costo computacional|5|5|3| 3| 
|Recursos en línea (Tesis-videos)|5|2|5|5|  
|Posibilidad de incluir modelos propios|1|1|4|5|  
|Información de los métodos numéricos implementados|1|1|5|5|  
|**Total**|65|50|79|75| 
