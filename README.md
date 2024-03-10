# Patrones-y-metodologias

---
Como usuario de RecycloSmart quiero cargar una imagen de mi factura de compra para que la aplicacion pueda procesar la informacion de la factura

Criterios de Aceptación:

- La aplicación debe permitir cargar una imágen desde los archivos de mi dispositivo
- Debe ser compatible con dos formatos de imagen comunes, JPEG y PNG
- La aplicación debe proporcionar retroalimentación inmediata al usuario después de cargar la imagen, confirmando que se ha recibido correctamente.
- La aplicación debe permitir al usuario revisar la imagen cargada antes de procesarla, para asegurarse de que sea legible y completa.
- La aplicación debe mostrar un mensaje de error claro si la imagen cargada no cumple con los requisitos mínimos de calidad o resolución.

---
Como usuario de RecycloSmart quiero poder escanear mis facturas de compra para identificar automáticamente los productos adquiridos.

Criterios de Aceptación:

- La aplicación ofrece una función de escaneo de facturas en la pantalla principal.
- Los usuarios pueden acceder a los archivos de su dispositivo para escanear la factura.
- Después del escaneo, la aplicación extrae la información relevante de la factura, como los productos.
- La información extraída se muestra de forma clara y legible para el usuario.
- Los productos identificados se almacenan en la base de datos de la aplicación para su posterior procesamiento.

---
Como usuario de RecycloSmart quiero que los productos identificados en mi factura se clasifiquen por categorías (reciclable, no reciclable, orgánico) para poder tomar decisiones informadas sobre cómo desechar adecuadamente cada producto.

Criterios de Aceptación:

- La aplicación clasifica automáticamente los productos identificados en la factura en una de las tres categorías: reciclable, no reciclable u orgánico.
- La clasificación se basa en la naturaleza y composición de cada producto.
- Los productos clasificados se muestran claramente en la pantalla de visualización de la factura.
- Los usuarios pueden ver fácilmente la categoría asignada a cada producto.
- Se proporciona una explicación breve sobre los criterios utilizados para clasificar cada producto.

---
Como usuario de RecycloSmart quiero ver un historial que refleje la informacion de mis facturas para tener un historias de mi actividad en la aplicacion

Criterios de Aceptacion:

- La aplicación debe proporcionar una sección específica de historial que muestre la información de las facturas cargadas por el usuario.
- El usuario debe poder acceder fácilmente al historial desde la interfaz principal de la aplicación.
- En el historial, se deben mostrar detalles de cada factura cargada, como la fecha de carga, el total de la factura y una lista de los productos comprados.
- La aplicación debe permitir al usuario filtrar y buscar facturas en el historial por fecha, total de la factura u otros criterios relevantes.
- El historial debe presentar la información de manera clara y ordenada, utilizando un diseño fácil de leer y navegación intuitiva.

---
Como usuario de RecycloSmart quiero recibir recomendaciones de reciclaje específicas para cada tipo de producto identificado en mi factura para saber cómo desechar adecuadamente cada producto y contribuir al reciclaje.

Criterios de Aceptación:

- Después de clasificar los productos por categorías, la aplicación muestra recomendaciones de reciclaje específicas para cada tipo de producto.
- Las recomendaciones incluyen información detallada sobre cómo desechar adecuadamente cada tipo de producto.
- Se proporcionan instrucciones claras sobre cómo separar y desechar los productos reciclables, no reciclables y orgánicos.
- Las recomendaciones de reciclaje se presentan de forma clara y fácil de entender para el usuario.
- Los usuarios pueden acceder a las recomendaciones de reciclaje en cualquier momento desde la pantalla de visualización de la factura.

---
Como usuario de RecycloSmart quiero ver los puntos de reciclaje cercanos a mi ubicacion para poder desechar adecuadamente los materiales reciclables y contribuir al cuidado del medio ambiente.

Criterios de Aceptación:

- La aplicación muestra un mapa interactivo con los puntos de reciclaje cercanos a la ubicación del usuario.
- Los puntos de reciclaje se representan claramente en el mapa con marcadores distintivos.
- Al hacer clic en un marcador, se muestra información adicional sobre ese punto de reciclaje, como los materiales aceptados y los horarios de apertura.
- Los usuarios pueden filtrar los puntos de reciclaje por tipo de material para encontrar los más adecuados para sus necesidades.
- La aplicación utiliza la ubicación actual del usuario para proporcionar resultados precisos y actualizados sobre los puntos de reciclaje cercanos.

---
Como usuario de RecycloSmart quiero poder crear una publicación en el foro para compartir mis experiencias, consejos o preguntas sobre reciclaje y sostenibilidad con otros usuarios.

Criterios de Aceptación:

- La aplicación proporciona una opción para crear una nueva publicación en el foro desde la interfaz de usuario.
- Los usuarios pueden seleccionar una categoría o etiqueta relevante para su publicación, como "Consejos de reciclaje" o "Preguntas sobre compostaje".
- Se proporciona un editor de texto enriquecido para que los usuarios puedan formatear su publicación y agregar imágenes si es necesario.
- Los usuarios pueden previsualizar su publicación antes de enviarla para asegurarse de que se vea como desean.
- Después de enviar la publicación, se muestra un mensaje de confirmación y se redirige al usuario a la página principal del foro donde pueden ver su publicación.

---
Como usuario de RecycloSmart quiero poder registrar mis actividades de reciclaje manualmente en la aplicación para incluir materiales reciclados fuera de las compras habituales o cuando el escaneo de facturas no sea posible.

Criterios de Aceptación:

- La aplicación ofrece una opción para agregar manualmente actividades de reciclaje desde la interfaz de usuario.
- Los usuarios pueden ingresar detalles como el tipo de material reciclado (papel, plástico, vidrio, etc.) y la cantidad.
- Se permite a los usuarios agregar notas opcionales para proporcionar detalles adicionales sobre la actividad de reciclaje.
- Las actividades de reciclaje manualmente registradas se agregan al progreso de reciclaje del usuario y se reflejan en las estadísticas.
- Los usuarios pueden editar o eliminar actividades de reciclaje registradas manualmente en cualquier momento si es necesario.

---
Como usuario de RecycloSmart quiero poder comentar en las publicaciones del foro de otros usuarios para compartir mis opiniones, sugerencias o responder preguntas de otros usuarios.

Criterios de Aceptación:

- La aplicación muestra una opción para comentar en las publicaciones del foro cuando un usuario está navegando por ellas.
- Los usuarios pueden escribir un comentario en el campo de entrada proporcionado y enviarlo para publicarlo.
- Los comentarios se muestran debajo de la publicación original en orden cronológico, con los comentarios más recientes en la parte superior.
- Se permite a los usuarios editar o eliminar sus propios comentarios si lo desean.
- Los usuarios pueden recibir notificaciones cuando alguien comenta en una de sus publicaciones o responde a uno de sus comentarios.

---
Como usuario de RecycloSmart quiero poder personalizar mis preferencias de reciclaje para recibir recomendaciones y consejos que se ajusten a mis necesidades y valores específicos.

Criterios de Aceptación:

- La aplicación permite a los usuarios establecer preferencias específicas de reciclaje, como el enfoque en la reducción de plásticos o la promoción del reciclaje de papel.
- Los usuarios pueden ajustar sus preferencias en cualquier momento desde la configuración de la aplicación.
- Las preferencias de reciclaje personalizadas se utilizan para filtrar los consejos y recomendaciones presentados a los usuarios.
- Se proporciona una opción para restablecer las preferencias de reciclaje a los valores predeterminados en caso de que el usuario desee cambiarlas.
- Los usuarios reciben confirmación de que sus preferencias de reciclaje se han guardado correctamente después de realizar cambios.

---
Yo como usuario de RecycloSmart quiero que las recomendaciones de reciclaje se actualicen automaticamente si hay un cambio en la clasificacion de un producto para siempre tener informacion precisa sobre como reciclar adecuadamente mis productos

Criterios de Aceptacion:

- La actualización de las recomendaciones de reciclaje debe ser rápida y precisa, reflejando cualquier cambio en la clasificación del producto de manera inmediata y sin demoras perceptibles para el usuario.
- La aplicación debe proporcionar una notificación o mensaje claro al usuario para informarle sobre la actualización automática de las recomendaciones de reciclaje después de que se realice un cambio en la clasificación del producto. Esto asegurará que el usuario esté al tanto de los cambios y pueda confiar en la precisión de la información proporcionada.
- La aplicación debe detectar automáticamente cualquier cambio en la clasificación de un producto realizada por el usuario.
- Una vez que se detecta un cambio en la clasificación del producto, la aplicación debe consultar una base de datos actualizada para obtener las recomendaciones de reciclaje más recientes para ese tipo de producto.
- Las recomendaciones de reciclaje actualizadas deben mostrarse inmediatamente al usuario después de que se realice el cambio en la clasificación del producto, sin necesidad de que el usuario realice ninguna acción adicional.

---
Como usuario nuevo de RecycloSmart quiero poder registrarme en la aplicación para acceder a todas las funcionalidades disponibles.

Criterios de Aceptación:

- La aplicación ofrece un formulario de registro accesible desde la pantalla de inicio.
- Los usuarios deben proporcionar un nombre de usuario, dirección de correo electrónico y contraseña para registrarse.
- Después del registro, la aplicación envía un correo electrónico de verificación al usuario.
- Los usuarios deben confirmar su dirección de correo electrónico haciendo clic en el enlace de verificación.
- Una vez verificado, el usuario es redirigido a la pantalla de inicio de sesión para iniciar sesión por primera vez.

---
Como usuario registrado de RecycloSmart quiero poder iniciar sesión en la aplicación para acceder a mi perfil y utilizar todas las funciones de la aplicación.

Criterios de Aceptación:

- La aplicación proporciona campos de entrada para nombre de usuario y contraseña en la pantalla de inicio de sesión.
- Los usuarios pueden iniciar sesión utilizando su nombre de usuario y contraseña registrados.
- Se valida la autenticación del usuario, permitiendo el acceso a la aplicación si las credenciales son correctas.
- Se muestra un mensaje de error si las credenciales ingresadas son incorrectas.
- Después del inicio de sesión exitoso, el usuario es dirigido a la pantalla principal de la aplicación.

---
Como usuario de RecycloSmart quiero poder reportar problemas técnicos o errores en la aplicación para contribuir a la mejora continua del rendimiento y la estabilidad de la aplicación.

Criterios de Aceptación:

- La aplicación proporciona un formulario de contacto o sección dedicada para reportar problemas.
- Los usuarios pueden describir el problema en detalle, incluyendo cualquier mensaje de error o comportamiento inesperado.
- Se solicita a los usuarios que proporcionen información adicional, como el dispositivo y la versión del sistema operativo que están utilizando.
- Los usuarios reciben una confirmación inmediata de que su informe ha sido recibido y está siendo revisado por el equipo de desarrollo.
- Se realiza un seguimiento de cada informe de problema y se proporciona una actualización o solución una vez que se resuelve.

---
Como usuario administrador, deseo tener la capacidad de borrar otros usuarios del sistema para eliminar perfiles obsoletos y mantener una base de datos actualizada

Criterios de Aceptación:

- La aplicación debe proporcionar una interfaz específica para administradores que les permita gestionar los usuarios del sistema.
- El administrador debe tener la capacidad de seleccionar y borrar usuarios del sistema de manera individual.
- Antes de proceder con el borrado de un usuario, la aplicación debe solicitar al administrador una confirmación para evitar eliminaciones accidentales.
- Cada vez que se elimina un usuario, la aplicación debe mantener un registro de esta acción en un registro de actividad o historial de auditoría para fines de seguimiento y seguridad.
- Después de borrar un usuario, la aplicación debe enviar una notificación al usuario afectado, informándole sobre la eliminación de su cuenta y proporcionando detalles relevantes sobre cómo proceder en caso de error o inconveniente.

---
Como usuario administrador, deseo tener la capacidad de controlar los permisos de otros usuarios y definir su jerarquia en el sistema para gestionar eficazmente el acceso a las funcionalidades y datos

Criterios de Aceptacion:

- La aplicación debe proporcionar una interfaz específica para administradores que les permita controlar los permisos de otros usuarios y definir su jerarquía en el sistema.
- El administrador debe tener la capacidad de definir los permisos específicos de cada usuario, incluyendo qué funcionalidades y datos pueden acceder.
- El administrador debe poder asignar una jerarquía específica a cada usuario, determinando su nivel de autoridad y acceso dentro del sistema.
- La interfaz de administración debe permitir al administrador ver los permisos actuales de cada usuario de forma clara y detallada.
- Cada vez que se realice un cambio en los permisos de un usuario o en su jerarquía dentro del sistema, la aplicación debe mantener un registro de esta acción en un registro de actividad o historial de auditoría para fines de seguimiento y seguridad.
