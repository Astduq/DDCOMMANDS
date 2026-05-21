# ping

## Descripción

Se utiliza para comprobar la conectividad entre equipos dentro de una red.

Permite verificar si un servidor, router o página web responde correctamente.

---

## Sintaxis (como se utiliza el comando "ping" en la terminal)

ping [dirección]

## Opciones útiles

### -c
Limita la cantidad de paquetes enviados.

### -i
Define el intervalo entre paquetes.

### -s
Permite cambiar el tamaño de los paquetes.

---

## Ejemplos

Comprobar conexión con Google (muy util para comprobar DNS): ping google.com

Enviar solo 4 paquetes: ping -c 4 google.com

Comprobar conexión con otra IP: ping 192.168.1.1

---

## Errores y problemas comunes

#### Error:
El comando no termina automáticamente.

-Ejemplo incorrecto: ping google.com (El comando continará ejecutándose indefinidamente)

#### Solución:
Detener el proceso manualmente con CTRL + C o limitar paquetes.

-Ejemplo correcto 1: ping -c 4 google.com
-Ejemplo correcto 2: CTRL + C
