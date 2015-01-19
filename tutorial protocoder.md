## ¿Qué es Protocoder?

Protocoder es un entorno de desarrollo para Android que nos permite utilizar javascript para crear aplicaciones rápidamente

Nos facilita el acceso al hardware del dispositivo: bluetooth, ¿cámara?, red...

Para utilizarlo sólo hay que instalar en nuestro dispositivo Android de Protocoder y tendremos acceso web a un potente entorno de desarrollo desde cualquier otro dispositivo que esté conectado a la misma red Wifi o al puerto USB sin más que acceder a la web que nos indica la aplicación al arrancar.

El entorno web además de un editor dispone de multitud de ejemplos y documentación.

Se han incluido multitud de APIs a las que podemos acceder desde javascript como (Processing)[http://processing.org] (desarrollo visual), (Pure Data)[http://puredata.org], (Open Street Map)[http://openstreetmap.org], ...

También podemos acceder al hardware de nuestro terminal, como el acelerómetro, ....

Todos los scripts javascript quedan almacenados dentro de la aplicación y podemos acceder a cualquiera de las realizadas (o descargadas) para editarlas o ejecutarlas.

Podemos conectar otras placas externas como arduino e intercambiar datos, controlarlas o representar gráficamente los contenidos 
!(grafica de sensores)[file:///home/javacasm/Dropbox/1_proyectos/bq/protocoder/Protocoder%20%20%20Hardware%20and%20software%20prototyping%20for%20Android%20devices_files/]


Permite depurar nuestro código línea a línea !(depuración)|[file:///home/javacasm/Dropbox/1_proyectos/bq/protocoder/Protocoder%20%20%20Hardware%20and%20software%20prototyping%20for%20Android%20devices_files/protocoder_livecoding.gif]



## Instalación

Para usarla necesitamos un dispositivo con Android 4.0 o posterior.

	* Descargamos la (aplicación básica)|[http://www.protocoder.org/downloads/protocoder-normal-0_97.apk] o la (extendida)|[http://www.protocoder.org/downloads/protocoder-extended-0_97.apk] (que incluye el acceso al envío de SMS) y la instalamos.

	* Conectamos nuestro ordenador y nuestro Android a la misma red  o por medio de cable.

	* Ejecutamos la aplicación Protocoder y en un navegador en el ordenador conectamos a la dirección que nos indica la aplicación (o por usb)

	* Para conectar vía USB usamos

	adb forward tcp:8585 tcp:8585
	adb forward tcp:8587 tcp:8587
	