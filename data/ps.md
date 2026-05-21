# ps

## Descripción

Se utiliza para mostrar los procesos activos del sistema.

Permite ver programas y servicios que están ejecutándose actualmente.

---

## Sintaxis (como se utiliza el comando "ps" en la terminal)

ps [opciones]

## Opciones útiles

### aux
Muestra todos los procesos activos del sistema.

### -e
Muestra todos los procesos.

### -f
Muestra información detallada.

---

## Ejemplos

Ver procesos actuales: ps

Mostrar todos los procesos: ps aux

Mostrar procesos detallados: ps -ef

---

## Errores y problemas comunes

#### Error:
Buscar procesos manualmente entre demasiados resultados.

-Ejemplo incorrecto: ps aux

#### Solución:
Combinar el comando con grep para filtrar resultados.

-Ejemplo correcto 1: ps aux | grep firefox
-Ejemplo correcto 2: ps -ef | grep apache
