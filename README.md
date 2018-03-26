# BusAltoke
'BusAltoke' es una aplicación móvil de la empresa 'GEP', donde ayuda a los usuarios que usan de manera constante su servicio a saber la ruta que tienen sus buses y en que momento llegan a la parada indicada.

![image](https://user-images.githubusercontent.com/30356026/37910130-633fdcc0-30d2-11e8-8dda-d2de24f3f8d4.png)


## Desarrollado para Laboratoria

## Puntos clave:
* Al ya tener una aplicación móvil donde ya indica sobre lo anteriormente mencionado, esta no es facil de entender para los usuarios.
* Se realizará un rediseño del flujo de compra de pasaje y seguimiento de rutas del bus donde se encuentra el usuario.

 ### Muestras de la aplicación:
 
 ![Aplicación original](assets/documents/origin.png)

 ## Descubrimiento e investigación
 ### Analisís del estado actual
 - **En base a la empresa**:  GEP es un grupo de empresas peruanas de transporte público en Lima, donde la integran Sfasa40, Las Flores18 y  Realidad Express03, la cual tiene como objetivo ofrecer un servicio de calidad.
 GEP aporta muy aparte del transporte al usuario, con un branding sobre ser ecoamigable. Ofrece a los usuarios poder utilizar una tarjeta recargable para el pago del pasaje en sus lineas o dando la opción de hacerlo aún sin tarjeta(en otras palabras pagando ni bien sube al transporte).

 - **En base al usuario**: Un pequeño background de mi - la usuaria y otros que dan su feedback al probar la aplicación.
    * La edad base es de entre 20 - 30 años los que hacen uso de la aplicación.
    * La gran mayoria no tiene la tarjeta de la empresa y paga directamente al subir.
    * Necesidad: Poder saber a que hora el bus llega al paradero con exactitud y que muestre un seguimiento de la ruta del bus.
    * Necesidad opcional: Poder tener un medio de acceso a sugerencuas y quejas, saber con exactitud mas información sobre las tarjetas y recargas.

 #### Benchmarking

 ![benchm](assets/documents/benchmarking.png)
#### BusAltoke Arquitectura de información
Estructura de la información en base al proceso actual de la aplicación:
* Selección de paradero son funciones repetidas.

![EI](assets/documents/eInformacion.jpg)

* Problemas Principales:
    - Falta de contenido sobre las rutas en las que se dividen.
    - Falta de seguimiento de rutas de los buses.
    - Flujo confuso de uso.
    - Funcionalidad confusa al intentar ver los paraderos y los horarios de llegada del bus.
#### Journey Map
A partir del journey map se indentificará y se creará estrategias para los puntos clave.

* Viaje
![viaje](assets/documents/JMViaje.jpg)

#### User research
* Feedback actual de usuarios sobre la aplicación.
![FeedbackApp](assets/documents/feedbackuser.png)
* Entrevistas [Link Drive](https://drive.google.com/open?id=1vnaxnEwmsOkipW4tgi-eYfAWQHFyk-Ex)
* Encuestas [Resultados de encuestas](https://docs.google.com/spreadsheets/d/1oYhzy1EKBkhn_p6WH7NTPPfQ9eA5YnH5FnrmsGDynGo/edit#gid=782536115) 

## Síntesis y definición
* Affinity map

![affinityMaps](assets/documents/affinityMaps.jpg)

### Ideación
* User persona

![jhon](assets/documents/userpersona.png)

### Nueva propuesta de arquitectura de información

![newAi](assets/documents/newAI.jpg)

### Prototipo en Baja Fidelidad

![PBF](assets/documents/prototipoBF.jpg)

### Prototipo en Alta Fidelidad

![PAF](assets/documents/mapaPAF.JPG)
* [Figma](https://www.figma.com/file/KjjHy8RNSg7342W5d0oCML6w/BusAltoke)
* [Marvel](https://marvelapp.com/4j9g8h5)

### Feedback

* En destinos guardados, que tambien guarde el origen (por ejemplo: casa).
* Recargar la tarjeta que muestre la forma en como hacerlo.
* Recargar, mostrar lugares en donde se puede hacer.
* Mostrar las rutas completas de cada linea.
