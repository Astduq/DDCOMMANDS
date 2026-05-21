# rm

## Descripción

Se utiliza para eliminar archivos y directorios desde la terminal.

Este comando debe utilizarse con cuidado ya que los archivos eliminados normalmente no se pueden recuperar facilmente.

---

## Sintaxis (como se utiliza el comando "rm" en la terminal)

rm [archivo]

---

## Opciones útiles

### -r
Permite eliminar directorios y su contenido.

### -f
Fuerza la eliminación sin pedir confirmación.

### -i
Pide confirmación antes de eliminar.

---

## Ejemplos

Eliminar archivo: rm prueba.txt

Eliminar carpeta completa: rm -r documentos/

Eliminar pidiendo confirmación: rm -i archivo.txt

---

## Errores y problemas comunes

#### Error:
Intentar eliminar carpetas sin utilizar "-r".

-Ejemplo incorrecto: rm documentos/

#### Solución:
Usar la opción "-r" para eliminar directorios.

-Ejemplo correcto 1: rm -r documentos/
-Ejemplo correcto 2: rm -ri documentos/
