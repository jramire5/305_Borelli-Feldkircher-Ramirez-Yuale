# TP DSW: Vesta Administración de consorcios

## Grupo

### Integrantes

- 46166 - [Borelli, Hernán](https://github.com/hdborelli)
- 48706 - [Feldkircher, Valentin](https://github.com/vlnfdk)
- 51403 - [Ramirez, Juan Nicolas](https://github.com/jramire5)
- 53252 - [Yuale, Luca](https://github.com/lucayuale)

### Repositorios

- [Frontend](https://github.com/hdborelli/TP-FRONTEND)
- [Backend](https://github.com/VlnFdk/TP-BACKEND)

## Tema

### Descripción

El proyecto consiste en un sistema orientado a la administración de edificios, diseñado tanto para administradores de consorcios como para los habitantes (propietarios e inquilinos) y el personal de mantenimiento.

La plataforma permitirá gestionar la reserva de áreas comunes, el reporte y seguimiento de incidencias, la administración de empleados y la gestión de edificios y unidades.

### Modelo
- [Link al DrawIO](https://drive.google.com/file/d/17G7TQw0CAH9kGfG2kJk2CU70XJ0VoKV7/view?usp=sharing)

  <img width="1579" height="824" alt="image" src="https://github.com/user-attachments/assets/ed1e0c30-931d-45f1-819e-423c285817c3" />

## Alcance Funcional

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD EDIFICIO<br>2. CRUD PROPIEDAD<br>3. CRUD USUARIO<br>4. CRUD ADMINISTRACIÓN|
|CRUD dependiente|1. CRUD incidencia {depende de} UNIDAD y USUARIO<br>2. CRUD reservacion {depende de} AREA_COMUN y USUARIO|
|Listado<br>+<br>detalle| 1. Listado de INCIDENCIAS filtrado por USUARIO, muestra id, estado y descripcion de la incidencia, y nombre y apellido del usuario => detalle CRUD INCIDENCIA<br> 2. Listado de reservas filtrado por rango de fecha, muestra descripcion e id de unidad, fecha de reservacion, estado => detalle muestra datos completos de la reserva y del usuario|
|CUU/Epic|1. Reportar Incidentes<br>2. Reservar espacios comunes|

Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. <br>2. <br>3. <br>4. <br>5. <br>6. <br>7. |
|CUU/Epic|1. <br>2. <br>3. |


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. <br>2. |
|CUU/Epic|1. <br>2. |
|Otros|1. |
