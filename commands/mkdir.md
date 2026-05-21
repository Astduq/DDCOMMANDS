# mkdir

## Descripción

Se utiliza para crear directorios/carpetas dentro del sistema.

---

## Sintaxis (como se utiliza el comando "mkdir" en la terminal)

mkdir [nombre_del_directorio]

---

## Opciones útiles

### -p
Permite crear varias carpetas dentro de una misma ruta aunque algunas no existan.

### -v
Muestra un mensaje indicando las carpetas que se van creando.

---

## Ejemplos

Crear una carpeta: mkdir pruebas

Crear varias carpetas dentro de una ruta: mkdir -p proyectos/linux/prueba

Mostrar las carpetas creadas: mkdir -v documentos

---

## Errores y problemas comunes

#### Error:
Intentar crear una carpeta que ya existe.

-Ejemplo incorrecto: mkdir Documentos

#### Solución:
Utilizar otro nombre o usar la opción "-p" si corresponde.

-Ejemplo correcto 1: mkdir documentos2
-Ejemplo correcto 2: mkdir -p documentos
