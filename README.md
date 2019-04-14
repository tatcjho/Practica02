# Practica02

ACTIVIDADES DESARROLLADAS
1.	Diseño de página web en base a dos columnas:
![1](https://github.com/tatcjho/Practica02/blob/master/images/cap1.jpg)

Ilustración 1Imagen de mi sitio web de dos columnas
2.	Diseño de página web en base a tres columnas:

![2](https://github.com/tatcjho/Practica02/blob/master/images/cap2.jpg)
Ilustración 2Imagen de mi sitio web de 3 columnas


3.	Archivos CSS:
A continuación, se presenta la creación de los archivos .css, el cual incluirá diferentes tipos de estilos que permitirá que la pagina sea amigable con el usuario y cumpla con los estándares de W3C.

![3](https://github.com/tatcjho/Practica02/blob/master/images/cap3.jpg)
 
Ilustración 3CSS desde vsc
4.	Selectores:

a)	Selector de etiqueta:
A continuación, se presenta el selector por etiqueta el cual selecciona todos los elementos de la página cuya etiqueta HTML coincide con el valor del selector, en este caso h1 y h3 tendran la similitud de tipo de letra y tamaño.
h1, h3 {
    font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    font-size: 1cm;
}





b)	Selector descendente:
A continuación, se presenta el selector descendente, el cual selecciona los elementos que se encuentran en otros elementos.
p span{
    color: darkmagenta;
}


c)	Selector de clase:
A continuación, se presenta el selector de clase, el cual selecciona las clases con sus respectivas características.
.as1 {
    height: 300px;
    width:198px; 
    float: right; 
    border: 1px solid black;
    border-radius: 15px;
    padding: 10px; 
}

  <aside class="as1">
                <h2>Ecuador</h2>
                <p align=justify> Ecuador, oficialmente denominado República del Ecuador, es un país americano ubicado en la sección sur de este continente. 
        </aside> 


d)	Selector por ID:
#img1, #img2, #img3 {
width: 270px;
height: 200px;
}

<img src="images/historia1.jpg" alt="historia cerveza"  id="img2" />
                <img src="images/chinos.jpg" alt="" id="img1"  />
                <img src="images/edadmedia.jpg" alt="edad Media" id="img3" />



5.	Personalizado de etiquetas (h1-h6)
Para personalizar las etiquetas de los títulos, he decido implementar solo los campos tipo de letra, color y tamaño para que se visualice de una mejor manera, a continuación el código que se utilizó y posteriormente los resultados en el navegador:
h1 {
    font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    color: crimson;
    font-size: 1cm;
}

h2 {
    font-family: fantasy;
    color: blue;
    size:1cm;
}

h3 {
    font-family: Arial, Helvetica, sans-serif;
    color: orangered;
    size: 0.5cm;
}

h4 {
    font-family: Georgia, 'Times New Roman', Times, serif;
    color: red;
    size:1cm;
}

h5{
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    color: brown;
    size: 1cm;
}

h6 {
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    color: darkblue;
    size: 1cm;
}



6.	Hipervínculos usando pseudo-clases.
Las pseudo-clases se utilizan para hacer referencia a ciertos comportamientos de los diferentes elementos del documento HTML. En este caso utilizaremos las pseudo-clases para poder visualizar el estado de los hipervínculos.
 


![4](https://github.com/tatcjho/Practica02/blob/master/images/cap4.jpg)
Ilustración 4 Código en VSC para pseudo-clases
 
![5](https://github.com/tatcjho/Practica02/blob/master/images/cap5.jpg)
Ilustración 5 Imagen compilada desde el navegador


7.	Formulario HTML:
A continuación, se presenta el formulario html, el cual permite una interacción entre el usuario y la emprsa.
    <form action="formulario1" method="GET">
            <h1>SUGERENCIAS</h1>
            <p>Nombre: <input type="text" name="nombre" size="40"></p>
            <p>Año de Nacimiento: <input type="number" name="año" max="2019"></p>
            <p>Sexo:
                <input type="radio" name="hm" value="H">Hombre
                <input type="radio" name="mj" value="M">Mujer
            </p>
            <p>Correo Electrónico: <input type="text" name="correo" size="40"></p>
            <p>Comentario</p><TExtarea></TExtarea>
            <p>
                    <input type="submit" value="Enviar">
                    <input type="reset" value="Borrar">
            </p>
    </form>

![6](https://github.com/tatcjho/Practica02/blob/master/images/cap6.jpg) 
Ilustración 6Imagen de compilación desde el navegador
8.	Repositorio GITHUB:

Usuario: tatcjho
Link: https://github.com/tatcjho/Practica02 









9.	VALIDACION EN W3C VALIDATOR:

![7](https://github.com/tatcjho/Practica02/blob/master/images/cap7.jpg) 
Ilustración 7 Validación de inicio.html

![8](https://github.com/tatcjho/Practica02/blob/master/images/cap8.jpg)
Ilustración 8 Validación de styles3.css
 
![9](https://github.com/tatcjho/Practica02/blob/master/images/cap9.jpg)
Ilustración 9 Validación de sugerencias.html

RESULTADO(S) OBTENIDO(S):
Tener el conocimiento suficiente para que el estudiante pueda entender y organizar de una mejor manera los sitios de web y de negocios en Internet.

CONCLUSIONES:
•	Ampliamos nuestro conocimiento mediante la investigación y la realización de esta práctica para resolver ciertos puntos como fue la realización del formulario HTML.
•	Esta práctica nos permitió realizar un correcto empleo de los estilos, para que además de que se vea bien, esté correctamente realizado su estructura y sea amigable con el usuario.

RECOMENDACIONES:
	• 	Probar la solución de la práctica en al menos tres navegadores web; Google Chrome, Firefox y Safari 
