# 🎓 Plataforma de Aprendizaje Online

Plataforma de aprendizaje online desarrollada con **Java, Spring Boot, Angular, TypeScript y Microsoft SQL Server**. Su objetivo es ofrecer un entorno donde los profesores puedan gestionar cursos y los alumnos puedan inscribirse, acceder a las lecciones y realizar un seguimiento de su progreso.

## 🚀 Funcionalidades

- **Gestión de usuarios y roles:** diferenciación de permisos entre alumnos y profesores.
- **Gestión de cursos:** creación, edición y publicación de cursos.
- **Gestión de lecciones:** organización de las lecciones asociadas a cada curso.
- **Inscripción a cursos:** posibilidad de que los alumnos se inscriban en cursos disponibles.
- **Seguimiento del progreso:** registro de las lecciones completadas por los alumnos.
- **Gestión de contenidos:** administración de información de cursos, descripciones y logotipos.

## 👥 Roles de usuario

### 🧑‍🎓 Alumno
- Consultar los cursos publicados.
- Inscribirse en cursos disponibles.
- Acceder a las lecciones.
- Registrar y consultar su progreso de aprendizaje.

### 👨‍🏫 Profesor
- Crear y editar cursos.
- Organizar y gestionar las lecciones.
- Administrar la publicación de los contenidos.

## 🛠️ Tecnologías utilizadas

| Área                 | Tecnologías          |
|----------------------|----------------------|
| Backend              | Java, Spring Boot    |
| Frontend             | Angular, TypeScript  |
| Base de datos        | Microsoft SQL Server |
| Control de versiones | Git, GitHub          |

## 🗄️ Modelo de datos

La base de datos contempla seis tablas principales:

| Tabla         | Propósito                                                      |
|---------------|----------------------------------------------------------------|
| `rol`         | Definición de los roles de usuario.                            |
| `usuarios`    | Información de los usuarios y su rol.                          |
| `curso`       | Datos del curso, profesor responsable y estado de publicación. |
| `leccion`     | Contenido y orden de las lecciones de cada curso.              |
| `inscripcion` | Registro de alumnos inscritos y fecha de inscripción.          |
| `progreso`    | Seguimiento de las lecciones completadas por cada alumno.      |

## 🔐 Registro, autenticación y control de acceso

La plataforma permitirá el registro de nuevos alumnos mediante un formulario de registro. Durante el inicio de sesión, Spring Security gestionará la autenticación e identificará el rol asociado a cada usuario, diferenciando entre alumnos y profesores.

En función del rol identificado, la aplicación ofrecerá acceso a las funcionalidades correspondientes:

Alumno: podrá consultar cursos publicados, inscribirse, acceder a las lecciones y realizar un seguimiento de su progreso.

Profesor: podrá crear y editar cursos, gestionar sus lecciones y administrar la publicación de los contenidos.

La gestión de roles permitirá adaptar los permisos y las operaciones disponibles a cada tipo de usuario, manteniendo separadas las funcionalidades de aprendizaje y administración de cursos.

## 📸 Capturas de pantalla

*Se añadirán capturas de la interfaz para mostrar las principales funcionalidades de la plataforma.*

