# Evaluación Módulo 3
## PROYECTO ALKE WALLET
 
**Ejercicio: Creación de una base de datos relacional para una wallet virtual** <br>

### Situación inicial 📍 <br>
 Como parte de un equipo de programadores recibiste el pedido de Alke
Wallet de desarrollar el diseño de una base de datos relacional para
gestionar un sistema de una Wallet la cual permitirá a sus usuarios
almacenar y gestionar sus fondos, realizar transacciones y ver el
historial de transacciones. Nuestro líder técnico ya cuenta con los
requerimientos desagregados en un backlog de tareas listo para que
comencemos la etapa de desarrollo<br><br>

### objetivo <br>
El objetivo de esta evaluación es diseñar el modelo conceptual, definir las
relaciones entre las entidades de una wallet y crear la base de datos para
almacenar la información que sea necesaria<br><br>

### Requerimientos<br>
La Alke Wallet deberá cumplir con una serie de características y
requerimientos técnicos para garantizar la calidad y funcionalidad de la
misma.<br>
Primero, como requerimiento general tenemos que poder implementar
todas las funcionalidades básicas que un usuario necesita para gestionar
sus fondos, realizar transacciones y ver el historial de transacciones,
las cuales son:<br>
● Diseñar una Bases de Datos que garantice la coherencia y la
integridad de los datos<br>
● Crear una conexión a una Bases de Datos llamada Alke Wallet<br>
● Crear Entidades:<br>

1. Usuario: Representa a cada usuario individual del sistema de
monedero virtual.<br>
- Atributos:<br>
user_id (clave primaria)<br>
nombre<br>
correo electrónico<br>
contraseña<br>
saldo.<br><br>
2. Transacción: Representa cada transacción financiera realizada por los
usuarios.<br>
- Atributos:<br>
transaction_id (Primary Key)<br>
sender_user_id (Foreign Key referenciando a User)<br>
receiver_user_id (Foreign Key referenciando a User)<br>
importe<br>
transaction_date.<br><br>
3. Moneda: Representa las diferentes monedas que se pueden utilizar
en el monedero virtual.<br>
- Atributos:<br>
currency_id (Primary Key)<br>
currency_name<br>
currency_symbol<br><br>

● Crear consultas SQL para:<br>
- Consulta para obtener el nombre de la moneda elegida por un
usuario específico<br>
- Consulta para obtener las transacciones realizadas por un usuario
específico<br>
- Consulta para obtener todos los usuarios registrados<br>
- Consulta para obtener todas las monedas registradas<rb>
- Consulta para obtener todas las transacciones registradas<br>
- Consulta para obtener todas las transacciones realizadas por un
usuario específico<br>
- Consulta para obtener todas las transacciones recibidas por un
usuario específico<br>
- Sentencia DML para modificar el campo correo electrónico de un
usuario específico<br>
- Sentencia para eliminar los datos de una transacción (eliminado de
la fila completa)<br>
- Sentencia para DDL modificar el nombre de la columna
correo_electronico por email<br>







