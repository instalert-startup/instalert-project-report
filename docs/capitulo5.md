# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
La Gestión de Configuración de Software (SCM, por sus siglas en inglés) es una disciplina en el desarrollo de software encargada de identificar, controlar y rastrear los componentes del software a lo largo de su ciclo de vida. Esta metodología facilita la administración organizada de cambios en documentos, códigos y otros elementos durante el proceso de desarrollo, garantizando así una gestión eficiente y ordenada. Su objetivo principal es mejorar la eficiencia del equipo de desarrollo y minimizar los errores. (Martin, 2023)

### 5.1.1. Software Development Environment Configuration.

**Definición de Requisitos**

Antes de iniciar el desarrollo, es crucial definir claramente los requisitos de KSI. Estos requisitos incluyen las funcionalidades clave que deseamos proporcionar, tales como:

- Automatización de Tareas: Implementación de herramientas que optimicen y automaticen tareas repetitivas para mejorar la eficiencia.
- Gestión de Información Robusta: Uso de bases de datos para una administración efectiva de la información del proyecto.
- Características Personalizables: Opciones adaptables a las necesidades específicas de cada startup.
- Colaboración Eficiente: Funcionalidades que faciliten la colaboración efectiva entre equipos, incluyendo soporte para metodologías ágiles.

**Elección de la Tecnología**
Con base en los requisitos, hemos seleccionado las siguientes tecnologías para KSI:

- Frontend: Angular para una interfaz de usuario dinámica y receptiva, que permita una interacción fluida con las herramientas de gestión y análisis.

- Configuración del Entorno de Desarrollo ItelliJ IDEA

    - Editor de Código: IntelliJ IDEA.
    - Propósito: Desarrollo de software y edición de código.
    - Ruta de descarga: https://www.jetbrains.com/idea/download/

- Editor de Código: Visual Studio Code
    - Propósito: Desarrollo y edición de código con soporte extensivo para JavaScript y herramientas de desarrollo.
    - Ruta de descarga: https://code.visualstudio.com/

- Control de Versiones: Git, con repositorios en GitHub.
    - Propósito: Gestión de versiones y colaboración en el código.
    - Ruta de descarga: https://git-scm.com/
    - Repositorio: https://github.com/instalert-startup/instalert-project-report 

**Product UX/UI Design**
- UI/UX: Crear una interfaz amigable y accesible para los usuarios.
    - Herramienta: Figma
    - Propósito: Diseño de prototipos y interfaces de usuario.

**Software Development HTML:**

- Descripción: El lenguaje base de etiquetado para aplicaciones web sera empleado en este proyecto.
- Enlace: https://www.w3schools.com/html/default.asp CSS:

Con KSI, buscamos no solo ofrecer herramientas de gestión de proyectos eficientes, sino también actuar como un socio estratégico para las startups, facilitando su crecimiento y éxito en el competitivo mercado tecnológico.

### 5.1.2. Source Code Management.
**Gestión de Cambios en el Código Fuente con GitHub**
En esta sección, nuestro equipo detalla los métodos y la estructura organizativa para gestionar los cambios en el código fuente utilizando GitHub como plataforma de control de versiones. Hemos configurado un repositorio remoto en GitHub para almacenar el código fuente y facilitar la colaboración entre los miembros del equipo. Los URLs de los repositorios son los siguientes:
- Landing Page: https://instalert-startup.github.io/landing-page/

**Estructura del Repositorio**

Hemos organizado el repositorio en ramas específicas para diferentes etapas del desarrollo, garantizando un flujo de trabajo ordenado y eficiente. La estructura de ramas es la siguiente:

- Main branch (rama principal): Contiene la versión estable y lista para producción del software.
- Develop branch: Contiene el código en desarrollo que se integrará en la rama principal después de ser probado y validado.

**Documentación**
La documentación del proyecto se encuentra en el archivo README.md dentro del repositorio. Este archivo proporciona detalles sobre la configuración, el uso del software y las guías para contribuir al proyecto.

### 5.1.3. Source Code Style Guide & Conventions.
En el Source Code Style Guide, presentaremos las convenciones, estilos, diseños y principios aplicados en los lenguajes utilizados durante el desarrollo de nuestro producto. Los lenguajes y herramientas empleados incluyen:

**LENGUAJES UTILIZADOS**

- *HTML* : Estructura del contenido en la web, utilizando etiquetas semánticas para mejorar la accesibilidad.
- *CSS*: Estilos y diseño visual del software, garantizando una experiencia de usuario óptima.

**HTML**

- Nombres Descriptivos: Utiliza nombres de clases e IDs que sean descriptivos y significativos, facilitando la comprensión del propósito de cada elemento. Por ejemplo, en lugar de box, usa project-card.
- Indentación: Indenta correctamente el código HTML para mejorar la legibilidad y mantener una estructura clara.
- Etiquetas Semánticas: Emplea etiquetas semánticas apropiadas, como <header>, <nav>, <main>, y <footer>, para mejorar la accesibilidad y el SEO del sitio.
- Comentarios: Usa comentarios para explicar secciones complejas o partes importantes del código HTML, facilitando la comprensión para otros desarrolladores.

**CSS**

- Nombres Descriptivos: Utiliza nombres de clases y selectores que sean descriptivos y coherentes para facilitar la identificación y el mantenimiento de los estilos. Por ejemplo, usa btn-submit en lugar de btn.
- Agrupación y Comentarios: Agrupa propiedades relacionadas y separa secciones de CSS con comentarios claros, como /_ Estilos de botones _/. Esto organiza el código y facilita su navegación.
- Preferencia por Clases: Prefiere el uso de clases en lugar de IDs para estilos reutilizables y más flexibles.
- Compatibilidad y Prefijos: Utiliza prefijos de vendedor y asegúrate de que el código sea compatible con diferentes navegadores cuando sea necesario.
- Medidas Relativas: Usa medidas relativas como em, rem, y % en lugar de medidas absolutas para mejorar la flexibilidad y la accesibilidad del diseño.
### 5.1.4. Software Deployment Configuration.

En los siguientes pasos se explicará cómo llevar a cabo la implementación de nuestro sitio web utilizando GitHub Pages

Deploy con GitHub Pages: En primer lugar, accedemos al repositorio de GitHub donde se encuentra nuestro proyecto y luego navegamos hacia la configuración del repositorio.

Dentro del menú de ajustes, elegimos la opción "Pages".

**Control de Versiones**

- Uso de Git: Mantén un historial completo de cambios y facilita el manejo de diferentes versiones del código.

En la sección de GitHub Pages, escogemos la rama principal (main) en el menú desplegable de la sección "Branch" y guardamos la configuración presionando el botón "Save". Después de unos momentos, recibiremos el enlace a nuestro sitio web publicado en GitHub Pages.

### 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

En este primer sprint se desarrolló la landing page y la documentación inicial del proyecto InstAlert.

#### 5.2.1.1. Sprint Planning 1

| Sprint # | Sprint 1 |
| :--- | :--- |
| **Sprint Planning Background** | |
| Date | 11/04/2026 |
| Time | 3:30 PM |
| Location | Google Meet |
| Prepared By | Alexander Paolo Justo Yauricasa |
| Attendees (to planning meeting) | Piero Leonardo Molina Falcón<br>Sebastian Victor Andre Diaz Mendoza<br>Breithner Rodolfo Perez Encarnación<br>Alexander Paolo Justo Yauricasa |
| **Sprint 1 Review Summary** | Durante este sprint, el equipo se enfocó en sentar las bases estratégicas del proyecto InstAlert. Se completaron entregables clave de UX como User Personas, Journey Maps y la arquitectura de información, que guiaron el diseño de la plataforma. Con esta base, se diseñó, maquetó y desplegó la primera versión funcional de la landing page. Esta página incluye la propuesta de valor del SaaS, los planes de suscripción. |
| **Sprint 1 Retrospective Summary** | Los miembros del equipo coincidieron en que la colaboración fue fluida gracias a la correcta asignación de roles. Se destacó la sinergia entre el diseño en Figma y la configuración inicial de los repositorios. Para el siguiente sprint, se identificó la oportunidad de mejorar la estimación de tiempos de desarrollo al iniciar la integración del backend. |
| **Sprint Goal & User Stories** | |
| **Sprint 1 Goal** | Nos enfocamos en entregar una primera versión de la landing page desplegada y la documentación de los primeros capítulos del informe. Creemos que esto entrega una propuesta de valor validada para atraer a nuestro segmento objetivo. Esto se confirmará cuando la web esté pública y el informe sea aprobado. |
| **Sprint 1 Velocity** | 20 |
| **Sum of Story Points** | 20 |

#### 5.2.1.2. Aspect Leaders and Collaborators

| Team Member | GitHub Username | Landing Page | Diseño UI/UX | Documentación |
| :--- | :--- | :--- | :--- | :--- |
| Piero Leonardo Molina Falcón | PieroMFAL | Colaborador | Colaborador | Líder |
| Alexander Paolo Justo Yauricasa | AlexanderJusto | Líder | Colaborador | Colaborador |
| Sebastian Victor Andre Diaz Mendoza | DiazDeveloper | Colaborador | Colaborador | Colaborador |
| Breithner Rodolfo Perez Encarnación | Breithner1 | Colaborador | Líder | Colaborador |

#### 5.2.1.3. Sprint Backlog 1

| User Story Id | User Story Title | Work Item/Task Id | Work Item/Task Title | Description | Estimation | Assigned To | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| US-13 | Descarga de la aplicación | T01 | Maquetado HTML base | Estructura de la landing: header, hero section y footer. | 3h | Alexander Justo | Done |
| US-14 | Visualización de información de la plataforma | T02 | Informacion landing | Implementación de la informacion de la aplicacion. | 2h | Piero Molina | Done |
| US-15 | Registro desde la landing page | T03 | Contacto | Implementacion de un formulario para contactarnos. | 2h | Sebastian Diaz | Done |
| US-16 | Visualización de testimonios o casos de uso | T04 | Testimonios | Revicion de las entrevistas y inplementacion de estas. | 2h | Breithner Perez | Done |

#### 5.2.1.4. Development Evidence for Sprint Review

En este primer Sprint hemos realizado la implementación de nuestra Landing Page y la configuración inicial de los repositorios, donde todo el equipo ha aportado mediante la gestión de ramas. En la siguiente tabla se muestran los commits realizados.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| instalert-startup/landing-page | main | 15ad028 | Initial commit | Initial commit | 19/04/2026 |
| instalert-startup/landing-page | main | 33ad2a9 | Actualización de index.html | Agregar codigo de html. | 19/04/2026 |
| instalert-startup/landing-page | main | 51ad5a7 | Actualización de index.html | Correcciones. | 03/05/2026 |

#### 5.2.1.5. Execution Evidence for Sprint Review.
En este Sprint, los miembros del equipo de desarrollo de software de KSI han completado y desplegado la Landing Page. A continuación, mostramos imágenes que demuestran cómo nuestra página presenta de manera clara e intuitiva la información sobre nuestro producto y nuestra empresa.

<img src="Imagen/landingPage-InstAlert.png">

#### 5.2.1.6. Services Documentation Evidence for Sprint Review.
No se emplearon servicios adicionales, ya que este primer sprint se centró exclusivamente en la implementación de la primera versión del web application.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.

Resumen Durante este Sprint, nos hemos enfocado en el despliegue de la landing page. Las actividades realizadas incluyen la configuración del entorno de desarrollo y el despliegue inicial del sitio. A continuación, se detalla el proceso seguido para el despliegue de la landing page.

**Actividades Realizadas**

- Creación de Cuentas y Configuración de Recursos:
Proveedor de Hosting: Selección y configuración de la cuenta en el proveedor de hosting para desplegar la landing page. Configuración del Entorno: Establecimiento del entorno de desarrollo y producción para la landing page.

- Configuración de Proyectos para Integración:
Repositorio de Código: Configuración del repositorio en GitHub para la integración continua y despliegue automático. Automatización: Configuración de scripts y herramientas para la automatización del despliegue.

- Despliegue de la Landing Page:
Subida de Archivos: Transferencia de archivos y recursos al servidor de hosting. Verificación: Comprobación de que la landing page se despliega correctamente y está accesible en la web.

Enlace al Repositorio: https://github.com/instalert-startup/landing-page 
#### 5.2.1.8. Team Collaboration Insights during Sprint.
En esta sección, se presenta un análisis detallado de la colaboración del equipo durante el Sprint. Durante este sprint, las actividades de implementación se organizaron siguiendo una metodología ágil, garantizando una colaboración fluida entre los miembros del equipo. Se exponen capturas de los analíticos de colaboración y de los commits realizados en GitHub, lo que permite visualizar la contribución individual de cada miembro del equipo.

- Diseño y Desarrollo: Diseño de la Landing Page: Desarrollo y diseño completo de la landing page, incluyendo la creación de secciones y funcionalidad. Implementación: Realización de las tareas de codificación, pruebas y ajustes necesarios para completar la página.
- Documentación y Despliegue: Documentación: Creación de documentación relevante para la landing page, incluyendo capturas de pantalla y descripciones. Despliegue: Configuración del entorno de despliegue y transferencia de archivos al servidor.
URL LANDING PAGE DESPLEGADA: https://instalert-startup.github.io/landing-page/

