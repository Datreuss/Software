# Software de Aduanas
Proyecto de software aduanero desarrollado para satisfacer la alta demanda de usuarios y optimizar el rendimiento del sistema durante los horarios de mayor concurrencia (horas punta).

# Versión 0.1.0
Fecha: 09/06/2026

Creación del sitio web de aduanas, ajustándose a las métricas iniciales entregadas y aplicando principios básicos de usabilidad basados en las Heurísticas de Nielsen. Para el diseño y la estructura, nuestro sitio web tomó como inspiración e integró buenas prácticas de dos plataformas referentes: Aduanas Chile y Airport Airlines.

CREATE: Lanzamiento inicial del sitio web de aduanas con la estructura base y la navegación principal operativa.

# Versión 0.1.1
Fecha: 15/06/2026

Modificaciones visuales y de accesibilidad en el software.
Explicación de la actualización: Según los principios de usabilidad de las Heurísticas de Nielsen, la paleta de colores juega un rol fundamental en la visualización, la jerarquía de la información y la experiencia general del usuario. Por ello, nos enfocamos en mejorar estos aspectos.

UPDATE: Cambios en la paleta de colores general para mejorar el contraste y la legibilidad.

UPDATE: Ajustes menores y refinamiento de la interfaz de usuario (UI).

UPDATE: Rediseño de botones y enlaces para que sean más notorios e intuitivos (mejora de llamados a la acción o Call to Actions).

UPDATE: Integración de un atajo rápido de Contacto/Ayuda. Este botón enlaza directamente con los canales de atención (Teléfono/WhatsApp de aduanas), ajustándose a la necesidad de comunicación inmediata del cliente. (Nota: Por el momento, esta funcionalidad no fue añadida en la versión para Android).

# Versión 0.2.0
Fecha: 20/06/2026

Modificación mayor del sistema (Major Update).
Esta versión incluye mejoras significativas basadas en retroalimentación técnica profesional. Solicitamos una auditoría externa a un Ingeniero en Informática, quien revisó nuestra plataforma contrastándola con nuestra matriz de requisitos (Excel) y las Heurísticas de Nielsen.

Feedback de la auditoría: "Dentro de esta aplicación pudimos notar la correcta generalización de un sistema de 'ayuda' o 'búsqueda' que apoya eficientemente la gestión de productos, junto con el fácil acceso para el ingreso y creación de cuentas de usuario. Sin embargo, se identificó que algunos botones y accesos directos presentan dificultades de entendimiento, lo cual requiere optimización en próximas actualizaciones."

En respuesta a esta evaluación, implementamos las siguientes mejoras de forma inmediata:

UPDATE: Ajuste en el color, tamaño y fuente tipográfica de los botones para maximizar su visibilidad y facilitar la interacción del usuario.

UPDATE: Implementación de retroalimentación del sistema: Se agregaron mensajes de error claros, pantallas de despedida y notificaciones de confirmación de acciones.

UPDATE: Rediseño del menú de navegación, haciéndolo más intuitivo y adaptable a la versión en desarrollo para dispositivos Android.

UPDATE: Nuevo ajuste en la paleta de colores de la interfaz, alineándose estrictamente a las métricas de accesibilidad recomendadas por la auditoría y los estándares de Nielsen.

UPDATE: Reestructuración profunda del sistema de Preguntas Frecuentes (FAQ). Evolucionamos de un centro de ayuda básico a un modelo híbrido: integramos un Asistente de Inteligencia Artificial para resolver consultas generales de forma rápida, y un canal de conexión directa con el equipo de Servicio al Cliente para requerimientos complejos.

UPDATE: Integración de la visualización y aceptación de "Términos y Condiciones" obligatorios durante la creación de cuentas o al iniciar un chat de soporte, mejorando el cumplimiento legal y la transparencia.

UPDATE: Localización y estandarización del lenguaje. Se modificaron las URLs y los textos del sistema para evitar anglicismos (ej. Login, Sign in, Register), reemplazándolos por términos en español claros: Ingreso al Sistema, Registrarse, Iniciar Sesión.

UPDATE: Implementación de validaciones de seguridad (sanitización de datos). Se añadieron restricciones para evitar el ingreso de caracteres especiales (!"#$%&/()=?¡) al momento de crear una cuenta o al utilizar la barra de búsqueda del sistema.

# Versión 0.3.0
Fecha: 23/06/2026

Última modificación y versión Pre-Release.
Con esta actualización cerramos definitivamente la fase de diseño y pruebas en entornos de desarrollo (testing). Tras una segunda revisión a cargo de otro especialista en informática, recopilamos recomendaciones finales para perfeccionar el proyecto.

Feedback de la auditoría final: El revisor destacó la solidez de la plataforma considerando que es un proyecto nuevo. Como mejora principal para la usabilidad ("Visibilidad del estado del sistema"), recomendó que siempre se haga evidente en qué vista se encuentra la persona, mostrando claramente indicadores como "Sesión iniciada como usuario" para evitar desorientación en la navegación.

Para cumplir con este estándar y dar los toques finales, integramos lo siguiente:

UPDATE: Implementación de la "Vista de Usuario", personalizando la experiencia y las opciones disponibles según la cuenta.

UPDATE: Refinamiento estético final de la interfaz gráfica general.

UPDATE: Integración de un Panel de Estado (Mini HUD) visible en la pantalla. Este indicador muestra claramente que el usuario tiene la sesión activa y ofrece la posibilidad de personalizar el perfil agregando una fotografía.

UPDATE: Diseño e implementación de los íconos oficiales del proyecto (tanto el favicon para los navegadores web como el ícono adaptable para futuras aplicaciones móviles), consolidando la identidad visual del software.
