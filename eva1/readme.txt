***************************************
Integrantes:
- Kaito Zaid Chota Shuña
- Josmel Montoya Paiva
- Guillermo Arturo Ugaz Montesinos
- Alexander jose illescas flores
- Cris Angelo Rivera Cardenas
***************************************


Software usado:
Java JDK 21 o 22
IntelliJ IDEA 2025.2.2
Apache Maven 3.9.6


Dependencias:
Spring Web
Rest Repositories
Spring Boot Dev Tools
Projectlombok
springdoc openapi


Instalación:
Para ejecutar primero necesitas instalar Java JDK (version 20 o superior), Apache Maven 3.9 y un Ide de preferencia, luego basta con descargar el proyecto y descomprimirlo.


Documentación de API disponible en:
http://localhost:8080/swagger-ui/index.html


Endpoints de la API:
Método	          URL	                 Descripción
POST	    /api/solicitudes	         Crear nueva solicitud
GET	        /api/solicitudes	 Listar todas las solicitudes
GET	        /api/solicitudes/{id}	 Buscar solicitud por ID
PUT	        /api/solicitudes/{id}	 Actualizar solicitud por ID
DELETE	    /api/solicitudes/{id}	 Eliminar solicitud por ID

POST	    /api/clientes	         Crear nuevo cliente
GET	        /api/clientes	         Lista todos los clientes
GET	        /api/clientes/{id}	 Buscar cliente por ID
PUT	        /api/clientes/{id}	 Actualizar cliente con ID
DELETE	    /api/clientes/{id}	         Eliminar cliente con ID

POST	    /api/tecnicos	         Crear nuevo cliente
GET	        /api/tecnicos	         Lista todos los clientes
GET	        /api/tecnicos/{id}	 Buscar cliente por ID
PUT	        /api/tecnicos/{id}	 Actualizar cliente con ID
DELETE	    /api/tecnicos/{id}	         Eliminar cliente con ID
