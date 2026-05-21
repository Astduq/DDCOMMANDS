# head

## Descripción

Se utiliza para mostrar únicamente las primeras líneas de un archivo.

Por defecto muestra las primeras 10 líneas.

Es útil para revisar rápidamente archivos grandes.

---

## Sintaxis (como se utiliza el comando "head" en la terminal)

head [archivo]

## Opciones útiles

### -n
Permite especificar la cantidad de líneas a mostrar.

### -q
Oculta los nombres de archivos en la salida.

### -v
Muestra siempre los nombres de los archivos.

---

## Ejemplos

Mostrar primeras líneas: head notas.txt

Mostrar 5 líneas: head -n 5 notas.txt

Mostrar contenido de varios archivos: head archivo1.txt archivo2.txt

---

## Errores y problemas comunes

#### Error:
Pensar que muestra el archivo completo.

-Ejemplo incorrecto: head registros.txt (Esperando visualizar todo el contenido)

#### Solución:
Recordar que únicamente muestra las primeras líneas.

-Ejemplo correcto 1: head registros.txt
-Ejemplo correcto 2: nano, more o less (si necesitas visualizar más allá de las primeras lineas)
