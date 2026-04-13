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

El proyecto consiste en la creación de un sistema pensado para la administración de edificios.Se piensa tanto para el administrador de consorcio como para los habitantes del edificio (Propietarios, inquilinos, etc.), como para el personal de manteniminto. El sistema permitirá gestionar el uso y mantenimiento de áreas comunes, pago y liquidación de expensas, reporte de incidentes y notificación de vencimientos.

### Modelo

![imagen del modelo](tp\Modelo_TP_DSW_2026.png)

## Alcance Funcional

### Alcance Mínimo

_Nota_: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD HOA<br>2. CRUD City<br>3. CRUD User|4. CRUD Unit_Type|5. CRUD Unit
|CRUD dependiente|1. CRUD Unit_HOA {depende de} HOA, Unit<br>2. CRUD Cliente {depende de} CRUD Localidad|
|Listado<br>+<br>detalle| 1. Listado de habitaciones filtrado por tipo de habitación, muestra nro y tipo de habitación => detalle CRUD Habitacion<br> 2. Listado de reservas filtrado por rango de fecha, muestra nro de habitación, fecha inicio y fin estadía, estado y nombre del cliente => detalle muestra datos completos de la reserva y del cliente|
|CUU/Epic|1. Reportar Incidentes<br>2. Reservar espacios comunes|

Adicionales para Aprobación

### Alcance Adicional Voluntario

_Nota_: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.
