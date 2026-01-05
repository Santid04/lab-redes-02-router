# Lab 2 – Comunicación entre redes con router

## Descripción
Este laboratorio simula una red de oficina compuesta por dos subredes distintas conectadas mediante un router Cisco, permitiendo la comunicación entre equipos que pertenecen a diferentes redes.

## Topología
- 1 Router Cisco
- 1 Switch
- 2 PCs (una por cada red)

## Direccionamiento IP

### Red A
- PC-A: 192.168.1.10 / 255.255.255.0
- Gateway: 192.168.1.1

### Red B
- PC-B: 192.168.2.10 / 255.255.255.0
- Gateway: 192.168.2.1

### Router
- GigabitEthernet0/0: 192.168.1.1 / 255.255.255.0
- GigabitEthernet0/1: 192.168.2.1 / 255.255.255.0

## Configuración del router
Se configuraron las interfaces del router con direccionamiento IPv4 estático y se habilitaron mediante el comando `no shutdown`.

## Pruebas de conectividad
Se verificó la comunicación entre las dos redes utilizando el comando `ping`, obteniendo respuesta exitosa entre los equipos.

## Archivos incluidos
- Archivo `.pkt` del laboratorio
- Captura de la topología
- Captura de las pruebas de conectividad
