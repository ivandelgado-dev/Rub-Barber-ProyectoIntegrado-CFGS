# Rubí Barber 💈

Aplicación web para la gestión de peluquerías, desarrollada como Proyecto Integrado DAM. La aplicación permite a clientes, peluqueros y administradores interactuar de forma segura mediante autenticación por roles, reserva de citas, envío de correos electrónicos y facturación automática.

Funcionalidades:
- Control de acceso por roles (RBAC): usuarios con roles CLIENTE, PELUQUERO o ADMIN acceden solo a las funcionalidades correspondientes.
- Gestión de citas: los clientes pueden reservar, modificar o cancelar citas; los peluqueros gestionan su agenda; los administradores supervisan toda la actividad.
 - Envío de correos automatizados: recordatorios de citas, confirmación de cancelaciones y recuperación de contraseñas mediante JavaMailSender.
 - Facturación automática: generación y envío de facturas en PDF tras la finalización de cada cita.
 - Mapa interactivo de peluquerías: visualización de ubicaciones con React Leaflet.
 - Interfaz moderna: frontend desarrollado con React, Material UI y animaciones con Framer Motion.

Tecnologías:
 - Frontend: React, JSX, CSS, Material UI, React Router DOM, Axios, React Leaflet, Framer Motion.
 - Backend: Spring Boot, Spring Security, JWT, BCryptPasswordEncoder, JavaMailSender, JPA/Hibernate.
 - Base de datos: H2/SQL (según configuración).
 - Otros: iText (generación de PDFs), tareas programadas con @Scheduled.

Estructura del proyecto:
  /frontend → Código React, componentes, páginas, estilos y contextos.
  /backend → Código Spring Boot, controladores, servicios, repositorios, seguridad.

Instalación y ejecución:
 - Backend: configura el archivo application.properties con tu usuario y contraseña de correo, y la base de datos. Ejecuta el proyecto con Spring Boot (RubiBarberApplication.java).
 - Frontend: instala dependencias con npm install y ejecuta la app con npm start.

Uso:
Regístrate como cliente, peluquero o administrador. Explora la aplicación según tu rol: reservas, gestión de citas, facturas, etc. Recibe correos automáticos y visualiza facturas en PDF generadas tras cada cita.

Documentación:
La documentación completa del proyecto está disponible en el archivo .pdf, incluyendo diseño del sistema RBAC, flujo de datos y autenticación JWT, envío de correos electrónicos, generación automática de facturas y estructura del frontend y backend.

Autor:
Iván Delgado – Desarrollo completo del proyecto, frontend y backend.
