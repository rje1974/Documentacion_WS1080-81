# Manual WS1080 y WS1081
Este proyecto de creación del manual al español de la estacion metereologica WS1080 y WS1081. La misma la produce la firma FineOffset en china. Se vende con distintos nombre genericos como DAZA, Ambient Weather, etc. Es un clonico de la metereología.

## Objetivos.
Fuera de traducir el manual existente, tenemos como objetivo llevar el manual a otro nivel mejorando los siguientes aspectos:

  1. Conocimientos generales y contexto de la herramienta
  2. Instalación de la herramienta
  3. Mantenimiento de la herramienta

## Observaciones.
Si desea participar y no sabe como, no dude en consultar personalmente a mi dirección de correo electrónico juaneduardoriva@gmail.com.

Proyecto documentación RAMPBA


## Introducción.
El presente es el proyecto de documentación de la RAMPBA. Entienda que el mismo está en desarrollo, pues las líneas de trabajo se están actualizando constantemente; no así el objetivo principal. El objetivo principal de este proyecto es crear o re acondicionar herramientas para que mediante los datos que aportan las estaciones meteorológicas particulares se puedan generar sistemas de alerta. A continuación Usted encontrará un índice de todos los temas que se fueron dando en el proceso del proyecto y en el proyecto mismo.

## Indice.

Tecnología.
Estaciones Metereologicas.
Software
as
as
a
s
as
Agradecimiento.

## Tecnología.
El presente proyecto se basa en las siguientes tecnologías:
Centrales meteorológicas económicas y disponibles en Argentina.
El proyecto uso las clónicas que fabrica la firma Fine Offset que en el país se venden bajo las marcas DAZA y otras.
Conectividad. Necesitamos tener conectividad a internet.
WIFI y GRPS.
Linux.
Es el sistema operativo que usará la computadora.
Weewx.
Es el software de administración y comunicación de las centrales. El mismo se puede instalar en linux y más específicamente tiene una imagen para raspberry Pi. 
Python.
Lenguaje de programación interpretado cuya filosofía hace hincapié en una sintaxis que favorezca un código legible.
Hackathon + Buena onda + Tiempo.
Se desarrolló en la hackathon Agro de Tandil por la voluntad de gente que puso su buena onda, paciencia y tiempo.
Objetivos generales.
Conectar las estaciones meteorológicas disponibles en Argentina a Internet y lograr que hagan cosas que le sirvan a la sociedad. Explicarlo, documentarlo y hacer esto disponible en un estándar “libre”.
Herramientas.
Estación Metereológica.
Con conectividad y soportada por el software. Vea la lista de estaciones soportadas y tenga en cuenta que si bien la suya puede no coincidir con el nombre puede que sea una copia o clon de otra. http://weewx.com/hardware.html
Computadora.
En el caso puntual se utilizó una dell 6000 con pantalla rota. Pero puede ser una portátil, de escritorio y una raspberry pi. Si es un computador se debe de poder instalar ubuntu, en el caso de los rasberry se instala una imagen específica.
Herramientas básicas de mano.
Las utilizaremos para poder instalar físicamente la estación.
## Proceso.
1. Instalacion Estacion Metereologica.
2. Configuración Estación Meteorológica.
3. Configuración CPU e instalación Weewx.
4. Laptops y Ordenadores.
5. Instalacion Linux.
6. Instalación Weewx.
7. Rasberry Pi.
8. Instalación imagen Raspberry Pi Weewx.
9. Creación cuentas servicios meteorológicos.
10. WeatherUnderGround.
11. WindGuru.
12. Configuración Weewx.
13. weewx.conf
  1. En esa configuración pondremos los datos generales.
  2. alarm.py script

## Consideraciones generales.
Durante el proceso nos encontramos con los siguientes problemas.
* SMTP Gmail.
 Cuando cargamos la dirección a donde tenía que alertar no poniamos bien el link del servidor y nos olvidamos de poner el puerto. La forma correcta es smtp.google.com:587
* Pilas.
 Las estaciones vienen con pilas de mala calidad. Si está dentro de sus posibilidad compre pilas de primera calidad.

## Agradecimientos.
* Tom Keffer. Creador de Weewx, sin su aporte esto hubiera sido imposible.
* Hackthlon. A los organizadores, sin este evento nada de esto hubiera sido posible.
* Franco Bellomo. Sin su generosidad en apoyar el proyecto de cero y sus aportes al código no hubiera sido posible el proyecto.
* Lucas Bellomo. Sin su generosidad en apoyar el proyecto de cero y sus aportes al código no hubiera sido posible el proyecto.
* Ing. Luis Sabbatini. Luis nos aportó los sets del manual de buenas prácticas un sábado por la tarde.
