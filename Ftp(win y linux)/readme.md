# Instalación y Configuración del Servicio FTP en Windows 2012 Server

### 1.- Instalamos la caracteriasttica de serivdor FTP (Es una caracteristica secundaria del IIS)

![img](./img/1.png)
![img](./img/1.1.png)

### 2.- hacemos un sitio ftp en el IIS

![img](./img/2.1.png)

![img](./img/2.2.png)

![img](./img/2.3.png)

![img](./img/2.4.png)

![img](./img/2.8.png)

![img](./img/2.9.png)
>Al principio el servidor ftp no funcionaba la solucion que hicimos fue ir a enlaces y cambiar la direccion ip por un "*")

![img](./img/2.6.png)

> Y ya nos dejaria entrar

![img](./img/2.7.png)


### 3.- Entramos al FTP desde el cliente

![img](./img/2.10cli.png)

![img](./img/2.11CLI.png)

### 4.- creamos usuarios y entramos con ellos

![img](./img/3.1.png)

![img](./img/3.1nodeja.png)

### 4 .- Instalamos WinSCP y hacemos varios sitios ftp

> Vemos que funciona

![img](./img/4.1.png)

> Creamos los demas usuarios ftp

![img](./img/4.2.png)

![img](./img/4.3.png)

![img](./img/4.4.png)

>Y los probamos(este sitio FTP permite SSL)

![img](./img/4.6.png)

![img](./img/4.8.png)

> Podemos entrar permitiendo ssl

![img](./img/4.9.SSL.png)

> Creamos el sitio 3

![img](./img/5.1.png)

![img](./img/5.2.png)

### 5.- ahora buscamos una forma para que se puedan usar los tres sitios a la vez

> para ello le ponemos puertos diferentes a cada uno de los sitios

![img](./img/3FTP.png)

# Instalamos ftp en linux

### 1.-Instalamos ssh y creamos usuarios con ciertos privilegios

![img](./img/linux/1.0.png)

![img](./img/linux/1.1.png)

![img](./img/linux/1.2.png)

## 2.- accedemos desde un cliente con ssh y ejecutamos una aplicacion grafica

![img](./img/linux/1.3.png)

![img](./img/linux/1.4.png)

### 2.- Accedemos al servidor usando los usuarios mediante SFTP que se instala con el SSH

![img](./img/linux/2.1.png)

![img](./img/linux/2.2.png
)
![img](./img/linux/2.3.png)

> Y probamos a descargarnos algun archivo

![img](./img/linux/2.4.png)

>Subimos un fichero mediante SCP de cliente a servidor

![img](./img/linux/3.png)

### 3 .- Instalamos proftpd

![img](./img/linux/4.1.png)

### 4.- Investigamos donde se ediata la configuracion del proftpd

![img](./img/linux/5.1.png)


### 5.- Nos conectamos al ftp gestionado por proftpd

![img](./img/linux/6.1.png)

![img](./img/linux/6.2.png)

> Y descargamos algo

![img](./img/linux/7.1.png)
