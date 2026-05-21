# cp

## Descripción

Se utiliza para copiar archivos y directorios de un lugar a otro.

---

## Sintaxis (como se utiliza el comando "cp" en la terminal)

cp [archivo_origen] [destino]

---

## Opciones útiles

### -r
Permite copiar directorios completos junto con su contenido.

### -v
Muestra los archivos que se van copiando.

### -i
Pide confirmación antes de sobrescribir archivos.

---

## Ejemplos

Copiar un archivo: cp archivo.txt copia.txt

Copiar una carpeta: cp -r documentos backup/

Copiar mostrando detalles: cp -v prueba.txt copia.txt

---

## Errores y problemas comunes

#### Error:
Intentar copiar una carpeta sin utilizar "-r".

-Ejemplo incorrecto: cp documentos backup/

#### Solución:
Utilizar la opción "-r" para copiar directorios.

-Ejemplo correcto 1: cp -r documentos backup/
-Ejemplo correcto 2: cp -rv documentos backup/
