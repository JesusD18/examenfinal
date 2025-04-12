La API permite gestionar usuarios, incluyendo la obtención, actualización, eliminación y visualización de detalles. A continuación, las principales rutas disponibles:

GET /usuarios: Obtiene todos los usuarios.

GET /usuario/{id}: Obtiene detalles de un usuario por ID.

DELETE /eliminarusuario/{id}: Elimina un usuario por ID.

PUT /actualizarusuario/{id}: Actualiza los datos de un usuario por ID.

Autenticación: Se requiere un token JWT en los encabezados (Authorization: Bearer <token>).

Para obtener el token, inicia sesión en el sistema.
