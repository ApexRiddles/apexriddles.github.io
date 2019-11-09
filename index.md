<!DOCTYPE html>
<html lang="en">
<head>
<link rel="icon" href="image/design.ico">
<title>Apex Riddles</title>
<meta name="google-site-verification" content="2xtauavm1RYCLmQMawnwFvqbxFF0lycd73fistyMujQ" />
<meta name="description" content="Apex Riddles is designed to be an engaging experience for all ages - whether you are young or old, come enjoy a few riddles with us!">

<style>
body {
	background-image: url("image/indexbg.jpg");
        background-repeat:no-repeat;
       background-size:cover;
} 

</style>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body {font-family: "Lato", sans-serif}
.mySlides {display: none}
#mySidenav a {
   position: absolute;
  left: -72px;
  transition: 0.3s;
  padding: 15px;
  width: 120px;
  text-decoration: none;
  font-size: 20px;
  color: white;
  border-radius: 0 10px 10px 0;
}

#mySidenav a:hover {
  left: 0;
}

#home {
  top: 440px;
  background-color: #2196F3;
}
 
#about {
  top: 494px;
  background-color: #4CAF50;
}

#levels {
  top: 544px;
  background-color: #f44336;
}

.moveimage1
{
    position: relative;
    top: -4px;
}
.moveimage2
{
    position: relative;
    top: -2px;
}
.moveimage3
{
    position: relative;
    top: -2px;
}
</style>
<body>
<!-- Page content -->
<div id="mySidenav" class="sidenav">
  <a href="index.html" id="home">Home&ensp;&nbsp;<img class="moveimage1" img src="image/home.png" style="width:24%"></a>
  <a href="contact.html" id="about">About&ensp;&nbsp;<img class="moveimage2" img src="image/about.png" style="width:24%"></a>
  <a href="levels.html" id="levels">Levels&ensp;&nbsp;<img class="moveimage3" img src="image/challenge.png" style="width:24%"></a>
</div>


  <!-- Automatic Slideshow Images -->
  <div class="mySlides w3-display-container w3-center">
    <img src="image/banner1.jpg" style="width:100%"> 

    </div>
  <div class="mySlides w3-display-container w3-center">
    <img src="image/banner2.jpg" style="width:100%">  
    </div>
  <div class="mySlides w3-display-container w3-center">
    <img src="image/banner3.jpg" style="width:100%">
  </div>
  <!-- The information -->
  <div class="w3-container w3-content w3-center w3-padding-64" style="max-width:800px" id="band">
<h1 class="w3-wide"><b>♕ 𝒜𝓅𝑒𝓍 𝑅𝒾𝒹𝒹𝓁𝑒𝓈 ♕ </b></h1>
<p class="w3-opacity">We love riddles! Can you make your way through these intriguing challenges?</p>
    <p class="w3-justify">Apex Riddles is designed to be a fun and engaging experience for individuals of all ages - whether you are young or old, we want you to experience the thrill and joy of riddles so that you can utilize your time to improve your skills! Numerous past participants have tried and recommended these riddles, due to their simplistic, yet challenging design. To maintain this website, we need your support. We work around the clock to help deliver smiles, and any donation or a simple "thank you" on our contact page is appreciated!
    </p>
    <div class="w3-row w3-padding-32">
      <div class="w3-third">
  </div>
  <!-- challenges -->
  <div class="w3-black" id="facts">
    <div class="w3-container w3-content w3-padding-64" style="max-width:800px">
      <h2 class="w3-wide w3-center">FACTS</h2>
      <p class="w3-opacity w3-center"><i>Interesting Facts You Probably Don't Know</i></p><br>
      

      <div class="w3-row-padding w3-padding-32" style="margin:0 -16px">
        <div class="w3-third w3-margin-bottom">
          <img src="image/firstgame.jpg" alt="first game" style="width:95%" class="w3-hover-opacity">
          <div class="w3-container w3-white">
            <p><b>First Game</b></p>
            <p>The First Game was Pong. It was invented in October 1958 by William Higinbotham.</p>
            <button class="w3-button w3-black w3-margin-bottom".style.display='block'"><a href="https://en.wikipedia.org/wiki/Early_history_of_video_games" target="_blank">View More</button></a>
          </div>
        </div>
        <div class="w3-third w3-margin-bottom">
          <img src="image/firstvirus.jpg" alt="first virus" style="width:95%" class="w3-hover-opacity">
          <div class="w3-container w3-white">
            <p><b>First Virus</b></p>
            <p>The First Virus was Creeper. It was invented in the early 1970s by Bob Thomas.</p>
            <button class="w3-button w3-black w3-margin-bottom".style.display='block'"><a href="https://en.wikipedia.org/wiki/Computer_virus" target="_blank">View More</button></a>
          </div>
        </div>
        <div class="w3-third w3-margin-bottom">
          <img src="image/firstprogrammer.jpg" alt="first programmer" style="width:101%" class="w3-hover-opacity">
          <div class="w3-container w3-white">
            <p><b>First Computer Programmer</b></p>
            <p>The First Computer programmer was Ada Lovelace.</p>
            <button class="w3-button w3-black w3-margin-bottom".style.display='block'"><a href="https://en.wikipedia.org/wiki/Ada_Lovelace" target="_blank">View More</button></a>
          </div>
        </div>
      </div>
    </div>
  </div>
<script>
// Automatic Slideshow - change image every 4 seconds
var myIndex = 0;
carousel();

function carousel() {
  var i;
  var x = document.getElementsByClassName("mySlides");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";  
  }
  myIndex++;
  if (myIndex > x.length) {myIndex = 1}    
  x[myIndex-1].style.display = "block";  
  setTimeout(carousel, 4000);    
}

</script>
</div>
</div>
<img src="https://payload.cargocollective.com/1/21/701338/13704473/TropicLabs_wave-banner_test.gif" alt="apex riddles banner" height="180" width=100%/>
</body>
</html>
