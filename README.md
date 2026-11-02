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

```{=typst}
#outline(
  title: none,
  depth: 3,
  indent: auto
)
```
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
```{=typst}
#pagebreak()
```

# Capítulo III: Requirements Specification

## 3.1. User Stories

Las historias de usuario para este proyecto se crearon en colaboración con el equipo de desarrollo, enfocándose en las necesidades principales de tres tipos de usuarios: paciente amputado, la clínica de rehabilitación y el centro ortopédico. Para mantener la organización, las historias se agruparon en épicas según sus funcionalidades y los criterios de aceptación se definieron utilizando la sintaxis Gherkin.

```{=typst}
#set text(size: 7.2pt)
#set table(
  columns: (1fr, 1.8fr, 2.5fr, 4.5fr, 0.8fr),
  stroke: 0.5pt + luma(180),
  inset: 4pt
)
```

| Epic / Story ID | Título | Descripción | Criterios de Aceptación (Gherkin) | Epic ID |
| :--- | :--- | :--- | :--- | :--- |
| **EP-01** | **Gestión de Pacientes y Prótesis** | Registro y administración de información de pacientes y prótesis vinculadas a clínicas y centros ortopédicos. | Gestión base de usuarios clínicos y dispositivos. | EP-01 |
| **US-01** | Registro de datos del paciente en la clínica | Como profesional de clínica, quiero registrar los datos clínicos de un paciente amputado para llevar un control de su proceso de rehabilitación. | **Escenario 1: Registro exitoso**\ • **Dado que** el profesional ingresa los datos obligatorios,\ • **Cuando** confirma el registro,\ • **Entonces** el paciente queda asociado a la clínica.\ \ **Escenario 2: Datos incompletos**\ • **Dado que** omite un dato obligatorio,\ • **Cuando** intenta confirmar,\ • **Entonces** el sistema muestra error y no guarda. | EP-01 |
| **US-02** | Asociación de prótesis a un paciente | Como técnico ortopédico, quiero asociar una prótesis a un paciente para llevar el registro de qué dispositivo utiliza. | **Escenario 1: Asociación exitosa**\ • **Dado que** selecciona un paciente y prótesis disponible,\ • **Cuando** confirma la asociación,\ • **Entonces** queda vinculada.\ \ **Escenario 2: Ya asociada**\ • **Dado que** la prótesis está asignada a otro usuario,\ • **Cuando** intenta asociar,\ • **Entonces** el sistema avisa que no está disponible. | EP-01 |
| **US-03** | Consulta de ficha del paciente | Como profesional de clínica, quiero consultar la ficha de un paciente para conocer su historial clínico y de prótesis. | **Escenario 1: Consulta exitosa**\ • **Dado que** selecciona un paciente de su clínica,\ • **Cuando** accede a su ficha,\ • **Entonces** visualiza datos clínicos y de prótesis.\ \ *Regla:* Solo personal autorizado accede al registro. | EP-01 |
| **EP-02** | **Monitoreo Biomecánico en Tiempo Real** | Recopilación, procesamiento y visualización de datos biomecánicos fuera de la clínica. | Telemetría y cinemática en tiempo real. | EP-02 |
| **US-04** | Visualización del dashboard biomecánico | Como profesional de clínica, quiero visualizar un dashboard con los datos biomecánicos recientes para evaluar su desempeño. | **Escenario 1: Datos disponibles**\ • **Dado que** existen registros cinemáticos,\ • **Cuando** entra al panel,\ • **Entonces** visualiza las métricas recientes.\ \ **Escenario 2: Sin datos**\ • **Dado que** no hay actividad,\ • **Cuando** entra al panel,\ • **Entonces** notifica ausencia de información. | EP-02 |
| **US-05** | Consulta del historial de datos biomecánicos | Como paciente, quiero consultar el historial de mis datos biomecánicos para conocer la evolución de mi desempeño. | **Escenario 1: Historial disponible**\ • **Dado que** tiene registros previos,\ • **Cuando** abre su historial,\ • **Entonces** se muestran cronológicamente.\ \ **Escenario 2: Filtro por fecha**\ • **Dado que** elige un rango,\ • **Cuando** filtra,\ • **Entonces** muestra solo ese periodo. | EP-02 |
| **US-06** | Identificación de postura o movimiento inadecuado | Como paciente, quiero recibir información sobre si mi postura fue adecuada para corregir mi marcha. | **Escenario 1: Postura inadecuada**\ • **Dado que** el sistema procesa la sesión,\ • **Cuando** detecta valores fuera de rango,\ • **Entonces** alerta de postura inadecuada.\ \ **Escenario 2: Postura correcta**\ • **Dado que** los valores son normales,\ • **Cuando** evalúa,\ • **Entonces** valida la postura adecuada. | EP-02 |
| **EP-03** | **Seguimiento de Rehabilitación y Ejercicios** | Asignación, registro y seguimiento de los planes terapéuticos en el hogar. | Cumplimiento y adherencia al tratamiento. | EP-03 |
| **US-07** | Asignación de plan de ejercicios | Como profesional de clínica, quiero asignar un plan personalizado para guiar la rehabilitación en casa. | **Escenario 1: Asignación exitosa**\ • **Dado que** define ejercicios y frecuencia,\ • **Cuando** confirma,\ • **Entonces** vincula el plan al paciente.\ \ **Escenario 2: Plan vacío**\ • **Dado que** no incluye ejercicios,\ • **Cuando** intenta guardar,\ • **Entonces** exige al menos un ejercicio. | EP-03 |
| **US-08** | Registro de cumplimiento de ejercicios | Como paciente, quiero registrar la realización de ejercicios para evidenciar mi adherencia. | **Escenario 1: Registro exitoso**\ • **Dado que** completa un ejercicio,\ • **Cuando** lo marca,\ • **Entonces** actualiza el estado a realizado.\ \ **Escenario 2: Fuera de plan**\ • **Dado que** intenta marcar un ejercicio ajeno a su plan,\ • **Cuando** guarda,\ • **Entonces** rechaza la acción. | EP-03 |
| **US-09** | Consulta del progreso de rehabilitación | Como profesional de clínica, quiero consultar el progreso de mis pacientes para evaluar la efectividad terapéutica. | **Escenario 1: Progreso disponible**\ • **Dado que** hay datos de cumplimiento,\ • **Cuando** consulta el progreso,\ • **Entonces** visualiza tasa de adherencia.\ \ **Escenario 2: Sin registros**\ • **Dado que** el paciente no ha registrado rutinas,\ • **Cuando** revisa,\ • **Entonces** alerta sin progreso. | EP-03 |
| **EP-04** | **Sistema de Alertas y Notificaciones** | Generación de alertas automáticas ante patrones lesivos o compensaciones musculares. | Triaje clínico preventivo. | EP-04 |
| **US-10** | Recepción de alerta por postura incorrecta | Como profesional de clínica, quiero recibir una alerta cuando se detecte una postura incorrecta para intervenir a tiempo. | **Escenario 1: Alerta generada**\ • **Dado que** detecta un patrón anómalo,\ • **Cuando** se crea el evento,\ • **Entonces** notifica al profesional.\ \ **Escenario 2: Cinemática normal**\ • **Dado que** todo está en rango,\ • **Cuando** evalúa,\ • **Entonces** no emite alerta. | EP-04 |
| **US-11** | Configuración de umbrales de alerta | Como profesional de clínica, quiero configurar los umbrales para adaptar el sistema a cada paciente. | **Escenario 1: Configuración exitosa**\ • **Dado que** define nuevos límites biomecánicos,\ • **Cuando** guarda cambios,\ • **Entonces** aplica a sesiones futuras.\ \ *Regla:* Modificable solo por personal autorizado. | EP-04 |
| **US-12** | Consulta del historial de alertas | Como profesional de clínica, quiero consultar el historial de alertas para revisar los eventos críticos. | **Escenario 1: Historial con alertas**\ • **Dado que** existen eventos registrados,\ • **Cuando** entra al módulo,\ • **Entonces** lista por fecha.\ \ **Escenario 2: Sin alertas**\ • **Dado que** no hay incidentes,\ • **Cuando** entra,\ • **Entonces** notifica sin novedades. | EP-04 |
| **EP-05** | **Gestión de Mantenimiento de Prótesis** | Historial técnico y programación de mantenimiento preventivo para ortopedias. | Ciclo de vida y telemetría de piezas. | EP-05 |
| **US-13** | Registro de historial técnico de la prótesis | Como técnico ortopédico, quiero registrar intervenciones para controlar piezas y desgastes. | **Escenario 1: Registro exitoso**\ • **Dado que** ingresa datos de mantenimiento,\ • **Cuando** guarda,\ • **Entonces** actualiza el historial técnico.\ \ **Escenario 2: Campos vacíos**\ • **Dado que** omite campos requeridos,\ • **Cuando** intenta guardar,\ • **Entonces** solicita completar datos. | EP-05 |
| **US-14** | Programación de mantenimiento preventivo | Como técnico ortopédico, quiero agendar fechas de revisión para anticiparme a fallas. | **Escenario 1: Agendamiento exitoso**\ • **Dado que** selecciona una fecha futura,\ • **Cuando** confirma,\ • **Entonces** agenda el mantenimiento.\ \ **Escenario 2: Fecha pasada**\ • **Dado que** selecciona una fecha anterior a hoy,\ • **Cuando** intenta guardar,\ • **Entonces** alerta fecha inválida. | EP-05 |
| **US-15** | Recepción de alerta de mantenimiento | Como técnico ortopédico, quiero recibir alertas por horas de uso acumulado para prevenir daños. | **Escenario 1: Alerta por desgaste**\ • **Dado que** el uso supera el límite fijado,\ • **Cuando** evalúa telemetría,\ • **Entonces** envía alerta al taller.\ \ **Escenario 2: Desgaste normal**\ • **Dado que** está dentro de vida útil,\ • **Cuando** procesa,\ • **Entonces** no emite aviso. | EP-05 |
| **EP-06** | **Comunicación entre Actores** | Mensajería estructurada entre paciente, clínica y taller ortopédico. | Interoperabilidad e intercambio seguro. | EP-06 |
| **US-16** | Envío de mensajes paciente-clínica | Como paciente, quiero enviar mensajes a mi clínica para resolver dudas de tratamiento. | **Escenario 1: Mensaje enviado**\ • **Dado que** redacta una consulta,\ • **Cuando** presiona enviar,\ • **Entonces** se entrega al terapeuta.\ \ **Escenario 2: Mensaje vacío**\ • **Dado que** no escribe texto,\ • **Cuando** envía,\ • **Entonces** impide el envío. | EP-06 |
| **US-17** | Compartir información con la ortopedia | Como profesional de clínica, quiero compartir datos de evolución con el taller para coordinar ajustes. | **Escenario 1: Envío exitoso**\ • **Dado que** selecciona métricas clínicas,\ • **Cuando** autoriza el envío,\ • **Entonces** el taller accede a los datos.\ \ *Regla:* Solo con la ortopedia asignada al paciente. | EP-06 |
| **US-18** | Consulta de notificaciones generales | Como usuario, quiero ver mis notificaciones generales para mantenerme al día de mi cuenta. | **Escenario 1: Notificaciones pendientes**\ • **Dado que** hay avisos pendientes,\ • **Cuando** abre la bandeja,\ • **Entonces** se listan ordenadas.\ \ **Escenario 2: Sin avisos**\ • **Dado que** no hay novedades,\ • **Cuando** entra,\ • **Entonces** muestra bandeja vacía. | EP-06 |
| **EP-07** | **Suscripciones y Licenciamiento** | Planes anuales para clínicas y licencias de software para ortopedias. | Monetización y control de accesos B2B. | EP-07 |
| **US-19** | Contratación de suscripción anual | Como administrador de clínica, quiero pagar la suscripción anual para dar acceso a mis pacientes. | **Escenario 1: Pago aprobado**\ • **Dado que** completa la transacción con éxito,\ • **Cuando** valida pasarela,\ • **Entonces** activa la cuenta institucional.\ \ **Escenario 2: Pago rechazado**\ • **Dado que** falla el cobro,\ • **Cuando** procesa,\ • **Entonces** notifica error de pago. | EP-07 |
| **US-20** | Adquisición de licencia de software | Como administrador de ortopedia, quiero comprar una licencia técnica para gestionar prótesis. | **Escenario 1: Compra exitosa**\ • **Dado que** selecciona plan y paga,\ • **Cuando** valida,\ • **Entonces** activa el módulo de taller.\ \ **Escenario 2: Licencia vigente**\ • **Dado que** ya cuenta con una activa,\ • **Cuando** intenta comprar,\ • **Entonces** alerta que ya posee licencia. | EP-07 |
| **US-21** | Consulta de estado de licencia | Como administrador, quiero consultar la vigencia de mi contrato para prever renovaciones. | **Escenario 1: Licencia activa**\ • **Dado que** el plan está vigente,\ • **Cuando** consulta,\ • **Entonces** muestra fecha de vencimiento.\ \ **Escenario 2: Vencida**\ • **Dado que** expiró,\ • **Cuando** ingresa,\ • **Entonces** solicita renovación. | EP-07 |
| **EP-08** | **Landing Page y Captación** | Sitio web estático informativo para difundir valor y captar prospectos B2B. | Conversión, difusión y contacto comercial. | EP-08 |
| **US-22** | Métricas e impacto en el Hero | Como visitante, quiero leer la propuesta central e indicadores en la cabecera para entender el producto. | **Escenario 1: Carga visual**\ • **Dado que** entra a la web,\ • **Cuando** visualiza el Hero,\ • **Entonces** muestra resumen e impacto.\ \ **Escenario 2: Botón de acción**\ • **Dado que** hace clic en registro,\ • **Cuando** presiona,\ • **Entonces** baja hacia el formulario. | EP-08 |
| **US-23** | Problemática de rehabilitación | Como visitante, quiero informarme de la falta de seguimiento para comprender qué soluciona Prothia. | **Escenario 1: Lectura de retos**\ • **Dado que** navega por desafíos,\ • **Cuando** revisa los paneles,\ • **Entonces** expone la falta de datos y desgaste. | EP-08 |
| **US-24** | Ecosistema colaborativo | Como visitante, quiero visualizar cómo interactúan paciente, clínica y taller en la plataforma. | **Escenario 1: Diagrama interactivo**\ • **Dado que** llega al ecosistema,\ • **Cuando** explora el gráfico,\ • **Entonces** ilustra el flujo integral. | EP-08 |
| **US-25** | Solución para clínicas | Como terapeuta visitante, quiero ver las herramientas clínicas para evaluar su utilidad asistencial. | **Escenario 1: Pestaña clínica**\ • **Dado que** elige vista clínica,\ • **Cuando** abre detalle,\ • **Entonces** exhibe expedientes y telemetría. | EP-08 |
| **US-26** | Solución para ortopedias | Como ortoprotesista visitante, quiero revisar las herramientas de taller para gestionar prótesis. | **Escenario 1: Pestaña taller**\ • **Dado que** elige vista taller,\ • **Cuando** abre detalle,\ • **Entonces** muestra alertas y trazabilidad. | EP-08 |
| **US-27** | Solución para pacientes | Como paciente visitante, quiero conocer las ventajas de entrenar con el sistema en casa. | **Escenario 1: Pestaña paciente**\ • **Dado que** elige vista paciente,\ • **Cuando** abre detalle,\ • **Entonces** destaca biofeedback y soporte. | EP-08 |
| **US-28** | Catálogo de herramientas clave | Como visitante, quiero explorar las funciones técnicas para validar la precisión del sistema. | **Escenario 1: Tarjetas técnicas**\ • **Dado que** entra a herramientas,\ • **Cuando** lee tarjetas,\ • **Entonces** detalla cadencia, simetría y apoyo. | EP-08 |
| **US-29** | Video demostrativo | Como visitante, quiero ver un video de prueba para comprobar el funcionamiento real del sistema. | **Escenario 1: Reproducción en sitio**\ • **Dado que** accede al bloque de video,\ • **Cuando** da play,\ • **Entonces** reproduce el clip en la página. | EP-08 |
| **US-30** | Comparador de precios | Como visitante, quiero alternar entre cobro mensual y anual para calcular mi presupuesto. | **Escenario 1: Alternar ciclo**\ • **Dado que** conmuta el selector,\ • **Cuando** alterna,\ • **Entonces** muestra precios y descuento anual.\ \ **Escenario 2: Selección de plan**\ • **Dado que** elige contratar,\ • **Cuando** hace clic,\ • **Entonces** redirige al formulario de compra. | EP-08 |
| **US-31** | Respaldo institucional | Como visitante, quiero conocer los estándares científicos que avalan el sistema. | **Escenario 1: Rigor técnico**\ • **Dado que** entra a respaldo,\ • **Cuando** lee la sección,\ • **Entonces** presenta normativas y seguridad. | EP-08 |
| **US-32** | Testimonios clínicos | Como visitante, quiero leer opiniones de médicos y usuarios para validar la experiencia del producto. | **Escenario 1: Fichas de testimonios**\ • **Dado que** baja a testimonios,\ • **Cuando** revisa citas,\ • **Entonces** muestra cargos e instituciones. | EP-08 |
| **US-33** | Preguntas frecuentes (FAQ) | Como visitante, quiero revisar las dudas habituales para resolver consultas inmediatas. | **Escenario 1: Acordeón interactivo**\ • **Dado que** selecciona una duda,\ • **Cuando** hace clic,\ • **Entonces** despliega la respuesta.\ \ **Escenario 2: Colapso**\ • **Dado que** vuelve a dar clic,\ • **Cuando** presiona,\ • **Entonces** oculta el texto. | EP-08 |
| **US-34** | Formulario de contacto comercial | Como directivo de clínica, quiero enviar mis datos para agendar una demostración en vivo. | **Escenario 1: Envío exitoso**\ • **Dado que** completa los campos requeridos,\ • **Cuando** envía,\ • **Entonces** registra el lead y confirma.\ \ **Escenario 2: Campos incompletos**\ • **Dado que** faltan datos,\ • **Cuando** envía,\ • **Entonces** marca campos obligatorios. | EP-08 |
| **US-35** | Suscripción a newsletter | Como visitante, quiero registrar mi email para recibir artículos sobre biomecánica. | **Escenario 1: Suscripción válida**\ • **Dado que** ingresa email nuevo,\ • **Cuando** suscribe,\ • **Entonces** confirma registro exitoso.\ \ **Escenario 2: Email repetido**\ • **Dado que** ya estaba registrado,\ • **Cuando** envía,\ • **Entonces** notifica duplicidad. | EP-08 |
| **US-36** | Selector de idioma (ES/EN) | Como visitante, quiero cambiar entre inglés y español para leer en mi idioma de preferencia. | **Escenario 1: Alternancia idiomática**\ • **Dado que** elige el idioma deseado,\ • **Cuando** conmuta,\ • **Entonces** traduce la página al instante.\ \ *Regla:* Persiste durante toda la sesión. | EP-08 |
| **US-37** | Políticas de privacidad y seguridad | Como visitante, quiero revisar las normas de confidencialidad médica y cifrado de datos. | **Escenario 1: Enlace en footer**\ • **Dado que** baja al pie de página,\ • **Cuando** hace clic en privacidad,\ • **Entonces** exhibe normas AES-256 y WCAG. | EP-08 |
| **EP-09** | **Reportes y Analítica** | Generación de reportes clínicos e indicadores consolidados de evolución. | Business Intelligence y trazabilidad médica. | EP-09 |
| **US-38** | Reporte de progreso del paciente | Como profesional de clínica, quiero generar reportes para documentar la evolución del tratamiento. | **Escenario 1: Generación exitosa**\ • **Dado que** hay datos suficientes,\ • **Cuando** genera reporte,\ • **Entonces** descarga documento médico.\ \ **Escenario 2: Sin datos**\ • **Dado que** faltan registros,\ • **Cuando** solicita,\ • **Entonces** notifica información insuficiente. | EP-09 |
| **US-39** | Exportación de datos históricos | Como profesional de clínica, quiero exportar datos para interconsultas médicas. | **Escenario 1: Exportación exitosa**\ • **Dado que** define rango de fechas válido,\ • **Cuando** exporta,\ • **Entonces** descarga archivo estructurado.\ \ **Escenario 2: Rango vacío**\ • **Dado que** no hay datos en el rango,\ • **Cuando** exporta,\ • **Entonces** notifica sin registros. | EP-09 |
| **US-40** | Indicadores globales de la clínica | Como médico director, quiero ver analíticas agregadas para evaluar el rendimiento global. | **Escenario 1: Métricas activas**\ • **Dado que** la clínica tiene pacientes,\ • **Cuando** abre analíticas,\ • **Entonces** muestra KPIs consolidados.\ \ **Escenario 2: Sin pacientes**\ • **Dado que** es nueva,\ • **Cuando** entra,\ • **Entonces** muestra panel vacío. | EP-09 |
| **TS-01** | Endpoints de pacientes y prótesis | Como developer, implementar la API RESTful para gestión de usuarios y prótesis. | **Escenario 1: POST exitoso (200 OK)**\ • **Dado que** envía solicitud con datos válidos,\ • **Cuando** el servidor procesa,\ • **Entonces** confirma la asociación.\ \ **Escenario 2: Prótesis ocupada (409 Conflict)**\ • **Dado que** ya está asignada,\ • **Cuando** procesa,\ • **Entonces** rechaza por conflicto. | EP-01 |
| **TS-02** | Ingesta de datos biomecánicos | Como developer, implementar el endpoint RESTful de recepción telemétrica de sensores. | **Escenario 1: Ingesta exitosa (201 Created)**\ • **Dado que** envía carga útil válida,\ • **Cuando** procesa,\ • **Entonces** persiste y retorna 201.\ \ **Escenario 2: Formato inválido (400 Bad Request)**\ • **Dado que** el payload es erróneo,\ • **Cuando** valida,\ • **Entonces** responde con 400. | EP-02 |
| **TS-03** | Endpoints de planes de ejercicio | Como developer, implementar la API para asignación y control de cumplimiento de rutinas. | **Escenario 1: PUT exitoso (200 OK)**\ • **Dado que** envía actualización de ejercicio válido,\ • **Cuando** procesa,\ • **Entonces** actualiza estado a 200.\ \ **Escenario 2: Ejercicio inválido (400 Bad Request)**\ • **Dado que** no pertenece al plan,\ • **Cuando** intenta actualizar,\ • **Entonces** responde 400. | EP-03 |
| **TS-04** | API de alertas críticas | Como developer, implementar endpoints para activar notificaciones automáticas ante eventos de riesgo. | **Escenario 1: Emisión exitosa**\ • **Dado que** detecta evento crítico,\ • **Cuando** invoca servicio de alerta,\ • **Entonces** notifica al profesional.\ \ **Escenario 2: Notificaciones inactivas**\ • **Dado que** el servicio está deshabilitado,\ • **Cuando** ocurre alerta,\ • **Entonces** solo guarda en log histórico. | EP-04 |
| **TS-05** | API de mantenimiento de prótesis | Como developer, implementar servicios RESTful para registrar mantenimientos de taller. | **Escenario 1: POST exitoso (201 Created)**\ • **Dado que** fecha de mantenimiento es futura,\ • **Cuando** registra,\ • **Entonces** guarda y retorna 201.\ \ **Escenario 2: Fecha pasada (400 Bad Request)**\ • **Dado que** la fecha ya ocurrió,\ • **Cuando** valida,\ • **Entonces** rechaza con 400. | EP-05 |
| **TS-06** | Endpoints de mensajería | Como developer, implementar servicios RESTful para intercambio de mensajes entre roles. | **Escenario 1: Envío exitoso (201 Created)**\ • **Dado que** remitente y receptor existen,\ • **Cuando** procesa,\ • **Entonces** persiste mensaje y retorna 201.\ \ **Escenario 2: Destinatario inexistente (404 Not Found)**\ • **Dado que** el ID no existe,\ • **Cuando** procesa,\ • **Entonces** responde con 404. | EP-06 |
| **TS-07** | API de suscripciones y pagos | Como developer, implementar endpoints para validar compras y estado de planes B2B. | **Escenario 1: Activación exitosa (201 Created)**\ • **Dado que** pasarela aprueba transacción,\ • **Cuando** procesa,\ • **Entonces** habilita licencia a la cuenta.\ \ **Escenario 2: Pago rechazado (402 Payment Required)**\ • **Dado que** el banco deniega fondos,\ • **Cuando** procesa,\ • **Entonces** responde con 402. | EP-07 |
| **TS-08** | Ingesta de formularios web | Como developer, exponer endpoints públicos para captar prospectos y registros de la Landing. | **Escenario 1: Demo exitosa (201 Created)**\ • **Dado que** envía datos válidos a /api/v1/leads,\ • **Cuando** almacena lead,\ • **Entonces** retorna 201 e ID de trámite.\ \ **Escenario 2: Email repetido (409 Conflict)**\ • **Dado que** ya existe en base de datos,\ • **Cuando** verifica,\ • **Entonces** responde con 409. | EP-08 |
| **TS-09** | API de reportes analíticos | Como developer, implementar endpoints de agregación y descarga de archivos clínicos. | **Escenario 1: Descarga exitosa (200 OK)**\ • **Dado que** paciente tiene historial en rango,\ • **Cuando** procesa,\ • **Entonces** retorna archivo descargable.\ \ **Escenario 2: Sin datos (204 No Content)**\ • **Dado que** el periodo está vacío,\ • **Cuando** procesa,\ • **Entonces** retorna código 204. | EP-09 |

```{=typst}
#set text(size: 11pt)
```

---

## 3.2. Impact Mapping

El equipo desarrolló un Impact Mapping en colaboración utilizando la herramienta UXPressia para conectar las metas de negocio directamente con los requerimientos funcionales de la plataforma:

![](../SeniorsInProcess-Pandoc/assets/Impact%20map.png){ width=100% }

---

## 3.3. Product Backlog

Para mantener el proyecto organizado, se empleó la escala de Fibonacci (1, 2, 3, 5, 8) para estimar el esfuerzo de cada historia y tarea técnica:

* **1:** Tareas sencillas y rápidas.
* **2:** Tareas de complejidad moderada.
* **3:** Tareas que requieren más tiempo y esfuerzo.
* **5:** Tareas complejas que abarcan múltiples capas de software.
* **8:** Tareas de muy alta complejidad técnica o de integración.

```{=typst}
#set text(size: 8.5pt)
#set table(
  columns: (0.8fr, 1.2fr, 4fr, 5fr, 1.2fr),
  stroke: 0.5pt + luma(180),
  inset: 5pt
)
```

| # Orden | ID | Título | Descripción | Puntos |
| :---: | :---: | :--- | :--- | :---: |
| 1 | US-22 | Propuesta de valor en Hero | Como visitante, quiero consultar la propuesta de valor y las métricas de impacto en la cabecera. | 2 |
| 2 | US-23 | Problemática de rehabilitación | Como visitante, quiero informarme sobre la brecha existente en el seguimiento de prótesis. | 1 |
| 3 | US-24 | Ecosistema colaborativo | Como visitante, quiero visualizar cómo se conectan los tres actores del sistema. | 3 |
| 4 | US-25 | Solución para clínicas | Como terapeuta visitante, quiero consultar las funciones orientadas al personal médico. | 2 |
| 5 | US-26 | Solución para ortopedias | Como técnico ortopédico visitante, quiero consultar las herramientas de supervisión protésica. | 2 |
| 6 | US-27 | Solución para pacientes | Como paciente visitante, quiero conocer los beneficios del uso cotidiano en casa. | 2 |
| 7 | US-28 | Catálogo de herramientas clave | Como visitante, quiero revisar las capacidades técnicas para validar las métricas que captura. | 2 |
| 8 | US-29 | Video de demostración | Como visitante, quiero visualizar un video demostrativo para ver el sistema en acción. | 1 |
| 9 | US-30 | Comparador de planes de precios | Como visitante, quiero comparar los planes y alternar cobro mensual y anual. | 3 |
| 10 | US-31 | Respaldo institucional | Como visitante, quiero conocer los estándares biomédicos que respaldan la plataforma. | 1 |
| 11 | US-32 | Testimonios clínicos | Como visitante, quiero leer testimonios de profesionales y pacientes para verificar valor. | 1 |
| 12 | US-33 | Preguntas frecuentes (FAQ) | Como visitante, quiero revisar dudas comunes para resolver inquietudes técnicas. | 1 |
| 13 | US-36 | Alternancia de idioma | Como visitante, quiero cambiar el idioma entre español e inglés de forma reactiva. | 3 |
| 14 | US-37 | Políticas de privacidad | Como visitante, quiero acceder a normas de privacidad médica y cifrado AES-256. | 1 |
| 15 | TS-08 | Captación de prospectos API | Como Developer, disponer de endpoints para captar leads y suscripciones web. | 3 |
| 16 | US-34 | Solicitud de demo comercial | Como médico de clínica, enviar datos institucionales para solicitar una cotización. | 3 |
| 17 | US-35 | Suscripción a newsletter | Como visitante, registrar mi correo para recibir novedades de biomecánica. | 2 |
| 18 | TS-01 | Gestión de pacientes y prótesis API | Como developer, implementar endpoints RESTful para asociar pacientes y dispositivos. | 5 |
| 19 | US-01 | Registro de pacientes | Como profesional, registrar datos clínicos de un paciente amputado en el sistema. | 3 |
| 20 | US-02 | Asociación de prótesis | Como técnico, asociar una prótesis a un paciente para registrar su dispositivo. | 3 |
| 21 | US-03 | Consulta de ficha de paciente | Como profesional de clínica, consultar historial clínico y de prótesis de un paciente. | 2 |
| 22 | TS-02 | Ingesta de datos biomecánicos API | Como developer, implementar endpoint RESTful que reciba telemetría de sensores. | 5 |
| 23 | US-04 | Dashboard biomecánico | Como profesional de clínica, visualizar dashboard con métricas recientes de postura. | 5 |
| 24 | US-05 | Historial biomecánico paciente | Como paciente, consultar el historial de mis registros para evaluar mi evolución. | 3 |
| 25 | US-06 | Detección de marcha inadecuada | Como paciente, recibir alertas si mi postura o marcha presentó desvíos. | 5 |
| 26 | TS-03 | Gestión de planes de ejercicio API | Como developer, implementar endpoints para asignar y marcar rutinas terapéuticas. | 3 |
| 27 | US-07 | Asignación de ejercicios | Como profesional, pautar un plan de rehabilitación personalizado para el hogar. | 3 |
| 28 | US-08 | Cumplimiento de ejercicios | Como paciente, marcar la ejecución de ejercicios para registrar adherencia. | 3 |
| 29 | US-09 | Consulta de progreso clínico | Como profesional, revisar adherencia y cumplimiento del paciente a lo largo del tiempo. | 3 |
| 30 | TS-04 | Gestión de alertas críticas API | Como developer, implementar el motor de alertas y notificaciones automáticas. | 5 |
| 31 | US-11 | Configuración de umbrales | Como profesional, calibrar los rangos tolerables de marcha por cada paciente. | 3 |
| 32 | US-10 | Alerta de postura incorrecta | Como profesional, recibir una notificación oportuna ante compensaciones musculares. | 5 |
| 33 | US-12 | Historial de alertas clínicas | Como profesional, consultar cronológicamente eventos críticos y posturas anómalas. | 2 |
| 34 | TS-05 | Gestión de mantenimiento API | Como developer, implementar endpoints para registrar revisiones de prótesis. | 3 |
| 35 | US-13 | Registro técnico de prótesis | Como técnico, registrar piezas cambiadas, desajustes mecánicos y desgaste. | 3 |
| 36 | US-14 | Programación preventiva | Como técnico, agendar fecha futura de mantenimiento para evitar roturas. | 2 |
| 37 | US-15 | Alerta de desgaste protésico | Como técnico, recibir aviso automático cuando una pieza cumpla horas límite de uso. | 3 |
| 38 | TS-06 | Mensajería interinstitucional API | Como developer, implementar endpoints para mensajería clínica-taller-paciente. | 3 |
| 39 | US-16 | Chat paciente-clínica | Como paciente, consultar dudas médicas directamente con mi terapeuta tratante. | 3 |
| 40 | US-17 | Compartir ficha técnica | Como profesional, autorizar el envío de datos biomecánicos a la ortopedia. | 3 |
| 41 | US-18 | Centro de notificaciones | Como usuario, visualizar notificaciones generales y alertas del sistema. | 2 |
| 42 | TS-07 | Gestión de suscripciones API | Como developer, implementar pasarela de pagos y activación de licencias B2B. | 5 |
| 43 | US-19 | Suscripción anual clínica | Como directivo de clínica, adquirir plan anual para habilitar acceso institucional. | 5 |
| 44 | US-20 | Licencia técnica ortopedia | Como encargado de taller, comprar licencia para control y trazabilidad de piezas. | 5 |
| 45 | US-21 | Consulta de plan y vigencia | Como administrador, consultar fecha de caducidad y estado de renovación de licencia. | 2 |
| 46 | TS-09 | Exportación y reportes API | Como developer, implementar generación y descarga de informes médicos en PDF. | 5 |
| 47 | US-38 | Reporte de progreso clínico | Como profesional, generar reportes de evolución para la historia clínica del paciente. | 3 |
| 48 | US-39 | Exportación de datos de marcha | Como profesional, exportar registros estructurados para interconsultas. | 3 |
| 49 | US-40 | Indicadores globales de clínica | Como director médico, evaluar volumen de adherencia y pacientes activos en la sede. | 5 |

```{=typst}
#set text(size: 11pt)
```

\

- **Tablero de Trello:** https://trello.com/invite/b/6aaa2414fe1250572c17b9fe/ATTIe7f0872c34d6ae28c8540edd005e015fC1DFC2EC/seniors-in-process-prothia

```{=typst}
#pagebreak()
```

```{=typst}
#pagebreak()
```

# Capítulo IV: Product Design

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines

* **Branding:** Identidad centrada en la salud digital y la biomecánica, orientada a reducir la brecha de información entre pacientes amputados, clínicas de rehabilitación y centros ortopédicos.
* **Typography:** La tipografía seleccionada es Montserrat para títulos y elementos destacados, por su claridad y estructura moderna. Para el cuerpo de texto se utiliza Inter a 14px con un interlineado de 1.5, garantizando una lectura fluida de los datos médicos. Los tamaños se adaptan al contexto web según la jerarquía: títulos, subtítulos y párrafos.

  * **Escala:**
    ![](../SeniorsInProcess-Pandoc/assets/Escala.png){ width=50% }

  * **Weights:**
    ![](../SeniorsInProcess-Pandoc/assets/Weights.png){ width=35% }

  * **Nomenclatura:**
    ![](../SeniorsInProcess-Pandoc/assets/Nomenclatura.png){ width=50% }

  * **Example:**
    ![](../SeniorsInProcess-Pandoc/assets/Example.png){ width=85% }

* **Colors:** La paleta de colores de Prothia prioriza la confianza médica, la tecnología y el progreso. El Azul Profundo transmite estabilidad y profesionalismo, usado en textos y fondos principales. El Teal (Verde Azulado) simboliza innovación y eficiencia, ideal para acentos y gráficos biomecánicos. El Verde Esmeralda incrementa la sensación de logro, siendo ideal para captar estados positivos o metas de rehabilitación cumplidas. Finalmente, el Gris Claro aporta orden y limpieza, usado en fondos secundarios y contenedores.

* **Spacing:** El espaciado está diseñado para ofrecer una experiencia clara y ordenada, facilitando la lectura de historiales técnicos y datos biomecánicos en tiempo real:
  * Entre secciones principales: mínimo 24px para marcar el cambio de contexto clínico.
  * Entre encabezados y párrafos: 16px para reforzar jerarquía visual.
  * Entre párrafos consecutivos: 14px para mantener continuidad y evitar bloques densos.
  * Espaciado de botones e inputs: mínimo 10px entre elementos para garantizar usabilidad, especialmente en dispositivos móviles.

* **Tono de comunicación:** Prothia transmite profesionalismo, empatía y proactividad, claves para un sistema que acompaña la adaptación a una prótesis:
  * Profesional y analítico, de modo que sea comprensible para clínicas de rehabilitación y centros ortopédicos.
  * Preventivo y confiable, orientado a alertar sobre posturas incorrectas sin generar alarma innecesaria.
  * Empático y cercano, resaltando que la plataforma está diseñada para apoyar al paciente en su rutina diaria.

* **Lenguaje aplicado:**
  * Claro y directo, evitando tecnicismos ortopédicos complejos en la vista del paciente.
  * Orientado a la acción, con instrucciones breves para los ejercicios de rehabilitación.
  * Consistente en terminología médica, garantizando coherencia en alertas, reportes de desempeño y documentación técnica.

---

### 4.1.2. Web Style Guidelines

Elegimos una paleta basada en Azul Profundo, Teal / Verde Azulado, Verde Esmeralda y Gris Claro, porque queremos representar los valores de profesionalismo médico, tecnología, progreso y confianza. El Azul Profundo transmite estabilidad clínica y rigor, siendo el color principal de fondos de cabecera y tipografías para garantizar un alto contraste. El Teal simboliza la salud digital y la innovación, y es utilizado en botones primarios, elementos interactivos y trazados de gráficos biomecánicos. El Verde Esmeralda se reserva para indicadores de éxito, como la confirmación de ejercicios completados o posturas correctas. Finalmente, el Gris Claro se emplea como color de fondo en los dashboards, ofreciendo un lienzo limpio que evita la fatiga visual al revisar historiales clínicos y reportes de uso prolongado.

El uso balanceado de estos tonos asegura que la información clave, como las alertas de posturas inadecuadas o avisos de mantenimiento preventivo, sea rápidamente perceptible sin perder sobriedad visual. Los contrastes se aplican estratégicamente para mantener un diseño ordenado, moderno y fácil de interpretar por los tres actores del sistema: pacientes, profesionales de rehabilitación y técnicos ortopédicos.

En cuanto a la tipografía, dado que Prothia gestiona datos biomecánicos, historiales técnicos y programas de ejercicios, optamos por fuentes claras y contemporáneas. Montserrat se utiliza en títulos y encabezados para dar una estructura moderna y sólida, mientras que Inter se aplica en los cuerpos de texto y tablas de datos para maximizar la legibilidad. Los tamaños son lo suficientemente grandes para asegurar claridad en las métricas, utilizando variaciones de peso para guiar la atención del usuario en las pantallas de monitoreo.

![](../SeniorsInProcess-Pandoc/assets/Colors.png){ width=50% }

* **Tipografía:** Se respetará la relación tipográfica y jerarquía establecida en los General Style Guidelines, combinando Montserrat e Inter.
* **Responsive Design Standards:** Prothia está diseñado con una arquitectura adaptable para satisfacer los distintos contextos de uso de sus usuarios:
  * **Mobile (360px – 768px):** Navegación tipo hamburguesa, tarjetas de ejercicios apiladas en columna y botones grandes para uso con una sola mano.
  * **Tablet (769px – 1024px):** Layout en 2 columnas y menú lateral colapsable para técnicos en taller.
  * **Desktop (1025px en adelante):** Menú principal persistente y dashboards clínicos en 3 columnas para visualización simultánea de gráficos y alertas.

* **Interactivity:**
  * **Botones:** Bordes redondeados en 8px, hover con transición suave y elevación sutil.
  * **Transiciones y animaciones:** Duración de 200–300ms con curva ease-in-out.
* **Accessibility:** Cumplimiento de pautas WCAG 2.1 AA con contraste mínimo 4.5:1, navegación por teclado y etiquetas aria para lectores de pantalla.
* **UI Consistency:** Iconografía homogénea, grilla base de 8px y paleta semántica estandarizada.

---

## 4.2. Information Architecture

### 4.2.1. Organization Systems

Para estructurar la gran cantidad de datos médicos y de sensores, Prothia utiliza los siguientes sistemas de organización:

* **Organización Jerárquica:** Utilizada en los dashboards principales, donde se prioriza mostrar en la parte superior las alertas críticas (posturas incorrectas o mantenimientos urgentes), seguidas por los resúmenes de progreso biomecánico y, finalmente, los historiales detallados.
* **Organización Secuencial:** Aplicada en los flujos de tareas paso a paso, como el registro de los datos clínicos de un paciente, la asociación de una prótesis a un usuario o la asignación de un plan de ejercicios.
* **Organización Matricial:** Empleada en las vistas de analítica, permitiendo a los profesionales de rehabilitación cruzar datos de adherencia a los ejercicios con métricas de simetría de apoyo o cadencia a lo largo del tiempo.

### 4.2.2. Labeling Systems

El sistema de etiquetado en Prothia está diseñado para reducir la carga cognitiva, utilizando un lenguaje ubicuo que sea familiar tanto para el personal clínico como para el paciente en su hogar:

* **Navegación global:** Inicio, Pacientes, Prótesis, Monitoreo, Alertas, Mensajes.
* **Landing Page:** Soluciones, Para Clínicas, Para Ortopedias, Para Pacientes, Contacto.
* **Gestión de rehabilitación (Clínicas):** Asignar plan, Progreso de rehabilitación, Historial biomecánico.
* **Gestión técnica (Ortopedias):** Historial de uso, Programar mantenimiento, Estado del dispositivo.
* **Acciones del usuario:** Registrar paciente, Asociar prótesis, Generar reporte, Enviar mensaje, Configurar umbrales.

### 4.2.3. SEO Tags and Meta Tags

* **Landing Page (Sitio Web Estático):**
  * **Title:** Prothia | Biomechanical Telemetry & Rehabilitation Platform
  * **Meta Description:** Prothia connects amputee patients, rehabilitation clinics, and orthopedic centers to optimize remote tracking, analyze biomechanical telemetry, and manage prosthetic maintenance.
  * **Meta Keywords:** biomechanical telemetry, prosthetic rehabilitation, amputee patient, smart prosthetics, clinical telerehabilitation, gait analysis, socket comfort, orthopedic maintenance, digital health, IoT healthcare
  * **Meta Author:** SeniorsInProcess
  * **Meta Robots:** index, follow
  * **Open Graph:** `og:type`: website | `og:url`: https://www.prothia.tech | `og:image`: https://www.prothia.tech/assets/Logo.png

* **Web Application (Aplicación Web Transaccional):**
  * **Title:** Prothia App | Clinical Telemetry & Prosthetic Management
  * **Meta Description:** Access the Prothia clinical portal to monitor real-time gait telemetry, manage patient exercise adherence, and track prosthetic mechanical durability.
  * **Meta Author:** SeniorsInProcess
  * **Meta Robots:** noindex, nofollow (resguardo de confidencialidad médica)

### 4.2.4. Searching Systems

El sistema de búsqueda permite a los usuarios localizar información relevante mediante:
* Palabras clave (nombres de pacientes, modelo de prótesis o personal tratante).
* Filtros cronológicos por fechas de sesiones o mantenimientos técnicos.
* Estados de registro (activo, en rehabilitación, completado o en mantenimiento).
* Búsqueda unívoca por DNI, historia clínica o número de serie de componentes.

### 4.2.5. Navigation Systems

* **Primera Navegación (Header Persistente):** Menú global fijado con enlaces principales, alternancia idiomática (ES / EN) y acceso al registro.
  ![](../SeniorsInProcess-Pandoc/assets/Primera-Navegacion.png){ width=90% }

* **Segunda Navegación (Hero Section con CTA):** Presentación directa de la propuesta de valor y acceso al formulario de onboarding.
  ![](../SeniorsInProcess-Pandoc/assets/Segunda-Navegacion.png){ width=90% }

* **Tercera Navegación (Footer Estructurado):** Pie de página categorizado con enlaces a políticas de privacidad, normativas de cifrado AES-256 y accesibilidad WCAG 2.1 AA.
  ![](../SeniorsInProcess-Pandoc/assets/Tercera-Navegacion.png){ width=90% }

---

## 4.3. Landing Page UI Design

La Landing Page comunica la propuesta de valor integral del producto, exponiendo el ecosistema biomecánico continuo y captando prospectos comerciales institucionales.

### 4.3.1. Landing Page Wireframe

Wireframe integral desarrollado en Figma con distribución modular y puntos de conversión:

![](../SeniorsInProcess-Pandoc/assets/Wireframe_-_Landing_Page.png){ width=95% }

*Enlace Figma:* https://www.figma.com/design/dqRIVk8vPGYi9k3EEpfijS/Sin-t%C3%ADtulo?node-id=0-1

### 4.3.2. Landing Page Mock-up

Mock-up en alta fidelidad aplicando la paleta de colores y componentes interactivos finales:

![](../SeniorsInProcess-Pandoc/assets/Mockup_-_Landing_Page.png){ width=95% }

*Enlace Figma:* https://www.figma.com/design/dqRIVk8vPGYi9k3EEpfijS/Sin-t%C3%ADtulo?node-id=19-3

---

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes (Desktop Web Browser)

![](../SeniorsInProcess-Pandoc/assets/Wireframe-AppWeb1.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/Wireframe-AppWeb2.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/Wireframe-AppWeb3.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/Wireframe-AppWeb4.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/Wireframe-AppWeb5.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/Wireframe-AppWeb6.png){ width=85% }

*Enlace Figma Wireframes:* https://www.figma.com/design/dqRIVk8vPGYi9k3EEpfijS/Sin-t%C3%ADtulo?node-id=10-2

---

### 4.4.2. Web Applications Wireflow Diagrams

**Segmento: Paciente Amputado**

![](../SeniorsInProcess-Pandoc/assets/wire1.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/wire2.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/wire3.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/wire4.png){ width=85% }

\

**Segmento: Profesionales de Terapia Física y Rehabilitación**

![](../SeniorsInProcess-Pandoc/assets/wire5.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/wire6.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/wire7.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/wire8.png){ width=85% }

\

**Segmento: Técnicos Ortoprotesistas**

![](../SeniorsInProcess-Pandoc/assets/wire9.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/wire10.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/wire11.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/wire12.png){ width=85% }

---

### 4.4.3. Web Applications Mock-ups (Desktop Web Browser)

![](../SeniorsInProcess-Pandoc/assets/AppWebMockup1.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/AppWebMockup2.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/AppWebMockup3.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/AppWebMockup4.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/AppWebMockup5.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/AppWebMockup6.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/AppWebMockup7.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/AppWebMockup8.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/AppWebMockup9.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/AppWebMockup10.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/AppWebMockup11.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/AppWebMockup12.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/AppWebMockup13.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/AppWebMockup14.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/AppWebMockup15.png){ width=85% }

*Enlace Figma Mock-ups:* https://www.figma.com/design/dqRIVk8vPGYi9k3EEpfijS/Sin-t%C3%ADtulo?node-id=10-2

---

### 4.4.4. Web Applications User Flow Diagrams

* **USER FLOW 01: Registrar la realización de los ejercicios indicados para llevar constancia de su adherencia**
  ![](../SeniorsInProcess-Pandoc/assets/USER_FLOW_1.png){ width=90% }

\

* **USER FLOW 02: Visualizar un dashboard con los datos biomecánicos recientes de un paciente para evaluar su desempeño**
  ![](../SeniorsInProcess-Pandoc/assets/USER_FLOW_2.png){ width=90% }

\

* **USER FLOW 03: Programar una fecha de mantenimiento preventivo para una prótesis para anticiparse a posibles fallas**
  ![](../SeniorsInProcess-Pandoc/assets/USER_FLOW_3.png){ width=90% }

---

## 4.5. Web Applications Prototyping

* **Prototipo navegable en Figma:** https://tinyurl.com/2x48v884
* **Video demostrativo del flujo de interacción:** https://tinyurl.com/mtpua6jk

![](../SeniorsInProcess-Pandoc/assets/AppWebMockup11.png){ width=90% }

```{=typst}
#pagebreak()
```
```{=typst}
#pagebreak()
```

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level EventStorming

Para pasar del entendimiento general del negocio al diseño de la arquitectura del software, se desarrolló un Design-Level Event Storming en tres etapas consecutivas: identificación de Pivotal Points, modelado de Aggregates y delimitación de Bounded Contexts.

#### Paso 1: Identificación de Eventos Clave y los Pivotal Points

![](../SeniorsInProcess-Pandoc/assets/Pivotal%20Points.jpg){ width=95% }

\

#### Paso 2: Modelado de Agregados y Comandos

![](../SeniorsInProcess-Pandoc/assets/Aggregates.jpg){ width=95% }

\

#### Paso 3: Delimitación de Contextos e Integraciones

![](../SeniorsInProcess-Pandoc/assets/Bounded%20Contexts.jpg){ width=95% }

*Tablero Miro:* https://miro.com/app/board/uXjVHm-Fti8=/?share_link_id=426808403513

---

## 4.6.2. Software Architecture Context Diagram

El Context Diagram representa a Prothia como un único sistema de software y muestra a los principales actores y sistemas externos con los que interactúa. Los actores considerados son Visitor, Patient, Healthcare Professional (Médico/Fisioterapeuta), Orthopedic Technician (Técnico Ortopédico), Clinic Administrator y Orthopedic Center Admin, de acuerdo con las interacciones principales representadas en la solución. Esta separación permite reflejar las responsabilidades relacionadas con la consulta pública del Landing Page, el seguimiento de rehabilitación, el monitoreo clínico, la gestión técnica de prótesis y la administración de suscripciones institucionales.

Como sistemas externos se consideran Payment Gateway, Email Service, Prosthesis Biomechanical Sensors (IMU) y External Orthopedic Workshop Systems. El Payment Gateway procesa los pagos asociados a suscripciones y licencias; el Email Service soporta recuperación de contraseña y comunicaciones transaccionales; los sensores biomecánicos suministran la telemetría utilizada durante el monitoreo del paciente; y los sistemas de centros ortopédicos externos reciben reportes clínicos cifrados e interconsultas.

**C4 System Context Diagram de Prothia:**

![](../SeniorsInProcess-Pandoc/assets/c4-system-context-diagram-prothia.png){ width=95% }

---

## 4.6.3. Software Architecture Container Diagrams

La solución se distribuye en cuatro containers principales: Landing Page, Web Application, RESTful API y Relational Database. La Landing Page utiliza HTML5, CSS3 y JavaScript para presentar el modelo de negocio y captar solicitudes públicas. La Web Application utiliza Vue 3, PrimeVue y TypeScript/JavaScript para proporcionar las experiencias autenticadas de los diferentes roles. El RESTful API utiliza ASP.NET Core, C# y Entity Framework Core para exponer servicios, aplicar reglas de negocio y coordinar persistencia e integraciones. La información relacional se almacena en PostgreSQL 16.

Los CTA de la Landing Page redirigen hacia la Web Application. Tanto los formularios públicos como la Web Application se comunican con el RESTful API mediante HTTPS y JSON. El RESTful API es el único container que accede a la base de datos y a los servicios externos.

**C4 Container Diagram de Prothia:**

![](../SeniorsInProcess-Pandoc/assets/c4-container-diagram-prothia.png){ width=95% }

---

## 4.6.4. Software Architecture Components Diagrams

### Landing Page Components

La Landing Page se descompone en Hero & Value Proposition Section, Segment Solutions Section, Pricing & Plans Section, Lead Capture & Newsletter Forms, Landing API Client e Internationalization & Accessibility. Los CTA dirigen a los visitantes hacia la experiencia correspondiente de la Web Application, mientras que los formularios utilizan Landing API Client para registrar información mediante el RESTful API.

**C4 Component Diagram - Landing Page:**

![](../SeniorsInProcess-Pandoc/assets/c4-component-diagram-landing-page.png){ width=90% }

\

### Web Application Components

La Web Application separa Authentication & Security UI, Patient Rehabilitation Portal, Therapist Clinical Dashboard UI, Orthopedic Fleet & Workshop UI y Subscription & Billing Management UI. Todas estas experiencias utilizan Centralized API Client para la comunicación asíncrona mediante Axios y Pinia, y comparten recursos de Internationalization & Accessibility, manteniendo una única vía de comunicación con el RESTful API.

**C4 Component Diagram - Web Application:**

![](../SeniorsInProcess-Pandoc/assets/c4-component-diagram-web-application.png){ width=90% }

\

### RESTful API Components

El RESTful API organiza sus componentes principales de acuerdo con los Bounded Contexts identificados en el Design-Level EventStorming: Patients, Prescription, Monitoring, Analytics, Workshop, Communication, Identity & Access Management y Subscriptions & Billing.

* **Patients Component:** administra admisión clínica de pacientes, verificación de DNI, asignación de nivel funcional K (K0-K4), validación de cupos y vinculación de prótesis.
* **Prescription Component:** gestiona prescripción terapéutica, selección de ejercicios, dosificación de series/repeticiones y publicación de planes domiciliarios.
* **Monitoring Component:** procesa la ingesta de telemetría a 100 Hz, calibración en cero angular, evaluación de umbrales biomecánicos y ciclo de vida de alertas clínicas.
* **Analytics Component:** consolida series temporales de marcha y adherencia, generación de informes clínicos con firma digital y colegiatura, y exportación de datasets CSV.
* **Workshop Component:** gestiona el parque de prótesis, sincronización de ciclos de uso, conmutación por fatiga crítica y órdenes de trabajo de taller.
* **Communication Component:** configura módulos confidenciales para anonimización y transmite reportes cifrados a centros ortopédicos externos.
* **Identity & Access Management:** concentra registro, autenticación JWT, roles y sesiones de usuario.
* **Subscriptions & Billing:** administra planes institucionales, licencias y pagos B2B.
* **Persistence & Gateway Layer:** concentra el acceso mediante Entity Framework Core hacia PostgreSQL y encapsula la comunicación con pasarelas de pago y servicios de correo.

**C4 Component Diagram - RESTful API:**

![](../SeniorsInProcess-Pandoc/assets/c4-component-diagram-restful-api.png){ width=90% }

\

### Relational Database Components

El container Relational Database se organiza mediante separación lógica de datos. Los esquemas `patients`, `prescription`, `monitoring`, `analytics`, `workshop`, `communication`, `identity_access`, `subscriptions_payments` y `public_leads` corresponden a los Bounded Contexts y módulos de soporte identificados en el diseño.

Esta organización permite conservar límites de responsabilidad a nivel de persistencia aun cuando PostgreSQL sea desplegado inicialmente como una única instancia.

**C4 Component Diagram - Relational Database:**

![](../SeniorsInProcess-Pandoc/assets/c4-component-diagram-relational-database.png){ width=90% }

```{=typst}
#pagebreak()
```


```{=typst}
#pagebreak()
```

## 4.7. Software Object-Oriented Design

El diseño orientado a objetos se organiza de acuerdo con los Bounded Contexts identificados en el Design-Level EventStorming y con los módulos de soporte necesarios para mantener trazabilidad con las User Stories del Capítulo III. Los nombres de clases, atributos, métodos e interfaces se mantienen en inglés y se especifican relaciones, multiplicidades y visibilidad de miembros.

### 4.7.1. Class Diagrams

#### Patients
Modela la admisión clínica y clasificación funcional del paciente amputado. El agregado Patient actúa como Aggregate Root y contiene los objetos de valor PatientId, Dni, AmputationLevel, KLevel y ProsthesisCode. Se relaciona con MedicalRecord para registrar antecedentes e historial clínico. PatientApplicationService coordina los comandos de registro, asignación de nivel funcional y vinculación de prótesis interactuando con IPatientRepository.

**Class Diagram - Patients:**

![](../SeniorsInProcess-Pandoc/assets/class_diagram_patients.png){ width=90% }

\

#### Prescription
Modela la prescripción terapéutica individualizada y la dosificación de rutinas domiciliarias. La raíz de agregado TherapeuticPrescription gestiona el conjunto de ejercicios prescritos mediante la entidad PlanExercise, la cual encapsula series, repeticiones y frecuencia semanal. ThresholdProfile gestiona los límites basales configurados de inclinación coronal y fuerza de impacto de talón.

**Class Diagram - Prescription:**

![](../SeniorsInProcess-Pandoc/assets/class_diagram_prescription.png){ width=90% }

\

#### Monitoring
Modela la ingesta continua de señales inerciales y el control cinemático de la marcha. La raíz de agregado GaitSession coordina el ciclo de vida de la sesión (iniciada, concluida, interrumpida por enlace BLE), la calibración en cero angular y la recepción de paquetes TelemetryPacket100Hz con mediciones de inclinación coronal, ángulo sagital e impacto de talón en fuerzas G. ClinicalAlert representa los eventos emitidos ante desviaciones biomecánicas para su inspección y resolución clínica.

**Class Diagram - Monitoring:**

![](../SeniorsInProcess-Pandoc/assets/class_diagram_monitoring.png){ width=90% }

\

#### Analytics
Modela la consolidación de series temporales, métricas de simetría bilateral, adherencia al tratamiento y formalización del informe clínico mensual. La raíz de agregado ClinicalReport encapsula las recomendaciones médicas redactadas por el fisioterapeuta, la referencia al dataset crudo exportado en formato CSV y el objeto de valor DigitalSignature con código de colegiatura profesional y hash de autenticidad.

**Class Diagram - Analytics:**

![](../SeniorsInProcess-Pandoc/assets/class_diagram_analytics.png){ width=90% }

\

#### Workshop
Modela el parque de dispositivos protésicos y la gestión de mantenimiento preventivo y correctivo. La raíz de agregado ProsthesisAsset supervisa el número de serie, ciclos acumulados de flexión/paso y conmutación de estado de salud (óptimo, preventivo al 60%, crítico por fatiga). La raíz de agregado MaintenanceOrder coordina el agendamiento técnico de citas, apertura de órdenes de trabajo, reemplazo de componentes (cilindro hidráulico) mediante TechnicalIntervention y conclusión del mantenimiento con restauración al estado óptimo.

**Class Diagram - Workshop:**

![](../SeniorsInProcess-Pandoc/assets/class_diagram_workshop.png){ width=90% }

\

#### Communication
Modela la transmisión segura y confidencial de información clínica hacia talleres y centros ortopédicos externos. La raíz de agregado WorkshopTransmission administra la configuración de módulos confidenciales para anonimización de datos sensibles del paciente, el algoritmo de cifrado aplicado, el estado de envío y el registro de confirmación de recepción técnica. Adicionalmente, InAppMessage soporta la mensajería interna entre el paciente y el equipo de rehabilitación para interconsultas.

**Class Diagram - Communication:**

![](../SeniorsInProcess-Pandoc/assets/class_diagram_communication.png){ width=90% }

---

### Módulos de Soporte

* **Identity & Access Management:** El modelo concentra UserAccount, UserSession y PasswordResetRequest. IdentityService implementa IIdentityService y coordina registro, autenticación JWT, administración de sesiones y recuperación de credenciales.
* **Subscriptions & Payment Management:** SubscriptionPlan representa la oferta contratada por una clínica, ClinicSubscription representa su acceso vigente y SoftwareLicense representa la licencia otorgada a un centro ortopédico. PaymentTransaction registra el resultado de cada operación de pago.
* **Public Lead Management:** DemoRequest y NewsletterSubscription representan los flujos públicos de captación utilizados en la Landing Page, persistiendo prospectos institucionales.

---

## 4.8. Database Design

El diseño de base de datos utiliza PostgreSQL como DBMS relacional y conserva la separación lógica establecida por los Bounded Contexts identificados en el Design-Level EventStorming. Se utiliza `lowercase_snake_case` para tablas y columnas, UUID para identificadores, TIMESTAMPTZ para instantes temporales, DATE para fechas y NUMERIC para valores biomecánicos de precisión.

### 4.8.1. Database Diagrams

#### Relational Database Model Diagram

Representa la estructura relacional integral de Prothia Platform en PostgreSQL 16, mostrando las tablas principales de cada Bounded Context y la trazabilidad de referencias lógicas entre pacientes, prescripciones, sesiones telemétricas, reportes, prótesis y transmisiones técnicas.

**Database Diagram - Relational Database Model:**

![](../SeniorsInProcess-Pandoc/assets/erd_database_model.png){ width=95% }

---

### Esquemas de Persistencia por Bounded Context

* **Patients (`patients`):** Persiste los datos de admisión clínica de pacientes amputados y sus expedientes médicos basales mediante las tablas `patients` y `medical_records`. El DNI del paciente es único y se restringe el nivel de amputación y el nivel funcional K mediante restricciones CHECK.
* **Prescription (`prescription`):** Persiste las prescripciones terapéuticas domiciliarias y los ejercicios dosificados mediante `therapeutic_prescriptions` y `prescription_exercises`, además de almacenar los límites basales en `threshold_profiles`.
* **Monitoring (`monitoring`):** Persiste las sesiones de marcha domiciliaria en `gait_sessions`, las mediciones inerciales a 100 Hz en `telemetry_measurements` y las alertas críticas emitidas por desviación biomecánica en `clinical_alerts`. Se indexa la combinación de sesión y número de secuencia.
* **Analytics (`analytics`):** Persiste los reportes clínicos mensuales en `clinical_reports`, registrando las puntuaciones de simetría bilateral, porcentaje de adherencia, recomendaciones médicas y la firma digital del fisioterapeuta con número de colegiatura.
* **Workshop (`workshop`):** Persiste el parque de prótesis en `prosthesis_assets`, controlando ciclos acumulados y límite de fatiga, las órdenes de mantenimiento en `work_orders` y las intervenciones técnicas con recambio de piezas en `technical_interventions`. El número de serie de cada prótesis es único.
* **Communication (`communication`):** Persiste las transmisiones cifradas a centros ortopédicos externos en `workshop_transmissions`, controlando la anonimización de DNI y acuse de recibo técnico, así como los mensajes de interconsulta en `in_app_messages`.
* **Identity & Access Management (`identity_access`):** Persiste cuentas de usuario, sesiones y solicitudes de recuperación de contraseña con control de caducidad e invalidación de tokens.
* **Subscriptions & Payment Management (`subscriptions_payments`):** Persiste planes de suscripción, suscripciones de clínicas, licencias de software y transacciones de pago con validación CHECK de exclusión mutua.
* **Public Lead Management (`public_leads`):** Persiste las solicitudes de demostración y las suscripciones al newsletter provenientes de la Landing Page con restricción de unicidad de correos.

```{=typst}
#pagebreak()
```
```{=typst}
#pagebreak()
```

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1 Software Configuration Management

La gestión en **SeniorsInProcess (Prothia)** incluye el código fuente, documentación, prototipos y configuraciones del entorno de desarrollo de la plataforma web de monitoreo y seguimiento de rehabilitación de pacientes amputados. El proyecto contempla distintos productos digitales, incluyendo una Landing Page institucional, una aplicación web para clínicas de rehabilitación y centros ortopédicos, y servicios backend orientados al procesamiento de datos biomecánicos y de uso de prótesis en tiempo real. El equipo adopta prácticas basadas en GitFlow, Conventional Commits y Semantic Versioning, asegurando un flujo de trabajo colaborativo y organizado.

### 5.1.1. Software Development Environment Configuration

```{=typst}
#set text(size: 7.5pt)
#set table(
  columns: (1.5fr, 1.2fr, 2fr, 3.5fr, 1.2fr, 2fr),
  stroke: 0.5pt + luma(180),
  inset: 5pt
)
```

| Categoría | Logo | Producto | Propósito de Uso en el Proyecto | Tipo | Referencia / Descarga |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Project Management | ![](../SeniorsInProcess-Pandoc/assets/trello.jpg){ width=35px } | Trello | Gestión de tareas mediante tableros organizados (To-Do, In Progress, Done) para el seguimiento de entregables. | SaaS | https://trello.com |
| Team Communication | ![](../SeniorsInProcess-Pandoc/assets/discord.png){ width=35px } | Discord | Comunicación remota sincrónica, planificación de Sprints y coordinación general del equipo. | SaaS / Desktop | https://discord.com/ |
| Requirements | ![](../SeniorsInProcess-Pandoc/assets/miro.jpg){ width=35px } | Miro | Diagramación de flujos, análisis de negocio y ejecución de sesiones de EventStorming. | SaaS | https://miro.com |
| Architecture | ![](../SeniorsInProcess-Pandoc/assets/structurizr.png){ width=35px } | Structurizr | Modelado de la arquitectura de software bajo el modelo C4 en sus distintos niveles de abstracción. | SaaS / Desktop | https://structurizr.com |
| UX/UI Design | ![](../SeniorsInProcess-Pandoc/assets/figma.png){ width=35px } | Figma | Diseño visual y prototipado interactivo de las interfaces de usuario (web y móvil). | SaaS / Desktop | https://www.figma.com |
| Technical Design | ![](../SeniorsInProcess-Pandoc/assets/lucidchart.png){ width=35px } | Lucidchart | Elaboración de diagramas de flujo de trabajo, arquitectura técnica y procesos operativos. | SaaS | https://www.lucidchart.com |
| Development | ![](../SeniorsInProcess-Pandoc/assets/html.png){ width=35px } | HTML5 / CSS3 / JS | Estándares y lenguajes base para el desarrollo frontend y maquetación de la Landing Page. | Lenguajes | https://developer.mozilla.org/es/ |
| IDE | ![](../SeniorsInProcess-Pandoc/assets/webstorm.jpg){ width=35px } | WebStorm | Entorno de desarrollo integrado principal para programación y depuración frontend. | Desktop | https://www.jetbrains.com/webstorm/ |
| Testing | ![](../SeniorsInProcess-Pandoc/assets/gherkin.png){ width=35px } | Gherkin | Lenguaje de especificación para definir escenarios de prueba BDD basados en historias de usuario. | DSL | https://cucumber.io/docs/gherkin/ |
| Version Control | ![](../SeniorsInProcess-Pandoc/assets/github.jpg){ width=35px } | GitHub | Control de versiones distribuido, registro de commits y alojamiento de documentación técnica. | SaaS | https://github.com |
| Deployment | ![](../SeniorsInProcess-Pandoc/assets/gitpages.jpg){ width=35px } | GitHub Pages | Servicio de alojamiento y despliegue continuo para la versión pública de la Landing Page. | SaaS | https://pages.github.com |

```{=typst}
#set text(size: 11pt)
```

---

### 5.1.2 Source Code Management

La gestión de código fuente del proyecto **Prothia (SeniorsInProcess)** se realiza mediante la plataforma **GitHub**, permitiendo un control de versiones en entorno de trabajo colaborativo. Se han definido repositorios independientes para cada producto digital.

#### 5.1.2.1 Repositories

| Product | Repository URL | Description |
| :--- | :--- | :--- |
| **Organization** | [SeniorsInProcess-Prothia-1ASI0729](https://github.com/SeniorsInProcess-Prothia-1ASI0729) | Organización central donde se ubican todos los repositorios del proyecto. |
| **Landing Page** | [Prothia-Business-Web-Page](https://github.com/upc-pre-202620-1asi0730-8155-SeniorsIP/SeniorsInProcess-Prothia-LandingPage) | Repositorio de la Landing Page institucional del proyecto. |
| **Frontend Web Application** | [Prothia-Front-End](https://github.com/upc-pre-202620-1asi0730-8155-SeniorsIP/SeniorsInProcess-Prothia-Frontend) | Aplicación web para el monitoreo y seguimiento de la rehabilitación de pacientes amputados. |
| **Backend Web Services** | [Prothia-Back-end](https://github.com/upc-pre-202620-1asi0730-8155-SeniorsIP/SeniorsInProcess-Prothia-Backend) | API REST y lógica de procesamiento de datos biomecánicos y de uso de prótesis. |
| **Documentation Repository** | [Prothia-Report](https://github.com/upc-pre-202620-1asi0730-8155-SeniorsIP/SeniorsInProcess-Prothia-Report/tree/develop) | Documentación técnica, reportes y entregables del proyecto. |

\

![](../SeniorsInProcess-Pandoc/assets/organization-photo.png){ width=95% }

---

#### 5.1.2.2 GitFlow Workflow

El equipo adopta **GitFlow** como estrategia de branching para mantener la estabilidad del código:

* **Main Branch:** Contiene únicamente versiones estables y aprobadas del proyecto listas para producción (`main`).
* **Develop Branch:** Rama principal de integración donde se consolidan las funcionalidades antes de pasar a producción (`develop`).
* **Feature Branches:** Cada nueva funcionalidad se desarrolla en una rama independiente (`feature/<feature-name>`). Ejemplos: `feature/patient-monitoring-dashboard`, `feature/biomechanical-data-tracking`.
* **Hotfix Branches:** Ramas de emergencia para corregir errores críticos detectados directamente en producción (`hotfix/<issue-description>`).

#### 5.1.2.3 Semantic Versioning

El proyecto utiliza **Semantic Versioning 2.0.0** para controlar las versiones de los productos digitales de Prothia:

| Version | Description |
| :--- | :--- |
| **v1.0.0** | Primera versión estable y funcional del producto. |
| **v1.1.0** | Incorporación de nuevas funcionalidades menores. |
| **v1.1.1** | Corrección de errores menores sin alterar compatibilidad. |
| **v2.0.0** | Cambios mayores que incluyen modificaciones estructurales incompatibles. |

#### 5.1.2.4 Conventional Commits

Se adopta el estándar de **Conventional Commits** para mantener un historial de cambios limpio y legible:

| Prefix | Purpose |
| :--- | :--- |
| **feat** | Implementación de nuevas funcionalidades. |
| **fix** | Corrección de errores o bugs. |
| **docs** | Actualizaciones en la documentación del repositorio. |
| **style** | Cambios que no afectan la lógica (espaciados, formatos, CSS). |
| **refactor** | Reestructuración del código existente sin cambiar su funcionalidad. |
| **test** | Corrección o adición de pruebas unitarias o de integración. |

---

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

Durante este primer sprint, el equipo se enfocó en la implementación de la Landing Page de Prothia, estableciendo el principal canal de comunicación pública y captación para la plataforma biomecánica.  

#### 5.2.1.1. Sprint Planning 1 

```{=typst}
#set table(
  columns: (1.5fr, 3.5fr),
  stroke: 0.5pt + luma(180),
  inset: 6pt
)
```

| **Campo** | **Detalle** |
| :--- | :--- |
| **Sprint #** | Sprint 1 |
| **Sprint Planning Background** | Reunión inicial para definir las prioridades del producto, enfocándonos en establecer la presencia web pública y habilitar la captación de usuarios interesados mediante la Landing Page. |
| **Date** | 2026-09-03 |
| **Time** | 20:00 PM |
| **Location** | Microsoft Teams Group Call |
| **Prepared By** | Patricio Farias, Ana Camila |
| **Attendees** | Patricio Farias, Ana Camila / Checa Burga, Oscar Diego / Dextre Flores, Leonardo Felix / Salcedo Correa, Carlos Mathhew / Barrenechea Bustamante, Rafael Andre |
| **Sprint Review Summary** | Durante la fase preliminar se definió la arquitectura de información, se elaboraron wireframes y mock-ups, y se configuraron los repositorios y tableros de Trello. |
| **Sprint Retrospective** | **Start:** Realizar sincronizaciones cortas para identificar bloqueos técnicos.\ \ **Continue:** Mantener la revisión cruzada de diseños.\ \ **Stop:** Retrasar la creación de ramas en el repositorio. |
| **Sprint 1 Goal** | Implementar la arquitectura base y funcionalidades del sitio web estático, permitiendo a los visitantes conocer la propuesta de valor y solicitar una demostración clínica. |
| **Sprint 1 Velocity** | 6 Story Points |

---

#### 5.2.1.2. Aspect Leaders and Collaborators 

| Integrante | GitHub | Landing Page (HTML/CSS/JS) | UX/UI & Prototyping | Project Documentation |
| :--- | :--- | :---: | :---: | :---: |
| Barrenechea Bustamante, Rafael Andre | yafussssss | C | C | C |
| Checa Burga, Oscar Diego | OscarCheca | C | C | L |
| Dextre Flores, Leonardo Felix | Leo-dex45 | C | C | C |
| Patricio Farias, Ana Camila | anacamilapatricio-sketch | C | L | L |
| Salcedo Correa, Carlos Mathhew | Matthewnhfe | L | L | C |

---

#### 5.2.1.3. Sprint Backlog 1 

Para organizar el flujo de trabajo, las tareas se gestionaron mediante **Trello**:

![](../SeniorsInProcess-Pandoc/assets/spring1.png){ width=95% }

*Tablero de Trello:* https://trello.com/invite/b/6aabb55b023122d8fe598ee0/ATTI98b4a9da9fc821f35855872e0885a87cFED1E6E2/seniorsinprocess-prothia-sprint-1

---

#### 5.2.1.4. Development Evidence for Sprint Review 

```{=typst}
#set text(size: 8pt)
#set table(
  columns: (1.8fr, 1fr, 0.8fr, 2.5fr, 1fr),
  stroke: 0.5pt + luma(180),
  inset: 5pt
)
```

| Repository | Branch | Commit Id | Commit Message | Commited on |
| :--- | :--- | :--- | :--- | :--- |
| SeniorsInProcess/Prothia-Landing-Page | develop | `e5acca4` | Feat(landing): complete landing page structure and content in index.html | 17/09/2026 |
| SeniorsInProcess/Prothia-Landing-Page | develop | `b2c7cce` | Feat(landing): complete landing page styles and responsive layout in styles.css | 17/09/2026 |
| SeniorsInProcess/Prothia-Landing-Page | develop | `f2b24fc` | feat(landing): complete main javascript interactions and logic in main.js | 17/09/2026 |
| SeniorsInProcess/Prothia-Landing-Page | develop | `a4d9681` | feat(landing): complete hero sequence animation logic in hero-sequence.js | 17/09/2026 |
| SeniorsInProcess/Prothia-Landing-Page | develop | `a4d9681` | feat(landing): complete internationalization logic and language switcher | 17/09/2026 |

```{=typst}
#set text(size: 11pt)
```

---

#### 5.2.1.5. Execution Evidence for Sprint Review

Capturas de pantalla de la Landing Page implementada en vistas Desktop y Mobile:

![](../SeniorsInProcess-Pandoc/assets/Execution-Evidence-Landing.png){ width=90% }

\

![](../SeniorsInProcess-Pandoc/assets/Execution-Evidence-LandingMobile.png){ width=45% }

* **URL de la Landing Page:** https://upc-pre-202620-1asi0730-8155-seniorsip.github.io/SeniorsInProcess-Prothia-LandingPage/
* **Video Demostrativo:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u202421065_upc_edu_pe/IQDNRf7YFyx2S7sfhe8y7z-aAemJubaEn3IlURxzwNnz_MM?e=NuhSGo

---

#### 5.2.1.6. Services Documentation Evidence for Sprint Review
Durante este Sprint 1, el esfuerzo del equipo se concentró de manera exclusiva en el desarrollo del Landing Page estático (HTML, CSS y JavaScript) y en establecer la identidad visual del producto. Dado que el alcance funcional de esta iteración no contempló aún el desarrollo del backend (RESTful API), no se cuenta con endpoints documentados mediante OpenAPI/Swagger para esta entrega.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review
Para asegurar el acceso público a la propuesta de Prothia, el Landing Page fue desplegado utilizando GitHub Pages desde la rama `develop` del repositorio respectivo:

![](../SeniorsInProcess-Pandoc/assets/github-pages.png){ width=90% }

---

#### 5.2.1.8. Team Collaboration Insights during Sprint 

El trabajo en equipo durante el Sprint 1 fluyó bajo GitFlow. Cada integrante trabajó en ramas `feature/` específicas y abrió Pull Requests hacia `develop`, los cuales fueron revisados por Ana Camila antes de su integración:

![](../SeniorsInProcess-Pandoc/assets/Github-Insights.png){ width=90% }

---

### 5.2.2. Sprint 2

Durante el Sprint 2, el equipo enfocó su trabajo en aplicar mejoras a la Landing Page y en desarrollar y desplegar la primera versión funcional de la aplicación web de Prothia, implementando todos los Bounded Contexts definidos en la arquitectura DDD.

#### 5.2.2.1. Sprint Planning 2

```{=typst}
#set table(
  columns: (1.5fr, 3.5fr),
  stroke: 0.5pt + luma(180),
  inset: 6pt
)
```

| **Campo** | **Detalle** |
| :--- | :--- |
| **Sprint #** | Sprint 2 |
| **Date / Time** | 2026-10-01 \| 8:00 PM |
| **Location** | Reunión virtual mediante Discord y Microsoft Teams |
| **Prepared By** | Patricio Farias, Ana Camila |
| **Attendees** | Ana Camila Patricio Farias, Oscar Diego Checa Burga, Leonardo Felix Dextre Flores, Carlos Matthew Salcedo Correa, Rafael Andre Barrenechea Bustamante |
| **Review Summary** | Se validó la versión mejorada de la Landing Page con conexión directa hacia la aplicación web y los módulos frontend en Vue 3 y PrimeVue. |
| **Sprint Goal** | Implementar mejoras en la Landing Page y desarrollar y desplegar la Web Application asegurando coherencia visual, soporte multilingüe (ES/EN) y acceso diferenciado por roles. |

---

#### 5.2.2.2. Aspect Leaders and Collaborators

| Integrante | GitHub | Aplicación Web | Despliegue Web | Documentación |
| :--- | :--- | :---: | :---: | :---: |
| **Patricio Farias, Ana Camila** | anacamilapatricio-sketch | L | C | L |
| **Checa Burga, Oscar Diego** | OscarCheca | L | C | L |
| **Dextre Flores, Leonardo Felix** | leo-dex45 | C | L | C |
| **Salcedo Correa, Carlos Matthew** | Matthewnhfe | L | L | C |
| **Barrenechea Bustamante, Rafael Andre** | yafussssss | C | C | C |

---

#### 5.2.2.3. Sprint Backlog 2

![](../SeniorsInProcess-Pandoc/assets/sprint2.png){ width=95% }

*Tablero Trello Sprint 2:* https://trello.com/invite/b/6a3482081843e32dea421094/ATTI18eefa82ccf88b07429958c3ca4d886e7D9A78CB/sprint-2-prothia

```{=typst}
#set text(size: 7.5pt)
#set table(
  columns: (0.8fr, 2.2fr, 1.2fr, 2.5fr, 0.6fr, 1.1fr, 0.7fr),
  stroke: 0.5pt + luma(180),
  inset: 4.5pt
)
```

| Story ID | Título Historia | Task ID | Tarea Técnica | Puntos | Asignado | Estado |
| :--- | :--- | :--- | :--- | :---: | :--- | :---: |
| US-01 | Registro de pacientes | US001TASK001 | Entidad `Patient`, store y formulario de alta clínica con validación de DNI y nivel K. | 3 | Oscar | Done |
| US-02 | Asociación de prótesis | US002TASK001 | Diálogo modal en workshop para vincular prótesis a paciente. | 3 | Leonardo | Done |
| US-03 | Consulta de ficha clínica | US003TASK001 | Directorio, filtros y vista 360 del paciente con prótesis activa. | 2 | Oscar | Done |
| US-04 | Dashboard biomecánico | US004TASK001 | Vista clínica con métricas de cadencia, simetría y ángulo sagital. | 4 | Oscar | Done |
| US-05 | Historial biomecánico | US005TASK001 | Monitoreo histórico de sesiones en portal paciente. | 3 | Carlos | Done |
| US-06 | Biofeedback en vivo | US006TASK001 | Pantalla de telemetría en vivo con indicadores de desalineación. | 4 | Carlos | Done |
| US-07 | Asignación de ejercicios | US007TASK001 | Entidades `Prescription` y `Exercise`, store y editor de rutinas. | 4 | Camila | Done |
| US-08 | Cumplimiento de ejercicios | US008TASK001 | Lista interactiva en patient-portal para marcar series completadas. | 3 | Carlos | Done |
| US-09 | Progreso de rehabilitación | US009TASK001 | Dashboard "Mi Día" con tasa porcentual de adherencia semanal. | 3 | Carlos | Done |
| US-10 | Alerta de postura incorrecta | US010TASK001 | Store y bandeja de eventos críticos en monitoring. | 3 | Oscar | Done |
| US-13 | Historial técnico prótesis | US013TASK001 | Entidad `Prosthesis`, catálogo de flota y bitácora de intervenciones. | 3 | Leonardo | Done |
| US-14 | Programación preventiva | US014TASK001 | Store Pinia y calendario de citas técnicas agendadas en taller. | 3 | Leonardo | Done |
| US-15 | Alerta de fatiga mecánica | US015TASK001 | Avisos automáticos por ciclos de uso o fuerza crítica en taller. | 2 | Leonardo | Done |
| US-16 | Chat paciente-clínica | US016TASK001 | Entidad `ClinicalMessage` y vista de mensajería bidireccional. | 3 | Camila/Carlos | Done |
| US-17 | Transmisiones a ortopedia | US017TASK001 | Formulario y servicio para enviar fichas técnicas al taller. | 4 | Camila | Done |
| US-18 | Centro de notificaciones | US018TASK001 | Bounded context `option` con menú y avisos de cuenta. | 3 | Rafael | Done |
| US-19 | Suscripción clínica | US019TASK001 | Entidades `ClinicSubscription` y vista de facturación en billing. | 4 | Leonardo | Done |
| US-20 | Licencia de taller | US020TASK001 | Control de licencia corporativa y cupos de prótesis activas. | 2 | Leonardo | Done |
| US-21 | Estado de suscripción | US021TASK001 | Barra de cupos activos, vigencia y facturas electrónicas. | 2 | Leonardo | Done |
| US-38 | Reporte de progreso clínico | US038TASK001 | Entidad `ClinicalReport` y generador con firma digital y colegiatura. | 4 | Carlos | Done |
| US-39 | Exportación de datos | US039TASK001 | Controles para exportar series de marcha en CSV y PDF. | 2 | Carlos | Done |

```{=typst}
#set text(size: 11pt)
```

---

#### 5.2.2.4. Development Evidence for Sprint Review

```{=typst}
#set text(size: 7.5pt)
#set table(
  columns: (1.5fr, 1.8fr, 0.8fr, 2.8fr, 3fr),
  stroke: 0.5pt + luma(180),
  inset: 4.5pt
)
```

| Repositorio | Autor / Branch | Commit Id | Commit Message | Descripción del cambio |
| :--- | :--- | :--- | :--- | :--- |
| Prothia-Frontend | anacamilapatricio-sketch | `de2aa3c` | chore: initial commit | Inicializa el repositorio base en Vue 3 y Vite. |
| Prothia-Frontend | anacamilapatricio-sketch | `6e21554` | chore: clean up code | Limpia plantilla eliminando archivos no utilizados. |
| Prothia-Frontend | anacamilapatricio-sketch | `a0a6754` | build: add dependencies | Agrega dependencias de PrimeVue, Pinia, Axios y Vue I18n. |
| Prothia-Frontend | anacamilapatricio-sketch | `b680551` | feat(i18n): add support | Configura soporte multilingüe en inglés y español. |
| Prothia-Frontend | anacamilapatricio-sketch | `2765848` | feat(router): in-app navigation | Incorpora enrutador principal de navegación interna. |
| Prothia-Frontend | anacamilapatricio-sketch | `b991c56` | feat(state): pinia management | Integra Pinia para la gestión centralizada de estado. |
| Prothia-Frontend | anacamilapatricio-sketch | `4c627e0` | feat(env): environment vars | Añade variables de entorno de desarrollo y producción. |
| Prothia-Frontend | anacamilapatricio-sketch | `79385f9` | feat(ui): primevue theme | Configura PrimeVue con tema visual Material Design. |
| Prothia-Frontend | OscarCheca | `2d73c91` | feat(shared): BaseApi infrastructure | Implementa clases base HTTP para consumo de APIs. |
| Prothia-Frontend | OscarCheca | `2f19f47` | feat(shared): role store | Crea store compartido para rol activo de usuario. |
| Prothia-Frontend | OscarCheca | `6a76f6e` | feat(shared): presentation views | Agrega vistas y componentes del módulo compartido. |
| Prothia-Frontend | OscarCheca | `8326e33` | feat(monitoring): add domain | Crea entidades de alertas y monitoreo biomecánico. |
| Prothia-Frontend | anacamilapatricio-sketch | `fe3110e` | feat(communication): domain entities | Define entidades de mensajes clínicos y transmisiones. |
| Prothia-Frontend | anacamilapatricio-sketch | `86cd7ba` | feat(communication): workshop view | Desarrolla vista de coordinación con talleres y rutas. |
| Prothia-Frontend | anacamilapatricio-sketch | `48d668f` | feat(prescription): domain entities | Entidades de prescripción terapéutica y ejercicios. |
| Prothia-Frontend | anacamilapatricio-sketch | `9a23e41` | feat(prescription): editor view | Construye vista del editor de planes clínicos. |
| Prothia-Frontend | leo-dex45 | `1e22528` | feat(billing): domain entities | Entidades de suscripción clínica y facturas. |
| Prothia-Frontend | leo-dex45 | `1344515` | feat(billing): subscription view | Desarrolla vista de administración de suscripción. |
| Prothia-Frontend | Matthewnhfe | `d7c4dca` | feat(analytics): report entity | Define entidad de informe clínico de evolución. |
| Prothia-Frontend | Matthewnhfe | `1466900` | feat(patient-portal): portal routing | Construye estructura visual y rutas del portal paciente. |
| Prothia-Frontend | Matthewnhfe | `dba99d2` | feat(patient-portal): dashboard views | Añade dashboard "Mi Día" y vista de rutina diaria. |
| Prothia-Frontend | Matthewnhfe | `90fa5d1` | feat(patient-portal): live telemetry | Implementa telemetría en vivo e historial de marcha. |

```{=typst}
#set text(size: 11pt)
```

---

#### 5.2.2.5. Execution Evidence for Sprint Review

* **Aplicación Web Desplegada:** https://prothia-web-app-7003f.web.app/
* **Landing Page Desplegada:** https://upc-pre-202620-1asi0730-8155-seniorsip.github.io/SeniorsInProcess-Prothia-LandingPage/

**Figura 1. Inicio de Sesión y Selección de Rol (Módulo IAM):**  
![](../SeniorsInProcess-Pandoc/assets/iam.png){ width=85% }

\

**Figura 2. Dashboard Principal del Paciente ("Mi Día" - Patient Portal):**  
![](../SeniorsInProcess-Pandoc/assets/figura2.png){ width=85% }

\

**Figura 3. Telemetría Biomecánica en Vivo e Historial de Marcha:**  
![](../SeniorsInProcess-Pandoc/assets/figura3.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/marcha.png){ width=85% }

\

**Figura 4. Mis Ejercicios y Mensajería Clínica del Paciente:**  
![](../SeniorsInProcess-Pandoc/assets/ejercicios.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/mensajeria.png){ width=85% }

\

**Figura 5. Dashboard Clínico y Alta de Pacientes (Módulo Patients):**  
![](../SeniorsInProcess-Pandoc/assets/clinica.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/paciente.png){ width=85% }

\

**Figura 6. Prescripción Terapéutica y Centro de Alertas (Prescription & Monitoring):**  
![](../SeniorsInProcess-Pandoc/assets/prescripcion.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/alertas.png){ width=85% }

\

**Figura 7. Coordinación con Ortopedia, Reportes y Suscripción (Communication, Analytics & Billing):**  
![](../SeniorsInProcess-Pandoc/assets/reporte.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/suscripcion.png){ width=85% }

\

**Figura 8. Portal del Taller Ortopédico: Flota, Mantenimiento y Alertas (Módulo Workshop):**  
![](../SeniorsInProcess-Pandoc/assets/taller.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/flota.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/mantenimiento.png){ width=85% }

\

![](../SeniorsInProcess-Pandoc/assets/alertasss.png){ width=85% }

---

#### 5.2.2.6. Services Documentation Evidence for Sprint Review

Durante el Sprint 2 se implementaron los servicios de consumo HTTP en el frontend apoyados en la infraestructura `BaseApi` y `BaseEndpoint` (Axios) y en clases Assembler para transformar los recursos JSON hacia entidades de dominio.

* **URL base local (JSON Server):** `http://localhost:3000`
* **Repositorio de servicios y datos:** https://github.com/upc-pre-202620-1asi0730-8155-SeniorsIP/SeniorsInProcess-Prothia-Frontend

```{=typst}
#set text(size: 7.2pt)
#set table(
  columns: (1.5fr, 0.8fr, 2.2fr, 2.5fr, 3fr),
  stroke: 0.5pt + luma(180),
  inset: 4pt
)
```

| Módulo / Acción | Método | Endpoint Local | Carga Útil (Payload) | Respuesta Ejemplo |
| :--- | :---: | :--- | :--- | :--- |
| Consultar pacientes | GET | `/patients` | Ninguno | `[{"id":1,"fullName":"Carlos Mendoza","kLevel":"K3"}]` |
| Registrar paciente | POST | `/patients` | Body JSON (`Patient`) | `{"id":5,"dni":"45892104","amputationLevel":"Transtibial"}` |
| Consultar sesiones | GET | `/gaitSessions` | Ninguno | `[{"id":1,"cadence":96,"symmetry":92.4}]` |
| Consultar alertas | GET | `/alerts` | Ninguno | `[{"id":1,"patientName":"Carlos Mendoza","severity":"Warning"}]` |
| Actualizar umbrales | PUT | `/thresholds/1` | Body JSON (`Threshold`) | `{"id":1,"maxPelvicTilt":12,"maxAsymmetry":15}` |
| Publicar prescripción | POST | `/prescriptions` | Body JSON (`Prescription`) | `{"id":1,"patientId":1,"phase":"Fase 2","adherence":88}` |
| Transmitir ficha | POST | `/transmissions` | Body JSON (`Transmission`) | `{"id":1,"workshop":"Ortopedia Avanzada","status":"Sent"}` |
| Enviar mensaje | POST | `/clinicalMessages` | Body JSON (`Message`) | `{"id":1,"sender":"Lic. Diego Salazar","text":"Mantén apoyo"}` |

```{=typst}
#set text(size: 11pt)
```

---

#### 5.2.2.7. Software Deployment Evidence for Sprint Review

* **Plataforma de Hosting:** Firebase Hosting (`prothia-web-app-7003f`).
* **Repositorio Frontend:** https://github.com/upc-pre-202620-1asi0730-8155-SeniorsIP/SeniorsInProcess-Prothia-Frontend
* **Aplicación Web Desplegada:** https://prothia-web-app-7003f.web.app/

![](../SeniorsInProcess-Pandoc/assets/firebase.png){ width=90% }

---

#### 5.2.2.8. Team Collaboration Insights during Sprint

```{=typst}
#set table(
  columns: (1.5fr, 1.2fr, 3.5fr),
  stroke: 0.5pt + luma(180),
  inset: 6pt
)
```

| Integrante | GitHub | Aportes registrados en SeniorsInProcess-Prothia-Frontend |
| :--- | :--- | :--- |
| **Patricio Farias, Ana Camila** | anacamilapatricio-sketch | Inicialización de repositorio, configuración de dependencias, i18n, router, Pinia, variables de entorno y PrimeVue; desarrollo e integración de los módulos Communication y Prescription. |
| **Checa Burga, Oscar Diego** | OscarCheca | Desarrollo de infraestructura Shared (BaseApi, BaseEndpoint, role store), diccionarios i18n e implementación de los módulos Monitoring y Patients. |
| **Dextre Flores, Leonardo Felix** | leo-dex45 | Desarrollo completo de los módulos Billing (suscripciones, API y facturación) y Workshop (flota de prótesis, agenda técnica y alertas mecánicas). |
| **Salcedo Correa, Carlos Matthew** | Matthewnhfe | Desarrollo de Analytics (reportes clínicos), Patient-Portal (layout, dashboard "Mi Día", telemetría en vivo, historial de marcha) y configuración raíz App-Setup. |
| **Barrenechea Bustamante, Rafael Andre** | yafussssss | Desarrollo de IAM (entidad User, auth client, interceptores, auth guard, Pinia store, vistas login/registro), módulo Option y actualización de documentación. |

\

![](../SeniorsInProcess-Pandoc/assets/sprint2insight.png){ width=90% }

```{=typst}
#pagebreak()
```
```{=typst}
#pagebreak()
```

### 5.1.3. Source Code Style Guide & Conventions

El uso de un estilo de código unificado y una arquitectura bien definida es clave para asegurar la escalabilidad, la mantenibilidad y la colaboración efectiva en el desarrollo de **Prothia**. Para ello, el proyecto incorpora prácticas de programación y convenciones estructurales que promueven la calidad técnica, la claridad y la consistencia en cada módulo de la plataforma, tomando como referencia estándares reconocidos de la industria y metodologías actuales.

#### Arquitectura y organización del sistema

Prothia adopta el modelo C4 de Simon Brown, lo que permite visualizar el sistema en distintos niveles de abstracción (contexto, contenedor, componente y código). Este enfoque ofrece una representación clara y comprensible, facilitando la comunicación entre desarrolladores, diseñadores y testers. Además, la arquitectura se fundamenta en los principios de Domain-Driven Design (DDD) y Clean Architecture, lo que garantiza una separación rigurosa entre capas (presentación, aplicación, dominio e infraestructura). Gracias a ello, se reduce el acoplamiento, se incrementa la mantenibilidad y se fortalece la capacidad de realizar pruebas automatizadas de manera eficiente.

#### Frontend: Vue.js

En el frontend, se emplea Vue.js como framework principal, implementando una arquitectura centrada en componentes reutilizables, organizados en directorios específicos como components, views y store. La convención de nombres establece el uso de PascalCase para los componentes (por ejemplo, `PatientCard.vue`) y kebab-case para los archivos (`patient-card.vue`), en concordancia con las recomendaciones de la comunidad Vue. Asimismo, se aplican buenas prácticas de desarrollo:

* Separación de lógica y presentación mediante el patrón container/presentational components.
* Uso de props y emits para la comunicación clara entre componentes.
* Implementación de lazy loading y code splitting para optimizar el rendimiento.
* Internacionalización con `vue-i18n`, gestionando archivos JSON para cada idioma.

#### Alineación con guías de estilo estándar

La estructura y nomenclatura utilizadas en Prothia siguen convenciones reconocidas como la Vue Style Guide y lineamientos generales de HTML/CSS. Además, el uso del inglés en identificadores, clases y funciones garantiza coherencia en el trabajo colaborativo, simplifica la integración con librerías externas y favorece la comprensión del código por parte de equipos internacionales.

---

### 5.1.4. Software Deployment Configuration

Esta sección describe la configuración y los pasos necesarios para desplegar la Landing Page de Prothia a partir del repositorio de código fuente.

* **Repositorio:** https://github.com/upc-pre-202620-1asi0730-8155-SeniorsIP/SeniorsInProcess-Prothia-LandingPage
* **URL publicada:** https://upc-pre-202620-1asi0730-8155-seniorsip.github.io/SeniorsInProcess-Prothia-LandingPage/
* **Rama de producción:** `main`
* **Stack:** HTML5 + CSS3 + JavaScript
* **Plataforma de despliegue:** GitHub Pages

#### Pasos de despliegue

1. Confirmar que la rama `main` contiene la versión estable de la Landing Page y que `index.html` se encuentra en la raíz del repositorio.
2. En el repositorio de GitHub, ir a **Settings → Pages**.
3. En la sección **Build and deployment**, configurar:
   * **Source:** Deploy from a branch
   * **Branch:** `main`
   * **Folder:** `/ (root)`
4. Hacer clic en **Save**. GitHub Pages generará automáticamente la URL pública.
5. Esperar entre 1 y 2 minutos y verificar que la página cargue correctamente.
6. Comprobar que el diseño responda correctamente en desktop (≥ 1025px), tablet (769–1024px) y móvil (≤ 768px).
7. Verificar que el toggle de idioma (EN / ES) funcione en todos los breakpoints.

#### Actualizaciones posteriores

Cada `git push` a la rama `main` desencadena un redespliegue automático en GitHub Pages. No se requiere ninguna acción manual adicional:

```bash
# Flujo estándar para publicar cambios
git add .
git commit -m "feat: update hero section copy"
git push origin main
```

#### Verificación post-despliegue

```{=typst}
#set table(
  columns: (1.5fr, 3.5fr),
  stroke: 0.5pt + luma(180),
  inset: 6pt
)
```

| Verificación | Detalle |
| :--- | :--- |
| **Carga de assets** | Logo institucional, imágenes descriptivas e iconografía visibles. |
| **Navegación** | Links del navbar redirigen a las secciones correspondientes (`#features`, `#plans`, `#audience`, `#demo`). |
| **Toggle de idioma** | Cambia correctamente entre EN y ES en todos los textos con atributos de traducción `data-i18n`. |
| **Menú móvil** | Se abre y cierra correctamente en smartphones y desaparece en resolución de escritorio. |
| **Diseño responsivo** | Ausencia de scroll horizontal en todos los anchos de pantalla. |

```{=typst}
#pagebreak()
```

```{=typst}
#pagebreak()
```

# Conclusiones y recomendaciones

### Conclusiones

1. A partir del análisis del problema y del proceso de needfinding, se obtuvo evidencia que respalda la problemática planteada inicialmente sobre la falta de seguimiento continuo durante la rehabilitación de pacientes amputados fuera de las sesiones presenciales. Las entrevistas realizadas muestran que una parte importante del proceso ocurre en el hogar, donde el paciente dispone de poca retroalimentación inmediata y los profesionales tienen una visibilidad limitada sobre la correcta ejecución de los ejercicios y la evolución de la marcha.

2. Los resultados de las entrevistas respaldan de manera preliminar las assumptions relacionadas con la necesidad de contar con información más objetiva y centralizada. En los pacientes se identificaron problemas de incertidumbre, falta de supervisión y dificultad para comprobar si los ejercicios se realizan correctamente. En las clínicas se evidenció la dependencia de información comunicada mediante WhatsApp, llamadas, videos ocasionales y registros separados, mientras que los centros ortopédicos señalaron dificultades para conocer el uso real, desgaste y necesidades de mantenimiento de las prótesis.

3. La información obtenida también muestra diferencias importantes entre las necesidades de los tres segmentos. Los pacientes priorizan facilidad de uso, retroalimentación comprensible y seguimiento de su progreso; los profesionales de rehabilitación necesitan datos biomecánicos interpretables, alertas y seguimiento entre sesiones; y los centros ortopédicos requieren trazabilidad de componentes, información de uso y soporte para mantenimiento preventivo. Estas diferencias justifican que Prothia contemple funcionalidades y experiencias diferenciadas según el rol del usuario.

4. La hipótesis relacionada con centralizar información de pacientes, clínicas de rehabilitación y centros ortopédicos encuentra un primer respaldo cualitativo en las entrevistas, debido a que los tres segmentos describen actualmente procesos de comunicación fragmentados. Sin embargo, en esta etapa todavía no es posible afirmar que la hipótesis se encuentra completamente validada, ya que será necesario comprobar durante las siguientes entregas si una versión funcional de Prothia mejora efectivamente el seguimiento, la comunicación y la toma de decisiones de los usuarios.

5. Los artefactos desarrollados durante el needfinding, entre ellos los User Personas, User Task Matrix, Journey Maps y Empathy Maps, permitieron transformar los resultados de las entrevistas en necesidades y tareas concretas. A partir de este análisis se priorizaron funcionalidades relacionadas con planes de rehabilitación, monitoreo biomecánico, seguimiento del progreso, alertas clínicas, mantenimiento de prótesis y comunicación entre los actores del sistema.

6. El Big Picture EventStorming y la definición del Ubiquitous Language permitieron establecer una representación común del dominio antes de definir la solución técnica. Posteriormente, las User Stories, el Product Backlog y el Design-Level EventStorming permitieron mantener trazabilidad entre las necesidades identificadas durante la investigación y las responsabilidades que deben ser implementadas en el producto.

7. El diseño UX/UI permitió llevar los requisitos definidos a una propuesta visual para la Landing Page y la Web Application. Los wireframes, mock-ups, wireflows, user flows y prototipos establecen una primera representación de la experiencia de pacientes, profesionales clínicos y centros ortopédicos. Esta propuesta deberá ser evaluada con usuarios representativos en las siguientes etapas para determinar si los flujos y la presentación de la información resultan realmente comprensibles y eficientes.

8. La arquitectura desarrollada mediante Domain-Driven Design y el modelo C4 permitió separar las principales responsabilidades de Prothia y mantener coherencia con el dominio previamente analizado. La definición de Context, Container y Component Diagrams, junto con los diagramas de clases y base de datos, proporciona una base técnica para implementar posteriormente la Web Application, el RESTful API y la persistencia de información sin concentrar todas las responsabilidades en un único componente.

9. En esta primera entrega se estableció también una estrategia para la gestión del código fuente y de los diferentes productos digitales del proyecto. El uso de repositorios independientes, GitFlow, Conventional Commits y Semantic Versioning proporciona una estructura de trabajo que facilita el desarrollo colaborativo y permite mantener trazabilidad sobre los cambios realizados durante las siguientes iteraciones.

10. Como primer avance funcional se logró contar con una versión desplegable de la Landing Page, utilizando HTML5, CSS3 y JavaScript y considerando GitHub Pages como plataforma de publicación. Este resultado permite disponer de un primer punto de contacto público para comunicar la propuesta de valor de Prothia. No obstante, las funcionalidades principales relacionadas con el seguimiento clínico, monitoreo biomecánico, alertas, gestión de rehabilitación y mantenimiento todavía deberán implementarse y validarse en los siguientes sprints.

11. En relación con los criterios de éxito definidos durante el proceso Lean UX, la evidencia disponible en AV1 permite evaluar principalmente la existencia y relevancia del problema, pero todavía no permite medir resultados como adopción recurrente de la plataforma, mejora del seguimiento clínico, reducción de problemas durante la rehabilitación o utilidad efectiva de los datos biomecánicos. Estos criterios deberán contrastarse progresivamente con las versiones funcionales y las entrevistas de validación de las siguientes entregas.

```{=typst}
#pagebreak()
```

```{=typst}
#pagebreak()
```

# Recomendaciones

1. **Priorización de funcionalidades críticas:** Continuar la implementación de Prothia priorizando las funcionalidades que aparecieron con mayor frecuencia e importancia durante el needfinding, especialmente el seguimiento de planes de rehabilitación, visualización de datos biomecánicos, generación de alertas y gestión del mantenimiento preventivo de las prótesis[cite: 24].

2. **Acceso diferenciado por roles:** Implementar en los siguientes sprints la primera versión funcional de la Web Application manteniendo el acceso diferenciado por roles definido en los requisitos y en la arquitectura, de manera que pacientes, profesionales clínicos y técnicos ortopédicos accedan únicamente a la información y funciones correspondientes a sus responsabilidades[cite: 24].

3. **Arquitectura desacoplada en el backend:** Desarrollar progresivamente el RESTful API y la persistencia de datos respetando los Bounded Contexts, componentes, clases y esquemas definidos durante el diseño técnico, evitando introducir dependencias innecesarias entre responsabilidades de dominio[cite: 24].

4. **Validación temprana con usuarios:** Realizar pruebas de usabilidad con usuarios representativos de los tres segmentos antes de considerar definitivas las interfaces desarrolladas en Figma[cite: 24]. Estas pruebas deben permitir comprobar especialmente la facilidad para interpretar dashboards, consultar progreso, identificar alertas y acceder a información relacionada con mantenimiento[cite: 24].

5. **Contraste de hipótesis y métricas Lean UX:** Durante las siguientes entregas, ejecutar las entrevistas de validación y evaluaciones heurísticas necesarias para contrastar las Hypothesis Statements y los criterios de éxito definidos durante Lean UX[cite: 24]. Los resultados deberán utilizarse para corregir assumptions que no coincidan con el comportamiento observado de los usuarios[cite: 24].

6. **Integración progresiva de telemetría:** Validar progresivamente la forma en que se obtendrán y procesarán los datos biomecánicos, comenzando con datos controlados o simulados cuando sea necesario y posteriormente comprobando la integración con sensores compatibles, debido a que la disponibilidad y precisión de esta información representa una parte esencial de la propuesta de valor de Prothia[cite: 24].

7. **Disciplina de control de versiones:** Mantener durante el desarrollo las prácticas de control de versiones establecidas para el proyecto, utilizando ramas de trabajo, mensajes de Conventional Commits y versiones identificables para facilitar la revisión de la participación del equipo y la trazabilidad entre requisitos, implementación y entregas[cite: 24].

8. **Alcance de la Landing Page:** Utilizar la Landing Page desplegada como primer canal para presentar la propuesta de valor y captar interés de clínicas y centros ortopédicos, pero evitar utilizar su publicación como evidencia de validación del producto completo, debido a que las principales funciones de Prothia todavía requieren implementación y evaluación con usuarios reales[cite: 24].

9. **Trazabilidad evolutiva de conclusiones:** Actualizar las conclusiones en cada entrega incorporando únicamente nueva evidencia obtenida durante el desarrollo y la validación[cite: 24]. De esta manera, las conclusiones actuales podrán contrastarse posteriormente con los resultados de la Web Application, Web Services, entrevistas de validación y versión final del producto[cite: 24].

```{=typst}
#pagebreak()
```

```{=typst}
#pagebreak()
#set par(hanging-indent: 1.5em)
```

# Bibliografía

Atlassian. (2020). *Gitflow workflow tutorial*. Atlassian Git Tutorials. https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow[cite: 25]

Bateni, H. (2012). Changes in balance in people with lower limb amputation using telemedicine-based rehabilitation. *Telemedicine and e-Health*, 18(7), 548–554. https://doi.org/10.1089/tmj.2011.0238[cite: 25]

Congreso de la República del Perú. (2011, 3 de julio). *Ley N.° 29733: Ley de Protección de Datos Personales*. Diario Oficial El Peruano. https://www.minjus.gob.pe/wp-content/uploads/2014/02/Cartilla-Funciones.pdf[cite: 25]

Conventional Commits. (2022). *Conventional Commits 1.0.0: A specification for adding human and machine readable meaning to commit messages*. https://www.conventionalcommits.org/en/v1.0.0/[cite: 25]

Driessen, V. (2010, 5 de enero). *A successful Git branching model*. nvie.com. https://nvie.com/posts/a-successful-git-branching-model/[cite: 25]

Gailey, R., Allen, K., Castles, J., Kucharik, J., & Roeder, M. (2008). Review of secondary physical conditions associated with lower-limb amputation and long-term prosthesis use. *Journal of Rehabilitation Research and Development*, 45(1), 15–30. https://doi.org/10.1682/JRRD.2006.11.0147[cite: 25]

Google. (2024). *Google HTML/CSS Style Guide*. Google GitHub Style Guides. https://google.github.io/styleguide/htmlcssguide.html[cite: 25]

Google Search Central. (2024). *Robots meta tag, data-nosnippet, and X-Robots-Tag specifications*. Google Developers. https://developers.google.com/search/docs/crawling-indexing/robots-meta-tag[cite: 25]

Instituto Nacional de Estadística e Informática. (2014). *Primera Encuesta Nacional Especializada sobre Discapacidad (ENEDIS 2012): Resumen ejecutivo*. INEI. https://www.inei.gob.pe/media/MenuRecursivo/publicaciones_digitales/Est/Lib1171/ENEDIS%202012%20-%20COMPLETO.pdf[cite: 25]

Ottobock SE & Co. KGaA. (2024). *Digital solutions and orthotic care overview*. Ottobock Global. https://www.ottobock.com/[cite: 25]

Preston-Werner, T. (2013). *Semantic Versioning 2.0.0*. https://semver.org/spec/v2.0.0.html[cite: 25]

World Health Organization. (2017). *WHO standards for prosthetics and orthotics*. World Health Organization. https://www.who.int/publications/i/item/9789241512480[cite: 25]

World Wide Web Consortium. (2018). *Web Content Accessibility Guidelines (WCAG) 2.1* (W3C Recommendation). W3C. https://www.w3.org/TR/WCAG21/[cite: 25]

```{=typst}
#set par(hanging-indent: 0em)
#pagebreak()
```

```{=typst}
#pagebreak()
```

# Anexos

### Enlaces de Evidencias Audiovisuales y Exposiciones

* **Exposición Hito AV1:**  
  [Ver grabación en OneDrive/SharePoint](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241i469_upc_edu_pe/IQDqhAqZpAyeR5ceLW2ZlHXYAe9KDSyisVNcXhKU1fc8GPE?e=YVZ80N)[cite: 26]

* **Exposición Hito TB1:**  
  *(Pendiente de adjuntar enlace de sustentación TB1)*[cite: 26]

* **Video Explicativo de la Landing Page:**  
  [Ver video explicativo](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241i469_upc_edu_pe/IQDlZXDCog1hSZahgdohxRyZAUDE54ZWuqHOa2_hl9PXBZ0?e=IQIjez)[cite: 26]

* **Video de Navegación del Prototipo:**  
  [Ver flujo interactivo en Figma](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241i469_upc_edu_pe/IQBrWctxdhvqS5eny_ZvVn_MASUXQFA7N_7C3_EMiJk3FeQ?e=DdLokI)[cite: 26]

---

### Evidencias de Entrevistas (Needfinding)

* **Entrevistas - Grabación Parte 1:**  
  [Ver grabaciones en OneDrive](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241i469_upc_edu_pe/IQC81Hz0hs9_QpIxWhYZ-TjAAZf92aSnv0wk24MMSoN7wl8?e=bn9ByD)[cite: 26]

* **Entrevistas - Grabación Parte 2:**  
  [Ver grabaciones en OneDrive](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241i469_upc_edu_pe/IQA_9jwIEEgTT4TH9ExhYDXBAStBqIjWMSpQZy_NVhKqW4s?e=Tad25u)[cite: 26]

---

### Tableros Ágiles de Trabajo (Trello)

* **Tablero General del Product Backlog:**  
  [Acceder al tablero en Trello](https://trello.com/invite/b/6aaa2414fe1250572c17b9fe/ATTIe7f0872c34d6ae28c8540edd005e015fC1DFC2EC/seniors-in-process-prothia)[cite: 26]

* **Tablero Sprint Backlog 1:**  
  [Acceder al tablero en Trello](https://trello.com/invite/b/6aabb55b023122d8fe598ee0/ATTI98b4a9da9fc821f35855872e0885a87cFED1E6E2/seniorsinprocess-prothia-sprint-1)[cite: 26]

* **Tablero Sprint Backlog 2:**  
  [Acceder al tablero en Trello](https://trello.com/invite/b/6ac4c443ac48cfe5f3483422/ATTI5559667781037e2f809ea13a3cfc44a317501C04/seniorsinprocess-prothia-sprint-backlog-2)[cite: 26]