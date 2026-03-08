#Foro Hub - API REST
API para la gestión de tópicos de un foro, desarrollada como parte del Challenge de Alura Latam. El sistema centraliza la administración de discusiones mediante una arquitectura profesional y segura.

Tecnologías

Java 17

Spring Boot 3

Spring Security 6

PostgreSQL

Flyway

JSON Web Token (JWT)

Configuración
Crear base de datos forohub en PostgreSQL.

Configurar credenciales en src/main/resources/application.properties:

spring.datasource.url: URL de la base de datos.

spring.datasource.username: Usuario de PostgreSQL.

spring.datasource.password: Contraseña.

api.security.secret: Clave para firma de tokens.

Seguridad
La API utiliza autenticación stateless con JWT. Todas las rutas requieren el token en el encabezado Authorization: Bearer <token>, excepto el endpoint de /login.

Endpoints
POST /login: Autenticación de usuario y generación de token.

POST /topicos: Registro de nuevos temas.

GET /topicos: Listado de temas con paginación.

PUT /topicos: Actualización de título o mensaje de un tópico existente.

DELETE /topicos/{id}: Eliminación física de un registro mediante su identificador.

Validación
Integridad de Datos: Se utiliza @Transactional para asegurar que las operaciones de escritura (POST, PUT, DELETE) sean atómicas.

Manejo de Errores: Implementación de @RestControllerAdvice para capturar excepciones y retornar códigos de estado estandarizados (200, 204, 400, 403, 404).

Validaciones: Uso de Bean Validation para asegurar que los campos obligatorios no lleguen nulos o vacíos al repositorio.

Autor: Francisco Olguín 
