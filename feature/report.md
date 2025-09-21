<div align="center">
<img src="../assets/upc_logo.png" alt="UPC Logo" width="200"/>

# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS

### Carrera: Ingeniería de Software

### Desarrollo de Aplicaciones Open Source - Presencial (1ASI0729)

### Profesor: Hugo Allan Mori Paiva

### NRC: 7401

## Informe - TB1

## Startup: Prodevs

## Producto: DenunciaYa

### INTEGRANTES

<div style="text-align: center;">

|        Apellidos y Nombres        | Código de Alumno |
|:---------------------------------:|:----------------:|
|   Mamani Marca, Gabriel Cristian  | u202220659       |
|   Omar Harold Rivera Ticllacuri   | u202214214       |
|      Franco Diego Rioja Nuñez     | u202221597       |
| Gabriel Anthony Brabuaite Toledo  | U20201e889       |
|   Augusto Sebastian Montes Maza   | u202218645       |

</div>

### Ciclo 2025-20

---

</div>

# Registro de versiones del informe

| Versión | Fecha       | Autor(es)                                                                                           | Descripción de modificación                                                                                                                                                                                                 |
|---------|-------------|------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| TB1     | 10/09/2024  | Mamani Marca, Gabriel Cristian <br> Omar Harold Rivera Ticllacuri  <br> Franco Diego Rioja Nuñez  <br> Gabriel Anthony Brabuaite Toledo  <br> Augusto Sebastian Montes Maza  | Se agregó el contenido del capítulo 1 (apartados 1.1, 1.2 y 1.3); el contenido del capítulo 2 (apartados 2.1, 2.2, 2.3, 2.4); el contenido del capítulo 3 (apartados 3.1, 3.2, 3.3 y 3.4); el contenido del capítulo 4 (apartados 4.1, 4.2, 4.3, 4.4, 4.5, 4.6, 4.7 y 4.8); y el contenido del capítulo 5 (apartados 5.1 y 5.2). |

# PROJECT REPORT COLLABORATION INSIGHTS

| Repositorio del Informe en GitHub |
|--|
| https://github.com/1ASI0729-7401-2520-Prodevs-DenunciaYa/DenunciaYa-Proyect-Report

TB1: Las tareas asignadas para la entrega TB1 se han completado y están documentadas en el siguiente repositorio de GitHub perteneciente a la organización del equipo: 
[Repositorio GitHUb](https://github.com/1ASI0729-7401-2520-Prodevs-DenunciaYa/DenunciaYa-Proyect-Report), link: | https://github.com/1ASI0729-7401-2520-Prodevs-DenunciaYa/DenunciaYa-Proyect-Report

### 2. Actividades de elaboracion del informe 
Durante la elaboración del informe se realizaron diversas actividades. Cada integrante redactó y diagramó sus contenidos asignados en formato Markdown, registrando posteriormente commits que permitieron mantener un control del avance en el repositorio. Asimismo, se generaron los artefactos correspondientes con las herramientas establecidas y se obtuvieron los enlaces de las imágenes desde la carpeta Assets ubicada en la rama develop del repositorio del informe. Finalmente, se llevaron a cabo reuniones de coordinación para supervisar el progreso del trabajo y compartir los avances vinculados al Sprint 1, cuyo objetivo principal fue la Landing Page.
### 3. Capturas en imagen de los analíticos de colaboración y commits en GitHub
![Contributors Analytics](../assets/contributors-analytics-2.png)


### 4. Evidencia de participacion de todos los miembros del equipo 
![Evidencia Participacion](../assets/Evidencia.png)

# Contenido

## Tabla de Contenidos
### [Registro de versiones del informe](#registro-de-versiones-del-informe)
### [Project Report Collaboration Insights](#project-report-collaboration-insights)
### [Contenido](#contenido)
### [Student Outcome](#student-outcome-1)
### [Capítulo I: Introducción](#capc3adtulo-i-introduccic3b3n-1)
- [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-description-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
        - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
        - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
        - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
        - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

### [Capítulo II: Requirements Elicitation & Analysis](#capc3adtulo-ii-requirements-elicitation--analysis-1)
- [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
    - [2.4. Ubiquitous Language](#24-Ubiquitous-language)
### [Capítulo III: Requirements Specification](#capc3adtulo-iii-requirements-specification-1)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

### [Capítulo IV: Product Design](#capc3adtulo-iv-product-design-1)
- [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
- [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
- [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
- [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
- [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
- [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
- [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
- [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)

### [Capítulo V: Product Implementation, Validation & Deployment](#capc3adtulo-v-product-implementation-validation--deployment-1)
  - [5.1. Software Configuration Management.](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration.](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management.](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions.](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration.](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services \& Applications Implementation.](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
    - [5.2.1.1. Sprint Planning 1.](#5211-sprint-planning-1)
    - [5.2.1.2. Aspect Leaders and Collaborators.](#5212-aspect-leaders-and-collaborators)
    - [5.2.1.3. Sprint Backlog 1.](#5213-sprint-backlog-1)
    - [5.2.1.4. Development Evidence for Sprint Review.](#5214-development-evidence-for-sprint-review)
    - [5.2.1.5. Execution Evidence for Sprint Review.](#5215-execution-evidence-for-sprint-review)
    - [5.2.1.6. Services Documentation Evidence for Sprint Review.](#5216-services-documentation-evidence-for-sprint-review)
    - [5.2.1.7. Software Deployment Evidence for Sprint Review.](#5217-software-deployment-evidence-for-sprint-review)
    - [5.2.1.8. Team Collaboration Insights during Sprint.](#5218-team-collaboration-insights-during-sprint)

# Student Outcome
**ABET – EAC - Student Outcome 5**  
*Criterio: La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.*

| Criterio específico                                                   | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Conclusiones |
|-----------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|
| Comunica oralmente con efectividad a diferentes rangos de audiencia.  | **TB1 <br> Gabriel Braithwaite:** Se comunicó con el equipo para el planeamiento del proyecto.<br>Comunicó la propuesta del proyecto hacia una persona de uno de los segmentos objetivos definidos mediante una entrevista oral. <br> **Gabriel Mamani**:Me comuniqué eficazmente y organicé mi tiempo para poder cumplir con mis responsabilidades tanto en las historias de usuario como en el capítulo de C4 diagrams.<br> **TB1 <br> Omar Rivera:** Me comuniqué con mi equipo para coordinar y liderar la parte del diseño de la landing page, asegurando que la propuesta reflejara los objetivos del proyecto.<br>Expliqué de forma clara las ideas y lineamientos generales de estilo para que el equipo pudiera aplicarlos en el desarrollo de los mockups y wireframes de las aplicaciones web. <br>  **TB1 <br> Franco Rioja:**: Contacté constantemente con el equipo para ayudar a que estemos en constante avance mutuo para estar todos alineados   <br>  **TB1 <br> Augusto Montes:** Dirección de entrevista con los segmentos objetivos clave para el proyecto. Estableciendo un diálogo claro y conciso para obtener información valiosa sobre las necesidades y expectativas de los usuarios, comunicación fue crucial para la definición de los requisitos del proyecto.                                                                                                                                                                                           | TB1:  El equipo demostró una comunicación efectiva y constante tanto interna como externa, lo que permitió mantener alineación en los objetivos y claridad en la transmisión de ideas; cada integrante organizó adecuadamente su tiempo y responsabilidades, aportando en áreas clave como las historias de usuario, los diagramas C4 y el diseño de la landing page, mientras que la coordinación y colaboración continua favorecieron el avance mutuo y el cumplimiento de los objetivos del proyecto.      |
| Comunica por escrito con efectividad a diferentes rangos de audiencia | **TB1 - Gabriel Braithwaite:** Comunicó las propuestas para diferentes puntos del proyecto de manera escrita para los miembros del equipo.<br>Los puntos realizados para el proyecto fueron documentados de manera escrita en el repositorio del reporte.<br>Gabriel Mamani: Durante el desarrollo del proyecto, desempeñé un rol integral al liderar la creación de los event storming, un proceso fundamental para establecer los requisitos y funcionalidades clave de nuestra aplicación.<br>**TB1 <br> Omar Rivera:** Documenté las guías generales de estilo y la propuesta de diseño en el repositorio del proyecto para facilitar su aplicación por el equipo.<br>Desarrollé y dejé registrados los mockups y wireframes tanto de la landing page como de las web applications, asegurando consistencia visual y comunicando de manera escrita las decisiones clave de diseño. **TB1 <br> Franco Rioja:**: Mi labro fue la realización de los user persona a partir de las entrevistas, a partir de eso completé la mayoría de apartados del needfiding, además hice una pequeña parte importante del capítulo 4 como por ejemplo el diagrama de clases <br> **TB1 <br> Augusto Montes:** Determinación de los segmentos objetivos finales del proyecto. Redacción de resumen claro y conciso de los logros y el progreso del equipo durante el sprint. | TB1:   En esta etapa del proyecto, el equipo se enfocó en la documentación y definición de requisitos, dejando un registro claro y organizado de los avances; Gabriel Braithwaite plasmó las propuestas y puntos desarrollados en el repositorio del reporte, mientras que Gabriel Mamani lideró la construcción del event storming para definir funcionalidades clave; Omar Rivera consolidó las guías de estilo, mockups y wireframes con documentación detallada que garantizó consistencia visual, y Franco Rioja aportó con la creación de user persona, el needfinding y diagramas de clases, fortaleciendo el entendimiento del usuario y la estructura técnica del sistema.     |

# Capítulo I: Introducción
## 1.1. Startup Profile

A continuación, se presenta información sobre a qué se dedica nuestra startup, Prodevs.

### 1.1.1. Descripción de la Startup

**Prodevs** es una startup tecnológica orientada a la creación de soluciones digitales que fortalecen la participación ciudadana y promueven la transparencia en la gestión pública. Nuestro objetivo general es cerrar la brecha entre los ciudadanos y las autoridades, utilizando la tecnología como un puente que facilite la comunicación, aumente la confianza y mejore la capacidad de respuesta de los gobiernos locales. Nos dedicamos a diseñar plataformas seguras, intuitivas y escalables que conviertan la voz ciudadana en datos accionables para la toma de decisiones.

Nuestra principal propuesta es **DenunciaYa**, una aplicación que permite a los ciudadanos reportar de manera rápida y segura problemas cotidianos como baches, basura, fugas de agua, corrupción o deficiencias en los servicios públicos. El propósito de la aplicación es simplificar el proceso de denuncia, garantizando anonimato opcional, seguimiento en tiempo real y notificaciones inmediatas sobre el estado de los reportes. Al mismo tiempo, ofrece a las autoridades un sistema integral de gestión con paneles de control, herramientas de análisis y métricas de eficiencia, contribuyendo a mejorar la calidad de los servicios municipales y gubernamentales.

**Misión:** Empoderar a los ciudadanos a través de la tecnología, brindándoles una herramienta confiable y accesible para denunciar problemas que afectan su entorno, mientras ayudamos a las autoridades a gestionar de manera más transparente, eficiente y responsable los recursos y soluciones públicas.

**Visión:** Convertirnos en la plataforma líder en Latinoamérica para denuncias ciudadanas y gestión de problemáticas urbanas, construyendo ciudades más transparentes, seguras y participativas, donde cada reporte ciudadano se traduzca en acción concreta y mejora de la calidad de vida.

**Alcance del proyecto:** Contempla en su fase inicial la implementación de la aplicación en municipios medianos y grandes, ofreciendo planes de suscripción adaptados a las capacidades de cada administración. A corto plazo, se busca consolidar la solución como un estándar en la gestión de denuncias urbanas; a mediano plazo, expandirse hacia distintas ciudades de la región, integrando la plataforma con sistemas existentes y canales de comunicación como WhatsApp; y a largo plazo, posicionarse como un ecosistema integral de gobernanza digital que promueva la participación activa de los ciudadanos y la modernización de los servicios públicos.

### 1.1.2. Perfiles de integrantes del equipo

| Foto                                                     |        Apellidos y Nombres        | Código de Alumno | Carrera                | Habilidades                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|----------------------------------------------------------|:---------------------------------:|:----------------:|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![GabrielMamani.png](../assets/GabrielMamani.png)        |   Mamani Marca, Gabriel Cristian  | u202220659       | Ingenieria de software | Soy estudiante de sexto ciclo de la carrera de Ingeniería de Software.Durante el camino aprendi lenguajes como c++,python y java.Tambien,sobre motores de base de datos como MongoDb y MYSQL                                                                                                                                                                                                                                                                            |
| ![GabrielMamani.png](../assets/Omar.jpeg)                |   Omar Harold Rivera Ticllacuri   | u202214214       | Ingenieria de software | Soy estudiante de Ingeniería de Software, tengo 20 años y actualmente me encuentro en el sexto ciclo de mi carrera. Soy una persona con la cual tengo la disciplina y responsable para desarrollar proyectos de software y software de entretenimiento. Cuento con experiencia sobre el desarrollo de software de entretenimiento. Por ende, apoyaré al grupo en todo lo posible para poder desarrollar adecuadamente el trabajo y la propuesta que se nos asignó.	     |
| ![Diego.jpeg](../assets/Diego.jpeg)                                                         |      Franco Diego Rioja Nuñez     | u202221597       |    Ingenieria de software                    | Soy estudiante de Ingeniería de Software, tengo 20 años y actualmente curso el séptimo ciclo de la carrera. Me considero una persona proactiva y comprometida en el desarrollo de proyectos, además de ser colaborativa y atenta a las necesidades y problemas de mis compañeros de equipo. En paralelo, me encuentro llevando cursos de especialización en Análisis de Datos, con el objetivo de ampliar mis conocimientos y fortalecer mis competencias profesionales.                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| ![Gabriel Braithuaite](../assets/GabrielBraithuaite.jpg) | Gabriel Anthony Brabuaite Toledo  | U20201e889       | Ingeniería de software | Soy estudiante de Ingeniería de Software. Tengo conocimientos en desarrollo web y móvil, así como en bases de datos y metodologías ágiles. Me considero una persona proactiva, responsable y con habilidades para trabajar en equipo. Estoy comprometido con la calidad del software y siempre busco aprender y mejorar mis habilidades técnicas y blandas. Estoy emocionado por contribuir al éxito de nuestro proyecto y aportar soluciones innovadoras.              |
| ![AugustoMontes.png](../assets/AugustoMontes.png)  |   Augusto Sebastian Montes Maza   | u202218645       | Ingenieria de software | Soy estudiante de Ingeniería de Software en sexto ciclo. Tengo una sólida formación en programación, análisis y diseño de sistemas, así como experiencia académica en el desarrollo de aplicaciones web y móviles, bases de datos y metodologías ágiles. Me destaco por mi capacidad de trabajo en equipo, pensamiento crítico y compromiso con la calidad del software, y busco aplicar mis habilidades para aportar soluciones innovadoras en proyectos tecnológicos. |

### 1.2. Solution Profile
**Product Name:** DenunciaYa

**Product Description:** DenunciaYa es una plataforma web y móvil que permite a los ciudadanos reportar problemas urbanos y actos de corrupción de forma rápida, segura y anónima. A través de fotos, videos y audios, los usuarios pueden denunciar incidencias como baches, fallas en el alumbrado público, acumulación de basura, fugas de agua y más. La aplicación envía los reportes a un sistema centralizado para que las autoridades municipales gestionen las incidencias en tiempo real. Además, ofrece notificaciones de seguimiento, paneles de control para gobiernos y herramientas de análisis que ayudan a mejorar la eficiencia y la transparencia en la gestión pública.

**Monetización:** El modelo de negocio está basado en suscripciones para gobiernos locales y entidades públicas, con distintos niveles de servicio:

* Plan Básico: recepción de denuncias y panel básico de gestión de tickets.
* Plan Premium: incluye analítica avanzada, dashboards, API para integraciones y soporte técnico prioritario.

### 1.2.1 Antecedentes y problemática

**Técnica de The 5 'W's y 2 'H's**

**What (Qué)?** <br>
¿Cuál es el problema?

En muchas ciudades de Latinoamérica, los ciudadanos enfrentan problemas cotidianos como baches, acumulación de basura, fugas de agua, fallas en el alumbrado público y actos de corrupción. Sin embargo, la mayoría de estos problemas no se denuncian debido a tres barreras principales:
- **Desconfianza**: Creen que reportar no servirá de nada.
- **Miedo**: Temen represalias si revelan su identidad.
- **Fricción**: Los procesos tradicionales (ir a oficinas, llenar formularios, esperar semanas) son lentos y poco accesibles.

Esto genera impunidad, baja calidad de vida y descontento ciudadano, mientras que las autoridades carecen de datos confiables y en tiempo real para gestionar los problemas urbanos de manera eficiente.


**When (Cuándo)?** <br>
¿Cuándo sucede el problema?

El problema ocurre a diario y de forma constante, ya que los desperfectos en la infraestructura urbana, la corrupción y las fallas en servicios públicos afectan a los ciudadanos en tiempo real. La falta de un canal accesible para reportar y dar seguimiento provoca que estas incidencias se acumulen, incrementando costos para los gobiernos y empeorando la percepción ciudadana de sus autoridades.


**Where (Dónde)?** <br>
¿Dónde surge el problema?

El problema surge principalmente en entornos urbanos de Latinoamérica, donde las ciudades crecen rápidamente pero los gobiernos locales no cuentan con plataformas modernas de gestión ciudadana. También se intensifica en comunidades donde existe desigualdad en el acceso a servicios digitales o falta de transparencia en la administración pública.


**Who (Quién)?** <br>
¿Quiénes son los afectados?

- **Ciudadanos**: Que viven con problemas no resueltos en su entorno inmediato.
- **Autoridades municipales y gubernamentales**: Que carecen de herramientas de gestión modernas y datos centralizados.
- **Comunidades enteras**: Que sufren deterioro en la calidad de vida y pérdida de confianza en las instituciones públicas.


**Why (Por qué)?** <br>
¿Cuál es la causa del problema?

- **Procesos de denuncia obsoletos**: Dependientes de oficinas físicas y trámites burocráticos.
- **Falta de transparencia**: Los ciudadanos rara vez reciben seguimiento sobre sus reportes.
- **Temor a represalias**: Muchos ciudadanos prefieren callar antes que exponerse.
- **Ausencia de datos estructurados**: Las autoridades no cuentan con métricas en tiempo real que les permitan priorizar y resolver de manera eficiente.
- **Escasa digitalización**: Muchos gobiernos locales aún no incorporan tecnologías de participación ciudadana.


**How (Cómo)?** <br>
¿Cómo se utilizará el producto?

DenunciaYa se utilizará como una plataforma integral accesible desde dispositivos móviles y web:

- **Para ciudadanos**:
    - Suben fotos, videos o audios de los problemas.
    - Pueden elegir entre anonimato total o parcial.
    - Obtienen un código de seguimiento y reciben notificaciones en tiempo real sobre el estado de su denuncia.

- **Para autoridades**:
    - Acceden a un panel de control centralizado para gestionar denuncias según ubicación, categoría, urgencia y estado.
    - Usan un sistema de ticketing para derivar reportes a las áreas correspondientes.
    - Visualizan dashboards y reportes automáticos para medir eficiencia y detectar patrones.
    - Se comunican de manera segura con los denunciantes sin exponer su identidad.


**How Much (Cuánto)?** <br>
¿Cuánto costará implementar la solución?

El modelo de negocio está basado en suscripciones para gobiernos locales y dependencias públicas, adaptadas a distintos niveles de gestión:

- **Plan Básico**: Recepción de denuncias y panel básico de asignación de tickets.
- **Plan Premium**: Incluye analytics, la API para integrarse con sus sistemas y soporte técnico prioritario.

La app será gratuita para los ciudadanos, con el objetivo de fomentar la participación masiva y la transparencia. La inversión inicial contempla el desarrollo de software, infraestructura en la nube, ciberseguridad y campañas de adopción ciudadana en municipios piloto.

### 1.2.2 Lean UX Process.

En esta sección, se presenta el proceso de Lean UX que se ha seguido para el desarrollo de la plataforma DenunciaYa. Este proceso incluye la creación de un Lean UX Problem Statement, Assumptions, Hypothesis Statements y un Lean UX Canvas.
El objetivo es definir claramente el problema que se busca resolver, las suposiciones que se tienen sobre los usuarios y el producto, así como las hipótesis que guiarán el desarrollo del mismo.

### 1.2.2.1. Lean UX Problem Statements.

Actualmente los ciudadanos enfrentan serias dificultades para denunciar problemas en sus comunidades, como baches, fallas en el alumbrado público, acumulación de basura, fugas de agua o incluso actos de corrupción. Los procesos tradicionales para reportar estas incidencias son lentos, burocráticos y poco accesibles, lo que genera desconfianza, miedo a represalias y una gran fricción para el ciudadano común. Como resultado, muchos problemas no se reportan ni se resuelven, lo que deteriora la calidad de vida, aumenta los costos de gestión y reduce la confianza en las instituciones públicas.

El desafío radica en que las soluciones actuales no ofrecen un canal unificado, seguro y accesible que permita a los ciudadanos denunciar de manera anónima, mientras que las autoridades carecen de datos en tiempo real para gestionar y priorizar los problemas urbanos de manera eficiente.

¿Cómo podemos construir una plataforma digital que permita a los ciudadanos reportar incidencias de forma rápida, anónima y confiable, y al mismo tiempo provea a las autoridades una herramienta moderna de gestión y análisis en tiempo real que aumente la transparencia y mejore la calidad de vida en las comunidades?

### 1.2.2.2. Lean UX Assumptions.

<ins>**Users Assumptions:**</ins>

1. **Creo que mis clientes necesitan** una herramienta fácil de usar para reportar problemas urbanos y actos de corrupción de forma rápida, segura y anónima, eliminando la fricción y la desconfianza de los procesos tradicionales.

2. **Estas necesidades se pueden resolver con** una aplicación web y móvil como DenunciaYa, que centraliza los reportes ciudadanos, permite el anonimato y brinda seguimiento en tiempo real a través de notificaciones.

3. **Mis clientes iniciales son** ciudadanos urbanos de Latinoamérica, especialmente jóvenes y adultos con acceso a smartphones, que enfrentan problemas en su entorno inmediato y desean denunciarlos de manera sencilla.

4. **El valor #1 que un cliente quiere de mi servicio es** la posibilidad de denunciar sin miedo ni burocracia, con la seguridad de que su reporte llegará a las autoridades y tendrá seguimiento.

5. **El cliente también puede obtener estos beneficios adicionales,** como recibir un código de seguimiento único, acceder a un historial de sus denuncias, contribuir a la transparencia en la gestión pública y mejorar la calidad de vida de su comunidad.

6. **Voy a adquirir la mayoría de mis clientes a través de estrategias de** campañas digitales en redes sociales, programas de concientización ciudadana y convenios con gobiernos locales como municipios piloto.

7. **Haré dinero a través de** un modelo de suscripción mensual o anual para gobiernos locales y entidades públicas, con diferentes niveles de servicio (básico y premium), mientras que la aplicación será gratuita para los ciudadanos.

8. **Mi competencia principal en el mercado serán** las plataformas municipales propias y otras aplicaciones de gestión ciudadana que suelen ser poco intuitivas, limitadas o con baja adopción.

9. **Los venceremos debido a** que ofrecemos una plataforma accesible, moderna y confiable, con énfasis en la facilidad de uso, la seguridad de datos y el anonimato del denunciante, lo que genera mayor confianza ciudadana.

10. **Mi mayor riesgo de producto es** que los ciudadanos no confíen en la plataforma, ya sea porque temen represalias, creen que su denuncia no será atendida o dudan de la transparencia de la gestión.

11. **Resolveremos esto a través de** un sistema de anonimato garantizado, un canal de seguimiento transparente con notificaciones en tiempo real, campañas educativas sobre la seguridad de la plataforma y convenios con autoridades que validen su uso.

12. **¿Qué otras suposiciones tenemos? ¿Eso, si se prueba que es falso, causará que nuestro negocio/proyecto no funcione?**

- Los ciudadanos están dispuestos a usar la aplicacion web para denunciar en lugar de métodos tradicionales.
- Las autoridades asignarán presupuesto y recursos para gestionar las denuncias en tiempo real.
- Los usuarios confiarán en que el anonimato está protegido y que no habrá represalias.
- Si alguna de estas suposiciones resulta falsa, el proyecto puede no generar adopción ni sostenibilidad.

**¿Quién es el usuario?**<br>

Vendrian a ser los ciudadanos urbanos que enfrentan problemas cotidianos en infraestructura y servicios públicos, así como los funcionarios municipales encargados de recibir, clasificar y atender las denuncias.

**¿Dónde encaja nuestro producto en su vida/trabajo?**<br>

Para los ciudadanos, el producto encaja en su vida diaria cuando necesitan reportar incidencias en tiempo real de forma sencilla. Para las autoridades, encaja en su trabajo cotidiano al centralizar reportes y permitir una gestión más ágil y transparente.

**¿Qué problemas tiene nuestro producto y cómo se pueden resolver?**<br>

El producto enfrenta problemas como la desconfianza en la gestión de denuncias, lo cual se puede resolver garantizando transparencia y brindando feedback en tiempo real. También sufre de baja adopción ciudadana, que puede superarse mediante un proceso de onboarding simple y campañas educativas. Además, existe resistencia institucional, que puede resolverse incentivando con dashboards de eficiencia y métricas claras de impacto social.

**¿¿Cuándo y cómo se usa el producto?**<br>

El ciudadano utiliza el producto en el momento en que observa un problema en la vía pública o un acto de corrupción, subiendo evidencia en forma de fotos, videos o audios desde su celular. El funcionario municipal lo utiliza de manera diaria para gestionar incidencias en un panel centralizado, asignarlas a las áreas responsables y darles seguimiento.

**¿Qué características son importantes?**<br>

Las características más importantes del producto son la posibilidad de realizar reportes rápidos con fotos, videos y audios, la opción de denuncia anónima o con identidad parcial, el uso de un código único con seguimiento en tiempo real, la existencia de un panel de control para autoridades con dashboards y analítica, la incorporación de un sistema de ticketing para priorizar incidencias y la seguridad y privacidad de los datos.

**¿Cómo debe verse nuestro producto y cómo debe comportarse?**<br>

Para los ciudadanos, el producto debe verse como una interfaz simple, limpia e intuitiva, con pasos mínimos para enviar una denuncia. Para las autoridades, debe presentarse como un panel profesional y moderno con visualizaciones claras de incidencias y métricas. El producto debe comportarse de manera estable, responsiva y rápida, ofreciendo notificaciones en tiempo real y un acceso fluido desde dispositivos móviles y web.

<ins>**Business Outcomes:**</ins>

1. Al desarrollar DenunciaYa, creemos que se generará una mayor confianza ciudadana en las autoridades gracias a un canal moderno, seguro y transparente.### 1.2.2.3. Lean UX Hypothesis Statements.
2. Generación de ingresos recurrentes mediante el modelo de suscripción a gobiernos locales.
3. Incremento de la eficiencia en la gestión municipal al centralizar reportes en tiempo real.
4. Posicionamiento como una plataforma líder en participación ciudadana y gobierno digital en Latinoamérica.

<ins>**User Outcomes:**</ins>

1. Los ciudadanos podrán denunciar sin miedo, de forma rápida y anónima.
2. Obtendrán visibilidad y seguimiento en tiempo real de sus reportes.
3. Las autoridades mejorarán su capacidad de respuesta y priorización de problemas urbanos.
4. La comunidad en general se beneficia de una mejor calidad de vida gracias a la resolución más rápida de incidencias.

<ins>**Features:**</ins>

- Envío de denuncias con foto, video y audio.
- Opción de denuncia anónima.
- Código de seguimiento y notificaciones en tiempo real.
- Panel de gestión centralizado para autoridades.
- Dashboards con métricas e indicadores de eficiencia.
- Historial de denuncias y estados.
- Sistema de ticketing para derivar incidencias.
- Gestión de suscripciones y planes para gobiernos.

### 1.2.2.4. Lean UX Canvas.

![leanCanvas.jpeg](../assets/leanCanvas.jpeg)

## 1.3. Segmentos objetivo.

1. Ciudadanos Urbanos Digitalmente Activos:
- Descripción: Este segmento incluye a personas cívicamente conscientes que residen en zonas urbanas, usan smartphones de forma habitual y desean un canal efectivo para reportar problemas que afectan a su comunidad.
Sexo: Masculino y femenino
- Edades: Adultos jóvenes (18-34 años), adultos de mediana edad (35-54 años) y adultos mayores (55+)
- Nivel socioeconómico: Clases B y C (Media-alta y media)
- Necesidades por satisfacer: La plataforma permite a estos usuarios superar la frustración y la desconfianza hacia las instituciones, ofreciendo un canal directo, rápido y seguro para ser escuchados. Satisface la necesidad de anonimato para evitar represalias, ahorra tiempo al eliminar procesos burocráticos y brinda certeza mediante notificaciones de seguimiento, empoderando al ciudadano para que participe activamente en la mejora de su entorno.
2. Entidades Gubernamentales y Autoridades Municipales:
- Descripción: El siguiente segmento incluye a las administraciones públicas y los funcionarios responsables de la gestión de servicios urbanos, obras públicas y participación ciudadana que buscan modernizar sus procesos y mejorar su capacidad de respuesta.
- Sexo: Masculino y Femenino
- Edades: Adultos jóvenes (18-34 años), Adultos de mediana edad (35 - 54) y adultos mayores (55+)
- Nivel socioeconómico: Clases B y C (Media-alta y media)
- Necesidades por satisfacer: Apoyar con el manejo de datos centralizados que se generan al momento en que los ciudadanos reportan incidencias. La plataforma ordena y prioriza los problemas, permitiendo tomar decisiones basadas en evidencia y optimizar el uso de recursos limitados. Además, promueve la transparencia y acelera los procesos de gestión, mejorando la percepción pública y la eficiencia interna de la administración.

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores.

En esta sección se presentará un análisis de los posibles competidores de DenunciaYa y de sus respectivas tácticas. Asimismo, se incluirá un análisis competitivo con una comparación de fortalezas y debilidades entre cada competidor

### 2.1.1. Análisis competitivo.

<table>
  <tr>
    <th colspan="22">Competitive Analysis Landscape</th>
  </tr>
  <tr>
    <td colspan="1">¿Por qué llevar a cabo el análisis?</td>
    <td colspan="17">Este análisis se lleva a cabo con la finalidad de conocer a los competidores actuales en el ámbito de denuncias ciudadanas en línea, y cómo la propuesta <b>DenunciaYa</b> se diferencia al enfocarse en usabilidad, transparencia y cobertura integral de problemas cotidianos.</td>
  </tr>
  <tr>
    <td colspan="2"></td>
    <td><img src="https://i.postimg.cc/httqmBWP/Denuncias-Contraloria.jpg" alt="Denuncias Contraloría"><br></td>
    <td><img src="https://i.postimg.cc/43GNq0jD/denuncias-ministerio-Publico.jpg" alt="Ministerio Público"><br></td>
    <td><img src="https://i.postimg.cc/5yr2r2Mg/Denuncias-Central.jpg" alt="Central Única 1818"/><br></td>
    <td><img src="https://i.postimg.cc/Hn1g88Hf/denunciaya-removebg-preview.png" alt="DenunciaYa"/><br></td>
</tr>
  <tr>
    <td rowspan="2">Perfil</td>
    <td>Overview</td>
    <td>La plataforma de la Contraloría General de la República ayuda a que los ciudadanos denuncien casos de corrupción en entidades públicas. Se centra exclusivamente en irregularidades administrativas y de gestión pública.</td>
    <td>El sistema del Ministerio Público ayuda a que los ciudadanos presenten denuncias relacionadas a delitos como robo, estafa, homicidio, violencia, entre otros. El proceso es formal y se conecta directamente con la Fiscalía.</td>
    <td>La Central Única de Denuncias 1818 recibe, canaliza y deriva denuncias de delitos graves como trata de personas, extorsión, violencia familiar, corrupción y crimen organizado. Disponible en línea y vía llamada gratuita 1818.</td>
    <td><b>DenunciaYa</b> es una aplicacion web  que permite a los ciudadanos reportar problemas urbanos (baches, basura, agua, alumbrado, inseguridad) y actos de corrupción de manera rápida, anónima y con evidencia multimedia. Incluye un panel de seguimiento en tiempo real y herramientas para gobiernos locales.</td>
</tr>
 <tr>
  <td>Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
  <td><b>Contraloría</b> ofrece una plataforma enfocada exclusivamente en la lucha contra la corrupción en el sector público. Brinda a los ciudadanos un canal oficial con respaldo institucional, lo que asegura fiscalización formal y procesos de control directo sobre entidades estatales.</td>
  <td><b>Ministerio Público</b> proporciona un sistema de denuncias en línea con acceso directo a la Fiscalía. Ofrece a los ciudadanos la formalidad y el peso legal necesarios para iniciar procesos penales, garantizando seriedad y validez jurídica en cada denuncia presentada.</td>
  <td><b>Central Única de Denuncias 1818</b> ayuda a los ciudadanos a presentar denuncias de delitos graves a través de múltiples canales (web, teléfono y móvil). Su disponibilidad 24/7, junto con la opción de confidencialidad o anonimato, ofrece confianza y accesibilidad a nivel nacional.</td>
  <td><b>DenunciaYa</b> ofrece una aplicación web innovadora y fácil de usar para reportar problemas urbanos y corrupción. Brinda anonimato configurable, posibilidad de adjuntar evidencias multimedia y seguimiento en tiempo real. Además, proporciona paneles de transparencia y estadísticas para ciudadanos y gobiernos locales, fortaleciendo la participación ciudadana y la confianza pública.</td>
</tr>

<tr>
    <td rowspan="2">Perfil de Marketing</td>
    <td>Mercado Objetivo</td>
    <td>Ciudadanos que identifican actos de corrupción en entidades del Estado.</td>
    <td>Víctimas y testigos de delitos comunes y graves que buscan iniciar un proceso legal.</td>
    <td>Población en riesgo o testigos de delitos graves (corrupción, extorsión, trata de personas, violencia familiar).</td>
    <td>Ciudadanos en general y municipalidades que necesitan resolver problemas urbanos de forma rápida, transparente y eficiente. Está orientado a problemas cotidianos que impactan en la calidad de vida.</td>
  </tr>
  <tr>
  <td>Estrategias de Marketing</td>
    <td>Campañas de concientización anticorrupción, presencia institucional en medios y redes sociales.</td>
    <td>Campañas educativas sobre acceso a la justicia, difusión en medios y redes institucionales.</td>
    <td>Campañas masivas en radio, TV y redes sociales para fomentar el uso del número 1818 y la web.</td>
    <td>Campañas digitales en redes sociales, alianzas con municipalidades, gamificación de la denuncia ciudadana, incentivos a la participación y transparencia mediante reportes públicos.</td>
    </tr>
<tr>
    <td rowspan="3">Perfil de Producto</td>
    <td>Productos y Servicios</td>
    <td>Plataforma de denuncias en línea para corrupción administrativa. Genera alertas internas de fiscalización.</td>
    <td>Denuncia formal en línea con constancia digital que inicia el proceso legal ante el Ministerio Público.</td>
    <td>Plataforma web y línea 1818 para recibir denuncias de delitos graves. Incluye derivación y orientación legal.</td>
    <td>Plataforma web con registro multimedia (foto, video, audio), seguimiento en tiempo real, panel de gestión para municipios y tablero ciudadano de transparencia.</td>
  </tr>
  <tr>
  <td>Precios y Costos</td>
    <td>Servicio gratuito financiado por el Estado.</td>
    <td>Servicio gratuito financiado por el Estado.</td>
    <td>Servicio gratuito financiado por el Estado.</td>
    <td>Modelo SaaS dirigido a municipalidades y gratuito para los ciudadanos. También se ofrecen planes premium con análisis de datos avanzados.</td>
    </tr>
<td>Canales de distribución (Web y/o Móvil)</td>
    <td>Plataforma web oficial.</td>
    <td>Plataforma web oficial.</td>
    <td>Plataforma web, línea 1818 y aplicación móvil en algunos casos.</td>
    <td>Plataforma web y aplicación móvil para Android y IOS. Difusión directa en redes sociales y municipalidades.</td>
<tr>
    <td rowspan="4">Análisis SWOT</td>
    <td>Fortalezas</td>
    <td>Respaldo institucional de la Contraloría y enfoque en corrupción.</td>
    <td>Poder legal y formalidad en la denuncia, conexión directa con fiscales.</td>
    <td>Cobertura amplia de delitos, atención continua, múltiples canales.</td>
    <td>Innovación tecnológica, interfaz amigable, transparencia, alcance a problemas cotidianos, seguimiento en tiempo real.</td>
  </tr>
  <tr>
  <td>Debilidades</td>
    <td>Limitado solo a corrupción pública.</td>
    <td>Burocracia en los procesos y tiempos de respuesta largos.</td>
    <td>Sobrecarga de denuncias y limitaciones en derivación.</td>
    <td>Requiere adopción municipal, campañas de confianza y posicionamiento en el mercado.</td>
    </tr>
  <tr>
<td>Oportunidades</td>
    <td>Ampliar alcance a corrupción privada y municipal.</td>
    <td>Mayor digitalización del sistema judicial y conexión con otras instituciones.</td>
    <td>Integración con más servicios y uso de inteligencia artificial para clasificar denuncias.</td>
    <td>Alianzas con gobiernos locales, integración con sistemas de smart cities, analítica avanzada y big data para mejorar gestión pública.</td>
</tr>
  <tr>
<td>Amenazas</td>
    <td>Desconfianza ciudadana hacia instituciones públicas.</td>
    <td>Competencia de plataformas privadas de denuncias.</td>
    <td>Desconfianza por falta de resultados rápidos.</td>
    <td>Competencia con instituciones ya consolidadas, resistencia de gobiernos locales a utilizar la aplicacion web.</td>
</tr>
</table>


### 2.1.2. Estrategias y tácticas frente a competidores.

Elaborar estrategias y tácticas sólidas para competir de manera efectiva exige un enfoque estructurado y bien planificado. A continuación, se detallan algunas posibles estrategias y tácticas diseñadas para fortalecer la posición competitiva de DenunciaYa frente a alternativas del mercado, tomando en cuenta sus fortalezas, debilidades, oportunidades y amenazas:

* Usabilidad y accesibilidad: Frente a la complejidad burocrática de los competidores, DenunciaYa implementará una interfaz simple, intuitiva y disponible en web y móvil, reduciendo barreras técnicas y mejorando la experiencia ciudadana.

* Anonimato y seguridad: Dado que la desconfianza de los ciudadanos hacia las instituciones públicas representa una amenaza, DenunciaYa ofrecerá denuncias anónimas, confidencialidad garantizada y cifrado de evidencias multimedia, fortaleciendo la confianza del usuario.

* Cobertura integral y seguimiento en tiempo real: Cobertura integral y seguimiento en tiempo real: A diferencia de plataformas que solo se enfocan en delitos graves o corrupción, DenunciaYa permitirá reportar también problemas urbanos cotidianos. Esto aprovechará la oportunidad de vincularse con gobiernos locales

## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.
#### Preguntas para el segmento objetivo "Ciudadanos"
- ¿Alguna vez has presenciado problemas en tu zona (como baches, basura, corrupción, accidentes de tránsito, entre otros)?
- ¿Encontraste alguna plataforma para presentar una queja o denuncia?
- ¿Tuviste alguna dificultad al hacer la denuncia? ¿Cómo lo hiciste?
- ¿Crees que existen causas que te desmotivan a presentar una denuncia ?
- ¿Cuánta confianza tienes en nuestras autoridades que atienden y resuelven las denuncias de los ciudadanos?
- ¿Qué tipo de anonimato te daría más confianza para denunciar (público, identificado solo para autoridades, completamente anónimo)?
- ¿Como te gustaría dar seguimiento a tu denuncia?(Aplicación Web,mensaje,correo o mediante llamada)
- ¿Si te llegaran notificaciones de denuncias hechas por otras personas que viven cerca del lugar donde vives?
- ¿Tuviste alguna experiencia de hacer una denuncia y nunca recibir la ayuda necesaria?
- Imagina una application web que te permita denunciar fácil y dar seguimiento en tiempo real. ¿Qué características te parecerían más útiles?
- ¿Qué sucesos te harían dejar de usar una aplicación web de denuncias (por ejemplo: procesos lentos, exceso de datos personales, poca respuesta de autoridades)?
#### Preguntas para el segmento objetivo  "Autoridades Municipales y Gubernamentales"

- ¿Por qué medio reciben las denuncias de ciudadanos actualmente?
- ¿Se te hace fácil o difícil dar seguimiento constante a las denuncias?
- ¿A qué problemas te enfrentas al gestionar las denuncias?
- ¿Cómo asignan las denuncias a cada departamento o funcionario responsable?
- ¿Tienen algún sistema o software que utilicen para gestionar denuncias?
- ¿Qué tan importante es para ustedes poder comunicarse con el denunciante para pedir más información, manteniendo su anonimato si lo solicita?
- Si tuvieran un dashboard centralizado, ¿qué información debería mostrar para que realmente les ayude en su trabajo diario?
- ¿Qué riesgos ven en crear una aplicación web de denuncias ciudadanas?
- ¿Qué funcionalidades serían más valiosas en una aplicación web de gestión de denuncias?
- Si existieran planes de suscripción (básico y premium), ¿qué características diferenciales harían que valga la pena pagar por un plan más avanzado?
### 2.2.2. Registro de entrevistas.

## Segmento: Ciudadanos

### Entrevista 1 – Luis Fernández

**Datos del entrevistado**  
- Nombre y Apellido: Luis Fernández  
- Edad: 28 años  
- Ocupación: Analista contable  
- Distrito: Lima  

**Evidencia en video**  
- Screenshot del video: 
- ![Luis Fernandez.png](../assets/Ciudadano.png)
 
- [Video de las entrevistas](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214214_upc_edu_pe/EQNiTxyruylChmng1hwYL_YBJDfK927PPDDTKSNgDrmHFg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=7dP7rr)
- Timing de la entrevista: Inicio [00:05] – Duración [05:54]  

**Resumen descriptivo de la entrevista**  
Luis Fernández, joven analista contable, mostró una personalidad práctica y crítica frente a los problemas de su entorno. Vive en Lima, donde observa con frecuencia basura acumulada y accidentes de tránsito. Usa principalmente su celular y laptop, con Android y Windows como sistemas operativos, navegando desde Google Chrome. Se comunica mayormente por WhatsApp, herramienta que considera esencial tanto en el trabajo como en la vida cotidiana.  

En cuanto a denuncias, comentó que la web de la municipalidad no funciona correctamente y que por teléfono nunca le respondieron. Expresó frustración porque siente que sus reportes no son atendidos, lo que le genera poca confianza en las autoridades. Aun así, estaría dispuesto a usar una aplicación móvil de denuncias si le permite hacer seguimiento mediante notificaciones. Valoraría especialmente rapidez, facilidad para adjuntar fotos y simplicidad en el proceso. Subjetivamente, se mostró impaciente ante procesos burocráticos y señaló que abandonaría una plataforma si es lenta o pide demasiados datos personales.  

---

### Entrevista 2 –  Stephano Moscoso  

**Datos del entrevistado**  
- Nombre y Apellido: Stephano Moscoso  
- Edad: 25 años  
- Ocupación: Profesora  
- Distrito: Arequipa  

**Evidencia en video**  
- Screenshot del video: - ![Stephano Moscoso.png](../assets/Ciudadano3.png)
 
- [Video de las entrevistas](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214214_upc_edu_pe/EQNiTxyruylChmng1hwYL_YBJDfK927PPDDTKSNgDrmHFg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=7dP7rr) 
- Timing de la entrevista: Inicio [10:07] – Duración [16:5]7  

**Resumen descriptivo de la entrevista**  
Stephano Moscoso  , profesora en un colegio público, vive en un barrio céntrico de Arequipa. Tiene una personalidad reflexiva y perseverante, aunque desanimada por la falta de respuesta de las autoridades. Utiliza principalmente su celular y laptop con Android y Windows, y accede a internet desde Chrome. Se comunica casi siempre por WhatsApp, pero también consulta Facebook para enterarse de problemas en su zona.  

Ha presenciado desorden vehicular y acumulación de basura. Intentó denunciar a través del WhatsApp municipal enviando fotos, pero nunca recibió respuesta. Esto ha reducido su motivación para denunciar y le genera muy poca confianza en las autoridades. Indicó que se sentiría más segura con un sistema en el que su identidad esté visible solo para las autoridades. Le interesaría dar seguimiento mediante una aplicación web en tiempo real y recibir notificaciones de denuncias cercanas. Considera útiles funciones como fotos, mapas y plazos visibles. Subjetivamente, enfatizó que dejaría de usar una app si la municipalidad no responde o si el sistema es lento.  

---

### Entrevista 3 – George Garcia Durand

**Datos del entrevistado**  
- Nombre y Apellido: George Garcia Durand  
- Edad: 24 años  
- Ocupación: Estudiante universitario y trabajador part-time en call center  
- Distrito: Trujillo  

**Evidencia en video**  
- Screenshot del video: 
- - ![George Garcia Durand.png](../assets/Ciudadano2.png)
- [Video de las entrevistas](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214214_upc_edu_pe/EQNiTxyruylChmng1hwYL_YBJDfK927PPDDTKSNgDrmHFg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=7dP7rr) 
- Timing de la entrevista: Inicio [05:55] – Duración [10:06]  

**Resumen descriptivo de la entrevista**  
George García es un estudiante universitario que también trabaja part-time, con una personalidad práctica y un tanto incrédula respecto a la eficacia de las denuncias ciudadanas. Vive en Trujillo y usa principalmente su celular y laptop con Android y Windows, navegando desde Chrome. WhatsApp es su canal de comunicación central, y en ocasiones utiliza Instagram para enterarse de lo que ocurre en su barrio.  

Comentó que ha visto problemas como baches y basura en su zona, pero que la web de la municipalidad no funcionó al intentar denunciar. La página incluso se cayó durante su intento, lo que le generó frustración y una sensación de inutilidad en el proceso. Tiene muy baja confianza en las autoridades y preferiría mantener completo anonimato. Para dar seguimiento, desea recibir notificaciones únicamente en su celular. Le parecen indispensables las funciones de geolocalización y envío de fotos. Subjetivamente, considera que dejaría de usar una aplicación si pide demasiada información personal o si resulta lenta.  

---

## Segmento: Autoridades

### Entrevista 1 – Carolina Méndez

**Datos del entrevistado**  
- Nombre y Apellido: Carolina Méndez  
- Edad: 26 años  
- Ocupación: Asistente de participación ciudadana  
- Distrito: Lima  

**Evidencia en video**  
- Screenshot del video: 
- ![Carolina Méndez.png](../assets/Autoridad.png)
- URL del video en Microsoft Stream: [URL único del video]
- [Video de las entrevistas](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214214_upc_edu_pe/EQNiTxyruylChmng1hwYL_YBJDfK927PPDDTKSNgDrmHFg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=7dP7rr)
- Timing de la entrevista: Inicio [17:04] – Duración [19:48]  

**Resumen descriptivo de la entrevista**  
Carolina Méndez trabaja como asistente de participación ciudadana en Lima. Se muestra organizada y crítica, consciente de las limitaciones en la gestión de denuncias. Usa PC de oficina y celular con Windows y Android, navegando en Chrome. Se comunica principalmente por correo institucional y WhatsApp para la coordinación diaria.  

Explicó que las denuncias llegan por teléfono y WhatsApp, pero el seguimiento es difícil por la falta de un sistema integrado. Señaló problemas como duplicidad de reportes y carencia de datos claros. Actualmente gestionan denuncias en Excel, de manera manual. Considera muy importante mantener contacto con el denunciante, respetando el anonimato. Sugiere que un dashboard debería mostrar el número de denuncias, estado y responsables. Como riesgos de una app, mencionó las denuncias falsas, aunque valoraría funcionalidades como centralización de información y reportes automáticos. Un plan premium, en su opinión, debería integrar otras plataformas y generar alertas.  

---

### Entrevista 2 – Jorge Torres

**Datos del entrevistado**  
- Nombre y Apellido: Jorge Torres  
- Edad: 27 años  
- Ocupación: Inspector municipal  
- Distrito: Chiclayo  

**Evidencia en video**  
- ![Jorge Torresz.png](../assets/Autoridad2.png)
- [Video de las entrevistas](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214214_upc_edu_pe/EQNiTxyruylChmng1hwYL_YBJDfK927PPDDTKSNgDrmHFg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=7dP7rr) 
- Timing de la entrevista: Inicio [19:49] – Duración [25:28]  

**Resumen descriptivo de la entrevista**  
Jorge Torres, inspector municipal en Chiclayo, tiene un perfil operativo y resolutivo, acostumbrado a trabajar en campo. Usa celular y PC con Android y Windows, navegando desde Chrome. Se comunica principalmente por WhatsApp y llamadas, ya que su trabajo es dinámico.  

Actualmente reciben denuncias por WhatsApp o llamadas, pero el seguimiento es complicado por la ausencia de un registro centralizado. Mencionó la falta de coordinación y la información incompleta como problemas recurrentes. No usan software especializado, solo papel y Excel. Considera clave comunicarse con el denunciante para obtener datos precisos. Un dashboard, según él, debería mostrar ubicación, fecha y estado de la denuncia. Ve como riesgo las denuncias falsas, pero valoraría funcionalidades como fotos, ubicación y actualización de estado directamente desde el campo. Un plan premium debería ofrecer geolocalización precisa y mejorar la coordinación entre inspector y oficina.  

---

### Entrevista 3 – Juan José

**Datos del entrevistado**  
- Nombre y Apellido: Juan José  
- Edad: 24 años  
- Ocupación: Asistente de Participación Ciudadana y Gestión de Denuncias  
- Distrito: Lima  

**Evidencia en video**  
- ![JuanJose.png](../assets/JuanJose.png)
- [Video de las entrevistas](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214214_upc_edu_pe/EQNiTxyruylChmng1hwYL_YBJDfK927PPDDTKSNgDrmHFg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=7dP7rr)
- Timing de la entrevista: Inicio [25:29] – Duración [28:51]  

**Resumen descriptivo de la entrevista**  
Juan José, asistente de participación ciudadana y gestión de denuncias en Lima, señaló que actualmente las denuncias se reciben por teléfono, libros de reclamaciones, correo y redes sociales, pero la ausencia de un sistema unificado genera duplicidad y demoras. La asignación se hace de manera manual y algunos departamentos usan herramientas propias sin conexión entre sí.  

Destacó la importancia de la comunicación con los denunciantes y la necesidad de un dashboard que muestre en tiempo real el estado, ubicación y responsable de cada denuncia. Reconoció riesgos como reportes falsos y problemas de seguridad de datos, aunque valoró funciones como notificaciones, geolocalización, categorización y adjuntar evidencias.  

Finalmente, consideró que un plan premium sería útil si incluyera reportes avanzados, integración con otros sistemas municipales y soporte técnico especializado.


### 2.2.3. Análisis de entrevistas.
#### Segmento: Ciudadanos

**Características objetivas más comunes**  
- 100% usan **smartphone y laptop** con Android y Windows.  
- 100% navegan principalmente en **Google Chrome**.  
- 100% utilizan **WhatsApp** como canal de comunicación central.  
- 67% también usan **otras redes sociales** (Facebook o Instagram).  

**Características subjetivas más comunes**  
- 100% expresan **desconfianza hacia las autoridades** por falta de respuesta.  
- 100% valoran **rapidez, simplicidad y notificaciones en tiempo real**.  
- 67% prefieren **mantener anonimato** en el proceso de denuncia.  
- 100% muestran **frustración** cuando el sistema no responde o es lento.  

**Síntesis para arquetipo**  
El ciudadano entrevistado es un joven adulto (20–30 años), urbano, con alta dependencia del celular y uso cotidiano de WhatsApp. Tiene poca confianza en autoridades, pero estaría dispuesto a denunciar si la aplicación es rápida, sencilla, con seguimiento en tiempo real y con posibilidad de anonimato.  

---

#### Segmento: Autoridades  

**Características objetivas más comunes**  
- 100% usan **PC y smartphone** con Windows y Android.  
- 100% navegan principalmente en **Google Chrome**.  
- 100% se comunican por **WhatsApp** y llamadas; algunos también por **correo institucional**.  
- 100% gestionan denuncias de forma **manual** (Excel, papel o memorandos).  

**Características subjetivas más comunes**  
- 100% reconocen la **falta de un sistema unificado** para la gestión de denuncias.  
- 100% resaltan la **importancia de mantener comunicación con el denunciante**, cuidando su anonimato.  
- 100% consideran riesgos las **denuncias falsas** y la **seguridad de datos**.  
- 100% valoran la posibilidad de un **dashboard centralizado** con estado, ubicación y responsables.  
- 67% expresan la necesidad de mejorar la **coordinación interna** entre áreas y con inspectores de campo.  

**Síntesis para arquetipo**  
La autoridad entrevistada es un joven profesional (24–27 años), con un perfil operativo y administrativo, dependiente del uso de PC y smartphone, y con WhatsApp como herramienta principal de coordinación. Reconoce las limitaciones de los métodos manuales y demanda una plataforma centralizada que permita trazabilidad, asignación clara de responsables, geolocalización y adjuntos. Desconfía de la sobrecarga de denuncias falsas y la vulnerabilidad de los datos, pero ve valor en notificaciones, reportes y funciones que optimicen la gestión. Un plan premium sería atractivo si integra sistemas municipales, brinda reportes estadísticos avanzados y facilita la coordinación en tiempo real.



## 2.3. Needfinding.
### 2.3.1. User Personas.

## User Persona - Ciudadano

![José Quispe.png](../assets/Jos%C3%A9%20Quispe.png)

## User Persona - Autoridad

![Carolina Méndez.png](../assets/Carolina%20M%C3%A9ndez.png)

### 2.3.2. User Task Matrix.

## Task Matrix - Ciudadano

|                                      **Tarea**                                       | **Frecuencia** | **Importancia** |
|:------------------------------------------------------------------------------------:|----------------|-----------------|
| Identificar problemas en su distrito (baches, basura, alumbrado, fugas, corrupción). | Alta           | Alta            |
|         Intentar reportar problemas en la municipalidad (presencial o web).          | Media          | Alta            |
| Usar redes sociales (WhatsApp, Facebook) para compartir evidencias (fotos, videos).  | Alta           | Media           |
|                  Adjuntar fotos, videos o ubicación como evidencia.                  | Media          | Alta            |
|                     Dar seguimiento al estado de las denuncias.                      | Media          | Alta            |
|            Escuchar comentarios de vecinos sobre problemas no resueltos.             | Alta           | Media           |
|       Expresar frustración o desconfianza en la respuesta de las autoridades.        | Media          | Alta            |
|           Buscar soluciones digitales alternativas (apps, foros, grupos).            | Baja           | Media           |
|                Desistir de denunciar por percibir que “no pasa nada”.                | Media          | Alta            |

## Task Matrix - Autoridad

|                                  **Tarea**                                  | **Frecuencia** | **Importancia** |
|:---------------------------------------------------------------------------:|----------------|-----------------|
|    Recibir denuncias por múltiples canales (teléfono, WhatsApp, correo).    | Alta           | Alta            |
| Registrar manualmente casos en hojas de cálculo u otros sistemas dispersos. | Alta           | Alta            |
|  Clasificar y organizar denuncias según tipo, urgencia o área responsable.  | Alta           | Alta            |
|         Comunicar demoras o falta de información a los ciudadanos.          | Media          | Alta            |
|          Coordinar con otras áreas municipales para derivar casos.          | Media          | Alta            |
|        Escuchar quejas ciudadanas por la lentitud en las respuestas.        | Alta           | Alta            |
|              Buscar maneras de reducir sobrecarga de trabajo.               | Media          | Alta            |
|      Explicar procesos internos a superiores para justificar retrasos.      | Media          | Media           |
|   Imaginar o investigar soluciones digitales que automaticen su trabajo.    | Baja           | Alta            |

### 2.3.3. User Journey Mapping.

## Journey Map - Ciudadano

![José Quispe journey map.png](../assets/Jos%C3%A9%20Quispe%20journey%20map.png)

## Journey Map - Autoridad

![Carolina Méndez journey map.png](../assets/Carolina%20M%C3%A9ndez%20journey%20map.png)

### 2.3.4. Empathy Mapping.

## Empathy map - Ciudadano

![José Quispe Empathy map.png](../assets/Jos%C3%A9%20Quispe%20Empathy%20map.png)

## Empathy map - Autoridad

![Carolina Méndez Empathy map.png](../assets/Carolina%20M%C3%A9ndez%20Empathy%20map.png)

## 2.4. Big Picture Event Storming.

A continuación, se presenta el Big Picture Event Storming realizado para el sistema DenunciaYa. Esta representación visual permite identificar los eventos más relevantes del dominio, mostrando de manera colaborativa cómo los segmentos objetivos interactúan con la plataforma en distintos procesos, como la creación de denuncias, gestión de cuentas, publicación de contenido, recepción de notificaciones y personalización de la experiencia. Este primer nivel de exploración brinda una visión general del negocio, resaltando los procesos clave y posibles áreas de mejora u oportunidad.

![BigPictureEventStorming.jpg](../assets/BigPictureEventStorming.jpg)

**Link del figma:** https://acortar.link/eh5Gx6
## 2.5. Ubiquitous Language.

A continuación, se presenta el Ubiquitous Language desarrollado para el sistema DenunciaYa. Este glosario de términos clave define de manera clara y precisa los conceptos fundamentales del dominio, facilitando la comunicación efectiva entre todos los miembros del equipo y asegurando una comprensión compartida de los elementos esenciales del negocio. Al establecer un lenguaje común, se minimizan las ambigüedades y se promueve la colaboración fluida durante todo el ciclo de vida del proyecto.


## Actores / Roles
| Término       | Definición                                                                 |
|---------------|----------------------------------------------------------------------------|
| Visitante     | Usuario no registrado que accede a la landing page.                        |
| Ciudadano     | Usuario registrado que realiza denuncias, las gestiona y participa en la comunidad. |
| Autoridad / Administrador | Usuario con privilegios avanzados para gestionar denuncias, ver métricas y dashboards. |
| Developer     | Miembro del equipo técnico responsable del diseño y funcionamiento.        |

---

## Conceptos Clave (Landing Page)
| Término            | Definición                                                                 |
|--------------------|----------------------------------------------------------------------------|
| Landing Page       | Página principal que presenta la plataforma a los visitantes.              |
| How it works       | Sección que explica de manera resumida el proceso de denuncia.             |
| About us           | Información sobre el objetivo y equipo desarrollador.                      |
| Testimonials       | Opiniones de ciudadanos que generan confianza.                             |
| News & Blog        | Espacio con novedades y artículos de la plataforma.                        |
| CTA (Call to Action)| Botón de acceso a la aplicación.                                           |
| Sección de Soporte | Espacio con FAQs, guías o contacto para resolver dudas.                    |
| Sección de Contacto| Información para comunicarse con el equipo (correo u otros medios).        |

---

## Denuncias
| Término             | Definición                                                                 |
|---------------------|----------------------------------------------------------------------------|
| Denuncia            | Reporte ciudadano de un problema urbano o de corrupción.                   |
| Categoría de denuncia | Clasificación del incidente (baches, basura, alumbrado, etc.).            |
| Ubicación           | Dirección exacta o zona del incidente.                                     |
| Descripción         | Texto explicativo del problema.                                            |
| Evidencia           | Archivos adjuntos (fotos, videos, audios).                                 |
| Borrador de denuncia| Denuncia guardada sin enviar para completarla más tarde.                   |
| Resumen de denuncia | Vista previa antes de enviar.                                              |
| Código de seguimiento| Identificador único generado al enviar.                                   |

---

## Gestión de Denuncias
| Término     | Definición                                                                 |
|-------------|----------------------------------------------------------------------------|
| Historial   | Lista de denuncias registradas por un usuario.                             |
| Detalle de denuncia | Información completa de un caso.                                    |
| Filtros     | Opciones para reducir los resultados (estado, categoría, fecha, ubicación).|
| Ordenar     | Reorganizar denuncias por fecha o estado.                                  |
| Búsqueda    | Localizar denuncias por número o palabra clave.                            |
| Timeline / Evolución del caso | Línea de tiempo con actualizaciones de estado.            |
| Empty state | Mensaje mostrado cuando no existen denuncias registradas.                  |

---

## Dashboard de Autoridades
| Término               | Definición                                                                 |
|-----------------------|----------------------------------------------------------------------------|
| Dashboard / Panel de control | Vista centralizada de métricas y denuncias.                          |
| Asignación de denuncia| Derivación de denuncias a un área responsable.                             |
| Métricas de eficiencia| Reportes de tiempos de resolución y desempeño de áreas.                    |
| Patrones de incidencias| Tendencias en categorías o zonas críticas.                                |
| Alertas internas      | Notificaciones para casos urgentes.                                        |
| Comunicación segura   | Mensajería entre autoridad y ciudadano manteniendo anonimato si aplica.    |

---

## Directorio
| Término             | Definición                                                                 |
|---------------------|----------------------------------------------------------------------------|
| Directorio de recursos | Listado de oficinas, contactos y recursos relevantes.                     |
| Filtros de directorio | Filtrar por región o distrito.                                             |
| Búsqueda de directorio | Localizar oficinas/contactos por nombre o palabra clave.                  |
| Detalle de contacto | Información detallada (dirección, teléfono, correo, horario).               |
| Acceso extendido    | Vista adicional para autoridades (responsables, jerarquía interna).         |

---

## Historial de Intervenciones
| Término                 | Definición                                                                 |
|-------------------------|----------------------------------------------------------------------------|
| Historial de intervenciones | Registro cronológico de acciones asociadas a una denuncia.             |
| Intervención            | Acción específica tomada en el proceso (asignación, comentario, adjunto). |
| Responsable             | Autoridad o área que ejecutó la acción.                                   |
| Adjunto                 | Documentos o reportes cargados en el historial.                           |
| Notificación de actualización | Aviso automático al ciudadano sobre cambios.                         |

---

## Autenticación y Gestión de Cuentas
| Término          | Definición                                                                 |
|------------------|----------------------------------------------------------------------------|
| Registro         | Creación de una cuenta (ciudadano o autoridad).                            |
| Inicio de sesión | Acceso a la plataforma con credenciales.                                   |
| Recuperar contraseña | Función para recuperar acceso en caso de olvido.                       |
| Restablecer contraseña | Definir nueva contraseña para volver a acceder.                       |
| Perfil básico    | Información básica del usuario.                                            |

---

## Comunidad
| Término             | Definición                                                                 |
|---------------------|----------------------------------------------------------------------------|
| Publicación / Post  | Mensaje creado por un ciudadano (texto, imagen, video, GIF, encuesta, emoji, recordatorio). |
| Me gusta            | Reacción positiva a una publicación.                                       |
| Comentario          | Respuesta a una publicación.                                               |
| Compartir publicación | Difusión de publicaciones de otros en el propio feed.                    |
| Encuesta            | Publicación interactiva con opciones de voto.                             |
| Feed comunitario    | Línea de tiempo de publicaciones de la comunidad.                         |

# Capítulo III: Requirements Specification
## 3.1. User Stories.
## 3.2. Impact Mapping.
## 3.3. Product Backlog
# Capítulo IV: Product Design
## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.
### 4.1.2. Web Style Guidelines.
## 4.2. Information Architecture.
### 4.2.1. Organization Systems.
### 4.2.2. Labeling Systems.
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems.
### 4.2.5. Navigation Systems.
## 4.3. Landing Page UI Design.
### 4.3.1. Landing Page Wireframe.
### 4.3.2. Landing Page Mock-up.
## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.
### 4.4.2. Web Applications Wireflow Diagrams.
### 4.4.2. Web Applications Mock-ups.
### 4.4.3. Web Applications User Flow Diagrams.
## 4.5. Web Applications Prototyping.
## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Design-Level Event Storming.
### 4.6.2. Software Architecture Context Diagram.
### 4.6.3. Software Architecture Container Diagrams.
### 4.6.4. Software Architecture Components Diagrams.
## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.
## 4.8. Database Design.
### 4.8.1. Database Diagrams.
# Capítulo V: Product Implementation, Validation & Deployment.
## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.
### 5.1.2. Source Code Management.
### 5.1.3. Source Code Style Guide & Conventions.
### 5.1.4. Software Deployment Configuration.
## 5.2. Landing Page, Services & Applications Implementation.
### 5.2.1. Sprint 1
### 5.2.1.1. Sprint Planning 1.
### 5.2.1.2. Aspect Leaders and Collaborators.
### 5.2.1.3. Sprint Backlog 1.
### 5.2.1.4. Development Evidence for Sprint Review.
### 5.2.1.5. Execution Evidence for Sprint Review.
### 5.2.1.6. Services Documentation Evidence for Sprint Review.
### 5.2.1.7. Software Deployment Evidence for Sprint Review.
### 5.2.1.8. Team Collaboration Insights during Sprint.
Conclusiones
Bibliografía
Anexos
