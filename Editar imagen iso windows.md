# Extraer archivo "install.win" de "install.esd"

Cuando se descarga una imagen ISO de Windows 10, utilizando la herramienta de creación de medios y al intentar crear una imagen liviana o para realizar un servicio WSD en un Windows server como rol se debe agregar un archivo de imagen (install.win) el cual es reemplazado por el archivo <<install.esd>> lo cual no permite de primera mano realizar el procedimiento que estemos realizando.

Como primera medida hay que convertir el archivo <<install.esd>> al tipo de archivo requerido por el programa o servicio que se desea configurar, este archivo se encuentra en la ruta "\sources" con el nombre de «install.esd». Este archivo contiene una copia completa del sistema operativo en un contenedor de protección el cual no puede ser editado.


Para extraer este archivo se realiza el siguiente procedimiento:
 
1. Como primera medida se debe descomprimir la imagen ISO en una carpeta o dar clic derecho y montar imagen, para este ejemplo se creó un directorio con el nombre "win" y se descomprime la imagen ISO. Luego se navega a la ruta donde se Encuentra el archivo, para este ejemplo se Encuentra en nuestro directorio "C:\Users\soporte4\Desktop\miniwin\win\sources"


![image](https://github.com/wobistdu003/Administracion-servidores-windows/assets/110427600/65eea173-0697-464e-8a2c-0891cec3b373)


2. Copiamos el archivo en el directorio donde se realizará la imagen.

3. Ejecutamos una consola "cmd" como administrador.

4. Mediante la línea de comandos de Windows se accede a la ubicación del archivo pegado anteriormente.

5. Ahora utilizamos el siguiente comando para saber que imágenes están disponibles en el archivo «install.esd».

 * dism /Get-WimInfo /WimFile:install.esd

6. Se listará las distribuciones de Windows 10 que contine la imagen ISO, en este caso tendrá que apuntar el número de índice según la distribución a utilizar.

Por ejemplo, si desea instalar la versión de Windows 10 Home deberá elegir el índice 1.

![image](https://github.com/wobistdu003/Administracion-servidores-windows/assets/110427600/fc3fd1a4-0747-4c3c-b05c-5bd9bbb1fff4)


7. A continuación utilizaremos el comando siguiente para extraer el archivo correspondiente de la versión Windows y así obtener el «install.wim».

Nota: Recuerde sustituir el número de índice en *IndexNumber* según corresponda, para este ejemplo se utilizó el numero 1 el cual es el índice para Windows 10 Home.

 * dism /export-image /SourceImageFile:install.esd /SourceIndex:1 /DestinationImageFile:install.wim /Compress:max /CheckIntegrity

![image](https://github.com/wobistdu003/Administracion-servidores-windows/assets/110427600/cd2d8af3-7d36-4f81-b06c-6d3c4d24a7ad)

8. Como paso final compiamos el archivo creado <<install.wind>> en la ruta o direcotorio "/sourses/ dnde se encunetra la imagen ISO a modificar.

   
## Video:movie_camera:



> [!IMPORTANT]
_¡Si tienes un problema comenta y la gente intentará ayudarte!_ :tada:
