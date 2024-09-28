<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital@0;1&display=swap" rel="stylesheet">
  <link rel= "icon" href= ./assests/logo.png>
  <title>Spotify - web player music for everyone</title>
  <link href="style.css" rel="stylesheet">
</head>
<body>
  <div class="main">
    <div class="sidebar">
      <div class="nav">
        <div class="nav-option">
          <i class="fa-solid fa-house"></i>
          <a href="#">Home</a>
        </div>
        <div class="nav-option">
          <i class="fa-solid fa-magnifying-glass"></i>
          <a href="#">search</a>
        </div>
      </div>
      <div class="library">
        <div class="option">
          <div class="library-option nav-option">
            <img src="assests/library_icon.png">
            <a href="#">Your library</a>
          </div>  
          <div class="icons">
            <i class="fa-solid fa-plus"></i>
            <i class="fa-solid fa-arrow-right"></i>
          </div>
        </div>
        <div class="lib-boxe">
          <div class="box">
            <div class="box-p1">Create your first playlist</div>
            <div class="box-p2">It' easy. We'll help you</div>
            <button class="badge">Create playlist</button>
          </div>
        </div>
        <div class= "box2">
          <div class="box-p1">Lets's find some podcast to follow</div>
          <div class="box-p2">We'll keep you updated on new episode</div>
          <button class="badge">Browse Podcast</button>
        </div>
      </div>
    </div>
    <div class="main_box">
      <div class= "sticky-nav">
        <div class="sticky-nav-option">
          <img src= "./assests/backward_icon.png" class="h">
          <img src= "./assests/forward_icon.png">
          <input class="input" type="text" placeholder="What do you want to play?">
        </div>
        <div class="sticky-nav-icons">
          <button class="badge h">Explore Premium</button>
          <button class="badge dark-badge"><i class="fa-solid fa-download" style="margin-right: 5px"></i>Install App</button>
          <i class="fa-regular fa-user nav-item"></i>
        </div>
      </div>
      <div class="cards">
        <h2><a class="under" href="#">Recently Played</a></h2>
        <div class="card-container">
          <div class="card">
            <img src="./assests/card1img.jpeg" class="card-img">
            <p class="card-title">Top 50 - Global</p>
            <p class="card-info">Your daily update of the most played tracks</p>
          </div>
        </div>
        <h2><a class="under" href="#">Popular Artist</a></h2>
        <div class="card-container">
          <div class="card">
            <img src="./assests/card2img.jpeg" class="card-img">
            <p class="card-title">Top 50 - Global</p>
            <p class="card-info">Your daily update of the most played tracks</p>
          </div>
        </div>
      </div>
    </div>
    <div class="music palyer">music player</div>
  </div>
</body>

</html>
