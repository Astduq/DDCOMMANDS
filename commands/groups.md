# groups

## Descripción

Se utiliza para mostrar los grupos a los que pertenece un usuario.

Es útil para comprobar permisos y accesos dentro del sistema.

---

## Sintaxis (como se utiliza el comando "groups" en la terminal)

groups [usuario]

## Opciones útiles

Este comando normalmente no necesita opciones.

---

## Ejemplos

Ver grupos del usuario actual: groups

Ver grupos de otro usuario: groups juan

Comprobar permisos de administrador: groups usuario

---

## Errores y problemas comunes

#### Error:
Esperar información detallada de permisos.

-Ejemplo incorrecto: groups (Buscar permisos completos del usuario)

#### Solución:
Usar id para obtener información más completa.

-Ejemplo correcto 1: groups
-Ejemplo correcto 2: id usuario
