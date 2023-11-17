<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Drogueria La Economia</title>
    <link rel="stylesheet" href="estilos.css">
    <script src="https://kit.fontawesome.com/e6d3741188.js" crossorigin="anonymous"></script>
    
</head>

<body class="hidden">
    <div class="centrado" id="onload">
        <div class="lds-facebook"><div></div><div></div><div></div></div>
    </div>
    <header>
        <nav id="nav" class="nav1">
            <div class="contenedor-nav">
                <div class="logo">
                    <img src="img/logo.png" alt="" width="100" height="800">
                </div>
                <div class="enlaces" id="enlaces">
                    <a href="#" id="enlace-inicio" class="btn-header">Inicio</a>
                    <a href="#" id="enlace-equipo" class="btn-header">Equipo</a>
                    <a href="pagina2.html" id="enlace-servicio" class="btn-header">Servicios</a>
                    <a href="#" id="enlace-trabajo" class="btn-header">Trabajos</a>
                    <a href="#" id="enlace-contacto" class="btn-header">Contacto</a>
                </div>
                <div class="icono" id="open">
                    <span>&#9776;</span>
                </div>
            </div>
        </nav>
        <div class="textos">
            <h1>Drogueria La Economia</h1>
            <h2>Tame - Arauca</h2>
        </div>
    </header>
    <main>
        <section class="team contenedor" id="equipo">
            <h3>Nuestro equipo</h3>
            <p class="after">Estamos para servirte en lo que necesites</p>
            <div class="card">
                <div class="content-card">
                    <div class="people">
                        <img src="img/people1.jpg" alt="">
                    </div>
                    <div class="texto-team">
                        <h4>Aurelio</h4>
                        <p>Farmaceutico</p>
                    </div>
                </div>
                <div class="content-card">
                    <div class="people">
                        <img src="img/people2.jpg" alt="">
                    </div>
                    <div class="texto-team">
                        <h4>Sophia</h4>
                        <p>Farmaceutica</p>
                    </div>
                </div>
                <div class="content-card">
                    <div class="people">
                        <img src="img/people3.jpg" alt="">
                    </div>
                    <div class="texto-team">
                        <h4>Marcela</h4>
                        <p>Farmaceutica</p>
                    </div>
                </div>
                <!--agrego un nuevo content-card a mi gusto-->
                <div class="content-card">
                    <div class="people">
                        <img src="img/people4.jpg" alt=""> <!--cambio imagen-->
                    </div>
                    <div class="texto-team">
                        <h4>Sasha</h4>
                        <p>Administradora Farmaceutica</p>
                    </div>
                </div>
                
            </div>
        </section>
        <section class="about" id="servicio">
            <div class="contenedor">
                <h3>Nuestros servicios</h3>
                <p class="after">Siempre mejorando para ti</p>
                <div class="servicios">
                    <div class="caja-servicios">
                        <img src="img/24h.png" alt="" width="200" height="200">
                        <h4>Servicio 24 horas</h4>
                        <p>Atendemos de Lunes a Domingo</p>
                    </div>
                    <div class="caja-servicios">
                        <img src="img/dom.png" alt="">
                        <h4>Servicio a domicilio</h4>
                        <p>Los domicilios se realizan de Lunes a viernes de 8:00am a 9:00pm</p>
                    </div>
                    <div class="caja-servicios">
                        <img src="img/inyec.png" alt="">
                        <h4>Servicio de Inyectologia</h4>
                        <p>Contamos con personal apto para aplicar inyecciones</p>
                    </div>
                </div>
            </div>
        </section>
        <section class="work contenedor" id="trabajo">
            <h3>Nuestros productos</h3>
            <p class="after">Todo lo que necesitas en un solo lugar</p>
            <div class="botones-work">
                <ul>
                    <li class="filter active" data-nombre='todos'>Todos</li>
                    <li class="filter" data-nombre='diseño'>Cosmeticos</li>
                    <li class="filter" data-nombre='programacion'>Farmaceuticos</li>
                    <li class="filter" data-nombre='marketing'>Aseo</li>
                </ul>
            </div>
            <div class="galeria-work">
                <div class="cont-work programacion">
                    <div class="img-work">
                        <img src="img/far1.png" alt="">
                    </div>
                    <div class="textos-work">
                        <h4>Acetaminofen 500 mg</h4>
                    </div>
                </div>
                <div class="cont-work programacion">
                    <div class="img-work">
                        <img src="img/far2.jpg" alt="">
                    </div>
                    <div class="textos-work">
                        <h4>Ibuprofeno</h4>
                    </div>
                </div>
                <div class="cont-work programacion">
                    <div class="img-work">
                        <img src="img/far3.png" alt="">
                    </div>
                    <div class="textos-work">
                        <h4>Jarabe para la tos</h4>
                    </div>
                </div>
                <div class="cont-work diseño">
                    <div class="img-work">
                        <img src="img/cos1.jpg" width="2000" height="2000">
                    </div>
                    <div class="textos-work">
                        <h4>Esmalte Masglo</h4>
                    </div>
                </div>
                <div class="cont-work diseño">
                    <div class="img-work">
                        <img src="img/cos2.jpg" alt="">
                    </div>
                    <div class="textos-work">
                        <h4>Polvos para la cara</h4>
                    </div>
                </div>
                <div class="cont-work diseño">
                    <div class="img-work">
                        <img src="img/cos3.jpg" alt="">
                    </div>
                    <div class="textos-work">
                        <h4>Brillo labial</h4>
                    </div>
                </div>
                <div class="cont-work marketing">
                    <div class="img-work">
                        <img src="img/ase1.jpg" alt="">
                    </div>
                    <div class="textos-work">
                        <h4>Shampoo Head and Shoulders</h4>
                    </div>
                </div>
                <div class="cont-work marketing">
                    <div class="img-work">
                        <img src="img/ase2.jpg" alt="">
                    </div>
                    <div class="textos-work">
                        <h4>Crema dental Colgate</h4>
                    </div>
                </div>
                <div class="cont-work marketing">
                    <div class="img-work">
                        <img src="img/ase3.jpg" alt="">
                    </div>
                    <div class="textos-work">
                        <h4>Jabon Palmolive</h4>
                    </div>
                </div>
            </div>
        </section>
    </main>
    <footer id="contacto">
        <div class="footer contenedor">
            <div class="marca-logo">
                <img src="img/logo.png" alt="">
            </div>
            <div class="iconos">
                <i class="fab fa-youtube"></i>
                <i class="fab fa-facebook-square"></i>
                <i class="fab fa-twitter"></i>
            </div>
            <p>5 años cuidando la salud de los Colombianos</p>
        </div>

    </footer>
    <script src="js/jquery.js"></script>
    <script src="js/main.js"></script>
    <script src="js/filtro.js"></script>
</body>
</html>
