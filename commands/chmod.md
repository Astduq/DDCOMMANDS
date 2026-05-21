# chmod

## Descripción

Se utiliza para cambiar los permisos de archivos y directorios.

Permite controlar quién puede leer, modificar o ejecutar un archivo dentro del sistema.

---

## Sintaxis (como se utiliza el comando "chmod" en la terminal)

chmod [permisos] [archivo]

## Opciones útiles

### -R
Aplica cambios de forma recursiva en carpetas.

### +x
Añade permisos de ejecución.

### 777
Otorga todos los permisos (usar con cuidado).

---

## Ejemplos

Dar permisos de ejecución: chmod +x script.sh

Cambiar permisos de una carpeta completa: chmod -R 755 proyectos/

Dar permisos totales: chmod 777 archivo.txt

---

## Errores y problemas comunes

#### Error:
Asignar permisos poco seguros y excesivos.

-Ejemplo incorrecto: chmod 777 sistema.txt

#### Solución:
Utilizar únicamente los permisos necesarios.

-Ejemplo correcto 1: chmod 755 script.sh
-Ejemplo correcto 2: chmod 644 documento.txt
