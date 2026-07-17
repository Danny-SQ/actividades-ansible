# Rol Ansible: Webserver

Este rol automatiza la instalación de Nginx, genera un archivo HTML personalizado dinámico utilizando Jinja2 y asegura que el servicio esté habilitado y activo en el arranque.

## Variables Expuestas
* `webserver_port`: El puerto TCP en el que Nginx escuchará las peticiones (Default: `8080`).
* `web_site_title`: El título que se renderizará en la pestaña del navegador.
* `web_welcome_message`: El encabezado principal que se despliega en la página de inicio.

## Dependencias
No tiene dependencias externas. Diseñado para distribuciones Debian/Ubuntu.