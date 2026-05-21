# adduser

## Descripción

Se utiliza para crear nuevos usuarios en el sistema.

Permite configurar contraseña y datos básicos del usuario.

---

## Sintaxis (como se utiliza el comando "adduser" en la terminal)

adduser [usuario]

## Opciones útiles

### --home
Permite definir directorio personal.

### --shell
Permite elegir shell del usuario.

### --ingroup
Añade el usuario a un grupo específico.

---

## Ejemplos

Crear un usuario: sudo adduser juan

Crear usuario con grupo: sudo adduser juan usuarios

Crear usuario personalizado: sudo adduser --shell /bin/bash juan

---

## Errores y problemas comunes

#### Error:
Intentar crear usuarios sin permisos de administrador.

-Ejemplo incorrecto: adduser juan

#### Solución:
Usar sudo para administrar usuarios.

-Ejemplo correcto 1: sudo adduser juan
-Ejemplo correcto 2: sudo adduser prueba
