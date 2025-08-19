
````markdown
# ForoHub - API REST

API REST construida con **Java + Spring Boot** para la gestión de un foro.  
Permite registrar usuarios, autenticar con **JWT** y administrar **tópicos** (crear, listar, ver, actualizar y eliminar).

## Tecnologías
- Java 17+
- Spring Boot
- Spring Security + JWT
- Spring Data JPA (MySQL)
- Maven

## Cómo ejecutar
1. Configurar la base de datos en `src/main/resources/application.properties`.


## Endpoints principales

* `POST /login` → Autenticación con usuario y contraseña (devuelve token JWT).
* `POST /topicos` → Crear un nuevo tópico.
* `GET /topicos` → Listar tópicos.
* `GET /topicos/{id}` → Ver detalle de un tópico.
* `PUT /topicos/{id}` → Actualizar un tópico.
* `DELETE /topicos/{id}` → Eliminar un tópico.
