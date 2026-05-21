# nano

## Descripción

Se utiliza para editar archivos de texto directamente desde la terminal.

Es uno de los editores más fáciles de usar para principiantes en Linux.

---

## Sintaxis (como se utiliza el comando "nano" en la terminal)

nano [archivo]

## Opciones útiles

### -B
Crea copias de seguridad automáticamente.

### -l
Muestra números de línea.

### -m
Permite usar el ratón dentro del editor.

---

## Ejemplos

Crear o editar un archivo: nano notas.txt

Abrir un archivo con números de línea: nano -l script.sh

Editar creando copia de seguridad: nano -B configuracion.conf

---

## Errores y problemas comunes

#### Error:
Cerrar nano sin guardar cambios (si no lo guardas manualmente perderas todo lo que modificaste).

-Ejemplo incorrecto: nano notas.txt (Cerrar directamente la terminal o salir sin guardar)

#### Solución:
Guardar utilizando CTRL + O antes de salir con CTRL + X.

-Ejemplo correcto 1: nano notas.txt CTRL + O
-Ejemplo correcto 2: CTRL + O seguido de CTRL + X (para salir del editor)
