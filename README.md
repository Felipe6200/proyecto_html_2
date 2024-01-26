## Proyecto html 2

#<!DOCTYPE html>
<html lang="en">

<head>
    <title>Pagina de Prueba</title>
</head>

<body>
    <h1>heading 1</h1> <!--H1 se usa para podres agrandar los textos y dar como secciones a la pagina-->
    <h2>heading 2</h2>
    <h3>heading 3</h3>
    <h4>heading 4</h4>
    <h5>heading 5</h5>
    <h6>heading 6 </h6>

    <p>Texto con p <br> y separado </p> <!--p se usa para poner texto-->
    <hr> <br> <!--hr es para poner una linea que separa, y br para solo separar-->

    <a target="_blank" href="https://github.com/Felipe6200"> ir a github</a>
    <br>
    <!--el "a" es para seleccionar enlaces, y el target blank para abrir el enlace en otra pestaña
    el "href"=" para colocar el link de la pagina a donde queremos ir" y el texto al final para que ese sea el hipervinculo -->

    <img src="img/git hub.png" width="100" height="100" />
    <!--el "img" es el comando para coloar imagenes el "src"="tendremo que poner el lugar donde esta la imagen
        width y height es para escoger el tamaño"-->
    <br>
    <hr>

    <form action="/formulario" method="post">
        <label for="Nombre"> Nombre </label>
        <input value="Mirko" type="text" id=" Nombre" name="Nombre" placeholder="Juan" />
        <br>
        <!-- form es el formulario
        for es el nombre de la etiqueta
        dentro de las label es lo que va a ir al costado de la etiqueta
        value es lo que aparecera como si ya fuera escrito
        type, el tipo de formulario, puede ser boton tmbn
        id, lo que le enviamo al servidor
        placeholder un ejemplo en sombra -->
        <br>
        <label for="apellido"> apellido </label>
        <input value="Saavedra" type="text" id=" apellido" name="apellido" placeholder="Gonzales" />
        <br>
        <br>
        <label for=" comentario"> Comentario </label>
        <textarea rows="10" cols="50" id="comentario" placeholder="ingrese comentario" name="comentario">  </textarea>
        <br>
        <br>
        <button type="button"> Tipo button </button>
        <button type="reset"> tipo reset</button>
        <button type="submit"> tipo submit </button>

    </form>


    <!--ul es lista no ordenada-->

    <ol>
        <li value="30"> Elemento 1</li>
        <!-- el valuer es el valor que empieza, en este caso el 30-->
        <li> Elemento 2</li>
        <li> Elemento 3</li>
        <li> Elemento 4</li>
        <ol>
            <li style="list-style-type: lower-alpha;"> sub elemento 1 </li>
            <li style="list-style-type: lower-alpha;"> sub elemento 2 </li>
            <li style="list-style-type: lower-alpha;"> sub elemento 3 </li>
            <li style="list-style-type: lower-alpha;"> sub elemento 4 </li>

        </ol>
        <!--ol es lista ordenada-->



    </ol>

    <table style="width: 200px;">
        <thead>
            <tr>
                <th>producto</th>
                <th>precio</th>
            </tr>
        </thead>
        <!---thead es para poner los titulos de la tabla y se usa th para engrosarlo y centrarlo-->
        <tbody>
            <tr>
                <td>pan</td>
                <td> S/.1 </td>

            </tr>
            <tr>
                <td> leche</td>
                <td> S/.1.20 </td>

            </tr>
            <tr>
                <td> ajo</td>
                <td> S/.3 </td>

            </tr>
        </tbody>
        <tfoot>
            <td></td>
            <td>total: S/.6.20</td>
        </tfoot>
    </table>
</body>

</html>