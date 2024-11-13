Backend de Adoptme
Adoptme es un proyecto desarrollado como parte del curso de Backend en CoderHouse. Se trata de una API RESTful enfocada en la gestión de usuarios, sesiones y mascotas para facilitar el proceso de adopción de animales.

Índice
Descripción del Proyecto
Funciones Clave
Requisitos Previos
Instrucciones de Instalación
Tecnologías Usadas
Enlaces
Licencia
Descripción del Proyecto
El backend de Adoptme proporciona una solución integral para gestionar usuarios y mascotas, manejar sesiones autenticadas y procesar solicitudes de adopción. El proyecto sigue buenas prácticas de desarrollo para garantizar un código limpio, escalable y mantenible.

Funciones Clave
Administración de usuarios: Permite registrar nuevos usuarios, autenticarlos y gestionar sus datos.
Autenticación de sesiones: Implementa sesiones seguras para el manejo de la autenticación de usuarios.
Gestión de mascotas: Proporciona CRUD completo para registrar, modificar y listar mascotas en adopción.
Solicitudes de adopción: Facilita la relación entre usuarios y las mascotas disponibles para adopción.
Conexión a MongoDB: Usa Mongoose para interactuar con la base de datos.
Manejo de configuración mediante dotenv: Para mantener segura la configuración del entorno.
Requisitos Previos
Antes de proceder con la instalación, asegúrate de tener lo siguiente:

Node.js (versión 18 o superior).
MongoDB (local o en la nube).
Docker (opcional, si prefieres ejecutar la aplicación en un contenedor).
Instrucciones de Instalación
Instalar dependencias:

npm install
Configurar las variables de entorno:
Crea un archivo .env en la raíz del proyecto con el siguiente contenido:

PORT=8080
MONGO_URL=tu_url_de_mongodb
Iniciar la aplicación:

npm start
Tecnologías Usadas
Node.js y Express.js para el desarrollo del backend.
MongoDB y Mongoose para la base de datos.
dotenv para gestionar variables de entorno.
Docker para ejecutar la aplicación en contenedores (opcional).
Enlaces:
[Imagen de Docker en DockerHub](https://hub.docker.com/repository/docker/erusiani/adoptme/general)