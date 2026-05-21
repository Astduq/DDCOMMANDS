# grep

## Descripción

Se utiliza para buscar palabras o patrones dentro de archivos de texto.

Es muy útil para encontrar información específica rápidamente.

---

## Sintaxis (como se utiliza el comando "grep" en la terminal)

grep [palabra] [archivo]

## Opciones útiles

### -i
Ignora mayúsculas y minúsculas.

### -n
Muestra el número de línea donde aparece el resultado.

### -r
Busca de forma recursiva dentro de carpetas.

---

## Ejemplos

Buscar una palabra: grep admin usuarios.txt

Buscar ignorando mayúsculas: grep -i error logs.txt

Buscar dentro de carpetas: grep -r root /etc

---

## Errores y problemas comunes

#### Error:
No ingresar explicitamente el archivo o directorio donde buscar.

-Ejemplo incorrecto: grep usuario

#### Solución:
Indicar correctamente el archivo o directorio donde se realizará la búsqueda.

-Ejemplo correcto 1: grep usuario cuentas.txt
-Ejemplo correcto 2: grep -r usuario /home
