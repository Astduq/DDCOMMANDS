# cut

## Descripción

Se utiliza para extraer partes específicas de un texto o archivo.

Es muy útil para trabajar con columnas o datos separados por símbolos.

---

## Sintaxis (como se utiliza el comando "cut" en la terminal)

cut [opciones] [archivo]

## Opciones útiles

### -d
Permite indicar el separador de columnas.

### -f
Selecciona qué campo o columna mostrar.

### -c
Selecciona caracteres específicos.

---

## Ejemplos

Mostrar primera columna: cut -d ":" -f1 usuarios.txt

Mostrar varios campos: cut -d ":" -f1,3 usuarios.txt

Mostrar caracteres específicos: cut -c1-5 texto.txt

---

## Errores y problemas comunes

#### Error:
No indicar correctamente el separador.

-Ejemplo incorrecto: cut -f1 usuarios.txt (El comando no sabe cómo dividir las columnas)

#### Solución:
Usar -d para especificar el separador correcto.

-Ejemplo correcto 1: cut -d ":" -f1 usuarios.txt
-Ejemplo correcto 2: cut -d "," -f2 datos.csv
