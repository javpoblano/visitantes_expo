#TCS - TradeCenterStats

TCS surge por la necesidad que tiene la Expo Guadalajara de tener estadísticas confiables sobre el comportamiento de sus visitantes. Esta solución se compone de una aplicación android y de una aplicación web que en tiempo real muestra cuales son las zonas con más afluencia.

Esta comunicación entre teléfono y aplicación web se lleva a cabo a través del uso de beacons.

##¿Qué son los beacons?
Los beacons son dispositivos bluetooth que se utilizan para compartir información y para interactuar con otros dispositivos móviles, tales como smartphones, tablets, laptops, etc. 
 
Estos dispositivos, cuentan con dimensiones reducidas lo cual permite que sean utilizados en cualquier tipo de establecimiento, sin importar su tamaño, cuentan con una batería que dura aproximadamente 8 meses y son una tecnología sumamente accesible.

El costo actual de un beacon oscila entre los $200 y los $400 mxn 

##App móvil
La aplicación móvil cuenta con las siguientes funciones:

Manejo de perfil de usuario
En base a la ubicación del usuario, la aplicación comparte información relevante al usuario.  ( Promociones, anuncios o eventos )
Obtención de ubicación del usuario con una precisión del 98% 
	
##App web
La aplicación web está basada en un servidor de Node.js lo cual nos proporciona tiempos de respuesta muy cortos y la capacidad de ver en tiempo real la comunicación entre dispositivos a través de sockets.

La aplicación web se encuentra disponible en https://tcs-app.herokuapp.com 


El stack de tecnologías utilizadas en servidor web es el siguiente.



