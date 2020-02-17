# Proyecto Final Tópicos Especiales 2019A

El presente proyecto trata de una aplicación realizada en Ionic 4 la cual tiene un LogIn conectado con el servicio de autenticación de Firebase y además consume una API de OmDb que almacena datos de una gran variedad de peliculas, series, episodios, entre otros.

## Objetivo General

 - Desarrollar una aplicación que consuma una API.

## Objetivos Específicos

 - Restringir el acceso de los usuarios no registrados.
 - Autenticar al usuario a través de Firebase Auth.
 - Mostrar los datos obtenidos de la API. 

## Requisitos previos

 - Ionic en su ultima versión.
 - IDE a elección (En este caso utilizaremos Visual Studio Code)
link de descarga:  [https://code.visualstudio.com/](https://code.visualstudio.com/)
 - NodeJS.
link de descarga: [https://nodejs.org/es/download/](https://nodejs.org/es/download/)
 - Cuenta de Google y en OMDb API.
 
 ## Generar APK
Para generar el APK del proyecto utilizaremos capacitor debido a que es mucho mas flexible y se adapta mejor a la plataforma de Android.
 - cd TopicosEspeciales "Cambiamos al directorio (raíz)"
 - npm install --save @capacitor/core @capacitor/cli "instalamos capacitor"
 - npx cap init "añadimos el nombre de la aplicación y el id"
 - npx cap add android "añadimos android (Si no existe la carpeta ./www procedemos a ejecutar el comando ionic cordova prepare android)"
 - npx cap open android "abrira Android Studio"
 - Generaremos el APK con Bundle y luego Generate APK en Build.

## Desarrollo de la aplicación

El siguiente link muestra la estructuracion, implementación y desarrollo del mismo de una manera básica: https://youtu.be/OPlxh0lgT2Q

