<!DOCTYPE html>
<html>
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Project</title>
  <link rel="stylesheet" type="text/css" href="hobbies.css">
   <link rel="stylesheet" type="text/css" href="w3.css">
  <script src="js/mainscript.js" defer></script>


  <style>
    #project {
      background-image: url('images/background2.png'); 
      background-size: cover;
      background-repeat: no-repeat;
      background-size: 100% 100%;
      font-family: Courier (sans-serif);
      text-shadow: 2px 2px 5px rgba(0, 0, 0, 15);
    }
  </style>
</head>
  <body>
    <body>
   <header>
<div>
    <div class="head " style="border: solid; border-color: skyblue; border-width: 2px;"> 
    <br>
  <nav>
      <ul class="zoom-effect">
              <li><a href="home.html">Home</a></li>
            <li><a href="hobby.html">hobbies</a></li>
            <li><a href="blog.html">Gallery</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>           
    </nav>
  </div>
</header>
<div class="search">
<div class="container">
    <input type="text" name="text" class="input" required="" placeholder="Type to search...">
    <div class="icon">
        <svg xmlns="http://www.w3.org/2000/svg" class="ionicon" viewBox="0 0 512 512">
            <title>Search</title>
            <path d="M221.09 64a157.09 157.09 0 10157.09 157.09A157.1 157.1 0 00221.09 64z" fill="none" stroke="currentColor" stroke-miterlimit="10" stroke-width="32"></path>
            <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-miterlimit="10" stroke-width="32" d="M338.29 338.29L448 448"></path>
        </svg>
    </div>
</div>
</div>
<br><br>

<div class="first_background">  
    <div class="drew">
    <legend class="w3-text-blue" style="margin-left:180px; margin-top:-340px;"> DREW AND <span class="friend"> FRIENDS </span> </legend>
      </div>
   
     
    <div id="project">
        <div class="fade-up-in">
        <h1 class="w3-text-white w3-center font1 fontshadow" style="padding-top: 50px; padding-bottom: 5px;"><b>HOBBIES</b></h1>
        <div style="display: flex; justify-content: center; ">
          <div class="project glow prj" style="height: 750px;">
          <h1 style="color:black; text-align: center; border:solid 2px black;border-radius: 40px; background-color:white;width: 400px;margin-left:140px;height: 70px;">BASKETBALL</h1>
            <img src="C:\Users\ella\OneDrive\Desktop\DREW AND FRIENDS\basketball.jpg" class="projectimages">
            
            <p class="w3-text-white font1 w3-center w3-large" style="padding-left: 30px; padding-right: 30px;font-family: century gothic;font-size: 14px;">
            Basketball my main hobby for my all kind of game. 
            When i was a elementary student after class im gonna go to house 
            and change my clothes and after that im going to the basketball court 
            and play with my classmates and then when i  junior high school. 
            I join in to the baranggay league. It means Liga in midget division. 
            I have also an award which is mythical 5 and same as in to my school intrams.
                </p>
            <div style="display: flex; justify-content: center;">
              <button onclick="if (confirm('Are you sure you want to leave this page?')) 
                {window.location.href='hobby.html'; }" class="zoom-effect button2">
                <b><span class="font1">BACK TO MAIN</span></b>
              </button>
            </div>
          </div>
        </div>
      </div>
   </div>
 </div>
  </div>
      </div>
   </div>
 </div>


    <script>
      const observer = new IntersectionObserver(entries => {
          entries.forEach(entry => {
              if (entry.isIntersecting) {
                  entry.target.classList.add('show');
              } else {
                  entry.target.classList.remove('show'); 
              }
          });
      });

      document.querySelectorAll('.fade-up-in').forEach(element => {
        observer.observe(element);
      });

      document.getElementById("search").addEventListener("keypress", function(event) {
        if (event.key === "Enter") {
          event.preventDefault();
          window.location.href = "project.html";
        }
      });
    </script>

    <footer><p>@Copyright;All Rights Reserved 2024 
<br>
Designed by Tolentino and Batalla
<br>
BSIT 2C</p></footer>
  </body>
</html>
