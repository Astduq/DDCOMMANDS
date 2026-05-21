# df

## Descripción

Se utiliza para mostrar el espacio disponible y utilizado en discos y particiones.

Es muy útil para comprobar almacenamiento en servidores y sistemas Linux.

---

## Sintaxis (como se utiliza el comando "df" en la terminal)

df [opciones]

## Opciones útiles

### -h
Muestra tamaños facilmente legibles.

### -T
Muestra tipo de sistema de archivos.

### -a
Muestra todos los sistemas de archivos.

---

## Ejemplos

Ver espacio de discos: df

Mostrar tamaños legibles: df -h

Ver tipos de sistemas: df -T

---

## Errores y problemas comunes

#### Error:
No entender tamaños mostrados.

-Ejemplo incorrecto: df (Tamaños difíciles de interpretar)

#### Solución:
Usar la opción -h para mayor legibilidad.

-Ejemplo correcto 1: df -h
-Ejemplo correcto 2: df -Th
