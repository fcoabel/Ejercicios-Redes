# EJERCICIO DE RED PARA EMPRESA

En este ejercicio se realizará la estructura y la configuración de una red para una empresa ficticia.

Esta pequeña empresa se dedica al suministro de recambios y materiales de trabajo para talleres industriales. Dicha empresa estará formada por dos departamentos los cuales serán: el departamento de oficinas y el departamento de ventas.

---

## Departamento de oficinas.

En este departamento tendremos cuatro ordenadores, un servidor HTTP, un servidor DNS y un servidor DHCP.

La configuración de las Ips  para los ordenadores de la oficina las dará el servidor DHCP.



### IPs Departamento de oficinas

La red general para los ordenadores de la oficina es la 192.168.83.0.

Los servidores están físicamente en la oficina pero usarán otra red.

El nombre de los ordenadores viene dado por la O de Oficina y un número del 1 al 4.



## Servidores

El servidor DNS tiene la Ip 192.168.145.2

El servidor HTTP mostrará una sencilla pagina web sobre la empresa, tiene la Ip 192.168.145.3



## Departamento de ventas.

En el departamento de ventas tenemos seis ordenadores con Ips estáticas. El nombre de los ordenadores del departamento de ventas viene dado por V de Ventas y un número del 1 al 6.



### IPs Departamento de Ventas

La red general del departamento será la 192.168.137.0.

V1: 192.168.137.11

V2: 192.168.137.12

V3: 192.168.137.13

V4: 192.168.137.14

V5: 192.168.137.15

V6: 192.168.137.16



## Rúters

Las direcciones Ip de los rúters son:



### Rúter Oficina

* 192.168.83.1
* 10.0.0.2
* 10.1.0.1



### Rúter Ventas

* 192.168.137.1

* 10.1.0.2

  

### Rúter Servidores

* 192.168.145.1
* 10.0.0.1















