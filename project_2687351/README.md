###Proyecto de conexión a base de datos MySQL con Java

Este proyecto consiste en una aplicación de Java que realiza una conexión a una base de datos MySQL y muestra los resultados en una interfaz de usuario desarrollada con Bootstrap.

###Requisitos

Para ejecutar este proyecto se necesitan los siguientes requisitos:

- Java 8 o superior
- Maven 2.9.0 o superior
- Una base de datos MySQL

###Configuración de la base de datos

Antes de ejecutar la aplicación, es necesario configurar la conexión a la base de datos en el archivo application.properties. Este archivo se encuentra en la ruta src/main/resources y debe tener el siguiente contenido:

-  private static final String URL= "jdbcmysql://localhost:3306/my_app serverTimezone=America/Bogota";"
- private static final String USER ="my_app_user";
- private static final String PASS="my_app_password";

###Autor

Este proyecto fue creado por Angelly Estrada y es propiedad del SENA


