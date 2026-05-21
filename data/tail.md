# tail

## Descripción

Se utiliza para mostrar las últimas líneas de un archivo.

Es muy utilizado para monitorear logs (registros) y archivos que cambian o se actualizan constantemente.

---

## Sintaxis (como se utiliza el comando "tail" en la terminal)

tail [archivo]

## Opciones útiles

### -n
Permite indicar cuántas líneas mostrar.

### -f
Actualiza el contenido en tiempo real.

### -q
Oculta nombres de archivos.

---

## Ejemplos

Mostrar últimas líneas: tail registros.txt

Mostrar últimas 20 líneas: tail -n 20 servidor.log

Monitorear logs en tiempo real: tail -f servidor.log

---

## Errores y problemas comunes

#### Error:
No saber cómo detener el modo en tiempo real (-f).

-Ejemplo incorrecto: tail -f servidor.log (El comando nunca termina por sí solo)

#### Solución:
Presionar CTRL + C para detener el proceso.

-Ejemplo correcto 1: tail -f servidor.log
-Ejemplo correcto 2: CTRL + C
