# touch

## Descripción

Se utiliza para crear archivos vacíos rápidamente desde la terminal.

Tambien puede modificar la fecha de actualización de un archivo ya existente (es como recargar el archivo).

---

## Sintaxis (como se utiliza el comando "touch" en la terminal)

touch [nombre_archivo]

---

## Opciones útiles

### -c
Evita crear el archivo si no existe.

### -a
Modifica únicamente la fecha de acceso.

### -m
Modifica únicamente la fecha de modificación.

---

## Ejemplos

Crear un archivo: touch prueba.txt

Crear varios archivos: touch archivo1.txt archivo2.sh

Actualizar fecha de modificación: touch -m prueba.txt

---

## Errores y problemas comunes

#### Error:
Intentar crear archivos en una ruta sin permisos.

-Ejemplo incorrecto: touch /root/prueba.txt

#### Solución:
Usar permisos adecuados o utilizar sudo.

-Ejemplo correcto 1: sudo touch /root/prueba.txt
-Ejemplo correcto 2: touch prueba.txt
