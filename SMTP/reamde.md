# Práctica Servicio SMTP Windows 2012 Server

## 1.-Instalar Servicio SMTP en Windows 2012 Server

![img](./IMG/1.png)

## 2.-Configuración de servicio SMTP a través del administrador de aplicaciones (IIS) 6.0.

![img](./IMG/2.1.png)

![img](./IMG/2.2.png)

![img](./IMG/2.3.png)

![img](./IMG/2.4.png)

![img](./IMG/2.5.png)

![img](./IMG/2.6.png)

![img](./IMG/2.7.png)

![img](./IMG/2.8.png)

## 3.- Deshabilitamos el cortafuegos

![img](./IMG/3.1.png)


![img](./IMG/3.2.png)

## 4.- Descargamos Opera mail

![img](./IMG/4.1.png)

**Lo configuramos de la siguiente manera:**

![img](./IMG/4.5.png)

**Enviamos algo por email a nuestra cuenta personal y vemos que funciona**

![img](./IMG/4.2.png)

>Se guardaran en la carpeta drop en el servidor

![img](./IMG/4.3.png)

## 5.- Hacemos otro cliente de email con usuarios de Active directory ,autentificacion basica y TLS

**En el servidor SMTP ponemos lo siguiente:**

![img](./IMG/5.1.png)

**Luego vamos a las cuentas de active directory y seleccionamos alguna:**

![img](./IMG/5.2.png)

**En el opera mail ponemos a luke(nuestro usuario) en propiedades de la cuenta**

![img](./IMG/5.3.png)

**En propiedades de la cuenta ponemos coneccion seguro TLS**

![img](./IMG/5.4.png)

**Cuando queramos enviar un email nos pedira autentificacion y nos dejara mandar un mensaje:**

![img](./IMG/5.5.png)

![img](./IMG/5.6.png)

# Practica hMailServer


## 1.- En primer lugar, hay que desinstalar el servicio SMTP de Windows 2012 Server

![img](./IMG2/1.png)

![img](./IMG2/1.1.png)

## 2.-Instalamos el servidor hMailServer

![img](./IMG2/2.png)

![img](./IMG2/2.3.png)

## 3.-Creamos los dominios

![img](./IMG2/2.1.png)

![img](./IMG2/2.2.png)


## 4.-Ejecutamos un diagnostico para ambos dominios

![img](./IMG2/3.1.png)

![img](./IMG2/3.2.png)


## 5.- Creamos cuentas de usuarios en el hMailServer

![img](./IMG2/4.1.png)

![img](./IMG2/4.5.png)


## 6.-Realiza todas las opciones de configuración que consideres necesarias y/o convenientes.

![img](./IMG2/5.1.png)

![img](./IMG2/5.2.png)

![img](./IMG2/5.3.png)


## 7.-Enviamos correos de prueba en operamail con los usuarios que Creamos

![img](./IMG2/5.4.png)

![img](./IMG2/5.5.png)


## 8.-Creamos una lista de distribución y probamos que funciona


![img](./IMG2/6.1.png)

![img](./IMG2/6.2.png)

>Hacemos el correos

![img](./IMG2/7.3.png)

>Vemos que se envian correctamente

![img](./IMG2/7.4.png)

![img](./IMG2/7.5.png)
