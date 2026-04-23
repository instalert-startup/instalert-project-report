# InstAlert

## Plataforma Web de Seguridad Ciudadana

InstAlert es una aplicación web orientada a mejorar la seguridad ciudadana mediante alertas en tiempo real, reportes comunitarios, botón de pánico, reportes ciudadanos y visualización de zonas de riesgo.

---

## Curso

Desarrollo de Aplicaciones Open Source

## Universidad

Universidad Peruana de Ciencias Aplicadas (UPC)

## Carrera

Ingeniería de Software

## Ciclo

2026-10

## NRC

[Colocar NRC]

## Profesor

[Nombre del docente]

---

## Startup

InstAlert Startup

## Producto

InstAlert

---

## Integrantes

* Nombre completo — Código UPC
* Nombre completo — Código UPC
* Nombre completo — Código UPC
* Nombre completo — Código UPC

---

## Repositorio del Informe

Este repositorio contiene la documentación oficial del proyecto final desarrollada en formato Markdown, siguiendo GitFlow, Conventional Commits y Semantic Versioning según los lineamientos del curso.

---

## Tabla de Contenidos

* Capítulo I: Introducción
* Capítulo II: Requirements Elicitation & Analysis
* Capítulo III: Requirements Specification
* Capítulo IV: Product Design
* Capítulo V: Product Implementation, Validation & Deployment
* Conclusiones
* Bibliografía
* Anexos



### Capítulo III: Requirements Specification 
## 3.1.User Stories
EP01	Gestión de Cuenta y Configuración <br>
EP02	Gestión de Alertas de Emergencia <br>
EP03	Reportes Comunitarios de Incidentes <br>
EP04	Gestión del Landing Pague <br>
EP05	Visualización de Zonas de Riesgo <br>
EP06	Visualización de Zonas de Riesgo <br>
EP07	Red de Apoyo y Contactos de Emergencia <br><br>

| Epic | titulo | descripcion |Criterios de Aceptacion|Relacionado con Epic ID|
|------|--------|-------------|-------------|-------------|
|HU1|Registro de usuario| Como cliente o comerciante quiero registrar mi mis datos para poder ingresar a la aplciacion y recibir notificion. | **Esenario 1: Registro exitoso de usuario** <br> _Dado_ que el cliente o comerciante accede a la pantalla de registro <br> _Cuando_ ingresa correctamente sus datos (nombre, correo, contraseña, teléfono, etc.) y presiona el botón "Registrarse" <br> _Entonces_ el sistema valida la información y crea la cuenta exitosamente Y el usuario es redirigido a la aplicación con acceso habilitado para recibir notificaciones <br><br> **Escenario 2: Error en el registro por datos inválidos** <br> _Dado_ que el cliente o comerciante se encuentra en la pantalla de registro <br> _Cuando_ ingresa datos incompletos, incorrectos o un correo ya registrado <br> _Entonces_ el sistema muestra un mensaje de error indicando el problema <br> _Y_ no permite completar el registro hasta que los datos sean corregidos|EP01|
| HU2 | Inicio de sesión |Como cliente o comerciante, quiero iniciar sesión en la aplicación con mis credenciales para acceder a mis funciones, recibir notificaciones y gestionar mi información de forma segura. | **Escenario 1: Inicio de sesión exitoso** <br> _Dado_ que el usuario se encuentra en la pantalla de inicio de sesión <br> _Cuando_ ingresa su correo y contraseña correctamente <br> _Entonces_ el sistema valida las credenciales <br> _Y_ permite el acceso a la aplicación <br> _Y_ redirige al usuario a la pantalla principal <br><br>  **Escenario 2: Error en el inicio de sesión por credenciales incorrectas** <br> _Dado_ que el usuario está en la pantalla de inicio de sesión <br> _Cuando_ ingresa un correo o contraseña incorrectos <br> _Entonces_ el sistema muestra un mensaje de error indicando credenciales inválidas <br> _Y_ no permite el acceso a la aplicación |EP01|
| HU3 | Configuración de perfil | Como cliente o comerciante, quiero configurar y actualizar mi perfil para mantener mis datos personales correctos y personalizar mi experiencia en la aplicación. | **Escenario 1: Actualización exitosa del perfil** <br> _Dado_ que el usuario ha iniciado sesión en la aplicación <br> _Cuando_ accede a la sección de perfil y modifica sus datos (nombre, teléfono, correo, etc.) correctamente <br> _Entonces_ el sistema guarda los cambios exitosamente <br> _Y_ muestra un mensaje de confirmación <br><br> **Escenario 2: Error al actualizar el perfil por datos inválidos** <br> _Dado_ que el usuario se encuentra en la sección de configuración de perfil <br> _Cuando_ ingresa datos incorrectos o incompletos <br> _Entonces_ el sistema muestra un mensaje de error indicando los campos inválidos <br> _Y_ no guarda los cambios hasta que la información sea corregida | EP01 |
| HU4 | Envío de alerta de emergencia | Como cliente o comerciante, quiero enviar una alerta de emergencia para notificar rápidamente a otros usuarios y autoridades sobre una situación de riesgo. | **Escenario 1: Envío exitoso de alerta de emergencia** <br> _Dado_ que el usuario ha iniciado sesión en la aplicación <br> _Cuando_ presiona el botón de alerta y confirma el envío <br> _Entonces_ el sistema registra la alerta con la ubicación y hora <br> _Y_ envía notificaciones a usuarios cercanos y contactos de emergencia | EP02 |
| HU5 | Geolocalización automática en alertas | Como cliente o comerciante, quiero que la aplicación obtenga automáticamente mi ubicación al enviar una alerta para proporcionar información precisa del incidente. | **Escenario 1: Geolocalización obtenida correctamente** <br> _Dado_ que el usuario ha iniciado sesión en la aplicación <br> _Y_ tiene activado el servicio de ubicación en su dispositivo <br> _Cuando_ envía una alerta de emergencia <br> _Entonces_ el sistema captura automáticamente la ubicación actual del usuario <br> _Y_ adjunta la geolocalización a la alerta enviada  | EP02 |
| HU6 | Recepción de alertas cercanas | Como cliente o comerciante, quiero recibir alertas de emergencia cercanas para estar informado y tomar precauciones ante posibles riesgos en mi entorno. | Escenario 1: Recepción de alertas cercanas en tiempo real <br> Dado que el usuario ha iniciado sesión en la aplicación <br> Y tiene activadas las notificaciones y la ubicación <br> Cuando se genera una alerta de emergencia dentro de su radio de proximidad <br> Entonces el sistema envía una notificación inmediata al usuario <br> Y muestra los detalles de la alerta (ubicación, tipo de incidente y hora) | EP02 |
| HU7 | Cancelación de alerta | Como cliente o comerciante, quiero cancelar una alerta enviada para evitar confusiones en caso de haberla activado por error. | **Escenario 1: Cancelación exitosa de alerta** <br> _Dado_ que el usuario ha enviado una alerta de emergencia <br> _Cuando_ accede a la opción de cancelar la alerta y confirma la acción <br> _Entonces_ el sistema actualiza el estado de la alerta a cancelada <br> _Y_ notifica a los usuarios que recibieron la alerta sobre su cancelación | EP02 |
| HU8 | Historial de alertas | Como cliente o comerciante, quiero visualizar el historial de alertas para consultar eventos pasados y llevar un seguimiento de las situaciones reportadas. | **Escenario 1: Visualización del historial de alertas** <br> _Dado_ que el usuario ha iniciado sesión en la aplicación <br> _Cuando_ accede a la sección de historial de alertas <br> _Entonces_ el sistema muestra la lista de alertas enviadas y recibidas <br> _Y_ presenta detalles como fecha, ubicación, tipo de incidente y estado | EP02 |
| HU9 | Creación de reportes de incidentes | Como cliente o comerciante, quiero crear reportes de incidentes para informar a la comunidad sobre situaciones relevantes que no requieren una alerta de emergencia. | **Escenario 1: Creación exitosa de reporte de incidente** <br> _Dado_ que el usuario ha iniciado sesión en la aplicación <br> _Cuando_ accede a la opción de crear reporte, completa la información del incidente y lo envía <br> _Entonces_ el sistema registra el reporte correctamente <br> _Y_ lo publica para que otros usuarios puedan visualizarlo | EP03 |
| HU10 | Adjuntar evidencia a reportes | Como cliente o comerciante, quiero adjuntar evidencia (imágenes o videos) a mis reportes para brindar mayor contexto y credibilidad al incidente reportado. | **Escenario 1: Adjuntar evidencia exitosamente** <br> _Dado_ que el usuario ha iniciado sesión en la aplicación <br> _Cuando_ crea o edita un reporte y adjunta una imagen o video válido <br> _Entonces_ el sistema carga correctamente el archivo <br> _Y_ lo asocia al reporte para su visualización por otros usuarios | EP03 |
| HU11 | Visualización de reportes en el mapa | Como cliente o comerciante, quiero visualizar los reportes de incidentes en un mapa para identificar rápidamente las zonas con mayor ocurrencia y tomar precauciones. | **Escenario 1: Visualización de reportes en el mapa** <br> _Dado_ que el usuario ha iniciado sesión en la aplicación <br> _Cuando_ accede a la vista de mapa de reportes <br> _Entonces_ el sistema muestra los reportes geolocalizados en el mapa <br> _Y_ permite ver detalles básicos del incidente al seleccionar un punto | EP03 |
| HU12 | Filtro de reportes | Como cliente o comerciante, quiero filtrar los reportes de incidentes para encontrar información relevante según mis necesidades (tipo de incidente, ubicación, fecha, etc.). | **Escenario 1: Filtrado de reportes exitoso** <br> _Dado_ que el usuario ha iniciado sesión en la aplicación <br> _Cuando_ accede a la sección de reportes y aplica filtros (tipo, fecha o ubicación) <br> _Entonces_ el sistema muestra únicamente los reportes que coinciden con los criterios seleccionados <br> _Y_ actualiza la lista de resultados de forma dinámica | EP03 |
| HU13 | Descarga de la aplicación | Como visitante, quiero acceder a enlaces de descarga para instalar la aplicación en mi dispositivo. | **Escenario 1: Descarga exitosa de la aplicación** <br> _Dado_ que el usuario se encuentra en la landing page <br> _Cuando_ selecciona el botón de descarga correspondiente a su dispositivo <br> _Entonces_ el sistema redirige a la tienda de aplicaciones correspondiente <br> _Y_ permite iniciar la descarga de la aplicación | EP4 |
| HU14 | Visualización de información de la plataforma | Como visitante, quiero ver información clara sobre InstAlert para entender sus beneficios y funcionamiento. | **Escenario 1: Visualización de información en la landing page** <br> _Dado_ que el usuario accede a la landing page <br> _Cuando_ navega por las secciones informativas <br> _Entonces_ el sistema muestra contenido sobre funcionalidades, beneficios y uso de la plataforma <br> _Y_ presenta la información de manera clara y estructurada | EP4 |
| HU15 | Registro desde la landing page | Como visitante, quiero registrarme directamente desde la landing page para comenzar a usar la aplicación rápidamente. | **Escenario 1: Registro exitoso desde la landing page** <br> _Dado_ que el usuario se encuentra en la landing page <br> _Cuando_ completa el formulario de registro con datos válidos <br> _Entonces_ el sistema crea la cuenta exitosamente <br> _Y_ redirige al usuario a la aplicación o confirma el registro | EP4 |
| HU16 | Visualización de testimonios o casos de uso | Como visitante, quiero ver experiencias de otros usuarios para confiar en la efectividad de la plataforma. | **Escenario 1: Visualización de testimonios** <br> _Dado_ que el usuario accede a la landing page <br> _Cuando_ navega a la sección de testimonios o casos de uso <br> _Entonces_ el sistema muestra opiniones y experiencias de usuarios <br> _Y_ presenta contenido que refuerza la confianza en la plataforma | EP4 |
| HU17 | Suscripción a notificaciones o novedades | Como visitante, quiero suscribirme para recibir noticias o actualizaciones sobre la plataforma. | **Escenario 1: Suscripción exitosa** <br> _Dado_ que el usuario se encuentra en la landing page <br> _Cuando_ ingresa su correo electrónico y se suscribe <br> _Entonces_ el sistema registra la suscripción correctamente <br> _Y_ confirma al usuario que recibirá futuras notificaciones o novedades | EP4 |
| HU18 | Visualizar mapa de zonas de riesgo | Como usuario, quiero ver un mapa con zonas de riesgo, para identificar áreas peligrosas cercanas. | **Escenario 1: Visualización exitosa** <br> _Dado_ que el usuario accede al mapa <br> _Cuando_ la aplicación carga la información <br> _Entonces_ el sistema muestra zonas de riesgo geolocalizadas <br><br> **Escenario 2: Sin conexión** <br> _Dado_ que el usuario no tiene conexión a internet <br> _Cuando_ intenta acceder al mapa <br> _Entonces_ el sistema muestra un mensaje de error <br> | EP5 |
| HU19 | Filtrar zonas por nivel de riesgo | Como usuario, quiero filtrar zonas según nivel de peligro, para analizar mejor la información. | **Escenario 1: Filtro aplicado** <br> _Dado_ que el usuario selecciona un nivel de riesgo <br> _Cuando_ aplica el filtro <br> _Entonces_ el sistema muestra solo las zonas correspondientes <br> **Escenario 2: Sin resultados** <br> _Dado_ que no existen zonas con ese nivel <br> _Cuando_ aplica el filtro <br> _Entonces_ el sistema muestra un mensaje informativo <br> | EP5 |
| HU20 | Consultar detalles de una zona de riesgo | Como usuario, quiero ver detalles de una zona específica, para entender el tipo de incidentes ocurridos. | **Escenario 1: Consulta exitosa** <br> _Dado_ que el usuario selecciona una zona en el mapa <br> _Cuando_ accede a sus detalles <br> _Entonces_ el sistema muestra información como tipo de incidentes y frecuencia <br> **Escenario 2: Error de carga** <br> _Dado_ que ocurre un fallo en la carga <br> _Cuando_ intenta ver detalles <br> _Entonces_ el sistema muestra un mensaje de error <br> | EP5 |
| HU21 | Búsqueda de direcciones específicas | Como usuario, quiero buscar una dirección o lugar en el mapa para conocer el nivel de riesgo de un destino antes de dirigirme allí. | **Escenario 1: Búsqueda con resultados** <br> _Dado_ que el usuario ingresa una dirección en la barra de búsqueda <br> _Cuando_ presiona "Enter" o el icono de lupa <br> _Entonces_ el sistema centra el mapa en esa ubicación y despliega los indicadores de riesgo cercanos <br> **Escenario 2: Dirección no encontrada** <br> _Dado_ que el usuario ingresa un texto que no coincide con ninguna ubicación <br> _Cuando_ realiza la búsqueda <br> _Entonces_ el sistema muestra un mensaje indicando que no se pudo encontrar el lugar <br> | EP5 |
| HU22 | Reporte de zonas con poca iluminación | Como usuario, quiero marcar áreas con deficiencia de alumbrado público en el mapa para advertir a otros sobre condiciones que facilitan la delincuencia. | **Escenario 1: Registro de zona oscura** <br> _Dado_ que el usuario selecciona la opción "Reportar falta de luz" <br> _Cuando_ marca el punto en el mapa <br> _Entonces_ el sistema añade un icono específico de "Zona Oscura" visible para toda la comunidad <br> **Escenario 2: Visualización de advertencia** <br> _Dado_ que un usuario navega cerca de un punto marcado como oscuro <br> _Cuando_ el sistema carga el mapa <br> _Entonces_ muestra una advertencia visual sobre la falta de iluminación en ese tramo <br> | EP5 |
| HU23 | Recibir alertas de emergencia cercanas | Como usuario, quiero recibir alertas cercanas, para estar informado de situaciones de peligro. | **Escenario 1: Notificación recibida** <br> _Dado_ que ocurre una alerta cerca del usuario <br> _Cuando_ el sistema detecta proximidad <br> _Entonces_ envía una notificación en tiempo real <br> **Escenario 2: Notificaciones desactivadas** <br> _Dado_ que el usuario desactivó notificaciones <br> _Cuando_ ocurre una alerta <br> _Entonces_ el sistema no envía notificación <br> | EP6 |
| HU24 | Configurar preferencias de notificación | Como usuario, quiero configurar qué tipo de alertas recibir, para evitar información innecesaria. | **Escenario 1: Configuración guardada** <br> _Dado_ que el usuario selecciona una zona en el mapa <br> _Cuando_ accede a sus detalles <br> _Entonces_ el sistema muestra información como tipo de incidentes y frecuencia <br> **Escenario 2: Error de carga** <br> _Dado_ que ocurre un fallo en la carga <br> _Cuando_ intenta guardar <br> _Entonces_ el sistema muestra un mensaje de error <br> | EP6 |
| HU25 | Recibir notificaciones de actividad comunitaria | Como usuario, quiero recibir notificaciones sobre reportes de la comunidad, para mantenerme informado. | **Escenario 1: Notificación de reporte** <br> _Dado_ que un usuario reporta un incidente <br> _Cuando_ este es relevante para la ubicación <br> _Entonces_ el sistema notifica <br> **Escenario 2: Sin relevancia geográfica** <br> _Dado_ que el incidente está lejos <br> _Cuando_ ocurre <br> _Entonces_ el sistema no notifica <br> | EP6 |
| HU26 |  Enviar alerta a contactos de emergencia|  Como usuario, quiero enviar alertas a mis contactos, para pedir ayuda inmediata.| **Escenario 1: Registro exitoso** <br> _Dado_ que el usuario activa el botón de emergencia <br> _Cuando_ se genera la alerta <br> _Entonces_ el sistema envía notificación con ubicación a los contactos <br> **Escenario 2: Error de envío** <br> _Dado_ que ocurre un fallo de red <br> _Cuando_ intenta enviar la alerta <br> _Entonces_ el sistema muestra un mensaje de error <br> | EP7 |
| HU27 | Solicitar apoyo a la comunidad cercana | Como usuario, quiero solicitar ayuda a usuarios cercanos, para recibir asistencia rápida. | **Escenario 1: Registro exitoso** <br> _Dado_ que el usuario activa la solicitud de ayuda <br> _Cuando_ se envía <br> _Entonces_ los usuarios cercanos reciben la alerta <br> **Escenario 2: Error de envío** <br> _Dado_ que no hay usuarios en el área <br> _Cuando_ envía la solicitud <br> _Entonces_ el sistema notifica que no hay disponibilidad <br> | EP7 |
| HU28 | Solicitar un asistente rapido   | Como usuario, quiero solicitar ayuda a usuarios cercanos, para recibir asistencia rápida. | **Escenario 1: Aceptación exitosa** <br> _Dado_ que el usuario envía una solicitud de contacto <br> _Cuando_ el destinatario hace clic en el enlace de aceptación <br> _Entonces_ el sistema activa el vínculo y notifica al usuario remitente <br> **Escenario 2: Rechazo de solicitud** <br> _Dado_ que una persona recibe una invitación por error <br> _Cuando_ selecciona "Rechazar" <br> _Entonces_ el sistema elimina la solicitud y no permite el envío de alertas a ese número <br> | EP7 |
| HU29 |Panel de monitoreo para contactos   | Como contacto de confianza, quiero acceder a un panel de control cuando recibo una alerta para visualizar la ubicación y estado del usuario en tiempo real.  | **Escenario 1: Acceso al panel** <br> _Dado_ que el contacto recibe un aviso de emergencia <br> _Cuando_ abre el enlace en su navegador <br> _Entonces_ el sistema despliega un mapa dinámico con la ubicación del usuario y botones de llamada rápida <br> **Escenario 2: Sesión caducada** <br> _Dado_ que el incidente fue resuelto hace más de 24 horas <br> _Cuando_ el contacto intenta acceder al panel <br> _Entonces_ el sistema deniega el acceso por motivos de privacidad <br>| EP7 |

## 3.2.Impact Mapping
![Impact Mapping].(ImpactMapping.png)

## 3.3.Product Backlog

| Orden | User Story ID | Título | Descripción | Story Points |
|------|---------------|-------------|--------|--------------|
| 1 | HU13 | Descarga de la aplicación | Como visitante, quiero acceder a enlaces de descarga para instalar la aplicación en mi dispositivo. | 1 |
| 2 | HU14 | Visualización de información de la plataforma | Como visitante, quiero ver información clara sobre InstAlert para entender sus beneficios y funcionamiento. | 1 |
| 3 | HU15 | Registro desde la landing page | Como visitante, quiero registrarme directamente desde la landing page para comenzar a usar la aplicación rápidamente. | 3 |
| 4 | HU16 | Visualización de testimonios o casos de uso | Como visitante, quiero ver experiencias de otros usuarios para confiar en la efectividad de la plataforma. | 1 |
| 5 | HU17 | Suscripción a notificaciones o novedades | Como visitante, quiero suscribirme para recibir noticias o actualizaciones sobre la plataforma. | 2 |
| 6 | HU1 | Registro de usuario | Como cliente o comerciante quiero registrar mi mis datos para poder ingresar a la aplicación y recibir notificación. | 5 |
| 7 | HU2 | Inicio de sesión | Como cliente o comerciante, quiero iniciar sesión en la aplicación con mis credenciales para acceder a mis funciones, recibir notificaciones y gestionar mi información de forma segura. | 3 |
| 8 | HU3 | Configuración de perfil | Como cliente o comerciante, quiero configurar y actualizar mi perfil para mantener mis datos personales correctos y personalizar mi experiencia en la aplicación. | 3 |
| 9 | HU4 | Envío de alerta de emergencia | Como cliente o comerciante, quiero enviar una alerta de emergencia para notificar rápidamente a otros usuarios y autoridades sobre una situación de riesgo. | 8 |
| 10 | HU5 | Geolocalización automática en alertas | Como cliente o comerciante, quiero que la aplicación obtenga automáticamente mi ubicación al enviar una alerta para proporcionar información precisa del incidente. | 5 |
| 11 | HU6 | Recepción de alertas cercanas | Como cliente o comerciante, quiero recibir alertas de emergencia cercanas para estar informado y tomar precauciones ante posibles riesgos en mi entorno. | 5 |
| 12 | HU7 | Cancelación de alerta | Como cliente o comerciante, quiero cancelar una alerta enviada para evitar confusiones en caso de haberla activado por error. | 2 |
| 13 | HU8 | Historial de alertas | Como cliente o comerciante, quiero visualizar el historial de alertas para consultar eventos pasados y llevar un seguimiento de las situaciones reportadas. | 3 |
| 14 | HU9 | Creación de reportes de incidentes | Como cliente o comerciante, quiero crear reportes de incidentes para informar a la comunidad sobre situaciones relevantes que no requieren una alerta de emergencia. | 5 |
| 15 | HU10 | Adjuntar evidencia a reportes | Como cliente o comerciante, quiero adjuntar evidencia (imágenes o videos) a mis reportes para brindar mayor contexto y credibilidad al incidente reportado. | 5 |
| 16 | HU11 | Visualización de reportes en el mapa | Como cliente o comerciante, quiero visualizar los reportes de incidentes en un mapa para identificar rápidamente las zonas con mayor ocurrencia y tomar precauciones. | 5 |
| 17 | HU12 | Filtro de reportes | Como cliente o comerciante, quiero filtrar los reportes de incidentes para encontrar información relevante según mis necesidades (tipo de incidente, ubicación, fecha, etc.). | 3 |
| 18 | HU18 | Visualizar mapa de zonas de riesgo | Como usuario, quiero ver un mapa con zonas de riesgo, para identificar áreas peligrosas cercanas. | 5 |
| 19 | HU19 | Filtrar zonas por nivel de riesgo | Como usuario, quiero filtrar zonas según nivel de peligro, para analizar mejor la información. | 3 |
| 20 | HU20 | Consultar detalles de una zona de riesgo | Como usuario, quiero ver detalles de una zona específica, para entender el tipo de incidentes ocurridos. | 3 |
| 21 | HU21 | Búsqueda de direcciones específicas | Como usuario, quiero buscar una dirección o lugar en el mapa para conocer el nivel de riesgo de un destino antes de dirigirme allí. | 5 |
| 22 | HU22 | Reporte de zonas con poca iluminación | Como usuario, quiero marcar áreas con deficiencia de alumbrado público en el mapa para advertir a otros sobre condiciones que facilitan la delincuencia. | 3 |
| 23 | HU23 | Recibir alertas de emergencia cercanas | Como usuario, quiero recibir alertas cercanas, para estar informado de situaciones de peligro. | 5 |
| 24 | HU24 | Configurar preferencias de notificación | Como usuario, quiero configurar qué tipo de alertas recibir, para evitar información innecesaria. | 3 |
| 25 | HU25 | Recibir notificaciones de actividad comunitaria | Como usuario, quiero recibir notificaciones sobre reportes de la comunidad, para mantenerme informado. | 3 |
| 26 | HU26 | Enviar alerta a contactos de emergencia | Como usuario, quiero enviar alertas a mis contactos, para pedir ayuda inmediata. | 5 |
| 27 | HU28 | Solicitar apoyo a la comunidad cercana | Como usuario, quiero solicitar ayuda a usuarios cercanos, para recibir asistencia rápida. | 5 |
| 28 | HU29 | Como contacto de confianza, quiero aceptar una invitación de vinculación para confirmar que estoy dispuesto a recibir alertas del usuario. | Como usuario, quiero solicitar ayuda a usuarios cercanos, para recibir asistencia rápida. | 3 |
| 29 | HU30 | Panel de monitoreo para contactos | Como contacto de confianza, quiero acceder a un panel de control cuando recibo una alerta para visualizar la ubicación y estado del usuario en tiempo real. | 8 |

