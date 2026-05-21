# find

## Descripción

Se utiliza para buscar archivos y directorios dentro del sistema.

Permite realizar búsquedas muy específicas utilizando nombres, extensiones, tamaños y otros criterios.

---

## Sintaxis (como se utiliza el comando "find" en la terminal)

find [ruta] [opciones]

---

## Opciones útiles

### -name
Busca archivos por nombre.

### -type
Permite buscar solamente archivos o directorios.

### -size
Busca archivos según su tamaño.

---

## Ejemplos

Buscar archivo: find /home -name prueba.txt

Buscar carpetas: find /home -type d

Buscar archivos grandes: find / -size +100M

---

## Errores y problemas comunes

#### Error:
Realizar búsquedas sin permisos suficientes.

-Ejemplo incorrecto: find /root -name archivo.txt

#### Solución:
Usar sudo o buscar en directorios permitidos.

-Ejemplo correcto 1: sudo find /root -name archivo.txt
-Ejemplo correcto 2: find /home -name archivo.txt
