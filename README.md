<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
        <link rel="stylesheet" type="text/css" href="style.css">
        <link rel="icon"  href="logo.png">	
        <title>Fitness!!!</title>
    </head>
    <body>

        <header id="home">
            <nav class="navbar navbar-expand-lg navbar-custom navbar-light bg-light fixed-top">
                <div class="container">
                    <a class="navbar-brand" href="https://www.nike.com/">
                        <img src="logo.png" width="40" height="30" class="d-inline-block align-top" alt="">
                        Stay in fit
                    </a>
                    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
                         <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse" id="navbarResponsive">
                        <ul class="navbar-nav ml-auto">
                            <li class="nav-item">
                                <a class="nav-link" href="#home"><i class="fas fa-home"></i> Home</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#about">Info</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#two">Stay fit</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#one">Application</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#contacts">Contacts</a>
                            </li>
                        </ul>
                        <form class="d-flex">   
                            <input class="form-control me-2" required type="search" placeholder="Search" aria-label="Search"  id="search" name="q">
                        </form>
                        
                            <button class="btn btn-outline-success button-custom" type="submit" onclick="search()">Search </button>
                    </div>
                </div>
            </nav>
        </header>
        <header>
          <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
              <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
              <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
              <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
            </ol>
            <div class="carousel-inner" role="listbox">
              <!-- Slide One - Set the background image for this slide in the line below -->
              <div class="carousel-item active" style="background-image: url('one.jpg')">
                <div class="carousel-caption d-none d-md-block">
                </div>
              </div>
              <!-- Slide Two - Set the background image for this slide in the line below -->
              <div class="carousel-item" style="background-image: url('two.jpg')">
                <div class="carousel-caption d-none d-md-block">
                </div>
              </div>
              <!-- Slide Three - Set the background image for this slide in the line below -->
              <div class="carousel-item" style="background-image: url('three.jpg')">
                <div class="carousel-caption d-none d-md-block">
                </div>
              </div>
            </div>
            <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
                  <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                  <span class="sr-only">Previous</span>
                </a>
            <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
                  <span class="carousel-control-next-icon" aria-hidden="true"></span>
                  <span class="sr-only">Next</span>
                </a>
          </div>
        </header>
        <div id="about">
            <h1 class="Elon">About the app</h1>
            <div class="alltext">
                <div class="bio">
                    <img class="info-images" src="qwe.jpg">
                    <p class="childhood">Workout with a wide selection of workouts and Programs*, get motivated with our Nike Trainers and gain tips for complete wellness. From home workouts to healthy recipes — strengthen both your mind and body with world-class personal trainers and wellness experts.
                    Easily find the perfect workout for staying active at home, from low intensity to high, including:
                        • YOGA: Essential Yoga Flows for Every Day

                        • CORE & STRENGTH: Best of Abs, Arms, and Glutes

                        • HOME WORKOUTS: Big Workouts for Small Spaces

                        • QUICK FITNESS: Done in Under 20 Min

                        • ALL ATHLETES: Exercises for all levels
                    </p>
                    <br>
                    <br>
                    <br>
                    <br>
                    <br>
                </div>
                <div class="bio">
                    <img class="info-images2" src="rty.jpg">
                    <p class="childhood1">WORKOUTS FOR ATHLETES OF ALL LEVELS

                        • HIT workouts, strength training, ab and core workouts, full body workouts, yoga, stretch and more - all available straight from your phone

                        • Home fitness is easier than ever with free workouts you can do with minimal to no equipment

                        • No matter how you get your sweat on, start with an inspiring trainer to get you started

                        • Workout by body part: target your abs and core, arms and shoulders, and glutes and legs

                        • New workouts every week with the trainers you love, with new in-class music curated for every workout

                        • Exercise & healthy habits are built with workout scheduling - schedule your workouts and receive reminders beforehand
                        </p>
                    
                    <br>
                    <br>
                    <br>
                    <br>
                </div>  
            </div>
        </div>
        <div class="two" id="two">
            <div class="transbox">
                <div class="fade"></div>
                <section class="star-wars">
                  <div class="crawl">
                    <div class="title">
                      <p>BENEFITS OF TRAINING</p>
                      <h1>Long life</h1>
                    </div>
                    <p>Physical activity can improve cognitive function in healthy elderly persons, and potentially reduces the risk of developing cognitive impairment.</p>
                      <br>
                      <p> Regular exercise can help increase your libido.  When you exercise, the brain produces endorphins that stimulate the release of sex hormones.</p>

                      <br>
                    <p> Exercise helps the intestinal muscles break down food and move it through your system correctly by strengthening the abdominal muscles and minimizing sluggishness.</p>
                  </div>
                </section>
            </div>
        </div>
        <div class="videos">
            <h1 style="padding: 40px; font-size: 50px; font-family: 'Playfair Display', serif;">Stay in fit</h1>
            <iframe width="75%" height="500px" 
                src="https://www.youtube.com/embed/WYP9AGtLvRg?autoplay=1&mute=1&loop=1" frameborder="0" allowfullscreen autoplay="1" loop="true" class="video">
            </iframe>
        </div>
        <div class="one" id="one">
            <div class="transbox">
                <h1>Application</h1>
                <p>Home fitness is easier than ever with free workouts you can do with minimal to no equipment.No matter how you get your sweat on, start with an inspiring trainer to get you started.Workout by body part: target your abs and core, arms and shoulders, and glutes and legs </p>
                <div class="btnn">
                    <a href="#">Learn More</a>
                </div>
            </div>
        </div>
        <div class="map">
            <h1>Our Locations</h1>
            <h1 style="letter-spacing: 5px; padding-left: 4%;">         AITU     |         Life Fitness  </h1>
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2847.5739583689096!2d71.41575686696537!3d51.090907977054435!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x424585a605525605%3A0x4dff4a1973f7567e!2sAstana%20IT%20University!5e0!3m2!1sru!2skz!4v1645173752704!5m2!1sru!2skz" class="map1" style="border:0;" allowfullscreen="" loading="lazy">
            </iframe>
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d10017.510330747571!2d71.42090066977539!3d51.11994299999998!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x424584180f4d608f%3A0xf8bc2369255634a5!2sLife%20Fitness%20Astana!5e0!3m2!1sru!2skz!4v1645173875700!5m2!1sru!2skz" class="map1" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
        </div>
        <footer id="contacts">
            <br>
            <h1>Made by NYSA</h1>
            <h2><i class="fas fa-phone"></i> +7(747)239-12-25</h2>
            <a href="https://www.instagram.com/nurgiiss/"> <img src="https://cdn.freebiesupply.com/images/large/2x/instagram-icon-white-on-black-circle.png" height="50" width="60"> </a>  
            <a href="mailto:tasnur2002@gmail.com"> <img src="gmail.png"height="50" width="45"> </a> 
            <a href="https://vk.com/nurgissa"> <img src="facebook.jpg"height="50" width="45"> </a>
        </footer>
        <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
        <script src="script.js"></script>
        <script src="https://unpkg.com/lunr/lunr.js"></script>
        <script src="https://kit.fontawesome.com/bca801d50d.js" crossorigin="anonymous"></script
>    </body>
</html>
