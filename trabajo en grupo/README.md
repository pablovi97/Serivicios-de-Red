*Alfonso Gonzáles Galván , Yared Martín Pérez , Pablo Viera Martin*

## DCHP FAILOVER  

* ### Paso 1/ Creamos un ámbito en el servidor 1 (DHCP1)

![imagenes](img/001.png)    

![imagenes](img/002.png)  

![imagenes](img/007.png)   


* ### Paso 2/ Clonamos el servidor, reiniciamos la MAC, bajamos un nivel el Active Directory y borramos el ámbito anterior  

![imagenes](img/003.png)     

  * #### Activamos asignacion por DCHP

  ![imagenes](img/004.png)   

  * ### Paso 3/ Creamos el  FAILOVER  en el DCHP1 asignándole el DHCP2  

![imagenes](img/005.png)  

![imagenes](img/008.png)  

![imagenes](img/009.png)  

![imagenes](img/010.png)   

* ### Paso 4/ Ahora, en el cliente, tenemos que coger la ip del segundo servidor, ya habiendo deshabilitado el primero  

![imagenes](img/011.png)   

![imagenes](img/012.png)
