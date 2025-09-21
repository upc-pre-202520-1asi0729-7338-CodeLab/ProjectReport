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
| Comunica oralmente con efectividad a diferentes rangos de audiencia.   |                     |              |
| Comunica por escrito con efectividad a diferentes rangos de audiencia. |                     |              |

# Capítulo I: Introducción

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
### 1.1.2. Perfiles de integrantes del equipo

## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática
### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
#### 1.2.2.2. Lean UX Assumptions
#### 1.2.2.3. Lean UX Hypothesis Statements
#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

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

### Epics

<table>
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Título</th>
      <th>Descripción (Como / Quiero / Para que)</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>EP01</td><td>Gestión de Reservas</td><td>Como administrador de un hostal quiero gestionar todo el ciclo de reservas (búsqueda, creación, cambios y cancelaciones) para reducir errores y optimizar la ocupación.</td></tr>
    <tr><td>EP02</td><td>Operación de Huéspedes</td><td>Como administrador quiero controlar check-in, check-out y el historial de cada huésped para ofrecer un servicio rápido y personalizado.</td></tr>
    <tr><td>EP03</td><td>Servicios y Experiencia</td><td>Como huésped quiero solicitar y pagar servicios adicionales en tiempo real para que mi estadía sea más cómoda y completa.</td></tr>
    <tr><td>EP04</td><td>Administración Financiera</td><td>Como administrador quiero registrar pagos, generar facturas y obtener reportes para mantener un control financiero confiable.</td></tr>
    <tr><td>EP05</td><td>Plataforma y Acceso Seguro</td><td>Como usuario quiero autenticarme y acceder desde cualquier dispositivo para que mis datos estén protegidos y pueda operar en todo momento.</td></tr>
    <tr><td>EP06</td><td>Marketing y Captación</td><td>Como visitante o potencial cliente quiero conocer la propuesta de valor, planes y testimonios en una landing page para decidir registrarme o solicitar más información.</td></tr>
    <tr><td>EP07</td><td>API Pública e Integraciones</td><td>Como desarrollador externo quiero consumir una API RESTful de reservas, pagos y usuarios para integrar Hostel Manager con otros sistemas o aplicaciones.</td></tr>
  </tbody>
</table>


### User Stories

> Cada historia incluye dos escenarios de aceptación en formato **Given–When–Then**.

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de Aceptación (2 escenarios)</th>
      <th>Epic</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US01</td>
      <td>Buscar disponibilidad</td>
      <td>Como huésped quiero consultar habitaciones libres por fecha para planificar mi viaje.</td>
      <td>
        Escenario 1: Dado fechas válidas, cuando solicita disponibilidad, entonces el sistema muestra habitaciones.<br/>
        Escenario 2: Dado rango invertido, cuando solicita disponibilidad, entonces el sistema informa “Fechas no válidas”.
      </td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US02</td>
      <td>Crear reserva</td>
      <td>Como administrador quiero registrar una reserva con datos de huésped y habitación para asegurar la disponibilidad.</td>
      <td>
        Escenario 1: Dado que ingresa datos válidos, cuando confirma, entonces el sistema guarda la reserva y confirma.<br/>
        Escenario 2: Dado que la habitación está ocupada, cuando intenta reservar, entonces el sistema muestra “No disponible”.
      </td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US03</td>
      <td>Modificar reserva</td>
      <td>Como administrador quiero actualizar las fechas o datos de una reserva para mantener la información correcta.</td>
      <td>
        Escenario 1: Dado que la reserva está activa, cuando modifica fechas, entonces el sistema valida y guarda cambios.<br/>
        Escenario 2: Dado que las nuevas fechas se superponen, cuando guarda, entonces el sistema muestra “Conflicto de fechas”.
      </td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US04</td>
      <td>Cancelar reserva</td>
      <td>Como administrador quiero cancelar reservas confirmadas para liberar la habitación.</td>
      <td>
        Escenario 1: Dado que selecciona una reserva activa, cuando confirma, entonces el sistema marca la reserva como cancelada <br/>
        Escenario 2: Dado que la reserva ya está cancelada, cuando intenta cancelarla, entonces el sistema indica “Reserva ya cancelada”.
      </td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US05</td>
      <td>Reserva en línea</td>
      <td>Como huésped quiero crear y pagar una reserva desde mi dispositivo para obtener confirmación inmediata.</td>
      <td>
        Escenario 1: Dado que ingresa datos válidos y método de pago, cuando confirma, entonces el sistema registra la reserva y envía confirmación. <br/>
        Escenario 2: Dado que el pago falla, cuando intenta reservar, entonces el sistema notifica “Transacción no completada”.
      </td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US06</td>
      <td>Confirmación por correo</td>
      <td>Como huésped quiero recibir un email con los detalles de la reserva para comprobarla en cualquier momento.</td>
      <td>
        Escenario 1: Dado que la reserva es creada, cuando el sistema procesa, entonces envía correo de confirmación. <br/>
        Escenario 2: Dado que el correo del huésped es incorrecto, cuando se intenta enviar, entonces el sistema registra el error y alerta al administrador.
      </td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US07</td>
      <td>Registrar huésped</td>
      <td>Como administrador quiero registrar la información de un nuevo huésped para mantener un historial de clientes.</td>
      <td>
        Escenario 1: Dado que ingresa todos los datos requeridos, cuando guarda, entonces el sistema confirma “Huésped registrado”. <br/>
        Escenario 2: Dado que falta información obligatoria, cuando se guarda, entonces el sistema muestra “Datos incompletos”.
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US08</td>
      <td>Actualizar datos de huésped</td>
      <td>Como administrador quiero editar información personal de un huésped para mantener registros actualizados.</td>
      <td>
        Escenario 1: Dado que el huésped existe, cuando modifica datos, entonces el sistema guarda los cambios. <br/>
        Escenario 2: Dado que el ID no existe, cuando intenta modificar, entonces el sistema muestra “Huésped no encontrado”.
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US09</td>
      <td>Check-in digital</td>
      <td>Como administrador quiero registrar el check-in de un huésped para actualizar el estado de la habitación en tiempo real.</td>
      <td>
        Escenario 1: Dado que hay reserva confirmada, cuando registra check-in, entonces el sistema cambia estado a “Ocupado”. <br/>
        Escenario 2: Dado que no hay reserva, cuando intenta check-in, entonces el sistema muestra “Reserva no encontrada”.
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US10</td>
      <td>Check-out digital</td>
      <td>Como administrador quiero registrar la salida de un huésped para que la habitación quede disponible.</td>
      <td>
        Escenario 1: Dado que la habitación está ocupada, cuando confirma check-out, entonces el sistema libera la habitación. <br/>
        Escenario 2: Dado que no se ha hecho check-in, cuando intenta check-out, entonces el sistema muestra “Check-in no registrado”.
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US11</td>
      <td>Consultar historial de huésped</td>
      <td>Como administrador quiero revisar el historial de visitas de cada huésped para ofrecer un servicio personalizado.</td>
      <td>
        Escenario 1: Dado que selecciona un huésped válido, cuando solicita historial, entonces el sistema muestra reservas previas. <br/>
        Escenario 2: Dado que el huésped no tiene historial, cuando solicita, entonces el sistema muestra “Sin registros disponibles”.
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US12</td>
      <td>Registrar preferencias</td>
      <td>Como administrador quiero guardar preferencias especiales de cada huésped para personalizar futuras estadías.</td>
      <td>
        Escenario 1: Dado que ingresa preferencias, cuando guarda, entonces el sistema las asocia al perfil <br/>
        Escenario 2: Dado que el ID no existe, cuando guarda, entonces el sistema indica “Huésped no encontrado”.
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US13</td>
      <td>Crear servicio adicional</td>
      <td>Como administrador quiero definir servicios extras con precios para ofrecer más opciones de venta.</td>
      <td>
        Escenario 1: Dado que ingresa nombre y precio, cuando confirma, entonces el sistema lo registra. <br/>
        Escenario 2: Dado que falta el precio, cuando se guarda, entonces el sistema muestra “Información incompleta”.
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US14</td>
      <td>Editar servicio adicional</td>
      <td>Como administrador quiero modificar o eliminar un servicio extra para mantener la oferta actualizada.</td>
      <td>
        Escenario 1: Dado que el servicio existe, cuando se actualiza o elimina, entonces el sistema guarda cambios. <br/>
        Escenario 2: Dado que el ID no existe, cuando intenta modificar, entonces el sistema muestra “Servicio no encontrado”.
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US15</td>
      <td>Solicitar servicio en estadía</td>
      <td>Como huésped quiero pedir un servicio extra en tiempo real para que mi experiencia sea más cómoda.</td>
      <td>
        Escenario 1: Dado que hay servicios activos, cuando selecciona uno, entonces el sistema registra la solicitud y notifica. <br/>
        Escenario 2: Dado que el servicio está deshabilitado, cuando intenta solicitar, entonces el sistema muestra “Servicio no disponible”.
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US16</td>
      <td>Pagar servicio adicional</td>
      <td>Como huésped quiero pagar los servicios consumidos para cerrar mi cuenta de manera rápida y segura.</td>
      <td>
        Escenario 1: Dado que selecciona método de pago válido, cuando confirma, entonces el sistema procesa pago y emite comprobante. <br/>
        Escenario 2: Dado que el método es inválido, cuando confirma, entonces el sistema informa “Pago rechazado”.
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US17</td>
      <td>Registrar pago de reserva</td>
      <td>Como administrador quiero validar y registrar pagos recibidos para que el control financiero sea exacto.</td>
      <td>
        Escenario 1: Dado que ingresa datos correctos, cuando confirma, entonces el sistema registra el pago. <br/>
        Escenario 2: Dado que falta monto, cuando confirma, entonces el sistema muestra “Información insuficiente”.
      </td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US18</td>
      <td>Emisión de factura electrónica</td>
      <td>Como administrador quiero generar comprobantes automáticos de pago para cumplir requisitos legales.</td>
      <td>
        Escenario 1: Dado que se registra un pago, cuando se procesa, entonces el sistema envía factura al correo. <br/>
        Escenario 2: Dado que el correo es incorrecto, cuando intenta enviar, entonces el sistema registra error y alerta al administrador.
      </td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US19</td>
      <td>Reporte financiero por fechas</td>
      <td>Como administrador quiero obtener reportes de ingresos y ocupación para analizar el desempeño del negocio.</td>
      <td>
        Escenario 1: Dado que selecciona rango válido, cuando solicita, entonces el sistema genera reporte con totales <br/>
        Escenario 2: Dado que la fecha inicial es mayor a la final, cuando solicita, entonces el sistema muestra “Rango de fechas inválido”.
      </td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US20</td>
      <td>Conciliación de pagos</td>
      <td>Como administrador quiero conciliar pagos con reservas para detectar discrepancias.</td>
      <td>
        Escenario 1: Dado que existen transacciones, cuando solicita conciliación, entonces el sistema identifica coincidencias. <br/>
        Escenario 2: Dado que no hay pagos, cuando solicita, entonces el sistema muestra “No hay datos para conciliar”.
      </td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US21</td>
      <td>Autenticación segura</td>
      <td>Como usuario quiero iniciar sesión con credenciales protegidas para que mis datos permanezcan seguros.</td>
      <td>
        Escenario 1: Dado que las credenciales son válidas, cuando se envían, entonces el sistema concede acceso. <br/>
        Escenario 2: Dado que la contraseña es incorrecta, cuando se envían, entonces el sistema responde “Usuario o contraseña incorrectos”.
      </td>
      <td>EP05</td>
    </tr>
    <tr>
      <td>US22</td>
      <td>Recuperar contraseña</td>
      <td>Como usuario quiero restablecer mi contraseña olvidada para volver a acceder.</td>
      <td>
        Escenario 1: Dado que ingresa correo registrado, cuando solicita recuperación, entonces el sistema envía enlace temporal. <br/>
        Escenario 2: Dado que el correo no existe, cuando solicita, entonces el sistema muestra “Correo no encontrado”.
      </td>
      <td>EP05</td>
    </tr>
    <tr>
      <td>US23</td>
      <td>Gestión de roles</td>
      <td>Como administrador quiero asignar roles con distintos permisos para que cada usuario tenga el acceso adecuado.</td>
      <td>
        Escenario 1: Dado que selecciona un usuario y rol, cuando guarda, entonces el sistema aplica permisos. <br/>
        Escenario 2: Dado que el rol no existe, cuando intenta asignarlo, entonces el sistema muestra “Rol no válido”.
      </td>
      <td>EP05</td>
    </tr>
    <tr>
      <td>US24</td>
      <td>Acceso multicanal</td>
      <td>Como usuario quiero acceder desde web o móvil para tener flexibilidad de uso.</td>
      <td>
        Escenario 1: Dado que posee credenciales válidas, cuando inicia sesión desde cualquier dispositivo, entonces el sistema ofrece las mismas funciones. <br/>
        Escenario 2: Dado que el navegador no es compatible, cuando inicia sesión, entonces el sistema muestra “Dispositivo no soportado”.
      </td>
      <td>EP05</td>
    </tr>
    <tr>
      <td>US25</td>
      <td>Información en landing page</td>
      <td>Como visitante quiero ver la propuesta de valor y testimonios para decidir si registrarme.</td>
      <td>
        Escenario 1: Dado que accede a la landing, cuando la página carga, entonces se muestran secciones informativas. <br/>
        Escenario 2: Dado que el servidor está inactivo, cuando intenta acceder, entonces el sistema muestra un mensaje de mantenimiento.
      </td>
      <td>EP06</td>
    </tr>
    <tr>
      <td>US26</td>
      <td>Registro rápido desde landing</td>
      <td>Como administrador interesado quiero crear una cuenta desde la landing para empezar a usar la plataforma de inmediato.</td>
      <td>
        Escenario 1: Dado que ingresa datos válidos, cuando envía el formulario, entonces el sistema crea la cuenta y envía confirmación. <br/>
        Escenario 2: Dado que el correo no es válido, cuando se envía, entonces el sistema muestra “Formato de correo inválido”.
      </td>
      <td>EP06</td>
    </tr>
    <tr>
      <td>US27</td>
      <td>Formulario de contacto</td>
      <td>Como visitante quiero enviar una consulta o solicitud de demostración para que el equipo comercial me responda.</td>
      <td>
        Escenario 1: Dado que completa nombre, correo y mensaje, cuando envía, entonces el sistema confirma el envío y notifica al equipo. <br/>
        Escenario 2: Dado que falta un campo obligatorio, cuando envía, entonces el sistema muestra “Complete todos los campos”.
      </td>
      <td>EP06</td>
    </tr>
    <tr>
      <td>US28</td>
      <td>Visualizar planes y precios</td>
      <td>Como visitante quiero revisar planes de suscripción y costos para elegir el más adecuado.</td>
      <td>
        Escenario 1: Dado que accede a la sección de precios, cuando carga, entonces el sistema muestra planes actualizados. <br/>
        Escenario 2: Dado que ocurre fallo de datos, cuando carga, entonces el sistema muestra “Información no disponible temporalmente”.
      </td>
      <td>EP06</td>
    </tr>
    <tr>
      <td>US29</td>
      <td>Endpoint de reservas</td>
      <td>Como desarrollador externo quiero crear reservas mediante un endpoint RESTful para integrar mi aplicación con el sistema.</td>
      <td>
        Escenario 1:  Dado que el request contiene datos correctos, cuando se envía, entonces el sistema responde 201 con JSON de la reserva. <br/>
        Escenario 2: Dado que falta un campo obligatorio, cuando se envía, entonces el sistema responde 400 con mensaje de error.
      </td>
      <td>EP07</td>
    </tr>
    <tr>
      <td>US30</td>
      <td>Endpoint de pagos</td>
      <td>Como desarrollador externo quiero registrar pagos mediante un endpoint RESTful para sincronizar mis sistemas de cobro.</td>
      <td>
        Escenario 1:  Dado que el request es válido, cuando se procesa, entonces el sistema responde 201 con confirmación de pago. <br/>
        Escenario 2: Dado que la pasarela rechaza el pago, cuando se procesa, entonces el sistema responde 402 con mensaje de rechazo.
      </td>
      <td>EP07</td>
    </tr>
  </tbody>
</table>

---

## 3.2. Impact Mapping

> ![Impact Mapping](/images/ImpactMapping.png)

El mapa de impacto identifica los **Business Goals**, los **Actors/Personas**, los **Impacts** esperados y los **Deliverables** junto con las **User Stories** que soportan cada entregable.

---

## 3.3. Product Backlog

<table>
  <thead>
    <tr>
      <th>#Orden</th>
      <th>User Story ID</th>
      <th>Título</th>
      <th>Descripción (resumen)</th>
      <th>Story Points</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>1</td><td>US01</td><td>Buscar disponibilidad</td><td>Consultar habitaciones libres.</td><td>5</td></tr>
    <tr><td>2</td><td>US02</td><td>Crear reserva</td><td>Registrar una reserva para asegurar disponibilidad.</td><td>8</td></tr>
    <tr><td>3</td><td>US05</td><td>Reserva en línea</td><td>Reservar y pagar en línea para confirmación inmediata.</td><td>8</td></tr>
    <tr><td>4</td><td>US03</td><td>Modificar reserva</td><td>Actualizar fechas o datos de una reserva.</td><td>5</td></tr>
    <tr><td>5</td><td>US04</td><td>Cancelar reserva</td><td>Cancelar reservas confirmadas.</td><td>3</td></tr>
    <tr><td>6</td><td>US06</td><td>Confirmación por correo</td><td>Recibir un email con los detalles de la reserva.</td><td>3</td></tr>
    <tr><td>7</td><td>US09</td><td>Check-in digital</td><td>Registrar el check-in para actualizar la ocupación.</td><td>5</td></tr>
    <tr><td>8</td><td>US10</td><td>Check-out digital</td><td>Registrar la salida de un huésped.</td><td>3</td></tr>
    <tr><td>9</td><td>US07</td><td>Registrar huésped</td><td>Registrar la información de un nuevo huésped.</td><td>3</td></tr>
    <tr><td>10</td><td>US08</td><td>Actualizar datos de huésped</td><td>Editar información personal de un huésped.</td><td>3</td></tr>
    <tr><td>11</td><td>US11</td><td>Consultar historial de huésped</td><td>Revisar el historial de visitas.</td><td>3</td></tr>
    <tr><td>12</td><td>US12</td><td>Registrar preferencias</td><td>Guardar las preferencias del huésped.</td><td>3</td></tr>
    <tr><td>13</td><td>US13</td><td>Crear servicio adicional</td><td>Definir servicios extras con precios.</td><td>5</td></tr>
    <tr><td>14</td><td>US15</td><td>Solicitar servicio en estadía</td><td>Pedir un servicio extra en tiempo real.</td><td>5</td></tr>
    <tr><td>15</td><td>US16</td><td>Pagar servicio adicional</td><td>Pagar los servicios consumidos.</td><td>5</td></tr>
    <tr><td>16</td><td>US14</td><td>Editar servicio adicional</td><td>Modificar o eliminar un servicio extra.</td><td>3</td></tr>
    <tr><td>17</td><td>US17</td><td>Registrar pago de reserva</td><td>Validar y registrar pagos recibidos.</td><td>5</td></tr>
    <tr><td>18</td><td>US18</td><td>Emisión de factura electrónica</td><td>Generar comprobantes automáticos de pago.</td><td>5</td></tr>
    <tr><td>19</td><td>US19</td><td>Reporte financiero por fechas</td><td>Obtener reportes de ingresos y ocupación.</td><td>5</td></tr>
    <tr><td>20</td><td>US20</td><td>Conciliación de pagos</td><td>Conciliar pagos con reservas.</td><td>3</td></tr>
    <tr><td>21</td><td>US25</td><td>Información en landing page</td><td>Ver la propuesta de valor y testimonios.</td><td>3</td></tr>
    <tr><td>22</td><td>US26</td><td>Registro rápido desde landing</td><td>Crear una cuenta desde la landing.</td><td>5</td></tr>
    <tr><td>23</td><td>US27</td><td>Formulario de contacto</td><td>Enviar una consulta o solicitud de demo.</td><td>3</td></tr>
    <tr><td>24</td><td>US28</td><td>Visualizar planes y precios</td><td>Revisar planes de suscripción y costos.</td><td>3</td></tr>
    <tr><td>25</td><td>US21</td><td>Autenticación segura</td><td>Iniciar sesión con credenciales protegidas.</td><td>5</td></tr>
    <tr><td>26</td><td>US22</td><td>Recuperar contraseña</td><td>Restablecer la contraseña olvidada.</td><td>3</td></tr>
    <tr><td>27</td><td>US23</td><td>Gestión de roles</td><td>Asignar roles con distintos permisos.</td><td>5</td></tr>
    <tr><td>28</td><td>US24</td><td>Acceso multicanal</td><td>Acceder desde web o móvil.</td><td>3</td></tr>
    <tr><td>29</td><td>US29</td><td>Endpoint de reservas</td><td>Crear reservas mediante un endpoint RESTful.</td><td>8</td></tr>
    <tr><td>30</td><td>US30</td><td>Endpoint de pagos</td><td>Registrar pagos mediante un endpoint RESTful.</td><td>8</td></tr>
  </tbody>
</table>

---

**Referencia del Backlog en Jira:**  
![Product Backlog](/images/ProductBacklog_1.png)
![Product Backlog](/images/ProductBacklog_2.png)
[https://upc-team-tohi2bk.atlassian.net/jira/software/projects/HOSTEL/boards/1/backlog](https://upc-team-tohi2bk.atlassian.net/jira/software/projects/HOSTEL/boards/1/backlog)

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
