# Clase 13

## Protocolos

![protocolos](tcp_ip.png)

### UDP -> User Datagram Protocol -> Protocolo de datagramas de usuario

[Permite el envío de datagramas a través de la red sin que se haya establecido previamente una conexión, ya que el propio datagrama incorpora suficiente información de direccionamiento en su cabecera. Tampoco tiene confirmación ni control de flujo, por lo que los paquetes pueden adelantarse unos a otros; y tampoco se sabe si ha llegado correctamente, ya que no hay confirmación de entrega o recepción.]

### TCP

![TCP](tcp.png)

[TCP da soporte a muchas de las aplicaciones más populares de Internet (navegadores, intercambio de ficheros, clientes FTP, etc.) y protocolos de aplicación HTTP, SMTP, SSH y FTP.]

### IP

![IP](ip.png)

Los datos se transfieren mediante paquetes conmutados.
Este protocolo se encargará de buscar el mejor método de enrutamiento, no garantiza alcanzar el destino final.

### DHCP 

![DHCP](dhcp.png)

[Es un protocolo de red de tipo cliente/servidor mediante el cual un servidor DHCP asigna dinámicamente una dirección IP y otros parámetros de configuración de red a cada dispositivo en una red para que puedan comunicarse con otras redes IP. Este servidor posee una lista de direcciones IP dinámicas y las va asignando a los clientes conforme estas van quedando libres.]

### HTTP Y HTTPS -> Hypertext Transfer Protocol -> Protocolo de transferencia de hypertexto

Orientado a transacciones, sigue el esquema petición-respuesta entre un cliente y un servidor.
Es algo inseguro.

[Permite las transferencias de información a través de archivos (XHML, HTML . . .) en la World Wide Web.]

### DNS -> Domain Name System -> Sistema de nombres de dominio

Su función es traducir los nombres de los dominios "youtube.com" en identificadores binarios.

### FTP ->  File Transfer Protocol -> Protocolo de transferencia de archivos

[Es un protocolo de red para la transferencia de archivos entre sistemas conectados a una red TCP (Transmission Control Protocol), basado en la arquitectura cliente-servidor. Desde un equipo cliente se puede conectar a un servidor para descargar archivos desde él o para enviarle archivos, independientemente del sistema operativo utilizado en cada equipo.]