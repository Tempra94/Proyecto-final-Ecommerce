# Curso Backend -  Proyecto Final



## User story/brief 👨‍💼👩‍💼

##### Contendrá las rutas necesarias que permitan listar los productos existentes, ingresar productos nuevos, borrar y modificar sus detalles, así como interactuar con el carrito de compras.

- Se implementará una API RESTful con los verbos get, post, put y delete para
  cumplir con todas las acciones necesarias.
- Debe brindar al frontend un mecanismo de ingreso autorizado al sistema
  basado en JWT (Json Web Token).
- Los productos ingresados se almacenarán en una base de datos MongoDB.
- El usuario podrá registrar sus credenciales de acceso (email y password)
  para luego poder ingresar a su cuenta. Estas credenciales serán guardadas
  en la base de datos MongoDB encriptando la contraseña.
- El cliente tendrá una sesión activa de usuario con tiempo de expiración
  configurable.
- Implementarás un canal de chat basado en websockets, el cual
  permita atender las consultas del cliente.
- La arquitectura del servidor estará basada en capas (MVC)
- El servidor podrá tomar configuraciones desde un archivo externo.
- Se enviará un mail a una casilla configurable, por cada registro nuevo de
  usuario y con cada orden de compra generada.
- En caso de detectar algún error, el servidor enviará una vista.

## Piezas 🔰

- Node.js
- MongoDB
- Passport JWT
- Mongoose
- Bcrypt
- Websocket
- Dotenv
- Handlebars
- Nodemailer


