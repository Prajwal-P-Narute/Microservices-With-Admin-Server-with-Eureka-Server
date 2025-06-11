If both Admin Server and Microservices are registered in Eureka,
then Admin Server can discover all registered microservices with Eureka automatically.


in this project we are registering all microservices and admin server to the
eureka server

so admin server automatically detects microservice register with admin server

thats why here Api-gateway microservice automatically gets registered because here
api-gateway is also registered with eureka server

in admin server ui api-gateway shows as DOWN status because in api-gateway
microservice we have not added admin-client but it registered with eureka
