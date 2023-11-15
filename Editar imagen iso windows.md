
Cuando había descargado una imagen ISO de Windows 10, utilizando la herramienta de creación de medios, me di cuenta al estar realizando una tarea en Windows server 2016 en la que intentaba crear un rol de WSD, y que justo en uno de los apartados de la configuración me pedía añadir el archivo de imagen install.wim, pero en mi Windows 10 no existía este archivo, habiendo solo un archivo llamado «install.esd» el cual no reconocía para poder continuar.

Este archivo se encuentra en la carpeta «sources» con el nombre de «install.esd», este archivo contiene una copia completa del sistema operativo en un contenedor de protección.

El archivo «install.esd» se puede utilizar para reparar el sistema operativo, utilizando la herramienta en linea de comando DISM añadiendo el modificador «/ sources», en caso de querer reparar Windows 10 o 8 / 8.1.
