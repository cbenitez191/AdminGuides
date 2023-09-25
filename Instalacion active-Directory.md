A continuación, te proporcionaré una guía básica paso a paso para la instalación de Active Directory en un servidor con Windows Server. Active Directory es una función importante de Windows Server que permite administrar recursos de red de manera centralizada. Asegúrate de que Windows Server ya esté instalado antes de comenzar con estos pasos.

Paso 1: Acceder al Administrador del servidor:

Inicia sesión en tu servidor con una cuenta que tenga permisos de administrador.
En el Escritorio, presiona las teclas "Ctrl + Alt + Supr" y selecciona "Administrar" o abre el "Administrador del servidor" desde el menú Inicio.
Paso 2: Agregar roles y características:
3. En el "Administrador del servidor", haz clic en "Administrar" en la esquina superior derecha y selecciona "Agregar roles y características".

Se abrirá el Asistente para agregar roles y características. Haz clic en "Siguiente" en la primera pantalla de bienvenida.
Paso 3: Seleccionar tipo de instalación:
5. En la siguiente pantalla, selecciona "Instalación basada en características o roles" y haz clic en "Siguiente".

Paso 4: Seleccionar el servidor:
6. Asegúrate de que tu servidor esté seleccionado en la lista y luego haz clic en "Siguiente".

Paso 5: Seleccionar roles de servidor:
7. En la lista de roles, marca la casilla junto a "Servicios de dominio de Active Directory" para instalarlo. Aparecerá una ventana emergente que te informará sobre las características adicionales que se deben instalar para el AD DS (Servicios de Dominio de Active Directory). Haz clic en "Agregar características" y luego en "Siguiente".

Paso 6: Confirmar selección:
8. Lee la información sobre el rol que estás a punto de instalar y haz clic en "Siguiente".

Paso 7: Características adicionales:
9. En la pantalla de "Características", simplemente haz clic en "Siguiente" para aceptar la selección predeterminada.

Paso 8: Confirmar instalación:
10. Revisa la información en la pantalla de confirmación y luego haz clic en "Instalar" para comenzar la instalación de Active Directory.

Paso 9: Completar la instalación:
11. Una vez que la instalación se complete, deberías ver un mensaje de éxito. Haz clic en "Cerrar" para finalizar la instalación.

Paso 10: Configurar Active Directory:
12. Después de instalar el rol de Servicios de Dominio de Active Directory, deberás configurar el dominio. Esto implicará establecer un nombre de dominio, una contraseña de administrador de Directory Services y otras configuraciones específicas de tu red.

Paso 11: Reiniciar el servidor:
13. Para aplicar completamente las configuraciones de Active Directory, se te pedirá que reinicies el servidor. Asegúrate de guardar cualquier trabajo no guardado antes de hacerlo.

Una vez que hayas completado estos pasos, habrás instalado Active Directory en tu servidor Windows. Puedes comenzar a administrar usuarios, grupos, políticas de seguridad y otros recursos de red de manera centralizada a través de Active Directory.

Recuerda que esta es una guía básica y que los detalles pueden variar según la versión específica de Windows Server que estés utilizando.
