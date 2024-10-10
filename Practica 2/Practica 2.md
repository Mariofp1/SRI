# Práctica 2 - Instalación y Configuración de servidor DHCP en Debian

## Ejercicio 1:

1. Instalamos el servidor DHCP.
![1](/Practica%202/imagenes/1.png)
2. Configuración previa del servidor DHCP.
![2](/Practica%202/imagenes/2.png)
3. Configuramos para cumplir los requisitos pedidos.
![3](/Practica%202/imagenes/3.png)
4. Hacemos la reserva del cliente Ubuntu.
![4](/Practica%202/imagenes/4.png)
5. Reiniciamos el servidor y miramos su estado.
![5](/Practica%202/imagenes/5.png)
## Ejercicio 2:

1. Miramos la configuración de red del cliente Windows.
![6](/Practica%202/imagenes/6.png)
2. Verificamos que tenga conexión a Internet.
![7](/Practica%202/imagenes/7.png)
3. Revisamos la configuración de red del cliente Ubuntu y hacemos un ping a Windows.
![8](/Practica%202/imagenes/8.png)
4. Verificamos que el cliente Ubuntu tenga conexión a Internet.
![9](/Practica%202/imagenes/9.png)
## Ejercicio 3:

Con este comando vemos los logs que suceden en tiempo real. Al hacer un `ipconfig /renew` en Windows, se solicita una nueva configuración de red al servidor DHCP y podemos ver esta conversación en la captura de pantalla.
![10](/Practica%202/imagenes/10.png)