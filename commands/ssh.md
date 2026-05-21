# ssh

## Descripción

Se utiliza para conectarse remotamente a otro equipo mediante red.

Es uno de los comandos más utilizados en administración de servidores Linux.

---

## Sintaxis (como se utiliza el comando "ssh" en la terminal)

ssh [usuario@ip]

## Opciones útiles

### -p
Permite indicar un puerto personalizado.

### -i
Permite usar una clave privada.

### -X
Activa redirección gráfica.

---

## Ejemplos

Conectarse a un servidor: ssh usuario@192.168.1.10

Conectarse usando otro puerto: ssh -p 2222 usuario@192.168.1.10

Conectarse usando clave privada: ssh -i clave.pem usuario@192.168.1.10

---

## Errores y problemas comunes

#### Error:
Intentar conectarse a equipos apagados o inaccesibles.

-Ejemplo incorrecto: ssh usuario@192.168.1.50 (Connection refused)

#### Solución:
Comprobar conectividad y que el servicio SSH esté activo.

-Ejemplo correcto 1: ping 192.168.1.50
-Ejemplo correcto 2: sudo systemctl status ssh
