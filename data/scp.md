# scp

## Descripción

Se utiliza para copiar archivos entre equipos mediante SSH.

Permite transferir archivos de forma segura a través de la red.

---

## Sintaxis (como se utiliza el comando "scp" en la terminal)

scp [archivo] [usuario@ip:ruta]

## Opciones útiles

### -r
Copia directorios completos.

### -P
Permite usar otro puerto SSH.

### -i
Permite usar clave privada.

---

## Ejemplos

Copiar archivo a otro equipo: scp archivo.txt usuario@192.168.1.10:/home/usuario

Copiar carpeta completa: scp -r proyectos usuario@192.168.1.10:/home/usuario

Usar puerto personalizado: scp -P 2222 archivo.txt usuario@192.168.1.10:/home/usuario

---

## Errores y problemas comunes

#### Error:
No tener permisos sobre la ruta destino.

-Ejemplo incorrecto: scp archivo.txt usuario@192.168.1.10:/root

#### Solución:
Copiar archivos a rutas permitidas para el usuario.

-Ejemplo correcto 1: scp archivo.txt usuario@192.168.1.10:/home/usuario
-Ejemplo correcto 2: scp -r carpeta usuario@192.168.1.10:/tmp
