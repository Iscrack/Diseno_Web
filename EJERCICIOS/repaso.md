              <!DOCTYPE html>
              <html lang="en">
              <head>
                  <meta charset="UTF-8">
                  <meta http-equiv="X-UA-Compatible" content="IE=edge">
                  <meta name="viewport" content="width=device-width, initial-scale=1.0">
                  <title>Evaluación HTML</title>
              </head>
              <link rel="stylesheet" href="css/estilos.css">
              <body>
                  <header>
                      <h1>ENCABEZADO NIVEL 1</h1>
                      <nav>
                         <ul>
                             <li><a href="">ENLACE1</a></li>
                             <li><a href="">ENLACE2</a></li>
                             <li><a href="">ENLACE3</a></li>
                             <li><a href="">ENLACE4</a></li>
                         </ul>
                      </nav>
                  </header>

                  <main>  
                      <section>
                          <h2>
                              Encabezado nivel 2
                          </h2>
                          <p>Aquí va el texto del primer párrafo</p>
                          <p>Aquí va el texto del segundo párrafo</p>
                      </section>    
                      <aside>                   
                          <h2>
                              Apartado
                          </h2>
                          <p>
                              Elije una opción
                          </p>
                          <form>
                             <label><input type="radio" name="opcion">Opción1</label><br>
                             <label><input type="radio" name="opcion">Opción2</label><br>
                             <label><input type="radio" name="opcion">Opción3</label><br>
                             <input type="submit">
                          </form>        
                      </aside>
                  </main>

                  <footer>
                      <p>Sección de información de contacto, derechos de autor, etc.</p>
                  </footer>
              </body>
              </html>
              
              
                *{
                    margin: 0;
                    padding: 0;
                }
                p{
                    color:#004BA8; 
                }
                header{
                    background-color: rgba(0, 0, 0, 0.822);
                }
                h1{
                    color:#8FC0A9;
                    text-align: center;
                }
                nav{
                    background-color:#8FC0A9;
                }
                ul{
                    color:black;
                }

                section{
                    background-color:aqua;
                    text-align: center;
                }

                aside{
                    background-color: rgb(226, 26, 176);
                    text-align: center;
                }
                footer{
                    background-color: yellow;
                    text-align: center;
                }
