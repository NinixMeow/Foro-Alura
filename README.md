# Foro-Alura
Esta es mi solución al último reto de la formación de Backend con Java y Spring del programa ONE. El proyecto consiste en una réplica del backend del foro de la plataforma Alura Latam, donde todos los estudiantes pueden hacer preguntas y responderlas, colaborando e interactuando con otros estudiantes, así como con profesores y moderadores.

Requerimientos

Los requerimientos para la API REST:

    Crear nueva publicación
    Mostrar todas las publicaciones creadas
    Mostrar una publicación específica
    Actualizar una publicación
    Eliminar una publicación

Requerimientos adicionales:

    Registro, ingreso y salida de usuarios
    Contraseñas encriptadas con BCrypt Password Encoder
    Cambio de contraseña y asignar rol a usuario
    Autenticación usando JSON Web Tokens (JWT)
    Autorización basada en roles y a nivel de métodos
    Refresh Tokens
    Entidades adicionales: Rol, Refresh Tokens y Etiquetas (Categorías y Subcategorías)
    Operaciones CRUD en todas las entidades
    Escoger respuesta como solución
    Manejo de excepciones con mensajes personalizados

Tecnologías utilizadas:

    Eclipse
    H2
    MySQL
    Java 17
    Spring Security 6
    Token JWT

Endpoints

Autenticación

    Registro de usuario (Sign up)
    Ingreso de usuario (Login)
    Salida de usuario (Log out)
    Refresh Token
    Cambiar contraseña
    Asignar rol a usuario
    Entidad Usuario
    Entidad Refresh Token

Roles

    Crear rol
    Entidad Rol

Etiquetas

    Entidad Etiqueta
    Enum Nivel

Categorías

    Crear Categoría
    Listar Categorías
    Obtener Categoría
    Editar Categoría
    Eliminar Categoría

Subcategorías

    Crear Subcategoría
    Listar Subcategorías
    Listar Subcategorías por Categoría
    Obtener Subcategorías por Id
    Editar Subcategoría
    Eliminar Subcategoría

Cursos

    Crear curso
    Listar Cursos
    Listar Cursos por Categoría
    Listar Cursos por Subcategoría
    Obtener Curso por Id
    Editar Curso
    Eliminar Curso

Publicaciones

    Crear Publicación
    Listar Publicaciones
    Listar Publicaciones por Curso
    Obtener Publicación por Id
    Editar Publicación
    Eliminar Publicación
    Entidad Publicación
    Enum EstadoPublicacion

Respuestas

    Crear Respuesta
    Listar Respuestas por Publicación
    Editar Respuesta
    Escoger Respuesta como Solución
    Entidad Respuesta
