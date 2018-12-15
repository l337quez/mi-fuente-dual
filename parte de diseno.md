
Regulador de corriente  https://www.diarioelectronicohoy.com/blog/electronica-practica


Regulacion de voltaje corsair y fine:
https://i.pinimg.com/originals/b1/ba/10/b1ba1097a7087a082dfbfb3a4229897c.gif
https://www.theprojectasylum.com/electronicsprojects/benchpowersupply/benchpowersupply.html

El diodo 11dq06 agauanta solo 1.1 A, mo sirve para el diseño, aunque por ahi no van a pasar los 25A, la corriente pasara por trasistores de potencia, quiza hasta funcione, yo busque un reemplazo porque tengo unos cuantos diodos shotkley. Este tipo de diodos son idealmente adecuado para bajo voltaje, alta frecuencia rectification, o como rueda libre y polaridad Diodos de protección. 

Usara un dido MOSPEC s16c40c http://www.mospec.com.tw/pdf/schottky/S16C30-S16C60.pdf
basicamente es casi lo mismo que el 11dq06, solo que aguanta mas corriente y tiene diferentes modos de conexion.


Los didos 1N400X son didos rectificadores multiproposito, soportan 1 Amperio. https://en.wikipedia.org/wiki/1N400x_general-purpose_diodes


Para que por el regulador pase mas 1 Amperio debemos colocar un transistor TIP como se mustra en la imagen http://2.bp.blogspot.com/-Tj8V-ZB88cE/UeOsITLUkBI/AAAAAAAADQw/IT__CcxUo2Q/s1600/Variabel+Power+Supply+LM317+10A.jpg   de la pagina http://jorgefloresvergaray.blogspot.com/2009/10/aumentar-la-salida-de-los-78xx.html


Importante el tip3055 aguanta 15A, parece que debemos colocar al menos 2 en paralelo, datasheet del tip3055 https://www.onsemi.com/PowerSolutions/document/TIP3055-D.PDF
