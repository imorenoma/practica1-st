Practica 1
----------
Esta es la primera practica de dispositivos 
en NetGUI
-----------
1.1 

Al hacer ping entre Pc1 y Pc2 solo vamos a recibir 
tramas en Pc2 porque solo habra intercambio de
paquetes entre máquinas de la misma red ya que S1 
esta desconectado he impide la conectividad entre 
otras redes.

Los paquetes que vamos ha encontrar en Pc2 seran
una trama con direccion IP destino a Broadcast
con la caché de ARP vacía (al inicio)

+++++++++++++++++++++++++++++++++++++++
1.2

A continación hacemos el ping de Pc1 a Pc2 y
realizamos la captura con el comando 

$tcpdump -i eth0 

en pc2 en pc3 y pc5.

Como observamos en la captura de pantalla 
ejercicio1-1.png efectivamente el unico que
recibe los paquetes es pc2 mientra el resto
de Pc's estan aun a la escucha.

+++++++++++++++++++++++++++++++++++++++
1.3

Comprobamos que no hay conectividad con otras
haciendo por ejemplo ping de pc1  pc3 y como vemos
en la captura de pantalla de pc1 todos los paquetes
se han perdido, ocuriria exactamente lo mismo con 
pc5
  


