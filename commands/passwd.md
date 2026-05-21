# passwd

## Descripción

Se utiliza para cambiar contraseñas de usuarios en Linux.

También permite bloquear o desbloquear cuentas.

---

## Sintaxis (como se utiliza el comando "passwd" en la terminal)

passwd [usuario]

## Opciones útiles

### -l
Bloquea una cuenta.

### -u
Desbloquea una cuenta.

### -d
Elimina contraseña del usuario.

---

## Ejemplos

Cambiar contraseña propia: passwd

Cambiar contraseña de otro usuario: sudo passwd juan

Bloquear una cuenta: sudo passwd -l juan

---

## Errores y problemas comunes

#### Error:
Intentar cambiar contraseñas ajenas sin permisos.

-Ejemplo incorrecto: passwd juan

#### Solución:
Usar sudo para administrar otros usuarios.

-Ejemplo correcto 1: sudo passwd juan
-Ejemplo correcto 2: passwd
