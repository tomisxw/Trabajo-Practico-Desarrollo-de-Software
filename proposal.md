# Propuesta TP DSW

## Grupo
### Integrantes
51654 - Aguilar, Maximiliano.<br>
50674 - Pavoni, Santiago.<br>
51821 - Sarmiento, Patricio.<br>
51534 - Salami, Tomás.

## Tema
### Descripción
Se desarrolla una plataforma para ofrecer información relevante a los clientes y miembros de staff respecto a los vuelos que realiza una determinada aerolínea, sumado a la posibilidad de poder realizar la compra de pasajes por medio de la misma plataforma.

### Modelo de Dominio
https://imgur.com/a/IDiH8vp

## Alcance Funcional 

|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Vuelo<br>2. CRUD Cliente<br>3. CRUD Usuario<br>4. CRUD Pasaje<br>5. CRUD Staff<br>6. CRUD Tripulacion<br>7. CRUD Aeropuerto<br>8. CRUD Historial-Vuelo<br>9. CRUD Pago<br>10. CRUD Localidad|
|CRUD dependiente|1. CRUD Pago {depende de} CRUD Pasaje<br> 2. CRUD Historial-Vuelo {depende de} CRUD Vuelo|
|Listado<br>+<br>detalle| 1. Listado de vuelos realizados filtrado por fecha, muestra códigodeVuelo, aerolinea, horaDespegue, horaAterrizaje y destino.<br> 2. Listado de vuelos disponibles filtrado por destino y nro pasajeros, muestra, aerolínea, fechaDespegue, horaDespegue,  precio. <br> 3.Listado de Clientes que realizaron un viaje filtrado por codigodeVuelo, muestra dni, nombre, apellido, edad, telefono, email.|
|CUU/Epic|1.Sacar pasaje para un vuelo.<br>2.Registrar usuario.<br>3.Cargar datos del cliente. <br>4.Carga de vuelos.<br>5.Consultar historial de vuelo.<br>6.Cargar nuevos aeropuertos.<br>7.Registrar tripulación de un vuelo.<br>8.Realizar el pago del pasaje.<br>9.Dar de baja un vuelo.<br>10.Cancelar un vuelo.|

## CRUD para desarrollar en la siguiente entrega

Sacar pasaje para un vuelo.

