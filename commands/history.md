# history

## Descripción

Se utiliza para mostrar el historial de comandos ejecutados en la terminal.

Es útil para recordar comandos usados anteriormente.

---

## Sintaxis (como se utiliza el comando "history" en la terminal)

history

## Opciones útiles

### -c
Borra el historial.

### número
Limita cantidad de resultados.

### !!
Ejecuta el último comando nuevamente.

---

## Ejemplos

Mostrar historial: history

Mostrar últimos 10 comandos: history 10

Repetir último comando: !!

---

## Errores y problemas comunes

#### Error:
Eliminar accidentalmente el historial utilizando la opcion incorrecta.

-Ejemplo incorrecto: history -c

#### Solución:
Usar la opción solo cuando hayas guardado o no necesites mas el history.

-Ejemplo correcto 1: history > historial.txt (Lo guarda en un .txt)
-Ejemplo correcto 2: history -c
