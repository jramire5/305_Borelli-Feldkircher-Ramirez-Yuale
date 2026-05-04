# Propuesta TP DSW

## Grupo

### Integrantes

- 46166 - [Borelli, Hernán](https://github.com/hdborelli)
- 48706 - [Feldkircher, Valentin](https://github.com/vlnfdk)
- 51403 - [Ramirez, Juan Nicolas](https://github.com/jramire5)
- 53252 - [Yuale, Luca](https://github.com/lucayuale)

### Repositorios

- [frontend app](Falta crear)
- [backend app](Falta Crear)

## Tema

### Descripción

El proyecto consiste en un sistema orientado a la administración de edificios, diseñado tanto para administradores de consorcios como para los habitantes (propietarios e inquilinos) y el personal de mantenimiento.

La plataforma permitirá gestionar el uso y mantenimiento de áreas comunes, la reserva de espacios compartidos, el reporte y seguimiento de incidencias y la administración de empleados.

### Modelo
- [Link al DrawIO](https://drive.google.com/file/d/17G7TQw0CAH9kGfG2kJk2CU70XJ0VoKV7/view?usp=sharing)

- [Imagen del modelo]<img width="1274" height="697" alt="Modelo_TP_DSW_2026-Página-1 drawio" src="https://github.com/user-attachments/assets/33f994e2-c742-4ab4-8605-68d35d84035d" />

## Alcance Funcional

### Alcance Mínimo

_Nota_: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD EDIFICIO<br>2. CRUD UNIDAD<br>3. CRUD USUARIO<br>4. CRUD ROL|
|CRUD dependiente|1. CRUD unidad_edificio {depende de} EDIFICIO y UNIDAD<br>2. CRUD admin_edificio {depende de} ADMINISTRACION y EDIFICIO|
|Listado<br>+<br>detalle| 1. Listado de INCIDENCIAS filtrado por USUARIO, muestra id, estado y descripcion de la incidencia, y nombre y apellido del usuario => detalle CRUD INCIDENCIA<br> 2. Listado de reservas filtrado por rango de fecha, muestra nro de habitación, fecha inicio y fin estadía, estado y nombre del cliente => detalle muestra datos completos de la reserva y del cliente|
|CUU/Epic|1. Reportar Incidentes<br>2. Reservar espacios comunes|

Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad<br>4. CRUD Provincia<br>5. CRUD Habitación<br>6. CRUD Empleado<br>7. CRUD Cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva<br>3. Realizar el check-out y facturación de estadía y servicios|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio de reserva por email|
