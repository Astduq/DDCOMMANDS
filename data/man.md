# man

## Descripción

Se utiliza para abrir el manual de ayuda de comandos y programas en Linux.

Permite consultar información oficial directamente desde la terminal.

---

## Sintaxis (como se utiliza el comando "man" en la terminal)

man [comando]

## Opciones útiles

### -k
Busca comandos relacionados.

### -f
Muestra descripción corta del comando.

### -a
Muestra todas las páginas disponibles.

---

## Ejemplos

Abrir manual de ls: man ls

Buscar comandos relacionados con red: man -k network

Mostrar descripción rápida: man -f grep

---

## Errores y problemas comunes

#### Error:
No saber salir del manual.

-Ejemplo incorrecto: man ls (Quedar atrapado dentro del manual)

#### Solución:
Presionar la tecla q para salir.

-Ejemplo correcto 1: man ls
-Ejemplo correcto 2: q
