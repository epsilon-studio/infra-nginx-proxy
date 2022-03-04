# Nginx Proxy

Implementacion de un sencillo proxy para aplicaciones web.

Basadado en la imagen de docker del popular servidor web Nginx.

## Propuesta

La idea es simple, configurar un punto comun por donde ingreses las peticiones de la aplicacion para luego estas redireccionarse a la direccion o ip de la aplicacion web.

## Posibles escenarios

Los escenarios pueden ser variados pero explicaremos los mas comunes:

- Multiples aplicaciones en una subcarpeta separada.

Esto es bien comun cuando se tiene un solo dominio web, las direcciones quedan de la siguiente forma: http://dominio.com/aplicacion01 y http://dominio.com/aplicacion02

- Un solo servidor publico y ocultar los servidores donde ejecutan las aplicaciones.

Este escenario es comun cuando se tiene un solo servicio expuesto por internet, pero los demas servicios no se desean exponer directamente.

<br/>
<center>
<img align="center" width="100%" src="assets/nginx-epsilon-min.png"> 
</center>
<br/><br/>
### Copyright

[Nginx , Docker office image ](https://hub.docker.com/_/nginx)
