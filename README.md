Ejercicio: CRUD con MongoDB y Python

Interacción con las herramientas

MongoDB Atlas 

- Seguridad: Creé un usuario para la base de datos con su contraseña para poder usarla en la cadena de conexión del código.
- Acceso de red: Al principio me dio un poco de problema porque olvidé habilitar el "Network Access". Tuve que agregar el IP para que Atlas permitiera la entrada de datos.
- Base de datos: Creé la base de datos y dentro la colección Estudiantes. 

MongoDB Compass (Gestión visual)

- Conecté Compass usando el mismo link (URI) que usé en el código.

Sobre el código y el menú

- El programa funciona con un menú interactivo que usa inputs para pedir la información. Las opciones que incluidas son:

Insertar estudiante: Aquí es donde se pide el nombre, la edad y la carrera de los compañeros para subirlos.
Listar estudiantes: Trae todos los datos guardados y los muestra en pantalla.
Actualizar edad: Busca a un estudiante por nombre y le cambia la edad.
Eliminar estudiante: Borra el registro de la base de datos.
Salir: Cierra la conexión.

Solución de errores (Handshake SSL)
Durante la práctica me salió un error de "SSL handshake failed". Lo solucioné instalando la librería certifi en Python.
