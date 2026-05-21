# vim

## Descripción

Se utiliza para editar archivos de texto desde la terminal.

Es un editor mucho más avanzado y potente que nano, aunque también más difícil de aprender al principio.

---

## Sintaxis (como se utiliza el comando "vim" en la terminal)

vim [archivo]

## Opciones útiles

### -R
Abre el archivo en modo solo lectura.

### -u
Permite usar un archivo de configuración específico.

### -y
Inicia vim en modo fácil (más cómodo para principiantes).

---

## Ejemplos

Editar un archivo: vim notas.txt

Abrir en solo lectura: vim -R archivo.txt

Abrir en modo fácil: vim -y practica.txt

---

## Errores y problemas comunes

#### Error:
No saber cómo salir de vim.

-Ejemplo incorrecto: vim archivo.txt (El usuario no logra cerrar el editor y tiene que cerrar abruptamente la terminal para salir)

#### Solución:
Presionar ESC y escribir :q para salir o :wq para guardar y salir.

-Ejemplo correcto 1: :q
-Ejemplo correcto 2: :wq
