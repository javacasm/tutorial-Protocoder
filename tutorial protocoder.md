## ¿Qué es Protocoder?

Protocoder es un entorno de desarrollo para Android que nos permite utilizar javascript para crear aplicaciones Android rápidamente.

Podemos resumir dicuendo que se trara de  un entorno de desarrollo de aplicacines Android que utiliza javascript  como  lenguaje y que  incleye la documentación y multitud de ejemplos en forma  local. Usaremos el navegador en el pc  para desarrollar de forma muy sencilla aplicaciones Android que se ejecutarán en el dispositivo en dicho dispositivo.

Se nota que su principal desarrollador (Victor Díaz @victornomad) ha tenido que trabajar en multitudes de entornos de lo  más diversos, con y sin conexión a Internet.

De ahí la necesidad de hacer un entorno que se puede ejecutar totalmente en local, en contra de la tendencia actual de emplazar las desarrollos en la nube.

Desde este entorno podremos realizar aplicaciones Android que  acceden de forma muy sencilla al hardware del dispositivo: bluetooth, cámara, red,...  a los distintos subsistemas del terminal: reconocimiento de voz, TextToSpeech (lectura de contenidos por voz) así como a dispositivos conectados (arduino o similares)

En definitiva nos permite crear aplicaciones capces de utilizar nuestro teléfono Android como centro de procesamiento de la información disponible, lo que lo hacen ideal para desarrollar aplicaciones de robótica donde el teléfono será el cerebro.

## Utilización

Para utilizarlo sólo hay que instalar en nuestro dispositivo Android la aplicación Protocoder. Al ejecutarla tendremos acceso vía un navegador web a un potente entorno de desarrollo desde cualquier otro dispositivo que esté conectado a la misma red Wifi o al puerto USB sin más que acceder a la url que nos indica la aplicación al arrancar.

** Incluir imagen de uso **

Este entorno de programación web además de un editor y un pequeño menú de las distintas opciones, dispone de multitud de ejemplos y documentación, a los que podemos acceder en cualquier momento.

** Incluir imagen **

Se han incluido multitud de APIs a las que podemos acceder desde javascript como (Processing)[http://processing.org] (desarrollo visual), (Pure Data)[http://puredata.org], (Open Street Map)[http://openstreetmap.org], ...

También podemos acceder al hardware de nuestro terminal, como el acelerómetro, ....

Todos los proyectos que realicemos (scripts javascript y los ficheros de recursos necesarios, como imágenes, sonidos, etc...)  quedan almacenados dentro de la aplicación y podemos acceder posteriormente a cualquiera de las realizadas (o descargadas) para editarlas o ejecutarlas. ** Verificar esto ** Incluso podemos generar aplicaciones independientes.

Además de usar los recursos del smartphone, podemos conectar otras placas externas como arduino (siempre que nuestro smartphone soporte USB OTG) e intercambiar datos entre ambos, controlándolas o representando gráficamente los contenidos 
!(grafica de sensores)[file:///home/javacasm/Dropbox/1_proyectos/bq/protocoder/Protocoder%20%20%20Hardware%20and%20software%20prototyping%20for%20Android%20devices_files/]


** Probar y mostrar cómo se hace **
Otra de las posibilidades es la de depurar nuestro código línea a línea !(depuración)|[file:///home/javacasm/Dropbox/1_proyectos/bq/protocoder/Protocoder%20%20%20Hardware%20and%20software%20prototyping%20for%20Android%20devices_files/protocoder_livecoding.gif]

Con esta aplicación tenemos todo lo necesario para programar en cualquier parte

## Instalación

Para usarla necesitamos un dispositivo con Android 4.0 o posterior.

	* Descargamos la (aplicación básica)|[http://www.protocoder.org/downloads/protocoder-normal-0_97.apk] o la (extendida)|[http://www.protocoder.org/downloads/protocoder-extended-0_97.apk] (que incluye el acceso al envío de SMS) y la instalamos.

	* Conectamos nuestro ordenador y nuestro Android a la misma red  o por medio de cable.

	* Ejecutamos la aplicación Protocoder y en un navegador en el ordenador conectamos a la dirección que nos indica la aplicación (o por usb)

	* Para conectar vía USB usamos **¿Permitir Depuración usb?**

	adb forward tcp:8585 tcp:8585
	adb forward tcp:8587 tcp:8587

(ejemplo protocoder)[captura ejemplo protocoder.png]
