# lsblk

## Descripción

Se utiliza para mostrar discos, particiones y dispositivos de almacenamiento conectados al sistema.

Es muy útil para identificar discos duros y memorias USB.

---

## Sintaxis (como se utiliza el comando "lsblk" en la terminal)

lsblk [opciones]

## Opciones útiles

### -f
Muestra sistemas de archivos.

### -a
Muestra dispositivos vacíos.

### -o
Permite elegir columnas específicas.

---

## Ejemplos

Mostrar discos y particiones: lsblk

Mostrar sistemas de archivos: lsblk -f

Mostrar columnas específicas: lsblk -o NAME,SIZE,FSTYPE

---

## Errores y problemas comunes

#### Error:
Confundir discos completos con particiones.

-Ejemplo incorrecto: sudo mount /dev/sda /mnt

#### Solución:
Montar siempre la partición correcta.

-Ejemplo correcto 1: lsblk
-Ejemplo correcto 2: sudo mount /dev/sda1 /mnt
