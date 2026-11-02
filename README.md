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
```

