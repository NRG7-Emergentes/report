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

**Segmento 1: Trabajador Remoto**

<img src="images/chapter-3/to-be-scenario-mapping-trabajador-remoto.png" alt="To-Be Trabajador">

**Segmento 2: Estudiante con clases virtuales**

<img src="images/chapter-3/to-be-scenario-mapping-estudiante.png" alt="To-Be Estudiante">

### 3.2 User Stories

**Epics:**

<table>
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Título</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>EP-001</td>
      <td>Monitoreo Postural en Tiempo Real</td>
      <td>Sistema central de captura y análisis de video para detectar la postura del usuario mediante IA. Incluye visualización del esqueleto, procesamiento de landmarks y detección de anomalías en hombros, cabeza y proximidad a la pantalla.</td>
    </tr>
    <tr>
      <td>EP-002</td>
      <td>Sistema de Alertas y Notificaciones</td>
      <td>Mecanismos de retroalimentación inmediata para corregir la postura. Incluye alertas visuales no intrusivas, alertas sonoras personalizables por tipo de error y gestión de preferencias de notificaciones.</td>
    </tr>
    <tr>
      <td>EP-003</td>
      <td>Personalización y Calibración</td>
      <td>Funcionalidades para adaptar la experiencia al usuario específico. Incluye un wizard de calibración inicial, ajustes de sensibilidad para cada tipo de alerta y gestión de umbrales personalizados.</td>
    </tr>
    <tr>
      <td>EP-004</td>
      <td>Seguimiento de Progreso y Analytics</td>
      <td>Panel de control y historial para que el usuario visualice su evolución. Incluye gráficos de estadísticas (tiempo de uso, postura correcta), historial diario/semanal detallado e identificación de patrones de error.</td>
    </tr>
    <tr>
      <td>EP-005</td>
      <td>Gestión de Bienestar y Prevención</td>
      <td>Funciones proactivas para promover hábitos saludables. Incluye un recordatorio inteligente de pausas activas, guía de ejercicios de estiramiento y gestión de temporizadores de descanso.</td>
    </tr>
    <tr>
      <td>EP-006</td>
      <td>Gestión de Usuario y Perfil</td>
      <td>Sistema de autenticación y administración de la cuenta. Incluye registro, inicio de sesión, verificación de correo, recuperación de contraseña, edición del perfil y gestión de preferencias de la cuenta.</td>
    </tr>
  </tbody>
</table>

**User Stories:**
    
<table>
  <thead>
    <tr>
      <th>User Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de Aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td>US-001</td>
        <td>Acceso a la Cámara</td>
        <td>Como usuario, quiere permitir el acceso a su cámara web para que el sistema pueda comenzar a analizar su postura.</td>
        <td>
            <b>Escenario 1: Permiso concedido</b><br>
            Dado que el usuario ha iniciado sesión,<br>
            Cuando inicia el monitoreo,<br>
            Entonces el navegador solicita permiso para acceder a la cámara y, al concederlo, el feed de video se muestra en la interfaz.<br>
            <b>Escenario 2: Permiso denegado</b><br>
            Dado que el navegador solicita acceso a la cámara,<br>
            Cuando el usuario deniega el permiso,<br>
            Entonces se muestra un mensaje de error claro con instrucciones para habilitar el acceso manualmente.
        </td>
        <td>EP-001</td>
    </tr>
    <tr>
        <td>US-002</td>
        <td>Visualización del Esqueleto en Tiempo Real</td>
        <td>Como usuario, quiere ver una superposición del esqueleto detectado sobre su imagen de video para entender cómo el sistema interpreta su postura.</td>
        <td>
            <b>Escenario: Renderizado del modelo</b><br>
            Dado que la cámara está activa y el usuario está en el campo de visión,<br>
            Cuando MediaPipe Pose detecta los 33 landmarks,<br>
            Entonces se dibuja un esqueleto semitransparente que se ajusta en tiempo real a los movimientos del usuario.
        </td>
        <td>EP-001</td>
    </tr>
    <tr>
        <td>US-003</td>
        <td>Detección de Postura Encorvada</td>
        <td>Como usuario, quiere que el sistema detecte automáticamente cuando sus hombros están desalineados o encorvados para poder corregirlo.</td>
        <td>
            <b>Escenario 1: Detección de encorvamiento</b><br>
            Dado que el usuario está siendo monitoreado,<br>
            Cuando la inclinación de sus hombros supera el umbral configurado,<br>
            Entonces el sistema registra el evento como una "mala postura" y lo almacena para su análisis.<br>
            <b>Escenario 2: Postura correcta</b><br>
            Dado que el usuario estaba encorvado,<br>
            Cuando corrige su postura y sus hombros vuelven a estar alineados,<br>
            Entonces el sistema deja de registrar el evento de "mala postura".
        </td>
        <td>EP-001</td>
    </tr>
    <tr>
        <td>US-004</td>
        <td>Detección de Proximidad a la Pantalla</td>
        <td>Como usuario, quiere que el sistema le alerte cuando su rostro está demasiado cerca de la pantalla para prevenir fatiga visual.</td>
        <td>
            <b>Escenario 1: Rostro demasiado cerca</b><br>
            Dado que la cámara está calibrada,<br>
            Cuando la distancia estimada entre su rostro y la pantalla es menor a 50 cm,<br>
            Entonces el sistema activa una alerta de proximidad.<br>
            <b>Escenario 2: Distancia correcta</b><br>
            Dado que su rostro estaba demasiado cerca,<br>
            Cuando se aleja a una distancia mayor a 50 cm,<br>
            Entonces la alerta de proximidad se desactiva.
        </td>
        <td>EP-001</td>
    </tr>
    <tr>
        <td>US-005</td>
        <td>Detección de Inclinación de Cabeza</td>
        <td>Como usuario, quiere que el sistema detecte si su cabeza no está en una posición neutral (demasiado hacia adelante o hacia los lados) para mantener una columna vertebral alineada.</td>
        <td>
            <b>Escenario: Cabeza hacia adelante</b><br>
            Dado que el usuario está siendo monitoreado,<br>
            Cuando la proyección de su nariz está significativamente por delante de la línea de sus hombros,<br>
            Entonces el sistema registra un evento de "postura de avestruz".
        </td>
        <td>EP-001</td>
    </tr>
    <tr>
        <td>US-006</td>
        <td>Toggle de Visualización de Esqueleto</td>
        <td>Como usuario, quiere poder activar o desactivar la visualización del esqueleto sobre el video para reducir la distracción cuando no la necesita.</td>
        <td>
            <b>Escenario: Ocultar superposición</b><br>
            Dado que el esqueleto se está mostrando,<br>
            Cuando el usuario oculta la visualización del esqueleto,<br>
            Entonces la superposición gráfica desaparece pero el análisis de postura continúa en segundo plano.
        </td>
        <td>EP-001</td>
    </tr>
    <tr>
        <td>US-007</td>
        <td>Detección de Ángulo Brazo-Antebrazo</td>
        <td>Como usuario, quiere que el sistema verifique el ángulo de su articulación del codo (brazo-antebrazo) para detectar posiciones tensionantes y prevenir lesiones por mal apoyo.</td>
        <td>
            <b>Escenario 1: Ángulo correcto (~90 grados)</b><br>
            Dado que el usuario está sentado frente a la computadora,<br>
            Cuando su ángulo de codo se mantiene entre 80-100 grados,<br>
            Entonces el sistema no emite ninguna alerta.<br>
            <b>Escenario 2: Ángulo incorrecto (extensión excesiva)</b><br>
            Dado que el usuario está trabajando,<br>
            Cuando su ángulo de codo supera los 120 grados o es menor a 60 grados,<br>
            Entonces el sistema registra un evento de "mala postura de brazo" y activa la alerta correspondiente.
        </td>
        <td>EP-001</td>
    </tr>
    <tr>
        <td>US-008</td>
        <td>Detección de Alineación Pierna-Cadera-Espalda</td>
        <td>Como usuario, quiere que el sistema monitoree el ángulo entre sus muslos, cadera y hombros para asegurar una posición sentada ergonómicamente correcta.</td>
        <td>
            <b>Escenario 1: Postura correcta (ángulos adecuados)</b><br>
            Dado que el usuario está sentado correctamente,<br>
            Cuando sus muslos forman un ángulo de 90-110 grados con su cadera y su espalda está entre 90-110 grados con sus muslos,<br>
            Entonces el sistema mantiene el estado de postura correcta.<br>
            <b>Escenario 2: Postura incorrecta (inclinación pélvica)</b><br>
            Dado que el usuario está sentado,<br>
            Cuando el ángulo entre sus muslos y cadera es menor a 80 grados o mayor a 120 grados,<br>
            Entonces el sistema detecta "mala postura pélvica" y genera la alerta correspondiente.
        </td>
        <td>EP-001</td>
    </tr>
    <tr>
        <td>US-009</td>
        <td>Alertas Visuales para Mala Postura</td>
        <td>Como usuario, quiere recibir alertas visuales no intrusivas cuando su postura es incorrecta, para corregirla inmediatamente sin interrupciones bruscas.</td>
        <td>
            <b>Escenario 1: Alerta visual activa</b><br>
            Dado que el sistema detecta una mala postura,<br>
            Cuando se activa el evento de alerta,<br>
            Entonces aparece un borde de color suave alrededor de la interfaz indicando el tipo de error postural.<br>
            <b>Escenario 2: Alerta persistente</b><br>
            Dado que la mala postura continúa,<br>
            Cuando pasan más de 5 segundos sin corrección,<br>
            Entonces la alerta visual aumenta ligeramente su intensidad para reforzar la notificación.
        </td>
        <td>EP-002</td>
    </tr>
    <tr>
        <td>US-010</td>
        <td>Alertas Sonoras Personalizables</td>
        <td>Como usuario, quiere asignar sonidos diferentes para cada tipo de error postural, para identificar rápidamente el problema específico sin mirar la pantalla.</td>
        <td>
            <b>Escenario 1: Sonido de encorvamiento</b><br>
            Dado que se detecta espalda encorvada,<br>
            Cuando se activa la alerta,<br>
            Entonces se reproduce el sonido específico configurado para "encorvamiento".<br>
            <b>Escenario 2: Sonido de proximidad</b><br>
            Dado que se detecta proximidad excesiva a la pantalla,<br>
            Cuando se activa la alerta,<br>
            Entonces se reproduce un sonido diferente configurado para "proximidad".
        </td>
        <td>EP-002</td>
    </tr>
    <tr>
        <td>US-011</td>
        <td>Personalización de Volumen de Alertas</td>
        <td>Como usuario, quiere ajustar el volumen de las alertas sonoras para adaptarlas a su entorno de trabajo y no molestar a otras personas.</td>
        <td>
            <b>Escenario 1: Ajuste de volumen</b><br>
            Dado que el usuario está en la configuración de sonidos,<br>
            Cuando mueve el control deslizante de volumen al 50%,<br>
            Entonces las próximas alertas sonoras se reproducirán a ese nivel de volumen.<br>
            <b>Escenario 2: Silenciar alertas</b><br>
            Dado que el usuario necesita concentrarse en una tarea,<br>
            Cuando ajusta el volumen al 0%,<br>
            Entonces las alertas sonoras se desactivan completamente.
        </td>
        <td>EP-002</td>
    </tr>
    <tr>
        <td>US-012</td>
        <td>Selección de Alertas Activas</td>
        <td>Como usuario, quiere elegir qué tipos de alertas quiere recibir (visuales, sonoras o ambas) para personalizar su experiencia de notificaciones.</td>
        <td>
            <b>Escenario 1: Solo alertas visuales</b><br>
            Dado que el usuario está en un entorno silencioso,<br>
            Cuando desactiva las alertas sonoras pero mantiene las visuales,<br>
            Entonces solo recibirá notificaciones visuales para errores posturales.<br>
            <b>Escenario 2: Solo alertas sonoras</b><br>
            Dado que el usuario no está mirando constantemente la pantalla,<br>
            Cuando desactiva las alertas visuales pero mantiene las sonoras,<br>
            Entonces solo recibirá notificaciones sonoras para errores posturales.
        </td>
        <td>EP-002</td>
    </tr>
    <tr>
        <td>US-013</td>
        <td>Modo Silencio Temporal</td>
        <td>Como usuario, quiere pausar temporalmente todas las alertas durante reuniones o llamadas importantes, para evitar interrupciones inoportunas.</td>
        <td>
            <b>Escenario: Silencio por 30 minutos</b><br>
            Dado que el usuario tiene una reunión importante,<br>
            Cuando activa el "modo silencio" por 30 minutos,<br>
            Entonces el sistema no emitirá alertas visuales ni sonoras durante ese período.
        </td>
        <td>EP-002</td>
    </tr>
    <tr>
        <td>US-014</td>
        <td>Panel de Gestión de Alertas</td>
        <td>Como usuario, quiere acceder a un panel centralizado donde pueda gestionar todas sus preferencias de notificaciones, para tener control completo sobre su experiencia de alertas.</td>
        <td>
            <b>Escenario: Configuración completa</b><br>
            Dado que el usuario accede al panel de gestión de alertas,<br>
            Cuando modifica múltiples configuraciones (volumen, tipos, sonidos),<br>
            Entonces todos los cambios se guardan correctamente y se aplican inmediatamente.
        </td>
        <td>EP-002</td>
    </tr>
    <tr>
        <td>US-015</td>
        <td>Calibración Inicial de Postura</td>
        <td>Como usuario, quiere realizar una calibración inicial de su postura correcta para que el sistema reconozca su posición ideal al sentarse.</td>
        <td>
            <b>Escenario: Calibración exitosa</b><br>
            Dado que el usuario inicia el wizard de calibración,<br>
            Cuando mantiene una postura correcta durante 5 segundos,<br>
            Entonces el sistema registra esta posición como referencia para futuras comparaciones.
        </td>
        <td>EP-003</td>
    </tr>
    <tr>
        <td>US-016</td>
        <td>Ajuste de Sensibilidad de Detección</td>
        <td>Como usuario, quiere ajustar la sensibilidad del detector de espalda encorvada para personalizar qué tan estricto es el sistema con su postura.</td>
        <td>
            <b>Escenario: Ajuste de sensibilidad media</b><br>
            Dado que el usuario accede a configuraciones de sensibilidad,<br>
            Cuando mueve el slider a un nivel medio (50%),<br>
            Entonces el sistema se vuelve moderadamente estricto al detectar encorvamiento.
        </td>
        <td>EP-003</td>
    </tr>
    <tr>
        <td>US-017</td>
        <td>Ajuste de Frecuencia de Detección</td>
        <td>Como usuario, quiere controlar la frecuencia con la que el sistema analiza su postura para equilibrar precisión y rendimiento.</td>
        <td>
            <b>Escenario: Frecuencia moderada</b><br>
            Dado que el usuario necesita optimizar el rendimiento,<br>
            Cuando ajusta la frecuencia a "moderada" (2 segundos),<br>
            Entonces el sistema realiza chequeos posturales cada 2 segundos.
        </td>
        <td>EP-003</td>
    </tr>
    <tr>
        <td>US-018</td>
        <td>Restablecer Configuración Predeterminada</td>
        <td>Como usuario, quiere poder restablecer todos los ajustes a los valores predeterminados del sistema para comenzar de cero si es necesario.</td>
        <td>
            <b>Escenario: Reset completo</b><br>
            Dado que los ajustes actuales del usuario no funcionan correctamente,<br>
            Cuando restablece los valores predeterminados,<br>
            Entonces todos los parámetros de calibración vuelven a su estado original.
        </td>
        <td>EP-003</td>
    </tr>
    <tr>
        <td>US-020</td>
        <td>Panel Principal de Estadísticas</td>
        <td>Como usuario, quiere ver un dashboard con sus métricas principales de postura para tener una visión general de su progreso diario.</td>
        <td>
            <b>Escenario: Visualización de métricas</b><br>
            Dado que el usuario ha usado el sistema por más de 1 hora,<br>
            Cuando accede al panel principal,<br>
            Entonces ve porcentaje de postura correcta, tiempo total de uso y número de alertas recibidas.
        </td>
        <td>EP-004</td>
    </tr>
    <tr>
        <td>US-021</td>
        <td>Gráfico de Progreso Semanal</td>
        <td>Como usuario, quiere visualizar su evolución semanal mediante un gráfico de líneas para identificar tendencias en su mejora postural.</td>
        <td>
            <b>Escenario: Gráfico interactivo</b><br>
            Dado que el usuario tiene datos de varios días,<br>
            Cuando selecciona la vista "semanal",<br>
            Entonces se muestra un gráfico con su porcentaje de postura correcta por día de la semana.
        </td>
        <td>EP-004</td>
    </tr>
    <tr>
        <td>US-022</td>
        <td>Historial Detallado de Sesiones</td>
        <td>Como usuario, quiere revisar el historial completo de sus sesiones de trabajo para analizar su comportamiento postural a lo largo del tiempo.</td>
        <td>
            <b>Escenario: Filtrado por fecha</b><br>
            Dado que el usuario quiere ver sus datos de ayer,<br>
            Cuando selecciona la fecha en el calendario,<br>
            Entonces el sistema muestra sus estadísticas detalladas de postura para ese día específico.
        </td>
        <td>EP-004</td>
    </tr>
    <tr>
        <td>US-023</td>
        <td>Recordatorio de Pausas Activas</td>
        <td>Como usuario, quiere recibir recordatorios automáticos para tomar pausas activas cada cierto tiempo para prevenir la fatiga y mejorar su bienestar postural.</td>
        <td>
            <b>Escenario: Recordatorio cada 45 minutos</b><br>
            Dado que el usuario ha estado trabajando continuamente,<br>
            Cuando transcurren 45 minutos de actividad,<br>
            Entonces el sistema muestra una notificación sugiriendo una pausa activa de 5 minutos.
        </td>
        <td>EP-005</td>
    </tr>
    <tr>
        <td>US-024</td>
        <td>Personalización de Temporizador de Descansos</td>
        <td>Como usuario, quiere configurar la frecuencia y duración de sus pausas activas para adaptarlas a su flujo de trabajo y necesidades personales.</td>
        <td>
            <b>Escenario: Configurar pausas personalizadas</b><br>
            Dado que el usuario accede a la configuración de descansos,<br>
            Cuando establece pausas cada 30 minutos con duración de 7 minutos,<br>
            Entonces el sistema aplica estos nuevos intervalos para sus recordatorios.
        </td>
        <td>EP-005</td>
    </tr>
    <tr>
        <td>US-025</td>
        <td>Sugerencias de Ejercicios Generales</td>
        <td>Como usuario, quiere recibir sugerencias generales de ejercicios durante las pausas activas para realizar estiramientos básicos que beneficien su postura.</td>
        <td>
            <b>Escenario: Sugerencias aleatorias</b><br>
            Dado que el usuario ha iniciado una pausa activa,<br>
            Cuando el sistema muestra sugerencias de ejercicios,<br>
            Entonces presenta 3 opciones diferentes de estiramientos generales seleccionados aleatoriamente de un banco predefinido.
        </td>
        <td>EP-005</td>
    </tr>
    <tr>
        <td>US-026</td>
        <td>Registro de Nueva Cuenta</td>
        <td>Como usuario nuevo, quiere registrarse con su correo electrónico y contraseña para poder acceder a todas las funcionalidades de la aplicación.</td>
        <td>
            <b>Escenario 1: Registro exitoso</b><br>
            Dado que el usuario es nuevo,<br>
            Cuando completa el formulario con email válido y contraseña segura,<br>
            Entonces recibe un email de verificación y su cuenta queda creada en estado pendiente.<br>
            <b>Escenario 2: Email ya registrado</b><br>
            Dado que el usuario intenta registrarse con un email existente,<br>
            Cuando envía el formulario,<br>
            Entonces recibe un mensaje indicando que el email ya está registrado.
        </td>
        <td>EP-006</td>
    </tr>
    <tr>
        <td>US-027</td>
        <td>Verificación de Correo Electrónico</td>
        <td>Como usuario registrado, quiere verificar su dirección de correo electrónico para activar completamente su cuenta y asegurar su autenticidad.</td>
        <td>
            <b>Escenario: Verificación exitosa</b><br>
            Dado que el usuario se ha registrado y recibió el email de verificación,<br>
            Cuando hace clic en el enlace de verificación,<br>
            Entonces su cuenta se activa y puede iniciar sesión normalmente.
        </td>
        <td>EP-006</td>
    </tr>
    <tr>
        <td>US-028</td>
        <td>Inicio de Sesión</td>
        <td>Como usuario registrado, quiere iniciar sesión con sus credenciales para acceder a su perfil personalizado y datos de postura.</td>
        <td>
            <b>Escenario 1: Login exitoso</b><br>
            Dado que el usuario tiene una cuenta verificada,<br>
            Cuando ingresa sus credenciales correctas,<br>
            Entonces accede a su dashboard personal.<br>
            <b>Escenario 2: Credenciales incorrectas</b><br>
            Dado que el usuario ingresa contraseña incorrecta,<br>
            Cuando intenta iniciar sesión,<br>
            Entonces recibe un mensaje de error sin especificar si el error es en usuario o contraseña.
        </td>
        <td>EP-006</td>
    </tr>
    <tr>
        <td>US-029</td>
        <td>Recuperación de Contraseña</td>
        <td>Como usuario que olvidó su contraseña, quiere restablecerla mediante un enlace enviado a su email para recuperar el acceso a su cuenta.</td>
        <td>
            <b>Escenario: Restablecimiento exitoso</b><br>
            Dado que el usuario solicita restablecer su contraseña,<br>
            Cuando establece una nueva contraseña,<br>
            Entonces puede iniciar sesión con sus nuevas credenciales.
        </td>
        <td>EP-006</td>
    </tr>
    <tr>
        <td>US-030</td>
        <td>Edición de Perfil</td>
        <td>Como usuario registrado, quiere editar su información personal para mantener su perfil actualizado.</td>
        <td>
            <b>Escenario: Actualización de perfil</b><br>
            Dado que el usuario está en su perfil,<br>
            Cuando modifica su nombre y guarda los cambios,<br>
            Entonces los nuevos datos se almacenan correctamente y se muestran inmediatamente.
        </td>
        <td>EP-006</td>
    </tr>
    <tr>
        <td>US-031</td>
        <td>Gestión de Preferencias</td>
        <td>Como usuario, quiere configurar sus preferencias de notificaciones y privacidad para personalizar su experiencia en la aplicación.</td>
        <td>
            <b>Escenario: Cambio de preferencias</b><br>
            Dado que el usuario accede a configuración,<br>
            Cuando modifica sus preferencias de notificaciones,<br>
            Entonces los cambios se aplican inmediatamente en el sistema.
        </td>
        <td>EP-006</td>
    </tr>
        <tr>
        <td>TS-001</td>
        <td>Integración de MediaPipe Pose</td>
        <td>Como developer, quiero integrar la librería MediaPipe Pose en la aplicación web para poder detectar los 33 landmarks corporales en tiempo real.</td>
        <td>
            <b>Escenario: Detección exitosa de landmarks</b><br>
            Dado que la cámara está activa,<br>
            Cuando se inicializa MediaPipe Pose,<br>
            Entonces el sistema debe detectar continuamente los 33 puntos corporales con una tasa de frames mayor a 30fps.
        </td>
        <td>EP-001</td>
    </tr>
    <tr>
        <td>TS-002</td>
        <td>Manejo de Permisos de Cámara</td>
        <td>Como developer, quiero implementar el sistema de permisos de cámara del navegador para garantizar el acceso al video stream necesario para el análisis.</td>
        <td>
            <b>Escenario 1: Permiso concedido</b><br>
            Dado que el usuario inicia la aplicación,<br>
            Cuando solicita acceso a la cámara,<br>
            Entonces el navegador debe mostrar el diálogo de permisos y al aceptar, obtener el stream de video.<br>
            <b>Escenario 2: Permiso denegado</b><br>
            Dado que el usuario deniega el permiso,<br>
            Cuando se intenta acceder a la cámara,<br>
            Entonces el sistema debe mostrar un mensaje de error apropiado.
        </td>
        <td>EP-001</td>
    </tr>
    <tr>
        <td>TS-003</td>
        <td>Renderizado del Esqueleto en Canvas</td>
        <td>Como developer, quiero implementar el renderizado del esqueleto detectado sobre el video para visualizar los resultados del análisis postural.</td>
        <td>
            <b>Escenario: Visualización en tiempo real</b><br>
            Dado que MediaPipe detecta los landmarks,<br>
            Cuando se reciben los puntos corporales,<br>
            Entonces se debe dibujar un esqueleto semitransparente superpuesto al video con actualización continua.
        </td>
        <td>EP-001</td>
    </tr>
    <tr>
        <td>TS-004</td>
        <td>Algoritmo de Detección de Postura</td>
        <td>Como developer, quiero implementar los algoritmos de cálculo angular para determinar desviaciones posturales basado en los landmarks detectados.</td>
        <td>
            <b>Escenario: Cálculo de ángulos posturales</b><br>
            Dado que se tienen los landmarks corporales,<br>
            Cuando se calculan los ángulos de hombros, cadera y columna,<br>
            Entonces el sistema debe identificar correctamente posturas incorrectas según los umbrales definidos.
        </td>
        <td>EP-001</td>
    </tr>
    <tr>
        <td>TS-005</td>
        <td>Sistema de Alertas en Tiempo Real</td>
        <td>Como developer, quiero implementar el sistema de notificaciones visuales que se active inmediatamente al detectar posturas incorrectas.</td>
        <td>
            <b>Escenario: Activación de alerta visual</b><br>
            Dado que se detecta una postura incorrecta,<br>
            Cuando persiste por más de 3 segundos,<br>
            Entonces se debe mostrar una alerta visual no intrusiva en los bordes de la pantalla.
        </td>
        <td>EP-001</td>
    </tr>
    <tr>
        <td>TS-006</td>
        <td>Manejo de Estados de Monitoreo</td>
        <td>Como developer, quiero implementar el sistema de gestión de estados (activo/inactivo/pausado) para controlar el ciclo de vida del monitoreo.</td>
        <td>
            <b>Escenario: Cambio de estados</b><br>
            Dado que el usuario inicia una sesión,<br>
            Cuando cambia entre estados de monitoreo,<br>
            Entonces el sistema debe responder adecuadamente liberando o asignando recursos según sea necesario.
        </td>
        <td>EP-001</td>
    </tr>
    <tr>
        <td>TS-007</td>
        <td>Optimización de Rendimiento</td>
        <td>Como developer, quiero optimizar el rendimiento del procesamiento de video para garantizar un funcionamiento fluido sin consumo excesivo de CPU.</td>
        <td>
            <b>Escenario: Uso eficiente de recursos</b><br>
            Dado que la aplicación está en funcionamiento,<br>
            Cuando se procesa el video en tiempo real,<br>
            Entonces el uso de CPU no debe exceder el 30% en equipos de gama media.
        </td>
        <td>EP-001</td>
    </tr>
    <tr>
        <td>TS-008</td>
        <td>Manejo de Errores y Excepciones</td>
        <td>Como developer, quiero implementar un sistema robusto de manejo de errores para gestionar fallos en la detección o procesamiento de video.</td>
        <td>
            <b>Escenario: Recuperación de errores</b><br>
            Dado que ocurre un error en la detección,<br>
            Cuando el sistema falla temporalmente,<br>
            Entonces debe recuperarse automáticamente sin requerir intervención del usuario.
        </td>
        <td>EP-001</td>
    </tr>
       <tr>
        <td>TS-009</td>
        <td>Sistema de Alertas Visuales</td>
        <td>Como developer, quiero implementar un sistema de alertas visuales no intrusivas que se activen al detectar mala postura para proporcionar retroalimentación inmediata al usuario.</td>
        <td>
            <b>Escenario: Activación de borde coloreado</b><br>
            Dado que se detecta una postura incorrecta,<br>
            Cuando persiste por más de 3 segundos,<br>
            Entonces se debe mostrar un borde de color suave alrededor de la interfaz indicando el tipo de error.
        </td>
        <td>EP-002</td>
    </tr>
    <tr>
        <td>TS-010</td>
        <td>Reproducción de Sonidos Personalizados</td>
        <td>Como developer, quiero implementar un sistema de reproducción de sonidos personalizables para cada tipo de error postural que permita identificar problemas sin mirar la pantalla.</td>
        <td>
            <b>Escenario: Sonido específico por error</b><br>
            Dado que se configura un sonido para "encorvamiento",<br>
            Cuando se detecta este tipo de error postural,<br>
            Entonces se debe reproducir el sonido específico asignado.
        </td>
        <td>EP-002</td>
    </tr>
    <tr>
        <td>TS-011</td>
        <td>Control de Volumen de Alertas</td>
        <td>Como developer, quiero implementar un control de volumen ajustable para las alertas sonoras que permita adaptarse a diferentes entornos de trabajo.</td>
        <td>
            <b>Escenario: Ajuste de volumen personalizado</b><br>
            Dado que el usuario ajusta el volumen al 50%,<br>
            Cuando se activa una alerta sonora,<br>
            Entonces el sonido debe reproducirse al nivel de volumen configurado.
        </td>
        <td>EP-002</td>
    </tr>
    <tr>
        <td>TS-012</td>
        <td>Sistema de Preferencias de Alertas</td>
        <td>Como developer, quiero implementar un sistema de gestión de preferencias que permita habilitar/deshabilitar tipos específicos de alertas según las necesidades del usuario.</td>
        <td>
            <b>Escenario: Desactivación de alertas sonoras</b><br>
            Dado que el usuario desactiva las alertas sonoras,<br>
            Cuando se detecta una mala postura,<br>
            Entonces solo se deben mostrar alertas visuales sin reproducción de sonido.
        </td>
        <td>EP-002</td>
    </tr>
    <tr>
        <td>TS-013</td>
        <td>Modo Silencio Temporal</td>
        <td>Como developer, quiero implementar un sistema de modo silencio temporal que permita pausar todas las alertas durante periodos específicos.</td>
        <td>
            <b>Escenario: Silencio programado</b><br>
            Dado que se activa el modo silencio por 30 minutos,<br>
            Cuando se detecta cualquier error postural,<br>
            Entonces el sistema no debe emitir alertas visuales ni sonoras durante ese período.
        </td>
        <td>EP-002</td>
    </tr>
    <tr>
        <td>TS-014</td>
        <td>Panel de Configuración de Alertas</td>
        <td>Como developer, quiero crear un panel centralizado de configuración donde los usuarios puedan gestionar todas sus preferencias de notificaciones.</td>
        <td>
            <b>Escenario: Configuración múltiple</b><br>
            Dado que el usuario accede al panel de configuración,<br>
            Cuando modifica varias preferencias simultáneamente,<br>
            Entonces todos los cambios deben guardarse y aplicarse inmediatamente.
        </td>
        <td>EP-002</td>
    </tr>
    <tr>
        <td>TS-015</td>
        <td>Persistencia de Configuraciones</td>
        <td>Como developer, quiero implementar un sistema de almacenamiento local para guardar las preferencias de alertas y asegurar que persistan entre sesiones.</td>
        <td>
            <b>Escenario: Persistencia de configuraciones</b><br>
            Dado que el usuario configura sus preferencias,<br>
            Cuando cierra y reabre la aplicación,<br>
            Entonces todas las configuraciones deben mantenerse igual.
        </td>
        <td>EP-002</td>
    </tr>
    <tr>
        <td>TS-016</td>
        <td>Sincronización de Estados de Alerta</td>
        <td>Como developer, quiero implementar un sistema que sincronice el estado de las alertas entre diferentes componentes de la aplicación para evitar inconsistencia.</td>
        <td>
            <b>Escenario: Sincronización de estados</b><br>
            Dado que se activa una alerta visual,<br>
            Cuando el usuario cambia de pestaña o componente,<br>
            Entonces el estado de la alerta debe mantenerse consistente en toda la aplicación.
        </td>
        <td>EP-002</td>
    </tr>
    <tr>
        <td>TS-016</td>
        <td>Wizard de Calibración Inicial</td>
        <td>Como developer, quiero implementar un wizard interactivo que guíe al usuario en el proceso de calibración inicial para establecer su postura de referencia correcta.</td>
        <td>
            <b>Escenario: Calibración exitosa</b><br>
            Dado que el usuario inicia el wizard de calibración,<br>
            Cuando completa todos los pasos y mantiene una postura correcta durante 5 segundos,<br>
            Entonces el sistema guarda los parámetros de calibración como referencia para futuras comparaciones.
        </td>
        <td>EP-003</td>
    </tr>
    <tr>
        <td>TS-017</td>
        <td>Sistema de Control de Sensibilidad</td>
        <td>Como developer, quiero implementar un control deslizante ajustable que permita modificar la sensibilidad del detector de postura para adaptarse a las preferencias del usuario.</td>
        <td>
            <b>Escenario: Ajuste de sensibilidad</b><br>
            Dado que el usuario accede a la configuración de sensibilidad,<br>
            Cuando ajusta el slider a un valor específico (ej: 50%),<br>
            Entonces el sistema actualiza los umbrales de detección en tiempo real con el nuevo valor.
        </td>
        <td>EP-003</td>
    </tr>
    <tr>
        <td>TS-018</td>
        <td>Control de Frecuencia de Análisis</td>
        <td>Como developer, quiero implementar un selector de frecuencia que permita configurar el intervalo entre chequeos posturales para optimizar el rendimiento del sistema.</td>
        <td>
            <b>Escenario: Cambio de frecuencia</b><br>
            Dado que el usuario selecciona una frecuencia de 2 segundos,<br>
            Cuando guarda la configuración,<br>
            Entonces el sistema ajusta el intervalo de análisis postural a cada 2 segundos.
        </td>
        <td>EP-003</td>
    </tr>
    <tr>
        <td>TS-019</td>
        <td>Función de Restablecimiento de Configuración</td>
        <td>Como developer, quiero implementar una función que restablezca todas las configuraciones personalizadas a los valores predeterminados del sistema.</td>
        <td>
            <b>Escenario: Restablecimiento completo</b><br>
            Dado que el usuario tiene configuraciones personalizadas,<br>
            Cuando activa la opción "Restablecer valores predeterminados",<br>
            Entonces todas las configuraciones vuelven a su estado original de fábrica.
        </td>
        <td>EP-003</td>
    </tr>
    <tr>
        <td>TS-020</td>
        <td>Persistencia de Configuraciones de Usuario</td>
        <td>Como developer, quiero implementar un sistema de almacenamiento local para guardar las configuraciones de calibración y preferencias del usuario entre sesiones.</td>
        <td>
            <b>Escenario: Persistencia de datos</b><br>
            Dado que el usuario ajusta sus configuraciones,<br>
            Cuando cierra y reabre la aplicación,<br>
            Entonces todas las configuraciones personales se mantienen igual.
        </td>
        <td>EP-003</td>
    </tr>
    <tr>
        <td>TS-021</td>
        <td>API de Recolección de Datos de Postura</td>
        <td>Como developer, quiero implementar una API que capture y almacene los datos de postura en tiempo real para generar análisis históricos.</td>
        <td>
            <b>Escenario: Captura de datos exitosa</b><br>
            Dado que el sistema está monitoreando postura,<br>
            Cuando se detecta un evento postural (correcto/incorrecto),<br>
            Entonces los datos se almacenan con marca de tiempo en la base de datos.
        </td>
        <td>EP-004</td>
    </tr>
    <tr>
        <td>TS-022</td>
        <td>Sistema de Dashboard de Métricas</td>
        <td>Como developer, quiero desarrollar un sistema de dashboard que muestre métricas clave de postura en tiempo real para el usuario.</td>
        <td>
            <b>Escenario: Visualización de métricas principales</b><br>
            Dado que el usuario accede al dashboard,<br>
            Cuando hay datos de más de 1 hora de uso,<br>
            Entonces se muestran porcentaje de postura correcta, tiempo total y alertas recibidas.
        </td>
        <td>EP-004</td>
    </tr>
    <tr>
        <td>TS-023</td>
        <td>Gráficos Interactivos de Progreso</td>
        <td>Como developer, quiero implementar gráficos interactivos que muestren la evolución postural semanal para identificar tendencias de mejora.</td>
        <td>
            <b>Escenario: Generación de gráfico semanal</b><br>
            Dado que existen datos de varios días,<br>
            Cuando el usuario selecciona "vista semanal",<br>
            Entonces se genera un gráfico de líneas con el progreso diario de postura correcta.
        </td>
        <td>EP-004</td>
    </tr>
    <tr>
        <td>TS-024</td>
        <td>Sistema de Filtrado por Fechas</td>
        <td>Como developer, quiero implementar un sistema de filtrado que permita consultar el historial de sesiones por fechas específicas.</td>
        <td>
            <b>Escenario: Filtrado por fecha específica</b><br>
            Dado que el usuario quiere ver datos de ayer,<br>
            Cuando selecciona la fecha en el calendario,<br>
            Entonces el sistema muestra solo las estadísticas de ese día.
        </td>
        <td>EP-004</td>
    </tr>
    <tr>
        <td>TS-025</td>
        <td>Exportación de Reportes</td>
        <td>Como developer, quiero implementar funcionalidad de exportación de datos para permitir generar reportes en formatos comunes.</td>
        <td>
            <b>Escenario: Exportación a CSV</b><br>
            Dado que el usuario quiere exportar sus datos,<br>
            Cuando selecciona "Exportar a CSV",<br>
            Entonces se genera y descarga un archivo con todos sus datos históricos.
        </td>
        <td>EP-004</td>
    </tr>
    <tr>
        <td>TS-026</td>
        <td>Sistema de Temporizador de Pausas Activas</td>
        <td>Como developer, quiero implementar un sistema de temporizador que active recordatorios de pausas activas basado en intervalos configurables para promover hábitos saludables.</td>
        <td>
            <b>Escenario: Recordatorio automático</b><br>
            Dado que el usuario ha estado activo por 45 minutos,<br>
            Cuando se cumple el intervalo configurado,<br>
            Entonces el sistema muestra una notificación sugiriendo una pausa activa.
        </td>
        <td>EP-005</td>
    </tr>
    <tr>
        <td>TS-027</td>
        <td>Configuración Personalizada de Intervalos</td>
        <td>Como developer, quiero implementar un sistema de configuración que permita personalizar la frecuencia y duración de las pausas activas según preferencias del usuario.</td>
        <td>
            <b>Escenario: Personalización de intervalos</b><br>
            Dado que el usuario configura pausas cada 30 minutos,<br>
            Cuando guarda la configuración,<br>
            Entonces el sistema programa los recordatorios con el nuevo intervalo.
        </td>
        <td>EP-005</td>
    </tr>
    <tr>
        <td>TS-028</td>
        <td>Banco de Ejercicios de Estiramiento</td>
        <td>Como developer, quiero crear un banco de ejercicios de estiramiento con instrucciones visuales que pueda ser accedido durante las pausas activas.</td>
        <td>
            <b>Escenario: Selección aleatoria de ejercicios</b><br>
            Dado que el usuario inicia una pausa activa,<br>
            Cuando solicita sugerencias de ejercicios,<br>
            Entonces el sistema muestra 3 opciones diferentes del banco de ejercicios.
        </td>
        <td>EP-005</td>
    </tr>
    <tr>
        <td>TS-029</td>
        <td>Sistema de Notificaciones de Bienestar</td>
        <td>Como developer, quiero implementar un sistema de notificaciones no intrusivas que muestre recordatorios de pausas y sugerencias de ejercicios.</td>
        <td>
            <b>Escenario: Notificación de pausa</b><br>
            Dado que se cumple el intervalo programado,<br>
            Cuando el sistema está activo,<br>
            Entonces se muestra una notificación suave sugiriendo una pausa activa.
        </td>
        <td>EP-005</td>
    </tr>
    <tr>
        <td>TS-030</td>
        <td>Gestor de Rutinas de Estiramiento</td>
        <td>Como developer, quiero desarrollar un sistema que gestione y roté las rutinas de estiramiento para evitar repetir los mismos ejercicios consecutivamente.</td>
        <td>
            <b>Escenario: Rotación de ejercicios</b><br>
            Dado que el usuario ha realizado varios ejercicios,<br>
            Cuando inicia una nueva pausa activa,<br>
            Entonces el sistema sugiere ejercicios no recientemente mostrados.
        </td>
        <td>EP-005</td>
    </tr>
    <tr>
        <td>TS-031</td>
        <td>Sistema de Registro de Usuarios</td>
        <td>Como developer, quiero implementar un sistema de registro seguro que valide credenciales y envíe emails de verificación para crear nuevas cuentas de usuario.</td>
        <td>
            <b>Escenario 1: Registro exitoso</b><br>
            Dado que un nuevo usuario completa el formulario,<br>
            Cuando los datos son válidos y el email no existe,<br>
            Entonces se crea la cuenta y se envía email de verificación.<br>
            <b>Escenario 2: Email duplicado</b><br>
            Dado que un usuario intenta registrarse con email existente,<br>
            Cuando envía el formulario,<br>
            Entonces el sistema muestra error de email ya registrado.
        </td>
        <td>EP-006</td>
    </tr>
    <tr>
        <td>TS-032</td>
        <td>Sistema de Verificación de Email</td>
        <td>Como developer, quiero implementar un sistema de verificación por email que valide la autenticidad de las cuentas mediante tokens seguros.</td>
        <td>
            <b>Escenario: Verificación exitosa</b><br>
            Dado que el usuario recibe el email de verificación,<br>
            Cuando hace clic en el enlace con token válido,<br>
            Entonces la cuenta se activa y puede iniciar sesión.
        </td>
        <td>EP-006</td>
    </tr>
    <tr>
        <td>TS-033</td>
        <td>Sistema de Autenticación</td>
        <td>Como developer, quiero implementar un sistema de login seguro que valide credenciales y maneje sesiones de usuario.</td>
        <td>
            <b>Escenario 1: Login exitoso</b><br>
            Dado que el usuario ingresa credenciales correctas,<br>
            Cuando el sistema valida la información,<br>
            Entonces se inicia sesión y redirige al dashboard.<br>
            <b>Escenario 2: Credenciales inválidas</b><br>
            Dado que el usuario ingresa credenciales incorrectas,<br>
            Cuando el sistema valida la información,<br>
            Entonces muestra error genérico sin especificar el campo erróneo.
        </td>
        <td>EP-006</td>
    </tr>
    <tr>
        <td>TS-034</td>
        <td>Sistema de Recuperación de Contraseña</td>
        <td>Como developer, quiero implementar un sistema seguro de recuperación de contraseña que genere tokens temporales y permita restablecer credenciales.</td>
        <td>
            <b>Escenario: Recuperación exitosa</b><br>
            Dado que el usuario solicita restablecer contraseña,<br>
            Cuando sigue el enlace del email y establece nueva contraseña,<br>
            Entonces puede iniciar sesión con las nuevas credenciales.
        </td>
        <td>EP-006</td>
    </tr>
    <tr>
        <td>TS-035</td>
        <td>API de Gestión de Perfil</td>
        <td>Como developer, quiero implementar una API para gestionar perfiles de usuario que permita editar y actualizar información personal.</td>
        <td>
            <b>Escenario: Actualización de perfil</b><br>
            Dado que el usuario modifica su información,<br>
            Cuando guarda los cambios,<br>
            Entonces los datos se actualizan inmediatamente en la base de datos.
        </td>
        <td>EP-006</td>
    </tr>
    <tr>
        <td>TS-036</td>
        <td>Sistema de Preferencias de Usuario</td>
        <td>Como developer, quiero implementar un sistema de gestión de preferencias que almacene y recupere configuraciones personalizadas.</td>
        <td>
            <b>Escenario: Cambio de preferencias</b><br>
            Dado que el usuario modifica sus preferencias,<br>
            Cuando guarda los cambios,<br>
            Entonces las configuraciones se aplican inmediatamente y persisten entre sesiones.
        </td>
        <td>EP-006</td>
    </tr>
    <tr>
        <td>TS-037</td>
        <td>Manejo de Sesiones Seguras</td>
        <td>Como developer, quiero implementar un sistema de manejo de sesiones con tokens JWT seguros y renovación automática.</td>
        <td>
            <b>Escenario: Sesión segura</b><br>
            Dado que el usuario inicia sesión,<br>
            Cuando navega por la aplicación,<br>
            Entonces la sesión se mantiene activa y segura con token JWT.
        </td>
        <td>EP-006</td>
    </tr>
  </tbody>
</table>

### 3.3 Impact Mapping

<img src="../report/images/chapter-3/impact-mapping.png" alt="Impact Mapping">

### 3.4 Product Backlog

| **Prioridad** | **Story ID** | **Título**                                    | **Descripción**                                                                                                   | **SP** |
| ------------- | ------------ | --------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- | ------ |
| 1             | US-001       | Acceso a la Cámara                            | Como usuario, quiere permitir el acceso a su cámara web para que el sistema pueda comenzar a analizar su postura. | 5      |
| 4             | US-002       | Visualización del Esqueleto en Tiempo Real    | Como usuario, quiere ver una superposición del esqueleto detectado sobre su imagen de video.                      | 8      |
| 1             | US-003       | Detección de Postura Encorvada                | Como usuario, quiere que el sistema detecte automáticamente cuando sus hombros están encorvados.                  | 8      |
| 1             | US-004       | Detección de Proximidad a la Pantalla         | Como usuario, quiere que el sistema le alerte cuando su rostro está demasiado cerca de la pantalla.               | 8      |
| 2             | US-005       | Detección de Inclinación de Cabeza            | Como usuario, quiere que el sistema detecte si su cabeza no está en posición neutral.                             | 8      |
| 4             | US-006       | Toggle de Visualización de Esqueleto          | Como usuario, quiere poder activar o desactivar la visualización del esqueleto.                                   | 5      |
| 5             | US-007       | Detección de Ángulo Brazo-Antebrazo           | Como usuario, quiere que el sistema verifique el ángulo de su codo para prevenir lesiones.                        | 8      |
| 3             | US-008       | Detección de Alineación Pierna-Cadera-Espalda | Como usuario, quiere que el sistema monitoree el ángulo entre muslos, cadera y hombros.                           | 8      |
| 1             | US-009       | Alertas Visuales para Mala Postura            | Como usuario, quiere recibir alertas visuales no intrusivas cuando su postura es incorrecta.                      | 5      |
| 3             | US-010       | Alertas Sonoras Personalizables               | Como usuario, quiere asignar sonidos diferentes para cada tipo de error postural.                                 | 5      |
| 3             | US-011       | Personalización de Volumen de Alertas         | Como usuario, quiere ajustar el volumen de las alertas sonoras.                                                   | 3      |
| 2             | US-012       | Selección de Alertas Activas                  | Como usuario, quiere elegir qué tipos de alertas quiere recibir.                                                  | 5      |
| 3             | US-013       | Modo Silencio Temporal                        | Como usuario, quiere pausar temporalmente todas las alertas.                                                      | 5      |
| 3             | US-014       | Panel de Gestión de Alertas                   | Como usuario, quiere acceder a un panel para gestionar preferencias de notificaciones.                            | 8      |
| 1             | US-015       | Calibración Inicial de Postura                | Como usuario, quiere realizar una calibración inicial de su postura correcta.                                     | 5      |
| 2             | US-016       | Ajuste de Sensibilidad de Detección           | Como usuario, quiere ajustar la sensibilidad del detector de postura.                                             | 5      |
| 5             | US-017       | Ajuste de Frecuencia de Detección             | Como usuario, quiere controlar la frecuencia del análisis postural.                                               | 5      |
| 1             | US-018       | Restablecer Configuración Predeterminada      | Como usuario, quiere restablecer todos los ajustes a valores predeterminados.                                     | 3      |
| 2             | US-020       | Panel Principal de Estadísticas               | Como usuario, quiere ver un dashboard con métricas principales de postura.                                        | 8      |
| 2             | US-021       | Gráfico de Progreso Semanal                   | Como usuario, quiere visualizar su evolución semanal en un gráfico.                                               | 5      |
| 3             | US-022       | Historial Detallado de Sesiones               | Como usuario, quiere revisar el historial completo de sus sesiones.                                               | 8      |
| 2             | US-023       | Recordatorio de Pausas Activas                | Como usuario, quiere recibir recordatorios automáticos de pausas.                                                 | 5      |
| 2             | US-024       | Personalización de Temporizador de Descansos  | Como usuario, quiere configurar frecuencia y duración de pausas.                                                  | 5      |
| 3             | US-025       | Sugerencias de Ejercicios Generales           | Como usuario, quiere recibir sugerencias de ejercicios durante pausas.                                            | 3      |
| 4             | US-026       | Registro de Nueva Cuenta                      | Como usuario nuevo, quiere registrarse con su correo y contraseña.                                                | 5      |
| 2             | US-027       | Verificación de Correo Electrónico            | Como usuario, quiere verificar su correo electrónico para activar su cuenta.                                      | 3      |
| 4             | US-028       | Inicio de Sesión                              | Como usuario, quiere iniciar sesión con sus credenciales.                                                         | 5      |
| 3             | US-029       | Recuperación de Contraseña                    | Como usuario, quiere restablecer su contraseña olvidada.                                                          | 5      |
| 4             | US-030       | Edición de Perfil                             | Como usuario, quiere editar su información personal.                                                              | 3      |
| 4             | US-031       | Gestión de Preferencias                       | Como usuario, quiere configurar sus preferencias de notificaciones y privacidad.                                  | 5      |

## Capítulo IV: Strategic-Level Software Design

### 4.1 Strategic-Level Attribute-Driven Design

#### 4.1.1 Design Purpose

#### 4.1.2 Attribute-Driven Design Inputs

##### 4.1.2.1 Primary Functionality (Primary User Stories)

##### 4.1.2.2 Quality attribute Scenarios

##### 4.1.2.3 Constraints

#### 4.1.3 Architectural Drivers Backlog

#### 4.1.4 Architectural Design Decisions

#### 4.1.5 Quality Attribute Scenario Refinements

### 4.2 Strategic-Level Domain-Driven Design

#### 4.2.1 EventStorming

#### 4.2.2 Candidate Context Discovery

#### 4.2.3 Domain Message Flows Modeling

#### 4.2.4 Bounded Context Canvases

#### 4.2.5 Context Mapping

### 4.3 Software Architecture

#### 4.3.1 Software Architecture System Landscape Diagram

#### 4.3.2 Software Architecture Context Level Diagrams

#### 4.3.3 Software Architecture Container Level Diagrams

#### 4.3.4 Software Architecture Deployment Diagrams

![nrg7-deployment.png](images/chapter-4/nrg7-deployment.png)

## Conclusiones

## Bibliografía

## Anexos
