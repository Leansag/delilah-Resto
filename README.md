# delilah-Resto
sistema de pedidos online para un restaurante.

https://github.com/Leansag/delilah-Resto

Delilah Restó es una aplicación web de restaurante. Este proyecto contiene el componente backend del sistema, que en general es un catálogo de productos y un administrador de pedidos.

Instalación

1. Instale NodeJS ( https://nodejs.org/es/ )
2. Abra la terminal CMD en Visual Studio Code
3. Asegúrese de que la ruta en el comando coincida con la ruta absoluta de la carpeta de rutas en su PC.

\delilahResto-main\

4.Ejecute el siguiente comando "npm install" y espere a que finalice

\delilahResto-main\> npm install

5. Ejecute el siguiente comando "Rutas de CD"

\delilahResto-main\> CD routes

6. Ejecute el siguiente comando "node index.js" 

\delilahResto-main\routes> node index.js

Uso

Para conocer el uso de esta API, consulte el archivo .yaml para ver la descripción del archivo Swagger OpenAPI.



Pruebas

Utilice Postman para probar todos los puntos finales disponibles en la API. Todas las solicitudes han sido probadas previamente, por lo que hay una colección Postman de solicitudes disponible dentro de la carpeta del proyecto dentro de la carpeta "adjuntos", "Delilah Restó.postman_collection.json".


Usuario

1- Poder registrar un nuevo usuario.

2- Un usuario debe poder enumerar todos los productos disponibles.

3- Un usuario debe poder generar un nuevo pedido al Restaurante con una lista de platos que desea.

4- El usuario con roles de administrador debe poder actualizar el estado del pedido.

5- Un usuario con rol de administrador debe poder realizar las acciones de creación, edición y eliminación de recursos de productos (CRUD de productos).

6- Un usuario sin roles de administrador no debería poder crear, editar o eliminar un producto, o editar o eliminar un pedido. Tampoco debería poder acceder a la información de otros usuarios.
