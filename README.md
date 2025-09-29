# Redes_19_Final
Entrega Final TP 19 Redes - Santino D'Acunti 5to 1ra

Escáner de Red + Netstat – TP Redes 5to Año

=
INFORMACIÓN GENERAL
=

Este proyecto consiste en un escáner de red y un módulo adicional de Netstat desarrollado en Java con interfaz gráfica (GUI).

Escáner de Red
--------------
Permite detectar qué dispositivos están activos dentro de un rango de direcciones IP en una red local, utilizando comandos del sistema como ping y nslookup.

- Tiene interfaz gráfica completa
- Permite ingresar IP de inicio y fin
- Verifica si las IPs están bien escritas
- Realiza el escaneo dentro de un rango definido
- Muestra resultados en tabla (IP, nombre, estado, tiempo de respuesta)
- Puede guardar resultados en archivo de texto
- Incluye barra de progreso
- Incluye filtros (texto y estado) para buscar resultados en la tabla

Netstat
-----------------------
El proyecto incluye un módulo de Netstat mejorado que permite ejecutar el comando con diferentes modificadores seleccionables por el usuario.

- Permite elegir entre tres comandos distintos:
  - `-a` → muestra todas las conexiones y puertos en escucha
  - `-n` → muestra direcciones en formato numérico
  - `-o` → muestra el PID asociado a cada conexión
- Tiene interfaz gráfica con combo de selección y botón de ejecución
- Muestra los resultados en un área de texto con scroll
- Permite analizar conexiones activas, puertos abiertos y procesos asociados

=
REQUISITOS RECOMENDADOS
=

- Java JDK 8 o superior
- Eclipse IDE
- Sistema operativo Windows (para compatibilidad con comandos ping y netstat)
- Acceso a una red local

=
CÓMO USAR EL PROGRAMA
=

Menú Principal
--------------
1. Al iniciar el programa, se abrirá el menú principal.
2. Desde allí, seleccionar si desea abrir el módulo **Escáner de Red** o **Netstat**.

Escáner de Red
--------------
1. Desde el menú principal, presionar el botón **"Abrir Escáner de Red"**.
2. Ingresar una dirección IP de inicio (por ejemplo: `192.168.0.1`).
3. Ingresar una dirección IP de fin (por ejemplo: `192.168.0.10`).
4. Presionar el botón **"Escanear"**.
5. Esperar a que se complete la barra de progreso.
6. (Opcional) Presionar **"Guardar"** para exportar los resultados.
7. (Opcional) Usar el botón **"Limpiar"** para borrar los campos y la tabla.
8. (Opcional) Usar los filtros de texto y estado para refinar los resultados.

Netstat
-----------------------
1. Desde el menú principal, presionar el botón **"Abrir Netstat"**.
2. En la ventana de Netstat, seleccionar el comando que desea ejecutar:
   - `-a` para mostrar todas las conexiones y puertos.
   - `-n` para ver las direcciones en formato numérico.
   - `-o` para visualizar el PID de los procesos.
3. Presionar el botón **"Ejecutar Netstat"**.
4. Los resultados se mostrarán en un área de texto con scroll.

=
Alumno
=

Santino D'Acunti
