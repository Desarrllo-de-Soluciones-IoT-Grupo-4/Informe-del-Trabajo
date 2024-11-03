<h2>Universidad Peruana de Ciencias Aplicadas</h2>

<img src="https://seeklogo.com/images/U/universidad-peruana-de-ciencias-aplicadas-upc-logo-B98C3A365C-seeklogo.com.png" alt="UPC Logo" width="15%" height="15%">

<h2>Informe del Trabajo Final</h2>

<h3>Carrera: Ingeniería de Software </h3>
<h3>Ciclo: 2024-02</h3>
<h3>Curso: Desarrollo de Soluciones IoT</h3>
<h3>Sección: WX71</h3>
<h3>Profesor: Marco Antonio León Baca</h3>

<h3>Startup: NewMinds</h3>

<h3>Producto: MedSync</h3>

<h3>Integrantes:</h3>

<ul>
  <li>Alonso Fernando Robles Astuñaupa (u202112662)</li>
  <li>Erick Armando Cueva Elera (u201910151)</li>
  <li>Erick Gabriel Urbizagastegui Alvarez (u20201e465)</li>
  <li>Mijael Alexander Imanol Yen Quispe (u202010305)</li>
  <li>William Ramos Vicente (u202117904)</li>
</ul>

**<h3>Noviembre, 2024</h3>**

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
|--------------|--------------|--------------|--------------|
| 1           | 05/09/2024      | - Alonso Fernando Robles Astuñaupa<br>- Erick Armando Cueva Elera<br>- Erick Gabriel Urbizagastegui Alvarez<br>- Mijael Alexander Imanol Yen Quispe<br>- William Ramos Vicente    | Implementación del capítulo 1 al 4      |
| 2           | 25/09/2024      | - Alonso Fernando Robles Astuñaupa<br>- Erick Armando Cueva Elera<br>- Erick Gabriel Urbizagastegui Alvarez<br>- Mijael Alexander Imanol Yen Quispe<br>- William Ramos Vicente    | Implementación del capítulo 5 y 6. Correcciones de la entrega pasada.      |
| 3           | 02/11/2024      | - Alonso Fernando Robles Astuñaupa<br>- Erick Armando Cueva Elera<br>- Erick Gabriel Urbizagastegui Alvarez<br>- Mijael Alexander Imanol Yen Quispe<br>- William Ramos Vicente    | Implementación del sprint 2. Correcciones de la entrega pasada.      |

# Contenido

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [Startup Profile](#startup-profile)
    - [Descripción de la Startup](#descripción-de-la-startup)
    - [Perfiles de integrantes del equipo](#perfiles-de-integrantes-del-equipo)
  - [Solution Profile](#solution-profile)
    - [Antecedentes y problemática](#antecedentes-y-problemática)
    - [Lean UX Process](#lean-ux-process)
      - [Lean UX Problem Statements](#lean-ux-problem-statements)
      - [Lean UX Assumptions](#lean-ux-assumptions)
      - [Lean UX Hypothesis Statements](#lean-ux-hypothesis-statements)
      - [Lean UX Canvas](#lean-ux-canvas)
  - [Segmentos objetivo](#segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [Competidores](#competidores)
    - [Análisis competitivo](#análisis-competitivo)
    - [Estrategias y tácticas frente a competidores](#estrategias-y-tácticas-frente-a-competidores)
  - [Entrevistas](#entrevistas)
    - [Diseño de entrevistas](#diseño-de-entrevistas)
    - [Registro de entrevistas](#registro-de-entrevistas)
    - [Análisis de entrevistas](#análisis-de-entrevistas)
  - [Needfinding](#needfinding)
    - [User Personas](#user-personas)
    - [User Task Matrix](#user-task-matrix)
    - [User Journey Mapping](#user-journey-mapping)
    - [Empathy Mapping](#empathy-mapping)
    - [As-is Scenario Mapping](#as-is-scenario-mapping)
  - [Ubiquitous Language](#ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [To-Be Scenario Mapping](#to-be-scenario-mapping)
    - [User Stories](#user-stories)
    - [Impact Mapping](#impact-mapping)
    - [Product Backlog](#product-backlog)
- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
  - [Strategic-Level Attribute-Driven Design](#strategic-level-attribute-driven-design)
    - [Event Storming](#event-storming)
      - [Candidate Context Discovery](#candidate-context-discovery)
      - [Domain Message Flows Modeling](#domain-message-flows-modeling)
      - [Bounded Context Canvases](#bounded-context-canvases)
    - [Context Mapping](#context-mapping)
    - [Software Architecture](#software-architecture)
      - [Software Architecture System Landscape Diagram](#software-architecture-system-landscape-diagram)
      - [Software Architecture Context Level Diagrams](#software-architecture-context-level-diagrams)
      - [Software Architecture Container Level Diagrams](#software-architecture-container-level-diagrams)
      - [Software Architecture Deployment Diagrams](#software-architecture-deployment-diagrams)
  - [Tactical-Level Domain-Driven Design](#tactical-level-domain-driven-design)
    - [Bounded Context: Authentication](#bounded-context-authentication)
      - [Domain Layer](#domain-layer)
      - [Interface Layer](#interface-layer)
      - [Application Layer](#application-layer)
      - [Infrastructure Layer](#infrastructure-layer)
      - [Bounded Context Software Architecture Component Level Diagrams](#bounded-context-software-architecture-component-level-diagrams)
      - [Bounded Context Software Architecture Code Level Diagrams](#bounded-context-software-architecture-code-level-diagrams)
        - [Bounded Context Domain Layer Class Diagram](#bounded-context-domain-layer-class-diagram)
        - [Bounded Context Database Design Diagram](#bounded-context-database-design-diagram)
- [Solution UI/UX Design](#solution-uiux-design)
  - [Style Guidelines](#style-guidelines)
    - [General Style Guidelines](#general-style-guidelines)
    - [Web, Mobile and IOT Style Guidelines](#web-mobile-and-iot-style-guidelines)
  - [Information Architecture](#information-architecture)
    - [Organization Systems](#organization-systems)
    - [Labeling Systems](#labeling-systems)
    - [SEO Tags and Meta Tags](#seo-tags-and-meta-tags)
    - [Navigations Systems](#navigations-systems)
    - [Searching Systems](#searching-systems)
  - [Landing Page UI](#landing-page-ui)
    - [Landing Page Wireframe](#landing-page-wireframe)
    - [Landing Page Mock-up](#landing-page-mock-up)
  - [Applications UX/UI Design](#applications-uxui-design)
    - [Applications Wireframes](#applications-wireframes)
    - [Applications Wireflow Diagram](#applications-wireflow-diagram)
    - [Applications Mock-ups](#applications-mock-ups)
    - [Applications User Flow Diagrams](#applications-user-flow-diagrams)
  - [Applications Prototyping](#applications-prototyping)
- [Product Implementation, Validation \& Deployment](#product-implementation-validation--deployment)
  - [Software Configuration Management](#software-configuration-management)
    - [Software Development Environment Configuration](#software-development-environment-configuration)
    - [Source Code Management](#source-code-management)
    - [Source Code Style Guide \& Conventions](#source-code-style-guide--conventions)
    - [Software Deployment Configuration](#software-deployment-configuration)
  - [Landing Page, Services \& Applications Implementation](#landing-page-services--applications-implementation)
    - [Aprint 1](#aprint-1)
      - [Sprint Planning 1](#sprint-planning-1)
      - [Sprint Backlog 1](#sprint-backlog-1)
      - [Development Evidence for Sprint Review](#development-evidence-for-sprint-review)
      - [Testing Suite Evidence for Sprint Review](#testing-suite-evidence-for-sprint-review)
      - [Execution Evidence for Sprint Review](#execution-evidence-for-sprint-review)
      - [Services Documentation Evidence for Sprint Review](#services-documentation-evidence-for-sprint-review)
      - [Software Deployment Evidence for Sprint Review](#software-deployment-evidence-for-sprint-review)
      - [Team Collaboration Insights during Sprint](#team-collaboration-insights-during-sprint)
    - [Sprint 2](#sprint-2)
      - [Sprint Planning 2](#sprint-planning-2)
      - [Sprint Backlog 2](#sprint-backlog-2)
      - [Development Evidence for Sprint Review](#development-evidence-for-sprint-review-1)
      - [Testing Suite Evidence for Sprint Review](#testing-suite-evidence-for-sprint-review-1)
      - [Execution Evidence for Sprint Review](#execution-evidence-for-sprint-review-1)
      - [Services Documentation Evidence for Sprint Review](#services-documentation-evidence-for-sprint-review-1)
      - [Software Deployment Evidence for Sprint Review](#software-deployment-evidence-for-sprint-review-1)
      - [Team Collaboration Insights during Sprint](#team-collaboration-insights-during-sprint-1)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

# Student Outcome

| Criterio Específico | Acciones realizadas | Conclusiones |
|---------|---------|---------|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta | **TB1**<br><br>*Alonso Robles*<br><br>Elabore los as y to be scenario mapping<br><br>*Erick Armando Cueva Elera*<br><br>Elaboré los user persona<br><br>*Erick Gabriel Urbizagastegui Alvarez*<br><br>Elaboré la arquitectura de la solución<br><br>*Mijael Alexander Imanol Yen Quispe*<br><br>Elaboré los diagramas de bounded contexts y entrevistas<br><br>*William Ramos Vicente*<br><br>Elaboré el diseño de las entrevistas y su análisis<br><br>**TP1**<br><br>*Alonso Robles*<br><br>Elaboré los style guidelines y software configuration management.<br><br>*Erick Armando Cueva Elera*<br><br>Elabore el sprint backlog<br><br>*Erick Gabriel Urbizagastegui Alvarez*<br><br>Elaboré la Landing Page<br><br>*Mijael Alexander Imanol Yen Quispe*<br><br>Elaboré los mockups y wireframes<br><br>*William Ramos Vicente*<br><br>Corregir la arquitectura de software (base de datos y diagramas de clases)<br><br>**TB2**<br><br>*Alonso Robles*<br><br>Elaboré el apartado de perfil de usuario de la app web.<br><br>*Erick Armando Cueva Elera*<br><br>Elaboré la mobile app.<br><br>*Erick Gabriel Urbizagastegui Alvarez*<br><br>Elaboré el login y el home de la web app.<br><br>*Mijael Alexander Imanol Yen Quispe*<br><br>Elaboré la documentación del proyecto.<br><br>*William Ramos Vicente*<br><br>Elaboré el backend de MedSync.<br><br>| **TB1**<br><br>Se planteó la problemática y el giro del negocio. Para esto investigamos acerca del estado actual de esta problemática, identificamos segmentos objetivo y los entrevistamos para obtener sus opiniones.<br><br>**TP1**<br><br>Se desarrolló el diseño de la aplicación más el Landing page de esta misma.<br><br>**TB2**<br><br>Se empezó con el desarrollo de la web app, mobile app y backend.|
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. | **TB1**<br><br>*Alonso Robles*<br><br>Elabore los as y to be scenario mapping<br><br>*Erick Armando Cueva Elera*<br><br>Elaboré los user persona<br><br>*Erick Gabriel Urbizagastegui Alvarez*<br><br>Elaboré la arquitectura de la solución<br><br>*Mijael Alexander Imanol Yen Quispe*<br><br>Elaboré los diagramas de bounded contexts y entrevistas<br><br>*William Ramos Vicente*<br><br>Elaboré el diseño de las entrevistas y su análisis<br><br>**TP1**<br><br>*Alonso Robles*<br><br>Elaboré los style guidelines y software configuration management.<br><br>*Erick Armando Cueva Elera*<br><br>Elabore el sprint backlog<br><br>*Erick Gabriel Urbizagastegui Alvarez*<br><br>Elaboré la Landing Page<br><br>*Mijael Alexander Imanol Yen Quispe*<br><br>Elaboré los mockups y wireframes<br><br>*William Ramos Vicente*<br><br>Corregir la arquitectura de software (base de datos y diagramas de clases)<br><br>**TB2**<br><br>*Alonso Robles*<br><br>Elaboré el apartado de perfil de usuario de la app web.<br><br>*Erick Armando Cueva Elera*<br><br>Elaboré la mobile app.<br><br>*Erick Gabriel Urbizagastegui Alvarez*<br><br>Elaboré el login y el home de la web app.<br><br>*Mijael Alexander Imanol Yen Quispe*<br><br>Elaboré la documentación del proyecto.<br><br>*William Ramos Vicente*<br><br>Elaboré el backend de MedSync.<br><br>| **TB1**<br><br>Se planteó la problemática y el giro del negocio. Para esto investigamos acerca del estado actual de esta problemática, identificamos segmentos objetivo y los entrevistamos para obtener sus opiniones.<br><br>**TP1**<br><br>Se desarrolló el diseño de la aplicación más el Landing page de esta misma.<br><br>**TB2**<br><br>Se empezó con el desarrollo de la web app, mobile app y backend.|

# Capítulo I: Introducción

## Startup Profile

### Descripción de la Startup

MedSync es una startup dedicada al desarrollo de soluciones IoT para la monitorización y gestión de la salud de sus usuarios. Nuestras soluciones utilizan herramientas altamente precisas para proporcionar datos exactos y en tiempo real, con el objetivo de mejorar el cuidado de los pacientes.

**Misión**

Empoderar a los profesionales de la salud y pacientes mediante soluciones IoT que faciliten la monitorización continua, promoviendo un cuidado preventivo y eficiente.

**Visión**

Convertirse en el líder global en soluciones médicas IoT, transformando el enfoque del cuidado de la salud con soluciones innovadoras que mejoren la calidad de vida de sus usuarios.


### Perfiles de integrantes del equipo

**Alonso Fernando Robles Astuñaupa (u202112662)**

![Imgur](https://i.gyazo.com/7a4f341fc6efabd042029bb98f091bf1.png)

**Erick Armando Cueva Elera (u201910151)**

![Imgur](https://gyazo.com/91be7877d088730e61825d23ac615210.png)

**Erick Gabriel Urbizagastegui Alvarez (u20201e465)**

![Imgur](https://gyazo.com/95efd96cf1a3b0392ee5396c5132b4b1.png)

**Mijael Alexander Imanol Yen Quispe (u202010305)**

![Imgur](https://gyazo.com/ca08a85f2148fc42e011a5fe96ebbfcc.png)

**William Ramos Vicente (u202117904)**

![Imgur](https://gyazo.com/526824617254222d1375b2247b950ac0.png)

## Solution Profile

### Antecedentes y problemática

Actualmente, la gestión de la salud relacionada al corazón suele depender de visitas periódicas al médico para medir el ritmo cardíaco, lo que implica que los datos obtenidos reflejan solo momentos específicos en ese momento de la revisión. Esta metodología no captura las variaciones diarias del ritmo cardíaco, lo que limita la capacidad de los médicos para detectar patrones o problemas futuros. Además, las visitas regulares pueden interrumpir la rutina diaria del paciente, conllevando un coste monetario y de tiempo. Como resultado, se pierde la oportunidad de una monitorización continua y precisa, lo que puede afectar negativamente la calidad del cuidado y la salud del paciente.

**Who ¿Quiénes van a ser los beneficiarios?**
  
A este problema se enfrentan pacientes con condiciones cardíacas y los contactos de emergencia de estos, quienes serán alertados si el ritmo cardiaco del paciente es inusual.

**What ¿Cuál es el problema?**

El problema es la falta de monitorización continua del ritmo cardíaco, lo que limita la capacidad de detectar problemas emergentes y hacer ajustes proactivos en el tratamiento.

**Where ¿Dónde se originó el problema?**
  
El problema se origina en la vida cotidiana de personas con riesgos cardiacos.

**When ¿Cuándo se originó el problema?**

El problema se presenta durante los períodos entre visitas médicas, cuando el ritmo cardíaco no es monitoreado en tiempo real, lo que puede ocurrir a lo largo del día y a lo largo del tiempo entre consultas.

**Why ¿Por qué se originó el problema?**

Sucede porque el monitoreo tradicional se basa en visitas médicas puntuales que no pueden capturar las variaciones diarias en el ritmo cardíaco, limitando la capacidad para detectar problemas emergentes y hacer intervenciones tempranas.

**How ¿Cómo debe hacerse?**

El problema se diferencia del estado óptimo porque los datos sobre el ritmo cardíaco no están disponibles en tiempo real y solo se obtienen de manera esporádica. La falta de datos continuos impide la identificación de patrones o tendencias en el ritmo cardíaco del paciente.

**How Much ¿Cómo el costo influye en la problemática?**

La frecuencia de problemas varía, pero puede incluir numerosos casos de eventos cardíacos no detectados hasta las siguientes visitas médicas, con un impacto significativo en la salud del paciente y costos adicionales en atención médica. Aunque los datos exactos pueden variar, el costo incluye gastos por visitas médicas adicionales, pruebas y potenciales emergencias, lo que puede sumar a miles de dólares anualmente.

### Lean UX Process

#### Lean UX Problem Statements

Como equipo, analizamos la problemática que trataremos y generamos la siguiente pregunta:

***¿Como podemos facilitar el monitoreo constante del ritmo cardiaco de una persona?***

#### Lean UX Assumptions

**Business Outcomes**  

- Creo que mis clientes necesitan un dispositivo que les permita monitorizar su ritmo cardíaco de forma continua y en tiempo real.
- Mis clientes iniciales son personas con condiciones cardíacas que buscan una solución para monitorear su salud de manera constante y accesible.
- Voy a adquirir a la mayoría de mis clientes a través de asociaciones con clínicas, hospitales y campañas de concienciación sobre salud cardiovascular.
- El valor número uno que mi cliente espera de mi servicio es obtener un monitoreo continuo y preciso de su ritmo cardíaco para una gestión más efectiva de su salud.
- Voy a hacer dinero a partir de la venta del dispositivo y una suscripción premium para características avanzadas y soporte adicional.
- Mi competencia principal en el mercado son otros dispositivos de monitoreo cardíaco que ofrecen seguimiento puntual, pero no continuo ni tan integrado con aplicaciones móviles.
- Mi mayor posibilidad de riesgo es que el sensor no proporcione datos precisos o que la aplicación no sea intuitiva para los usuarios.

**User Outcomes**  

- **¿Quién es el usuario?**  
Personas que sufren reisgos cardiacos y sus contactos de emergencia
- **¿Dónde encaja nuestro producto? ¿En su trabajo o vida?**  
En su vida, ya que en cualquier momento pueden sufrir una complicación cardiaca.
- **¿Qué problemas tiene nuestro producto y cómo se pueden resolver?**  
El mayor problema es lograr que el contacto de emergencia se entere que el usuario principal está teniendo una complicación cardiaca. Esto se resolverá mediante notificaciones inmediatas en caso se de una situación como la mencionada.
- **¿Cuándo y cómo es usado nuestro producto?**  
La solución será usada periódicamente durante el día por la persona con riesgo cardiaco. Dicha persona deberá colocar su dedo en el dispositivo y esto automáticamente hará el resto del proceso.
- **¿Qué características son importantes?**  
Medición del ritmo cardiaco; notificaciones a contactos de emergencia y facilidad de uso.
- **¿Cómo debe verse nuestro producto y cómo debe comportarse?**  
Debe verse como un aparato sencillo de usar, con un diseño intuitivo que de a entender al usuario en donde debe insertar su dedo índice. Asimismo, debe enviar notificaciones en tiempo real a los contactos de emergencia para que estos se enteren del estado del usuario principal.

#### Lean UX Hypothesis Statements

**Hipótesis 1**  
Creemos que nuestro sensor cardíaco IoT ayudará a los pacientes a monitorear su ritmo cardíaco de forma continua y en tiempo real, mejorando la gestión de su salud cardiovascular. Sabremos que el dispositivo tuvo éxito si los pacientes reportan una mejora en el manejo de su salud cuando veamos que los pacientes utilizan regularmente el dispositivo y proporcionan retroalimentación positiva sobre la precisión de los datos y la facilidad de uso.

**Hipótesis 2**  
Creemos que una integración fluida entre el sensor y la aplicación móvil permitirá a los usuarios recibir alertas y recomendaciones personalizadas, lo que optimizará la gestión de su salud cardiovascular. Sabremos que la integración fue exitosa si los usuarios reportan que las alertas y recomendaciones son útiles y contribuyen a una mejor toma de decisiones sobre su salud cuando veamos que la mayoría de los usuarios interactúan con las alertas y siguen las recomendaciones proporcionadas por la aplicación.

**Hipótesis 3**  
Creemos que ofrecer un diseño intuitivo y una interfaz de usuario clara mejorará la experiencia general del usuario y reducirá problemas técnicos y de usabilidad. Sabremos que el diseño y la interfaz fueron exitosos si los usuarios reportan una experiencia fluida y sin problemas técnicos, y si la tasa de resolución de problemas es alta cuando veamos que los comentarios de los usuarios son mayoritariamente positivos respecto a la usabilidad del dispositivo y la aplicación, y que la frecuencia de problemas técnicos reportados es baja.

#### Lean UX Canvas 

<table align="center">
  <tr>
    <td align="center"><strong>Business Problem</strong><br><br>Muchos pacientes con condiciones cardíacas necesitan un monitoreo constante y preciso de su ritmo cardíaco, pero los dispositivos actuales son costosos, complicados de usar o no se integran bien con la tecnología actual.</td>
    <td align="center" rowspan="2"><strong>Solution Ideas</strong><br><br>- Desarrollar un dispositivo IoT económico y fácil de usar que monitoree continuamente el ritmo cardíaco y envíe datos a una aplicación web.<br><br>- CIntegrar alertas automáticas y personalizables que notifiquen tanto al usuario como a un contacto de emergencia en caso de anomalías.<br><br>- Ofrecer una plataforma de datos históricos que permita a los usuarios y médicos rastrear y analizar tendencias en el ritmo cardíaco.</td>
    <td align="center"><strong>Business Outcomes</strong><br><br>- Aumentar las ventas de dispositivos IoT en el sector salud.<br><br>- Mejorar la retención de clientes mediante la oferta de un producto confiable y fácil de usar.<br><br>- Posicionar a MedSync como un líder innovador en soluciones IoT para el cuidado de la salud.</td>
  </tr>
  <tr>
    <td align="center"><strong>Users and Customers</strong><br>- Pacientes que requieren monitoreo cardíaco: Personas con afecciones cardíacas que necesitan un seguimiento regular y preciso de su ritmo cardíaco.<br><br>- Familiares y contactos de emergencia: Personas cercanas al paciente que desean ser notificados en caso de emergencias o anomalías en los datos cardíacos.</td>
    <td align="center"><strong>User Benefits</strong><br><br>- Monitoreo continuo y preciso del ritmo cardíaco, proporcionando tranquilidad a los usuarios.<br><br>- Notificaciones automáticas para familiares o contactos de emergencia, mejorando la seguridad del paciente.<br><br>- Acceso a un historial de datos que facilita la consulta médica y el seguimiento de la salud del usuario.</td>
  </tr>
  <tr>
    <td align="center"><strong>Hypothesis</strong><br>- Creemos que nuestro sensor cardíaco IoT ayudará a los pacientes a monitorear su ritmo cardíaco de forma continua y en tiempo real, mejorando la gestión de su salud cardiovascular. Sabremos que el dispositivo tuvo éxito si los pacientes reportan una mejora en el manejo de su salud cuando veamos que los pacientes utilizan regularmente el dispositivo y proporcionan retroalimentación positiva sobre la precisión de los datos y la facilidad de uso.<br><br>- Creemos que una integración fluida entre el sensor y la aplicación móvil permitirá a los usuarios recibir alertas y recomendaciones personalizadas, lo que optimizará la gestión de su salud cardiovascular. Sabremos que la integración fue exitosa si los usuarios reportan que las alertas y recomendaciones son útiles y contribuyen a una mejor toma de decisiones sobre su salud cuando veamos que la mayoría de los usuarios interactúan con las alertas y siguen las recomendaciones proporcionadas por la aplicación.<br><br>- Creemos que ofrecer un diseño intuitivo y una interfaz de usuario clara mejorará la experiencia general del usuario y reducirá problemas técnicos y de usabilidad. Sabremos que el diseño y la interfaz fueron exitosos si los usuarios reportan una experiencia fluida y sin problemas técnicos, y si la tasa de resolución de problemas es alta cuando veamos que los comentarios de los usuarios son mayoritariamente positivos respecto a la usabilidad del dispositivo y la aplicación, y que la frecuencia de problemas técnicos reportados es baja.</td>
    <td align="center"><strong>What’s the most important thing we need to learn first?</strong><br><br>- ¿Están los pacientes y sus familiares interesados y dispuestos a utilizar un dispositivo IoT para el monitoreo cardíaco continuo?<br><br>- ¿Qué características consideran más valiosas o necesarias?</td>
    <td align="center"><strong>What's the least amount of work we need to do to learn the next most important thing?</strong><br><br>- Realizar entrevistas con pacientes y familiares para entender sus necesidades y preocupaciones.<br><br>- Desarrollar un prototipo de baja fidelidad de la aplicación y las alertas para obtener retroalimentación inicial.</td>
  </tr>
</table>

## Segmentos objetivo

**Personas diagnosticadas con problemas cardiacos**
- Descripción: Individuos con condiciones cardíacas preexistentes o riesgos elevados que necesitan un monitoreo constante de sus signos vitales para gestionar su salud de manera proactiva.
- Necesidades: Monitoreo continuo, alertas en tiempo real en caso de anomalías, y acceso a un historial detallado de medidas para compartir con su médico.

**Familiares y Contactos de Emergencia**
- Descripción: Familiares o amigos designados como contactos de emergencia que desean estar informados de la salud y seguridad del paciente en caso de eventos críticos.
- Necesidades: Notificaciones inmediatas sobre cualquier irregularidad en las medidas cardíacas del paciente, para poder tomar acciones rápidas y adecuadas en situaciones de emergencia.

# Capítulo II: Requirements Elicitation & Analysis

## Competidores
### Análisis competitivo

<table border="1">
  <thead>
    <tr>
      <th colspan="6"><strong>Competitive Analysis Landscape</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="1" style="text-align:center;">¿Por qué llevar a cabo este análisis?</td>
      <td colspan="5"><br>Para entender el posicionamiento de MedSync  frente a sus competidores, identificar áreas de oportunidad y mejorar la propuesta de valor para diferenciarse en el mercado.</td>
    </tr>
    <tr>
      <td colspan="2" style="text-align:center;">Competidores</td>
      <td style="text-align:center;">MedSync</td>
      <td style="text-align:center;">Omron</td>
      <td style="text-align:center;">Fitbit</td>
      <td style="text-align:center;">Garmin</td>
    </tr>
    <tr>
      <td rowspan="2" style="text-align:center;">Perfil</td>
      <td style="text-align:center;">Overview</td>
      <td style="text-align:center;">Startup enfocada en el desarrollo de soluciones IoT para el sector salud</td>
      <td style="text-align:center;">Líder en dispositivos médicos de precisión, especialmente en monitores de presión arterial conectados.</td>
      <td style="text-align:center;">Empresa líder en dispositivos wearables para el seguimiento de la actividad física y la salud general.</td>
      <td style="text-align:center;">Fabricante de dispositivos portátiles y wearables enfocados en el fitness, la salud y la navegación.</td>
    </tr>
    <tr>
      <td style="text-align:center;">Ventaja competitiva<br>¿Qué valor ofrece a los clientes?</td>
      <td style="text-align:center;">Ofrece facilidad de uso y alertas en tiempo real para pacientes y contactos de emergencia.</td>
      <td style="text-align:center;">Reconocida fiabilidad y precisión en la medición de la presión arterial, con tecnología validada clínicamente.</td>
      <td style="text-align:center;">Amplia comunidad de usuarios y una plataforma de salud bien desarrollada que ofrece programas personalizados de bienestar.</td>
      <td style="text-align:center;">Fuerte enfoque en la precisión y durabilidad de sus dispositivos, especialmente para atletas y usuarios activos.</td>
    </tr>
    <tr>
      <td rowspan="2" style="text-align:center;">Perfil de Marketing</td>
      <td style="text-align:center;">Mercado objetivo</td>
      <td style="text-align:center;">Se dirige a personas  interesadas en el monitoreo cardíaco a sus familiares o contactos de emergencia.</td>
      <td style="text-align:center;">Adultos y personas mayores que necesitan monitoreo de presión arterial.</td>
      <td style="text-align:center;">Personas activas y deportistas que buscan monitorear su salud y actividad física.</td>
      <td style="text-align:center;">Atletas y entusiastas del fitness que buscan dispositivos duraderos y precisos.</td>
    </tr>
    <tr>
      <td style="text-align:center;">Estrategias de marketing</td>
      <td style="text-align:center;">Utiliza marketing digital, alianzas con proveedores de salud y testimonios de usuarios para promocionar HeartLink.</td>
      <td style="text-align:center;">Se enfoca en la publicidad en medios de salud y médicos, marketing en punto de venta y colaboraciones con profesionales de la salud para promover la fiabilidad de sus dispositivos.</td>
      <td style="text-align:center;">Emplea campañas en redes sociales, asociaciones con influencers y expertos en salud, y publicidad en línea para promover sus dispositivos y programas de bienestar.</td>
      <td style="text-align:center;">Realiza marketing a través de patrocinios deportivos, colaboraciones con atletas y campañas publicitarias en medios especializados en deportes y fitness.</td>
    </tr>
    <tr>
      <td rowspan="3" style="text-align:center;">Perfil de Producto</td>
      <td style="text-align:center;">Productos & Servicios</td>
      <td style="text-align:center;">HeartLink es un dispositivo IoT portátil que monitorea continuamente el ritmo cardíaco y envía alertas automáticas.</td>
      <td style="text-align:center;">Omron ofrece monitores de presión arterial y otros dispositivos médicos de precisión, diseñados para el monitoreo de la salud cardiovascular en el hogar y entornos clínicos.</td>
      <td style="text-align:center;">Fitbit proporciona una variedad de dispositivos wearables que rastrean la actividad física, frecuencia cardíaca, sueño y bienestar general, con integración en una plataforma de salud.</td>
      <td style="text-align:center;">Garmin ofrece relojes inteligentes y rastreadores de actividad diseñados para monitorear el rendimiento deportivo, la salud general y la actividad física en entornos exigentes.</td>
    </tr>
    <tr>
      <td style="text-align:center;">Precios & Costos</td>
      <td style="text-align:center;">El producto oscilará entre un precio de S/ 10 - S/ 20 y su servicio será gratuito.</td>
      <td style="text-align:center;">Los monitores de presión arterial de Omron tienen precios que generalmente oscilan entre $50 y $150, dependiendo del modelo.</td>
      <td style="text-align:center;">Los dispositivos Fitbit tienen precios que oscilan entre $100 y $330, dependiendo del modelo y las funcionalidades.</td>
      <td style="text-align:center;">Los relojes y rastreadores de Garmin varían en precio desde unos $200 hasta más de $800, según las características y el nivel de precisión.</td>
    </tr>
    <tr>
      <td style="text-align:center;">Canales de distribución<br>(Web y/o Móvil)</td>
      <td style="text-align:center;">Distribuye a través de ventas en línea y acuerdos con instituciones médicas.</td>
      <td style="text-align:center;">Distribuye sus productos a través de su sitio web, tiendas en línea de minoristas, farmacias, y en algunos casos, mediante distribuidores médicos y clínicas.</td>
      <td style="text-align:center;">Distribuye sus dispositivos a través de su sitio web, tiendas en línea de minoristas, y puntos de venta en tiendas físicas y grandes cadenas de electrónica.</td>
      <td style="text-align:center;">Ofrece sus productos a través de su sitio web, tiendas en línea de minoristas, y en tiendas físicas especializadas en deportes y electrónica.</td>
    </tr>
    <tr>
      <td rowspan="4" style="text-align:center;">Perfil de Producto</td>
      <td style="text-align:center;">Fortalezas</td>
      <td style="text-align:center;">Enfoque en seguridad y accesibilidad.</td>
      <td style="text-align:center;">Alta fiabilidad y precisión en la medición de la presión arterial.</td>
      <td style="text-align:center;">Amplia comunidad de usuarios y una plataforma de salud bien establecida.</td>
      <td style="text-align:center;">Precisión y durabilidad de dispositivos orientados a atletas y entusiastas del fitness.</td>
    </tr>
    <tr>
      <td style="text-align:center;">Debilidades</td>
      <td style="text-align:center;">Reconocimiento de marca limitado.</td>
      <td style="text-align:center;">AMayor enfoque en dispositivos para presión arterial, con menos innovación en otras áreas de salud.</td>
      <td style="text-align:center;">Pérdida de diferenciación en un mercado competitivo con múltiples dispositivos similares.</td>
      <td style="text-align:center;">El enfoque principal en el mercado deportivo puede limitar su atractivo para consumidores generales.</td>
    </tr>
    <tr>
      <td style="text-align:center;">Oportunidades</td>
      <td style="text-align:center;">Crecimiento en el mercado de salud digital.</td>
      <td style="text-align:center;">Innovar en tecnología de monitoreo de salud y aumentar la presencia en mercados emergentes.</td>
      <td style="text-align:center;">Expansión en el mercado de salud y colaboración con proveedores de atención médica.</td>
      <td style="text-align:center;">Aprovechar el interés creciente en fitness para lanzar nuevos dispositivos y características.</td>
    </tr>
    <tr>
      <td style="text-align:center;">Amenazas</td>
      <td style="text-align:center;">Competencia intensa y regulaciones del sector salud.</td>
      <td style="text-align:center;">Riesgos asociados con la regulación estricta y la necesidad de mantener alta precisión en dispositivos médicos.</td>
      <td style="text-align:center;">Presión competitiva de nuevos jugadores y cambios en las preferencias del consumidor.</td>
      <td style="text-align:center;">Competencia creciente en el mercado de dispositivos deportivos y de salud de bajo costo.</td>
    </tr>
  </tbody>
</table>

### Estrategias y tácticas frente a competidores

**Diferenciación en Características**
- Estrategia: Desarrolla características únicas en HeartLink que no estén presentes en los productos de la competencia.
- Táctica: Implementa funciones adicionales como alertas personalizadas, análisis de tendencias a largo plazo, o integración con otros dispositivos de salud en el hogar.

**Enfoque en la Experiencia del Usuario**
- Estrategia: Ofrece una experiencia de usuario superior a través de la simplicidad y la facilidad de uso.
- Táctica: Diseña una interfaz de usuario intuitiva en la app móvil, proporciona soporte técnico accesible, y asegura una instalación y configuración sin problemas

**Estrategia de Precios Competitivos**
- Estrategia: Establece una estrategia de precios que ofrezca una buena relación calidad-precio en comparación con los competidores.
- Táctica: Ofrece un servicio gratuito 

**Estrategia de Asociaciones y Colaboraciones**
- Estrategia: Forma alianzas con profesionales de la salud, clínicas, o empresas de tecnología para aumentar la visibilidad y credibilidad del producto.
- Táctica: Colabora con médicos para validar la eficacia del dispositivo y utiliza sus recomendaciones en campañas de marketing, o establece acuerdos con proveedores de seguros de salud para ofrecer HeartLink a sus clientes.

**Campañas de Marketing y Educación**
- Estrategia: Realiza campañas de marketing dirigidas y programas educativos para aumentar la conciencia sobre la importancia del monitoreo del ritmo cardíaco y los beneficios de HeartLink.
- Táctica: Utiliza publicidad en redes sociales, blogs de salud, y webinars para educar a los consumidores sobre los beneficios del monitoreo cardíaco, y destaca cómo HeartLink puede mejorar su bienestar.

     
## Entrevistas 

### Diseño de entrevistas

**Paciente**

- ¿Cuál es su diagnóstico o condición cardíaca específica?
- ¿Cuánto tiempo ha estado bajo monitoreo o tratamiento para esta condición?
- ¿Cómo está monitoreando actualmente su ritmo cardíaco y otros signos vitales?
- ¿Qué aspectos de su sistema actual de monitoreo le parecen útiles o problemáticos?
- ¿Qué funcionalidades considera más importantes en un dispositivo de monitoreo cardíaco?
- ¿Cómo prefiere recibir alertas y notificaciones sobre cambios en su salud?
- ¿Cómo le gustaría que el dispositivo se integre en su vida diaria?
- ¿Qué tipo de información y frecuencia le gustaría que se muestre en la aplicación web?
- ¿Qué le preocupa acerca del uso de un dispositivo de monitoreo cardíaco?
- ¿Qué características adicionales le gustaría ver para mejorar su experiencia?

**Contacto de emergencia**

- ¿Cuál es su relación con el paciente que utilizará el dispositivo?
- ¿Cuál es su rol en el cuidado o supervisión del paciente?
- ¿Cómo recibe actualmente información sobre la salud del paciente?
- ¿Qué tipo de notificaciones y alertas le parecen más útiles?
- ¿Qué tipo de notificaciones le gustaría recibir y con qué frecuencia?
- ¿Cómo preferiría que se le informe en caso de una emergencia con el paciente?
- ¿Qué información le gustaría ver en la aplicación en caso de una alerta?
- ¿Qué funcionalidades adicionales considera importantes para gestionar la salud del paciente?
- ¿Qué le preocupa acerca de recibir notificaciones sobre la salud del paciente?
- ¿Cómo podría mejorarse la comunicación y la coordinación entre usted y el paciente en situaciones críticas?

### Registro de entrevistas

El video de las entrevistas fue subido a Microsoft Stream. Podrá acceder a este mediante el enlace proporcionado en el Anexo 1.

**Entrevistas a pacientes:**

**Entrevista 1**

![Imgur](https://gyazo.com/1a44c6a37b8212a1ddec311350295c71.png)

**Nombre:** Cristian Luis Iparraguirre Rueda

**Edad:** 20

**Resumen:** Cristian empieza contándonos el diagnóstico de su condición cardiaca, el cual es hipertensión arterial, lo que ha llevado a estar durante 2 años en tratamiento, implicando monitoreo manual y consultas periódicas al doctor. Nos comenta que a veces se olvida de tomarse la presión en casa, además de que se le hace tedioso llevar el registro de los medicamentos que toma. Considera importante que un dispositivo que le tome la presión debe ser de uso fácil y sobre todo preciso con las mediciones. Además, desearía que fuese discreto, fácil de llevar y que pueda integrarse con diferentes dispositivos de uso diario. Una de sus principales preocupaciones es la precisión de la medición del dispositivo, además de que recibir tantas notificaciones podrían provocarle ansiedad. Por último, considera indispensable que el dispositivo muestre métricas de su presión a lo largo del tiempo, teniendo valores máximos y mínimos, además de recibir notificaciones en caso una medición salga de su rango.

**Entrevista 2**

![Imgur](https://gyazo.com/b4317a618a1007fe1cab004df2c97395.png)

**Nombre:** Luis Trujillo

**Edad:** 25

**Resumen:** Luis nos cuenta que sufre de hipertensión arterial y arritmia, lo cual lo hace más propenso a sufrir ataques cardíacos y accidentes cerebrovasculares. Lleva aproximadamente 4 años en tratamiento, lo que implica monitoreo desde su casa y visitas constantes al cardiólogo. Luis comenta que se le hace incómodo llevar instrumentos para medir su ritmo cardíaco, además que los considera incómodos y no muy precisos. Considera que lo más importante que debe tener un instrumento para su medición del ritmo cardiaco es que debe ser preciso y fácil de usar, además de registrar todas las lecturas y tener la opción de compartirlas. También comenta que preferiría que las notificaciones le lleguen al teléfono móvil, a modo de notificación corta y concisa, o mediante sms o llamada. Sus mayores preocupaciones son que el dispositivo no sea preciso y que pueda llegar a tener alguna falla al detectar alguna anomalía. Por último agrega que le gustaría que contara con un botón de emergencia para poder alertar a quien necesite.

**Entrevista 3**

![Imgur](https://gyazo.com/8fb5d37f38b001fe44d718ab6e25f998.png)

**Nombre:** Valeria Nevado

**Edad:** 21

**Resumen:** Valeria nos cuenta que ella padece de una arritmia, la cual necesita ser monitorizada con frecuencia, en la cual lleva 2 años de tratamiento y monitoreo. El monitoreo lo realiza principalmente en sus visitas médicas, y en su casa usa un oxímetro. Nos señala que el oxímetro le parece útil porque su precisión es muy buena, sin embargo, tiende a malograrse muy rápido. También nos señala que lo más importante de un dispositivo que mida la frecuencia cardiaca debe ser la precisión, además de que le gustaría que la batería tenga una larga duración y sea resistente al agua. Además, nos comenta que le gustaría que el dispositivo fuera fácil de transportar, y que la información mostrada debería ser principalmente su historial de ritmo cardiaco, además de un resumen semanal o mensual y que en base a esto hayan recomendaciones personalizadas. Nos cuenta también que su mayor preocupación son las posibles malas lecturas del dispositivo, ya que esto supondría preocuparse ella y su familia por falsa información. Por último añade que le gustaría que el dispositivo también funcione en sus horas de sueño, así podría saber cómo se comporta su corazón mientras descansa.

**Entrevistas a contactos de emergencia:**

**Entrevista 1**

![Imgur](https://gyazo.com/dc85490b7cd10c17894c17c9f41084fa.png)

**Nombre:** Alessandro Ramiro Condori Lozano

**Edad:** 21

**Resumen:** Alessandro nos cuenta que él está a cargo de su primo, el cual es el paciente con problemas cardiacos y el cual estaría interesado en usar nuestro dispositivo. Actualmente la información que recibe de la persona a su cargo es mediante informes médicos. Nos cuenta además que le gustaría recibir notificaciones en caso haya algún cambio en la frecuencia del ritmo cardíaco del paciente, y que estas notificaciones no puedan ser ignoradas, el cual es su mayor miedo, por lo que piensa que deberían ser mediante una alarma o una llamada telefónica. También, nos comenta que la información más relevante debe ser su ritmo cardiaco, además de un historial de este mismo para detectar cualquier anomalía. Por último, indica que le gustaría que el dispositivo también mida la presión y la glucosa. Así como también le gustaría tener una conexión más directa con el paciente para tener más información en todo momento, no solamente mediante informes médicos.

**Entrevista 2**

![Imgur](https://gyazo.com/759f83a390c64d75c849a5027d18cd70.png)

**Nombre:** Liliana Fu Ye

**Edad:** 23

**Resumen:** Lilliana nos comenta que cuida a su abuelo de 78 años, quien sufre problemas de corazón. Actualmente la información que recibe es por medio de citas médicas y mediante una máquina que tiene en su casa que mide la presión. Nos comenta que, ella prefiere que ante cualquier anomalía en el ritmo cardíaco de su paciente, reciba una notificación y en base a ello ponerse en contacto con su médico para realizar los respectivos procedimientos. Y en caso la anomalía fuese muy grave, priorizar el contacto con la clínica. Añade que la información que ella considera indispensable en el dispositivo es el registro de pulsaciones del paciente, para poder identificar los rangos normales y hacer un seguimiento más detallado Además, añade que el dispositivo debe ser cómodo y el doctor asignado debe tener acceso a la información. Por último, señala que las mediciones deben ser precisas, para que no realice notificaciones erróneas, y , que debe tener un botón para comunicarse directamente y lo más antes posible con ella en caso se necesite.

**Entrevista 3**

![Imgur](https://gyazo.com/82d7bb3f5aceb54abfc6c1fa7b797eec.png)

**Nombre:** Joaquin Pinto

**Edad:** 21

**Resumen:** Joaquin nos cuenta que su tío es la persona que tiene los problemas en el corazón, en donde la información que recibe actualmente es por medio de visitas de su tío a su casa o por medio de conversaciones con sus padres. También nos indica que él preferiría recibir las alertas mediante mensajes de WhatsApp, ya que es el medio al que más pendiente está, o, en caso sea urgente, por medio de una llamada. Nos añade que el dispositivo debe medir el ritmo cardiaco exacto y que podría significar. Además de registrar un historial de su ritmo cardiaco durante el día. Nos comenta que una de sus mayores preocupaciones es recibir la alerta tarde o no recibirla. Por último, señala que el dispositivo debería mandar la alerta y que esta se sobreponga al resto de notificaciones, ya que es la más importante y no debería ser capaz de ser ignorada. 

### Análisis de entrevistas 

**Paciente**

- Estadísticas y Aspectos Comunes: Todos los pacientes realizan tratamiento médico y coinciden en que la precisión del dispositivo para medir el ritmo cardiaco es fundamental. Un 33% está interesado en que el dispositivo funcione durante el sueño.
- Características Objetivas: La precisión es la prioridad, junto con la comodidad y facilidad de uso del dispositivo.
- Características Subjetivas: Todos los entrevistados expresan miedo a fallos en el dispositivo, ya sea por lecturas incorrectas o por no registrar los datos.

**Contacto de Emergencia**

- Estadísticas y Aspectos Comunes: El 67% de los entrevistados reciben información sobre el paciente a través de informes médicos. Todos consideran esencial que el dispositivo registre las pulsaciones diarias para detectar anomalías y que notifique al médico y al responsable ante cualquier irregularidad.
- Características Objetivas: Es necesario implementar un sistema de registro y notificación para abordar las inquietudes de los familiares.
- Características Subjetivas: Existe una preocupación generalizada sobre la posibilidad de que las alertas ante anomalías no lleguen a tiempo, lo que podría poner en riesgo al paciente.

## Needfinding

### User Personas

**Paciente**

![Image from Gyazo](https://gyazo.com/d6037819b1f2ea2199e67bf70d0a4791.png)

**Contacto de emergencia**

![Image from Gyazo](https://i.gyazo.com/5138273c81832215e01cbef18d956587.png)

### User Task Matrix

![Imgur](https://gyazo.com/5b492e6ba012ccd4bf0fb4bad59cde22.png)
![Imgur](https://gyazo.com/2ca018cba74c163b221d62131de83e68.png)

### User Journey Mapping



### Empathy Mapping

**Paciente**

![Imgur](https://gyazo.com/1097f897c71024c9e04e6672ec54cbaf.png)

**Contacto de emergencia**

![Imgur](https://gyazo.com/1c5a899801d51c96ab4ed92d17bdc5c6.png)

### As-is Scenario Mapping

**Paciente**

![Imgur](https://gyazo.com/039309e7c188655865f17e871f7dab11.png)

**Contacto de emergencia**

![Imgur](https://gyazo.com/6165e99c08663e609ac4624d5ee1eaa9.png)

## Ubiquitous Language

- **Software**: Conjunto de programas, instrucciones y datos que permiten a una computadora realizar tareas específicas.
- **Sprint**: Ciclo de trabajo corto y enfocado en metodologías ágiles, donde un equipo se concentra en completar una cantidad definida de trabajo en un tiempo limitado, generalmente de 1 a 4 semanas.
- **Sensor**: Dispositivo que detecta cambios en el entorno físico o químico y genera una señal que puede ser medida o registrada.
- **Ritmo cardíaco**: Número de veces que el corazón late por minuto, indicador clave de la salud cardiovascular.
- *Alcance*: Definición clara de los límites y objetivos específicos de un proyecto, detallando lo que se incluirá y lo que no.
- **Servicio cloud**: Servicios de computación que se proporcionan a través de internet, como almacenamiento, procesamiento y aplicaciones, sin necesidad de infraestructura física local.
- **Protocolos de comunicación**: Conjunto de reglas y normas que permiten la transmisión de datos entre dispositivos electrónicos o sistemas de red.

# Capítulo III: Requirements Specification

### To-Be Scenario Mapping

**Paciente**

![Imgur](https://gyazo.com/260dc8cc8ce6d027fb6541d192149e94.png)

**Contacto de emergencia**

![Imgur](https://gyazo.com/2394618b4432fbba25b57f7c268d640e.png)

### User Stories

![Imgur](https://gyazo.com/36573eca70e8ee65eaa1dfce312d462b.png)
![Imgur](https://gyazo.com/6a50e6414d8d71e9d7fec6619e7072b7.png)
![Imgur](https://gyazo.com/aacf2a5b8853773715fb609177239a9b.png)
![Imgur](https://gyazo.com/aaf0f57a9b88d1c2691979a3c549fc3c.png)

### Impact Mapping

![](https://gyazo.com/231f21636b49c36884e6348c4da35333.png)

### Product Backlog

![Imgur](https://gyazo.com/f9916942332cbdd2a3233694ead8d05e.png)
![Imgur](https://gyazo.com/741a42aca40c1b5eb8f8b0a3fbb1733e.png)
![Imgur](https://gyazo.com/716b7fe4c3c3bddfe6d310ed593d3403.png)

# Capítulo IV: Solution Software Design

## Strategic-Level Attribute-Driven Design

### Event Storming

#### Candidate Context Discovery

Durante el proceso se realizaron los siguientes pasos: identificación de los eventos claves del negocio; identificación de acciones de los actores; identificación de disparadores e identificación de bounded contexts.

![Imgur](https://gyazo.com/a59d5f5964a07d3ae97d07a394488fed.png)
![Imgur](https://gyazo.com/332b2fbe54a67076663471f30981f8c5.png)
![Imgur](https://gyazo.com/0f205d6394348c3f53e7d3befc068b57.png)
![Imgur](https://gyazo.com/b02234b674b905471a2f6e84b0333583.png)

#### Domain Message Flows Modeling

**Paciente mide su ritmo cardiaco**

Primero el BC de Gestión del sensor deberá preparar este para medir el ritmo cardiaco; luego el paciente insertará su dedo en el dispositivo y el BC de Monitoreo del paciente recopilará la data, para posteriormente avisar al BC Notificaciones que avise a los contactos de emergencia del paciente.

#### Bounded Context Canvases

![Imgur](https://gyazo.com/add89067458602ed57446a1c90276476.jpeg)
![Imgur](https://gyazo.com/eb3460c889f4506e6061c7bbbc04d53e.jpeg)

### Context Mapping

A continuación, se presenta el context mapping elaborado para nuestra solución. Este representa el cómo se comportan y colaboran los BC entre sí y de qué depende que esto suceda.

![Imgur](https://gyazo.com/c67ec3acd12e1d4204655b37fdaec698.png)

### Software Architecture

#### Software Architecture System Landscape Diagram

![Imgur](https://gyazo.com/02332071c2253fbb2b399376bfbb0bd0.jpg)

#### Software Architecture Context Level Diagrams

![Imgur](https://gyazo.com/4423fb04db9e9fcbf64e72f00e893d81.jpg)

#### Software Architecture Container Level Diagrams

![Imgur](https://gyazo.com/ae2e0c43b6df100060bfb2fefbd8015a.jpg)

#### Software Architecture Deployment Diagrams

![Imgur](https://gyazo.com/9e0827e933d50b77d105db76c12fb68e.jpg)

## Tactical-Level Domain-Driven Design

### Bounded Context: Authentication

#### Domain Layer

![Imgur](https://gyazo.com/4875ff1a473e0047fa056e33b542460c.png)

**User**

![Imgur](https://gyazo.com/c9bbd823d229b8e1d34d8141c5f11b40.png)
![Imgur](https://gyazo.com/2fd76002d03a094e748de85d5d984627.png)

**Role**

![Imgur](https://gyazo.com/447ee49beeed44885e48289a3d4f9ced.png)
![Imgur](https://gyazo.com/b7367159fd3710504ada094be4c6e412.png)

**AuthToken**

![Imgur](https://gyazo.com/ce6c06ea3ba82113e869ee3a7ff787e0.png)
![Imgur](https://gyazo.com/595bfb6a76bfbc6bd4cf6e664017f18f.png)

#### Interface Layer

![Imgur](https://gyazo.com/ee4fe0b30d271f917e7478e9f8cc6de9.png)

**UserController**

![Imgur](https://gyazo.com/7330d1cbb55bdb12919a3ade8ca710d4.png)

**RoleController**

![Imgur](https://gyazo.com/69c32f074d6361026cbebac2ec93ea4c.png)

#### Application Layer

![Imgur](https://gyazo.com/e8407bab218c76b451b5f317f47c3aeb.png)

#### Infrastructure Layer

![Imgur](https://gyazo.com/ba5a9be1a935777be35a26936afdc52a.png)

**UserRepository**

![Imgur](https://gyazo.com/0051815e03c8434c3473e30d44adf733.png)

**RoleRepository**

![Imgur](https://gyazo.com/324e54df6b895b5a7b8061c97d6b8fcd.png)

#### Bounded Context Software Architecture Component Level Diagrams

![](https://gyazo.com/e61238a3bec30b675025fc1d4893d85b.png)

#### Bounded Context Software Architecture Code Level Diagrams

##### Bounded Context Domain Layer Class Diagram

![](https://gyazo.com/e9e459e213f28c94b880f37ceb01ab64.png)

##### Bounded Context Database Design Diagram

![](https://gyazo.com/218a88320337aa76d94c3d7d2f312620.png)

# Solution UI/UX Design

## Style Guidelines

### General Style Guidelines

**Overview**

Nuestro objetivo es captar la atención del usuario desde la primera interacción, mediante la creación de una interfaz con un diseño tanto atractivo visualmente como intuitivo, de esta forma logrando una conexión inmediata y reconocible con MedSync.

**Brand Name**

Se optó por el nombre de “MedSync” dado su enfoque y la simpleza de su pronunciación a la vez de su recordatorio.

**Typography**

Se seleccionaron cuidadosamente la fuente “Montserrat” con la finalidad de transmitir una imagen moderna, elegante y legible.

![](https://gyazo.com/0c8113f6214cd6ee23d07531831bd732.png)

**Colors**

Los colores principales son el cian oscuro y el blanco. El cian oscuro nos fue seleccionado dado por la asociación a la calma, la confianza y la modernidad, aspectos claves de la solución. Este color demuestra nuestro compromiso de ofrecer soluciones tanto innovadoras como confiables. Por otro lado, el blanco se utiliza como predominante para el fondo, dado que muestra un contraste limpio y elegante, resaltando la claridad y simplicidad.

![](https://gyazo.com/11b11b6ca5d8c12b89a954e787221553.png)

**Spacing**

Hemos establecido niveles de espacio para garantizar un aspecto equilibrado y experiencia visual agradable, los valores van desde 8px hasta los 96px.

![](https://gyazo.com/3c5f98aa320feffbf7c1943c1ab0865c.png)

**Buttons**

Se distribuye en 3 tipos de botones que están en relación del tamaño en general y tamaño de la letra.

![](https://gyazo.com/5f94a50a37b600d1590c7ae747919ff2.png)

### Web, Mobile and IOT Style Guidelines

MedSync se basará en una aplicación de web, se optó por el uso de los principios del Web Responsive Design, dado que tiene como finalidad mostrar la información en relación al tamaño de la ventana; de esta manera, garantizando que el contenido no sufra variaciones. También, existe la versión para móviles.

![](https://gyazo.com/8a14ca3c0febf88950fd604911dbbc16.png)

Del mismo modo, como equipo, tomamos la decisión de emplear el patrón de diseño en forma de Z, puesto que está técnica mejora de forma efectiva la experiencia del usuario dado que brindan una jerarquía visual además de centrar la atención del usuario en elementos claves.

![](https://gyazo.com/f82695e6fc460b1d4d9bf9f152d84d1c.png)

Por otro lado, se tomará en cuenta el principio de Hick ya que reduce en gran medida el tiempo de toma de decisión por parte de nuestros usuarios; esto es posible gracias a la optimización de nuestras funcionalidades a brindar mediante opciones claras y limitadas.

## Information Architecture

### Organization Systems

Como sistema de organización, hemos optado por una mezcla entre un sistema secuencial (step-by-step to accomplish) y un sistema de forma jerárquica (visual hierarchy). Esto debido a que contamos con segmentos que merecen la importancia jerárquica y también con segmentos en donde el usuario deberá seguir con un camino para lograr su objetivo.

### Labeling Systems

Los labels que hemos utilizado para nuestro proyecto son: 
- Landing Page: Inicio, Sobre nosotros, Especificaciones, Contacta con nosotros.
- Aplicación: Frecuencia cardíaca, Registro cardíaco, Contacto de emergencia, Perfil.

### SEO Tags and Meta Tags

![](https://gyazo.com/b0a16152226b299121bc39722aafeab5.png)

### Navigations Systems

¿Qué se busca?: El usuario quiere saber las especificaciones del dispositivo.
¿Cómo lo logra?: El usuario deberá dirigirse al apartado de Especificaciones en la landing page mediante scroll o la barra de navegación..

¿Qué se busca?: El usuario quiere saber más acerca del equipo detrás del proyecto.
¿Cómo lo logra?: El usuario deberá desplazarse hasta la sección de Sobre Nosotros en la landing page mediante scroll o la barra de navegación.


¿Qué se busca?: El usuario quiere revisar y descargar el historial cardiaco del paciente.
¿Cómo lo logra?: El usuario deberá dirigirse a la sección de Registro Cardiaco en la aplicación, donde podrá revisar el historial de la frecuencia cardiaca en un lapso determinado y también podrá descargarlo.

¿Qué se busca?: El usuario desea editar sus contactos de emergencia.
¿Cómo lo logra?: El usuario deberá dirigirse a la sección de Contactos de Emergencia en la aplicación, donde podrá añadir y editar los contactos de emergencia.

### Searching Systems

La navegación dentro de la landing page será mediante el scroll con el mouse o mediante los botones situados en la barra de navegación ubicada en la parte superior.

La navegación dentro de la aplicación se basará en el manejo de secciones mediante los labels en la barra de navegación.

## Landing Page UI

### Landing Page Wireframe

![](https://gyazo.com/033fc1551385d391c3e81962855b4e52.png)
![](https://gyazo.com/da868eb27409555b57a11fc8f087640c.png)

### Landing Page Mock-up

![](https://gyazo.com/33d4469ad2f501ad9fa22538de4a97c4.jpeg)
![](https://gyazo.com/c0532a36f2a94614d259745f9434f4e8.jpeg)
![](https://gyazo.com/d8e2fb855639a1a08a32726bde440949.jpeg)
![](https://gyazo.com/c76c0b6daf62a458264a6cdb24646733.jpeg)

## Applications UX/UI Design

### Applications Wireframes

![](https://gyazo.com/6478fc9aa016a60ae40cc7d713f7b320.png)
![](https://gyazo.com/0d5c7ecc0c158d151dc3dbb9e7b2c107.png)

### Applications Wireflow Diagram

**Revisar pulso cardiaco**

![](https://gyazo.com/b3af46f53ae69d57c020db5f6f81f1c8.png)

**Registrarse en la aplicación**

![](https://gyazo.com/67412a190bc794e5cb5663997d90ab1f.png)

**Revisar historial diario**

![](https://gyazo.com/c96d158cad4ef0fb041cdaf66a309018.png)

**Ver y editar perfil**

![](https://gyazo.com/8ea2fc756aab656b34d3aa6025ee66d4.png)

**Ver datos de contacto de emergencia**

![](https://gyazo.com/297f553694edda6c01e8e4b4af765172.png)

### Applications Mock-ups

![](https://gyazo.com/c99ed166e6c61ac914dcce6acd8157c7.png)
![](https://gyazo.com/4978fdbd174ee9bc77530795080a9310.png)

### Applications User Flow Diagrams

**Revisar pulso cardiaco**

![](https://gyazo.com/bc3a8342f5a16595c95bacdd720638ea.png)

**Registrarse en la aplicación**

![](https://gyazo.com/21886d32e3a282a6f7003a40878bf400.png)

**Revisar historial diario**

![](https://gyazo.com/fa756c53214fd29ea04e60b651916aaa.png)

**Ver y editar perfil**

![](https://gyazo.com/935206ec578a7d2febe3284b2013f082.png)

**Ver datos de contacto de emergencia**

![](https://gyazo.com/b685d1b651d422c377c024d41e5a5a84.png)

## Applications Prototyping

![](https://gyazo.com/bb8f83c089f9810575bca31c33730f4f.png)

**Link del prototipo:** [https://www.figma.com/proto/cf3yKXcnu0z0nXSdqhNfIo/AndroidPrototype-(Copy)?node-id=11-547&node-type=canvas&t=9qykzaIHyC1JXwIN-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=11%3A547](https://www.figma.com/proto/cf3yKXcnu0z0nXSdqhNfIo/AndroidPrototype-(Copy)?node-id=11-547&node-type=canvas&t=9qykzaIHyC1JXwIN-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=11%3A547)

# Product Implementation, Validation & Deployment

## Software Configuration Management

### Software Development Environment Configuration

Project Management:
- Repositorio del informe general:
  https://github.com/Desarrllo-de-Soluciones-IoT-Grupo-4/Informe-del-Trabajo 

- GitHub: 
  Servicio web y en la nube que ayuda a los desarrolladores a almacenar y administrar su código para llevar el control de cambios de versiones Git.

Requirements Management:
- Trello (https://trello.com/es):
  Esta herramienta permite a nuestro equipo gestionar nuestro proyecto y flujo de trabajo, así mismo nos permite asignarnos tareas y personalizar según nuestras necesidades.

- UXPressia (https://uxpressia.com):
  Esta herramienta permite la creación fácil y rápida de mapas de empatía, journey maps, perfiles de usuarios de forma online.

- Figma (https://www.figma.com/es-la/):
  Herramienta para la creación de diseño de interfaces, ofreciendo desde plantillas hasta imágenes y formas que ayudarán a con la creación. Asimismo, nos permite desarrollar un prototipo de la solución, únicamente basado en los bocetos hechos. 

- Miro (https://miro.com/es/):
  Herramienta para la creación de contenido visual de cualquier tipo, ofreciendo diversos servicios desde plantillas como contenido propio de la página brindada. Asimismo, brindando conexiones con otras plataformas.

- Discord (https://discord.com) y  Whatsapp (https://www.whatsapp.com/?lang=es_LA):
  Medios principales de comuniones entre los integrantes del equipo, destacando la difusión de mensajes al igual para la realización de las reuniones, asimismo, organizando grupos de estudios y trabajo.

Product UX/UI Design:
- HTML: 
  Alto impacto en el desarrollo de aplicaciones web, proporciona la estructura base de la que se rige la solución.

- CSS:
  Lenguaje utilizado para ordenar el diseño de las páginas web y para la presentación del contenido de forma visualmente atractiva 

- GitHub: 
  Reiterar su función como servicio de almacenamiento y control sobre el avance del contenido de la propuesta de solución. 

### Source Code Management

Como anteriormente se mencionó, se hará uso de GitHub como sistema de almacenamiento y control de versiones. Por ello se crearon los diversos repositorios que contendrán información valiosa de la propuesta de solución:

- Repositorio Landing Page: [https://github.com/EUrbizagastegui/MedSync-Landing-Page](https://github.com/EUrbizagastegui/MedSync-Landing-Page)

Del mismo modo, se trabajará bajo la metodología de GitFlow, la cual nos permitirá trabajar de forma más eficiente en el trabajo colaborativo:

- Rama Main: Encargado de contener el código fuente para su uso en producción.

- Rama Feature: Principal función de desarrollar las nuevas funcionalidades del proyecto, tiene como base a la rama Main. Asimismo, una vez culminado su labor, la rama se fusionará con la rama principal.

- Rama Testing: Función primordial de desarrollar las distintas pruebas para la validación del correcto funcionamiento de los implementados en el transcurso de la solución.

- Rama Hotfix: Función de corregir rápidamente los problemas o errores que se originaron en el código base.

### Source Code Style Guide & Conventions

HTML:
- Index.html: este source code en HTML establecerá la estructura del Landing Page.

CSS:
- Main.css: este source code en CSS se integrará al source code de HTML en el diseño del Landing Page 
- Base.css: este source code en CSS se integrará al source code de HTML en el diseño del Landing Page 
- Fonts.css: este source code en CSS se integrará al source code de HTML en el diseño del Landing Page 
- Vendor.css: este source code en CSS se integrará al source code de HTML en el diseño del Landing Page 

JavaScript:
- Jquery-2.1.3.min.js: Este archivo mejora la experiencia del usuario en el Landing Page.
- main.js: main.js es un archivo de código fuente fundamental para el funcionamiento del Landing Page en AutoYa!. 
- modernizr.js: modernizr.js garantiza una experiencia coherente y eficiente en diferentes navegadores.
- pace.min.js: Esto ayuda a los usuarios a comprender cuándo se ha completado la carga del sitio web. En AutoYa!, pace.min.js mejora la percepción del rendimiento del sitio y la experiencia de usuario.
- plugins.js: Este archivo contiene plugins y extensiones de JavaScript que se utilizan en diversas partes del Landing Page.

**Convenciones generales**

![](https://gyazo.com/220678fda348468a1769f01e3aa42923.png)

**Convenciones del formato HTML**

![](https://gyazo.com/db20d0f830cb1bc2b3a0b0aba3e35ad3.png)

**Convenciones del formato CSS**

![](https://gyazo.com/841bbab81fecc222044914681bd68f31.png)

### Software Deployment Configuration

Para la implementación del despliegue ya sea tanto para el Landing Page como la Aplicación Web en sí, se hará uso de la plataforma “Vercel” dado que esta nos facilita tanto la configuración como la automatización de cambios en futuras ediciones.

![](https://gyazo.com/f97a5431f484035cc4ce23976b7d20b9.png)

## Landing Page, Services & Applications Implementation

### Aprint 1

#### Sprint Planning 1

![](https://gyazo.com/6161e54401dea4abe089243aa15cbf66.png)

#### Sprint Backlog 1

![](https://gyazo.com/ae96e0de935a70ab38ed6154dad24e68.png)

#### Development Evidence for Sprint Review

![](https://gyazo.com/b8a24d7a8d53de0aaca54d9cecf043e2.png)

#### Testing Suite Evidence for Sprint Review

Al ser un landing page, no se requiere de una suite de pruebas para su desarrollo.

#### Execution Evidence for Sprint Review

En esta entrega desarrollamos y desplegamos la landing page.

**Link del landing page desplegado:** [https://med-sync-landing-page.vercel.app/](https://med-sync-landing-page.vercel.app/)

![](https://gyazo.com/ad2dc99e42ab95769c6bed12f2042d06.png)

#### Services Documentation Evidence for Sprint Review

Al tratarse de una landing page, no requiere documentación de servicios.

#### Software Deployment Evidence for Sprint Review

En este sprint, desarrollamos la landing page del proyecto, para la cual usamos los siguientes recursos:
- Github: Utilizado como repositorio para almacenar el código
  desarrollado y facilitar el control de versión para el equipo.
- Vercel: Utilizado como plataforma para el despliegue de nuestra
  landing page. 

#### Team Collaboration Insights during Sprint

![](https://gyazo.com/548cda9f0b4b39e5fa1ab6ed5d1d7d69.png)

### Sprint 2

#### Sprint Planning 2

![](https://gyazo.com/0eeac028cfe64d9aa3741db2f9dd19b6.png)

#### Sprint Backlog 2

![](https://gyazo.com/514b30db0a9f5303f19a149a6dc5394c.png)

#### Development Evidence for Sprint Review

![](https://gyazo.com/1b5bed88235f6170fdbaf779b78d9edd.png)

#### Testing Suite Evidence for Sprint Review

Para el término de esta entrega, no se desarrolló este apartado.

#### Execution Evidence for Sprint Review

**FrontEnd**

![](https://gyazo.com/c13513071523aef41f9bf0d056a5db3a.png)
![](https://gyazo.com/1be0b49495ed35f1278c95de42d1c709.png)
![](https://gyazo.com/d5dff5bb723f4dee76da6944e9548ad0.png)
![](https://gyazo.com/7e36cf98419f81ec05722be84c930341.png)

**Mobile**

![](https://gyazo.com/e4810b2e77280012afc03d5f7a9164f3.png)
![](https://gyazo.com/cb5c3d3325435da4db315c1aa9471319.png)
![](https://gyazo.com/e2d0dcc6ff0b291c1a1fe8a5d69511f2.png)
![](https://gyazo.com/79bb333f6138de65b891fb866c61edf2.png)

#### Services Documentation Evidence for Sprint Review

Link del Swagger: [https://medsync-api.up.railway.app/swagger-ui/index.html#/](https://medsync-api.up.railway.app/swagger-ui/index.html#/)

![](https://gyazo.com/b5d9af13f6fa175b860e271689b5f119)

#### Software Deployment Evidence for Sprint Review

En el presente Sprint se desplegó el backend del proyecto en Railway, según los pasos especificados en la configuraciones de software. A continuación, se presenta la evidencia del despliegue:

Link del Backend: [https://medsync-api.up.railway.app/swagger-ui/index.html#/ ](https://medsync-api.up.railway.app/swagger-ui/index.html#/)

![](https://gyazo.com/7e32d0acd5df976b4eb048ce4205e6b5.png)

Asimismo, se desplegó la primera versión del frontend en Vercel

Link del frontend: [https://med-sync-frontend-4bb8.vercel.app/login](https://med-sync-frontend-4bb8.vercel.app/login)

![](https://gyazo.com/d09523a85b626d63d27426d83a894713.png)

#### Team Collaboration Insights during Sprint

Insights del repositorio: [https://github.com/William062004/MedSync-Api](https://github.com/William062004/MedSync-Api)

![](https://gyazo.com/ab73adaccfb4538732f2ae32470da86f.png)

Insights del repositorio: [https://github.com/Desarrllo-de-Soluciones-IoT-Grupo-4/MedSync-Frontend](https://github.com/Desarrllo-de-Soluciones-IoT-Grupo-4/MedSync-Frontend)

![](https://gyazo.com/dba3e74b392d0e953cce3207addc8a52.png)

# Conclusiones

- Realizar una correcta detección de bounded contexts es crucial para poder identificar los servicios que se desarrollarán en la solución.
- Estudiar el escenario en el que se empleará el software es vital para decidir el tipo de arquitectura que se empleará.
- El alcance del proyecto debe ser bien definido para tener una idea clara de qué dispositivos se necesitarán adquirir para lograr este.

# Bibliografía

# Anexos

**Anexo 1**

- Video de entrevistas: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201e465_upc_edu_pe/EaQvOOIttDFKt8FSMPzlqgoB76xM4hqbUw4pZFTKLzBITQ?e=kq5WWo](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201e465_upc_edu_pe/EaQvOOIttDFKt8FSMPzlqgoB76xM4hqbUw4pZFTKLzBITQ?e=kq5WWo)

**Repositorio del landing page:**<br>
[https://github.com/EUrbizagastegui/MedSync-Landing-Page](https://github.com/EUrbizagastegui/MedSync-Landing-Page)

**Repositorio de la aplicación móvil:**<br>
[https://github.com/Desarrllo-de-Soluciones-IoT-Grupo-4/MedSync-Frontend-Mobile](https://github.com/Desarrllo-de-Soluciones-IoT-Grupo-4/MedSync-Frontend-Mobile)

**Repositorio de la app web:**<br>
[https://github.com/Desarrllo-de-Soluciones-IoT-Grupo-4/MedSync-Frontend](https://github.com/Desarrllo-de-Soluciones-IoT-Grupo-4/MedSync-Frontend)

**Repositorio del landing page:**<br>
[https://github.com/Desarrllo-de-Soluciones-IoT-Grupo-4/MedSync-Api](https://github.com/Desarrllo-de-Soluciones-IoT-Grupo-4/MedSync-Api)

**App Web Desplegada:**<br>
[https://med-sync-frontend-4bb8.vercel.app/](https://med-sync-frontend-4bb8.vercel.app/)