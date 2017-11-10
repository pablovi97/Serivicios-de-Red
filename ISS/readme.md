* # Instalacion y configuracion del ISS

## PASO 1 -. Instalación del ISS wn Windows :   

![img](./IMG/001.png)  

![img](./IMG/002.png)   

### Y ya esa instalado :   

![img](./IMG/003.png)    

### PASO 2 -.
**comprobamos el acceso a nuestro servidor web con (localhost)**

![img](./IMG/parteiss.png)

**ahora accedemos por el cliente al con la ip del servidor**    


  ![img](./IMG/cliaserv.png)   
   
  **Tambien accedemos al w7 con un alias que hayamos creado en nuestro servidor**  

![img](./IMG/elalias.png)  

 ![img](./IMG/entrarconalias.png)   

  **Ahora accedemos con el dominio principal**    

 ![img](./IMG/dominio.png)   

 ### PASO 3 -. creamos una pagina web  

  **Crea  una  página  web  HTML  sencilla  (index.htm)  como  página  principal  de  tu  dominio  y**  
      colócala  en C:\Inetpub\wwwroot.   

   ![img](./IMG/web.png)     


* # Creacion de sistios web Independientes   

### PASO 1-.   
 **Creamos dos sitios web , uno asociado al dominio principal y otro al subdominio**   

  ![img](./IMG/SERV.png)

### PASO 2-.
 **Definimos algun sitio web con algun tema**    

![img](./IMG/2.1.png)

### Paso 3-.
**hacemos un sitio web que no sea parte del dominio principal , ademas incluir  una  nueva  zona  de  búsqueda  directa  en  tu  servicio  DNS  con  las  opciones  de  configuración necesarias :**   

![img](./IMG/2.2.png)    

![img](./IMG/2.3.png)

### Paso 4-.  
 **Finalmente,  incorpora  algunos  archivos  HTML,  imágenes  y  subcarpetas  a  tu  nuevo  sitio  web  y  comprueba  el  acceso  desde  navegadores  web  tanto  del  servidor  como  del  cliente  W7**  

![img](./IMG/2.5.png)      

# Creacion de directorios virtuales

## Paso 1 -.    

**crea  una  carpeta  que  se  corresponda  con una posible sección del sitio web creado en la práctica anterior (creación de sitios web
independientes).  Crea  un  nuevo  directorio  virtual  en  IIS  (dentro  del  citado  sitio  web)  y  relaciónalo con la carpeta que has creado**   

![img](./IMG/3.png)  

![img](./IMG/3.1.png)  

![img](./IMG/3.2.png)  

**Comprobar  el  acceso  a  cada  una  de  las  diferentes  secciones  de  nuestro  sitio  web,  tanto  desde el servidor como desde el cliente W7**  
![img](./IMG/2.cli.png)    

![img](./IMG/2.2cli.png)      
