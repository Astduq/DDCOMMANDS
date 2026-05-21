# top

## Descripción

Se utiliza para monitorear procesos y recursos del sistema en tiempo real.

Permite ver el uso de CPU, memoria RAM y procesos activos.

---

## Sintaxis (como se utiliza el comando "top" en la terminal)

top

## Opciones útiles

### -u
Filtra procesos por usuario.

### -d
Cambia el tiempo de actualización.

### -n
Limita cantidad de actualizaciones.

---

## Ejemplos

Abrir monitor del sistema: top

Ver procesos de un usuario: top -u juan

Actualizar cada 5 segundos: top -d 5

---

## Errores y problemas comunes

#### Error:
No saber cómo salir del programa.

-Ejemplo incorrecto: top

(El programa permanece abierto continuamente)

#### Solución:
Presionar la tecla "q" para cerrar el programa.

-Ejemplo correcto 1: top
-Ejemplo correcto 2: q
