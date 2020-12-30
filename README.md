<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="node_modules/bootstrap/dist/css/bootstrap.min.css" />
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lobster|Open+Sans" />
    /<link rel="stylesheet" href="css/deviceful.css" />
    <link rel="stylesheet" href="node_modules/font-awesome/css/font-awesome.min.css" />
    <title>Deviceful Designs</title>
    <style>
    body {
    font-family: "Open Sans", sans-serif;
}

h1, h2, h3 {
    font-family: "Lobster", cursive;
}

h2 {
    color: black;
}

header h2 {
    color: #CEC8FF;
}

footer{
    background-image: linear-gradient(blue,white);
    padding: 20px 0;
}

.jumbotron {
    margin: 0;
    padding: 30px;
    background-image: linear-gradient(white,blue);
    color: rgb(17, 17, 17);
    text-align: center;
}
.row-content {
    padding: 50px 0;
    border-bottom: 1px ridge;
    min-height: 200px;
}

.navbar {
    background-color: #140970;
}

.tab-content {
    border: 1px solid #DDD;
    border-top: none;
    padding: 10px;
}

.carousel-caption {
    background-color: rgba(0, 0, 0, 0.5);
}

.carousel {
    border: solid #5637DD;
}

h5 {
    color: black;
}

background {
    background-color: #140970 ;
}
</script>
</head>

<body>
    <header class="jumbotron jumbotron-fluid">
        <div class="container">
            <div class="col">
                <h5 style="text-align: left;">Your case </h5>
                <h5 style="text-align: right;"> your way</h5>
                <div class="col">
                     <h1 style="font-size: 500 PX;">Deviceful Designs</h1>
                </div>
            </div>
        </div>
    </header>
    <nav class="navbar navbar-expand-sm navbar-dark sticky-top">
        <div class="container">
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#nucampNavbar">
             <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#nucampNavbar">
                 <span class="navbar-toggler-icon"></span>
             </button>
             <div class="collapse navbar-collapse" id="nucampNavbar">
                 <ul class="navbar-nav">    
                     <ul class="navbar-nav">
                        <li class="nav-item "><a class="nav-link" href="index.html"><i class="fa fa-home fa lg"></i>Home</a></li>
                        <li class="nav-item "><a class="nav-link" href="contactus.html"><i class="fa fa-address-card fa lg"></i>Contact</a></li>
                        <li class="nav-item "><a class="nav-link" href="Shop.html"><i class="fas fa-store"></i>Store</a></li>
                     </ul>
                 </ul>
             </div>
        </div>
    </nav>

    <div class="container">
        <div class="row row-content">
            <div class="col-6 mx-auto">
                <div id="homeCarousel" class="carousel slide" data-ride="carousel">
                    <ol class="carousel-indicators">
                        <li data-target="#homeCarousel" data-slide-to="0" class="active"></li>
                        <li data-target="#homeCarousel" data-slide-to="1"></li>
                        <li data-target="#homeCarousel" data-slide-to="2"></li>
                    </ol>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img class="d-block  w-100" src="img/Clearcases.PNG" alt="Clear Phone cases" />
                            <div class="carousel-caption">
                                <h3>clear Phone Cases</h3>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img class="d-block w-100" src="img/Customipadcases.PNG" alt="Custom Photo Cases" />
                            <div class="carousel-caption">
                                <h3>Custom Ipad Cases</h3>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img class="d-block w-100" src="img/Customphotocases.PNG" alt="Custom Photo Cases" />
                            <div class="carousel-caption">
                                <h3>Custom Photo Cases</h3>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img class="d-block w-100" src="img/Leathercases.PNG" alt="Leather Cases" />
                            <div class="carousel-caption">
                                <h3>Leather Cases</h3>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img class="d-block w-100" src="img/Designercase.PNG" alt="Designer Cases" />
                            <div class="carousel-caption">
                                <h3>Designer Cases</h3>
                            </div>
                        </div> 
                    </div>
                    <a class="carousel-control-prev" href="#homeCarousel" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon"></span>
                        <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#homeCarousel" role="button" data-slide="next">
                        <span class="carousel-control-next-icon"></span>
                        <span class="sr-only">Next</span>
                    </a>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <div class="container">
            <div class="row">             
                <div class="col-4 col-sm-2 offset-1">
                    <h5>Links</h5>
                    <ul class="list-unstyled">
                        <li class="nav-item "><a class="nav-link" href="index.html"><i class="fa fa-home fa lg"></i>Home</a></li>
                        <li class="nav-item "><a class="nav-link" href="contactus.html"><i class="fa fa-address-card fa lg"></i>Contact</a></li>
                    </ul>
                </div>
                <div class="col-6 col-sm-5 text-center">
                    <h5>Social</h5>
                    <a href="http://instagram.com/">Instagram</a>
                    <a href="http://facebook.com/">Facebook</a>
                    <a href="http://twitter.com/">Twitter</a>
                    <a href="http://youtube.com/">YouTube</a>
                </div>
                <div class="col-sm-4 text-center">
                    Email: mcdonnelljames44@gmail.com
                </div>                
           </div>
        </div>
    </footer>
    <script src="node_modules/jquery/dist/jquery.slim.min.js"></script>
    <script src="node_modules/popper.js/dist/umd/popper.min.js"></script>
    <script src="node_modules/bootstrap/dist/js/bootstrap.min.js"></script>

</body>

</html>
