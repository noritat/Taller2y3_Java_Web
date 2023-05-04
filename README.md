# Proyecto de conexión a base de datos MySQL con Java

Este proyecto consiste en una aplicación de Java que realiza una conexión a una base de datos MySQL y muestra los resultados en una interfaz de usuario desarrollada con Bootstrap.

# Requisitos

Para ejecutar este proyecto se necesitan los siguientes requisitos:

- Java 8 o superior
- Maven 2.9.0 o superior
- Una base de datos MySQL
- Widfly 27.0.1
- IntelliJ IDEA

# Configuración de la base de datos

Antes de ejecutar la aplicación, es necesario configurar la conexión a la base de datos en la carpeta Util dentro de esta en el archivo DbConnection debe tener el siguiente contenido:

-  private static final String URL= "jdbcmysql://localhost:3306/my_app serverTimezone=America/Bogota";"
- private static final String USER ="My_app";
- private static final String PASS="";

# Autor

Este proyecto fue creado por Angely Estrada.
Derechos reservados a Servicio Nacional de Aprendizaje (SENA).


