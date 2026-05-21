# ss

## Descripción

Se utiliza para mostrar conexiones y puertos de red activos.

Es una alternativa moderna y más rápida que netstat.

---

## Sintaxis (como se utiliza el comando "ss" en la terminal)

ss [opciones]

## Opciones útiles

### -t
Muestra conexiones TCP.

### -u
Muestra conexiones UDP.

### -l
Muestra puertos abiertos.

---

## Ejemplos

Mostrar conexiones activas: ss

Mostrar puertos abiertos: ss -tuln

Mostrar conexiones TCP: ss -t

---

## Errores y problemas comunes

#### Error:
No entender la información mostrada.

-Ejemplo incorrecto: ss (Demasiados datos difíciles de leer)

#### Solución:
Usar filtros y opciones específicas.

-Ejemplo correcto 1: ss -t
-Ejemplo correcto 2: ss -tuln
