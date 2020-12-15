# Presupuesto


Presupuesto es una aplicación web responsive con la que podés fijar inicialmente un presupuesto semanal para tus gastos e ir cargando el dinero que destinarás para cada uno de ellos, visualizando el restante de dinero que te queda para gastar. Una característica a destacar es que mientras tus gastos no superen el 50% de tu presupuesto, se destacará tu remanente en verde, si lo hacés, el restante se mostrará destacado en color amarillo, y si finalmente superás en gastos el 75% tu presupuesto, se mostrará tu capital en rojo. Esto se logra renderizando condicionalmente las distintas alertas, configuradas a partir de distintas clases.

Podés probarla en el siguiente enlace: 

https://presupuesto-semanal-jp.netlify.app
</br>
</br>
<h3>Comenzarás indicando tu presupuesto.</h3>
</br>
<img src= "https://raw.githubusercontent.com/JairoPonti/presupuesto/main/client/src/screenShots/img1.png" style="width: 25%"/>
</br>
</br>

<h3>Luego cargarás tus gastos: a qué los destinarás y la cantidad de dinero que emplearás en ellos</h3>
</br>
<img src= "https://raw.githubusercontent.com/JairoPonti/presupuesto/main/client/src/screenShots/img2.png" style="width: 25%"/>
</br>
</br>

<h3>Al presionar "Agregar gastos" empezarás a listarlos.</h3>
</br>
<img src= "https://raw.githubusercontent.com/JairoPonti/presupuesto/main/client/src/screenShots/img3.png" style="width: 25%"/>
</br>
</br>

<h3>Aquí un ejemplo superando el 50% del presupuesto.</h3>
</br>
<img src= "https://raw.githubusercontent.com/JairoPonti/presupuesto/main/client/src/screenShots/img4.png" style="width: 25%"/>
</br>
</br>
<h3>En este caso se llama la atención al usuario resaltando su restante en rojo (se ha superado el 75% del presupuesto).</h3>
</br>
<img src= "https://raw.githubusercontent.com/JairoPonti/presupuesto/main/client/src/screenShots/img5.png" style="width: 25%"/>
<strong>En este proyecto se trabajó con Hooks. Se realizó la documentación con PropTypes</strong>

Podrás correrlo de forma local también, para hacerlo:
En la ubicación '/presupuesto/client' deberás realizar un 'npm install' primero y luego 'npm start'. Verás la aplicación en tu localhost 
