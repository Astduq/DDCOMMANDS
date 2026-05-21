# more

## Descripción

Se utiliza para visualizar archivos largos página por página.

Es parecido a less, aunque tiene menos funciones.

---

## Sintaxis (como se utiliza el comando "more" en la terminal)

more [archivo]

## Opciones útiles

### -d
Muestra mensajes de ayuda mientras se navega.

### -c
Limpia la pantalla antes de mostrar cada página.

### -s
Reduce líneas vacías repetidas.

---

## Ejemplos

Leer un archivo: more documento.txt

Leer mostrando ayuda: more -d notas.txt

Leer limpiando pantalla: more -c registros.txt

---

## Errores y problemas comunes

#### Error:
Pensar que se puede navegar libremente como en less.

-Ejemplo incorrecto: more archivo.txt (Intentando usar muchas teclas de navegación avanzadas)

#### Solución:
Usar less si se necesita mayor control al navegar y te sientes mas comodo.

-Ejemplo correcto 1: less archivo.txt
-Ejemplo correcto 2: more archivo.txt (utilizalo si necesitas leer un archivo de manera rapida y facil)
