# wget

## Descripción

Se utiliza para descargar archivos desde internet directamente desde la terminal.

Es muy útil para descargar programas, scripts o archivos rápidamente.

---

## Sintaxis (como se utiliza el comando "wget" en la terminal)

wget [dirección]

## Opciones útiles

### -O
Permite guardar el archivo con otro nombre.

### -c
Continúa descargas interrumpidas.

### -q
Oculta mensajes de salida.

---

## Ejemplos

Descargar un archivo: wget archivo.zip

Guardar con otro nombre: wget -O programa.zip archivo.zip

Continuar descarga: wget -c archivo.zip

---

## Errores y problemas comunes

#### Error:
Intentar descargar archivos en rutas sin permisos.

-Ejemplo incorrecto:wget archivo.zip -O /root/programa.zip

#### Solución:
Guardar el archivo en una carpeta accesible o usar sudo.

-Ejemplo correcto 1:wget archivo.zip
-Ejemplo correcto 2:sudo wget archivo.zip -O /root/programa.zip
