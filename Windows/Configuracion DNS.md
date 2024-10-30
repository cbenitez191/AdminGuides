![DNS](https://github.com/wobistdu003/Administracion-servidores-windows/assets/110427600/bf76048e-42e5-470e-a33f-9c314832243d)

# Configuración DNS server. :page_facing_up:
El sistema de nombres de dominio, también conocido como DNS, es una estructura de nomenclatura jerárquica y descentralizada que se utiliza para 
identificar dispositivos conectados a redes IP, como la Internet o una red privada. En este sistema, se vincula una variedad de datos con los 
nombres de dominio asignados a cada uno de los usuarios o dispositivos involucrados.

A continuación comparto una guia basica para configurar los DNS en un servidor Windows.

## Paso 1: Instalar el servicio DNS.

- [x] Inicia sesión en tu servidor Windows como administrador.
- [x] Abre el "Administrador del servidor". Puedes hacerlo desde el menú "Inicio" o escribiendo "ServerManager" en el cuadro de búsqueda.
- [x] En el Administrador del servidor, haz clic en "Administrar" en la parte superior derecha y selecciona "Agregar roles y características".
- [x] En el asistente de instalación de roles y características, selecciona "Servidor DNS" en la lista de roles. Luego, sigue las instrucciones
      del asistente para completar la instalación.

## Paso 2: Configurar los servidores DNS. 

- [x] Después de instalar el servicio DNS, debes configurar los servidores DNS. Aquí te explicaré cómo configurar un servidor DNS primario:
- [x] Abre el "Administrador de DNS". Puedes encontrarlo en "Herramientas administrativas" en el menú "Inicio".
- [x] En el Administrador de DNS, expande el nodo del servidor (generalmente se llama el nombre de tu servidor).
- [x] Haz clic derecho en "Zonas de búsqueda directa" y selecciona "Nueva zona..." para crear una nueva zona de búsqueda directa. Sigue el
      asistente para configurar la zona, incluyendo la opción de "Zona primaria" y "Almacenar la zona en archivos de texto".
- [x] Configura la zona con los registros DNS que necesites, como registros A para direcciones IP de host o registros MX para el correo.

## Paso 3: Configurar la reenviadores (forwarders) (opcional).

- [x] Si deseas que tu servidor DNS redirija las consultas DNS no resueltas a otro servidor DNS (como los servidores DNS de tu proveedor de
      servicios de Internet), puedes configurar los reenviadores de la siguiente manera:
- [x] En el Administrador de DNS, haz clic derecho en el nodo del servidor y selecciona "Propiedades".
- [ ]Ve a la pestaña "Reenviadores".
- [x] Haz clic en "Editar..." y agrega las direcciones IP de los servidores DNS a los que deseas reenviar las consultas no resueltas.

## Paso 4: Configurar la resolución inversa (opcional).

- [x] Si deseas configurar la resolución inversa para convertir direcciones IP en nombres de host (registros PTR), puedes hacerlo de la siguiente manera:
- [x] En el Administrador de DNS, expande el nodo del servidor.
- [x] Haz clic derecho en "Zonas de búsqueda inversa" y selecciona "Nueva zona..." para crear una nueva zona de búsqueda inversa. Sigue el asistente y selecciona
      "Zona primaria" y "Almacenar la zona en archivos de texto".
- [x] Configura la zona inversa con registros PTR para las direcciones IP de tu red.
- [x] Asegúrate de que la configuración de red de tus adaptadores esté configurada para usar este servidor DNS como servidor DNS preferido.

## Paso 5: Prueba la configuración.
- [x] Finalmente, es importante probar la configuración del servidor DNS para asegurarte de que funcione correctamente. Puedes hacerlo ejecutando comandos
      como "nslookup" o "ping" desde otros equipos de la red para verificar la resolución de nombres.

## Video :movie_camera:


# 
### :loudspeaker:
> [!NOTE]
> Recuerda que esta es una guía básica para configurar un servidor DNS en Windows Server. La configuración exacta puede variar según tus necesidades específicas
> y la topología de tu red. Además, asegúrate de seguir las mejores prácticas de seguridad, como restringir el acceso al servidor DNS y mantenerlo actualizado con
> parches de seguridad.
