Agrega aqui el código de la página de Octavio Paz en HTML Y CSS

            <!DOCTYPE html>
            <html>
              <head>
               <title>Poemas de Octavio Paz</title>
              </head>
              <link rel="preconnect" href="https://fonts.googleapis.com">
              <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
              <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@200&display=swap" rel="stylesheet">
                <link rel="stylesheet" href="css/estilos.css">
              <body class="contenido">
                <header>
                <b><p class="rojo"> Poesía </p></b>
                </header>
                <main>
                <div class="info">
                  <h1> 5 Poemas de Octavio Paz </h1>
                  <a class="fecha">07 Dic 2017 </a> <a class="autora">/ LAURA DI VERSO / </a> <a class="octavio	">Octavio Paz, poesía</a><br>
                  <a href="https://web.whatsapp.com" target="blank"> <img src="img/whatsapp.jpg" alt="whatsapp" height="40px" width="40px"></a>
                  <a href="https://www.facebook.com" target="blank"> <img src="img/facebook.jpg" alt="facebook" height="40px" width="40px"></a>  
                  <a href="https://www.gmail.com" target="blank"> <img src="img/mail.jpg" alt="correo electrónico" height="40px" width="45px"></a>
                  <a href="https://www.twitter.com" target="blank"> <img src="img/twitter.jpg" alt="twitter" height="40px" width="40px"></a> <br>
                </div>
                <div class="foto">	
                  <a href="https://www.zendalibros.com/5-poemas-octavio-paz/" target="blank"><img src="img/octaviopaz.jpg"  alt="OctavioPaz" height="400px" width="600px"></a>
                </div>	
                <p class="reseña"> <em> Poeta y ensayista mexicano, recibió el Premio Nobel de literatura en 1990 <br>
                  como reconocimiento a su obra literaria. Aquí te ofrecemos 5 poemas de <br>
                  Octavio Paz. </em></p><br>

                <p class="centro"> <strong> Decir, hacer </strong> </p><br>
                <p class="centro"> A Roman Jacobson </p><br>
                <p class="centro">Entre lo que veo y digo,<br>
                    Entre lo que digo y callo,<br>
                  Entre lo que callo y sueño,<br>
                  Entre lo que sueño y olvido<br>
                  La poesía.<br>
                  Se desliza entre el sí y el no:<br>
                  dice lo que callo,<br>
                  calla lo que digo,<br>
                  sueña lo que olvido.<br>
                  No es un decir:	es un hacer.<br>
                  Es un hacer que es un decir.<br>
                  La poesía se dice y se oye:<br>
                  es real.<br>
                  Y apenas digo es real, 
                  se disipa.<br>
                  ¿Así es más real?<br>
                  Idea palpable,<br>
                  palabra impalpable:<br>
                  la poesía va y viene<br>
                  entre lo que es<br>
                  y lo que no es.<br>
                  Teje reflejos y los desteje.<br>
                  La poesía siembra ojos en las páginas<br>
                  siembra palabras en los ojos.<br>
                  Los ojos hablan<br>
                  las palabras miran,<br>
                  las miradas piensan.<br>
                  Oír los pensamientos,<br>
                  ver lo que decimos<br>
                  tocar el cuerpo de la idea.<br>
                  Los ojos se cierran<br>
                  Las palabras se abren.<br>
              </main>
              </body>

            </html>




            *{
                margin: 0;
                padding: 0;
            }

            .rojo{
                color: #b51623;
                background-color: #f0f0f0;
                font-family: 'JetBrains Mono', monospace;
                letter-spacing: 1px;
                text-align: left;
                margin: 90px 450px 0px 450px;
                padding: 10px;
                font-size: 2em;
            }

            header h5{
                padding: 30px;
            }

            .foto{
                text-align: center;
            }
            .octavio{
                image-rendering: center;
            }

            .reseña{
                padding: 18px 0px 0px 459px;
                text-align: justify;
                line-height: 25px;
                font-size: 20px;
            }

            .centro{
                text-align: center;
                font-size: 25px;
                line-height: 40px;
            }

            .info{
                padding: 10px 0px 20px 459px; 
                line-height: 40px;  
            }
