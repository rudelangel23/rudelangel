# rudelangel
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aprende leyendo</title>
    <link rel="stylesheet" href="css/estilos.css">
</head>
<body>
        <header>
            
            <div class="nav">
                <a href="./index.html">Batalla del 19 Marzo</a>
                <a href="./30.html">Batalla del 30 de marzo</a>
                <a href="./completa.html">evaluacion del 19 de marzo</a>
                <a href="./completa30.html">evaluacion del 30 de marzo</a>
            </div>
        </header>
        <div class="container">
        <main class="principal">
            <article>
                <div class="banner_title">
                    <h1>Batalla del 19 de Marzo</h1>
                    <img  id="slider">
                    
                </div>
                <p>
                    La batalla del 19 de marzo o batalla de Azua fue la primera gran batalla en defensa de la República Dominicana y se libró el 19 de marzo de 1844. Una fuerza de 2500 soldados dominicanos que fueron reclutados para enfrentarse con el ejército haitiano, una parte del ejército del sur, estaba dirigido por el general Pedro Santana, derrotaron a 10 000 soldados del ejército de Haití encabezados por el General Souffrant. el enfrentamiento de las tropas dominicanas fue liderado por el general Pedro Santana y las tropas haitianas encabezadas por el presidente haitiano, Charles Hérard 
                    Luego de declarada la independencia dominicana, el presidente haitiano Charles Hérard organizó su ejército con 30 000 hombres. Dicho ejército fue dividido en tres flancos para penetrar en la nación recién proclamada. El primero estaba al mando del general Pierrot con 10 000 hombres, que entrarían por el norte y tomarían Santiago y Puerto Plata. El segundo estaba dirigido por el propio Hérard y pretendía tomar Azua y San Juan de la Maguana, y el tercero, dirigido por Souffrand, debía entrar por Neiba.
                </p>
                <p>
                    El 19 de marzo de 1844 se produjo en Azua el enfrentamiento de las tropas dominicanas lideradas por el general Pedro Santana y las tropas haitianas encabezadas por el presidente haitiano, Charles Hérard Ainé. Esta justa implicó el inicio del afianzamiento de las ideas de independencia que se pusieron de manifiesto en el trabucazo del 27 de febrero de 1844. Con la división del ejército haitiano, Hérard pretendía unir la columna del sur con la del norte para atacar a Azua, pero las tropas dominicanas, dirigidas por Fernando Taveras, Vicente Noble, Dionisio Reyes, y Pedro Santana las fuerzas del General Broum que estaban posicionadas en las Marías, desarrollándose el primer combate en el fuerte de Rodeo.
            </p>
                <p>
                    Por otro lado, las tropas del general Souffrand avanzaron hacia Azua, enfrentándose en el Paso de la Hicotea con los dominicanos comandados por Manuel Mora. Las tropas de Hérard pasaron por los Jovillos persiguiendo a Luis Álvarez, pero las tropas dominicanas del General Lucas Díaz, apostadas en el Paso del Jura, atacaron al ejército haitiano. los dominicanos fueron a la batalla
                    con to lo que sea que parezca un arma piedra machete cuchillo fusiles
                    lanzas garrote
                </p>
                <p>

                    El 19 de marzo a las 7 y 30 de la mañana, el General Hérard organizaba su ejército con el fin de atacar a las tropas dominicanas, pero los dominicanos atacaron a los haitianos que avanzaban por El Camino de los Conucos. El enemigo fue rechazado por el cañón de Francisco Soñé, cuyos impactos dejaron decenas de muertos y un enorme terreno despejado por la metralla en las que minutos antes habían sido compactas filas enemigas. Los comandantes dominicanos, aprovechando el terror causado por la metralla, ordenaban cerradas descargas de fusilería y cargas a machete, motivando que el pánico se apoderara del enemigo y emprendieran la retirada. Al ser decapitado el comandante haitiano Vicent Jean Degales por los comandantes Matías de Vargas, José Leger y Feliciano Martínez, sus tropas (noveno y décimo regimiento) se desplegaron en desorden por falta de jefe. Poco después las tropas haitianas que avanzaban por El Camino del Barro (segundo y sexto regimiento), fueron sorprendidos por el contingente de azuanos, quienes apoyados por la fusilería de Nicolás Mañón, se lanzaron en un asalto de machete que sembró el terror y la muerte, obligándolas a retirarse.
                </p>
             
            </article>
           
        </main>
    

    </div>

    <script>
        window.addEventListener('load',  ()=>{
            let slider = document.getElementById('slider')
            let imgenes = [];
            imgenes[0] = '0.jpg'
            imgenes[1] = '1.jpg'
            imgenes[2] = '2.jpg'
            imgenes[3] = '3.jpg'

            let indiceimg = 0;
            function changeimg() {
                slider.src = imgenes[indiceimg]

                if (indiceimg < 3 ) {
                    indiceimg++;
                }else{
                    indiceimg = 0;
                }
                
            }

            setInterval(changeimg, 3000)
        })

    </script>
    
</body>
</html>
