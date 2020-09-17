Lógica de Desarrollo
====================

En esta sección abarcaremos a detalle, todos los requerimientos de desarrollo entregados por el cliente.
Estos requerimientos son funcionalidades dentro del sistema de información, que nos permitirá almacenar, modificar, enviar, actualizar & borrar datos, dependiendo de lo requerido en cada módulo.


Requerimientos de desarrollo:
-----------------------------

i)Primer Requerimiento(Formulario/Registro):
--------------------------------------------

a.)Se debe validar que no hayan campos vacios.
b.)Validar que C.C. & Código Postal solo sean números.
c.)Fecha de nacimiento con el selector de calendario.
d.)Crear 10 habilidades con un check, se permita un máximo de 3 habilidades por usuario.
e.)Descripión debe ser un espacio de texto para máximo 500 caracteres
f.)Este formulario se debe alojar en la Base de Datos Firebase


ii)Segundo Requerimiento(Registro & Home/sidebar):
--------------------------

a.)Validar dato de cédula & e-mail no existan en la base de datos, si existe, avisar inmediatamente al usuario.
b.)Añadir web service para los municipios y departamentos de Colombia.
c.)Al ser exitoso el registro, debe salir un modal dando la gracias por el registro.
d.)Menu lateral a la izquierda. con los 4 módulos: Registro, Inicio de Sesion, Registros, Mi Perfil, Video & Salir
e.)Registros: Crear tabla que liste por columnas todos los registro que haya en la base de datos.


iii)Tercer Requerimiento(Restricciones):
----------------------------------------

a)Sector público: Home, Resgistro, Inicio de Sesion & Video.
b)Sectro privado: Todoas las secciones habilitadas del ejercicio.


iv)Cuarto Requerimiento(Mi Perfil):
-------------------------
a)Logo en la esquina superior izquierda en navegador y al medio en modo responsivo.
b)Sección de mi perfil, se mostrarán los datos del usuario logeado.
c)Botón de editar, permite abrir los campos y actualizar los que sean editados con un botón de guardar.
d)Permitir añadir una foto que no pese más de 1Mb en formato jpg/png

v)Quinto Requerimiento(Menú y Contacto):
-----------------------

a.)Añadir al header un menú en el medio con los componentes de Inicio, Equipo y Contacto.
b.)crear formulario para contacto. en el formulario, validar que sea un correo, se debe almacenar el formulario enviado en la Base de datos, 
y enviar la información de ese contacto por correo electrónico a CEO@AIATIC.COM

vi)Sexto Requerimiento (Nuevos integrantes):
-----------------------------------
a)Crear una copia del proyecto desarrollado
b)Compartir acceso a la copia del proyecto
c)Agregar nuevas funciones 
  1.Añadir los nuevos miembros
  2.Cambiar nombre del proyecto
  3.Cambiar el Logo
  4.Cambiar el color del header.
