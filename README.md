## Universidad EAFIT
## Ing. de Sistemas
### Edwin Montoya - emontoya@eafit.edu.co

# App de carga de imagenes para Jmeter test

* Hace file upload desde una pagina web.
* Deja los archivos en dir upload/

## Tener en cuenta para correr app en Linux Centos:

* Abrir el puerto de la app, por default es 3456, pero puede cambiarlo en "server.js"

>     user1@dca236$ sudo firewall-cmd --zone=public --add-port=3456/tcp --permanent
>     user1@dca236$ sudo firewall-cmd --reload
