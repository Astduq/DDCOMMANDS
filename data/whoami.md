# whoami

## Descripción

Se utiliza para mostrar el nombre del usuario actual.

Es útil para comprobar con qué usuario se está trabajando.

---

## Sintaxis (como se utiliza el comando "whoami" en la terminal)

whoami

## Opciones útiles

Este comando normalmente no necesita opciones.

---

## Ejemplos

Mostrar usuario actual: whoami

Comprobar usuario después de usar sudo: sudo whoami

Verificar usuario en servidor: whoami

---

## Errores y problemas comunes

#### Error:
Confundir usuario normal con root.

-Ejemplo incorrecto: sudo su (No comprobar el usuario actual)

#### Solución:
Verificar siempre el usuario activo.

-Ejemplo correcto 1: whoami
-Ejemplo correcto 2: sudo whoami
