Aqui almacenarás todo lo referente a tú proyecto




HTML
         
         
         <!DOCTYPE html>
             <html lang="en">
             <head>

                 <meta charset="UTF-8">
                 <meta http-equiv="X-UA-Compatible" content="IE=edge">
                 <meta name="viewport" content="width=device-width, initial-scale=1.0">
                 <title>PILARES</title>
                 <link rel="stylesheet" href="css/estilos.css">
             </head>
             <body>
                 <main>
                      <div class="cuadro">
                         <p> <b>PILARES </b> </p>
                      </div>

                      <div class="blanco">
                          <p> <b>¿Qué es? </b><br>
                          Son puntos de encuentro de y para la ciudadanía, en ellos encontrarás: 
                          ciberescuelas, disciplinas artísticas, actividades deportivas, talleres de emprendimiento y capacitación para el empleo.<br>
                          </p>
                      </div>

                         <div class="recreacion"> 
                             <p><b>RECREACIÓN</b></p>
                         </div>  

                         <div class="negro">
                                 <p>Proyecto<br>
                                 Son puntos de encuentro de y para la ciudadanía, en ellos encontrarás:<br>
                                 ciberescuelas, disciplinas artísticas, actividades deportivas, talleres de emprendimiento y capacitación para el empleo. <br>
                                 </p>
                          </div>

                             <div class="conexion">
                                 <p><b>CONEXIÓN</b></p>
                          </div>
                          <div class="negro">
                                 <p>¿Qué ofrece?<br>
                                 Son puntos de encuentro de y para la ciudadanía, en ellos encontrarás:<br>
                                 ciberescuelas, disciplinas artísticas, actividades deportivas, talleres de emprendimiento y capacitación para el empleo.  <br>
                                 </p>
                          </div>

                         <div class="comunidad">
                             <p><b>EMPODERAMIENTO</b></p>
                                        </div>  
                 </main>

             </body>
             </html>
             
  CSS
  
          *{
            margin: 0;
            padding: 0;
        }

        .cuadro{
            height: 50vh;
            width: 100%;
            margin: auto;
            background: url(../img/pilares.jpg);
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
            background-attachment: fixed;
            display: flex;
            align-items: center;
            justify-content: center;
            opacity: .8;
        }
        .cuadro p{
            color: white;
            font-size: 30px;
            background-color: rgb(7, 7, 7);
            text-align: center;
        }

        .blanco{
            font-size: 30px;
            background-color: azure;
            text-align: center;

        }

        .recreacion{
            height: 50vh;
            width: 100%;
            margin: auto;
            background: url(../img/pilares2.jpg);
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
            background-attachment: fixed;
            display: flex;
            align-items: center;
            justify-content: center;
            opacity: .8;
        }

        .recreacion p{
            font-size: 30px;
            background-color: azure;
            text-align: center;
        }

        .conexion{
            height: 50vh;
            width: 100%;
            margin: auto;
            background: url(../img/pilares3.jpg);
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
            background-attachment: fixed;
            display: flex;
            align-items: center;
            justify-content: center;
            opacity: .8;
        }

        .conexion p{
            font-size: 30px;
            background-color: azure;
            text-align: center;
        }

        .comunidad{
            height: 50vh;
            width: 100%;
            margin: auto;
            background: url(../img/pilares4.jpg);
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
            background-attachment: fixed;
            display: flex;
            align-items: center;
            justify-content: center;
            opacity: .8;
        }

        .comunidad p{
            color: white;
            font-size: 30px;
            background-color: rgb(7, 7, 7);
            text-align: center;
        }

        .negro{
            font-size: 30px;
            color: white;
            background-color: rgb(7, 7, 7);
            text-align: center;
        }    
