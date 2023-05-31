# Aplicación de Películas

## Descripción
Este proyecto es una aplicación de películas que permite realizar operaciones CRUD (Crear, Leer, Actualizar y Eliminar) en una base de datos de películas. Está desarrollado en Node.js utilizando el patrón de diseño MVC (Modelo-Vista-Controlador) con Express como framework backend.

La aplicación consta de los siguientes componentes:
- Controladores (Controllers): Manejan las solicitudes HTTP y gestionan la lógica de negocio.
- Rutas (Routes): Definen las rutas de la API y establecen la conexión entre las solicitudes HTTP y los controladores correspondientes.
- Modelos (Models): Representan la estructura y el comportamiento de los datos de la aplicación. Utiliza Sequelize para interactuar con la base de datos.
- Vistas (Views): Utiliza EJS para generar las vistas HTML dinámicas.

Además de las operaciones CRUD en la base de datos de películas, este proyecto también provee una API que puede ser consumida por un dashboard en otro proyecto.

## Tecnologías utilizadas
- Node.js
- Express
- Express Validator
- HTML
- CSS
- JavaScript
- EJS
- Sequelize

## Instalación
1. Clona el repositorio: `git clone https://github.com/tu_usuario/tu_repositorio.git`
2. Ingresa al directorio del proyecto: `cd tu_repositorio`
3. Instala las dependencias: `npm install`
4. Configura la conexión a la base de datos en el archivo `.env`
5. Ejecuta las migraciones de la base de datos: `npm run migrate`
6. Inicia la aplicación: `npm start`

## Uso
- Accede a la aplicación a través de tu navegador web en la siguiente dirección: `http://localhost:3000`
- Utiliza las diferentes rutas y funcionalidades para realizar operaciones CRUD en la base de datos de películas.

## Contribución
Las contribuciones son bienvenidas. Si tienes alguna sugerencia o mejora, no dudes en abrir un problema o enviar un pull request.


## Contacto
Puedes contactarme a través de mi correo electrónico: villalbaleandroesteban@gmail.com
