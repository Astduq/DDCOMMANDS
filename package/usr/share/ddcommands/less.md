# less

## Descripción

Se utiliza para leer archivos largos página por página desde la terminal.

A diferencia de cat, permite desplazarse cómodamente usando las flechas del teclado.

Es muy útil para leer logs o archivos extensos.

---

## Sintaxis (como se utiliza el comando "less" en la terminal)

less [archivo]

## Opciones útiles

### -N
Muestra números de línea.

### -S
Evita que las líneas largas se dividan visualmente.

### +F
Permite seguir archivos en tiempo real (similar a tail -f).

---

## Ejemplos

Leer un archivo largo: less registros.txt

Mostrar líneas numeradas: less -N notas.txt

Leer logs en tiempo real: less +F servidor.log

---

## Errores y problemas comunes

#### Error:
No saber cómo salir del comando.

-Ejemplo incorrecto: less notas.txt (El usuario queda "atrapado" dentro del visor sin poder salir)

#### Solución:
Presionar la tecla q para salir.

-Ejemplo correcto 1: less notas.txt
-Ejemplo correcto 2: q
