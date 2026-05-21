# stat

## Descripción

Se utiliza para mostrar información detallada sobre archivos y directorios.

Permite ver permisos, tamaño, fechas y otra información importante.

---

## Sintaxis (como se utiliza el comando "stat" en la terminal)

stat [archivo]

## Opciones útiles

### -c
Permite personalizar la información mostrada.

### -f
Muestra información del sistema de archivos.

### --printf
Muestra datos con formato personalizado.

---

## Ejemplos

Ver información de un archivo: stat notas.txt

Mostrar sistema de archivos: stat -f notas.txt

Mostrar solo tamaño: stat -c %s notas.txt

---

## Errores y problemas comunes

#### Error:
Consultar archivos inexistentes.

-Ejemplo incorrecto: stat prueba.txt

#### Solución:
Comprobar primero que el archivo exista.

-Ejemplo correcto 1: ls
-Ejemplo correcto 2: stat archivo.txt
