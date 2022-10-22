# Glosario FRONTEND

## Fundamentos de internet 

### Direcciones IP

Son asignadas a cada dispositivo en Internet para identificarse y permite a otros dispositivos encontrar a otros. Estas direcciones toman la forma de #.#.#.#.#, donde cada # es un número en el rango de 0 a 255. Ej: 192.228.17.57

Cuando se envía información a través de Internet, se utilizan las direcciones IP para que Internet sepa a dónde se envía la información. Parecido al envío de correo físico: la información tiene tanto una dirección de correo (hacia) como una de retorno (desde).

IP: Protocolo de Internet. 

### DHCP

Dynamic Host Configuration Protocol (protocolo de configuración dinámica del host) 
Es el responsable de asignar IP a los ordenadores.
Este lleva a cabo diferente sub procesos los cuales son:
+ Discover: Es cuando el cliente envia un mensaje (broadcast) para descubrir los servidores DHCP activos
+ Ofter: Los servidores DHCP envian un mensaje al cliente con una propuesta de configuracion
+ Request: El cliente envia un mensaje al servidor solicitado, selecciona uno
+ Ack-Nack: El servidor seleccionado devuelve un mensaje al cliente con los parametros de configuracion (ip, mascara de red y puerta de enlace).
+ Release: Cuando ya el cliente no necesita mas esa direccion IP para que el servidor la libere.

### URL

Es la direccion que se escribe como texto en el buscador para no tener que escribir la IP del sitio web. 
Ej: Google.com

### DNS

Sistema de Nombres de Dominio: Son servidores que toman URLs y las convierten de ida y vuelta a direcciones IP. Basicamente se encarga de descifrar los urls para buscarle su direccion IP.

### TCP 

Protocolo de Control de Transmision: Es otro protocolo que se encarga de garantizar la entrega de todos los paquetes de datos que se envian a traves de Internet y saber para que servicio esta destinado (navegación web, correo electrónico, etc.)

### HTTP

Protocolo de Transferencia de Hipertexto: Ayuda en la comunicacion entre los navegadores y servidores web.

### COOKIE 

Es un pequeño archivo que contiene informacion que un servidor almacena en nuestro sistema. 


## Frontend

### Definicion "Frontend"

+ A nivel basico y general un desarrollador frontend es el encargado de producir codigo HTML, CSS y JS para el lado del cliente. 

+ La principal dificultad del desarrollo web frontend reside en la rapidez en la que cambian o aparececn nuevas herramientas y tecnicas para realizar el trabajo.

+ Mantenerse al dia es un requisito indispensable.

### HTML

Es el lenguaje de marcado, la parte de las estructuras de la pagina web.

#### Hiperenlaces

Son los enlaces que te envian a otra pagina web u otra parte de la misma pagina.
Existen 2 tipos de hiperenlaces:

+ Absolutos: Estas incluyen todas las partes de la URL (protocolo, servidor y ruta).
+ Relativos: Solicitan recursos que están alojados al mismo servidor. Ej. "secciones/contacto.html" 

### CSS

Es el lenguaje de estilos, es el diseño y los estilos de la pagina web.

### Javascript

Es un lenguaje de programacion indisipensable para web que le da funcionalidad a las paginas.



