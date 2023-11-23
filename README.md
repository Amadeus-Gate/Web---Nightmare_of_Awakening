<!DOCTYPE html>
<html lang="ES">
    <head>
        <title>Prototipo</title>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css">
        <script src="https://cdn.jsdelivr.net/npm/jquery@3.6.4/dist/jquery.slim.min.js"></script>
        <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"></script>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <!--===================Barra de Navegación===================-->
        <nav class="navbar navbar-expand-md navbar-dark">
            <a class="navbar-brand" href="#">
                <a href="Index.html" class="logo me-auto me-lg-0 img-fluid"><img src="img/logo.png" alt="" width="90px"></a>
            </a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
          
                 <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item active">
                        <a class="nav-link" href="#">Home</a>
                        </li>
                        <li class="nav-item">
                        <a class="nav-link" href="#">Acerca de nosotros</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Contacto</a>
                        </li>
                        <li class="nav-item">
                          <a class="nav-link" href="https://github.com/Amadeus-Gate/DM_Integral">Otras aplicaciones</a>
                      </li>
                  </div>
                </li>
              </ul>
            </div>
          </nav>
          <!--===================Banner===================-->
          <div class="container-fluid banner d-flex justify-content-center align-items-center text-center">
            <div class="row">
              <div class="col-12">
                <h1 class="mb-5 title">Nightmare of awakening</h1>
                <p class="mb-5">En "Nightmare of Awakening", te embarcarás en un aterrador viaje hacia los rincones más oscuros de la mente humana. Después de sobrevivir a un accidente automovilístico en una remota y nebulosa carretera, te despiertas en un mundo alterado, donde la realidad se entrelaza con los peores temores de tu subconsciente. ¿Podras sobrevivir?</p>
                
                <!--Hipervinculo DEMO-->
                <a href="https://drive.google.com/file/d/19disGW8o5GQpQk3vPevHxwQiFtFSZSVM/view?usp=drive_link">
                <button class="btn btn-dark mt-5">¡Prueba nuestra DEMO!</button>
                </a>

              </div>
            </div>
          </div>
          <!--===============Pagina principal===============-->
          <main>
            <div class="container">
              <div class="roW la-empresa text-center my-5">
                <h2>Nuestra empresa</h2>
                <p>En Amadeus;Gate, nos dedicamos a la creación de experiencias de juego excepcionales que transportan a jugadores a mundos imaginarios, desafiándolos a explorar, aprender y disfrutar. Nos esforzamos por fusionar la innovación tecnológica con la creatividad sin límites para ofrecer títulos que no solo entretienen, sino que también inspiran y conectan a la comunidad global de jugadores.</p>
              </div>
            
            <!--===============Acerca de nosotros===============-->
              <div class="container">
                <div class="roW la-empresa text-center my-5">
                  <h2>Acerca de nosotros</h2>
              </div>
              <!--Misión y Visión-->
                <div class="container">
                  <div class="row text-center my-5">
                    <div class="col-md-6">
                      <h2>Misión</h2>
                      <p>Crear experiencias de entretenimiento inigualables a través de videojuegos innovadores que cautiven a jugadores de todas las edades. Nos esforzamos por ofrecer emociones, historias envolventes y calidad excepcional en cada uno de nuestros títulos, estableciendo así un vínculo duradero con nuestra comunidad de jugadores</p>
                    </div>
                    <div class="col-md-6">
                      <h2>Visión</h2>
                      <p>Ser reconocidos como líderes en la industria de los videojuegos, impulsados por la creatividad, la tecnología de vanguardia y la pasión por ofrecer experiencias de juego memorables. Aspiramos a ser pioneros en la creación de mundos virtuales que inspiren, conecten y desafíen a jugadores de todo el mundo, posicionándonos como referentes en la convergencia de la narrativa y la tecnología</p>
                    </div>
                  </div>
                </div>
                
                <!--Trailer dejuego-->
                <div class="container negro">
                  <div class="roW la-empresa text-center my-5">
                    <h2>¡Trailer de nuestro proximo proyecto!</h2>
                    <iframe width="500px" height="500px" src="https://www.youtube.com/embed/6bVIIr2gcD4" title="Nightmare of Awakening Trailer #1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
                </div>
                <!--===============Nuestros productos===============-->
                <div class="container">
                  <div class="roW la-empresa text-center my-5">
                    <h2>Nuestros productos</h2>
                </div>
                <!--Producto 1-->
                <div class="row productos">
                    <div class="col-md-4 col-12 my-4">
                      <div class="card">
                        <img src="./img/prod3.png" class="card-img oscurecer" alt="" height="500px" width="500px">
                        <div class="card-img-overlay d-flex flex-column justify-content-center align-items-center">
                          <h3>SMT III: Nocturne</h3>
                          
                        </div>
                      </div>
                    </div>
                  <!--Producto 2-->
                    <div class="col-md-4 col-12 my-4">
                      <div class="card">
                        <img src="./img/prod2.jpg" class="card-img oscurecer" alt="" height="500px" width="500px">
                        <div class="card-img-overlay d-flex flex-column justify-content-center align-items-center">
                          <h3>SMT IV: Apocalipsis</h3>
                        </div>
                      </div>
                    </div>
                  <!--Producto 3-->
                  <div class="col-md-4 col-12 my-4">
                    <div class="card">
                      <img src="./img/prod.jpg" class="card-img oscurecer" alt="" height="500px" width="500px">
                      <div class="card-img-overlay d-flex flex-column justify-content-center align-items-center">
                        <h3>Shin Megami Tensei</h3>
                        <p> </p>
                      </div>
                    </div>
                  </div>
                </div>
          </main>
          <!--===============Contacto===============-->
          <!--===============Footer===============-->
          <footer class="text-light text-center py-3">
            <div class="container">
              <p>
                <a href="#">Términos y Condiciones</a> | <a href="#">Aviso de Privacidad</a>
              </p>
                &copy; Created by: Amadeus; Gate 2023
            </div>
        </footer>
    </body>
</html>
