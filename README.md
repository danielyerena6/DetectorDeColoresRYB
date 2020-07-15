# DetectorDeColoresRYB
Este repositorio contiene una prueba del detector de colores con openCV, desarrollado en python con jupyter notebook.
La configuracion inicial es para los colores Rojo, Amarillo y Azul.
Se puede cambiar los colores con el standard HSV.
https://es.wikipedia.org/wiki/Modelo_de_color_HSV

El detector tiene como componentes una raspberry pi 3 b que es donde corre el script de python3 y un telefono celular
utilizado como camara web con la aplicacion IP Webcam.

El procesamiento de imagen se hace con la libreria opencv en su version 4.1.0.25. Haciendo uso de conceptos basicos de vision
por computadora se pueden diferenciar los colores azul, amarillo y rojo y variando los parametros de color con HSV se pueden 
detectar otros colores distintos.

Como trabajo a futuro se implementara un modelo de redes neuronales para poder detectar si una persona usa cubre bocas para 
permitir el paso a un establecimiento bajo el mismo siste

<h1>Evidencias:</h1>







![Alt text](https://github.com/danielyerena6/DetectorDeColoresRYB/blob/master/evidencias/Screenshot_20200715-151805.png?raw=true "IP web cam original")


![Alt text](https://github.com/danielyerena6/DetectorDeColoresRYB/blob/master/evidencias/Screenshot_20200715-152333.png?raw=true "IP web cam original")


![Alt text](https://github.com/danielyerena6/DetectorDeColoresRYB/blob/master/evidencias/Screenshot_20200715-152353.png?raw=true "IP web cam original")






[![IMAGE ALT TEXT](http://img.youtube.com/vi/9cl8wLylQb8/0.jpg)](https://youtu.be/9cl8wLylQb8 "Demostracion de lo que muestra la Raspberry pi")

La imagen de arriba es un vinculo directo a la demostracion en video del funcionanmiento del script y como se muestra en la raspberry pi.

El programa presenta los problemas tipicos de la vision por computadora donde influye la resolucion de la imagen, calidad del video y la iluminacion.

De igual manera el programa no hace filtrado a nivel de ojo humano asi que muestra colores donde a simple vista pareiera que no estan, esto debido que
los pixeles sobre pasan el umbral de luz establecido por el programa pero no el umbral del ojo humano.
