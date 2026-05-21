# ls

## Descripción

Se utiliza para listar/mostrar los elementos contenidos en un directorio (carpeta)

---

## Sintaxis (como se utiliza el comando "ls" en la terminal)

ls -[opciones]

## Opciones útiles (tambien se pueden utilizar varias a la vez sin repetir el "-")

### -l
Muestra informacion detallada pero general.

### -a
Muestra los archivos ocultos dentro del directorio.

### -h 
Muestra los nombres de los archivos omitiendo cierta informacion para mayor legibilidad.

---

## Ejemplos

Mostrar archivos: ls

Mostrar detalles de dichos archivos: ls -l

Mostrar archivos ocultos con sus detalles: ls -la

---

## Errores y problemas comunes 

#### Error:
 Repetir el guión seguido uno del otro al momento de sumar opciones.

-Ejemplo incorrecto: ls -l-h-a

#### Solución:
 Simplemente utilizar un solo guión o bien separar las opciones con un espacio para evitar problemas.

-Ejemplo correcto 1: ls -lha 
-Ejemplo correcto 2: ls -l -h -a
