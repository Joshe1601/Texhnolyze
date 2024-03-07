# Texhnolyze
Texhnolyze es un sistema de gestión de inventario, despliegue y atención de averías diseñado específicamente para empresas de telecomunicaciones. Este proyecto está desarrollado en Spring y Java, ofreciendo una solución robusta y escalable para la gestión eficiente de los sitios y equipos de telecomunicaciones, así como para la coordinación de tareas de despliegue y mantenimiento.

**For English Speakers:** This readme is in Spanish. If you want to read it in English, [click here to continue]().


## Características principales

### Gestión de Inventario: 
Texhnolyze permite la creación, edición, visualización y eliminación de sitios de telecomunicaciones, así como la gestión de equipos asociados a cada sitio. Esto incluye la capacidad de agregar, editar y quitar una lista de equipos determinados según la naturaleza del sitio (tecnología móvil o fija).

### Gestión de Tareas:
El sistema incluye un módulo de gestión de tareas o tickets de despliegue/mantenimiento. Los tickets son iniciados por analistas de la operadora, gestionados por supervisores de campo y atendidos por técnicos. Texhnolyze ofrece funcionalidades para monitorear el estado de los tickets, incluyendo dashboards con contadores cuantitativos y estadísticas de atención de tareas.

## Roles de Usuario

### Superadmin: 
Usuario génesis con capacidad para crear cualquier tipo de usuario, incluyendo administradores.
### Administrador: 
Administrador del sistema con capacidad para editar campos de sitio, crear tipos de equipos y gestionar campos de equipos.
### Analista de Despliegue o Planificación:
Usuarios de la operadora encargados de crear y supervisar tickets de atención en campo.
### Analista de Operación y Mantenimiento (OyM): 
Usuarios de la operadora encargados de dar seguimiento a tickets de incidentes o mantenimiento.
### Supervisor de Campo: 
Usuarios de empresas externas encargados de recibir tickets de despliegue/mantenimiento y asignar tareas a técnicos.
### Técnico: 
Usuarios de empresas externas encargados de atender tickets de despliegue/mantenimiento.

## Instalación
- Clona este repositorio: git clone https://github.com/tu_usuario/texhnolyze.git
- Importa el proyecto en tu IDE preferido.
- Configura las propiedades de la base de datos en application.properties.
- Ejecuta la aplicación.

## Contribución
¡Las contribuciones son bienvenidas! Si deseas contribuir a Texhnolyze, por favor sigue estos pasos:

- Fork del repositorio.
- Crea una nueva rama (git checkout -b feature/nueva-funcionalidad).
- Realiza tus cambios y haz commit (git commit -am 'Agrega nueva funcionalidad').
- Sube tus cambios (git push origin feature/nueva-funcionalidad).
- Abre un Pull Request.

## Avisos
- El diseño de la interfaz de los roles está basado y le pertenece a https://themeselection.com
  
  Echa un vistazo a sus precios en el siguiente link: https://themeselection.com/item/sneat-dashboard-pro-bootstrap/
- Si deseas que se te otorgue un usuario para poder probar el proyecto, lo puedes solicitar al correo: jmorillosp@pucp.edu.pe

  O puedes visitar mi página web y contactarme en: [Mi portafolio personal - Jose Morillos](https://mptechprojects.com/)
