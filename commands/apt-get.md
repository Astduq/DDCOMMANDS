# apt-get

## Descripción

Se utiliza para gestionar paquetes en sistemas Debian y Ubuntu.

Es una versión más tradicional de apt y sigue siendo muy utilizada en servidores y scripts.

---

## Sintaxis (como se utiliza el comando "apt-get" en la terminal)

apt-get [acción]

## Opciones útiles

### install
Instala programas.

### remove
Elimina programas.

### upgrade
Actualiza paquetes instalados.

---

## Ejemplos

Actualizar repositorios: sudo apt-get update

Instalar Apache: sudo apt-get install apache2

Actualizar paquetes: sudo apt-get upgrade

---

## Errores y problemas comunes

#### Error:
Olvidar permisos administrativos.

-Ejemplo incorrecto: apt-get install nginx

#### Solución:
Utilizar sudo para administrar paquetes.

-Ejemplo correcto 1: sudo apt-get install nginx
-Ejemplo correcto 2: sudo apt-get update
