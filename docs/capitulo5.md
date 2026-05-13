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


### 5.2.2. Sprint 2

#### 5.2.2.1. Sprint Planning 2

#### 5.2.2.1. Sprint Planning 2

| Sprint # | Sprint 2 |
| :--- | :--- |
| **Sprint Planning Background** | |
| Date | 10/05/2026 |
| Time | 5:30 PM |
| Location | Virtual |
| Prepared By | Sebastian Victor Andre Diaz Mendoza |
| Attendees (to planning meeting) | Piero Leonardo Molina Falcón<br>Sebastian Victor Andre Diaz Mendoza<br>Alexander Paolo Justo Yauricasa<br>Breithner Rodolfo Perez Encarnación |
| **Sprint 2 Review Summary** | Durante este sprint, el equipo se enfocó de lleno en el desarrollo e implementación de la interfaz de usuario (UI) de la aplicación web InstAlert. Se logró maquetar, diseñar e integrar la experiencia visual abarcando un total de 23 Historias de Usuario (HU). Esto incluyó la creación de componentes interactivos, vistas de reportes, mapas de zonas de riesgo y flujos de navegación, sentando toda la base frontend de la plataforma. |
| **Sprint 2 Retrospective Summary** | El equipo demostró una gran capacidad de ejecución y coordinación para manejar el alto volumen de tareas visuales. El uso de componentes reutilizables agilizó significativamente el desarrollo de las 28 HU. Como punto de mejora, identificamos que para los próximos sprints debemos optimizar los tiempos de revisión en los Pull Requests para evitar cuellos de botella antes de integrar la lógica de negocio y la conexión con bases de datos. |
| **Sprint Goal & User Stories** | |
| **Sprint 2 Goal** | Completar el diseño y la maquetación frontend de la aplicación web InstAlert, garantizando que las interfaces de las 28 HU planificadas sean totalmente funcionales a nivel visual, responsivas y alineadas con la guía de estilos, dejando el proyecto listo para la integración con los servicios del backend. |
| **Sprint 2 Velocity** | 84 |
| **Sum of Story Points** | 84 |

#### 5.2.2.2. Aspect Leaders and Collaborators

Durante el desarrollo del Sprint 2, se han identificado distintos aspectos funcionales relacionados al diseño y construcción de la aplicación web de InstAlert. Con el objetivo de organizar el trabajo del equipo de manera eficiente, se ha elaborado una matriz de Liderazgo y Colaboración (LACX), donde se asigna a cada integrante el rol de líder (L) en los módulos clave del desarrollo que se le han asignado, y el rol de colaborador (C) en otros aspectos. 

Los aspectos definidos para este Sprint, basados en las 28 Historias de Usuario trabajadas, son:

1. **Apartado de Login:** Registro e inicio de sesión.
2. **Apartado de Configuración:** Perfil, preferencias de notificación y comunidades cercanas.
3. **Apartado de Comunidad:** Solicitudes de apoyo, asistentes rápidos y panel de monitoreo.
4. **Botón de Emergencia y Dashboard:** Envío, recepción, historial y cancelación de alertas con geolocalización.
5. **Reportes:** Creación, adjunto de evidencias y filtros de incidentes y zonas.
6. **Mapa de Riesgo:** Visualización, filtros por nivel de riesgo y búsqueda de direcciones.
7. **Revisión general y mejoras:** Pruebas visuales, responsividad y ajustes de UI/UX conjuntos.

A continuación, se presenta la matriz de responsabilidades del equipo:

| Team Member (Last Name, First Name) | GitHub Username | Login | Configuration | Community | Emergency Button & Dashboard | Reports | Risk Map | Review and improvements |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Justo Yauricasa, Alexander Paolo | AlexanderJusto | L | L | L | C | C | C | C |
| Diaz Mendoza, Sebastian Victor Andre | DiazDeveloper | C | C | C | L | C | C | C |
| Perez Encarnación, Breithner Rodolfo | Breithner1 | C | C | C | C | L | C | C |
| Molina Falcón, Piero Leonardo | PieroMFAL | C | C | C | C | C | L | C |

#### 5.2.2.3. Sprint Backlog 2

| User Story Id | User Story Title | Work Item/Task Id | Work Item/Task Title | Description | Estimation | Assigned To | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| US-01 | Registro de usuario | T01 | Interfaz de Registro | Maquetación del formulario para crear una nueva cuenta. | 3h | Alexander Justo | To Do |
| US-02 | Inicio de sesión | T02 | Interfaz de Login | Maquetación de la vista de autenticación de usuarios. | 2h | Alexander Justo | To Do |
| US-03 | Configuración de perfil | T03 | Vista Perfil y Comunidades | Diseño de los campos de usuario y apartado de comunidades cercanas. | 4h | Alexander Justo | To Do |
| US-23 | Configurar preferencias de notificación | T04 | UI Preferencias Notificación | Diseño de toggles y opciones para configuración de alertas. | 2h | Alexander Justo | To Do |
| US-26 | Solicitar apoyo a la comunidad cercana | T05 | Modal de Apoyo | Interfaz para emitir solicitudes de ayuda a vecinos. | 3h | Alexander Justo | To Do |
| US-27 | Solicitar un asistente rápido | T06 | Vista de Asistente Rápido | Maquetación del panel de solicitud de asistencia. | 2h | Alexander Justo | To Do |
| US-28 | Panel de monitoreo para contactos | T07 | UI Monitoreo Contactos | Diseño de lista y estado activo de contactos asignados. | 3h | Alexander Justo | To Do |
| US-04 | Envío de alerta de emergencia | T08 | UI Botón de Emergencia | Diseño del botón principal y pantalla de confirmación. | 4h | Sebastian Diaz | To Do |
| US-05 | Geolocalización automática en alertas | T09 | UI Indicador de Ubicación | Componente visual que muestra las coordenadas capturadas. | 2h | Sebastian Diaz | To Do |
| US-06 | Recepción de alertas cercanas | T10 | UI Alertas Entrantes | Tarjetas visuales para notificar emergencias en la zona. | 3h | Sebastian Diaz | To Do |
| US-07 | Cancelación de alerta | T11 | Modal de Cancelación | Interfaz con confirmación de seguridad para anular alerta. | 2h | Sebastian Diaz | To Do |
| US-08 | Historial de alertas | T12 | UI Lista de Historial | Tabla o timeline con el registro de alertas previas. | 3h | Sebastian Diaz | To Do |
| US-09 | Creación de reportes de incidentes | T13 | Formulario de Reporte | Maquetación del modal/página para detallar un incidente. | 3h | Breithner Perez | To Do |
| US-10 | Adjuntar evidencia a reportes | T14 | UI Subida de Archivos | Diseño de zona drag & drop y vista previa de imágenes. | 2h | Breithner Perez | To Do |
| US-11 | Visualización de reportes en el mapa | T15 | UI Pines en Mapa | Diseño de marcadores visuales para incidentes en el mapa. | 3h | Breithner Perez | To Do |
| US-12 | Filtro de reportes | T16 | UI Controles de Filtro | Selectores para filtrar incidentes por fecha y categoría. | 2h | Breithner Perez | To Do |
| US-22 | Reporte de zonas con poca iluminación | T17 | UI Reporte Iluminación | Variante del formulario adaptada a reportes de vía pública. | 2h | Breithner Perez | To Do |
| US-23 | Recibir alertas de emergencia cercanas | T18 | Popups de Emergencia | Diseño de la notificación emergente tipo banner. | 2h | Breithner Perez | To Do |
| US-25 | Recibir notificaciones de actividad comunitaria | T19 | Feed de Actividad | Diseño del listado lateral de notificaciones comunitarias. | 3h | Breithner Perez | To Do |
| US-26 | Enviar alerta a contactos de emergencia | T20 | UI Selector de Contactos | Interfaz para seleccionar a quién notificar en una alerta. | 2h | Breithner Perez | To Do |
| US-18 | Visualizar mapa de zonas de riesgo | T21 | UI Mapa Base | Contenedor principal para la visualización cartográfica. | 4h | Piero Molina | To Do |
| US-19 | Filtrar zonas por nivel de riesgo | T22 | UI Capas de Riesgo | Botones/Selectores de niveles (Alto, Medio, Bajo). | 3h | Piero Molina | To Do |
| US-20 | Consultar detalles de una zona de riesgo | T23 | Tarjeta de Detalles de Zona | Panel lateral flotante con estadísticas de la zona clicada. | 3h | Piero Molina | To Do |
| US-21 | Búsqueda de direcciones específicas | T24 | UI Barra de Búsqueda | Componente de input con diseño de autocompletado. | 2h | Piero Molina | To Do |

#### 5.2.2.4. Development Evidence for Sprint Review

En este segundo Sprint hemos realizado la implementación del fronte-end, donde todo el equipo ha aportado mediante la gestión de ramas. En la siguiente tabla se muestran los commits realizados.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| DiazDeveloper | feature/Alexander | b133adb87ea2fe29bbab4b993cefd8f18ab7b842 | -- | -- | [12/05/2026] |
| DiazDeveloper | feature/report | 1ca6bd2ee4032be7b56aa7ceb6cd0f7e9e0f2840 | -- | -- | [12/05/2026] |
| DiazDeveloper | feature/sebdiaz | f7c920e4a1d83b56e0f4c2a918d7b3e52f6a0c84 | -- | -- | [12/05/2026] |
| DiazDeveloper | feature/piero | 3e8d1f70b25c94a6e0f3d1b728a59c4e16f80d23 | -- | -- | [12/05/2026] |

#### 5.2.2.5. Execution Evidence for Sprint Review.

Basado en el ejemplo que me proporcionaste y en la información de tu proyecto InstAlert, aquí tienes la redacción adaptada para tu reporte de sprint:

Durante este sprint, se desarrollaron 22 historias de usuario únicas centradas en la implementación de la aplicación web de InstAlert. Este sprint se enfocó en crear funcionalidades clave orientadas a la seguridad ciudadana, tales como el sistema de autenticación y configuración de cuentas, la implementación de un botón de emergencia con geolocalización automática, el módulo de reportes comunitarios y la visualización interactiva de mapas de riesgo. Las historias incluyen tanto el diseño de interfaces de usuario como la implementación de funciones críticas como el envío y recepción de alertas cercanas, la creación de reportes de incidentes con evidencia adjunta, y la capacidad de solicitar apoyo a la comunidad cercana.

El equipo completó con éxito todas las tareas planificadas para los apartados de Login, Configuración, Comunidad, Botón de emergencia, Reportes y Mapa de riesgo. Además, se logró un diseño responsive para todas las secciones clave de la aplicación, garantizando una experiencia de usuario fluida, intuitiva —fundamental para reducir la fricción en situaciones de alto estrés o urgencia— y completamente alineada con los objetivos estratégicos de prevención y reacción rápida de la plataforma.

Evidencia visual:

A continuación, se presentan capturas de pantalla de las vistas implementadas en este Sprint:

incio de sesion

<img src="../assets/images/mockapplicationweb/evidencia3.jpeg" alt="Tipografía" width="700">

Configuracion de perfil

<img src="../assets/images/mockapplicationweb/evidencia2.jpeg" alt="Tipografía" width="700">

<img src="../assets/images/mockapplicationweb/evidencia1.jpeg" alt="Tipografía" width="700">

Boton de panico

<img src="../assets/images/mockapplicationweb/evidencia4.jpeg" alt="Tipografía" width="700">

<img src="../assets/images/mockapplicationweb/evidencia5.jpeg" alt="Tipografía" width="700">

Reportes

<img src="../assets/images/mockapplicationweb/evidencia6.jpeg" alt="Tipografía" width="700">

<img src="../assets/images/mockapplicationweb/evidencia7.jpeg" alt="Tipografía" width="700">

Mapa de Riesgo

<img src="../assets/images/mockapplicationweb/evidencia9.jpeg" alt="Tipografía" width="700">

<img src="../assets/images/mockapplicationweb/evidencia10.jpeg" alt="Tipografía" width="700">

<img src="../assets/images/mockapplicationweb/evidencia11.jpeg" alt="Tipografía" width="700">

<img src="../assets/images/mockapplicationweb/evidencia12.jpeg" alt="Tipografía" width="700">

#### 5.2.2.6. Services Documentation Evidence for Sprint Review

Durante el Sprint 2, el desarrollo del frontend de InstAlert para las funcionalidades de autenticación, alertas de emergencia, reportes de incidentes, visualización del mapa de riesgos, gestión de comunidades y notificaciones se implementó utilizando una API fake. Esta API simulada se localiza en la carpeta `server` y dentro se encuentra el archivo `db.json`, el cual contiene toda la información de los datos utilizados. El uso de esta fake API (JSON Server) nos permitió emular las operaciones de una base de datos real y validar la interfaz gráfica sin depender del backend definitivo.

| Endpoint Simulado (Fake API) | Entidad Principal Gestionada | Operaciones CRUD Soportadas (Simuladas) vía JSON Server | Futuro Alcance con OpenAPI |
| :--- | :--- | :--- | :--- |
| `http://localhost:3000/users` | Usuarios (Users) | GET, POST, PUT | Documentación para el registro de usuarios, inicio de sesión, configuración de perfil y gestión de contactos de emergencia. |
| `http://localhost:3000/alerts` | Alertas (Alerts) | GET, POST, PUT, DELETE | Documentación para gestionar el envío, recepción, historial y cancelación de alertas de emergencia con geolocalización. |
| `http://localhost:3000/reports` | Reportes (Reports) | GET, POST | Documentación para la creación de reportes de incidentes, adjuntar evidencias y aplicar filtros de búsqueda. |
| `http://localhost:3000/risk-zones` | Zonas de Riesgo (Risk Zones) | GET | Documentación para consultar las coordenadas, detalles y niveles de riesgo de las zonas mostradas en el mapa interactivo. |
| `http://localhost:3000/communities` | Comunidades (Communities) | GET, POST | Documentación para obtener información de las comunidades cercanas y gestionar solicitudes de apoyo o asistentes rápidos. |
| `http://localhost:3000/notifications` | Notificaciones (Notifications) | GET, POST, DELETE | Documentación para gestionar las preferencias del usuario, recibir alertas entrantes y notificaciones de actividad comunitaria. |

#### 5.2.2.7. Software Deployment Evidence for Sprint Review.

**Resumen**
Durante este Sprint, nos hemos enfocado en el despliegue de [Nombre de la aplicación o módulo]. Las actividades realizadas incluyen la configuración del entorno y el despliegue. A continuación, se detalla el proceso seguido.

**Actividades Realizadas**

- [Actividad 1, Ej: Configuración de Base de Datos]: [Descripción de la actividad].
- [Actividad 2, Ej: Configuración de Proyectos para Integración]: [Descripción de la actividad].
- [Actividad 3, Ej: Despliegue de la Web App]: [Descripción de la actividad].

**Enlace al Repositorio:** [URL del repositorio]  
**Enlace de Despliegue:** [URL del proyecto desplegado, si aplica]  

#### 5.2.2.8. Team Collaboration Insights during Sprint.

En esta sección, se presenta un análisis detallado de la colaboración del equipo durante el Sprint. Las actividades de implementación se organizaron siguiendo una metodología ágil, garantizando una colaboración fluida. 

- **Diseño y Desarrollo:** [Resumen de cómo se dividieron y ejecutaron las tareas de código y diseño].
- **Documentación y Despliegue:** [Resumen de cómo se manejó la redacción del informe y las configuraciones de hosting/servidores].

*[Opcional: Puedes incluir aquí imágenes de los analíticos de GitHub o herramientas de Jira/Trello si tu equipo las utiliza]*


