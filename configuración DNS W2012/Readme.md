# *Instalación y configuración DNS W2012*

## Paso 1  
 **Creamos una zona de busqueda directa para el servidor y inversa para la subred**   

![imagenes](./IMG/001.png)  

![imagenes](./IMG/003.png)  

![imagenes](./IMG/004.png)  

![imagenes](./IMG/005.png)  

![imagenes](./IMG/006.png)    

> Aqui configuramos el reenviador , ponemos por ejemplo la ip de google para que se reenvie a esta ip cuando pongamos la nuestra  

![imagenes](./IMG/007.png)

**Y ya estan creadas las dos zonas** :  

![imagenes](./IMG/008.png)   

## Paso 2
**Configuramos la puerta de enlace del cliente**
> Cambiamos la puerta de enlace del cliente por la ip del servidor dns, para que acceda a internet con esta ip que a su vez esta  sera reenviada a la ip de google 8.8.8.8  

**IP del servidor**:  
![imagenes](./IMG/011.png)

**IP del cliente**:  

![imagenes](./IMG/010.png)   

## Paso 3  
**Ahora configuramos el dns maestro ademas de cache**

**En las zonas de busqueda directa añadimos los siguientes registros:**



+ ***Un alias para tu servidor denominado server***   

![imagenes](./IMG/012.png)  

+ ***Una impresora con IP fija denominada printer (no hace falta alias)***  

![imagenes](./IMG/013.png)   

+ ***Un servidor de correo (ficticio) denominado correo, asociado a una dirección en tu servidor.***

![imagenes](./IMG/014.png)  

+ ***una subzona denominada servicio (dominio nuevo) y agregar a ésta un servidor ftp (asociado a la misma IP del servidor), una impresora nueva (con una IP fija) y el equipo del administrador del sistema (también con IP fija).***

![imagenes](./IMG/015.png)    

![imagenes](./IMG/016.png)

## Paso 4
**Comprobamos que se resuelven los nombres desde la consola del servidor.**

![imagenes](./IMG/017.png)   

## Paso 5  

**Metemos al cliente en el dominio del servidor y nos tendra que aparecer en la zona de busqeda como nuevo registro A**  

![imagenes](./IMG/018.png)  

![imagenes](./IMG/019.png)   

**Y por ultimo comprobamos si nos funcionan los dns desde el cliente con nslookup**  

![imagenes](./IMG/020.png)
