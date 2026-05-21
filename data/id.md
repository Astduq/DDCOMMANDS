# id

## Descripción

Se utiliza para mostrar información sobre un usuario dentro del sistema.

Permite ver el UID, GID y los grupos a los que pertenece el usuario.

---

## Sintaxis (como se utiliza el comando "id" en la terminal)

id [usuario]

## Opciones útiles

### -u
Muestra únicamente el ID del usuario.

### -g
Muestra únicamente el ID del grupo principal.

### -n
Muestra nombres en lugar de números.

---

## Ejemplos

Ver información del usuario actual: id

Ver UID del usuario: id -u

Ver información de otro usuario: id juan

---

## Errores y problemas comunes

#### Error:
Consultar usuarios inexistentes.

-Ejemplo incorrecto: id usuariofalso

#### Solución:
Comprobar primero que el usuario exista en el sistema.

-Ejemplo correcto 1: cat /etc/passwd
-Ejemplo correcto 2: id usuario
