<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" width="150" alt="UPC Logo">

# Universidad Peruana de Ciencias Aplicadas

### **CURSO:** Arquitecturas De Software Emergentes

### **NRC**: 7291

### **Profesor:** Royer Edelwer Rojas Malasquez

### **Ingeniería de software**

## Informe de -

### **Nombre del startup:** NRG7

### **Nombre del producto:** -

## **Integrantes**

| **Nombre**                                | **Codigo** |
| ----------------------------------------- | ---------- |
| **Astonitas Díaz Juan Diego**             | U202110237 |
| **Casas Sanchez Gabriel Alexander**       | U202220033 |
| **Espinoza Delgado BárbaraAntonella**     | U201911727 |
| **Godofredo Quispe Tipon**                | u202120772 |
| **Pasquale Barrenechea Gianluca Santino** | U202112078 |

**Agosto 2025**

## Registro de Versiones del Informe

<table>
  <thead>
    <tr>
      <th>Versión</th>
      <th>Fecha</th>
      <th>Autor</th>
      <th>Descripción de modificación</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

## Project Report Collaboration Insights

El enlace a github del reporte del proyecto es el siguiente: [https://github.com/NRG7-Emergentes/report](https://github.com/NRG7-Emergentes/report).

## Contenido

- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1 Startup Profile](#11-startup-profile)
    - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2 Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1 Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3 Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3 Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1 Competidores](#21-competidores)
    - [2.1.1 Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2 Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2 Entrevistas](#22-entrevistas)
    - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2 Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3 Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3 Needfinding](#23-needfinding)
    - [2.3.1 User Personas](#231-user-personas)
    - [2.3.2 User Task Matrix](#232-user-task-matrix)
    - [2.3.3 Empathy Mapping](#233-empathy-mapping)
    - [2.3.4 As-is Scenario Mapping](#234-as-is-scenario-mapping)
  - [2.4 Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1 To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2 User Stories](#32-user-stories)
  - [3.3 Impact Mapping](#33-impact-mapping)
  - [3.4 Product Backlog](#34-product-backlog)
- [Capítulo IV: Strategic-Level Software Design](#capítulo-iv-strategic-level-software-design)
  - [4.1 Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
    - [4.1.1 Design Purpose](#411-design-purpose)
    - [4.1.2 Attribute-Driven Design Inputs](#412-attribute-driven-design-inputs)
      - [4.1.2.1 Primary Functionality (Primary User Stories)](#4121-primary-functionality-primary-user-stories)
      - [4.1.2.2 Quality attribute Scenarios](#4122-quality-attribute-scenarios)
      - [4.1.2.3 Constraints](#4123-constraints)
    - [4.1.3 Architectural Drivers Backlog](#413-architectural-drivers-backlog)
    - [4.1.4 Architectural Design Decisions](#414-architectural-design-decisions)
    - [4.1.5 Quality Attribute Scenario Refinements](#415-quality-attribute-scenario-refinements)
  - [4.2 Strategic-Level Domain-Driven Design](#42-strategic-level-domain-driven-design)
    - [4.2.1 EventStorming](#421-eventstorming)
    - [4.2.2 Candidate Context Discovery](#422-candidate-context-discovery)
    - [4.2.3 Domain Message Flows Modeling](#423-domain-message-flows-modeling)
    - [4.2.4 Bounded Context Canvases](#424-bounded-context-canvases)
    - [4.2.5 Context Mapping](#425-context-mapping)
  - [4.3 Software Architecture](#43-software-architecture)
    - [4.3.1 Software Architecture System Landscape Diagram](#431-software-architecture-system-landscape-diagram)
    - [4.3.2 Software Architecture Context Level Diagrams](#432-software-architecture-context-level-diagrams)
    - [4.3.3 Software Architecture Container Level Diagrams](#433-software-architecture-container-level-diagrams)
    - [4.3.4 Software Architecture Deployment Diagrams](#434-software-architecture-deployment-diagrams)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 3**

Criterio: _Capacidad de comunicarse efectivamente con un rango de audiencias._
En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
del ABET – EAC - Student Outcome 3.

<table>
  <thead>
    <tr>
      <th style="text-align: left;">Criterio específico</th>
      <th style="text-align: left;">Acciones realizadas</th>
      <th style="text-align: left;">Conclusiones</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería.</strong></td>
      <td>
        -
      </td>
      <td>
        -
      </td>
    </tr>
    <tr>
      <td><strong>Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto eningeniería.</strong></td>
      <td>
        -
      </td>
      <td>
        -
      </td>
    </tr>
  </tbody>
</table>

## Capítulo I: Introducción

### 1.1 Startup Profile

#### 1.1.1 Descripción de la Startup

#### 1.1.2 Perfiles de integrantes del equipo

### 1.2 Solution Profile

#### 1.2.1 Antecedentes y problemática

#### 1.2.2 Lean UX Process

##### 1.2.2.1 Lean UX Problem Statements

##### 1.2.2.2 Lean UX Assumptions

##### 1.2.2.3 Lean UX Hypothesis Statements

##### 1.2.2.4 Lean UX Canvas

### 1.3 Segmentos objetivo

## Capítulo II: Requirements Elicitation & Analysis

### 2.1 Competidores

#### 2.1.1 Análisis competitivo

#### 2.1.2 Estrategias y tácticas frente a competidores

### 2.2 Entrevistas

#### 2.2.1 Diseño de entrevistas

#### 2.2.2 Registro de entrevistas

#### 2.2.3 Análisis de entrevistas

### 2.3 Needfinding

#### 2.3.1 User Personas

#### 2.3.2 User Task Matrix

#### 2.3.3 Empathy Mapping

#### 2.3.4 As-is Scenario Mapping

### 2.4 Ubiquitous Language

## Capítulo III: Requirements Specification

### 3.1 To-Be Scenario Mapping

### 3.2 User Stories

### 3.3 Impact Mapping

### 3.4 Product Backlog

## Capítulo IV: Strategic-Level Software Design

### 4.1 Strategic-Level Attribute-Driven Design

El enfoque Attribute-Driven Design (ADD) permite estructurar la arquitectura de una solución priorizando los atributos de calidad que impulsan las decisiones clave de diseño. En esta sección se presenta el proceso a nivel estratégico, donde se establecen los drivers arquitectónicos, se justifican las decisiones de diseño y se ilustran los escenarios de atributos de calidad, concluyendo con una primera vista de la arquitectura de alto nivel.

#### 4.1.1 Design Purpose

El propósito del proceso de diseño en ErgoVision es establecer una arquitectura de solución que aborde de manera integral la problemática de los riesgos ergonómicos derivados del uso prolongado de dispositivos digitales. Este diseño se orienta a garantizar que la plataforma cumpla con los requerimientos de monitoreo postural en tiempo real, retroalimentación inmediata del comportamiento del usuario. De esta manera, se busca responder a las necesidades específicas de los segmentos objetivo, usuarios expuestos a posturas inadecuadas durante jornadas de trabajo o estudio, mediante un sistema que fomente hábitos saludables y prevenga lesiones. Al mismo tiempo, el proceso de diseño asegura la alineación con los objetivos estratégicos del negocio, fortaleciendo la propuesta de valor en el marco de la transformación digital aplicada a la salud y el bienestar.

#### 4.1.2 Attribute-Driven Design Inputs

En esta sección se fundamentará la identificación y análisis de insumos clave que orientan las decisiones arquitectónicas. Estos insumos constituyen la base para garantizar que la solución responda tanto a los requerimientos funcionales como a los atributos de calidad y restricciones que condicionan el diseño. En el caso de ErgoVision, los inputs se organizan en tres categorías: las funcionalidades primarias representadas por las historias de usuario más relevantes, los escenarios de atributos de calidad que reflejan las propiedades críticas de la solución, y las restricciones tecnológicas, organizacionales y de entorno que delimitan el espacio de diseño.

##### 4.1.2.1 Primary Functionality (Primary User Stories)

La primary user stories se refiere a aquellas historias de usuario que tienen un impacto directo en el cómo se va a estructurar la arquitectura de aplicación. Las primary user stories identificadas son las siguientes:

| User Story ID | Título                                     | Descripción                                                                                                                                                  | Criterios de Aceptación | Epic ID |
| ------------- | ------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------- | ------- |
| US-001        | Acceso a la Cámara                         | Como usuario, quiero permitir el acceso a mi cámara web para que el sistema pueda comenzar a analizar mi postura.                                            |                         | EP-001  |
| US-002        | Visualización del Esqueleto en Tiempo Real | Como usuario, quiero ver una superposición del esqueleto detectado sobre mi imagen de video para entender cómo el sistema interpreta mi postura.             |                         | EP-001  |
| US-003        | Detección de Postura Encorvada             | Como usuario, quiero que el sistema detecte automáticamente cuando mis hombros están desalineados o encorvados para poder corregirlo.                        |                         | EP-001  |
| US-004        | Detección de Proximidad a la Pantalla      | Como usuario, quiero que el sistema me alerte cuando mi rostro está demasiado cerca de la pantalla para prevenir fatiga visual.                              |                         | EP-001  |
| US-009        | Alertas Visuales para Mala Postura         | Como usuario, quiero recibir alertas visuales no intrusivas cuando mi postura es incorrecta, para corregirla inmediatamente sin interrupciones bruscas.      |                         | EP-002  |
| US-010        | Alertas Sonoras Personalizables            | Como usuario, quiero asignar sonidos diferentes para cada tipo de error postural, para identificar rápidamente el problema específico sin mirar la pantalla. |                         | EP-002  |
| US-015        | Calibración Inicial de Postura             | Como usuario, quiero realizar una calibración inicial de mi postura correcta para que el sistema reconozca mi posición ideal al sentarme.                    |                         | EP-003  |
| US-020        | Panel Principal de Estadísticas            | Como usuario, quiero ver un dashboard con mis métricas principales de postura para tener una visión general de mi progreso diario.                           |                         | EP-004  |
| US-023        | Recordatorio de Pausas Activas             | Como usuario, quiero recibir recordatorios automáticos para tomar pausas activas cada cierto tiempo para prevenir la fatiga y mejorar mi bienestar postural. |                         | EP-005  |

##### 4.1.2.2 Quality attribute Scenarios

Los escenarios de atributos de calidad de ErgoVision constituyen un insumo crítico para el diseño arquitectónico, ya que permiten anticipar cómo debe comportarse el sistema ante condiciones específicas relacionadas con el uso real. Estos escenarios reflejan las propiedades clave que aseguran la efectividad de la solución.

| **Atributo**       | **Fuente**    | **Estímulo**                                                              | **Artefacto**              | **Entorno**                              | **Respuesta**                                                               | **Medida**                                                          |
| ------------------ | ------------- | ------------------------------------------------------------------------- | -------------------------- | ---------------------------------------- | --------------------------------------------------------------------------- | ------------------------------------------------------------------- |
| **Rendimiento**    | Usuario       | El usuario habilita la cámara para iniciar monitoreo postural.            | Módulo de IA + Cámara      | Operación normal del sistema.            | El sistema procesa video y muestra esqueleto en tiempo real.                | Latencia ≤ 200 ms en la visualización del esqueleto.                |
| **Usabilidad**     | Usuario       | El usuario recibe una notificación de postura incorrecta.                 | Interfaz de Alertas        | Durante el uso continuo del sistema.     | El sistema despliega alerta visual no intrusiva y clara.                    | El 90% de usuarios entiende y actúa en < 3 segundos tras la alerta. |
| **Disponibilidad** | Usuario       | El usuario utiliza la app en una jornada de 8 horas.                      | Plataforma completa        | Carga de trabajo prolongada.             | El sistema mantiene el monitoreo sin interrupciones críticas.               | Uptime ≥ 99% durante sesiones de 8h.                                |
| **Escalabilidad**  | Administrador | La base de usuarios crece de 100 a 10,000 en 6 meses.                     | Infraestructura en la nube | Escenario de crecimiento progresivo.     | El sistema mantiene tiempos de respuesta consistentes al aumentar usuarios. | Tiempo de respuesta ≤ 500 ms con 10,000 usuarios concurrentes.      |
| **Fiabilidad**     | Usuario       | El sistema detecta un fallo en la conexión de cámara.                     | Módulo de Captura de Video | Cámara desconectada o error de hardware. | El sistema informa al usuario y permite reconectar automáticamente.         | Reconexión exitosa en < 10 segundos en el 95% de los casos.         |
| **Privacidad**     | Usuario       | El usuario configura su cuenta para no almacenar imágenes, solo métricas. | Módulo de Persistencia     | Configuración personalizada habilitada.  | El sistema guarda únicamente datos agregados sin imágenes sensibles.        | 100% de cumplimiento con la preferencia del usuario.                |

##### 4.1.2.3 Constraints

El proceso de diseño de ErgoVisión debe considerar restricciones no negociables que han sido impuestas tanto por las necesidades del negocio como por requerimientos técnicos mínimos para garantizar la viabilidad de la solución. Estas restricciones actúan como guías ineludibles para orientar la arquitectura hacia una plataforma confiable, segura y escalable, asegurando el cumplimiento de normativas y la alineación con las capacidades actuales del equipo de desarrollo y la infraestructura disponible. A continuación, se detallan las principales restricciones identificadas:

| Technical Story ID | Título                                            | Descripción                                                                                                                                                         | Criterios de Aceptación                                                                                                                                                                                                                                                               | Relacionado con (Epic ID) |
| ------------------ | ------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------- |
| TS-01              | Cumplimiento con normativas de seguridad de datos | La plataforma debe garantizar la protección de los datos de salud y ergonomía de los trabajadores según normativas locales e internacionales (ej. GDPR, ISO 27001). | **Escenario 1: Encriptación de datos** <br> **Dado que** un usuario registra o consulta información personal y de salud, **cuando** el sistema procesa o almacena esos datos, **entonces** los mismos deben estar encriptados y accesibles únicamente por usuarios autorizados.       | EP-01, EP-02              |
| TS-02              | Infraestructura Cloud                             | La solución debe desplegarse en un entorno de nube pública para asegurar escalabilidad y disponibilidad.                                                            | **Escenario 1: Disponibilidad** <br> **Dado que** el sistema se encuentra en operación, **cuando** se presente una consulta de disponibilidad, **entonces** el sistema debe demostrar un tiempo de actividad de al menos 99.5%.                                                       | EP-03                     |
| TS-03              | Multiplataforma                                   | El sistema debe ser accesible desde navegadores web modernos y dispositivos móviles (Android/iOS).                                                                  | **Escenario 1: Multiplataforma** <br> **Dado que** un usuario accede a la plataforma, **cuando** lo hace desde un navegador moderno o desde un dispositivo móvil, **entonces** la aplicación debe mostrar y ejecutar correctamente las funcionalidades principales.                   | EP-01, EP-04              |
| TS-04              | Límites de presupuesto                            | La solución debe desarrollarse utilizando tecnologías open-source o de bajo costo para ajustarse a los recursos económicos del negocio.                             | **Escenario 1: Tecnologias Open Source** <br> **Dado que** el equipo de desarrollo selecciona tecnologías, **cuando** se evalúen opciones de frameworks, librerías o servicios, **entonces** se deben priorizar alternativas open-source o de bajo costo salvo justificación técnica. | EP-03                     |
| TS-06              | Integración con sensores IoT                      | El sistema debe soportar la conexión con hardware de sensores IoT para captura de métricas ergonómicas.                                                             | **Escenario 1: IoT** <br> **Dado que** un sensor IoT certificado envía datos al sistema, **cuando** se recibe la transmisión, **entonces** la plataforma debe almacenar correctamente al menos un tipo de dato (ej. postura, movimiento).                                             | EP-02                     |

#### 4.1.3 Architectural Drivers Backlog

El proceso de identificación de Architectural Drivers se desarrolló de manera iterativa mediante un Quality Attribute Workshop, en el cual el equipo analizó los requisitos funcionales clave, los atributos de calidad prioritarios y las restricciones no negociables que condicionan el diseño de ErgoVisión.

El resultado de este análisis se consolida en un backlog de drivers arquitecturales, el cual sirve como guía estratégica para la definición y evolución de la solución. Dichos drivers se han clasificado según su importancia para los stakeholders y su impacto en la complejidad técnica de la arquitectura, priorizando aquellos con mayor influencia en ambas dimensiones.

Se siguió la siguiente leyenda para los drivers ID: FD = Functional Driver, QD = Quality Driver, TS = Technical Story.

| Driver ID | Título de Driver                         | Descripción                                                                                                                              | Importancia para Stakeholders | Impacto en Architecture Technical Complexity |
| --------- | ---------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------- | -------------------------------------------- |
| FD-01     | Monitoreo postural en tiempo real        | Permite capturar y analizar la postura del usuario mediante IA, identificando desviaciones en hombros, cabeza y distancia a la pantalla. | High                          | High                                         |
| FD-02     | Sistema de alertas y notificaciones      | Proporciona retroalimentación inmediata (visual, sonora o push) para corregir la postura y prevenir riesgos.                             | High                          | Medium                                       |
| FD-03     | Personalización y calibración            | Facilita un proceso de configuración inicial y ajustes de sensibilidad según el usuario.                                                 | Medium                        | Medium                                       |
| FD-04     | Seguimiento de progreso y analytics      | Ofrece paneles con métricas de evolución, hábitos y patrones de error.                                                                   | Medium                        | Medium                                       |
| FD-05     | Gestión de bienestar y prevención        | Incluye recordatorios de pausas activas y guías de estiramiento.                                                                         | Medium                        | Low                                          |
| FD-06     | Gestión de usuario y perfil              | Permite registro, login, recuperación de contraseña y preferencias de cuenta.                                                            | High                          | Medium                                       |
| QD-01     | Performance y baja latencia              | El sistema debe procesar video y emitir alertas en menos de 200 ms.                                                                      | High                          | High                                         |
| QD-02     | Usabilidad y accesibilidad               | La interfaz debe ser clara, accesible y adaptada a usuarios con diferentes perfiles.                                                     | High                          | Medium                                       |
| QD-03     | Escalabilidad                            | La plataforma debe soportar un incremento progresivo de usuarios y dispositivos IoT.                                                     | High                          | High                                         |
| QD-04     | Seguridad de datos                       | Los datos de postura y salud deben almacenarse y transmitirse de forma encriptada.                                                       | High                          | High                                         |
| QD-05     | Disponibilidad                           | El sistema debe mantener un uptime mínimo de 99.5% en entorno cloud.                                                                     | High                          | Medium                                       |
| QD-06     | Interoperabilidad IoT                    | La plataforma debe integrarse con sensores IoT heterogéneos.                                                                             | Medium                        | High                                         |
| TS-01     | Cumplimiento con normativas de seguridad | La solución debe cumplir GDPR e ISO 27001 para datos sensibles.                                                                          | High                          | High                                         |
| TS-02     | Infraestructura Cloud                    | El sistema debe desplegarse en nube pública.                                                                                             | High                          | Medium                                       |
| TS-03     | Multiplataforma                          | La aplicación debe estar disponible en navegadores modernos y móviles (Android/iOS).                                                     | High                          | Medium                                       |
| TS-04     | Límites de presupuesto                   | Se deben priorizar tecnologías open-source o de bajo costo.                                                                              | Medium                        | Medium                                       |
| TS-06     | Integración con sensores IoT             | El sistema debe procesar datos enviados por hardware externo.                                                                            | High                          | High                                         |

#### 4.1.4 Architectural Design Decisions

Las Architectural Design Decisions de ErgoVision representan una especificación detallada de las elecciones arquitectónicas clave que guiaran el diseño de la solución y las alternativas que se tomaron en cuenta

| Driver ID | Driver                              | Decisión Relacionada                                       | Motivación                                                                             | Alternativas Consideradas                         | Estado   |
| --------- | ----------------------------------- | ---------------------------------------------------------- | -------------------------------------------------------------------------------------- | ------------------------------------------------- | -------- |
| FD-01     | Monitoreo postural en tiempo real   | DD1: Uso de Google AI Mediapipe Pose Landmark              | Aprovechar un modelo probado de visión por computadora para detección precisa y rápida | Desarrollar un modelo propio de IA, usar OpenPose | Aprobada |
| FD-02     | Sistema de alertas y notificaciones | DD2: Uso de Firebase Cloud Messaging                       | Permite notificaciones push en tiempo real en múltiples dispositivos                   | Socket.io, servicios de terceros de mensajería    | Aprobada |
| FD-06     | Gestión de usuario y perfil         | DD3: Base de datos PostgreSQL                              | Ofrece robustez, consistencia ACID y buena integración con Spring Boot                 | MySQL, MongoDB                                    | Aprobada |
| QD-01     | Performance y baja latencia         | DD4: Arquitectura monolítica con Spring Boot               | Reduce complejidad y overhead, garantizando menor latencia en despliegues iniciales    | Arquitectura de microservicios                    | Aprobada |
| QD-01     | Performance y baja latencia         | DD10: Uso de Redis como caché en memoria                   | Permite reducir la carga de PostgreSQL y acelerar la respuesta a consultas frecuentes  | Memcached, solo acceso directo a Postgres         | Aprobada |
| QD-02     | Usabilidad y accesibilidad          | DD5: Frontend en Angular + Tailwind                        | Permite una UI escalable, responsive y de fácil mantenimiento                          | React, Vue + Bootstrap                            | Aprobada |
| QD-03     | Escalabilidad                       | DD6: Contenerización con Docker y orquestación con Compose | Facilita replicación del servicio en distintos entornos y despliegues ágiles           | Kubernetes, despliegue manual sin contenedores    | Aprobada |
| QD-04     | Seguridad de datos                  | DD7: Nginx como balanceador + TLS                          | Provee capa de seguridad y manejo eficiente de tráfico entrante                        | Apache HTTP Server, Caddy                         | Aprobada |
| QD-05     | Disponibilidad                      | DD8: Hosting en Render con autoescalado básico             | Plataforma gestionada que ofrece despliegue sencillo con redundancia mínima            | AWS EC2, Azure App Services                       | Aprobada |
| QD-06     | Interoperabilidad IoT               | DD9: Uso de webcam externa estándar                        | Garantiza compatibilidad amplia con librerías de visión por computadora                | Cámaras IP propietarias, sensores personalizados  | Aprobada |
| TS-01     | Cumplimiento de normativas          | DD7: Cifrado TLS con Nginx                                 | Protege los datos y cumple buenas prácticas en privacidad                              | Sin cifrado extremo a extremo                     | Aprobada |
| TS-02     | Infraestructura Cloud               | DD8: Render como proveedor de hosting                      | Minimiza costos y facilita despliegue sin infraestructura propia                       | Servidores on-premise                             | Aprobada |
| TS-03     | Multiplataforma                     | DD2 + DD5: Firebase Cloud Messaging + Angular PWA          | Garantiza disponibilidad en navegador y dispositivos móviles                           | Desarrollo nativo Android/iOS                     | Aprobada |
| TS-04     | Límites de presupuesto              | DD6 + DD8: Uso de Docker Compose y Render                  | Reduce costos operativos y licencias, aprovecha servicios gratuitos/low-cost           | Kubernetes, proveedores cloud empresariales       | Aprobada |

#### 4.1.5 Quality Attribute Scenario Refinements

Los escenarios refinados de atributos de calidad de ErgoVision representan una especificación detallada de cómo los atributos deben manifestarse en situaciones de uso concretas. A través de su refinamiento, se convierten en condiciones medibles y verificables, que permiten evaluar de manera objetiva el desempeño del sistema bajo distintos estímulos.

| Atributo de Calidad | Estímulo                                              | Escenario Refinado                                           | Evaluación Esperada                      |
| ------------------- | ----------------------------------------------------- | ------------------------------------------------------------ | ---------------------------------------- |
| Rendimiento         | Usuario habilita la cámara para iniciar monitoreo.    | El sistema procesa video y muestra esqueleto en <200 ms.     | 95% de las pruebas cumplen con ≤200 ms.  |
| Usabilidad          | Usuario recibe notificación de postura incorrecta.    | El sistema despliega alerta clara y entendible en <3 s.      | 90% de usuarios comprenden y reaccionan. |
| Disponibilidad      | Usuario utiliza la app durante una jornada de 8 h.    | El sistema mantiene monitoreo continuo sin interrupciones.   | Uptime ≥99.5% en jornadas de 8h.         |
| Escalabilidad       | La base de usuarios crece de 100 a 10,000 en 6 meses. | El sistema mantiene tiempos de respuesta ≤500 ms.            | Respuesta ≤500 ms con 10k usuarios.      |
| Fiabilidad          | El sistema detecta un fallo en la conexión de cámara. | El sistema informa al usuario y reconecta en <10 s.          | Reconexión exitosa en ≥95% de casos.     |
| Privacidad          | Usuario configura su cuenta para no guardar imágenes. | El sistema guarda únicamente datos agregados y no sensibles. | 100% cumplimiento GDPR e ISO 27001.      |

### 4.2 Strategic-Level Domain-Driven Design

#### 4.2.1 EventStorming

Para la sección de Event Storming el equipo de desarrollo tuvo una reunión donde expusimos ideas acerca de las funcionalidades y caracteristicas a implementar en el proyecto. En el transcurso de la reunión, se lograron plantar varias ideas para la plataforma y la aplicación mobil, además de las primeras versiones para los bounded context.

En esta etapa, se identificaron los eventos clave que representan las acciones significativas dentro de la solución IoT. La herramienta utilizada fue Miro.

1.  Define the Purpose
    En esta fase se generan ideas relacionadas con el objetivo del proyecto, aprovechando la lluvia de ideas como recurso clave.

    <img src="../report/images/chapter-4/paso-1.png" alt="Define the Purpose">

2.  Timelines
    Durante esta fase, los eventos identificados fueron agrupados en subgrupos liderados por un evento en general que encapsula la función principal del grupo.

    <img src="../report/images/chapter-4/paso-2.png" alt="Timelines">

3.  Paint Points
    En este proceso, se identificaron paint points o puntos problemáticos, que son áreas donde los usuarios pueden experimentar dificultados o fricciones en su interacción con la aplicación. Estos puntos son cruciales para mejorar la experiencia del usuario y optimizar el diseño del sistema.

    <img src="../report/images/chapter-4/paso-3.png" alt="Paint Points">

4.  Pivotal points
    Se señalaron los pivotal points o puntos clave, que son eventos críticos que marcan hitos improtantes en el flujo de la plataforma. Estos eventos tienden a ser significativos en el comportamiento del sistema o en la experiencia del usuario.

    <img src="../report/images/chapter-4/paso-4.png" alt="Pivotal points">

5.  Commands
    Cada evento se asoció a un comando en específico que lo desencadena y un actor que lo realiza. Esto ayudó a tener un mejor reconocimiento de cómo interactúan los diferentes usuarios con el sistema.

    <img src="../report/images/chapter-4/paso-5.png" alt="Commands">

6.  Policies
    Durante esta etapa, se identifican las politicas relevantes para cada contexto del sistema. Estas politicas pueden incluir restricciones de negocio, reglas de validación, etc.

    <img src="../report/images/chapter-4/paso-6.png" alt="Policies">

7.  Read Models
    Durante esta fase, se diseñan y desarrollan lso modelos de lectura para cada contexto de sistema, asegurando que proporcionen la información necesaria de manera eficiente y coherente.

    <img src="../report/images/chapter-4/paso-7.png" alt="Read Models">

8.  External Systems
    Durante esta etapa, se identifican los sistemas externos relevantes para la plataforma y se establecen las interfaces necesarias para integrarlos de manera efectiva.

    <img src="../report/images/chapter-4/paso-8.png" alt="External Systems">

9.  Aggregates
    Durante esta etapa, se definen aggregates para cada contexto del sistema, asegurando que representen correctamente las transacciones y operaciones coherentes dentro del sistema.
    <img src="../report/images/chapter-4/paso-9.png" alt="Aggregates">

El enlace al Miro: [https://miro.com/app/board/uXjVJIOOJ5E=/](https://miro.com/app/board/uXjVJIOOJ5E=/).

#### 4.2.2 Candidate Context Discovery

A continuación, elegimos utilizar la técnica de start-with-value ya que el equipo de desarrollo decidió empezar por el valor de la aplicación (core), esto es importante para tener una mejor visión del producto.

- **Identificación de Valores del Negocio** : Analizamos los valores clave del negocio, como la experiencia del usuario al estar en su entorno de trabajo/estudio y monitorear su postura, la alertas/notificaciones y la eficiencia en la gestión de usuarios.
- **Identificación de Funcionalidades clave** : Identificar las funcionalidades esenciales de la aplicación, el monitoreo postura correcta, notificaciones/alertas y registro de su proceso que contribuyen directamente a la mejora de salud e eficioencia en su entorno.

**Candidate para Bounded Context: IAM**

Este contexto está encargado de manejar el ciclo de vida de los usuarios en la plataforma, desde el registro hasta la validación de credenciales y el acceso a la plataforma, de acuerdo con su rol, ya sea estudiante o trabajador remoto. Se cubren tres políticas clave: Política de Registro , Registro de Roles y Política de Autenticación.

Posibles responsabilidades del Bounded Context:

- Gestionar el registro y autenticación de usuarios.
- Definir y aplicar políticas de roles para asegurarse de que cada usuario tenga las capacidades correctas dentro del sistema.
- Proveer un sistema de validación de credenciales utilizando estándares de seguridad como JWT.
- Facilitar el acceso a la plataforma basado en los roles asignados al usuario al registrarse.

<img src="../report/images/chapter-4/iam.png" alt="iam">

**Candidate para Bounded Context: Orquestrador**

Este contexto se encarga de administrar y coordinar las configuraciones externas a la plataforma, garantizando que los dispositivos y el entorno estén correctamente preparados para el monitoreo.

Posibles responsabilidades del Bounded Context:

- Gestionar la configuración de la cámara web (posición, encuadre, resolución).
- Ajustar la iluminación y otros parámetros del entorno que influyen en la detección postural.
- Coordinar la comunicación entre los distintos módulos (Monitoreo, Notificaciones, Estadísticas).

<img src="../report/images/chapter-4/orquestador.png" alt="orquestador">

**Candidate para Bounded Context: Monitoreo**

Este contexto se encarga de supervisar en tiempo real la postura del usuario durante sus actividades frente a la estación de trabajo/estudio, utilizando modelos de visión por computadora.

Posibles responsabilidades del Bounded Context:

- Capturar datos de video y extraer puntos clave del cuerpo del usuario.
- Analizar la postura del usuario en función de umbrales de confort previamente definidos.
- Detectar desviaciones o malas posturas de forma continua.
- Registrar la evolución de la postura del usuario a lo largo de la sesión de trabajo.

<img src="../report/images/chapter-4/monitoreo.png" alt="monitoreo">

**Candidate para Bounded Context: Notificaciones**

Este contexto se encarga de alertar y comunicar al usuario cuando se detecta una postura inadecuada, ofreciendo recordatorios y sugerencias de corrección.

Posibles responsabilidades del Bounded Context:

- Emitir notificaciones en tiempo real al detectar malas posturas.
- Generar recordatorios de pausas activas o microdescansos.
- Adaptar la frecuencia e intensidad de las alertas según la severidad de la desviación postural.
- Permitir personalización de notificaciones (tono).

<img src="../report/images/chapter-4/notificaciones.png" alt="notificacion">

**Candidate para Bounded Context: Estadisticas**

Este contexto se encarga de recolectar, procesar y presentar métricas relacionadas con el comportamiento postural del usuario, con el fin de apoyar la mejora continua y la prevención de lesiones.

Posibles responsabilidades del Bounded Context:

- Generar reportes semanales o mensuales sobre la postura del usuario.
- Consolidar métricas de tiempo en buena/mala postura.
- Identificar patrones de riesgo o tendencias a lo largo del tiempo.
- Proveer visualizaciones de datos para el usuario y/o administradores.

<img src="../report/images/chapter-4/estadisticas.png" alt="estadistica">

Vista completa:

<img src="../report/images/chapter-4/bc-completo.png" alt="BondenContext">

#### 4.2.3 Domain Message Flows Modeling

#### 4.2.4 Bounded Context Canvases

**Estadísticas**

El diseño del bounded context se centra en proporcionar visibilidad del comportamiento postural de los usuarios a través de métricas y reportes. Al ser parte del dominio Core, el valor del sistema depende en gran medida de la capacidad de ofrecer retroalimentación clara y confiable que permita prevenir problemas de salud relacionados con la ergonomía. La solución está orientada a consolidar datos de monitoreo en información útil y visualizaciones que promuevan la mejora continua.

1. **Propósito (Purpose):**

El contexto está diseñado para gestionar la recolección, procesamiento y visualización de estadísticas posturales, permitiendo a los usuarios conocer su comportamiento a lo largo del tiempo y tomar decisiones que favorezcan una postura saludable.

2. **Clasificación Estratégica (Strategic Classification):**

- **Dominio:** Core, ya que la interpretación de los datos de monitoreo es fundamental para cumplir con el objetivo del sistema: mejorar la salud postural de los usuarios.
- **Modelo de Negocio:** Funciona como un decision enabler, al transformar datos en información que guía la prevención de riesgos.
- **Evolución:** Clasificado como custom build, ya que las métricas y reportes deben adaptarse al contexto específico del monitoreo ergonómico y a las necesidades de usuarios remotos.

3. **Roles del Dominio (Domain Roles):**

El contexto actúa bajo el rol de Analytical Context, donde los usuarios consumen reportes y visualizaciones para comprender patrones de comportamiento y tendencias relacionadas con su postura.

4. **Comunicación Entrante (Inbound Communication):**

Los datos provienen principalmente de los módulos de **Monitoreo** e **IAM**.
Mensajes clave entrantes:

- Posture session data
- Metrics request
- User identification

5. **Comunicación Saliente (Outbound Communication):**

El sistema genera salidas hacia el **Frontend** y potencialmente al módulo de **Notificaciones**.
Mensajes clave salientes:

- Statistics report generated
- Trend visualization ready
- Risk pattern identified

6. **Lenguaje Ubicuo (Ubiquitous Language):**

- **Métrica (Metric):** Valor cuantitativo que refleja un aspecto del comportamiento postural.
- **Reporte (Report):** Resumen visual o textual de las métricas en un período definido.
- **Tendencia (Trend):** Variación de una métrica en el tiempo.
- **Sesión (Session):** Intervalo en el que se recopilan datos de monitoreo postural.

7. **Decisiones de Negocio (Business Decisions):**

- Los reportes deben segmentarse en diferentes períodos (día, semana, mes).
- Los datos históricos se deben preservar para comparación a largo plazo.
- Solo los usuarios autenticados pueden acceder a sus propias estadísticas.
- La detección de tendencias de riesgo debe generar recomendaciones preventivas.

8. **Suposiciones (Assumptions):**

- Los datos de monitoreo son confiables y están previamente validados.
- Los reportes generados son utilizados activamente por los usuarios para mejorar su postura.
- El sistema debe ser capaz de manejar un volumen creciente de datos históricos.

9. Métricas de Verificación (Verification Metrics):

El éxito del contexto se medirá por:

- El número de reportes generados y consultados por los usuarios.
- El nivel de interacción de los usuarios con las visualizaciones de tendencias.
- La reducción de alertas por malas posturas a lo largo del tiempo (como efecto indirecto).
- La satisfacción de los usuarios con la claridad y utilidad de los reportes generados.

 <img src="../report/images/chapter-4/canvas-estadistica.png" alt="Canvas Estadistica">

#### 4.2.5 Context Mapping

### 4.3 Software Architecture

#### 4.3.1 Software Architecture System Landscape Diagram

![nrg7-landscape.png](images/chapter-4/nrg7-landscape.png)

#### 4.3.2 Software Architecture Context Level Diagrams

![nrg7-context.png](images/chapter-4/nrg7-context.png)

#### 4.3.3 Software Architecture Container Level Diagrams

![nrg7-container.png](images/chapter-4/nrg7-container.png)

#### 4.3.4 Software Architecture Deployment Diagrams

## Conclusiones

## Bibliografía

## Anexos
