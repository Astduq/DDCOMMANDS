# ifconfig

## Descripción

Se utiliza para mostrar y configurar interfaces de red.

Actualmente está considerado un comando antiguo en muchas distribuciones, siendo reemplazado por ip.

---

## Sintaxis (como se utiliza el comando "ifconfig" en la terminal)

ifconfig

## Opciones útiles

### up
Activa una interfaz.

### down
Desactiva una interfaz.

### -a
Muestra todas las interfaces.

---

## Ejemplos

Ver interfaces de red: ifconfig

Activar interfaz: sudo ifconfig eth0 up

Desactivar interfaz: sudo ifconfig eth0 down

---

## Errores y problemas comunes

#### Error:
El sistema no reconoce el comando.

-Ejemplo incorrecto: ifconfig (command not found, ya que en muchas distribuciones no viene preinstalado)

#### Solución:
Instalar net-tools o utilizar ip.

-Ejemplo correcto 1: sudo apt install net-tools
-Ejemplo correcto 2: ip a
