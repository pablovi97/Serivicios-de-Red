# PHP, MySQL, phpMyadmin, FTP y Drupal

## PASO 1 .-Instalación de PHP, MySQL y PHPMyAdmin  

>Vamos a realizar las instalaciones y configuraciones necesarias para obtener un Servidor Web con
soporte PHP y accesos a bases de datos relacionales, acceso FTP y gestor de bases de datos. Sobre
este servidor, podremos realizar instalaciones de aplicaciones integradas (CMS, e-commerce, etc)
desde el propio servidor o en modo remoto desde un cliente  

* ### Instala soporte para PHP para tus sitios Web gestionados por IIS.   

![img](IMG/001.png)  

![img](IMG/002.png)  
* Comprobar la instalación correcta de PHP colocando un fichero index.php en el sitio web destinado
a gestionar el CMS Drupal (www.miEmpresa.com ó miEmpresa\principal)   

![img](IMG/003.png)   

![img](IMG/005.png)  
* ponemos el siguiente código en un index.php en la carpeta principal:  
  ><?php phpinfo(); ?>  

![img](IMG/004.png)  

* ### Instala el servidor de bases de datos relacionales MySQL para tus sitios Web gestionados por IIS      

![img](IMG/006.png)    

![img](IMG/013.png)    

![img](IMG/014.png)   

![img](IMG/015.png)     

* ### Instala PHPMyAdmin para tus sitios Web gestionados   por   IIS.   Para   esto   debes   crear   un   nuevo   sitio   web   asociado   a phpmyadmin.miEmpresa.com    

![img](IMG/009.png)     

![img](IMG/010.png)   
* En la carpeta "phpmyadmin"  puse el contenido de php :    

![img](IMG/011.png)       

* Luego fuimos a la web y comprobé que se podía acceder a phpmyadmin :  

![img](IMG/012.png)  

![img](IMG/016.png)  


## Instalación de Servidor FTP y CMS Drupal    

* Instalar Servidor FTP FileZilla en Windows 2012 Server.  

![img](IMG/017.png)    

   * Crear un usuario denominado ftpuser en el Servidor FTP y asociarle a este usuario permisos
   de Control Total sobre la carpeta en la que se va a instalar el CMS de miEmpresa.  

![img](IMG/018.png)
  * Crear un nuevo registro DNS que permita acceder a nuestro sitio FTP a través de la dirección
 ftp.miEmpresa.com

![img](IMG/019.png)  

![img](IMG/020.png)  

**Ahora se hara todo en modo remoto**:  

* Comprobar acceso a phpMyAdmin desde un navegador (phpmyadmin.miEmpresa.com)

![img](IMG/021.png)   

* Descargarmos Drupal:  

![img](IMG/022.png)   

* Comprobar el acceso al sitio FTP creado a través de un navegador y con el usuario ftpuse  

![img](IMG/023.png)  

* **Instalar un cliente ftp**   

![img](IMG/024.png)    

* Descomprimir y subir archivos Drupal a carpeta principal  

![img](IMG/027.png)  

![img](IMG/028.png)  

* Crear una nueva base de datos, denominada cms, a través de phpMyAdmin  

![img](IMG/029.png)  

![img](IMG/030.png)    

![img](IMG/031.png)  


* **Instalar  CMS  Drupal  desde  el  navegador  siguiendo  los  pasos  y  consultando  documentación  en Internet.**  
> La pagina la cambiamos por *drupal.miempresa.com* por ciertos problemas

![img](IMG/032drupal.png)  

*  Descargarmos el idioma español y lo metemos una carpeta  dentro del drupal:  

![img](IMG/033.png)  

![img](IMG/034.png)   

![img](IMG/035.png)  

![img](IMG/037.png)  

![img](IMG/038.png)  

* Luego Instalamos los temas y los metemos en la carpeta dentro de drupal:  

![img](IMG/039.png)  

* Y ya tendriamos la pagina del drupal  

![img](IMG/pagdru.png)

* Creamos variass subpaginas    

![img](IMG/040.png)  


* **Por ultimo instalamos alguna aplicacion a travez del navegador:**    

* Hacemos un dns nuevo con el nombre de la app:    

![img](IMG/041.png)
* Una pagina en IIS:  

![img](IMG/042.png)  

* Y Creamos una carpeta dentro de miempresa con el nombre del programa a instalar y la descomprimimos ahi cuando la descarguemos:    

![img](IMG/042.1.png)

* Y por ultimo cuando accedemos a la web ya estaria lista para instalar  

![img](IMG/043.png)
