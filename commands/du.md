# du

## Descripción

Se utiliza para calcular el espacio ocupado por archivos y carpetas.

Es útil para localizar directorios que consumen mucho almacenamiento.

---

## Sintaxis (como se utiliza el comando "du" en la terminal)

du [ruta]

## Opciones útiles

### -h
Muestra tamaños legibles.

### -s
Muestra solo el total.

### -a
Incluye archivos individuales.

---

## Ejemplos

Ver tamaño de una carpeta: du documentos/

Mostrar tamaños legibles: du -h documentos/

Mostrar tamaño total: du -sh documentos/

---

## Errores y problemas comunes

#### Error:
Generar demasiada información en carpetas grandes.

-Ejemplo incorrecto: du /

#### Solución:
Limitar resultados o usar resúmenes.

-Ejemplo correcto 1: du -sh /home
-Ejemplo correcto 2: du -h documentos/
