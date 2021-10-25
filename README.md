DESCRIPCIÓN
Para propósitos de este reto debes crear un proyecto que emule la funcionalidad de una herramienta administrativa:
1.	Crear un formulario de autenticación con usuario y contraseña.
Debe tener las siguientes validaciones:
- El usuario debe ser un correo válido
- La contraseña mínimo 7 caracteres
- La contraseña debe tener al menos un número
- La contraseña debe tener al menos una letra mayúscula
Adicionalmente, debes mostrar mensajes de error en los casos que apliquen.
2.	Debes hacer un markup llamativo y fácil de usar.
3.	En el contenido de la página “Usuarios” debes mostrar un listado de 10 usuarios que debes traer del backend realizado, los usuarios deben tener: id, nombres, apellidos, teléfono, email y estado (true o false). Además los usuarios deben venir ordenados por id en el Json, pero al momento de representarlos deben ser organizados por nombre, y mostrar los siguientes campos: nombre completo (nombres y apellidos), teléfono, email y estado.
4.	En la página “Tareas”, el usuario puede hacer un CRUD. Estas tareas deben estar sincronizadas con el componente de notificaciones del toolbar (mostrar el número de tareas).
5.	El manejo de sesión debe cumplir con las siguientes características:

- Las páginas de Inicio, Usuario y Tareas, sólo pueden ser accedidas cuando el usuario está logueado.
- Si el usuario tiene una sesión activa, no puede ver la página de logueo
