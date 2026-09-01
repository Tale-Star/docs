<div style="margin-top: 140px;"></div>

<div align="center">
  <img src="./imgs/upc-logo.png" alt="Logo de UPC" width="120" />
</div>

## <p align="center">Universidad Peruana de Ciencias Aplicadas</p>

<p align="center">Ingeniería de Software</p>
<p align="center"><strong>Ciclo:</strong> 202620</p>
<p align="center">1ASI0728 | Arquitecturas de Software Emergentes</p>
<p align="center"><strong>NRC:</strong> 16365</p>
<p align="center"><strong>Docente:</strong> Enrique Alejandro Valdivia Verde</p>

# <p align="center">Informe del Trabajo Final</p>
<p align="center"><strong>Startup:</strong> Tale Star</p>
<p align="center"><strong>Producto:</strong> Tale Star</p>

### Integrantes

| Código | Nombres y Apellidos |
| :--- | :--- |
| U202210167 | Diego Antonio Seijas Vasquez |
| U20231D534 | Jorge Luis Diaz Fiestas |
| U202310004 | Ricardo Fernando Cardenas Minaya |
| U202310222 | Mariano Moises Oblitas Davila |
| U201819645 | Ariana Huapaya Buitron |

<p align="center"><strong>Diciembre 2026</strong></p>

<div style="page-break-before: always;"></div>

<a id="registro-de-versiones-del-informe"></a>
# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
| :--- | :--- | :--- | :--- |
|  |  |  |  |

<a id="project-report-collaboration-insights"></a>
# Project Report Collaboration Insights

<a id="contenido"></a>
# Contenido

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capitulo-i-introduccion)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripcion-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problematica)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capitulo-ii-requirements-elicitation-analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-analisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tacticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseno-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-analisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. Empathy Mapping](#233-empathy-mapping)
    - [2.3.4. As-is Scenario Mapping](#234-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capitulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Strategic-Level Software Design](#capitulo-iv-strategic-level-software-design)
  - [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
    - [4.1.1. Design Purpose](#411-design-purpose)
    - [4.1.2. Attribute-Driven Design Inputs](#412-attribute-driven-design-inputs)
      - [4.1.2.1. Primary Functionality (Primary User Stories)](#4121-primary-functionality-primary-user-stories)
      - [4.1.2.2. Quality Attribute Scenarios](#4122-quality-attribute-scenarios)
      - [4.1.2.3. Constraints](#4123-constraints)
    - [4.1.3. Architectural Drivers Backlog](#413-architectural-drivers-backlog)
    - [4.1.4. Architectural Design Decisions](#414-architectural-design-decisions)
    - [4.1.5. Quality Attribute Scenario Refinements](#415-quality-attribute-scenario-refinements)
  - [4.2. Strategic-Level Domain-Driven Design](#42-strategic-level-domain-driven-design)
    - [4.2.1. EventStorming](#421-eventstorming)
    - [4.2.2. Candidate Context Discovery](#422-candidate-context-discovery)
    - [4.2.3. Domain Message Flows Modeling](#423-domain-message-flows-modeling)
    - [4.2.4. Bounded Context Canvases](#424-bounded-context-canvases)
    - [4.2.5. Context Mapping](#425-context-mapping)
  - [4.3. Software Architecture](#43-software-architecture)
    - [4.3.1. Software Architecture System Landscape Diagram](#431-software-architecture-system-landscape-diagram)
    - [4.3.2. Software Architecture Context Level Diagram](#432-software-architecture-context-level-diagram)
    - [4.3.3. Software Architecture Container Level Diagram](#433-software-architecture-container-level-diagram)
    - [4.3.4. Software Architecture Deployment Diagram](#434-software-architecture-deployment-diagram)
- [Capítulo V: Tactical-Level Software Design](#capitulo-v-tactical-level-software-design)
  - [5.1. Bounded Context: Story Authoring](#51-bounded-context-story-authoring)
    - [5.1.1. Domain Layer](#511-domain-layer)
    - [5.1.2. Interface Layer](#512-interface-layer)
    - [5.1.3. Application Layer](#513-application-layer)
    - [5.1.4. Infrastructure Layer](#514-infrastructure-layer)
    - [5.1.5. Bounded Context Software Architecture Component Level Diagrams](#515-bounded-context-software-architecture-component-level-diagrams)
    - [5.1.6. Bounded Context Software Architecture Code Level Diagrams](#516-bounded-context-software-architecture-code-level-diagrams)
      - [5.1.6.1. Bounded Context Domain Layer Class Diagrams](#5161-bounded-context-domain-layer-class-diagrams)
      - [5.1.6.2. Bounded Context Database Design Diagram](#5162-bounded-context-database-design-diagram)
  - [5.2. Bounded Context: Generative Media](#52-bounded-context-generative-media)
    - [5.2.1. Domain Layer](#521-domain-layer)
    - [5.2.2. Interface Layer](#522-interface-layer)
    - [5.2.3. Application Layer](#523-application-layer)
    - [5.2.4. Infrastructure Layer](#524-infrastructure-layer)
    - [5.2.5. Bounded Context Software Architecture Component Level Diagrams](#525-bounded-context-software-architecture-component-level-diagrams)
    - [5.2.6. Bounded Context Software Architecture Code Level Diagrams](#526-bounded-context-software-architecture-code-level-diagrams)
      - [5.2.6.1. Bounded Context Domain Layer Class Diagrams](#5261-bounded-context-domain-layer-class-diagrams)
      - [5.2.6.2. Bounded Context Database Design Diagram](#5262-bounded-context-database-design-diagram)
  - [5.3. Bounded Context: Identity & Access](#53-bounded-context-identity-access)
    - [5.3.1. Domain Layer](#531-domain-layer)
    - [5.3.2. Interface Layer](#532-interface-layer)
    - [5.3.3. Application Layer](#533-application-layer)
    - [5.3.4. Infrastructure Layer](#534-infrastructure-layer)
    - [5.3.5. Bounded Context Software Architecture Component Level Diagrams](#535-bounded-context-software-architecture-component-level-diagrams)
    - [5.3.6. Bounded Context Software Architecture Code Level Diagrams](#536-bounded-context-software-architecture-code-level-diagrams)
      - [5.3.6.1. Bounded Context Domain Layer Class Diagrams](#5361-bounded-context-domain-layer-class-diagrams)
      - [5.3.6.2. Bounded Context Database Design Diagram](#5362-bounded-context-database-design-diagram)
  - [5.4. Bounded Context: Content Library](#54-bounded-context-content-library)
    - [5.4.1. Domain Layer](#541-domain-layer)
    - [5.4.2. Interface Layer](#542-interface-layer)
    - [5.4.3. Application Layer](#543-application-layer)
    - [5.4.4. Infrastructure Layer](#544-infrastructure-layer)
    - [5.4.5. Bounded Context Software Architecture Component Level Diagrams](#545-bounded-context-software-architecture-component-level-diagrams)
    - [5.4.6. Bounded Context Software Architecture Code Level Diagrams](#546-bounded-context-software-architecture-code-level-diagrams)
      - [5.4.6.1. Bounded Context Domain Layer Class Diagrams](#5461-bounded-context-domain-layer-class-diagrams)
      - [5.4.6.2. Bounded Context Database Design Diagram](#5462-bounded-context-database-design-diagram)
- [Capítulo VI: Solution UX Design](#capitulo-vi-solution-ux-design)
  - [6.1. Style Guidelines](#61-style-guidelines)
    - [6.1.1. General Style Guidelines](#611-general-style-guidelines)
    - [6.1.2. Web, Mobile & Devices Style Guidelines](#612-web-mobile-devices-style-guidelines)
  - [6.2. Information Architecture](#62-information-architecture)
    - [6.2.1. Organization Systems](#621-organization-systems)
    - [6.2.2. Labeling Systems](#622-labeling-systems)
    - [6.2.3. Searching Systems](#623-searching-systems)
    - [6.2.4. SEO Tags and Meta Tags](#624-seo-tags-and-meta-tags)
    - [6.2.5. Navigation Systems](#625-navigation-systems)
  - [6.3. Landing Page UI Design](#63-landing-page-ui-design)
    - [6.3.1. Landing Page Wireframe](#631-landing-page-wireframe)
    - [6.3.2. Landing Page Mock-up](#632-landing-page-mock-up)
  - [6.4. Applications UX/UI Design](#64-applications-uxui-design)
    - [6.4.1. Applications Wireframes](#641-applications-wireframes)
    - [6.4.2. Applications Wireflow Diagrams](#642-applications-wireflow-diagrams)
    - [6.4.3. Applications Mock-ups](#643-applications-mock-ups)
    - [6.4.4. Applications User Flow Diagrams](#644-applications-user-flow-diagrams)
  - [6.5. Applications Prototyping](#65-applications-prototyping)
- [Capítulo VII: Product Implementation, Validation & Deployment](#capitulo-vii-product-implementation-validation-deployment)
  - [7.1. Software Configuration Management](#71-software-configuration-management)
    - [7.1.1. Software Development Environment Configuration](#711-software-development-environment-configuration)
    - [7.1.2. Source Code Management](#712-source-code-management)
    - [7.1.3. Source Code Style Guide & Conventions](#713-source-code-style-guide-conventions)
    - [7.1.4. Software Deployment Configuration](#714-software-deployment-configuration)
  - [7.2. Solution Implementation](#72-solution-implementation)
    - [7.2.1. Sprint 1](#721-sprint-1)
      - [7.2.1.1. Sprint Planning 1](#7211-sprint-planning-1)
      - [7.2.1.2. Sprint Backlog 1](#7212-sprint-backlog-1)
      - [7.2.1.3. Development Evidence for Sprint Review](#7213-development-evidence-for-sprint-review)
      - [7.2.1.4. Testing Suite Evidence for Sprint Review](#7214-testing-suite-evidence-for-sprint-review)
      - [7.2.1.5. Execution Evidence for Sprint Review](#7215-execution-evidence-for-sprint-review)
      - [7.2.1.6. Services Documentation Evidence for Sprint Review](#7216-services-documentation-evidence-for-sprint-review)
      - [7.2.1.7. Software Deployment Evidence for Sprint Review](#7217-software-deployment-evidence-for-sprint-review)
      - [7.2.1.8. Team Collaboration Insights during Sprint](#7218-team-collaboration-insights-during-sprint)
    - [7.2.2. Sprint 2](#722-sprint-2)
      - [7.2.2.1. Sprint Planning 2](#7221-sprint-planning-2)
      - [7.2.2.2. Sprint Backlog 2](#7222-sprint-backlog-2)
      - [7.2.2.3. Development Evidence for Sprint Review](#7223-development-evidence-for-sprint-review)
      - [7.2.2.4. Testing Suite Evidence for Sprint Review](#7224-testing-suite-evidence-for-sprint-review)
      - [7.2.2.5. Execution Evidence for Sprint Review](#7225-execution-evidence-for-sprint-review)
      - [7.2.2.6. Services Documentation Evidence for Sprint Review](#7226-services-documentation-evidence-for-sprint-review)
      - [7.2.2.7. Software Deployment Evidence for Sprint Review](#7227-software-deployment-evidence-for-sprint-review)
      - [7.2.2.8. Team Collaboration Insights during Sprint](#7228-team-collaboration-insights-during-sprint)
  - [7.3. Validation Interviews](#73-validation-interviews)
    - [7.3.1. Diseño de Entrevistas](#731-diseno-de-entrevistas)
    - [7.3.2. Registro de Entrevistas](#732-registro-de-entrevistas)
    - [7.3.3. Evaluaciones según heurísticas](#733-evaluaciones-segun-heuristicas)
  - [7.4. Video About-the-Product](#74-video-about-the-product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
  - [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografia)
- [Anexos](#anexos)
  - [Anexo A. Repositorios del proyecto](#anexo-a-repositorios-del-proyecto)
  - [Anexo B. Diseño y prototipos](#anexo-b-diseno-y-prototipos)
  - [Anexo C. Documentación de servicios](#anexo-c-documentacion-de-servicios)
  - [Anexo D. Videos de Exposiciones](#anexo-d-videos-de-exposiciones)

<a id="student-outcome"></a>
# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 3**  
**Criterio:** Capacidad de comunicarse efectivamente con un rango de audiencias.

| Criterio específico | Acciones realizadas | Conclusiones |
| :--- | :--- | :--- |
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. |  |  |
| Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. |  |  |

<a id="capitulo-i-introduccion"></a>
# Capítulo I: Introducción

<a id="11-startup-profile"></a>
## 1.1. Startup Profile

<a id="111-descripcion-de-la-startup"></a>
### 1.1.1. Descripción de la Startup

<a id="112-perfiles-de-integrantes-del-equipo"></a>
### 1.1.2. Perfiles de integrantes del equipo


| Nombre: Seijas Vasquez, Diego Antonio | <img src="imgs/team/Diego.png" alt="Diego" title="Foto de Diego" width="320"/> |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------- |
| **Código:** U202210167  |                               |
| **Carrera:** Ingeniería de Software |                               |
| **Habilidades:** Me llamo ____________. Tengo ____________ años. Estudio ____________. Me considero una persona ____________. Tengo conocimientos y experiencia en ____________. Puedo aportar al equipo mediante ____________.

| Nombre: Diaz Fiestas, Jorge Luis | <img src="imgs/team/Luis.png" alt="Luis" title="Foto de Luis" width="320"/> |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------- |
| **Código:** U20231D534  |                               |
| **Carrera:** Ingeniería de Software |                               |
| **Habilidades:** Me llamo ____________. Tengo ____________ años. Estudio ____________. Me considero una persona ____________. Tengo conocimientos y experiencia en ____________. Puedo aportar al equipo mediante ____________.

| Nombre: Cardenas Minaya, Ricardo Fernando | <img src="imgs/team/Ricardo.png" alt="Ricardo" title="Foto de Ricardo" width="320"/> |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------- |
| **Código:** U202310004  |                               |
| **Carrera:** Ingeniería de Software |                               |
| **Habilidades:** Me llamo ____________. Tengo ____________ años. Estudio ____________. Me considero una persona ____________. Tengo conocimientos y experiencia en ____________. Puedo aportar al equipo mediante ____________.

| Nombre: Oblitas Davila, Mariano Moises | <img src="imgs/team/Mariano.png" alt="Mariano" title="Foto de Mariano" width="320"/> |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------- |
| **Código:** U202310222  |                               |
| **Carrera:** Ingeniería de Software |                               |
| **Habilidades:** Me llamo ____________. Tengo ____________ años. Estudio ____________. Me considero una persona ____________. Tengo conocimientos y experiencia en ____________. Puedo aportar al equipo mediante ____________.

| Nombre: Huapaya Buitron, Ariana  | <img src="imgs/team/Ariana.png" alt="Ariana" title="Foto de Ariana" width="320"/> |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------- |
| **Código:** U201819645  |                               |
| **Carrera:** Ingeniería de Software |                               |
| **Habilidades:** Me llamo ____________. Tengo ____________ años. Estudio ____________. Me considero una persona ____________. Tengo conocimientos y experiencia en ____________. Puedo aportar al equipo mediante ____________.


<a id="12-solution-profile"></a>
## 1.2. Solution Profile

<a id="121-antecedentes-y-problematica"></a>
### 1.2.1. Antecedentes y problemática

<a id="122-lean-ux-process"></a>
### 1.2.2. Lean UX Process

<a id="1221-lean-ux-problem-statements"></a>
#### 1.2.2.1. Lean UX Problem Statements

<a id="1222-lean-ux-assumptions"></a>
#### 1.2.2.2. Lean UX Assumptions

<a id="1223-lean-ux-hypothesis-statements"></a>
#### 1.2.2.3. Lean UX Hypothesis Statements

<a id="1224-lean-ux-canvas"></a>
#### 1.2.2.4. Lean UX Canvas

<a id="13-segmentos-objetivo"></a>
## 1.3. Segmentos objetivo

<a id="capitulo-ii-requirements-elicitation-analysis"></a>
# Capítulo II: Requirements Elicitation & Analysis

<a id="21-competidores"></a>
## 2.1. Competidores

<a id="211-analisis-competitivo"></a>
### 2.1.1. Análisis competitivo

<a id="212-estrategias-y-tacticas-frente-a-competidores"></a>
### 2.1.2. Estrategias y tácticas frente a competidores

<a id="22-entrevistas"></a>
## 2.2. Entrevistas

<a id="221-diseno-de-entrevistas"></a>
### 2.2.1. Diseño de entrevistas

<a id="222-registro-de-entrevistas"></a>
### 2.2.2. Registro de entrevistas

<a id="223-analisis-de-entrevistas"></a>
### 2.2.3. Análisis de entrevistas

<a id="23-needfinding"></a>
## 2.3. Needfinding

<a id="231-user-personas"></a>
### 2.3.1. User Personas

<a id="232-user-task-matrix"></a>
### 2.3.2. User Task Matrix

<a id="233-empathy-mapping"></a>
### 2.3.3. Empathy Mapping

<a id="234-as-is-scenario-mapping"></a>
### 2.3.4. As-is Scenario Mapping

<a id="24-ubiquitous-language"></a>
## 2.4. Ubiquitous Language

<a id="capitulo-iii-requirements-specification"></a>
# Capítulo III: Requirements Specification

<a id="31-to-be-scenario-mapping"></a>
## 3.1. To-Be Scenario Mapping

<a id="32-user-stories"></a>
## 3.2. User Stories

<a id="33-impact-mapping"></a>
## 3.3. Impact Mapping

<a id="34-product-backlog"></a>
## 3.4. Product Backlog

<a id="capitulo-iv-strategic-level-software-design"></a>
# Capítulo IV: Strategic-Level Software Design

<a id="41-strategic-level-attribute-driven-design"></a>
## 4.1. Strategic-Level Attribute-Driven Design

<a id="411-design-purpose"></a>
### 4.1.1. Design Purpose

<a id="412-attribute-driven-design-inputs"></a>
### 4.1.2. Attribute-Driven Design Inputs

<a id="4121-primary-functionality-primary-user-stories"></a>
#### 4.1.2.1. Primary Functionality (Primary User Stories)

<a id="4122-quality-attribute-scenarios"></a>
#### 4.1.2.2. Quality Attribute Scenarios

<a id="4123-constraints"></a>
#### 4.1.2.3. Constraints

<a id="413-architectural-drivers-backlog"></a>
### 4.1.3. Architectural Drivers Backlog

<a id="414-architectural-design-decisions"></a>
### 4.1.4. Architectural Design Decisions

<a id="415-quality-attribute-scenario-refinements"></a>
### 4.1.5. Quality Attribute Scenario Refinements

<a id="42-strategic-level-domain-driven-design"></a>
## 4.2. Strategic-Level Domain-Driven Design

<a id="421-eventstorming"></a>
### 4.2.1. EventStorming

<a id="422-candidate-context-discovery"></a>
### 4.2.2. Candidate Context Discovery

<a id="423-domain-message-flows-modeling"></a>
### 4.2.3. Domain Message Flows Modeling

<a id="424-bounded-context-canvases"></a>
### 4.2.4. Bounded Context Canvases

<a id="425-context-mapping"></a>
### 4.2.5. Context Mapping

<a id="43-software-architecture"></a>
## 4.3. Software Architecture

<a id="431-software-architecture-system-landscape-diagram"></a>
### 4.3.1. Software Architecture System Landscape Diagram

<a id="432-software-architecture-context-level-diagram"></a>
### 4.3.2. Software Architecture Context Level Diagram

<a id="433-software-architecture-container-level-diagram"></a>
### 4.3.3. Software Architecture Container Level Diagram

<a id="434-software-architecture-deployment-diagram"></a>
### 4.3.4. Software Architecture Deployment Diagram

<a id="capitulo-v-tactical-level-software-design"></a>
# Capítulo V: Tactical-Level Software Design

<a id="51-bounded-context-story-authoring"></a>
## 5.1. Bounded Context: Story Authoring

<a id="511-domain-layer"></a>
### 5.1.1. Domain Layer

<a id="512-interface-layer"></a>
### 5.1.2. Interface Layer

<a id="513-application-layer"></a>
### 5.1.3. Application Layer

<a id="514-infrastructure-layer"></a>
### 5.1.4. Infrastructure Layer

<a id="515-bounded-context-software-architecture-component-level-diagrams"></a>
### 5.1.5. Bounded Context Software Architecture Component Level Diagrams

<a id="516-bounded-context-software-architecture-code-level-diagrams"></a>
### 5.1.6. Bounded Context Software Architecture Code Level Diagrams

<a id="5161-bounded-context-domain-layer-class-diagrams"></a>
#### 5.1.6.1. Bounded Context Domain Layer Class Diagrams

<a id="5162-bounded-context-database-design-diagram"></a>
#### 5.1.6.2. Bounded Context Database Design Diagram

<a id="52-bounded-context-generative-media"></a>
## 5.2. Bounded Context: Generative Media

<a id="521-domain-layer"></a>
### 5.2.1. Domain Layer

<a id="522-interface-layer"></a>
### 5.2.2. Interface Layer

<a id="523-application-layer"></a>
### 5.2.3. Application Layer

<a id="524-infrastructure-layer"></a>
### 5.2.4. Infrastructure Layer

<a id="525-bounded-context-software-architecture-component-level-diagrams"></a>
### 5.2.5. Bounded Context Software Architecture Component Level Diagrams

<a id="526-bounded-context-software-architecture-code-level-diagrams"></a>
### 5.2.6. Bounded Context Software Architecture Code Level Diagrams

<a id="5261-bounded-context-domain-layer-class-diagrams"></a>
#### 5.2.6.1. Bounded Context Domain Layer Class Diagrams

<a id="5262-bounded-context-database-design-diagram"></a>
#### 5.2.6.2. Bounded Context Database Design Diagram

<a id="53-bounded-context-identity-access"></a>
## 5.3. Bounded Context: Identity & Access

<a id="531-domain-layer"></a>
### 5.3.1. Domain Layer

<a id="532-interface-layer"></a>
### 5.3.2. Interface Layer

<a id="533-application-layer"></a>
### 5.3.3. Application Layer

<a id="534-infrastructure-layer"></a>
### 5.3.4. Infrastructure Layer

<a id="535-bounded-context-software-architecture-component-level-diagrams"></a>
### 5.3.5. Bounded Context Software Architecture Component Level Diagrams

<a id="536-bounded-context-software-architecture-code-level-diagrams"></a>
### 5.3.6. Bounded Context Software Architecture Code Level Diagrams

<a id="5361-bounded-context-domain-layer-class-diagrams"></a>
#### 5.3.6.1. Bounded Context Domain Layer Class Diagrams

<a id="5362-bounded-context-database-design-diagram"></a>
#### 5.3.6.2. Bounded Context Database Design Diagram

<a id="54-bounded-context-content-library"></a>
## 5.4. Bounded Context: Content Library

<a id="541-domain-layer"></a>
### 5.4.1. Domain Layer

<a id="542-interface-layer"></a>
### 5.4.2. Interface Layer

<a id="543-application-layer"></a>
### 5.4.3. Application Layer

<a id="544-infrastructure-layer"></a>
### 5.4.4. Infrastructure Layer

<a id="545-bounded-context-software-architecture-component-level-diagrams"></a>
### 5.4.5. Bounded Context Software Architecture Component Level Diagrams

<a id="546-bounded-context-software-architecture-code-level-diagrams"></a>
### 5.4.6. Bounded Context Software Architecture Code Level Diagrams

<a id="5461-bounded-context-domain-layer-class-diagrams"></a>
#### 5.4.6.1. Bounded Context Domain Layer Class Diagrams

<a id="5462-bounded-context-database-design-diagram"></a>
#### 5.4.6.2. Bounded Context Database Design Diagram

<a id="capitulo-vi-solution-ux-design"></a>
# Capítulo VI: Solution UX Design

<a id="61-style-guidelines"></a>
## 6.1. Style Guidelines

<a id="611-general-style-guidelines"></a>
### 6.1.1. General Style Guidelines

<a id="612-web-mobile-devices-style-guidelines"></a>
### 6.1.2. Web, Mobile & Devices Style Guidelines

<a id="62-information-architecture"></a>
## 6.2. Information Architecture

<a id="621-organization-systems"></a>
### 6.2.1. Organization Systems

<a id="622-labeling-systems"></a>
### 6.2.2. Labeling Systems

<a id="623-searching-systems"></a>
### 6.2.3. Searching Systems

<a id="624-seo-tags-and-meta-tags"></a>
### 6.2.4. SEO Tags and Meta Tags

<a id="625-navigation-systems"></a>
### 6.2.5. Navigation Systems

<a id="63-landing-page-ui-design"></a>
## 6.3. Landing Page UI Design

<a id="631-landing-page-wireframe"></a>
### 6.3.1. Landing Page Wireframe

<a id="632-landing-page-mock-up"></a>
### 6.3.2. Landing Page Mock-up

<a id="64-applications-uxui-design"></a>
## 6.4. Applications UX/UI Design

<a id="641-applications-wireframes"></a>
### 6.4.1. Applications Wireframes

<a id="642-applications-wireflow-diagrams"></a>
### 6.4.2. Applications Wireflow Diagrams

<a id="643-applications-mock-ups"></a>
### 6.4.3. Applications Mock-ups

<a id="644-applications-user-flow-diagrams"></a>
### 6.4.4. Applications User Flow Diagrams

<a id="65-applications-prototyping"></a>
## 6.5. Applications Prototyping

<a id="capitulo-vii-product-implementation-validation-deployment"></a>
# Capítulo VII: Product Implementation, Validation & Deployment

<a id="71-software-configuration-management"></a>
## 7.1. Software Configuration Management

<a id="711-software-development-environment-configuration"></a>
### 7.1.1. Software Development Environment Configuration

<a id="712-source-code-management"></a>
### 7.1.2. Source Code Management

<a id="713-source-code-style-guide-conventions"></a>
### 7.1.3. Source Code Style Guide & Conventions

<a id="714-software-deployment-configuration"></a>
### 7.1.4. Software Deployment Configuration

<a id="72-solution-implementation"></a>
## 7.2. Solution Implementation

<a id="721-sprint-1"></a>
### 7.2.1. Sprint 1

<a id="7211-sprint-planning-1"></a>
#### 7.2.1.1. Sprint Planning 1

<a id="7212-sprint-backlog-1"></a>
#### 7.2.1.2. Sprint Backlog 1

<a id="7213-development-evidence-for-sprint-review"></a>
#### 7.2.1.3. Development Evidence for Sprint Review

<a id="7214-testing-suite-evidence-for-sprint-review"></a>
#### 7.2.1.4. Testing Suite Evidence for Sprint Review

<a id="7215-execution-evidence-for-sprint-review"></a>
#### 7.2.1.5. Execution Evidence for Sprint Review

<a id="7216-services-documentation-evidence-for-sprint-review"></a>
#### 7.2.1.6. Services Documentation Evidence for Sprint Review

<a id="7217-software-deployment-evidence-for-sprint-review"></a>
#### 7.2.1.7. Software Deployment Evidence for Sprint Review

<a id="7218-team-collaboration-insights-during-sprint"></a>
#### 7.2.1.8. Team Collaboration Insights during Sprint

<a id="722-sprint-2"></a>
### 7.2.2. Sprint 2

<a id="7221-sprint-planning-2"></a>
#### 7.2.2.1. Sprint Planning 2

<a id="7222-sprint-backlog-2"></a>
#### 7.2.2.2. Sprint Backlog 2

<a id="7223-development-evidence-for-sprint-review"></a>
#### 7.2.2.3. Development Evidence for Sprint Review

<a id="7224-testing-suite-evidence-for-sprint-review"></a>
#### 7.2.2.4. Testing Suite Evidence for Sprint Review

<a id="7225-execution-evidence-for-sprint-review"></a>
#### 7.2.2.5. Execution Evidence for Sprint Review

<a id="7226-services-documentation-evidence-for-sprint-review"></a>
#### 7.2.2.6. Services Documentation Evidence for Sprint Review

<a id="7227-software-deployment-evidence-for-sprint-review"></a>
#### 7.2.2.7. Software Deployment Evidence for Sprint Review

<a id="7228-team-collaboration-insights-during-sprint"></a>
#### 7.2.2.8. Team Collaboration Insights during Sprint

<a id="73-validation-interviews"></a>
## 7.3. Validation Interviews

<a id="731-diseno-de-entrevistas"></a>
### 7.3.1. Diseño de Entrevistas

<a id="732-registro-de-entrevistas"></a>
### 7.3.2. Registro de Entrevistas

<a id="733-evaluaciones-segun-heuristicas"></a>
### 7.3.3. Evaluaciones según heurísticas

<a id="74-video-about-the-product"></a>
## 7.4. Video About-the-Product

<a id="conclusiones"></a>
# Conclusiones

<a id="conclusiones-y-recomendaciones"></a>
## Conclusiones y recomendaciones

<a id="video-about-the-team"></a>
## Video About-the-Team

<a id="bibliografia"></a>
# Bibliografía

<a id="anexos"></a>
# Anexos

<a id="anexo-a-repositorios-del-proyecto"></a>
## Anexo A. Repositorios del proyecto

<a id="anexo-b-diseno-y-prototipos"></a>
## Anexo B. Diseño y prototipos

<a id="anexo-c-documentacion-de-servicios"></a>
## Anexo C. Documentación de servicios

<a id="anexo-d-videos-de-exposiciones"></a>
## Anexo D. Videos de Exposiciones
