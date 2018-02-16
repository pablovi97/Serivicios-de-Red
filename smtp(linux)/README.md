# Instalación y Configuración de un Servidor de Correo

### SMTP

**Instalar servicio SMT en Linux, utilizando el servidor Postfix:**

![img](img/1.png)

> creamos el dominio

![img](img/2.png)

> netstat –utap

![img](img/3.png)

**Realizar  una  prueba  de  envío  de  mensaje  entre  dos  usuarios  del  sistema  mediante telnet**

![img](img/4.png)

![img](img/5.png)

![img](img/6.png)

**Comprobamos que se envio el correo del telnet**

![img](img/7.png)

**Editamos el etc/aliases de la siguiente forma**

![img](img/8.png)

**Crear  dos  nuevas  entradas  en  /etc/hosts:  smtp.miempresa.com  y  pop.miempresa.com
asociadas a la IP del servido**

![img](img/11.png)


**Creamos usuarios en el cliente**

![img](img/12.png)

**Instalamos y configuramos Evolution**

> Ponemos IMAP+ y la ip del servidor cuando se solicite

![img](img/14.png)

![img](img/15.png)

**Y vemos que se ha recibido el correo del evolution correctamente**

![img](img/18.png)

>netstat -utap para ver que el IMAP está a la escucha

![img](img/19.png)

### IMAP y Squirrelmail

**Descargamos el squirrelmail y comprobamos sus ficheros de configuración**

![img](img/20.png)

![img](img/21.png)

**Copiar lineas
no comentadas
/etc/squirrelmail/apache.conf
en
un nuevo fichero .conf de
/etc/apache2/sites
-
available
, habilitar sitio
y reiniciar apache**

![img](img/22.png)


![img](img/16.png)

**Comprobamos desde el servidor y el cliente**

![img](img/23.png)

![img](img/24.png)

**Probamos desde el cliente a enviar un correo**

![img](img/25.png)

**Comprobamos**

![img](img/26.png)

### POP3

** Instalamos pop3 y comprobamos puertos**

![img](img/27.png)

> En este apartado nos dio error a la hora de configurarlo como a muchos de nuestros compañeros y no pudimos seguir
