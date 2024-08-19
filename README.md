# Adjusting the provided HTML template to include the requested content in Polish.
polish_html_content = """
<!doctype html>
<html class="no-js" lang="pl">

<head>
    <!-- meta data -->
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->

    <!--font-family-->
    <link href="https://fonts.googleapis.com/css?family=Poppins:100,200,300,400,500,600,700,800,900&amp;subset=devanagari,latin-ext" rel="stylesheet">
    
    <!-- title of site -->
    <title>Historia Adriana</title>

    <!-- For favicon png -->
    <link rel="shortcut icon" type="image/icon" href="assets/logo/favicon.png"/>
   
    <!--font-awesome.min.css-->
    <link rel="stylesheet" href="assets/css/font-awesome.min.css">

    <!--flat icon css-->
    <link rel="stylesheet" href="assets/css/flaticon.css">

    <!--animate.css-->
    <link rel="stylesheet" href="assets/css/animate.css">

    <!--owl.carousel.css-->
    <link rel="stylesheet" href="assets/css/owl.carousel.min.css">
    <link rel="stylesheet" href="assets/css/owl.theme.default.min.css">
    
    <!--bootstrap.min.css-->
    <link rel="stylesheet" href="assets/css/bootstrap.min.css">
    
    <!-- bootsnav -->
    <link rel="stylesheet" href="assets/css/bootsnav.css">    
    
    <!--style.css-->
    <link rel="stylesheet" href="assets/css/style.css">
    
    <!--responsive.css-->
    <link rel="stylesheet" href="assets/css/responsive.css">
    
    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    
    <!--[if lt IE 9]>
        <script src="https://oss.maxcdn.com/html5shiv/3.7.3/html5shiv.min.js"></script>
        <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->

</head>

<body>
    <!-- Top Area -->
    <header class="top-area">
        <div class="header-area">
            <!-- Start Navigation -->
            <nav class="navbar navbar-default bootsnav navbar-fixed dark no-background">
                <div class="container">
                    <!-- Start Header Navigation -->
                    <div class="navbar-header">
                        <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#navbar-menu">
                            <i class="fa fa-bars"></i>
                        </button>
                        <a class="navbar-brand" href="index.html">Podróż Adriana</a>
                    </div><!--/.navbar-header-->
                    <!-- End Header Navigation -->

                    <!-- Collect the nav links, forms, and other content for toggling -->
                    <div class="collapse navbar-collapse menu-ui-design" id="navbar-menu">
                        <ul class="nav navbar-nav navbar-right" data-in="fadeInDown" data-out="fadeOutUp">
                            <li class="smooth-menu active"><a href="#welcome-hero">Strona główna</a></li>
                            <li class="smooth-menu"><a href="#about">O mnie</a></li>
                            <li class="smooth-menu"><a href="#story">Historia</a></li>
                            <li class="smooth-menu"><a href="#future-plans">Plany na przyszłość</a></li>
                            <li class="smooth-menu"><a href="#contact">Kontakt</a></li>
                        </ul><!--/.nav -->
                    </div><!-- /.navbar-collapse -->
                </div><!--/.container-->
            </nav><!--/nav-->
            <!-- End Navigation -->
        </div><!--/.header-area-->
        <div class="clearfix"></div>
    </header><!-- /.top-area-->
    <!-- Top Area End -->
    
    <!-- Welcome Hero Start -->
    <section id="welcome-hero" class="welcome-hero">
        <div class="container">
            <div class="row">
                <div class="col-md-12 text-center">
                    <div class="header-text">
                        <h2>Cześć, jestem Adrian</h2>
                        <p>Moja podróż do zostania triathlonistą</p>
                    </div><!--/.header-text-->
                </div><!--/.col-->
            </div><!-- /.row-->
        </div><!-- /.container-->
    </section><!--/.welcome-hero-->
    <!-- Welcome Hero End -->

    <!-- About Start -->
    <section id="about" class="about">
        <div class="section-heading text-center">
            <h2>O mnie</h2>
        </div>
        <div class="container">
            <div class="about-content">
                <div class="row">
                    <div class="col-sm-6">
                        <div class="single-about-txt">
                            <h3>
                                Moja podróż rozpoczęła się, gdy znudzony pracą, siedząc na zaciskarce do papieru, rozmawiałem z kolegami. To właśnie wtedy wpadłem na pomysł, by zostać triathlonistą.
                            </h3>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section><!--/.about-->
    <!-- About End -->

    <!-- Story Start -->
    <section id="story" class="story">
        <div class="section-heading text-center">
            <h2>Moja Historia</h2>
        </div>
        <div class="container">
            <div class="story-content">
                <p>
                    Choć od dawna jeździłem na rowerze, nigdy wcześniej nie myślałem o triathlonie. Po podjęciu decyzji o rozpoczęciu treningów, pojawiły się pierwsze problemy - brak funduszy na strój, nowy rower oraz wszystkie potrzebne sprzęty. 
                </p>
                <p>
                    Rodzina na początku nie rozumiała mojego pomysłu, ale byłem wytrwały i dążyłem do spełnienia swojego marzenia. Wiele czytałem, oglądałem filmy na YouTube i studiowałem książki, aby dobrze przygotować się do mojego pierwszego wyścigu.
                </p>
                <p>
                    W zeszłym roku wziąłem udział w moim pierwszym triathlonie, a sukcesy zaczęły się pojawiać. Zacząłem angażować w mój świat sportu również moją narzeczoną.
                </p>
            </div>
        </div>
    </section><!--/.story-->
    <!-- Story End -->

    <!-- Future Plans Start -->
    <section id="future-plans" class="future-plans">
        <div class="section-heading text-center">
            <h2>Plany na przyszłość</h2>
        </div>
        <div class="container">
            <div class="future-plans-content">
                <p>
                    Kiedy zakończę swoją karierę sportową, po osiągnięciu wieku 30 lat, planuję stać się człowiekiem wielu pasji. Jedną z nich będzie gra na pianinie.
                </p>
            </div>
        </div>
    </section><!--/.future-plans-->
    <!-- Future Plans End -->

    <!-- Contact Start -->
    <section id="contact" class="contact">
        <div class="section-heading text-center">
            <h2>Kontakt</h2>
        </div>
        <div class="container">
            <div class="contact-content">
                <div class="row">
                    <div class="col-md-offset-1 col-md-5 col-sm-6">
                        <div class="single-contact-box">
                            <div class="contact-form">
                                <form>
                                    <div class="row">
                                        <div class="col-sm-6 col-xs-12">
                                            <div class="form-group">
                                                <input type="text" class="form-control" id="name" placeholder="Imię*" name="name">
                                            </div><!--/.form-group-->
                                        </div><!--/.col-->
                                        <div class="col-sm-6 col-xs-12">
                                            <div class="form-group">
                                                <input type="email" class="form-control" id="email" placeholder="Email*" name="email">
                                            </div><!--/.form-group-->
                                        </div><!--/.col-->
                                    </div><!--/.row-->
                                    <div class="row">
                                        <div class="col-sm-12">
                                            <div class="form-group">
                                                <input type="text" class="form-control" id="subject" placeholder="Temat" name="subject">
                                            </div><!--/.form-group-->
                                        </div><!--/.col-->
                                    </div><!--/.row-->
                                    <div class="row">
                                        <div class="col-sm-12">
                                            <div class="form-group">
                                                <textarea class="form-control" rows="8" id="comment" placeholder="Wiadomość"></textarea>
                                            </div><!--/.form-group-->
                                        </div><!--/.col-->
                                    </div><!--/.row-->
                                    <div class="row">
                                        <div class="col-sm-12">
                                            <div class="single-contact-btn">
                                                <a class="contact-btn" href="#"
                                                <a class="contact-btn" href="#" role="button">Wyślij</a>
                                            </div><!--/.single-contact-btn-->
                                        </div><!--/.col-->
                                    </div><!--/.row-->
                                </form><!--/form-->
                            </div><!--/.contact-form-->
                        </div><!--/.single-contact-box-->
                    </div><!--/.col-->
                </div><!--/.row-->
            </div><!--/.contact-content-->
        </div><!--/.container-->
    </section><!--/.contact-->
    <!-- Contact End -->

    <!-- Footer Start -->
    <footer id="footer-copyright" class="footer-copyright">
        <div class="container">
            <div class="hm-footer-copyright text-center">
                <p>
                    &copy; 2024 Podróż Adriana. Projekt i rozwój: Adrian.
                </p><!--/p-->
            </div><!--/.text-center-->
        </div><!--/.container-->

        <div id="scroll-Top">
            <div class="return-to-top">
                <i class="fa fa-angle-up " id="scroll-top" ></i>
            </div>
        </div><!--/.scroll-Top-->
    </footer><!--/.footer-copyright-->
    <!-- Footer End -->

    <!-- Include all js compiled plugins (below), or include individual files as needed -->
    <script src="assets/js/jquery.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/modernizr/2.8.3/modernizr.min.js"></script>
    <script src="assets/js/bootstrap.min.js"></script>
    <script src="assets/js/bootsnav.js"></script>
    <script src="assets/js/jquery.sticky.js"></script>
    <script src="assets/js/progressbar.js"></script>
    <script src="assets/js/jquery.appear.js"></script>
    <script src="assets/js/owl.carousel.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery-easing/1.4.1/jquery.easing.min.js"></script>
    <script src="assets/js/custom.js"></script>
</body>

</html>
