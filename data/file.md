# file

## Descripción

Se utiliza para identificar el tipo de un archivo.

Puede detectar si un archivo es texto, imagen, ejecutable, comprimido, entre otros.

---

## Sintaxis (como se utiliza el comando "file" en la terminal)

file [archivo]

## Opciones útiles

### -i
Muestra el tipo MIME del archivo.

### -b
Oculta el nombre del archivo en la salida.

### -z
Permite analizar archivos comprimidos.

---

## Ejemplos

Identificar archivo: file documento.txt

Ver tipo MIME: file -i imagen.png

Analizar archivo comprimido: file -z respaldo.zip

---

## Errores y problemas comunes

#### Error:
Intentar analizar un archivo inexistente.

-Ejemplo incorrecto: file prueba.txt (Si el archivo no existe)

#### Solución:
Verificar primero que el archivo exista.

-Ejemplo correcto 1: ls
-Ejemplo correcto 2: file documento.txt
