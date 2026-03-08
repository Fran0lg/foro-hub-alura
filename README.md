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

Gemini dijo
¡Claro que sí, Francisco! He transformado tu información en un archivo README.md profesional, con una estructura clara, badges (insignias) para las tecnologías y una organización visual que hará que tu portafolio destaque en GitHub.

Aquí tienes el código listo para copiar y pegar:

Markdown
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
🔐 Seguridad
La API utiliza un modelo de autenticación stateless con JWT.

Acceso: Todas las rutas (excepto /login) están protegidas.

Cabecera: Se requiere enviar el token en el encabezado:
Authorization: Bearer <tu_token_aqui>

Gemini dijo
¡Claro que sí, Francisco! He transformado tu información en un archivo README.md profesional, con una estructura clara, badges (insignias) para las tecnologías y una organización visual que hará que tu portafolio destaque en GitHub.

Aquí tienes el código listo para copiar y pegar:

Markdown
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
🔐 Seguridad
La API utiliza un modelo de autenticación stateless con JWT.

Acceso: Todas las rutas (excepto /login) están protegidas.

Cabecera: Se requiere enviar el token en el encabezado:
Authorization: Bearer <tu_token_aqui>

🚀 Endpoints Principales

Método,Endpoint,Descripción
POST,/login,Autenticación de usuario y generación de token.
POST,/topicos,Registro de nuevos temas de discusión.
GET,/topicos,Listado de temas con soporte de paginación.
PUT,/topicos,Actualización de título o mensaje de un tópico.
DELETE,/topicos/{id},Eliminación física de un registro por ID.









