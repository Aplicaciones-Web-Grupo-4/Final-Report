# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management  

### 5.1.1. Software Development Environment Configuration  
En seguida, se procederá a describir cada uno de los productos de software que han sido utilizados en el proyecto. Este apartado servirá de suma utilidad para posibilitar que los actuales y futuros desarrolladores puedan contribuir durante el ciclo de vida del proyecto.

## Project Management  

### [Trello](https://trello.com)  
Herramienta utilizada para la gestión de tareas y organización del flujo de trabajo. A través de tableros Kanban, se registraron las actividades planificadas, en proceso y finalizadas, lo que permitió tener una visión clara del avance del equipo en cada etapa del proyecto. Además, se empleó para segmentar el Product Backlog y gestionar los Sprints de manera colaborativa.  

### [Discord](https://discord.com)  
Se utilizó como principal canal de comunicación interna del equipo. Gracias a sus funciones de mensajería, llamadas de voz y videollamadas, fue posible coordinar reuniones periódicas, compartir pantallas para revisiones en conjunto y mantener una comunicación fluida durante todo el desarrollo del proyecto.  

---

## Requirements Management & Product UX/UI Design  

### [Canva](https://www.canva.com/)  
Se empleó para la elaboración de los **User Personas** y **Empathy Maps**, fundamentales para comprender las motivaciones, dolores y expectativas de los segmentos objetivo. Sus plantillas gráficas facilitaron la creación de documentos visuales claros y accesibles para todo el equipo.  

### [Miro](https://miro.com/es/)  
Fue utilizada para la construcción del **User Journey Map**, permitiendo mapear la experiencia de los usuarios a lo largo de su interacción con las ferias gastronómicas. Su dinámica de pizarra colaborativa facilitó el trabajo en tiempo real y la alineación de ideas en equipo.  

### [UXPressia](https://uxpressia.com)  
Se destinó específicamente al desarrollo del **Impact Mapping**, lo cual permitió relacionar los objetivos estratégicos de la plataforma con las necesidades de los usuarios y las funcionalidades propuestas. Esto ayudó a priorizar esfuerzos y mantener la coherencia entre la visión del producto y las soluciones diseñadas.  

### [Figma](https://www.figma.com/)  
Fue la herramienta central en el **Capítulo IV: Product Design**, al utilizarse para la creación de **wireframes** y **mockups** interactivos de la aplicación *NextHappen*. Gracias a su carácter colaborativo y basado en la nube, facilitó la co-creación, la retroalimentación inmediata y la iteración constante del diseño visual.  

---

## Software Development  

### Landing Page (HTML5, CSS3 y JavaScript)  
La página de aterrizaje del proyecto fue desarrollada empleando las tecnologías básicas del desarrollo web: **HTML5** para la estructura, **CSS3** para los estilos y **JavaScript** para la interactividad. Se aplicaron buenas prácticas de nomenclatura (BEM) con el fin de facilitar el mantenimiento y escalabilidad del código. Esta landing sirvió como carta de presentación del producto y espacio inicial de validación con los usuarios.  

### [GitHub](https://github.com)  
Se utilizó como repositorio principal de control de versiones. Permitió al equipo almacenar, organizar y dar seguimiento al código fuente de la landing page y otros entregables. Asimismo, sirvió como medio para la documentación del proyecto mediante el archivo **README.md** y como canal de despliegue gracias a **GitHub Pages**.  

### 5.1.2. Source Code Management  
La gestión de todas las actividades de la startup **Neovent** se lleva a cabo dentro de una organización en **GitHub**, centralizando la documentación y el código fuente del proyecto.  

## Repositorios  

- **Organization:** [Aplicaciones-Web-Grupo-4](https://github.com/Aplicaciones-Web-Grupo-4)  
- **Final Report Repository (Documentación):** [Final Report](https://github.com/Aplicaciones-Web-Grupo-4/Final-Report.git)  
- **Landing Page Repository:** [Landing Page](https://github.com/Aplicaciones-Web-Grupo-4/Landing-Page.git)  

---

### 5.1.3. Source Code Style Guide & Conventions  
En el desarrollo de **NextHappen**, se han adoptado guías de estilo reconocidas que permiten mantener un código legible, consistente y fácil de mantener.  
A continuación, se describen las convenciones aplicadas en este proyecto:

---

## HTML & CSS

Se sigue la **Google HTML/CSS Style Guide**:  
[Guía oficial](https://google.github.io/styleguide/htmlcssguide.html)

**Convenciones aplicadas:**
- Declarar siempre el tipo de documento con `<!DOCTYPE html>`.  
- Usar nombres de elementos en **minúsculas** (`<h1>`, `<p>`, `<footer>`).  
- Cerrar correctamente los elementos HTML (`<h1></h1>`).  
- Colocar los **atributos entre comillas** (`<img src="logo.png" alt="Logo">`).  
- Declarar siempre `alt`, `width` y `height` en las imágenes.  
- Mantener un espaciado consistente en el código.  
- Evitar líneas excesivamente largas.  
- Incluir siempre `<title>` dentro de `<head>`.  
- Usar **meta tags** para SEO y responsividad.  
- Organizar las clases de CSS siguiendo la convención **BEM (Block, Element, Modifier)** para mejorar la escalabilidad.  

---

## JavaScript

Se sigue la **Google JavaScript Style Guide**:  
[Guía oficial](https://google.github.io/styleguide/jsguide.html)

**Convenciones aplicadas:**
- Nombrar variables y funciones en **camelCase** (`function openMenu() {}`).  
- Usar **espacios después de comas y dos puntos**.  
- Strings con **comillas simples** (`'texto'`).  
- Siempre finalizar sentencias con `;`.  
- Evitar `var`; usar **`let`** o **`const`**.  
- Mantener funciones cortas y con una única responsabilidad.  
- Comentar solo lo necesario, priorizando código autoexplicativo.

### 5.1.4. Software Deployment Configuration  

  <p>Para desplegar la Landing Page desde GitHub Pages hay que seguir estos pasos:</p>

  <ol>
    <li>Ubicar el repositorio y dirigirse a <strong>Settings</strong>.</li>
    <li>Seleccionar la sección <strong>Pages</strong>.</li>
    <li>Configurar la rama que será usada para deploy.</li>
  </ol>

## 5.2. Landing Page, Services & Applications Implementation  

### 5.2.1. Sprint 1  

#### 5.2.1.1. Sprint Planning 1  
En esta sección, se presentará el sprint planning 1 donde se describirá de manera detallada cada una de las evidencias planificadas e implementación del *Landing Page*. Asimismo, se evidenciarán los avances del proyecto e *insights* de colaboración en equipo mediante nuestro repositorio de GitHub.

| Sprint # | Sprint 1 |
|----------|-----------|
| **Sprint Planning Background**  |
| **Date** | 2025/09/14 |
| **Time** | 12:56 AM |
| **Location** | Discord |
| **Prepared by** | José Adrian Paredes Dávila |
| **Attendees (to planning meeting)** | Todos los miembros del equipo NeoEvent |
| **Sprint 1 Review Summary** | Dado que es el primer sprint que se está llevando a cabo, no se está considerando los *Review Summary* ya que no hemos recibido ninguno en el sprint anterior. |
| **Sprint 1 Retrospective Summary** | Al ser el primer Sprint, se planea el desarrollo de nuestra landing page mediante el uso de herramientas web nativas como **HTML5, CSS3 y JavaScript**. Adicional a ello, se dialogó con todo el equipo sobre el contenido de los textos que tendrá el landing page, así como el diseño que se ha venido implementando anteriormente en **Figma**. Finalizado el desarrollo, se procederá a desplegar la landing page mediante los servicios de **GitHub Pages** para que cualquier usuario pueda acceder y visualizar la página a través del link generado. |
|**Sprint Goal & User Stories**  
| **Sprint 1 Velocity:**| 18  |
| **Sum of story points:**| 18 | 

#### 5.2.1.2. Aspect Leaders and Collaborators 1  
<table border="1">
  <tr>
    <th>Team Member (Last Name, First Name)</th>
    <th>GitHub Username</th>
    <th>Aspect Name 1 Leader (L) / Collaborator (C)</th>
    <th>Aspect Name 2 Leader (L) / Collaborator (C)</th>
    <th>Aspect Name 3 Leader (L) / Collaborator (C)</th>
  </tr>
  <tr>
    <td>-</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Ruiz Madrid, Billy Jake</td>
    <td>BJRM03</td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Chirito Torres, Jose Raul</td>
    <td>JoseR044</td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Martinez Gaona, Pablo Afranio</td>
    <td>Delzekl</td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>-</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>

#### 5.2.1.3. Sprint Backlog 1  
![Sprint1](../../assets/chapter-5/sprint1.png)

#### 5.2.1.4. Development Evidence for Sprint Review  
<table>
  <tr>
    <th>Repository</th>
    <th>Branch</th>
    <th>Commit Id</th>
    <th>Commit</th>
    <th>Commit</th>
    <th>Commited</th>
  </tr>
  <tr>
    <td>NeoEvent/Final-Report</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>NeoEvent/-</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>NeoEvent/-</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>NeoEvent/-</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>NeoEvent/-</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>

#### 5.2.1.5. Execution Evidence for Sprint Review  

#### 5.2.1.6. Services Documentation Evidence for Sprint Review  
  <p>En el primer Sprint el equipo diseñó, programó y puso en funcionamiento la Landing Page para presentar la aplicación web "NEXTHAPPEN".</p>

  <table>
    <thead>
      <tr><th>End Point</th><th>Funciones</th></tr>
    </thead>
    <tbody>
      <tr>
        <td>https://aplicaciones-web-grupo-4.github.io/Landing-Page/</td>
        <td>Mostrar la Landing Page Desplegada</td>
      </tr>
    </tbody>
  </table>

#### 5.2.1.7. Software Deployment Evidence for Sprint Review  
<p>
  <a href="https://aplicaciones-web-grupo-4.github.io/Landing-Page/">Landing Page NEXTHAPPEN</a> -
  <a href="https://aplicaciones-web-grupo-4.github.io/Landing-Page/">https://aplicaciones-web-grupo-4.github.io/Landing-Page/</a>
</p>

#### 5.2.1.8. Team Collaboration Insights during Sprint  

![overview-spring1.jpg](../../assets/chapter-5/overview-spring1.jpg)
![network-graph-sprint1.jpg](../../assets/chapter-5/network-graph-sprint1.jpg)
![visitors-sprint1.jpg](../../assets/chapter-5/visitors-sprint1.jpg)

### 5.2.2. Sprint 2
#### 5.2.2.1. Sprint Planning 2
#### 5.2.2.2. Aspect Leaders and Collaborators

<table border="1">
  <tr>
    <th>Team Member (Last Name, First Name)</th>
    <th>GitHub Username</th>
    <th>Aspect Name 1 Leader (L) / Collaborator (C)</th>
    <th>Aspect Name 2 Leader (L) / Collaborator (C)</th>
    <th>Aspect Name 3 Leader (L) / Collaborator (C)</th>
  </tr>
  <tr>
    <td>-</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Ruiz Madrid, Billy Jake</td>
    <td>BJRM03</td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Chirito Torres, Jose Raul</td>
    <td>JoseR044</td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Martinez Gaona, Pablo Afranio</td>
    <td>Delzekl</td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>-</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>

#### 5.2.2.3. Sprint Backlog 2
#### 5.2.2.4. Development Evidence for Sprint Review
#### 5.2.2.5. Execution Evidence for Sprint Review
#### 5.2.2.6. Services Documentation Evidence for Sprint Review

  <p>En el segundo Sprint el equipo diseñó, programó y puso en funcionamiento el Front-end para presentar la aplicación web "NEXTHAPPEN".</p>

  <table>
    <thead>
      <tr><th>End Point</th><th>Funciones</th></tr>
    </thead>
    <tbody>
      <tr>
        <td>https://front-end-5r5h.vercel.app/user/home</td>
        <td>Mostrar el Front-end Desplegado</td>
      </tr>
    </tbody>
  </table>
  
#### 5.2.2.7. Software Deployment Evidence for Sprint Review

<p>
  <a href="https://front-end-5r5h.vercel.app/user/home">Front-end NEXTHAPPEN</a> -
  <a href="https://front-end-5r5h.vercel.app/user/home">https://front-end-5r5h.vercel.app/user/home</a>
</p>

#### 5.2.2.8. Team Collaboration Insights during Sprint

![overview-spring2.jpg](../../assets/chapter-5/overview-spring1.jpg)
![network-graph-sprint2.jpg](../../assets/chapter-5/network-graph-sprint1.jpg)
![visitors-sprint2.jpg](../../assets/chapter-5/visitors-sprint1.jpg)
