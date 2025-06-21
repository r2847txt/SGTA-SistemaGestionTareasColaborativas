# SGTA - Sistema de Gestion de Tareas Colaborativas
Sistema web para la gestión de tareas, donde multiples usuarios puedan colaborar en proyectos, asignar tareas, establecer fechas y seguir el progreso.

## Funcionalidades clave
- Autenticación y autorización de usuarios:
  - Registro e inicio de sesión de usuarios.
  - Roles de usuarios (ej. administrador de proyecto, miembro del equipo).
  - Protección de rutas y datos basados en roles
- Gestión de proyectos:
  - Creación, edición y eleminación de proyectos.
  - Asignación de miembros a un proyecto.
  - Visualización de proyectos a los que el usuario pertenece.
- Gestión de tareas:
  - Creación, edición y eliminación de tareas dentro de un proyecto.
  - Asignación de tareas a usuarios específicos.
  - Establecimiento de fechas límite y prioridades para las tareas.
  - Cambio de estado de las tareas (ej. pendiente, en progreso, completada).
- Colaboración y notificaciones:
  - Comentarios en las tareas.
  - Posiblemente notificaciones básicas (ej. cuando se te asigna una tarea).
- Interfaz de usuario:
  - Panel de control intuitivo para cada usuario.
  - Vistas claras para proyectos y tareas.
  - Formularios para la creación y edición.

## Tecnologias utilizadas
- Backend (API RESTful):
  - Lenguaje: JaaScript / TypeScript.
  - Framework: NestJS
  - Base de datos: MySQL
- Frontend (Aplicación web):
  - Framework: React.
  - Manejo de estado: Context API, Redux o Zustand.
  - Routing: React Router DOM.
  - Estilos: CSS Modules, Styled Components oo un framework como Material-UI o Ant Design.
 
## Despliegue
Se utilizara heroku para backend, Netlify/Vercel para frontend).
