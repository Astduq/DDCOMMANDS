# cat

## Descripción

Se utiliza para mostrar el contenido de archivos directamente desde la terminal.

También puede utilizarse para unir archivos o crear archivos rápidos desde consola.

Es uno de los comandos más básicos e importantes en Linux.

---

## Sintaxis (como se utiliza el comando "cat" en la terminal)

cat [archivo]

## Opciones útiles

### -n
Muestra números de línea junto al contenido.

### -b
Numera únicamente las líneas que contienen texto.

### -s
Reduce múltiples líneas vacías consecutivas.

---

## Ejemplos

Mostrar contenido de un archivo: cat notas.txt

Mostrar contenido numerado: cat -n notas.txt

Unir dos archivos: cat archivo1.txt archivo2.txt

---

## Errores y problemas comunes

#### Error:
Intentar leer un archivo inexistente sin permisos de lectura.

-Ejemplo incorrecto: cat prueba.txt (sin verificar si existe en el directorio actual)

#### Solución:
Verificar primero que el archivo exista dentro del directorio actual y que tenga activado el permiso de r (read/lectura).

-Ejemplo correcto 1: ls -l
-Ejemplo correcto 2: cat prueba.txt (si existe y tiene los permisos adecuados)
