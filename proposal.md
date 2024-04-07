# Propuesta TP DSW

## Grupo
### Integrantes
51654 - Aguilar, Maximiliano.<br>
50674 - Pavoni, Santiago.<br>
51821 - Sarmiento, Patricio.<br>
51534 - Salami, Tomás.


### Repositorios
* [frontend app]
* [backend app]
COMPLETAR

## Tema
### Descripción
Se desarrolla una plataforma para ofrecer información relevante a los clientes y miembros de staff respecto a los vuelos que realiza una determinada aerolínea, sumado a la posibilidad de poder realizar la compra de pasajes por medio de la misma plataforma.

### Modelo de Dominio
https://imgur.com/a/IDiH8vp

## Alcance Funcional 

### Alcance Mínimo

|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Vuelo<br>2. CRUD Cliente<br>3. CRUD Usuario<br>4. CRUD Pasaje<br>5. CRUD Staff<br>6. CRUD Tripulacion<br>7. CRUD Aeropuerto<br>8. CRUD Historial-Vuelo<br>9. CRUD Pago<br>10. CRUD Localidad|
|CRUD dependiente|1. CRUD Aeropuerto {depende de} CRUD Localidad<br> 2. CRUD Historial-Vuelo {depende de} CRUD Vuelo|
|Listado<br>+<br>detalle| 1. Listado de vuelos realizados filtrado por fecha, muestra códigodeVuelo, aerolinea, horaDespegue, horaAterrizaje y destino.<br> 2. Listado de vuelos disponibles filtrado por destino y nro pasajeros, muestra, aerolínea, fechaDespegue, horaDespegue,  precio. <br> 3.Listado de Clientes que realizaron un viaje filtadro por codigodeVuelo, muestra dni, nombre, apellido, edad, telefono, checking, cantper.|
|CUU/Epic|COMPLETAR|
