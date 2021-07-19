### Hi there 👋

<!--
**EliudBarcenas/EliudBarcenas** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Rock & EDM Festival </title>
    <link rel="stylesheet" href="build/css/app.css">
</head>
<body>

    <header class="header">
        <div class="contenedor contenido-header">
            <h1> Rock & EDM Festival </h1>

            <nav class="navegacion-principal">
            <a href="#"> Line Up </a>
            <a href="#"> Galeria </a>
            <a href="#"> Boletos </a>
            </nav>

        </div>
    </header>
    
    <div class="video">
        <div class="overlay">
            <div class="contenedor contenido-video">
                <h2>
                    Rock & EDM Festival
                    <span> Julio 2021, Monterrey, México </span>
                </h2>
            </div>
        </div>
        <video controls autoplay muted loop>
            <source src="video/concierto.mp4" type="video/mp4">
            <source src="video/concierto.ogg" type="video/ogg">
            <source src="video/concierto.webm" type="video/webm"> 
        </video>
    </div>

    <div class="informacion-festival contenedor">
        <div class="imagen">
            <img src=".build/img/imagen_vocalista.jpg" alt="imagen vocalista">
        </div>
        
        <div class="contenido-festival">
        <h2> Rock & EDM Festival </h2>
        <p class="fecha"> Julio 2021 Monterrey, México </p>
        <p class="texto">
            Cras aliquam sem lacus, id ultricies urna eleifend nec. Etiam lacinia, arcu at maximus feugiat,
            neque leo gravida tortor, nec scelerisque lacus nisl ultricies odio. Suspendisse egestas tempor blandit. Aliquam in nunc mattis,
            molestie tellus in, accumsan leo. Suspendisse vel elit eget ligula tincidunt placerat. Nullam finibus a ligula ac rutrum.
            Vestibulum varius sem a ante suscipit ornare.
        </p>
        </div>
    </div>

        <section class="lineup">
            <h3> Line Up </h3>

            <p class="dia"> Viernes 21 </p>
            <div class="escenarios-contenedor contenedor">
                <div class="escenario rock bg-amarillo">
                    <p class="nombre-escenario"> Escenario Rap </p>

                    <ul class="calendario">
                        <li> 24:00 | <span> Cartel del Santa </span> </li>
                        <li> 22:00 | <span> Santa Fe Klan </span> </li>
                        <li> 20:00 | <span> Gera MX </span> </li>
                        <li> 19:00 | <span> Aleman </span> </li>
                        <li> 18:00 | <span> Jamby el Favo </span> </li>
                        <li> 17:00 | <span> Santa Grifa </span> </li>
                    </ul>

                </div>

                <div class="escenario edm bg-verde">
                    <p class="nombre-escenario"> Escenario Reggaeton </p>

                    <ul class="calendario">
                        <li> 24:00 | <span> Anuel AA </span> </li>
                        <li> 22:00 | <span> Marvel Boy </span> </li>
                        <li> 20:00 | <span> Kevin Roldan </span> </li>
                        <li> 19:00 | <span> Myke Towers </span> </li>
                        <li> 18:00 | <span> Blessed </span> </li>
                        <li> 17:00 | <span> Maluma </span> </li>
                    </ul>
                </div>

            </div>

            <p class="dia"> Sábado 22 </p>
            <div class="escenarios-contenedor contenedor">
                <div class="escenario rap bg-verde">
                    <p class="nombre-escenario"> Escenario Rap </p>

                    <ul class="calendario">
                        <li> 24:00 | <span> Cartel del Santa </span> </li>
                        <li> 22:00 | <span> Santa Fe Klan </span> </li>
                        <li> 20:00 | <span> Gera MX </span> </li>
                        <li> 19:00 | <span> Aleman </span> </li>
                        <li> 18:00 | <span> Jamby el Favo </span> </li>
                        <li> 17:00 | <span> Santa Grifa </span> </li>
                    </ul>

                </div>

                <div class="escenario edm bg-amarillo">
                    <p class="nombre-escenario"> Escenario Reggaeton </p>

                    <ul class="calendario">
                        <li> 24:00 | <span> Anuel AA </span> </li>
                        <li> 22:00 | <span> Marvel Boy </span> </li>
                        <li> 20:00 | <span> Kevin Roldan </span> </li>
                        <li> 19:00 | <span> Myke Towers </span> </li>
                        <li> 18:00 | <span> Blessed </span> </li>
                        <li> 17:00 | <span> Maluma </span> </li>
                    </ul>
                </div>
        </section>

</body>
</html>
