# systemctl

## Descripción

Se utiliza para administrar servicios y procesos del sistema en Linux.

Permite iniciar, detener, reiniciar y comprobar servicios.

---

## Sintaxis (como se utiliza el comando "systemctl" en la terminal)

systemctl [acción] [servicio]

## Opciones útiles

### start
Inicia un servicio.

### stop
Detiene un servicio.

### status
Muestra el estado del servicio.

---

## Ejemplos

Ver estado de Apache: systemctl status apache2

Iniciar un servicio: sudo systemctl start apache2

Reiniciar un servicio: sudo systemctl restart apache2

---

## Errores y problemas comunes

#### Error:
Intentar administrar servicios sin permisos sudo.

-Ejemplo incorrecto: systemctl restart apache2

#### Solución:
Usar sudo para administrar servicios.

-Ejemplo correcto 1: sudo systemctl restart apache2
-Ejemplo correcto 2: sudo systemctl status apache2
