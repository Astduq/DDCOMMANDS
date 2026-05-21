# chown

## Descripción

Se utiliza para cambiar el propietario de archivos y directorios.

Es muy utilizado en servidores y administración de sistemas Linux.

---

## Sintaxis (como se utiliza el comando "chown" en la terminal)

chown [usuario] [archivo]

## Opciones útiles

### -R
Aplica cambios de forma recursiva.

### usuario:grupo
Permite cambiar usuario y grupo al mismo tiempo.

### --reference
Copia permisos de otro archivo.

---

## Ejemplos

Cambiar propietario de un archivo: sudo chown juan archivo.txt

Cambiar usuario y grupo: sudo chown juan:usuarios archivo.txt

Cambiar permisos en carpetas: sudo chown -R juan proyectos/

---

## Errores y problemas comunes

#### Error:
Intentar cambiar propietarios sin permisos de administrador.

-Ejemplo incorrecto: chown root archivo.txt

#### Solución:
Utilizar sudo para realizar cambios administrativos.

-Ejemplo correcto 1: sudo chown root archivo.txt
-Ejemplo correcto 2: sudo chown usuario carpeta/
