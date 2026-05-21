# mv

## Descripción

Se utiliza para mover archivos/directorios o cambiarles el nombre.

---

## Sintaxis (como se utiliza el comando "mv" en la terminal)

mv [archivo] [destino]

---

## Opciones útiles

### -i
Pide confirmación antes de sobrescribir archivos.

### -v
Muestra detalles del movimiento realizado.

### -n
Evita sobrescribir archivos existentes.

---

## Ejemplos

Mover archivo: mv prueba.txt documentos/

Cambiar nombre: mv archivo.txt nuevo.txt

Mover mostrando detalles: mv -v archivo.txt backup/

---

## Errores y problemas comunes

#### Error:
Mover archivos a una ruta inexistente.

-Ejemplo incorrecto: mv prueba.txt carpeta/

#### Solución:
Verificar que el directorio exista antes de mover archivos.

-Ejemplo correcto 1: mkdir carpeta
-Ejemplo correcto 2: mv prueba.txt carpeta/
