![WhatsApp Image 2023-09-25 at 3 00 26 PM](https://github.com/wobistdu003/Administracion-servidores-windows/assets/110427600/9c21c64a-b724-4b02-bb95-245bc9f2e232)

# Instalaciòn DHCP server. :page_facing_up:
Esta guía básica de instalación de DHCP en Windows Server. El Protocolo de Configuración Dinámica de Host (DHCP) es fundamental para asignar direcciones IP de 
forma automática a dispositivos en una red. Aquí tienes los pasos para configurar un servidor DHCP en Windows Server:

## Paso 1: Inicia sesión en tu servidor. 

- [x] Asegúrate de estar conectado a tu servidor Windows con derechos de administrador.

## Paso 2: Abre el Administrador del Servidor.

- [x] Presiona las teclas Win + X y selecciona "Administrador del Servidor" o simplemente busca "Administrador del Servidor" en el menú Inicio.

## Paso 3: Agrega el rol de servidor DHCP.

- [x] En el Administrador del Servidor, selecciona "Agregar roles y características" desde el panel de tareas en el dashboard.

## Paso 4: Asistente para Agregar Roles y Características.

- [x] Aparecerá el Asistente para Agregar Roles y Características. Haz clic en "Siguiente" para avanzar.

## Paso 5: Selección de roles.

- [x]  En la pantalla "Seleccionar tipo de instalación", elige "Rol basado en características o en roles" y haz clic en "Siguiente".

## Paso 6: Selección del servidor.

- [x] Selecciona tu servidor en la lista o ingresa su nombre y haz clic en "Siguiente".

## Paso 7: Roles de servidor.

- [x] En la lista de roles de servidor, busca y selecciona "Servidor DHCP". Se te mostrará una ventana emergente que explica el rol de DHCP, haz clic en "Agregar características"
para agregar las características requeridas y luego "Siguiente".

## Paso 8: Confirmación.

- [x] Revisa la información en la pantalla de confirmación y luego haz clic en "Instalar" para comenzar la instalación del servidor DHCP.

## Paso 9: Completar el asistente.

- [x] Una vez que se complete la instalación, verás una pantalla de confirmación. Haz clic en "Cerrar" para finalizar el asistente.

## Paso 10: Configurar el servidor DHCP.

- [x] Ahora que DHCP está instalado, debes configurarlo. Abre el "Administrador de DHCP" desde el menú "Herramientas administrativas" en el menú Inicio.

## Paso 11: Configuración de ámbito.

- [x] En el Administrador de DHCP, expande el nombre de tu servidor y luego haz clic derecho en "Ámbitos" y selecciona "Nuevo ámbito".

## Paso 12: Asistente para nuevo ámbito.

- [x] El asistente para el nuevo ámbito te guiará a través de la configuración del ámbito DHCP. Debes proporcionar información como el nombre del ámbito, el rango de direcciones
IP que se asignarán, la máscara de subred, la puerta de enlace predeterminada, el DNS y más.

## Paso 13: Activar el ámbito.

- [x] Una vez configurado el ámbito, actívalo haciendo clic derecho en él y seleccionando "Activar ámbito".

## Video :movie_camera:


# 
### :loudspeaker:
> [!NOTE]
> ¡Eso es todo! Tu servidor DHCP en Windows Server ahora está configurado y activo, y debería empezar a asignar direcciones IP automáticamente a los dispositivos de tu red.

> [!IMPORTANT]
Asegúrate de ajustar la configuración del ámbito según tus necesidades específicas de red, como la duración de la concesión de direcciones IP, las exclusiones, las reservas y otros parámetros necesarios para tu entorno.
