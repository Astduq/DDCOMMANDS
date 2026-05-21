# tree

## Descripción

Se utiliza para mostrar directorios y archivos en forma de árbol.

Ayuda mucho a visualizar la estructura de carpetas de manera organizada.

---

## Sintaxis (como se utiliza el comando "tree" en la terminal)

tree [ruta]

## Opciones útiles

### -L
Limita la profundidad del árbol mostrado.

### -d
Muestra únicamente directorios.

### -a
Incluye archivos ocultos.

---

## Ejemplos

Mostrar estructura actual: tree

Mostrar solo carpetas: tree -d

Limitar profundidad: tree -L 2

---

## Errores y problemas comunes

#### Error:
Intentar usar el comando sin tenerlo instalado (sucede mucho en vms) o confundirlo con el 3 en ingles (three).

-Ejemplo incorrecto: tree 

#### Solución:
Instalar el paquete tree.

-Ejemplo correcto 1: sudo apt install tree
-Ejemplo correcto 2: tree (significa árbol)
