# Rol Ansible: Firewall (UFW)

Este rol instala y configura el firewall UFW, estableciendo una política restrictiva por defecto para conexiones entrantes y permitiendo una lista dinámica de puertos TCP.

## Variables Expuestas
* `firewall_allowed_ports`: Una lista de enteros/strings con los puertos TCP que deben abrirse de manera explícita (Default: `[22]`).
## Dependencias
Requiere privilegios de escalado (`become: yes`) y que el sistema operativo soporte UFW.s