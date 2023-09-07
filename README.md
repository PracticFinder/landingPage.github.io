![Logo UPC](https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png)

Universidad Peruana de Ciencias Aplicadas

Ingeniería de Software

Ciclo 2023-02

# Desarrollo de Aplicaciones Open Source
## TB1 REPORT

Sección: SW54

**Profesor:** Hugo Allan Mori Paiva

***INFORME DE TRABAJO FINAL - TB1***

**Startup:** PractiFinder

**Producto:** PractiFinder

**Integrantes:**

- Alejo Cardenas, Luis Angel                (U202122519)
- Moreno Vergara, Johan Raúl                (U20201C105)
- Primo Estrada, Rafael Wimmer              (U202023137)
- Trujillo Acosta, Enzo Paolo				(U202120379)

Link al video de exposición: [Youtube]()

Agosto del 2023

---
# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de la modificación |

<table border="1" width="70%" style="text-align:center;">
    <thead>
        <tr style="background-color: #a4c2f4;">
            <th><b>Versión</b></th>
            <th><b>Fecha</b></th>
            <th><b>Autor</b></th>
            <th><b>Descripción de modificación</b></th>
        </tr>
    </thead>
    <tbody style="text-align:left;">
        <tr>
            <td rowspan="4">TB1</td>
            <td rowspan="4">11/09/2023</td>
            <td>Alejo Cardenas, Luis Angel</td>
            <td>Registrarme</td>
        </tr>
        <tr>
            <td>Moreno Vergara, Johan Raúl</td>
            <td>Iniciar sesión</td>
        </tr>
        <tr>
            <td>Primo Estrada, Rafael Wimmer</td>
            <td>Recuperar contraseña</td>
        </tr>
        <tr>
            <td>Trujillo Acosta, Enzo Paolo	</td>
            <td>Salir o borrar la cuenta</td>
        </tr>
    </tbody>
    
</table>


---
# Project Report Collaboration Insights

Link de repositorio Github: 

---
# Contenido 
## Tabla de Contenido
 [Student Outcome](#student-outcome)<br>
 [Capítulo I: Introducción](#capítulo-i-introducción)<br>
   [1.1. Startup Profile](#11-startup-profile)<br>
     [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)<br>
     1.1.2. [Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)<br>
   [1.2. Solution Profile](#12-solution-profile)<br>
     [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)<br>
     [1.2.2 Lean UX Process](#122-lean-ux-process)<br>
       [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)<br>
       [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)<br>
       [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)<br>
       [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)



---
# Student Outcome

_ABET – EAC - Student Outcome 3: Capacidad de comunicarse efectivamente con un rango de audiencias_

<br>

| Criterio específico | Acciones realizadas | Conclusiones |
| - | - | - |
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. | | |
| Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. | | |

---

# Capítulo I: Introducción

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

Nuestra startup denominada “PractiFinder” es una plataforma en línea enfocada a estudiantes universitarios de últimos ciclos o recién egresados que tiene como objetivo ayudarlos a buscar prácticas universitarias o su primer empleo.<br>
PractiFinder busca conectar estudiantes con empresas mediante la creación de perfiles detallados en donde cada universitario podrá resaltar sus habilidades y logros académicos. De esta forma, brindamos a las empresas una nueva solución para descubrir y contratar nuevos talentos emergentes. Por otro lado, las empresas pueden publicar ofertas de prácticas y empleos dirigidas exclusivamente a estudiantes y recién graduados.<br>
Nuestra misión es facilitar la transición exitosa entre estudiantes y recién regresados al mundo laboral y proporcionar a las empresas una fuente confiable de nuevos talentos. PractiFinder busca crear un puente entre el mundo académico y el mundo profesional impulsando el crecimiento personal y desarrollo empresarial en una sola plataforma de manera segura, transparente y dinámica. 


### 1.1.2. Perfiles de integrantes del equipo

<table border="1" width="70%" style="text-align:center;">
    <tbody style="text-align:left;">
        <tr >
            <td><img src="https://cdn.discordapp.com/attachments/1146490170917535764/1148756119347544094/43178475.png" alt="StudiStay" width="1000px"</td>
            <td style="text-align:left;"><b>Alejo Cardenas, Luis Angel</b><br>
<em>Ingeniería de Software</em><br>
Soy un estudiante de la carrera de Ingeniería de Software cursando mi 5to ciclo en la Universidad Peruana de Ciencias Aplicadas. Tengo conocimientos en programación en C++, Python, HTML y CSS. Además, soy bueno haciendo cálculos matemáticos, me comprometo a apoyar a mi equipo en todo lo posible y ser responsable con cada actividad que se me asigne.</td>
        </tr>
    </tbody>
    <tbody style="text-align:left;">
        <tr >
            <td><img src="https://cdn.discordapp.com/attachments/906396646886223913/1149023245484441620/image.png" alt="StudiStay" width="1000px"</td>
            <td style="text-align:left;"><b>Moreno Vergara, Johan Raúl</b><br>
<em>Ingeniería de Software</em><br>
Soy estudiante de la carrera de Ingeniería de Software. Tengo conocimientos en lenguajes como C++, Python, HTML, CSS y un poco de JavaScript. Me gusta entrenar, hace poco me aceptaron en la selección de Sanda de la UPC. Me comprometo a usar mis conocimientos para hacer un buen trabajo junto a mis compañeros.</td>
        </tr>
    </tbody>
    <tbody style="text-align:left;">
        <tr >
            <td><img src="https://cdn.discordapp.com/attachments/906396646886223913/1149023301419663410/image.png" alt="StudiStay" width="1000px"</td>
            <td style="text-align:left;"><b>Primo Estrada, Rafael Wimmer</b><br>
<em>Ingeniería de Software</em><br>
Soy un estudiante de la carrera de Ingeniería de Software cursando mi 5to ciclo en la Universidad Peruana de Ciencias Aplicadas. Tengo conocimientos en programación en C++, C#, Java, Kotlin, HTML y CSS. Además, me comprometo a apoyar responsablemente y ser puntual a mi grupo con lo que se me asigne del trabajo final y en cada actividad de este curso. </td>
        </tr>
    </tbody>
    <tbody style="text-align:left;">
        <tr >
            <td><img src="https://cdn.discordapp.com/attachments/906396646886223913/1149023433649307799/image.png" alt="StudiStay" width="1000px"</td>
            <td style="text-align:left;"><b>Trujillo Acosta, Enzo Paolo	</b><br>
<em>Ingeniería de Software</em><br>
Soy un estudiante de la carrera de Ingeniería de Software cursando mi 5to ciclo en la Universidad Peruana de Ciencias Aplicadas. Tengo conocimientos en programación en C++, Python y Java. Además, me gusta bastante analizar y resolver problemas usando la lógica. Me comprometo a apoyar a mi equipo en la organización y en cada activa que se nos asigne y estoy dispuesto a aprender y crecer continuamente en mi carrera de ingeniería de software.</td>
        </tr>
    </tbody>
</table>

## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática
- <b>WHAT?</b><br>
    <p>El problema percibido por nuestra Startup es la dificultad que tiene el estudiante que busca             prácticas preprofesionales en alguna empresa; por parte de la empresa, el problema de evaluar a los         practicantes para asegurarse que son competentes y cumplen con las habilidades requeridas para el oficio     a realizar.</p>
- <b>WHY?</b><br>
    <p>Se presentan muchas dificultades al momento de postular como practicante, por ejemplo, las habilidades, conocimientos que uno posee, las entrevistas y controles de evaluación de las empresas. Así mismo, las empresas tienen que gestionar las miles de solicitudes a diferentes puestos de trabajo, generar preguntas específicas, arreglar un horario y delegar a alguien para las entrevistas.</p>
- <b>WHO?</b><br>
    <p>El problema involucra a los estudiantes que buscan prácticas preprofesionales, puesto que tienen que ir a entrevistas y mantenerse en comunicación con las empresas; estas últimas también están involucradas, ya que gestionar y evaluar a todos los practicantes es difícil.</p>
- <b>WHEN?</b><br>
    <p>El problema sucede cuando el estudiante postula como practicante a una empresa y esta tiene que contactarse con el postulante para acordar una fecha en la cual será entrevistado y evaluado por la empresa.</p>
- <b>WHERE?</b><br>
    <p>El problema se encuentra en las medianas y grandes empresas, ya que son estas las que ofrecen puestos como practicantes, y gestionan las entrevistas y evaluaciones.</p>
- <b>HOW?</b><br>
    <p>Usualmente el problema se da luego de postular como practicante, ya que debes esperar a que la empresa te contacte, luego acordar una fecha en la que ambos coincidan para la entrevista, por último esperar a ser evaluado y te informen si eres aceptado o no en la empresa.</p>
- <b>HOW MUCH?</b><br>
    <p>El costo de nuestra app dependerá de las diferentes herramientas que utilicemos y funcionalidades que     le proporcionamos a los usuarios como por ejemplo, un chat bidireccional entre usuarios, filtro de          búsqueda,     publicaciones o postulaciones, entre otras funcionalidades, además de brindarle una           experiencia única y         cómoda al hacer uso de nuestra aplicación. </p><br>

### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.
- Problem Statement 1<br>
    <p>Las empresas enfrentan dificultades al seleccionar candidatos entre un gran número de postulantes. La     falta de un sistema eficiente para diferenciar a los aspirantes dificulta el proceso de selección, lo       que a su vez retrasa la contratación de nuevos talentos.</p>
- Problem Statement 2<br>
    <p>Los postulantes, especialmente aquellos sin experiencia previa, encuentran dificultades para acceder a oportunidades de prácticas y empleos. La falta de una plataforma que les brinde orientación y la oportunidad de demostrar sus habilidades obstaculiza su entrada en el mundo laboral. </p>
- Problem Statement 3<br>
    <p>Tanto las empresas como los aspirantes a menudo luchan por encontrar la correspondencia adecuada entre las habilidades y los requisitos del puesto. Esto conduce a una alta tasa de incompatibilidad, lo que resulta en la frustración tanto para las empresas como para los candidatos.</p>
- Problem Statement 4<br>
    <p>Los aspirantes enfrentan dificultades para demostrar sus conocimientos y habilidades en situaciones prácticas relevantes. La falta de una plataforma que les permita poner a prueba sus capacidades y recibir retroalimentación valiosa dificulta su proceso de búsqueda de empleo.</p>
- Problem Statement 5<br>
    <p>Existe una brecha entre lo que se enseña en entornos académicos y lo que se requiere en el mundo laboral. Los recién graduados y aquellos en transición de carrera carecen de oportunidades para aplicar sus conocimientos teóricos en situaciones laborales reales, lo que limita su empleabilidad.</p>
- Problem Statement 6<br>
    <p>Tanto los aspirantes como las empresas carecen de una plataforma integral que combine la búsqueda de oportunidades de prácticas y empleos con recursos de desarrollo profesional. La ausencia de un espacio donde los candidatos puedan mejorar continuamente sus habilidades y las empresas puedan identificar y nutrir el talento limita el crecimiento de ambas partes.</p><br>

#### 1.2.2.2. Lean UX Assumptions.
<b>Business Assumptions:</b><br>
<p><b>Creo que mis usuarios necesitan</b> una manera efectiva de encontrar oportunidades de prácticas y empleo, independientemente de su nivel de experiencia, brindándoles la posibilidad de evaluar sus conocimientos y asegurar su primer puesto de práctica o trabajo. Simultáneamente, esta aplicación permitirá a las empresas descubrir nuevos candidatos para sus vacantes laborales, al simplificar el arduo proceso de selección y facilitar la identificación de talento fresco en sus equipos.</p>
<p><b>Estas necesidades se pueden resolver</b> mediante una plataforma en línea que facilite a los usuarios encontrar prácticas laborales relevantes, ofreciendo una experiencia intuitiva y funcionalidades valiosas a un costo asequible.</p>
<p><b>Mis clientes iniciales</b> son tanto estudiantes que buscan prácticas laborales como empresas que buscan candidatos para prácticas o empleos.</p>
<p><b>El valor #1 que el cliente requiere de mi servicio</b> es la facilidad de búsqueda y aplicación a prácticas laborales, además de la garantía de encontrar oportunidades legítimas y de calidad que se ajusten a sus habilidades y metas.</p>
<p><b>El cliente también puede obtener estos servicios adicionales</b>, como la creación de perfiles personalizados, asesoramiento para entrevistas, notificaciones oportunas sobre nuevas oportunidades, recursos educativos y la posibilidad de interactuar con profesionales de otras regiones.</p>
<p><b>Voy a adquirir a mis clientes a través de</b> estrategias de marketing digital en plataformas como LinkedIn, Instagram, Facebook y Twitter. Además, se considerará la colaboración con universidades, ferias de empleo y referencias de usuarios satisfechos.</p>
<p><b>Mi competencia en el mercado son plataformas</b> similares que conectan a candidatos con oportunidades laborales. Sin embargo, mi ventaja radicarà en ofrecer una experiencia más personalizada y centrada en el usuario, al brindar herramientas para demostrar habilidades, acceso a recursos educativos y recomendaciones específicas.</p>
<p><b>Los venceremos debido a que</b> ofreceremos una interfaz más intuitiva, una amplia gama de oportunidades de prácticas, servicios adicionales exclusivos y una mayor atención al cliente.</p>
<p><b>Mis mayores riesgos de producto son garantizar</b> que la plataforma esté en funcionamiento constante, ya que estará en uso a nivel internacional. Para abordar esto, trabajaremos en un robusto proceso de desarrollo y realizaremos pruebas exhaustivas antes del lanzamiento. Además, implementará un sistema de soporte para resolver cualquier problema técnico de manera eficiente.</p>
<p><b>Resolveremos esto</b> llevando a cabo investigaciones exhaustivas de mercado y entrevistas con los usuarios para entender sus necesidades y preferencias. Esto me ayudará a crear una plataforma que satisfaga sus requisitos y a construir relaciones sólidas con los usuarios a lo largo del tiempo.</p><br>
<b>Users assumptions</b><br>
<b>¿Quién es el usuario?</b>

- <p>Personas que buscan oportunidades de prácticas laborales o empleo, independientemente de su nivel de experiencia laboral.</p>
- <p>Empresas que buscan candidatos para prácticas laborales o empleo.</p>

<b>¿Dónde encaja nuestro servicio en su trabajo o vida?</b>

- <p> Para los usuarios que buscan oportunidades de prácticas laborales o empleo, nuestro servicio encaja cuando están en búsqueda activa de oportunidades profesionales, así como cuando desean mejorar sus habilidades y experiencia. </p>
- <p> Para las empresas, encaja en su proceso de selección de candidatos para prácticas laborales o empleo, ayudándoles a encontrar candidatos calificados de manera más eficiente. </p>

<b>¿Qué problema resuelve nuestro servicio y cómo lo resuelve?</b>

- <p> Un problema común para los usuarios es la dificultad para encontrar oportunidades de prácticas laborales o empleo que se ajusten a sus habilidades y metas. Nuestro servicio resuelve este problema al proporcionar una plataforma centralizada y fácil de usar para buscar y aplicar a oportunidades relevantes. </p>
- <p> Otro problema es la falta de confianza en la calidad de las oportunidades de prácticas laborales o empleo encontradas en línea. Nuestro servicio aborda esto al verificar y validar las oportunidades publicadas en la plataforma, garantizando que sean legítimas y de calidad.  </p>
- <p> Para las empresas, el desafío puede ser el proceso de selección de candidatos, que a menudo es costoso y consume mucho tiempo. Nuestro servicio simplifica este proceso al proporcionar herramientas de filtrado y clasificación de candidatos basadas en sus habilidades y experiencia, lo que ahorra tiempo y recursos. </p>
- <p> Además, nuestro servicio ayuda a los usuarios a mejorar sus posibilidades de éxito en sus búsquedas profesionales al ofrecer servicios adicionales, como asesoramiento para entrevistas y recursos educativos. </p>

<b>¿Cuándo y cómo se utiliza nuestro servicio?</b>

- <p> Los usuarios utilizan nuestro servicio cuando están activamente buscando oportunidades de prácticas laborales o empleo. Lo utilizan para buscar, aplicar y gestionar sus solicitudes, así como para acceder a recursos de mejora profesional. </p>
- <p> Las empresas utilizan nuestro servicio cuando desean encontrar candidatos para prácticas laborales o empleo. Lo utilizan para publicar oportunidades, revisar y clasificar candidatos, y agilizar su proceso de selección. </p>
- <p> Tanto los usuarios como las empresas acceden a nuestro servicio a través de una plataforma en línea, ya sea desde un navegador web o una aplicación web. </p>

<b>Users outcomes</b>

- <p> Acceso a Oportunidades Laborales Relevantes </p>
- <p> Ahorro de Tiempo en la Búsqueda de Empleo </p>
- <p> Gestión Efectiva de Trabajos </p>
- <p> Interfaz Intuitiva para Todos </p>

<b>Business outcomes</b>

- <p> Facilitar la búsqueda efectiva de oportunidades laborales y prácticas. </p>
- <p> Promover la colocación exitosa de candidatos en oportunidades de empleo y prácticas. </p>
- <p> Minimizar el tiempo necesario para que los usuarios encuentren oportunidades laborales adecuadas. </p>
- <p> Fomentar una alta tasa de éxito en la colocación de candidatos en empleos y prácticas deseadas. </p>
- <p> Mantener un alto nivel de satisfacción de los usuarios al encontrar oportunidades laborales y prácticas adecuadas. </p>
- <p> Facilitar la comunicación eficaz entre candidatos y empleadores durante el proceso de selección. </p>

<b>Features</b><br>
<b>¿Qué características son importantes?</b>

- <p> Un motor de búsqueda robusto que permita a los usuarios buscar oportunidades laborales y prácticas con filtros avanzados, como ubicación, industria, nivel de experiencia y más. </p>
- <p> Perfiles de usuario personalizables que incluyen detalles como experiencia laboral, educación, habilidades y logros. </p>
- <p> Validación y verificación de oportunidades laborales y prácticas para garantizar su autenticidad. </p>
- <p> Herramientas de comunicación que permitan a usuarios y empresas interactuar de manera efectiva en la plataforma. </p>
- <p> Acceso a recursos educativos, guías de entrevistas, cursos en línea y consejos para el desarrollo profesional. </p>
- <p> Un sistema de calificación y comentarios para usuarios y empresas. </p>
- <p> Un calendario integrado para programar citas y gestionar trabajos anteriores y actuales. </p>
- <p> Notificaciones personalizadas sobre oportunidades laborales, solicitudes de entrevistas y actualizaciones de perfiles. </p>

<b>¿Cómo debería verse y comportarse nuestro servicio?</b>

- <p> El motor de búsqueda debe presentarse con una interfaz limpia y fácil de usar, permitiendo a los usuarios ajustar sus criterios de búsqueda de manera intuitiva. </p>
- <p> Los perfiles de usuario deben ser fáciles de crear y editar, con un diseño limpio y la posibilidad de cargar currículos y portafolios. </p>
- <p>Las oportunidades validadas deben mostrar un sello de autenticidad en la plataforma para generar confianza entre los usuarios. </p>
- <p> Debe haber opciones de mensajería en tiempo real, notificaciones de estado de solicitud y capacidad de programar entrevistas. </p>
- <p> Los recursos deben estar organizados en secciones fáciles de navegar, con enlaces relevantes en las páginas de oportunidades. </p>
- <p> Debe haber secciones de calificación y comentarios en los perfiles de usuarios y empresas, con la capacidad de ver opiniones de otros usuarios. </p>
- <p> El calendario debe ser fácil de usar, con opciones de programación y visualización de trabajos pasados y futuros. </p>
- <p> Los usuarios deben poder personalizar sus preferencias de notificación y recibir alertas relevantes. </p>

#### 1.2.2.3. Lean UX Hypothesis Statements.
<b>¿Cómo debería verse y comportarse nuestro servicio?</b>

- <p> El motor de búsqueda debe presentarse con una interfaz limpia y fácil de usar, permitiendo a los usuarios ajustar sus criterios de búsqueda de manera intuitiva. </p>
- <p> Los perfiles de usuario deben ser fáciles de crear y editar, con un diseño limpio y la posibilidad de cargar currículos y portafolios. </p>
- <p>Las oportunidades validadas deben mostrar un sello de autenticidad en la plataforma para generar confianza entre los usuarios. </p>
- <p> Debe haber opciones de mensajería en tiempo real, notificaciones de estado de solicitud y capacidad de programar entrevistas. </p>
- <p> Los recursos deben estar organizados en secciones fáciles de navegar, con enlaces relevantes en las páginas de oportunidades. </p>
- <p> Debe haber secciones de calificación y comentarios en los perfiles de usuarios y empresas, con la capacidad de ver opiniones de otros usuarios. </p>
- <p> El calendario debe ser fácil de usar, con opciones de programación y visualización de trabajos pasados y futuros. </p>
- <p> Los usuarios deben poder personalizar sus preferencias de notificación y recibir alertas relevantes. </p>

#### 1.2.2.4. Lean UX Canvas.
<td align="center">
<img src="https://cdn.discordapp.com/attachments/906396646886223913/1149119188678479942/image.png?ex=64fa5824&is=64f906a4&hm=6f330c0baa7f54300ed7a520bf3f749d40eab8d44798a8a4868ea25ef1dcec5a&" alt="StudiStay" width="600px">
</td>


### 1.3. Segmentos objetivo.
- <b>Practicante:</b><br>
    <p><b>Estudiantes Universitarios en Búsqueda de Prácticas</b><br>
    <b>- Edad:</b> 18-24 años<br>
    <b>- Descripción: </b>Estudiantes universitarios que desean adquirir experiencia laboral relevante antes de su graduación. Buscan oportunidades de prácticas que se alineen con sus campos de estudio y objetivos profesionales para prepararse mejor para el mercado laboral.<br><br>
    <b>Recién Graduados Sin Experiencia Laboral:</b><br>
    <b>Edad:</b> 22-28 años<br>
<b>Descripción: </b>Personas que han completado su educación universitaria recientemente y carecen de experiencia laboral. Este grupo busca empleos de nivel inicial que estén dispuestos a contratar a candidatos sin experiencia previa. La aplicación les ayuda a demostrar sus habilidades mediante pruebas prácticas.</p>
- <b>Empleador:</b><br>
    <p><b>Emprendimientos en Fase de Expansión:</b><br>
    Empresas jóvenes y en crecimiento que están buscando expandirse y necesitan contratar nuevos talentos para apoyar su desarrollo. Estas empresas a menudo tienen limitaciones de recursos y buscan una manera eficiente de encontrar candidatos adecuados que se ajusten a sus necesidades específicas.</p>
    <p><b>Empresas en Sectores Especializados:</b><br>
    Pequeñas y medianas empresas que operan en sectores altamente especializados y requieren talentos específicos para su expansión. Estas empresas enfrentan desafíos únicos para encontrar candidatos con habilidades especializadas, y la aplicación les permitirá identificar y evaluar a profesionales con experiencia en esos campos.<br><br></p>
    <p><b>Empresas con Crecimiento Rápido:</b><br>
    Empresas que están experimentando un crecimiento rápido y necesitan aumentar su fuerza laboral para satisfacer la demanda. La aplicación sería beneficiosa para estas empresas al proporcionarles una forma ágil y eficiente de acceder a una amplia variedad de candidatos y evaluar sus habilidades a través de pruebas prácticas.<br><br></p>
    
# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores.
### 2.1.1. Análisis competitivo.

<table>
  <tr>
    <th colspan="7" valign="top"><b>Competitive Analysis Landscape</b></th>
  </tr>
  <tr>
    <td colspan="2" rowspan="">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="3">Para evaluar nuestra posición en el mercado, identificar las preferencias del usuario y de esa forma identificar áreas donde PractiFinder podría ofrecer un mejor servicio.</td>
  </tr>
  <tr>
    <td colspan="3">Competidores</td>
    <td colspan="1" valign="top" style="font-weight: bold;">
        Linkedln
        <br>
        <div style="text-align: center; margin-top: 10px;">
                <img src="https://1000marcas.net/wp-content/uploads/2020/01/Logo-Linkedin.png" alt="StudiStay" width="200px">
        </div>
    <td colspan="1" valign="top" style="font-weight: bold;">
    Indeed
    <div style="text-align: center;">
                <img src="https://logos-marcas.com/wp-content/uploads/2021/02/Indeed-Logo.png" alt="Uniplaces" width="200px">
        </div>
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil</p></td>
    <td colspan="2">Overview</td>
    <td colspan="1" valign="top">Red social orientada al uso empresarial, a los negocios y al empleo. Cada usuario libremente revela su experiencia laboral y sus destrezas, la web se encarga de poner en contacto a los empleados y empresas.</td>
    <td colspan="1" valign="top">Es un servicio gratuito donde cada usuario puede subir su CV y activar las alertas para determinadas ofertas laborales.</td>
    
  </tr>
  <tr>
    <td colspan="2">Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
    <td colspan="1" valign="top">Destaca por ser una red profesional global que permite a sus usuarios pertenecer a una amplia red de networking permitiéndoles expandir sus contactos y exponer sus logros. Esto fomenta el desarrollo a largo plazo en el sector en el que se destaquen.</td>
    <td colspan="1" valign="top">Destaca por su enfoque en la búsqueda de empleo. Ofrece a sus usuarios un gran número de listados de oportunidades laborales para que puedan postular. Su valor radica en la simplicidad de la búsqueda de oportunidades laborales.</td>
    
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil de Marketing</p></td>
    <td colspan="2">Mercado objetivo</td>
    <td colspan="1" valign="top">Dirigido principalmente a profesionales, trabajadores autónomos, empresarios y reclutadores. 
</td>
    <td colspan="1" valign="top">Dirigida a una audiencia más amplia que incluye profesionales y personas que buscan satisfacer la necesidad de un empleo inmediato. 
</td>
    
  </tr>
  <tr>
    <td colspan="2">Estrategias de marketing</td>
    <td colspan="1" valign="top">Se enfoca en fomentar el branding personal y la creación de relaciones profesionales. Utiliza publicidad para promover el networking y la construcción de perfiles. 
</td>
    <td colspan="1" valign="top">Su estrategia se centra en la publicidad y la promoción de listados de empleos variados. Su enfoque está en su facilidad de búsqueda y la diversidad de oportunidades laborales.
</td>
    
  </tr>
  <tr>
    <td colspan="1" rowspan="3"><p>Perfil de Producto</p></td>
    <td colspan="2">Productos & Servicios</td>
    <td colspan="1" valign="top">-Perfiles profesionales detallados.<br>
-Herramientas de networking. <br>
-Posibilidad de establecer presencia profesional en línea.
</td>
    <td colspan="1" valign="top">-Listados de empleo de diversas fuentes.<br>
-Búsquedas avanzadas y reseñas de empleados.<br>
-Información sobre empresas.

</td>
    
  </tr>
  <tr>
    <td colspan="2">Precios y Costos</td>
    <td colspan="1" valign="top">Modelo freemium donde los usuarios acceden a funciones básicas de manera gratuita, pero también ofrece una versión premium para reclutadores y profesionales que necesitan una búsqueda avanzada. 
</td>
    <td colspan="1" valign="top">Gratuito para candidatos que decidan buscar empleo, pero para los empleadores que quieran destacar sus listados necesitarán pagar una suscripción premium..</td>
    
  </tr>
  <tr>
    <td colspan="2">Canales de distribución (Web y/o Móvil)</td>
    <td colspan="1" valign="top">-Aplicaciones Web<br>
-App móviles
</td>
    <td colspan="1" valign="top">-Aplicaciones Web<br>
-App móviles
</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="5"><p>Análisis SWOT</p></td>
    
  </tr>
  <tr>
    <td colspan="2">Fortalezas</td>
    <td colspan="1" valign="top">-Amplia red profesional global.<br>
-Contenido educativo para poder desarrollarse profesionalmente.<br>
-Capacidad de establecer presencia profesional en línea.

</td>
    <td colspan="1" valign="top">-Diversidad y cantidad de empleos disponibles.<br>
-Posibilidad de explorar empresas y poder leer la reseña de otros empleados.

</td>
    
  </tr>
  <tr>
    <td colspan="2">Debilidades</td>
    <td colspan="1" valign="top">-Puede no ser exclusivamente orientada a la búsqueda de empleo.<br>
-Usuarios nuevos pueden encontrar su interfaz un poco abrumadora por la cantidad de contenido.

</td>
    <td colspan="1" valign="top">-Podría mejorar más la calidad de relación entre empleadores y candidatos.<br>
-La calidad de los listados de empleo pueden ser variables habiendo algunos empleos muy malos.

</td>
  </tr>
  <tr>
    <td colspan="2">Oportunidades</td>
    <td colspan="1" valign="top">-Tiene potencial para expandir sus servicios a áreas de formación en línea como viene haciéndolo. 
</td>
    <td colspan="1" valign="top">-Podría expandir sus funciones premium para cubrir mejor las necesidades de la empresa.
</td>
  </tr>
  <tr>
    <td colspan="2">Amenazas</td>
    <td colspan="1" valign="top">-La principal amenaza son nuevas plataformas emergentes que destaquen y se centren en la búsqueda de empleo en ciertos sectores.
</td>
    <td colspan="1" valign="top">-La principal amenaza son nuevas plataformas emergentes que destaquen y se centren en la búsqueda de empleo en ciertos sectores.
</td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores.

Enfocarnos en el ámbito empresarial y la búsqueda de prácticas laborales, es de vital importancia mantener un enfoque constante en la mejora continua de la experiencia del usuario. Esto implica una optimización constante de la interfaz de la plataforma, respaldada por una recopilación activa de comentarios de los usuarios para implementar cambios significativos. Además, nuestro compromiso se extiende a brindar contenido educativo de alta calidad que ofrezca un valor concreto a los usuarios, contribuyendo así a su crecimiento profesional y fomentando su compromiso con nuestra plataforma.

Una táctica altamente efectiva es la expansión de nuestros servicios premium para satisfacer las necesidades tanto de los candidatos como de las empresas. Esto puede involucrar la incorporación de características avanzadas de filtrado y búsqueda para los empleadores, así como la inclusión de servicios complementarios para la creación de perfiles y herramientas de networking dirigidas a los candidatos. Además, alentaremos la interacción y el establecimiento de conexiones entre los usuarios a través de grupos especializados, foros de discusión y eventos virtuales, fortaleciendo así las relaciones profesionales y manteniendo a los usuarios activamente comprometidos.

Una estrategia clave radica en la mejora de la calidad de los listados de empleo. Esto implica la implementación de medidas de verificación para asegurar la autenticidad y relevancia de los trabajos publicados, asegurando que sean valiosos para nuestra audiencia. Además, vamos a optimizar la función de búsqueda laboral, proporcionando opciones avanzadas de filtrado que permitan a los usuarios encontrar oportunidades que se alineen con sus habilidades y preferencias particulares.

Además, consideraremos la posibilidad de establecer alianzas estratégicas con instituciones educativas, asociaciones profesionales y empresas relevantes. A través de estas colaboraciones, seremos capaces de ofrecer beneficios exclusivos a los miembros de nuestra plataforma, tales como descuentos en programas de formación, acceso a eventos selectos y oportunidades de networking exclusivas. Esta integración con otros entes y la construcción de relaciones sólidas fortalecerán aún más nuestra propuesta de valor y contribuirán al crecimiento continuo de nuestra plataforma.

## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.

El diseño de entrevista es una gran manera eficaz de conocer a nuestro público objetivo y realizar preguntas según cada segmento objetivo nos permitirá profundizar en cuáles son sus necesidades y objetivos, de tal manera que nos permitirá desarrollar un aplicativo el cual resolverá la mayoría de sus problemas y que les será de gran utilidad.

<p> Preguntas generales:
<br>1. ¿Cuál es tu nombre?
<br>2. ¿Cuál es tu edad?
<br>3. ¿Cuál es tu lugar de residencia?
<br>4. ¿Te consideras introvertido o extrovertido? ¿Por qué?
<br>5. ¿Cómo es tu estilo de vida, eres una persona activa o sedentaria?
<br>6. ¿Podría mencionarnos a qué se dedica actualmente?<br><br>
</p>
<p>Preguntas para reclutadores:
<br>1. ¿Qué complicaciones se presentan al seleccionar postulantes?
<br>2. ¿Qué es lo más difícil al entrevistar a un postulante?
<br>3. ¿Qué es lo más complicado al realizar una evaluación al postulante?
<br>4. ¿De qué manera se comunican con los postulantes?
<br>5. ¿Cuánto tiempo tarda la empresa en darle una respuesta a los postulantes?
<br>6. ¿Cómo se decide que postulante es el más apto para el puesto ofrecido?<br><br>
</p>Preguntas para practicantes
<br>1. ¿Qué complicaciones o limitaciones encuentras al buscar una empresa que busque practicantes?	
<br>2. ¿A cuántas empresas has presentado tu currículum?
<br>3. ¿Cuánto tiempo aproximadamente tarda la empresa en comunicarse contigo?
<br>4. ¿Qué complicaciones o limitantes encuentras durante el proceso de postulación?
<br>5. ¿Alguna vez ha notado que su entrevistador no ha leído tu currículum?
<br>6. ¿Hay algún paso del proceso de postulación que le gustaría agilizar o mejorar? ¿Cuál es y de qué manera le gustaría mejorarlo?
<br><br>Pregunta de cierre
<br>1. El entrevistador presenta de forma breve la Startup ¿Qué le parece nuestra propuesta? ¿Consideras que es una herramienta que le sería útil?

### 2.2.2. Registro de entrevistas.

- <b>Segmento 1: Practicantes</b><br>
    <p><b>ENTREVISTA 1</b><br>
    <u>Datos del entrevistado:</u><br>
    Nombre: César Villena<br>
    Edad: 20 años<br>
    Análisis:
    <br><img src="https://cdn.discordapp.com/attachments/906396646886223913/1149133880209702942/image.png" width="800px">
    <br>Inicio:                                  
    <br>Fin: 
    <br>Enlace de entrevista:
    <br>La entrevista con César proporcionó información valiosa sobre los desafíos que enfrentan los estudiantes al buscar prácticas. Uno de los desafíos principales es que muchas empresas requieren experiencia previa o recomendaciones, lo que puede dificultar la búsqueda para estudiantes sin experiencia. Además, el proceso de comunicación con las empresas a menudo puede ser lento y complicado. César expresó interés en una aplicación web que facilite la búsqueda de prácticas al conectar a estudiantes con empresas de manera más eficiente. También destacó la importancia de la descripción del currículum en la aplicación para ayudar a las empresas a tomar decisiones informadas. Sin embargo, mencionó que una posible preocupación podría ser la mayor competencia entre los estudiantes debido a la mayor accesibilidad de las oportunidades de prácticas.</p>

    <p><b>ENTREVISTA 2</b>*<br>
    <u>Datos del entrevistado:</u><br>
    Nombre: Britney Ramos<br>
    Edad: 19 años<br>
    Análisis:
    <br><img src="https://cdn.discordapp.com/attachments/906396646886223913/1149135568119287858/image.png" width="800px">
    <br>Inicio:                                  
    <br>Fin: 
    <br>Enlace de entrevista:
    <br>La entrevista a Britney nos proporcionó información valiosa sobre cuáles son las dificultades y obstáculos que se les presentan a los estudiantes a la hora de buscar prácticas preprofesionales. Algunas de las varias complicaciones que se le presentan son que las empresas sólo ofrecen puestos a estudiantes en último año o recién graduados y otra complicación es que el proceso de solicitud puede ser largo y un poco tedioso. Nos comenta que la empresa tarda en promedio 1 mes en contactarse con ella. La entrevista mostró interés en nuestra aplicación web, destacando que sería muy útil para estudiantes universitarios que buscan prácticas por el hecho de facilitar el proceso de búsqueda de prácticas, y ayudaría a encontrar oportunidades según sus intereses y habilidades.</p>

<br>

- <b>Segmento 2: Empleadores Practicantes</b><br>
    <p><b>ENTREVISTA 1</b><br>
    <u>Datos del entrevistado:</u><br>
    Nombre: Fabio Portella<br>
    Edad: 23 años<br>
    Análisis:
    <br><img src="https://cdn.discordapp.com/attachments/906396646886223913/1149136401854644304/image.png" width="800px">
    <br>Inicio:                                  
    <br>Fin: 
    <br>Enlace de entrevista:
    <br>La entrevista a Fabio nos proporcionó información valiosa sobre cuáles son las dificultades y obstáculos que se les presentan a los empleadores a la hora de buscar y seleccionar practicantes. Muchas de las complicaciones que se le presentan son preparar preguntas relevantes para el puesto de trabajo y a la vez crear un ambiente agradable para el entrevistado, al realizar una evaluación puede ser compleja por el hecho de que se debe establecer un criterio de evaluación con el fin de evaluar sus habilidades técnicas, teóricas y blandas. Usualmente se comunican por correo electrónico o llamadas telefónicas entre 1 semana a 1 mes, dependiendo del puesto de trabajo y la cantidad de postulantes. Por último, nos mencionas cuales son los puntos más importantes a la hora de seleccionar al postulante más apto, como sus decisiones, habilidades, debe tener una formación educativa adecuada para el puesto, también poseer una personalidad y valores compatibles con la empresa.</p>

### 2.2.3. Análisis de entrevistas.



## 2.3. Needfinding.
### 2.3.1. User Personas.

User Practicante
<img src="https://cdn.discordapp.com/attachments/906396646886223913/1149137885447082044/image.png" width="800px">

<br>

User Empleador
<img src="https://cdn.discordapp.com/attachments/906396646886223913/1149138113717874828/image.png" width="800px">

### 2.3.2. User Task Matrix.
En esta sección presentamos el user task matrix, la cual se centra en los segmentos objetivos (practicante y empleador), que nos permitirá identificar las tareas y objetivos por cumplir de cada segmento objetivo. Para la frecuencia se han considerado cinco opciones: never, rarely, sometimes, often, always; y para la importancia tres opciones: low, medium, high. <br>

<table style="text-align:center;">
  
  <tr>
    <td colspan="2" rowspan="2"><b>User Task</b></td>
    <td colspan="2"><b>Practicante</b></td>
    
  </tr>
  <td colspan >Frequency</td>
  <td colspan >Importance</td>
  
  <tr>
    <td colspan="2" style="text-align:left;">Crear un currículum</td>
    <td colspan="1" valign="top" >
        Sometimes
    </td>
    <td colspan="1" valign="top">
    High
    </td>
  </tr>
  <tr>
    <td colspan="2" style="text-align:left;">Postular a puestos en su área en diferentes empresas</td>
    <td colspan="1" valign="top" >
        Often
    </td>
    <td colspan="1" valign="top">
    High
    </td>
  </tr>
  <tr>
    <td colspan="2" style="text-align:left;">Pactar una fecha para la entrevista con la empresa</td>
    <td colspan="1" valign="top" >
        Always
    </td>
    <td colspan="1" valign="top">
    High
    </td>
  </tr>
  <tr>
    <td colspan="2" style="text-align:left;">Prepararse para entrevistas</td>
    <td colspan="1" valign="top" >
        Rarely
    </td>
    <td colspan="1" valign="top">
    Medium
    </td>
  </tr>
  <tr>
    <td colspan="2" style="text-align:left;">Rendir evaluaciones y/o capacitaciones para el puesto</td>
    <td colspan="1" valign="top" >
        Often
    </td>
    <td colspan="1" valign="top">
    Medium
    </td>
  </tr>
  <tr>
    <td colspan="2" style="text-align:left;">Recibir notificaciones sobre el proceso de postulación y respuesta final</td>
    <td colspan="1" valign="top" >
        Always
    </td>
    <td colspan="1" valign="top">
    Medium
    </td>
  </tr>
  
</table>

<br>

<table style="text-align:center;">
  
  <tr>
    <td colspan="2" rowspan="2"><b>User Task</b></td>
    <td colspan="2"><b>Empleador</b></td>
    
  </tr>
  <td colspan >Frequency</td>
  <td colspan >Importance</td>
  
  <tr>
    <td colspan="2" style="text-align:left;">Revisar currículum del postulante</td>
    <td colspan="1" valign="top" >
        Sometimes
    </td>
    <td colspan="1" valign="top">
    High
    </td>
  </tr>
  <tr>
    <td colspan="2" style="text-align:left;">Pactar una fecha para la entrevista con el postulante</td>
    <td colspan="1" valign="top" >
        Always
    </td>
    <td colspan="1" valign="top">
    Medium
    </td>
  </tr>
  <tr>
    <td colspan="2" style="text-align:left;">Preparar entrevista según el área de trabajo</td>
    <td colspan="1" valign="top" >
        Sometimes
    </td>
    <td colspan="1" valign="top">
    Medium
    </td>
  </tr>
  <tr>
    <td colspan="2" style="text-align:left;">Preparar pruebas de evaluación/capacitación</td>
    <td colspan="1" valign="top" >
        Sometimes
    </td>
    <td colspan="1" valign="top">
    High
    </td>
  </tr>
  <tr>
    <td colspan="2" style="text-align:left;">Seleccionar al postulante más apto</td>
    <td colspan="1" valign="top" >
        Often
    </td>
    <td colspan="1" valign="top">
    High
    </td>
  </tr>
  <tr>
    <td colspan="2" style="text-align:left;">Notificar a los postulante su desempeño durante todo el proceso</td>
    <td colspan="1" valign="top" >
        Always
    </td>
    <td colspan="1" valign="top">
    Medium
    </td>
  </tr>
  
</table>

<br>

De acuerdo con el User Task Matrix podemos reconocer los task de mayor frecuencia e importancia de los segmentos. Así como las principales diferencias y coincidencias con los User Personas.

Con respecto a los postulantes las task con mayor frecuencia son:
- Pactar una fecha para la entrevista con la empresa
- Recibir notificaciones sobre el proceso de postulación y respuesta final

En el proceso de postulación el practicante siempre debe pactará una fecha con la empresa para la entrevista y recibirá notificaciones sobre su proceso y respuesta final de postulación. Las tasks mencionadas para los practicantes son de una frecuencia “Always”.

<br>

Mientras que las task con mayor importancia son:
- Crear un currículum
- Postular a puestos en su área en diferentes empresas
- Pactar una fecha para la entrevista con la empresa

Con respecto a los empleadores las task con mayor frecuencia son:
- Pactar una fecha para la entrevista con el postulante
- Notificar a los postulante su desempeño durante todo el proceso

Las actividades con mayor frecuencia para los empleadores son pactar una fecha con el postulante y notificarle sus avances durante todo el proceso de postulación- Las tasks mencionadas para los empleadores son de una frecuencia “Always”.

Mientras que las task con mayor importancia son:
- Revisar currículum del postulante
- Preparar pruebas de evaluación/capacitación
- Seleccionar al postulante más apto

La diferencia entre las tasks de cada segmento son que los practicantes se preparan para las actividades que la empresa le impondrá, mientras que los empleadores son los que gestionan y preparan todas estas actividades con el fin de encontrar al más indicado para el puesto de trabajo ofrecido.

Con respecto a las coincidencias, ambos User Personas deben llegar a acordar una fecha para realizar la entrevista y mantenerse en contacto para recibir y mandar información si fuera requerida.


### 2.3.3. User Journey Mapping.
User Journey Mapping: Practicante
<img src="https://cdn.discordapp.com/attachments/906396646886223913/1149143861885673483/image.png" width="800px">

<br>

User Journey Mapping: Empleador
<img src="https://cdn.discordapp.com/attachments/906396646886223913/1149143919821594694/image.png" width="800px">

### 2.3.4. Empathy Mapping.

<img src="https://cdn.discordapp.com/attachments/1148837446117752832/1149137598867046420/Empathy_map_3.png" width="800px"><br><br>

<img src="https://cdn.discordapp.com/attachments/1148837446117752832/1149137599315853372/Empathy_map_2.png" width="800px"><br>

### 2.3.5. As-is Scenario Mapping.

As - Is : Escenario cuando el estudiante necesita realizar prácticas
<img src="https://cdn.discordapp.com/attachments/906396646886223913/1149145063914483802/image.png" width="800px">

As - Is : Escenario cuando una empresa necesita contratar practicantes
<img src="https://cdn.discordapp.com/attachments/906396646886223913/1149145118591422535/image.png" width="800px">

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping.

To - Be : Escenario cuando el estudiante necesita realizar prácticas
<img src="https://cdn.discordapp.com/attachments/906396646886223913/1149145694570037318/image.png" width="800px">

To - Be : Escenario cuando una empresa necesita contratar practicantes
<img src="https://cdn.discordapp.com/attachments/906396646886223913/1149145784533667860/image.png" width="800px">

## 3.2. User Stories.

<table border="1" width="70%" style="text-align:center;">
    <thead>
        <tr style="background-color: #a4c2f4;">
            <th><b>EpicID</b></th>
            <th><b>Epic</b></th>
            <th><b>UserStoryID</b></th>
            <th><b>User stories</b></th>
        </tr>
    </thead>
    <tbody style="text-align:left;">
        <tr>
            <td rowspan="4">E01</td>
            <td rowspan="4"><b>Sistema de Inscripción<br>Como</b> usuario  <b>quiero</b> registrarme, logearme y poseer control de mi cuenta <b>para</b>utilizar la aplicación.</td>
            <td style="background-color: #fce5cd;">US01</td>
            <td>Registrarse</td>
        </tr>
        <tr>
            <td style="background-color: #fce5cd;">US02</td>
            <td>Loguearse</td>
        </tr>
        <tr>
            <td style="background-color: #fce5cd;">US03</td>
            <td>Recuperar contraseña</td>
        </tr>
        <tr>
            <td style="background-color: #fce5cd;">US04</td>
            <td>Cerrar sesión o borrar cuenta</td>
        </tr>
    </tbody>
    <tbody style="text-align:left;">
        <tr>
            <td rowspan="4">E02</td>
            <td rowspan="4"><b>Oportunidades de trabajo<br>Como</b> usuario  <b>quiero</b> poder encontrar oportunidades de prácticas <b>para</b> poder postular y aplicar a algún empleo.</td>
            <td style="background-color: #fce5cd;">US05</td>
            <td>Búsqueda de oportunidades laborales</td>
        </tr>
        <tr>
            <td style="background-color: #fce5cd;">US06</td>
            <td>Sugerencia de puestos de trabaj</td>
        </tr>
        <tr>
            <td style="background-color: #fce5cd;">US07</td>
            <td>Comunicación con las empresas</td>
        </tr>
        <tr>
            <td style="background-color: #fce5cd;">US08</td>
            <td>Búsqueda avanzada mediante filtros</td>
        </tr>
    </tbody>
    <tbody style="text-align:left;">
        <tr>
            <td rowspan="4">E03</td>
            <td rowspan="4"><b>Perfil de usuario<br>Como</b> usuario  <b>quiero</b> tener un perfil completo y atractivo <b>para</b> destacar frente a los empleadores y aumentar mis posibilidades de ser seleccionado para prácticas o empleos.</td>
            <td style="background-color: #fce5cd;">US09</td>
            <td>Editar perfil personal</td>
        </tr>
        <tr>
            <td style="background-color: #fce5cd;">US10</td>
            <td>Agregar experiencia académica y laboral</td>
        </tr>
        <tr>
            <td style="background-color: #fce5cd;">US11</td>
            <td>Subir una foto de perfil</td>
        </tr>
        <tr>
            <td style="background-color: #fce5cd;">US12</td>
            <td>Establecer preferencias de búsqueda de empleo</td>
        </tr>
    </tbody>
    <tbody style="text-align:left;">
        <tr>
            <td rowspan="4">E04</td>
            <td rowspan="4"><b>Seguimiento de procesos de selección<br>Como</b> usuario  <b>quiero</b> poder realizar un seguimiento de los procesos de selección en los que estoy participando  <b>para</b> poder saber el estado en el que me encuentro en esa selección.</td>
            <td style="background-color: #fce5cd;">US13</td>
            <td>Ver el estado de mis postulaciones</td>
        </tr>
        <tr>
            <td style="background-color: #fce5cd;">US14</td>
            <td>Recibir notificaciones de cambios en los procesos de selección</td>
        </tr>
        <tr>
            <td style="background-color: #fce5cd;">US15</td>
            <td>Registrar entrevistas y pruebas de selección</td>
        </tr>
        <tr>
            <td style="background-color: #fce5cd;">US16</td>
            <td>Calificar y dejar comentarios sobre los procesos de selección</td>
        </tr>
    </tbody>
    <tbody style="text-align:left;">
        <tr>
            <td rowspan="4">E05</td>
            <td rowspan="4"><b>Publicar y gestionar ofertas de empleo<br>Como</b> usuario  <b>quiero</b> tener la capacidad de publicar nuevas ofertas de empleo en la plataforma <b>para</b> atraer a candidatos calificados.</td>
            <td style="background-color: #fce5cd;">US17</td>
            <td>Publicar nueva oferta de empleo</td>
        </tr>
        <tr>
            <td style="background-color: #fce5cd;">US18</td>
            <td>Editar ofertas de empleo</td>
        </tr>
        <tr>
            <td style="background-color: #fce5cd;">US19</td>
            <td>Gestionar postulaciones</td>
        </tr>
        <tr>
            <td style="background-color: #fce5cd;">US20</td>
            <td>Comunicación con candidatos</td>
        </tr>
    </tbody>
    <tbody style="text-align:left;">
        <tr>
            <td rowspan="4">E06</td>
            <td rowspan="4"><b>Evaluar y seleccionar candidatos<br>Como</b> usuario  <b>quiero</b> disponer de herramientas efectivas <b>para</b> evaluar los perfiles de los candidatos, colaborar con el equipo de selección en la toma de decisiones, y extender ofertas de empleo de manera eficiente.</td>
            <td style="background-color: #fce5cd;">US21</td>
            <td>Evaluar perfiles de candidatos</td>
        </tr>
        <tr>
            <td style="background-color: #fce5cd;">US22</td>
            <td>Colaboración en la toma de decisiones</td>
        </tr>
        <tr>
            <td style="background-color: #fce5cd;">US23</td>
            <td>Extender ofertas de empleo</td>
        </tr>
        <tr>
            <td style="background-color: #fce5cd;">US24</td>
            <td>Registrar observaciones y entrevistas</td>
        </tr>
    </tbody>
    <tbody style="text-align:left;">
        <tr>
            <td rowspan="4">E07</td>
            <td rowspan="4"><b>Ayuda Asistida<br>Como</b> usuario <b>quiero</b> acceso a recursos de ayuda y soporte en la plataforma <b>para</b> resolver dudas, aprender a utilizar la plataforma y solucionar problemas de manera eficiente.</td>
            <td style="background-color: #fce5cd;">US25</td>
            <td>Acceder a recursos de ayuda y tutoriales.</td>
        </tr>
        <tr>
            <td style="background-color: #fce5cd;">US26</td>
            <td>Contactar al soporte de la plataforma para resolver problemas o hacer preguntas.</td>
        </tr>
        <tr>
            <td style="background-color: #fce5cd;">US27</td>
            <td>Reportar problemas o dar retroalimentación sobre la plataforma.</td>
        </tr>
        <tr>
            <td style="background-color: #fce5cd;">US28</td>
            <td>Acceder a un chat en vivo con el soporte</td>
        </tr>
    </tbody>
    
</table>
<br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US01 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Registrarse</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Practicante - Empleador</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> practicante o empleador <b>quiero</b> registrarme  <b>para</b> hacer uso de la aplicación.</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario</em>
            <br><span style="color:red">Dado</span></b> que el usuario practicante ingresa por primera vez a la aplicación
            <br><b><span style="color:red">Y</span></b> quiere registrarse para hacer uso de la aplicación,
            <br><b><span style="color:red">Cuando</span></b> rellene con sus datos personales los campos obligatorios
            <br><b><span style="color:red">Y</span></b> de click al botón “Registrar”
            <br><b><span style="color:red">Entonces</span></b> el usuario practicante será registrado
            <br><b><span style="color:red">Y</span></b> podrá acceder a todas las secciones y funciones de un practicante en la app.
            <br><br><b><em>Escenario 2: Registrarse como empleador</em>
            <br><span style="color:red">Dado</span></b> que el usuario empleador ingresa por primera vez a la aplicación
            <br><b><span style="color:red">Y</span></b> quiere registrarse para hacer uso de la aplicación,
            <br><b><span style="color:red">Cuando</span></b> rellene con sus datos personales y de la empresa en los campos obligatorios
            <br><b><span style="color:red">Y</span></b> de click al botón “Registrar”
            <br><b><span style="color:red">Entonces</span></b> el usuario empleador será registrado
            <br><b><span style="color:red">Y</span></b> podrá acceder a todas las secciones y funciones de un empleador en la app.
            </td>
        </tr>
    </tbody>
</table>
<br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US02 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Loguearse</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Practicante - Empleador</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> practicante o empleador <b>quiero</b> loguearme  <b>para</b> acceder a mi cuenta y utilizar la aplicación.</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Iniciar sesión como practicante</em>
            <br><span style="color:red">Dado</span></b> que el usuario practicante inicia sesión en la app
            <br><b><span style="color:red">Cuando</span></b> ingrese sus datos correctos
            <br><b><span style="color:red">Y</span></b> selecciona el botón “Iniciar sesión”
            <br><b><span style="color:red">Entonces</span></b> el usuario practicante tendrá acceso a la aplicación
            <br><b><span style="color:red">Y</span></b> visualizará las diferentes propuestas de trabajo publicadas, filtros de búsqueda, entre otras funciones como practicante.
            <br><br><b><em>Escenario 2: Iniciar sesión como empleador</em>
            <br><span style="color:red">Dado</span></b> que el usuario empleador inicia sesión en la app
            <br><b><span style="color:red">Cuando</span></b> ingrese sus datos correctos
            <br><b><span style="color:red">Y</span></b> selecciona el botón “Iniciar sesión”
            <br><b><span style="color:red">Entonces</span></b> el usuario empleador tendrá acceso a la aplicación
            <br><b><span style="color:red">Y</span></b> visualizará sus publicaciones sobre los puestos de trabajo ofrecidos, mensajes, entre otras funciones como empleador.
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US03 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Recuperar contraseña</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Practicante - Empleador</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> practicante o empleador <b>quiero</b> recuperar mi contraseña <b>para</b> acceder a mi cuenta y utilizar la aplicación</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Recuperar contraseña con un correo electrónico</em>
            <br><span style="color:red">Dado</span></b> que el usuario ha olvidado su contraseña y quiere recuperarla
            <br><b><span style="color:red">Cuando</span></b> le de click a la opción “Recuperar contraseña”
            <br><b><span style="color:red">Y</span></b> después selecciona la opción “Correo electrónico”, recibirá un correo de la empresa al correo electrónico asociado con un código
            <br><b><span style="color:red">Entonces</span></b> luego de ingresar el código en el campo requerido
            <br><b><span style="color:red">Y</span></b> restablecer su contraseña, tendrá que iniciar sesión otra vez.
            <br><br><b><em>Escenario 2: Recuperar contraseña con un mensaje de texto</em>
            <br><span style="color:red">Dado</span></b> que el usuario ha olvidado su contraseña y quiere recuperarla
            <br><b><span style="color:red">Cuando</span></b> le de click a la opción “Recuperar contraseña”
            <br><b><span style="color:red">Y</span></b> después selecciona la opción “Mensaje de texto”, recibirá un mensaje de texto de la empresa al teléfono asociado con un código
            <br><b><span style="color:red">Entonces</span></b> luego de ingresar el código en el campo requerido
            <br><b><span style="color:red">Y</span></b> restablecer su contraseña, tendrá que iniciar sesión otra vez.
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US04 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Cerrar sesión o borrar cuenta</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Practicante - Empleador</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> practicante o empleador <b>quiero</b> salir o borrar mi cuent <b>para</b> garantizar la protección y privacidad de mis datos.</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Salir de la cuenta</em>
            <br><span style="color:red">Dado</span></b> que el usuario desea cerrar sesión
            <br><b><span style="color:red">Cuando</span></b> le de click a su perfil
            <br><b><span style="color:red">Y</span></b> seleccione la opción “Cerrar sesión”
            <br><b><span style="color:red">Entonces</span></b>  se cerrará su cuenta
            <br><b><span style="color:red">Y</span></b> será redirigido a la pantalla de inicio de sesión.
            <br><br><b><em>Escenario 2: Borrar la cuenta</em>
            <br><span style="color:red">Dado</span></b> que el usuario desea borrar su cuenta
            <br><b><span style="color:red">Cuando</span></b> le de click a su perfil
            <br><b><span style="color:red">Y</span></b> seleccione la opción “Borrar cuenta”, le saldrá un mensaje de confirmación para borrar su cuenta 
            <br><b><span style="color:red">Entonces</span></b> le da click a la opción “Confirmar”, su cuenta será borrada.
            <br><b><span style="color:red">Y</span></b> será redirigido a la pantalla de inicio de sesión.
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US05 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Búsqueda de oportunidades laborales</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Practicante</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> practicante  <b>quiero</b> poder buscar oportunidades laborales <b>para</b> poder postular y aplicar al puesto de trabajo.</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Búsqueda de oportunidades laborales - Exitosa</em>
            <br><span style="color:red">Dado</span></b> que el usuario desea buscar oportunidades laborales
            <br><b><span style="color:red">Cuando</span></b> ingrese sus preferencias
            <br><b><span style="color:red">Y</span></b> seleccione la opción “buscar”
            <br><b><span style="color:red">Entonces</span></b> se le mostrará la lista de puestos de trabajo en base a sus preferencias
            <br><b><span style="color:red">Y</span></b> el usuario podrá postular a dicho empleo de trabajo.
            <br><br><b><em>Escenario 2: Búsqueda de oportunidades laborales - Fallida</em>
            <br><span style="color:red">Dado</span></b> que el usuario desea buscar oportunidades laborales
            <br><b><span style="color:red">Cuando</span></b> ingrese sus preferencias
            <br><b><span style="color:red">Y</span></b> seleccione la opción “buscar”
            <br><b><span style="color:red">Entonces</span></b> NO se le mostrará la lista de puestos de trabajo en base a sus preferencias
            <br><b><span style="color:red">Y</span></b> el usuario NO podrá postular a dicho empleo de trabajo.
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US06 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Sugerencia de puestos de trabajo</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Practicante</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> practicante  <b>quiero</b> recibir sugerencias de puestos de trabajo <b>para</b> poder aplicar a dicho puesto.</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Recibe sugerencias de puestos de trabajo</em>
            <br><span style="color:red">Dado</span></b> que el usuario espera recibir sugerencia de puestos de trabajo
            <br><b><span style="color:red">Cuando</span></b> haya alguna vacante en base a sus habilidades descritas
            <br><b><span style="color:red">Y</span></b> cumpla con la mayoría de requisitos o todos
            <br><b><span style="color:red">Entonces</span></b> se le mostrará como sugerencia mediante una notificación 
            <br><b><span style="color:red">Y</span></b> el usuario podrá ver si le interesa el puesto de trabajo.
            <br><br><b><em>Escenario 2: NO Recibe sugerencias de puestos de trabajo</em>
            <br><span style="color:red">Dado</span></b> que el usuario espera recibir sugerencia de puestos de trabaj
            <br><b><span style="color:red">Cuando</span></b> NO vacantes en base a sus habilidades descritas
            <br><b><span style="color:red">Y</span></b> NO cumpla con la mayoría de requisitos o todos
            <br><b><span style="color:red">Entonces</span></b> NO se le mostrará como sugerencia mediante una notificación 
            <br><b><span style="color:red">Y</span></b> el usuario NO recibirá sugerencias de trabajo.
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US07 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Comunicación con las empresas</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Practicante</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> practicante  <b>quiero</b> poder comunicarme con las empresas <b>para</b> poder coordinar entrevistas y obtener más información.</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Comunicación con la empresa - Exitosa</em>
            <br><span style="color:red">Dado</span></b> que el usuario desea comunicarse con la empresa o reclutador
            <br><b><span style="color:red">Cuando</span></b> se dirija a la sección de mensajes y consultas
            <br><b><span style="color:red">Y</span></b> envíe su mensaje
            <br><b><span style="color:red">Entonces</span></b> algún encargado de la empresa le responderá
            <br><b><span style="color:red">Y</span></b> establecerán conexión entre candidato y empresa.
            <br><br><b><em>Escenario 2: Comunicación con la empresa - Fallida</em>
            <br><span style="color:red">Dado</span></b> que el usuario desea comunicarse con la empresa o reclutador
            <br><b><span style="color:red">Cuando</span></b> se dirija a la sección de mensajes y consultas
            <br><b><span style="color:red">Y</span></b> vea que no existe una sección de comunicación
            <br><b><span style="color:red">Entonces</span></b> no podrá comunicarse con la empresa
            <br><b><span style="color:red">Y</span></b> no podrá concretar entrevistas y resolver sus dudas.
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US08 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Búsqueda avanzada mediante filtros</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Practicante</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> practicante  <b>quiero</b> realizar una búsqueda avanzada mediante filtros específicos <b>para</b> garantizar resultados más objetivos a mis habilidades.</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Uso de la búsqueda avanzada - Existoso</em>
            <br><span style="color:red">Dado</span></b> que el usuario desea realizar una búsqueda avanzada
            <br><b><span style="color:red">Cuando</span></b> aplique los filtros correspondientes
            <br><b><span style="color:red">Y</span></b> seleccione la opción “buscar”
            <br><b><span style="color:red">Entonces</span></b> se le mostrarán puestos más objetivos a sus habilidades
            <br><b><span style="color:red">Y</span></b> podrá aplicar a algún puesto de trabajo
            <br><br><b><em>Escenario 2: Uso de la búsqueda avanzada - Fallid</em>
            <br><span style="color:red">Dado</span></b> que el usuario desea realizar una búsqueda avanzada
            <br><b><span style="color:red">Cuando</span></b> quiera aplicar los filtros
            <br><b><span style="color:red">Y</span></b> se de cuenta de que no existe una opción de búsqueda avanzada
            <br><b><span style="color:red">Entonces</span></b> NO se le mostrarán puestos más objetivos a sus habilidades 
            <br><b><span style="color:red">Y</span></b> NO podrá aplicar a algún puesto de trabajo
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US09 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Editar perfil personal</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Practicante</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> practicante  <b>quiero</b> poder editar mi perfil personal <b>para</b> mantenerlo actualizado y completo con información relevante.</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Edición Exitosa </em>
            <br><span style="color:red">Dado</span></b> que el usuario desea editar su perfil personal
            <br><b><span style="color:red">Cuando</span></b> haga clic en la opción de "Editar perfil"
            <br><b><span style="color:red">Y</span></b> seleccione la opción “buscar”
            <br><b><span style="color:red">Entonces</span></b> realice cambios en la información, como actualizar su estado educativo, agregar nuevas habilidades o modificar su resumen profesiona
            <br><b><span style="color:red">Y</span></b> se mostrará un mensaje de confirmación de edición exitosa.
            <br><br><b><em>Escenario 2: Cancelación de Edición</em>
            <br><span style="color:red">Dado</span></b> que el usuario está editando su perfil
            <br><b><span style="color:red">Cuando</span></b> realice cambios en la información
            <br><b><span style="color:red">Y</span></b> luego decida cancelar la edición en lugar de guardar los cambios
            <br><b><span style="color:red">Entonces</span></b> los cambios no se guardarán
            <br><b><span style="color:red">Y</span></b> se mostrará un mensaje de confirmación de cancelación.
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US10 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Agregar experiencia académica y laboral</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Practicante</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> practicante  <b>quiero</b> poder agregar mi experiencia académica y laboral a mi perfil <b>para</b> destacar mis logros y habilidades relevantes.</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Agregar Experiencia Académica</em>
            <br><span style="color:red">Dado</span></b> que el usuario desea agregar experiencia académica a su perfil
            <br><b><span style="color:red">Cuando</span></b> haga clic en la opción de "Agregar Experiencia Académica"
            <br><b><span style="color:red">Y</span></b> complete los campos requeridos, como nombre de la institución, título, fecha de inicio y finalización
            <br><b><span style="color:red">Entonces</span></b> la experiencia académica se añadirá correctamente a su perfil
            <br><b><span style="color:red">Y</span></b> se mostrará un mensaje de confirmación de la adición exitosa.
            <br><br><b><em>Escenario 2: Agregar Experiencia Laboral</em>
            <br><span style="color:red">Dado</span></b> que el usuario desea agregar experiencia laboral a su perfil
            <br><b><span style="color:red">Cuando</span></b> haga clic en la opción de "Agregar Experiencia Laboral"
            <br><b><span style="color:red">Y</span></b> complete los campos requeridos, como nombre de la empresa, cargo, fecha de inicio y finalización
            <br><b><span style="color:red">Entonces</span></b> la experiencia laboral se añadirá correctamente a su perfil
            <br><b><span style="color:red">Y</span></b> se mostrará un mensaje de confirmación de la adición exitosa.
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US11 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Subir una foto de perfil</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Practicante</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> practicante  <b>quiero</b> poder subir una foto de perfil a mi cuent <b>para</b> personalizar mi perfil y hacerlo más atractivo para los empleadores y otros usuarios.</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Subir Foto de Perfil Exisotamente</em>
            <br><span style="color:red">Dado</span></b> que el usuario desea subir una foto de perfi
            <br><b><span style="color:red">Cuando</span></b> seleccione la opción de "Subir Foto de Perfil"
            <br><b><span style="color:red">Y</span></b> la foto de perfil se cargará exitosamente en su cuenta
            <br><b><span style="color:red">Entonces</span></b> la experiencia académica se añadirá correctamente a su perfil
            <br><b><span style="color:red">Y</span></b> se mostrará un mensaje de confirmación de la carga exitosa.    
            <br><br><b><em>Escenario 2: Formato de Imagen Incorrecto</em>
            <br><span style="color:red">Dado</span></b> que el usuario desea subir una foto de perfil
            <br><b><span style="color:red">Cuando</span></b> intente cargar un archivo que no sea una imagen válida (por ejemplo, un archivo de texto o un archivo corrupto)
            <br><b><span style="color:red">Entonces</span></b> se mostrará un mensaje de error indicando que el formato de la imagen es incorrecto
            <br><b><span style="color:red">Y</span></b> se le pedirá al usuario que seleccione un archivo de imagen válido.
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US12 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Establecer preferencias de búsqueda de empleo</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Practicante</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> practicante  <b>quiero</b> poder establecer mis preferencias de búsqueda de empleo en la aplicació <b>para</b> recibir recomendaciones más precisas y relevantes sobre oportunidades laborales.</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Configuración de Preferencias Exitosa</em>
            <br><span style="color:red">Dado</span></b> que el usuario desea establecer sus preferencias de búsqueda de empleo
            <br><b><span style="color:red">Cuando</span></b> acceda a la sección de "Preferencias de Búsqueda de Empleo"
            <br><b><span style="color:red">Y</span></b> complete los campos requeridos, como ubicación, salario deseado, tipo de contrato, industria, etc
            <br><b><span style="color:red">Entonces</span></b> las preferencias se guardarán correctamente en su perfil
            <br><b><span style="color:red">Y</span></b> se mostrará un mensaje de confirmación de configuración exitosa
            <br><br><b><em>Escenario 2: Preferencia por Defecto</em>
            <br><span style="color:red">Dado</span></b> que el usuario aún no ha configurado sus preferencias de búsqueda de empleo
            <br><b><span style="color:red">Cuando</span></b> inicie sesión por primera vez en la aplicación
            <br><b><span style="color:red">Y</span></b> complete los campos requeridos, como nombre de la empresa, cargo, fecha de inicio y finalización
            <br><b><span style="color:red">Entonces</span></b> se utilizarán las preferencias de búsqueda de empleo por defecto (si están disponibles)
            <br><b><span style="color:red">Y</span></b> el usuario podrá modificar estas preferencias en cualquier momento.
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US13 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Ver el estado de mis postulaciones</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Practicante</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> practicante  <b>quiero</b> poder ver el estado de mis postulaciones a oportunidades laborales <b>para</b> conocer el progreso y la situación de mis aplicaciones.</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Ver Estado de Postulaciones Exitosamente</em>
            <br><span style="color:red">Dado</span></b> que el usuario desea verificar el estado de sus postulaciones
            <br><b><span style="color:red">Cuando</span></b> inicie sesión en la aplicación
            <br><b><span style="color:red">Y</span></b> acceda a la sección de "Mis Postulaciones" o "Estado de Postulaciones"
            <br><b><span style="color:red">Entonces</span></b> se mostrará una lista de las oportunidades a las que ha aplicado junto con el estado actual de cada postulación (por ejemplo, pendiente, en revisión, rechazada o aceptada)
            <br><b><span style="color:red">Y</span></b> el usuario podrá hacer clic en cada postulación para obtener más detalles.
            <br><br><b><em>Escenario 2: Sin Postulaciones Anteriores</em>
            <br><span style="color:red">Dado</span></b> que el usuario no ha realizado ninguna postulación previa
            <br><b><span style="color:red">Cuando</span></b> acceda a la sección de "Mis Postulaciones" o "Estado de Postulaciones"
            <br><b><span style="color:red">Entonces</span></b> se proporcionará orientación sobre cómo buscar oportunidades laborales y aplicar.
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US14 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Recibir notificaciones de cambios en los procesos de selección</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Practicante</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> practicante  <b>quiero</b> recibir notificaciones en tiempo real sobre cualquier cambio en el estado de los procesos de selección a los que he aplicado <b>para</b> estar informado y tomar decisiones oportunas.</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Recepción de Notificación de Cambio Exitosa</em>
            <br><span style="color:red">Dado</span></b> que el usuario ha aplicado a un proceso de selección
            <br><b><span style="color:red">Cuando</span></b> el estado de ese proceso de selección cambie (por ejemplo, de "pendiente" a "entrevista programada" o "selección finalizada")
            <br><b><span style="color:red">Entonces</span></b> el sistema enviará una notificación instantánea al usuario
La notificación contendrá información sobre el cambio en el estado y una breve descripción de la actualización
            <br><b><span style="color:red">Y</span></b> el usuario podrá hacer clic en la notificación para obtener más detalles.
            <br><br><b><em>Escenario 2: Sin Cambios en los Procesos de Selección</em>
            <br><span style="color:red">Dado</span></b> que el usuario ha aplicado a procesos de selección
            <br><b><span style="color:red">Cuando</span></b> no haya cambios en el estado de ninguno de los procesos de selección a los que se ha postulado
            <br><b><span style="color:red">Entonces</span></b> el usuario no recibirá notificaciones de cambios
            <br><b><span style="color:red">Y</span></b> se le informará que no ha habido actualizaciones recientes en sus aplicaciones.
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US15 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Registrar entrevistas y pruebas de selección</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Practicante</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> practicante  <b>quiero</b> poder registrar las fechas y detalles de las entrevistas y pruebas de selección a las que soy convocado <b>para</b> llevar un registro organizado de mi proceso de búsqueda de empleo.</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Registro de Entrevista Existoso</em>
            <br><span style="color:red">Dado</span></b> que el usuario desea registrar una entrevista o prueba de selección
            <br><b><span style="color:red">Cuando</span></b> acceda a la sección de "Registrar Entrevista" o "Registrar Prueba de Selección"
            <br><b><span style="color:red">Y</span></b> complete los campos obligatorios, como fecha, hora, ubicación y detalles adicionales (por ejemplo, nombre del entrevistador o descripción de la prueba)
            <br><b><span style="color:red">Entonces</span></b> la información de la entrevista o prueba se registrará exitosamente en su perfil
            <br><b><span style="color:red">Y</span></b> se mostrará un mensaje de confirmación de registro exitoso
            <br><br><b><em>Escenario 2: Sin Cambios Obligatorios Completados</em>
            <br><span style="color:red">Dado</span></b> que el usuario desea registrar una entrevista o prueba de selección
            <br><b><span style="color:red">Cuando</span></b> intente guardar el registro sin completar todos los campos obligatorios
            <br><b><span style="color:red">Entonces</span></b> se mostrará un mensaje de error indicando los campos que deben completarse
            <br><b><span style="color:red">Y</span></b> el usuario deberá completar los campos faltantes antes de poder guardar el registro.
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US16 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Calificar y dejar comentarios sobre los procesos de selección</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Practicante</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> practicante  <b>quiero</b> poder calificar y dejar comentarios sobre los procesos de selección en los que he participado <b>para</b> proporcionar retroalimentación y compartir mi experiencia con otros usuarios.</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Calificar y Comentar un Proceso de Selección</em>
            <br><span style="color:red">Dado</span></b> que el usuario ha participado en un proceso de selección
            <br><b><span style="color:red">Cuando</span></b> acceda al proceso de selección desde su lista de postulaciones o historial
            <br><b><span style="color:red">Y</span></b> tenga la opción de calificar el proceso (por ejemplo, con estrellas o puntuación numérica)
            <br><b><span style="color:red">Y</span></b> también tenga la opción de dejar un comentario detallado sobre su experiencia
            <br><b><span style="color:red">Entonces</span></b> la calificación y el comentario se registrarán exitosamente para ese proceso de selección
            <br><b><span style="color:red">Y</span></b> se mostrará un mensaje de confirmación de registro exitoso.
            <br><br><b><em>Escenario 2: Editar Clasificación y Comentario</em>
            <br><span style="color:red">Dado</span></b> que el usuario ha calificado y dejado un comentario sobre un proceso de selección previamente
            <br><b><span style="color:red">Cuando</span></b> decida editar su calificación o comentario para proporcionar más detalles o actualizar su opinión
            <br><b><span style="color:red">Entonces</span></b> el proceso de selección mostrará la calificación y el comentario actualizados
            <br><b><span style="color:red">Y</span></b> se mostrará un mensaje de confirmación de edición exitosa.
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US17 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Publicar nueva oferta de empleo</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Responsable de recursos humanos / empleador</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> responsable de recursos humanos <b>quiero</b> poder publicar nuevas ofertas de empleo en la plataforma <b>para</b> atraer candidatos cualificados.</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Publicación exitosa</em>
            <br><span style="color:red">Dado</span></b> que soy un responsable de recursos humanos que quiere publicar una nueva oferta de empleo
            <br><b><span style="color:red">Cuando</span></b> complete todos los campos obligatorios del formulario de publicación
            <br><b><span style="color:red">Entonces</span></b> la oferta de empleo se publicará exitosamente en la plataforma y se mostrará un mensaje de confirmación.
            <br><br><b><em>Escenario 2: Editar Clasificación y Comentario</em>
            <br><span style="color:red">Dado</span></b> soy un responsable de recursos humanos que quiere publicar una nueva oferta de empleo
            <br><b><span style="color:red">Cuando</span></b> intente publicar la oferta sin completar todos los campos obligatorios del formulario
            <br><b><span style="color:red">Entonces</span></b> se mostrará un mensaje de error que indica los campos que deben completarse antes de la publicación.
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US18 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Editar ofertas de empleo</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Responsable de recursos humanos / empleador</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> responsable de recursos humanos <b>quiero</b> poder editar las ofertas de empleo existentes en caso de cambios en los requisitos o en la descripción del trabajo <b>para</b> proporcionar ofertas de empleo actualizadas.</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Edición existosa</em>
            <br><span style="color:red">Dado</span></b> que soy un responsable de recursos humanos que quiere editar una oferta de empleo existente
            <br><b><span style="color:red">Cuando</span></b> acceda a la oferta de empleo que deseo modificar, realice los cambios necesarios y confirme la edición
            <br><b><span style="color:red">Entonces</span></b> los cambios se guardarán exitosamente y se mostrará un mensaje de confirmación.
            <br><br><b><em>Escenario 2: Campos obligatorios incompletos al editar</em>
            <br><span style="color:red">Dado</span></b> que soy un responsable de recursos humanos que quiere editar una oferta de empleo existente
            <br><b><span style="color:red">Cuando</span></b> intente guardar la edición sin completar los campos obligatorios del formulari
            <br><b><span style="color:red">Entonces</span></b> se mostrará un mensaje de error que indica los campos que deben completarse antes de la actualización.
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US19 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Gestionar postulaciones</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Responsable de recursos humanos / empleador</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> responsable de recursos humanos <b>quiero</b> poder gestionar las postulaciones de los candidatos a las ofertas de empleo <b>para</b> evaluar y avanzar en el proceso de selección.</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Visualizar postulaciones con éxito</em>
            <br><span style="color:red">Dado</span></b> que soy un responsable de recursos humanos que desea gestionar las postulaciones a una oferta de empleo
            <br><b><span style="color:red">Cuando</span></b> acceda a la lista de postulaciones para una oferta específica
            <br><b><span style="color:red">Entonces</span></b> podré ver la lista de candidatos que se han postulado correctamente, incluyendo sus perfiles y documentos adjuntos.
            <br><br><b><em>Escenario 2: Cambiar estado de postulación</em>
            <br><span style="color:red">Dado</span></b> ue soy un responsable de recursos humanos que quiere gestionar las postulaciones
            <br><b><span style="color:red">Cuando</span></b> seleccione una postulación y cambie su estado (por ejemplo, de "pendiente" a "entrevista programada")
            <br><b><span style="color:red">Entonces</span></b> el sistema actualizará el estado de la postulación y enviará notificaciones automáticas al candidato sobre el cambio.
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US20 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Comunicación con candidatos</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Responsable de recursos humanos / empleador</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> responsable de recursos humanos <b>quiero</b> poder comunicarme con los candidatos de manera efectiva durante el proceso de selección <b>para</b> comunicarle toda la información necesaria a los postulantes.</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Enviar mensajes privados con éxito</em>
            <br><span style="color:red">Dado</span></b> que soy un responsable de recursos humanos que desea comunicarse con candidatos
            <br><b><span style="color:red">Cuando</span></b> seleccione un candidato y envíe un mensaje privado a través de la plataforma
            <br><b><span style="color:red">Entonces</span></b> el mensaje se entregará correctamente al candidato y quedará registrado en el sistema.
            <br><br><b><em>Escenario 2: Programación de entrevistas y pruebas</em>
            <br><span style="color:red">Dado</span></b> que soy un responsable de recursos humanos que quiere comunicarse con candidatos
            <br><b><span style="color:red">Cuando</span></b> programe entrevistas o pruebas de selección y notifique a los candidatos a través de la plataforma
            <br><b><span style="color:red">Entonces</span></b> los candidatos recibirán notificaciones automáticas sobre las fechas, horas y ubicaciones de las entrevistas o pruebas programadas.
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US21 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Evaluar perfiles de candidatos</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Responsable de recursos humanos / empleador</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> responsable de recursos humanos <b>quiero</b>  tener herramienta <b>para</b> evaluar de manera eficaz los perfiles de los candidatos y sus habilidades.</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Visualización de resumen de perfiles exitosa</em>
            <br><span style="color:red">Dado</span></b> que soy un responsable de recursos humanos que quiere evaluar perfiles de candidatos
            <br><b><span style="color:red">Cuando</span></b> acceda a la sección de evaluación de candidatos
            <br><b><span style="color:red">Entonces</span></b> podré visualizar un resumen claro de los perfiles de los candidatos que incluirá información relevante como educación, experiencia y habilidades destacadas.
            <br><br><b><em>Escenario 2: Calificación y comentarios</em>
            <br><span style="color:red">Dado</span></b> que soy un responsable de recursos humanos que quiere evaluar perfiles de candidatos
            <br><b><span style="color:red">Cuando</span></b> seleccione un candidato y califique su perfil (por ejemplo, mediante estrellas o puntuación numérica) y deje comentarios detallados sobre su desempeño y habilidades
            <br><b><span style="color:red">Entonces</span></b> mi calificación y comentarios se registrarán en el sistema y estarán disponibles para futuras referencias.
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US22 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Colaboración en la toma de decisiones</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Responsable de recursos humanos / empleador</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> responsable de recursos humanos <b>quiero</b> poder colaborar con otros miembros del equipo de selección <b>para</b> tomar decisiones consensuadas sobre los candidatos.</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Invitar a miembros del equipo de selección</em>
            <br><span style="color:red">Dado</span></b> que soy un responsable de recursos humanos que quiere colaborar en la toma de decisiones sobre candidatos
            <br><b><span style="color:red">Cuando</span></b> acceda a la evaluación de candidatos
            <br><b><span style="color:red">Entonces</span></b> podré invitar a otros miembros del equipo de selección a participar en la revisión de perfiles y agregar sus comentarios y calificaciones.> 
            <br><br><b><em>Escenario 2: Visualización de comentarios y calificaciones del equipo</em>
            <br><span style="color:red">Dado</span></b> que soy un responsable de recursos humanos que quiere colaborar en la toma de decisiones sobre candidatos
            <br><b><span style="color:red">Cuando</span></b> invite a otros miembros del equipo de selección y estos realicen evaluaciones
            <br><b><span style="color:red">Entonces</span></b> podré ver y consolidar las calificaciones y comentarios de todos los miembros del equipo en una única vista, lo que facilitará la toma de decisiones basadas en consenso.
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US23 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Extender ofertas de empleo</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Responsable de recursos humanos / empleado</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> responsable de recursos humanos <b>quiero</b> poder extender ofertas de empleo a los candidatos seleccionados de manera eficiente <b>para</b> brindarles oportunidad a los candidatos.</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Extensión de oferta exitosa</em>
            <br><span style="color:red">Dado</span></b> que soy un responsable de recursos humanos que desea extender una oferta de empleo a un candidato seleccionado
            <br><b><span style="color:red">Cuando</span></b> seleccione a un candidato, complete los detalles de la oferta, y confirme la extensión
            <br><b><span style="color:red">Entonces</span></b> la oferta se enviará exitosamente al candidato y se registrará en el sistema.
            <br><br><b><em>Escenario 2: Notificaciones automáticas</em>
            <br><span style="color:red">Dado</span></b> que soy un responsable de recursos humanos que desea extender ofertas de empleo
            <br><b><span style="color:red">Cuando</span></b> envíe una oferta a un candidato y este la reciba
            <br><b><span style="color:red">Entonces</span></b> el sistema enviará notificaciones automáticas al candidato para confirmar la recepción de la oferta y proporcionar los siguientes pasos.
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US24 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Registrar observaciones y entrevistas</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Responsable de recursos humanos / empleador</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> responsable de recursos humanos <b>quiero</b> tener la capacidad de registrar observaciones y detalles de las entrevistas realizadas con los candidatos <b>para</b> tener un registro completo de las interacciones y tomar decisiones informadas.</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Registro de observaciones exitoso</em>
            <br><span style="color:red">Dado</span></b> que soy un responsable de recursos humanos que desea registrar observaciones sobre un candidato después de una entrevista
            <br><b><span style="color:red">Cuando</span></b> seleccione un candidato y registre observaciones detalladas
            <br><b><span style="color:red">Entonces</span></b> las observaciones se guardarán exitosamente y quedarán asociadas al perfil del candidato.
            <br><br><b><em>Escenario 2: Adjuntar notas y calificaciones</em>
            <br><span style="color:red">Dado</span></b> que soy un responsable de recursos humanos que desea registrar observaciones sobre un candidato después de una entrevista
            <br><b><span style="color:red">Cuando</span></b> añada notas, comentarios y calificaciones sobre el desempeño del candidato
            <br><b><span style="color:red">Entonces</span></b> estas notas y calificaciones se registrarán de manera efectiva para futuras referencias y decisiones.
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US25 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Acceder a recursos de ayuda y tutoriales </td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Responsable de recursos humanos / empleador y estudiante</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> usuario <b>quiero</b> acceder a recursos de ayuda y tutoriales <b>para</b> entender mejor cómo utilizar la plataforma y resolver mis dudas de manera independiente</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Acceso a Tutoriales</em>
            <br><span style="color:red">Dado</span></b> que soy un usuario registrado y estoy conectado a mi cuenta
            <br><b><span style="color:red">Cuando</span></b> hago clic en la sección "Ayuda" o "Recursos de ayuda" en el menú principal,
            <br><b><span style="color:red">Entonces</span></b> soy redirigido a una página con una lista de tutoriales y recursos de ayuda relevantes.
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US26 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Contactar al soporte de la plataforma</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Estudiante</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> estudiante en busca de una pasantía <b>quiero</b> contactar al soporte de la plataforma <b>para</b> obtener asistencia personalizada y resolver problemas específicos</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Acceso a sección de “Soporte”</em>
            <br><span style="color:red">Dado</span></b> que soy un estudiante registrado y estoy conectado a mi cuenta
            <br><b><span style="color:red">Cuando</span></b> accedo a la sección de "Soporte" o "Contacto" en la plataforma,
            <br><b><span style="color:red">Entonces</span></b> se me presenta un formulario de contacto con campos para ingresar mi nombre, dirección de correo electrónico y descripción detallada del problema o pregunta. 
            <br><b><span style="color:red">Y</span></b> lleno el formulario y presiono el botón de enviar,
            <br><br><b><em>Escenario</em>
            <br><span style="color:red">Dado</span></b> 
            <br><b><span style="color:red">Y</span></b> 
            <br><b><span style="color:red">Cuando</span></b> 
            <br><b><span style="color:red">Y</span></b> 
            <br><b><span style="color:red">Entonces</span></b> 
            <br><b><span style="color:red">Y</span></b> 
            </td>
        </tr>
    </tbody>
</table><br>
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tbody >
        <tr>
            <td style="background-color: #ccc;">HU:</td>
            <td>US27 </td>
            <td style="background-color: #ccc;">Título:</td>
            <td style="text-align:left;">Reportar problemas o dar retroalimentación sobre la plataforma</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Usuario:</td>
            <td colspan="3" style="text-align:left;">Estudiante</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Descripción</td>
            <td colspan="3" style="text-align:left;"><b>Como</b> estudiante <b>quiero</b> reportar problemas o dar retroalimentación sobre la plataforma <b>para</b> ayudar poder resolver los problemas que existen</td>
        </tr>
        <tr>
            <td style="background-color: #ccc;">Criterios de aceptación</td>
            <td colspan="3" style="text-align:left;"><b><em>Escenario 1: Usuario estudiante reporta un Problema</em>
            <br><span style="color:red">Dado</span></b> que soy un Usuario estudiante registrado y estoy conectado a mi cuenta,
            <br><b><span style="color:red">Cuando</span></b> accedo a la sección de "Reportar un problema" o "Enviar retroalimentación" en la plataforma
            <br><b><span style="color:red">Entonces</span></b> se me presenta un formulario que me permite seleccionar el tipo de problema o comentario que deseo reportar, proporcionar una descripción detallada y adjuntar capturas de pantalla si es necesario.
            <br><b><span style="color:red">Y</span></b> llenó el formulario y presionó el botón de enviar,
            </td>
        </tr>
    </tbody>
</table><br>

## 3.3. Impact Mapping.

 <b>Impact Mapping - Practicante </b>
 <img src="https://cdn.discordapp.com/attachments/906396646886223913/1149146891804741692/image.png" width="800px">
 
 <b>Impact Mapping - Empleador </b>
 <img src="https://cdn.discordapp.com/attachments/906396646886223913/1149147270403604540/Impact_map_1.png" width="800px">

## 3.4. Product Backlog.

| #Orden | User Story Id | Titulo | Descripcion | Story Points(1 / 2 / 3 / 5 / 8)|
|:--------|:------|:----|:-----|:-----|
|01|HU01|Registrarse|Como practicante o empleador quiero registrarme para hacer uso de la aplicación.|5|
|02|HU02|Loguearse|Como practicante o empleador quiero loguearme para acceder a mi cuenta y utilizar la aplicación.|5|
|03|HU03|Recuperar contraseña|Como practicante o empleador quiero recuperar mi contraseña para acceder a mi cuenta y utilizar la aplicación.|5|
|04|HU04|Cerrar sesión o borrar cuenta|Como practicante o empleador quiero salir o borrar mi cuenta para garantizar la protección y privacidad de mis datos.|2|
|05|HU05|Búsqueda de oportunidades laborales|Como practicante quiero poder buscar oportunidades laborales para poder postular y aplicar al puesto de trabajo.|5|
|06|HU06|Sugerencia de puestos de trabajo|Como practicante quiero recibir sugerencias de puestos de trabajo para poder aplicar a dicho puesto.|2|
|07|HU07|Comunicación con las empresas|Como practicante quiero poder comunicarme con las empresas para poder coordinar entrevistas y obtener más información.|8|
|08|HU08|Búsqueda avanzada mediante filtros|Como practicante quiero realizar una búsqueda avanzada mediante filtros específicos para garantizar resultados más objetivos a mis habilidades.|5|
|09|HU09|Editar perfil personal|Como practicante quiero poder editar mi perfil personal para mantenerlo actualizado y completo con información relevante.|2|
|10|HU10|Agregar experiencia académica y laboral|Como practicante quiero poder agregar mi experiencia académica y laboral a mi perfil para destacar mis logros y habilidades relevantes.|3|
|11|HU11|Subir una foto de perfil|Como practicante quiero poder subir una foto de perfil a mi cuenta para personalizar mi perfil y hacerlo más atractivo para los empleadores y otros usuarios.|2|
|12|HU12|Establecer preferencias de búsqueda de empleo|Como practicante quiero poder establecer mis preferencias de búsqueda de empleo en la aplicación para recibir recomendaciones más precisas y relevantes sobre oportunidades laborales.|5|
|13|HU13|Ver el estado de mis postulaciones|Como practicante quiero poder ver el estado de mis postulaciones a oportunidades laborales para conocer el progreso y la situación de mis aplicaciones.|1|
|14|HU14|Recibir notificaciones de cambios en los procesos de selección|Como practicante quiero  recibir notificaciones en tiempo real sobre cualquier cambio en el estado de los procesos de selección a los que he aplicado para estar informado y tomar decisiones oportunas.|2|
|15|HU15|Registrar entrevistas y pruebas de selección|Como practicante quiero poder registrar las fechas y detalles de las entrevistas y pruebas de selección a las que soy convocado para llevar un registro organizado de mi proceso de búsqueda de empleo.|8|
|16|HU16|Calificar y dejar comentarios sobre los procesos de selección|Como practicante quiero  poder calificar y dejar comentarios sobre los procesos de selección en los que he participado para proporcionar retroalimentación y compartir mi experiencia con otros usuarios.|3|
|17|HU17|Publicar nueva oferta de empleo|Como responsable de recursos humanos quiero  poder publicar nuevas ofertas de empleo en la plataforma para atraer candidatos cualificados.|8|
|18|HU18|Editar ofertas de empleo|Como responsable de recursos humanos quiero  poder editar las ofertas de empleo existentes en caso de cambios en los requisitos o en la descripción del trabajo para proporcionar ofertas de empleo actualizadas.|3|
|19|HU19|Gestionar postulaciones|Como responsable de recursos humanos quiero  poder gestionar las postulaciones de los candidatos a las ofertas de empleo para evaluar y avanzar en el proceso de selección.|5|
|20|HU20|Comunicación con candidatos|Como responsable de recursos humanos quiero  poder comunicarme con los candidatos de manera efectiva durante el proceso de selección para comunicarle toda la información necesaria a los postulantes.|8|
|21|HU21|Evaluar perfiles de candidatos|Como responsable de recursos humanos quiero tener herramientas para evaluar de manera eficaz los perfiles de los candidatos y sus habilidades.|3|
|22|HU22|Colaboración en la toma de decisiones|Como responsable de recursos humanos quiero  poder colaborar con otros miembros del equipo de selección para tomar decisiones consensuadas sobre los candidatos.|3|
|23|HU23|Extender ofertas de empleo|Como responsable de recursos humanos quiero  poder extender ofertas de empleo a los candidatos seleccionados de manera eficiente para brindarles oportunidad a los candidatos.|1|
|24|HU24|Registrar observaciones y entrevistas|Como responsable de recursos humanos quiero  tener la capacidad de registrar observaciones y detalles de las entrevistas realizadas con los candidatos para tener un registro completo de las interacciones y tomar decisiones informadas.|3|
|25|HU25|Acceder a recursos de ayuda y tutoriales.|Como usuario quiero acceder a recursos de ayuda y tutoriales para entender mejor cómo utilizar la plataforma y resolver mis dudas de manera independiente|3|
|26|HU26|Contactar al soporte de la plataforma para resolver problemas o hacer preguntas|Como estudiante en busca de una pasantía, quiero contactar al soporte de la plataforma, para obtener asistencia personalizada y resolver problemas específicos.|3|
|27|HU27|Reportar problemas o dar retroalimentación sobre la plataforma.|Como estudiante quiero reportar problemas o dar retroalimentación sobre la plataforma, para ayudar poder resolver los problemas que existen|3|

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
### 4.6.1. Software Architecture Context Diagram.
### 4.6.2. Software Architecture Container Diagrams.
### 4.6.3. Software Architecture Components Diagrams.
## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.
### 4.7.2. Class Dictionary.
## 4.8. Database Design.
### 4.8.1. Database Diagram.    
# Capítulo V: Product Implementation, Validation & Deployment.
## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.
### 5.1.2. Source Code Management.
### 5.1.3. Source Code Style Guide & Conventions.
### 5.1.4. Software Deployment Configuration.
## 5.2. Landing Page, Services & Applications Implementation.
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1.
#### 5.2.1.2. Sprint Backlog 1.
#### 5.2.1.3. Development Evidence for Sprint Review.
#### 5.2.1.4. Testing Suite Evidence for Sprint Review.
#### 5.2.1.5. Execution Evidence for Sprint Review.
#### 5.2.1.6. Services Documentation Evidence for Sprint Review.
#### 5.2.1.7. Software Deployment Evidence for Sprint Review.
#### 5.2.1.8. Team Collaboration Insights during Sprint.
