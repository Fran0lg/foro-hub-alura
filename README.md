# Foro Hub - API REST 🌐

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

Esta API REST es una solución robusta para la gestión de tópicos en un foro, desarrollada como parte del **Challenge de Alura Latam**. El sistema centraliza la administración de discusiones mediante una arquitectura profesional, escalable y segura.

---

## 🛠️ Tecnologías Utilizadas

* **Java 17**: Lenguaje principal.
* **Spring Boot 3**: Framework para el desarrollo ágil de la aplicación.
* **Spring Security 6**: Implementación de seguridad y control de acceso.
* **PostgreSQL**: Base de datos relacional para persistencia de datos.
* **Flyway**: Control de versiones para el esquema de la base de datos.
* **JSON Web Token (JWT)**: Autenticación stateless y segura.

---

## ⚙️ Configuración del Proyecto

Sigue estos pasos para ejecutar el proyecto localmente:

1.  **Base de Datos**: Crea una base de datos llamada `forohub` en tu instancia de PostgreSQL.
2.  **Propiedades**: Configura tus credenciales en el archivo `src/main/resources/application.properties`:

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/forohub
spring.datasource.username=tu_usuario
spring.datasource.password=tu_contrasena
api.security.secret=${JWT_SECRET:tu_clave_secreta}
