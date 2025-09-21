<div align="center">

# Universidad Peruana De Ciencias Aplicadas
<img src = "https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img>
<br/> **Carrera:** Ingeniería de Software
<br/> **Ciclo:** 202520
<br/> **Curso:** 1ASI0729 - Desarrollo de Aplicaciones Open Source 
<br/> **NRC:** 7338
<br/> **Profesor:** Velasquez Nuñez, Angel Augusto
<br/> **Informe del Trabajo Final**
<br/> **Startup:** CodeLab
<br/> **Producto:** HostelManager

| Integrantes                     | Código     |
|---------------------------------|------------|
| Bautista Rivera, Jose Diego     | u202310949 |
| Carranza Perez, Jhordi Luis     | u20191e835 |
| Janampa Gutierrez, Jhoan Darner | u202323319 |
| Pillaca Velasquez, Andre        | u202022056 |
| Quiroz Caceres, Adrian Alonso   | u202214864 |

</div>

# Registro de Versiones del Informe
| Versión | Fecha      | Autor | Descripción de modificación|
|---------|------------|-------|----------------------------|
| V0.1    | 01/09/2025 | Todos | Creación del repositorio   |

# Project Report Collaboration Insights

# Contenido
- [**Capítulo I: Introducción**](#capítulo-i-introducción)
    - [**1.1. Startup Profile.**](#11-startup-profile)
        - [**1.1.1. Descripción de la Startup.**](#111-descripción-de-la-startup)
        - [**1.1.2. Perfiles de integrantes del equipo.**](#112-perfiles-de-integrantes-del-equipo)
    - [**1.2. Solution Profile.**](#12-solution-profile)
        - [**1.2.1. Antecedentes y problemática.**](#121-antecedentes-y-problemática)
        - [**1.2.2. Lean UX Process.**](#122-lean-ux-process)
            - [**1.2.2.1. Lean UX Problem Statements.**](#1221-lean-ux-problem-statements)
            - [**1.2.2.2. Lean UX Assumptions.**](#1222-lean-ux-assumptions)
            - [**1.2.2.3. Lean UX Hypothesis Statements.**](#1223-lean-ux-hypothesis-statements)
            - [**1.2.2.4. Lean UX Canvas.**](#1224-lean-ux-canvas)
    - [**1.3. Segmentos objetivo.**](#13-segmentos-objetivo)
- [**Capítulo II: Requirements Elicitation & Analysis**](#capítulo-ii-requirements-elicitation--analysis)
    - [**2.1. Competidores.**](#21-competidores)
        - [**2.1.1. Análisis competitivo.**](#211-análisis-competitivo)
        - [**2.1.2. Estrategias y tácticas frente a competidores.**](#212-estrategias-y-tácticas-frente-a-competidores)
    - [**2.2. Entrevistas.**](#22-entrevistas)
        - [**2.2.1. Diseño de entrevistas.**](#221-diseño-de-entrevistas)
        - [**2.2.2. Registro de entrevistas.**](#222-registro-de-entrevistas)
        - [**2.2.3. Análisis de entrevistas.**](#223-análisis-de-entrevistas)
    - [**2.3. Needfinding.**](#23-needfinding)
        - [**2.3.1. User Personas.**](#231-user-personas)
        - [**2.3.2. User Task Matrix.**](#232-user-task-matrix)
        - [**2.3.3. User Journey Mapping.**](#233-user-journey-mapping)
        - [**2.3.4. Empathy Mapping.**](#234-empathy-mapping)
    - [**2.4. Big Picture EventStorming.**](#24-big-picture-eventstorming)
    - [**2.5. Ubiquitous Language.**](#25-ubiquitous-language)
- [**Capítulo III: Requirements Specification**](#capítulo-iii-requirements-specification)
    - [**3.1. User Stories.**](#31-user-stories)
    - [**3.2. Impact Mapping.**](#32-impact-mapping)
    - [**3.3. Product Backlog.**](#33-product-backlog)
- [**Capítulo IV: Product Design**](#capítulo-iv-product-design)
    - [**4.1. Style Guidelines.**](#41-style-guidelines)
        - [**4.1.1. General Style Guidelines.**](#411-general-style-guidelines)
        - [**4.1.2. Web Style Guidelines.**](#412-web-style-guidelines)
    - [**4.2. Information Architecture.**](#42-information-architecture)
        - [**4.2.1. Organization Systems.**](#421-organization-systems)
        - [**4.2.2. Labeling Systems.**](#422-labeling-systems)
        - [**4.2.3. SEO Tags and Meta Tags**](#423-seo-tags-and-meta-tags)
        - [**4.2.4. Searching Systems.**](#424-searching-systems)
        - [**4.2.5. Navigation Systems.**](#425-navigation-systems)
    - [**4.3. Landing Page UI Design.**](#43-landing-page-ui-design)
        - [**4.3.1. Landing Page Wireframe.**](#431-landing-page-wireframe)
        - [**4.3.2. Landing Page Mock-up.**](#432-landing-page-mock-up)
    - [**4.4. Web Applications UX/UI Design.**](#44-web-applications-uxui-design)
        - [**4.4.1. Web Applications Wireframes.**](#441-web-applications-wireframes)
        - [**4.4.2. Web Applications Wireflow Diagrams.**](#442-web-applications-wireflow-diagrams)
        - [**4.4.2. Web Applications Mock-ups.**](#442-web-applications-mock-ups)
        - [**4.4.3. Web Applications User Flow Diagrams.**](#443-web-applications-user-flow-diagrams)
    - [**4.5. Web Applications Prototyping.**](#45-web-applications-prototyping)
    - [**4.6. Domain-Driven Software Architecture.**](#46-domain-driven-software-architecture)
        - [**4.6.1. Design-Level EventStorming.**](#461-design-level-eventstorming)
        - [**4.6.2. Software Architecture Context Diagram.**](#462-software-architecture-context-diagram)
        - [**4.6.3. Software Architecture Container Diagrams.**](#463-software-architecture-container-diagrams)
        - [**4.6.4. Software Architecture Components Diagrams.**](#464-software-architecture-components-diagrams)
    - [**4.7. Software Object-Oriented Design.**](#47-software-object-oriented-design)
        - [**4.7.1. Class Diagrams.**](#471-class-diagrams)
    - [**4.8. Database Design.**](#48-database-design)
        - [**4.8.1. Database Diagrams.**](#481-database-diagrams)
- [**Capítulo V: Product Implementation, Validation & Deployment**](#capítulo-v-product-implementation-validation--deployment)
    - [**5.1. Software Configuration Management.**](#51-software-configuration-management)
        - [**5.1.1. Software Development Environment Configuration.**](#511-software-development-environment-configuration)
        - [**5.1.2. Source Code Management.**](#512-source-code-management)
        - [**5.1.3. Source Code Style Guide & Conventions.**](#513-source-code-style-guide--conventions)
        - [**5.1.4. Software Deployment Configuration.**](#514-software-deployment-configuration)
    - [**5.2. Landing Page, Services & Applications Implementation.**](#52-landing-page-services--applications-implementation)
        - [**5.2.1. Sprint 1**](#521-sprint-1)
            - [**5.2.1.1. Sprint Planning 1.**](#5211-sprint-planning-1)
            - [**5.2.1.2. Aspect Leaders and Collaborators.**](#5212-aspect-leaders-and-collaborators)
            - [**5.2.1.3. Sprint Backlog 1.**](#5213-sprint-backlog-1)
            - [**5.2.1.4. Development Evidence for Sprint Review.**](#5214-development-evidence-for-sprint-review)
            - [**5.2.1.5. Execution Evidence for Sprint Review.**](#5215-execution-evidence-for-sprint-review)
            - [**5.2.1.6. Services Documentation Evidence for Sprint Review.**](#5216-services-documentation-evidence-for-sprint-review)
            - [**5.2.1.7. Software Deployment Evidence for Sprint Review.**](#5217-software-deployment-evidence-for-sprint-review)
            - [**5.2.1.8. Team Collaboration Insights during Sprint.**](#5218-team-collaboration-insights-during-sprint)
- [**Conclusiones**](#conclusiones)
- [**Bibliografía**](#bibliografía)
- [**Anexos**](#anexos)

## Student Outcome
**El curso contribuye al cumplimiento del Student Outcome ABET:** ABET – EAC - Student Outcome 3
<br/> **Criterio:** Capacidad de comunicarse efectivamente con un rango de audiencias.

| Criterio específico                                                    | Acciones realizadas | Conclusiones |
|------------------------------------------------------------------------|---------------------|--------------|
| Comunica oralmente con efectividad a diferentes rangos de audiencia.   | **Jhordi Carranza:**<br>Realicé entrevistas a ambos segmentos de usuarios (huéspedes y administradores) para levantar requerimientos.<br>Presenté y expliqué el Capítulo V ante el equipo, especialmente en temas de configuración del entorno, control de versiones y despliegue.<br>Exposé los diseños en Figma de la web app, explicando el flujo de navegación y la justificación de decisiones de diseño. | Se demostró capacidad para **explicar de manera clara y adaptada a cada audiencia** (usuarios no técnicos en entrevistas y equipo técnico en revisiones internas), logrando validar requerimientos y obtener retroalimentación útil para el proyecto. |
| Comunica por escrito con efectividad a diferentes rangos de audiencia. | Jhordi Carranza<br>Redacté el Capítulo V: *Product Implementation, Validation & Deployment*, estructurado en secciones técnicas (gestión del código, guías de estilo, evidencia de despliegue, colaboración en sprints).<br>Elaboré la documentación de servicios y evidencias en cada sprint.<br>Produje entregables visuales y escritos en Figma y reportes, asegurando claridad en la transmisión de la información. | Se logró **documentar de manera precisa y ordenada** los procesos técnicos, facilitando la comprensión del proyecto tanto para un público especializado (desarrolladores, docentes) como para uno no técnico (usuarios, interesados en la landing page). |


# Capítulo I: Introducción

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
Codelab es una startup orientada al desarrollo de software, cuyo principal objetivo es diseñar soluciones tecnológicas que respondan de manera creativa y eficiente a los retos que enfrentan las empresas en el entorno digital. La iniciativa surge de estudiantes de la Universidad Peruana de Ciencias Aplicadas (UPC), quienes, motivados por su formación académica y su espíritu innovador, buscan aportar valor mediante el uso estratégico de la tecnología.

**Misión:** Nuestra misión es desarrollar herramientas digitales innovadoras que permitan a empresas y organizaciones optimizar sus procesos, resolver problemas actuales y potenciar su crecimiento en un entorno cada vez más competitivo.

**Visión:** Nuestra visión es consolidarnos como una empresa referente en el sector tecnológico, contribuyendo al progreso digital y convirtiéndonos en socios estratégicos de organizaciones que buscan generar impacto sostenible en la sociedad.

### 1.1.2. Perfiles de integrantes del equipo

<table style="width: 100%; border-collapse: collapse;">
    <tr>
        <td style="width: 30%; border: 1px solid #FFF; padding: 10px; vertical-align: top;">
            <img src="/images/jhoan.jpg" alt="Jhoan Darner Photo" style="display: block; margin: 50 auto 0 auto;"/>
        </td>
        <td style="width: 70%; border: 1px solid #FFF; padding: 10px; vertical-align: top;">
            <strong>Janampa Gutierrez Jhoan Darner (U292323319)</strong> - Ingeniería de Software<br><br>
            Actualmente estoy cursando el 5to ciclo de Ingeniería de Software, con 19 años. Me gusta jugar videojuegos, ir al gimnasio, entrenar básquet y practicar programación. Deseo en un futuro desempeñarme en desarrollo web y ciberseguridad. Mis habilidades incluyen perseverancia, escucha activa, trabajo en equipo y motivación. Me comprometo a acabar eficazmente los entregables que me asignen y apoyar en todo lo que haga falta en el proyecto.
        </td>
    </tr>
    <tr>
        <td style="width: 30%; border: 1px solid #FFF; padding: 10px; vertical-align: top;">
            <img src="/images/Jose_Diego.jpeg" alt="José Diego Photo" style="display: block; margin: 50 auto 0 auto;"/>
        </td>
        <td style="width: 70%; border: 1px solid #FFF; padding: 10px; vertical-align: top;">
            <strong>Bautista Rivera José Diego (U202310949)</strong> - Ingeniería de Software<br><br>
            Descripción pendiente. Habilidades: Pendientes. Compromiso: Pendiente.
        </td>
    </tr>
    <tr>
        <td style="width: 30%; border: 1px solid #FFF; padding: 10px; vertical-align: top;">
            <img src="/images/Jhordi_Luis.jpeg" alt="Jhordi Luis Photo" style="display: block; margin: 50 auto 0 auto;"/>
        </td>
        <td style="width: 70%; border: 1px solid #FFF; padding: 10px; vertical-align: top;">
            <strong>Jhordi Luis Carranza Pérez (U20191E835)</strong> - Ingeniería de Software<br><br>
            Tengo 23 años y actualmente curso el sexto ciclo de Ingeniería de Software. Tengo experiencia en desarrollo web, especialmente en frontend. Además, soy músico trompetista y practico deportes de resistencia y al aire libre. Me quiero enfocar más adelante en Telecomunicaciones o Neurociencia computacional. Mis habilidades incluyen empatía, compromiso y colaboración. Me comprometo a desarrollar un proyecto con buena salida en el mundo y que ayude a muchas personas.
        </td>
    </tr>
    <tr>
        <td style="width: 30%; border: 1px solid #FFF; padding: 10px; vertical-align: top;">
            <img src="/images/Aqc.jpeg" alt="Integrante 4 Photo" style="display: block; margin: 50 auto 0 auto;"/>
        </td>
        <td style="width: 70%; border: 1px solid #FFF; padding: 10px; vertical-align: top;">
            <strong>Quiroz Cáceres, Adrian Alonso (U202214864)</strong> - Ingeniería de Software<br><br>
            Soy estudiante del 5.º ciclo de Ingeniería de Software. Tengo conocimientos en C++ y bases de datos, áreas que me permiten contribuir al desarrollo de soluciones digitales. En mi tiempo libre disfruto de escuchar música y jugar videojuegos, actividades que me ayudan a mantener el equilibrio entre lo académico y lo personal. Me comprometo a colaborar activamente con mi equipo, cumplir los plazos establecidos y asegurar la calidad de los entregables, con el objetivo de alcanzar los objetivos del proyecto de manera eficiente.
        </td>
    </tr>
    <tr>
        <td style="width: 30%; border: 1px solid #FFF; padding: 10px; vertical-align: top;">
            <img src="/images/Integrante5.jpeg" alt="Integrante 5 Photo" style="display: block; margin: 50 auto 0 auto;"/>
        </td>
        <td style="width: 70%; border: 1px solid #FFF; padding: 10px; vertical-align: top;">
            <strong>Integrante 5</strong> - Ingeniería de Software<br><br>
            Información pendiente.
        </td>
    </tr>
</table>

## 1.2. Solution Profile

En Hostel Manager nos dedicamos a diseñar soluciones tecnológicas modernas y accesibles que simplifican y optimizan la gestión hotelera en hostales y pequeños hoteles. Entendemos los desafíos que enfrentan los administradores independientes: la complejidad operativa, la dispersión de herramientas digitales y la dificultad para ofrecer un servicio ágil y personalizado. Por ello, desarrollamos una plataforma web integral que centraliza la administración de reservas, huéspedes y servicios complementarios, facilitando tanto el control diario como la toma de decisiones estratégicas.

Nuestra solución integra funcionalidades clave como:

- Gestión en tiempo real de reservas y disponibilidad, evitando sobreventas y errores en la asignación de habitaciones o servicios.

- Control centralizado de pagos y emisión automática de comprobantes, con integración a pasarelas de pago seguras como PayPal y registro de pagos presenciales.

- Módulo de opiniones y calificaciones, que promueve la retroalimentación directa y mejora continua de la experiencia del huésped.

- Reportes dinámicos y personalizados, con información sobre ocupación, ingresos y uso de servicios adicionales.

- Configuración flexible de promociones y tarifas, para atraer nuevos clientes y mejorar la rentabilidad del alojamiento.

La plataforma está desarrollada con tecnologías web modernas, garantizando una experiencia intuitiva, segura y responsiva, accesible desde cualquier dispositivo con conexión a internet.

Con Hostel Manager, aspiramos a transformar la gestión hotelera independiente en América Latina, permitiendo que los administradores dediquen más tiempo a ofrecer experiencias memorables, mientras nuestra plataforma se encarga de la eficiencia operativa y el control inteligente del negocio.

### 1.2.1. Antecedentes y problemática

En el sector turístico, hostales y hoteles enfrentan limitaciones tecnológicas significativas. muchos aún gestionan sus reservas, huéspedes y servicios adicionales de manera manual o con herramientas poco integradas, lo que genera errores, duplicidad de información y una pérdida constante de oportunidades de ingreso. Estudios recientes señalan que la transformación digital en la hospitalidad aumenta la eficiencia operativa y puede reducir los tiempos de check-in/check-out hasta en un 30%, además de mejorar la precisión en procesos críticos (ResearchGate, 2024).

Al mismo tiempo, los huéspedes actuales esperan experiencias digitales rápidas y personalizadas, como check-in móvil, pagos en línea y la posibilidad de solicitar servicios desde su propio dispositivos, lo cual ya se ha convertido en un estándar de la industria (Linkedin, 2024). Sin embargo, la adopción de estas tecnologías por parte de hoteles sigue siendo limitada debido a costos altos y a la falta de capacidades internas para implementarlas.

En este contexto, Hostel Manager surge para cerrar esa brecha: ofrece una solución integral, accesibilidad y escalable que digitaliza la gestión hotelera y mejora la eficiencia operativa.

The 5 “W's

1. What (Qué):

¿Cual es el problema?

En el sector turístico, los hostales y hoteles enfrentan problemas al gestionar reservas, huéspedes y servicios adicionales, la mayoría utiliza procesos manuales o herramientas poco integradas, lo que genera errores, pérdida de ingreso y una experiencia deficiente para los huéspedes. Además, los viajeros esperan soluciones digitales como reservas en línea, pagos seguros y solicitudes rápidas de servicio, lo cual muchas veces no está disponible en este segmento.

¿Cuál es la relación con la persona en cuestión?

Administrador: utiliza la plataforma para gestionar precios, disponibilidad, clientes y reportes.

2. When (Cuándo):

¿Cuándo sucede el problema?

La problemática ocurre en los procesos diarios de gestión hotelera: cuando se realizan reservas, check-ins, cancelaciones o solicitudes de room service. En esos momentos la falta de un sistema centralizado provoca retrasos y errores.

¿Cuándo utiliza el cliente el producto?

Los administradores lo utilizan todo el tiempo: en la operación diaria, generación de reportes y gestión de negocio.

3. Where (dónde):

¿Dónde está el cliente cuando usa el producto?

El administrador lo usa en el hostal/hotel o de manera remota gracias a la plataforma web.

¿A dónde se dirige?

El administrador busca disfrutar de una experiencia ágil y personalizada.

¿Dónde surge el problema?

En la falta de digitalización de hoteles, que genera ineficiencia y desventaja frente a grandes cadenas que ya poseen sistemas integrados de gestión.

4. Who (quién):

¿Quiénes están involucrados?

- Administradores/propietarios: gestionan operaciones, precios, reportes y personal.

- Huéspedes: reservan habitaciones y solicitan servicios.

- Desarrolladores: crean y mantienen la plataforma.

¿A quiénes le sucede el problema?

A los administradores, que pierden tiempo e ingresos por falta de herramientas modernas.

¿Quién lo utilizará?
Administradores (panel de gestion).

5. Why (por qué):

Hostel Manager busca digitalizar y profesionalizar la gestión de hostales y hoteles, ofreciendo una herramienta escalable y accesible que permita competir con grandes cadenas.

¿Cuál es la causa del problema?

La raíz está en la falta de plataformas centralizadas, accesibles y adaptadas a este tipo de negocios. Los sistemas existentes son costosos o demasiado complejos, lo que obliga a los hostales y hoteles a depender de procesos manuales que afectan su productividad y satisfacción del cliente.

The 2 “H”s

1. How(cómo):

¿En qué condiciones los clientes usan nuestro producto?

Los administradores lo usan en tiempo real como herramienta centralizada para controlar reservas, coordinar servicios adicionales y generar reportes de gestión.

¿Cómo nos conocieron los compradores?

Mediante estrategias de marketing digital, especialmente mediante campañas en redes sociales y anuncios en buscadores como Google Ads.

¿Qué llevó a la persona a llegar a esta situación?

- Frustración con métodos manuales.
- Necesidad de optimizar ingresos y procesos.
- Expectativas creciente de los huéspedes respecto a servicios digitales.

2. How much(cuánto): 

La plataforma funcionará bajo un modelo de suscripción mensual accesible para hostales y hoteles, con planes escalables según el número de habitaciones o usuarios administradores registrados. Este esquema permite a los negocios pagar únicamente por lo que utilizan, manteniendo los costos bajo control.

### 1.2.2. Lean UX Process

Con el objetivo de optimizar nuestro enfoque en el diseño centrado en el usuario, hemos adoptado las buenas prácticas descritas por Gothelf y Seiden (2021) para estructurar nuestro propio Lean UX Process dentro del proyecto. Según los autores, el Lean UX representa una evolución natural impulsada por la transformación continua en la forma en que se diseñan productos y servicios digitales. Este enfoque combina herramientas de diseño con metodologías ágiles de desarrollo de software, fomentando la colaboración continua entre todos los actores involucrados.

En el contexto hotelero y de hostales, donde la experiencia del huésped es el eje central de la propuesta de valor, Lean UX resulta particularmente valioso al permitir ciclos iterativos rápidos, validación temprana de hipótesis y una comunicación fluida entre diseñadores, desarrolladores, personal operativo y stakeholders. Esta filosofía no solo mejora la eficiencia en la toma de decisiones, sino que garantiza que las soluciones estén profundamente alineadas con las necesidades reales de los huéspedes y los objetivos estratégicos del negocio.

#### 1.2.2.1. Lean UX Problem Statements

Domain:

- Los administradores de hostales y de hoteles independientes carecen de un sistema centralizado y de fácil acceso para gestionar las reservaciones, los huéspedes y los servicios adicionales. Como resultado, recurren a procesos manuales, lo que conduce a que la información se duplique, se cometan errores y se pierdan oportunidades de ingresos.

Customer Segments:

- Administradores y propietarios de hostales y de pequeños hoteles.
- Empresas familiares que actualmente gestionan las reservas de forma manual.

Pain Points:

- Los procesos manuales para las reservas, check-in/check-out y servicios adicionales pueden generar errores y pérdida de ingresos.
- La falta de un sistema integrado y accesible para que las operaciones estén bien centralizadas.

Gap:

- Existen sistemas de gestión de hoteles en el mercado, pero la mayoría son costosos, complejos o están pensados para las grandes cadenas. Esto deja a los pequeños hostales y hoteles en una desventaja tecnológica y operacional.

Vision/Strategy:

- Hostel Manager busca ser la plataforma líder en gestión digital para hostales y hoteles en latinoamérica, reconocida por la innovación tecnológica, la integración con dispositivos inteligentes y el modelo de suscripción flexible. Aspirando a construir un ecosistema turístico más  competitivo, eficiente y sostenible, donde la tecnología impulse el crecimiento de los negocios.

Initial Segment:

- El segmento inicial lo conforman hostales y hoteles pequeños situados en zonas turísticas de Perú y Latinoamérica, con recursos económicos limitados, que necesitan una solución de gestión sencilla y flexible mediante una suscripción mensual.

#### 1.2.2.2. Lean UX Assumptions

- Los administradores de hostales necesitan herramientas tecnológicas fáciles de usar y de bajo costo.  
- Los procesos manuales provocan una pérdida de tiempo, generan errores y generan una baja competitividad en comparación con las grandes cadenas. 
- Una aplicación accesible que centralice sus operaciones puede resolver estas necesidades.
- Los administradores podrán optimizar los ingresos, reducir los errores operativos y mejorar la satisfacción de los huéspedes. 
- Los usuarios estarán dispuestos a pagar una suscripción mensual si les ayuda a aumentar la eficiencia y la rentabilidad.

#### 1.2.2.3. Lean UX Hypothesis Statements

- Creemos que los administradores optarán por utilizar Hostel Manager para centralizar y gestionar reservas y servicios adicionales, para reducir errores y ahorrar tiempo frente a los procesos manuales. Sabremos que estamos en lo cierto cuando al menos el 70% de los usuarios activos reportan una disminución en errores o duplicación de reservas en el primer trimestre.  

- Creemos que al ofrecer un modelo de suscripción mensual de bajo costo, para pequeños hostales y hoteles sin acceso a soluciones tecnológicas por el alto costo ayudará a la expansión del negocio. Sabremos que estamos en lo cierto cuando al menos el 50% de los hostales prospectos se conviertan en clientes de pago dentro de los 3 primeros meses.  

- Creemos que la simplificación de los procesos de check-in y check-out dará como resultado una reducción de tiempos de espera y errores administrativos, aumentando la productividad. Sabremos que estamos en lo cierto cuando los administradores reporten un ahorro promedio de 20 minutos al huésped.  

- Creemos que la generación automática de reportes financieros y operativos dará como resultado una mejor toma de decisiones sin necesidad de conocimientos avanzados y gestión. Sabremos que estamos en lo cierto cuando al menos 60% de los administradores usan los reportes semanales y manifiestan mejoras en la gestión de su negocio.  

- Creemos que la integración de un módulo de analítica predictiva dará como resultado una mejor planificación de recursos y estrategias de precios dinámicos. Sabremos que estamos en lo cierto cuando los hostales logren al menos un 5% de incremento en su tasa de ocupación en los primeros meses.  

- Creemos que la implementación de un sistema de soporte y asistencia en tiempo real dará como resultado una rápida resolución de incidencias y una mayor confianza en el uso de la aplicación. Sabremos que estamos en lo correcto cuando al menos el 70% de los administradores califiquen positivamente la asistencia recibida y se reduzca en un 30% las quejas relacionadas con el uso de la plataforma.  

- Creemos que la incorporación de pagos digitales (tarjetas, billeteras móviles, transferencia) dará como resultado una mayor comodidad para los huéspedes y un mejor control financiero para los administradores. Sabremos que estamos en lo cierto cuando el 50% de las transacciones se realicen a través de la plataforma en los primeros meses.

#### 1.2.2.4. Lean UX Canvas

![Lean Ux Canva](/images/LeanUXCanvas.jpg)

## 1.3. Segmentos objetivo

| Descripción | Estadísticas demográficas | Comportamiento y retos | Justificación de datos |
|---|---|---|---|
| **Administradores de Hostales y Pequeños Hoteles Independientes** <br><br> Este segmento agrupa a propietarios o administradores de hostales de entre 10 y 50 habitaciones que operan de manera independiente y sin grandes cadenas de respaldo. Su principal motivación es optimizar la ocupación, reducir errores de gestión manual y mejorar la experiencia del huésped para sostener la competitividad frente a la creciente oferta local y digital (ej. Airbnb, Booking, etc.). A pesar de tener conocimientos básicos en gestión hotelera, suelen depender de hojas de cálculo o sistemas desconectados que generan sobreventa, errores en asignación de habitaciones y altos costos de soporte. | **Edad:** 28–55 años <br><br> **Género:** Tanto hombres como mujeres <br><br> **Nivel socioeconómico:** Medio a medio-alto <br><br> **Educación:** Superior técnica o universitaria (administración, turismo, contabilidad o afines) <br><br> **Ubicación:** Principalmente en Lima Metropolitana y ciudades con alta afluencia turística (Cusco, Arequipa, Piura) <br><br> **Tamaño de negocio:** Hostales y pequeños hoteles con entre 10 y 50 habitaciones <br><br> **Pain Points:** Sobrecarga administrativa, errores en check-in/out, dificultad de integración con plataformas de reservas online, sobrecostos en soporte | **Digitalización rezagada:** El 55 % de hostales y pequeños hoteles en Latinoamérica aún operan con sistemas manuales o herramientas no integradas, generando pérdidas de eficiencia y errores en reservas (ALTUS, 2024). <br><br> **Competencia digital:** Plataformas como Airbnb y Booking capturan más del 35 % de las reservas urbanas, obligando a pequeños negocios a modernizar sus procesos para mantenerse competitivos (Statista, 2024). <br><br> **Impacto económico:** La sobreventa y la doble asignación generan pérdidas del 10–15 % en ingresos anuales para negocios independientes que no usan sistemas de gestión integrados (Hospitality Tech Report, 2023). <br><br> **Demanda de SaaS accesible:** Los pequeños hoteles priorizan soluciones de bajo costo y fácil adopción, siendo el SaaS una opción creciente en mercados emergentes (LATAM Hotel Tech Study, 2024). | **Oportunidad de adopción inmediata:** Hostel Manager se posiciona como una solución costo-eficiente que elimina errores manuales y profesionaliza la gestión. <br><br> **Escalabilidad en el mercado local:** Al dirigirse a negocios de 10–50 habitaciones, se atiende un segmento amplio y altamente desatendido en Perú y la región. <br><br> **Reducción de fricciones:** El diseño intuitivo y los reportes dinámicos permiten que administradores con poca experiencia digital puedan adaptarse rápidamente. <br><br> **Apalancamiento competitivo:** Un producto bien posicionado en este segmento puede convertirse en referencia en Lima y luego expandirse hacia hubs turísticos clave. |
| **Huéspedes Digitales y Viajeros Millennials** <br><br> Este segmento reúne a viajeros jóvenes (nacionales e internacionales) que buscan experiencias prácticas, rápidas y sin fricciones en sus estadías. Valoran herramientas como check-in online, notificaciones en tiempo real y comunicación directa con el hostal vía digital. Su motivación principal es reducir tiempos de espera y asegurar que su estadía sea cómoda y sin sorpresas negativas. Aunque no son quienes contratan el software directamente, su experiencia impacta en la percepción y recomendación del hostal, influyendo en la decisión del administrador de mantener la suscripción a Hostel Manager. | **Edad:** 20–40 años <br><br> **Género:** Hombres y mujeres con predominio del perfil millennial y centennial <br><br> **Nivel socioeconómico:** Medio a medio-alto <br><br> **Educación:** Secundaria completa o estudios superiores <br><br> **Ubicación:** Principalmente turistas nacionales de Lima, Cusco, Arequipa y extranjeros en tránsito por circuitos turísticos del Perú <br><br> **Perfil viajero:** Frecuentan hostales por viajes cortos, escapadas urbanas o turismo de aventura <br><br> **Pain Points:** Check-in lento, mala comunicación con el hostal, falta de notificaciones claras sobre reservas y servicios | **Preferencia digital:** Más del 70 % de los viajeros millennials prefiere gestionar sus reservas y check-in desde dispositivos móviles (Phocuswright, 2023). <br><br> **Intolerancia a la fricción:** El 60 % de los huéspedes abandona una reserva si el proceso digital es complejo o poco confiable (Booking Insights, 2024). <br><br> **Impacto en reviews:** Hasta el 80 % de las calificaciones negativas en plataformas como TripAdvisor están asociadas a demoras en check-in y deficiencias de comunicación (Travel Tech Association, 2023). <br><br> **Tendencia mobile-first:** El 65 % de las reservas en hostales urbanos de LATAM proviene de dispositivos móviles (Statista, 2024). | **Relevancia indirecta en la adopción:** Aunque los huéspedes no pagan por el software, sus expectativas digitales influyen en la decisión del administrador de mantener Hostel Manager activo. <br><br> **Efecto en reputación:** Mejorar la experiencia digital del huésped reduce reseñas negativas y aumenta la recomendación boca a boca, un factor crítico para hostales independientes. <br><br> **Tendencia global alineada:** La digitalización de la experiencia del huésped es un estándar creciente en hotelería, lo que convierte a Hostel Manager en una solución indispensable para mantenerse competitivo. <br><br> **Valor agregado en fidelización:** Al responder a las demandas de los viajeros tech, se refuerza la lealtad del administrador hacia la plataforma. |

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores
### 2.1.1. Análisis competitivo
### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping

## 2.4. Big Picture EventStorming
## 2.5. Ubiquitous Language

# Capítulo III: Requirements Specification

## 3.1. User Stories
## 3.2. Impact Mapping
## 3.3. Product Backlog

# Capítulo IV: Product Design

## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines
### 4.1.2. Web Style Guidelines

## 4.2. Information Architecture
### 4.2.1. Organization Systems
### 4.2.2. Labeling Systems
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems
### 4.2.5. Navigation Systems

## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
### 4.3.2. Landing Page Mock-up

## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.2. Web Applications Mock-ups
### 4.4.3. Web Applications User Flow Diagrams

## 4.5. Web Applications Prototyping

## 4.6. Domain-Driven Software Architecture
### 4.6.1. Design-Level EventStorming
### 4.6.2. Software Architecture Context Diagram
### 4.6.3. Software Architecture Container Diagrams
### 4.6.4. Software Architecture Components Diagrams

## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams

## 4.8. Database Design
### 4.8.1. Database Diagrams

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
### 5.1.2. Source Code Management
### 5.1.3. Source Code Style Guide & Conventions
### 5.1.4. Software Deployment Configuration

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1
#### 5.2.1.2. Aspect Leaders and Collaborators
#### 5.2.1.3. Sprint Backlog 1
#### 5.2.1.4. Development Evidence for Sprint Review
#### 5.2.1.5. Execution Evidence for Sprint Review
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
#### 5.2.1.8. Team Collaboration Insights during Sprint

# Conclusiones

# Bibliografía

# Anexos
