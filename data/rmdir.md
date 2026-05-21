# rmdir

## Descripción

Se utiliza para eliminar directorios vacíos.

A diferencia de "rm -r", este comando solamente funciona si la carpeta no contiene archivos.

---

## Sintaxis (como se utiliza el comando "rmdir" en la terminal)

rmdir [nombre_directorio]

---

## Opciones útiles

### --ignore-fail-on-non-empty
Evita mostrar errores si la carpeta contiene archivos.

### -v
Muestra información del proceso.

### --help
Muestra ayuda sobre el comando.

---

## Ejemplos

Eliminar carpeta vacía: rmdir pruebas

Eliminar mostrando detalles: rmdir -v pruebas

---

## Errores y problemas comunes

#### Error:
Intentar eliminar carpetas que contienen archivos.

-Ejemplo incorrecto: rmdir documentos

#### Solución:
Vaciar primero la carpeta o utilizar "rm -r".

-Ejemplo correcto 1: rm -r documentos
-Ejemplo correcto 2: rmdir pruebas
