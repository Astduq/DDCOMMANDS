# curl

## Descripción

Se utiliza para transferir datos desde o hacia servidores.

Es muy utilizado para descargar contenido y probar APIs.

---

## Sintaxis (como se utiliza el comando "curl" en la terminal)

curl [dirección]

## Opciones útiles

### -O
Guarda el archivo descargado.

### -I
Muestra solo encabezados.

### -X
Permite especificar método HTTP.

---

## Ejemplos

Consultar una página web: curl google.com

Descargar un archivo: curl -O archivo.zip

Ver encabezados: curl -I google.com

---

## Errores y problemas comunes

#### Error:
No guardar correctamente los archivos descargados.

-Ejemplo incorrecto:curl archivo.zip



#### Solución:
Usar la opción -O para guardar archivos.

-Ejemplo correcto 1: curl -O archivo.zip
-Ejemplo correcto 2: wget archivo.zip
