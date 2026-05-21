# sort

## Descripción

Se utiliza para ordenar líneas de texto alfabética o numéricamente.

Es muy útil para organizar información rápidamente.

---

## Sintaxis (como se utiliza el comando "sort" en la terminal)

sort [archivo]

## Opciones útiles

### -r
Ordena en orden inverso.

### -n
Ordena números correctamente.

### -u
Elimina líneas repetidas mientras ordena.

---

## Ejemplos

Ordenar un archivo: sort nombres.txt

Ordenar números: sort -n numeros.txt

Ordenar eliminando duplicados: sort -u usuarios.txt

---

## Errores y problemas comunes

#### Error:
Intentar ordenar números sin usar -n.

-Ejemplo incorrecto: sort numeros.txt (Los números se ordenarán como texto y no matemáticamente)

#### Solución:
Usar la opción -n para ordenar correctamente valores numéricos.

-Ejemplo correcto 1: sort -n numeros.txt
-Ejemplo correcto 2: sort -nr numeros.txt
