# dpkg

## Descripción

Se utiliza para instalar y administrar paquetes .deb en Linux.

Es muy útil para instalar programas descargados manualmente.

---

## Sintaxis (como se utiliza el comando "dpkg" en la terminal)

dpkg [opciones]

## Opciones útiles

### -i
Instala un paquete .deb.

### -r
Elimina paquetes instalados.

### -l
Muestra paquetes instalados.

---

## Ejemplos

Instalar paquete: sudo dpkg -i programa.deb

Eliminar paquete: sudo dpkg -r programa

Ver paquetes instalados: dpkg -l

---

## Errores y problemas comunes

#### Error:
Faltan dependencias después de instalar un paquete.

-Ejemplo incorrecto: sudo dpkg -i programa.deb (Error de dependencias)

#### Solución:
Corregir dependencias con apt.

-Ejemplo correcto 1: sudo apt --fix-broken install
-Ejemplo correcto 2: sudo dpkg -i programa.deb
