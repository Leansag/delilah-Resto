# delilah-Resto
sistema de pedidos online para un restaurante.

https://github.com/Leansag/delilah-Resto

Delilah Restó es una aplicación web de restaurante. Este proyecto contiene el componente backend del sistema, que en general es un catálogo de productos y un administrador de pedidos.

Instalación

Servidor HTTP y base de datos

El sistema Delilah Restó se ejecuta con una base de datos MySQL, por lo que se debe instalar el motor de la base de datos MySQL.

1. XAMMP instalar
2. Inicie tanto Apache como MySQL
3. Abra el administrador de MySQL
4.Crea una nueva base de datos

5. Nombre la nueva base de datos como "delilah_resto" y haga clic en crear
6.Haga clic en "importar"
7.Haga clic en seleccionar
8.Seleccione el archivo "delilah_resto.sql" adjunto en la carpeta del proyecto
9.Vamos

Servidor Express

1.Instalar NodeJS ( https://nodejs.org/es/ )

2.Abra la terminal CMD en Visual Studio Code

3.Asegúrese de que la ruta en el comando coincida con la ruta absoluta de la carpeta de rutas en su PC.

\delilahResto-main\

4.Ejecute el siguiente comando "npm install" y espere a que finalice

\delilahResto-main\> npm install

5.Ejecute el siguiente comando "Rutas de CD"

\delilahResto-main\> CD routes

6.Ejecute el siguiente comando "nodo index.js"

\delilahResto-main\routes\> node index.js

Uso

Para conocer el uso de esta API, consulte el archivo .yaml para ver la descripción del archivo Swagger OpenAPI.

Pruebas

Use Postman para probar todos los puntos finales disponibles en la API. Postman de solicitudes disponible dentro de la carpeta del proyecto dentro de la carpeta "adjuntos", "Delilah Restó.postman_collection.json".

Usuario

1 - Poder registrar un nuevo usuario.

2 - Un usuario debe poder enumerar todos los productos disponibles.

3 - Un usuario debe poder generar un nuevo pedido al Restaurante con una lista de platos que desea.

4 - El usuario con roles de administrador debe poder actualizar el estado del pedido.

5 - Un usuario con rol de administrador debe poder realizar las acciones de creación, edición y eliminación de recursos de productos (CRUD de productos).

6 - Un usuario sin roles de administrador no debería poder crear, editar o eliminar un producto, o editar o eliminar un pedido. Tampoco debería poder acceder a la información de otros usuarios.





