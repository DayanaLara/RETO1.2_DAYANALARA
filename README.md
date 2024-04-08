# RETO1.2_DAYANALARA
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
      body {
        background-color: lightblue;
        /* Color de fondo de la página */
        color: darkblue;
        /* Color de texto */
      }

      /* Estilos para centrar el título */
      h1 {
        text-align: center;
      }

      /* Estilos para cambiar el color del título */
      .titulo-colorido {
        color: #ff9000;
        /* Puedes cambiar el color especificando un código hexadecimal, RGB o nombre de color */
      }

      /* Estilos para los párrafos */
      p {
        font-family: Arial, sans-serif;
        font-size: 18px;
        line-height: 1.6;
        color: #333;
        margin-bottom: 20px;
      }

      /* Estilos para el enlace "Ver más" */
      .ver-mas {
        color: #007bff;
        /* Color del enlace */
        text-decoration: underline;
        /* Subrayado del enlace */
        cursor: pointer;
        /* Cambia el cursor al pasar sobre el enlace */
      }

      table {
        width: 100%;
        border-collapse: collapse;
      }

      th,
      td {
        padding: 10px;
        border: 1px solid #ddd;
        text-align: center;
      }

      th {
        background-color: #f2f2f2;
      }

      caption {
        font-size: 1.5em;
        margin-bottom: 10px;
      }

      table {
        width: 100%;
        border-collapse: collapse;
      }

      th,
      td {
        padding: 10px;
        border: 1px solid #ddd;
        text-align: center;
      }

      th {
        background-color: #f2f2f2;
      }

      caption {
        font-size: 1.5em;
        margin-bottom: 10px;
      }

      .lista-desplegable {
        list-style: none;
        padding: 0;
        margin: 0;
        width: 200px;
        border: 1px solid #ccc;
        border-radius: 4px;
        overflow: hidden;
        transition: max-height 0.3s ease-out;
        max-height: 0;
      }

      .lista-desplegable.active {
        max-height: 200px;
        /* Altura máxima cuando está desplegado */
      }

      .lista-desplegable li {
        padding: 10px;
        border-bottom: 1px solid #ccc;
        cursor: pointer;
      }

      .lista-desplegable li:last-child {
        border-bottom: none;
        /* Eliminar el borde inferior del último elemento */
      }
    </style>
  </head>

  <body>
    <h1>JARDINES DEL ALMA</h1>
    <h1 class="titulo-colorido">BIENVENIDO A ESTE MUNDO DE JARDINES</h1>
    
    <h2>ROSA</h2>

    <p>
      La rosa es quizás una de las flores más reconocidas y populares en
      todo el mundo. Con sus pétalos suaves y delicados, la rosa viene en una
      amplia gama de colores, desde el clásico rojo pasión hasta el delicado
      rosa, el vibrante amarillo y el puro blanco. Además de su belleza visual,
      la rosa también es apreciada por su aroma dulce y distintivo. Se ha
      asociado durante mucho tiempo con el amor, la pasión y el romance, lo que
      la convierte en una opción popular para regalos románticos y ocasiones
      especiales como bodas y aniversarios.
    </p>

    <h2>TULIPANES</h2>

    <p>
      El tulipán es una flor primaveral encantadora conocida por su
      forma única y sus brillantes colores. Con sus tallos delgados y sus
      pétalos en forma de copa, el tulipán viene en una amplia variedad de
      tonos, desde el rojo intenso y el amarillo brillante hasta el morado
      profundo y el blanco puro. Esta diversidad de colores y formas hace que
      los tulipanes sean una opción versátil para arreglos florales y
      decoraciones. Además de su belleza visual, el tulipán también es apreciado
      por su elegancia simple y su simbolismo de amor y felicidad, lo que lo
      convierte en una opción popular para una amplia gama de ocasiones, desde
      cumpleaños y aniversarios hasta eventos formales y celebraciones de
      primavera.
    </p>

    <h2>LIRIO</h2>

    <p>
      El lirio es una flor elegante y majestuosa que se destaca por sus
      tallos altos y sus flores grandes y llamativas. Con sus pétalos
      acampanados y sus colores vibrantes, como el blanco puro, el rosa suave y
      el amarillo brillante, el lirio agrega un toque de gracia y sofisticación
      a cualquier arreglo floral. Además de su belleza estética, el lirio
      también tiene un aroma distintivo y encantador. Se asocia comúnmente con
      la pureza, la inocencia y la renovación, lo que lo convierte en una opción
      popular para celebrar ocasiones como nacimientos, bautizos y bodas.
      <a href="https://vallegrande.edu.pe/" class="ver-mas">Ver más</a>
    </p>
    <h2>Video de jardines</h2>
    <a href="https://www.youtube.com/watch?v=ZvIUR4-W1pU&t=2s" target="_blank"
      >JARDINES</a
    >

    <table>
      <caption>
        JARDINES 2024
      </caption>
      <thead>
        <tr>
          <th>Rosa</th>
          <th>Tulipanes</th>
          <th>Lirio</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>50%</td>
          <td>20%</td>
          <td>30%</td>
        </tr>
      </tbody>
    </table>

    <h2>CREATIVIDAD DE JARDINES</h2>

    <!-- Primera imagen con estilos en línea -->
    <img
      src="https://biblioteca.acropolis.org/wp-content/uploads/2019/07/Rosa-Mister_Lincoln.jpg"
      alt="ROSA1"
      style="
        display: block;
        margin: 20px auto;
        width: 300px;
        height: auto;
        border-radius: 10px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      "
    />

    <!-- Segunda imagen con estilos en línea -->
    <img
      src="https://verdecora.es/blog/wp-content/uploads/2020/11/tulipanes-colores.jpg.webp"
      alt="TULIPANES2"
      style="
        display: block;
        margin: 20px auto;
        width: 300px;
        height: auto;
        border-radius: 10px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      "
    />

    <!-- Tercera imagen con estilos en línea -->
    <img
      src="https://floreshoy.co/wp-content/uploads/2023/04/Diseno-sin-titulo-98-825x510.png"
      alt="LIRIO3"
      style="
        display: block;
        margin: 20px auto;
        width: 300px;
        height: auto;
        border-radius: 10px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      "
    />
    <h2>Selecciona una fecha:</h2>

    <form action="/submit-formulario" method="post">
      <label for="fecha">Fecha:</label><br>
      <input type="date" id="fecha" name="fecha"><br><br>
      <input type="submit" value="Enviar">
    </form>


    <h2>Selecciona una opción:</h2>
    <!-- Lista desplegable -->
    <select id="opciones" onchange="mostrarSeleccion()">
      <option value="opción1">ROSA</option>
      <option value="opción2">TULIPANES</option>
      <option value="opción3">LIRIO</option>
    </select>

    <!-- Script para mostrar la selección -->
    <script>
      function mostrarSeleccion() {
        var lista = document.getElementById("opciones");
        var seleccion = lista.options[lista.selectedIndex].text;
        alert("Has seleccionado: " + seleccion);
      }
    </script>

    <!-- Botón de referencia -->
    <a href="https://vallegrande.edu.pe/">
      <button>Ir a Referencia</button>
    </a>

    <!-- Sección de referencia -->
    <div id="https://vallegrande.edu.pe/" style="margin-top: 200px">
      <h2>Referencia</h2>
      <p>
        valle grande_Antigua Panamericana Sur Km. 144, Distrito San Vicente de
        Cañete, provincia de Cañete, Región Lima, Perú.
      </p>
    </div>

    <cite>DAYANA LARA</cite>

    <footer>
      <p>publicado el <time datetime="2024-04-08"> 8 de abril de 2024</time></p>
    </footer>
  </body>
</html>
