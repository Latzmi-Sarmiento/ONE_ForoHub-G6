~~# Challenge Back-end ONE Foro_Hub G6 🌐
[![Alura Latam](https://img.shields.io/badge/Alura-Latam-blue?style=flat)](https://www.aluracursos.com/)
[![Static Badge](https://img.shields.io/badge/ONE-Oracle_Next_Education-orange?style=flat&logo=oracle&logoColor=orange)](https://www.oracle.com/co/education/oracle-next-education/) [![Static Badge](https://img.shields.io/badge/IDE-IntelliJ_IDEA-%23ff0534?style=flat&logo=IntelliJ%20IDEA&logoColor=%232196f3)](https://www.jetbrains.com/es-es/idea/) [![Static Badge](https://img.shields.io/badge/Language-Java-%23ff0000?style=flat)](#)
[![Static Badge](https://img.shields.io/badge/Java_Library-Gson_%2F_Json-blue?style=flat&logo=json)](https://mvnrepository.com/artifact/com.google.code.gson/gson)
[![Static Badge](https://img.shields.io/badge/API-Exchange_Rate_API-%23e90000?style=flat)](https://www.exchangerate-api.com/docs/java-currency-api)
[![Static Badge](https://img.shields.io/badge/license-MIT-blue)](#)

## 📋 Descripción del Proyecto 
ForoHub es un proyecto de la Especialización Back-End G6 de Alura - Oracle Next Education que desarrolla un foro para que los participantes planteen preguntas sobre diversos tópicos. Utilizando una API REST construida con Spring, el proyecto permite gestionar tópicos mediante la creación, visualización, actualización y eliminación de entradas. Además, se implementa un sistema de autenticación y autorización para asegurar un acceso controlado, fomentando un entorno seguro que promueve la colaboración y el intercambio de conocimiento

## 🛠️ Tecnologías Utilizadas
-**JDK (Java Development Kit)**: Proporciona las herramientas necesarias para compilar y ejecutar aplicaciones Java, asegurando un entorno de desarrollo adecuado.
-**IntelliJ IDEA**: Entorno de desarrollo integrado (IDE) que facilita la programación en Java con características como autocompletado y depuración.
-**Spring Boot**: Framework que simplifica la creación de la API REST, proporcionando una estructura y configuración que aceleran el desarrollo.
-**Spring Security**: Implementa la seguridad en la aplicación, gestionando la autenticación y autorización de usuarios para proteger el acceso a datos y funcionalidades.
-**JWT (JSON Web Tokens)**: Utilizado para la autenticación de usuarios, permitiendo un manejo seguro de sesiones sin almacenar estado en el servidor.
-**JPA (Java Persistence API)**: Facilita la interacción con la base de datos, permitiendo operaciones de creación, lectura, actualización y eliminación (CRUD) de manera eficiente.
-**H2 Database**: Base de datos en memoria utilizada para desarrollo y pruebas, ofreciendo un entorno ligero y fácil de configurar.
-**Postman**: Herramienta para probar la API, permitiendo enviar solicitudes HTTP y verificar respuestas de manera eficiente.
-**Swagger**: Proporciona documentación interactiva de la API, facilitando la exploración y comprensión de las rutas y funcionalidades disponibles.

## 👩‍💻 Desarrollo del Proyecto
1. **Conectar y Configurar la API**: Utilizar la API de Gutendex para obtener datos de libros. Para interactuar con la API se utilizan clases de Java para manejar solicitudes HTTP y procesar las respuestas.
- **Cliente para Solicitudes (HttpClient)**:Se utiliza la clase HttpClient de Java para realizar solicitudes HTTP a la API de Gutendex, facilitando la obtención de datos.
- **Solicitud (HttpRequest)**: La clase HttpRequest se utiliza para configurar y personalizar las solicitudes enviadas a la API de Gutendex, incluyendo parámetros y URL de consulta.
- **Respuesta (HttpResponse)**: La clase HttpResponse maneja las respuestas de la API, proporcionando acceso al código de estado, encabezados y cuerpo de la respuesta.
- **Conversión de Datos JSON**: Análisis y conversión de datos JSON obtenidos de la API a objetos Java.

2. **Implementar Funcionalidades**:
- Registro y autenticación de usuarios.
- Creación, edición y eliminación de tópicos.
- Respuesta a tópicos existentes.
- Listado de usuarios y tópicos.
- Autenticación mediante JWT.

3. **Interfaz de Usuario**: Crear un menú interactivo en consola que permita al usuario seleccionar opciones para buscar y consultar libros y autores.

4. **Documentación**: Documentar el proyecto en GitHub, incluyendo instrucciones de uso, dependencias y una descripción del funcionamiento en un README.

5. **Funcionalidades Extra**: Puedes añadir algunas funciones más al LiterAlura como la <code>generación de Estadísticas</code> (los libros más descargados o los autores más prolíficos), <code>búsqueda de Autor por nombre</code> y <code>listado de autores por diversos criterios</code>.

## 🚀 Cómo Ejecutar el Proyecto
Para ejecutar el proyecto, sigue estos pasos:

- **Clona o descarga desde GitHub**: Clona o descarga el repositorio en tu disco local <code>https://github.com/Latzmi-Sarmiento/ONE_LiterAlura-G6.git</code>
- **Importa el proyecto**: Importa el proyecto en tu IDE (recomendado IntelliJ IDEA) y configura las dependencias.
- **Configurar la API Key**: Inserte su clave de API en la configuración del proyecto.
- **Ejecutar el Proyecto**: Usa tu IDE para compilar y ejecutar la clase <code>LiteraturaApplication</code>.

## ✅ Insignia de Entregado para este Challenge


## 💬 Datos de Contacto
Email:<code>latzmisarmiento@gmail.com</code>

Autor:<code>Latzmi Sarmiento Palomino</code>
