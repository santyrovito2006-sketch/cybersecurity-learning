# Networking fundamentals

## TCP/IP

TCP/IP es el conjunto de protocolos utilizado para la comunicación entre dispositivos en Internet y en muchas redes privadas.

## TCP y UDP

### TCP
Es orientado a conexión y prioriza que la información llegue correctamente y en orden. Usa acknowledgements, retransmisión y control del orden de los segmentos.

### UDP
No establece una conexión previa y tiene menos control sobre la entrega. Tiene menor overhead y se usa cuando importa más la velocidad.

## DNS
DNS traduce nombres de dominio a direcciones IP. Generalmente usa UDP para consultas normales, aunque también puede utilizar TCP.

## HTTP y HTTPS
HTTP permite el intercambio de información web. HTTPS agrega cifrado mediante TLS.

- HTTP: 80
- HTTPS: 443

## ICMP
ICMP se usa para mensajes de diagnóstico y control de red. `ping` es uno de los ejemplos más conocidos.

## DMZ
Una DMZ es una zona separada que suele contener servicios accesibles desde Internet para evitar exponer directamente toda la red interna.

## VPN
Una VPN crea un canal protegido entre dos puntos. Estudié conceptos básicos de WireGuard e IPsec.

## CIDR
CIDR indica qué parte de una dirección IP representa la red. Por ejemplo, `192.168.1.0/24` usa 24 bits para la red y 8 bits para hosts.
