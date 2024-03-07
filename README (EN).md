# Texhnolyze
Texhnolyze is an inventory management, deployment, and fault handling system specifically designed for telecommunications companies. This project is developed in Spring and Java, offering a robust and scalable solution for efficient management of telecommunication sites and equipment, as well as for coordinating deployment and maintenance tasks.

**Para hablantes de español**: Este archivo README está en inglés. Si deseas leerlo en español, [haz clic aquí para continuar](README.md).

## Main Features
### Inventory Management:
Texhnolyze allows for the creation, editing, viewing, and deletion of telecommunications sites, as well as the management of equipment associated with each site. This includes the ability to add, edit, and remove a list of specific equipment according to the nature of the site (mobile or fixed technology).

### Task Management:
The system includes a task or deployment/maintenance ticket management module. Tickets are initiated by operator analysts, managed by field supervisors, and serviced by technicians. Texhnolyze offers functionalities to monitor the status of tickets, including dashboards with quantitative counters and task service statistics.

## User Roles
### Superadmin:
Genesis user with the ability to create any type of user, including administrators.

### Administrator:
System administrator with the ability to edit site fields, create equipment types, and manage equipment fields.

### Deployment or Planning Analyst:
Operator users responsible for creating and monitoring field service tickets.

### Operation and Maintenance (O&M) Analyst:
Operator users responsible for following up on incident or maintenance tickets.

### Field Supervisor:
External company users responsible for receiving deployment/maintenance tickets and assigning tasks to technicians.

### Technician:
External company users responsible for servicing deployment/maintenance tickets.

## Installation
- Clone this repository: git clone https://github.com/your_username/texhnolyze.git
- Import the project into your preferred IDE.
- Configure the database properties in application.properties.
- Run the application.
  
## Contribution
Contributions are welcome! If you wish to contribute to Texhnolyze, please follow these steps:

- Fork the repository.
- Create a new branch (git checkout -b feature/new-feature).
- Make your changes and commit (git commit -am 'Add new feature').
- Push your changes (git push origin feature/new-feature).
- Open a Pull Request.

## Notices
- The interface design of the roles is based on and belongs to https://themeselection.com

  Check out their prices at the following link: https://themeselection.com/item/sneat-dashboard-pro-bootstrap/

- If you wish to be granted a user to test the project, you can request it at the email: jmorillosp@pucp.edu.pe

  Or you can visit my website and contact me at: [My Personal Portfolio - Jose Morillos](https://mptechprojects.com/)
