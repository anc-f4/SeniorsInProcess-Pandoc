```{=typst}
#align(center)[
```

![](../SeniorsInProcess-Pandoc/assets/UPC_logo_transparente.png){ width=130px }

# Universidad Peruana de Ciencias Aplicadas

### 1ASI030 - Aplicaciones Web

NRC: 8155

\

# Informe del Trabajo Final

Docente:

**Velasquez Nuñez, Angel Augusto**

Equipo:

**SeniorsInProcess**

Proyecto:

**Prothia**

\

**Integrantes**

Codigo | Apellidos y Nombres
---|---
U202421823 | Dextre Flores, Leonardo Felix
U20231E492 | Checa Burga, Oscar Diego
U202421065 | Salcedo Correa, Carlos Mathhew
U20241I469 | Patricio Farias, Ana Camila
U202417417 | Barrenechea Bustamante, Rafael

\

**Período 202620**

**Septiembre 2026**

```{=typst}
]
```
```{=typst}
#pagebreak()
#set table(
  columns: (1fr, 2fr, 3fr, 6fr),
  stroke: 0.5pt + luma(150),
  inset: 6pt
)
```

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
| :--- | :--- | :--- | :--- |
| 2.0 | 2026/09/30 | Ana Camila Patricio Farias | Aplicación de correcciones metodológicas en los Capítulos I, II y III basadas en la retroalimentación docente. |
| 2.1 | 2026/10/01 | Leonardo Felix Dextre Flores | Aplicación de correcciones metodológicas en el Capítulo IV basadas en la retroalimentación docente. |
| 2.2 | 2026/10/04 | Rafael Barrenechea Bustamante | Adición de las secciones 5.2.2.1 a 5.2.2.3 correspondientes a la fase de planificación del Sprint 2. |
| 2.3 | 2026/10/05 | Oscar Diego Checa Burga | Integración de las secciones 5.2.2.4 a 5.2.2.7 con las evidencias técnicas del Sprint 2. |
| 2.4 | 2026/10/06 | Carlos Matthew Salcedo | Adición de la sección 5.2.2.8 y actualización integral de las Conclusiones, Bibliografía y Anexos para reflejar los resultados de la segunda entrega. |
| 1.0 | 2026/09/01 | Oscar Diego Checa Burga | Creación de la estructura base del informe. Integración de Carátula, Student Outcome y Capítulo I (Introducción). |
| 1.1 | 2026/09/03 | Ana Camila Patricio Farias | Adición del Capítulo II y Capítulo III, incluyendo entrevistas y Product Backlog. |
| 1.2 | 2026/09/06 | Leonardo Felix Dextre Flores | Integración del Capítulo IV. Se añaden wireframes. |
| 1.3 | 2026/09/08 | Carlos Matthew Salcedo | Adición de los mock ups y landing page. |
| 1.4 | 2026/09/15 | Rafael Barrenechea Bustamante | Adición de la sección Software Configuration Management, Services & Applications Implementation con las evidencias del Sprint 1. |
| 1.5 | 2026/09/17 | Ana Camila Patricio Farias | Adición de las conclusiones, bibliografía y anexos. |


```{=typst}
#pagebreak()
```


# Project Report Collaboration Insights

El Project Report del equipo se encuentra alojado en el repositorio de informes dentro de la organización de GitHub del equipo:

- **Organización de GitHub:** https://github.com/upc-pre-202620-1asi0730-8155-SeniorsIP
- **Repositorio del Project Report:** https://github.com/upc-pre-202620-1asi0730-8155-SeniorsIP/SeniorsInProcess-Prothia-Report

El informe se elaboró de manera colaborativa utilizando Git y GitHub como plataforma de control de versiones. Cada integrante trabajó las secciones asignadas y registró sus aportes mediante commits al repositorio del informe, lo cual queda evidenciado en los analíticos de colaboración de GitHub y en el Registro de Versiones del Informe. A continuación, se describe el desarrollo de las actividades por cada entrega.

![](../SeniorsInProcess-Pandoc/assets/collaboration_insights.png){ width=100% }


```{=typst}
#pagebreak()
```

# Tabla de Contenidos

## [Capítulo I: Introducción](01-Chapter-1-Introducción.md#capítulo-i-introducción)

- [1.1. Startup Profile](01-Chapter-1-Introducción.md#11-startup-profile)
  - [1.1.1. Descripción de la Startup](01-Chapter-1-Introducción.md#111-descripcion-del-startup)
  - [1.1.2. Perfiles de integrantes del equipo](01-Chapter-1-Introducción.md#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](01-Chapter-1-Introducción.md#12-solution-profile)
  - [1.2.1. Antecedentes y problemática](01-Chapter-1-Introducción.md#121-antecedentes-y-problemática)
  - [1.2.2. Lean UX Process](01-Chapter-1-Introducción.md#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](01-Chapter-1-Introducción.md#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](01-Chapter-1-Introducción.md#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](01-Chapter-1-Introducción.md#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](01-Chapter-1-Introducción.md#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](01-Chapter-1-Introducción.md#13-segmentos-objetivos)

---

## [Capítulo II: Requirements Elicitation & Analysis](02-Chapter-2-Requirements-Elicitation-Analysis.md#capítulo-ii-requirements-elicitation--analysis)

- [2.1. Competidores](02-Chapter-2-Requirements-Elicitation-Analysis.md#21-competidores)
  - [2.1.1. Análisis competitivo](02-Chapter-2-Requirements-Elicitation-Analysis.md#211-analisis-competitivo)
  - [2.1.2. Estrategias y tácticas frente a competidores](02-Chapter-2-Requirements-Elicitation-Analysis.md#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](02-Chapter-2-Requirements-Elicitation-Analysis.md#22-entrevistas)
  - [2.2.1. Diseño de entrevistas](02-Chapter-2-Requirements-Elicitation-Analysis.md#221-diseño-de-entrevistas)
  - [2.2.2. Registro de entrevistas](02-Chapter-2-Requirements-Elicitation-Analysis.md#222-registro-de-entrevistas)
  - [2.2.3. Análisis de entrevistas](02-Chapter-2-Requirements-Elicitation-Analysis.md#223-análisis-de-entrevistas)
- [2.3. Needfinding](02-Chapter-2-Requirements-Elicitation-Analysis.md#23-needfinding)
  - [2.3.1. User Personas](02-Chapter-2-Requirements-Elicitation-Analysis.md#231-user-personas)
  - [2.3.2. User Task Matrix](02-Chapter-2-Requirements-Elicitation-Analysis.md#232-user-task-matrix)
  - [2.3.3. User Journey Mapping](02-Chapter-2-Requirements-Elicitation-Analysis.md#233-user-journey-mapping)
  - [2.3.4. Empathy Mapping](02-Chapter-2-Requirements-Elicitation-Analysis.md#234-empathy-mapping)
- [2.4. Big Picture Event Storming](02-Chapter-2-Requirements-Elicitation-Analysis.md#24-big-picture-EventStorming)
- [2.5. Ubiquitous Language](02-Chapter-2-Requirements-Elicitation-Analysis.md#25-ubiquitous-language)

---

## [Capítulo III: Requirements Specification](03-Chapter-3-Requirements-Specification.md#capítulo-iii-requirements-specification)

- [3.1. User Stories](03-Chapter-3-Requirements-Specification.md#31-user-stories)
- [3.2. Impact Mapping](03-Chapter-3-Requirements-Specification.md#32-impact-mapping)
- [3.3. Product Backlog](03-Chapter-3-Requirements-Specification.md#33-product-backlog)

---

## [Capítulo IV: Product Design](04-Chapter-4-Product-Design.md#capítulo-iv-product-design)

- [4.1. Style Guidelines](04-Chapter-4-Product-Design.md#41-style-guidelines)
  - [4.1.1. General Style Guidelines](04-Chapter-4-Product-Design.md#411-general-style-guidelines)
  - [4.1.2. Web Style Guidelines](04-Chapter-4-Product-Design.md#412-web-style-guidelines)
- [4.2. Information Architecture](04-Chapter-4-Product-Design.md#42-information-architecture)
  - [4.2.1. Organization Systems](04-Chapter-4-Product-Design.md#421-organization-systems)
  - [4.2.2. Labeling Systems](04-Chapter-4-Product-Design.md#422-labeling-systems)
  - [4.2.3. SEO Tags and Meta Tags](04-Chapter-4-Product-Design.md#423-seo-tags-and-meta-tags)
  - [4.2.4. Searching Systems](04-Chapter-4-Product-Design.md#424-searching-systems)
  - [4.2.5. Navigation Systems](04-Chapter-4-Product-Design.md#425-navigation-systems)
- [4.3. Landing Page UI Design](04-Chapter-4-Product-Design.md#43-landing-page-ui-design)
  - [4.3.1. Landing Page Wireframe](04-Chapter-4-Product-Design.md#431-landing-page-wireframe)
  - [4.3.2. Landing Page Mock-up](04-Chapter-4-Product-Design.md#432-landing-page-mock-up)
- [4.4. Web Applications UX/UI Design](04-Chapter-4-Product-Design.md#44-web-applications-uxui-design)
  - [4.4.1. Web Applications Wireframes](04-Chapter-4-Product-Design.md#441-web-applications-wireframes)
  - [4.4.2. Web Applications Wireflow Diagrams](04-Chapter-4-Product-Design.md#442-web-applications-wireflow-diagrams)
  - [4.4.3. Web Applications Mock-ups](04-Chapter-4-Product-Design.md#443-web-applications-mock-ups)
  - [4.4.4. Web Applications User Flow Diagrams](04-Chapter-4-Product-Design.md#444-web-applications-user-flow-diagrams)
- [4.5. Web Applications Prototyping](04-Chapter-4-Product-Design.md#45-web-applications-prototyping)
- [4.6. Domain-Driven Software Architecture](04-Chapter-4-Product-Design.md#46-domain-driven-software-architecture)
  - [4.6.1. Design-Level Event Storming.](04-Chapter-4-Product-Design.md#461-design-level-event-storming.)
  - [4.6.2. Software Architecture Context Diagram](04-Chapter-4-Product-Design.md#462-software-architecture-context-diagram)
  - [4.6.3. Software Architecture Container Diagrams](04-Chapter-4-Product-Design.md#463-software-architecture-container-diagrams)
  - [4.6.4. Software Architecture Components Diagrams](04-Chapter-4-Product-Design.md#464-software-architecture-components-diagrams)
- [4.7. Software Object-Oriented Design](04-Chapter-4-Product-Design.md#47-software-object-oriented-design)
  - [4.7.1. Class Diagrams](04-Chapter-4-Product-Design.md#471-class-diagrams)
- [4.8. Database Design](04-Chapter-4-Product-Design.md#48-database-design)
  - [4.8.1. Database Diagram](04-Chapter-4-Product-Design.md#481-database-diagram)

---

## [Capítulo V: Product Implementation, Validation & Deployment](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#capítulo-v-product-implementation-validation--deployment)

- [5.1. Software Configuration Management](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#51-software-configuration-management)
  - [5.1.1. Software Development Environment Configuration](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#511-software-development-environment-configuration)
  - [5.1.2. Source Code Management](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#512-source-code-management)
  - [5.1.3. Source Code Style Guide & Conventions](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#513-source-code-style-guide--conventions)
  - [5.1.4. Software Deployment Configuration](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#514-software-deployment-configuration)
- [5.2. Landing Page, Services & Applications Implementation](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#52-landing-page-services--applications-implementation)
  - [5.2.1. Sprint 1](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#521-sprint-1)
    - [5.2.1.1. Sprint Planning 1](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5211-sprint-planning-1)
    - [5.2.1.2. Aspect Leaders and Collaborators](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5212-aspect-leaders-and-collaborators)
    - [5.2.1.3. Sprint Backlog 1](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5213-sprint-backlog-1)
    - [5.2.1.4. Development Evidence for Sprint Review](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5214-development-evidence-for-sprint-review)
    - [5.2.1.5. Execution Evidence for Sprint Review](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5215-execution-evidence-for-sprint-review)
    - [5.2.1.6. Services Documentation Evidence for Sprint Review](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5216-services-documentation-evidence-for-sprint-review)
    - [5.2.1.7. Software Deployment Evidence for Sprint Review](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5217-software-deployment-evidence-for-sprint-review)
    - [5.2.1.8. Team Collaboration Insights during Sprint](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5218-team-collaboration-insights-during-sprint)
  - [5.2.2. Sprint 2](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#522-sprint-2)
    - [5.2.2.1. Sprint Planning 2](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5221-sprint-planning-2)
    - [5.2.2.2. Aspect Leaders and Collaborators](#5222-aspect-leaders-and-collaborators)
    - [5.2.2.3. Sprint Backlog 2](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5223-sprint-backlog-2)
    - [5.2.2.4. Development Evidence for Sprint Review](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5224-development-evidence-for-sprint-review)
    - [5.2.2.5. Execution Evidence for Sprint Review](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5225-execution-evidence-for-sprint-review)
    - [5.2.2.6. Services Documentation Evidence for Sprint Review](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5226-services-documentation-evidence-for-sprint-review)
    - [5.2.2.7. Software Deployment Evidence for Sprint Review](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5227-software-deployment-evidence-for-sprint-review)
    - [5.2.2.8. Team Collaboration Insights during Sprint](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5228-team-collaboration-insights-during-sprint)
  - [5.2.3. Sprint 3](#523-sprint-3)
    - [5.2.3.1. Sprint Planning 3](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5231-sprint-planning-3)
    - [5.2.3.2. Aspect Leaders and Collaborators](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5232-aspect-leaders-and-collaborators)
    - [5.2.3.3. Sprint Backlog 3](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5233-sprint-backlog-3)
    - [5.2.3.4. Development Evidence for Sprint Review](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5234-development-evidence-for-sprint-review)
    - [5.2.3.5. Execution Evidence for Sprint Review](#5235-execution-evidence-for-sprint-review)
    - [5.2.3.6. Services Documentation Evidence for Sprint Review](#5236-services-documentation-evidence-for-sprint-review)
    - [5.2.3.7. Software Deployment Evidence for Sprint Review](#5237-software-deployment-evidence-for-sprint-review)
    - [5.2.3.8. Team Collaboration Insights during Sprint](#5238-team-collaboration-insights-during-sprint)
  - [5.2.4. Sprint 4](#524-sprint-4)
    - [5.2.4.1. Sprint Planning 4](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5241-sprint-planning-4)
    - [5.2.4.2. Aspect Leaders and Collaborators](#5242-aspect-leaders-and-collaborators)
    - [5.2.4.3. Sprint Backlog 4](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5243-sprint-backlog-4)
    - [5.2.4.4. Development Evidence for Sprint Review](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5244-development-evidence-for-sprint-review)
    - [5.2.4.5. Execution Evidence for Sprint Review](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5245-execution-evidence-for-sprint-review)
    - [5.2.4.6. Services Documentation Evidence for Sprint Review](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5246-services-documentation-evidence-for-sprint-review)
    - [5.2.4.7. Software Deployment Evidence for Sprint Review](#5247-software-deployment-evidence-for-sprint-review)
    - [5.2.4.8. Team Collaboration Insights during Sprint](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#5248-team-collaboration-insights-during-sprint)
- [5.3. Validation Interviews](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#53-validation-interviews)
  - [5.3.1. Diseño de entrevistas](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#531-diseño-de-entrevistas)
  - [5.3.2. Registro de entrevistas](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#532-registro-de-entrevistas)
  - [5.3.3. Evaluaciones según heurísticas](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#533-evaluaciones-según-heurísticas)
- [5.4. Video About-the-Product](05-Chapter-5-Product-Implementation%2C-Validation-%26-Deployment.md#54-video-about-the-product)



```{=typst}
#pagebreak()
#set text(size: 8.5pt)
#set table(
  columns: (2.2fr, 5fr, 2.8fr),
  stroke: 0.5pt + luma(180),
  inset: (x: 6pt, y: 7pt)
)
```

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 5**

**Criterio**: *La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.*

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 5.

# Student Outcome: Trabajo en Equipo

| Criterio específico | Acciones realizadas | Conclusiones |
| :--- | :--- | :--- |
| **Trabaja en equipo para proporcionar liderazgo en forma conjunta** | **Patricio Farias, Ana Camila**\ \ **AVI:** Lideró el levantamiento inicial de requisitos funcionales, la estructura base del User Story Mapping y la redacción de los primeros escenarios de valor del negocio.\ \ **TB1:** Lideró la actualización integral de la sección Needfinding y la adecuación de las User Stories incorporando las correcciones recibidas. Dirigió el refinamiento del Product Backlog y co-lideró la actualización del Design-Level / Big Picture EventStorming en colaboración con Carlos Salcedo y Leonardo Dextre. Asimismo, asumió el liderazgo del desarrollo frontend en la aplicación web para los bounded contexts de Communication, Locales y Prescription.\ \ --- \ \ **Dextre Flores, Leonardo Felix**\ \ **AVI:** Coordinó la visión arquitectural inicial y guió las pautas preliminares de modelado de dominio de la solución web.\ \ **TB1:** Lideró la formulación y refinamiento del Big Picture EventStorming en conjunto con Ana Camila y Carlos Salcedo. Dirigió las correcciones y mejoras profundas en el Capítulo IV (Product Design: diseño de arquitectura de software) y lideró la implementación del frontend en la aplicación web para los bounded contexts de Billing y Workshop.\ \ --- \ \ **Checa Burga, Oscar Diego**\ \ **AVI:** Coordinó la redacción del contexto del problema, los antecedentes y el alcance inicial en el Capítulo I.\ \ **TB1:** Lideró la revisión y subsanación de observaciones en el Capítulo I (Introduction), perfeccionando los Lean UX Assumptions, problem statements y objetivos de la solución. En el desarrollo de la aplicación web, lideró y codificó el módulo transversal Shared, así como los bounded contexts de Monitoring y Patients.\ \ --- \ \ **Salcedo Correa, Carlos Matthew**\ \ **AVI:** Facilitó la estructura de los artefactos ágiles iniciales y colaboró en el mapeo de procesos clave de negocio.\ \ **TB1:** Co-lideró la sesión de EventStorming para el descubrimiento y alineamiento de eventos y comandos del sistema junto con Ana Camila y Leonardo Dextre. Asumió la dirección del desarrollo e integración en la plataforma web de los bounded contexts de Analytics y Patient-Portal.\ \ --- \ \ **Barrenechea Bustamante, Rafael**\ \ **AVI:** Supervisó el modelado conceptual y la elaboración de los primeros diagramas estáticos y de contenedores.\ \ **TB1:** Lideró de forma integral el área de diagramas de arquitectura y software del proyecto, realizando las actualizaciones y correcciones observadas en el Sprint 1 e incorporando los diagramas pertinentes para el Sprint 2. En el desarrollo de la aplicación web, asumió y lideró la implementación técnica de los bounded contexts de IAM (Identity and Access Management) y Option. | A través de la iteración hacia el hito TB1 (Semana 7), el equipo consolidó una estructura de liderazgo distribuido y balanceado. Cada integrante asumió la titularidad técnica de bounded contexts y artefactos clave de diseño y especificación, logrando que las decisiones de modelado de dominio (EventStorming), arquitectura y desarrollo se tomen de forma colegiada, técnica y orientada a los objetivos del negocio. |
| **Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.** | **Patricio Farias, Ana Camila**\ \ **AVI:** Fomentó la participación equitativa de todos los miembros durante el proceso de investigación y entrevistas.\ \ **TB1:** Promovió sesiones de trabajo conjunto para alinear los requisitos corregidos con las tareas del Sprint 2. Participó en la planificación de las metas del sprint e integró activamente los componentes de sus bounded contexts (Communication, Locales, Prescription) interactuando continuamente con las interfaces y componentes del resto del equipo durante las tres semanas de desarrollo.\ \ --- \ \ **Dextre Flores, Leonardo Felix**\ \ **AVI:** Facilitó la discusión constructiva para superar bloqueos iniciales en la definición de perfiles de usuario.\ \ **TB1:** Fomentó un ambiente de apoyo mutuo en las sesiones sincrónicas semanales de desarrollo web, resolviendo dudas de interconexión técnica y asegurando la sincronización fluida de los bounded contexts de Billing y Workshop con el flujo global de la aplicación.\ \ --- \ \ **Checa Burga, Oscar Diego**\ \ **AV1:** Participó proactivamente en la asignación transparente y equitativa de tareas de documentación.\ \ **TB1:** Mantuvo una presencia activa y colaborativa en todas las reuniones de coordinación a lo largo de las tres semanas, asegurando que el módulo transversal Shared proveyera componentes reutilizables y estandarizados para el beneficio del trabajo de todos sus compañeros.\ \ --- \ \ **Salcedo Correa, Carlos Matthew**\ \ **AV1:** Impulsó acuerdos de consenso en la estimación de tiempos y puntos de historia en el backlog.\ \ **TB1:** Contribuyó al logro de las metas del Sprint 2 cumpliendo con las entregas asignadas dentro de los plazos establecidos y colaborando abiertamente durante la definición del EventStorming, facilitando la integración de Analytics y Patient-Portal con los demás servicios de la aplicación.\ \ --- \ \ **Barrenechea Bustamante, Rafael**\ \ **AVI:** Aportó alternativas de solución durante las sesiones de revisión de diseño arquitectural y las c4 model.\ \ **TB1:** Participó de forma constante y puntual en las sesiones de trabajo y reuniones de seguimiento realizadas durante las tres semanas. Coordinó activamente con el equipo para aclarar dudas sobre los permisos y autenticación gestionados en IAM, manteniendo sincronizados los diagramas de diseño con la implementación real del software. | Durante las 3 semanas de desarrollo orientadas a TB1 (Sprint 2), el equipo mantuvo una comunicación abierta, transparente y continua mediante reuniones virtuales periódicas. Se logró un entorno inclusivo donde se planificaron las metas, se resolvieron dependencias entre los bounded contexts y se corrigieron observaciones de forma colaborativa, cumpliendo satisfactoriamente los objetivos y entregables exigidos para la semana 7. |

```{=typst}
#set text(size: 11pt)
```
```{=typst}
#pagebreak()
```

# Capítulo I: Introducción

## 1.1 Startup Profile

### 1.1.1 Descripción de la Startup

Somos una startup peruana denominada **SeniorsInProcess**, creada por estudiantes de la carrera de Ingeniería de Software de la Universidad Peruana de Ciencias Aplicadas (UPC), cuyo objetivo principal es mejorar el monitoreo y seguimiento de la rehabilitación de pacientes amputados mediante el uso de tecnología y análisis de datos biomecánicos.

Nuestra misión es reducir la brecha de comunicación e información entre los pacientes amputados, las clínicas de rehabilitación y los centros ortopédicos, facilitando un proceso de adaptación a la prótesis más seguro, personalizado y basado en datos. Buscamos que los profesionales de la salud puedan conocer cómo los pacientes utilizan sus prótesis en su vida cotidiana y puedan realizar un seguimiento oportuno de su evolución fuera de las instalaciones de la clínica.

Para cumplir con este propósito, hemos desarrollado una plataforma web de monitoreo y seguimiento de rehabilitación que permite recopilar datos biomecánicos y de uso de la prótesis en tiempo real. La información obtenida es procesada y presentada mediante la plataforma web a los diferentes actores involucrados, permitiendo a las clínicas supervisar el progreso del paciente y realizar un seguimiento más eficiente de los ejercicios de rehabilitación.

Asimismo, la solución permite la participación de los centros ortopédicos, brindándoles acceso a información relacionada con el uso y mantenimiento de las prótesis. De esta manera, Prothia busca integrar en una misma plataforma a los principales actores del proceso de rehabilitación, facilitando el intercambio de información y contribuyendo a una mejor adaptación del paciente a su prótesis.

El modelo de negocio de SeniorsInProcess se basa principalmente en una suscripción anual dirigida a las clínicas de rehabilitación, mediante la cual estas instituciones obtienen acceso a la plataforma y pueden proporcionar su uso como parte del tratamiento de sus pacientes amputados. Por otro lado, a los centros ortopédicos se les ofrece una licencia de software que les permite utilizar la plataforma para la gestión de las prótesis, así como acceder a información relacionada con su uso y necesidades de mantenimiento.

De esta manera, SeniorsInProcess busca generar valor para cada uno de sus segmentos objetivo: pacientes amputados, clínicas de rehabilitación y centros ortopédicos, proporcionando información que facilite la toma de decisiones, mejore el seguimiento de la rehabilitación y permita una gestión más eficiente de las prótesis.

### 1.1.2. Perfiles de integrantes del equipo

```{=typst}
#set table(
  columns: (1fr, 3.2fr),
  stroke: 0.5pt + luma(180),
  inset: 7pt
)
```

| **Campo** | **Detalle** |
| :--- | :--- |
| **Integrante** | **Ana Camila Patricio Farias** |
| **Código del Estudiante** | u20241i469 |
| **Carrera** | Ingeniería de Software |
| **Descripción** | Mi nombre es Camila Patricio. Tengo 20 años, soy estudiante de Ingeniería de Software y considero que mis principales fortalezas son la responsabilidad, el compromiso y la disposición para aprender constantemente. Puedo aportar a mi grupo habilidades en programación, análisis de problemas y búsqueda de soluciones creativas. Además, me caracterizo por trabajar en equipo de manera colaborativa y organizada. Mi propósito es aportar mis conocimientos y esfuerzo para que logremos juntos los objetivos de nuestro proyecto. |
| **Foto** | ![](../SeniorsInProcess-Pandoc/assets/AnaCamila.png){ width=130px } |

\

| **Campo** | **Detalle** |
| :--- | :--- |
| **Integrante** | **Oscar Diego Checa Burga** |
| **Código del Estudiante** | U20231E492 |
| **Carrera** | Ingeniería de Software |
| **Descripción** | Mi nombre es Oscar Diego Checa Burga con código de alumno u20231e492. Soy estudiante de la carrera de ingeniería de software de 5to ciclo, interesado en el desarrollo de soluciones tecnológicas. Destaco por mi trabajo en equipo y comunicación constante. Tengo conocimiento en base de datos, desarrollo de aplicaciones y programación. Me gusta ir adaptándome a las nuevas tecnologías y aprender de estas, para poder desarrollar más en el ámbito profesional. |
| **Foto** | ![](../SeniorsInProcess-Pandoc/assets/OscarCheca.jpg){ width=130px } |

\

| **Campo** | **Detalle** |
| :--- | :--- |
| **Integrante** | **Leonardo Felix Dextre Flores** |
| **Código del Estudiante** | U202421823 |
| **Carrera** | Ingeniería de Software |
| **Descripción** | Soy Leonardo Dextre, tengo 23 años, actualmente estoy cursando el cuarto ciclo de mi carrera ingeniería de software en la UPC. Entre mis habilidades más destacadas es saber un poco de programación especialmente en C++ y un poco en Python. Además, tengo básico conocimiento en programas de Microsoft como el Excel. Mis pasatiempos son ver películas y jugar videojuegos. Mi objetivo con el curso es aprender más cosas acerca de mi carrera y poder aplicarlo en mi futuro laboral como profesional. |
| **Foto** | ![](../SeniorsInProcess-Pandoc/assets/LeonardoDextre.png){ width=130px } |

\

| **Campo** | **Detalle** |
| :--- | :--- |
| **Integrante** | **Carlos Mathhew Salcedo Correa** |
| **Código del Estudiante** | U202421065 |
| **Carrera** | Ingeniería de Software |
| **Descripción** | Soy Carlos Salcedo, tengo 18 años y actualmente curso el cuarto ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Cuento con conocimientos de nivel básico a intermedio en el lenguaje de programación C++, así como habilidades básicas en diseño. Además, tengo afinidad por el arte, especialmente el dibujo, y un fuerte interés por la música. Me considero una persona comprometida, responsable y con disposición constante para aprender. Mi objetivo en este curso es profundizar en los temas relacionados con mi carrera, fortalecer mis habilidades y prepararme para aplicarlas de manera efectiva en mi futuro profesional. |
| **Foto** | ![](../SeniorsInProcess-Pandoc/assets/CarlosSalcedo.png){ width=130px } |

\

| **Campo** | **Detalle** |
| :--- | :--- |
| **Integrante** | **Rafael Andre Barrenechea Bustamante** |
| **Código del Estudiante** | u202417417 |
| **Carrera** | Ingeniería de Software |
| **Descripción** | Soy Rafael André Barrenechea Bustamante, estudiante del quinto ciclo de la carrera de Ingeniería de Software. Una de mis principales cualidades es la capacidad para diseñar experiencias de usuario intuitivas y desarrollar componentes tecnológicos adaptados a las necesidades del proyecto. En el equipo, contribuiré con mis conocimientos en tecnologías como C++, Python y TypeScript, así como en el prototipado de interfaces, trabajando eficientemente para cumplir con todos los objetivos que se demanden. |
| **Foto** | ![](../SeniorsInProcess-Pandoc/assets/RafaelBarrenechea.png){ width=130px } |

\

### 1.2.1 Antecedentes y Problemática

**What / ¿QUÉ?**  
Se presenta una falta de monitoreo y seguimiento continuo durante el proceso de rehabilitación de pacientes amputados que utilizan prótesis. Una vez que el paciente recibe su prótesis, gran parte del proceso de adaptación y realización de ejercicios ocurre fuera de la clínica, lo que dificulta que los profesionales puedan conocer cómo utiliza la prótesis en su vida cotidiana, si realiza correctamente los ejercicios indicados o si presenta posturas y movimientos inadecuados.

**When / ¿CUÁNDO?**  
El problema se manifiesta principalmente después de que el paciente recibe la prótesis y continúa con su proceso de rehabilitación en el hogar. Durante este periodo, los profesionales de la clínica tienen una visibilidad limitada sobre las actividades que realiza el paciente fuera de las sesiones presenciales, dificultando la identificación oportuna de problemas durante su adaptación.

**Where / ¿DÓNDE?**  
La problemática se presenta principalmente en el entorno doméstico del paciente, donde se desarrolla una parte importante de la adaptación y rehabilitación con la prótesis. También involucra a las clínicas de rehabilitación y centros ortopédicos, debido a que estos actores necesitan información sobre el progreso, uso y estado de la prótesis para brindar un mejor seguimiento y servicio.

**Who / ¿QUIÉN?**  
Afecta principalmente a los pacientes amputados que utilizan una prótesis y necesitan realizar ejercicios y actividades de adaptación fuera de la clínica. También impacta a los profesionales de las clínicas de rehabilitación, quienes requieren información sobre el desempeño del paciente para realizar un seguimiento adecuado, y a los centros ortopédicos, que necesitan conocer el uso y comportamiento de las prótesis para facilitar su mantenimiento y gestión.

**Why / ¿POR QUÉ?**  
Sucede debido a la falta de herramientas que permitan recopilar y compartir información objetiva sobre el uso de la prótesis y el desempeño biomecánico del paciente durante sus actividades cotidianas. Actualmente, gran parte del seguimiento depende de las sesiones presenciales, la observación del profesional y la información que el propio paciente comunica, lo que puede limitar la visibilidad sobre su evolución fuera de la clínica.

**How / ¿CÓMO?**  
El problema se presenta porque los datos sobre el uso de la prótesis, los movimientos y el desempeño del paciente durante la rehabilitación en el hogar no se recopilan de manera continua ni se encuentran centralizados para los diferentes actores involucrados. Como consecuencia, los profesionales pueden tener dificultades para detectar posturas incorrectas, ejercicios realizados inadecuadamente o patrones de uso que requieran atención, mientras que los centros ortopédicos cuentan con información limitada para realizar un seguimiento del mantenimiento y uso de las prótesis.

**How Much / ¿CUÁNTO?**  
La magnitud del problema se relaciona con la cantidad de tiempo que el paciente realiza su rehabilitación fuera de la clínica, durante el cual los profesionales cuentan con información limitada sobre su desempeño. Esta falta de visibilidad puede generar un seguimiento discontinuo y dificultar la detección temprana de problemas de adaptación, posturas incorrectas o un uso inadecuado de la prótesis. Para establecer un porcentaje o valor cuantitativo específico, será necesario realizar una validación con pacientes, clínicas y centros ortopédicos.

### 1.2.2 Lean UX Process

#### 1.2.2.1 Lean UX Problem Statements

Actualmente, el seguimiento y la rehabilitación de pacientes amputados se centran en evaluaciones presenciales puntuales en clínicas de rehabilitación y en controles periódicos en centros ortopédicos, por lo que la supervisión de los ejercicios y la evaluación del uso de la prótesis dependen del tiempo de consulta y del reporte subjetivo del paciente. Los productos y servicios existentes no logran dar visibilidad continua sobre el desempeño del paciente y el uso de su prótesis fuera de la clínica, ni conectar en una misma plataforma al paciente, la clínica y el centro ortopédico, lo que genera un seguimiento discontinuo y decisiones de rehabilitación, ajuste y mantenimiento basadas en percepciones y no en datos objetivos. 

Prothia busca cubrir esta necesidad mediante una plataforma web que recopile, procese y visualice datos biomecánicos y de uso de la prótesis, y que conecte el monitoreo durante las actividades cotidianas del paciente con la supervisión de los profesionales de rehabilitación y de los especialistas ortopédicos. Nuestro enfoque inicial estará dirigido a pacientes amputados en proceso de adaptación y rehabilitación, Profesionales de Terapia Física y Rehabilitación; y Técnicos Ortoprotesistas. Sabremos que la solución es exitosa cuando los pacientes mantengan el uso de la plataforma y de la prótesis a los 30 y 90 días con sesiones de monitoreo cada semana, los profesionales consulten los datos de cada paciente activo al menos una vez por semana y basen sus decisiones en reportes biomecánicos objetivos, y los técnicos ortoprotesistas programen ajustes, revisiones y mantenimiento a partir del uso real de las prótesis.

#### 1.2.2.2 Lean UX Assumptions

**A. Business Assumptions**
- **Creemos que** las clínicas de rehabilitación y los centros ortopédicos que atienden pacientes amputados carecen de información objetiva sobre el desempeño del paciente y el uso de la prótesis fuera de la consulta, y que adoptarían una solución digital si se integra a su rutina de seguimiento.
- **Creemos que** un modelo de suscripción anual para clínicas y licencias de software para centros ortopédicos es viable, siempre que el servicio demuestre mejoras medibles en el seguimiento y la eficiencia operativa.
- **Creemos que** nuestra ventaja será integrar en una sola plataforma a pacientes, clínicas y centros ortopédicos, frente a herramientas aisladas de monitoreo, seguimiento o de fabricantes de prótesis.
- **Creemos que** nuestro equipo, con competencias en software, análisis de datos biomecánicos y sector salud, podrá construir y dar soporte a la solución, y que las alianzas con clínicas y centros ortopédicos que validen el uso clínico y faciliten el acceso al mercado permitirán mitigar los mayores riesgos: la integración de sensores con distintas prótesis y la adopción por parte de clínicas y pacientes.

**B. Business Outcome Assumptions**
- **Creemos que** lograremos una adopción inicial de la plataforma, con 3 a 5 instituciones que completan el piloto en los primeros 6 meses y 50% o más que decide continuar con una suscripción o licencia, si las clínicas y los centros ortopédicos perciben mejoras concretas en su seguimiento durante el piloto.
- **Creemos que** lograremos que los profesionales de terapia física y rehabilitación incorporen el monitoreo como parte de su tratamiento, con 30% o más de sus pacientes amputados registrados y al menos una consulta semanal de datos por paciente activo, si los profesionales perciben que los datos les ayudan a decidir mejor.
- **Creemos que** lograremos que los pacientes usen la plataforma de forma sostenida, con retención de uso a los 30 y 90 días, si perciben avances en su rehabilitación y en el uso de su prótesis durante las primeras semanas.
- **Creemos que** lograremos una alta retención de clínicas, con una renovación anual de 80% o más, si el servicio demuestra mejoras medibles en el seguimiento clínico y en la eficiencia operativa.
- **Creemos que** podemos alcanzar la sostenibilidad financiera si logramos consolidar una base de clínicas y centros ortopédicos con suscripciones y licencias recurrentes, y mantener un costo de adquisición bajo gracias a los casos de éxito de los pilotos.

**C. User Assumptions**
- **Creemos que** cada clínica de rehabilitación cuenta con profesionales (fisioterapeutas, médicos fisiatras) responsables del seguimiento de los pacientes, y que cada centro ortopédico cuenta con técnicos ortoprotesistas responsables de adaptar y mantener las prótesis. Junto con los pacientes amputados, son los principales usuarios de Prothia.
- **Creemos que** estos usuarios necesitan acceder a información actualizada sobre el desempeño del paciente y el uso de la prótesis entre los controles presenciales.
- **Creemos que** actualmente el seguimiento depende de la consulta y del reporte subjetivo del paciente, y que la información de clínicas y centros ortopédicos está separada, lo que dificulta su análisis y seguimiento.
- **Creemos que** quienes pagarán serán las clínicas y los centros ortopédicos, mientras que el paciente será quien use la plataforma con más frecuencia, y que el técnico ortoprotesista instalará y vinculará los sensores a la prótesis (por validar).
- **Creemos que** los usuarios pueden adaptarse a una plataforma web, incluso con distintos niveles de familiaridad con la tecnología, siempre que la interfaz sea simple, clara y accesible.

**D. User Outcome & Benefit Assumptions**
- **Creemos que** los pacientes podrán conocer su progreso y el uso de su prótesis en sus actividades cotidianas, corregir hábitos y mantenerse motivados, con la tranquilidad de que su equipo clínico observa su avance incluso fuera de las sesiones presenciales.
- **Creemos que** los profesionales de rehabilitación podrán identificar a tiempo posturas, movimientos o patrones de uso que requieren atención, y tomar decisiones clínicas basadas en datos objetivos y no solo en lo observado en consulta.
- **Creemos que** los técnicos ortoprotesistas podrán anticipar el mantenimiento y los ajustes de las prótesis a partir de su uso real, y programar revisiones de forma oportuna.
- **Creemos que** pacientes, clínicas y centros ortopédicos percibirán una comunicación más fluida, con menos pérdida de datos y menos duplicidad de esfuerzos, al compartir la información en una plataforma centralizada.

**E. Feature Assumptions**
- **Creemos que** lograremos que las clínicas consulten los datos al menos una vez por semana por paciente activo si los profesionales de rehabilitación logran visualizar el progreso de todos sus pacientes y priorizar la atención de quienes más la necesitan con un dashboard centralizado de monitoreo.
- **Creemos que** lograremos una adopción inicial de 3 a 5 instituciones piloto, con 50% o más que continúa, si los profesionales logran contar con datos objetivos sobre el desempeño del paciente en sus actividades reales con un módulo de monitoreo biomecánico que registre movimientos, posturas e indicadores de uso de la prótesis mediante sensores o dispositivos portátiles compatibles con distintas prótesis.
- **Creemos que** lograremos una renovación anual de clínicas de 80% o más si los profesionales logran revisar la evolución de cada paciente y comparar su desempeño entre periodos con un módulo de seguimiento de rehabilitación.
- **Creemos que** lograremos que al menos 70% de las alertas sean revisadas por el profesional en 48 horas (propuesta) si los profesionales logran detectar a tiempo patrones de uso, posturas o movimientos que requieren atención con alertas automáticas con umbrales definidos por el profesional.
- **Creemos que** lograremos retención de uso de los pacientes a los 30 y 90 días, con sesiones semanales de monitoreo fuera de la clínica, si los pacientes logran conocer su propio desempeño y el uso de su prótesis con una vista de progreso personal.
- **Creemos que** lograremos que los centros ortopédicos contraten y renueven licencias si los técnicos ortoprotesistas logran anticipar mantenimiento y ajustes con un historial de uso de la prótesis que permita agendar revisiones.
- **Creemos que** lograremos que los tres actores estén activos en cada institución piloto si pacientes, profesionales y técnicos logran ver solo lo relevante para su rol e intercambiar información con un acceso diferenciado por tipo de usuario.

#### 1.2.2.3 Lean UX Hypothesis Statements

- **Creemos que** lograremos que las clínicas incorporen el monitoreo como parte habitual de su tratamiento, con al menos 1 consulta semanal de datos por paciente activo y 30% o más de los pacientes amputados de cada clínica piloto registrados, si los profesionales de rehabilitación logran visualizar el progreso y el desempeño de todos sus pacientes en un solo lugar, priorizar la atención de quienes más la necesitan y decidir con evidencia, con un dashboard centralizado de monitoreo que muestre el estado y la evolución de cada paciente.
- **Creemos que** lograremos una adopción inicial de la plataforma, con 3 a 5 instituciones que completan el piloto en 6 meses y 50% o más que continúa con suscripción o licencia, si los profesionales de rehabilitación logran contar con datos objetivos sobre el desempeño del paciente durante sus actividades reales, y no solo con lo observado en consulta o el reporte subjetivo, con un módulo de monitoreo biomecánico que, mediante sensores o dispositivos portátiles compatibles con distintas prótesis, registre movimientos, posturas e indicadores de uso de la prótesis.
- **Creemos que** lograremos una alta retención de clínicas, con una renovación anual de 80% o más y baja cancelación en el primer año, si los profesionales de rehabilitación logran revisar la evolución de cada paciente, comparar su desempeño entre periodos y ajustar el tratamiento con base en evidencia, con un módulo de seguimiento de rehabilitación que permita consultar el historial de cada paciente y comparar periodos.
- **Creemos que** lograremos una alta retención de clínicas, al demostrar valor medible en la detección temprana de problemas (propuesta: al menos 70% de las alertas revisadas por el profesional en 48 horas), si los profesionales de rehabilitación logran detectar a tiempo patrones de uso, posturas o movimientos que requieren atención, antes de que generen complicaciones o retrasos, con un sistema de alertas automáticas con umbrales definidos por el profesional.
- **Creemos que** lograremos un uso sostenido de la plataforma por parte de los pacientes, con retención de uso a los 30 y 90 días (propuesta: 60% y 40%) y sesiones semanales de monitoreo fuera de la clínica (propuesta: al menos 3), si los pacientes amputados en proceso de rehabilitación logran un mayor conocimiento de su propio desempeño y del uso de su prótesis, que les permita corregir hábitos y mantenerse motivados, con una vista de progreso personal que muestre su desempeño y el uso de su prótesis en sus actividades cotidianas.
- **Creemos que** lograremos un crecimiento sostenible mediante la contratación y renovación de licencias por parte de los centros ortopédicos (propuesta: renovación de 80% o más), si los técnicos ortoprotesistas logran anticipar mantenimiento y ajustes a partir del uso real de cada prótesis, con un historial de uso de la prótesis que permita consultar cómo se utiliza cada dispositivo, agendar revisiones y registrar el mantenimiento.
- **Creemos que** lograremos una adopción inicial de la plataforma y su uso por los tres actores (propuesta: al menos un usuario activo por semana de cada rol en el 100% de las instituciones piloto), si pacientes, profesionales de clínicas y técnicos ortoprotesistas logran una comunicación e intercambio de información más fluidos, viendo solo lo relevante para su rol, con un acceso diferenciado por tipo de usuario que muestre a cada rol solo la información y las funcionalidades pertinentes y permita el intercambio de datos entre clínicas y centros.

#### 1.2.2.4 Lean UX Canvas

```{=typst}
#set text(size: 8pt)
#set table(
  columns: (1fr, 1.2fr, 1fr),
  stroke: 0.5pt + luma(180),
  inset: 6pt
)
```

| **Business Problem** | **Solutions** | **Business Outcomes** |
| :--- | :--- | :--- |
| El seguimiento y la rehabilitación de pacientes amputados se basa en evaluaciones presenciales puntuales y controles periódicos, por lo que hay poca visibilidad sobre el desempeño del paciente y el uso de la prótesis fuera de la clínica. Los profesionales no pueden observar si los ejercicios se realizan correctamente ni si existen compensaciones posturales. Además, los datos entre paciente, clínica y taller están fragmentados. Prothia busca resolver esto centralizando datos biomecánicos y de uso en una plataforma web. | • **Dashboard centralizado:** visualización de progreso de todos los pacientes en un solo lugar.\ \ • **Monitoreo biomecánico:** datos continuos de movimientos y posturas cotidianas.\ \ • **Seguimiento de rehabilitación:** evolución y comparación de desempeño.\ \ • **Alertas automáticas:** detección temprana de posturas de riesgo.\ \ • **Vista de progreso:** acceso directo del paciente a su evolución.\ \ • **Historial técnico:** registro de uso real para revisiones de prótesis. | • **Adopción inicial:** 3 a 5 instituciones completan pilotos en 6 meses y ≥50% continúa con suscripción.\ \ • **Incorporación al tratamiento:** ≥30% de pacientes registrados y al menos 1 consulta semanal por paciente activo.\ \ • **Uso sostenido:** retención a 30 y 90 días con sesiones semanales en casa.\ \ • **Retención:** renovación anual de clínicas ≥80%.\ \ • **Crecimiento sostenible:** retornos escalables y menor costo de adquisición. |

\

```{=typst}
#set table(
  columns: (1fr, 1fr),
  stroke: 0.5pt + luma(180),
  inset: 6pt
)
```

| **Users** | **User Outcomes & Benefits** |
| :--- | :--- |
| • **Pacientes amputados:** *"Quiero realizar mi rehabilitación y adaptación a la prótesis de manera adecuada y saber que mi equipo clínico conoce mi progreso incluso cuando estoy fuera de la clínica."*\ \ • **Profesionales de rehabilitación:** *"Necesito conocer cómo evolucionan mis pacientes entre sesiones para detectar problemas a tiempo y tomar decisiones basadas en datos objetivos."*\ \ • **Técnicos ortoprotesistas:** *"Necesito conocer cómo se utiliza realmente cada prótesis para programar ajustes y mantenimiento de forma oportuna."* | • **Pacientes:** rehabilitación más efectiva y autónoma, seguimiento continuo, conocimiento de hábitos y motivación constante.\ \ • **Profesionales:** visibilidad de la evolución fuera de consulta, prevención temprana de complicaciones y decisiones clínicas basadas en evidencia.\ \ • **Técnicos ortoprotesistas:** conocimiento del uso real del dispositivo y mantenimiento oportuno.\ \ • **Articulación conjunta:** comunicación fluida sin pérdida ni duplicidad de información clínica y técnica. |

\

```{=typst}
#set table(
  columns: (1.1fr, 1fr, 1fr),
  stroke: 0.5pt + luma(180),
  inset: 6pt
)
```

| **Hypotheses** | **¿Qué debemos aprender primero?** | **¿Menor esfuerzo para validarlo?** |
| :--- | :--- | :--- |
| • **Dashboard:** las clínicas incorporarán el monitoreo si priorizan pacientes con un panel centralizado.\ \ • **Monitoreo biomecánico:** se logrará adopción si existen datos objetivos del paciente en casa.\ \ • **Seguimiento:** retención alta al comparar la evolución entre periodos.\ \ • **Alertas:** prevención temprana de compensaciones musculares lesivas.\ \ • **Historial técnico:** los ortoprotesistas anticiparán el mantenimiento preventivo. | • ¿Los profesionales consideran la falta de datos remotos un problema crítico y pagarían por resolverlo?\ \ • ¿Los pacientes aceptarían usar sensores portátiles en casa a 30 y 90 días?\ \ • ¿Qué métricas biomecánicas son indispensables para la clínica?\ \ • ¿Qué información de desgaste técnico requiere el ortoprotesista? | • Entrevistas semiestructuradas a especialistas y técnicos.\ \ • Entrevistas a pacientes sobre su rutina domiciliaria.\ \ • Prototipo de alta fidelidad en Figma con dashboard y progreso.\ \ • Pruebas de usabilidad con datos biomecánicos simulados.\ \ • Priorización de requerimientos antes del desarrollo del MVP. |

```{=typst}
#set text(size: 11pt)
```

## 1.3 Segmentos Objetivos

### Segmento 1: Pacientes Amputados

Corresponde a los usuarios finales de la solución, conformado por personas que han sufrido una amputación y utilizan una prótesis como parte de su proceso de recuperación y adaptación. Estos pacientes realizan una parte importante de su rehabilitación fuera de las instalaciones de la clínica, principalmente en sus hogares, donde deben realizar ejercicios y actividades orientadas a mejorar su movilidad y adaptación al dispositivo. En su rutina pueden enfrentar dificultades para realizar correctamente los ejercicios, mantener posturas adecuadas o identificar problemas relacionados con el uso de la prótesis, especialmente cuando no cuentan con supervisión profesional constante.

En este contexto, valoran soluciones que les permitan contar con un mayor acompañamiento durante su proceso de rehabilitación sin necesidad de acudir constantemente a la clínica. Para este segmento, Prothia representa una herramienta que permite complementar las sesiones presenciales mediante el monitoreo del uso de la prótesis y la recopilación de información que puede ser revisada por los profesionales responsables de su rehabilitación.

**Características demográficas e información estadística de sustento:**  
Según la Primera Encuesta Nacional Especializada sobre Discapacidad del Instituto Nacional de Estadística e Informática (INEI), en el Perú existen 1 millón 575 mil 402 personas con algún tipo de discapacidad, lo que representa el 5,2% de la población total del país. De este grupo, la discapacidad motora —dificultad para moverse, caminar o usar brazos y piernas— es la que más afecta, alcanzando 932 mil personas (59,2% del total con discapacidad).

Dentro de este segmento con discapacidad motora, el 56,4% son mujeres (525 mil 719 personas) y el 43,6% son hombres (406 mil 274 personas). Respecto al origen de la limitación, esta se presenta principalmente por edad avanzada (32,5%), enfermedad crónica (24,4%), causas genéticas o congénitas (9,8%), accidentes comunes fuera del hogar (4,9%), accidentes en el hogar (4,6%) y accidentes de tránsito (4,0%).

A nivel de causas específicas de amputación, un estudio del Instituto Nacional de Rehabilitación (Callao, Perú) revisó 1,290 historias clínicas de pacientes amputados atendidos entre 2003 y 2007, de los cuales 108 casos correspondieron a amputaciones por accidentes de trabajo. Asimismo, otro estudio publicado en la Revista Peruana de Medicina Experimental y Salud Pública documentó las características clínico-epidemiológicas de amputaciones de miembro inferior por pie diabético en hospitales de la costa norte peruana entre 1990 y 2000, lo que confirma al pie diabético como otra causa relevante de amputación en el país, además de los accidentes laborales y de tránsito.

### Segmento 2: Profesionales de Terapia Física y Rehabilitación

Corresponde al segmento principal al que se dirige el modelo de negocio de Prothia, conformado por clínicas y profesionales especializados en la rehabilitación de pacientes amputados. Estas instituciones son responsables de acompañar al paciente durante su proceso de adaptación y recuperación, pero presentan limitaciones para conocer su desempeño cuando este se encuentra fuera de las sesiones presenciales. Necesitan información que les permita realizar un seguimiento más completo, identificar posibles dificultades y evaluar la evolución del paciente durante el tratamiento.

En este contexto, valoran herramientas que permitan complementar la observación presencial con información recopilada durante las actividades cotidianas del paciente. Prothia representa para este segmento una plataforma que permite centralizar la información de sus pacientes, visualizar datos biomecánicos y de uso de las prótesis y realizar un seguimiento más continuo de la rehabilitación. La clínica obtiene acceso mediante una suscripción anual a la plataforma y puede proporcionar el acceso a sus pacientes como parte del tratamiento.

**Características demográficas e información estadística de sustento:**  
En Lima existe una oferta amplia y fragmentada de centros de rehabilitación física, que incluye tanto establecimientos privados especializados en traumatología, ortopedia y fisioterapia, como servicios públicos, entre ellos el Centro de Medicina Física y Rehabilitación de EsSalud. Directorios comerciales de la ciudad listan más de una decena de centros de rehabilitación física activos solo en distritos como Pueblo Libre, La Molina, Jesús María, San Miguel y Surquillo, varios de los cuales ofrecen explícitamente tratamiento pre y post quirúrgico para amputaciones y adaptación de prótesis.

### Segmento 3: Técnicos Ortoprotesistas

Corresponde a los establecimientos especializados en la fabricación, adaptación y mantenimiento de prótesis para pacientes amputados. Estos centros necesitan conocer las condiciones de uso de los dispositivos para facilitar su seguimiento y mantenimiento, así como contar con información que pueda contribuir a comprender el comportamiento de la prótesis durante las actividades cotidianas del usuario. Actualmente, parte de esta información puede depender de las observaciones realizadas durante las visitas del paciente o de la comunicación entre el usuario y el especialista.

En este contexto, los centros ortopédicos valoran soluciones que les permitan acceder a información sobre el uso de las prótesis y mantener un registro que facilite su gestión. Prothia representa una herramienta que permite complementar la información técnica de la prótesis con datos relacionados con su utilización, brindando a las ortopedias acceso a la plataforma mediante un modelo de licenciamiento de software.

**Características demográficas e información estadística de sustento:**  
El mercado de centros ortopédicos en Lima está compuesto principalmente por negocios especializados en la venta de productos ortopédicos, prótesis externas, corsés y otros dispositivos de rehabilitación, distribuidos en distritos como La Victoria, Cercado de Lima y María Auxiliadora, según directorios comerciales locales. Estos establecimientos suelen operar de forma independiente, sin un sistema compartido que centralice la información sobre el uso o mantenimiento de las prótesis que fabrican o ajustan.

```{=typst}
#pagebreak()
```
```{=typst}
#pagebreak()
```

# Capítulo II: Requirements Elicitation & Analysis 

## 2.1. Competidores

### Competidor 1: DyCare (ReHub)
DyCare es una empresa de salud digital que ha desarrollado ReHub, una plataforma de telerehabilitación asistida por inteligencia artificial y visión computacional para el tratamiento de afecciones musculoesqueléticas. Proporciona herramientas para la prescripción de ejercicios personalizados, guía interactiva con biofeedback en tiempo real para el paciente desde su hogar y un panel clínico para monitorear la adherencia y evolución del tratamiento. Esta plataforma es reconocida en el sector de la fisioterapia digital por permitir a las clínicas y aseguradoras optimizar el seguimiento remoto sin requerir hardware adicional complejo.

### Competidor 2: Ottobock Digital Solutions
Ottobock Digital Solutions es la división tecnológica del fabricante global de prótesis y órtesis Ottobock, la cual ofrece herramientas digitales y aplicaciones móviles (como connectgo, connectgo.pro y Cockpit) conectadas por Bluetooth a sus prótesis controladas por microprocesador. Proporciona funcionalidades para que los técnicos ortopédicos calibren y configuren modos de movimiento, al tiempo que permite a los usuarios monitorear el estado del dispositivo, el nivel de batería y métricas básicas de actividad física diaria. Esta suite es conocida por su alto nivel de precisión técnica y por facilitar el mantenimiento y control directo de dispositivos protésicos de alta gama.

### Competidor 3: SWORD Health
SWORD Health es una plataforma integral de terapia física digital y telerehabilitación predictiva enfocada en el tratamiento del dolor y la recuperación posquirúrgica. Su solución combina sensores de movimiento inerciales portátiles con un terapeuta digital impulsado por IA (Phoenix), el cual guía y corrige al paciente en tiempo real durante cada sesión mientras un equipo de fisioterapeutas clínicos supervisa su progreso de forma remota a través de la nube. Esta plataforma es ampliamente reconocida en el mercado corporativo y de aseguradoras de salud por reducir significativamente la deserción en las terapias domiciliarias y disminuir costos médicos asociados a cirugías o tratamientos tradicionales.

---

## 2.1.1. Análisis competitivo

> **¿Por qué llevar a cabo este análisis?**  
> Identificar las soluciones existentes de telerehabilitación y monitoreo de prótesis en el mercado, contrastando sus propuestas de valor frente al enfoque integrado de SeniorsInProcess (paciente–clínica–ortopedia) para detectar ventajas competitivas y oportunidades de posicionamiento.

```{=typst}
#set text(size: 7.5pt)
#set table(
  columns: (1.5fr, 1.8fr, 2.5fr, 2.5fr, 2.5fr, 2.5fr),
  stroke: 0.5pt + luma(180),
  inset: 4.5pt
)
```

| Sección | Variable | SeniorsInProcess (Prothia) | DyCare (Rehub) | Ottobock Digital | SWORD Health |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Logotipo** | Identificador visual | ![](../SeniorsInProcess-Pandoc/assets/Prothia_logo.png){ width=50px } | ![](../SeniorsInProcess-Pandoc/assets/logo_Rehub.png){ width=50px } | ![](../SeniorsInProcess-Pandoc/assets/logo_ottobock.png){ width=50px } | ![](../SeniorsInProcess-Pandoc/assets/logo_swordhealth.png){ width=50px } |
| **Perfil** | Overview | Plataforma web integral de monitoreo biomecánico y seguimiento remoto de rehabilitación para amputados, articulando clínica, paciente y ortopedia. | Software de telerehabilitación y análisis de movimiento en tiempo real para lesiones musculoesqueléticas. | Soluciones digitales de prótesis/órtesis inteligentes con apps de configuración y telemetría de dispositivos. | Plataforma de terapia física digital enfocada en la rehabilitación guiada por sensores y terapeuta con IA. |
| **Perfil** | Ventaja competitiva | Integra en una sola plataforma clínica, ortopedia y paciente, cruzando biomecánica con historial técnico protésico. | Visión computacional propia sin hardware (+60 puntos anatómicos) y biofeedback visual inmediato. | Marca de referencia mundial, integración nativa de microprocesadores y sensores mecánicos en la prótesis. | Solución integral con sensores inerciales portátiles propietarios y alta adherencia clínica. |
| **Marketing** | Mercado objetivo | Clínicas de rehabilitación física, centros ortopédicos y pacientes amputados (Perú y LATAM). | Clínicas de fisioterapia, hospitales, aseguradoras y mutuas laborales en Europa y Latinoamérica. | Ortesistas/protesistas certificados (CPO), clínicas especializadas y usuarios de alta gama global. | Aseguradoras médicas y grandes corporaciones/empleadores que reducen costos de bajas laborales. |
| **Marketing** | Estrategias | Ventas B2B directas, pilotos clínicos, alianzas universitarias y demostraciones de producto. | Inbound marketing médico, acuerdos con mutuas, ferias sanitarias y pruebas institucionales. | Venta cruzada atada al hardware protésico, capacitación médica y congresos de ortopedia. | Modelo B2B2C centrado en beneficios corporativos para empresas y marketing institucional. |
| **Producto** | Productos & Servicios | Plataforma web con dashboard biomecánico, alertas posturales, seguimiento clínico e historial técnico. | Software Rehub con IA, catálogo de +3,500 ejercicios terapéuticos y corrección postural. | Suite de apps (Cockpit, connectgo, Myo Plus) para configuración, batería y mantenimiento. | Kit de sensores inerciales corporales, tableta con ejercicios interactivos y portal en la nube. |
| **Producto** | Precios & Costos | Suscripción anual para clínicas y licencias de software para centros ortopédicos. | Planes SaaS por número de fisioterapeutas/pacientes o contratos corporativos a gran escala. | Apps básicas incluidas con el hardware; licencias clínicas avanzadas ligadas al costo protésico. | Tarificación por miembro cubierto (PEPM) o cobro por episodio rehabilitador a aseguradoras. |
| **Producto** | Canales | Plataforma Web (SaaS clínico/taller) con portal web/móvil responsivo para el paciente. | Portal Web para profesionales y aplicación móvil/tableta (iOS y Android) para pacientes. | Aplicaciones móviles nativas en Google Play y App Store vía Bluetooth a componentes. | Envío de hardware directo a domicilio con apps móviles y portal clínico web. |
| **SWOT** | Fortalezas | • Enfoque de nicho centrado en amputados.\ \ • Conexión directa clínica-ortopedia.\ \ • Arquitectura web adaptable. | • Certificación CE Clase IIa.\ \ • IA madura sin hardware extra.\ \ • Amplio catálogo terapéutico. | • Líder mundial y marca consolidada.\ \ • Integración hardware-software de alta gama.\ \ • Solidez y patentes. | • Amplia validación clínica global.\ \ • Gran capitalización y alianzas de salud.\ \ • Experiencia de usuario pulida. |
| **SWOT** | Debilidades | • Etapa temprana de desarrollo.\ \ • Requiere validar compatibilidad con sensores.\ \ • Presupuesto inicial limitado. | • No especializada en adaptación o encaje protésico.\ \ • No integra fabricantes u ortopedias. | • Ecosistema cerrado exclusivo para componentes Ottobock.\ \ • Poca profundidad en ejercicios caseros. | • Solución de alto costo orientada a países desarrollados.\ \ • Poca personalización en amputados. |
| **SWOT** | Oportunidades | • Alta demanda desatendida en Perú y LATAM.\ \ • Alianzas estratégicas con clínicas locales.\ \ • Telemedicina asequible. | • Expansión en salud pública y aseguradoras para listas de espera.\ \ • Nuevas patologías. | • Analítica predictiva de marcha y desgaste para mantenimiento programado. | • Penetración en nuevos mercados internacionales vía salud corporativa. |
| **SWOT** | Amenazas | • Resistencia al cambio de especialistas tradicionales.\ \ • Tiempos largos de compra en clínicas. | • Apps gratuitas o de bajo costo sin suscripción.\ \ • Normativas sobre IA y datos de salud. | • Fabricantes emergentes de prótesis accesibles o de código abierto.\ \ • Falta de interoperabilidad. | • Entrada de gigantes MedTech al mercado de la telerehabilitación.\ \ • Políticas de reembolso. |

```{=typst}
#set text(size: 11pt)
```

---

### 2.1.2. Estrategias y tácticas frente a competidores

Hemos identificado diversas estrategias y tácticas para diferenciarnos y competir efectivamente con otros actores del mercado de la telerehabilitación y las soluciones tecnológicas protésicas:

**Estrategias de Diferenciación:**
* **Ecosistema Integrado:** A diferencia de competidores como DyCare (Rehub), que se enfocan en la relación terapeuta-paciente para rehabilitación musculoesquelética general, Prothia articula en una sola plataforma web a las clínicas de rehabilitación, los centros ortopédicos y los pacientes amputados. Esto permite cruzar datos de evolución motriz con métricas de uso y mantenimiento técnico del dispositivo protésico. 
* **Plataforma Multimarca e Interoperable:** Frente a competidores directos como Ottobock Digital Solutions, cuyos sistemas de software están cerrados exclusivamente a sus propios componentes biónicos, Prothia se posiciona como una solución agnóstica. Nuestra plataforma está diseñada para registrar y analizar datos biomecánicos sin importar la marca o fabricante de la prótesis utilizada por el paciente. 
* **Visualización Biomecánica Simplificada:** La plataforma prioriza una interfaz intuitiva con dashboards claros y alertas automáticas de posturas o patrones de marcha incorrectos. Esto permite que tanto el paciente en su hogar como el fisioterapeuta puedan interpretar la información de inmediato sin requerir conocimientos avanzados de ingeniería biomecánica. 

**Tácticas de Marketing:**
* **Demostraciones Clínicas y Pruebas Piloto B2B:** Implementaremos contacto directo con directores de centros de rehabilitación y talleres ortopédicos en Lima, ofreciendo demostraciones en vivo y programas piloto controlados con pacientes reales. Esta táctica nos permite validar la utilidad clínica de la plataforma y acelerar la confianza en el producto frente a competidores internacionales que carecen de presencia local. 
* **Contenido Especializado y Difusión Científica:** Desarrollaremos casos de estudio, artículos y material informativo sobre la importancia del seguimiento domiciliario en pacientes amputados, difundidos en redes profesionales (como LinkedIn) y eventos del sector salud. De esta manera, nos posicionamos como referentes técnicos en rehabilitación protésica basada en datos. 

**Expansión y Adaptabilidad:**
* **Enfoque Local Inicial y Expansión Regional:** A diferencia de soluciones globales como Ottobock o SWORD Health, Prothia comenzará su validación e implementación en clínicas y centros ortopédicos de Lima, adaptándose a los flujos de trabajo y presupuestos de la realidad sanitaria peruana antes de expandirse a nivel nacional y latinoamericano. 
* **Alianzas Estratégicas con Centros Ortopédicos y de Rehabilitación Locales:** Estableceremos convenios de colaboración mutua con ortopedias y especialistas locales para co-diseñar módulos clave (como el historial de uso y mantenimiento preventivo), garantizando una adopción fluida y un soporte técnico directo que las plataformas extranjeras no pueden ofrecer en el mercado local.

---

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

**Preguntas para el Segmento Objetivo 1 – Pacientes Amputados:**
1. ¿Cuál es su edad, estado civil y en qué distrito o ciudad reside?
2. ¿A qué se dedica actualmente y con quiénes vive en su hogar?
3. ¿Hace cuánto tiempo utiliza una prótesis y de qué tipo es (mecánica, hidráulica, mioeléctrica)? 
4. ¿Podrías detallar qué tipo de amputación tienes o qué extremidad se vio afectada?
5. ¿Con qué frecuencia asiste a sus sesiones presenciales de terapia física o rehabilitación? 
6. ¿Qué ejercicios o rutinas le indica su terapeuta para realizar en casa y con qué regularidad los practica? 
7. ¿Qué dificultades o molestias (como dolor, fatiga o desbalances) suele experimentar al realizar sus ejercicios o al caminar solo en casa? 
8. ¿Cómo sabe si está realizando correctamente los movimientos o si mantiene una postura adecuada sin la presencia del profesional? 
9. ¿Cómo se comunica habitualmente con su clínica o con su ortopedia cuando presenta dudas o problemas con el uso de su dispositivo? 
10. ¿Utiliza actualmente su celular, computadora u otra herramienta tecnológica para llevar el registro de su salud o terapias?
11. ¿Qué tan valioso le resultaría contar con una plataforma que le muestre en tiempo real si realiza bien sus movimientos y alerte a su médico si hay errores? 
12. ¿Qué dispositivos (computadora, tableta o teléfono inteligente) utiliza con mayor frecuencia y preferiría para interactuar con esta solución? 
13. En su opinión, ¿qué características o funciones son indispensables para que usted decida usar diariamente esta plataforma? 
14. ¿Qué factores o situaciones harían que usted se desmotive o deje de utilizar una aplicación de seguimiento de su prótesis?

**Preguntas para el Segmento Objetivo 2 – Profesionales de Terapia Física y Rehabilitación:**
1. ¿Cuál es su edad, profesión o cargo en la institución y en qué ciudad labora?
2. ¿Hace cuántos años trabaja en el área de rehabilitación física y cuántos pacientes amputados atienden periódicamente en su centro? 
3. ¿Cómo estructuran y coordinan actualmente el plan de rehabilitación y adaptación protésica fuera de las consultas presenciales? 
4. ¿Cómo supervisan y registran el progreso biomecánico o la adherencia del paciente cuando este realiza sus ejercicios en el hogar? 
5. ¿Cuáles son los principales problemas o riesgos que detectan cuando los pacientes no cuentan con seguimiento continuo en sus domicilios? 
6. ¿Qué mecanismos o canales emplean actualmente para compartir información médica con los centros ortopédicos que confeccionan las prótesis? 
7. ¿Utilizan en su clínica algún software clínico, sistema de telemedicina o herramienta digital para evaluar métricas biomecánicas? 
8. ¿Qué tan valioso resultaría para su equipo disponer de un dashboard centralizado que muestre datos biomecánicos y de uso de la prótesis en tiempo real? 
9. ¿Qué impacto tendría en su trabajo contar con alertas automáticas ante posturas incorrectas o compensaciones musculares de los pacientes? 
10. ¿Estaría su clínica dispuesta a adquirir una suscripción anual por una solución digital que optimice el seguimiento y aumente el valor clínico del servicio? 
11. ¿Qué módulos o indicadores considera estrictamente indispensables para que su equipo médico adopte una plataforma de este tipo? 
12. ¿A través de qué dispositivos preferirían los profesionales de su centro acceder a la plataforma (navegador web en PC, laptops, tabletas)? 
13. ¿Qué barreras o problemas operativos podrían desincentivar el uso continuado de este software en su institución? 

**Preguntas para el Segmento Objetivo 3 – Técnicos Ortoprotesistas:**
1. ¿Cuál es su edad, especialidad técnica o cargo y en qué ciudad opera su centro ortopédico?
2. ¿A qué se dedica específicamente su taller y cuántas prótesis adaptan o fabrican mensualmente? 
3. ¿Cómo organizan actualmente el calendario de ajustes, revisiones periódicas y mantenimiento de las prótesis entregadas? 
4. ¿Llevan un historial técnico o registro estructurado del estado físico y vida útil de cada componente protésico? ¿Cómo lo gestionan? 
5. ¿Qué dificultades enfrentan para saber con certeza el uso real, desgaste y esfuerzo al que los usuarios someten las prótesis en su vida cotidiana? 
6. ¿Cómo fluye actualmente la comunicación técnica entre su taller y los médicos o fisioterapeutas a cargo de la rehabilitación del paciente? 
7. ¿Han utilizado previamente algún software de gestión de prótesis o telemetría para componentes ortopédicos? Si fue así, ¿cuál fue su experiencia? 
8. ¿Qué tan beneficioso sería para su centro disponer de un portal con el historial de uso y horas de actividad del dispositivo en tiempo real? 
9. ¿De qué manera ayudaría a su negocio recibir alertas preventivas sobre necesidad de mantenimiento o calibración de las piezas? 
10. ¿Estaría su centro ortopédico dispuesto a pagar una licencia de software para optimizar la trazabilidad, posventa y servicio técnico de sus prótesis? 
11. ¿Qué funcionalidades técnicas considera fundamentales para que una herramienta digital sea útil en la rutina de un protesista u ortesista? 
12. ¿En qué dispositivos (computadoras de escritorio del taller, laptops de evaluación o smartphones) necesitarían utilizar la herramienta? 

---

### 2.2.2. Registro de entrevistas

#### Segmento objetivo 1 - Pacientes amputados

### Entrevista 1 – Enrique Diaz

* **Nombres y Apellidos:** Enrique Diaz Aguero
* **Edad:** 26 años
* **Distrito de Residencia:** Lince (Lima)
* **Estado Civil:** Soltero
* **Ocupación:** Asistente administrativo (modalidad teletrabajo)
* **Condición Médica:** Amputación transtibial en la pierna derecha (uso de prótesis mecánica convencional desde hace 2 años).
* **Fecha de entrevista:** 08/09/2026 | **Duración:** 7:16
* **Enlace:** https://tinyurl.com/2ezssk23

![](../SeniorsInProcess-Pandoc/assets/Entrevista_Segmento1.png){ width=80% }

**Resumen de la entrevista:**  
El entrevistado es Enrique Díaz, un joven de 26 años de edad, de estado civil soltero, que reside en el distrito de Lince en Lima, Perú, y labora actualmente como asistente administrativo desempeñándose en la modalidad de teletrabajo la mayor parte del tiempo, viviendo solo en su departamento. En cuanto a su condición física, Enrique tiene una amputación transtibial en la pierna derecha por debajo de la rodilla como secuela de un accidente de tránsito ocurrido hace poco más de dos años, momento desde el cual utiliza una prótesis mecánica convencional. Respecto a su rehabilitación, en las etapas iniciales concurría a terapia presencial dos veces por semana, pero en la actualidad redujo su asistencia a una vez cada quince días debido a las severas dificultades de movilidad y traslado en la ciudad.

En su hogar tiene asignada una rutina diaria de descarga de peso, ejercicios de equilibrio apoyado frente a una silla y caminatas cortas en línea recta, no obstante, reconoce que por agotamiento laboral o desgana los ejecuta de manera interdiaria. Al ejercitarse o caminar solo experimenta fricción e irritación cutánea generada por el roce del encaje de la prótesis, así como dolores en la espalda baja al finalizar el día debido a que compensa de forma asimétrica el peso corporal cargándolo hacia la pierna contralateral o pisando de manera desalineada. Para comunicarse con la clínica utiliza WhatsApp con demoras habituales, y ante desajustes mecánicos acude presencialmente al taller perdiendo horas de trabajo. Establece como indispensables una interfaz simple, botones legibles y que no consuma su plan de datos móviles ni batería.

\

### Entrevista 2 – Juan Ramirez

* **Nombres y Apellidos:** Juan Ramirez
* **Edad:** 30 años
* **Distrito de Residencia:** San Miguel (Lima)
* **Estado Civil:** Soltero
* **Ocupación:** Desarrollador de software freelance
* **Condición Médica:** Amputación transtibial en la pierna izquierda.
* **Fecha de entrevista:** 08/09/2026 | **Duración:** 7:04
* **Enlace:** https://tinyurl.com/3p23ymt4

![](../SeniorsInProcess-Pandoc/assets/PacienteAmputado-imagen.jpeg){ width=80% }

**Resumen de la entrevista:**  
Juan Ramirez tiene 30 años y se desempeña como desarrollador freelance. Presenta una amputación transtibial y utiliza una prótesis mecánica de respuesta dinámica. Asiste mensualmente a control con su fisioterapeuta y realiza rutinas de muñón y equilibrio en casa. Durante sus ejercicios experimenta sobrecarga lumbar y fatiga en el muñón. Como método de validación casera se grababa en video, pero aún siente incertidumbre sobre si desvía el eje corporal. Considera de alto valor una plataforma con retroalimentación visual o auditiva inmediata, gráficas de balance y rechaza de manera enfática las notificaciones invasivas o sistemas de calibración lentos.

\

### Entrevista 3 – Miguel Suarez

* **Nombres y Apellidos:** Miguel Suarez Casas
* **Edad:** 25 años
* **Distrito de Residencia:** San Martín de Porres (Lima)
* **Estado Civil:** Soltero
* **Ocupación:** Asistente administrativo (modalidad teletrabajo)
* **Condición Médica:** Amputación transfemoral en la pierna derecha (uso de prótesis mecánica desde hace 3 años).
* **Fecha de entrevista:** 08/09/2026 | **Duración:** 5:10
* **Enlace:** https://tinyurl.com/23hvbfxw

![](../SeniorsInProcess-Pandoc/assets/Entrevista_PacienteAmputado(3).png){ width=80% }

**Resumen de la entrevista:**  
Miguel presenta una amputación transfemoral y asiste a terapia física una vez por semana. Realiza rutinas de adaptación tres a cuatro veces por semana, experimentando desbalances y temor a caídas o vicios de marcha por sobrecompensación. Usa su celular permanentemente para consultas médicas y videos de ejercicios. Demanda una plataforma móvil intuitiva con métricas históricas de avance, alertas ante fallos cinemáticos y que proteja estrictamente su privacidad.

---

#### Segmento objetivo 2 - Profesionales de Terapia Física y Rehabilitación

### Entrevista 1 – Diego Salazar

* **Nombres y Apellidos:** Diego Salazar Mendoza
* **Edad:** 28 años
* **Ocupación:** Licenciado en Terapia Física y Rehabilitación
* **Centro de trabajo:** Centro de rehabilitación en Jesús María (Lima)
* **Fecha de entrevista:** 07/09/2026 | **Duración:** 7:09
* **Enlace:** https://tinyurl.com/mwx4b4s6

![](../SeniorsInProcess-Pandoc/assets/Entrevista_Segmento2.png){ width=80% }

**Resumen de la entrevista:**  
Diego atiende de 6 a 10 pacientes amputados de forma regular. Explica que la clínica carece de herramientas objetivas para supervisar el cumplimiento de los ejercicios en el hogar y dependen únicamente del testimonio verbal del paciente. La comunicación con ortopedias se realiza por WhatsApp y llamadas sin un expediente unificado. Recomienda adoptar un dashboard centralizado que muestre datos biomecánicos, planes de ejercicio y alertas de desalineación, priorizando la visualización en computadoras y tabletas clínicas.

\

### Entrevista 2 – Ana Mercedes

* **Nombres y Apellidos:** Ana Mercedes
* **Edad:** 38 años
* **Ocupación:** Fisioterapeuta especialista en rehabilitación física (Lima)
* **Fecha de entrevista:** 08/09/2026 | **Duración:** 6:12
* **Enlace:** https://tinyurl.com/44yuywb7

![](../SeniorsInProcess-Pandoc/assets/clinica-entrevista.jpeg){ width=80% }

**Resumen de la entrevista:**  
Ana cuenta con 10 años de experiencia asistencial. Subraya el grave riesgo clínico de que los pacientes desarrollen compensaciones lumbares al entrenar solos. La coordinación técnica con ortopedias es reactiva y se limita a casos de daño estructural. Considera indispensable un módulo de análisis cinemático de marcha, exportación de reportes al historial médico y una interfaz sencilla que no agregue sobrecarga administrativa de digitación manual.

\

### Entrevista 3 – Carmen Salazar

* **Nombres y Apellidos:** Carmen Salazar
* **Edad:** 70 años
* **Ocupación:** Médica especialista en Rehabilitación (Directora Médica en Lima)
* **Fecha de entrevista:** 10/09/2026 | **Duración:** 6:12
* **Enlace:** https://tinyurl.com/5xxj6njv

![](../SeniorsInProcess-Pandoc/assets/Entrevista3_Segmento2.png){ width=80% }

**Resumen de la entrevista:**  
Con más de 40 años de trayectoria, la Dra. Carmen señala que una plataforma digital debe complementar el criterio médico sin burocracia. Propone una vista con semaforización (verde, amarillo y rojo) para triaje rápido de pacientes y alertas preventivas. Señala que la clínica contrataría una suscripción anual si el sistema demuestra reducir tiempos de consulta e integrar métricas objetivas a la historia clínica.

---

#### Segmento objetivo 3 - Técnicos Ortoprotesistas

### Entrevista 1 – Miguel Sanchez

* **Nombres y Apellidos:** Miguel Sanchez Castillo
* **Edad:** 57 años
* **Ocupación:** Protesista-ortesista (Director técnico de taller en Pueblo Libre)
* **Fecha de entrevista:** 09/09/2026 | **Duración:** 5:24
* **Enlace:** https://tinyurl.com/2asw539n

![](../SeniorsInProcess-Pandoc/assets/entrevista_Segmento3.png){ width=80% }

**Resumen de la entrevista:**  
Miguel dirige un taller con una producción de 10 a 15 prótesis al mes. Reconoce que el mantenimiento actual es totalmente reactivo: los usuarios solo acuden cuando una pieza se rompe. Respaldaría firmemente el pago de una licencia de software que le permita ver horas de uso y pasos reales para validar garantías con datos objetivos y agendar revisiones preventivas.

\

### Entrevista 2 – Juan Carlos Salcedo

* **Nombres y Apellidos:** Juan Carlos Salcedo
* **Edad:** 47 años
* **Ocupación:** Técnico ortoprotesista (Taller en Av. 28 de Julio, Lima)
* **Fecha de entrevista:** 16/09/2026 | **Duración:** 5:36
* **Enlace:** https://tinyurl.com/bdhm2vcm

![](../SeniorsInProcess-Pandoc/assets/Entrevista2_Segmento3.png){ width=80% }

**Resumen de la entrevista:**  
Especialista enfocado en el cuidado biomecánico del muñón y la fluctuación volumétrica a lo largo del día. Destaca la necesidad de monitorear horas de caminata y pasos diarios. Advierte que muchos pacientes son personas adultas mayores con amputaciones diabéticas, por lo que el sistema debe ser intuitivo tanto para el usuario como para sus familiares.

\

### Entrevista 3 – Jose Riveros Veliz

* **Nombres y Apellidos:** Jose Riveros Veliz
* **Edad:** 30 años
* **Ocupación:** Técnico ortoprotesista (Encargado de taller en Lima)
* **Fecha de entrevista:** 16/09/2026 | **Duración:** 4:20
* **Enlace:** https://tinyurl.com/2p4uysyj

![](../SeniorsInProcess-Pandoc/assets/Entrevista3_Segmento3.png){ width=80% }

**Resumen de la entrevista:**  
José produce entre 4 y 6 prótesis mensuales y efectúa alineaciones continuas. Ha utilizado software de marcas específicas para rodillas mecatrónicas pero critica su condición cerrada. Demanda una plataforma multimarca con alertas de fatiga de materiales y trazabilidad por número de serie, compatible con computadoras y smartphones para pruebas en pista de marcha.

---

### 2.2.3. Análisis de entrevistas

**Segmento 1: Pacientes Amputados**
* El 100% (3/3) son varones entre 25 y 30 años residentes en Lima, que realizan teletrabajo y usan prótesis mecánicas de extremidad inferior.
* El 100% espacia sus visitas clínicas por costos y traslados en transporte público.
* El 100% experimenta fatiga, dolor lumbar por compensación asimétrica y falta de supervisión en sus rutinas caseras.
* Exigen interfaces móviles sencillas, sin saturación publicitaria ni drenaje excesivo de batería y datos móviles.

**Segmento 2: Profesionales de Rehabilitación**
* Promedio de 18.3 años de experiencia en el área de medicina física. Atienden entre 15 y 20 pacientes amputados de forma continua.
* El 100% depende del testimonio verbal del paciente para el seguimiento ambulatorio.
* Valoran la creación de dashboards con alertas tempranas, semáforos de riesgo y exportación de reportes clínicos.
* Demandan soporte en PC de escritorio para historia clínica y en tabletas para evaluaciones físicas dinámicas.

**Segmento 3: Técnicos Ortoprotesistas**
* Promedio de 44.7 años. Fabrican entre 4 y 15 dispositivos al mes.
* El 100% opera bajo un modelo de mantenimiento correctivo/reactivo por falta de telemetría de uso.
* El 66.7% tiene total disposición a pagar licencias de software que aporten trazabilidad técnica y justifiquen garantías de componentes.
* Requieren métricas de conteo de pasos, horas de esfuerzo mecánico y alertas preventivas multimarca.

---

## 2.3. Needfinding

### 2.3.1. User Personas

**Segmento 1: Carlos Mendoza (Paciente Amputado)**  
![](../SeniorsInProcess-Pandoc/assets/UP-Carlos%20Mendoza.png){ width=100% }

\

**Segmento 2: Valeria Rios (Jefa de Fisioterapia y Rehabilitación)**  
![](../SeniorsInProcess-Pandoc/assets/Valeria%20Rios.png){ width=100% }

\

**Segmento 3: Miguel Torres (Técnico Ortoprotésico)**  
![](../SeniorsInProcess-Pandoc/assets/Miguel%20Torres.png){ width=100% }

---

### 2.3.2. User Task Matrix

```{=typst}
#set text(size: 7.5pt)
#set table(
  columns: (3fr, 1.2fr, 1.2fr, 1.2fr, 1.2fr, 1.2fr, 1.2fr),
  stroke: 0.5pt + luma(180),
  inset: 4.5pt
)
```

| Tarea (Task) | Paciente Frec. | Paciente Imp. | Terapeuta Frec. | Terapeuta Imp. | Ortoprotésico Frec. | Ortoprotésico Imp. |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1. Colocación, ajuste e inspección del encaje y muñón | Muy alta | Crítica | Baja | Alta | Baja | Alta |
| 2. Ejecución de ejercicios de fortalecimiento y marcha | Alta | Crítica | Rara vez | Media | Rara vez | Baja |
| 3. Monitoreo y autoobservación postural para evitar vicios | Muy alta | Crítica | Baja | Media | Rara vez | Baja |
| 4. Registro y reporte de sensaciones de dolor o fatiga | Alta | Alta | Media | Alta | Baja | Media |
| 5. Asistencia a sesiones presenciales de fisioterapia | Media | Alta | Alta | Crítica | Rara vez | Baja |
| 6. Evaluación biomecánica presencial de postura y apoyo | Rara vez | Alta | Alta | Crítica | Baja | Alta |
| 7. Prescripción y ajuste de planes de ejercicio terapéutico | Rara vez | Media | Alta | Crítica | Rara vez | Baja |
| 8. Revisión y análisis de la evolución clínica del paciente | Baja | Media | Alta | Crítica | Rara vez | Media |
| 9. Documentación y actualización del historial clínico | Rara vez | Baja | Alta | Alta | Rara vez | Baja |
| 10. Fabricación, adaptación, alineación y entrega de prótesis | Rara vez | Crítica | Rara vez | Alta | Media | Crítica |
| 11. Evaluación del desgaste físico y holguras mecánicas | Baja | Media | Rara vez | Media | Media | Crítica |
| 12. Mantenimiento preventivo y cambio de consumibles | Rara vez | Alta | Rara vez | Baja | Media | Crítica |
| 13. Calibración mecánica de articulaciones y alineación | Rara vez | Alta | Rara vez | Media | Media | Crítica |
| 14. Registro y trazabilidad de componentes entregados | Rara vez | Baja | Rara vez | Baja | Alta | Alta |
| 15. Coordinación interinstitucional clínica–ortopedia | Baja | Media | Media | Alta | Media | Alta |
| 16. Traslado físico hacia los centros de atención | Media | Media | Rara vez | Baja | Rara vez | Baja |

```{=typst}
#set text(size: 11pt)
```

---

### 2.3.3. User Journey Mapping

**Segmento 1: Carlos Mendoza**  
![](../SeniorsInProcess-Pandoc/assets/JM-Carlos%20Mendoza.png){ width=100% }

\

**Segmento 2: Valeria Rios**  
![](../SeniorsInProcess-Pandoc/assets/JM-Valeria%20Rios.png){ width=100% }

\

**Segmento 3: Miguel Torres**  
![](../SeniorsInProcess-Pandoc/assets/JM-Miguel%20Torres.png){ width=100% }

---

### 2.3.4. Empathy Mapping

**Segmento 1: Carlos Mendoza**  
![](../SeniorsInProcess-Pandoc/assets/EM-CarlosMendoza.png){ width=100% }

\

**Segmento 2: Valeria Rios**  
![](../SeniorsInProcess-Pandoc/assets/EM-ValeriaRios.png){ width=100% }

\

**Segmento 3: Miguel Torres**  
![](../SeniorsInProcess-Pandoc/assets/EM-MiguelTorres.png){ width=100% }

---

## 2.4. Big Picture EventStorming

**1- Colocación de eventos del dominio (tarjetas naranjas):**  
![](../SeniorsInProcess-Pandoc/assets/fase1.png){ width=100% }

\

**2- Ordenamiento de los eventos en secuencia cronológica:**  
![](../SeniorsInProcess-Pandoc/assets/fase2.png){ width=100% }

\

**3- Colocación de actores (tarjetas amarillas) y sistemas externos (tarjetas azules):**  
![](../SeniorsInProcess-Pandoc/assets/fase3.png){ width=100% }

\

**4- Identificación de problemas en la secuencia (tarjetas rosadas):**  
![](../SeniorsInProcess-Pandoc/assets/fase4.png){ width=100% }

\

* **Procesos clave:** Fabricación y entrega de prótesis, evaluación clínica y prescripción, ejecución de rutinas caseras y detección de daños para mantenimiento.
* **Problemas:** Ceguera clínica fuera de consulta, reporte subjetivo por WhatsApp, mantenimiento puramente reactivo y datos dispersos.
* **Oportunidades:** Telemetría biomecánica en tiempo real, alertas de compensación muscular, historial unificado de mantenimiento y comunicación directa interinstitucional.

*Tablero Miro:* https://miro.com/app/board/uXjVGbuSqec=/?share_link_id=610103626578

---

## 2.5. Ubiquitous Language

```{=typst}
#set table(
  columns: (1.3fr, 3fr),
  stroke: 0.5pt + luma(180),
  inset: 6pt
)
```

| Término | Definición |
| :--- | :--- |
| **Amputee Patient** | Persona que ha sufrido una amputación, utiliza una prótesis y participa en un proceso de adaptación y rehabilitación. |
| **Rehabilitation Clinic** | Institución o equipo profesional responsable de evaluar, planificar y realizar seguimiento al proceso de rehabilitación del paciente. |
| **Orthopedic Center** | Establecimiento especializado en la fabricación, adaptación, revisión y mantenimiento de prótesis. |
| **Prosthesis** | Dispositivo utilizado por el paciente para sustituir total o parcialmente una extremidad y apoyar su movilidad. |
| **Rehabilitation Plan** | Conjunto de objetivos y actividades definidas para acompañar la recuperación y adaptación del paciente. |
| **Exercise Plan** | Conjunto de ejercicios asignados a un paciente, incluyendo frecuencia y repeticiones esperadas. |
| **Exercise Completion** | Registro que indica que un paciente realizó un ejercicio perteneciente a su plan vigente. |
| **Adherence** | Nivel de cumplimiento del paciente respecto de los ejercicios y actividades indicadas en su plan de rehabilitación. |
| **Biomechanical Data** | Información obtenida durante el movimiento o uso de la prótesis y utilizada para analizar el desempeño del paciente. |
| **Biomechanical Session** | Periodo de actividad durante el cual se recopilan y procesan datos biomecánicos relacionados con un paciente. |
| **Posture Assessment** | Evaluación del movimiento o postura del paciente a partir de datos biomecánicos y parámetros establecidos. |
| **Biomechanical History** | Conjunto cronológico de registros biomecánicos asociados a un paciente. |
| **Rehabilitation Progress** | Evolución del paciente a partir del cumplimiento de ejercicios y la información registrada durante su rehabilitación. |
| **Clinical Alert** | Aviso generado cuando se identifica una condición biomecánica que requiere la revisión de un profesional de la clínica. |
| **Alert Threshold** | Valor o rango configurado para determinar cuándo un indicador biomecánico debe generar una alerta. |
| **Technical History** | Registro de intervenciones, revisiones y observaciones realizadas sobre una prótesis. |
| **Maintenance** | Actividad de revisión, ajuste o intervención realizada para conservar el funcionamiento adecuado de una prótesis. |
| **Preventive Maintenance** | Mantenimiento programado antes de la aparición de una falla, según fecha o condiciones de uso. |
| **Maintenance Alert** | Aviso dirigido al centro ortopédico cuando una prótesis alcanza una condición que requiere revisión o mantenimiento. |
| **Patient Information Sharing** | Acción mediante la cual la clínica habilita información relevante del paciente al centro ortopédico responsable de su prótesis. |
| **Biomechanical Monitoring** | Seguimiento de información biomecánica generada durante el uso de la prótesis y las actividades de rehabilitación. |
| **Prosthesis Usage** | Información relacionada con el uso acumulado y condiciones de utilización de una prótesis. |

```{=typst}
#pagebreak()
```
