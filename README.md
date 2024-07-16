# Challenge Back-end ONE Foro_Hub G6 🌐

[![Alura Latam](https://img.shields.io/badge/Alura-Latam-blue?style=flat)](https://www.aluracursos.com/)
[![Static Badge](https://img.shields.io/badge/ONE-Oracle_Next_Education-orange?style=flat&logo=oracle&logoColor=orange)](https://www.oracle.com/co/education/oracle-next-education/) [![Static Badge](https://img.shields.io/badge/IDE-IntelliJ_IDEA-%23ff0534?style=flat&logo=IntelliJ%20IDEA&logoColor=%232196f3)](https://www.jetbrains.com/es-es/idea/) [![Static Badge](https://img.shields.io/badge/Language-Java-%23ff0000?style=flat)](#)
[![Static Badge](https://img.shields.io/badge/Java_Library-Gson_%2F_Json-blue?style=flat&logo=json)](https://mvnrepository.com/artifact/com.google.code.gson/gson)
[![Static Badge](https://img.shields.io/badge/API-Exchange_Rate_API-%23e90000?style=flat)](https://www.exchangerate-api.com/docs/java-currency-api)
[![Static Badge](https://img.shields.io/badge/license-MIT-blue)](#)

## 📋 Descripción del Proyecto 
ForoHub es un proyecto de la especialización **Back-End G6 de Alura - Oracle Next Education** que desarrolla un foro para que los participantes planteen preguntas sobre diversos tópicos. Utilizando una API REST construida con Spring, el proyecto permite gestionar tópicos mediante la creación, visualización, actualización y eliminación de entradas. Además, se implementa un sistema de autenticación y autorización para asegurar un acceso controlado, fomentando un entorno seguro que promueve la colaboración y el intercambio de conocimiento

## 🛠️ Tecnologías Utilizadas
- **JDK (Java Development Kit)**: Proporciona las herramientas necesarias para compilar y ejecutar aplicaciones Java, asegurando un entorno de desarrollo adecuado.

- **IntelliJ IDEA**: Entorno de desarrollo integrado (IDE) que facilita la programación en Java con características como autocompletado y depuración.

- **Spring Boot**: Framework que simplifica la creación de la API REST, proporcionando una estructura y configuración que aceleran el desarrollo.

- **Spring Security**: Implementa la seguridad en la aplicación, gestionando la autenticación y autorización de usuarios para proteger el acceso a datos y funcionalidades.

- **MySQL**: Sistema de gestión de bases de datos utilizado para almacenar la información del foro.

- **JWT (JSON Web Tokens)**: Utilizado para la autenticación de usuarios, permitiendo un manejo seguro de sesiones sin almacenar estado en el servidor.
  
- **JPA (Java Persistence API)**: Facilita la interacción con la base de datos, permitiendo operaciones de creación, lectura, actualización y eliminación (CRUD) de manera eficiente.
  
- **H2 Database**: Base de datos en memoria utilizada para desarrollo y pruebas, ofreciendo un entorno ligero y fácil de configurar.

- **Postman**: Herramienta para probar la API, permitiendo enviar solicitudes HTTP y verificar respuestas de manera eficiente.

- **Swagger**: Proporciona documentación interactiva de la API, facilitando la exploración y comprensión de las rutas y funcionalidades disponibles.

- **Git y GitHub**: Sistemas de control de versiones que permiten mantener el historial del proyecto y colaborar en equipo.

## 👩‍💻 Desarrollo del Proyecto
1. **Construcción de la Base de Datos**: Se integró y configuró una base de datos MySQL, creando la base de datos forohub_alura. Se utilizaron Flyway para gestionar las migraciones SQL y se incluyeron dependencias necesarias como Validation y MySQL Driver.

2. **Funcionalidades e Implementación de Endpoints**: Se desarrollaron múltiples endpoints para manejar la funcionalidad del foro
  - **Registro y autenticación de usuarios**: Se creó un endpoint POST /login para autenticar a los usuarios, recibiendo datos en formato JSON.
  - **Creación de tópicos**: Se implementó el endpoint POST /topicos para registrar nuevos tópicos, validando los datos de entrada.
  - **Listado de tópicos**: Se desarrolló el endpoint GET /topicos para listar todos los tópicos almacenados.
  - **Detalles de un tópico específico**: Se creó el endpoint GET /topicos/{id} para obtener información detallada de un tópico.
  - **Edición de tópicos**: Se implementó el endpoint PUT /topicos/{id} para actualizar tópicos existentes.
  - **Eliminación de tópicos**: Se desarrolló el endpoint DELETE /topicos/{id} para eliminar un tópico, tras verificar su existencia.
  
3. **Seguridad y Autenticación**: Se configuró la seguridad de la API utilizando Spring Security, definiendo rutas permitidas sin autenticación y rutas protegidas. Se implementó AuthenticationManager para manejar la autenticación en el código Java. Además, se añadió la biblioteca JWT para controlar el acceso a la API mediante tokens. Se creó un TokenService para generar y validar los tokens, y se configuró el controlador de autenticación para utilizar dichos tokens en las solicitudes.

5. **Pruebas de la API**: Se utilizaron herramientas como Postman o Insomnia para probar las funcionalidades de la API, realizando operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre usuarios y tópicos para asegurar que todo funcionaba correctamente.

6. **Documentación del Proyecto**: Se elaboró un archivo README que proporciona información sobre el propósito del proyecto, su configuración y los pasos necesarios para ejecutarlo. También se configuró Swagger para documentar automáticamente la API, facilitando el acceso a los endpoints y asegurando que la documentación esté siempre actualizada.

## 🚀 Cómo Ejecutar el Proyecto
Para ejecutar el proyecto, sigue estos pasos:
- **Clona o descarga desde GitHub**: Clona o descarga el repositorio en tu disco local <code>https://github.com/Latzmi-Sarmiento/ONE_ForoHub-G6.git</code>
- **Importa el proyecto**: Importa el proyecto en tu IDE (recomendado IntelliJ IDEA) y configura las dependencias.
- **Configurar**: Configura las dependencias y ajusta la configuración según sea necesario.
- **Ejecutar el Proyecto**: Usa tu IDE para compilar y ejecutar la clase <code>ChallengeForoHubApplication</code>.

## ✅ Insignia de Entregado para este Challenge
![Latzmi Badge-Spring](https://github.com/user-attachments/assets/bfd668cd-ac2b-484b-8725-18527ad1b85d)

## 💬 Datos de Contacto
Email:<code>latzmisarmiento@gmail.com</code>

Autor:<code>Latzmi Sarmiento Palomino</code>
