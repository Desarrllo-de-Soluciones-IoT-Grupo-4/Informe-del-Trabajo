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

**<h3>Setiembre, 2024</h3>**

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
|--------------|--------------|--------------|--------------|
| 1           | 05/09/2023      | - Alonso Fernando Robles Astuñaupa<br>- Erick Armando Cueva Elera<br>- Erick Gabriel Urbizagastegui Alvarez<br>- Mijael Alexander Imanol Yen Quispe<br>- William Ramos Vicente    | Implementación del capítulo 1 al 4      |

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
      - [Software Architecture Container Level Diagrams](#software-architecture-container-level-diagrams)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

# Student Outcome

| Criterio Específico | Acciones realizadas | Conclusiones |
|---------|---------|---------|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta | **TB1**<br><br>*Alonso Robles*<br><br>Elabore los as y to be scenario mapping<br><br>*Erick Armando Cueva Elera*<br><br>Elaboré los user persona<br><br>*Erick Gabriel Urbizagastegui Alvarez*<br><br>Elaboré la arquitectura de la solución<br><br>*Mijael Alexander Imanol Yen Quispe*<br><br>Elaboré los diagramas de bounded contexts y entrevistas<br><br>*William Ramos Vicente*<br><br>Elaboré el diseño de las entrevistas y su análisis<br><br>|**TB1**<br><br>CONCLUSION<br><br>|
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. | **TB1**<br><br>*Alonso Robles*<br><br>Elabore los as y to be scenario mapping<br><br>*Erick Armando Cueva Elera*<br><br>Elaboré los user persona<br><br>*Erick Gabriel Urbizagastegui Alvarez*<br><br>Elaboré la arquitectura de la solución<br><br>*Mijael Alexander Imanol Yen Quispe*<br><br>Elaboré los diagramas de bounded contexts y entrevistas<br><br>*William Ramos Vicente*<br><br>Elaboré el diseño de las entrevistas y su análisis<br><br>| **TB1**<br><br>CONCLUSION<br><br> |

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

![Imgur](https://i.imgur.com/GHaRGNq.png)

**Erick Armando Cueva Elera (u201910151)**

![Imgur](/Resources/erickC.png)

**Erick Gabriel Urbizagastegui Alvarez (u20201e465)**

![Imgur](/Resources/erickU.png)

**Mijael Alexander Imanol Yen Quispe (u202010305)**

![Imgur](/Resources/mijael.png)

**William Ramos Vicente (u202117904)**

![Imgur](/Resources/william.png)

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

![Imgur](/Resources/eChristian.png)

**Nombre:** Cristian Luis Iparraguirre Rueda

**Edad:** 20

**Resumen:** Cristian empieza contándonos el diagnóstico de su condición cardiaca, el cual es hipertensión arterial, lo que ha llevado a estar durante 2 años en tratamiento, implicando monitoreo manual y consultas periódicas al doctor. Nos comenta que a veces se olvida de tomarse la presión en casa, además de que se le hace tedioso llevar el registro de los medicamentos que toma. Considera importante que un dispositivo que le tome la presión debe ser de uso fácil y sobre todo preciso con las mediciones. Además, desearía que fuese discreto, fácil de llevar y que pueda integrarse con diferentes dispositivos de uso diario. Una de sus principales preocupaciones es la precisión de la medición del dispositivo, además de que recibir tantas notificaciones podrían provocarle ansiedad. Por último, considera indispensable que el dispositivo muestre métricas de su presión a lo largo del tiempo, teniendo valores máximos y mínimos, además de recibir notificaciones en caso una medición salga de su rango.

**Entrevista 2**

![Imgur](/Resources/eLuis.png)

**Nombre:** Luis Trujillo

**Edad:** 25

**Resumen:** Luis nos cuenta que sufre de hipertensión arterial y arritmia, lo cual lo hace más propenso a sufrir ataques cardíacos y accidentes cerebrovasculares. Lleva aproximadamente 4 años en tratamiento, lo que implica monitoreo desde su casa y visitas constantes al cardiólogo. Luis comenta que se le hace incómodo llevar instrumentos para medir su ritmo cardíaco, además que los considera incómodos y no muy precisos. Considera que lo más importante que debe tener un instrumento para su medición del ritmo cardiaco es que debe ser preciso y fácil de usar, además de registrar todas las lecturas y tener la opción de compartirlas. También comenta que preferiría que las notificaciones le lleguen al teléfono móvil, a modo de notificación corta y concisa, o mediante sms o llamada. Sus mayores preocupaciones son que el dispositivo no sea preciso y que pueda llegar a tener alguna falla al detectar alguna anomalía. Por último agrega que le gustaría que contara con un botón de emergencia para poder alertar a quien necesite.

**Entrevista 3**

![Imgur](/Resources/eValeria.png)

**Nombre:** Valeria Nevado

**Edad:** 21

**Resumen:** Valeria nos cuenta que ella padece de una arritmia, la cual necesita ser monitorizada con frecuencia, en la cual lleva 2 años de tratamiento y monitoreo. El monitoreo lo realiza principalmente en sus visitas médicas, y en su casa usa un oxímetro. Nos señala que el oxímetro le parece útil porque su precisión es muy buena, sin embargo, tiende a malograrse muy rápido. También nos señala que lo más importante de un dispositivo que mida la frecuencia cardiaca debe ser la precisión, además de que le gustaría que la batería tenga una larga duración y sea resistente al agua. Además, nos comenta que le gustaría que el dispositivo fuera fácil de transportar, y que la información mostrada debería ser principalmente su historial de ritmo cardiaco, además de un resumen semanal o mensual y que en base a esto hayan recomendaciones personalizadas. Nos cuenta también que su mayor preocupación son las posibles malas lecturas del dispositivo, ya que esto supondría preocuparse ella y su familia por falsa información. Por último añade que le gustaría que el dispositivo también funcione en sus horas de sueño, así podría saber cómo se comporta su corazón mientras descansa.

**Entrevistas a contactos de emergencia:**

**Entrevista 1**

![Imgur](/Resources/eAlessandro.png)

**Nombre:** Alessandro Ramiro Condori Lozano

**Edad:** 21

**Resumen:** Alessandro nos cuenta que él está a cargo de su primo, el cual es el paciente con problemas cardiacos y el cual estaría interesado en usar nuestro dispositivo. Actualmente la información que recibe de la persona a su cargo es mediante informes médicos. Nos cuenta además que le gustaría recibir notificaciones en caso haya algún cambio en la frecuencia del ritmo cardíaco del paciente, y que estas notificaciones no puedan ser ignoradas, el cual es su mayor miedo, por lo que piensa que deberían ser mediante una alarma o una llamada telefónica. También, nos comenta que la información más relevante debe ser su ritmo cardiaco, además de un historial de este mismo para detectar cualquier anomalía. Por último, indica que le gustaría que el dispositivo también mida la presión y la glucosa. Así como también le gustaría tener una conexión más directa con el paciente para tener más información en todo momento, no solamente mediante informes médicos.

**Entrevista 2**

![Imgur](/Resources/eLiliana.png)

**Nombre:** Liliana Fu Ye

**Edad:** 23

**Resumen:** Lilliana nos comenta que cuida a su abuelo de 78 años, quien sufre problemas de corazón. Actualmente la información que recibe es por medio de citas médicas y mediante una máquina que tiene en su casa que mide la presión. Nos comenta que, ella prefiere que ante cualquier anomalía en el ritmo cardíaco de su paciente, reciba una notificación y en base a ello ponerse en contacto con su médico para realizar los respectivos procedimientos. Y en caso la anomalía fuese muy grave, priorizar el contacto con la clínica. Añade que la información que ella considera indispensable en el dispositivo es el registro de pulsaciones del paciente, para poder identificar los rangos normales y hacer un seguimiento más detallado Además, añade que el dispositivo debe ser cómodo y el doctor asignado debe tener acceso a la información. Por último, señala que las mediciones deben ser precisas, para que no realice notificaciones erróneas, y , que debe tener un botón para comunicarse directamente y lo más antes posible con ella en caso se necesite.

**Entrevista 3**

![Imgur](/Resources/eJoaquin.png)

**Nombre:** Joaquin Pinto

**Edad:** 21

**Resumen:** Joaquin nos cuenta que su tío es la persona que tiene los problemas en el corazón, en donde la información que recibe actualmente es por medio de visitas de su tío a su casa o por medio de conversaciones con sus padres. También nos indica que él preferiría recibir las alertas mediante mensajes de WhatsApp, ya que es el medio al que más pendiente está, o, en caso sea urgente, por medio de una llamada. Nos añade que el dispositivo debe medir el ritmo cardiaco exacto y que podría significar. Además de registrar un historial de su ritmo cardiaco durante el día. Nos comenta que una de sus mayores preocupaciones es recibir la alerta tarde o no recibirla. Por último, señala que el dispositivo debería mandar la alerta y que esta se sobreponga al resto de notificaciones, ya que es la más importante y no debería ser capaz de ser ignorada. 

### Análisis de entrevistas 



## Needfinding

### User Personas

**Paciente**

![Image from Gyazo](https://gyazo.com/d6037819b1f2ea2199e67bf70d0a4791.png)

**Contacto de emergencia**

![Image from Gyazo](https://i.gyazo.com/5138273c81832215e01cbef18d956587.png)(https://gyazo.com/5138273c81832215e01cbef18d956587)

### User Task Matrix

![Imgur](/Resources/userTaskMatrix1.png)
![Imgur](/Resources/userTaskMatrix2.png)

### User Journey Mapping



### Empathy Mapping

**Paciente**

![Imgur](/Resources/eMap1.png)

**Contacto de emergencia**

![Imgur](/Resources/eMap2.png)

### As-is Scenario Mapping

**Paciente**

![Imgur](/Resources/aSM1.png)

**Contacto de emergencia**

![Imgur](/Resources/aSM2.png)

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

![Imgur](/Resources/tBM1.png)

**Contacto de emergencia**

![Imgur](/Resources/tBM2.png)

### User Stories

![Imgur](/Resources/us1.png)
![Imgur](/Resources/us2.png)
![Imgur](/Resources/us3.png)
![Imgur](/Resources/us4.png)

### Impact Mapping



### Product Backlog

![Imgur](/Resources/pb1.png)
![Imgur](/Resources/pb2.png)
![Imgur](/Resources/pb3.png)

# Capítulo IV: Solution Software Design

## Strategic-Level Attribute-Driven Design

### Event Storming

#### Candidate Context Discovery

Durante el proceso se realizaron los siguientes pasos: identificación de los eventos claves del negocio; identificación de acciones de los actores; identificación de disparadores e identificación de bounded contexts.

![Imgur](/Resources/ccd1.png)
![Imgur](/Resources/ccd2.png)
![Imgur](/Resources/ccd3.png)
![Imgur](/Resources/ccd4.png)

#### Domain Message Flows Modeling

**Paciente mide su ritmo cardiaco**

Primero el BC de Gestión del sensor deberá preparar este para medir el ritmo cardiaco; luego el paciente insertará su dedo en el dispositivo y el BC de Monitoreo del paciente recopilará la data, para posteriormente avisar al BC Notificaciones que avise a los contactos de emergencia del paciente.

#### Bounded Context Canvases

### Context Mapping

A continuación, se presenta el context mapping elaborado para nuestra solución. Este representa el cómo se comportan y colaboran los BC entre sí y de qué depende que esto suceda.

![Imgur](/Resources/cm.png)

### Software Architecture

#### Software Architecture System Landscape Diagram

![Imgur](/Resources/dc.png)

#### Software Architecture Container Level Diagrams

![Imgur](/Resources/dcon.png)

# Conclusiones



# Bibliografía



# Anexos

**Anexo 1**

Video de entrevistas: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201e465_upc_edu_pe/EaQvOOIttDFKt8FSMPzlqgoB76xM4hqbUw4pZFTKLzBITQ?e=kq5WWo](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201e465_upc_edu_pe/EaQvOOIttDFKt8FSMPzlqgoB76xM4hqbUw4pZFTKLzBITQ?e=kq5WWo)