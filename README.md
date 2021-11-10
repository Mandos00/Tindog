# Tindog<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>TinDog</title>
  <link rel="stylesheet" href="css/styles.css">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
  <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@100;400;900&family=Ubuntu:wght@300;400;500&display=swap" rel="stylesheet">
  <script defer src="https://use.fontawesome.com/releases/v5.0.7/js/all.js"></script>
</head>

<body>
  <section id="title">
    <div class="container-fluid">

      <!-- Nav Bar -->
      <nav class="navbar navbar-expand-lg navbar-dark">

        <a class="navbar-brand" href="">tindog</a>

        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo01" aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarTogglerDemo01">

          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link" href="">Contact</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="">Pricing</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="">Download</a>
            </li>
          </ul>
        </div>
      </nav>

      <!-- Title -->
      <div class="row">
        <div class="col-lg-6">
          <h1 class="hi">Meet new and interesting dogs nearby.</h1>
          <button type="button" class="btn btn-dark btn-lg download-button"><i class="fab fa-apple"></i> Download</button>
          <button type="button" class="btn btn-outline-light btn-lg download-button"><i class="fab fa-google-play"></i>Download</button>
        </div>

        <div class="col-lg-6">
          <img class="tittle-image" src="images/iphone6.png" alt="iphone-mockup">
        </div>
      </div>

    </div>
  </section>

  <!-- Features -->
  <section id="features">

    <div class="row">
      <div class="feature-box col-lg-4">
        <i class="icon fas fa-check-circle fa-3x "></i>
        <h3>Easy to use.</h3>
        <p>So easy to use, even your dog could do it.</p><br>
      </div>

      <div class="feature-box col-lg-4">
        <i class="icon fas fa-bullseye fa-3x"></i>
        <h3>Elite Clientele</h3>
        <p>We have all the dogs, the greatest dogs.</p><br>
      </div>

      <div class="feature-box col-lg-4">
        <i class="icon fas fa-heart fa-3x"></i>
        <h3>Guaranteed to work.</h3>
        <p>Find the love of your dog's life or your money back.<br>
      </div>

    </div>
  </section>

  <!-- Testimonials -->
  <section id="testimonials">

    <div id="testimonial-carousel" class="carousel slide" data-ride="false">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <h2 class="hit">I no longer have to sniff other dogs ass for love. I've found the hottest Corgi on TinDog. Woof.</h2>
          <img class="testimonial-image" src="images/dog-img.jpg" alt="dog-profile">
          <em>Pebbles, New York</em>
        </div>
        <div class="carousel-item">
          <h2 class="hit"> My dog used to be so lonely, but with TinDog's help, they've found the love of their life. I think.</h2>
          <img class="testimonial-image" src="images/lady-img.jpg" alt="lady-profile">
          <em>Beverly, Illinois</em>
        </div>
      </div>


      <a class="carousel-control-prev" href="#testimonial-carousel" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon"></span>
      </a>
      <a class="carousel-control-next" href="#testimonial-carousel" role="button" data-slide="next">
        <span class="carousel-control-next-icon"></span>
      </a>
    </div>
  </section>


  <!-- Press -->

  <section id="press">
    <img class="press-logo" src="images/techcrunch.png" alt="tc-logo">
    <img class="press-logo" src="images/tnw.png" alt="tnw-logo">
    <img class="press-logo" src="images/bizinsider.png" alt="biz-insider-logo">
    <img class="press-logo" src="images/mashable.png" alt="mashable-logo">

  </section>


  <!-- Pricing -->



  <section id="pricing">

    <h2>A Plan for Every Dog's Needs</h2>
    <p>Simple and affordable price plans for your and your dog.</p>

    <div class="row">
      <div class="pricing-column col-lg-4 col-md-6">
        <div class="card">
          <div class="card-header">
            <h3>Chihuahua</h3>
          </div>
          <div class="cad-body">
            <h2>Free</h2>
            <p>5 Matches Per Day</p>
            <p>10 Messages Per Day</p>
            <p>Unlimited App Usage</p>
            <button type="button" class="btn btn-outline-dark btn-lg btn-block">Sign Up</button>
          </div>
        </div>
      </div>

      <div class="pricing-column col-lg-4 col-md-6">
        <div class="card">
          <div class="card-header">
            <h3>Labrador</h3>
          </div>
          <div class="cad-body">
            <h2>$49 / mo</h2>
            <p>Unlimited Matches</p>
            <p>Unlimited Messages</p>
            <p>Unlimited App Usage</p>
            <button type="button" class="btn btn-dark btn-lg btn-block">Sign Up</button>
          </div>
        </div>
      </div>

      <div class="pricing-column col-lg-4 col-md-12">
        <div class="card">
          <div class="card-header">
            <h3>Mastiff</h3>
          </div>
          <div class="cad-body">
            <h2>$99 / mo</h2>
            <p>Pirority Listing</p>
            <p>Unlimited Matches</p>
            <p>Unlimited Messages</p>
            <p>Unlimited App Usage</p>
            <button type="button" class="btn btn-dark btn-lg btn-block">Sign Up</button>
          </div>
        </div>
      </div>
    </div>
  </section>


  <!-- Call to Action -->

  <section id="cta">

    <h3>Find the True Love of Your Dog's Life Today.</h3>
    <button type="button">Download</button>
    <button type="button">Download</button>

  </section>


  <!-- Footer -->

  <footer id="footer">

    <p>© Copyright 2018 TinDog</p>

  </footer>


</body>

</html>
