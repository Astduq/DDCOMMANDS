# sudo

## Descripción

Se utiliza para ejecutar comandos con permisos de administrador.

Es uno de los comandos más importantes en Linux.

---

## Sintaxis (como se utiliza el comando "sudo" en la terminal)

sudo [comando]

## Opciones útiles

### -i
Abre una sesión como administrador.

### -u
Ejecuta comandos como otro usuario.

### -k
Elimina credenciales guardadas.

---

## Ejemplos

Actualizar paquetes: sudo apt update

Ejecutar comando como root: sudo -i

Ejecutar comando como otro usuario: sudo -u juan ls

---

## Errores y problemas comunes

#### Error:
No pertenecer al grupo sudo.

-Ejemplo incorrecto: sudo apt update (usuario no autorizado)

#### Solución:
Agregar el usuario al grupo sudo.

-Ejemplo correcto 1: su (Para root)
-Ejemplo correcto 2: usermod -aG sudo usuario
