## SE REALIZO LA SIGUIENTE SECUENCIA DE PASOS:

```
1.- Se creo 3 instancias de base de datos postgres una para cada microservicio
2.- Se creo un docker-compose en la raiz para unificar las bases de datos, nats y lo microservicios en una misma red haci hacer mas dinamico el trabajo
3.- Se configuro una imagen docker para nats para hacer la comunicacion mediante NATS con cada microservicios
4.- Se configuro el cliente-gateway en el docker compose para poder levantarlo en la misma red
5.- Se configuro el microservicio productos en el docker compose
6.- Se configuro el microservicio orders en el docker compose
7.- Se configuro el microservicio de aUTH en el docker compose
```

```

```