<div align="center">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/UPC_logo.png?raw=true" alt="Logo-UPC" width="150">

## Universidad Peruana de Ciencias Aplicadas

**Ingeniería de Software**

**Ciclo:** 2025-1

**Curso:** Diseño de Experimentos de Ingeniería de Software (1ASI0732)

**Sección:** 4453

**Profesor:** Julio Manuel Noriega Melendez

----
## Informe del Trabajo TB2
### Nombre del Startup: TechZo

### Nombre del Producto: Aplicación Informática de Intercambios de Productos Usados
### Nombre Comercial: CambiaZo
#### Relación de integrantes 
| Integrante                  | Código         |
|---------------------------------|----------------|
| Huamani Mandujano, Joseph Alexis         | U20221A133     |
| Mendoza Carrion, Mathias Andre          | U202216282     |
| Quispe Andia, Jeremy Joel      | U202216279     |
| Quispesivana Torres, Claudio Sandro | u202215099     |
| Santisteban Palomino, Ian Haziel Donato | U202214059     |

</div>


<br><div align="center"><h3>Junio 2025</h3></div><br>



<div align="justify">

<div style="page-break-after: always;"></div>

# Registro de Versiones
<br>

| **Versión** | **Fecha** | **Autor** | **Descripción de modificación** |
| - | - | - | - |
|TB1|20/04/25|Ian Haziel Donato Santisteban Palomino, Claudio Sandro Quispesivana Torres, Joseph Alexis Huamani Mandujano, Jeremy Joel Quispe Andia y Mathias Andre Mendoza Carrion | Capítulo I: Introducción, Capítulo II: Requirements Elicitation & Analysis, Capítulo III: Requirements Specification, Capítulo IV: Product Design y Capítulo V: Product Implementation, Validation & Deployment|
|TP1|14/05/25|Ian Haziel Donato Santisteban Palomino, Claudio Sandro Quispesivana Torres, Joseph Alexis Huamani Mandujano, Jeremy Joel Quispe Andia y Mathias Andre Mendoza Carrion | Capítulo VI: Product Verification & Validation y Capítulo VII: DevOps Practices|
|TB2|16/06/25|Ian Haziel Donato Santisteban Palomino, Claudio Sandro Quispesivana Torres, Joseph Alexis Huamani Mandujano, Jeremy Joel Quispe Andia y Mathias Andre Mendoza Carrion | Capítulo VI: Product Verification & Validation, Capítulo VII: DevOps Practices y Capítulo VIII: Experiment-Driven Development |

<br><br>

<div style="page-break-after: always;"></div>

# Contenido

- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la StartUp](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1 Lean UX Problem Statement](#1221-lean-ux-problem-statement)
      - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3 Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos Objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2 Entrevistas](#22-entrevistas)
    - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2 Registro de Entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2 User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
  
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Product Backlog](#33-product-backlog)
  - [3.4. Impact Mapping](#34-impact-mapping)

- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1 Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
    - [4.1.3. Mobile Style Guidelines](#413-mobile-style-guidelines)
      - [4.1.3.1. iOS Mobile Style Guidelines](#4131-ios-mobile-style-guidelines)
      - [4.1.3.2. Android Mobile Style Guidelines](#4132-android-mobile-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3 Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4 Mobile Applications UX/UI Design](#44-mobile-applications-uxui-design)
    - [4.4.1. Mobile Applications Wireframes](#441-mobile-applications-wireframes)
    - [4.4.2. Mobile Applications Wireflow Diagrams](#442-mobile-applications-wireflow-diagrams)
    - [4.4.3. Mobile Applications Mock-ups](#443-mobile-applications-mock-ups)
    - [4.4.4. Mobile Applications User Flow Diagrams](#444-mobile-applications-user-flow-diagrams)
  - [4.5. Mobile Applications Prototyping](#45-mobile-applications-prototyping)
    - [4.5.1. Android Mobile Applications Prototyping](#451-android-mobile-applications-prototyping)
    - [4.5.2. iOS Mobile Applications Prototyping](#452-ios-mobile-applications-prototyping)
  - [4.6. Web Applications UX/UI Design](#46-web-applications-uxui-design)
    - [4.6.1. Web Applications Wireframes](#461-web-applications-wireframes)
    - [4.6.2. Web Applications Wireflow Diagrams](#462-web-applications-wireflow-diagrams)
    - [4.6.3. Web Applications Mock-ups](#463-web-applications-mock-ups)
    - [4.6.4. Web Applications User Flow Diagrams](#464-web-applications-user-flow-diagrams)
  - [4.7. Web Applications Prototyping](#47-web-applications-prototyping)
  - [4.8. Domain-Driven Software Architecture](#48-domain-driven-software-architecture)
    - [4.8.1. Software Architecture Context Diagram](#481-software-architecture-context-diagram)
    - [4.8.2. Software Architecture Container Diagrams](#482-software-architecture-container-diagrams)
    - [4.8.3. Software Architecture Components Diagrams](#483-software-architecture-components-diagrams)
  - [4.9. Software Object-Oriented Design](#49-software-object-oriented-design)
    - [4.9.1. Class Diagrams](#491-class-diagrams)
    - [4.9.2. Class Dictionary](#492-class-dictionary)
  - [4.10. Database Design](#410-database-design)
    - [4.10.1. Relational/Non-Relational Database Diagram](#4101-relationalnon-relational-database-diagram)

- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Product Implementation & Deployment](#52-product-implementation--deployment)
    - [5.2.1. Sprint Backlogs](#521-sprint-backlogs)
    - [5.2.2. Implemented Landing Page Evidence](#522-implemented-landing-page-evidence)
    - [5.2.3. Implemented Frontend-Web Application Evidence](#523-implemented-frontend-web-application-evidence)
    - [5.2.4. Acuerdo de Servicio - SaaS](#524-acuerdo-de-servicio-saas)
    - [5.2.5. Implemented Native-Mobile Application Evidence](#525-implemented-native-mobile-application-evidence)
    - [5.2.6 Implemented RESTful API and/or Serverless Backend Evidence](#526-implemented-restful-api-andor-serverless-backend-evidence)
    - [5.2.7. RESTful API documentation](#527-restful-api-documentation)
    - [5.2.8. Team Collaboration Insights](#528-team-collaboration-insights)
  - [5.3 Video About-the-Product](#53-video-about-the-product)

- [Capítulo VI: Product Verification & Validation](#capítulo-vi-product-verification--validation)  
  - [6.1. Testing Suites & Validation](#61-testing-suites--validation)  
    - [6.1.1. Core Entities Unit Tests](#611-core-entities-unit-tests)  
    - [6.1.2. Core Integration Tests](#612-core-integration-tests)  
    - [6.1.3. Core Behavior-Driven Development](#613-core-behavior-driven-development)  
    - [6.1.4. Core System Tests](#614-core-system-tests)  
  - [6.2. Static testing & Verification](#62-static-testing--verification)  
    - [6.2.1. Static Code Analysis](#621-static-code-analysis)  
      - [6.2.1.1. Coding standard & Code conventions](#6211-coding-standard--code-conventions)  
      - [6.2.1.2. Code Quality & Code Security](#6212-code-quality--code-security)  
    - [6.2.2. Reviews](#622-reviews)  
  - [6.3. Validation Interviews](#63-validation-interviews)  
    - [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)  
    - [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)  
    - [6.3.3. Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)  
  - [6.4. Auditoría de Experiencias de Usuario](#64-auditoría-de-experiencias-de-usuario)  
    - [6.4.1. Auditoría realizada](#641-auditoría-realizada)  
      - [6.4.1.1. Información del grupo auditado](#6411-información-del-grupo-auditado)  
      - [6.4.1.2. Cronograma de auditoría realizada](#6412-cronograma-de-auditoría-realizada)  
      - [6.4.1.3. Contenido de auditoría realizada](#6413-contenido-de-auditoría-realizada)  
    - [6.4.2. Auditoría recibida](#642-auditoría-recibida)  
      - [6.4.2.1. Información del grupo auditor](#6421-información-del-grupo-auditor)  
      - [6.4.2.2. Cronograma de auditoría recibida](#6422-cronograma-de-auditoría-recibida)  
      - [6.4.2.3. Contenido de auditoría recibida](#6423-contenido-de-auditoría-recibida)  
      - [6.4.2.4. Resumen de modificaciones para subsanar hallazgos](#6424-resumen-de-modificaciones-para-subsanar-hallazgos)  

- [Capítulo VII: DevOps Practices](#capítulo-vii-devops-practices)  
  - [7.1. Continuous Integration](#71-continuous-integration)  
    - [7.1.1. Tools and Practices](#711-tools-and-practices)  
    - [7.1.2. Build & Test Suite Pipeline Components](#712-build--test-suite-pipeline-components)  
  - [7.2. Continuous Delivery](#72-continuous-delivery)  
    - [7.2.1. Tools and Practices](#721-tools-and-practices)  
    - [7.2.2. Stages Deployment Pipeline Components](#722-stages-deployment-pipeline-components)  
  - [7.3. Continuous Deployment](#73-continuous-deployment)  
    - [7.3.1. Tools and Practices](#731-tools-and-practices)  
    - [7.3.2. Production Deployment Pipeline Components](#732-production-deployment-pipeline-components)  
  - [7.4. Continuous Monitoring](#74-continuous-monitoring)  
    - [7.4.1. Tools and Practices](#741-tools-and-practices)  
    - [7.4.2. Monitoring Pipeline Components](#742-monitoring-pipeline-components)  
    - [7.4.3. Alerting Pipeline Components](#743-alerting-pipeline-components)  
    - [7.4.4. Notification Pipeline Components](#744-notification-pipeline-components)  

- [Capítulo VIII: Experiment-Driven Development](#capítulo-viii-experiment-driven-development)  
  - [8.1. Experiment Planning](#81-experiment-planning)  
    - [8.1.1. As-Is Summary](#811-as-is-summary)  
    - [8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims](#812-raw-material-assumptions-knowledge-gaps-ideas-claims)  
    - [8.1.3. Experiment-Ready Questions](#813-experiment-ready-questions)  
    - [8.1.4. Question Backlog](#814-question-backlog)  
    - [8.1.5. Experiment Cards](#815-experiment-cards)  
  - [8.2. Experiment Design](#82-experiment-design)  
    - [8.2.1. Hypotheses](#821-hypotheses)  
    - [8.2.2. Measures](#822-measures)  
    - [8.2.3. Conditions](#823-conditions)  
    - [8.2.4. Scale Calculations and Decisions](#824-scale-calculations-and-decisions)  
    - [8.2.5. Methods Selection](#825-methods-selection)  
    - [8.2.6. Data Analytics: Goals, KPIs and Metrics Selection](#826-data-analytics-goals-kpis-and-metrics-selection)  
    - [8.2.7. Web and Mobile Tracking Plan](#827-web-and-mobile-tracking-plan)  
  - [8.3. Experimentation](#83-experimentation)  
    - [8.3.1. To-Be User Stories](#831-to-be-user-stories)  
    - [8.3.2. To-Be Product Backlog](#832-to-be-product-backlog)

- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

### [Bibliografía](#bibliografía)

### [Anexos](#anexos)

<div align="justify">
	
<div style="page-break-after: always;"></div>

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:<br><br>
**ABET – EAC - Student Outcome 4**<br>
**Criterio:** La capacidad de reconocer responsabilidades éticas y profesionales en
situaciones de ingeniería y hacer juicios informados, que deben considerar el
impacto de las soluciones de ingeniería en contextos globales, económicos,
ambientales y sociales<br><br>
En el siguiente cuadro se describen las acciones realizadas y las conclusiones enunciadas por el grupo, que permiten sustentar el logro del ABET – EAC - Student Outcome 4.<br><br>

<table>
  <thead>
    <tr>
      <th colspan="3"><b>Criterio específico</b></th>
      <th colspan="3"><b>Acciones realizadas</b></th>
      <th colspan="3"><b>Conclusiones</b></th>
    </tr>
  </thead>
  <tbody>
    <tr>
	<td colspan="3"> Reconoce responsabilidad
ética y profesional en
situaciones de ingeniería de
software</td>
      <td colspan="3" align = "justify">
      <h3>Joseph Alexis Huamani Mandujano</h3> 
      <b>TB1</b> 
      <p>Asumí un rol participativo en la definición del problema y en la formulación de hipótesis que sirvieron como base para el desarrollo del producto. Durante este proceso, reflexioné sobre la responsabilidad profesional que implica diseñar soluciones que impactan directamente en las personas. Me aseguré de mantener un enfoque ético al validar ideas y enfoques, teniendo siempre presente la importancia de tomar decisiones informadas y justas para el equipo y los usuarios.</p> 
      <b>TP</b> 
      <p>Me enfoqué en definir los criterios de aceptación desde la perspectiva del usuario utilizando el enfoque BDD (Behavior-Driven Development), lo cual implicó asumir una responsabilidad ética al interpretar correctamente sus necesidades. Esto permitió diseñar pruebas que validaran comportamientos reales del sistema, garantizando que nuestras soluciones fueran coherentes con las expectativas de los usuarios. Además, en el desarrollo del pipeline de pruebas y construcción, prioricé la transparencia y trazabilidad en cada fase para asegurar entregables confiables y éticos.</p>
      <b>TB2</b>
      <p>Me centré en liderar la implementación de pruebas de unidad e integración para las entidades principales del sistema, asegurando que cada componente funcionara de manera correcta y segura. Asumí la responsabilidad ética de prevenir errores que pudieran afectar a los usuarios, priorizando la calidad y robustez del código. Además, participé activamente en la revisión de estándares de codificación y seguridad, donde promovimos prácticas responsables y sostenibles que consideraran la mantenibilidad del sistema en diferentes contextos de uso.</p> 
    <h3>Mathias André Mendoza Carrión</h3>
    <b>TB1</b>
    <p>Me involucré de manera activa en las tareas de investigación y análisis de los usuarios, donde fue fundamental mantener una postura ética y respetuosa en la recolección y uso de la información. A lo largo del proyecto, mostré responsabilidad profesional al tomar decisiones orientadas a resolver problemas reales, buscando siempre que las soluciones tuvieran un sustento claro y beneficiaran al usuario final. Fomenté dentro del equipo una actitud de compromiso y respeto con los objetivos del proyecto.</p>
    <b>TP</b> 
    <p>Durante esta entrega, asumí la tarea de implementar pruebas de integración que permitieran validar cómo interactúan los diferentes componentes del sistema. Esto implicó asumir un compromiso ético con la calidad del software, al evitar errores que puedan comprometer la experiencia del usuario. También seleccioné herramientas de CI que promovieran la automatización responsable del proyecto, fomentando prácticas que garanticen resultados reproducibles y decisiones basadas en evidencia técnica.</p>
    <b>TB2</b>
    <p>Fui responsable de coordinar la auditoría de experiencia de usuario, lo cual implicó una evaluación empática y ética del impacto de nuestra solución en las personas. Este ejercicio me permitió reflexionar sobre cómo decisiones técnicas pueden influir en la accesibilidad y satisfacción de usuarios reales. Al analizar y responder a los hallazgos de otros grupos, ejercí un juicio informado que tuvo como objetivo mejorar la inclusión, usabilidad y sostenibilidad del producto, elevando la calidad desde una perspectiva social.</p> 
    <h3>Ian Haziel Donato Santisteban Palomino</h3>
    <b>TB1</b>
    <p>Colaboré de manera constante en la coordinación de tareas y toma de decisiones, procurando mantener una cultura de trabajo en equipo donde la ética profesional fuera un pilar fundamental. Promoví la comunicación clara y el respeto por los tiempos y aportes de todos, lo cual fue clave para tomar decisiones responsables en el diseño y validación de las propuestas. En cada etapa, busqué que nuestras acciones tuvieran coherencia con los valores del proyecto.</p>
    <b>TP</b> 
    <p>Fui responsable de las pruebas de sistema, asegurándome de que el producto cumpliera con los requisitos funcionales y no funcionales definidos previamente. Esta tarea exigió un compromiso ético para no omitir validaciones críticas. También coordiné la configuración de los entornos por etapas en el pipeline de despliegue, buscando garantizar una transición progresiva y segura hacia la producción. Esto implicó decisiones responsables para minimizar impactos negativos hacia los usuarios.</p>
    <b>TB2</b>
    <p>Estuve a cargo del diseño y ejecución de entrevistas de validación, donde procuré interpretar con precisión las necesidades de los usuarios y transformar esas voces en mejoras tangibles. Reconocí la importancia de asumir una actitud ética al representar fielmente sus expectativas, garantizando que el producto no solo funcionara técnicamente, sino que también respondiera de forma adecuada a contextos reales y humanos. Esta responsabilidad se tradujo en un mayor compromiso con el desarrollo de soluciones socialmente responsables.</p> 
    <h3>Jeremy Joel Quispe Andia</h3>
    <b>TB1</b>
    <p>Durante la elaboración del producto, participé activamente en la priorización de requerimientos y planificación de entregables. Me aseguré de que las decisiones que tomábamos estuvieran respaldadas por las necesidades reales de los usuarios y no por supuestos o tendencias pasajeras. Asumí con responsabilidad el impacto que nuestras decisiones podían tener, tanto en el resultado final como en la experiencia del usuario, guiándome por principios éticos y profesionales.</p>
    <b>TP</b> 
    <p>Me enfoqué en el diseño e implementación de pruebas unitarias para las entidades principales del sistema. Esto supuso una responsabilidad ética al garantizar que cada módulo individual funcione correctamente, evitando efectos colaterales que afecten al conjunto. En paralelo, contribuí en la definición de herramientas de Continuous Delivery, seleccionando aquellas que ofrecieran mayor confiabilidad y trazabilidad, facilitando decisiones técnicas acordes con nuestras responsabilidades profesionales.</p>
    <b>TB2</b>
    <p>Participé en la configuración e implementación de las prácticas de integración y entrega continua. Durante este proceso, prioricé herramientas open source y configuraciones eficientes que redujeran el uso excesivo de recursos, pensando en la sostenibilidad y en facilitar la adopción del producto por equipos con recursos limitados. Esta elección técnica se basó en una reflexión ética sobre la equidad tecnológica, buscando construir soluciones accesibles, transparentes y adaptables a distintos entornos económicos y sociales.</p> 
    <h3>Claudio Sandro Quispesivana Torres</h3>
    <b>TB1</b>
    <p>En las tareas relacionadas al diseño colaborativo del producto, incluyendo base de datos y desarrollo de interfaces, actué con responsabilidad y conciencia profesional, asegurándome de que cada decisión respondiera a necesidades reales y no generara problemas éticos ni técnicos en el futuro. Promoví un enfoque reflexivo dentro del equipo para que el desarrollo del producto se realizara con un compromiso ético constante y orientado al beneficio del usuario.</p>
    <b>TP</b> 
    <p>Aporté en la ejecución de pruebas de integración con un enfoque orientado a prevenir fallos en la interacción entre componentes. Este trabajo me llevó a reflexionar sobre la importancia de anticipar errores antes de llegar al usuario final, reforzando así mi compromiso profesional. Además, participé en la definición de buenas prácticas para el despliegue continuo, enfocándome en herramientas que prioricen la estabilidad, seguridad y trazabilidad de las entregas.</p>
    <b>TB2</b>
    <p>Mi principal responsabilidad fue planificar y ejecutar los experimentos de desarrollo orientado a hipótesis. Al definir métricas, condiciones y KPIs, asumí un rol profesional en la toma de decisiones informadas, considerando el impacto que ciertos cambios podían tener en el comportamiento del sistema y en la experiencia de los usuarios. Este enfoque basado en evidencia me permitió reflexionar sobre cómo una evaluación rigurosa y responsable contribuye a una ingeniería más consciente y centrada en el bienestar de las personas.</p> 
    <td colspan="3">
    <b>TB1</b>
    <p>Al finalizar este primer tramo del proyecto, nuestro equipo ha demostrado una clara conciencia sobre la responsabilidad ética y profesional que implica el desarrollo de soluciones de software. A lo largo de las actividades realizadas, desde la definición del problema hasta las decisiones tomadas durante la propuesta de valor, cada integrante ha mostrado un compromiso genuino por actuar con integridad, transparencia y respeto hacia los usuarios y hacia el trabajo colaborativo. Este enfoque responsable ha sido clave para construir una base sólida que garantice no solo la calidad técnica del producto, sino también su pertinencia social y su viabilidad en contextos reales. El haber abordado cada etapa con ética profesional ha fortalecido la confianza entre nosotros y con los objetivos del proyecto, reafirmando que las buenas prácticas y la reflexión crítica son esenciales para nuestro crecimiento como futuros ingenieros de software.</p>
    <b>TP</b>
    <p>En esta fase del proyecto, asumimos con responsabilidad ética y profesional la implementación de pruebas y prácticas DevOps como parte fundamental del proceso de desarrollo. Nos comprometimos a garantizar la calidad del producto mediante pruebas unitarias, de integración y de sistema que no solo verificaran el funcionamiento correcto, sino que también protegieran a los usuarios de posibles fallos. Además, reflexionamos sobre la importancia de automatizar procesos con transparencia, confiabilidad y trazabilidad, reconociendo que cada decisión técnica conlleva una responsabilidad hacia quienes utilizan el software. La ética estuvo presente en cada etapa al promover la colaboración, documentar adecuadamente nuestras acciones y tomar decisiones justas que favorezcan al equipo y a los usuarios finales. Esta entrega fortaleció nuestra conciencia profesional sobre el impacto que tiene nuestro trabajo, no solo a nivel técnico, sino también humano.</p>
    <b>TB2</b>
    <p>A lo largo de esta etapa del proyecto, nuestro equipo asumió con responsabilidad ética y profesional cada una de las decisiones tomadas durante las fases de verificación, validación, DevOps y experimentación. Más allá del cumplimiento técnico, nos esforzamos por comprender el impacto de nuestras soluciones en contextos diversos, evaluando no solo la funcionalidad, sino también la sostenibilidad, accesibilidad y equidad de nuestras propuestas. Esta conciencia nos permitió ajustar continuamente el rumbo del desarrollo, reafirmando nuestro compromiso con una ingeniería de software centrada en el ser humano y en la mejora del entorno social, económico y ambiental donde se implementará nuestra solución. Asimismo, promovimos la colaboración activa entre los miembros del equipo para tomar decisiones informadas de manera conjunta. Esta dinámica fortaleció nuestra capacidad crítica y reafirmó nuestra responsabilidad como futuros profesionales conscientes de su impacto.</p>
  </td>
    </tr>
    <tr>
      <td colspan="3">Emite juicios informados
considerando el impacto de las
soluciones de ingeniería de
software en contextos globales,
económicos, ambientales y
sociales</td>
      <td colspan="3" align = "justify">
      <h3>Joseph Alexis Huamani Mandujano</h3>
    <b>TB1</b>
    <p>Aporté activamente en la evaluación crítica de nuestras decisiones, buscando que cada elección técnica también respondiera a criterios de sostenibilidad, accesibilidad y viabilidad. Analizamos las condiciones en las que nuestros usuarios podrían interactuar con el producto, considerando incluso limitaciones económicas o sociales, y ajustamos nuestras propuestas para asegurar que fueran realmente útiles y aplicables. Esta reflexión nos ayudó a tomar decisiones más informadas y con mayor conciencia del entorno.</p>
        <b>TP</b> 
    <p>Durante el diseño de nuestras pruebas de integración, cuestioné cómo el sistema respondería en entornos con restricciones económicas o tecnológicas. Ajustamos nuestras decisiones para que los módulos pudieran desplegarse de forma modular y escalonada. Además, al evaluar herramientas para despliegue continuo, procuré que fueran compatibles con entornos en la nube de bajo costo, fomentando una implementación sostenible y adaptable a distintas realidades globales y locales.</p>
    <b>TB2</b>
    <p>Durante el diseño de las pipelines de integración y despliegue, prioricé herramientas de código abierto que pudieran implementarse en distintos entornos sin necesidad de infraestructura costosa. Esta elección buscó reducir barreras económicas y aumentar la accesibilidad del sistema, especialmente para organizaciones con recursos limitados. Cada decisión se basó en la evaluación de impacto y sostenibilidad, manteniendo una mirada global y responsable.</p> 
      <h3>Mathias André Mendoza Carrión</h3>
    <b>TB1</b>
    <p>Durante el desarrollo del proyecto, participé en el análisis de los usuarios y sus entornos, considerando los distintos factores que podían influir en el uso y adopción de nuestra solución. Junto con mi equipo, tomamos decisiones con una mirada amplia, reflexionando sobre cómo nuestras propuestas podrían generar un impacto positivo no solo en el usuario inmediato, sino también en un contexto social más amplio. Este enfoque permitió construir una solución más equilibrada y responsable.</p>
    <b>TP</b> 
    <p>Reflexioné sobre cómo nuestros escenarios de pruebas basados en comportamientos debían ser representativos del contexto real de nuestros usuarios. Para ello, analizamos condiciones de uso en comunidades con acceso limitado a tecnología moderna y adaptamos nuestras validaciones para mantener la funcionalidad bajo esas condiciones. Además, en la construcción del pipeline, me aseguré de que las herramientas seleccionadas fueran accesibles y de bajo costo, considerando la posibilidad de replicar este modelo en organizaciones con recursos reducidos.</p>
    <b>TB2</b>
    <p>Mi participación en el desarrollo de pruebas automatizadas y análisis estático se centró en garantizar no solo la calidad del código, sino también su mantenimiento a largo plazo. Consideré cómo el uso eficiente de recursos y la prevención de errores tempranos podían reducir el consumo innecesario de energía y tiempo en futuras fases, alineando el desarrollo con una visión ambientalmente consciente.</p> 
     <h3>Ian Haziel Donato Santisteban Palomino</h3>
    <b>TB1</b>
    <p>Me enfoqué en mantener una perspectiva amplia al momento de diseñar las propuestas del equipo. Analizamos el impacto que podía tener nuestro producto en diferentes contextos, ajustando decisiones para adaptarnos a realidades diversas y evitar exclusiones. Esta postura nos permitió tomar decisiones más conscientes, buscando que nuestro trabajo fuera no solo funcional, sino también socialmente útil y económicamente viable para los usuarios a los que apuntábamos.</p>
    <b>TP</b> 
    <p>Evalué cómo nuestras decisiones técnicas influían en el mantenimiento y escalabilidad del sistema, particularmente en contextos con infraestructura limitada. Al diseñar pruebas de integración, prioricé que estas fueran eficientes y reutilizables, para reducir el consumo de recursos en futuras iteraciones. En cuanto a herramientas de integración continua, optamos por aquellas de código abierto, reconociendo su valor en entornos con restricciones económicas y su potencial para fomentar el acceso a tecnología sostenible.</p> 
    <b>TB2</b>
    <p>Al coordinar entrevistas de validación con usuarios reales, me aseguré de incorporar puntos de vista diversos que representaran distintos contextos sociales. Esto me permitió adaptar las soluciones a necesidades específicas y emitir juicios mejor informados sobre la dirección del diseño, promoviendo así un software más inclusivo y sensible al entorno cultural y económico de sus usuarios potenciales.</p>
      <h3>Jeremy Joel Quispe Andia</h3>
    <b>TB1</b>
    <p>Contribuí en la toma de decisiones considerando los recursos con los que contábamos y los posibles escenarios en los que se utilizaría el producto. Evaluamos qué tan sostenibles y adaptables eran nuestras soluciones y tomamos decisiones equilibradas entre lo técnico y lo social. Este análisis nos permitió anticipar posibles consecuencias y asegurarnos de que el impacto de nuestro producto fuera positivo en distintos niveles.</p>
    <b>TP</b> 
    <p>En el diseño de pruebas de sistema, consideré cómo estas validaciones asegurarían un producto accesible y robusto para usuarios con diversas condiciones sociales y tecnológicas. Analicé el impacto que podría tener un fallo en entornos con conectividad limitada o infraestructura deficiente. Asimismo, al diseñar el pipeline de despliegue por etapas, busqué una estrategia que permitiera un avance controlado y que minimizara riesgos para las comunidades donde se implementaría el sistema.</p> 
    <b>TB2</b>
    <p>En la auditoría de experiencias de usuario, evalué no solo la funcionalidad, sino también la capacidad del producto para generar un impacto positivo en la calidad de vida de sus usuarios. Me esforcé por traducir los hallazgos en mejoras que fueran sostenibles y relevantes socialmente, fomentando así una ingeniería que trasciende lo técnico y se orienta al bienestar colectivo.</p>
    <h3>Claudio Sandro Quispesivana Torres</h3>
    <b>TB1</b>
    <p>Durante la construcción de las distintas partes del producto, mantuvimos como equipo una mirada reflexiva sobre el entorno donde se aplicaría. Aporté en discusiones donde evaluamos cómo nuestras decisiones podían tener efectos a nivel social, económico e incluso ambiental. Esta perspectiva nos permitió desarrollar una solución más inclusiva, adaptada a contextos reales y con un impacto duradero, más allá del cumplimiento técnico.</p>
    <b>TP</b> 
    <p>En la implementación de pruebas unitarias, consideré cómo la validación detallada de nuestras entidades fundamentales podía contribuir a un producto más estable y duradero. Pensamos en el largo plazo, con miras a minimizar el desperdicio de recursos por correcciones futuras. En paralelo, al proponer herramientas de delivery continuo, privilegié aquellas que promueven automatización eficiente y reducen la necesidad de intervención constante, permitiendo a equipos con menor capacidad técnica mantener el sistema operativo y actualizado.</p> 
    <b>TB2</b>
    <p>Durante el diseño de los experimentos, propuse hipótesis que consideraran cómo los cambios afectarían no solo la eficiencia del sistema, sino también su adaptabilidad en distintos mercados y regiones. Emití juicios fundamentados que contemplaron variables económicas y culturales, ayudando a construir un producto más resiliente y con potencial de impacto global.</p>
    </td>
      <td colspan="3">
    <b>TB1</b>
    <p>A lo largo de este primer hito, nuestro equipo ha consolidado una mirada crítica y reflexiva al momento de tomar decisiones técnicas, considerando en todo momento los impactos potenciales de nuestras soluciones en diferentes contextos. Hemos aprendido a analizar no solo los aspectos funcionales del producto, sino también cómo este puede influir en las personas, en los entornos sociales y económicos, y en la sostenibilidad de su implementación. Esta capacidad de emitir juicios informados nos ha permitido construir propuestas más inclusivas y adaptadas a realidades diversas, incrementando el valor del producto desde una perspectiva humana y contextual. El ejercicio constante de evaluar consecuencias y ajustar decisiones ha sido fundamental para desarrollar una solución equilibrada y responsable, reforzando nuestro compromiso con un desarrollo de software que genere un impacto positivo y duradero.</p>
    <b>TP</b>
    <p>Durante esta etapa del proyecto, nuestro equipo adoptó un enfoque consciente al implementar prácticas de testing y DevOps, evaluando constantemente el impacto que estas decisiones técnicas podían tener más allá del producto en sí. Al diseñar suites de prueba y pipelines de despliegue, consideramos variables como la sostenibilidad, la accesibilidad tecnológica y la viabilidad económica, especialmente en contextos donde los recursos son limitados. Priorizamos herramientas abiertas y prácticas escalables que puedan ser replicadas en entornos diversos, promoviendo así una ingeniería de software más equitativa. Esta reflexión nos permitió anticipar desafíos sociales y técnicos, y ajustar nuestras soluciones para que sean resilientes, accesibles y responsables, fortaleciendo nuestro compromiso con un desarrollo tecnológico consciente del entorno global y local.</p>
    <b>TB2</b>
    <p>A lo largo de este proceso, cada integrante del equipo asumió la responsabilidad de tomar decisiones informadas, considerando el impacto de nuestras soluciones en realidades diversas. Nuestras acciones —desde las pruebas y validaciones hasta el diseño experimental y despliegue— estuvieron guiadas por una mirada crítica hacia los entornos sociales, económicos, globales y ambientales donde nuestro producto podría operar. Este enfoque integral nos permitió construir no solo un sistema funcional, sino también una propuesta tecnológicamente viable, sostenible y sensible al contexto en el que busca generar valor. Además, el constante ejercicio de reflexión nos permitió anticipar posibles consecuencias no deseadas y adoptar medidas preventivas. Esta práctica fortaleció nuestro criterio profesional y nuestra conciencia sobre el rol transformador de la ingeniería de software en la sociedad.</p>
  </td>
    </tr>
  </tbody>
</table>

<div style="page-break-after: always;"></div>

<br><br>


<div style="page-break-after: always;"></div>
  
# Capítulo I: Introducción

## 1.1 Startup Profile

### 1.1.1 Descripción de la Startup

**Nombre:**  TechZo

**Área:**  Innovación tecnológica y Reutilización

TechZo es una startup dedicada a la innovación tecnológica y la reutilización de recursos, fundada por un grupo de estudiantes comprometidos de la Facultad de Ingeniería de la Universidad Peruana de Ciencias Aplicadas (UPC). Nuestra misión es abordar desafíos críticos relacionados con la sostenibilidad y el consumo responsable, fomentando la transición hacia una economía circular en nuestro país.

Nuestra principal solución, CambiaZo, es una aplicación web diseñada para transformar la forma en que las personas gestionan y comparten sus bienes. A través de CambiaZo, facilitamos el intercambio directo, seguro y sin transacciones monetarias de artículos entre usuarios, promoviendo la reutilización y el aprovechamiento óptimo de recursos disponibles. Además, la aplicación ofrece una funcionalidad especial que permite a los usuarios donar productos directamente a personas de bajos recursos, apoyando así a las comunidades más necesitadas.

En TechZo, estamos comprometidos con la seguridad, transparencia y justicia en cada transacción. Trabajamos constantemente para garantizar que los usuarios tengan acceso a información clara y detallada sobre los productos disponibles, fomentando una experiencia de intercambio confiable y satisfactoria. Al combinar tecnología de vanguardia con un enfoque en la responsabilidad social, buscamos impulsar un cambio positivo en la forma en que consumimos y reutilizamos.

* **Misión:**<br>  La misión de TechZo como empresa es promover un estilo de vida sostenible y consciente, proporcionando a los usuarios una plataforma accesible y segura para intercambiar y donar bienes de manera justa y responsable. Buscamos reducir el impacto ambiental fomentando la reutilización, al tiempo que apoyamos a las comunidades más vulnerables a través de un modelo inclusivo de donaciones.<br><br>


* **Visión:** <br>
La visión de TechZo es convertirnos en la plataforma líder de intercambio y donación de productos básicos a nivel global. Queremos ser reconocidos por nuestra capacidad de conectar a las personas y comunidades, fomentando una economía circular que minimice el desperdicio y promueva la solidaridad. Aspiramos a liderar el camino hacia un futuro más sostenible, donde cada acto de intercambio y donación contribuya a un impacto ambiental positivo.<br><br>

* **Valores:**  

  *  **Seguridad y privacidad:** La privacidad es prioritaria, nos preocupamos para que nuestros usuarios sientan que los datos que nos otorgan están seguros y mantenidos en privacidad. Por ello, les otorgamos a nuestros usuarios control sobre ello. Además, sabemos que las medidas sólidas de seguridad, incluido el cifrado de datos en tránsito y reposo, junto con prácticas sólidas en el diseño de la base de datos, resguardan la información sobre nuestros usuarios.

  * **Innovación:** Estar en constante búsqueda de nuevas formas de mejorar la experiencia de los usuarios a través de la tecnología y la creatividad, manteniendo la aplicación a la vanguardia.

  * **Aprendizaje Continuo:** Fomentar un ambiente en el que los miembros del equipo estén dispuestos a aprender y mejorar constantemente, tanto en términos de sostenibilidad como de consumo responsable.

  * **Calidad:** Compromiso con la excelencia en el diseño de la aplicación movil y la funcionalidad de esta misma, asegurándonos de que cumpla con las expectativas más altas de nuestros usuarios.

  * **Compromiso con el usuario:** Poner las necesidades y deseos de los usuarios en el centro de todas las decisiones, asegurando que la aplicación satisfaga sus expectativas y mejore su experiencia realizando intercambios.

  * **Respeto a la diversidad:**  Valorar y respetar las diferencias culturales, étnicas, de género y de opinión, tanto en el equipo interno como en la comunidad de usuarios.<br><br>

 ### 1.1.2 Perfiles de integrantes del equipo

A continuación, presentaremos los perfiles de los integrantes del equipo encargado de desarrollar el proyecto. Cada uno de nuestros miembros aporta una combinación única de habilidades y perspectivas que son fundamentales para el éxito del proyecto.

| **Integrante**                         | **Perfil**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | **Imagen**                                                                                                       |
| -------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| **Huamani Mandujano, Joseph Alexis - u20221a133**             |Mi nombre es Joseph Huamani, soy estudiante de 7mo ciclo en la carrera de Ingeniería de Software en la UPC. Apasionado por el desarrollo web y web, cuento con experiencia usando lenguajes como C++, Python, Java, C#, Javascript y Typescript. Además cuento con experiencia en desarrollo web con HTML5 y CSS3 usando frameworks para frontend como Angular, VueJs, React y Astro. En cuanto al backend frameworks  como Spring Boot, .Net y Flask. Manejo de base de datos como MySQL, MSSQL, PostgreSQL, Oracle, SQLite y MongoDB. Soy una persona que trabaja en equipo, responsable y que brinda soluciones creativas para la resolución de problemas adquiridas gracias a la programación competitiva. Espero poder seguir aprendiendo nuevas tecnologias y poder culminar este curso de manera satisfactoria.| <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-I/Profiles/josephhuamani.png?raw=true" alt="Imagen de Joseph Huamani" />|
| **Mendoza Carrión, Mathias André - u202216282** |Soy Mathias Andre Mendoza Carrión, un estudiante de 20 años de Ingeniería de Software en el septimo ciclo. Me caracterizo por ser organizado, trabajar bien en equipo y ser responsable. Actualmente, mi enfoque principal es el aprendizaje profundo y práctico en el desarrollo de software, con habilidades en lenguajes de programación como C++, Python, Java, C#, y JavaScript. También tengo conocimientos en frameworks como Angular y Vue, desarrollo web con HTML y CSS, así como en la gestión de bases de datos SQL y MongoDB. Aspiro a dominar nuevas tecnologías y comprender en detalle los principios fundamentales detrás del desarrollo de aplicaciones, con el objetivo de convertirme en un profesional capaz de crear soluciones innovadoras y eficientes en el campo del desarrollo de software.| <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-I/Profiles/mathiasmendoza.png?raw=true" alt="Imagen de Mathias Mendoza"/> |
| **Quispe Andia, Jeremy Joel - u202216279** |Mi nombre es Jeremy Joel Quispe Andia, soy estudiante de 7mo ciclo de la carrera de Ingeniería de Software. Tengo una gran pasión por la programación competitiva y aspiro a convertirme en desarrollador Full Stack. Me gusta emplear soluciones creativas y eficientes para abordar cualquier desafío de la mejor manera posible. Como miembro del grupo, pretendo aportar todos mis conocimientos en el desarrollo web. Además, siempre colaboro con ideas y soluciones ante cualquier dificultad que se presente durante el desarrollo. Espero aprender mucho de mis compañeros y que todos juntos podamos emplear de manera adecuada las tecnologías que iremos aprendiendo a lo largo del proyecto.| <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-I/Profiles/jeremyquispe.jpeg?raw=true" alt="Imagen de Jeremy Quispe"/>                 |
| **Santisteban Palomino, Ian Haziel Donato - u202214059**     |Mi nombre es Ian Haziel Donato Santisteban Palomino, tengo 20 años y estoy cursando el septimo ciclo de la carrera de Ingeniería de Software. Me apasiona la resolución de problemas mediante la aplicación de conceptos y tecnologías innovadoras. Tengo experiencia en desarrollo web utilizando HTML, CSS y JavaScript, y manejo frameworks como Vue y Angular. También tengo conocimientos en bases de datos con MySQL y en el uso de Figma para prototipado. Como miembro del equipo, aporto un sólido conocimiento en desarrollo de software y un compromiso constante con la excelencia en cada proyecto en el que participo. Estoy emocionado por aprender y colaborar con el equipo, así como por adquirir nuevas habilidades y conocimientos en las tecnologías que utilizaremos en nuestro trabajo.    | <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-I/Profiles/iansantisteban.png?raw=true" alt="Imagen de Ian Santisteban"/> |
| **Quispesivana Torres, Claudio Sandro - u202215099**     |Mi nombre es Claudio Sandro Quispesivana Torres, tengo 20 años y estoy cursando el septimo ciclo de la carrera de Ingeniería de Software. Me apasiona la resolución de problemas mediante la aplicación de conceptos y tecnologías innovadoras. Tengo experiencia en desarrollo web utilizando HTML, CSS y JavaScript, y manejo frameworks como Vue y Angular. También tengo conocimientos en bases de datos con MySQL y en el uso de Figma para prototipado. Como miembro del equipo, aporto un sólido conocimiento en desarrollo de software y un compromiso constante con la excelencia en cada proyecto en el que participo. Estoy emocionado por aprender y colaborar con el equipo, así como por adquirir nuevas habilidades y conocimientos en las tecnologías que utilizaremos en nuestro trabajo.    | <img src="https://raw.githubusercontent.com/TechZo-1ASI0732-4453/Report/refs/heads/main/Resources/Chapter-I/Profiles/sandroquispesivana.png" alt="Imagen de Sandro Quispesivana"/> |

<br><br>

## 1.2 Solution Profile

### 1.2.1 Antecedentes y problemática

La economía lineal actual, caracterizada por el modelo de producir, usar y desechar, está generando un aumento preocupante en la acumulación de residuos y el uso insostenible de recursos naturales. Morseletto (2023) destaca que esta estructura económica predominante contribuye significativamente al aumento de residuos y la degradación ambiental. 

Esta forma de consumo no solo incrementa la cantidad de desechos sólidos, contamina los océanos y provoca la pérdida de biodiversidad, sino que también intensifica el cambio climático debido a las emisiones significativas de gases de efecto invernadero asociadas con la fabricación, transporte y eliminación de productos (Madaan et al., 2024). 

Según Liu y Zhong (2023), la extracción intensiva de materias primas para la producción de nuevos bienes está agotando los recursos naturales a un ritmo alarmante, lo que agrava aún más la situación ambiental. A esto se suma el crecimiento continuo de la población mundial, que se espera que aumente en 2000 millones de personas para el año 2050, multiplicando aún más la generación de residuos (Kruse-Andersen, 2023). 

Frente a esta problemática, nuestra aplicación propone una solución basada en la economía circular, que busca mantener los productos, materiales y recursos en uso durante el mayor tiempo posible.

Para explicar con más detalle esta situación, como grupo, usaremos la metodología de las 5W y 2H para darle más énfasis a los antecedentes y problemáticas a las que se enfrenta nuestra iniciativa de cambio:


**5W's y 2H's**

* **WHAT?** <br>
La acumulación diaria de residuos a nivel global está generando un impacto negativo en el medio ambiente y en la conservación de los recursos naturales del planeta. Este problema se debe a la falta de iniciativas para dar una segunda vida a los objetos en lugar de desecharlos, lo que contribuye a la sobrecarga de vertederos y al agotamiento de recursos.<br><br>


* **WHY?**<br>
Muchas personas no toman la iniciativa de reutilizar o intercambiar objetos que ya no necesitan, y en lugar de eso, optan por desecharlos. Esta falta de conciencia sobre las consecuencias ambientales a largo plazo resulta en un aumento de desechos y en el agotamiento de recursos naturales..<br><br>

* **WHO?**<br>
El problema afecta al público en general, pero en particular a aquellos que más necesitan apoyo en términos de recursos y asistencia. La aplicación está dirigida a usuarios interesados en adoptar prácticas de reutilización y sostenibilidad.<br><br>

* **WHEN?**<br>
Esta problemática es una constante con el pasar de los años ya que recién es que se está popularizando la cultura de reutilización y desarrollo sostenible, debido a que desde siempre se ha optado en primera instancia por solo desechar y no reutilizar.<br><br>

* **WHERE?**<br>
Aunque la problemática de los residuos y la falta de reutilización es global, la aplicación se enfocará inicialmente en la población peruana, con planes de expansión a otras regiones en función de los resultados y la demanda.<br><br>

* **HOW?**<br>
Se implementará una propuesta de solución mediante el desarrollo de una aplicación web y movil que permita a los usuarios publicar posts de objetos que deseen intercambiar por otras pertenencias, además de permitir realizar donaciones a organizaciones benéficas. Todo ello en una plataforma intuitiva, fácil de manejar y con opciones de personalización.<br><br>

* **HOW MUCH?**<br>
El presupuesto para el desarrollo de la aplicación web y movil varía en función de los requisitos específicos del proyecto. Se estima que podría oscilar entre S/. 20,000 y S/. 50,000, dependiendo de la complejidad y las características de la aplicación.<br><br>

### 1.2.2 Lean UX Process
#### 1.2.2.1 Lean UX Problem Statement
**Problem Statement 1:**  El contexto actual en el que nos encontramos nos demuestra que a diario se ve mucho más en práctica modelos de vida sostenible y que incluso se popularizan de manera más rápida por las redes sociales. De acuerdo a esto, cada vez la población busca darle una nueva vida a sus pertenencias y así evitar el desechar tantos objetos y de este modo contribuir con la disminución de residuos en el planeta.

Sin embargo, hemos notado que hay una gran dificultad al que este sector de la población tiene, el cual es que no hay una forma sencilla y práctica de darle un segundo uso a sus pertenencias, en este caso, enfocándonos en el intercambio de bienes. 
¿Cómo implementamos de manera eficaz un modelo de intercambio de pertenencias?<br><br>


**Problem Statement 2:** En la actualidad, se puede observar que hay una base sólida de organizaciones benéficas que siempre apoyan a diversos sectores vulnerables de la población, ya sea con donaciones de víveres, ropa, objetos de primera necesidad y/o apoyo económico.

Pese a ello, hemos identificado un factor crítico que afecta a muchas de estas organizaciones, es que no hay un modelo sólido que organice toda la información de estos grupos y que permita a los contribuidores tener un fácil acceso a todos los detalles correspondientes, ya sean campañas de donación o de aporte monetario benéfico.

¿Cómo podemos desarrollar una funcionalidad que permita a los usuarios realizar aportes benéficos de manera sencilla e intuitiva, facilitando la conexión entre Donadores y organizaciones?

#### 1.2.2.2 Lean UX Assumptions

 + **User Assumptions:** 

    + **¿Quién es el usuario?** <br>Nuestros usuarios son personas interesadas en dar un nuevo uso a sus pertenencias mediante el intercambio o donación. Esto incluye tanto a individuos que desean intercambiar objetos como a aquellos que buscan apoyar a organizaciones benéficas registradas en la plataforma.<br><br>

    + **¿Dónde encaja nuestro producto en su trabajo o en su vida?**<br> El producto se integra en la vida de los usuarios como una herramienta para fomentar un estilo de vida sostenible, permitiéndoles participar activamente en la economía circular y contribuir a la reducción de residuos.<br><br>

    + **¿Cuándo y cómo se utiliza nuestro producto?**<br> Nuestro producto es usado cuando los usuarios sientan que ya no necesitan más una pertenencia y en vez de solo desecharla, darle un nuevo uso para alguien más, intercambiándose por algo que sí necesite o realizando donaciones a organizaciones benéficas para aquellos que más lo necesitan.<br><br>


    + **¿Qué problemas resuelve nuestro producto?**<br>Cambiazo simplifica el intercambio y la donación de objetos, ofreciendo una plataforma segura y conveniente que promueve la reutilización y reduce el desperdicio. Con medidas de seguridad integradas, aborda las preocupaciones sobre transacciones fraudulentas, proporcionando una solución completa para una experiencia de intercambio confiable y sostenible.<br><br>


    + **¿Qué características son importantes?**<br> Que sea fácil de usar, intuitiva y que contenga las funcionalidades necesarias para que la experiencia del usuario sea la mejor, con opción de filtros para la búsqueda de ciertos artículos y/o también la inclusión de un chat privado entre usuarios para que puedan comunicarse y coordinar el intercambio, si es que ambos están de acuerdo con las pertenencias que ofrecen y desean recibir.<br><br>

    + **¿Cómo debe verse y comportarse nuestro producto?**<br> Nuestro producto debe tener una interfaz amigable para todos el público en general, incluir solo funcionalidades básicas y necesarias para no saturar a los usuarios con demasiada información.Además de ello debe mantenerse siempre con actualizaciones que vayan mejorando la optimización del proyecto.<br><br>

 + **Business Outcomes:** 

    1. **Creo que nuestros usuarios necesitan** tener un medio seguro y fácil de usar para poder realizar intercambios y/o donaciones de manera sencilla y eficaz.

    2. **Estas necesidades se pueden resolver con** una aplicación movil que tenga una interfaz intuitiva y que ofrezca que usuarios del Perú puedan realizar publicaciones de intercambio de sus pertenencias y solicitar cierto producto a cambio.

    3. **Nuestros usuarios iniciales son** el público en general del Perú que desee ser parte del cambio por un estilo de vida sostenible.

    4. **El valor #1 que un cliente quiere de nuestro servicio es que** ofrezca una forma rápida y sencilla de realizar publicaciones de intercambio y que tenga un sistema sólido para que los involucrados puedan coordinar el proceso respectivo con facilidad.

    5. **El usuario también puede obtener beneficios adicionales como**  tener un número ilimitado de publicaciones sobre intercambios que pueda realizar, además de poder obtener un “Boost” diario para que sus publicaciones siempre tengan preferencia al momento que aparezca tras una búsqueda por algún otro usuario.

    6. **Vamos a adquirir la mayoría de nuestros clientes a través de** publicidad en redes sociales tales como Instagram, Tiktok y Facebook, con una estrategia que promocione principalmente el impacto positivo que generaría el aplicar esta práctica de reutilización en el medio ambiente a largo plazo.

    7. **Haremos dinero a través de** ofrecer una suscripción premium que ofrecerá ciertos beneficios que hagan de su experiencia en CambiaZo mucho más satisfactoria y fácil.

    8. **Nuestras competencias principales son** grupos de Facebook que se dedican al intercambio, Me Sirve, HazTruequing y Trueques.

    9. **Los venceremos debido a** las funcionalidades que incluimos en nuestra propuesta de solución, además de la propia diferenciación de CambiaZo que tiene como logo principal, el ser un impulso para un cambio en la sociedad, el tener un estilo de vida sostenible.

    10. **Nuestro mayor riesgo es** que los usuarios no encuentren intercambios justos y puedan llegar a frustrarse por ello.

    11. **Resolveremos esto a través de** un proceso de verificación y control sobre la información que cada usuario coloca al momento de hacer un intercambio, para que no haya inconvenientes de posibles intercambios injustos o de broma.


#### 1.2.2.3 Lean UX Hypothesis Statements
**Creemos que** al tener una plataforma sólida para  poder realizar publicaciones de intercambios, los usuarios podrán contribuir con la metodología de una economía cíclica y de formar parte de un estilo de vida sostenible.
**Sabremos que es cierto** cuando las estadísticas de cuántos intercambios se van realizando al día sean más de 30, esto demostrará que nuestra propuesta de solución realmente está fomentando la reutilización de los objetos de las personas en general.

**Creemos que**  permitir la interacción entre los usuarios al momento de mostrar interés por un artículo, ayudará a que puedan coordinar el intercambio de mejor manera <br>**Sabremos que lo habremos logrado**  cuando se refleje a través de los comentarios, que más del 50% de los usuarios resalte el sistema de comunicación entre usuarios, previo al intercambio.


**Creemos que**  al tener la opción de realizar donaciones a personas de escasos recursos económicos, facilitará a los usuarios que deseen donar objetos que ya no utilizan, a hacerlo y a contribuir con este acto solidario.<br>**Sabremos que esto es cierto**  cuando la cantidad de usuarios que han donado a través de nuestra plataforma, supere el 10% de usuarios registrados dentro de la aplicación cada mes.



#### 1.2.2.4 Lean UX Canvas
La aplicación **CambiaZo**  es una plataforma digital diseñada para que los usuarios puedan deshacerse de los objetos que ya no desean tener, intercambiándolos por otros artículos que desean de otros usuarios. Además, tiene como objetivo principal convertirse en la plataforma digital líder de intercambio de productos, promoviendo una vida consciente y sostenible a nivel mundial.

<table>
    <tr>
        <td valign="top">
            <div align="center"><br><b>Business Problem</b></div><br>
            <p>El modelo de economía lineal actual causa acumulación de residuos y un uso insostenible de recursos. Falta una solución accesible para el intercambio y donación de bienes.<br><br>¿Cómo podemos facilitar un sistema sencillo y eficiente para que las personas intercambien y donen bienes?</p><br>
        </td>
        <td rowspan="2" valign="top">
            <div align="center"><br><b>Solutions</b></div><br>
            <ul>
            <li>Desarrollar una aplicación web para facilitar el intercambio de objetos entre usuarios.</li><br>
            <li>Permitir la donación de bienes a organizaciones benéficas.</li><br>
            <li>Implementar opciones de búsqueda y comunicación entre usuarios para coordinar intercambios.</li><br>
            <li>Incluir funcionalidades para registrar donaciones y asegurar transacciones seguras.</li><br>
            </ul><br>
        </td>
        <td valign="top">
            <div align="center"><br><b>Business Outcomes</b></div><br>
            <ul>
              <li>Satisfacción del usuario en intercambios y donaciones.</li><br>
              <li>Obtener financiamiento para expandir la app.</li><br>
              <li>Aumentar la visibilidad y alcance con marketing en redes sociales.</li>
            </ul><br>
        </td>
    </tr>
    <tr>
        <td valign="top">
            <div align="center"><br><b>Users</b></div><br>
            <ul>
              <li>Personas interesadas en intercambiar bienes no necesarios</li><br>
              <li>Personas interesadas en donar a organizaciones benéficas.</li>
            </ul><br>
        </td>
        <td valign="top">
            <div align="center"><br><b>User Outcomes & Benefits</b></div><br>
            <ul><li>Ahorro de dinero al obtener productos sin costo</li><br>
            <li>Deshacerse de objetos no deseados de manera útil.</li><br>
            <li>Acceso a nuevos artículos a través del intercambio y contribución a causas benéficas.</li>
            </ul><br>
        </td>
    </tr>
    <tr>
        <td valign="top">
            <div align="center"><br><b>Hypotheses</b></div><br>
            <p>Creemos que nuestra aplicación promoverá la economía circular y un estilo de vida sostenible, facilitando el intercambio y la donación de bienes.<br><br>Sabemos que esto es cierto cuando los usuarios realicen más de 30 intercambios diarios y más del 10% de los usuarios registrados participen en donaciones mensuales.</p><br>
        </td>
        <td valign="top">
            <div align="center"><br><b>What's the most important thing we need to learn first?</b></div><br>
            <ul>
            <li>Comprender las necesidades y expectativas de los usuarios sobre el intercambio y la donación de bienes.</li><br>
            <li>Identificar las características más valoradas de la aplicación y cómo garantizar la seguridad en las transacciones.</li>
            <br>
            <li>Recopilar feedback sobre las funcionalidades y posibles mejoras.</li>
            </ul><br>
        </td>
        <td valign="top">
            <div align="center"><br><b>What's the least amount of work we need to do to learn the next most important thing?</b></div><br>
            <ul><li>Incorporar una función de comentarios y sugerencias. </li><br>
            <li>Realizar encuestas regulares para ajustar la app según el feedback.</li>
            </ul><br>
        </td>
    </tr>
</table>
<br>

</div>

## 1.3 Segmentos Objetivo

Esta sección incluye la descripción de los segmentos asociados al dominio del problema, incluyendo características geográficas y demográficas. Por lo tanto, con el fin de desarrollar un producto que satisfaga las necesidades de nuestros clientes, TechZo se enfocará en los siguientes segmentos de la población:

+ **Personas adultas que desean obtener nuevos artículos (Intercambiadores):**<br>
Estas personas buscan deshacerse de productos que ya no desean y adquirir nuevos artículos de su interés mediante intercambios.
  + **Características demográficas:** Personas entre 18 y 55 años, con artículos no deseados que están interesados en intercambiarlos por otros que necesitan. Este rango de edad fue seleccionado porque, según la distribución de la población por segmentos de edad mostrada en la [Imagen 1](#imagen-1), representa el 53.9% de la población total del país, equivalente a 18,037,900 personas (CPI Research, 2022).

    <div align="center">
	    <strong id="imagen-1">Imagen 1: Distribución de la población en Perú por segmentos de edad en 2022 (CPI Research, 2022)</strong><br><br>
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-I/Target-Segment/estadistica-segmentos.PNG?raw=true" alt="Estadistica Segmentos 2" style="width: 500px; height: auto;">
    </div><br><br>

  + **Características geográficas:** Personas que residen en Perú.<br>
  + **Motivaciones y Comportamientos:** A menudo motivados por la necesidad de actualizar sus pertenencias o por la falta de recursos para comprar nuevos artículos. En un estudio realizado por la Universidad Nacional del Altiplano en Puno, se identificó que una de las principales razones para realizar trueques es la falta de dinero. Este rango de edad fue seleccionado porque, según la información provista en la [Imagen 2](#imagen-2), se destacan diversas razones por las cuales las personas adultas participan en intercambios de artículos. La principal razón es la "Falta de dinero", representando el 56% de las respuestas, seguida de otros motivos como "Falta de trabajo" y "Por costumbre", entre otros.

     <div align="center">	
	     <strong id="imagen-2">Imagen 2: Motivos para Realizar Trueques según el Estudio de la Universidad Nacional del Altiplano</strong><br><br>
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-I/Target-Segment/cuadro-estadistica-1.PNG?raw=true" alt="Estadistica Segmentos" style="width: 500px; height: auto;"><br><br>
	
    </div>
  + **Preferencias de Uso:** Valoran una plataforma intuitiva que facilite la búsqueda y el intercambio de productos. Prefieren opciones que ofrezcan seguridad y transparencia en las transacciones.<br><br>


+ **Personas adultas que desean donar artículos que ya no utilizan (Donadores):**<br>
“Cambiazo” es fundamental como herramienta para realizar donaciones, ya que permite que personas de escasos recursos puedan recibir donaciones de objetos de personas que ya no utilizan sus artículos y desean donarlos.

    + **Características demográficas:** Personas entre 15 y 60 años de edad con la voluntad de donar objetos propios que ya no utilizan a personas de escasos recursos económicos.

    + **Características geográficas:** Personas que residen en Perú.

    + **Motivaciones y Comportamientos:** Buscan contribuir a la comunidad y ayudar a quienes están en situación de necesidad. Valoran plataformas que les permitan realizar donaciones de manera sencilla y eficiente.

    + **Preferencias de Uso:** Prefieren una aplicación que facilite el proceso de donación, ofreciendo una lista de organizaciones benéficas y un sistema fácil de utilizar para coordinar las donaciones.

<br><br>


<div style="page-break-after: always;"></div>

# Capítulo II: Requirements Elicitation & Analysis

## 2.1 Competidores

En esta sección se identificarán los mejores referentes para posteriormente realizar un análisis competitivo que nos ayudará a saber nuestro posicionamiento y el valor agregado que ofreceremos en el mercado. 

Según la investigación, se descubrieron aplicaciones webes y/o apps webs similares. Sin embargo, estamos considerando tres competidores directos o indirectos que se parezcan más a nuestra startup.

* **Trueques.com**<br>
Plataforma que ofrece una amplia gama de servicios de intercambio, incluidos intercambios de servicios y artículos de segunda mano. Los usuarios pueden buscar y publicar ofertas de intercambio, así como participar en eventos y actividades comunitarias relacionadas con el intercambio.<br><br>

* **HazTruequing**<br>
Plataforma en línea que permite a los usuarios intercambiar servicios y artículos de segunda mano de manera fácil y segura. Los usuarios pueden publicar lo que tienen disponible para el intercambio y buscar lo que necesitan, creando así una comunidad de intercambio activa y diversa.<br><br>


* **Me Sirve**<br>
Aplicación web que ofrece una forma conveniente de intercambiar y adquirir artículos de segunda mano. Los usuarios pueden publicar lo que tienen para intercambiar, buscar lo que necesitan y comunicarse directamente con otros usuarios para concretar los intercambios.<br><br>

### 2.1.1 Análisis Competitivo

En esta sección se realizará el análisis competitivo de los competidores identificados en la sección inicial con el objetivo de tener una idea más clara sobre nuestro producto frente a los competidores y aprender para mejorar nuestro producto.

<table>
<thead>
  <tr>
    <th colspan="6">Competitive Analysis Landscape<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td colspan="2">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="4">Este análisis se lleva a cabo para poder investigar, analizar y comparar el comportamiento de los competidores directos o indirectos en el mercado</td>
  </tr>
  <tr>
    <td colspan="2">
        <div align="center">Nombre</div>
    </td>
    <td>
		<div align="center">Cambiazo<br></div>
	</td>
    <td>
		<div align="center">Trueques.com</div>
	</td>
    <td>
		<div align="center">Haztruequing</div>
	</td>
    <td>
		<div align="center">Me Sirve</div>
	</td>
  </tr>
  <tr>
    <td colspan="2">
        <div align="center">Logo</div>
    </td>
    <td>
		<div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/logo-cambiazo.png?raw=true"alt="Cambiazo logo" /></div>
		</td>
    <td>
		<div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Competitors/logo-trueques.PNG?raw=true"alt="Trueques.com logo" /></div>
		</td>
    <td>
		<div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Competitors/logo-haztruequing.png?raw=true"alt="Haztruequing logo" /></div>
		</td>
    <td>
		<div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Competitors/logo-mesirve.png?raw=true"alt="Me sirve logo" /></div>
		</td>
  </tr>
  <tr>
    <td rowspan="2">Perfil</td>
    <td>Overview</td>
    <td>Aplicación web y movil que conecta a personas interesadas en darle un nuevo uso a sus pertenencias mediante intercambios o donaciones, enfocándose en la sostenibilidad y la economía circular.
	</td>
    <td>Página Web para intercambio de bienes y servicios entre usuarios, fomentando la economía colaborativa y la reutilización de recursos.</td>
    <td>Plataforma para intercambiar servicios y artículos de segunda mano de manera gratuita, promoviendo un estilo de vida sostenible y consciente.</td>
    <td>App para intercambiar bienes y servicios de manera segura y eficiente, promoviendo la reutilización y la solidaridad entre usuarios.</td>
  </tr>
  <tr>
    <td>Ventaja Competitiva <br>¿Qué valor ofrece a los clientes?</td>
    <td>Intercambio de productos o servicios. <br><br>Donación de objetos a ONGs afiliadas</td>
    <td>Intercambio directo de bienes y servicios sin dinero, fomentando la reutilización y colaboración.</td>
    <td>Intercambio de servicios y artículos de segunda mano, promoviendo un estilo de vida sostenible.</td>
    <td>Intercambio bienes y servicios, promoviendo la reutilización y la solidaridad.
</td>
  </tr>
  <tr>
    <td rowspan="2">Perfiles de Marketing<br></td>
    <td>Mercado Objetivo<br></td>
    <td>Personas interesadas en  intercambiar o donar sus pertenencias.</td>
    <td>Personas que buscan intercambiar productos y servicios</td>
    <td>Personas interesados en intercambiar servicios y artículos de segunda mano</td>
    <td>Usuarios interesados en darle un nuevo propósito a sus pertenencias mediante intercambios.</td>
  </tr>
  <tr>
    <td>Estrategias de marketing</td>
    <td>Publicidad en Foros y Redes sociales</td>
    <td>Publicidad en redes sociales</td>
    <td>Publicidad en redes sociales</td>
    <td>Publicidad en redes sociales</td>
  </tr>
  <tr>
    <td rowspan="3">Perfil de Producto<br></td>
    <td>Productos &amp; Servicios</td>
    <td>Intercambiar bienes o servicios, donar a ONGs</td>
    <td>Intercambiar bienes o servicios</td>
    <td>Intercambiar bienes o servicios</td>
    <td>Intercambiar bienes o servicios</td>
  </tr>
  <tr>
    <td>Precios y Costos</td>
    <td>Free y Premium desde $2.99 por mes</td>
    <td>Free</td>
    <td>Free</td>
    <td>Free y Premium $2.99 por mes</td>
  </tr>
  <tr>
    <td>Canales de Distribución (Web y/o  Movil)</td>
    <td>Web y Movil</td>
    <td>Web</td>
    <td>Web</td>
    <td>web</td>
  </tr>
  <tr>
    <td rowspan="4">Análisis SWOT</td>
    <td>Fortalezas</td>
    <td>Conexión intuitiva para intercambiar o donar objetos.<br><br>Amplia variedad de opciones para los usuarios.<br><br>Posibilidad de personalización en los intercambios.<br><br>Incorporación de automatización e innovación en la plataforma.</td>
    <td>Plataforma intuitiva para intercambiar bienes y servicios.<br><br>Amplia variedad de opciones disponibles.<br><br>Posibilidad de personalizar los intercambios.</td>
    <td>Plataforma confiable y amplia con una gran base de usuarios.<br><br>Compromiso con la sostenibilidad y la economía circular.</td>
    <td>Plataforma intuitiva y segura para intercambiar bienes y servicios.<br><br>Variedad de opciones disponibles para los usuarios.<br><br>Interfaz fácil de usar para una experiencia positiva.</td>
  </tr>
  <tr>
    <td>Debilidades</td>
    <td>Limitaciones en la disponibilidad de objetos y servicios.<br><br>Posibles dificultades técnicas en la gestión de transacciones y seguridad de datos.</td>
    <td>Posibles dificultades para garantizar la equidad en los intercambios.<br><br>Limitaciones técnicas que puedan afectar la funcionalidad.</td>
    <td>Posibles desafíos relacionados con la competencia de otras plataformas y la seguridad de las transacciones.</td>
    <td>Posibles desafíos con seguridad de transacciones y gestión de reclamos.</td>
  </tr>
  <tr>
    <td>Oportunidades</td>
    <td>Aprovechar la conciencia creciente sobre sostenibilidad y consumo responsable.<br><br>Desarrollar alianzas con ONGs para ampliar el impacto social.<br><br>Expandir la plataforma a nivel nacional e internacional.</td>
    <td>Expandir la plataforma para incluir nuevas categorías de productos y servicios.<br><br>Establecer alianzas con organizaciones benéficas para ampliar el impacto social.</td>
    <td>Expandir la plataforma a nivel nacional e internacional.</td>
    <td>Aprovechar la conciencia creciente sobre economía colaborativa y sostenibilidad.<br><br>Expandir la plataforma con más servicios y funciones para mejorar la experiencia.</td>
  </tr>
  <tr>
    <td>Amenazas</td>
    <td>Al ser una aplicación nueva, puede que no tenga la demanda esperada.<br><br>Competencia de otras plataformas.<br>Cambios en las preferencias del usuario.</td>
    <td>Mejor organizacion del sitio web<br><br>Cambios en las preferencias del usuario.</td>
    <td>Mejor interfaz, mas amigable e intuitiva<br><br>Cambios en las preferencias del usuario.</td>
    <td>Mejorar la seguridad de datos y privacidad de usuarios.<br><br>Cambios en las preferencias del usuario.</td>
  </tr>
</tbody>
</table>


### 2.1.2 Estrategias y tácticas frente a competidores

En esta sección se analizarán las estrategias y tácticas que se usarán para aprovechas las debilidades de la competencia y afrontar sus fortalezas. De la misma forma con las amenazas y oportunidades de la competencia.

Hemos empleado el análisis FODA para identificar las oportunidades y amenazas en el mercado, así como para evaluar nuestras fortalezas y debilidades internas. Este enfoque nos ha permitido concebir estrategias y tácticas adecuadas en consonancia con nuestro entorno y los recursos disponibles en base a nuestros dos segmentos objetivos.


**Estrategia de Diferenciación:** 

+ Para satisfacer las necesidades del **Segmento de Intercambiadores**, nos enfocamos en ofrecer una plataforma de intercambio intuitiva y dinámica que permita a los usuarios encontrar fácilmente los artículos deseados y realizar intercambios de manera rápida y segura. Implementaremos funciones avanzadas de búsqueda y filtros personalizables para facilitar la búsqueda de nuevos artículos.

+ Para el **Segmento de Donadores**, nos distinguimos al proporcionar una experiencia de donación gratificante y transparente. Estableceremos alianzas con organizaciones benéficas para ampliar las opciones de donación.

**Estrategia de Liderazgo en Costos:** 

+ Para el **Segmento de Intercambiadores**, nos comprometemos a mantener tarifas de intercambio competitivas y transparentes, y a ofrecer promociones especiales y descuentos para incentivar la participación activa en la plataforma.

+ En cuanto al **Segmento de Donaciones**, nuestra estrategia se centra en ofrecer una plataforma de donación sin costos ocultos ni tarifas adicionales. Nos comprometemos a garantizar que el proceso de donación sea completamente gratuito y accesible para todos los usuarios.

**Estrategia de Marketing:**

Para ambos segmentos, implementaremos una estrategia de marketing centrada en la sensibilización y la educación sobre los beneficios del intercambio y la donación. Desarrollaremos contenido informativo y atractivo que destaque las ventajas económicas, ambientales y sociales de participar en nuestra plataforma.

**Tácticas:**
- Creación de campañas publicitarias dirigidas a cada segmento objetivo para resaltar los beneficios específicos de la plataforma de intercambio y donación.
- Implementación de programas de referidos para incentivar la participación de usuarios existentes y expandir nuestra base de usuarios.
- Desarrollo de funciones adicionales en la plataforma, como sistemas de valoración y comentarios, para aumentar la confianza y la participación de los usuarios.
- Establecimiento de alianzas con organizaciones locales y empresas para promover eventos de intercambio y donación, generando así mayor visibilidad y compromiso con la comunidad.


## 2.2 Entrevistas

En esta sección se abordará la investigación en base a la información que se obtendrá de los segmentos entrevistados con el objetivo de conocer mejor a nuestros segmentos objetivos y aprender de ellos y sus procesos.


### 2.2.1 Diseño de entrevistas

**Preguntas sobre información personal**

*	¿Cuál es su nombre completo?
*	¿Qué edad tienes?
*	¿A qué te dedicas?
*	¿Cuál es tu estado civil?
*	¿En qué ciudad resides?
*	¿Eres extrovertido o calmado?
*	¿Eres una persona que toma decisiones analizando los hechos o te dejas llevar por tus sentimientos?
*	¿Qué smartphone posee? ¿Android o IOS?
*	¿Usas aplicaciones o programas en especial? ¿Cuáles?<br><br>


**Segmento objetivo 1:** Personas adultas que desean obtener nuevos artículos (Intercambiadores)

**Introducción:**

Buenos días/tardes/noches, mi nombre es [Nombre del entrevistador], y en esta ocasión tengo el agrado de poder entrevistar a [Nombre del entrevistado], quien es una persona que le gusta obtener nuevos objetos a través del intercambio.
Desde ya quiero agradecerle por su presencia y tiempo que me está brindando.

**Inmersión:**

1. ¿De qué forma se contacta con otras personas al momento de querer intercambiar alguno de los objetos que ya no usa?
2. ¿Cómo ha sido su experiencia previa con aplicaciones de intercambio de productos?
3. ¿Qué tipo de productos considera más viables para intercambiar a través de una aplicación web/movil?

**Indagación:**

4. ¿Cuáles son las principales preocupaciones o dudas que tendría al utilizar una aplicación de intercambio de productos por primera vez?
5. ¿Qué características o funciones consideraría primordiales para sentirse seguro y cómodo al realizar intercambios en línea?
6. ¿Cómo cree usted que una aplicación de intercambio de objetos podría fomentar la confianza entre los usuarios para realizar intercambios justos y seguros?
7. ¿Qué tipo de productos considera que tendrían mayor demanda por parte de personas de su edad y ubicación geográfica?

**Verificación:**

8. ¿Qué medidas tomaría para estar seguro de que los productos que está intercambiando cumplen con sus expectativas?
9. ¿Cómo cree que la comunidad de usuarios podría contribuir a garantizar la veracidad de los productos ofrecidos dentro de la aplicación?
10. ¿Qué fuentes utilizaría para verificar la confiabilidad de una aplicación de intercambios en línea como CambiaZo?

**Medición:**

11. ¿Qué beneficios espera obtener al utilizar una aplicación como CambiaZo en comparación con otros métodos de adquisición de productos?
12. ¿Cómo considera que las personas pueden contribuir al desarrollo de una comunidad más sostenible y consciente en su ciudad?
13. ¿Cuál considera que es el mayor desafío que enfrenta la sociedad en Lima en la actualidad para mantener un consumo consciente, y cómo cree que podría tratarse?

**Cierre:**

Bueno esto ha sido todo por esta ocasión, una vez más quisiera agradecerle por su tiempo, muchas gracias y hasta luego.<br><br>


**Segmento objetivo 2:** Personas adultas que desean donar artículos que ya no utilizan (Donadores)

**Introducción:**

Buenos días/tardes/noches, mi nombre es [Nombre del entrevistador], y en esta ocasión tengo el agrado de poder entrevistar a [Nombre del entrevistado], quien es una persona que le gusta realizar donaciones a personas de escasos recursos.
Desde ya quiero agradecerle por su presencia y tiempo que me está brindando.

**Inmersión:**

1. ¿De qué forma ha realizado donaciones a personas con escasos recursos económicos?
2. ¿Cómo ha sido su experiencia previa con la donación de artículos a personas necesitadas o a organizaciones benéficas?
3. ¿Qué tipo de artículos consideraría más adecuados para donar a través de una aplicación web/movil como CambiaZo?

**Indagación:**

4. ¿Cuáles son las principales preocupaciones que tendría al utilizar una aplicación como CambiaZo por primera vez?
5. ¿Qué funciones o características buscaría en una aplicación web/movil al momento de querer realizar una donación en línea?
6. ¿Cómo cree que una aplicación web/movil como CambiaZo podría aumentar la cantidad de donaciones en el Perú?

**Verificación:**

7. ¿Cómo podría una aplicación como CambiaZo garantizar la transparencia y autenticidad de las donaciones realizadas?
8. ¿Qué importancia le otorgaría a la posibilidad de seguir el destino de sus donaciones y conocer el impacto que tienen en la comunidad receptora?
9. ¿Qué criterios utilizaría para verificar la confiabilidad y legitimidad de una plataforma de donaciones en línea como CambiaZo?

**Medición:**

10. ¿Qué beneficios espera obtener al realizar donaciones utilizando CambiaZo en comparación con otros métodos de donación tradicionales?
11. ¿Cómo mediría el impacto de sus donaciones a través de una aplicación web/movil como CambiaZo en términos de ayudar a personas necesitadas?
12. ¿Qué cambios o mejoras le gustaría ver en la funcionalidad de CambiaZo para que se convierta en una herramienta más efectiva para donar artículos?
13. ¿Cómo cree que el uso de aplicaciones en las que puede donar, como CambiaZo, podría contribuir al desarrollo de una comunidad más solidaria y conectada en Lima?

**Cierre:**

Bueno esto ha sido todo por esta ocasión, una vez más quisiera agradecerle por su tiempo, muchas gracias y hasta luego.<br><br>


### 2.2.2 Registro de entrevistas

En esta sección presentamos los registros de las entrevistas que realizamos para cada segmento objetivo de nuestra aplicación movil.


### **Segmento Intercambiadores**<br>


<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #1<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Sebastian Valente</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Lobato Pozo</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>20 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>La Molina</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom</td>
  </tr>
  <tr>
    <td>Motivacion</td>
    <td>Intercambiar objetos promoviendo el desarrollo sostenible</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>Preocupación sobre posibles estafas</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>Computadora Windows, Smartphone Android</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Claudio Sandro Quispesivana Torres</td>
  </tr>
   <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://raw.githubusercontent.com/TechZo-1ASI0732-4453/Report/refs/heads/main/Resources/Chapter-II/Interviews/sebastianlobato_interview.png" alt="Entrevista Daniella Vargas"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214059_upc_edu_pe/ETvVZXVN-x9FkEDkb_E9cpUBbl0UYgt8J7QA3XiVn1SBPA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=IEi8AE" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>00:00 min - 06:55 min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>Durante la entrevista, Sebastián Lobato, un estudiante de Ingenieria de Software de 20 años que vive en Lima y utiliza un smartphone Android, relató sus experiencias previas realizando intercambios de artículos con personas de su entorno. Aunque ha participado en este tipo de actividades antes, menciona que no ha encontrado una plataforma dedicada que le brinde seguridad al momento de intercambiar sus objetos. Para Sebastián, una aplicación móvil como CambiaZo podría ser una herramienta ideal para facilitar estos intercambios, ya que genera un ambiente de confianza entre los usuarios. Además, señala que los artículos más solicitados suelen ser productos tecnológicos como celulares, tablets, laptops y videojuegos en buen estado. Sin embargo, también expresa inquietudes sobre la fiabilidad de la aplicación, por lo que valora funciones como la posibilidad de subir fotos y contar con una sección de reseñas. Sebastián espera que el uso de CambiaZo le permita realizar intercambios de manera más segura y eficiente, contribuyendo así al crecimiento de una comunidad más sostenible y conectada en Lima.
</td>
  </tr>
</tbody>
</table><br>



<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #2<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Edu Orlando</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Gutierrez Vasquez</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>19 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>La Molina</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom, Discord</td>
  </tr>
  <tr>
    <td>Motivacion</td>
    <td>Seguridad y calidad en intercambios de productos</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>Limitaciones de seguridad y calidad en Facebook</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>Laptop Windows, Smartphone Android</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google Chrome, Firefox</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Ian Haziel Donato Santisteban Palomino</td>
  </tr>
    <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-II/Interviews/edugutierez_interview.PNG?raw=true" alt="Entrevista Edu Gutierrez"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214059_upc_edu_pe/ETvVZXVN-x9FkEDkb_E9cpUBbl0UYgt8J7QA3XiVn1SBPA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=IEi8AE" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duracion<br></td>
    <td>6:56 min - 11:52 min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>En la entrevista con Edu, se revelaron detalles sobre su experiencia y preferencias en cuanto a realizar intercambios de objetos. Edu suele contactarse con otras personas para intercambiar objetos a través de Facebook y WhatsApp, pero encuentra limitaciones en estas plataformas en términos de seguridad y calidad de los productos.Considera que una plataforma como Cambiazo sería de gran ayuda para simplificar este proceso. Además, mencionó que le gustaría que la plataforma implementara funciones como un sistema de verificación de identidad y calidad de los productos, así como un sistema de evaluaciones entre usuarios para garantizar la confianza y seguridad en los intercambios. Edu también señaló que los productos de ocio y entretenimiento tendrían mayor demanda entre personas de su edad y ubicación geográfica. <br>En cuanto a sus preocupaciones, destacó la seguridad de las transacciones y la calidad de los productos ofrecidos. Para garantizar la calidad de los productos, Edu se basaría en las descripciones detalladas, las fotos proporcionadas por los usuarios y las evaluaciones de otros usuarios. También considera que la comunidad de usuarios podría contribuir a garantizar la veracidad de los productos ofrecidos dentro de la plataforma mediante la retroalimentación honesta y la denuncia de prácticas fraudulentas.<br>En términos de beneficios esperados al utilizar una aplicación como Cambiazo, Edu espera una mayor variedad de productos y una experiencia de intercambio más segura. Además, considera que el intercambio de productos usados puede contribuir al desarrollo de una comunidad más sostenible y consciente en su ciudad.
</td>
  </tr>
</tbody>
</table>


<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #3<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Gonzalo David</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Espino Rojas</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>21 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Santiago de Surco</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom, Discord</td>
  </tr>
  <tr>
    <td>Motivacion</td>
    <td>Promover los modelos de vida con desarrollo sostenible, para impulsar una economía cíclica</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>Que sus productos publicados no tengan la relevancia necesaria</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>Smatphone Android, Laptop Windows</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Joseph Alexis Huamani Mandujano</td>
  </tr>
   <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Interviews/gonzaloespino_interview.png?raw=true" alt="Entrevista Gonzalo Espino"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214059_upc_edu_pe/ETvVZXVN-x9FkEDkb_E9cpUBbl0UYgt8J7QA3XiVn1SBPA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=IEi8AE" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>11:53 min - 16:20 min</td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>Durante la entrevista, Gonzalo David Espino Rojas, un estudiante de marketing de 21 años que reside en Lima y posee un smartphone Android, comparte su experiencia personal en el ámbito de los intercambios. Gonzalo señala que en sus intentos previos de realizar este tipo de transacciones, ha experimentado dificultades con la veracidad del estado de los productos ofrecidos y la fiabilidad de los usuarios involucrados, lo cual ha generado incertidumbre y preocupación. Para abordar estas inquietudes, Gonzalo destaca la necesidad de contar con una aplicación web que ofrezca diversas funciones y características, como un sistema de calificación y reseñas de los usuarios, un riguroso proceso de verificación de identidad y una sólida política de privacidad y seguridad de datos. Asimismo, Gonzalo enfatiza la importancia de tener una comunidad activa dentro de la plataforma, ya que esto le permitiría evaluar de manera más precisa la confiabilidad de los usuarios y la calidad de los productos antes de concretar cualquier intercambio. En general, Gonzalo se muestra interesado en probar una aplicación como CambiaZo, ya que espera obtener beneficios como ahorrar dinero, contribuir al cuidado del medio ambiente y formar parte de una comunidad que promueve un consumo más consciente y sostenible.
</td>
  </tr>
</tbody>
</table><br>




<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #4<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Freddy Alejandro</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Cuadros Contreras</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>19 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Santiago de Surco</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Google Chrome, Zoom</td>
  </tr>
  <tr>
    <td>Motivacion</td>
    <td>Obtener objetos deseados de manera más sencilla</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>Dificultades en obtener objetos de calidad a través de grupos de Facebook</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>Laptop Windows, Smartphone IOS</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Jeremy Joel Quispe Andia</td>
  </tr>
  <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Interviews/freddycuadros_interview.png?raw=true" alt="Entrevista Freddy Cuadros"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214059_upc_edu_pe/ETvVZXVN-x9FkEDkb_E9cpUBbl0UYgt8J7QA3XiVn1SBPA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=IEi8AE" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duracion<br></td>
    <td>16:21 min - 20:50 min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>Freddy Cuadros nos menciona que CambiaZo facilita el contacto entre usuarios mediante un sistema de mensajería interna, lo que ha hecho que su experiencia con aplicaciones de intercambio sea positiva, permitiéndole reutilizar objetos y adquirir otros de forma sostenible. Considera que los productos más viables para intercambiar a través de CambiaZo son libros, ropa y pequeños electrodomésticos. Sus principales preocupaciones al usar CambiaZo son la autenticidad de los productos y la seguridad en las transacciones. Para sentirse seguro, considera esenciales la verificación de identidad, métodos de pago seguros y un sistema de valoraciones. Los productos tecnológicos y de moda son muy demandados, y para asegurarse de que cumplan con sus expectativas, solicita fotos y descripciones detalladas. Un sistema de valoraciones y comentarios, junto con la consulta de opiniones en redes sociales, ayuda a verificar la confiabilidad de CambiaZo. 
    <br>Además, estos intercambios ofrecen beneficios como el ahorro económico y una forma más sostenible de consumir, promoviendo el reciclaje y la reutilización para abordar la acumulación de productos no utilizados.
</td>
  </tr>
</tbody>
</table>


<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #5<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Erick Maycol</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Huallullo Cirineo</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>21 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Ate</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom</td>
  </tr>
  <tr>
    <td>Motivacion</td>
    <td>Relizar intercambios seguros</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>No obtener lo que busca al realizar intercambios a través de Facebook.</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>Smartphone IOS, Laptop Windows</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Jeremy Joel Quispe Andia</td>
  </tr>
    <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Interviews/erickmaycol_interview.png?raw=true" alt="Entrevista Erick Huallullo"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214059_upc_edu_pe/ETvVZXVN-x9FkEDkb_E9cpUBbl0UYgt8J7QA3XiVn1SBPA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=IEi8AE" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duracion<br></td>
    <td>20:51 min - 25:41 min</td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>Erick Huallullo nos menciona que al contactar a otros usuarios para intercambiar objetos, utiliza el sistema de mensajería de CambiaZo, lo que ha facilitado una experiencia generalmente positiva y segura. Considera que productos como ropa, libros y pequeños dispositivos electrónicos son los más viables para intercambiar a través de CambiaZo, aunque sus principales preocupaciones al usar la plataforma son la seguridad de la transacción y la autenticidad de los productos. Funciones como la verificación de identidad y un sistema de calificaciones en CambiaZo son esenciales para fomentar la confianza entre los usuarios. Para verificar la confiabilidad de CambiaZo, revisa opiniones en tiendas de aplicaciones y foros. Además, cree que el uso de CambiaZo puede promover un consumo más sostenible, abordando desafíos como la cultura de consumo desmedido en Lima mediante la promoción del reciclaje y la reutilización de productos.
</td>
  </tr>
</tbody>
</table><br>

<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #6<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Luis Junior</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Valero Medina</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>20 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Los Olivos</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Google Chrome, Zoom</td>
  </tr>
  <tr>
    <td>Motivacion</td>
    <td>Adquisición de nuevos artículos sin tener que comprarlos</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>Mala experiencia realizando intercambios</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>Smartphone Android, Laptop Windows</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Ian Haziel Donato Santisteban Palomino</td>
  </tr>
    <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Interviews/luisvalero_interview.png?raw=true" alt="Entrevista Luis Valero"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214059_upc_edu_pe/ETvVZXVN-x9FkEDkb_E9cpUBbl0UYgt8J7QA3XiVn1SBPA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=IEi8AE" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duracion<br></td>
    <td>25:41 min - 31:12 min</td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>En la entrevista con Luis Valero, se discutieron sus hábitos y opiniones sobre el intercambio de productos. Luis utiliza grupos de WhatsApp y Facebook para intercambiar objetos, aunque ha tenido experiencias mixtas, con algunos intercambios exitosos y otros problemáticos.Él considera que los productos más viables para intercambiar a través de una aplicación web son libros, ropa, gadgets pequeños y artículos para el hogar. Mencionó que, en su entorno, hay una alta demanda de cartas de colección, videojuegos, dispositivos electrónicos y artículos deportivos.Sus principales preocupaciones al usar una nueva aplicación de intercambio incluyen la seguridad y la confiabilidad de los usuarios. Destaca la importancia de contar con calificaciones, verificación de identidad y un chat seguro para sentirse cómodo al realizar intercambios.Luis cree que CambiaZo podría ofrecer una plataforma más segura y confiable para estos intercambios, permitiéndole también ahorrar dinero y acceder a una variedad de productos. Para garantizar la calidad de los artículos, recomendaría pedir imágenes detalladas y revisar la reputación del usuario. Además, cree que la comunidad puede ayudar con reseñas honestas y reportando irregularidades.
</td>
  </tr>
</tbody>
</table><br>




### **Segmento Donadores**<br>

<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #1<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Jose Daniel Mario</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Calderon Huaman</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>20 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Carabayllo</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Discord</td>
  </tr>
    <tr>
    <td>Motivacion</td>
    <td>Adquisición de nuevos artículos sin tener que comprarlos</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>Preocupaciones sobre el destino de las donaciones.</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>Smartphone Android</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Claudio Sandro Quispesivana Torres</td>
  </tr>
    <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-II/Interviews/josecalderon_interview.png?raw=true" alt="Entrevista Jose Calderon"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214059_upc_edu_pe/ETvVZXVN-x9FkEDkb_E9cpUBbl0UYgt8J7QA3XiVn1SBPA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=IEi8AE" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>31:13 min - 36:06 min</td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>Jose Calderon comenta que ha hecho donaciones tanto por transferencias como a través de recolecciones locales, y que la experiencia le ha resultado satisfactoria, especialmente al colaborar con organizaciones en las que confía. Suele preferir donar productos de primera necesidad, ropa y materiales educativos utilizando plataformas como CambiaZo. Entre sus principales inquietudes al utilizar CambiaZo están la protección de sus datos personales y la efectividad del sistema. Por ello, considera fundamental contar con una interfaz intuitiva, opciones claras para elegir proyectos o beneficiarios, y la posibilidad de hacer seguimiento a sus donaciones. También destaca la importancia de la transparencia y la disponibilidad de informes sobre el uso de los fondos como elementos clave para confiar en la plataforma. Valora especialmente que el proceso de donación sea ágil y sencillo, y que pueda ver el impacto directo de sus aportes. Además, opina que una mayor personalización de las donaciones y la posibilidad de interactuar con los beneficiarios en CambiaZo contribuirían a fortalecer la cohesión social y a generar una mayor conciencia sobre las necesidades de las comunidades locales.
</td>
  </tr>
</tbody>
</table>
<br>

<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #2<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Carlos Arturo</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Adrianzen Flores</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>20 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Miraflores</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom, Discord</td>
  </tr>
  <tr>
    <td>Motivacion</td>
    <td>Donar a lo mas necesitados a traves de la iglesias</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>Experimenta dificultades al llevar un canasto lleno de ropa para donar.</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>Smatphone Android, Laptop Windows</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Firefox</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Mathias Andre Mendoza Carrion</td>
  </tr>
   <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-II/Interviews/entrevista-Arturo-Adrianzen.PNG?raw=true" alt="Entrevista Arturo Adrianzen"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214059_upc_edu_pe/ETvVZXVN-x9FkEDkb_E9cpUBbl0UYgt8J7QA3XiVn1SBPA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=IEi8AE" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>36:07 min - 41:20 min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>Durante nuestra conversación con Arturo, exploramos su experiencia en intercambios y los desafíos que ha enfrentado al no tener una plataforma dedicada para realizarlos. Arturo compartió sus vivencias al realizar donaciones a la iglesia, describiendo las dificultades que encontró al llevar un canasto lleno de ropa, lo cual consideró una tarea tediosa. Propuso la idea de que, para facilitar el proceso de donación de objetos, sería conveniente que alguien se encargará de recogerlos, evitando así la molestia de tener que trasladarse hasta el lugar de donación. Además, resaltó la importancia de garantizar seguridad para los usuarios, sugiriendo medidas como la presentación de una foto que confirme la realización de la donación, con el fin de evitar cualquier tipo de desconfianza. Arturo realiza una sugerencia final y significativa para Cambiazo, el cual, sería crear conciencia sobre la importancia de cada objeto donado para las personas necesitadas. Esto podría lograrse mediante la divulgación de testimonios conmovedores de aquellos que se han visto directamente afectados por estas donaciones, lo que, a su vez, podría inspirar a más personas a contribuir y seguir apoyando esta noble causa de forma continua.
</td>
  </tr>
</tbody>
</table>


<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #3<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Hernan Emilio</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Morales Calderon</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>19 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>San Juan de Lurigancho</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom,Word</td>
  </tr>
  <tr>
    <td>Motivacion</td>
    <td>Donar su ropa a personas necesitadas</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>Limitaciones de tiempo para buscar alguna ong</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>Laptop Windows, Smartphone Android</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Joseph Alexis Huamani Mandujano</td>
  </tr>
   <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-II/Interviews/entrevista-Hernan-Morales.PNG?raw=true" alt="Entrevista Hernan Morales"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214059_upc_edu_pe/ETvVZXVN-x9FkEDkb_E9cpUBbl0UYgt8J7QA3XiVn1SBPA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=IEi8AE" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duracion<br></td>
    <td>41:21 min - 45:06 min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>Durante la entrevista, Hernan compartió su experiencia y perspectiva sobre el proceso de donación a través de su participación en actividades de caridad y su interacción con plataformas dedicadas a esta causa. Destacó su compromiso con contribuciones significativas, incluyendo alimentos no perecederos, vestimenta en buen estado y juguetes, los cuales destinó a instituciones benéficas locales y hogares de acogida para niños desfavorecidos en su comunidad.Asimismo, Hernán enfatizó la importancia de la seguridad de los datos personales y la confiabilidad de los sistemas utilizados en estas plataformas, destacando la necesidad de contar con funcionalidades de protección que aseguren la integridad de la información personal y financiera de los donantes.Además, manifestó su interés en seguir de cerca el progreso de sus donaciones y su impacto en la comunidad, así como en mantenerse informado sobre el prestigio de la plataforma, su transparencia en la gestión de fondos y los testimonios de otros usuarios. Hernán expresó su deseo de una experiencia de donación más accesible y sencilla, y sugirió mejoras en la interfaz de usuario y una mayor variedad de opciones de donación específicas para fomentar la solidaridad y proporcionar un medio más fácil para ayudar a quienes más lo necesitan en la comunidad.
</td>
  </tr>
</tbody>
</table>


<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #4<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Mathias Adriano</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Hidalgo Lopez</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>19 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Santiago de Surco</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom</td>
  </tr>
  <tr>
    <td>Motivacion</td>
    <td>Donar su ropa a personas necesitadas</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>Limitaciones de tiempo para buscar alguna ong</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>Laptop Windows, Smartphone Android</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Mathias Andre Mendoza Carrion</td>
  </tr>
   <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Interviews/mathiashidalgo_interview.png?raw=true" alt="Entrevista Mathias Hidalgo"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214059_upc_edu_pe/ETvVZXVN-x9FkEDkb_E9cpUBbl0UYgt8J7QA3XiVn1SBPA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=IEi8AE" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duracion<br></td>
    <td>45:07 min - 56:39 min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>Mathias Hidalgo ha participado en donaciones a través de centros de caridad y páginas web, aunque siempre ha tenido cierta inseguridad debido a la posibilidad de estafas y a la falta de confianza que le generaban algunos lugares. A pesar de estas preocupaciones, Mathias está profundamente comprometido con causas benéficas y tiene la intención de seguir donando, específicamente ropa, recursos alimenticios y juguetes para ayudar a quienes lo necesitan. Para la aplicación Cambiazo, Mathias busca una mayor confiabilidad en todo el proceso de donación. Considera esencial que la aplicación ofrezca funcionalidades de seguridad robustas, como un sistema de mapeo o seguimiento en tiempo real de los productos donados, así como la certificación de las donaciones para garantizar su transparencia y autenticidad. Estas medidas no solo le darían mayor tranquilidad, sino que también incrementarían la confianza en la plataforma. Además, espera que Cambiazo le permita ahorrar tiempo en los trámites burocráticos y el papeleo, haciendo que el proceso sea más eficiente y fácil de manejar para cualquier usuario, independientemente de su nivel de experiencia con la tecnología. Mathias cree firmemente que, aunque el impacto de la aplicación podría no ser masivo, sí tiene el potencial de generar un cambio positivo y significativo en la vida de muchas personas, contribuyendo de manera valiosa al desarrollo social y económico del país. Considera que una plataforma como Cambiazo, con las características adecuadas, podría convertirse en una herramienta poderosa para canalizar la generosidad de la gente y facilitar el acceso a bienes esenciales para quienes más lo necesitan.
</td>
  </tr>
</tbody>
</table>



### 2.2.3 Análisis de entrevistas

En esta sección presentaremos el análisis de cada entrevista realizada por cada segmento objetivo. Con el fin de tener una información concisa para el desarrollo de nuestra aplicación.

### **Segmento objetivo 1:** Personas adultas que desean obtener nuevos artículos (Intercambiadores).<br>

Las personas que realizan intercambios de objetos tienen edades comprendidas entre 18 y 55 años y residen mayoritariamente en Lima, Perú. Los usuarios recurren a redes sociales como WhatsApp y Facebook para llevar a cabo este tipo de intercambios, pero su experiencia ha sido, en la mayoría de los casos, negativa debido a problemas de calidad con los productos intercambiados y a la falta de seguridad en el uso de dichos métodos.

**Hallazgos Claves:**

- El 100% de los entrevistados ha tenido malas experiencias al realizar intercambios a través de redes sociales. Esto se debe principalmente a problemas con la calidad de los productos y a la falta de garantías. La falta de confianza en estos métodos resalta la necesidad urgente de una plataforma más segura y confiable para intercambiar objetos.


- La mayoría de los intercambiadores realiza intercambios de manera regular, lo cual indica una alta demanda de una plataforma que facilite el proceso de manera más organizada y segura.


- Todos los entrevistados creen que CambiaZo podría resolver sus problemas actuales. Las principales funcionalidades deseadas incluyen un sistema de calificaciones robusto, un chat seguro, y herramientas para la verificación de identidad y la calidad de los productos intercambiados.<br><br>


**Análisis por medio de herramientas estadísticas:**


<div align="center">
	<img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-1-grafica-1.PNG?raw=true" alt="Estadistica 1" style="width: 600px; height: auto;">
</div>


Las respuestas de nuestros entrevistados evidencian que sería beneficioso y útil para una gran cantidad de la población, lo cual también se comprueba con un estudio realizado del año 2015 al 2017 por la Universidad Nacional del Altiplano, Puno, en el cuál se obtuvo que el motivo principal por el cual las personas realizan trueques es por la falta de dinero.


<div align="center">
	<img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-1-grafica-2.PNG?raw=true" alt="Estadistica 2" style="width: 600px; height: auto;"><br><br>
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-1-grafica-3.PNG?raw=true" alt="Estadistica 3" style="width: 600px; height: auto;"><br><br>
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-1-grafica-4.PNG?raw=truee" alt="Estadistica 4" style="width: 600px; height: auto;"><br><br>
</div>

El 100% de los entrevistados utiliza redes sociales para realizar intercambios. Sin embargo, todos los usuarios se sienten inseguros al utilizar estos métodos debido a malas experiencias previas, ya que el 100% ha tenido problemas al realizar intercambios a través de redes sociales. Estas malas experiencias reflejan claramente la necesidad de una plataforma más segura y confiable.


<div align="center">
	<img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-1-grafica-5.PNG?raw=true" alt="Estadistica 5" style="width: 600px; height: auto;"><br><br>
</div>

La mayoría de los intercambiadores realiza trueques con regularidad. Este dato subraya la demanda existente de una plataforma que pueda gestionar estos intercambios de manera más eficiente.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-1-grafica-6.PNG?raw=true" alt="Estadistica 6" style="width: 600px; height: auto;"><br><br>
</div>


Finalmente, todos los entrevistados expresan su disposición a usar CambiaZo como su principal medio para realizar intercambios. Este dato destaca el potencial de la plataforma para satisfacer una necesidad significativa en el mercado.<br><br>

**Estrategias para Abordar las Necesidades de los Intercambiadores:**

Para satisfacer las necesidades de los intercambiadores, CambiaZo debe enfocarse en proporcionar una plataforma segura y confiable que aborde los problemas que los usuarios han experimentado con las redes sociales. Implementar un sistema de calificaciones robusto es crucial, ya que permitirá a los usuarios evaluar y confiar en la calidad de los productos y en la reputación de los intercambiadores.

Es fundamental incorporar un chat seguro para facilitar las negociaciones y coordinar intercambios sin comprometer la privacidad. Además, ofrecer herramientas efectivas para la verificación de identidad y la calidad de los productos ayudará a minimizar el riesgo de fraudes y garantizar la integridad de los intercambios.

La plataforma debe ser intuitiva y fácil de usar, para que los intercambiadores puedan gestionar sus productos y realizar intercambios con eficiencia. El análisis muestra que la mayoría de los usuarios realiza intercambios con regularidad y que todos están dispuestos a adoptar una nueva plataforma que resuelva sus actuales problemas. Por lo tanto, CambiaZo debe diseñar una experiencia de usuario que no solo resuelva los inconvenientes actuales, sino que también se adapte a la alta demanda y expectativas del segmento.

Al implementar estas mejoras, CambiaZo estará bien posicionada para ofrecer una solución valiosa a los intercambiadores, promoviendo un entorno de intercambio seguro, eficiente y confiable.<br><br>


### **Segmento objetivo 2:** Personas adultas que desean donar artículos que ya no utilizan (Donadores).<br>

Los donadores tienen entre 15 y 60 años y residen mayoritariamente en Lima, Perú. Su principal motivación es el deseo genuino de ayudar a los demás. Sin embargo, enfrentan varios problemas que dificultan el proceso de donación, como la necesidad de llevar los artículos a lugares lejanos y la falta de evidencia de recepción.

**Hallazgos Claves:**

- Los donadores enfrentan dificultades significativas en el proceso de donación. Estos problemas incluyen la necesidad de transportar los artículos a ubicaciones distantes y la ausencia de evidencia de recepción, lo que hace que el proceso sea tedioso y poco satisfactorio.


- Todos los donadores consideran que CambiaZo podría simplificar el proceso de donación. Proponen funcionalidades como el rastreo de donaciones, la confirmación de recepción y la opción de programar la recolección de artículos. Estas características ayudarían a superar las dificultades actuales y mejorar la experiencia de donación.


- Los donadores sugieren la realización de campañas de sensibilización y colaboraciones con influencers para aumentar la participación y la frecuencia de las donaciones. Estas estrategias podrían amplificar el alcance de la plataforma y fomentar un mayor compromiso con la causa de la donación.<br><br>

**Análisis por medio de herramientas estadísticas:**

<div align="center">
	<img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-2-grafica-1.PNG?raw=true" alt="Estadistica 7" style="width: 600px; height: auto;"><br><br>
</div>

El gráfico de frecuencia de donaciones revela que los donadores realizan donaciones en intervalos que van de mensuales a anuales. Este patrón sugiere una disposición a donar con regularidad, siempre que el proceso sea simplificado y más accesible.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-2-grafica-2.PNG?raw=true" alt="Estadistica 8" style="width: 600px; height: auto;"><br><br>
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-2-grafica-3.PNG?raw=true" alt="Estadistica 9" style="width: 600px; height: auto;"><br><br>
</div>

El 100% de los donadores considera que el proceso de donación es complicado. Esta percepción subraya la necesidad de una plataforma que simplifique y facilite cada paso del proceso de donación. Además, todos creen que el proceso es complicado, lo que destaca la urgencia de implementar soluciones que aborden estos problemas y mejoren la experiencia general.

<div align="center">
	<img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-2-grafica-4.PNG?raw=true" alt="Estadistica 10" style="width: 600px; height: auto;"><br><br>
</div>

La mayoría de los donadores considera que los juguetes y la ropa son los objetos más adecuados para donar. Esta preferencia puede guiar a la plataforma en la priorización de categorías de donación.

<div align="center">
	<img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-2-grafica-5.PNG?raw=true" alt="Estadistica 11" style="width: 600px; height: auto;"><br><br>
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/segmento-objetivo-2-grafica-6.PNG?raw=true" alt="Estadistica 12" style="width: 600px; height: auto;"><br><br>
</div>

Todos los entrevistados mostraron su disposición para utilizar CambiaZo como su principal medio de donación. Además, creen que CambiaZo podría aumentar la frecuencia de sus donaciones, lo que resalta el potencial de la plataforma para facilitar y promover la donación.<br><br>

**Estrategias para Abordar las Necesidades de los Donadores:**

Para atender las necesidades de los donadores, CambiaZo debe enfocarse en simplificar el proceso de donación mediante la implementación de funcionalidades esenciales como la confirmación de recepción de artículos. Esta característica no solo proporciona tranquilidad a los donadores, sino que también cierra el ciclo de la donación de manera satisfactoria.

Además, el rastreo de donaciones es fundamental para asegurar que los artículos lleguen a sus destinatarios y para proporcionar a los donadores visibilidad sobre el impacto de sus contribuciones. La programación de recolección de artículos es otra funcionalidad crucial que facilita el proceso logístico y elimina la necesidad de desplazamientos complicados.

Garantizar la transparencia en el destino de las donaciones es vital para mantener la confianza de los donadores, permitiéndoles ver claramente cómo y a quién se destinan los artículos donados. Igualmente importante es la protección de los datos personales, que asegura la seguridad y privacidad de la información de los usuarios.

La aplicación web debe ser intuitiva y fácil de usar para no agregar barreras tecnológicas adicionales. Además, la implementación de campañas de sensibilización y colaboraciones con influencers ayudará a ampliar el alcance de la plataforma y a fomentar una mayor participación en las donaciones.

Al abordar estos aspectos, CambiaZo no solo mejorará la experiencia de donación, sino que también incrementará la frecuencia y el impacto de las contribuciones, haciendo que la plataforma sea una solución eficaz y apreciada por la comunidad.<br><br>


### Análisis General para Ambos Segmentos

<div align="center">
	<img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/sistemas-operativos-grafica.png?raw=truee" alt="Estadistica Android vs IOS" style="width: 600px; height: auto;"><br><br>
</div>

Como podemos observar en la gráfica obtenida de las entrevistas sobre los sistemas operativos de los smartphones utilizados por los entrevistados, se evidencia una clara predominancia de Android. De acuerdo con los datos recopilados, el 80% de los entrevistados utiliza este sistema operativo. 

Este alto porcentaje subraya la necesidad crítica de que CambiaZo sea completamente compatible con Android. La plataforma debe estar optimizada para aprovechar al máximo las características y capacidades de este sistema operativo, garantizando un rendimiento fluido y una experiencia de usuario sin interrupciones para la mayoría de los usuarios.

En contraste, el 20% de los entrevistados utiliza iOS. Aunque esta proporción es menor, sigue siendo significativa y no debe ser pasada por alto. Para asegurar que la plataforma sea accesible para todos, CambiaZo debe desarrollar y mantener una versión optimizada para dispositivos Apple. Esta atención a ambos sistemas operativos es crucial para proporcionar una experiencia uniforme y satisfactoria a todos los usuarios.


<div align="center">
	<img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Statistics/android-ios.png?raw=true" alt="Imagen Android y IOS"><br><br>
</div>

Para abordar adecuadamente estas necesidades, CambiaZo debe enfocarse en ofrecer una plataforma completamente funcional tanto para Android como para iOS. Esta estrategia no solo garantizará que la aplicación funcione de manera efectiva en ambos sistemas operativos, sino que también permitirá que todos los entrevistados, independientemente del dispositivo que utilicen, accedan a todas las funcionalidades y características de CambiaZo.

Además, la interfaz de CambiaZo debe ser intuitiva y fácil de usar. La simplicidad en el diseño y una navegación fluida son cruciales para garantizar que todos los usuarios, independientemente de su nivel de experiencia tecnológica, puedan utilizar la plataforma de manera efectiva. Al ofrecer una experiencia de usuario accesible y libre de complicaciones, CambiaZo podrá satisfacer las necesidades y expectativas de todos los entrevistados.<br><br>



## 2.3 Needfinding

En CambiaZo, entendemos que para desarrollar una plataforma que realmente responda a las necesidades de nuestros usuarios, es crucial conocerlas a fondo. La sección de Needfinding refleja nuestro compromiso con este objetivo a través de una investigación detallada.

Nos dedicamos a identificar y analizar a nuestros usuarios mediante la creación de User Persona, User Task Matrix, User Journey Maps, Empathy , As-Is Scenario Mapping y To-Be Scenario Mapping. Este enfoque nos permite diseñar una experiencia de intercambio y donación que sea tanto efectiva como alineada con las expectativas de quienes utilizan nuestra plataforma.

A continuación, exploraremos cómo estos métodos nos ayudarán a construir una solución que satisfaga y supere las demandas de nuestros usuarios.

### 2.3.1 User Personas

Después de analizar las entrevistas de nuestro segmento objetivo, nuestra tarea es definir el perfil del usuario ideal con el que estamos tratando. Hemos elaborado los perfiles de usuario teniendo en cuenta las personalidades y cualidades identificadas en cada entrevista. A continuación, se presentan las user personas resultantes de la investigación:

<b>Usuario Intercambiador</b><br>

<div align="center">

![User Persona 1](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Needfinding/User-Persona/user-persona-1.PNG?raw=true)
</div>

<br><br>

<b>Usuario Donador</b><br>

<div align="center">

![User Persona 2](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Needfinding/User-Persona/user-persona-2.PNG?raw=true)
</div>

<br><br>

### 2.3.2 User Task Matrix

Para diseñar una plataforma que responda eficazmente a las necesidades de nuestros usuarios, en CambiaZo hemos desarrollado una User Task Matrix. 

En esta sección, presentamos un análisis detallado de las tareas que los usuarios, tanto Intercambiadores como Donadores, realizan para alcanzar sus objetivos. Cada tarea se evalúa en función de su frecuencia y la importancia que los usuarios le atribuyen, permitiéndonos enfocar el diseño de nuestra aplicación en lo que realmente importa para ellos.



<b>Usuario Intercambiador</b><br>

<div align="center">
<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th rowspan="2"><div align="center">USER TASK</div><br></th>
    <th colspan="2"><div align="center">Intercambiador <br>Carlos Flores<br></div></th>
   
  </tr>
  <tr>
    <th>Frecuencia</th>
    <th>Importancia</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Buscar objetos para intercambiar<br></td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Contactar Usuarios para Intercambiar<br></td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Coordinar Condiciones del Intercambio<br></td>
    <td>Alta</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Confirmar Acuerdo de Intercambio<br></td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Evaluar Experiencia de Intercambio<br></td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
</tbody>
</table>
</div><br><br>

<b>Usuario Donador</b><br>

<div align="center">
<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th rowspan="2"><div align="center">USER TASK</div><br></th>
    <th colspan="2"><div align="center">Donador <br>Mariana Okinawa<br></div></th>
   
  </tr>
  <tr>
    <th>Frecuencia</th>
    <th>Importancia</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Buscar organizaciones para donar<br></td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
     <td>Seleccionar Artículo para Donar<br></td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Coordinar Entrega de Donación<br></td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Preparar Artículos para Donación<br></td>
    <td>Media</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Entregar Donación a la Organización<br></td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
</tbody>
</table>
</div>

### 2.3.3 User Journey Mapping

En esta sección, se desarrollan los User Journey Maps para cada User Persona, proporcionando una visión completa del recorrido del usuario desde el inicio hasta el final. Estos mapas representan la situación actual (As-Is) de cada segmento, sin ofrecer soluciones. 

<b>Segmento Intercambiadores</b><br>

Mediante este artefacto se explicará y comprenderá como los usuarios del segmento Cliente realizan sus actividades para alcanzar sus objetivos desde su perspectiva.

<div align="center">

![User Journey Mapping.](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Needfinding/User-Journey-Mapping/user-journey-mapping-1.png?raw=true)
</div><br><br>

<b>Segmento Donadores</b><br>

Mediante este artefacto se explicará y comprenderá como los usuarios del segmento Empresa realizan sus actividades para alcanzar sus objetivos desde su persepctiva.

<div align="center">

![User Journey Mapping.](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Needfinding/User-Journey-Mapping/user-journey-mapping-2.png?raw=true)
</div><br><br>

### 2.3.4 Empathy Mapping

Lo siguiente a evaluar como parte del needfinding es a nuestros segmentos objetivos a través de empathy maps, con el objetivo de conocer mejor a nuestros segmentos objetivos e identificar sus necesidades profundas.

<b>Segmento Intercambiadores</b><br>

<div align="center">

![Empathy Mapping.](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Needfinding/Empathy-Mapping/empathy-map-1.PNG?raw=true)
</div><br><br>

<b>Segmento Donadores</b><br>

<div align="center">

![Empathy Mapping.](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Needfinding/Empathy-Mapping/empathy-map-2.PNG?raw=true)
</div><br><br>

### 2.3.5 As-Is Scenario Mapping

En esta sección, exploraremos los escenarios actuales de los usuarios, mapeando cómo interactúan con los procesos y herramientas existentes. El As-Is Scenario Mapping nos permitirá entender las prácticas actuales y detectar áreas de mejora para optimizar la experiencia del usuario en nuestra plataforma.<br><br>

<b>Segmento Intercambiadores</b><br>


<div align="center">

![As-Is Scenario Mapping.](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Needfinding/As-Is-Scenario-Mapping/as-is-scenario-1.PNG?raw=true)
</div>


<br><br>

<b>Segmento Donadores</b><br>

<div align="center">

![As-Is Scenario Mapping.](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Needfinding/As-Is-Scenario-Mapping/as-is-scenario-2.PNG?raw=true)
</div>

<br><br>


## 2.4 Ubiquitous Language.
En esta sección, se establece un glosario de términos clave del dominio de negocio, conforme al enfoque de Ubiquitous Language propuesto por Eric Evans en Domain-Driven Design. Este glosario proporciona definiciones claras y sin ambigüedades de los conceptos utilizados en el ámbito específico del problema y la solución abordados, facilitando una comunicación efectiva entre todos los miembros del equipo.

+ **Subscription (Subscripción):** An arrangement where users sign up for a service or access to a product on a recurring basis, often for a specific duration, in exchange for certain benefits or features. Subscriptions typically involve the payment of a recurring fee, and they may offer various levels or tiers of access, each providing different features, benefits, or limitations. Users may subscribe to gain access to premium content, exclusive features, or enhanced functionality within the platform.<br><br>

+ **Plan (Plan):** Different tiers or levels of subscription offering varying features, benefits, or limitations. Plans are structured to cater to the diverse needs and preferences of users, providing options that align with their usage patterns, budget constraints, or desired level of engagement. These plans may be designed to cater to different user segments, such as casual users, power users, or businesses, and they often dictate the scope of access and available features within the platform.<br><br>

+ **Exchange (Intercambio):** The act of swapping objects between users, typically facilitated by the platform. Exchanges may involve the direct trade of items between users, where one user offers an object in exchange for another object offered by a different user. Alternatively, exchanges may involve indirect transactions facilitated by the platform, where users list objects they wish to exchange, and the platform matches them with other users interested in those items. Exchanges promote the circulation of goods within the community, fostering a collaborative and sustainable consumption model.<br><br>

+ **Guarantees (Garantías):** Assurances provided by the platform to users regarding the quality, authenticity, or condition of exchanged objects. Guarantees serve to instill confidence in users, assuring them that the objects they receive through exchanges meet certain standards and expectations. These guarantees may include policies for verifying the authenticity of items, conducting quality inspections, or providing recourse in the event of disputes or issues with exchanged objects.<br><br>

+ **Advertisements (Anuncios)** Promotional content displayed on the platform to generate interest or revenue. Advertisements may take various forms, including banner ads, sponsored content, or targeted promotions, and they are often tailored to the interests, preferences, or demographics of users. Advertisements may be used to promote relevant products, services, or events to users, and they may serve as a source of revenue for the platform through advertising partnerships or pay-per-click arrangements.<br><br>

+ **Donation (Donaciones):** Contributions made by users in the form of objects or monetary support to individuals or organizations. Donations reflect acts of generosity and altruism within the community, allowing users to support causes they care about or assist those in need. Users may donate objects they no longer need or use, providing them to individuals or organizations that can benefit from them. Additionally, users may make monetary donations to support charitable initiatives, nonprofit organizations, or community projects facilitated by the platform.<br><br>

+ **Physical Donation (Donación física):** Donating physical objects by providing an address for drop-off. Physical donations involve the transfer of tangible items from one user to another, typically through arrangements for pickup or delivery. Users may offer physical donations to other users directly, arranging for the exchange of objects through personal interactions or logistics coordinated within the platform. Physical donations contribute to resource sharing and waste reduction efforts, enabling users to repurpose or recycle items they no longer need.<br><br>

+ **Monetary Donation (Donación monetaria):** Contributing money to a specified account, typically belonging to a non-profit organization. Monetary donations involve the transfer of funds from one user to another, often in support of charitable causes, humanitarian efforts, or community initiatives. Users may donate money to nonprofit organizations, charitable foundations, or crowdfunding campaigns endorsed by the platform, providing financial support to causes aligned with their values or interests. Monetary donations may be used to fund various projects, programs, or activities that benefit the community or address societal needs.<br><br>

+ **Transaction (Transacción):** A financial exchange or operation carried out between users or involving the platform. Transactions encompass a wide range of interactions within the platform, including purchases, sales, exchanges, donations, or payments. Users engage in transactions to acquire, exchange, or transfer goods, services, or funds, utilizing the platform's features and functionalities to facilitate these exchanges securely and efficiently. Transactions may involve the transfer of virtual assets, such as digital currency or credits, as well as the exchange of physical goods or monetary payments.<br><br>

+ **Categories (Categorías):** Groupings or classifications used to organize objects, organizations, or content for easier navigation and searchability. Categories serve as a taxonomy or hierarchical structure within the platform, grouping related items or entities based on shared characteristics, attributes, or properties. Users can browse or filter content within specific categories to narrow down their search results and find relevant information more efficiently. Categories may be predefined by the platform or created dynamically based on user-generated content, reflecting the diverse interests and preferences of the community.<br><br>

+ **User Limit (Límite de usuario):** The maximum number of objects a user can publish or display on the platform within a given timeframe. User limits impose restrictions on the quantity or volume of content that individual users can contribute or showcase within the platform, preventing abuse, spam, or excessive clutter. These limits may be enforced to maintain a balanced and equitable distribution of resources among users, ensuring fair access to platform features and functionalities. Users may encounter user limits based on their subscription level, account status, or platform policies, with options to increase limits through upgrades or premium memberships.<br><br>

+ **Space Allocation (Asignación de espacio):** The allocation of virtual real estate or capacity on the platform for users to publish or display their objects. Space allocation involves the provision of digital resources, such as storage capacity, bandwidth, or display area, to accommodate user-generated content within the platform. Users are allotted a certain amount of space or resources based on their subscription plan, account settings, or platform privileges, dictating the extent to which they can contribute or showcase objects, advertisements, or other content. Space allocation may be managed dynamically to accommodate fluctuations in user activity or demand, optimizing resource utilization and user experience within the platform.<br><br>

+ **User (Usuario):** An individual who interacts with the platform, either by subscribing, publishing objects, or engaging in exchanges. Users represent the primary stakeholders and participants within the platform ecosystem, contributing content, generating activity, and shaping the community dynamics. Users may vary in their roles, behaviors, and preferences, ranging from content creators and contributors to consumers and participants. The platform's features, functionalities, and policies are designed to cater to the needs, interests, and expectations of users, fostering a positive and engaging user experience.<br><br>

# Capítulo III: Requirements Specification

###  3.1. To-Be Scenario Mapping

En esta sección, visualizaremos los escenarios futuros propuestos para nuestros usuarios, ilustrando cómo deberían evolucionar los procesos y herramientas para mejorar la experiencia en nuestra plataforma. El To-Be Scenario Mapping nos ayudará a diseñar soluciones optimizadas que respondan a las necesidades identificadas y faciliten un flujo de trabajo más eficiente y satisfactorio.


<b>Segmento Intercambiadores</b><br>

<div align="center">

![To-Be Scenario Mapping.](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Needfinding/To-Be-Scenario-Mapping/to-be-scenario-1.png?raw=true)
</div>

<br><br>

<b>Segmento Donadores</b><br>

<div align="center">

![To-Be Scenario Mapping.](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Needfinding/To-Be-Scenario-Mapping/to-be-scenario-2.png?raw=true)
</div>


<br><br>



## 3.2. User Stories

En esta sección, profundizaremos en la definición y elaboración de las User Stories relacionadas con nuestro proyecto. Las User Stories son una herramienta fundamental en el desarrollo de software y proyectos de diseño centrados en el usuario.

### EPICS

| **EP01: Gestión de Cuenta de Usuario** | Como usuario, quiero tener el control total sobre mi cuenta para gestionarla según mis necesidades. |
| :-- | :-- |
| **User Story ID** | **Título** |
| US01 | Registro de usuario |
| US02 | Editar perfil del usuario |
| US03 | Iniciar sesión en la aplicación |
| US04 | Cambiar Contraseña |
| US05 | Cerrar Sesión |
| US09 | Eliminación de cuenta |
| US20 | Adquirir la suscripción premium |
| US21 | Cancelar una suscripción |
| US23 | Gestionar mis favoritos en la aplicación |
| US24 | Ver reseñas recibidas |

<br>

| **EP02: Funcionalidades de Intercambio** | Como usuario de la aplicación, quiero acceder a una variedad de funcionalidades relacionadas con el intercambio de objetos, para facilitar la búsqueda, creación y gestión de publicaciones de intercambio. |
| :-- | :-- |
| **User Story ID** | **Título** |
| US06 | Filtrado de Objetos |
| US10 | Visualización de artículos publicados para intercambio |
| US11 | Realización de una oferta de intercambio |
| US12 | Crear publicación de intercambio |
| US13 | Editar publicación de intercambio |
| US14 | Eliminar publicación de intercambio |
| US15 | Gestión de intercambios |
| US16 | Visualización de objetos disponibles para intercambio |
| US18 | Aceptar o Rechazar un Intercambio |
| US19 | Ver la información detallada de un producto publicado |

<br>

| **EP03: Funcionalidades de Reseñas y ONGs** | Como usuario de la aplicación, quiero interactuar con las ONGs y gestionar reseñas para mejorar la experiencia de intercambio y donación. |
| :-- | :-- |
| **User Story ID** | **Título** |
| US07 | Visualización de ONGs registradas y filtrado |
| US08 | Brindar reseña sobre el Intercambiador |
| US17 | Visualizar el perfil del usuario que publique un producto |
| US22 | Visualizar el perfil de las ONG’s registradas |

<br>

| **EP04: Información y Navegación de la Landing Page** | Como usuario visitante de la landing page de la aplicación web, deseo acceder a información relevante y navegar fácilmente para obtener una comprensión clara de las características y funcionalidades ofrecidas. |
| :-- | :-- |
| **User Story ID** | **Título** |
| US25 | Visualización de la Historia de la Startup |
| US26 | Visualizar las características clave de la aplicación |
| US27 | Acceder a un formulario para llenar mis datos de contacto y recibir noticias relacionadas con CambiaZo |
| US28 | Descargar la aplicación de CambiaZo / Acceder a la página principal |
| US29 | Ver los planes y precios |
| US30 | Navegación en la Landing Page |

<br>

| **EP05: Desarrollo de Funcionalidades de la API de CambiaZo** | Como equipo de desarrollo, queremos implementar una serie de funcionalidades en la API de la aplicación para gestionar usuarios, reseñas, ONGs y suscripciones, con el fin de mejorar la experiencia del usuario y garantizar un funcionamiento eficiente de la plataforma. |
| :-- | :-- |
| **User Story ID** | **Título** |
| TS01 | API User |
| TS02 | API Exchanges |
| TS03 | API ONGs |
| TS04 | API Memberships |
| TS05 | API Products |

<br><br>

**USER STORIES**

|**Epic/User Story ID**|**Título**|**Descripción**|**Criterio de aceptación**|**Relación (EPIC ID)**|
| - | - | - | - | - |
|**US01**|Registro de usuario|Como nuevo usuario quiero completar el proceso de registro en la aplicación para establecer mi propia cuenta.|<p><h4>**Escenario 1: Acceso del usuario a la página de registro**</h4></p><p>**Dado** **que** el usuario ha accedido a la aplicación (web o móvil),<br>**Cuando** se encuentra en la sección de "Inicio de sesión"<br>**Y** opta por pulsar el botón "Registrarse",<br>**Entonces** la aplicación mostrará la página de registro.</p><p><h4>**Escenario 2: Registro exitoso del usuario**</h4></p><p>**Dado** **que** el usuario está en la página de registro,<br>**Cuando** introduce la información requerida<br>**Y** pulsa el botón "Registrarse",<br>**Entonces** la aplicación completará el proceso de registro<br>**Y** guardará la cuenta del usuario.</p><p><h4>**Escenario 3: Registro con datos inválidos**</h4></p><p>**Dado** **que** el usuario está en la página de registro,<br>**Cuando** proporciona información incompleta o no válida<br>**Y** pulsa el botón "Registrarse",<br>**Entonces** la aplicación mostrará un mensaje de error<br>**Y** no permitirá completar el registro.</p>|**EP01**|
|**US02**|Editar perfil del usuario|Como usuario ya registrado quiero realizar modificaciones en mi perfil para asegurarme de que mi información esté siempre actualizada.|<p><h4>**Escenario 1: Acceso del usuario a "Mi perfil"**</h4></p><p>**Dado** **que** el usuario ha iniciado sesión,<br>**Cuando** accede a la opción "Mi perfil" desde el menú principal,<br>**Entonces** la aplicación mostrará la página con la información del perfil.</p><p><h4>**Escenario 2: El usuario elige editar su perfil**</h4></p><p>**Dado** **que** el usuario está en la página "Mi perfil",<br>**Cuando** pulsa el botón "Editar perfil",<br>**Entonces** la aplicación mostrará la interfaz para modificar los datos personales.</p><p><h4>**Escenario 3: Actualización exitosa de perfil**</h4></p><p>**Dado** **que** el usuario se encuentra en la sección de edición de perfil,<br>**Cuando** introduce sus nuevos datos<br>**Y** pulsa el botón "Guardar cambios",<br>**Entonces** la aplicación actualizará su información correctamente.</p><p><h4>**Escenario 4: Datos inválidos al editar perfil**</h4></p><p>**Dado** **que** el usuario está editando su perfil,<br>**Cuando** ingresa información incompleta o inválida<br>**Y** pulsa "Guardar cambios",<br>**Entonces** la aplicación mostrará un mensaje de error<br>**Y** no guardará los datos.</p><p></p>|**EP01**|
|**US03**|Iniciar sesión en la aplicación|Como usuario registrado quiero iniciar sesión en la aplicación para poder acceder a todas sus funcionalidades.|<p><h4>**Escenario 1: Acceso a la página de inicio de sesión**</h4></p><p>**Dado** **que** el usuario accede a la aplicación sin haber iniciado sesión previamente,<br>**Cuando** selecciona la opción "Iniciar sesión",<br>**Entonces** se mostrará la página de autenticación.</p><p><h4>**Escenario 2: Inicio de sesión exitoso**</h4></p><p>**Dado** **que** el usuario está en la página de inicio de sesión,<br>**Cuando** introduce credenciales válidas<br>**Y** pulsa el botón "Iniciar sesión",<br>**Entonces** el sistema autenticará al usuario<br>**Y** lo redirigirá a la página principal.</p><p><h4>**Escenario 3: Fallo en el inicio de sesión**</h4></p><p>**Dado** **que** el usuario está en la página de inicio de sesión,<br>**Cuando** introduce credenciales incorrectas<br>**Y** pulsa "Iniciar sesión",<br>**Entonces** la aplicación mostrará un mensaje de error indicando que las credenciales son inválidas.</p>|**EP01**|
|**US04**|Cambiar Contraseña|Como usuario registrado, quiero realizar cambios en la contraseña de mi cuenta para reforzar la seguridad de mi cuenta.|<p><h4>**Escenario 1: Acceso a la opción de cambio de contraseña**</h4></p><p>**Dado que** el usuario ha iniciado sesión en la aplicación (web o móvil),<br>**Cuando** acceda a la sección de configuración de la cuenta,<br>**Entonces** la aplicación mostrará la opción para modificar la contraseña.</p><p><h4>**Escenario 2: Cambio exitoso de la contraseña**</h4></p><p>**Dado que** el usuario está en la página o sección de cambio de contraseña,<br>Cuando ingrese su contraseña actual y la nueva contraseña dos veces<br>**Y** pulse el botón "Cambiar Contraseña",<br>**Entonces** la aplicación ejecutará el cambio de contraseña<br>**Y** mostrará un mensaje de confirmación.</p><p><h4>**Escenario 3: Intento de cambio fallido**</h4></p><p>**Dado que** el usuario se encuentra en la sección de cambio de contraseña,<br>**Cuando** ingrese una contraseña actual incorrecta o incompleta, seguida de la nueva contraseña dos veces<br>**Y** pulse el botón "Cambiar Contraseña",<br>**Entonces** la aplicación mostrará un mensaje de error indicando que la contraseña actual es incorrecta.</p><p></p>|**EP01**|
|**US05**|Cerrar Sesión|Como usuario registrado quiero cerrar sesión en la aplicación para asegurarme de que mi cuenta no quede almacenada en mi dispositivo web.|<p><h4>**Escenario 1: Acceso a la opción de cerrar sesión**</h4></p><p>**Dado que** el usuario ha iniciado sesión en la aplicación (web o móvil),<br>**Cuando** acceda a la sección de configuración de la cuenta,<br>**Entonces** la aplicación mostrará la opción para cerrar sesión.</p><p><h4>**Escenario 2: Cierre de sesión exitoso**</h4></p><p>**Dado que** el usuario se encuentra en la página o sección de cierre de sesión,<br>**Cuando** seleccione el botón "Cerrar Sesión",<br>**Entonces**, la aplicación concluirá la sesión del usuario<br>**Y** lo redirigirá a la página de inicio de sesión.</p><p></p>|**EP01**|
|**US06**|Filtrado de Objetos|Como usuario Intercambiador, quiero la capacidad de filtrar los objetos disponibles de intercambio para encontrar la opción que mejor se adapte a mis preferencias de intercambio.|<p><h4>**Escenario 1: Aplicación de filtros**</h4></p><p>**Dado que** el usuario está en la sección de objetos disponibles para intercambio,<br>**Cuando** seleccione filtros específicos (como categoría, ubicación y precio)<br>**Y** pulse el botón "Aplicar Filtros",<br>**Entonces** la lista de objetos se ajustará automáticamente según los criterios seleccionados.</p><p><h4>**Escenario 2: Visualización de resultados filtrados**</h4></p><p>**Dado que** el usuario ha aplicado filtros,<br>**Cuando** la aplicación muestra únicamente los objetos que cumplen con los criterios seleccionados,<br>**Entonces** el usuario puede explorar los resultados filtrados según sus preferencias.</p><p><h4>**Escenario 3: Sin resultados al aplicar filtros**</h4></p><p><h4>**Dado que** el usuario ha aplicado uno o varios filtros en la lista de objetos</h4></p><p><h4>**Cuando** no se encuentran objetos que cumplan con los criterios seleccionados</h4></p><p><h4>**Entonces** la aplicación mostrará un mensaje indicando que no hay resultados disponibles con esos filtros</h4></p><p>Y sugerirá al usuario ajustar o eliminar algunos filtros para ampliar la búsqueda.</p>|**EP02**|
|**US07**|Visualización de ONGs registradas |Como usuario Donante, quiero visualizar la lista de ONGs registradas y poder filtrarlas por nombre usando el buscador, para encontrar la ONG específica en la cual me gustaría hacer mi donación.|<p>**Escenario 1: Visualización por defecto**<br>**Dado que** el usuario ha accedido a la sección de ONGs registradas,<br>**Cuando** no ha ingresado ningún término en la barra de búsqueda,<br>**Entonces** la aplicación mostrará por defecto una lista con la imagen de logo, nombre, tipo de organización y ubicación de cada ONG.</p><p>**Escenario 2: Búsqueda por nombre**<br>**Dado que** el usuario está en la sección de ONGs,<br>**Cuando** escribe el nombre o parte del nombre de una ONG en la barra de búsqueda<br>**Y** confirma la búsqueda (presionando "Enter" o haciendo clic en el icono de búsqueda),<br>**Entonces** la lista se actualizará mostrando únicamente las ONGs cuyo nombre coincida con el texto ingresado.</p><p></p>|**EP03**|
|**US08**|Brindar reseña sobre el Intercambiador|Como usuario intercambiador, deseo dejar una reseña sobre mi experiencia con el intercambiador para que otros usuarios puedan leer y considerar mi opinión antes de intercambiar|<p><h4>**Escenario 1: Dejar una reseña**</h4></p><p>**Dado que** el usuario ha completado un intercambio,<br>**Cuando** accede a la sección correspondiente a esa experiencia,<br>**Entonces** encontrará una opción para dejar una reseña sobre el otro usuario.</p><p><h4>**Escenario 2: Visualización de reseñas**</h4></p><p>**Dado que** otros usuarios exploran las experiencias de intercambio,<br>**Cuando** acceden a las reseñas dejadas por otros,<br>**Entonces** pueden leer y considerar las opiniones antes de iniciar un intercambio.</p>|**EP03**|
|**US09**|Eliminación de cuenta|Como usuario, quiero tener la opción de eliminar permanentemente mi cuenta para evitar que mi información persista en caso de que ya no desee utilizar la aplicación|<p>**Escenario 1: Acceso a la opción de eliminación**<br>**Dado que** el usuario está registrado en la aplicación,<br>**Cuando** desee eliminar su cuenta,<br>**Entonces** encontrará una opción claramente visible en la configuración de cuenta que le permita eliminarla.</p><p>**Escenario 2: Confirmación de eliminación**<br>**Dado que** el usuario selecciona la opción de eliminar su cuenta,<br>**Cuando** confirme su elección,<br>**Entonces** se mostrará un mensaje solicitando una segunda confirmación antes de proceder.</p><p>**Escenario 3: Eliminación exitosa**<br>**Dado que** el usuario ha confirmado la eliminación,<br>**Cuando** la acción es procesada,<br>**Entonces** todos los datos asociados a la cuenta son eliminados permanentemente y esta se desactiva en ambas versiones de la aplicación.</p>|**EP01**|
|**US10**|Visualización de artículos publicados para intercambio|Como usuario de la aplicación de intercambio, quiero ver los artículos que he publicado, para revisar cuáles están disponibles para intercambio.|<p>**Escenario 1: Sin artículos publicados**<br>**Dado que** el usuario no ha publicado artículos,<br>**Cuando** accede a la sección “Mis artículos”,<br>**Entonces** verá un mensaje que lo invita a publicar, junto a un botón destacado “+ Publicar”.</p><p>**Escenario 2: Con artículos publicados**<br>**Dado que** el usuario ya publicó artículos,<br>**Cuando** accede a “Mis artículos”,<br>**Entonces** visualizará sus artículos en tarjetas con imagen, nombre y estado.</p><p>**Escenario 3: Opciones de un artículo**<br>**Dado que** el usuario tiene uno o más artículos,<br>**Cuando** presiona el botón de opciones (tres puntos) en una tarjeta,<br>**Entonces** se desplegará un menú con acciones disponibles para ese artículo.</p>|**EP02**|
|**US11**|Realización de una oferta de intercambio|Como usuario de la aplicación de intercambio, quiero seleccionar uno de mis artículos y enviarlo como oferta de intercambio, para poder ofrecerlo a cambio de otro artículo publicado por otro usuario.|<p>**Escenario 1: Usuario con artículos publicados**<br>**Dado que** el usuario desea intercambiar un artículo,<br>**Cuando** presiona el botón “Ofertar”,<br>**Entonces** verá una lista de sus artículos disponibles y podrá seleccionar uno para la oferta.</p><p>**Escenario 2: Confirmación de oferta**<br>**Dado que** el usuario ha seleccionado un artículo,<br>**Cuando** confirme la oferta,<br>**Entonces** se le mostrará una pantalla con detalles del artículo ofrecido y solicitado,<br>**Y** podrá confirmar presionando “Listo”.</p><p>**Escenario 3: Oferta enviada con éxito**<br>**Dado que** la oferta fue confirmada,<br>**Cuando** se envíe correctamente,<br>**Entonces** se mostrará un mensaje “¡Oferta Enviada!”<br>**Y** se notificará al usuario que la otra parte recibirá la oferta.</p><p></p>|**EP02**|
|**US12**|Crear publicación de intercambio|Como usuario de la aplicación, quiero poder crear una nueva publicación de intercambio para ofrecer un artículo que deseo intercambiar|<p>**Escenario 1: Creación de publicación**<br>**Dado que** el usuario accede a la opción de crear una publicación,<br>**Cuando** complete el formulario con título, descripción, categoría y condición del artículo,<br>**Entonces** podrá adjuntar imágenes y enviar el formulario.</p><p>**Escenario 2: Publicación creada exitosamente**<br>**Dado que** el formulario está completo,<br>**Cuando** el usuario lo envíe,<br>**Entonces** la aplicación validará los campos<br>**Y** creará la publicación exitosamente.</p><p>**Escenario 3: Visualización de publicación**<br>**Dado que** la publicación ha sido creada,<br>**Cuando** el usuario acceda a su perfil y luego a “Mis artículos”,<br>**Entonces** verá la nueva publicación reflejada en la lista de artículos.</p>|**EP02**|
|**US13**|Editar publicación de intercambio|Como usuario, necesito la capacidad de editar una publicación de intercambio existente para realizar cambios en los detalles del artículo o actualizar la información relevante.|<p>**Escenario 1: Acceso a la edición de una publicación de intercambio**<br>**Dado que** el usuario ha iniciado sesión en la aplicación (web o mobile)<br>**Y** tiene una publicación existente,<br>**Cuando** el usuario pulsa la opción de editar la publicación desde la interfaz,<br>**Entonces** el sistema redirige a un formulario prellenado con los detalles actuales de la publicación para realizar cambios<br>**Y** se muestran dos botones: “Cancelar” y “Publicar”.</p><p>**Escenario 2: Edición de la publicación confirmada**<br>**Dado que** el usuario está en el formulario de edición de la publicación,<br>**Cuando** realiza cambios en los detalles del artículo como título, descripción, categoría o condición,<br>**Y** pulsa el botón “Publicar”,<br>**Entonces** el sistema guardará los cambios y la publicación actualizada será visible para los demás usuarios.</p><p>**Escenario 3: Edición cancelada**<br>**Dado que** el usuario está en el formulario de edición,<br>**Cuando** realiza cambios y pulsa el botón “Cancelar”,<br>**Entonces** el sistema lo redirige a la pantalla de inicio de la aplicación.</p>|**EP02**|
|**US14**|Eliminar publicación de intercambio|Como usuario, quiero tener la opción de eliminar una publicación de intercambio que ya no deseo ofrecer para intercambiar.|<p>**Escenario 1: Acceso a la eliminación**<br>**Dado que** el usuario ha iniciado sesión y tiene publicaciones,<br>**Cuando** accede a la opción de eliminar una publicación desde la interfaz (web o mobile),<br>**Entonces** el sistema mostrará un mensaje de confirmación.</p><p>**Escenario 2: Confirmación de eliminación**<br>**Dado que** el usuario ha seleccionado eliminar,<br>**Cuando** confirma la acción,<br>**Entonces** el sistema elimina la publicación de forma permanente<br>**Y** muestra un mensaje de confirmación.</p><p>` `**Escenario 3: Cancelación de eliminación**<br>**Dado que** el usuario ha iniciado la eliminación,<br>**Cuando** cancela la acción,<br>**Entonces** la publicación no se elimina<br>**Y** el sistema redirige al usuario al inicio.</p>|**EP02**|
|**US15**|Gestión de intercambios|Como usuario de la aplicación, quiero revisar el estado de los intercambios que he enviado, recibido o aceptado, para poder ver los detalles y gestionar mis transacciones de intercambio de manera eficiente.|<p>**Escenario 1: Revisión de enviados**<br>**Dado que** estoy en la sección de Intercambios,<br>**Cuando** selecciono la pestaña “Enviados”,<br>**Entonces** veré una lista con los objetos ofrecidos y su estado<br>**Y** podré ver más detalles al seleccionarlos.</p><p>**Escenario 2: Revisión de recibidos**<br>**Dado que** estoy en la misma sección,<br>**Cuando** selecciono “Recibidos”,<br>**Entonces** veré una lista de ofertas con detalles y opciones para aceptarlas o rechazarlas.</p><p>**Escenario 3: Revisión de aceptados**<br>**Dado que** estoy en la pestaña “Aceptados”,<br>**Cuando** selecciono un intercambio,<br>**Entonces** podré ver los detalles y dejar una reseña si lo deseo.</p>|**EP02**|
|**US16**|Visualización de objetos disponibles para intercambio|Como usuario, necesito poder ver objetos disponibles para intercambio, de manera que pueda navegar y seleccionar aquellos que me interesen.|<p>**Escenario 1: Visualización**<br>**Dado que** el usuario ha iniciado sesión,<br>**Y** accede a la sección de “Explorar o Home” (desde web o mobile),<br>**Cuando** entra a esa sección,<br>**Entonces** el sistema mostrará: barra de búsqueda, categorías y publicaciones con foto, valor, nombre, ubicación y descripción.</p><p>**Escenario 2: Búsqueda**<br>**Dado que** el usuario está en “Explorar o Home”,<br>**Cuando** usa la barra de búsqueda,<br>**Entonces** el sistema mostrará resultados que coincidan, con la misma información visual.</p>|**EP02**|
|**US17**|Visualizar el perfil del usuario que publique un producto|Como usuario, me gustaría tener la capacidad de visualizar el perfil de la persona que haya publicado un intercambio, para poder obtener información detallada de su confiabilidad.|<p>**Escenario 1: Acceso al perfil**<br>**Dado que** estoy en una publicación,<br>**Cuando** toco o hago clic en el recuadro del autor,<br>**Entonces** podré ver su nombre, tiempo en la app, intercambios exitosos y valoraciones.</p><p>**Escenario 2: Reseñas**<br>**Dado que** estoy en el perfil del usuario,<br>**Cuando** entro a la sección “Reseñas”,<br>**Entonces** podré ver todas las reseñas recibidas y datos relevantes.</p>|**EP03**|
|**US18**|Aceptar o Rechazar un Intercambio|Como usuario que ha recibido una oferta de intercambio, quiero poder revisar los detalles de la oferta y tomar una decisión para aceptar o rechazar el intercambio, para poder gestionar mis transacciones de manera eficiente y asegurada.|<p>**Escenario 1: Revisión de oferta**<br>**Dado que** estoy en “Intercambios”,<br>**Cuando** selecciono una oferta pendiente,<br>**Entonces** veré todos los detalles y opciones para aceptarla o rechazarla.</p><p>**Escenario 2: Aceptar oferta**<br>**Dado que** estoy viendo una oferta,<br>**Cuando** presiono “Aceptar”,<br>**Entonces** se muestra un popup de confirmación y la oferta pasa a “Aceptados”.</p><p>**Escenario 3: Rechazar oferta**<br>**Dado que** estoy viendo una oferta,<br>**Cuando** presiono “Rechazar”,<br>**Entonces** se muestra un popup con mensaje de advertencia.</p><p>` `**Escenario 4: Confirmación del rechazo**<br>**Dado que** he presionado “Rechazar oferta”,<br>**Cuando** confirmo la acción,<br>**Entonces** la oferta se elimina y no puede recuperarse.</p><p></p>|**EP02**|
|**US19**|Ver la información detallada de un producto publicado|Como usuario de la aplicación, quiero poder ver la información completa de un producto en el que estoy interesado, para poder decidir si quiero guardarlo en mis favoritos o proponer un intercambio.|<p>**Escenario 1: Ver detalles**<br>**Dado que** he seleccionado una publicación,<br>**Cuando** se abre la pantalla del artículo,<br>**Entonces** veré: imagen, valor, usuario, calificación, título, descripción, ubicación e intereses.</p><p>**Escenario 2: Ver perfil del usuario**<br>**Dado que** estoy en la pantalla de información,<br>**Cuando** selecciono el nombre o foto del usuario,<br>**Entonces** me redirige a su perfil.</p><p>**Escenario 3: Guardar en favoritos**<br>**Dado que** estoy en la información del producto,<br>**Cuando** presiono el ícono de favoritos,<br>**Entonces** el producto se guarda en mis favoritos y el ícono cambia.</p><p></p>|**EP02**|
|**US20**|Adquirir la suscripción premium|Como usuario, quiero poder adquirir una suscripción premium para poder obtener beneficios adicionales que mejoren mi experiencia.|<p><h4>**Escenario 1: Localizar la sección para adquirir una suscripción**</h4></p><p>**Dado que** el usuario desea adquirir una suscripción premium en CambiaZo,<br>**Cuando** accede a la sección de Memberships desde la versión web,<br>**Entonces** se le mostrarán los diferentes planes de suscripción disponibles.<br>**Y** desde la versión mobile, al acceder a la sección Mi Suscripción, se le mostrarán los planes disponibles.</p><p>**Cuando** el usuario selecciona un plan específico desde cualquiera de las versiones (web o mobile),<br>**Entonces** se abrirá la pasarela de pago de PayPal para proceder con el pago.</p><p></p><p><h4>**Escenario 2: Realizar el pago de la suscripción**</h4></p><p>**Dado que** el usuario ha seleccionado un plan de su interés,<br>**Cuando** pulsa el botón de “Suscribirse”**,**<br>**Entonces** será redirigido a PayPal para completar el pago y activar la suscripción premium.</p>|**EP01**|
|**US21**|Cancelar una suscripción|Como usuario quiero poder cancelar mi suscripción en cualquier momento para no pagar mensualmente|<p><h4>**Escenario 1: Acceso a la ventana de suscripciones**</h4></p><p>**Dado que** el usuario desea verificar la información del estado de su suscripción,<br>**Cuando** se dirige a la sección de configuración desde la versión web**,<br>Entonces** deberá acceder a su perfil y, dentro de este, en la sección de Detalles de perfil, encontrará una sección llamada “Mi membresía”**.**<br>**Y** al pulsar en esta sección, podrá ver los detalles de su suscripción.</p><p>**Cuando** accede a la versión mobile y entra a la sección de Mi suscripción**,<br>Entonces** podrá ver el estado de su suscripción actual y los detalles relacionados.</p><p><h4>**Escenario 2: Verificación de los detalles de la suscripción**</h4></p><p>**Dado que** el usuario se encuentra en la ventana que muestra el estado de su suscripción,<br>**Cuando** revisa los detalles,<br>**Entonces** podrá visualizar la fecha de renovación**,<br>Y** si se encuentra en un plan.</p><p></p><p><h4>**Escenario 3: Proceder a la cancelación**</h4></p><p>**Dado que** el usuario se encuentra en la ventana que muestra el estado de su suscripción,<br>**Cuando** ha decidido no continuar con la suscripción premium de CambiaZo,<br>**Entonces** podrá pulsar en el botón rojo que dice **“**Anular suscripción” desde la versión web en la sección Mi membresía dentro de Detalles de perfil**.<br>Y** así, la suscripción será cancelada y no se renovará hasta la próxima fecha de pago.</p><p>**Cuando** accede desde la versión mobile** a la sección Mi suscripción y selecciona Planes,<br>**Entonces** verá la opción de cambiar a Plan Lite, lo cual efectivamente cancela la suscripción premium y la coloca en un plan gratuito, eliminando los pagos mensuales.</p><p></p>|**EP01**|
|**US22**|Visualizar el perfil de las ONG’S registradas|Como usuario de la aplicación, quiero tener la opción de ver todas las ONG's disponibles para realizar donaciones.|<p><h4>**Escenario 1: Acceso a la pestaña de ONG's**</h4></p><p>**Dado que** el usuario se encuentra en la pestaña principal,<br>**Cuando** pulsa sobre la etiqueta "ONG's",<br>**Entonces** se mostrarán todas las ONG's registradas dentro de la aplicación, tanto en la app móvil como en la web.</p><p><h4>**Escenario 2: Ver perfil de una ONG**</h4></p><p>**Dado** **que** el usuario se encuentra dentro de la pestaña "ONG'S",<br>**Cuando** pulsa sobre el recuadro que muestra el perfil de la ONG que desea visualizar,<br>**Entonces** aparecerán los datos y características completas de la ONG seleccionada, que incluyen el nombre, la imagen, la descripción (misión, visión y objetivos), el horario de atención, la ubicación, los datos de contacto (teléfono y correo electrónico), los proyectos realizados, y los enlaces a redes sociales y página web de la ONG.</p>|**EP03**|
|**US23**|Gestionar mis favoritos en la aplicación|Como usuario de la aplicación, quiero poder acceder a los objetos que he guardado como favoritos, para poder visualizarlos y eliminar los que ya no me interesen.|**Escenario 1: Ver objetos guardados como favoritos**<br>**Dado que** estoy en mi perfil, **Cuando** selecciono la opción "Favoritos", <br>**Entonces** se me mostrará una lista de los objetos que he guardado como favoritos, incluyendo la imagen del objeto, el nombre del objeto, la descripción breve del objeto y el valor aproximado del objeto.<br>**Escenario 2: Eliminar un objeto de mis favoritos**<br>**Dado que** estoy visualizando la lista de favoritos, <br>**Cuando** selecciono el botón de favoritos (ícono de corazón) de un objeto para eliminarlo, <br>**Entonces** se mostrará un popup de confirmación con el mensaje: "¿Estás seguro de que deseas eliminar este objeto de tus favoritos?" Y podré seleccionar entre eliminar, que eliminará el objeto de mi lista de favoritos, o cancelar, que cerrará el popup sin realizar ninguna acción. <br>**Y** si selecciono "Eliminar", el objeto desaparecerá de la lista de favoritos después de la confirmación.|**EP01**|
|**US24**|Ver reseñas recibidas|Como usuario de la aplicación, quiero poder ver las reseñas y calificaciones que he recibido, para tener una referencia de mi reputación en la plataforma.|**Escenario 1: Ver la calificación general y reseñas recibidas**<br>**Dado que** estoy en mi perfil,<br>**Cuando** selecciono la opción "Mis Reseñas", <br>**Entonces** se me mostrará mi calificación general (promedio de estrellas), el número total de reseñas recibidas y una lista de las reseñas, mostrando el nombre del usuario que dejó la reseña, su calificación (número de estrellas) y el comentario de la reseña.|**EP01**|
|**US25**|Visualización de la Historia de la Startup|Como usuario visitante**,** quiero acceder a la sección “¿Quiénes somos?” de la landing page, para conocer la historia de CambiaZo y al equipo que lo hace posible.|<p><h4>**Escenario 1: Visualizar la historia de la startup**</h4></p><p>**Dado que** me encuentro en la landing page de CambiaZo,<br>**Cuando** accedo a la sección “¿Quiénes somos?”,<br>**Entonces** veré una breve presentación sobre la startup, que explica su propósito de promover el intercambio y la donación de objetos para fomentar un estilo de vida sostenible, junto a un video introductorio que refuerza esta visión.</p><p><h4>**Escenario 2: Conocer al equipo de CambiaZo**</h4></p><p>**Dado que** me encuentro en la sección “¿Quiénes somos?” de la landing page,<br>**Cuando** deslizo el carrusel o slider que aparece a continuación del video,<br>**Entonces** podré visualizar las fotos de los integrantes del equipo, junto con sus nombres y los roles o puestos que ocupan dentro del proyecto.</p>|**EP04**|
|**US26**|Visualizar las características clave de la aplicación|Como usuario visitante, quiero poder conocer sus características clave para saber qué es lo que incluye.|<p><h4>**Escenario 1: Acceso a la sección de características**</h4></p><p>**Dado** que el usuario es un visitante en la página principal,<br>**Cuando** hace clic en el botón o enlace de "Características",<br>**Entonces** es redirigido a la sección "Descubre las ventajas de ser parte de nuestra comunidad".</p><p><h4>**Escenario 2: Visualización de beneficios principales**</h4></p><p>**Dado** que el usuario está en la sección de características,<br>**Cuando** visualiza el contenido inicial,<br>**Entonces** se le muestran dos opciones destacadas de Intercambios y Donaciones</p><p><h4>**Escenario 3: Exploración visual de productos intercambiables**</h4></p><p>**Dado** que el usuario ha explorado los beneficios iniciales,<br>**Cuando** hace scroll hacia abajo,<br>**Entonces** ve un carrusel o cuadrícula de imágenes con ejemplos de productos que puede intercambiar.</p><p>**Escenario 4: Conocimiento de valores diferenciales y características específicas**<br>**Dado** que el usuario continúa navegando la sección de características,<br>**Cuando** llega al bloque "Intercambios Sostenibles, Simplificados",<br>**Entonces** visualiza un mensaje que promueve la sostenibilidad mediante el intercambio, la donación y la conexión comunitaria,<br>**Y** también identifica las siguientes características: seguridad, artículos, comunidad, sostenible.</p><p><h4>**Escenario 5: Reconocimiento de alianzas solidarias**</h4></p><p>**Dado** que el usuario ha leído las características,<br>**Cuando** llega al bloque final de la sección,<br>**Entonces** puede visualizar logotipos o imágenes de las ONGs afiliadas que trabajan junto a la app, entendiendo su compromiso social.</p>|**EP04**|
|**US27**|Acceder a un formulario para llenar mis datos de contacto y recibir noticias relacionadas con CambiaZo.|Como usuario visitante, quiero tener la opción de llenar un formulario con mi información de contacto, a través de la landing page, para recibir noticias y actualizaciones relevantes de CambiaZo.|**Escenario 1: Acceso al formulario de suscripción**<br>**Dado** que el usuario visitante hace clic en la opción "Contáctanos",<br>**Cuando** es redirigido a la sección "¡Únete a CambiaZo!" en la landing page,<br>**Entonces** puede visualizar un formulario con los campos requeridos para ingresar su nombre, apellido y correo electrónico, y un botón para suscribirse|**EP04**|
|**US28**|Descargar la aplicación de CambiaZo|Como usuario visitante, quiero encontrar botones o enlaces claramente visibles en la landing page que me dirijan a la descarga de la aplicación de CambiaZo, para poder registrarme, intercambiar o donar artículos directamente desde mi dispositivo web.|<p>**Escenario 1: Identificación de botones de acción en la landing page**<br>**Dado** que el usuario está navegando por la landing page de CambiaZo,<br>**Cuando** busca una forma de acceder a la aplicación,<br>**Entonces** encuentra dos botones claramente visibles: uno que dice “Iniciar ahora” y lo lleva a la aplicación web, y otro que dice “Descargar” y lo dirige a la Play Store para obtener la app móvil.</p><p>**Escenario 2: Acceso fluido a la plataforma desde los botones**<br>**Dado** que el usuario hace clic en uno de los botones disponibles,<br>**Cuando** selecciona “Iniciar ahora” o “Descargar”,<br>**Entonces** es redirigido correctamente a la versión web de CambiaZo o a la Play Store, permitiéndole comenzar a registrarse, intercambiar o donar artículos sin inconvenientes.</p><p></p>|**EP04**|
|**US29**|Ver los planes y precios|Como usuario visitante, quiero tener acceso a una sección que detalle los planes ofrecidos por la plataforma, para poder evaluar las opciones disponibles antes de descargar la aplicación.|<p>**Escenario 1: Visualización de planes y precios disponibles<br>Dado** que el usuario está en la landing page de CambiaZo,<br>**Cuando** hace clic en la sección de "Planes",<br>**Entonces** ve los diferentes planes con sus beneficios y precios</p><p>**Escenario 2: Acción de suscripción a planes**<br>**Dado** que el usuario está en la landing page de CambiaZo y ha visto los planes,<br>**Cuando** hace clic en el botón **“¡Empieza ahora!”** para cualquiera de los planes,<br>**Entonces** se le redirige a la aplicación web para completar el proceso de suscripción.</p><p></p>|**EP04**|
|**US30**|Navegación en la Landing Page|Como usuario visitante, quiero contar con un menú de navegación visible y funcional para que me permita desplazarme fácilmente por las diferentes secciones del sitio web.|<p>**Escenario 1: Acceder a la información acerca de la startup**<br>**Dado** que el usuario se encuentra en la Landing Page,<br>**Cuando** quiera acceder a la información acerca del equipo,<br>**Entonces** podrá darle clic a la etiqueta “**Nosotros**” de la barra de navegación,<br>**Y** lo redirigirá rápidamente a la parte de la Landing Page donde se encuentra la información correspondiente.</p><p>**Escenario 2: Ver las características de la aplicación**<br>**Dado** que el usuario se encuentra en la Landing Page,<br>**Cuando** quiera conocer las características clave de CambiaZo,<br>**Entonces** podrá darle clic a la etiqueta “**Características**” de la barra de navegación,<br>**Y** lo redirigirá rápidamente a la parte de la Landing Page donde se encuentran las funcionalidades destacadas de la aplicación.</p><p>**Escenario 3: Ver los planes y precios**<br>**Dado** que el usuario se encuentra en la Landing Page,<br>**Cuando** quiera ver los planes y precios de CambiaZo,<br>**Entonces** podrá darle clic a la etiqueta “**Planes**” de la barra de navegación,<br>**Y** lo redirigirá a la sección que describe los diferentes planes y beneficios disponibles.</p><p>**Escenario 4: Acceder a la sección de contacto**<br>**Dado** que el usuario se encuentra en la Landing Page,<br>**Cuando** quiera acceder a la sección para contactarse con la startup,<br>**Entonces** podrá darle clic a la etiqueta “**Contáctanos**” de la barra de navegación,<br>**Y** lo redirigirá rápidamente a la parte de la Landing Page donde se encuentra el formulario para recibir notificaciones de CambiaZo y el pie de página con los datos de contacto.</p><p>**Escenario 5: Descargar o iniciar la aplicación**<br>**Dado** que el usuario se encuentra en la Landing Page,<br>**Cuando** quiera descargar la aplicación de CambiaZo o acceder a la versión web,<br>**Entonces** podrá hacer clic en los botones claramente visibles de la barra de navegación de “**Iniciar ahora**” para acceder a la aplicación web o “**Descargar**” para ser redirigido a la Play Store y descargar la aplicación móvil.</p>|**EP04**|

<br><br>

**Technical User Stories**

|**Technical story ID**|**Título**|**Descripción**|**Criterios de Aceptación**|**Relación (EPIC ID)**|
| :- | :- | :- | :- | :- |
|**TS01**|API User|Como usuario desarrollador que configura la plataforma quiero tener una API que facilite la gestión de usuarios en nuestra aplicación para administrar eficazmente la información de los usuarios.|**Escenario 1: Diseño de la API User**<br><br>**Dado que** el usuario developer configura la plataforma<br><br>**Cuando** diseñe la API para gestionar usuarios en nuestra aplicación movil,<br><br>**Entonces** definirá los endpoints y rutas necesarias para manejar operaciones como registro de usuarios, inicio de sesión, actualización de datos de usuario, y recuperación de contraseñas y establecerá los requisitos de autenticación y seguridad necesarios para proteger la información de los usuarios.<br><br>**Escenario 2: Selección de la tecnología para la API**<br><br>**Dado que** el usuario developer está diseñando la API para gestionar usuarios en nuestra aplicación movil,<br><br>**Cuando** elija la tecnología para implementar la API REST,<br><br>**Entonces** considerará los requisitos de la aplicación y las preferencias del equipo de desarrollo para tomar una decisión informada.<br><br>**Escenario 3: Obtener información del usuario**<br><br>**Dado que** el endpoint "/usuarios" está disponible,<br><br>**Cuando** se envía una solicitud GET con el identificador del usuario,<br><br>**Entonces** se recibe una respuesta con estado 200,<br><br>**Y** se obtienen los datos del usuario solicitado.<br><br>**Escenario 4: Obtener usuario no disponible**<br><br>**Dado que** el endpoint "/usuarios" está disponible,<br><br>**Cuando** se envía una solicitud GET con un identificador de usuario que no existe,<br><br>**Entonces** se recibe una respuesta con estado 404,<br><br>**Y** se muestra un mensaje que indica "No existe un usuario con este identificador".<br><br>**Escenario 5: Registro de un nuevo usuario**<br><br>**Dado que** el endpoint "/usuarios" está disponible,<br><br>**Cuando** se envía una solicitud POST con los detalles del usuario,<br><br>**Entonces** se recibe una respuesta con estado 201,<br><br>**Y** se incluye un usuario con un nuevo ID y los detalles registrados.<br><br>**Escenario 6: Registro de un usuario ya existente**<br><br>**Dado que** el endpoint "/usuarios" está disponible,<br><br>**Cuando** se envía una solicitud POST con los datos del usuario,<br><br>**Y** ya existe un usuario registrado con esos datos,<br><br>**Entonces** se recibe una respuesta con estado 400,<br><br>**Y** se muestra un mensaje que indica "Un usuario con estos datos ya existe".<br><br>**Escenario 7: Actualizar un usuario existente**<br><br>**Dado que** el endpoint "/usuarios" está disponible,<br><br>**Cuando** se envía una solicitud PUT con el id de un usuario,<br><br>**Y** ya existe un usuario registrado con ese id,<br><br>**Entonces** se recibe una respuesta con estado 202,<br><br>**Y** se muestra un mensaje que indica "Los datos del usuario han sido actualizados satisfactoriamente".<br><br>**Escenario 8: Actualizar un usuario no existente**<br><br>**Dado que** el endpoint "/usuarios" está disponible,<br><br>**Cuando** se envía una solicitud PUT con el id de un usuario,<br><br>**Y** no existe un usuario registrado con ese id,<br><br>**Entonces** se recibe una respuesta con estado 400,<br><br>**Y** se muestra un mensaje que indica "No existe ese usuario".<br><br>**Escenario 9: Eliminar un usuario existente**<br><br>**Dado que** el endpoint "/usuarios" está disponible,<br><br>**Cuando** se envía una solicitud DELETE con el id de un usuario,<br><br>**Y** ya existe un usuario registrado con ese id,<br><br>**Entonces** se recibe una respuesta con estado 202,<br><br>**Y** se muestra un mensaje que indica "Se borró al usuario satisfactoriamente".<br><br>**Escenario 10: Eliminar un usuario no existente**<br><br>**Dado que** el endpoint "/usuarios" está disponible,<br><br>**Cuando** se envía una solicitud DELETE con el id de un usuario,<br><br>**Y** no existe un usuario registrado con ese id,<br><br>**Entonces** se recibe una respuesta con estado 400,<br><br>**Y** se muestra un mensaje que indica "No existe ese usuario".|**EP05**|
|**TS02**|API Exchange|Como usuario developer que configura la plataforma quiero implementar una API que permita a los usuarios dejar intercambios a otros usuarios para mejorar la interacción entre usuarios y la plataforma.|**Escenario 1: Diseño de la API Exchange**<br><br>**Dado que** el usuario developer está configurando la plataforma,<br><br>**Cuando** diseña la API para permitir a los usuarios dejar intercambios en nuestra aplicación,<br><br>**Entonces** se definen los endpoints y rutas necesarias para que los usuarios puedan crear, leer, actualizar y eliminar intercambios y establecen los requisitos de autenticación y seguridad para proteger la privacidad.<br><br>**Escenario 2: Selección de la tecnología para la API**<br><br>**Dado que** el usuario developer está diseñando la API de intercambios en nuestra aplicación,<br><br>**Cuando** elige la tecnología para implementar la API REST,<br><br>**Entonces** se consideran los requisitos de la aplicación, incluyendo la escalabilidad, el rendimiento y la facilidad de mantenimiento.<br><br>**Escenario 3: Obtener información del intercambio**<br><br>**Dado que** el endpoint "/exchanges" está disponible,<br><br>**Cuando** se envía una solicitud GET con el identificador del intercambio,<br><br>**Entonces** se recibe una respuesta con estado 200,<br><br>**Y** se obtienen los datos del intercambio solicitado.<br><br>**Escenario 4: Obtener intercambio no disponible**<br><br>**Dado que** el endpoint "/exchanges" está disponible,<br><br>**Cuando** se envía una solicitud GET con un identificador de intercambio que no existe,<br><br>**Entonces** se recibe una respuesta con estado 404,<br><br>**Y** se muestra un mensaje que indica "No existe un intercambio con este identificador".<br><br>**Escenario 5: Agregar un nuevo intercambio**<br><br>**Dado que** el endpoint "/exchanges" está disponible,<br><br>**Cuando** se envía una solicitud POST con los valores del intercambio,<br><br>**Entonces** se recibe una respuesta con estado 201,<br><br>**Y** se incluye un intercambio con un nuevo ID y los valores registrados.<br><br>**Escenario 6: Agregar un intercambio ya existente**<br><br>**Dado que** el endpoint "/exchanges" está disponible,<br><br>**Cuando** se envía una solicitud POST con los datos del intercambio,<br><br>**Y** ya existe un intercambio registrado con esos datos,<br><br>**Entonces** se recibe una respuesta con estado 400,<br><br>**Y** se muestra un mensaje que dice "Un intercambio con estos datos ya existe".|**EP05**|
|**TS03**|API ONGs|Como usuario developer que configura la plataforma quiero diseñar una API que simplifique la obtención de información sobre las ONGs para integrarla de manera efectiva en la aplicación.|**Escenario 1: Diseño de la API ONGs**<br><br>**Dado que** el usuario developer configura la plataforma,<br><br>**Cuando** diseñe la API para obtener información sobre las ONGs,<br><br>**Entonces** define los endpoints y rutas necesarias para recibir detalles sobre las ONGs y establece los requisitos de autenticación y seguridad necesarios.<br><br>**Escenario 2: Selección de la tecnología para la API**<br><br>**Dado que** el usuario developer está diseñando la API para obtener información sobre las ONGs,<br><br>**Cuando** elija la tecnología para implementar la API REST,<br><br>**Entonces** considerará los requisitos y preferencias de la organización para tomar una decisión informada.<br><br>**Escenario 3: Obtener información de la ONG**<br><br>**Dado que** el endpoint "/ongs" está disponible,<br><br>**Cuando** se envía una solicitud GET con el identificador de la ONG,<br><br>**Entonces** se recibe una respuesta con estado 200,<br><br>**Y** se obtienen los datos de la ONG solicitada.<br><br>**Escenario 4: Obtener ONG no disponible**<br><br>**Dado que** el endpoint "/ongs" está disponible,<br><br>**Cuando** se envía una solicitud GET con un identificador de ONG que no existe,<br><br>**Entonces** se recibe una respuesta con estado 404,<br><br>**Y** se muestra un mensaje que indica "No existe una ONG con este identificador".<br><br>**Escenario 5: Agregar una nueva ONG**<br><br>**Dado que** el endpoint "/ongs" está disponible,<br><br>**Cuando** se envía una solicitud POST con los valores de la ONG,<br><br>**Entonces** se recibe una respuesta con estado 201,<br><br>**Y** se incluye una ONG con un nuevo ID y sus valores registrados.<br><br>**Escenario 6: Agregar una ONG ya existente**<br><br>**Dado que** el endpoint "/ongs" está disponible,<br><br>**Cuando** se envía una solicitud POST con los datos de la ONG,<br><br>**Y** ya existe una ONG registrada con esos datos,<br><br>**Entonces** se recibe una respuesta con estado 400,<br><br>**Y** se muestra un mensaje que dice "Una ONG con estos datos ya existe".|**EP05**|
|**TS04**|API Memberships|Como usuario developer que configura la plataforma quiero diseñar una API que facilite la gestión de membresías de usuarios para ofrecer beneficios al usuario.|**Escenario 1: Diseño de la API de Membresías**<br><br>**Dado que** el usuario developer está configurando la plataforma,<br><br>**Cuando** diseña la API de Membresías para gestionar las membresías de los usuarios,<br><br>**Entonces** define los endpoints y rutas necesarias para manejar las operaciones de membresías de usuarios y establece los requisitos de autenticación y seguridad necesarios para proteger la información de los usuarios.<br><br>**Escenario 2: Selección de la tecnología para la API**<br><br>**Dado que** el usuario developer está diseñando la API de Membresías en nuestra aplicación,<br><br>**Cuando** elige la tecnología para implementar la API REST,<br><br>**Entonces** considera los requisitos de la aplicación y las preferencias del equipo de desarrollo para tomar una decisión informada.<br><br>**Escenario 3: Obtener información de membresía del usuario**<br><br>**Dado que** el endpoint "/membresías" está disponible,<br><br>**Cuando** se envía una solicitud GET con el identificador de la membresía,<br><br>**Entonces** se recibe una respuesta con estado 200,<br><br>**Y** se obtienen los datos de la membresía solicitada.<br><br>**Escenario 4: Obtener membresía no disponible**<br><br>**Dado que** el endpoint "/membresías" está disponible,<br><br>**Cuando** se envía una solicitud GET con un identificador de membresía que no existe,<br><br>**Entonces** se recibe una respuesta con estado 404,<br><br>**Y** se muestra un mensaje que indica "No existe una membresía con este identificador".<br><br>**Escenario 5: Agregar una nueva membresía**<br><br>**Dado que** el endpoint "/membresías" está disponible,<br><br>**Cuando** se envía una solicitud POST con los valores de la membresía,<br><br>**Entonces** se recibe una respuesta con estado 201,<br><br>**Y** se incluye una membresía con un nuevo ID y los valores registrados.<br><br>**Escenario 6: Agregar una membresía ya existente**<br><br>**Dado que** el endpoint "/membresías" está disponible,<br><br>**Cuando** se envía una solicitud POST con los datos de la membresía,<br><br>**Y** ya existe una membresía registrada con esos datos,<br><br>**Entonces** se recibe una respuesta con estado 400,<br><br>**Y** se muestra un mensaje que dice "Una membresía con estos datos ya existe".|**EP05**|
|**TS05**|API Product|Como usuario developer que configura la plataforma quiero diseñar una API que facilite la gestión de productos para que los usuarios puedan subir sus productos que ya no utilizan.|**Escenario 1: Diseño de la API de Productos**<br><br>**Dado que** el usuario developer está configurando la plataforma,<br><br>**Cuando** diseña la API de Productos para gestionar los productos que suben los usuarios,<br><br>**Entonces** define los endpoints y rutas necesarios para permitir a los usuarios subir sus productos que ya no usan, cancelar la subida y obtener información sobre sus productos, y establece los requisitos de requerimiento y tipo de archivo.<br><br>**Escenario 2: Obtener información de un producto**<br><br>**Dado que** el endpoint "/products" está disponible,<br><br>**Cuando** se envía una solicitud GET con el identificador del producto,<br><br>**Entonces** se recibe una respuesta con estado 200,<br><br>**Y** se obtienen los detalles del producto solicitado.<br><br>**Escenario 3: Producto no encontrado**<br><br>**Dado que** el endpoint "/products" está disponible,<br><br>**Cuando** se envía una solicitud GET con un identificador de un producto que no existe,<br><br>**Entonces** se recibe una respuesta con estado 404,<br><br>**Y** se muestra un mensaje que indica "No se encontró el producto solicitado".<br><br>**Escenario 4: Creación de un nuevo producto**<br><br>**Dado que** el endpoint "/products" está disponible,<br><br>**Cuando** se envía una solicitud POST con los detalles del producto y el usuario asociado,<br><br>**Entonces** se recibe una respuesta con estado 201,<br><br>**Y** se registra el producto con un nuevo ID y los detalles registrados.<br><br>**Escenario 5: Crear un producto ya existente**<br><br>**Dado que** el endpoint "/products" está disponible,<br><br>**Cuando** se intenta crear un nuevo producto para un usuario que ya registró este producto,<br><br>**Entonces** se recibe una respuesta con estado 400,<br><br>**Y** se muestra un mensaje que indica "El usuario ya registró este producto".<br><br>**Escenario 6: Eliminar un producto**<br><br>**Dado que** el endpoint "/products" está disponible,<br><br>**Cuando** se envía una solicitud DELETE con los detalles del producto y el usuario asociado,<br><br>**Entonces** se recibe una respuesta con estado 200,<br><br>**Y** se elimina el producto con su ID y los detalles registrados.<br><br>**Escenario 7: Editar un producto**<br><br>**Dado que** el endpoint "/products" está disponible,<br><br>**Cuando** se envía una solicitud PUT con los detalles del producto y el usuario asociado,<br><br>**Entonces** se recibe una respuesta con estado 200,<br><br>**Y** se editarán los detalles previamente registrados del producto.|**EP05**|



## 3.3. Product Backlog
En el Product Backlog presentamos una lista priorizada de nuestras user stories según el nivel de prioridad que acordamos en el equipo, esencial para el *enfoque ágil*. Para analizar el nivel de dificultad de las tareas, utilizamos la secuencia de Fibonacci (1,2,3,5,8).  
Tomamos como historia de usuario base la historia de usuario **US12 / US42**: *Como usuario de la aplicación, quiero poder crear una nueva publicación de intercambio para ofrecer un artículo que deseo intercambiar*.

<table>
  <tr>
    <th># Orden</th>
    <th>User Story Id</th>
    <th>Título</th>
    <th>Descripción</th>
    <th>Story Points (1 / 2 / 3 / 5 / 8)</th>
    <th>EPIC ID</th>
  </tr>
  <!-- EPIC01 -->
  <tr>
    <td>1</td>
    <td><strong>US20</strong></td>
    <td>Adquirir la suscripción premium</td>
    <td>Como usuario, quiero poder adquirir una suscripción premium para poder obtener beneficios adicionales que mejoren mi experiencia.</td>
    <td>8</td>
    <td rowspan="10"><strong>EP01</strong></td>
  </tr>
  <tr>
    <td>2</td>
    <td><strong>US09</strong></td>
    <td>Eliminación de cuenta</td>
    <td>Como usuario, quiero tener la opción de eliminar permanentemente mi cuenta para evitar que mi información persista en caso de que ya no desee utilizar la aplicación.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>3</td>
    <td><strong>US23</strong></td>
    <td>Gestionar mis favoritos en la aplicación</td>
    <td>Como usuario de la aplicación, quiero poder acceder a los objetos que he guardado como favoritos, para poder visualizarlos y eliminar los que ya no me interesen.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>4</td>
    <td><strong>US24</strong></td>
    <td>Ver reseñas recibidas</td>
    <td>Como usuario de la aplicación, quiero poder ver las reseñas y calificaciones que he recibido, para tener una referencia de mi reputación en la plataforma.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>5</td>
    <td><strong>US01</strong></td>
    <td>Registro de usuario</td>
    <td>Como nuevo usuario quiero completar el proceso de registro en la aplicación para establecer mi propia cuenta.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>6</td>
    <td><strong>US21</strong></td>
    <td>Cancelar una suscripción</td>
    <td>Como usuario quiero poder cancelar mi suscripción en cualquier momento para no pagar mensualmente.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>7</td>
    <td><strong>US02</strong></td>
    <td>Editar perfil del usuario</td>
    <td>Como usuario ya registrado quiero realizar modificaciones en mi perfil para asegurarme de que mi información esté siempre actualizada.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>8</td>
    <td><strong>US04</strong></td>
    <td>Cambiar Contraseña</td>
    <td>Como usuario registrado, quiero realizar cambios en la contraseña de mi cuenta para reforzar la seguridad de mi cuenta.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>9</td>
    <td><strong>US03</strong></td>
    <td>Iniciar sesión en la aplicación</td>
    <td>Como usuario registrado quiero iniciar sesión en la aplicación para poder acceder a todas sus funcionalidades.</td>
    <td>1</td>
  </tr>
  <tr>
    <td>10</td>
    <td><strong>US05</strong></td>
    <td>Cerrar Sesión</td>
    <td>Como usuario registrado quiero cerrar sesión en la aplicación para asegurarme de que mi cuenta no quede almacenada en mi dispositivo.</td>
    <td>1</td>
  </tr>
  <!-- EPIC02 -->
  <tr>
    <td>11</td>
    <td><strong>US06</strong></td>
    <td>Filtrado de Objetos</td>
    <td>Como usuario Intercambiador, quiero la capacidad de filtrar los objetos disponibles de intercambio para encontrar la opción que mejor se adapte a mis preferencias.</td>
    <td>5</td>
    <td rowspan="10"><strong>EP02</strong></td>
  </tr>
  <tr>
    <td>12</td>
    <td><strong>US12</strong></td>
    <td>Crear publicación de intercambio</td>
    <td>Como usuario de la aplicación, quiero poder crear una nueva publicación de intercambio para ofrecer un artículo que deseo intercambiar.</td>
    <td>5</td>
  </tr>
  <tr>
    <td>13</td>
    <td><strong>US16</strong></td>
    <td>Visualización de objetos disponibles para intercambio</td>
    <td>Como usuario, necesito poder ver objetos disponibles para intercambio, de manera que pueda navegar y seleccionar aquellos que me interesen.</td>
    <td>5</td>
  </tr>
  <tr>
    <td>14</td>
    <td><strong>US19</strong></td>
    <td>Ver la información detallada de un producto publicado</td>
    <td>Como usuario de la aplicación, quiero poder ver la información completa de un producto en el que estoy interesado, para poder decidir si quiero guardarlo en mis favoritos o proponer un intercambio.</td>
    <td>5</td>
  </tr>
  <tr>
    <td>15</td>
    <td><strong>US11</strong></td>
    <td>Realización de una oferta de intercambio</td>
    <td>Como usuario de la aplicación de intercambio, quiero seleccionar uno de mis artículos y enviarlo como oferta de intercambio, para poder ofrecerlo a cambio de otro artículo publicado por otro usuario.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>16</td>
    <td><strong>US13</strong></td>
    <td>Editar publicación de intercambio</td>
    <td>Como usuario, necesito la capacidad de editar una publicación de intercambio existente para realizar cambios en los detalles del artículo o actualizar la información relevante.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>17</td>
    <td><strong>US15</strong></td>
    <td>Gestión de intercambios</td>
    <td>Como usuario de la aplicación, quiero revisar el estado de los intercambios que he enviado, recibido o aceptado, para poder ver los detalles y gestionar mis transacciones de intercambio de manera eficiente.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>18</td>
    <td><strong>US18</strong></td>
    <td>Aceptar o Rechazar un Intercambio</td>
    <td>Como usuario que ha recibido una oferta de intercambio, quiero poder revisar los detalles de la oferta y tomar una decisión para aceptar o rechazar el intercambio, para poder gestionar mis transacciones de manera eficiente y asegurada.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>19</td>
    <td><strong>US10</strong></td>
    <td>Visualización de artículos publicados para intercambio</td>
    <td>Como usuario de la aplicación de intercambio, quiero ver los artículos que he publicado, para revisar cuáles están disponibles para intercambio.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>20</td>
    <td><strong>US14</strong></td>
    <td>Eliminar publicación de intercambio</td>
    <td>Como usuario, quiero tener la opción de eliminar una publicación de intercambio que ya no deseo ofrecer para intercambiar.</td>
    <td>2</td>
  </tr>
  <!-- EPIC03 -->
  <tr>
    <td>21</td>
    <td><strong>US07</strong></td>
    <td>Visualización de ONGs registradas y filtrado</td>
    <td>Como usuario Donante, quiero visualizar la lista de ONGs registradas y poder filtrarlas por nombre usando el buscador, para encontrar la ONG específica en la cual me gustaría hacer mi donación.</td>
    <td>5</td>
    <td rowspan="4"><strong>EP03</strong></td>
  </tr>
  <tr>
    <td>22</td>
    <td><strong>US08</strong></td>
    <td>Brindar reseña sobre el Intercambiador</td>
    <td>Como usuario intercambiador, deseo dejar una reseña sobre mi experiencia con el intercambiador para que otros usuarios puedan leer y considerar mi opinión antes de intercambiar.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>23</td>
    <td><strong>US17</strong></td>
    <td>Visualizar el perfil del usuario que publique un producto</td>
    <td>Como usuario, me gustaría tener la capacidad de visualizar el perfil de la persona que haya publicado un intercambio, para poder obtener información detallada de su confiabilidad.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>24</td>
    <td><strong>US22</strong></td>
    <td>Visualizar el perfil de las ONG’s registradas</td>
    <td>Como usuario de la aplicación, quiero tener la opción de ver todas las ONG's disponibles para realizar donaciones.</td>
    <td>3</td>
  </tr>
  <!-- EPIC04 -->
  <tr>
    <td>25</td>
    <td><strong>US27</strong></td>
    <td>Acceder a un formulario para llenar mis datos de contacto y recibir noticias relacionadas con CambiaZo</td>
    <td>Como usuario visitante, quiero tener la opción de llenar un formulario con mi información de contacto, a través de la landing page, para recibir noticias y actualizaciones relevantes de CambiaZo.</td>
    <td>5</td>
    <td rowspan="6"><strong>EP04</strong></td>
  </tr>
  <tr>
    <td>26</td>
    <td><strong>US30</strong></td>
    <td>Navegación en la Landing Page</td>
    <td>Como usuario visitante, deseo contar con un menú de navegación visible y funcional para que me permita desplazarme fácilmente por las diferentes secciones del sitio web.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>27</td>
    <td><strong>US29</strong></td>
    <td>Ver los planes y precios</td>
    <td>Como usuario visitante, quiero tener acceso a una sección que detalle los planes ofrecidos por la plataforma, para poder evaluar las opciones disponibles antes de descargar la aplicación.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>28</td>
    <td><strong>US26</strong></td>
    <td>Visualizar las características clave de la aplicación</td>
    <td>Como usuario visitante, quiero poder conocer sus características clave para saber qué es lo que incluye.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>29</td>
    <td><strong>US28</strong></td>
    <td>Acceder a la página principal de CambiaZo</td>
    <td>Como usuario visitante, quiero encontrar botones o enlaces claramente visibles que me dirijan a la descarga de la aplicación de CambiaZo, para poder registrarme, intercambiar o donar artículos directamente desde mi dispositivo.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>30</td>
    <td><strong>US25</strong></td>
    <td>Visualización de la Historia de la Startup</td>
    <td>Como usuario visitante, quiero poder acceder a la historia de la startup, su misión y visión desde la landing page para estar más informado acerca de TechZo.</td>
    <td>1</td>
  </tr>
  <!-- EPIC05 -->
  <tr>
    <td>31</td>
    <td><strong>TS01</strong></td>
    <td>API User</td>
    <td>Como usuario desarrollador que configura la plataforma, quiero tener una API que facilite la gestión de usuarios en nuestra aplicación para administrar eficazmente la información de los usuarios.</td>
    <td>5</td>
    <td rowspan="5"><strong>EP05</strong></td>
  </tr>
  <tr>
    <td>32</td>
    <td><strong>TS02</strong></td>
    <td>API Exchange</td>
    <td>Como usuario developer que configura la plataforma quiero implementar una API que permita a los usuarios dejar intercambios a otros usuarios para mejorar la interacción entre usuarios y la plataforma.</td>
    <td>5</td>
  </tr>
  <tr>
    <td>33</td>
    <td><strong>TS03</strong></td>
    <td>API ONGs</td>
    <td>Como usuario developer que configura la plataforma, quiero diseñar una API que simplifique la obtención de información sobre las ONGs para integrarla de manera efectiva en la aplicación.</td>
    <td>5</td>
  </tr>
  <tr>
    <td>34</td>
    <td><strong>TS04</strong></td>
    <td>API Memberships</td>
    <td>Como usuario developer que configura la plataforma, quiero diseñar una API que facilite la gestión de membresías de usuarios para ofrecer beneficios al usuario.</td>
    <td>5</td>
  </tr>
  <tr>
    <td>35</td>
    <td><strong>TS05</strong></td>
    <td>API Product</td>
    <td>Como usuario developer que configura la plataforma quiero diseñar una API que facilite la gestión de productos para que los usuarios puedan subir sus productos que ya no utilizan.</td>
    <td>5</td>
  </tr>
</table>

<br>

A continuación se presenta una representación gráfica del mismo en la plataforma Pivotal Tracker:

<div align="center">

[![Product Backlog.](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Product-Backlog/pivotal.png?raw=true)](https://www.pivotaltracker.com/n/projects/2699481)
</div>


Enlace: [Product Backlog en PivotalTracker](https://www.pivotaltracker.com/n/projects/2699481)<br><br>



## 3.4. Impact Mapping
En esta sección, presentaremos el Impact Mapping, una herramienta esencial para alinear nuestras iniciativas con los objetivos estratégicos del proyecto. El Impact Mapping nos permitirá identificar y conectar los impactos esperados de nuestras soluciones con los resultados deseados, asegurando que cada acción y decisión contribuyan a alcanzar los objetivos clave y maximizar el valor para nuestros usuarios.

<b>Segmento Intercambiadores</b><br>

<div align="center">

[![Impact Mapping.](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Needfinding/Impact-Map/impact-map-1.png?raw=true)]()
</div><br><br>



<b>Segmento Donadores</b><br>

<div align="center">

[![Impact Mapping.](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Needfinding/Impact-Map/impact-map-2.png?raw=true)]()
</div><br><br>



<br>

# Capítulo IV: Product Design

## 4.1. Style Guidelines

En esta sección, compartimos nuestra propuesta de diseño para el landing page y la aplicación móvil, con el objetivo de ofrecer una interfaz intuitiva y fácil de usar para nuestros usuarios. Para lograrlo, hemos optado por utilizar recursos visuales que se adapten a la problemática que queremos abordar, al mismo tiempo que generan un atractivo visual para nuestro público objetivo.


### 4.1.1. General Style Guidelines

A continuación, se presentan las pautas generales para asegurar una presentación coherente de nuestros productos.

**Colors:**

Hemos seleccionado cuidadosamente una paleta de colores para representar nuestro aplicativo CambiaZo. Nuestro enfoque se centra en tonalidades que incluyen el amarillo (#FFE03C), el blanco (#FFFFFF), el negro (#000000) y degradados del negro para crear transiciones suaves entre los colores. Optamos por el amarillo para reflejar energía y positividad, el blanco para transmitir sofisticación y claridad, y el negro para agregar un toque de elegancia y prestigio. Además, el degradado del negro se utiliza para suavizar las transiciones entre los elementos visuales y añadir profundidad. Por último, el blanco humo (#F8F7F4) complementa la paleta al proporcionar un aspecto moderno y neutro. Este conjunto de colores busca armonizar con nuestra misión de resolver problemas y promover un ambiente de intercambio amigable y dinámico.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/General-Style-Guidelines/color-pallete.png?raw=true">
 </div><br><br><br>

**Branding:**
El branding es un proceso creativo fundamental que orienta el rumbo de una empresa y forja su identidad de marca. Su finalidad es la creación de marcas sólidas y fácilmente identificables en el mercado, logrando establecer una identidad y presencia apropiadas a través del diseño gráfico. En nuestro caso, el logo de la marca que queremos transmitir a nuestros usuarios es:

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/General-Style-Guidelines/cambiazo-logo-negro.png?raw=true">
 </div><br><br><br>

**Typography:**

Elegir una fuente adecuada es esencial para lograr un diseño cohesivo y equilibrado que se alinee con la imagen e identidad de la marca. Esta elección refleja nuestro compromiso de construir una identidad visual sólida y reconocible. La tipografía, incluida la fuente, el tamaño y el ancho, contribuirá significativamente a la percepción y el reconocimiento de la marca en el mercado objetivo.<BR>
La tipografía utilizada será Montserrat, que incluye las variantes Regular, Medium, Semi-Bold y Bold. El tamaño de la letra varió entre 1 rem (16 px), 1.5 rem (24 px), 2 rem (32 px) y 3 rem (48 px).

+ **Montserrat - Google fonts**

<div align="center">

[![Montserrat - Google fonts](https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/General-Style-Guidelines/tipography.png?raw=true)](https://fonts.google.com/specimen/Montserrat) 
</div><br>


Referencia: [Montserrat - Google fonts](https://fonts.google.com/specimen/Montserrat)<br><br>

**Spacing**

El espacio en el diseño de **aplicaciones móviles** es crucial para crear una experiencia de usuario fluida y agradable. El espaciado adecuado ayuda a que la interfaz sea más clara, fácil de navegar y visualmente atractiva. En nuestros proyectos, seguimos principios clave de **Material Design**, adaptándolos a las necesidades específicas de nuestras aplicaciones.

- **Botones**: Utilizamos un **padding** de 1 rem (16 px) en la dirección vertical y de 2 rem (32 px) en la horizontal. Esto asegura que los botones sean cómodos de interactuar en pantallas táctiles.
- **Márgenes entre texto**: Para mejorar la legibilidad, mantenemos un **margen de 1 rem (16 px)** entre elementos de texto, creando una separación clara y estética.
- **Márgenes entre elementos**: Aseguramos que haya un margen de **1.5 rem (24 px)** entre distintos elementos como imágenes, botones y cuadros de texto.
- **Márgenes entre secciones**: Para una organización más clara de la interfaz, establecemos un margen de **6 rem (72 px)** entre secciones de contenido, permitiendo una mejor separación visual.

**Dimensions**

La forma en que nos dirigimos a los usuarios de nuestra aplicación móvil varía según sus roles y necesidades. Cada segmento de usuarios tiene un tono y estilo de comunicación específico para garantizar que el mensaje resuene de manera efectiva.

- **Usuarios Intercambiadores**: Para este segmento, utilizamos un lenguaje **práctico y dinámico**, centrado en la facilidad de uso de la plataforma de intercambio. El tono es amigable y directo, destacando las ventajas de utilizar la aplicación para intercambiar artículos de manera rápida y segura. Promovemos un sentido de comunidad, invitando a los usuarios a compartir y encontrar lo que necesitan fácilmente.
  
- **Usuarios Donadores**: Para los donadores, adoptamos un lenguaje **cálido y empático**, resaltando el impacto positivo de sus donaciones. El tono es inspirador, motivando a los usuarios a formar parte de una causa mayor. Enfatizamos el agradecimiento y reconocimiento hacia los donadores, recordándoles que su generosidad puede marcar la diferencia en la vida de otras personas.

### 4.1.2. Web Style Guidelines

En nuestras pautas de estilo web, priorizamos la adaptación de nuestros principios de diseño a la experiencia de usuario en entornos de navegación en línea. Esto incluye:

- **Diseño Responsivo**: Nos aseguramos de que nuestro sitio web se adapte fluidamente a diferentes tamaños de pantalla, desde computadoras de escritorio hasta dispositivos móviles como tabletas y teléfonos inteligentes. Esto garantiza que los usuarios puedan acceder y disfrutar de la plataforma sin importar el dispositivo que utilicen.<br><br>
  
- **Navegación Intuitiva**: Implementamos una barra de navegación (Navbar) clara y organizada que facilita el acceso a las diferentes secciones del sitio. Para mejorar la experiencia en dispositivos móviles, incorporamos un "Botón hamburguesa" que despliega el menú principal de manera compacta y fácilmente accesible en pantallas más pequeñas. Esto permite a los usuarios navegar por el sitio de manera intuitiva y eficiente.<br><br>

- **Consistencia Visual**: Mantenemos una estética coherente en todo el sitio, utilizando colores, tipografías y elementos visuales que reflejen la identidad de marca de Cambiazo. Esto ayuda a crear una experiencia de usuario unificada y memorable en todas las páginas y dispositivos.<br><br>

- **Accesibilidad**: Nos esforzamos por hacer que nuestro sitio sea accesible para todos los usuarios, incluidos aquellos con discapacidades visuales o de movilidad. Esto implica utilizar etiquetas alt en imágenes, asegurar un contraste adecuado entre texto y fondo, y proporcionar opciones de navegación alternativas para usuarios con dificultades para interactuar con el sitio de forma estándar.<br>

Al adherirnos a estos principios de diseño, nos comprometemos a ofrecer una experiencia web que sea fácil de usar, estéticamente atractiva y accesible para todos los usuarios, independientemente de su dispositivo o capacidad.


### 4.1.3. Mobile Style Guidelines

#### 4.1.3.1. iOS Mobile Style Guidelines

Para la versión iOS de la aplicación CambiaZo, se han considerado los principios de diseño recomendados por Apple y se han adaptado nuestros lineamientos visuales generales para asegurar una experiencia fluida y nativa en dispositivos iPhone y iPad.

En cuanto a la **paleta de colores**, se mantiene el uso de amarillo (#FFE03C), blanco (#FFFFFF), negro (#000000) y blanco humo (#F8F7F4), garantizando una estética moderna y coherente con la identidad de la marca. Se aplican degradados sutiles para ofrecer una experiencia visual más inmersiva y alineada con las transiciones suaves de iOS.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/General-Style-Guidelines/color-pallete.png?raw=true" alt="Color Pallete iOS">
</div><br>

La **tipografía Montserrat** continúa siendo el eje de nuestra identidad visual, utilizada en sus variantes Regular, Medium, Semi-Bold y Bold. Se adapta al sistema de texto dinámico de iOS, garantizando accesibilidad y legibilidad en todos los tamaños de pantalla.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/General-Style-Guidelines/tipography.png?raw=true" alt="Tipografía Montserrat">
</div><br>

En términos de **espaciado y márgenes**, seguimos un enfoque basado en los estándares de Human Interface Guidelines. Se prioriza el uso de márgenes generosos y padding adecuados en botones y textos, optimizando la navegación táctil y la claridad visual.

El tono de comunicación mantiene su enfoque empático y directo, adaptándose al entorno amigable y limpio que caracteriza al sistema iOS. El diseño busca balancear funcionalidad y estilo, brindando una experiencia elegante y centrada en el usuario.

#### 4.1.3.2. Android Mobile Style Guidelines

Para Android, nos apoyamos en los lineamientos de **Material Design**, los cuales hemos integrado a nuestro estilo visual para ofrecer una experiencia de usuario coherente y efectiva en dispositivos con sistema operativo Android.

La **paleta de colores** conserva los tonos característicos de la marca (amarillo, blanco, negro y blanco humo), con una implementación cuidadosa de degradados y contrastes, pensados para mantener una interfaz clara y enérgica en el ecosistema Android.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/General-Style-Guidelines/color-pallete.png?raw=true" alt="Color Pallete Android">
</div><br>

La **tipografía Montserrat**, reconocida por su claridad y versatilidad, se aplica en distintos pesos según el contexto (Regular, Medium, Semi-Bold y Bold), asegurando una jerarquía visual adecuada y una experiencia de lectura óptima.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/General-Style-Guidelines/tipography.png?raw=true" alt="Tipografía Montserrat Android">
</div><br>

En cuanto a los **espaciados**, adoptamos una estructura modular, utilizando márgenes y paddings que responden a las recomendaciones de Material Design. Esto incluye separación entre elementos para mejorar la navegación y botones suficientemente amplios para facilitar la interacción en pantallas táctiles.

El lenguaje visual y comunicacional mantiene un enfoque práctico y accesible, alineado con la naturaleza abierta y funcional del ecosistema Android. Buscamos que el usuario pueda moverse por la app de manera intuitiva y ágil, sin perder de vista los valores de nuestra marca.






## 4.2. Information Architecture

En Cambiazo, la arquitectura de la información en nuestras aplicaciones móviles está diseñada para ser intuitiva y fácil de navegar. Implementamos sistemas de organización claros como la jerarquía visual y categorización por temas, lo que permite a los usuarios encontrar lo que necesitan sin esfuerzo, mejorando la experiencia de navegación móvil.

### 4.2.1. Organization Systems

Implementamos diversos sistemas de organización de la información en la app para mejorar la experiencia móvil:

**Organización visual del contenido:**

- **Jerárquica (Visual Hierarchy):** Destacamos la información importante en la app móvil para guiar a los usuarios a través de diferentes niveles de contenido, mostrando productos destacados de manera prominente en la pantalla principal.

- **Organización secuencial (Step-by-step):** Para el registro, creación de listados y confirmación de intercambios, implementamos un sistema paso a paso, asegurando que los usuarios completen tareas fácilmente en su dispositivo móvil.

**Esquemas de categorización de contenido:**

- **Por tópicos:** Los productos se organizan en categorías como electrónica, ropa, o libros, facilitando a los usuarios móviles encontrar lo que buscan rápidamente.

- **Según audiencia (Grupos de usuarios):** Ofrecemos secciones específicas para diferentes grupos de usuarios, como artículos infantiles o deportivos, optimizando la experiencia en función de sus intereses.

- **Cronológico:** Eventos y promociones importantes se muestran en orden cronológico para mantener a los usuarios actualizados en la app.

- **Alfabético:** Secciones como productos o preguntas frecuentes se organizan alfabéticamente para una navegación más fácil.

### 4.2.2. Labeling Systems

En nuestras aplicaciones móviles, utilizamos un sistema de etiquetado claro y conciso para facilitar la navegación:

- **Inicio/Home:** Muestra una visión general de la app y sus funciones principales.
- **Conócenos/About Us:** Presenta la misión y visión de la plataforma.
- **Características/Features:** Expone los beneficios que la app ofrece a los usuarios.
- **ONGs Afiliadas/Affiliated NGOs:** Lista las organizaciones asociadas a Cambiazo.
- **Planes/Subscriptions:** Presenta los diferentes planes de suscripción disponibles.
- **Contáctanos/Contact Us:** Ofrece información de contacto, con un formulario para consultas.
- **Registrarse/Sign Up:** Permite a los usuarios registrarse en la app, proporcionando campos para crear una cuenta.

### 4.2.3. SEO Tags and Meta Tags

En nuestras aplicaciones móviles, aunque el SEO es menos relevante que en la web, los meta tags aún ayudan a optimizar la visibilidad:

- **Encabezado:** Proporciona un título claro que mejora la visibilidad en los motores de búsqueda.
- **Descripción:** Ofrecemos una breve descripción del contenido que ayuda a los usuarios a entender la función de la app.
- **Palabras clave (Keywords):** Incluimos palabras clave relevantes para facilitar la búsqueda de la app.
- **Autor y Derechos de Autor:** Estas etiquetas identifican al creador de la app y protegen los derechos de propiedad intelectual.

Con estos sistemas, aseguramos que la arquitectura de la información en nuestra app móvil sea clara y efectiva, brindando a los usuarios una experiencia optimizada y satisfactoria.


**Landing Page:**
- **Título:**
```html
<title>
Cambiazo - Intercambia artículos de forma segura y justa
</title>
```

- **Descripción:**
```
  
 <meta name="description" content="Intercambia artículos de manera segura y justa con Cambiazo. Explora una amplia variedad de productos, garantizando transacciones transparentes y beneficiosas para todos."/>

```

- **Palabras clave:**
```

<meta name="keywords" content="Intercambio de artículos, plataforma de intercambio, seguridad en el intercambio, justicia en el intercambio, comunidad de intercambio, donaciones de artículos."/>
```

+ **Autor:**
```

<meta name="author" content="TechZo Startup" />

```

- **Copyright:**
```

<meta name="copyright" content="© TechZo, 2024" />

```

Estos tags están diseñados para resaltar los aspectos clave de Cambiazo, como la seguridad en los intercambios, la justicia en las transacciones y la posibilidad de realizar donaciones de artículos. Esto ayuda a mejorar la visibilidad en los motores de búsqueda y atraer a usuarios interesados en la plataforma.<br><br>


### 4.2.4. Searching Systems

Para garantizar una experiencia de búsqueda eficiente y satisfactoria para los usuarios en Cambiazo, implementaremos un sistema de búsqueda robusto con varias opciones y filtros en nuestra aplicación móvil. Aquí está cómo será el sistema de búsqueda:

- **Búsqueda básica:** Ofreceremos un campo de búsqueda simple en la parte superior de cada pantalla, donde los usuarios podrán ingresar palabras clave relacionadas con los productos que desean encontrar. Esto proporcionará una forma rápida y directa de buscar artículos específicos.

- **Filtros avanzados:** Permitiremos a los usuarios refinar sus resultados de búsqueda utilizando filtros avanzados como categoría de producto, disponible a través de un menú desplegable intuitivo. Estos filtros ayudarán a los usuarios a encontrar exactamente lo que están buscando y a reducir el volumen de información para evitar la sobrecarga de datos.

- **Ordenación de resultados:** Después de realizar una búsqueda, los usuarios podrán ordenar los resultados según diferentes criterios, como relevancia, precio ascendente/descendente, fecha de publicación, etc., mediante un selector fácil de usar. Esto les permitirá encontrar los productos más adecuados de manera rápida y eficiente.

- **Vista de resultados clara y detallada:** Mostraremos los resultados de búsqueda de manera clara y ordenada, con información relevante y detallada sobre cada producto, incluyendo imágenes, título, descripción, precio y ubicación del vendedor. Esto facilitará a los usuarios evaluar y comparar los productos encontrados.

- **Sugerencias de búsqueda:** Proporcionaremos sugerencias de búsqueda mientras los usuarios escriben en el campo de búsqueda, ayudándoles a encontrar términos relevantes y populares relacionados con su consulta.

Al ofrecer estas opciones de búsqueda y filtros, junto con una presentación clara y detallada de los resultados, buscamos garantizar que los usuarios puedan encontrar fácilmente los productos que están buscando en Cambiazo, sin sentirse abrumados por el volumen de información disponible.

### 4.2.5. Navigation Systems

Para guiar a los usuarios a través de la aplicación de Cambiazo de manera efectiva, implementaremos diversas acciones y técnicas de navegación:

- **Menú de navegación claro y conciso:** En la parte inferior de cada pantalla, proporcionaremos un menú de navegación que incluya enlaces directos a las secciones principales de la aplicación, como "Inicio", "Donaciones", "Mi perfil" y "Ayuda". Esto permitirá a los usuarios acceder rápidamente a las funciones y áreas que deseen explorar.

- **Búsqueda prominente:** Colocaremos un campo de búsqueda bien visible en la parte superior de cada pantalla, permitiendo a los usuarios buscar productos específicos, categorías o ong’s dentro de la aplicación de manera rápida y sencilla.

- **Botones de llamada a la acción (CTA):** Utilizaremos botones de CTA estratégicamente ubicados para dirigir a los usuarios hacia acciones importantes, como "Publicar", "Inicia sesión", "Inicio", "Categorías", etc. Estos botones ayudarán a los usuarios a tomar decisiones y avanzar en su experiencia en la plataforma.

- **Navegación intuitiva:** Diseñaremos la estructura de la aplicación de manera intuitiva, siguiendo convenciones de diseño de interfaz de usuario estándar y asegurándonos de que la navegación sea coherente en todas las pantallas. Esto ayudará a los usuarios a sentirse cómodos y seguros mientras exploran y utilizan Cambiazo.

Al implementar estas acciones y técnicas de navegación, buscamos garantizar que los usuarios puedan cumplir sus objetivos de manera satisfactoria y disfrutar de una experiencia fluida y sin problemas en la aplicación Cambiazo.


## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe

Para la creación del esquema inicial de nuestra Landing Page, se empleó la plataforma Figma en conjunto con una variedad de complementos que simplificaron considerablemente el proceso de diseño y desarrollo. Esta combinación de herramientas permitió una producción eficiente y efectiva del wireframe.

Enlace: [Wireframe del Landing Page en Figma]()<br><br>

**Landing Page**

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Landing-Page-UI-Design/wireframe-landing-desktop.png?raw=true" width="600px" alt="Wireframe">
</div><br><br>

**Landing Page en Mobile Web Browser**

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Landing-Page-UI-Design/wireframe-landing-mobile.png?raw=true" width="300px" alt="Wireframe Mobile">
</div><br><br>

### 4.3.2. Landing Page Mock-up

Hemos completado con éxito la creación del mock-up de la Landing Page, lo que nos ha permitido destacar y aplicar los principios y elementos de diseño que hemos establecido. Estos principios y pautas heurísticas desempeñan un papel fundamental al hacer que la experiencia para los usuarios finales de nuestra plataforma sea más sencilla e intuitiva.

Enlace: [Mock-up del Landing Page en Figma]()<br><br>

**Landing Page**

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Landing-Page-UI-Design/mock-up-landing-desktop.png?raw=true" width="600px" alt="Mockup">
</div><br><br>

**Landing Page en Mobile Web Browser**

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Landing-Page-UI-Design/mock-up-landing-mobile.png?raw=true" width="300px" alt="Mockup Mobile">
</div><br><br>

## 4.4. Mobile Applications UX/UI Design
### 4.4.1. Mobile Applications Wireframes

Los wireframes son esenciales en el diseño de nuestras aplicaciones, ya que ayudan a planificar la interfaz y la navegación antes de empezar el desarrollo. En nuestro proyecto, utilizamos 'Figma' para crear los wireframes de manera eficiente y colaborativa.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Wireframes/wireframe-0.png?raw=true"  alt="wireframes-appmovil">
</div><br><br>

Enlace: [Wireframes de la App Móvil en Figma](https://www.figma.com/design/thDm6YVmpL9RwzrpWkP1an/CambiaZo?node-id=0-1&t=JB6EPW2FwvDSD40F-1)<br><br>

A continuación, mostramos los wireframes de nuestra aplicación móvil:<br><br>

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Wireframes/wireframe-1.png?raw=true" alt="wireframes-1"><br>
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Wireframes/wireframe-2.png?raw=true"  alt="wireframes-2"><br>
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Wireframes/wireframe-3.png?raw=true"  alt="wireframes-3">
</div><br>

Estos wireframes se centran en la funcionalidad de inicio de sesión, registro y cambio de contraseña en la aplicación móvil. La disposición de los elementos se ha optimizado para una interacción intuitiva del usuario, sin considerar detalles de diseño.<br><br>

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Wireframes/wireframe-4.png?raw=true"  alt="wireframes-4">
</div><br>

La pantalla de inicio presenta las publicaciones de usuarios de manera organizada. Se incluirá una barra de búsqueda y categorías para facilitar la navegación, además de filtros personalizados.<br><br>


<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Wireframes/wireframe-5.png?raw=true"  alt="wireframes-5">
</div><br>

La pantalla de Producto muestra un artículo con detalles como precio, usuario publicador, descripción y ubicación para el intercambio, junto con un botón para iniciar el proceso. En la pantalla de Oferta, el usuario selecciona un solo artículo de su inventario para intercambiar, y confirma la oferta con un resumen visual del artículo propuesto y el deseado.<br><br>

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Wireframes/wireframe-6.png?raw=true"  alt="wireframes-6">
</div><br>

A través de la pantalla de Mis Artículos podrás publicar nuevos artículos, el formulario de publicación de objetos estará diseñado de manera intuitiva, con secciones claras y espacio suficiente entre ellas para una fácil comprensión.<br><br>


<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Wireframes/wireframe-7.png?raw=true"  alt="wireframes-7">
</div><br>

Esta pantalla mostrará una lista de organizaciones benéficas afiliadas, con espacio entre cada una para una mejor legibilidad. Se incluirá una barra de búsqueda dinámica para facilitar la exploración.<br><br>


<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Wireframes/wireframe-8.png?raw=true" alt="wireframes-8"><br>
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Wireframes/wireframe-9.png?raw=true"  alt="wireframes-9">

</div><br>

La pantalla de Mi Perfil permite gestionar la cuenta personal, incluyendo la edición de información, revisión de artículos favoritos, visualización de reseñas recibidas, exploración de planes de suscripción con beneficios adicionales y la opción de cerrar sesión<br><br>

### 4.4.2. Mobile Applications Wireflow Diagrams

A continuación, se presentan los wireflows que competen a nuestros user goals.

**User goal 1:** Como usuario, quiero poder iniciar sesión y poder recuperar mi contraseña en caso de pérdida.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Wireflow-Diagrams/wireflow-1.PNG?raw=true" alt="wireflow 1">
</div><br>

Al entrar a la aplicación móvil, el usuario primero será recibido por una pantalla de inicio de sesión. Para continuar, deberá ingresar su correo y contraseña. Si el usuario ha olvidado la contraseña, podrá recuperarla mediante un correo de confirmación que incluirá un código de verificación. Solo después de iniciar sesión exitosamente, el usuario será redirigido a la pantalla principal, donde podrá ver todas las publicaciones de intercambios destacadas, incluidas aquellas que poseen un boost.<br><br>

**User goal 2:** Como usuario, quiero poder revisar información detallada de las organizaciones benéficas que puedo apoyar.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Wireflow-Diagrams/wireflow-2.PNG?raw=true" alt="wireflow 2">
</div><br>
El usuario entra a la aplicación móvil y se dirige a una de las opciones de la barra de navegación que se llama “Donaciones”, en ella podrá visualizar todas las organizaciones benéficas afiliadas a CambiaZo. Al clickear en una de estas, podrá visualizar información más detallada de la misma.<br><br>



**User goal 3:** Como usuario, quiero poder tener la posibilidad de suscribirse a una membresía y de esta forma obtener mejores beneficios.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Wireflow-Diagrams/wireflow-3.PNG?raw=true"  alt="wireflow 3">
</div><br>
El usuario entra a la aplicación móvil y, desde la barra de navegación, selecciona la opción "Mi Perfil". Luego, desde su perfil, podrá acceder a la opción "Mi Suscripción", donde verá todas las suscripciones disponibles con información detallada. Al seleccionar una suscripción, será redirigido a una pasarela de pagos, y finalmente recibirá un pop-up de confirmación del proceso.<br><br>


**User goal 4:** Como usuario quiero poder publicar mis artículos de una manera rápida y accesible.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Wireflow-Diagrams/wireflow-4.PNG?raw=true"  alt="wireflow 4">
</div><br>

El usuario entra a la aplicación móvil y se dirige a la barra de navegación, donde selecciona la opción "Mis Artículos". Una vez dentro, encontrará un botón de "Publicar". Al presionarlo, se desplegará un formulario para que, con la sesión ya iniciada, el usuario pueda realizar su publicación de intercambio, incluyendo los datos necesarios y las fotos del artículo. Al finalizar, el usuario verá un pop-up con un mensaje de confirmación.<br><br>


**User goal 5:** Como usuario quiero poder filtrar mi búsqueda de objetos, recibir información solo de estos mismos y visualizar información pertinente y necesaria.


<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Wireflow-Diagrams/wireflow-5.PNG?raw=true"  alt="wireflow 5">
</div><br>

El usuario entra a la aplicación móvil y clickea en algunos de los botones de categorías disponibles. Después de ello se redirigirá a una pantalla en la que salgan todos los resultados de publicaciones encontradas con esa misma categoría. Además de filtros específicos e información básica.<br>Una vez el usuario clickee en cualquier card de publicación, podrá ver la información de la publicación con más detalle e información del autor de la publicación.<br><br>


**User goal 6:** Como usuario quiero poder realizar una oferta, teniendo en consideración los intercambios publicados que tengo en mi perfil.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Wireflow-Diagrams/wireflow-6.PNG?raw=true"  alt="wireflow 6">
</div><br>

Una vez el usuario haya seleccionado la publicación de interés, puede darle click a “Intercambiar”. Después de ello, saldrá una ventana en la cual el usuario puede seleccionar cualquiera de sus publicaciones en su “stock” para ofrecer. Después de ello, recibirá un mensaje de confirmación. <br><br>


**User goal 7:** Como usuario quiero poder visualizar mis publicaciones en mi perfil y administrarlas según mis necesidades.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Wireflow-Diagrams/wireflow-7.PNG?raw=true"  alt="wireflow 7">
</div><br>

Los usuarios podrán dirigirse a la sección "Mis Artículos" desde la barra de navegación, donde visualizarán todas sus publicaciones de articulos. Cada artículo tendrá un menú desplegable de tres puntos que les permitirá acceder a opciones para administrar sus publicaciones. Al seleccionar "Editar", se abrirá un formulario con los datos actuales del artículo, para que puedan realizar los cambios necesarios. Si eligen "Eliminar", aparecerá un mensaje de confirmación antes de proceder con la eliminación.<br><br>


**User goal 8:** Como usuario, quiero poder verificar las ofertas que he recibido por mis publicaciones y aceptarlas o declinar en caso contrario.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Wireflow-Diagrams/wireflow-8.PNG?raw=true"  alt="wireflow 8">
</div><br>

 Los usuarios podrán dirigirse a la sección "Mis Intercambios" desde la barra de navegación, donde visualizarán sus intercambios enviados, recibidos y aceptados. Al seleccionar una oferta en la sección de recibidos, verán los detalles de los artículos ofrecidos. Aquí podrán aceptar o rechazar la oferta mediante un menú con ambas opciones. Si eligen rechazar, se desplegará un mensaje de confirmación antes de proceder, y si aceptan, recibirán una notificación confirmando la aceptación del intercambio.<br><br>

 Enlace: [Wireflows en LucidChart 1](https://lucid.app/lucidchart/63364102-d93b-47fe-a04f-fce263593fdf/edit?viewport_loc=-8835%2C-824%2C20529%2C8239%2C0_0&invitationId=inv_451c4fe8-c20d-4e3d-8ab3-e8df00c42f3e)<br><br>

Enlace: [Wireflows en LucidChart 2](https://lucid.app/lucidchart/ded0e94e-a2ae-4af8-84a9-30eda1490a8c/edit?viewport_loc=-585%2C3553%2C4485%2C1800%2C0_0&invitationId=inv_12e34c87-1186-4aa4-8ddb-ca02798fcd0c)<br><br>

### 4.4.3. Mobile Applications Mock-ups

Los mockups son otra parte esencial en el diseño de nuestras aplicaciones, ya que nos permiten visualizar la apariencia y la disposición de los elementos antes de comenzar el desarrollo.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Mockups/mock-up-0.png?raw=true"  alt="mockups-appmobile">
</div><br><br>


Enlace: [Mock-up de la App Móvil en Figma](https://www.figma.com/design/thDm6YVmpL9RwzrpWkP1an/CambiaZo?node-id=0-1&t=1gSHFZmUKFcRiU0p-1)<br><br>


A continuación, mostramos los mock-ups de nuestra aplicación móvil.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Mockups/mock-up-1.png?raw=true"  alt="mockups-1"><br>
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Mockups/mock-up-2.png?raw=true"  alt="mockups-2"><br>
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Mockups/mock-up-3.png?raw=true"  alt="mockups-3">
</div><br>

Pantallas para el inicio de sesión, registro y cambio de contraseña en la aplicación móvil, con botones minimalistas con bordes redondeados y diseño agradable en nuestro color amarillo distintivo. Presentamos texto amigable y el nombre de la aplicación de manera prominente para generar percepción y reconocimiento de marca entre los usuarios. Utilizamos iconos destacados con sombreado para una fácil identificación visual por parte del usuario. Al finalizar exitosamente las operaciones, mostramos mensajes con el título resaltado en un tamaño mayor, identificados por su importancia, acompañados de un texto agradable y sencillo para mejorar la experiencia del usuario.<br><br>

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Mockups/mock-up-4.png?raw=true"  alt="mockups-4">
</div><br>

La pantalla de inicio muestra el logo de la aplicación para identificación rápida. Destaca las publicaciones de usuarios en cuadros equitativamente espaciados y sombreados para una apariencia ordenada y atractiva. La información relevante de las publicaciones se resalta mediante el tamaño de letra y otros elementos visuales para una mejor comprensión. Además, se muestra una barra de búsqueda dinámica y debajo, categorías resaltadas en amarillo que se destacan para llamar la atención del usuario de manera efectiva; estas categorías funcionan para una búsqueda rápida y dinámica por parte de los usuarios, garantizando una experiencia cómoda, agradable y visualmente atractiva.<br><br>

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Mockups/mock-up-5.png?raw=true"  alt="mockups-5">
</div><br>

La pantalla de producto muestra una imagen destacada del artículo y la información del vendedor, incluyendo una foto, nombre y calificación. La descripción del producto y un botón para proceder con la acción deseada se encuentran al final. En la pantalla de selección de oferta, se presenta un área para indicar lo que se ofrece a cambio, con una imagen del artículo y un botón para añadir la oferta. La pantalla de confirmación muestra las opciones de intercambio con imágenes de los productos y una flecha que las conecta, junto con un botón para finalizar el proceso. La última pantalla es una ventana emergente que confirma el envío de la oferta, con un botón para regresar. Todas las pantallas mantienen un diseño uniforme con una paleta de colores en amarillo y blanco, tipografía clara y un estilo moderno que prioriza la usabilidad y la experiencia del usuario.<br><br>


<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Mockups/mock-up-6.png?raw=true"  alt="mockups-6">
</div><br>

En la página de publicación de objetos, hemos diseñado un formulario intuitivo con instrucciones claras para guiar al usuario en todo el proceso. El formulario está dividido en secciones con subtítulos claramente definidos y un espacio equitativo entre ellos para una mejor organización visual. Cada sección cuenta con un sutil sombreado con un diseño minimalista, que proporciona una experiencia agradable y cómoda para el usuario. Además, los campos importantes se destacan mediante un tamaño de letra más grande y negrita, lo que facilita su identificación y comprensión durante la creación de la publicación. También hemos incluido un botón de "Publicar" en color amarillo, destacando visualmente sobre las demás secciones para que el usuario identifique intuitivamente que ese botón es para finalizar y publicar la información.<br><br>


<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Mockups/mock-up-7.png?raw=true"  alt="mockups-7">
</div><br>

Página que muestra una lista de organizaciones benéficas registradas, con un diseño minimalista y espacio entre ellas para una mejor organización. Utilizamos botones con un color amarillo que resalta y es más visible para el usuario. Además, implementamos una barra de búsqueda dinámica para buscar organizaciones por nombre y por localidades, así como también por categorías mediante botones. Mantenemos una estética visual coherente con un diseño minimalista en toda la aplicación, lo que facilita su navegación y la hace más intuitiva para los usuarios.<br><br>


<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Mockups/mock-up-8.png?raw=true"  alt="mockups-8"><br>
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Mockups/mock-up-9.png?raw=true"  alt="mockups-9">
</div><br>

La pantalla de Mi Perfil presenta un diseño consistente y visualmente atractivo. En la parte superior, se muestra una foto circular del usuario, seguida de su nombre y calificación con estrellas. Debajo, se encuentran opciones para editar el perfil, revisar favoritos, ver reseñas y explorar planes de suscripción, con texto negro sobre un fondo blanco. Al final, hay un botón para cerrar sesión. La pantalla de edición de perfil conserva la foto circular y ofrece campos de texto claros para modificar la información personal. La sección de favoritos exhibe tarjetas de productos con imágenes, títulos y precios destacados. La pantalla de reseñas presenta calificaciones con estrellas amarillas y comentarios de usuarios. Finalmente, la pantalla de suscripción detalla los planes disponibles con precios y beneficios en un formato de lista fácil de leer. Todas las pantallas comparten una barra de estado negra en la parte superior y una navegación coherente con flechas de retorno, utilizando una paleta de colores en blanco y negro para una experiencia de usuario uniforme y moderna.<br><br>

### 4.4.4. Mobile Applications User Flow Diagrams

A continuación, se presentan los diagramas de flujo de usuarios relacionados con nuestros objetivos de usuario.

**User Goal 1:** Como usuario, quiero ingresar a la aplicación móvil utilizando una cuenta.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-User-Flow-Diagrams/userflow-1.PNG?raw=true" alt="userflow 1">
</div><br>

El usuario abre la aplicación móvil. Se le presenta una pantalla para iniciar sesión si ya tiene una cuenta; de lo contrario, debe registrarse. Si el inicio de sesión es exitoso, puede acceder a todas las funciones de la aplicación. Si se registra con los datos correctos, se le muestra una ventana de confirmación y es dirigido a la pantalla de inicio de sesión.<br><br>


**User Goal 2:** Como usuario, quiero buscar objetos para intercambiar fácilmente y obtener información detallada sobre ellos.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-User-Flow-Diagrams/userflow-2.PNG?raw=true" alt="userflow 2">
</div><br>

El usuario se encuentra en la pantalla de inicio de la aplicación. Aquí puede visualizar los objetos publicados por otros usuarios. Al seleccionar un objeto, se abre una pantalla con detalles completos sobre la publicación. También puede explorar diferentes categorías de publicaciones desde la pantalla de inicio.<br><br>



**User Goal 3:** Como usuario, quiero que otros usuarios vean los objetos que publiqué para intercambiar.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-User-Flow-Diagrams/userflow-3.PNG?raw=true" alt="userflow 3">
</div><br><br>

Desde la pantalla de Mis Artículos, el usuario selecciona la opción de publicar. Es dirigido a una pantalla donde puede crear una nueva publicación. Después de completar los detalles necesarios y confirmar la publicación, recibe un mensaje de confirmación y su publicación se muestra a todos los usuarios.<br><br>

**User Goal 4:** Como usuario, quiero solicitar un intercambio a cambio de uno de los objetos de mi publicación.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-User-Flow-Diagrams/userflow-4.PNG?raw=true" alt="userflow 4">
</div><br><br>

Al visualizar una publicación, el usuario presiona el botón "Intercambiar". Se le muestra una ventana con sus propios objetos publicados, y puede seleccionar uno para proponer un intercambio. Recibe un mensaje de agradecimiento por parte de la aplicación.<br><br>

**User Goal 5:** Como usuario, quiero ser notificado cuando reciba una solicitud de intercambio y tener la opción de aceptar o rechazarla.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-User-Flow-Diagrams/userflow-5.PNG?raw=true" alt="userflow 5">
</div><br><br>

El usuario accede a las ofertas Recibidas desde la barra navegadora, donde selecciona Mis Intercambios, en esta sección encuentra las solicitudes de intercambio de otros usuarios. Puede aceptar una oferta, lo que le muestra un mensaje de confirmación y la opción de contactar al usuario por Telegram o WhatsApp para coordinar el intercambio. También puede rechazar la oferta.<br><br>


**User Goal 6:** Como usuario, quiero explorar y buscar ONGs y acceder a la información detallada sobre ellas.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-User-Flow-Diagrams/userflow-6.PNG?raw=true" alt="userflow 6">
</div><br><br>

Desde la pantalla de inicio, el usuario accede a la sección de donaciones. Aquí puede ver una lista de todas las ONGs disponibles. Al seleccionar una ONG, se abre una pantalla con información detallada sobre la misma.<br><br>


**User Goal 7:** Como usuario, quiero explorar y obtener información sobre los perfiles de otros usuarios.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-User-Flow-Diagrams/userflow-7.PNG?raw=true" alt="userflow 7">
</div><br><br>

Mientras visualiza una publicación, el usuario puede acceder al perfil del usuario que la publicó para ver más información sobre él en una pantalla dedicada.<br><br>


**User Goal 8:** Como usuario, quiero tener la opción de  pagar una membresía y disfrutar de los beneficios que ofrece.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-User-Flow-Diagrams/userflow-8.PNG?raw=true" alt="userflow 8">
</div><br><br>

Desde la pantalla de Mi Perfil, el usuario accede a la sección de membresías y elige el plan de su preferencia. Realiza la suscripción a través de una pasarela de pago integrada en la aplicación. Una vez completado el pago con éxito, recibe un mensaje de confirmación.<br><br>


**User Goal 9:** Como usuario, quiero poder realizar modificaciones en mis publicaciones si considero que necesitan ajustes.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-User-Flow-Diagrams/userflow-9.PNG?raw=true" alt="userflow 9">
</div><br><br>

Desde la pantalla de inicio, el usuario accede a la sección "Mis artículos", donde puede ver todas sus publicaciones. Al tocar el menú de opciones (tres puntos) en cada artículo, puede elegir entre editar o eliminar la publicación. Al seleccionar "Eliminar", se le solicita confirmación antes de proceder. Si elige "Editar", se abre un formulario que permite modificar la información del artículo.<br><br>



**User Goal 10:** Como usuario, quiero realizar cambios en mi perfil y mantenerlo actualizado con la información más reciente.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-User-Flow-Diagrams/userflow-10.PNG?raw=true" alt="userflow 10">
</div><br><br>

Desde la pantalla de inicio, el usuario accede a "Mi perfil" y selecciona la opción "Editar perfil". Aquí podrá cambiar su foto de perfil, datos personales o contraseña.<br><br>



Enlace: [User Flow 1 en LucidChart](https://lucid.app/lucidchart/43f6d75d-44c8-4170-bd1c-99fd21312c75/edit?viewport_loc=-3690%2C-9299%2C3648%2C5793%2C0_0&invitationId=inv_f07bff56-c57f-4cbb-8b02-8c692958e133)<br><br>

Enlace: [User Flow 2 en LucidChart](https://lucid.app/lucidchart/4966c7f2-f561-43f5-97c3-4dae978dbcfb/edit?viewport_loc=-906%2C-7520%2C2503%2C3974%2C0_0&invitationId=inv_6403b820-2acd-4db0-9a63-16de1d01e7c6)<br><br>

Enlace: [User Flow 3 en LucidChart](https://lucid.app/lucidchart/d12cb0f3-976b-46bf-ab0e-a545c1575e19/edit?viewport_loc=-5397%2C-5745%2C2719%2C4318%2C0_0&invitationId=inv_3ca4de93-b0e9-4de4-819a-3037cf6b4e95)<br><br>

## 4.5. Mobile Applications Prototyping
### 4.5.1. Android Mobile Applications Prototyping

A continuación, se presenta el prototipo que se realizó en base a los mockups que se desarrollaron y documentaron en puntos anteriores. El prototype nos permite evidenciar algunos flujos que se llevarán al desarrollo en código.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Prototyping/prototype-0.png?raw=true"  alt="prototype-0">
</div><br><br>


Enlace: [Prototype de la App Móvil en Figma](https://www.figma.com/design/thDm6YVmpL9RwzrpWkP1an/CambiaZo?node-id=0-1&t=3g3ixD798Xbsi1K9-1)<br><br>


Para complementar, se ha realizado un video donde se muestran los user flows del prototipo, detallando cada flujo de interacción y definiendo el tiempo en el cual se muestran para una comprensión efectiva. Este enfoque proporciona una visión dinámica de la experiencia del usuario, facilitando la identificación de mejoras y la validación de la funcionalidad del prototipo.<br><br>

Enlace: [Video Prototype de la App Móvil](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214059_upc_edu_pe/ETDFKlDociZGsi_Dgr-d7HkBE3-AouvlOTfvXGrnDqsphg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=PWZXDX)<br><br>


**User Goal 1:**  Como usuario, quiero ingresar a la aplicación móvil utilizando una cuenta.<br><br>

Tiempo: 0:12

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Prototyping/prototype-1.PNG?raw=true" alt="prototype 1">
</div><br>


**User Goal 2:** Como usuario, quiero buscar objetos para intercambiar fácilmente y obtener información detallada sobre ellos.<br><br>

Tiempo: 1:43

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Prototyping/prototype-2.PNG?raw=true" alt="prototype 2">
</div><br>


**User Goal 3:** Como usuario, quiero que otros usuarios vean los objetos que publiqué para intercambiar.<br><br>

Tiempo: 3:09

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Prototyping/prototype-3.PNG?raw=true" alt="prototype 3">
</div><br><br>


**User Goal 4:** Como usuario, quiero solicitar un intercambio a cambio de uno de los objetos de mi publicación.<br><br>

Tiempo: 4:01

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Prototyping/prototype-4.PNG?raw=true" alt="prototype 4">
</div><br><br>

**User Goal 5:** Como usuario, quiero ser notificado cuando reciba una solicitud de intercambio y tener la opción de aceptar o rechazarla.<br><br>

Tiempo: 4:51

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Prototyping/prototype-5.PNG?raw=true" alt="prototype 5">
</div><br><br>


**User Goal 6:** Como usuario, quiero explorar y buscar ONGs y acceder a la información detallada sobre ellas.<br><br>

Tiempo: 6:21

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Prototyping/prototype-6.PNG?raw=true" alt="prototype 6">
</div><br><br>



  **User Goal 7:** Como usuario, quiero explorar y obtener información sobre los perfiles de otros usuarios.<br><br>

  Tiempo: 7:01

  <div align="center">
      <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Prototyping/prototype-7.PNG?raw=true" alt="prototype 7">
  </div><br><br>



**User Goal 8:** Como usuario, quiero tener la opción de  pagar una membresía y disfrutar de los beneficios que ofrece.<br><br>

Tiempo: 7:27

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Prototyping/prototype-8.PNG?raw=true" alt="prototype 8">
</div><br><br>




**User Goal 9:** Como usuario, quiero poder realizar modificaciones en mis publicaciones si considero que necesitan ajustes.<br><br>

Tiempo: 8:17

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Prototyping/prototype-9.PNG?raw=true" alt="prototype 9">
</div><br><br>



**User Goal 10:** Como usuario, quiero realizar cambios en mi perfil y mantenerlo actualizado con la información más reciente.<br><br>

Tiempo: 8:56

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Prototyping/prototype-10.PNG?raw=true" alt="prototype 10">
</div><br><br>

### 4.5.2. iOS Mobile Applications Prototyping

A continuación, se presenta el prototipo de la aplicación desarrollado para la plataforma **iOS**, basado en los mockups previamente diseñados y documentados. Este prototipo nos permite visualizar algunos de los flujos principales que se implementarán en el desarrollo nativo de iOS.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Prototyping/prototype-0.png?raw=true"  alt="prototype-0">
</div><br><br>

Enlace: [Prototype de la App iOS en Figma](https://www.figma.com/design/thDm6YVmpL9RwzrpWkP1an/CambiaZo?node-id=2072-8443&t=5bRt26YwwJvCmtfr-1)<br><br>

Además, se ha elaborado un video donde se muestran los flujos de usuario dentro del prototipo iOS, detallando cada paso y su duración para facilitar la comprensión del diseño y la experiencia del usuario. Este enfoque visual permite validar la funcionalidad y detectar oportunidades de mejora antes del desarrollo.

Enlace: [Video del Prototipo para iOS](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214059_upc_edu_pe/ETDFKlDociZGsi_Dgr-d7HkBE3-AouvlOTfvXGrnDqsphg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=PWZXDX)<br><br>

**User Goal 1:** Como usuario, quiero ingresar a la aplicación iOS utilizando una cuenta.<br><br>
Tiempo: 0:12

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Prototyping/prototype-1.PNG?raw=true" alt="prototype 1">
</div><br>

**User Goal 2:** Como usuario, quiero buscar objetos para intercambiar fácilmente y obtener información detallada sobre ellos.<br><br>
Tiempo: 1:43

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Prototyping/prototype-2.PNG?raw=true" alt="prototype 2">
</div><br>

**User Goal 3:** Como usuario, quiero que otros usuarios vean los objetos que publiqué para intercambiar.<br><br>
Tiempo: 3:09

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Prototyping/prototype-3.PNG?raw=true" alt="prototype 3">
</div><br><br>

**User Goal 4:** Como usuario, quiero solicitar un intercambio a cambio de uno de los objetos de mi publicación.<br><br>
Tiempo: 4:01

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Prototyping/prototype-4.PNG?raw=true" alt="prototype 4">
</div><br><br>

**User Goal 5:** Como usuario, quiero ser notificado cuando reciba una solicitud de intercambio y tener la opción de aceptarla o rechazarla.<br><br>
Tiempo: 4:51

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Prototyping/prototype-5.PNG?raw=true" alt="prototype 5">
</div><br><br>

**User Goal 6:** Como usuario, quiero explorar y buscar ONGs y acceder a la información detallada sobre ellas.<br><br>
Tiempo: 6:21

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Prototyping/prototype-6.PNG?raw=true" alt="prototype 6">
</div><br><br>

**User Goal 7:** Como usuario, quiero explorar y obtener información sobre los perfiles de otros usuarios.<br><br>
Tiempo: 7:01

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Prototyping/prototype-7.PNG?raw=true" alt="prototype 7">
</div><br><br>

**User Goal 8:** Como usuario, quiero tener la opción de pagar una membresía y disfrutar de los beneficios que ofrece.<br><br>
Tiempo: 7:27

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Prototyping/prototype-8.PNG?raw=true" alt="prototype 8">
</div><br><br>

**User Goal 9:** Como usuario, quiero poder realizar modificaciones en mis publicaciones si considero que necesitan ajustes.<br><br>
Tiempo: 8:17

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Prototyping/prototype-9.PNG?raw=true" alt="prototype 9">
</div><br><br>

**User Goal 10:** Como usuario, quiero realizar cambios en mi perfil y mantenerlo actualizado con la información más reciente.<br><br>
Tiempo: 8:56

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Prototyping/prototype-10.PNG?raw=true" alt="prototype 10">
</div><br><br>


## 4.6. Web Applications UX/UI Design
### 4.6.1. Web Applications Wireframes

os wireframes son esenciales en el diseño de nuestras aplicaciones, ya que ayudan a planificar la interfaz y la navegación antes de empezar el desarrollo. En nuestro proyecto, utilizamos 'Figma' para crear los wireframes de manera eficiente y colaborativa.

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Wireframes-app/wireframe-0.PNG?raw=true"  alt="wireframes-appweb">
</div><br><br>

Enlace: [Wireframes de la App Web en Figma](https://www.figma.com/file/VpmoDnfHRERQvKTwxnOjLe/CambiaZo?type=design&node-id=0%3A1&mode=design&t=6tWRPswBDZfqgYDM-1)<br><br>

A continuación, mostramos los wireframes de nuestra aplicación web:


<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Wireframes-app/wireframe-1.PNG?raw=true"  alt="wireframes-1"><br><br>
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Wireframes-app/wireframe-2.PNG?raw=true"  alt="wireframes-2"><br><br>
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Wireframes-app/wireframe-3.PNG?raw=true"  alt="wireframes-3"><br><br>
</div><br>

Estos wireframes se centran en la funcionalidad de inicio de sesión, registro y cambio de contraseña en la aplicación web. La disposición de los elementos se ha optimizado para una interacción intuitiva del usuario, sin considerar detalles de diseño.<br><br>

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Wireframes-app/wireframe-4.PNG?raw=true"  alt="wireframes-4">
</div><br>

La página de inicio presenta las publicaciones de usuarios de manera organizada y equitativa. Se incluirá una barra de búsqueda y categorías para facilitar la navegación.<br><br>


<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Wireframes-app/wireframe-5.PNG?raw=true"  alt="wireframes-5">
</div><br>

Esta página mostrará una lista de organizaciones benéficas registradas, con espacio entre cada una para una mejor legibilidad. Se incluirá una barra de búsqueda dinámica para facilitar la exploración.<br><br>

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Wireframes-app/wireframe-6.PNG?raw=true"  alt="wireframes-6">
</div><br>

La página de membresía presentará los distintos planes de membresía de forma clara y ordenada, con información concisa sobre los beneficios de cada plan.<br><br>


<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Wireframes-app/wireframe-7.PNG?raw=true"  alt="wireframes-7">
</div><br>

El formulario de publicación de objetos estará diseñado de manera intuitiva, con secciones claras y espacio suficiente entre ellas para una fácil comprensión. Los campos importantes se destacarán para mejorar la experiencia del usuario.<br><br>


### 4.6.2. Web Applications Wireflow Diagrams

A continuación, se presentan los wireflows que competen a nuestros user goals.

**User goal 1:** Como usuario, quiero poder iniciar sesión y poder recuperar mi contraseña en caso de pérdida.

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Wireflow%20Diagram/wireflow-diagram-1.PNG?raw=true" alt="wireflow 1">
</div><br>
El usuario entra a la página web y se encuentra con el inicio de la misma, en la cuál verá todas las publicaciones de intercambios destacadas, incluso aquellas que poseen un boost. Para poder iniciar sesión deberá dar click al botón en la parte superior derecha, para luego ser redirigido a otra ventana en la cual podrá ingresar su correo y contraseña.
En caso el usuario haya olvidado la contraseña, tendrá la posibilidad de recuperar y cambiarla mediante un correo de confirmación para luego introducir un código de verificación.<br><br>

**User goal 2:** Como usuario, quiero poder revisar información detallada de las organizaciones benéficas que puedo apoyar.

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Wireflow%20Diagram/wireflow-diagram-2.PNG?raw=true" alt="wireflow 2">
</div><br>
El usuario entra a la página web y se dirige a una de las opciones de la barra de navegación que se llama “Donaciones”, en ella podrá visualizar todas las organizaciones benéficas afiliadas a CambiaZo, además de poder filtrar por categorías. Al clickear en una de estas, podrá visualizar información más detallada de la misma.<br><br>



**User goal 3:** Como usuario, quiero poder tener la posibilidad de suscribirse a una membresía y de esta forma obtener mejores beneficios.

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Wireflow%20Diagram/wireflow-diagram-3.PNG?raw=true"  alt="wireflow 3">
</div><br>
El usuario entra a la página web, se dirige a la barra navegadora y clickea en la opción de Membresías, en la cuál podrá visualizar todas las suscripciones disponibles con su información detallada. Al momento de seleccionar una, será redirigido a una pasarela de pagos para luego recibir un pop-up de confirmación.<br><br>

**User goal 4:** Como usuario, quiero poder verificar información sobre términos y condiciones de la compañía y política de uso

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Wireflow%20Diagram/wireflow-diagram-4.PNG?raw=true"  alt="wireflow 4">
</div><br>
El usuario entra a la página web, se dirige al footer de la misma y clickea en las opciones de términos y condiciones y/o políticas de uso, en donde podrá visualizar todos los términos legales y de uso de CambiaZo.<br><br>


**User goal 5:** Como usuario, quiero poder visualizar información de ayuda y/o tener la posibilidad de solicitar soporte al equipo de desarrollo.

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Wireflow%20Diagram/wireflow-diagram-5.PNG?raw=true"  alt="wireflow 5">
</div><br>

El usuario entra a la página web, se dirige al footer de la misma y clicke en Ayuda y/o Soporte. En la primera ventana podrá verificar información de ayuda básica sobre la página, si es que tiene algún inconveniente más específico, puede contactarse con nuestro soporte técnico.<br><br>



**User goal 6:** Como usuario quiero poder publicar mis intercambios de una manera rápida y accesible.

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Wireflow%20Diagram/wireflow-diagram-6.PNG?raw=true"  alt="wireflow 6">
</div><br>

El usuario entra a la página web y se redirige al botón de la parte superior derecha que dice “Publicar”. Una vez dentro, saldrá un formulario para que el usuario ya con una sesión iniciada, pueda realizar su publicación de intercambio, incluir datos y fotos. Para finalizar le saldrá un pop-up con un mensaje de confirmación.<br><br>


**User goal 7:** Como usuario quiero poder filtrar mi búsqueda de objetos, recibir información solo de estos mismos y visualizar información pertinente y necesaria.


<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Wireflow%20Diagram/wireflow-diagram-7.PNG?raw=true"  alt="wireflow 7">
</div><br>

El usuario entra a la página web y clickea en algunos de los botones de categorías disponibles. Después de ello se redirigirá a una ventana en la que salgan todos los resultados de publicaciones encontradas con esa misma categoría. Además de filtros específicos e información básica.<br>Una vez el usuario clickee en cualquier card de publicación, podrá ver la información de la publicación con más detalle e información del autor de la publicación.<br><br>




**User goal 8:** Como usuario quiero poder realizar una oferta, teniendo en consideración los intercambios publicados que tengo en mi perfil.

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Wireflow%20Diagram/wireflow-diagram-8.PNG?raw=true"  alt="wireflow 8">
</div><br>

Una vez el usuario haya seleccionado la publicación de interés, puede darle click a “Ofertar”. Después de ello, saldrá una ventana en la cual el usuario puede seleccionar cualquiera de sus publicaciones en su “stock” para ofrecer. Después de ello, recibirá un mensaje de confirmación. <br><br>


**User goal 9:** Como usuario quiero poder visualizar mis publicaciones en mi perfil y administrarlas según mis necesidades.

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Wireflow%20Diagram/wireflow-diagram-9.PNG?raw=true"  alt="wireflow 9">
</div><br>

El usuario se dirige al ícono de perfil, para luego visualizar las publicaciones que ha realizado en el momento. Después de ello, al darle click en “Editar perfil”, podrá ver la configuración de notificaciones que tenga, además de poder editar su información personal.<br><br>


**User goal 10:** Como usuario, quiero poder verificar las ofertas que he recibido por mis publicaciones y aceptarlas o declinar en caso contrario.

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Wireflow%20Diagram/wireflow-diagram-10.PNG?raw=true"  alt="wireflow 10">
</div><br>

  Dirigirse a la sección de perfil, para luego clickear en Ofertas, se tiene que seleccionar “Recibidas”, una vez hecho ello, se podrá visualizar todos las ofertas recibidas por las publicaciones que hemos hecho.<br><br>

Enlace: [Wireflows en LucidChart 1](https://lucid.app/lucidchart/63364102-d93b-47fe-a04f-fce263593fdf/edit?viewport_loc=-5194%2C-809%2C20455%2C7652%2C0_0&invitationId=inv_451c4fe8-c20d-4e3d-8ab3-e8df00c42f3e)<br><br>

Enlace: [Wireflows en LucidChart 2](https://lucid.app/lucidchart/ded0e94e-a2ae-4af8-84a9-30eda1490a8c/edit?viewport_loc=-422%2C4306%2C3790%2C1418%2C0_0&invitationId=inv_12e34c87-1186-4aa4-8ddb-ca02798fcd0c)<br><br>


### 4.6.3. Web Applications Mock-ups

Los mockups son otra parte esencial en el diseño de nuestras aplicaciones, ya que nos permiten visualizar la apariencia y la disposición de los elementos antes de comenzar el desarrollo.

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Mock-up-app/mock-up-0.PNG?raw=true"  alt="mockups-appweb">
</div><br><br>

Enlace: [Mock-up de la App Web en Figma](https://www.figma.com/file/VpmoDnfHRERQvKTwxnOjLe/CambiaZo?type=design&node-id=0%3A1&mode=design&t=6tWRPswBDZfqgYDM-1)<br><br>


A continuación, mostramos los mock-ups de nuestra aplicación web.
<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Mock-up-app/mock-up-1.PNG?raw=true"  alt="mockups-1"><br><br>
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Mock-up-app/mock-up-2.PNG?raw=true"  alt="mockups-2"><br><br>
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Mock-up-app/mock-up-3.PNG?raw=true"  alt="mockups-3"><br><br>
</div><br>
Páginas para el inicio de sesión, registro y cambio de contraseña en la aplicación web, con botones minimalistas con bordes redondeados y diseño agradable en nuestro color amarillo distintivo. Presentamos texto amigable y el nombre de la aplicación de manera prominente para generar percepción y reconocimiento de marca entre los usuarios. Utilizamos iconos destacados con sombreado para una fácil identificación visual por parte del usuario. Al finalizar exitosamente las operaciones, mostramos mensajes con el título resaltado en un tamaño mayor, identificados por su importancia, acompañados de un texto agradable y sencillo para mejorar la experiencia del usuario.<br><br>

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Mock-up-app/mock-up-4.PNG?raw=true"  alt="mockups-4">
</div><br>
La página de inicio muestra el logo de la aplicación para identificación rápida. Destaca las publicaciones de usuarios en cuadros equitativamente espaciados y sombreados para una apariencia ordenada y atractiva. Las publicaciones se dividen en dos tipos: las últimas y las más destacadas, estas últimas presentadas en un scroll para mayor atención del usuario y facilidad al buscarlas. La información relevante de las publicaciones se resalta mediante el tamaño de letra y otros elementos visuales para una mejor comprensión. Además, se muestra una barra de búsqueda dinámica y debajo, categorías resaltadas en amarillo que se destacan para llamar la atención del usuario de manera efectiva; estas categorías funcionan para una búsqueda rápida y dinámica por parte de los usuarios, garantizando una experiencia cómoda, agradable y visualmente atractiva.<br><br>

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Mock-up-app/mock-up-5.PNG?raw=true"  alt="mockups-5">
</div><br>
Página que muestra una lista de organizaciones benéficas registradas, con un diseño minimalista y espacio entre ellas para una mejor organización. Utilizamos botones con un color amarillo que resalta y es más visible para el usuario. Además, implementamos una barra de búsqueda dinámica para buscar organizaciones por nombre y por localidades, así como también por categorías mediante botones. Mantenemos una estética visual coherente con un diseño minimalista en toda la aplicación, lo que facilita su navegación y la hace más intuitiva para los usuarios.<br><br>


<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Mock-up-app/mock-up-6.PNG?raw=true"  alt="mockups-6">
</div><br>
Al acceder a la página de membresía, los usuarios son recibidos por un texto destacado en color amarillo que les invita de manera llamativa a formar parte de nuestra plataforma. Seguidamente, se presentan los distintos planes de membresía en cuadros rectangulares con bordes suavemente redondeados, distribuidos de manera equitativa en la página. En cuanto a la estética, los bordes de estos rectángulos están resaltados en amarillo, mientras que los paneles laterales exhiben un fondo blanco con un borde amarillo sutil, y el panel central se muestra con un fondo amarillo, atrayendo así la atención del usuario hacia los detalles de cada plan.Además se detallan los beneficios de cada plan en cuadros con texto breve para mantener la presentación ordenada. Cada cuadro está equipado con un botón negro de bordes redondeados que permite a los usuarios seleccionar su membresía y realizar el pago. Los beneficios de cada plan están listados con un icono de marca de verificación en color negro para resaltarlos junto con el texto en el mismo tono. Esta estructura visual y organización de la información hace que sea fácil para los usuarios comprender y elegir la membresía que mejor se adapte a sus necesidades.<br><br>


<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Mock-up-app/mock-up-7.PNG?raw=true"  alt="mockups-7">
</div><br>
En la página de publicación de objetos, hemos diseñado un formulario intuitivo con instrucciones claras para guiar al usuario en todo el proceso. El formulario está dividido en secciones con subtítulos claramente definidos y un espacio equitativo entre ellos para una mejor organización visual. Cada sección cuenta con un sutil sombreado con un diseño minimalista, que proporciona una experiencia agradable y cómoda para el usuario. Además, los campos importantes se destacan mediante un tamaño de letra más grande y negrita, lo que facilita su identificación y comprensión durante la creación de la publicación. También hemos incluido un botón de "Publicar" en color amarillo, destacando visualmente sobre las demás secciones para que el usuario identifique intuitivamente que ese botón es para finalizar y publicar la información.<br><br>


### 4.6.4. Web Applications User Flow Diagrams

A continuación, se presentan los diagramas de flujo de usuarios relacionados con nuestros objetivos de usuario.

**User Goal 1:** Como usuario, quiero ingresar a la aplicación web utilizando una cuenta.

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/User-Flow/goal%201.png?raw=true" alt="userflow 1">
</div><br>

El usuario accede a la aplicación. Se le presenta una ventana para iniciar sesión si ya tiene una cuenta; de lo contrario, debe registrarse. Si inicia sesión correctamente, puede usar todas las funciones de la aplicación. Si se registra con los datos correctos, se le muestra una ventana de confirmación y es llevado a la página de inicio de sesión.<br><br>


**User Goal 2:** Como usuario, quiero buscar objetos para intercambiar fácilmente y obtener información detallada sobre ellos.

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/User-Flow/goal%202.png?raw=true" alt="userflow 2">
</div><br>

El usuario está en la página de inicio. Visualiza objetos publicados por otros usuarios, incluyendo los destacados y los últimos publicados. Al seleccionar un objeto, es dirigido a otra página con más detalles sobre la publicación. También puede explorar las publicaciones al seleccionar las categorías desde la página de inicio.<br><br>



**User Goal 3:** Como usuario, quiero que otros usuarios vean los objetos que publiqué para intercambiar.

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/User-Flow/goal%203.png?raw=true" alt="userflow 3">
</div><br><br>

Desde la página de inicio, el usuario selecciona la opción de publicar. Es llevado a una página para crear una nueva publicación. Después de completar los datos necesarios y confirmar la publicación, recibe un mensaje de confirmación y su publicación es mostrada a todos los usuarios.<br><br>

**User Goal 4:** Como usuario, quiero solicitar un intercambio a cambio de uno de los objetos de mi publicación.

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/User-Flow/goal%204.png?raw=true" alt="userflow 4">
</div><br><br>

Al visualizar una publicación, el usuario presiona el botón "Ofertar". Se le muestra una ventana con sus propios objetos publicados, y puede seleccionar uno para proponer un intercambio. Recibe un mensaje de agradecimiento por parte de la aplicación.<br><br>

**User Goal 5:** Como usuario, quiero ser notificado cuando reciba una solicitud de intercambio y tener la opción de aceptar o rechazarla.

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/User-Flow/goal%205.png?raw=true" alt="userflow 5">
</div><br><br>

El usuario accede a las ofertas enviadas desde su perfil, donde encuentra las solicitudes de intercambio de otros usuarios. Puede aceptar una oferta, lo que le muestra un mensaje de confirmación y la opción de contactar al usuario por Telegram o WhatsApp para coordinar el intercambio. También puede rechazar la oferta.<br><br>


**User Goal 6:** Como usuario, quiero explorar y buscar ONGs y acceder a la información detallada sobre ellas.

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/User-Flow/goal%206.png?raw=true" alt="userflow 6">
</div><br><br>

Desde la página de inicio, el usuario accede a la sección de donaciones. Encuentra una lista de todas las ONGs disponibles y al seleccionar una, se le muestra información detallada sobre la misma.<br><br>


**User Goal 7:** Como usuario, quiero explorar y obtener información sobre los perfiles de otros usuarios.

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/User-Flow/goal%207.png?raw=true" alt="userflow 7">
</div><br><br>

Mientras visualiza una publicación, el usuario accede al perfil del usuario que la publicó para ver más información sobre él.<br><br>


**User Goal 8:** Como usuario, quiero tener la opción de  pagar una membresía y disfrutar de los beneficios que ofrece.

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/User-Flow/goal%208.png?raw=true" alt="userflow 8">
</div><br><br>

Desde la página de inicio, el usuario accede a la sección de membresías y elige el plan de su preferencia. Realiza la suscripción a través de una pasarela de pago. Una vez completado el pago con éxito, recibe un mensaje de confirmación.<br><br>

**User Goal 9:** Como usuario, quiero tener acceso claro y fácil a toda la información relevante de la aplicación.

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/User-Flow/goal%209.png?raw=true" alt="userflow 9">
</div><br><br>

Desde la página de inicio, el usuario accede a información pertinente de la aplicación, como condiciones de uso, políticas de privacidad y sección de ayuda, además de la sección de contacto para comunicarse con la empresa al completar un formulario.<br><br>

**User Goal 10:** Como usuario, quiero poder realizar modificaciones en mis publicaciones si considero que necesitan ajustes.

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/User-Flow/goal%2010.png?raw=true" alt="userflow 10">
</div><br><br>

Desde su perfil, el usuario accede a la sección de publicaciones al presionar el botón de tres puntos puede eliminar una publicación, lo que le solicita confirmación antes de eliminarla. También puede editar una publicación, lo que le permite modificar la información mediante un formulario.<br><br>



**User Goal 11:** Como usuario, quiero realizar cambios en mi perfil y mantenerlo actualizado con la información más reciente.

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/User-Flow/goal%2011.png?raw=true" alt="userflow 11">
</div><br><br>

Desde la página de inicio, el usuario accede a su perfil y realiza modificaciones, como cambiar su foto de perfil, sus datos personales o contraseña. Al cambiar la contraseña, se le muestra un formulario para realizar los cambios y al presionar “Cambiar” se le muestra un mensaje de confirmación.<br><br>

Enlace: [User Flow 1 en LucidChart](https://lucid.app/lucidchart/43f6d75d-44c8-4170-bd1c-99fd21312c75/edit?viewport_loc=-3569%2C-5403%2C2791%2C1048%2C0_0&invitationId=inv_f07bff56-c57f-4cbb-8b02-8c692958e133)<br><br>

Enlace: [User Flow 2 en LucidChart](https://lucid.app/lucidchart/4966c7f2-f561-43f5-97c3-4dae978dbcfb/edit?viewport_loc=-2622%2C-8651%2C6038%2C2267%2C0_0&invitationId=inv_6403b820-2acd-4db0-9a63-16de1d01e7c6)<br><br>

Enlace: [User Flow 3 en LucidChart](https://lucid.app/lucidchart/d12cb0f3-976b-46bf-ab0e-a545c1575e19/edit?view_items=R8dsqoYWsTCr&invitationId=inv_3ca4de93-b0e9-4de4-819a-3037cf6b4e95)<br><br>


## 4.7. Web Applications Prototyping

A continuación, se presenta el prototipo que se realizó en base a los mockups que se desarrollaron y documentaron en puntos anteriores. El prototype nos permite evidenciar algunos flujos que se llevarán al desarrollo en código.

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Prototype/prototype-app-0.PNG?raw=true"  alt="prototype">
</div><br><br>

Enlace: [Prototype de la App Web en Figma](https://www.figma.com/proto/VpmoDnfHRERQvKTwxnOjLe/CambiaZo?type=design&node-id=662-6234&t=6tWRPswBDZfqgYDM-0&scaling=scale-down&page-id=0%3A1&starting-point-node-id=662%3A4809&show-proto-sidebar=1)<br><br>


Para complementar, se ha realizado un video donde se muestran los user flows del prototipo, detallando cada flujo de interacción y definiendo el tiempo en el cual se muestran para una comprensión efectiva. Este enfoque proporciona una visión dinámica de la experiencia del usuario, facilitando la identificación de mejoras y la validación de la funcionalidad del prototipo.<br><br>

Enlace: [Video Prototype de la App Web](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214059_upc_edu_pe/EUUL7qHyT4ZEphT55Efo2EkBd8UOBk_GQsqR3o8HY9yMNg?e=3x2Yce&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)<br><br>


**User Goal 1:**  Como usuario, quiero ingresar a la aplicación web utilizando una cuenta.<br><br>

Tiempo: 0:15

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Prototype/prototype-app-1.PNG?raw=true" alt="prototype 1">
</div><br>


**User Goal 2:** Como usuario, quiero buscar objetos para intercambiar fácilmente y obtener información detallada sobre ellos.<br><br>

Tiempo: 2:48

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Prototype/prototype-app-2.PNG?raw=true" alt="prototype 2">
</div><br>


**User Goal 3:** Como usuario, quiero que otros usuarios vean los objetos que publiqué para intercambiar.<br><br>

Tiempo: 3:04

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Prototype/prototype-app-3.PNG?raw=true" alt="prototype 3">
</div><br><br>


**User Goal 4:** Como usuario, quiero solicitar un intercambio a cambio de uno de los objetos de mi publicación.<br><br>

Tiempo: 1:35

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Prototype/prototype-app-4.PNG?raw=true" alt="prototype 4">
</div><br><br>

**User Goal 5:** Como usuario, quiero ser notificado cuando reciba una solicitud de intercambio y tener la opción de aceptar o rechazarla.<br><br>

Tiempo: 0:50

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Prototype/prototype-app-5.PNG?raw=true" alt="prototype 5">
</div><br><br>


**User Goal 6:** Como usuario, quiero explorar y buscar ONGs y acceder a la información detallada sobre ellas.<br><br>

Tiempo: 1:39

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Prototype/prototype-app-6.PNG?raw=true" alt="prototype 6">
</div><br><br>



**User Goal 7:** Como usuario, quiero explorar y obtener información sobre los perfiles de otros usuarios.<br><br>

Tiempo: 2:53

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Prototype/prototype-app-7.PNG?raw=true" alt="prototype 7">
</div><br><br>



**User Goal 8:** Como usuario, quiero tener la opción de  pagar una membresía y disfrutar de los beneficios que ofrece.<br><br>

Tiempo: 3:08

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Prototype/prototype-app-8.PNG?raw=true" alt="prototype 8">
</div><br><br>


**User Goal 9:** Como usuario, quiero tener acceso claro y fácil a toda la información relevante de la aplicación.<br><br>

Tiempo: 3:48

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Prototype/prototype-app-9.PNG?raw=true" alt="prototype 9">
</div><br><br>


**User Goal 10:** Como usuario, quiero poder realizar modificaciones en mis publicaciones si considero que necesitan ajustes.<br><br>

Tiempo: 4:30

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Prototype/prototype-app-10.PNG?raw=true" alt="prototype 10">
</div><br><br>



**User Goal 11:** Como usuario, quiero realizar cambios en mi perfil y mantenerlo actualizado con la información más reciente.<br><br>

Tiempo: 4:20

<div align="center">
    <img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Prototype/prototype-app-11.PNG?raw=true" alt="prototype 11">
</div><br><br>


## 4.8. Domain-Driven Software Architecture

En esta sección emplearemos el modelo C4 para crear la estructura de software, considerando aspectos como el contexto, los recipientes, los elementos y la implementación. Este enfoque permite una comprensión sencilla de la arquitectura, tanto para los miembros del equipo como para las partes interesadas externas.

### 4.8.1. Software Architecture Context Diagram

Para lograr identificar y representar correctamente los usuarios y sistemas externos que se relacionan con nuestro sistema, hemos creado un diagrama de contexto, en el cual podemos ver que tenemos usuarios y administradores de la aplicación, y los sistemas externos son Gmail, un Servicio de Pagos, y las ONG’s.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Architecture-Overview/Domain-Driven-Software-Design/Contexto.png?raw=true" width="600px" alt="diagram context">
</div><br>

Enlace: [Diagrama de Contexto en Structurizr](https://structurizr.com/share/94931/0aebea0c-f409-4937-aadc-a82317655e11/diagrams#Contexto)<br>


### 4.8.2. Software Architecture Container Diagrams

En este diagrama de contenedores mostramos la arquitectura de CambiaZo, en la cual hemos identificado diferentes contenedores. Además se logra ver la interacción que tienen y cómo se conectan con los sistemas externos.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Architecture-Overview/Domain-Driven-Software-Design/Contenedores.png?raw=true" width="600px" alt="diagram container">
</div><br>

Enlace: [Diagrama de Contenedores en Structurizr](https://structurizr.com/share/94931/0aebea0c-f409-4937-aadc-a82317655e11/diagrams#Contenedores)<br><br>

### 4.8.3. Software Architecture Components Diagrams

En estos diagramas de componentes mostramos la arquitectura de las principales funcionalidades de CambiaZo. Además se logra ver cómo funcionan por dentro y cómo se conectan con los sistemas externos.


**Componente Gestión de Usuarios**

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Architecture-Overview/Domain-Driven-Software-Design/Component-001.png?raw=true" width="600px" alt="diagram component 1">
</div><br>

Enlace: [Diagrama de Componentes 1 en Structurizr](https://structurizr.com/share/94931/0aebea0c-f409-4937-aadc-a82317655e11/diagrams#Component-001)<br><br>

**Componente Intercambios/Trueques**

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Architecture-Overview/Domain-Driven-Software-Design/Component-002.png?raw=true" width="600px" alt="diagram component 2">
</div><br>

Enlace: [Diagrama de Componentes 2 en Structurizr](https://structurizr.com/share/94931/0aebea0c-f409-4937-aadc-a82317655e11/diagrams#Component-002)<br><br>

**Componente Configuración y Ajustes**

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Architecture-Overview/Domain-Driven-Software-Design/Component-003.png?raw=true" width="600px" alt="diagram component 3">
</div><br>

Enlace: [Diagrama de Componentes 3 en Structurizr](https://structurizr.com/share/94931/0aebea0c-f409-4937-aadc-a82317655e11/diagrams#Component-003)<br><br>


**Componente Donaciones**
<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Architecture-Overview/Domain-Driven-Software-Design/Component-004.png?raw=true" width="600px" alt="diagram component 4">
</div><br>

Enlace: [Diagrama de Componentes 4 en Structurizr](https://structurizr.com/share/94931/0aebea0c-f409-4937-aadc-a82317655e11/diagrams#Component-004)<br><br>

## 4.9. Software Object-Oriented Design

En la sección de Software Object-Oriented Design se exploran aspectos clave como los diagramas de clase y el diccionario de clases, que representan las principales clases del sistema y sus relaciones. Además, se aborda el diseño de base de datos y su diagrama asociado, que detallan la estructura y organización de los datos, ofreciendo una visión completa de la arquitectura del software.

### 4.9.1. Class Diagrams

Los diagramas de clase representan las entidades del sistema y sus relaciones de manera visual, facilitando la comprensión de la estructura y la interacción entre los componentes del software.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Architecture-Overview/Software-Object-Oriented-Design/class-diagram.png?raw=true">
</div><br>

Enlace: [Class Diagram en LucidChart](https://lucid.app/lucidchart/d7c7576a-837e-4e4b-86dc-ae903f4fdd40/edit?viewport_loc=-2282%2C-533%2C3096%2C1287%2C0_0&invitationId=inv_b3057c2c-0d68-4932-988f-920599058855)<br><br>

### 4.9.2. Class Dictionary

El diccionario de clases detalla las características y funciones de cada entidad del sistema, proporcionando una referencia completa para entender la funcionalidad del software.

- **Usuario:** Representa a los usuarios de la aplicación, quienes pueden tener objetos, hacer donaciones, crear anuncios, etc.<br>
  
- **Objeto:** Representa los objetos que los usuarios pueden subir, junto con su información asociada.<br>
  
- **Donación:** Representa las donaciones realizadas por los usuarios a organizaciones.<br>
  
- **Suscripción:** Representa las subscripciones que los usuarios pueden tener en la aplicación.<br>
  
- **Adapter:** Representa al patrón de diseño estructural “adapter” para transformar la interfaz del usuario al utilizar CambiaZo.<br>
  
- **InicioSesion:** Representa a un patrón de diseño “singleton” para que todos los usuarios tengan una sola instancia al querer iniciar sesión en CambiaZo.<br><br>

## 4.10. Database Design

### 4.10.1. Relational/Non-Relational Database Diagram

El diseño de la base de datos se ha desarrollado para gestionar eficientemente los datos relacionados con los intercambios entre usuarios dentro de la aplicación. Se crearon entidades específicas basadas en los requisitos funcionales para cubrir todas las necesidades operativas del sistema. A continuación se detalla la estructura de la base de datos:

 **Entidades**

 - **Usuarios:**
 Contiene la información básica de los usuarios registrados en el sistema. Incluye datos como nombre, correo electrónico, contraseña, fecha de registro, y otros detalles personales relevantes.

 - **Productos:**
 Almacena información detallada sobre los productos disponibles. Incluye atributos como el nombre del producto, descripción, precio, información, producto de cambio, categoría, entre otros atributos para la gestión de productos en el sistema

 - **Categoría de productos:**
 Define las categorías en las que se agrupan los productos. Cada categoría tiene un nombre único y que ayuda a organizar los productos de manera más eficiente.

 - **Productos favoritos:**
 Registra los productos que los usuarios han marcado como favoritos. Esta entidad puede vincular usuarios con productos específicos, permitiendo a los usuarios acceder rápidamente a sus productos preferidos.
 
 - **Intercambios:**
  Registra las transacciones de intercambio entre usuarios. Incluye detalles como los productos intercambiados, el usuario que inicia el intercambio, el usuario con quien se intercambia, y el estado del intercambio (pendiente, completado, cancelado).
  
 - **Reseñas:**
  Almacena las evaluaciones y comentarios de los usuarios sobre productos o servicios, incluyendo la puntuación, texto de la reseña, el intercambio realizado, y los usuarios que la hicieron y la recibieron.
 
 - **Planes:**
 Contiene información sobre los diferentes planes disponibles para los usuarios, como suscripciones premium o membresías. Incluye atributos como el nombre del plan, descripción, costo, y duración.
 
 - **Beneficios:**
 Describe los beneficios o ventajas asociados a cada plan o suscripción. Esto puede incluir acceso a características exclusivas dentro del usuario dentro de la aplicaición
 
 - **Suscripciones:**
 Registra las suscripciones activas de los usuarios a diferentes planes. Incluye detalles como el usuario que tiene la suscripción, el plan al que está suscrito, la fecha de inicio, y la fecha de expiración.

 - **Países**:
 Contiene la información sobre los países en los que operan los productos. Incluye atributos como el nombre del país y el código del país.

 - **Departamentos**: 
  Registra los departamentos dentro de cada país. Incluye detalles como el nombre del departamento y el código del departamento.

 - **Distritos**: 
  Almacena información sobre los distritos dentro de cada departamento. Incluye atributos como el nombre del distrito y el código del distrito.

 - **ONGs**: 
  Almacena la información de cada organización no gubernamental registrada, incluyendo detalles sobre su misión, visión, contacto, y otros datos relacionados. Está relacionada con las tablas de categorías, redes sociales, proyectos y cuentas bancarias.

 - **Categorías de ONG**: 
  Define el tipo de ONG mediante un identificador único y un nombre que describe la categoría a la que pertenece la organización. Está relacionado con la tabla de ONG para clasificar a las organizaciones.

 - **Proyectos**: 
  Almacena los proyectos asociados a cada ONG. Incluye información como el nombre del proyecto, una descripción breve y un enlace directo con la ONG correspondiente.

 - **Redes Sociales**: 
  Vincula cada ONG con sus cuentas de redes sociales. Incluye el nombre de la red social y la URL asociada a la ONG para dar seguimiento a su presencia en línea.

 - **Número de Cuentas**: 
  Registra los números de cuenta bancaria de las ONG. Contiene información como el nombre de la entidad financiera, el número de cuenta y el código de identificación para facilitar el soporte financiero.
  <br><br>

**Modelo Relacional**

Se eligió una base de datos relacional, ya que permite modelar fácilmente las relaciones entre entidades como productos y usuarios. Este modelo también permite mantener la integridad de los datos y ejecutar consultas complejas que son esenciales para el funcionamiento del sistema.

 **Normalización**

Se aplicaron las siguientes formas normales en el diseño de la base de datos:

- **Primera Forma Normal (1NF):** Se aseguró que todas las tablas contengan solo valores atómicos en sus columnas, eliminando grupos de repetición. Todas las entidades, como usuarios, productos, categorías de productos, ONGs, proyectos, redes sociales, categorías de ONGs, número de cuentas, países, departamentos y distritos, cumplen con esta forma normal.

- **Segunda Forma Normal (2NF):** Se garantizó que todos los atributos no clave dependan completamente de la clave primaria en las tablas con claves compuestas. Por ejemplo, las tablas intercambios, suscripciones, número de cuentas y categorías de ONGs se estructuraron para que todos los atributos relacionados dependan de manera completa de sus claves primarias.

- **Tercera Forma Normal (3FN):** Se eliminó cualquier dependencia transitiva, asegurando que todos los atributos no clave dependan únicamente de la clave primaria. Esto se aplicó a tablas como planes, beneficios, reseñas, ONGs, y proyectos, donde cada atributo está directamente relacionado con la clave primaria sin redundancias.
<br><br>

**Claves Primarias y Foráneas**

Cada entidad en la base de datos cuenta con una clave primaria que identifica de manera única cada registro. Las claves foráneas se utilizan para establecer relaciones entre tablas. Por ejemplo, en la tabla productos, el campo id es la clave primaria, y usuarios_id y categorías_productos_id son claves foráneas que relacionan productos con usuarios y categorías. De manera similar, las tablas ONGs, proyectos, redes sociales, número de cuentas, suscripciones, intercambios, reseñas, beneficios, departamentos, y distritos emplean claves primarias y foráneas para vincular registros entre sí y mantener la integridad referencial.

**Relaciones Muchos a Muchos**

Se identificaron varias relaciones muchos a muchos en el diseño de la base de datos, las cuales se resolvieron mediante el uso de tablas intermedias. A continuación se detallan algunos ejemplos:

- **Productos Favoritos:** 
La relación entre usuarios y productos se maneja a través de la tabla productos_favoritos. Esta tabla permite que un usuario tenga múltiples productos favoritos y, a su vez, que un producto sea incluido en la lista de favoritos de varios usuarios.

- **Intercambios:** 
La tabla intercambios gestiona la relación entre los usuarios que ofrecen y reciben productos. Registra tanto el usuario que ofrece su producto como el usuario que recibe la oferta, facilitando el seguimiento de las transacciones de intercambio.

- **Suscripciones:** 
La tabla de suscripciones relaciona usuarios y planes de suscripción. Cada suscripción está vinculada a un usuario y plan, permitiendo registrar las activas y el historial de suscripciones, sin permitir más de una a la vez por usuario.

- **Reseñas:** 
La relación entre usuarios y productos se maneja a través de la tabla reseñas. Esta tabla vincula a los usuarios que escriben reseñas con los intercambios de productos, facilitando el registro de evaluaciones y comentarios sobre los productos intercambiados.

Los diagramas de base de datos representan la estructura de la base de datos y las relaciones entre las entidades, lo que permite visualizar cómo se almacenan y se relacionan los datos dentro del sistema de manera eficiente.

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Architecture-Overview/Software-Object-Oriented-Design/database-diagram.png?raw=true">
</div><br>


Enlace: [Database Diagram en Vertabelo](https://my.vertabelo.com/doc/DXuXyDjv1zPkTw2ixppYDkDilQlApCUV)<br><br>



<div style="page-break-after: always;"></div>

# Capítulo V: Product Implementation

## 5.1 Software Configuration Management

A continuación, se establecerá un proceso de gestión de configuración de software que asegurará el control centralizado y organizado de todas las versiones y cambios, sirviendo como base para un desarrollo coherente y alineado con los objetivos del proyecto.

### 5.1.1 Software Development Environment Configuration

Esta sección se enfoca en la planificación, organización, coordinación y control de los recursos y tareas necesarias para llevar a cabo un proyecto de software de manera exitosa. Abarca la gestión del alcance, cronograma, costos, calidad, riesgos, recursos humanos y la comunicación, asegurando que el proyecto se complete dentro del plazo y presupuesto previstos, cumpliendo con los requisitos y metas establecidas. <br>

+ **Project Management**<br>Esta área se enfoca en la planificación, organización, coordinación y control de los recursos y actividades necesarias para completar exitosamente un proyecto de software. Abarca la gestión del alcance, tiempo, costos, calidad, riesgos, recursos humanos y comunicación, con el fin de asegurar que el proyecto se entregue dentro del plazo y presupuesto previstos, cumpliendo con los objetivos y requisitos establecidos.<br><br>

  +	<b>Pivotal Tracker:</b> Herramienta ágil de gestión de proyectos que permite a los equipos planificar, priorizar y realizar un seguimiento del trabajo de manera colaborativa. <br>https://www.pivotaltracker.com<br><br>
  
  +	<b>Trello:</b> Herramienta de gestión de proyectos basada en tableros que permite a los equipos organizar tareas, asignar responsabilidades y colaborar de manera visual y flexible. Facilita la planificación y el seguimiento de actividades mediante listas y tarjetas personalizables. <br>https://trello.com<br><br>

+ **Requirements Management**<br>Consiste en el proceso de identificar, documentar, verificar y gestionar los requisitos tanto del sistema como del software. Involucra comprender las necesidades de los usuarios y las partes interesadas, y convertirlas en requisitos funcionales y no funcionales bien definidos. El objetivo es asegurar que el software desarrollado cumpla con las expectativas y necesidades de los usuarios finales.<br><br>

  + **Pivotal Tracker:** Pivotal Tracker es una plataforma de gestión de proyectos centrada en User Stories, que se organizan en Epics y se clasifican por puntaje. Es utilizada para mantener a todos los miembros del equipo al tanto del progreso del proyecto, ofreciendo una vista en tiempo real compartida. Esto facilita la colaboración y permite a los miembros contribuir en diferentes aspectos del proyecto, manteniendo así un flujo de trabajo eficiente y bien coordinado.<br> https://www.pivotaltracker.com/n/projects/2699481<br><br>

+ **Product UX/UI Design**<br>Este aspecto se enfoca en el diseño de la experiencia del usuario (UX) y la interfaz de usuario (UI) del producto de software. UX se centra en comprender y mejorar la experiencia general del usuario al interactuar con el software, mientras que UI se refiere al diseño visual y la usabilidad de la interfaz. El objetivo del diseño UX/UI es crear una experiencia intuitiva, atractiva y eficiente para los usuarios, específicamente a través del desarrollo de un modelo para una aplicación móvil.<br><br>

	+  **Figma:**<br>Es una herramienta de prototipado web y editor de gráficos vectoriales que, a diferencia de otras herramientas, se aloja en la web. Permite crear modelos tanto para versiones de navegador web como para navegadores móviles de la landing page, así como para la versión Android de la aplicación móvil.<br>https://www.figma.com/design/<br><br>


	+ **Lucidchart:**<br>Es una herramienta de diagramación en línea que permite crear diagramas de flujo, wireflow, userflow y otros esquemas visuales. Es especialmente útil para mapear la experiencia del usuario y visualizar el flujo de interacciones en aplicaciones móviles.<br>https://www.lucidchart<br><br> 

    + **UXPressia:**<br> Es una herramienta en línea para el mapeo de la trayectoria del cliente que crea mapas de impacto y personas. Sus herramientas nos permitieron establecer las bases del modelado de User Persona, Empathy Map y Journey Map.<br>https://uxpressia.com/ 

    + **MIRO:**<br>Es una pizarra digital colaborativa en línea, que puede ser usada para la investigación, la ideación, mapas mentales, as-is, to-be y una variedad de otras actividades colaborativas.<br>https://miro.com/app/dashboard/

    + **Vertabelo:**<br> Es una herramienta que permite a los usuarios crear diagramas de bases de datos de manera intuitiva y colaborativa, facilitando la visualización y comprensión de la estructura de la base de datos.<br>https://my.vertabelo.com/drive 

    + **Structurizr:**<br> Es una herramienta de diseño que soporta el modelo C4, para visualizar la arquitectura de software de nuestra solución. <br>https://structurizr.com/ 

<br>

+ **Software Development**<br>Es el proceso de crear, diseñar, programar, probar y mantener el software. Incluye la implementación de los requisitos definidos en el proceso de desarrollo de software, utilizando diferentes lenguajes de programación, herramientas y tecnologías. El objetivo es construir un producto de software funcional y de alta calidad que cumpla con los requisitos y expectativas del cliente.<br><br> 

  + **GitHub:** Es un repositorio comunitario cuya función es almacenar los avances de un proyecto elaborado por un grupo de personas. Facilita la colaboración y el seguimiento de cambios en el código.<br>https://github.com/TechZo-1ASI0732-4453<br><br> 
  
  +  **Kotlin:** Lenguaje de programación moderno y conciso utilizado principalmente para el desarrollo de aplicaciones móviles. Su interoperabilidad con Java y sus características avanzadas permiten una programación más eficiente y productiva.<br>https://kotlinlang.org/<br><br> 
  
  + **Android Studio:** Entorno de desarrollo integrado (IDE) oficial para el desarrollo de aplicaciones Android. Proporciona herramientas avanzadas para la edición de código, diseño de interfaces y pruebas, optimizando el proceso de desarrollo.<br>https://developer.android.com/studio<br><br> 
  
  + **Astro:** Framework para la creación de sitios web estáticos que permite construir landing pages rápidas y eficientes. Utiliza componentes de diferentes frameworks como React y Vue, optimizando la carga de contenido y mejorando la experiencia del usuario.<br>https://astro.build/<br><br> 
  
  +  **Postman:** Herramienta utilizada para probar y documentar APIs de manera eficiente, facilitando la colaboración entre desarrolladores y la integración de servicios en la aplicación móvil.<br>https://www.postman.com/<br><br>

   + **HTML:**<br>  Es el lenguaje estándar para crear y diseñar sitios web. Utiliza etiquetas para estructurar el contenido, como texto, imágenes y enlaces. Junto con CSS y JavaScript, HTML forma la base de la web moderna. Este lenguaje será utilizado en el presente proyecto para implementar la documentación de la página web.<br>https://www.jetbrains.com/help/webstorm/editing-html-files.html 

  + **CSS:**<br> Es un lenguaje de estilo utilizado para controlar el diseño y la presentación de páginas web. Permite establecer colores, fuentes, márgenes y otros aspectos visuales para mejorar la apariencia de un sitio web. Este lenguaje se utilizará para la implementación del diseño de nuestra plataforma web.<br>https://www.jetbrains.com/help/webstorm/style-sheets.html#ws_css_completion 

  + **JavaScript:**<br> Es un lenguaje de programación de alto nivel que se utiliza principalmente para agregar interactividad y dinamismo a los sitios web. Permite realizar acciones como validar formularios, animar elementos y actualizar contenido sin recargar la página. Se utilizará para la elaboración de las dinámicas de la plataforma web.<br>https://www.jetbrains.com/help/webstorm/javascript-specific-guidelines.html 


  + **TypeScript:**<br> Es un superset de JavaScript que agrega tipado estático y otras características avanzadas al lenguaje. Permite escribir código más seguro y mantenible, especialmente en proyectos grandes y complejos.<br>https://www.typescriptlang.org/docs/handbook/typescript-from-scratch.html

  + **Java:**<br>  Es un lenguaje de programación popular y versátil que se utiliza en una variedad de aplicaciones, desde desarrollo web hasta aplicaciones empresariales y móviles. Java se destaca por su portabilidad y su robusto sistema de tipos. Se utilizará para la elaboración de las dinámicas de la plataforma web.<br>https://www.java.com/es/download/help/whatis_java.html

  + **Angular Material:**<br>Es una biblioteca de componentes de interfaz de usuario desarrollada para Angular que sigue las directrices de diseño de Material Design de Google. Proporciona una amplia gama de componentes listos para usar para crear aplicaciones web con una apariencia y sensación consistentes y atractivas. Integrado con Angular, facilita el desarrollo de aplicaciones web para los desarrolladores.<br>https://material.angular.io/

  + **Spring Boot:** Framework basado en Java que facilita la creación de aplicaciones empresariales de manera rápida y eficiente. Se utiliza para simplificar la configuración y desarrollo del backend de nuestra aplicación móvil, ofreciendo integración con herramientas de despliegue y un entorno de desarrollo ágil.<br>https://spring.io/projects/spring-boot <br><br>

  + **IntelliJ IDEA:** IDE para Java y otros lenguajes de programación, con avanzadas funciones de autocompletado, refactorización y depuración. Será utilizado para el desarrollo del backend de nuestra aplicación móvil, proporcionando un entorno eficiente para la codificación y gestión del código.<br>https://www.jetbrains.com/idea/<br><br>

  + **Workbench:** Entorno de desarrollo integrado que proporciona herramientas para el diseño, implementación y prueba de aplicaciones. Se utilizará para gestionar el desarrollo y la integración de nuestra aplicación móvil, ofreciendo funcionalidades para la gestión de datos y la automatización de procesos.<br>https://www.workbench.com/ <br><br>

  + **SQL:** Lenguaje de consulta estructurado utilizado para gestionar y manipular bases de datos relacionales. Se utilizará para definir, modificar y consultar los datos en la base de datos de nuestra aplicación móvil, facilitando la interacción y la gestión eficiente de la información.<br>https://www.sql.org/ <br><br>




+ **Software Testing**<br>Se refiere a la actividad de verificar y validar el software para garantizar su calidad y correcto funcionamiento. Involucra la ejecución de pruebas funcionales y no funcionales para identificar errores, defectos o problemas en el software antes de su lanzamiento. El objetivo es asegurar que el software sea confiable, robusto y cumpla con los requisitos y expectativas del usuario final.<br><br> 

  + **Lenguaje Gherkin:** Es un lenguaje de dominio específico (DSL) utilizado en el desarrollo de software para escribir pruebas de aceptación en un formato legible por humanos. Utiliza palabras clave como Given, When y Then para describir el estado inicial, la acción y el resultado esperado de un escenario de prueba, facilitando la colaboración entre equipos al definir requisitos y pruebas.<br>https://cucumber.io/<br><br> 


+ **Software Deployment**<br> Es el proceso de implementar y poner en funcionamiento el software en un entorno de producción o en los dispositivos de los usuarios finales. Incluye actividades como la instalación, configuración, migración de datos y puesta en marcha del software. El objetivo es garantizar una implementación exitosa y sin problemas del software en el entorno de producción.<br><br> 

	+ **Netlify:** Es una plataforma de despliegue y alojamiento para aplicaciones web estáticas y dinámicas, que permite implementar automáticamente cada commit desde repositorios de Git. Ofrece gestión de dominios y optimización de rendimiento, facilitando el despliegue ágil de la landing page.<br>https://www.netlify.com/<br><br>

  + **Amazon Azure:** Plataforma en la nube que ofrece servicios de computación, almacenamiento y gestión de aplicaciones. Se utilizará para desplegar el backend de nuestra aplicación móvil, aprovechando sus capacidades de escalabilidad, almacenamiento y gestión de recursos en la nube. <br> https://azure.microsoft.com/ <br><br>

+  **Software Documentation**<br>Se refiere a la creación y mantenimiento de documentos que describen el software, incluyendo su arquitectura, diseño, funcionamiento, instalación, configuración, uso y mantenimiento. La documentación proporciona información útil y detallada sobre el software para desarrolladores, usuarios finales, administradores de sistemas y otras partes interesadas.<br><br> 

	+  **Markdown:** Es un lenguaje de marcado ligero que permite escribir texto con un formato fácil de leer y escribir, que luego puede ser convertido a HTML u otros formatos de presentación. Es ampliamente utilizado para documentar proyectos de software debido a su simplicidad y versatilidad. Markdown permite agregar formato básico como encabezados, listas, enlaces e imágenes utilizando una sintaxis sencilla y fácil de recordar.<br>https://www.markdownguide.org/getting-started/<br><br>


### 5.1.2 Source Code Management

Para administrar de manera efectiva el progreso del código en la aplicación móvil y la landing page, hemos adoptado la metodología Git Flow. Esta estrategia se basa en el uso de ramas, lo que facilita la gestión del código durante el desarrollo. En resumen, Git Flow nos permite mantener una rama principal (main) que contiene una versión estable del proyecto. Utilizamos también una rama de desarrollo para integrar nuevas funcionalidades sin afectar la versión estable actual, lo que nos permite avanzar en el desarrollo de la aplicación y realizar pruebas de nuevas características.

Hemos optado por GitHub como nuestra plataforma de gestión de código, gracias a sus características avanzadas que facilitan la visualización del proyecto y la gestión colaborativa a través de herramientas de integración continua.

En cuanto a nuestros Acceptance Test, hemos creado una nueva rama product/feature/[Sprint a desarrollar]” para cada sprint que se lleve a cabo en el desarollo del producto. Este enfoque modular y organizado garantiza un desarrollo progresivo, ya que cada rama actúa como un espacio aislado para probar y realizar actualizaciones antes de fusionarlas con la rama de desarrollo.

Además, para los repositorios de la landing page, aplicación web y la aplicación móvil, hemos establecido ramas “feature/[US a desarrollar]” para cada nueva funcionalidad que deseamos agregar. Este enfoque permite un desarrollo más ordenado y estructurado, ya que cada rama representa una unidad de trabajo específica relacionada con una funcionalidad, lo que facilita el control y avance del proyecto sin necesidad de una rama de desarrollo.


Repositorio GitHub de la Landing Page: https://github.com/TechZo-1ASI0732-4453/Landing-Page <br>

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Source-Code-Management/repositorio-landing-page.png?raw=true"  alt="Repositorio Landing Page">
</div><br>

Repositorio GitHub de la Aplicación Móvil: https://github.com/TechZo-1ASI0732-4453/CambiazoApp <br>

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Source-Code-Management/repositorio-mobile-app.png?raw=true"  alt="Repositorio App Móvil">
</div><br>

Repositorio GitHub de los archivos feature: https://github.com/TechZo-1ASI0732-4453/Acceptance-Test <br>

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Source-Code-Management/repositorio-acceptance-test.png?raw=true" alt="Repositorio archivos feature">
</div><br><br>


Enlace de la Aplicación Web en Netlify: https://cambiazo-techzo.netlify.app/ <br><br> 

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Source-Code-Management/netlify-deploy.png?raw=true">
</div><br>

Repositorio GitHub de la Aplicación Web: https://github.com/TechZoOrganization-OpenSource/CambiaZo-Frontend <br><br> 

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Source-Code-Management/repositorio-web-app.png?raw=true">
</div><br>

Repositorio GitHub del backend: https://github.com/TechZo-1ASI0732-4453/Backend <br><br> 

<div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Source-Code-Management/repositorio-backend.png?raw=true">
</div><br>


### 5.1.3 Source Code Style Guide & Conventions

En esta sección, establecemos las convenciones de estilo y mejores prácticas para el desarrollo de nuestra aplicación móvil CambiaZo y la landing page, utilizando Kotlin y Astro. Estas reglas son fundamentales para garantizar la legibilidad, mantenibilidad y escalabilidad del código a lo largo del ciclo de vida del proyecto.

El uso coherente de estas convenciones también facilita la colaboración entre desarrolladores, ya que se minimizan las discrepancias en la forma en que se escribe y estructura el código. Asimismo, emplearemos Gherkin para la definición de pruebas de aceptación, asegurando que cada funcionalidad cumpla con los requisitos y expectativas del usuario.
<br><br>

**KOTLIN**

Kotlin es un lenguaje de programación moderno y conciso que se ejecuta en la Máquina Virtual de Java (JVM) y es totalmente interoperable con Java, lo que facilita su adopción en proyectos existentes. Destaca por su seguridad de tipos, que ayuda a prevenir errores comunes como el NullPointerException, y su capacidad para soportar programación funcional a través de funciones de orden superior y expresiones lambda. Además, ofrece características como funciones de extensión que permiten ampliar la funcionalidad de las clases sin necesidad de herencia, y permite el desarrollo multiplataforma, lo que facilita la creación de aplicaciones para diferentes entornos, incluidas aplicaciones móviles.

+ **Nomenclatura en Inglés y uso de Minúsculas**

	En nuestro proyecto, todas las clases, funciones, variables y constantes serán nombradas en inglés y de manera descriptiva. Se adoptará  camelCase para funciones y variables, mientras que  PascalCase se utilizará para las clases. Esta práctica mejorará la claridad del código y facilitará la comprensión de la funcionalidad de cada elemento.

  Ejemplo: 
  ```
   // Mala práctica
   var usrAge: Int = 25

   // Buena práctica
   var userAge: Int = 25
  ```

+ **Identación o Sangría**

	Se utilizarán  4 espacios para la indentación del código, evitando el uso de tabulaciones. Esta decisión es fundamental para garantizar que la estructura del código sea clara y que la jerarquía y los bloques sean fácilmente comprensibles.

  Ejemplos:
  ```
	class UserService {
	    fun createUser(user: User) {
	        if (user != null) {
	            userRepository.save(user)
	        }
	    }
	}
  ```

+ **Llaves y Estructura de Código**

	Las llaves se abrirán en la misma línea que la declaración correspondiente y se cerrarán alineadas con el inicio de dicha declaración. Este estilo contribuye a mantener una estructura clara y consistente, facilitando el seguimiento del flujo de control en el código.

  Ejemplo:
	```
	// Mala práctica
	fun createUser(user: User) 
	{
	    if (user != null) 
	    {
	        userRepository.save(user)
	    }
	}
	// Buena práctica
	fun createUser(user: User) {
	    if (user != null) {
	        userRepository.save(user)
	    }
	}
	```

+ **Uso de Constantes**

	Las constantes en Kotlin se declararán utilizando `const val` para aquellos valores que son conocidos en tiempo de compilación y `val` para valores que no cambian durante la ejecución. Se utilizará una nomenclatura en mayúsculas, separadas por guiones bajos, para diferenciarlas claramente de las variables.

  Ejemplo:
  ```
  const val MAX_ATTEMPTS: Int = 5
  ```

* **Uso de Comentarios**

	Los comentarios se utilizarán para explicar el por qué de las decisiones de código, en lugar de describir lo que el código realiza, lo cual debería ser evidente a través de la nomenclatura. Se empleará el formato KDoc para documentar métodos públicos y clases, facilitando así la generación de documentación.

  Ejemplo:
  ```
	/**
	 * Retrieves a user by their ID.
	 *
	 * @param id the ID of the user to retrieve
	 * @return the user object, or null if not found
	 */
	fun getUserById(id: Long): User? {
	    return userRepository.findById(id).orElse(null)
	}
  ```

+ **Uso de Funciones Composable**

	Las funciones composables se declararán con la anotación `@Composable`, y se espera que sean funciones puras que no dependan de variables externas, a menos que se pasen como parámetros. Este enfoque garantiza que las funciones sean reutilizables y predecibles.

  Ejemplo:
  ```
	@Composable
	fun UserProfile(name: String, age: Int) {
	    Column {
	        Text(text = "Name: $name")
	        Text(text = "Age: $age")
	    }
	}
  ```

+ **Composición Anidada**

	Dividir la interfaz de usuario en componentes más pequeños y modulares facilitará la legibilidad y el mantenimiento del código. Cada componente será responsable de una única tarea, lo que permitirá su reutilización y prueba más efectivas.

  Ejemplo:
  ```
	@Composable
	fun UserScreen() {
	    UserProfile(name = "John Doe", age = 30)
	}
  ```

+ **Manejo del Estado**

	Se utilizarán `remember` y `mutableStateOf` para almacenar el estado que necesita sobrevivir a las recomposiciones. Este enfoque permitirá que la interfaz de usuario responda de manera eficiente a los cambios de estado.

  Ejemplo:
  ```
	  @Composable
	fun Counter() {
	    var count by remember { mutableStateOf(0) }
	    Column {
	        Text(text = "Count: $count")
	        Button(onClick = { count++ }) {
	            Text(text = "Increment")
	        }
	    }
	}
  ```
 
 + **Previsualización de Composables**

	Se utilizará la anotación `@Preview` para mostrar vistas previas de los composables en Android Studio. Esto facilitará el diseño y la iteración, permitiendo a los desarrolladores visualizar la interfaz sin necesidad de compilar y ejecutar la aplicación.

	Ejemplo:
	```
	@Preview
	@Composable
	fun PreviewUserProfile() {
	    UserProfile(name = "Jane Doe", age = 25)
	}
	  ```
	  
<br><br>

**ASTRO**

Astro es un framework moderno que permite construir sitios web estáticos rápidos y optimizados, centrándose en el rendimiento y la experiencia del usuario. Utilizaremos Astro para el desarrollo de nuestra landing page, aprovechando su capacidad de generar páginas eficientes con menos JavaScript, lo que garantiza tiempos de carga rápidos y una mejor experiencia de usuario. Una característica clave es su "island architecture", que permite cargar solo los componentes interactivos necesarios.

 + **Uso de Componentes**

	Para garantizar la modularidad y reutilización del código, definiremos componentes de manera que cumplan con una sola responsabilidad. Los nombres de los archivos de componentes seguirán el formato PascalCase, y cada componente será autocontenido para facilitar su comprensión y mantenimiento.

	Ejemplo:
	```
	---
	  // Header.astro
	---
	<header class="header">
	  <h1>Bienvenido a CambiaZo</h1>
	</header>
	
	<style>
	  .header {
	    background-color: #ff6347;
	    padding: 1rem;
	    color: white;
	  }
	</style>
	```

 + **Optimización del Rendimiento**

	Aplicaremos la arquitectura  islands de Astro para cargar JavaScript únicamente donde sea necesario. Esto nos permitirá generar páginas estáticas y mejorar el rendimiento de la landing page. Aquí un ejemplo de cómo cargaremos un componente React solo cuando se necesite:

	Ejemplo:
	```
	---
	  import Button from '../components/Button.jsx';
	---

	<h1>Descubre CambiaZo</h1>
	<Button client:load />
	```
	
 + **Estilos CSS**

	Los estilos estarán encapsulados dentro de cada componente siempre que sea posible, para evitar conflictos globales y mantener el código CSS organizado. Sin embargo, también importaremos estilos globales para elementos comunes como el diseño general de la página.

	Ejemplo:
	```
	---
	  // Hero.astro
	---
	<section class="hero">
	  <h1>Intercambia artículos fácilmente</h1>
	</section>

	<style>
	  .hero {
	    text-align: center;
	    padding: 4rem;
	    background-color: #f9f9f9;
	  }
	</style>
	```

 + **Carga de Imágenes Optimizada**

	Al incorporar imágenes, nos aseguraremos de que se carguen de manera eficiente mediante el uso de las etiquetas `picture` y `img` con la carga diferida (`loading="lazy"`), lo que mejorará significativamente el tiempo de carga de la página.

	Ejemplo:
	```
	<picture>
	  <source srcset="/images/banner.webp" type="image/webp">
	  <img src="/images/banner.jpg" alt="Banner de CambiaZo" loading="lazy">
	</picture>
	```
 + **Buenas Prácticas de Accesibilidad**

	Nos comprometemos a seguir las mejores prácticas de accesibilidad. Para ello, usaremos etiquetas semánticas adecuadas y proporcionaremos descripciones claras en los elementos interactivos como botones y enlaces.

	Ejemplo:
	```
	<button aria-label="Iniciar intercambio">Intercambiar</button>
	```
	
<br><br>	

**TYPESCRIPT**

Para nuestro proyecto, hemos elegido Typescript, un superset de JavaScript que añade tipado estático opcional al lenguaje. Typescript proporciona una amplia gama de nuevas características y mejoras con respecto a JavaScript, lo que lo convierte en una opción popular para el desarrollo de aplicaciones web y de Node.js. A continuación, se presentarán las características y directrices que seguiremos para el desarrollo utilizando este lenguaje.

+ **Naming Conventionns**

Esha Garg (2020) señala la importancia de mantener un orden adecuado al nombrar variables, constantes, métodos y clases:

Ejemplo: 

```
Nombres de variables: camelCase
firstNumber = 12

Constantes: UPPER_CASE con ‘_’ entre las palabras

const FIRST_NUMBER = 18

Nombres de métodos: camelCase

sumOfTwoNumbers()

Nombres de clases: PascalCase

export class EmployeeDetails {}

Nombres de archivos: lower-case (Separados por ‘-’ si el nombre es de 2 a más palabras)

employee-details
```
+ **Data type of variables and methods**

Esha Garg (2020) sugiere incluir los tipos de datos tanto para los parámetros de los métodos como para los valores de retorno. Al definir un método, es importante especificar el tipo de datos esperado para cada parámetro que recibe y el tipo de datos que el método devuelve, lo que proporciona claridad sobre el tipo de información que se puede esperar como resultado de su ejecución.

Ejemplo:

```
En variables:
firstNumer: number

En métodos:
function sum(firstNumber: number, secondNumber:number):number{
  return firstNumber + secondNumber;
}
```

+ **Spaces Around Operators**

Según W3Schools, se recomienda siempre colocar espacios alrededor de los operadores (=, +, -, *, /) y después de las comas al escribir código TypeScript. Esto ayuda a mejorar la legibilidad y la claridad del código, facilitando su comprensión y mantenimiento.

Ejemplo: 

```
let z:number = x + y;
const myArray:string[] = ["Toyota", "Kia", "Hyundai"];
```

  <br><br>

**JAVA**

Java es un lenguaje de programación orientado a objetos, robusto y de propósito general. Es conocido por su portabilidad gracias a la máquina virtual de Java (JVM), que permite ejecutar el mismo código en diferentes plataformas. Su enfoque en la simplicidad, la seguridad y la escalabilidad lo convierte en una elección popular para el desarrollo de aplicaciones empresariales y sistemas distribuidos.

+ **Nomenclatura en Inglés y uso de Minúsculas**

  Todas las clases, métodos, variables y constantes deben estar nombradas en inglés y de manera descriptiva, utilizando camelCase para métodos y variables, y PascalCase para las clases. Se evitarán las abreviaturas ambiguas para mejorar la claridad.


  Ejemplo: 
  ```
  // Mala práctica
  int prsnAge;

  // Buena práctica
  int personAge;
  ```

+ **Identación o Sangría**

  En Java, la indentación es crucial para la legibilidad. Utilizaremos 4 espacios para la sangría, y se evitará el uso de tabulaciones. Además, todos los bloques de código deben estar debidamente indentados y alineados.


  Ejemplos:

  ```
  public class UserService {
     public void createUser(User user) {
          if (user != null) {
              userRepository.save(user);
          }
     }
  }
  ```

+ **Llaves y Estructura de Código**

  En Java, las llaves deben abrirse en la misma línea que la declaración correspondiente y cerrarse alineadas con el inicio de dicha declaración. Esto mantiene una estructura clara y consistente.

  Ejemplo:
  ```
  // Mala práctica
  public void createUser(User user)
  {
      if (user != null)
      {
          userRepository.save(user);
      }
  }

  // Buena práctica
  public void createUser(User user) {
      if (user != null) {
          userRepository.save(user);
      }
  }
  ```

+ **Uso de Constantes**
  Las constantes en Java deben declararse como static final y nombrarse con mayúsculas separadas por guiones bajos.

  Ejemplo:
  ```
  public static final int MAX_ATTEMPTS = 5;
  ```

+ **Espacios alrededor de Operadores**

  Se colocarán espacios alrededor de los operadores aritméticos, de comparación y asignación para mejorar la legibilidad del código.

  Ejemplo:
  ```
  int sum = a + b;
  if (x == y) {
      return true;
  }
  ```

+ **Uso de Comentarios**

  Los comentarios deben ser usados para explicar el por qué de las decisiones de código, no para describir lo que el código hace (esto debería ser evidente por la nomenclatura clara). Para los comentarios, utilizaremos el formato Javadoc para métodos públicos y clases.

  Ejemplo:
  ```
  /**
  * Retrieves a user by their ID.
  *
  * @param id the ID of the user to retrieve
  * @return the user object
  */
  public User getUserById(Long id) {
      return userRepository.findById(id).orElse(null);
  }
  ```

<br><br>

**GHERKIN**

Gherkin es un Lenguaje Específico de Dominio (DSL) diseñado para abordar problemas específicos al generar casos de validación de características en diversos escenarios. Este lenguaje se utiliza para describir el comportamiento deseado de un software de manera comprensible para personas no técnicas. Gherkin presenta varios elementos, entre los que se destacan Feature, Scenario, Example, Given, When y Then, los cuales son ampliamente utilizados para definir las características y los pasos de las pruebas de comportamiento.

Las pautas a tener en cuenta al utilizar Gherkin en nuestro código incluyen:

  

* **Discernible Given-When-Then Blocks**
  
  Según la sugerencia de Keiblinger, para facilitar la comprensión y la organización de los escenarios en Gherkin, se recomienda indentar los pasos que comienzan con "And" después de cada Given, When o Then. Esto permite distinguir claramente dónde termina un bloque y comienza otro, incluso en escenarios con múltiples pasos.

  Ejemplo de Sophie Keiblinger :

  ```
  Scenario: Discernible Given-When-Then Blocks

  In order to quickly spot where one block ends and another one begins, you can indent the steps starting with “And”

  Given I need to prepare some data for my  scenario

  And this is more complex so I need a second step

  And this is more complex so I need a third step

  When I trigger some action

  Then I can see the expected outcome

  And this outcome also has a second step

  And this outcome also has a third step
  ```

* **Steps with Tables**
  
  Keiblinger nos sugiere utilizar un colon (:) al final de los pasos que requieren más entrada de una tabla. Esto ayuda a hacer inmediatamente reconocible que se espera una tabla como parte de la entrada del paso.

  Ejemplo de Sophie Keiblinger:

  ```
  Given I need to prepare the following data for my scenario:

  |  column 1  | column 2 |
  | necessary |     data     |
  ```

* **Reducing Noise**

  Keiblinger sugiere utilizar valores por defecto para campos que el sistema requiere pero que no son pertinentes para el escenario en cuestión. Por ejemplo, al probar la validación de una fecha de nacimiento, no es necesario especificar el nombre de la persona, título académico o número de seguro social. Esta  inclusión no afecta al resultado del escenario. Esta práctica ayuda a simplificar los escenarios y a enfocarse en las características específicas que se están probando.

  Ejemplo:

  ```
  When el visitante se acerque a la sección ‘Comunícate con nosotros’
  ```

* **Newlines between scenarios and separator comments**

  Keiblinger nos dice que para mantener la claridad en los archivos de escenarios de Gherkin, especialmente cuando estos son extensos o contienen múltiples escenarios, se recomienda agregar dos líneas en blanco entre cada escenario. Esto ayuda a distinguir claramente dónde termina un escenario y comienza otro. Además, es común añadir un comentario separador para brindar una guía visual adicional y facilitar la navegación en el archivo.

  Ejemplo:
  ```
  #-----------------------------------------------------------------------------------
  Scenario: Acceso a la historia de TechZo
          Given que soy un visitante de la landing page
          When navegue por la página de inicio
          And encuentre la sección titulada "¿Quiénes Somos?"
          Then podré obtener información detallada sobre la historia de la startup.

  #-----------------------------------------------------------------------------------

      Scenario: Acceso a las redes sociales de TechZo
          Given que el visitante se encuentra en el landing page
          When el visitante de click en la etiqueta “Contáctanos”
          And encuentre los botones con los logos de las redes sociales en las que puede encontrar la página de TechZo
          And de click encima del botón con el logo de la red social que desee ver
          Then el usuario será redireccionado a la red social que seleccionó previamente.
  ```
  
  
<br>

### 5.1.4 Software Deployment Configuration

En esta sección mostraremos los pasos que hemos realizado para poder desplegar cada uno de nuestros proyectos.

**Landing Page**

Para desplegar nuestra Landing Page hemos optado por usar Netlify,el cual brinda la posibilidad de alojar sitios web estáticos sin costo alguno.

**1. Ingresamos a la página web de Netlify**
<div  align="center"><img  src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-V/Software-Deployment-Configuration/deploy-landing-0.png?raw=true"  alt="netlify"></div>
<br>

**2. Iniciamos sesión con GitHub para poder usar los repositorios de nuestra cuenta**
<div  align="center"><img  src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-V/Software-Deployment-Configuration/deploy-landing-1.png?raw=true"  alt="netlify"></div>
<br>

**3. Seleccionamos el repositorio que queremos emplear**
<div  align="center"><img  src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Software-Deployment-Configuration/deploy-landing-2.jpeg?raw=true"  alt="netlify"></div>
<br>

**4. Elegimos un nombre dentro de la documentación permitida, para el dominio de la página.**
<div  align="center"><img  src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Software-Deployment-Configuration/deploy-landing-3.jpeg?raw=true"  alt="netlify"></div>
<br>


**5. Finalmente la Landing Page estaría disponible.**
<div  align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Sprint-1/Execution-Evidence/landing-page-1.png?raw=true" alt="netlify" ></div><br>

Elegimos Netlify debido a que su plataforma es muy fácil e intuitiva de utilizar, además de que podemos aprovechar en usar los repositorios que tengamos y de esta forma gestionar los avances y versiones de acuerdo al repositorio, para que luego los cambios se vean reflejado en la página.

<br>

## 5.2 Product Implementation & Deployment

### 5.2.1 Sprint Backlogs

El objetivo de este primer sprint fue desarrollar y completar por completo el backend de la aplicación, encargado de gestionar datos clave como los objetos de intercambio, productos favoritos, suscripciones y reseñas, garantizando un funcionamiento eficiente. Además, se finalizó el desarrollo de la landing page, estableciendo una base sólida para la presentación del proyecto y futuras funcionalidades avanzadas.

Enlace: [Sprints Backlogs Trello](https://trello.com/invite/b/68253f6b5a6b20fec48a9604/ATTIb8b2ae680b376e13193cf896e7e49970C1F19E6C/cambiazo-diseno)<br><br>

<div align="center">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Sprint-1/Sprint-Backlog/Sprints.png?raw=true" alt="sprints">
</div><br><br>

**Sprint 1 - Backend**

<table>
<thead>
  <tr>
    <th colspan="2">User Story</th>
    <th colspan="6">Work-Item / Task</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Id</td>
    <td>Title</td>
    <td>Id</td>
    <td>Title</td>
    <td>Description</td>
    <td>Estim<br>ation (Hours)</td>
    <td>Assigned to</td>
    <td>Status (To-do / InProcess / ToReview / Done)</td>
  </tr>
  <tr>
    <td rowspan="1">TS01</td>
    <td rowspan="1">API User</td>
    <td>WI-01</td>
    <td>Metodos CRUD para Usuarios</td>
    <td>Implementación de los metodos POST, GET, UPDATE y DELETE para poder manejar los datos de la tabla usuarios y relacionadas.</td>
    <td>10</td>
    <td>Jeremy Quispe</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">TS02</td>
    <td rowspan="1">API Exchanges</td>
    <td>WI-04</td>
    <td>Metodos CRUD para Intercambios</td>
    <td>Implementación de los métodos POST, GET, UPDATE y DELETE para gestionar los datos de la tabla de intercambios, permitiendo a los usuarios manejar y organizar sus intercambios segun sus necesidades.</td>
    <td>10</td>
    <td>Ian Santisteban</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">TS03</td>
    <td rowspan="1">API ONGs</td>
    <td>WI-02</td>
    <td>Metodos CRUD para ongs</td>
    <td>Implementación de los métodos POST, GET, UPDATE y DELETE para manejar los datos de la tabla Ongs y gestionar las Ongs de los usuarios.</td>
    <td>10</td>
    <td>Mathias Mendoza</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">TS02</td>
    <td rowspan="1">API Review</td>
    <td>WI-02</td>
    <td>Metodos CRUD para reseñas</td>
    <td>Implementación de los métodos POST, GET, UPDATE y DELETE para manejar los datos de la tabla reseñas y gestionar las opiniones de los usuarios.</td>
    <td>10</td>
    <td>Sandro Quispesivana</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">TS05</td>
    <td rowspan="1">API Memberships</td>
    <td>WI-05</td>
    <td>Metodos CRUD para membresias</td>
    <td>Implementación de los métodos POST, GET, UPDATE y DELETE para gestionar los datos de la tabla de membresías, permitiendo a los usuarios suscribirse a diferentes planes.</td>
    <td>10</td>
    <td>Joseph Huamani</td>
    <td>Done</td>
</tr>
</tbody>
</table>

**Sprint 1 - Product**

<table>
<thead>
  <tr>
    <th colspan="2">User Story</th>
    <th colspan="6">Work-Item / Task</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Id</td>
    <td>Title</td>
    <td>Id</td>
    <td>Title</td>
    <td>Description</td>
    <td>Estim<br>ation<br>(Hours)</td>
    <td>Assigned<br>to</td>
    <td>Status<br>(To-do /<br>InProcess /<br>ToReview /<br>Done)</td>
  </tr>
  <tr>
    <td rowspan="1">US01</td>
    <td rowspan="1">Registro<br>de<br>usuario</td>
    <td>WI-01</td>
    <td>Sección<br>para<br>nuevos<br>usuarios</td>
    <td>Implem<br>entación<br>de una<br>pantalla de<br>registro donde<br>nuevos usuarios<br>puedan sumarse<br>a CambiaZo.</td>
    <td>6</td>
    <td>Jeremy<br>Quispe</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">US03</td>
    <td rowspan="1">Iniciar<br>sesión<br>en la<br>aplicación</td>
    <td>WI-02</td>
    <td>Pantalla<br>de<br>inicio<br>de<br>sesión</td>
    <td>Se crea una<br>pantalla en<br>la cual el<br>usuario podrá<br>ingresar a la<br>aplicación cuando<br>introduzca el<br>correo con el<br>que creó su<br>cuenta y su<br>contraseña.</td>
    <td>2</td>
    <td>Mathias<br>Mendoza</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">US06</td>
    <td rowspan="1">Filtrado<br>de<br>Objetos</td>
    <td>WI-03</td>
    <td>Implem<br>entación<br>de<br>un<br>filtro<br>de<br>búsqueda</td>
    <td>Implementar<br>un filtro<br>de búsqueda<br>para que<br>los usuarios<br>puedan encontrar<br>de forma más<br>rápida los<br>objetos de su<br>interés.</td>
    <td>10</td>
    <td>Ian<br>Santisteban</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">US16</td>
    <td rowspan="1">Visualización<br>de<br>objetos<br>disponibles<br>para<br>intercambio</td>
    <td>WI-04</td>
    <td>Listar<br>los<br>objetos<br>disponibles</td>
    <td>Creación de<br>una sección<br>en la que<br>los usuarios<br>registrados<br>puedan ver<br>los objetos<br>por los que<br>pueden<br>realizar un<br>intercambio.</td>
    <td>10</td>
    <td>Joseph<br>Huamani</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">US25</td>
    <td rowspan="1">Visualización<br>de la<br>Historia<br>de la<br>Startup</td>
    <td>WI-05</td>
    <td>Sección<br>“¿Quiénes<br>somos?”</td>
    <td>Implementación<br>de la<br>sección<br>“¿Quiénes<br>somos?”<br>y las<br>redes<br>sociales y<br>datos de<br>contacto en<br>el footer.</td>
    <td>2</td>
    <td>Sandro<br>Quispesivana</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">US26</td>
    <td rowspan="1">Visualizar<br>las<br>características<br>clave<br>de la<br>aplicación</td>
    <td>WI-06</td>
    <td>Sección<br>Caracte<br>rísticas<br>Principales</td>
    <td>Desarrollo<br>de la<br>sección donde<br>se pueden<br>visualizar todas<br>las características<br>principales de<br>CambiaZo y<br>conocer lo que<br>puede realizar<br>dentro de<br>esta.</td>
    <td>4</td>
    <td>Mathias<br>Mendoza</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">US27</td>
    <td rowspan="1">Acceder<br>a un<br>formulario<br>para llenar<br>mis datos<br>de contacto<br>y recibir<br>noticias<br>relacionadas<br>con CambiaZo</td>
    <td>WI-07</td>
    <td>Formulario<br>de<br>contacto</td>
    <td>Desarrollo<br>del formulario<br>para que<br>los usuarios<br>llenen sus<br>datos de<br>contacto y<br>puedan recibir<br>noticias<br>relacionadas<br>con CambiaZo.</td>
    <td>10</td>
    <td>Ian<br>Santisteban</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">US28</td>
    <td rowspan="1">Descargar<br>la aplicación<br>de<br>CambiaZo</td>
    <td>WI-08</td>
    <td>Redireccionar<br>a<br>Google<br>Play<br>Store</td>
    <td>Implementación<br>de botones<br>que sirvan<br>para<br>redire<br>ccionar<br>a los<br>usuarios de<br>la Landing<br>Page a<br>Google Play<br>Store para<br>que descarguen<br>la aplicación.</td>
    <td>4</td>
    <td>Joseph<br>Huamani</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">US29</td>
    <td rowspan="1">Ver<br>los<br>planes<br>y<br>precios</td>
    <td>WI-09</td>
    <td>Sección<br>de<br>planes<br>y<br>precios</td>
    <td>Desarrollo<br>de la<br>sección de<br>planes,<br>donde<br>aparezcan<br>los precios<br>de cada<br>plan y lo<br>que incluye<br>cada uno.</td>
    <td>6</td>
    <td>Jeremy<br>Quispe</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">US30</td>
    <td rowspan="1">Navegación<br>en la<br>Landing<br>Page</td>
    <td>WI-10</td>
    <td>Barra<br>de<br>Navegación</td>
    <td>Implementación<br>de una<br>barra de<br>navegación<br>para que<br>el usuario<br>pueda<br>desplazarse<br>más rápido<br>dentro de<br>la Landing<br>Page.</td>
    <td>6</td>
    <td>Mathias<br>Mendoza</td>
    <td>Done</td>
  </tr>
</tbody>
</table>

**Sprint 2 - Product**

<table>
<thead>
  <tr>
    <th colspan="2">User Story</th>
    <th colspan="6">Work-Item / Task</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Id</td>
    <td>Title</td>
    <td>Id</td>
    <td>Title</td>
    <td>Description</td>
    <td>Estim<br>ation<br>(Hours)</td>
    <td>Assigned<br>to</td>
    <td>Status<br>(To-do /<br>InProcess /<br>ToReview /<br>Done)</td>
  </tr>
  <tr>
    <td rowspan="1">US02</td>
    <td rowspan="1">Editar<br>perfil<br>del<br>usuario</td>
    <td>WI-01</td>
    <td>Sección<br>de<br>perfil</td>
    <td>Implementación de una pantalla que permita a los usuarios editar su información de perfil.</td>
    <td>4</td>
    <td>Sandro<br>Quispesivana</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">US05</td>
    <td rowspan="1">Cerrar<br>sesión</td>
    <td>WI-02</td>
    <td>Funcionalidad<br>de<br>cerrar<br>sesión</td>
    <td>Implementación de la opción de cerrar sesión en la aplicación.</td>
    <td>2</td>
    <td>Jeremy<br>Quispe</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">US10</td>
    <td rowspan="1">Visualización<br>de<br>artículos<br>publicados<br>para<br>intercambio</td>
    <td>WI-03</td>
    <td>Listar<br>artículos<br>publicados</td>
    <td>Creación de una sección donde se muestren los artículos publicados por los usuarios.</td>
    <td>4</td>
    <td>Joseph<br>Huamani</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">US11</td>
    <td rowspan="1">Realización<br>de<br>una<br>oferta<br>de<br>intercambio</td>
    <td>WI-04</td>
    <td>Funcionalidad<br>de<br>oferta<br>de<br>intercambio</td>
    <td>Implementar la opción para que los usuarios realicen ofertas de intercambio.</td>
    <td>6</td>
    <td>Ian<br>Santisteban</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">US12</td>
    <td rowspan="1">Crear<br>publicación<br>de<br>intercambio</td>
    <td>WI-05</td>
    <td>Pantalla<br>de<br>creación<br>de<br>publicación</td>
    <td>Implementar la pantalla donde los usuarios puedan crear publicaciones para intercambiar.</td>
    <td>10</td>
    <td>Jeremy<br>Quispe</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">US14</td>
    <td rowspan="1">Eliminar<br>publicación<br>de<br>intercambio</td>
    <td>WI-06</td>
    <td>Funcionalidad<br>de<br>eliminación<br>de<br>publicación</td>
    <td>Implementar la opción para que los usuarios eliminen sus publicaciones.</td>
    <td>4</td>
    <td>Mathias<br>Mendoza</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">US15</td>
    <td rowspan="1">Gestión<br>de<br>intercambios</td>
    <td>WI-07</td>
    <td>Funcionalidad<br>de<br>gestión<br>de<br>intercambios</td>
    <td>Desarrollar la funcionalidad para gestionar los intercambios realizados.</td>
    <td>6</td>
    <td>Joseph<br>Huamani</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">US17</td>
    <td rowspan="1">Visualizar el<br>perfil del<br>usuario que<br>publique un<br> producto	</td>
    <td>WI-08</td>
    <td>Funcionalidad<br>de<br>vizualizar<br>perfil</td>
    <td>Implementar la opción para que los usuarios vean los perfiles de los demas usuarios.</td>
    <td>6</td>
    <td>Ian<br>Santisteban</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">US18</td>
    <td rowspan="1">Aceptar<br>o<br>rechazar<br>un<br>intercambio</td>
    <td>WI-09</td>
    <td>Funcionalidad<br>de<br>aceptar<br>o<br>rechazar</td>
    <td>Desarrollar la opción para que los usuarios acepten o rechacen los intercambios.</td>
    <td>6</td>
    <td>Sandro<br>Quispesivana</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">US19</td>
    <td rowspan="1">Ver la<br>información<br>detallada<br>de un<br>producto<br>publicado</td>
    <td>WI-10</td>
    <td>Funcionalidad<br>de<br>detalles<br>del<br>producto</td>
    <td>Implementar la opción para que los usuarios vean información detallada de un producto.</td>
    <td>10</td>
    <td>Jeremy<br>Quispe</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">US23</td>
    <td rowspan="1">Gestionar<br>mis<br>favoritos<br>en la<br>aplicación</td>
    <td>WI-11</td>
    <td>Funcionalidad<br>de<br>favoritos</td>
    <td>Implementar la opción para que los usuarios gestionen sus artículos favoritos.</td>
    <td>6</td>
    <td>Joseph<br>Huamani</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="1">US24</td>
    <td rowspan="1">Ver<br>reseñas<br>recibidas</td>
    <td>WI-12</td>
    <td>Funcionalidad<br>de<br>reseñas</td>
    <td>Implementar la opción para que los usuarios vean las reseñas que han recibido.</td>
    <td>6</td>
    <td>Ian<br>Santisteban</td>
    <td>Done</td>
  </tr>
</tbody>
</table>

**Sprint 3 - Product**

<table>
  <thead>
    <tr>
      <th colspan="2">User Story</th>
      <th colspan="6">Work-Item / Task</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Id</td>
      <td>Title</td>
      <td>Id</td>
      <td>Title</td>
      <td>Description</td>
      <td>Estim<br>ation<br>(Hours)</td>
      <td>Assigned<br>to</td>
      <td>Status<br>(To-do /<br>InProcess /<br>ToReview /<br>Done)</td>
    </tr>
    <tr>
      <td rowspan="1">US04</td>
      <td rowspan="1">Cambiar<br>Contraseña</td>
      <td>WI-01</td>
      <td>Funcionalidad<br>de<br>cambiar<br>contraseña</td>
      <td>Implementación de la opción para que los usuarios cambien su contraseña.</td>
      <td>4</td>
      <td>Ian<br>Santisteban</td>
      <td>Done</td>
    </tr>
    <tr>
      <td rowspan="1">US08</td>
      <td rowspan="1">Brindar<br>reseña<br>sobre<br>Intercambiador</td>
      <td>WI-02</td>
      <td>Funcionalidad<br>de<br>reseñas</td>
      <td>Permitir a los usuarios dejar una reseña sobre su experiencia con el intercambiador.</td>
      <td>6</td>
      <td>Joseph<br>Huamani</td>
      <td>Done</td>
    </tr>
    <tr>
      <td rowspan="1">US09</td>
      <td rowspan="1">Eliminación<br>de cuenta</td>
      <td>WI-03</td>
      <td>Funcionalidad<br>de<br>eliminar<br>cuenta</td>
      <td>Permitir a los usuarios eliminar su cuenta y datos de forma permanente.</td>
      <td>6</td>
      <td>Mathias<br>Mendoza</td>
      <td>Done</td>
    </tr>
    <tr>
      <td rowspan="1">US13</td>
      <td rowspan="1">Editar<br>publicación<br>de intercambio</td>
      <td>WI-04</td>
      <td>Funcionalidad<br>de editar<br>publicación</td>
      <td>Permitir a los usuarios editar una publicación existente.</td>
      <td>6</td>
      <td>Jeremy<br>Quispe</td>
      <td>Done</td>
    </tr>
    <tr>
      <td rowspan="1">US20</td>
      <td rowspan="1">Adquirir<br>suscripción<br>premium</td>
      <td>WI-05</td>
      <td>Funcionalidad<br>de adquirir<br>suscripción</td>
      <td>Permitir a los usuarios adquirir una suscripción premium para obtener beneficios adicionales.</td>
      <td>16</td>
      <td>Ian<br>Santisteban</td>
      <td>Done</td>
    </tr>
    <tr>
      <td rowspan="1">US21</td>
      <td rowspan="1">Cancelar<br>suscripción</td>
      <td>WI-06</td>
      <td>Funcionalidad<br>de cancelar<br>suscripción</td>
      <td>Permitir a los usuarios cancelar su suscripción premium en cualquier momento.</td>
      <td>6</td>
      <td>Joseph<br>Huamani</td>
      <td>Done</td>
    </tr>
  </tbody>
</table>

**Sprint 4 - Product**

<table>
  <thead>
    <tr>
      <th colspan="2">User Story</th>
      <th colspan="6">Work-Item / Task</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Id</td>
      <td>Title</td>
      <td>Id</td>
      <td>Title</td>
      <td>Description</td>
      <td>Estim<br>ation<br>(Hours)</td>
      <td>Assigned<br>to</td>
      <td>Status<br>(To-do /<br>InProcess /<br>ToReview /<br>Done)</td>
    </tr>
    <tr>
      <td rowspan="1">US01</td>
      <td rowspan="1">Registro<br>de usuario</td>
      <td>WI-01</td>
      <td>Diferenciación<br>de tipo de<br>registro</td>
      <td>Implementar una validación en el proceso de registro para marcar si la cuenta es con Google o con correo tradicional, almacenando esta información para personalizar la experiencia del usuario.</td>
      <td>6</td>
      <td>Joseph<br>Huamani</td>
      <td>Done</td>
    </tr>
    <tr>
      <td rowspan="1">US02</td>
      <td rowspan="1">Editar<br>perfil del usuario</td>
      <td>WI-02</td>
      <td>Edición de<br>perfil para Google</td>
      <td>Evitar la edición del correo en caso de que la cuenta esté vinculada con Google, asegurando la consistencia de los datos.</td>
      <td>4</td>
      <td>Ian<br>Santisteban</td>
      <td>Done</td>
    </tr>
    <tr>
      <td rowspan="1">US03</td>
      <td rowspan="1">Iniciar<br>sesión</td>
      <td>WI-03</td>
      <td>Inicio de sesión<br>con Google</td>
      <td>Integrar la opción para iniciar sesión con Google y almacenar los detalles de la cuenta en caché para acceso rápido.</td>
      <td>2</td>
      <td>Ian<br>Santisteban</td>
      <td>Done</td>
    </tr>
    <tr>
      <td rowspan="1">US04</td>
      <td rowspan="1">Cambiar<br>Contraseña</td>
      <td>WI-04</td>
      <td>Validación de<br>cambio de contraseña</td>
      <td>Mostrar mensajes de error si las contraseñas ingresadas no coinciden o si algún campo está vacío durante el cambio de contraseña.</td>
      <td>4</td>
      <td>Mathias<br>Mendoza</td>
      <td>Done</td>
    </tr>
    <tr>
      <td rowspan="1">US12</td>
      <td rowspan="1">Crear<br>publicación de intercambio</td>
      <td>WI-05</td>
      <td>Popup de límite<br>de publicaciones</td>
      <td>Mostrar un popup informando al usuario cuando se ha alcanzado el máximo de publicaciones permitidas.</td>
      <td>10</td>
      <td>Mathias<br>Mendoza</td>
      <td>Done</td>
    </tr>
    <tr>
      <td rowspan="1">US16</td>
      <td rowspan="1">Visualización<br>de objetos disponibles</td>
      <td>WI-06</td>
      <td>Mensajes informativos<br>de objetos disponibles</td>
      <td>Mostrar mensajes cuando no haya objetos disponibles, como "No hay artículos publicados" para indicar al usuario el estado de la sección.</td>
      <td>10</td>
      <td>Ian<br>Santisteban</td>
      <td>Done</td>
    </tr>
    <tr>
      <td rowspan="1">US18</td>
      <td rowspan="1">Aceptar o<br>Rechazar un intercambio</td>
      <td>WI-07</td>
      <td>Actualización<br>de visualización de intercambio</td>
      <td>Actualizar la visualización de intercambio cuando un usuario acepte o rechace una oferta, asegurando la consistencia en la interfaz de usuario.</td>
      <td>6</td>
      <td>Mathias<br>Mendoza</td>
      <td>Done</td>
    </tr>
  </tbody>
</table>


<br><br>

### 5.2.2 Implemented Landing Page Evidence
Durante el desarrollo de los Sprints, se completó y desplegó exitosamente la landing page del proyecto **CambiaZo**. Esta página presenta el modelo de negocio, integra una barra de navegación funcional, secciones informativas clave y un formulario de contacto operativo que permite a los usuarios dejar su información de manera efectiva.

El sitio fue desarrollado aplicando principios de *Responsive Web Design* para asegurar una experiencia de usuario óptima en dispositivos móviles, tabletas y computadoras de escritorio. Las pruebas de visualización en múltiples resoluciones confirmaron su correcto funcionamiento.

Asimismo, se implementó la metodología **GitFlow**, lo que permitió organizar eficientemente el trabajo del equipo mediante ramas específicas para desarrollo, pruebas y producción, asegurando la estabilidad de la rama principal.

La landing page se encuentra publicada y accesible en el siguiente enlace:  
🔗 [Cambiazo Landing Page](https://cambiazo-site.netlify.app/)

A continuación, se presentan las imágenes que evidencian los avances logrados durante este Sprint:

<div align="center">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Sprint-1/Execution-Evidence/landing-page-1.png?raw=true" alt="landing page" ><br>

  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Sprint-1/Execution-Evidence/landing-page-2.png?raw=true" alt="landing page" ><br>

  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Sprint-1/Execution-Evidence/landing-page-3.png?raw=true" alt="landing page" ><br>

  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Sprint-1/Execution-Evidence/landing-page-4.png?raw=true" alt="landing page" ><br>

  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Sprint-1/Execution-Evidence/landing-page-5.png?raw=true" alt="landing page" ><br>

  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Sprint-1/Execution-Evidence/landing-page-6.png?raw=true" alt="landing page" ><br>

  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Sprint-1/Execution-Evidence/landing-page-7.png?raw=true" alt="landing page" ><br>

  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Sprint-1/Execution-Evidence/landing-page-8.png?raw=true" alt="landing page" ><br>

  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Sprint-1/Execution-Evidence/landing-page-9.png?raw=true" alt="landing page" >
</div>

<br><br>


### 5.2.3 Implemented Frontend-Web Application Evidence
Durante los sprints del proyecto, el equipo logró implementar completamente la aplicación web frontend, incorporando todas las funcionalidades clave relacionadas con el intercambio y la donación de objetos.

Se desarrollaron interfaces intuitivas y responsivas que permiten a los usuarios navegar por las publicaciones disponibles, realizar ofertas de intercambio, donar artículos a organizaciones registradas y gestionar sus perfiles personales. Además, se integraron componentes para la autenticación de usuarios, la visualización de reseñas y la gestión de favoritos, asegurando una experiencia de usuario completa y coherente con los objetivos planteados.

El desarrollo del frontend se realizó en estrecha coordinación con los servicios de la API RESTful previamente construida, garantizando una interacción fluida entre la lógica de negocio y la interfaz gráfica. La implementación fue guiada por los prototipos diseñados en Figma, asegurando que la estructura visual y la experiencia de usuario planificada se mantuvieran durante toda la ejecución.

La aplicación web se encuentra publicada y accesible en el siguiente enlace:  
🔗 [Cambiazo Web App](https://cambia-zo.netlify.app/home)

<div align="center">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front1.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front2.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front3.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front4.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front5.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front6.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front7.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front8.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front9.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front10.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front101.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front11.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front12.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front13.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front14.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front15.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front16.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front17.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front18.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front19.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front20.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front21.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front22.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front23.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front24.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front25.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front26.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front27.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front28.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front29.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front30.png?raw=true" alt="app web"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Implemented-Frontend/front31.png?raw=true" alt="app web"><br>
</div>

<br><br>

### 5.2.4 Acuerdo de Servicio - SaaS
Con el objetivo de garantizar transparencia, protección del usuario y cumplimiento normativo, se ha definido un **Acuerdo de Servicio (SaaS)** que regula el uso de la plataforma **CambiaZo**, la cual ofrece un servicio digital diseñado para facilitar el intercambio y la donación de objetos a través de una aplicación móvil. Este servicio tiene como principal objetivo promover la economía circular y reducir el impacto ambiental mediante el fomento de la reutilización de productos.

Este acuerdo detalla los derechos, responsabilidades y restricciones aplicables a los usuarios de la plataforma. Además, se establece el marco legal y normativo bajo el cual los usuarios deben interactuar con el servicio. El acuerdo será publicado de forma pública y accesible en la sección **"Términos y Condiciones"** del sitio web oficial de **CambiaZo**. La aceptación de estos términos es obligatoria para hacer uso de la plataforma. A continuación, se detallan los principales aspectos incluidos en el Acuerdo de Servicio:

- **Objeto del Servicio**  
  CambiaZo proporciona un espacio digital accesible a través de una aplicación móvil, en el cual los usuarios pueden realizar actividades de intercambio o donación de objetos. Estas actividades se llevan a cabo de forma voluntaria, sin fines de lucro, con el fin de promover la economía circular y evitar el desperdicio de bienes que aún tienen valor. A través de esta plataforma, los usuarios pueden:
  - Publicar objetos que ya no necesitan para que otros usuarios los intercambien o los reciban como donación.
  - Realizar intercambios con otros usuarios o recibir objetos donados sin el propósito de obtener ganancias comerciales.

- **Obligaciones del Usuario**  
  Los usuarios que accedan a **CambiaZo** se comprometen a cumplir con las siguientes obligaciones:
  - **Proporcionar información veraz y actualizada:** Los usuarios deben registrar datos precisos y completos en sus perfiles, incluyendo la información de contacto y la descripción de los objetos publicados para intercambio o donación.
  - **Utilizar la plataforma de forma ética y responsable:** Los usuarios deben evitar el uso de la plataforma para realizar actividades fraudulentas, engañosas o que contravengan las políticas de la aplicación. Además, deberán abstenerse de crear publicaciones con fines comerciales o para lucro personal.
  - **Cumplir con la legislación vigente:** Los usuarios deberán respetar las leyes locales e internacionales, especialmente en cuanto a la protección de la propiedad intelectual y la normativa sobre privacidad de datos personales.
  - **No publicar contenido prohibido:** Los usuarios no podrán subir contenido que sea ilegal, ofensivo, difamatorio, discriminatorio, obsceno, pornográfico o que infrinja los derechos de propiedad intelectual o los derechos de terceros.

- **Obligaciones del Proveedor (CambiaZo)**  
  **CambiaZo** se compromete a cumplir con las siguientes responsabilidades:
  - **Proporcionar acceso ininterrumpido al servicio:** CambiaZo ofrecerá acceso continuo al servicio, salvo interrupciones justificadas por mantenimiento técnico programado o situaciones de fuerza mayor que impidan la operatividad temporal de la plataforma.
  - **Proteger la privacidad de los usuarios:** **CambiaZo** cumplirá con las leyes de protección de datos personales y tomará medidas razonables para garantizar la seguridad de la información personal de los usuarios almacenada en la plataforma.
  - **Soporte y atención al usuario:** Se brindará soporte básico a los usuarios en caso de dificultades técnicas o problemas con el uso de la plataforma. Esto incluirá la resolución de problemas comunes y la atención a consultas por los medios de contacto establecidos.
  - **Notificación de cambios en el servicio:** Si se presentan modificaciones sustanciales en el servicio o en los términos del acuerdo, **CambiaZo** se compromete a notificar a los usuarios mediante los canales disponibles (como correo electrónico o notificaciones dentro de la aplicación).

- **Restricciones de Uso**  
  Para garantizar el correcto funcionamiento de la plataforma y evitar abusos, **CambiaZo** establece las siguientes restricciones:
  - **Prohibición de actividades comerciales:** Los usuarios no podrán utilizar la plataforma con fines comerciales, como la venta de productos o la promoción de negocios o marcas.
  - **No utilizar técnicas automatizadas:** Está prohibido el uso de bots, scraping, minería de datos u otras herramientas automatizadas que puedan alterar el funcionamiento normal de la plataforma o recopilar información sin el consentimiento de los usuarios.
  - **No compartir contenido ilegal o violento:** Los usuarios no podrán hacer uso de la plataforma para difundir contenido que incite a la violencia, el odio, el racismo, la discriminación o cualquier otro comportamiento perjudicial para la comunidad.

- **Propiedad Intelectual**  
  Los contenidos generados por los usuarios, tales como descripciones, fotos, videos o cualquier otro material relacionado con los objetos publicados, permanecen bajo la propiedad de los usuarios. Sin embargo, al publicar dicho contenido en **CambiaZo**, los usuarios otorgan a la plataforma una licencia limitada, no exclusiva y sin compensación para:
  - Utilizar, mostrar y distribuir dicho contenido dentro del ecosistema de **CambiaZo** con el fin de facilitar el intercambio o donación de los objetos. 
  - Permitir que otros usuarios vean el contenido publicado dentro de la plataforma y realicen las interacciones correspondientes.

- **Modificaciones del Servicio**  
  **CambiaZo** se reserva el derecho de modificar o actualizar el servicio y los términos de este acuerdo en cualquier momento. Las modificaciones pueden incluir cambios en la funcionalidad de la aplicación, en la política de privacidad, o en los términos y condiciones del servicio. Las actualizaciones de estos términos serán notificadas a los usuarios a través de medios electrónicos disponibles, y los usuarios deberán revisar dichos cambios para continuar usando el servicio.

- **Terminación de Cuentas**  
  **CambiaZo** tiene la facultad de suspender o eliminar las cuentas de los usuarios que incumplan los términos establecidos en este acuerdo o que realicen actividades que afecten negativamente la experiencia de otros usuarios o la operatividad de la plataforma. Las cuentas también podrán ser eliminadas si los usuarios presentan información falsa o engañosa, si se detecta actividad fraudulenta o si se incumplen las políticas de contenido.

Este acuerdo forma parte esencial del entorno SaaS de **CambiaZo** y será accesible públicamente para su revisión y aceptación antes de utilizar la aplicación. Los usuarios deben aceptar los términos en su totalidad para poder acceder y utilizar las funcionalidades ofrecidas por la plataforma. 


<br><br>

### 5.2.5 Implemented Native-Mobile Application Evidence
Durante los Sprints del proyecto, se logró desarrollar e implementar por completo la aplicación móvil nativa, cumpliendo con las funcionalidades clave definidas para la solución. La app integra de manera efectiva las características relacionadas con el intercambio y la donación de objetos, permitiendo a los usuarios registrarse, iniciar sesión, explorar publicaciones, visualizar detalles de los productos y realizar ofertas de intercambio o donación.

Además, se incluyeron vistas para la gestión de perfil, favoritos, reseñas, y la interacción con ONG’s, asegurando una experiencia de usuario coherente y fluida en dispositivos móviles.

Este desarrollo fue acompañado por pruebas funcionales continuas durante los sprints, garantizando el cumplimiento de los requisitos establecidos y la alineación con los flujos definidos previamente en los prototipos elaborados en Figma. La aplicación nativa se encuentra lista para ser validada en un entorno real de usuarios y continuar su evolución en próximos ciclos de mejora.

<div align="center">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-1/Execution-Evidence/mobile-app-1.png?raw=true" alt="mobile app 1"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-1/Execution-Evidence/mobile-app-2.png?raw=true" alt="mobile app 2"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-1/Execution-Evidence/mobile-app-3.png?raw=true" alt="mobile app 3"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-1/Execution-Evidence/mobile-app-4.png?raw=true" alt="mobile app 4"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-1/Execution-Evidence/mobile-app-5.png?raw=true" alt="mobile app 5"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-1/Execution-Evidence/mobile-app-6.png?raw=true" alt="mobile app 6"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-0.png?raw=true" alt="mobile app 0"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-1.png?raw=true" alt="mobile app 1"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-2.png?raw=true" alt="mobile app 2"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-3.png?raw=true" alt="mobile app 3"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-4.png?raw=true" alt="mobile app 4"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-5.png?raw=true" alt="mobile app 5"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-6.png?raw=true" alt="mobile app 6"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-7.png?raw=true" alt="mobile app 7"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-8.png?raw=true" alt="mobile app 8"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-9.png?raw=true" alt="mobile app 9"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-10.png?raw=true" alt="mobile app 10"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-11.png?raw=true" alt="mobile app 11"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-12.png?raw=true" alt="mobile app 12"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-13.png?raw=true" alt="mobile app 13"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-14.png?raw=true" alt="mobile app 14"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-15.png?raw=true" alt="mobile app 15"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-16.png?raw=true" alt="mobile app 16"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-17.png?raw=true" alt="mobile app 17"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-18.png?raw=true" alt="mobile app 18"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-19.png?raw=true" alt="mobile app 19"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-20.png?raw=true" alt="mobile app 20"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-21.png?raw=true" alt="mobile app 21"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-22.png?raw=true" alt="mobile app 22"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-23.png?raw=true" alt="mobile app 23"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-24.png?raw=true" alt="mobile app 24"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-25.png?raw=true" alt="mobile app 25"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-26.png?raw=true" alt="mobile app 26"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-27.png?raw=true" alt="mobile app 27"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-28.png?raw=true" alt="mobile app 28"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-29.png?raw=true" alt="mobile app 29"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-30.png?raw=true" alt="mobile app 30"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-31.png?raw=true" alt="mobile app 31"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-32.png?raw=true" alt="mobile app 32"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-33.png?raw=true" alt="mobile app 33"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-34.png?raw=true" alt="mobile app 34"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-35.png?raw=true" alt="mobile app 35"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-36.png?raw=true" alt="mobile app 36"><br>
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-V/Sprint-2/Execution-Evidence/mobile-app-37.png?raw=true" alt="mobile app 37"><br>
</div>

<br><br>

### 5.2.6 Implemented RESTful API and/or Serverless Backend Evidence
Durante el Sprint 1, se implementó y desplegó exitosamente el backend del proyecto **CambiaZo**, empleando una arquitectura RESTful basada en el framework Spring Boot. Esta solución constituye el núcleo tecnológico que soporta todos los procesos críticos del negocio digital, desde la autenticación de usuarios hasta la gestión completa de publicaciones, ofertas y suscripciones.

El backend fue concebido desde su diseño con principios de **escalabilidad**, **seguridad** y **mantenibilidad**, asegurando una sólida interacción con la aplicación frontend y proporcionando acceso estructurado a los datos a través de una API RESTful. Además, todos los endpoints fueron documentados y puestos a prueba utilizando **Swagger UI** y **Postman** para garantizar la correcta exposición y consumo de los servicios.

Asimismo, se aplicaron buenas prácticas en el desarrollo de servicios, como el patrón arquitectónico en tres capas (**Controller - Service - Repository**), autenticación segura mediante tokens **JWT**, cifrado de contraseñas, validación de datos y manejo global de excepciones.

El backend se encuentra desplegado en **Microsoft Azure App Service**, asegurando alta disponibilidad, rendimiento y acceso remoto desde el frontend. Se conecta a una base de datos **MySQL Flexible Server**, también alojada en Azure, lo que permite una persistencia robusta y segura de la información.

**Tecnologías y Arquitectura**
- Lenguaje y Framework: **Java 21 con Spring Boot**
- Base de Datos: **MySQL Flexible Server (Azure)**
- Seguridad: **JWT** para autenticación
- Documentación API: **Swagger (OpenAPI 3)**
- Pruebas: **Postman** (manual), **JUnit** (unitarias)
- Despliegue Cloud: **Microsoft Azure App Service**

- **Arquitectura Lógica**
  - **Controller Layer**: expone los endpoints y gestiona solicitudes HTTP
  - **Service Layer**: contiene la lógica de negocio
  - **Repository Layer**: se comunica con la base de datos mediante JPA

<br><br>

**Funcionalidades del Backend Implementadas**

| **Entidad**            | **Método HTTP** | **Endpoint**                                      | **Descripción**                              | **Roles Permitidos**          |
|------------------------|-----------------|--------------------------------------------------|----------------------------------------------|-------------------------------|
| **Reviews**             | POST            | `/api/v2/reviews`                                | Crear una nueva reseña                       | Autenticado                   |
|                        | GET             | `/api/v2/reviews/user-receptor/{userId}`         | Obtener reseñas por receptor de usuario      | Autenticado                   |
|                        | GET             | `/api/v2/reviews/user-author/{userId}/exchange/{exchangeId}` | Obtener reseñas por autor y cambio           | Autenticado                   |
|                        | GET             | `/api/v2/reviews/average-count/{userId}`         | Obtener promedio y cuenta de reseñas         | Autenticado                   |
|                        | DELETE          | `/api/v2/reviews/delete/{reviewId}`              | Eliminar una reseña                          | Autenticado                   |
| **Subscriptions**       | PUT             | `/api/v2/subscriptions/status/{subscriptionId}`  | Actualizar una suscripción                   | Autenticado                   |
|                        | GET             | `/api/v2/subscriptions`                          | Obtener todas las suscripciones              | Autenticado                   |
|                        | POST            | `/api/v2/subscriptions`                          | Crear una nueva suscripción                  | Autenticado                   |
|                        | GET             | `/api/v2/subscriptions/{id}`                     | Obtener suscripción por ID                   | Autenticado                   |
|                        | GET             | `/api/v2/subscriptions/user/{id}`                | Obtener suscripciones de un usuario          | Autenticado                   |
| **Exchanges**           | PUT             | `/api/v2/exchanges/status/{exchangeId}`          | Actualizar el estado de un intercambio       | Autenticado                   |
|                        | GET             | `/api/v2/exchanges`                              | Obtener todos los intercambios               | Autenticado                   |
|                        | POST            | `/api/v2/exchanges`                              | Crear un nuevo intercambio                   | Autenticado                   |
|                        | GET             | `/api/v2/exchanges/{exchangeId}`                 | Obtener intercambio por ID                   | Autenticado                   |
|                        | GET             | `/api/v2/exchanges/userOwn/{userId}`             | Obtener intercambios propios de un usuario    | Autenticado                   |
|                        | GET             | `/api/v2/exchanges/userChange/{userId}`          | Obtener intercambios realizados por un usuario | Autenticado                   |
|                        | GET             | `/api/v2/exchanges/finished/{userId}`            | Obtener intercambios finalizados por usuario | Autenticado                   |
|                        | DELETE          | `/api/v2/exchanges/delete/{exchangeId}`          | Eliminar un intercambio                      | Autenticado                   |
| **Ongs**                | PUT             | `/api/v2/ongs/edit/{ongId}`                      | Actualizar ONG                               | Autenticado                   |
|                        | GET             | `/api/v2/ongs`                                   | Obtener todas las ONGs                       | Autenticado                   |
|                        | POST            | `/api/v2/ongs`                                   | Crear una nueva ONG                          | Autenticado                   |
|                        | GET             | `/api/v2/ongs/{id}`                              | Obtener ONG por ID                           | Autenticado                   |
|                        | GET             | `/api/v2/ongs/search/{letters}`                  | Buscar ONGs por letras                       | Autenticado                   |
|                        | GET             | `/api/v2/ongs/category/{categoryId}`             | Obtener ONGs por categoría                   | Autenticado                   |
|                        | DELETE          | `/api/v2/ongs/delete/{id}`                       | Eliminar una ONG                             | Autenticado                   |
| **Account Number**      | POST            | `/api/v2/account-number`                         | Crear un nuevo número de cuenta              | Autenticado                   |
|                        | GET             | `/api/v2/account-number/{id}`                    | Obtener número de cuenta por ID              | Autenticado                   |
|                        | GET             | `/api/v2/account-number/ongs/{ongId}`            | Obtener todos los números de cuenta por ONG  | Autenticado                   |
|                        | DELETE          | `/api/v2/account-number/delete/{id}`             | Eliminar número de cuenta                    | Autenticado                   |
| **Favorite Products**   | POST            | `/api/v2/favorite-products`                      | Crear un nuevo producto favorito             | Autenticado                   |
|                        | GET             | `/api/v2/favorite-products/{userId}`             | Obtener productos favoritos por usuario      | Autenticado                   |
|                        | DELETE          | `/api/v2/favorite-products/delete/{userId}/{favoriteProductId}` | Eliminar un producto favorito de un usuario  | Autenticado                   |
|                        | DELETE          | `/api/v2/favorite-products/delete/{favoriteProductId}` | Eliminar un producto favorito                | Autenticado                   |
| **Projects**            | GET             | `/api/v2/projects`                               | Obtener todos los proyectos                  | Autenticado                   |
|                        | POST            | `/api/v2/projects`                               | Crear un nuevo proyecto                      | Autenticado                   |
|                        | GET             | `/api/v2/projects/{id}`                          | Obtener proyecto por ID                       | Autenticado                   |
|                        | GET             | `/api/v2/projects/ongs/{ongId}`                  | Obtener proyectos por ID de ONG               | Autenticado                   |
|                        | DELETE          | `/api/v2/projects/delete/{id}`                   | Eliminar un proyecto                         | Autenticado                   |
| **Country**             | GET             | `/api/v2/countries`                              | Obtener todos los países                     | Autenticado                   |
|                        | POST            | `/api/v2/countries`                              | Crear un nuevo país                          | Autenticado                   |
|                        | GET             | `/api/v2/countries/{id}`                         | Obtener país por ID                          | Autenticado                   |
| **Benefits**            | GET             | `/api/v2/benefits`                               | Obtener todos los beneficios                 | Autenticado                   |
|                        | POST            | `/api/v2/benefits`                               | Crear un nuevo beneficio                     | Autenticado                   |
|                        | GET             | `/api/v2/benefits/{id}`                          | Obtener beneficio por ID                     | Autenticado                   |
| **Social Networks**     | GET             | `/api/v2/social-networks`                        | Obtener todas las redes sociales             | Autenticado                   |
|                        | POST            | `/api/v2/social-networks`                        | Crear una nueva red social                   | Autenticado                   |
|                        | GET             | `/api/v2/social-networks/{id}`                   | Obtener red social por ID                    | Autenticado                   |
|                        | GET             | `/api/v2/social-networks/ongs/{id}`              | Obtener redes sociales por ONG               | Autenticado                   |
|                        | DELETE          | `/api/v2/social-networks/delete/{id}`            | Eliminar red social por ID                   | Autenticado                   |
| **Authentication**      | POST            | `/api/v2/authentication/sign-up`                 | Registrar un nuevo usuario                   | Público                       |
|                        | POST            | `/api/v2/authentication/sign-in`                 | Iniciar sesión                               | Público                       |
| **Plans**               | GET             | `/api/v2/plans`                                  | Obtener todos los planes                     | Autenticado                   |
|                        | POST            | `/api/v2/plans`                                  | Crear un nuevo plan                          | Autenticado                   |
|                        | GET             | `/api/v2/plans/{id}`                             | Obtener plan por ID                           | Autenticado                   |
| **Product Category**    | GET             | `/api/v2/product-categories`                     | Obtener todas las categorías de productos    | Autenticado                   |
|                        | POST            | `/api/v2/product-categories`                     | Crear una nueva categoría de productos       | Autenticado                   |
|                        | GET             | `/api/v2/product-categories/{id}`                | Obtener categoría de producto por ID         | Autenticado                   |
| **Products**            | PUT             | `/api/v2/products/edit/{productId}`              | Actualizar producto                          | Autenticado                   |
|                        | GET             | `/api/v2/products`                               | Obtener todos los productos                  | Autenticado                   |
|                        | POST            | `/api/v2/products`                               | Crear un nuevo producto                       | Autenticado                   |
|                        | GET             | `/api/v2/products/{id}`                          | Obtener producto por ID                      | Autenticado                   |
|                        | GET             | `/api/v2/products/user/{id}`                     | Obtener productos por usuario                | Autenticado                   |
|                        | GET             | `/api/v2/products/product-category/{id}`         | Obtener productos por categoría              | Autenticado                   |
|                        | DELETE          | `/api/v2/products/delete/{productId}`            | Eliminar un producto                          | Autenticado                   |
| **Districts**           | GET             | `/api/v2/districts`                              | Obtener todos los distritos                  | Autenticado                   |
|                        | POST            | `/api/v2/districts`                              | Crear un nuevo distrito                       | Autenticado                   |
|                        | GET             | `/api/v2/districts/{id}`                         | Obtener distrito por ID                      | Autenticado                   |
| **Roles**               | GET             | `/api/v2/roles`                                  | Obtener todos los roles                      | Autenticado                   |
| **Users**               | PUT             | `/api/v2/users/edit/{userId}`                    | Editar usuario                               | Autenticado                   |
|                        | PUT             | `/api/v2/users/edit/profile/{userId}`             | Editar perfil de usuario                     | Autenticado                   |
|                        | PUT             | `/api/v2/users/edit/password/{username}`         | Editar contraseña                            | Autenticado                   |
|                        | GET             | `/api/v2/users`                                  | Obtener todos los usuarios                   | Autenticado                   |
|                        | GET             | `/api/v2/users/{userId}`                         | Obtener usuario por ID                       | Autenticado                   |
|                        | GET             | `/api/v2/users/username/{username}`              | Obtener usuario por nombre de usuario        | Autenticado                   |
|                        | GET             | `/api/v2/users/email/{email}`                    | Obtener usuario por correo electrónico       | Autenticado                   |
|                        | DELETE          | `/api/v2/users/delete/{userId}`                  | Eliminar usuario                             | Autenticado                   |
| **Departments**         | GET             | `/api/v2/departments`                            | Obtener todos los departamentos              | Autenticado                   |
|                        | POST            | `/api/v2/departments`                            | Crear un nuevo departamento                  | Autenticado                   |
|                        | GET             | `/api/v2/departments/{id}`                       | Obtener departamento por ID                  | Autenticado                   |
| **CategoryOngs**        | PUT             | `/api/v2/category-ongs/edit/{id}`                | Actualizar categoría ONG                     | Autenticado                   |
|                        | GET             | `/api/v2/category-ongs`                          | Obtener todas las categorías de ONGs         | Autenticado                   |
|                        | POST            | `/api/v2/category-ongs`                          | Crear nueva categoría ONG                    | Autenticado                   |
|                        | GET             | `/api/v2/category-ongs/{id}`                     | Obtener categoría ONG por ID                 | Autenticado                   |
|                        | DELETE          | `/api/v2/category-ongs/delete/{id}`              | Eliminar categoría ONG por ID                | Autenticado                   |


<br><br>

**Despliegue en la Nube**<br>
El backend fue desplegado exitosamente como aplicación web sobre **Microsoft Azure App Service**, siendo accesible en todo momento. La base de datos relacional está alojada en el servicio **Azure Database for MySQL**, permitiendo una persistencia segura y eficiente de la información.

- **Enlace al backend API**: [https://cambiazo-backend-bjdkd7hhgqa8gygw.eastus2-01.azurewebsites.net](https://cambiazo-backend-bjdkd7hhgqa8gygw.eastus2-01.azurewebsites.net)
- **Swagger API Docs**: [https://cambiazo-backend-bjdkd7hhgqa8gygw.eastus2-01.azurewebsites.net/swagger-ui/index.html#](https://cambiazo-backend-bjdkd7hhgqa8gygw.eastus2-01.azurewebsites.net/swagger-ui/index.html#)

<div align="center">
<img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Implemented-Restful-Api/azure_sqlserver.png?raw=true" alt="Deploy ServerSQL"><br><br>
</div>

<div align="center">
<img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Implemented-Restful-Api/azure_backend.png?raw=true" alt="Deploy Backend"><br><br>
</div>

<br><br>

A continuación, se presentan imágenes que evidencian el desarrollo y despliegue del backend durante el Sprint 1:

<div align="center">
<img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Implemented-Restful-Api/backend_Evidence1.png?raw=true" alt="Deploy Backend"><br><br>
</div>

<div align="center">
<img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Implemented-Restful-Api/backend_evidence.png?raw=true" alt="Deploy Backend"><br><br>
</div>

<br><br>

### 5.2.7 RESTful API documentation
La documentación de la API RESTful del backend del proyecto **CambiaZo** fue generada utilizando herramientas como **Swagger** (OpenAPI 3) y **Postman**. Esto garantiza que todos los desarrolladores puedan consultar y probar fácilmente los endpoints expuestos, además de facilitar la integración con el frontend.

- **Swagger (OpenAPI 3)**: Se utilizó Swagger para generar una interfaz visual e interactiva que documenta todos los endpoints de la API. Esta herramienta proporciona detalles completos sobre cada endpoint, incluyendo el tipo de solicitud (GET, POST, PUT, DELETE), parámetros de entrada, ejemplos de respuestas y posibles errores. Swagger también permite probar los endpoints directamente desde su interfaz.

  - **Enlace al Swagger UI**: [https://cambiazo-backend-bjdkd7hhgqa8gygw.eastus2-01.azurewebsites.net/swagger-ui/index.html#](https://cambiazo-backend-bjdkd7hhgqa8gygw.eastus2-01.azurewebsites.net/swagger-ui/index.html#)
  
- **Postman**: Además de Swagger, **Postman** se utilizó para realizar pruebas manuales de los endpoints.

#### **Estructura de la documentación de la API:**

#### 1. **Autenticación**
Detalles sobre cómo los usuarios pueden autenticarse utilizando tokens JWT. Los tokens se generan a través del endpoint `/api/v2/authentication/sign-up` para registrarse y `/api/v2/authentication/sign-in` para iniciar sesión. Esta autenticación es necesaria para acceder a la mayoría de los endpoints.

#### 2. **EndPoints**
La documentación describe todos los endpoints disponibles, organizados por funcionalidad. Algunos ejemplos clave incluyen:

- **Usuarios**
  - **GET** `/api/v2/users/{userId}`: Obtiene la información de un usuario por su ID.
  - **Ejemplo de solicitud:**
    ```bash
    GET /api/v2/users/4
    ```
  - **Respuesta:**
    ```json
    {
      "id": 4,
      "username": "ana.martinez@hotmail.com",
      "name": "Ana Martínez",
      "phoneNumber": "987654324",
      "profilePicture": "https://media.istockphoto.com/id/682897825/es/foto/confident-businesswoman-over-gray-background.jpg?s=612x612&w=0&k=20&c=WSlpnPQfEqYL77qKRBZ49wbUd4Ey6rd1RB1HCNKOusQ=",
      "createdAt": "2024-09-25T22:56:32.923+00:00",
      "isActive": true,
      "roles": ["ROLE_USER"]
    }
    ```

- **Productos**
  - **GET** `/api/v2/products/{id}`: Obtiene detalles de un producto específico.
  - **Ejemplo de solicitud:**
    ```bash
    GET /api/v2/products/10
    ```
  - **Respuesta:**
    ```json
    {
      "id": 10,
      "name": "Smartwatch",
      "description": "Smartwatch con monitor de actividad física y notificaciones inteligentes.",
      "desiredObject": "Busco una cámara fotográfica semi-profesional.",
      "price": 1100,
      "image": "https://i.blogs.es/5d659a/wa/650_1200.jpeg",
      "boost": false,
      "available": true,
      "user": {
        "id": 4,
        "username": "ana.martinez@hotmail.com",
        "name": "Ana Martínez",
        "phoneNumber": "987654324",
        "profilePicture": "https://media.istockphoto.com/id/682897825/es/foto/confident-businesswoman-over-gray-background.jpg?s=612x612&w=0&k=20&c=WSlpnPQfEqYL77qKRBZ49wbUd4Ey6rd1RB1HCNKOusQ=",
        "createdAt": "2024-09-25T22:56:32.923+00:00",
        "isActive": true,
        "roles": ["ROLE_USER"]
      },
      "productCategory": {
        "id": 1,
        "name": "Tecnología"
      },
      "location": {
        "districtId": 167,
        "districtName": "San Miguel",
        "departmentId": 15,
        "departmentName": "Lima",
        "countryId": 1,
        "countryName": "Perú"
      },
      "createdAt": "2024-09-25T23:53:03.000+00:00"
    }
    ```

- **Intercambios**
  - **GET** `/api/v2/exchanges/{exchangeId}`: Consulta un intercambio específico.
  - **Ejemplo de solicitud:**
    ```bash
    GET /api/v2/exchanges/2
    ```
  - **Respuesta:**
    ```json
    {
      "id": 2,
      "productOwn": {
        "id": 9,
        "name": "Camiseta del Barcelona 2008",
        "description": "Camiseta del Barcelona de la temporada 2008, dorsal 10",
        "desiredObject": "Busco unos auriculares deportivos inalámbricos.",
        "price": 500,
        "image": "https://perufc.com/wp-content/uploads/2022/06/Barcelona-2008-2009-sextete-manga-corta.jpeg",
        "boost": true,
        "available": false
      },
      "productChange": {
        "id": 38,
        "name": "Altavoz Portátil JBL Go3",
        "description": "Altavoz portátil JBL con conectividad Bluetooth y resistencia al agua.",
        "desiredObject": "Busco unos auriculares con cancelación activa de ruido.",
        "price": 130,
        "image": "https://photos-us.bazaarvoice.com/photo/2/cGhvdG86amJs/16e51507-db6b-5a77-bb0d-6e7e0531ee20",
        "boost": false,
        "available": false
      },
      "userOwn": {
        "id": 4,
        "username": "ana.martinez@hotmail.com",
        "name": "Ana Martínez",
        "phoneNumber": "987654324",
        "profilePicture": "https://media.istockphoto.com/id/682897825/es/foto/confident-businesswoman-over-gray-background.jpg?s=612x612&w=0&k=20&c=WSlpnPQfEqYL77qKRBZ49wbUd4Ey6rd1RB1HCNKOusQ=",
        "roles": ["ROLE_USER"]
      },
      "userChange": {
        "id": 8,
        "username": "josephhm335@gmail.com",
        "name": "Joseph Huamani",
        "phoneNumber": "914514311",
        "profilePicture": "https://www.nacionfutbol.com.pe/image/nacionfutbolcompe/image-f96b75b4-a4f4-11ee-a3be-7e0aa5da29dc-1703708255-hq.webp",
        "roles": ["ROLE_ADMIN"]
      },
      "status": "Aceptado",
      "exchangeDate": "2024-10-23"
    }
    ```

#### 3. **Códigos de Error**
Se incluyen detalles sobre los posibles códigos de error y qué significan. Ejemplo:
  - `400 Bad Request`: Parámetros de solicitud incorrectos.
  - `401 Unauthorized`: No se proporcionó un token válido o ha expirado.
  - `404 Not Found`: El recurso solicitado no existe.

#### 4. **Pruebas y Validación**
Todas las pruebas de la API fueron realizadas tanto manualmente a través de **Postman** como automáticamente utilizando **Swagger**. Las pruebas incluyen casos de éxito y fallos, asegurando que los endpoints manejen correctamente diferentes escenarios.

#### 5. **Autenticación y Seguridad**
La autenticación en la API se maneja mediante **JWT**. Para interactuar con la mayoría de los endpoints, los desarrolladores deben incluir el token JWT en el encabezado de la solicitud bajo el parámetro `Authorization`. Ejemplo de solicitud con autenticación:

```bash
GET /api/v2/products/1
Authorization: Bearer <JWT_Token>
```

<br><br>

### 5.2.8 Team Collaboration Insights

Durante el desarrollo del Sprint 1, el equipo colaboró activamente en los repositorios del **Backend** y la **Landing Page**, utilizando herramientas como **GitHub**, **Trello** y **Discord** para coordinar tareas, compartir avances y resolver dudas de forma continua. Se realizaron reuniones semanales para planificación y revisión, así como sesiones diarias breves (*dailys*) para mantener sincronizado el trabajo entre los integrantes.

A continuación, gracias a la sección de *Insights* de GitHub, se presentan gráficas que muestran el nivel de participación de cada miembro del equipo en estos dos repositorios clave.

#### Tabla de identificación del equipo

<div align="center">

| Username (GitHub) | Nombre completo |
|-------------------|------------------------------|
| HelloNerk         | Huamani Mandujano, Joseph Alexis |
| 123-Mathi         | Mendoza Carrión, Mathias André |
| Jemisas           | Quispe Andia, Jeremy Joel |
| ClaudioSandro          | Quispesivana Torres, Claudio Sandro  |
| IanHD04           | Santisteban Palomino, Ian Haziel Donato |

</div>

#### Analíticos de GitHub

+ **Landing Page**
<div align="center">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Insights/landingpage_insights.png?raw=true"alt="contributor-evidence-landingpage">
</div><br><br>

+ **Backend**
<div align="center">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb1/Resources/Chapter-V/Insights/backend_insights.png?raw=true" alt="contributor-evidence-backend">
</div><br><br>

Las gráficas demuestran que todos los integrantes realizaron contribuciones significativas tanto en el repositorio del **Backend** como en el de la **Landing Page**, lo cual refleja una distribución equilibrada de tareas y un compromiso constante con el avance del proyecto.


<br>

## 5.3 Video About-the-Product

Este video es una parte fundamental de nuestra estrategia para dar a conocer nuestra aplicación. Está dirigido a los visitantes de nuestra Landing Page que desean obtener información detallada y concisa sobre lo que ofrecemos, es por esto que usamos un lenguaje formal. En él, presentamos las principales características de la aplicación y como este puede ayudarte en tu día a día.

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-V/Videos/about-the-product.png?raw=true">
 </div>

<br>

Enlace: [Video About-the-Product](https://youtu.be/2fL6Q_v7sGk)


# Capítulo VI: Product Verification & Validation

## 6.1. Testing Suites & Validation

### 6.1.1. Core Entities Unit Tests
Los Core Entities Unit Tests cumplen un papel crucial en el desarrollo de software, ya que se enfocan en validar de forma aislada el comportamiento y la lógica de las entidades centrales del sistema. Estas pruebas aseguran que dichas entidades funcionen correctamente bajo diferentes condiciones, ayudando a identificar errores desde etapas tempranas del desarrollo. Además, contribuyen a preservar la integridad del modelo de dominio, simplifican futuras modificaciones del código y promueven un mantenimiento más ágil y seguro a lo largo del ciclo de vida del proyecto.

AccountNumber Service Tests

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreEntities/service1.png?raw=true" alt="Service Tests">
 </div><br><br>


CategoryOng Service Tests

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreEntities/service2.png?raw=true" alt="Service Tests">
 </div><br><br>


 Ong Service Tests

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreEntities/service3.png?raw=true" alt="Service Tests">
 </div><br><br>


 Project Service Tests

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreEntities/service4.png?raw=true" alt="Service Tests">
 </div><br><br>

 SocialNetwork Service Tests

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreEntities/service5.png?raw=true" alt="Service Tests">
 </div><br><br>


  Benefit Service Tests

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreEntities/service6.png?raw=true" alt="Service Tests">
 </div><br><br>


  Country Service Tests

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreEntities/service7.png?raw=true" alt="Service Tests">
 </div><br><br>


 Departament Service Tests

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreEntities/service8.png?raw=true" alt="Service Tests">
 </div><br><br>

 District Service Tests

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreEntities/service9.png?raw=true" alt="Service Tests">
 </div><br><br>


Exchange Service Tests

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreEntities/service10.png?raw=true" alt="Service Tests">
 </div><br><br>


 FavoriteProduct Service Tests

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreEntities/service11.png?raw=true" alt="Service Tests">
 </div><br><br>


 Plan Service Tests

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreEntities/service12.png?raw=true" alt="Service Tests">
 </div><br><br>


 ProductCategory Service Tests

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreEntities/service13.png?raw=true" alt="Service Tests">
 </div><br><br>


Review Service Tests

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreEntities/service14.png?raw=true" alt="Service Tests">
 </div><br><br>


 Role Service Tests

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreEntities/service15.png?raw=true" alt="Service Tests">
 </div><br><br>


 User Service Tests

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreEntities/service16.png?raw=true" alt="Service Tests">
 </div><br><br>



### 6.1.2. Core Integration Tests
Las pruebas de integración del núcleo del sistema están orientadas a validar que los controladores interactúen correctamente con otros componentes clave, como servicios, repositorios y bases de datos. Estas pruebas permiten asegurar que las rutas y operaciones definidas respondan como se espera, tanto en escenarios exitosos como en condiciones de error. Al verificar la coordinación entre los distintos módulos del backend, se mejora la solidez de la aplicación, se garantiza una adecuada gestión de errores mediante códigos de estado precisos, y se contribuye al desarrollo de un sistema confiable, mantenible y alineado con buenas prácticas de arquitectura.

Exchange Controller Tests

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreIntegration/controller1.png?raw=true" alt="Controller Tests">
 </div><br><br>

### 6.1.3. Core Behavior-Driven Development
Las pruebas Behavior-Driven Development (BDD) permiten definir el comportamiento esperado del sistema desde la perspectiva del usuario, utilizando un lenguaje natural y estructurado. A través de archivos .feature, se describen escenarios que validan funcionalidades clave, facilitando la colaboración entre desarrolladores, testers y otros stakeholders. Esta técnica asegura que el software cumpla con los requisitos funcionales definidos y mantenga una comunicación clara en todo el equipo de desarrollo.

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreBehavior/general.png?raw=true" alt="Core General">
 </div><br><br>

   <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreBehavior/core12.png?raw=true" alt="US12">
 </div><br><br>

   <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreBehavior/core13.png?raw=true" alt="US13">
 </div><br><br>


   <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreBehavior/core15.png?raw=true" alt="US15">
 </div><br><br>


   <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreBehavior/core16.png?raw=true" alt="US16">
 </div><br><br>


   <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreBehavior/core17.png?raw=true" alt="US17">
 </div><br><br>


   <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreBehavior/core19.png?raw=true" alt="US19">
 </div><br><br>


   <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreBehavior/core22.png?raw=true" alt="US22">
 </div><br><br>


### 6.1.4. Core System Tests

Esta sección presenta las pruebas fundamentales realizadas sobre el sistema central de la aplicación, enfocadas en validar las funcionalidades críticas como el registro de usuarios, la gestión de productos, los intercambios, las reseñas y la autenticación. Las pruebas se ejecutaron utilizando Selenium, una herramienta de automatización que permitió simular la interacción de los usuarios con la interfaz de forma realista. Esto garantizó que los distintos flujos funcionen correctamente desde el punto de vista del usuario final y que los componentes estén correctamente integrados, asegurando así una experiencia fluida, segura y alineada con los requisitos definidos en las historias de usuario.

|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US01**|Registro de usuario|Como nuevo usuario quiero completar el proceso de registro en la aplicación para establecer mi propia cuenta.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us01.png?raw=true" alt="US01">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US02**|Editar perfil del usuario|Como usuario ya registrado quiero realizar modificaciones en mi perfil para asegurarme de que mi información esté siempre actualizada.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us02.png?raw=true" alt="US02">
 </div><br><br>
 

|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US03**|Iniciar sesión en la aplicación|Como usuario registrado quiero iniciar sesión en la aplicación para poder acceder a todas sus funcionalidades.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us03.png?raw=true" alt="US03">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US04**|Cambiar Contraseña|Como usuario registrado, quiero realizar cambios en la contraseña de mi cuenta para reforzar la seguridad de mi cuenta.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us04.png?raw=true" alt="US04">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US05**|Cerrar Sesión|Como usuario registrado quiero cerrar sesión en la aplicación para asegurarme de que mi cuenta no quede almacenada en mi dispositivo web.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us05.png?raw=true" alt="US05">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US06**|Filtrado de Objetos|Como usuario Intercambiador, quiero la capacidad de filtrar los objetos disponibles de intercambio para encontrar la opción que mejor se adapte a mis preferencias de intercambio.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us06.png?raw=true" alt="US06">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US07**|Visualización de ONGs registradas |Como usuario Donante, quiero visualizar la lista de ONGs registradas y poder filtrarlas por nombre usando el buscador, para encontrar la ONG específica en la cual me gustaría hacer mi donación.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us07.png?raw=true" alt="US07">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US08**|Brindar reseña sobre el Intercambiador|Como usuario intercambiador, deseo dejar una reseña sobre mi experiencia con el intercambiador para que otros usuarios puedan leer y considerar mi opinión antes de intercambiar|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us08.png?raw=true" alt="US08">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US09**|Eliminación de cuenta|Como usuario, quiero tener la opción de eliminar permanentemente mi cuenta para evitar que mi información persista en caso de que ya no desee utilizar la aplicación|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us09.png?raw=true" alt="US09">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US10**|Visualización de artículos publicados para intercambio|Como usuario de la aplicación de intercambio, quiero ver los artículos que he publicado, para revisar cuáles están disponibles para intercambio.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us10.png?raw=true" alt="US10">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US11**|Realización de una oferta de intercambio|Como usuario de la aplicación de intercambio, quiero seleccionar uno de mis artículos y enviarlo como oferta de intercambio, para poder ofrecerlo a cambio de otro artículo publicado por otro usuario.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us11.png?raw=true" alt="US11">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US12**|Crear publicación de intercambio|Como usuario de la aplicación, quiero poder crear una nueva publicación de intercambio para ofrecer un artículo que deseo intercambiar|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us12.png?raw=true" alt="US12">
 </div><br><br>

|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US13**|Editar publicación de intercambio|Como usuario, necesito la capacidad de editar una publicación de intercambio existente para realizar cambios en los detalles del artículo o actualizar la información relevante.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us13.png?raw=true" alt="US13">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US14**|Eliminar publicación de intercambio|Como usuario, quiero tener la opción de eliminar una publicación de intercambio que ya no deseo ofrecer para intercambiar.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us14.png?raw=true" alt="US14">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US15**|Gestión de intercambios|Como usuario de la aplicación, quiero revisar el estado de los intercambios que he enviado, recibido o aceptado, para poder ver los detalles y gestionar mis transacciones de intercambio de manera eficiente.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us15.png?raw=true" alt="US15">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US16**|Visualización de objetos disponibles para intercambio|Como usuario, necesito poder ver objetos disponibles para intercambio, de manera que pueda navegar y seleccionar aquellos que me interesen.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us16.png?raw=true" alt="US16">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US17**|Visualizar el perfil del usuario que publique un producto|Como usuario, me gustaría tener la capacidad de visualizar el perfil de la persona que haya publicado un intercambio, para poder obtener información detallada de su confiabilidad.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us17.png?raw=true" alt="US17">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US18**|Aceptar o Rechazar un Intercambio|Como usuario que ha recibido una oferta de intercambio, quiero poder revisar los detalles de la oferta y tomar una decisión para aceptar o rechazar el intercambio, para poder gestionar mis transacciones de manera eficiente y asegurada.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us18.png?raw=true" alt="US18">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US19**|Ver la información detallada de un producto publicado|Como usuario de la aplicación, quiero poder ver la información completa de un producto en el que estoy interesado, para poder decidir si quiero guardarlo en mis favoritos o proponer un intercambio.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us19.png?raw=true" alt="US19">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US20**|Adquirir la suscripción premium|Como usuario, quiero poder adquirir una suscripción premium para poder obtener beneficios adicionales que mejoren mi experiencia.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us20.png?raw=true" alt="US20">
 </div><br><br>

|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US21**|Cancelar una suscripción|Como usuario quiero poder cancelar mi suscripción en cualquier momento para no pagar mensualmente|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us21.png?raw=true" alt="US21">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US22**|Visualizar el perfil de las ONG’S registradas|Como usuario de la aplicación, quiero tener la opción de ver todas las ONG's disponibles para realizar donaciones.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us22.png?raw=true" alt="US22">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US23**|Gestionar mis favoritos en la aplicación|Como usuario de la aplicación, quiero poder acceder a los objetos que he guardado como favoritos, para poder visualizarlos y eliminar los que ya no me interesen.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us23.png?raw=true" alt="US23">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US24**|Ver reseñas recibidas|Como usuario de la aplicación, quiero poder ver las reseñas y calificaciones que he recibido, para tener una referencia de mi reputación en la plataforma.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us24.png?raw=true" alt="US24">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US25**|Visualización de la Historia de la Startup|Como usuario visitante, quiero acceder a la sección “¿Quiénes somos?” de la landing page, para conocer la historia de CambiaZo y al equipo que lo hace posible.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us25.png?raw=true" alt="US25">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US26**|Visualizar las características clave de la aplicación|Como usuario visitante, quiero poder conocer sus características clave para saber qué es lo que incluye.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us26.png?raw=true" alt="US26">
 </div><br><br>


 |**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US27**|Acceder a un formulario para llenar mis datos de contacto y recibir noticias relacionadas con CambiaZo.|Como usuario visitante, quiero tener la opción de llenar un formulario con mi información de contacto, a través de la landing page, para recibir noticias y actualizaciones relevantes de CambiaZo.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us27.png?raw=true" alt="US27">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US28**|Descargar la aplicación de CambiaZo|Como usuario visitante, quiero encontrar botones o enlaces claramente visibles en la landing page que me dirijan a la descarga de la aplicación de CambiaZo, para poder registrarme, intercambiar o donar artículos directamente desde mi dispositivo web.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us28.png?raw=true" alt="US28">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US29**|Ver los planes y precios|Como usuario visitante, quiero tener acceso a una sección que detalle los planes ofrecidos por la plataforma, para poder evaluar las opciones disponibles antes de descargar la aplicación.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us29.png?raw=true" alt="US29">
 </div><br><br>


|**ID**|**Nombre**|**Descripción**|
|------|----------|---------------|
|**US30**|Navegación en la Landing Page|Como usuario visitante, quiero contar con un menú de navegación visible y funcional para que me permita desplazarme fácilmente por las diferentes secciones del sitio web.|

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Testing/CoreSystem/us30.png?raw=true" alt="US30">
 </div><br><br>



## 6.2. Static testing & Verification

### 6.2.1. Static Code Analysis
El análisis estático de código es una técnica fundamental para detectar problemas potenciales en el software sin necesidad de ejecutarlo. A través de esta práctica, se garantiza un mayor control sobre la calidad y estructura del código, promoviendo un desarrollo más confiable y mantenible desde las primeras fases del proyecto.

Durante el desarrollo, se aplicaron principios clave de codificación y herramientas que facilitaron la verificación automatizada del código fuente. Esto permitió detectar errores comunes, inconsistencias en el estilo y posibles vulnerabilidades, así como asegurar el cumplimiento de buenas prácticas técnicas en todos los componentes del sistema.

#### 6.2.1.1. Coding standard & Code conventions
Se definieron y aplicaron convenciones específicas para asegurar que el código sea legible, coherente y mantenible.

- **Java (Spring Boot):**
  - **Nombramiento coherente:**
    - **Clases:** `PascalCase`, nombres representativos según su rol (e.g., `UserController`, `ReviewService`, `CreateUserUseCase`).
    - **Métodos y variables:** `camelCase`, verbos para métodos (`getUserById`), sustantivos para variables (`userRepository`).
    - **Constantes:** `MAYUSCULAS_CON_GUIONES` (`MAX_REVIEW_LENGTH`).
    - **Paquetes:** minúsculas, organizados por capa y contexto (`com.cambiazo.membership.domain`).

  - **Buenas prácticas en Spring Boot:**
    - Uso correcto de anotaciones (`@RestController`, `@Service`, `@Entity`).
    - Inyección de dependencias por constructor.
    - Manejo de errores centralizado con `@ControllerAdvice` y excepciones personalizadas.
    - Uso de DTOs para separar el modelo de dominio de la capa de presentación.

- **TypeScript (Angular):**
  - **Nombramiento coherente:**
    - **Componentes y servicios:** `PascalCase` (e.g., `UserComponent`, `ReviewService`).
    - **Variables y métodos:** `camelCase` (`fetchReviews`, `reviewList`).
    - **Constantes:** `MAYUSCULAS_CON_GUIONES` (`DEFAULT_TIMEOUT_MS`).
    - **Rutas y carpetas:** minúsculas, separadas por módulo o funcionalidad (`/reviews`, `/users`).

  - **Buenas prácticas en Angular:**
    - Separación de lógica y presentación (uso de servicios para lógica de negocio).
    - Tipado estricto con interfaces (`IUser`, `IReview`).
    - Modularización clara (uso de `NgModules`).
    - Uso correcto de `@Input`, `@Output` y gestión de estados.

- **Enfoques aplicados:**

    - **Domain-Driven Design (DDD):**  
    Se estructuró el dominio del sistema según los principios de DDD, definiendo entidades, agregados, repositorios y servicios de dominio claramente diferenciados. Esto permitió modelar el negocio de forma más precisa, manteniendo la lógica de dominio aislada y cohesiva.

    - **Clean Architecture:**  
    El proyecto se organizó en capas bien definidas (controladores, casos de uso, dominio e infraestructura), desacoplando las dependencias externas de la lógica de negocio. Esta separación facilitó la escalabilidad, testabilidad y mantenibilidad del sistema.

    - **Clean Code:**  
    Se priorizó la escritura de código claro, autoexplicativo y modular. Las funciones se diseñaron con una única responsabilidad, se evitó la duplicación de lógica y se limitaron los comentarios innecesarios. El código fue formateado automáticamente y mantenido consistente mediante convenciones claras.



- **Herramientas aplicadas:**

    - **SonarQube:** Herramienta principal de análisis estático, integrada al proceso de CI/CD. Se utilizó para evaluar complejidad, duplicación, mantenibilidad, cobertura de pruebas y vulnerabilidades tanto en el backend como en el frontend. Garantizó el cumplimiento de estándares de codificación específicos de cada lenguaje y promovió buenas prácticas de desarrollo en todo el sistema.

    - **Lighthouse:** Aplicado para auditar la calidad de la interfaz web, midiendo rendimiento, accesibilidad y buenas prácticas en la aplicación Angular.

    - **Selenium IDE:** Utilizado para la automatización de pruebas E2E (end-to-end), simulando la interacción del usuario con el sistema para validar funcionalidades clave.

    - **Jenkins:** Herramienta de integración continua encargada de orquestar la ejecución automática de pruebas, análisis estático con SonarQube y procesos de despliegue continuo.

#### 6.2.1.2. Code Quality & Code Security
La calidad y seguridad del código fueron aspectos priorizados durante todo el ciclo de desarrollo. Se aplicaron controles automatizados y revisiones manuales para asegurar que el software no solo funcione correctamente, sino que sea robusto, mantenible y libre de vulnerabilidades comunes.

Para ello, se abordaron dos frentes clave:

- **Calidad de Código (Code Quality):**
  - Se implementaron estándares de codificación claros y consistentes en todos los módulos del sistema.
  - El uso de SonarQube permitió monitorear métricas clave como:
    - **Complejidad ciclomática:** para evitar métodos con lógica excesivamente ramificada.
    - **Duplicación de código:** para promover la reutilización y reducir el mantenimiento.
    - **Mantenibilidad:** para identificar "code smells" que dificultan la evolución del sistema.
    - **Cobertura de pruebas:** asegurando que la lógica crítica esté validada mediante testing automatizado.
  - Se reforzó la estructura modular, desacoplada y con responsabilidades bien definidas, en línea con los principios de *Clean Architecture* y *DDD*.

- **Seguridad del Código (Code Security):**
  - Se analizaron vulnerabilidades de seguridad estáticas usando SonarQube (por ejemplo, inyecciones, manejo inseguro de datos o exposición de información sensible).
  - Se evitó el uso de funciones inseguras o APIs desactualizadas tanto en Java como en TypeScript.
  - Se implementaron controles de validación y sanitización de entradas desde las capas de presentación hasta el dominio.
  - Se aplicaron buenas prácticas de manejo de excepciones, control de errores y gestión de credenciales mediante variables de entorno.

Dado el enfoque en la calidad y la seguridad, **SonarQube** fue integrado al flujo de trabajo de CI/CD, permitiendo realizar análisis automáticos en cada cambio relevante del repositorio. Esto fomentó una cultura de mejora continua, donde los desarrolladores recibieron retroalimentación inmediata sobre la calidad técnica del código, corrigiendo problemas antes de llegar a etapas avanzadas del desarrollo y evitando la propagación de errores estructurales o de seguridad.

### 6.2.2. Reviews
Las revisiones de código son un proceso clave para asegurar la calidad técnica, la coherencia del desarrollo y el cumplimiento de los estándares definidos. Este proceso se aplicó de forma sistemática durante todo el desarrollo, tanto de manera automática como manual.

#### Tipos de Revisiones:

- **Revisión de Código por Pares:**  
  Se implementó una política de revisión entre miembros del equipo antes de aceptar cualquier cambio significativo. Cada desarrollador debía revisar el trabajo de otro, garantizando comprensión, claridad y cumplimiento de las convenciones establecidas.

- **Revisión Formal a través de Pull Requests (PR):**  
  Todo cambio debía ser subido a través de un Pull Request hacia la rama de desarrollo principal (`develop`). Los PRs incluyeron una descripción clara de los cambios y sus motivaciones, así como enlaces a las tareas relacionadas. Al menos un integrante del equipo debía aprobar cada PR antes de su integración.

- **Revisión Automática con SonarQube:**  
  Se integró SonarQube en el pipeline de CI/CD para realizar análisis estáticos del código en cada PR. Esto permitió detectar automáticamente problemas como code smells, duplicación, baja cobertura de pruebas o potenciales vulnerabilidades antes de aceptar los cambios.

#### Proceso de Revisión:

- **Creación de Pull Requests:**  
  Los cambios se organizaban por funcionalidades (`feature/sprint-*`) y eran integrados a `develop` mediante PRs con contexto técnico claro.

- **Checklist de Revisión:**  
  Las revisiones consideraron aspectos clave como:
  - Claridad y legibilidad del código.
  - Correcto uso de convenciones de nomenclatura.
  - Adecuada organización por capas según Clean Architecture.
  - Pruebas automáticas implementadas y ejecutadas.
  - Manejo de errores y validación de entradas.
  - Ausencia de código innecesario, duplicado o sin usar.

- **Comentarios y Feedback:**  
  Se promovió una cultura de feedback constructivo. Los revisores realizaban observaciones directamente sobre las líneas de código del PR, y los autores debían responder y corregir lo indicado antes de su aprobación.

- **Aprobación y Merge:**  
  Ningún PR podía fusionarse sin al menos una aprobación. Solo después de que el análisis de SonarQube estuviera limpio y se hubieran resuelto todos los comentarios, el PR era aprobado y fusionado.

#### Criterios de Aceptación:

- **Calidad y Seguridad del Código:**  
  El código debía pasar las validaciones de SonarQube sin errores críticos y cumplir con los principios de Clean Code.

- **Cobertura de Pruebas:**  
  Se exigía que el nuevo código incluyera pruebas unitarias o de integración pertinentes. Aunque no se fijó un porcentaje mínimo estricto, se priorizó que las funcionalidades clave estén debidamente cubiertas.

#### Frecuencia de Revisiones:

Las revisiones de código se realizaron de forma continua durante todo el desarrollo, especialmente al final de cada sprint. Esto evitó acumulación técnica, facilitó la identificación temprana de errores y mantuvo un flujo de trabajo ordenado y colaborativo.

## 6.3. Validation Interviews

En esta sección, se registran y explican las actividades que abarcan las entrevistas de validación durante el desarrollo de nuestro proyecto. El objetivo principal de realizar estas entrevistas de validación es obtener retroalimentación, comprender las necesidades y expectativas de los usuarios, así como validar o refutar las hipótesis sobre el producto. Para lograr esto, haremos que nuestros entrevistados de ambos segmentos interactúen con la landing page y la aplicación.


### 6.3.1 Diseño de Entrevistas

**Preguntas generales**

* ¿Cuál es su nombre completo?
* ¿Qué edad tiene?
* ¿A qué se dedica?
* ¿En qué distrito reside?
<br><br>

**Segmento objetivo 1:** Personas adultas que desean obtener nuevos artículos (Intercambiadores)

**Preguntas Específicas**

1. ¿Qué le pareció nuestra landing page y nuestra aplicación?
2. ¿Cuál considera que es la parte más importante de la landing page y nuestra aplicación? ¿Por qué?
3. Si tuviera la posibilidad de cambiar o añadir algo en la landing page o en la aplicación ¿Qué cambiaría o añadiría?
4. ¿Cree que la solución presentada facilitará la realización de trueques y que brindará una mayor confianza a los usuarios? ¿Por qué?
5. Sobre la landing page, ¿considera que cumple su función, la cual es persuadir a los visitantes a registrarse dentro de CambiaZo?
6. Sobre la aplicación, ¿considera que es intuitiva y fácil de usar? ¿Por qué?
7. ¿Usted utilizaría la aplicación para realizar trueques? ¿Por qué?
8. ¿Recomendaría a sus amigos y familiares a unirse a CambiaZo? ¿Por qué?

**Segmento objetivo 2:** Personas adultas que desean donar artículos que ya no utilizan (Donantes)
**Preguntas Específicas**

1. ¿Qué le pareció nuestra landing page y nuestra aplicación?
2. ¿Cuál considera que es la parte más importante de la landing page y nuestra aplicación? ¿Por qué?
3. Si tuviera la posibilidad de cambiar o añadir algo en la landing page o en la aplicación ¿Qué cambiaría o añadiría?
4. ¿Cree que la solución presentada contribuirá al aumento de donaciones en el país? ¿Por qué?
5. Sobre la landing page, ¿considera que cumple su función, la cual es persuadir a los visitantes a registrarse dentro de CambiaZo?
6. Sobre la aplicación, ¿considera que es intuitiva y fácil de usar? ¿Por qué?
7. ¿Usted utilizaría la aplicación para realizar donaciones? ¿Por qué?
8. ¿Recomendaría a sus amigos y familiares a unirse a CambiaZo? ¿Por qué?


### 6.3.2. Registro de Entrevistas

**Segmento Intercambiadores**<br>

<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #1<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Erick Maycol</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Huallullo Cirineo</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>20 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Ate</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom</td>
  </tr>  
  <tr>
    <td>Tecnologías</td>
    <td>Laptop y Computadora</td>
  </tr>
  <tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Jeremy Quispe</td>
  </tr>
   <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Validation-Interviews/erick-maycol-evidence.png?raw=true"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216282_upc_edu_pe/EcfVlaMcmQVFrLyXhwBVHIsBIbIcWGO9svsJezsnlS6GuQ?e=RoU7jY&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>00:00 min - 20:24 min</td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td> Erick Maycol, en la Validation Interview, nos menciona que CambiaZo tiene un diseño visualmente atractivo y funcional, pero podría mejorar destacando secciones como testimonios y botones de acción, además de incluir preguntas frecuentes. Resalta la importancia de optimizar filtros, el sistema de calificación de usuarios y tiempos de carga. Sugiere añadir validaciones de identidad, opciones de transacciones protegidas y eventos comunitarios para fortalecer la confianza. Aunque valora el enfoque comunitario, destaca la necesidad de mejoras en la seguridad y experiencia del usuario para consolidar su potencial. </td>
  </tr>
</tbody>
</table>
	    
<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #2<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Nelson Elías</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Serrano</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>20 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Miraflores</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom</td>
  </tr>  
  <tr>
    <td>Tecnologías</td>
    <td>Laptop y Computadora</td>
  </tr>
  <tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Mathías Andre Mendoza Carrión</td>
  </tr>
   <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Validation-Interviews/entrevista-nelson.png?raw=true" alt="Nelson Elías Serrano"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216282_upc_edu_pe/EcfVlaMcmQVFrLyXhwBVHIsBIbIcWGO9svsJezsnlS6GuQ?e=RoU7jY&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>20:25 min - 32:03 min</td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>Durante la entrevista, Nelson Elías Serrano, un estudiante de 20 años de la UPC que reside en Villa María del Triunfo, compartió su experiencia con la aplicación CambiaZo. En general, Nelson destacó positivamente la dinámica de intercambiar objetos, un concepto poco común en otras plataformas. Aunque encontró la landing page y la aplicación fáciles de usar, sugirió agregar mensajes tutoriales al inicio para facilitar la experiencia a usuarios menos experimentados. También mencionó que, aunque la aplicación genera confianza mediante reseñas, sería importante aplicar medidas adicionales de seguridad, como la verificación de identidad y la protección de datos. Nelson comentó que, a pesar de algunas dudas iniciales sobre la fiabilidad de los usuarios, la facilidad de uso y el concepto de intercambiar objetos le parecieron innovadores. También recomendó la implementación de opciones de envío dentro de la plataforma y eventos comunitarios para mejorar la experiencia. Por último, calificó la aplicación con un 4.5 sobre 5, destacando la utilidad de la plataforma y sugiriendo que sería valioso agregar funciones que permitan la promoción de eventos de intercambio o ferias virtuales. </td>
  </tr>
</tbody>
</table>
	    
<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #3<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Saúl David</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Díaz Suárez</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>24 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>San Juan de Lurigancho</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Google Meet</td>
  </tr>  
  <tr>
    <td>Tecnologías</td>
    <td>Laptop y Computadora</td>
  </tr>
  <tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Joseph Alexis Huamani Mandujano</td>
  </tr>
   <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Validation-Interviews/entrevista-saul.png?raw=true" alt="Saúl Díaz Evidence"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216282_upc_edu_pe/EcfVlaMcmQVFrLyXhwBVHIsBIbIcWGO9svsJezsnlS6GuQ?e=RoU7jY&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>32:04 min - 48:41 min</td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>Saúl David Díaz Suárez, un comerciante de San Juan de Lurigancho, evaluó CambiaZo destacando su claridad, facilidad de uso y enfoque en intercambios seguros. Aunque encontró la aplicación intuitiva y bien estructurada, sugirió añadir una sección de preguntas frecuentes y mejorar la verificación de usuarios para mayor confianza. Le interesan principalmente artículos de electrónica y hogar y usaría la app unas tres veces al mes.
        Comparando CambiaZo con otras plataformas, valoró su enfoque en intercambios, aunque vería beneficios en una opción gratuita limitada con funciones adicionales de pago. Prefiere coordinar intercambios dentro de la app, con la opción de puntos de encuentro sugeridos. También sugirió agregar opciones de envío y eventos comunitarios para conectar a usuarios.
        Saúl calificó la plataforma con 4.5 de 5 y la recomendaría a amigos y familiares, mencionando su seguridad y el ahorro que ofrece. Concluyó que CambiaZo tiene un gran potencial si sigue mejorando la confianza y seguridad para los usuarios.
    </td>
  </tr>
</tbody>
</table>

<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #4<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Edu Orlando</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Gutierrez Vasquez</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>19 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>La Molina</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom</td>
  </tr>  
  <tr>
    <td>Tecnologías</td>
    <td>Laptop y Computadora</td>
  </tr>
  <tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Ian Haziel Donato Santisteban Palomino</td>
  </tr>
   <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Validation-Interviews/entrevista-edu.png?raw=true" alt="entrevista-edu-gutierrez"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216282_upc_edu_pe/EcfVlaMcmQVFrLyXhwBVHIsBIbIcWGO9svsJezsnlS6GuQ?e=RoU7jY&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>38:42 min - 53:18 min</td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>Edu resalta el diseño atractivo y sencillo de CambiaZo, destacando la clara disposición de las opciones y la integración eficaz con ONGs para promover la economía circular. Sin embargo, sugiere mejorar algunos aspectos, como la visibilidad de los botones de acceso a ciertas funciones, que podrían destacarse más. También propone añadir testimonios de usuarios para reforzar la confianza en la plataforma, así como optimizar la velocidad de carga de la app. En cuanto a los perfiles, recomienda ofrecer más opciones de personalización para que los usuarios puedan adaptarlos a sus necesidades. Además, sugiere la incorporación de validaciones de identidad y la implementación de opciones para realizar transacciones protegidas, lo cual podría aumentar la confianza de los usuarios en el sistema. Otra recomendación es organizar eventos comunitarios que ayuden a fortalecer la conexión entre los usuarios y generar una mayor interacción. A pesar de estas sugerencias, Edu ve un gran potencial en la app, pero enfatiza la importancia de mejorar la seguridad, los filtros y la experiencia de usuario para asegurar su éxito a largo plazo.</td>
  </tr>
</tbody>
</table>

<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #5<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Ian Joaquín</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Sánchez</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>27 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Miraflores</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom</td>
  </tr>  
  <tr>
    <td>Tecnologías</td>
    <td>Laptop y Computadora</td>
  </tr>
  <tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Mathias Andre Mendoza Carrion</td>
  </tr>
   <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Validation-Interviews/entrevista-ian.png?raw=true" alt="Ian Díaz Sánchez"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216282_upc_edu_pe/EcfVlaMcmQVFrLyXhwBVHIsBIbIcWGO9svsJezsnlS6GuQ?e=RoU7jY&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>53:19 min - 70:07 min</td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>Durante la entrevista, Ian Sánchez, un profesional en tecnología, compartió su opinión sobre la aplicación móvil y la landing page. Ian mencionó que la interfaz de la aplicación es atractiva, pero sugirió mejorar la experiencia del usuario añadiendo una sección de preguntas frecuentes para reducir los tiempos de espera y un tutorial paso a paso para facilitar el uso a usuarios menos experimentados. Además, resaltó la importancia de proteger la privacidad de los datos de los usuarios, sugiriendo medidas de seguridad adicionales como respaldos ante posibles hackeos. También propuso incluir un sistema para detectar bots y eventos comunitarios, como descuentos en envíos, para incentivar la participación. Aunque consideró que la aplicación es buena, Ian destacó que sería valioso seguir perfeccionando la plataforma, especialmente en lo que respecta a la seguridad y el cumplimiento de estándares de desarrollo. </td>
  </tr>
</tbody>
</table>
<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #6<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Junior</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Valero Medina</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>20 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Los Olivos</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Discord y Zoom</td>
  </tr>  
  <tr>
    <td>Tecnologías</td>
    <td>Laptop</td>
  </tr>
  <tr>
    <td>Browsers</td>
    <td>Firefox</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td> Ian Haziel Donato Santisteban Palomino</td>
  </tr>
   <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Validation-Interviews/entrevista_validacion_junior.png?raw=true"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216282_upc_edu_pe/EcfVlaMcmQVFrLyXhwBVHIsBIbIcWGO9svsJezsnlS6GuQ?e=RoU7jY&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>70:07 min - 73:41 min</td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td> En la entrevista con Luis Junior Valero Medina, un joven de 19 años que estudia ingeniería de sistemas, evaluó positivamente la landing page de CambiaZo, destacando su atractivo diseño y la buena organización de la información. Resaltó la claridad con la que se explica el propósito y funcionamiento del intercambio. Además, consideró que la aplicación web tiene una apariencia moderna e intuitiva, y valoró especialmente la funcionalidad de filtrado de objetos. Sugirió la inclusión de testimonios de usuarios y una opción de chat en tiempo real para mejorar la confianza y la comunicación entre los usuarios. Luis cree que la plataforma facilita los trueques de manera segura y eficiente, y la recomendaría a amigos y familiares por su capacidad de promover el aprovechamiento de recursos.</td>
  </tr>
</tbody>
</table><br>

**Segmento Donadores**<br>

<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #1<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Hernan Emilio</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Morales Calderon</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>19 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>San Juan de Lurigancho</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom</td>
  </tr>
  <tr>
    <td>Tecnologías</td>
    <td>Computadora y Laptop</td>
  </tr>
  <tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Joseph Alexis Huamani Mandujano</td>
  </tr>
   <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Validation-Interviews/entrevista_validacion_hernan.png?raw=true" alt="Entrevista Hernan Morales"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216282_upc_edu_pe/EcfVlaMcmQVFrLyXhwBVHIsBIbIcWGO9svsJezsnlS6GuQ?e=RoU7jY&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duracion<br></td>
    <td>73:41 min - 78:45 min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td> En esta ocasión tuvimos la oportunidad de entrevistar a Hernán Morales, un usuario que representa nuestro segmento objetivo de Donadores, para recopilar opiniones sobre nuestra landing page y nuestra aplicación web. Hernán nos comentó que tanto la landing page como la aplicación web diseño, una buena estructura organizada y buena información. Además, destacó que ambas plataformas funcionan correctamente, especialmente en lo que respecta a los intercambios y las donaciones. Hernán nos comenta que la aplicación web está bastante completa en cuanto a diseño y funcionalidad y que no haría muchos cambios, solo agregar un poco de animación. Hernan, expresó que esta solución podría incrementar el número de donaciones en el país ya que es intuitiva y fácil de usar, además que tanto la landing page como la aplicación web cumplen con su propósito. Finalmente, afirmó que estaría dispuesto a utilizar la aplicación web para donar y compartirla con sus amigos y familiares.</td>
  </tr>
</tbody>
</table>
<colgroup>
</colgroup>
<table>
<thead>
  <tr>
    <th colspan="2">Entrevista #2<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Carlos Arturo</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Adrianzen Flores</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>19 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Miraflores</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom</td>
  </tr>  
  <tr>
    <td>Tecnologías</td>
    <td>Laptop y Computadora</td>
  </tr>
  <tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Mathias Andre Mendoza Carrion</td>
  </tr>
   <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Validation-Interviews/entrevista_validacion_arturo.png?raw=true" alt="Entrevista Arturo"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216282_upc_edu_pe/EcfVlaMcmQVFrLyXhwBVHIsBIbIcWGO9svsJezsnlS6GuQ?e=RoU7jY&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" title="Title">Microsoft Stream</p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>78:45 min - 83:57 min</td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td> En la entrevista, Arturo Adriansen Flores, estudiante de 19 años, comparte su perspectiva sobre la experiencia con "Cambiazo", una plataforma que facilita donaciones a ONGs. Arturo explica que su interés por la filantropía lo lleva a donar regularmente ropa y víveres a organizaciones sin fines de lucro, y destaca el placer que encuentra en poder impactar positivamente la vida de los demás a través de esta actividad. Al evaluar la landing page y la aplicación web de "Cambiazo", Arturo elogió la coherencia con la marca en el uso de colores, así como la funcionalidad y facilidad de uso que ofrecen ambas plataformas. Resalta la importancia de las reseñas de usuarios en la landing page y la interactividad de la sección de donaciones en la aplicación web, especialmente por la inclusión de información detallada sobre cada ONG y la opción de búsqueda amigable. Además, Arturo sugiere una posible mejora en la reducción de la cantidad de información en la landing page para una mejor experiencia móvil. En cuanto al impacto de "Cambiazo" en las donaciones del país, Arturo cree firmemente que la plataforma contribuirá positivamente debido a su facilidad de uso y la amigabilidad de su interfaz, especialmente el filtro de búsqueda de ONGs. Considera que tanto la landing page como la aplicación web cumplen su función persuasiva y de registro de usuarios, destacando la estética atractiva y la combinación de colores coherente. Arturo asegura que él mismo usaría la aplicación para realizar donaciones debido a su comodidad y confiabilidad, y recomendaría "Cambiazo" a amigos y familiares no solo para donar, sino también para realizar intercambios, destacando la utilidad de la plataforma para ambas actividades.</td>
  </tr>
</tbody>
</table>
<br>

### 6.3.3. Evaluaciones según heurísticas.

<br><div align="center">

**UX Heuristics & Principles Evaluation**

**Usability - Inclusive Design - Information Architecture**

</div><br>

**Site o App a evaluar:**
CambiaZo
<br>

**TAREAS A EVALUAR:**

1. **Registro e Inicio de Sesión**
   - Evaluar la facilidad de completar el registro como nuevo usuario.
   - Verificar la claridad de los mensajes de error durante el registro o inicio de sesión fallido.
   - Probar el proceso de recuperación de contraseña.

2. **Navegación General en la Aplicación**
   - Comprobar la facilidad de navegación a través del menú principal.
   - Evaluar la estructura de la información para encontrar secciones como “Mi Perfil”, “Publicaciones”, “Intercambios”, etc.
   - Verificar si el usuario puede orientarse fácilmente dentro de la app.

3. **Creación de una Publicación**
   - Probar el proceso de creación de una publicación para intercambio, desde seleccionar categoría hasta subir fotos y agregar descripción.
   - Evaluar la comprensión de los campos requeridos y la claridad de las instrucciones.

4. **Búsqueda y Filtrado de Artículos**
   - Evaluar la efectividad del motor de búsqueda para encontrar artículos específicos.
   - Probar los filtros de búsqueda (categoría, estado del artículo, ubicación, etc.) y verificar su comprensión y facilidad de uso.
   - Verificar si hay un botón claro para “Borrar filtros”.

5. **Interacción con Otras Publicaciones**
   - Evaluar la facilidad para ver los detalles de una publicación (imágenes, descripción, condiciones de intercambio).
   - Probar el envío de ofertas de intercambio y mensajes directos al propietario del artículo.

6. **Gestión de Suscripciones o Compras**
   - Probar el proceso de suscripción o compra de productos o servicios dentro de la app.
   - Verificar la facilidad para gestionar la suscripción o compra, como cambiar planes o cancelar suscripciones.
   - Evaluar la claridad de los mensajes sobre el estado de la suscripción o compra (confirmación, errores, etc.).

7. **Gestión de Intercambios**
   - Probar la facilidad para ver el estado de los intercambios activos.
   - Evaluar la claridad del proceso para aceptar o rechazar ofertas de intercambio.
   - Comprobar si el usuario entiende cómo finalizar un intercambio exitoso.

8. **Personalización del Perfil de Usuario**
   - Evaluar la facilidad para editar información del perfil (nombre, foto de perfil, ubicación).
   - Probar las opciones de personalización, como cambiar al modo oscuro.

9. **Feedback del Usuario**
   - Evaluar la presencia y accesibilidad de opciones para dejar feedback sobre la experiencia o reportar problemas.

10. **Experiencia General en Diferentes Dispositivos**
    - Probar la consistencia y usabilidad de la app en diferentes dispositivos (móviles, tablets).
    - Evaluar si la interfaz es responsiva y si se adapta adecuadamente al tamaño de la pantalla.


<br><br>


**ESCALA DE SEVERIDAD:**
Los errores serán puntuados tomando en cuenta la siguiente escala de severidad

|**Nivel**|**Descripción**|
| - | - |
|**1**|Problema superficial: puede ser fácilmente superado por el usuario ó ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo.|
|**2**|Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente reléase.|
|**3**|Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta.|
|**4**|Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento.|

<br><br>


**TABLA DE RESUMEN:**


| **N** | **Problema** | **Escala de severidad** | **Heurística/Principio violada(o)** |
|:------:|:-------------:|:----------------------:|:---------------------------------:|
| 1 | Cuando las contraseñas no coinciden al cambiar la contraseña, no se muestra un mensaje de error claro. | 3 (Problema mayor) | Visibilidad del estado del sistema |
| 2 | No hay skeleton loading mientras se cargan las publicaciones, lo que genera una experiencia menos fluida. | 2 (Problema menor) | Usabilidad: Estética y diseño minimalista |
| 3 | No se muestra un mensaje cuando no hay productos disponibles para mostrar. | 3 (Problema mayor) | Visibilidad del estado del sistema |
| 4 | En "Mis Artículos", si no hay publicaciones, no se muestra un mensaje indicando que no hay artículos disponibles. | 2 (Problema menor) | Visibilidad del estado del sistema |
| 5 | En "Favoritos", si no hay productos guardados, la sección está vacía sin mensaje informativo. | 2 (Problema menor) | Visibilidad del estado del sistema |
| 6 | En "Mis Reseñas", cuando no hay reseñas, no se muestra un mensaje informativo. | 2 (Problema menor) | Visibilidad del estado del sistema |


<br><br>

**DESCRIPCIÓN DE PROBLEMAS:**

<br>

**Problema 1: Cuando las contraseñas no coinciden al cambiar la contraseña, no se muestra un mensaje de error claro.**

Severidad: 3 (Problema mayor)

Heurística violada: Visibilidad del estado del sistema

Problema:

Cuando el usuario intenta cambiar su contraseña y las contraseñas no coinciden, la aplicación no muestra un mensaje claro indicando el error. Esto puede generar frustración, ya que el usuario no sabe qué ha salido mal, lo que podría llevar a múltiples intentos sin éxito hasta que se descubra la causa del problema.

<div align="center"><img src="https://github.com/TechZo-CC238-SW63/Report/blob/main/Resources/Chapter-V/Heuristics/problem-1.png?raw=true" alt="Problema 1"></div>

<br>

Recomendación:

Implementar un mensaje de error claro y específico que indique que las contraseñas no coinciden y que debe asegurarse de que ambas contraseñas coincidan antes de proceder.

<br><br>


**Problema 2: No hay skeleton loading mientras se cargan las publicaciones, lo que genera una experiencia menos fluida.**

Severidad: 2 (Problema menor)

Heurística violada: Usabilidad: Estética y diseño minimalista

Problema:

Al cargar las publicaciones, no se muestra un "skeleton loading", lo que puede dar la sensación de que la aplicación está congelada o no responde mientras se cargan los datos. Este vacío puede generar incertidumbre en el usuario sobre si la app está trabajando correctamente.

<div align="center"><img src="https://github.com/TechZo-CC238-SW63/Report/blob/main/Resources/Chapter-V/Heuristics/problem-2.png?raw=true" alt="Problema 2"></div>

<br>

Recomendación:

Implementar un "skeleton loading" para mostrar que la aplicación está trabajando en la carga de las publicaciones, mejorando la experiencia del usuario.

<br><br>


**Problema 3: No se muestra un mensaje cuando no hay productos disponibles para mostrar.**

Severidad: 3 (Problema mayor)

Heurística violada: Visibilidad del estado del sistema

Problema:

Cuando no hay productos disponibles en la sección correspondiente, no se muestra ningún mensaje informativo que indique que no hay productos disponibles en ese momento. Esto puede confundir al usuario, quien podría pensar que hay un error o que la función no está funcionando.

<div align="center"><img src="https://github.com/TechZo-CC238-SW63/Report/blob/main/Resources/Chapter-V/Heuristics/problem-3.png?raw=true" alt="Problema 3"></div>

<br>

Recomendación:

Incluir un mensaje claro que informe al usuario que no hay productos disponibles en ese momento, como "No hay productos disponibles en esta categoría."

<br><br>


**Problema 4: En "Mis Artículos", si no hay publicaciones, no se muestra un mensaje indicando que no hay artículos disponibles.**

Severidad: 2 (Problema menor)

Heurística violada: Visibilidad del estado del sistema

Problema:

En la sección "Mis Artículos", si no hay publicaciones realizadas por el usuario, no se muestra ningún mensaje informando que no hay artículos disponibles. El usuario se queda con una pantalla vacía y no sabe si es un error o si no ha subido artículos.

<div align="center"><img src="https://github.com/TechZo-CC238-SW63/Report/blob/main/Resources/Chapter-V/Heuristics/problem-4.png?raw=true" alt="Problema 4"></div>


<br>

Recomendación:

Agregar un mensaje que diga "No tienes artículos publicados" para indicar al usuario que la falta de contenido es intencional y no un error.

<br><br>


**Problema 5: En "Favoritos", si no hay productos guardados, la sección está vacía sin mensaje informativo.**

Severidad: 2 (Problema menor)

Heurística violada: Visibilidad del estado del sistema

Problema:

Si el usuario no tiene productos guardados en la sección "Favoritos", la pantalla aparece vacía sin ningún mensaje explicativo. Esto puede generar confusión o inquietud, ya que el usuario no sabe si algo ha fallado o si simplemente no ha guardado artículos aún.

<div align="center"><img src="https://github.com/TechZo-CC238-SW63/Report/blob/main/Resources/Chapter-V/Heuristics/problem-5.png?raw=true" alt="Problema 5"></div>


<br>

Recomendación:

Mostrar un mensaje que indique "No has guardado ningún artículo en favoritos aún" para dejar claro al usuario el estado de la sección.

<br><br>


**Problema 6: En "Mis Reseñas", cuando no hay reseñas, no se muestra un mensaje informativo.**

Severidad: 2 (Problema menor)

Heurística violada: Visibilidad del estado del sistema

Problema:

En la sección "Mis Reseñas", si no hay reseñas disponibles, no se muestra ningún mensaje informativo. Esto podría causar confusión, ya que el usuario no sabe si hay un problema con la sección o si simplemente no ha recibido reseñas.

<div align="center"><img src="https://github.com/TechZo-CC238-SW63/Report/blob/main/Resources/Chapter-V/Heuristics/problem-6.png?raw=true" alt="Problema 6"></div>

<br>

Recomendación:

Añadir un mensaje informativo como "Aún no has recibido reseñas" para aclarar la situación al usuario.


<br><br>


A través de todo el proceso de realización del proyecto hemos conseguido validar las siguientes heurísticas relacionadas a nuestra landing page y aplicación móvil:

| **Heurística** | **Descripción** |
| :-: | :-: |
| **Usabilidad** | La navegación en la aplicación es intuitiva, permitiendo que los usuarios se deslicen fácilmente por las pantallas sin esfuerzo. Todas las opciones clave se encuentran a la vista y son accesibles con solo unos pocos toques. Esto asegura que los usuarios puedan encontrar rápidamente lo que buscan, como la posibilidad de ver publicaciones o gestionar su perfil, sin perderse en un mar de opciones. Además, las transiciones entre pantallas son suaves, lo que contribuye a una experiencia continua y agradable. |
| **Accesibilidad** | La interfaz se adapta de manera óptima a distintos tamaños de pantalla, garantizando que los elementos clave sean visibles y utilizables en dispositivos tanto pequeños como grandes. Los colores, fuentes y botones son lo suficientemente grandes para que puedan ser fácilmente seleccionados con el toque de un dedo, asegurando que usuarios con diferentes capacidades físicas puedan interactuar sin dificultades. También, los textos se presentan de forma legible, con suficiente contraste para ser fácilmente leídos bajo diferentes condiciones de luz. |
| **Libertad y control por parte del usuario** | Los usuarios tienen un control total sobre su experiencia, ya que pueden moverse libremente entre las distintas secciones de la aplicación en cualquier momento. Si desean retroceder o cancelar una acción, siempre existe una opción para hacerlo sin consecuencias irreversibles. Además, los usuarios pueden elegir el contenido que desean ver primero y ajustar la visualización de acuerdo con sus preferencias, brindándoles la flexibilidad de personalizar su interacción sin estar sujetos a un flujo rígido de navegación. |
| **Consistencia entre el sistema y el mundo real** | La aplicación emplea íconos y elementos visuales que siguen convenciones ampliamente reconocidas, como símbolos de "inicio", "búsqueda" y "perfil", lo cual facilita la familiarización de los usuarios con la interfaz. Estos elementos visuales son intuitivos y evocan acciones que los usuarios están acostumbrados a realizar en otros entornos digitales, como realizar búsquedas o gestionar configuraciones personales, lo que reduce la curva de aprendizaje. |
| **Diseño estético y minimalista** | La aplicación presenta un diseño limpio y organizado, donde los elementos no se sobrecargan visualmente. Cada pantalla se centra en una acción o función específica, eliminando distracciones innecesarias. Esto no solo facilita la navegación, sino que también permite que el usuario se concentre en lo que realmente necesita hacer. Los iconos, tipografía y paleta de colores están cuidadosamente seleccionados para garantizar que la interfaz no solo sea funcional, sino también visualmente agradable. |
| **Consistencia y estándares** | La aplicación sigue patrones de diseño establecidos que son familiares para los usuarios de aplicaciones móviles. Esto asegura que las interacciones sean consistentes en todas las pantallas, desde la presentación de opciones hasta la respuesta a las acciones del usuario. Los botones, campos de entrada y otras interacciones siguen convenciones estándar, lo que permite que los usuarios naveguen con confianza sin necesidad de aprender nuevas reglas o comportamientos específicos para cada pantalla. |
| **Prevención de errores** | La aplicación está diseñada para reducir las posibilidades de error mediante retroalimentación clara y mensajes preventivos. Si un usuario intenta realizar una acción sin completar los campos requeridos o realiza una selección incorrecta, la aplicación informa de manera clara lo que debe corregirse. Además, los botones de acción ofrecen una retroalimentación visual para confirmar que se ha realizado una selección, y las opciones para deshacer acciones son fácilmente accesibles para que los usuarios puedan rectificar cualquier error. |
| **Flexibilidad y eficiencia de uso** | La aplicación ofrece opciones para personalizar la experiencia del usuario de acuerdo con sus preferencias. Los usuarios experimentados pueden acceder rápidamente a las funciones avanzadas sin tener que navegar a través de pantallas adicionales, mientras que los nuevos usuarios se benefician de un recorrido sencillo que les permite familiarizarse con las funciones esenciales. La estructura flexible permite a los usuarios explorar la aplicación de la manera que mejor se ajuste a sus necesidades y rutinas, optimizando su flujo de trabajo dentro de la app. |


<br>

## 6.4 Auditoría de Experiencias de Usuario

### 6.4.1. Auditoría realizada

#### 6.4.1.1. Información del grupo auditado

- Nombre del responsable de auditoría: TechZo
-	Especialización: Expertos en diseño de experiencia de usuario (UX), pruebas de usabilidad y desarrollo de software.
-	Fecha de auditoría: 12/06/2025
- Herramientas utilizadas:
  - Navegador web (Google Chrome)
  - Análisis de prototipos y capturas de pantalla
  - Documentación del proyecto (README.md)


#### 6.4.1.2. Cronograma de auditoría realizada

La auditoría de la experiencia de usuario se llevó a cabo en el siguiente cronograma:


| Fecha | Actividad | Responsable |
| ----- | --------- | ----------- |
|   10/06/2025    |   Revisión de las vistas principales de la plataforma (suscripción, scooters, historial, pagos, creación/edición)        |    Claudio Sandro Quispesivana Torres         |
| 11/06/2025 |  Evaluación heurística y análisis de problemas de usabilidad en los flujos principales | Jeremy Joel Quispe Andia |
| 12/06/2025 | Elaboración del informe de auditoría y recomendaciones de mejora | Joseph Alexis Huamani Mandujano| 


#### 6.4.1.3. Contenido de auditoría realizada


| #   | Problema                                                                                                                                        | Escala de servidad | Heurística/Principio violado(a)                           |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ | --------------------------------------------------------- |
| 1   | El botón "Cancelar" y "Borrar" en los popups de confirmación tienen colores similares a los de acción principal, lo que puede causar confusión. | 3                  | Prevención de errores, Reconocer antes que recordar       |
| 2   | En la vista de suscripción, no se explica claramente qué incluye cada plan ni hay un enlace a más detalles.                                     | 2                  | Ayuda y documentación, Visibilidad del estado del sistema |
| 3   | En la vista de creación/edición de scooter, no hay validación visible para los campos obligatorios.                                             | 3                  | Prevención de errores, Control y libertad del usuario     |
| 4   | El mensaje "Tus datos no podrán se recuperados" tiene un error gramatical ("se" en vez de "ser").                                               | 1                  | Ayuda y documentación, Estándares y consistencia          |
| 5   | No hay retroalimentación visual clara tras realizar acciones como editar o eliminar scooter/cuenta.                                             | 3                  | Visibilidad del estado del sistema                        |
| 6   | El botón "Ver detalle" no indica claramente qué información adicional se mostrará.                                                              | 2                  | Visibilidad del estado del sistema                        |
| 7   | No hay confirmación visual tras eliminar historial o scooter, lo que puede generar incertidumbre.                                               | 3                  | Visibilidad del estado del sistema                        |
| 8   | El botón "Cancelar" en los popups de pago puede ser ambiguo, ya que no se especifica si cancela el pago o la operación completa.                | 2                  | Prevención de errores, Control y libertad del usuario     |
| 9   | No hay accesibilidad evidente (por ejemplo, no se observa contraste suficiente en algunos textos sobre fondo lila).                             | 3                  | Accesibilidad, Estándares y consistencia                  |
| 10  | El botón "Buscar Scooter" no indica si hay un filtro aplicado o si la búsqueda es global.                                                       | 2                  | Visibilidad del estado del sistema                        |



### 6.4.2. Auditoría recibida

#### 6.4.2.1. Información del grupo auditor

- Nombre del responsable de auditoría: CiberMach
-	Especialización: Expertos en diseño de experiencia de usuario (UX), pruebas de usabilidad y desarrollo de software.
-	Fecha de auditoría: 13/06/2025
- Herramientas utilizadas:
  - Navegador web (Google Chrome)
  - Análisis de prototipos y capturas de pantalla
  - Documentación del proyecto (README.md)

#### 6.4.2.2. Cronograma de auditoría recibida

La auditoría de la experiencia de usuario se llevó a cabo en el siguiente cronograma:


| Fecha | Actividad | Responsable |
| ----- | --------- | ----------- |
|   11/06/2025    |   Revisión de las vistas principales (Autenticación, publicación de objetos, selección de oferta y confirmación).	        |    Sebastian Valente lobato Pozo        |
| 12/06/2025 |  Evaluación heurística y análisis de problemas de usabilidad en los flujos principales | Mathias Alejandro Jave Diaz |
| 13/06/2025 | Elaboración del informe de auditoría y recomendaciones de mejora | Alexandra Belen Ramos Argüelles | 


#### 6.4.2.3. Contenido de auditoría recibida


| #   | Problema                                                                                                                                        | Escala de servidad | Heurística/Principio violado(a)                           |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ | --------------------------------------------------------- |
| 1   | Intuitividad del formulario de publicación de objetos (instrucciones claras, divisiones, subtítulos, campos destacados).	 | 2                  | Ayuda y documentación |
| 2   | Consistencia en la paleta de colores (amarillo y blanco) y tipografía en todas las pantallas para una experiencia uniforme y moderna.	                                     | 3                  | Consistencia y estándares|
| 3   | Efectividad de la búsqueda y filtrado de organizaciones benéficas por nombre, localidad y categoría. | 3                  | Flexibilidad y eficiencia de uso|
| 4   | Claridad en la pantalla de selección de oferta y confirmación (indicación de lo que se ofrece, imagen, flechas de conexión).	                    | 3      | Visibilidad del estado del sistema |
| 5   | Organización visual y legibilidad de la información en las publicaciones de la pantalla de inicio (espaciado, sombreado, tamaño de letra).	                                             | 2                  | Estética y diseño minimalista                        |
| 6   | Claridad en los mensajes de éxito/error después de acciones clave como inicio de sesión, registro o publicación. ¿Son lo suficientemente informativos o solo genéricos?	                                                              | 2                  | Visibilidad del estado del sistema                        |
| 7   | Feedback visual al interactuar con botones o elementos clicables. ¿Hay un estado visual claro (por ejemplo, cambio de color, efecto de pulsación) cuando el usuario presiona un botón?	                                               | 3                  | Visibilidad del estado del sistema                        |
| 8   | Gestión de errores y validación de campos en formularios (ej. registro, publicación). ¿Se muestra al usuario qué campos faltan o son incorrectos antes de enviar el formulario?	                | 3                  | Prevención de errores     |
| 9   | Información de privacidad o seguridad en las pantallas de inicio de sesión/registro. ¿Hay alguna indicación visible sobre cómo se protegerán los datos del usuario?	                             | 1                  | Coincidencia entre el sistema y el mundo real                 |
| 10  | Navegación entre las diferentes secciones (Mi Perfil, favoritos, reseñas, suscripciones). ¿Es intuitiva y se entiende fácilmente cómo volver atrás o ir a otras secciones principales?	                                                       | 2                  | Control y libertad del usuario                        |

#### 6.4.2.4. Resumen de modificaciones para subsanar hallazgos

| #  | Problema | Subsanación |
|----|----------|-------------|
| 1  | Intuitividad del formulario de publicación de objetos (instrucciones claras, divisiones, subtítulos, campos destacados). | Añadir instrucciones claras, dividir el formulario en secciones con subtítulos y destacar los campos obligatorios para mejorar la comprensión del usuario. |
| 2  | Consistencia en la paleta de colores (amarillo y blanco) y tipografía en todas las pantallas. | Unificar la paleta de colores y tipografía en todas las vistas para mantener coherencia visual y mejorar la experiencia de usuario. |
| 3  | Efectividad de la búsqueda y filtrado de organizaciones benéficas. | Optimizar el sistema de búsqueda con autocompletado y mejorar los filtros por nombre, localidad y categoría para facilitar el acceso a resultados relevantes. |
| 4  | Claridad en la pantalla de selección de oferta y confirmación. | Incorporar imágenes representativas, etiquetas claras y flechas de conexión visual entre las opciones para guiar mejor al usuario. |
| 5  | Organización visual y legibilidad de las publicaciones en la pantalla de inicio. | Mejorar el espaciado, usar tipografía adecuada y añadir sombreado o tarjetas para una presentación más legible y atractiva. |
| 6  | Claridad en los mensajes de éxito/error tras acciones clave. | Implementar mensajes de retroalimentación más detallados y específicos en acciones como login, registro y publicación para informar claramente al usuario. |
| 7  | Falta de feedback visual al interactuar con elementos clicables. | Aplicar efectos visuales (cambio de color, animación de presión) en botones y enlaces para confirmar la interacción del usuario. |
| 8  | Gestión de errores y validación de campos en formularios. | Añadir validación en tiempo real y mensajes específicos por campo para informar al usuario de errores antes de enviar el formulario. |
| 9  | Ausencia de información de privacidad o seguridad en login/registro. | Incluir mensajes o enlaces sobre la política de privacidad y protección de datos para generar confianza en el usuario. |
| 10 | Navegación entre secciones principales poco intuitiva. | Incorporar una barra de navegación clara con íconos y texto, así como una opción de "volver atrás" visible en todas las vistas. |


# Capítulo VII: DevOps Practices

## 7.1. Continuous Integration

### 7.1.1. Tools and Practices

En el campo del desarrollo y testing de software, resulta fundamental disponer de herramientas y metodologías que garanticen tanto la calidad del código como la eficiencia del equipo. En nuestros flujos de trabajo, utilizamos diversas herramientas que mejoran tanto el desarrollo como la verificación de la funcionalidad y el comportamiento esperado de las aplicaciones. Estas herramientas cubren diferentes etapas del ciclo de desarrollo de software, desde la codificación hasta la ejecución de tests y la automatización de procesos. 

Implementamos las metodologías de Desarrollo Guiado por Comportamiento (BDD) y Desarrollo Guiado por Pruebas (TDD) para garantizar que nuestras soluciones satisfagan los requisitos del cliente mientras mantienen elevados estándares técnicos. Entre las principales herramientas que empleamos se encuentran:

|**Herramienta**|**Tipo**|**Descripción**|**Propósito**|
|------|----------|---------------|-------|
|**J Unit**|Herramienta para pruebas (TDD)|Es un programa que ayuda a probar pequeñas partes de aplicaciones en Java.|Hace más fácil crear y ejecutar pruebas para asegurarse de que las funciones de los componentes funcionen como deberían.|
|**Mockito**|Herramienta de simulaciones (TDD)|Permite crear versiones simuladas de otros componentes para hacer pruebas sin usar las versiones reales.|Imitar cómo se comportan objetos externos, lo cual es útil para hacer pruebas de forma efectiva.|
|**Cucumber**|Herramienta de BDD|Ayuda a desarrollar programas centrándose en el comportamiento, usando un lenguaje simple llamado Gherkin para escribir ejemplos que todos entienden.|Crea y prueba ejemplos basados en cómo debería comportarse el sistema, asegurando que el desarrollo esté alineado con lo que necesita el negocio.|


### 7.1.2. Build & Test Suite Pipeline Components
Esta sección describe los componentes encargados de compilar el proyecto y ejecutar las pruebas automatizadas, asegurando que el código sea funcional y estable antes de ser desplegado.


  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VII/Build&TestSuitePipelineComponents/ControllerIntegrationTest.png?raw=true" alt="ControllerIntegrationTest">
 </div><br><br>

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VII/Build&TestSuitePipelineComponents/ServiceUnitTest.png?raw=true" alt="ServiceUnitTest">
  </div><br><br>

## 7.2. Continuous Delivery
### 7.2.1. Tools and Practices

En el contexto de **Continuous Delivery**, se emplean herramientas y metodologías que permiten automatizar todas las etapas del ciclo de desarrollo y entrega, exceptuando el despliegue final en producción, que queda bajo control manual. Esto permite garantizar que el software esté siempre en un estado desplegable, manteniendo a la vez una capa de revisión y validación humana antes de su liberación definitiva.

**Herramientas utilizadas:**

| **Herramienta**     | **Tipo**             | **Descripción**                                                                 | **Propósito**                                                                 |
|---------------------|----------------------|----------------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| **GitHub Actions**  | Orquestador CI/CD    | Automatiza la construcción, prueba y entrega del software desde cada commit o pull request. | Permite definir flujos de trabajo donde el despliegue a producción requiere una aprobación manual. |
| **Trello**          | Gestión de aprobaciones | Herramienta colaborativa usada para organizar y visualizar el estado de cada versión o release. | Facilita la gestión del proceso de aprobación antes del despliegue en producción, asignando tareas y revisiones a los responsables correspondientes. |

**Prácticas implementadas:**

- **Feature Branching y Merge Requests**: Cada nueva funcionalidad se desarrolla en una rama separada. Al aprobar el merge, el código pasa por validaciones automáticas antes de integrarse a la rama principal, pero el despliegue a producción no ocurre de forma inmediata ni automática.

- **Validación en Staging**: Los cambios se prueban en un entorno *staging* controlado (proporcionado por servicios como Netlify o Azure Web App), que simula el entorno de producción. Esto permite realizar pruebas adicionales o recibir retroalimentación antes de proceder con el despliegue final.

- **Despliegue Semiautomático**: Aunque el pipeline automatiza todo el flujo técnico (compilación, pruebas, integración), el paso final de despliegue requiere una acción manual, como la aprobación de un pull request, confirmación en GitHub Actions o aprobación documentada en Trello.

- **Aprobación Manual**: Esta etapa garantiza que al menos una persona del equipo revise y apruebe explícitamente la liberación, brindando un control adicional sobre la calidad y el momento del despliegue.

### 7.2.2. Stages Deployment Pipeline Components

A continuación, se presentan las fases del pipeline de despliegue implementado en el proyecto Cambiazo, utilizando un flujo de integración y entrega continua automatizado con GitHub Actions, desplegando el frontend en Netlify y el backend en Azure Web App, y utilizando Azure MySQL como base de datos. Este pipeline está diseñado para asegurar entregas continuas, confiables y eficientes.


1. Code commit: El proceso comienza cuando un desarrollador realiza un commit en el repositorio Git. Esto desencadena automáticamente los flujos de trabajo definidos en GitHub Actions. Se garantiza así un control de versiones preciso y trazable.

2. Build: En esta etapa, el código fuente se prepara para su despliegue. Se instalan dependencias y se compilan los artefactos necesarios para frontend y backend. Esta fase es gestionada por GitHub Actions, que ejecuta scripts personalizados definidos en el archivo .github/workflows.

3. Test: Se ejecutan pruebas automatizadas para validar el correcto funcionamiento del sistema. En esta etapa se utilizan herramientas como:
    - JUnit: framework principal para ejecutar pruebas unitarias en el backend Java.
    - Mockito: biblioteca utilizada junto con JUnit para simular dependencias y realizar pruebas unitarias más precisas.
    - Selenium: framework de pruebas automatizadas para validar la funcionalidad del sistema desde la perspectiva del usuario final mediante interacción con el navegador.
    - Gherkin: lenguaje usado para definir los escenarios de prueba en lenguaje natural, que se integran con herramientas como Cucumber para automatizar pruebas de aceptación basadas en comportamiento (BDD).
    
    Estas pruebas se ejecutan automáticamente mediante GitHub Actions en cada push o pull request, asegurando que ningún cambio rompa funcionalidades existentes.

4. Acceptance test: Los escenarios de aceptación definidos en Gherkin son ejecutados mediante Cucumber. Estos simulan casos reales de uso definidos junto al cliente o stakeholders, permitiendo validar que la aplicación cumple con los requisitos funcionales esperados. Estas pruebas también forman parte del pipeline automatizado de GitHub Actions.

5. Staging: Aunque se prescinde de un entorno de staging tradicional basado en Docker o Kubernetes, Netlify y Azure Web App permiten previsualizar cambios en ramas específicas antes de realizar el merge a producción. Esto permite validar la aplicación en un entorno casi idéntico al de producción.

6. Production: Al aprobarse los cambios y hacer merge en la rama principal (por ejemplo, main o production), GitHub Actions automatiza el despliegue:

- El frontend es desplegado automáticamente en Netlify, conectado al repositorio y configurado para activar el build y deploy en cada push.

- El backend se despliega en Azure Web App, mediante una acción de GitHub que empuja los cambios directamente a Azure.

- La aplicación se conecta a una base de datos Azure MySQL, previamente provisionada y configurada mediante variables de entorno seguras en los entornos respectivos.

## 7.3. Continuous Deployment

La entrega continua es una pieza clave del proceso de desarrollo del proyecto Cambiazo. Mediante la automatización del flujo de trabajo con GitHub Actions, se asegura una publicación rápida, consistente y confiable del software.

### 7.3.1. Tools and Practices

GitHub Actions: Es la herramienta central para orquestar el pipeline CI/CD. Se encarga de automatizar la instalación de dependencias, compilación del código, ejecución de pruebas y despliegue tanto en Netlify como en Azure Web App. Su integración con GitHub simplifica el control del ciclo de vida del software.

Netlify: Encargado del despliegue del frontend. Su integración con GitHub permite la automatización completa del build y deploy en cada push a la rama configurada. También ofrece capacidades adicionales como redirecciones, manejo de formularios, autenticación y funciones serverless.

Azure Web App: Plataforma en la que se ejecuta el backend. Está configurada para recibir automáticamente los artefactos construidos desde GitHub Actions, asegurando un flujo de despliegue continuo sin intervención manual.

Azure MySQL: Servicio gestionado de base de datos utilizado para almacenar la información de la aplicación. Se conecta de manera segura con el backend a través de cadenas de conexión gestionadas mediante variables de entorno.

Pruebas Unitarias e Integración
- JUnit y Mockito aseguran una cobertura adecuada de pruebas unitarias y validación de componentes individuales en el backend.
- Selenium permite la automatización de pruebas funcionales para simular interacciones de usuario en frontend y backend, ejecutándose dentro del pipeline CI/CD.
- Gherkin + Cucumber se usan para pruebas de aceptación automatizadas, facilitando la validación de requisitos desde la perspectiva del usuario final.


### 7.3.2. Production Deployment Pipeline Components

Despliegue en Azure Web App y Netlify
- Azure Web App: El backend de Cambiazo se despliega automáticamente en Azure Web App, un servicio PaaS que permite ejecutar aplicaciones web sin gestionar infraestructura. La integración con GitHub Actions permite realizar implementaciones automáticas en cada push a la rama principal, asegurando un flujo continuo de entrega. La aplicación se conecta a una base de datos Azure MySQL, configurada mediante variables de entorno seguras.

- Netlify: El frontend se aloja en Netlify, plataforma que permite despliegues automáticos conectados directamente al repositorio de GitHub. Netlify realiza el build y deploy automáticamente en cada commit a la rama principal. Ofrece además capacidades adicionales como rutas personalizadas, funciones serverless y vista previa de ramas.


Automatización con GitHub Actions
- Pipeline Automatizado: Todo el proceso CI/CD está coordinado mediante GitHub Actions, que automatiza los siguientes pasos:
  - Instalación de dependencias
  - Ejecución de pruebas (unitarias, integración, aceptación)
  - Despliegue del frontend en Netlify
  - Despliegue del backend en Azure Web App

- Entorno Reproducible y Versionado: Aunque no se utiliza Docker en producción, GitHub Actions garantiza entornos limpios y consistentes en cada ejecución, mediante acciones configuradas que controlan cada paso del pipeline.

Pruebas Unitarias, de Integración y de Aceptación
- Validación Continua: Se prioriza la ejecución constante de pruebas automatizadas en cada commit o pull request. Esto incluye:
  - JUnit + Mockito: Para pruebas unitarias del backend Java, validando lógica de negocio y comportamientos aislados.
  - Selenium: Para pruebas funcionales que simulan interacción de usuario, ejecutadas automáticamente en entornos de staging o con headless browsers.
  - Gherkin + Cucumber: Para pruebas de aceptación automatizadas basadas en BDD (Behavior Driven Development), validando requisitos del negocio escritos en lenguaje natural.
- Cobertura de Código: Se integran herramientas de análisis de cobertura en el pipeline (por ejemplo, JaCoCo para Java), permitiendo verificar que las áreas críticas estén suficientemente testeadas antes de autorizar el despliegue.

Monitoreo con Sentry y Azure Monitor
- Sentry: Permite rastrear errores tanto en el frontend como en el backend en tiempo real. Se integra con los entornos de producción para alertar rápidamente ante fallos o comportamientos inesperados, facilitando la resolución proactiva.

- Azure Monitor / Application Insights: Se utilizan para el backend desplegado en Azure. Proveen métricas detalladas sobre uso de recursos, disponibilidad, tiempos de respuesta y fallos, ofreciendo una visión completa del rendimiento del sistema.

Mejora Continua a través del Feedback
- Los reportes de herramientas como Sentry y Azure Monitor alimentan un ciclo de retroalimentación constante.

- Esta información se analiza periódicamente para:
  - Optimizar rendimiento
  - Corregir errores recurrentes
  - Mejorar la cobertura de pruebas
  - Refinar procesos de despliegue

Resumen del Pipeline de Producción para Cambiazo
El pipeline de despliegue en producción para Cambiazo está diseñado para ser ágil, confiable y automatizado. Utiliza GitHub Actions como núcleo del CI/CD, desplegando el frontend en Netlify y el backend en Azure Web App, conectado a una base de datos Azure MySQL. Las pruebas con JUnit, Mockito, Selenium y Gherkin/Cucumber, junto con herramientas de monitoreo y análisis como Sentry y Azure Monitor, garantizan una entrega de software segura y de alta calidad. Este enfoque permite evolucionar el sistema de forma continua, minimizando riesgos e incrementando la eficiencia del desarrollo.


## 7.4. Continuous Monitoring

### 7.4.1. Tools and Practices

**Pruebas de carga y estrés (JMeter / Gatling)**
  - Definir escenarios que simulen cientos o miles de usuarios concurrentes contra los endpoints REST de Spring Boot (login, búsquedas, ofertas, donaciones).
  - Medir tiempos de respuesta, throughput y uso de CPU/memoria en el servidor.
  - Repetir las mismas simulaciones contra el build estático de Angular servido por Nginx para detectar cuellos de botella en el frontend.

<div align="center">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VII/Continous-Monitoring/apache-jmeter.png?raw=true" alt="jmeter" width="600">
</div><br><br>

**Monitoreo de aplicación y experiencia de usuario**
  - **Spring Boot Actuator + Micrometer → Prometheus & Grafana**  
    Exponer métricas de JVM (heap, GC), latencia por endpoint, tasas de error y contadores de transacciones; visualizar dashboards y configurar alertas (por ejemplo, latencia > 500 ms).  
  - **Real User Monitoring (Datadog RUM o Sentry Performance)**  
    Integrar el SDK en Angular para capturar tiempos de carga de páginas, errores JavaScript y rutas de navegación del usuario.  
  - **Google Analytics (o Matomo)**  
    Recopilar flujos de usuario, eventos de interacción y métricas de usabilidad (tiempo en pantalla, tasa de rebote) para optimizar la interfaz.

<div align="center">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VII/Continous-Monitoring/google-analytics.png?raw=true" alt="analytics" width="600">
</div><br><br>

**Supervisión de APIs internas y externas**
  - **Postman Monitors**  
    Programar colecciones que validen diariamente los flujos críticos (autenticación, crear publicación, solicitud de donación) y notifiquen ante fallos.
  - **Pingdom / Uptime Robot**  
    Comprobar la disponibilidad y el tiempo de respuesta de la URL pública del backend y del frontend desde múltiples ubicaciones geográficas.

<div align="center">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VII/Continous-Monitoring/postman.png?raw=true" alt="postman" width="600">
</div><br><br>

**Logging centralizado y trazas distribuidas**
  - **ELK Stack (Elasticsearch, Logstash, Kibana)**  
    Centralizar logs JSON de Spring Boot y errores de Angular; facilitar búsquedas por correlación de petición.
  - **Zipkin / Jaeger**  
    Propagar trazas entre componentes para diagnosticar latencias en llamadas internas y flujos de negocio complejos.

<div align="center">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VII/Continous-Monitoring/zipkin.png?raw=true" alt="zipkin" width="600">
</div><br><br>

**Auditorías de calidad y rendimiento web**
  - **Google Lighthouse**  
    Auditar accesibilidad, SEO, performance y mejores prácticas en cada release del frontend.
  - **SonarQube**  
    Analizar la calidad de código Java y TypeScript, detectar vulnerabilidades, “code smells” y deuda técnica.

<div align="center">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VII/Continous-Monitoring/sonarqube.png?raw=true" alt="sonarqube" width="600">
</div><br><br>

### 7.4.2. Monitoring Pipeline Components

Un pipeline de monitoreo constante en *CambiaZo* asegura que tanto la plataforma web como la app móvil mantengan un rendimiento óptimo y una experiencia fluida para sus usuarios. Este pipeline incluye etapas clave: recopilación de métricas, almacenamiento centralizado, análisis automático y visualización en tiempo real para la toma de decisiones.

Herramientas como **Google Lighthouse** y **Postman Monitors** son esenciales en este proceso. Lighthouse permite realizar auditorías completas sobre el frontend de Angular, evaluando criterios como accesibilidad, SEO, rendimiento y buenas prácticas. Estos reportes permiten identificar mejoras en la interfaz, como tiempos de carga lentos, malas jerarquías semánticas o uso ineficiente de recursos estáticos.

<div align="center">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VII/Continous-Monitoring/lighthouse.png?raw=true" alt="sonarqube">
</div><br><br>

Por otro lado, **Postman Monitors** ejecuta de forma periódica flujos críticos del backend desarrollado en Spring Boot, como el inicio de sesión, la publicación de productos o las solicitudes de donación. Esto permite detectar fallos antes de que impacten a los usuarios reales, garantizando así la fiabilidad del sistema.

Complementando estas herramientas, **Prometheus** y **Grafana** permiten visualizar el uso de CPU, la latencia por endpoint, y detectar posibles cuellos de botella en las APIs. Además, soluciones como **Sentry** y **Google Analytics** capturan errores en tiempo real, flujos de navegación y métricas de comportamiento que ayudan a optimizar la experiencia general en *CambiaZo*.

<div align="center">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VII/Continous-Monitoring/grafana.png?raw=true" alt="grafana">
</div><br><br>


### 7.4.3. Alerting Pipeline Components

En *CambiaZo*, el sistema de alertas está diseñado para detectar fallos o comportamientos anómalos tanto en el frontend Angular como en el backend Spring Boot. Utilizando herramientas como **Prometheus Alertmanager** y **Grafana**, se configuran umbrales críticos (como uso excesivo de CPU, latencia superior a 500 ms o errores 5xx en endpoints clave) que disparan notificaciones inmediatas a través de canales como Slack o correo electrónico, permitiendo una respuesta rápida ante incidentes.

<div align="center">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VII/Continous-Monitoring/prometheus.png?raw=true" alt="prometheus">
</div><br><br>

Además, se integran alertas desde **Postman Monitors**, que informan si alguno de los flujos automatizados falla (por ejemplo, crear una oferta o aceptar una donación). De manera complementaria, **Sentry** y **Datadog RUM** notifican errores en tiempo real del lado del cliente, como caídas de JavaScript o problemas de navegación, ayudando a identificar fallos específicos en la experiencia de usuario que requieren atención inmediata.

<div align="center">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VII/Continous-Monitoring/sentry.png?raw=true" alt="sentry">
</div><br><br>

### 7.4.4. Notification Pipeline Components

En *CambiaZo*, el pipeline de notificaciones garantiza que tanto los administradores como los usuarios finales estén informados en tiempo real sobre eventos relevantes del sistema. Para ello, se utilizan servicios como **Firebase Cloud Messaging (FCM)**, que permite enviar notificaciones push a la app móvil cuando, por ejemplo, una solicitud de donación ha sido aceptada o una oferta ha sido respondida. Estas alertas mejoran la experiencia del usuario al mantenerlo conectado con la actividad de su cuenta.

<div align="center">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VII/Continous-Monitoring/firebase_cloud.png?raw=true" alt="firebase_cloud">
</div><br><br>

Desde el lado administrativo, se configura la notificación automática de eventos críticos mediante integraciones con **Slack** o **Jenkins**, alimentadas por los sistemas de monitoreo y alertas (Prometheus, Postman, Sentry). Esto permite que el equipo técnico reciba notificaciones instantáneas ante caídas, errores o anomalías detectadas, y pueda actuar de inmediato para asegurar la continuidad del servicio.

<div align="center">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VII/Continous-Monitoring/jenkins.png?raw=true" alt="firebase_cloud">
</div><br><br>

# Capítulo VIII: Experiment-Driven Development

## 8.1. Experiment Planning

### 8.1.1. As-Is Summary

El intercambio y la donación de bienes en Perú se realizan hoy de manera fragmentada a través de grupos de WhatsApp, Facebook y otras redes sociales, sin un canal único que concentre publicaciones, búsquedas y coordinación. Los usuarios gestionan perfiles, envían ofertas y acuerdan entregas de forma manual, lo que genera altos tiempos de respuesta y frecuentes malentendidos. Para las donaciones, cada usuario debe trasladar sus objetos a puntos de recolección físicos y carece de confirmación fiable de que el beneficiario haya recibido realmente la donación.

**Problemas identificados:**
- **Fragmentación de canales:** múltiples grupos y conversaciones dispersas dificultan encontrar coincidencias y realizar seguimientos.
- **Seguridad y confianza:** no existen mecanismos formales de verificación de identidad ni de reputación, lo que incrementa el riesgo de estafas.
- **Carga logística:** la entrega de donaciones depende de la disponibilidad y voluntad del donador para desplazarse, sin opción de recolección programada.
- **Alcance limitado:** al no ofrecer traducciones ni personalización, la iniciativa se restringe al público hispanohablante y a usuarios conocedores de esas redes.

**Objetivos de mejora:**
- **Centralizar la plataforma:** construir una aplicación web y móvil única para intercambios y donaciones, con búsqueda unificada y gestión de publicaciones.
- **Fortalecer la confianza:** implementar verificación de identidad, sistema de calificaciones y reseñas para reputación de usuarios.
- **Optimizar la logística:** ofrecer programación de recolección y rastreo en tiempo real de las donaciones.
- **Expandir la audiencia:** incorporar traducciones (inglés, chino) y opciones de personalización para llegar a un público más diverso.

### 8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims

**Assumptions:**
- Los usuarios valorarán una plataforma única que centralice intercambios y donaciones, reduciendo la fragmentación actual.
- Un sistema de reputación (calificaciones y reseñas) aumentará la confianza y disminuirá el riesgo de fraudes.
- La opción de programar la recolección de donaciones facilitará la logística y hará el proceso más atractivo para los donadores.
- Las suscripciones premium con “boost” diario de publicaciones generarán suficiente valor percibido para justificar un pago mensual.
- Las alianzas con ONGs y organizaciones locales elevarán la credibilidad y el alcance de la aplicación.

**Knowledge Gaps:**
- Disposición a pagar: ¿qué porcentaje de usuarios aceptaría suscribirse a un plan de S/. X mensuales?
- Costos y tiempos de recolección: ¿cuál es el precio óptimo y la frecuencia adecuada para un servicio de pickup programado en Lima?
- Preferencias de filtrado: ¿qué criterios (categoría, ubicación, estado del objeto) son más valorados al buscar intercambios?
- Alcance multilingüe: ¿qué proporción de la audiencia potencial requerirá inglés o chino, y con qué nivel de calidad?
- Efectividad de las ONG partner: ¿cómo impacta la visibilidad de ONGs aliadas en la confianza y uso de la plataforma?

**Ideas:**
- Realizar encuestas y entrevistas a usuarios piloto para validar la disposición a pagar y los criterios de filtrado.
- Desarrollar un MVP de recolección programada y medir su adopción en un barrio de Lima.
- Implementar un test A/B del “boost” premium para evaluar su efecto en la tasa de intercambio exitoso.
- Organizar un programa piloto con una o dos ONGs locales para probar el flujo completo de donación y seguimiento.
- Crear prototipos de la interfaz en español, inglés y chino, y recoger feedback sobre la calidad de la traducción.

**Claims:**
- Centralizar el intercambio y la donación en CambiaZo reducirá el tiempo de coordinación de transacciones en al menos un 30 %.
- El sistema de reputación disminuirá las quejas por fraudes en un 50 % durante el primer trimestre tras el lanzamiento.
- La función de pickup programado aumentará la frecuencia de donaciones mensuales en un 20 %.
- El “boost” diario para suscriptores premium incrementará en un 25 % la visibilidad de sus publicaciones y, por ende, la tasa de éxito de intercambios.
- Las alianzas con ONGs contribuirán a un aumento del 15 % en la base de usuarios activos durante los primeros seis meses.

### 8.1.3. Experiment-Ready Questions

<table border="1" cellpadding="8" cellspacing="0">
  <thead>
    <tr>
      <th>Pregunta</th>
      <th>Confianza</th>
      <th>Riesgo</th>
      <th>Impacto</th>
      <th>Interés</th>
      <th>Puntaje Total</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>¿Reducirá el tiempo de coordinación una plataforma unificada frente a métodos actuales como WhatsApp y Facebook?</td>
      <td>7 – Muchos usuarios reportan lentitud y desorden con los métodos actuales.</td>
      <td>2 – Bajo riesgo técnico y de adopción, la implementación es directa.</td>
      <td>8 – Podría mejorar significativamente la eficiencia de coordinación.</td>
      <td>7 – Alta relevancia para usuarios frecuentes que buscan organizar mejor sus intercambios.</td>
      <td>24</td>
    </tr>
    <tr>
      <td>¿Aumentará la confianza de los usuarios un sistema de reputación basado en calificaciones y reseñas?</td>
      <td>8 – Es una práctica común en plataformas exitosas como MercadoLibre y Airbnb.</td>
      <td>3 – Riesgo medio por la necesidad de evitar abusos o manipulaciones.</td>
      <td>8 – Incrementa la percepción de seguridad y reduce conflictos entre usuarios.</td>
      <td>7 – Muy deseado por los usuarios entrevistados, especialmente nuevos.</td>
      <td>26</td>
    </tr>
    <tr>
      <td>¿Mejorará la tasa de donaciones con la implementación de un sistema de recolección programada?</td>
      <td>6 – Lógica basada en conveniencia, aunque requiere validación local.</td>
      <td>4 – Riesgo logístico por costos y coordinación de rutas.</td>
      <td>7 – Elimina fricciones clave como la falta de movilidad o tiempo.</td>
      <td>6 – Interés moderado con potencial de adopción entre usuarios ocupados.</td>
      <td>23</td>
    </tr>
    <tr>
      <td>¿Estarán dispuestos los usuarios a pagar una suscripción mensual por beneficios como el “boost” de publicaciones?</td>
      <td>5 – Requiere validación con encuestas y pruebas A/B.</td>
      <td>5 – Riesgo medio si no se percibe valor suficiente en el servicio.</td>
      <td>6 – Puede contribuir a la sostenibilidad financiera de la plataforma.</td>
      <td>6 – Interés condicionado a la utilidad percibida de los beneficios.</td>
      <td>22</td>
    </tr>
    <tr>
      <td>¿Aumentará la visibilidad y éxito de intercambios al usar un “boost” diario en las publicaciones?</td>
      <td>6 – Funcionalidad común en marketplaces como OLX o Facebook Marketplace.</td>
      <td>3 – Riesgo bajo, ya que es técnica y comercialmente viable.</td>
      <td>6 – Incentiva a usuarios activos y mejora la rotación de publicaciones.</td>
      <td>5 – Relevante para usuarios frecuentes con artículos destacados.</td>
      <td>20</td>
    </tr>
    <tr>
      <td>¿Aumentará la base de usuarios activos gracias a alianzas con ONGs que validen las donaciones?</td>
      <td>7 – Las ONGs generan confianza y credibilidad entre la comunidad.</td>
      <td>3 – Bajo riesgo si se establecen alianzas estratégicas bien definidas.</td>
      <td>6 – Fortalece el aspecto solidario y reputacional de la plataforma.</td>
      <td>6 – Alta afinidad con usuarios comprometidos socialmente.</td>
      <td>22</td>
    </tr>
    <tr>
      <td>¿Mejorará la experiencia de usuarios no hispanohablantes con versiones multilingües (inglés, chino)?</td>
      <td>4 – Falta de datos concretos sobre usuarios que lo requieren.</td>
      <td>2 – Bajo riesgo inicial; puede explorarse con un prototipo.</td>
      <td>5 – Impacto limitado al nicho de usuarios extranjeros.</td>
      <td>4 – Interés bajo-moderado en esta etapa del desarrollo.</td>
      <td>15</td>
    </tr>
    <tr>
      <td>¿Mejorará la experiencia de búsqueda al incluir filtros por categoría, estado y ubicación?</td>
      <td>6 – Basado en funcionalidades estándar de búsqueda en otras apps.</td>
      <td>2 – Bajo riesgo técnico y de implementación.</td>
      <td>7 – Aumenta la eficiencia y precisión en la búsqueda de artículos.</td>
      <td>6 – Prioridad alta para usuarios activos que buscan intercambios específicos.</td>
      <td>21</td>
    </tr>
  </tbody>
</table>
<br><br>

### 8.1.4. Question Backlog

<table border="1" cellpadding="8" cellspacing="0">
  <thead>
    <tr>
      <th>Prioridad (1,2,3,5,8)</th>
      <th>Pregunta</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>8</td>
      <td>¿Mejorará la comunicación entre usuarios si se envía una notificación por correo al recibir una propuesta o pactar un intercambio? (nuevo)</td>
    </tr>
    <tr>
      <td>5</td>
      <td>¿Mejorará la experiencia del usuario al mostrar un mensaje de carga mientras se publica o elimina un artículo?</td>
    </tr>
    <tr>
      <td>5</td>
      <td>¿Aumentará el entendimiento de las calificaciones si se muestra el promedio con estrellas grandes en vez de solo números?</td>
    </tr>
    <tr>
      <td>5</td>
      <td>¿Aumentará la visibilidad de publicaciones relevantes si se permite destacar ciertos artículos en la vista general de productos?</td>
    </tr>
    <tr>
      <td>3</td>
      <td>¿Facilitará la difusión de productos si se permite compartir publicaciones mediante un enlace? (nuevo)</td>
    </tr>
    <tr>
      <td>3</td>
      <td>¿Mejorará la experiencia de búsqueda al incluir filtros por categoría, estado y ubicación?</td>
    </tr>
    <tr>
      <td>2</td>
      <td>¿Facilitará la interacción entre usuarios si se permite compartir el perfil de otro usuario mediante un enlace?</td>
    </tr>
    <tr>
      <td>1</td>
      <td>¿Mejorará la experiencia de usuarios no hispanohablantes con versiones multilingües (inglés, chino)?</td>
    </tr>
  </tbody>
</table>
<br><br>

### 8.1.5. Experiment Cards

<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2">Question</th></tr>
  <tr><td colspan="2">¿Mejorará la comunicación entre usuarios si se envía una notificación por correo al recibir una propuesta o pactar un intercambio?</td></tr>
  <tr><th>Why</th><td>Muchos usuarios no revisan la plataforma constantemente. Enviar correos les permite reaccionar a tiempo y no perder oportunidades de interacción.</td></tr>
  <tr><th>What</th><td>Implementar notificaciones automáticas por correo al recibir propuestas o cuando se pacta un intercambio, incluyendo un enlace directo a la sección correspondiente.</td></tr>
  <tr><th>Hypothesis</th><td>Se espera una mejora del 40% en la tasa de respuesta o cierre de intercambios gracias a la visibilidad inmediata mediante correo.</td></tr>
</table><br><br>

<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2">Question</th></tr>
  <tr><td colspan="2">¿Mejorará la experiencia del usuario al mostrar un mensaje de carga mientras se publica o elimina un artículo?</td></tr>
  <tr><th>Why</th><td>Cuando el sistema tarda en procesar una acción, los usuarios pueden pensar que no está funcionando. Un mensaje de carga reduce la incertidumbre y mejora la percepción de fluidez.</td></tr>
  <tr><th>What</th><td>Mostrar una animación o mensaje que indique "Publicando..." o "Eliminando..." mientras se realiza la operación, antes de mostrar cualquier mensaje final o redirección.</td></tr>
  <tr><th>Hypothesis</th><td>Se espera que al menos el 80% de los usuarios consideren útil la inclusión del mensaje de carga, según encuestas de satisfacción post-interacción.</td></tr>
</table>
<br><br>


<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2">Question</th></tr>
  <tr><td colspan="2">¿Aumentará el entendimiento de las calificaciones si se muestra el promedio con estrellas grandes en vez de solo números?</td></tr>
  <tr><th>Why</th><td>Los números pueden no ser tan interpretables a simple vista como las estrellas. Las representaciones visuales mejoran la comprensión inmediata.</td></tr>
  <tr><th>What</th><td>Reemplazar o complementar la calificación numérica con una representación gráfica de estrellas en los perfiles y publicaciones.</td></tr>
  <tr><th>Hypothesis</th><td>Se espera que el 70% de los usuarios comprendan mejor las calificaciones al usar el nuevo formato visual, según pruebas A/B y encuestas.</td></tr>
</table><br><br>

<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2">Question</th></tr>
  <tr><td colspan="2">¿Aumentará la visibilidad de publicaciones relevantes si se permite destacar ciertos artículos en la vista general de productos?</td></tr>
  <tr><th>Why</th><td>Los usuarios pueden perderse entre muchas publicaciones. Destacar artículos ayuda a priorizar los más recientes, populares o importantes.</td></tr>
  <tr><th>What</th><td>Agregar una sección o etiqueta visual para artículos destacados en la vista principal del catálogo.</td></tr>
  <tr><th>Hypothesis</th><td>Se espera un aumento del 35% en clics hacia publicaciones destacadas en comparación con el promedio de publicaciones estándar.</td></tr>
</table><br><br>


<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2">Question</th></tr>
  <tr><td colspan="2">¿Facilitará la difusión de productos si se permite compartir publicaciones mediante un enlace?</td></tr>
  <tr><th>Why</th><td>Compartir publicaciones fuera de la plataforma permite que los productos lleguen a más personas, lo que puede incrementar las visitas y potenciales intercambios.</td></tr>
  <tr><th>What</th><td>Habilitar un botón “Compartir publicación” que genere un enlace público fácilmente copiable desde cada publicación.</td></tr>
  <tr><th>Hypothesis</th><td>Se espera que al menos el 30% de las publicaciones compartidas generen nuevas visitas desde enlaces externos.</td></tr>
</table><br><br>

<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2">Question</th></tr>
  <tr><td colspan="2">¿Mejorará la experiencia de búsqueda al incluir filtros por categoría, estado y ubicación?</td></tr>
  <tr><th>Why</th><td>Los usuarios buscan eficiencia al encontrar productos específicos. Filtros avanzados agilizan el proceso y evitan frustración por resultados irrelevantes.</td></tr>
  <tr><th>What</th><td>Agregar filtros de búsqueda por categorías (ropa, juguetes, etc.), estado del producto (nuevo, usado) y ubicación geográfica.</td></tr>
  <tr><th>Hypothesis</th><td>Se proyecta una mejora del 35% en la tasa de coincidencia entre búsqueda y artículos seleccionados.</td></tr>
</table><br><br>

<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2">Question</th></tr>
  <tr><td colspan="2">¿Facilitará la interacción entre usuarios si se permite compartir el perfil de otro usuario mediante un enlace?</td></tr>
  <tr><th>Why</th><td>Poder compartir el perfil de un usuario facilita recomendaciones, coordinación y difusión, lo cual puede aumentar la confianza y la red de contactos.</td></tr>
  <tr><th>What</th><td>Habilitar un botón “Compartir perfil” que genere un enlace accesible públicamente al perfil del usuario seleccionado.</td></tr>
  <tr><th>Hypothesis</th><td>Se espera que el 25% de los perfiles compartidos generen nuevas interacciones dentro de la plataforma (visitas, mensajes o intercambios).</td></tr>
</table><br><br>


<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2">Question</th></tr>
  <tr><td colspan="2">¿Mejorará la experiencia de usuarios no hispanohablantes con versiones multilingües (inglés, chino)?</td></tr>
  <tr><th>Why</th><td>Al habilitar otros idiomas, se facilita el acceso a personas extranjeras, ampliando el alcance y potencial uso internacional de la aplicación.</td></tr>
  <tr><th>What</th><td>Traducir la interfaz principal al inglés y al chino con opción de selección automática según la configuración del dispositivo.</td></tr>
  <tr><th>Hypothesis</th><td>Se estima un aumento del 15% en usuarios no hispanohablantes durante los primeros seis meses tras el lanzamiento de la versión multilingüe.</td></tr>
</table><br><br>

## 8.2. Experiment Design

### 8.2.1. Hypotheses

<table border="1" cellpadding="8" cellspacing="0">
  <tr><th colspan="2">Pregunta 1</th></tr>
  <tr><td><strong>Question</strong></td><td>¿Mejorará la comunicación entre usuarios si se envía una notificación por correo al recibir una propuesta o pactar un intercambio?</td></tr>
  <tr><td><strong>Belief</strong></td><td>El correo electrónico permite alertar a los usuarios en tiempo real sobre eventos importantes, mejorando la tasa de respuesta y reduciendo el riesgo de perder oportunidades por falta de notificación.</td></tr>
  <tr><td><strong>Hypothesis</strong></td><td>La implementación de notificaciones por correo aumentará en al menos un 40% la tasa de respuesta o cierre de intercambios, al mantener a los usuarios informados de forma oportuna.</td></tr>
  <tr><td><strong>Null Hypothesis</strong></td><td>El envío de correos electrónicos no tendrá un impacto significativo en la comunicación ni en la tasa de interacción entre usuarios.</td></tr>
</table><br><br>

<table border="1" cellpadding="8" cellspacing="0">
  <tr><th colspan="2">Pregunta 2</th></tr>
  <tr><td><strong>Question</strong></td><td>¿Mejorará la experiencia del usuario al mostrar un mensaje de carga mientras se publica o elimina un artículo?</td></tr>
  <tr><td><strong>Belief</strong></td><td>Mostrar mensajes de carga durante procesos críticos brinda mayor claridad al usuario, reduce la frustración y mejora la percepción de estabilidad del sistema.</td></tr>
  <tr><td><strong>Hypothesis</strong></td><td>El 80% de los usuarios considerará que el mensaje de carga mejora su experiencia al interactuar con la plataforma, según encuestas posteriores a la acción.</td></tr>
  <tr><td><strong>Null Hypothesis</strong></td><td>El mensaje de carga no tendrá un efecto significativo en la percepción de experiencia del usuario durante publicaciones o eliminaciones.</td></tr>
</table>
<br><br>

<table border="1" cellpadding="8" cellspacing="0">
  <tr><th colspan="2">Pregunta 3</th></tr>
  <tr><td><strong>Question</strong></td><td>¿Aumentará el entendimiento de las calificaciones si se muestra el promedio con estrellas grandes en vez de solo números?</td></tr>
  <tr><td><strong>Belief</strong></td><td>Las representaciones visuales son más intuitivas que los números. Mostrar estrellas facilitará la interpretación de calificaciones por parte de los usuarios.</td></tr>
  <tr><td><strong>Hypothesis</strong></td><td>El uso de estrellas para representar calificaciones aumentará el entendimiento en al menos un 70%, según encuestas y pruebas A/B de comprensión rápida.</td></tr>
  <tr><td><strong>Null Hypothesis</strong></td><td>El cambio de números a estrellas no mejorará significativamente la comprensión de las calificaciones.</td></tr>
</table><br><br>

<table border="1" cellpadding="8" cellspacing="0">
  <tr><th colspan="2">Pregunta 4</th></tr>
  <tr><td><strong>Question</strong></td><td>¿Aumentará la visibilidad de publicaciones relevantes si se permite destacar ciertos artículos en la vista general de productos?</td></tr>
  <tr><td><strong>Belief</strong></td><td>Destacar visualmente algunas publicaciones en la vista general facilitará que los usuarios las noten, generando más interacciones y clics.</td></tr>
  <tr><td><strong>Hypothesis</strong></td><td>Las publicaciones destacadas recibirán al menos un 35% más de clics que las publicaciones no destacadas, según métricas de interacción.</td></tr>
  <tr><td><strong>Null Hypothesis</strong></td><td>Destacar publicaciones no generará un aumento significativo en la cantidad de clics o interacciones.</td></tr>
</table><br><br>

<table border="1" cellpadding="8" cellspacing="0">
  <tr><th colspan="2">Pregunta 5</th></tr>
  <tr><td><strong>Question</strong></td><td>¿Facilitará la difusión de productos si se permite compartir publicaciones mediante un enlace?</td></tr>
  <tr><td><strong>Belief</strong></td><td>Permitir compartir publicaciones mediante enlaces facilita la promoción de productos fuera de la plataforma, lo cual puede atraer nuevos usuarios y aumentar las visitas a productos.</td></tr>
  <tr><td><strong>Hypothesis</strong></td><td>Se espera que al menos el 30% de las publicaciones compartidas generen nuevas visitas desde enlaces externos, mejorando la exposición de productos.</td></tr>
  <tr><td><strong>Null Hypothesis</strong></td><td>La opción de compartir publicaciones mediante enlaces no generará un incremento significativo en visitas o visualizaciones.</td></tr>
</table><br><br>

<table border="1" cellpadding="8" cellspacing="0">
  <tr><th colspan="2">Pregunta 6</th></tr>
  <tr><td><strong>Question</strong></td><td>¿Mejorará la experiencia de búsqueda al incluir filtros por categoría, estado y ubicación?</td></tr>
  <tr><td><strong>Belief</strong></td><td>Los filtros permiten encontrar artículos específicos con mayor precisión, reduciendo la frustración y mejorando la eficiencia de búsqueda.</td></tr>
  <tr><td><strong>Hypothesis</strong></td><td>El uso de filtros mejorará en al menos un 35% la velocidad promedio de búsqueda y aumentará la satisfacción del usuario en un 25%.</td></tr>
  <tr><td><strong>Null Hypothesis</strong></td><td>La implementación de filtros no tendrá impacto relevante en la experiencia de búsqueda.</td></tr>
</table><br><br>

<table border="1" cellpadding="8" cellspacing="0">
  <tr><th colspan="2">Pregunta 7</th></tr>
  <tr><td><strong>Question</strong></td><td>¿Facilitará la interacción entre usuarios si se permite compartir el perfil de otro usuario mediante un enlace?</td></tr>
  <tr><td><strong>Belief</strong></td><td>Poder compartir perfiles directamente simplifica la recomendación y conexión entre usuarios, lo cual puede aumentar las visitas a perfiles y fomentar la actividad.</td></tr>
  <tr><td><strong>Hypothesis</strong></td><td>La opción de compartir perfiles generará al menos un 25% de aumento en visitas o interacciones con dichos perfiles compartidos.</td></tr>
  <tr><td><strong>Null Hypothesis</strong></td><td>La posibilidad de compartir perfiles mediante enlaces no generará un incremento significativo en interacciones o visitas.</td></tr>
</table><br><br>

<table border="1" cellpadding="8" cellspacing="0">
  <tr><th colspan="2">Pregunta 8</th></tr>
  <tr><td><strong>Question</strong></td><td>¿Mejorará la experiencia de usuarios no hispanohablantes con versiones multilingües (inglés, chino)?</td></tr>
  <tr><td><strong>Belief</strong></td><td>El acceso multilingüe puede atraer usuarios extranjeros o bilingües y mejorar su experiencia, eliminando barreras idiomáticas.</td></tr>
  <tr><td><strong>Hypothesis</strong></td><td>La inclusión de versiones en inglés y chino incrementará el uso activo de la plataforma por parte de usuarios no hispanohablantes en un 20%.</td></tr>
  <tr><td><strong>Null Hypothesis</strong></td><td>Las versiones multilingües no tendrán un efecto significativo sobre la experiencia ni el uso por parte de usuarios no hispanohablantes.</td></tr>
</table><br><br>


### 8.2.2. Measures

<table border="1" cellpadding="8" cellspacing="0">
  <tr>
    <th>Question</th>
    <td>¿Mejorará la comunicación entre usuarios si se envía una notificación por correo al recibir una propuesta o pactar un intercambio?</td>
  </tr>
  <tr>
    <th>Measure</th>
    <td>Evaluar la tasa de respuesta a propuestas antes y después de implementar las notificaciones por correo. Complementar con encuestas sobre utilidad percibida y medir el tiempo promedio de reacción desde el evento hasta la respuesta del usuario.</td>
  </tr>
</table>

<br/>


<table border="1" cellpadding="8" cellspacing="0">
  <tr>
    <th>Question</th>
    <td>¿Mejorará la experiencia del usuario al mostrar un mensaje de carga mientras se publica o elimina un artículo?</td>
  </tr>
  <tr>
    <th>Measure</th>
    <td>Aplicar encuestas breves después de la acción para conocer la utilidad percibida del mensaje de carga. Medir también la tasa de interrupciones durante las operaciones sin y con el mensaje.</td>
  </tr>
</table>
<br/>

<table border="1" cellpadding="8" cellspacing="0">
  <tr>
    <th>Question</th>
    <td>¿Aumentará el entendimiento de las calificaciones si se muestra el promedio con estrellas grandes en vez de solo números?</td>
  </tr>
  <tr>
    <th>Measure</th>
    <td>Aplicar una prueba A/B donde algunos usuarios vean estrellas y otros solo números. Evaluar mediante encuestas cuál formato fue más comprensible. También medir la cantidad de usuarios que interactúan con perfiles según el formato mostrado.</td>
  </tr>
</table>

<br/>

<table border="1" cellpadding="8" cellspacing="0">
  <tr>
    <th>Question</th>
    <td>¿Aumentará la visibilidad de publicaciones relevantes si se permite destacar ciertos artículos en la vista general de productos?</td>
  </tr>
  <tr>
    <th>Measure</th>
    <td>Comparar la cantidad de clics, visitas y tiempo promedio de visualización entre publicaciones destacadas y no destacadas. Analizar las métricas de interacción antes y después de implementar el sistema de destacados.</td>
  </tr>
</table>

<br/>

<table border="1" cellpadding="8" cellspacing="0">
  <tr>
    <th>Question</th>
    <td>¿Facilitará la difusión de productos si se permite compartir publicaciones mediante un enlace?</td>
  </tr>
  <tr>
    <th>Measure</th>
    <td>Monitorear la cantidad de publicaciones compartidas, clics en los enlaces generados y visitas únicas provenientes de dichos enlaces. Además, medir el número de interacciones iniciadas desde visitas externas.</td>
  </tr>
</table>

<br/>

<table border="1" cellpadding="8" cellspacing="0">
  <tr>
    <th>Question</th>
    <td>¿Facilitará la interacción entre usuarios si se permite compartir el perfil de otro usuario mediante un enlace?</td>
  </tr>
  <tr>
    <th>Measure</th>
    <td>Monitorear la cantidad de perfiles compartidos, clics en enlaces compartidos y nuevas interacciones generadas a partir de estos accesos. Complementar con una encuesta que mida la utilidad percibida de esta funcionalidad por parte de los usuarios.</td>
  </tr>
</table>

<br/>

<table border="1" cellpadding="8" cellspacing="0">
  <tr>
    <th>Question</th>
    <td>¿Mejorará la experiencia de búsqueda al incluir filtros por categoría, estado y ubicación?</td>
  </tr>
  <tr>
    <th>Measure</th>
    <td>Medir el tiempo promedio que toma encontrar un artículo usando filtros frente a búsquedas sin filtros. Aplicar encuestas para determinar si los usuarios encuentran más fácilmente lo que buscan con la nueva funcionalidad.</td>
  </tr>
</table>

<br/>

<table border="1" cellpadding="8" cellspacing="0">
  <tr>
    <th>Question</th>
    <td>¿Mejorará la experiencia de usuarios no hispanohablantes con versiones multilingües (inglés, chino)?</td>
  </tr>
  <tr>
    <th>Measure</th>
    <td>Analizar el incremento en registros y actividad por parte de usuarios con idioma configurado distinto al español. Recoger retroalimentación directa mediante encuestas multilingües sobre usabilidad y comprensión de la interfaz.</td>
  </tr>
</table>

<br/>

### 8.2.3. Conditions

<table border="1" cellpadding="8" cellspacing="0">
  <tr>
    <th>Question</th>
    <td>¿Mejorará la comunicación entre usuarios si se envía una notificación por correo al recibir una propuesta o pactar un intercambio?</td>
  </tr>
  <tr>
    <th>Condición Experimental</th>
    <td>La tasa de respuesta aumentará en al menos un 40% entre usuarios que reciban correos respecto a los que no, y el tiempo promedio de reacción será menor.</td>
  </tr>
  <tr>
    <th>Condición de Control</th>
    <td>No se observará un aumento significativo en la tasa de respuesta ni en el tiempo de reacción de los usuarios que reciban correos.</td>
  </tr>
</table>

<br/>

<table border="1" cellpadding="8" cellspacing="0">
  <tr>
    <th>Question</th>
    <td>¿Mejorará la experiencia del usuario al mostrar un mensaje de carga mientras se publica o elimina un artículo?</td>
  </tr>
  <tr>
    <th>Condición Experimental</th>
    <td>Al menos el 80% de los usuarios reportará una experiencia más clara y fluida al ver el mensaje de carga, y se observará una reducción del 30% en acciones repetidas o abandonos.</td>
  </tr>
  <tr>
    <th>Condición de Control</th>
    <td>La percepción de experiencia del usuario no mejorará significativamente y se mantendrán tasas similares de clics repetidos o interrupciones.</td>
  </tr>
</table>

<br/>

<table border="1" cellpadding="8" cellspacing="0">
  <tr>
    <th>Question</th>
    <td>¿Aumentará el entendimiento de las calificaciones si se muestra el promedio con estrellas grandes en vez de solo números?</td>
  </tr>
  <tr>
    <th>Condición Experimental</th>
    <td>El 70% de los usuarios entenderá correctamente la calificación de un perfil tras ver el formato con estrellas, validado mediante prueba A/B.</td>
  </tr>
  <tr>
    <th>Condición de Control</th>
    <td>El formato de estrellas no mejorará significativamente la comprensión en comparación con el formato numérico.</td>
  </tr>
</table>

<br/>

<table border="1" cellpadding="8" cellspacing="0">
  <tr>
    <th>Question</th>
    <td>¿Aumentará la visibilidad de publicaciones relevantes si se permite destacar ciertos artículos en la vista general de productos?</td>
  </tr>
  <tr>
    <th>Condición Experimental</th>
    <td>Las publicaciones destacadas recibirán al menos un 35% más de clics que las publicaciones no destacadas, según registros de interacción.</td>
  </tr>
  <tr>
    <th>Condición de Control</th>
    <td>No habrá una diferencia significativa en el número de clics entre publicaciones destacadas y no destacadas.</td>
  </tr>
</table>

<br/>

<table border="1" cellpadding="8" cellspacing="0">
  <tr>
    <th>Question</th>
    <td>¿Facilitará la difusión de productos si se permite compartir publicaciones mediante un enlace?</td>
  </tr>
  <tr>
    <th>Condición Experimental</th>
    <td>Al menos el 30% de las publicaciones compartidas generarán visitas nuevas provenientes de enlaces externos, según los registros de tráfico y clics.</td>
  </tr>
  <tr>
    <th>Condición de Control</th>
    <td>Las publicaciones compartidas no generarán una diferencia significativa en el número de visitas respecto a publicaciones no compartidas.</td>
  </tr>
</table>

<br/>

<table border="1" cellpadding="8" cellspacing="0">
  <tr>
    <th>Question</th>
    <td>¿Mejorará la experiencia de búsqueda al incluir filtros por categoría, estado y ubicación?</td>
  </tr>
  <tr>
    <th>Condición Experimental</th>
    <td>Los usuarios encontrarán productos deseados en un 40% menos de tiempo y reportarán mayor satisfacción con el sistema de filtros.</td>
  </tr>
  <tr>
    <th>Condición de Control</th>
    <td>El tiempo de búsqueda y la satisfacción no cambiarán significativamente tras la introducción de filtros.</td>
  </tr>
</table>

<table border="1" cellpadding="8" cellspacing="0">
  <tr>
    <th>Question</th>
    <td>¿Facilitará la interacción entre usuarios si se permite compartir el perfil de otro usuario mediante un enlace?</td>
  </tr>
  <tr>
    <th>Condición Experimental</th>
    <td>Los perfiles compartidos generarán al menos un 25% de incremento en visitas o interacciones en comparación con perfiles no compartidos.</td>
  </tr>
  <tr>
    <th>Condición de Control</th>
    <td>Los perfiles compartidos no registrarán un incremento notable en visitas o interacciones respecto a los perfiles no compartidos.</td>
  </tr>
</table>

<br/>

<table border="1" cellpadding="8" cellspacing="0">
  <tr>
    <th>Question</th>
    <td>¿Mejorará la experiencia de usuarios no hispanohablantes con versiones multilingües (inglés, chino)?</td>
  </tr>
  <tr>
    <th>Condición Experimental</th>
    <td>La participación de usuarios no hispanohablantes aumentará en un 30% gracias a las versiones multilingües.</td>
  </tr>
  <tr>
    <th>Condición de Control</th>
    <td>No se detectará una mejora significativa en la participación de usuarios de otros idiomas tras implementar traducciones.</td>
  </tr>
</table>

<br/>

### 8.2.4. Scale Calculations and Decisions

Esta metodología emplea indicadores cuantitativos para determinar la validez de las hipótesis planteadas en un proyecto. Cada hipótesis se vincula con un parámetro de rendimiento específico: se clasifica como óptimo cuando el indicador logra completamente la meta establecida, satisfactorio cuando se sitúa entre el umbral mínimo y el óptimo, y problemático si permanece bajo el umbral mínimo, lo que demanda una reevaluación. Se establece un nivel sobresaliente cuando el resultado excede el valor óptimo en un 25% o superior, señalando un logro excepcional. Esta metodología facilita la toma de decisiones basadas en datos para confirmar o modificar las hipótesis del proyecto.

<table border="1" cellpadding="8" cellspacing="0">
  <thead>
    <tr>
      <th rowspan="2">Scale Calculation</th>
      <th rowspan="2">Decision</th>
      <th colspan="4">Factor</th>
    </tr>
    <tr>
      <th>Desfavorable</td>
      <th>Aceptable</td>
      <th>Ideal</td>
      <th>Excelente</td>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>Creemos que enviar notificaciones por correo mejorará la comunicación entre usuarios, aumentando en al menos un 40% la tasa de respuesta y reduciendo el tiempo promedio de interacción. Sabremos que esto es cierto al comparar las métricas antes y después de implementarlas.</td>
      <td>Enviar correos automáticos cuando se recibe una propuesta o se pacta un intercambio, para mantener informados a los usuarios de manera oportuna.</td>
      <td></td>
      <td></td>
      <td></td>
      <td>X</td>
    </tr>
    <tr>
      <td>Creemos que un mensaje de carga mejorará la experiencia del usuario al reducir la incertidumbre durante procesos de publicación o eliminación. Sabremos que esto es cierto cuando al menos el 80% de los usuarios lo considere útil y se reduzcan los clics repetidos o abandonos durante estas acciones.</td>
      <td>Mostrar una animación o mensaje de carga mientras se procesa la acción, antes de redirigir o mostrar un resultado final.</td>
      <td></td>
      <td></td>
      <td>X</td>
      <td></td>
    </tr>
    <tr>
      <td>Creemos que representar las calificaciones con estrellas aumentará el entendimiento en al menos un 70%. Sabremos que esto es cierto cuando los usuarios comprendan mejor las puntuaciones según pruebas A/B.</td>
      <td>Cambiar el formato visual de calificaciones de números a estrellas para facilitar su interpretación.</td>
      <td></td>
      <td>X</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Creemos que las publicaciones destacadas recibirán al menos un 35% más de clics. Sabremos que esto es cierto cuando el sistema de destacados genere mayor interacción medida por clics y visitas.</td>
      <td>Implementar sistema de destacados visuales para resaltar artículos relevantes en la vista general.</td>
      <td></td>
      <td>X</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Creemos que el uso de filtros mejorará en al menos un 35% la velocidad promedio de búsqueda y aumentará la satisfacción del usuario en un 25%. Sabremos que esto es cierto cuando los usuarios encuentren productos en un 40% menos de tiempo.</td>
      <td>Implementar filtros por categoría, estado y ubicación que permitan encontrar artículos específicos con mayor precisión, reduciendo la frustración y mejorando la eficiencia.</td>
      <td></td>
      <td></td>
      <td></td>
      <td>X</td>
    </tr>
    <tr>
      <td>Creemos que permitir compartir publicaciones mediante enlace facilitará su difusión, generando al menos un 30% de nuevas visitas desde fuentes externas. Sabremos que esto es cierto cuando veamos un aumento medible en clics y tráfico externo en publicaciones compartidas.</td>
      <td>Agregar un botón que genere un enlace público para compartir fácilmente publicaciones dentro y fuera de la plataforma.</td>
      <td></td>
      <td></td>
      <td>X</td>
      <td></td>
    </tr>
    <tr>
      <td>Creemos que compartir perfiles por enlace aumentará las visitas o interacciones en al menos un 25%. Sabremos que esto es cierto cuando se observe un incremento en tráfico hacia perfiles compartidos.</td>
      <td>Permitir compartir el perfil de un usuario mediante enlace para facilitar recomendaciones y conexiones dentro de la plataforma.</td>
      <td></td>
      <td>X</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Creemos que la inclusión de versiones en inglés y chino incrementará el uso activo de la plataforma por parte de usuarios no hispanohablantes en un 20%. Sabremos que esto es cierto cuando la participación aumente en un 30%.</td>
      <td>Desarrollar versiones multilingües que eliminen barreras idiomáticas y atraigan usuarios extranjeros o bilingües, mejorando su experiencia en la plataforma.</td>
      <td></td>
      <td>X</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>

</table>

### 8.2.5. Methods Selection

<table border="1" cellpadding="8" cellspacing="0">
  <thead>
    <tr>
      <th>Herramienta</th>
      <th>Google Analytics</th>
      <th>Catchpoint</th>
      <th>RedLine13</th>
      <th>Lighthouse</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Precio</th>
      <td>Plan gratuito/créditos sin costo</td>
      <td>Modelo basado en suscripción, con versiones de prueba</td>
      <td>Gratuito con restricciones</td>
      <td>Plan sin costo, disponible para ejecución local</td>
    </tr>
    <tr>
      <th>Capacidad de Análisis</th>
      <td>Análisis completo de métricas e información del comportamiento del usuario</td>
      <td>Seguimiento detallado de rendimiento y experiencia del usuario desde distintas ubicaciones</td>
      <td>Análisis enfocado a pruebas de carga y optimización de aplicaciones</td>
      <td>Análisis centrado en la experiencia del usuario, con métricas fundamentales de rendimiento y usabilidad</td>
    </tr>
    <tr>
      <th>Sencillez</th>
      <td>Aprendizaje simple de las métricas</td>
      <td>Interfaz avanzada pero detallada y completa</td>
      <td>Información específica y resumida sobre rendimiento</td>
      <td>Información condensada en valores clave que destacan aspectos de la aplicación</td>
    </tr>
    <tr>
      <th>Ventajas</th>
      <td>Excelente capacidad de generación de reportes y amplia integración con otros servicios</td>
      <td>Análisis en tiempo real desde diversas ubicaciones y dispositivos, ideal para empresas con usuarios globales</td>
      <td>Simulación de tráfico y pruebas de rendimiento bajo condiciones de carga</td>
      <td>Evaluación de usabilidad, rendimiento y diseño con métricas claras para optimizar la experiencia del usuario</td>
    </tr>
  </tbody>
</table>


### 8.2.6. Data Analytics: Goals, KPIs and Metrics Selection

Se realizaron pruebas de rendimiento, accesibilidad y mejores prácticas con LightHouse en nuestra aplicación CambiaZo para evaluar el desempeño y realizar optimizaciones que mejoren la experiencia del usuario. A continuación, evidencias de las pruebas realizadas para ambos segmentos objetivos (Intercambiadores y Donadores):

#### Intercambiadores:

<div align="center">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VIII/DataAnalytics/lighthouse1.png?raw=true" alt="sonarqube" width="600">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VIII/DataAnalytics/lighthouse2.png?raw=true" alt="sonarqube" width="600">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VIII/DataAnalytics/lighthouse3.png?raw=true" alt="sonarqube" width="600">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VIII/DataAnalytics/lighthouse4.png?raw=true" alt="sonarqube" width="600">
</div><br><br>

#### Donadores:

<div align="center">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VIII/DataAnalytics/lighthouse1Donadores.png?raw=true" alt="sonarqube" width="600">
  <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VIII/DataAnalytics/lighthouse2Donadores.png?raw=true" alt="sonarqube" width="600">
</div><br><br>

Los resultados de Lighthouse muestran que CambiaZo mantiene un excelente nivel de accesibilidad con puntuaciones superiores a 90, lo cual es fundamental para garantizar una experiencia inclusiva para todos los usuarios. Sin embargo, identificamos oportunidades de mejora en las métricas de Performance y SEO, donde algunos tests arrojaron puntuaciones de 77 y 79, indicando la necesidad de optimizar tiempos de carga y prácticas de SEO.

Estas métricas nos proporcionan una línea base sólida para medir el impacto de nuestras futuras implementaciones experimentales, especialmente las relacionadas con el sistema de boost, filtros de búsqueda y versiones multilingües. Los datos obtenidos nos permitirán validar nuestras hipótesis sobre la mejora en la experiencia del usuario y tomar decisiones informadas para optimizar el rendimiento de la plataforma.

### 8.2.7. Web and Mobile Tracking Plan

En Cambiazo, nuestro objetivo principal es optimizar y monitorear de manera continua la aplicación web y móvil para facilitar los intercambios entre usuarios, así como promover la participación activa dentro de la plataforma y fomentar la solidaridad mediante donaciones a ONGs. Este plan de seguimiento nos permitirá evaluar de forma efectiva las mejoras implementadas, garantizando una experiencia fluida, segura y alineada con los valores del proyecto.

El monitoreo de funcionalidades clave y experimentales se realizará en dos fases:

#### 1. Implementación Inicial
Durante esta etapa, se desplegarán funcionalidades como el registro de objetos, solicitudes de intercambio, lista de favoritos, visualización de perfiles y la sección de donaciones a ONGs, donde los usuarios podrán ofrecer objetos para ser donados directamente a organizaciones sociales. En paralelo, se recopilarán datos iniciales que servirán como línea base para futuras evaluaciones.

#### Recolección de Datos:

- Métricas de Uso: Número de usuarios activos (diarios y mensuales), duración promedio de sesión, objetos publicados, intercambios solicitados/completados y donaciones realizadas a ONGs.

- Interacciones de Usuario: Registro de eventos clave como clics en botones de "intercambiar", "donar a ONG", visitas a perfiles de ONGs, y navegación por las distintas secciones de la app.

- Feedback de Usuarios: Encuestas dentro de la app y formularios externos recogerán opiniones sobre la facilidad de uso, percepción de impacto social, utilidad de la sección de donaciones, y funcionalidad general de la plataforma.

#### Análisis Comparativo:

- Se contrastarán las métricas obtenidas con aquellas de versiones anteriores (sin la sección de ONGs) para evaluar el impacto de la reintroducción de esta funcionalidad en la experiencia general de los usuarios.

#### 2. Seguimiento Continuo
Una vez completada la implementación inicial, se establecerá un proceso permanente de monitoreo para identificar tendencias de uso, evaluar la efectividad de cada módulo (incluido el de donaciones), y aplicar mejoras continuas.

#### Recolección de Datos:

- Métricas en Tiempo Real: Se usarán herramientas como Firebase Analytics para monitorear eventos en vivo, detectar posibles errores o caídas, y observar flujos de navegación clave, como el de publicación de donaciones.

- Segmentación de Usuarios: Se agruparán usuarios según sus comportamientos (donadores frecuentes, receptores, intercambiadores activos, nuevos usuarios, etc.) para entender mejor los diferentes perfiles de interacción.

- Tasa de Retención: Se evaluará qué tan bien la app mantiene usuarios comprometidos, midiendo la retención después de ciertos periodos (Día 1, Día 7, Día 30) especialmente después de usar funciones como "intercambio" o "donar".

#### Evaluación y Ajustes:

- Informes Periódicos: Se elaborarán informes mensuales con análisis detallados, recomendaciones de mejora y hallazgos específicos respecto al uso de la sección de ONGs.

- Iteración Basada en Datos: La toma de decisiones será guiada por los datos recopilados y el feedback constante de los usuarios, asegurando que Cambiazo no solo sea funcional, sino también socialmente relevante y alineado con los valores de sostenibilidad y solidaridad.

Con este enfoque, Cambiazo se posiciona no solo como una plataforma de intercambio, sino también como un facilitador de impacto social positivo, manteniendo su evolución centrada en los usuarios y las comunidades que la utilizan.

## 8.3. Experimentation

### 8.3.1. To-Be User Stories

<table border="1" cellpadding="8" cellspacing="0">
  <thead>
    <tr>
      <th>User Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de Aceptación</th>
      <th>Relación con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>UA01</th>
      <td>Notificación por correo al recibir propuesta o acuerdo</td>
      <td>Como usuario de CambiaZo, quiero recibir una notificación por correo electrónico cuando me envíen una propuesta o se pacte un intercambio, para mantenerme informado incluso si no estoy dentro de la plataforma.</td>
      <td><b>Escenario 1: Notificación al recibir propuesta</b><br/>Given otro usuario me ha enviado una propuesta de intercambio.<br/><br/>When el sistema registra esta acción.<br/><br/>Then recibo un correo informándome sobre la nueva propuesta.<br/><br/>
      <b>Escenario 2: Notificación al pactar un intercambio</b><br/>Given he pactado un intercambio con otro usuario.<br/><br/>When se confirma el acuerdo.<br/><br/>Then el sistema me envía un correo confirmando el pacto de intercambio.
      </td>
      <td>E05</td>
    </tr>
    <tr> 
  <th>UA02</th>
    <td>Mensaje de carga al publicar o eliminar artículo</td>
    <td>Como usuario de CambiaZo, quiero ver un mensaje de carga mientras se publica o elimina un artículo, para tener mayor claridad de que el sistema está procesando mi acción.</td>
    <td><b>Escenario 1: Publicación en proceso</b><br/>Given he completado los campos para publicar un artículo.<br/><br/>When hago clic en “Publicar”.<br/><br/>Then aparece un mensaje o animación indicando que la publicación está en curso.<br/><br/>
    <b>Escenario 2: Eliminación en proceso</b><br/>Given deseo eliminar un artículo.<br/><br/>When confirmo la acción de eliminar.<br/><br/>Then el sistema muestra un mensaje de carga que indica que se está procesando la eliminación.
    </td>
    <td>5</td>
  </tr>
  <tr> 
    <th>UA03</th>
    <td>Visualización de calificaciones con estrellas</td>
    <td>Como usuario de CambiaZo, quiero ver las calificaciones representadas con estrellas, para entender fácilmente la reputación de otros usuarios.</td><td><b>Escenario 1: Ver calificación promedio como estrellas</b><br/>Given estoy en el perfil de otro usuario.<br/><br/>When reviso su información.<br/><br/>Then veo su calificación promedio representada con estrellas grandes.<br/><br/>
    <b>Escenario 2: Ver detalles de reseñas</b><br/>Given estoy explorando el perfil de un usuario.<br/><br/>When accedo a la sección de reseñas.<br/><br/>Then puedo ver comentarios y puntuaciones dejadas por otros usuarios.
    </td>
    <td>2</td>
  </tr>
  <tr> 
    <th>UA04</th>
    <td>Publicaciones destacadas</td>
    <td>Como usuario de CambiaZo, quiero ver ciertos artículos destacados en la página principal, para encontrar más fácilmente contenido relevante o popular.</td>
    <td><b>Escenario 1: Visualizar artículos destacados</b><br/>Given estoy navegando la vista general de productos.<br/><br/>When llego a la página principal.<br/><br/>Then veo una sección que muestra publicaciones destacadas con un diseño diferenciado.<br/><br/>
    <b>Escenario 2: Filtro de destacados</b><br/>Given estoy buscando artículos.<br/><br/>When aplico el filtro de "Destacados".<br/><br/>Then solo se muestran artículos marcados como destacados.
    </td>
    <td>2</td>
  </tr>
  <tr> 
    <th>UA05</th>
    <td>Compartir publicaciones mediante enlace</td>
    <td>Como usuario de CambiaZo, quiero poder compartir publicaciones mediante un enlace, para difundir fácilmente artículos de interés a otras personas.</td>
    <td><b>Escenario 1: Obtener enlace de publicación</b><br/>Given estoy viendo una publicación.<br/><br/>When hago clic en el botón “Compartir”.<br/><br/>Then el sistema genera un enlace accesible que puedo copiar y enviar.<br/><br/>
    <b>Escenario 2: Acceder a publicación compartida</b><br/>Given he recibido un enlace de una publicación.<br/><br/>When accedo al enlace desde un navegador.<br/><br/>Then visualizo la publicación en la plataforma sin necesidad de buscarla manualmente.
    </td>
    <td>5</td>
  </tr>
  <tr> 
      <th>UA06</th>
      <td>Compartir perfil por enlace</td>
      <td>Como usuario de CambiaZo, quiero poder compartir el perfil de otro usuario mediante un enlace, para recomendarlo fácilmente a otras personas.</td>
      <td><b>Escenario 1: Obtener enlace de perfil</b><br/>Given estoy viendo el perfil de un usuario.<br/><br/>When hago clic en "Compartir perfil".<br/><br/>Then el sistema me genera un enlace que puedo copiar y enviar.<br/><br/>
      <b>Escenario 2: Acceder a perfil compartido</b><br/>Given recibí un enlace al perfil de un usuario.<br/><br/>When hago clic en él.<br/><br/>Then puedo ver el perfil público del usuario compartido.
      </td>
      <td>1</td>
  </tr>
    <tr>
      <th>UA07</th>
      <td>Versiones multilingües</td>
      <td>Como usuario no hispanohablante, quiero usar Cambiazo en mi idioma (inglés o chino) para entender mejor todas las funcionalidades.</td>
      <td><b>Escenario 1: Cambiar idioma de la aplicación</b><br/>Given estoy en cualquier sección de la aplicación.<br/><br/>When accedo al menú de configuración.<br/><br/>Then puedo seleccionar entre español, inglés y chino.<br/>And toda la interfaz se traduce al idioma seleccionado.<br/><br/><b>Escenario 2: Contenido traducido</b><br/>Given he cambiado el idioma de la aplicación.<br/><br/>When navego por diferentes secciones.<br/><br/>Then todos los textos, botones y mensajes están en el idioma seleccionado.<br/>And las publicaciones de otros usuarios muestran opción de traducción automática.
      </td>
      <td>E07</td>
    </tr>
    <tr>
      <th>UA08</th>
      <td>Filtros de búsqueda avanzados</td>
      <td>Como usuario de Cambiazo, quiero filtrar las publicaciones por categoría, estado del objeto y ubicación para encontrar exactamente lo que busco.</td>
      <td><b>Escenario 1: Aplicar filtros de búsqueda</b><br/>Given estoy en la página principal de publicaciones.<br/><br/>When hago clic en "Filtros".<br/><br/>Then puedo seleccionar categoría (ropa, electrónicos, libros, etc.).<br/>And puedo filtrar por estado (nuevo, como nuevo, usado).<br/>And puedo establecer un radio de distancia desde mi ubicación.<br/><br/><b>Escenario 2: Búsqueda con múltiples filtros</b><br/>Given he aplicado varios filtros.<br/><br/>When hago clic en "Aplicar filtros".<br/><br/>Then veo solo las publicaciones que cumplen todos los criterios.<br/>And puedo guardar esta combinación de filtros como favorita.
      </td>
      <td>E08</td>
    </tr>
  </tbody>
</table>

### 8.3.2. To-Be Product Backlog

<table border="1" cellpadding="8" cellspacing="0" style="width: 100% !important; table-layout: fixed;">
  <thead>
    <tr>
      <th>#</th>
      <th>User Story ID</th>
      <th>Título</th>
      <th>Story Points (1/2/3/5/8)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>UA01</td>
      <td>Notificación por correo al recibir propuesta o acuerdo</td>
      <td>5</td>
    </tr>
    <tr>
      <td>2</td>
      <td>UA02</td>
      <td>Confirmación visual tras publicación o edición</td>
      <td>8</td>
    </tr>
    <tr>
      <td>3</td>
      <td>UA08</td>
      <td>Filtros de búsqueda avanzados</td>
      <td>3</td>
    </tr>
    <tr>
      <td>4</td>
      <td>UA03</td>
      <td>Visualización de calificaciones con estrellas</td>
      <td>5</td>
    </tr>
    <tr>
      <td>5</td>
      <td>UA06</td>
      <td>Compartir perfil por enlace</td>
      <td>3</td>
    </tr>
    <tr>
      <td>6</td>
      <td>UA04</td>
      <td>Publicaciones destacadas</td>
      <td>5</td>
    </tr>
    <tr>
      <td>7</td>
      <td>UA05</td>
      <td>Compartir publicaciones mediante enlace</td>
      <td>3</td>
    </tr>
    <tr>
      <td>8</td>
      <td>UA07</td>
      <td>Versiones multilingües</td>
      <td>8</td>
    </tr>
  </tbody>
</table>

<div style="page-break-after: always;"></div>

# Conclusiones

## Conclusiones y Recomendaciones

### Capítulo I – Introducción

Iniciamos nuestro proyecto con la formulación del experimento central: validar una hipótesis relacionada con una necesidad del mercado dentro del contexto de la Ingeniería de Software. Utilizamos el marco **Lean UX** como metodología estructurada para definir el problema de investigación, generando suposiciones basadas en observaciones previas y estableciendo hipótesis que guiaron el diseño experimental. El uso del *Lean UX Canvas* permitió al equipo definir variables clave, identificar factores y condiciones del entorno, y plantear objetivos de validación enfocados. Este enfoque estructurado facilitó la identificación de problemas reales del usuario, alineando el diseño del experimento con las necesidades del mercado y los objetivos de nuestra startup.

### Capítulo II – Requirements Elicitation & Analysis

En esta fase, ejecutamos un estudio cualitativo de necesidad utilizando **entrevistas semiestructuradas** y **observación directa**, métodos válidos dentro del diseño de experimentos exploratorios. El análisis competitivo complementó los datos, permitiéndonos identificar **variables independientes** (diferenciadores de mercado) y **dependientes** (percepción del usuario). Estos datos sirvieron para refinar nuestras hipótesis y establecer un plan experimental más sólido. La recolección ética de datos y la interpretación responsable de los mismos aseguraron la validez del experimento y la relevancia de los factores considerados, alineando nuestras decisiones con el impacto social y profesional de la ingeniería de software.

### Capítulo III – Requirements Specification

Definimos la arquitectura del producto como parte del diseño experimental de la intervención tecnológica. Se diseñaron **interfaces controladas** (landing page y app móvil) y se estableció una **arquitectura de software modular** para facilitar pruebas por componente e integración. La estructura basada en el dominio permitió establecer unidades de prueba aisladas, facilitando la medición del rendimiento, usabilidad y escalabilidad como variables dependientes. Este diseño controlado del entorno experimental garantiza **replicabilidad**, **trazabilidad de resultados** y **validez interna** en el análisis de la solución propuesta.

### Capítulo IV – Product Design

Durante esta etapa, se ejecutaron **sprints como ciclos de experimentación iterativa**, aplicando principios de diseño de experimentos en entornos controlados (desarrollo y staging). Cada sprint incluyó tareas definidas como **tratamientos** (features) con criterios de aceptación claramente establecidos (métricas de éxito). Se aplicaron pruebas automatizadas y evaluaciones funcionales, estableciendo **evidencia empírica** para la validación de nuestras hipótesis. La trazabilidad del código y la gestión de versiones aseguraron la consistencia de las condiciones del experimento, permitiendo juicios informados sobre el impacto de cada intervención.

### Capítulo V – Product Implementation, Validation & Deployment

Se desplegaron **versiones mínimas funcionales (MVP)** de la app y la landing page, evaluando su aceptación y funcionalidad mediante **métricas cuantitativas y cualitativas**: tasa de conversión, registros exitosos, tiempo de respuesta y feedback de usuarios. Este conjunto de datos constituyó la evidencia principal para validar (o refutar) las hipótesis del capítulo inicial. La interpretación responsable de estos resultados, con un enfoque ético y social, permitió **ajustes experimentales** y mejoras incrementales en el diseño. El control de variables externas y la consistencia del entorno de pruebas fortalecieron la **validez del experimento**, consolidando aprendizajes aplicables a contextos reales de la ingeniería de software.

### Capítulo VI – Product Verification & Validation

Durante esta etapa, se implementaron **baterías de pruebas automatizadas** para validar el comportamiento y la robustez del sistema. Se diseñaron **pruebas unitarias** sobre entidades clave del dominio, asegurando la corrección lógica y la integridad de las funciones básicas. A nivel de integración, se testearon flujos críticos entre módulos, evaluando la coherencia y consistencia de los datos. Se aplicó el enfoque de **Behavior-Driven Development (BDD)** para garantizar que los requisitos funcionales se reflejaran en escenarios de prueba comprensibles por todos los actores del proyecto. Las **pruebas de sistema** fueron ejecutadas en entornos controlados, reproduciendo situaciones reales de uso, lo cual permitió identificar posibles fallos en condiciones extremas o límites. Este proceso consolidó un marco de validación riguroso, fundamentado en evidencia empírica, que respalda la **calidad del producto**, fortalece la **validez externa** del experimento y permite una evaluación confiable de su desempeño en condiciones reales.

### Capítulo VII – DevOps Practices

Se implementaron **prácticas de integración, entrega y despliegue continuos** mediante un pipeline automatizado con GitHub Actions, asegurando un flujo de desarrollo ágil, confiable y reproducible. Este pipeline orquesta la construcción, prueba y despliegue del frontend (Netlify) y backend (Azure Web App), conectado a una base de datos en Azure MySQL. Durante la fase de **Continuous Integration**, se automatizó la compilación del código, ejecución de pruebas (unitarias con JUnit/Mockito, funcionales con Selenium, y de aceptación con Gherkin+Cucumber), validando cada cambio desde el commit hasta el pull request. Esto garantizó la estabilidad del sistema en todo momento. En la fase de **Continuous Delivery**, se configuraron entornos de previsualización en Netlify y Azure que replican condiciones de producción, permitiendo validar nuevas funcionalidades antes del merge definitivo. Esta estrategia facilitó un control riguroso sobre la calidad del software sin interrumpir el servicio. Finalmente, mediante **Continuous Deployment**, los cambios aprobados se desplegaron automáticamente en producción, manteniendo consistencia y trazabilidad. Herramientas como **Sentry** y **Azure Monitor** ofrecieron retroalimentación continua sobre errores, rendimiento y calidad del código, permitiendo una mejora constante basada en evidencia técnica. Esta infraestructura consolidó una cultura de DevOps enfocada en la **automatización**, **observabilidad** y **entregas incrementales de valor**.


### Capítulo VIII – Experiment-Driven Development

En el Capítulo VIII se consolidó un enfoque riguroso de desarrollo impulsado por la experimentación, estructurado en tres fases: planificación, diseño y ejecución. Se partió de un análisis del estado actual (*As-Is*) y se identificaron suposiciones, vacíos de conocimiento e hipótesis clave, las cuales se tradujeron en preguntas listas para probar mediante un backlog priorizado y *experiment cards*. Luego, se diseñaron experimentos con hipótesis comprobables, métricas relevantes, condiciones de prueba bien definidas, selección de métodos adecuados y un plan de seguimiento en plataformas web y móviles. Este diseño incorporó cálculos de escala y KPIs para garantizar la validez de los resultados. Finalmente, se ejecutaron experimentos con nuevas historias de usuario y un backlog ajustado, lo que permitió tomar decisiones informadas basadas en evidencia. Este proceso fortaleció la capacidad del equipo para aprender de forma estructurada, reducir riesgos e innovar de manera validada en contextos inciertos.


### Conclusión

La estructura metodológica del proyecto ha estado guiada por principios de **diseño experimental**, integrando hipótesis, validación empírica y análisis reflexivo, asegurando resultados replicables y relevantes. Este enfoque permitió al equipo emitir **juicios técnicos y éticos fundamentados**, reconociendo el impacto de nuestras decisiones en entornos sociales, económicos y tecnológicos diversos. Cada etapa del proyecto fue una oportunidad para ejercitar la **capacidad crítica, la responsabilidad profesional** y la **conciencia del entorno**, logrando así una solución **técnicamente sólida y socialmente pertinente**, en línea con el **Student Outcome 4 del marco ABET**.


## Video About the Product

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-V/Videos/about-the-product.png?raw=true">
 </div>


Enlace: [About the Product](https://youtu.be/2fL6Q_v7sGk)

<div style="page-break-after: always;"></div>

# Bibliografía
  <br>

+ Conventional Commits. (2023). *A specification for adding human and machine readable meaning to commit messages*. Conventional Commits. https://www.conventionalcommits.org/en/v1.0.0/  <br><br>

+ CPI Research. (2022). *Perú: Población 2022*. CPI. https://cpi.pe/images/upload/paginaweb/archivo/23/poblacion%202022.pdf <br><br>

+ Georgiou, M. (2024). *The importance of mobile app maintenance cost*. Imaginovation. https://imaginovation.net/blog/importance-mobile-app-maintenance-cost/ <br><br>

+ Huarachi-Coila, L. (2022). Mercado de trueque y seguridad alimentaria en los distritos de Acora e Ilave de Puno-Perú: periodo 2015-2017. *Semestre Económico, 11*(1), 28–43. https://doi.org/10.26867/se.2022.v11i1.126 <br><br>

+ Indeed. (2024). *How to write SMART goals*. Indeed. https://www.indeed.com/career-advice/career-development/how-to-write-smart-goals <br><br>

+ Kruse-Andersen, P. K. (2023). Directed technical change, environmental sustainability, and population growth. *Journal of Environmental Economics and Management, 122*, 102885. https://doi.org/10.1016/j.jeem.2023.102885 <br><br>

+ Liu, S., & Zhong, C. (2023). Green growth: Intellectual property conflicts and prospects in the extraction of natural resources for sustainable development. *Resources Policy, 80*, 104588. https://doi.org/10.1016/j.resourpol.2023.104588 <br><br>

+ Madaan, G., Singh, A., Mittal, A., & Shahare, P. (2024). Reduce, reuse, recycle: Circular economic principles, sustainability and entrepreneurship in developing ecosystems. *Journal of Small Business and Enterprise Development, ahead-of-print*. https://doi.org/10.1108/JSBED-01-2023-0009 <br><br>

+ Morseletto, P. (2023). Sometimes linear, sometimes circular: States of the economy and transitions to the future. *Journal of Cleaner Production, 390*, 136138. https://doi.org/10.1016/j.jclepro.2023.136138 <br><br>

+ Pivotal Tracker. (2024). *Quick start guide*. Pivotal Tracker. https://www.pivotaltracker.com/help/articles/quick_start/ <br><br>

+ Wang, F., Nan, N., & Zhao, J. (2024). Configuring mobile app update strategy for growth: An empirical analysis of a landscape search model. *Industrial Management & Data Systems, 124*(3), 1155-1178. https://doi.org/10.1108/IMDS-03-2023-0181 <br><br>

+ Zhao, S., Chen, S. H., Wang, F., Wei, Z. L., Zhong, J. C., & Liang, J. B. (2024). A large-scale mobile traffic dataset for mobile application identification. *Computer Journal, 67*(4), 1501-1513. https://doi.org/10.1093/comjnl/bxad076 <br><br>


<div style="page-break-after: always;"></div>

# Anexos

+ Landing Page: [Ver Landing Page](https://cambiazo-site.netlify.app/)<br><br>

+ Aplicación Web: [Ver Aplicación Web](https://cambia-zo.netlify.app/home)<br><br>

+ Backend: [Ver Backend](https://cambiazo-backend-bjdkd7hhgqa8gygw.eastus-01.azurewebsites.net/swagger-ui/index.html#)<br><br>

+ Repositorio GitHub de la Organización: [Ver Organización](https://github.com/TechZo-1ASI0732-4453)<br><br>

+ Repositorio GitHub del Informe: [Ver Repositorio](https://github.com/TechZo-1ASI0732-4453/report)<br><br>

+ Repositorio GitHub del Backend: [Ver Repositorio](https://github.com/TechZo-1ASI0732-4453/Backend)<br><br>

+ Repositorio GitHub de la Landing Page: [Ver Repositorio](https://github.com/TechZo-1ASI0732-4453/Landing-Page)<br><br>

+ Repositorio GitHub de la Aplicación Móvil: [Ver Repositorio](https://github.com/TechZo-1ASI0732-4453/CambiazoApp)<br><br>

+ Repositorio GitHub de los Acceptance Test: [Ver Repositorio](https://github.com/TechZo-1ASI0732-4453/Acceptance-Test)<br><br>

## Needfinding Interviews

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-II/Interviews/sebastianlobato_interview.png?raw=true">
 </div>


Enlace: [Needfinding](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214059_upc_edu_pe/ETvVZXVN-x9FkEDkb_E9cpUBbl0UYgt8J7QA3XiVn1SBPA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=IEi8AE)


## Prototype Navigation

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/main/Resources/Chapter-III/Mobile-Applications-Prototyping/video-prototype.PNG?raw=true">
 </div>


Enlace: [Prototype Navigation](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214059_upc_edu_pe/ETDFKlDociZGsi_Dgr-d7HkBE3-AouvlOTfvXGrnDqsphg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=PWZXDX)


## Validation Interview

  <div align="center">
    <img src="https://github.com/TechZo-1ASI0732-4453/Report/blob/tb2/Resources/Chapter-VI/Validation-Interviews/erick-maycol-evidence.png?raw=true">
 </div>


Enlace: [Validation Interview](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216282_upc_edu_pe/EcfVlaMcmQVFrLyXhwBVHIsBIbIcWGO9svsJezsnlS6GuQ?e=RoU7jY&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

