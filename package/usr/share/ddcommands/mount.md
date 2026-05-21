# mount

## Descripción

Se utiliza para montar dispositivos y sistemas de archivos en Linux.

Permite acceder a discos, USB y particiones.

---

## Sintaxis (como se utiliza el comando "mount" en la terminal)

mount [dispositivo] [ruta]

## Opciones útiles

### -t
Especifica tipo de sistema de archivos.

### -o
Permite usar opciones avanzadas.

### -a
Monta todos los sistemas definidos en fstab.

---

## Ejemplos

Montar una partición: sudo mount /dev/sdb1 /mnt

Montar USB: sudo mount /dev/sdc1 /media/usb

Montar usando tipo específico: sudo mount -t ext4 /dev/sdb1 /mnt

---

## Errores y problemas comunes

#### Error:
Intentar montar rutas inexistentes.

-Ejemplo incorrecto: sudo mount /dev/sdb1 /usb

#### Solución:
Crear primero el punto de montaje.

-Ejemplo correcto 1: sudo mkdir /usb
-Ejemplo correcto 2: sudo mount /dev/sdb1 /usb
