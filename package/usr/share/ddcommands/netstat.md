# netstat

## Descripción

Se utiliza para mostrar conexiones de red, puertos y estadísticas del sistema.

Es muy útil para diagnóstico y administración de redes.

---

## Sintaxis (como se utiliza el comando "netstat" en la terminal)

netstat [opciones]

## Opciones útiles

### -t
Muestra conexiones TCP.

### -u
Muestra conexiones UDP.

### -l
Muestra puertos en escucha.

---

## Ejemplos

Mostrar conexiones activas: netstat

Ver puertos abiertos: netstat -tuln

Mostrar estadísticas: netstat -s

---

## Errores y problemas comunes

#### Error:
No encontrar el comando preinstalado.

-Ejemplo incorrecto: netstat (command not found)

#### Solución:
Instalar net-tools o usar ss.

-Ejemplo correcto 1: sudo apt install net-tools
-Ejemplo correcto 2: ss -tuln
