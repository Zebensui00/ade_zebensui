## Informe MySQL Server - Zebensui Lorenzo Esquivel

Lo primero es instalar el Ubuntu Server, con la configuración que nos piden que en este caso es instalarlo de forma normal con el opensssh.

![](img/1.png)

![](img/2.png)

![](img/3.png)

![](img/4.png)

![](img/5.png)

![](img/6.png)

![](img/7.png)

![](img/8.png)

![](img/9.png)

![](img/10.png)

![](img/11.png)

![](img/12.png)

![](img/13.png)

Luego de esto instalamos el entorno gráfico que más nos guste, en mi caso fue xubunto-desktop y procedemos a instalar el servidor MySQL.

![](img/14.png)

Comprobamos la versión y el estado del servicio, lo apagamos lo encendemos y vemos que todo funciona correctamente.

![](img/15.png)

![](img/16.png)

Ahora vamos a comprobar que no entra al mysql con el usuario root aunque le pongamos bien la contraseña y posteriormente lo vamos a arreglar con los comandos que vemos a continuación.

![](img/17.png)

![](img/18.png)

Nos descargamos el WorkBench, lo abrimos para comprobar que funciona e importamos una base de datos para ver que todo funciona correctamente. En mi caso use la de jardinería.

![](img/19.png)

![](img/20.png)

![](img/21.png)

![](img/22.png)

![](img/23.png)

Nos instalamos adminer.

![](img/24.png)

Ahora ejecutamos el comando php para que cree el archivo adminer con la correspondiente versión.

![](img/25.png)

![](img/26.png)

Lo siguiente que tenemos que hacer es crear el fichero de configuración de adminer en apache y meter dentro la siguiente linea

![](img/28.png)

Solo nos queda guardar los cambios, reiniciar el servicio y confirmar la conexión de local host por el alias que le hemos configurado

![](img/29.png)

![](img/30.png)

Lo último que nos falta es instalar es el PhPMyAdmin que nos va preguntando ciertas cosas durante la instalación pero con dejarlo todo como veremos a continuación es suficiente.

![](img/31.png)

![](img/32.png)

![](img/33.png)

![](img/34.png)

![](img/35.png)

## Preguntas finales:

Directorio de instalación.

![](img/36.png)

Lo que pasa con el comando es que suspende el servicio:

![](img/42.png)

![](img/43.png)

Directorio del servidor

![](img/37.png)

Directorio de los datos

![](img/38.png)

Archivo de configuración:

![](img/39.png)

![](img/41.png)

Propietario de las bases de datos:

![](img/40.png)
