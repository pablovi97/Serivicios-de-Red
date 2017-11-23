# Instalación y Configuración de un Servidor Web Avanzado (carpetas seguras)

## PASO1-.Crea una nueva zona de búsqueda directa en los servicios DNS asociado al dominio miEmpresa
>  Crea también una carpeta miEmpresa
en C:\ y una subcarpeta ‘principal’.

![IMG](./IMG1/002.png)

## PASO2-.Crea  un  nuevo  sitio  web  denominado  miEmpresa
>  en  IIS  asociado  a  la  subcarpeta  anterior  y  con  acceso a través de la dirección
www.miEmpresa.com. Actualiza DNS adecuadamente.

![IMG](./IMG1/001.png)

>*Dentro de pagos*  

![IMG](./IMG1/006.png)
## PASO3-.crea  un  nuevo sitio
>un sitio web (denominado ‘pagos’) como subdominio de miEmpresa, (pagos.miEmpresa.com) y configura
este último para ser accedido de forma segura, vía ‘https’.



* **Vamos al IIS y ceramos el sitio**

![IMG](./IMG1/003.png)


* **Configuración  A: configura  el  nuevo  sitio  para que se pueda acceder (sólo) como sitio web seguro (https) con un Certificado Autofirmado.**  

![IMG](./IMG1/007.png)  

![IMG](./IMG1/008.png)  

* **Configuración B: Creamos un nuevo sitio seguro (tienda.miempresa.com) con la generación de un  Certificado  Digital a  través  de  la  aplicación  OpenSSL.**

![IMG](./IMG1/009.png)  

* **través de OpenSSl genera un nuevo certificado de servidor:**    

![IMG](./IMG1/010.png)   

![IMG](./IMG1/011.png)  

![IMG](./IMG1/012.png)  

![IMG](./IMG1/013.png)  

![IMG](./IMG1/014.png)    

## PASO4-. Requerir  que  nuestros  sitio  seguros  sólo  se  pueda  acceder  mediante  una  conexión  segura  y  reiniciar los sitios web.    

![IMG](./IMG1/015.png)    

## PASO5-. Finalmente, acceder mediante http y mediante https a los sitios seguros desde el propio servidor y desde un cliente :
![IMG](./IMG1/cli.png)    

![IMG](./IMG1/cli2.png)  

![IMG](./IMG1/cli1pag.png)     


# Instalación y Configuración de un Servidor Web Avanzado (carpetas privadas)  

## PASO 1-.crear  un  nuevo  sitio  web   
> (empleados.miEmpresa.com) destinado a almacenar información privada de los empleados:  

![IMG](./IMG2/001.png)  

* **Necesitamos  crear  una  carpeta  empleados  (dentro  de  miEmpresa)  y,  dentro  de  esta,  tres  o  cuatro subcarpetas personales con nombres de empleados**   

![IMG](./IMG2/004.png)  

* **Crearemos  el  nuevo  sitio  web,  como subdominio  de  nuestro  dominio principal,  asociado a  la  carpeta genérica empleados.**  

![IMG](./IMG2/002.png)    

* **habilitamos la opcion para poder navegar por las carpetas desde la web:**  

![IMG](./IMG2/003.png)   

* **y comprobamos si el sitio funciona:**  

![IMG](./IMG2/005.png)   

## PASO 2 -.Quitamos el acceso anonimo a las carpetas y ponemos la funcion de autentificacion basica:  

*  **el sitio principal:**  

![IMG](./IMG2/006.png)  

* **empleado1:**  

![IMG](./IMG2/006.1.png)    

* **empleado2:**  

![IMG](./IMG2/006.2.png)  

* **empleado3:**  

![IMG](./IMG2/006.3.png)   


## PASO 3 -. creamos usuarios empleados y grupo empleados en active directory:  

![IMG](./IMG2/008.png)   

![IMG](./IMG2/009.png)


## PASO 4 -. vamos a las carpetas que creamos antes y quitamos permisos a todos los usuarios menos al usuario que hayamos creado para esa carpeta :

* **para la carpeta empleado 1:**    

![IMG](./IMG2/010.png)   

* **para la carpeta empleado 2:**   

![IMG](./IMG2/011.png)  

* **para la carpeta empleado 3:**  

![IMG](./IMG2/012.png)     

## PASO 5 - ahora vamos al navegador y buscamos la web   

* **y ya tenemos que poner alguna clave y usuarios para poder entrar**  

![IMG](./IMG2/013.png)
