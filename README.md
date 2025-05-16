# 🪟 Scripts y guías para administración de Windows Server

## 📌 Descripción del Proyecto.

Esta sección del repositorio contiene documentación técnica y, próximamente, scripts en PowerShell orientados a la administración de **Windows Server**. Está diseñada para apoyar tareas comunes como configuración de roles, mantenimiento, creación de usuarios y automatización de tareas administrativas en entornos reales o de laboratorio.

---

## 🎯 Objetivos.

- Reunir guías paso a paso para roles y servicios en Windows Server.
- Incluir scripts que automaticen tareas administrativas frecuentes.
- Facilitar el aprendizaje técnico para estudiantes y profesionales de TI.
- Servir como base para prácticas de laboratorio y producción.

---

## 📁 Estructura de la Carpeta `Windows/`.

| Archivo / Script                              | Descripción                                                                 |
|-----------------------------------------------|-----------------------------------------------------------------------------|
| `Introduccion_Windows_server.md`              | Introducción a conceptos clave de Windows Server.                          |
| `Configuracion DNS.md`                        | Guía de instalación y configuración del rol DNS.                           |
| `Instalacion DHCP.md`                         | Instalación y configuración del servicio DHCP.                             |
| `Instalacion active-Directory.md`             | Implementación de Active Directory Domain Services (AD DS).                |
| `Novedades_Windows_server_2022.md`            | Características destacadas de Windows Server 2022.                         |
| `Editar imagen iso windows.md`                | Cómo personalizar imágenes ISO para despliegue automatizado.              |
| `Instalar VMware Workstation 17.md`           | Instalación de VMware Workstation para entornos de prueba o desarrollo.    |

---

## ⚙️ Ejemplos de Scripts PowerShell.

- `verificar_servicios.ps1`: Revisa servicios críticos y los reinicia si están detenidos.
- `backup_directorios.ps1`: Realiza copias de seguridad de carpetas clave.
- `limpiar_temp.ps1`: Limpia archivos temporales del sistema.
- `inventario_software.ps1`: Genera un inventario de software instalado.
- `crear_usuarios_AD.ps1`: Automatiza la creación de usuarios en Active Directory desde CSV.

---
# 🐧 Administración de Servidores Linux.

Esta carpeta está dedicada a la administración de servidores Linux, incluyendo scripts en Bash y documentación técnica orientada a tareas comunes de administración, mantenimiento y monitoreo. Es ideal para automatizar procesos repetitivos y aplicar buenas prácticas en entornos reales o de laboratorio.

---

## 📄 Scripts Disponibles.

| Script                                 | Descripción                                                                 |
|----------------------------------------|-----------------------------------------------------------------------------|
| `verificar_ruta.sh`                    | Solicita una ruta y valida si corresponde a un archivo, directorio o si no existe. |
| `monitorear_disco.sh` *(pendiente)*    | Revisa el uso del disco y lanza alertas si se supera un umbral.            |
| `backup_rapido.sh` *(pendiente)*       | Realiza una copia de seguridad comprimida (`tar.gz`) de un directorio.     |
| `actualizar_sistema.sh` *(pendiente)*  | Automatiza la actualización del sistema (`apt`, `yum`, o `dnf`).           |
| `crear_usuarios.sh` *(pendiente)*      | Crea múltiples usuarios desde un archivo `.csv`.                           |

---

## 📚 Documentación (Futura).

| Archivo sugerido                          | Descripción                                                                 |
|-------------------------------------------|-----------------------------------------------------------------------------|
| `Introduccion_Linux_Server.md`            | Conceptos básicos sobre administración de servidores Linux.                 |
| `Configuracion_SSH_Seguro.md`             | Recomendaciones para proteger el acceso remoto SSH.                         |
| `Hardening_Basico_Linux.md`               | Pasos iniciales para reforzar la seguridad de un servidor Linux.            |
| `Instalacion_Servidor_Web_Apache.md`      | Instalación y configuración básica de Apache como servidor web.             |
| `Configurar_Cron_Tareas_Automatizadas.md` | Guía para automatizar tareas con cron.                                      |

---

## 👥 Público Objetivo.

Este material está dirigido a:

- Administradores de sistemas Windows
- Técnicos de soporte en entornos empresariales
- Estudiantes de redes, sistemas o infraestructura
- Profesionales que deseen documentar y automatizar su entorno Windows

---

## 📬 Contribuciones.

¿Tienes un procedimiento documentado o script útil en PowerShell?  
¡Tu aporte puede ser muy valioso!  
Puedes enviar un Pull Request o abrir un *issue* con tu sugerencia.

---

📌 **Autor:** Carlos Benítez – CBTech  
🛡️ Proyecto técnico en desarrollo para fortalecer la administración de servidores Windows.
