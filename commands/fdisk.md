# fdisk

## Descripción

Se utiliza para administrar particiones de discos en Linux.

Permite crear, eliminar y modificar particiones.

---

## Sintaxis (como se utiliza el comando "fdisk" en la terminal)

fdisk [disco]

## Opciones útiles

### -l
Muestra discos y particiones.

### -x
Muestra información detallada.

### -u
Muestra sectores y tamaños.

---

## Ejemplos

Ver discos disponibles: sudo fdisk -l

Administrar un disco: sudo fdisk /dev/sdb

Mostrar información detallada: sudo fdisk -x /dev/sdb

---

## Errores y problemas comunes

#### Error:
Modificar el disco incorrecto.

-Ejemplo incorrecto: sudo fdisk /dev/sda (Modificar el disco principal accidentalmente)

#### Solución:
Identificar correctamente los discos antes de trabajar.

-Ejemplo correcto 1: lsblk
-Ejemplo correcto 2: sudo fdisk -l
