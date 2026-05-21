# kill

## Descripción

Se utiliza para finalizar procesos en ejecución.

Es útil cuando un programa deja de responder o consume demasiados recursos.

---

## Sintaxis (como se utiliza el comando "kill" en la terminal)

kill [PID]

## Opciones útiles

### -9
Fuerza el cierre del proceso.

### -15
Finaliza procesos de forma segura.

### -l
Muestra señales disponibles.

---

## Ejemplos

Cerrar un proceso: kill 1234

Forzar cierre de un proceso: kill -9 1234

Mostrar señales: kill -l

---

## Errores y problemas comunes

#### Error:
Intentar cerrar procesos con nombre en lugar de PID.

-Ejemplo incorrecto: kill firefox

#### Solución:
Comprobar primero el PID correcto del proceso y cerrarlo con dicho PID.

-Ejemplo correcto 1: ps aux
-Ejemplo correcto 2: kill 1234
