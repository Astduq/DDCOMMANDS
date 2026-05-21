# apt

## Descripción

Se utiliza para instalar, actualizar y eliminar programas en distribuciones basadas en Debian.

Es uno de los comandos más importantes en Linux.

---

## Sintaxis (como se utiliza el comando "apt" en la terminal)

apt [acción]

## Opciones útiles

### install
Instala programas.

### remove
Elimina programas.

### update
Actualiza la lista de paquetes.

---

## Ejemplos

Actualizar repositorios: sudo apt update

Instalar un programa: sudo apt install nginx

Eliminar un programa: sudo apt remove nginx

---

## Errores y problemas comunes

#### Error:
Intentar instalar paquetes sin actualizar repositorios.

-Ejemplo incorrecto: sudo apt install programa

#### Solución:
Actualizar primero la lista de paquetes.

-Ejemplo correcto 1: sudo apt update
-Ejemplo correcto 2: sudo apt install programa
