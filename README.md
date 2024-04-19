# Personal-Project
Astro Space Agency
MAIN PAGE:CODE  
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Astro Space Agency Travel</title>
    <style>
        

        /* Global styles */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
	    color: #fff;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        .video-container {
            position: fixed;
            width: 100%;
            height: 100%;
            overflow: hidden;
            top: 0;
            left: 0;
            z-index: -1;
        }

        video {
            min-width: 100%;
            min-height: 100%;
            width: auto;
            height: auto;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header styles */
        header {
            background-color: rgba(0, 0, 0, 0.7);
            color: #fff;
            padding: 20px 0;
        }

        header h1 {
            font-size: 36px;
            text-align: center;
            margin-bottom: 20px;
        }

        nav ul {
            list-style-type: none;
            text-align: center;
            margin-top: 20px;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 18px;
        }

        /* Hero section styles */
        .hero {
            text-align: center;
            padding: 100px 0;
            background-color: rgba(0, 0, 0, 0.7);
        }

        .hero h2 {
            font-size: 48px;
            margin-bottom: 20px;
            color: #ffcc00;
        }

        .hero p {
            font-size: 24px;
            margin-bottom: 20px;
	    color:#ffcc00;
		
        }

        .btn {
            display: inline-block;
            padding: 15px 30px;
            background-color: #ffcc00;
            color: #000;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s ease;
            font-size: 20px;
        }

        .btn:hover {
            background-color: #e6b800;
        }

        /* Main section styles */
        section {
            padding: 50px 0;
            text-align: center;
        }

        section h2 {
            font-size: 36px;
            margin-bottom: 20px;
            color: #ffcc00;
        }

        section img {
            display: block;
            margin: 0 auto 20px;
            width: 300px; /* Adjust the image width as needed */
        }

        /* Footer styles */
        footer {
            background-color: rgba(0, 0, 0, 0.7);
            color: #fff;
            text-align: center;
            padding: 20px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        footer p {
            font-size: 18px;
        }
    </style>
</head>
<body>
<div class="video-container">
    <video autoplay loop muted>
        <source src="C:\Users\hp\Downloads\space-video.mp4" type="video/mp4">
        <!-- Add other video formats if needed -->
        Your browser does not support the video tag.
    </video>
</div>
<header>
    <div class="container">
        <h1><b>Astro Space Agency</b></h1>
        <nav>
            <ul>
		<li><a href="C:\Users\hp\Desktop\login.html">Login</a></li>
                <li><a href="C:\Users\hp\Desktop\home.html">Home</a></li>
                <li><a href="C:\Users\hp\Desktop\about.html">About</a></li>
                <li><a href="C:\Users\hp\Desktop\services.html">Services</a></li>
		<li><a href="C:\Users\hp\Desktop\weather.html">Weather</a></li>
                <li><a href="C:\Users\hp\Desktop\news.html">News</a></li>
                <li><a href="C:\Users\hp\Desktop\contact.html">Contact</a></li>
		

            </ul>
        </nav>
    </div>
</header>

<section id="home" class="hero">
    <div class="container">
        <h2>Welcome to Astro Space Agency</h2>
        <p><b>Explore the wonders of space with us!</b></p>
        <a href="#services" class="btn">Discover More<span>&rarr;</span></a>
    	<div id="discover-content" style="display: none;">
            <p>Embark on a journey to the stars and beyond. Our space tours offer breathtaking views of distant galaxies and celestial phenomena.</p>
            <p>Join us as we push the boundaries of exploration and expand our understanding of the universe.</p>
        </div>
    </div>
</section>

<section id="login">
    <div class="container">
        <a href="C:\Users\hp\Desktop\login.html" class="btn">Login</a>
    </div>
</section>


<section id="about">
    <div class="container">
        <href="C:\Users\hp\Desktop\about.html">
    </div>
</section>

<section id="services">
    <div class="container">
        <href="C:\Users\hp\Desktop\services.html">
    </div>
</section>
<section id="services">
    <div class="container">
        <href="C:\Users\hp\Desktop\services.html">
    </div>
</section>
<section id="weather">
    <div class="container">
        <href="C:\Users\hp\Desktop\weather.html">
    </div>
</section>

<section id="contact">
    <div class="container">
        <href="C:\Users\hp\Desktop\contact.html">
    </div>
</section>

<footer>
    <div class="container">
        <p>&copy; 2024 Space Agency. All rights reserved.</p>
    </div>
</footer>
</body>
</html>
<script>
    document.addEventListener("DOMContentLoaded", function() {
        var discoverButton = document.querySelector(".btn");
        var discoverContent = document.getElementById("discover-content");

        // Toggle content visibility when button is clicked
        discoverButton.addEventListener("click", function() {
            if (discoverContent.style.display === "none") {
                discoverContent.style.display = "block";
            } else {
                discoverContent.style.display = "none";
            }
        });
    });
</script>

LOGIN PAGE:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css"> <!-- Font Awesome for icons -->
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #00171f; /* Dark blue color */
            color: #fff;
            margin: 0;
            padding: 0;
            position: relative; /* Add position relative for absolute positioning */
        }

        .container {
            display: flex;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            position: relative; /* Add position relative for absolute positioning */
        }

        .screen {      
            background: linear-gradient(90deg, #5D54A4, #7C78B8);      
            position: relative;  
            height: 600px;
            width: 360px;   
            box-shadow: 0px 0px 24px #5C5696;
        }

        .screen__content {
            z-index: 1;
            position: relative; 
            height: 100%;
        }

        .login {
            width: 320px;
            padding: 30px;
            padding-top: 156px;
            position: relative; /* Add position relative for absolute positioning */
        }

        .login-key {
            position: absolute;
            top: 10px;
            right: 10px;
            font-size: 24px;
            color: #fff;
        }

        .login__field {
            padding: 20px 0px;    
            position: relative;    
        }

        .login__icon {
            position: absolute;
            top: 30px;
            color: #7875B5;
        }

        .login__input {
            border: none;
            border-bottom: 2px solid #D1D1D4;
            background: none;
            padding: 10px;
            padding-left: 24px;
            font-weight: 700;
            width: 75%;
            transition: .2s;
        }

        .login__input:active,
        .login__input:focus,
        .login__input:hover {
            outline: none;
            border-bottom-color: #6A679E;
        }

        .login__submit {
            background: #fff;
            font-size: 14px;
            margin-top: 30px;
            padding: 16px 20px;
            border-radius: 26px;
            border: 1px solid #D4D3E8;
            text-transform: uppercase;
            font-weight: 700;
            display: flex;
            align-items: center;
            width: 100%;
            color: #4C489D;
            box-shadow: 0px 2px 2px #5C5696;
            cursor: pointer;
            transition: .2s;
        }

        .login__submit:active,
        .login__submit:focus,
        .login__submit:hover {
            border-color: #6A679E;
            outline: none;
        }
    </style>
</head>
<body>
    <div id="message" style="display: none; background-color: green; color: white; padding: 10px; text-align: center;">You are logged in successfully</div>
    <div class="container">
        <div class="screen">
            <!-- Small login key -->
            <i class="login-key fas fa-key"></i>
            <div class="screen__content">
                <!-- HTML content from the provided snippet -->
                <form id="loginForm" class="login">
                    <div class="login__field">
                        <i class="login__icon fas fa-user"></i>
                        <input type="text" class="login__input" id="username" placeholder="User name / Email">
                    </div>
                    <div class="login__field">
                        <i class="login__icon fas fa-lock"></i>
                        <input type="password" class="login__input" id="password" placeholder="Password">
                    </div>
                    <button type="submit" class="button login__submit">
                        <span class="button__text">Log In Now</span>
                        <i class="button__icon fas fa-chevron-right"></i>
                    </button>                
                </form>
            </div>
        </div>
    </div>
    <script>
        document.getElementById("loginForm").addEventListener("submit", function(event) {
            event.preventDefault(); // Prevent default form submission
            // Here you can add your login logic, for demonstration purposes, I'll simply display the message
            document.getElementById("message").style.display = "block"; // Show the message
            setTimeout(function(){
                document.getElementById("message").style.display = "none"; // Hide the message after 3 seconds
            }, 3000);
        });
    </script>
</body>
</html>


HOME PAGE:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Astro Space Agency - Home</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #00171f; /* Dark blue color */
            color: #fff;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            text-align: center;
            padding: 50px;
        }

        h1 {
            font-size: 36px;
            margin-bottom: 20px;
            color: #ffcc00; /* Yellow color */
        }

        p {
            font-size: 20px;
            margin-bottom: 30px;
        }

        .btn {
            display: inline-block;
            padding: 10px 20px;
            background-color: #ffcc00; /* Yellow color */
            color: #000;
            text-decoration: none;
            border-radius: 5px;
            font-size: 18px;
            transition: background-color 0.3s ease;
        }

        .btn:hover {
            background-color: #e6b800; /* Darker yellow color on hover */
        }

        img {
            width: 300px;
            border-radius: 10px;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="C:/Users/hp/Downloads/space-background.jpg" alt="Space Background">
        <h1>Welcome to Astro Space Agency</h1>
        <p>Explore the wonders of space with us!</p>
        <a href="discover.html" class="btn">Discover More</a>
        <div id="discover-content" style="display: none;">
            <h2>Distance of Planets from Earth</h2>
            <img src="C:/Users/hp/Pictures/Screenshots/distance.png" alt="Distance of Planets from Earth">
            <img src="C:/Users/hp/Downloads/planets.jpg" alt="Planets">
        </div>
    </div>
</body>
</html>

ABOUT PAGE:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Astro Space Agency - About</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css"> <!-- Font Awesome CSS -->
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #00171f; /* Dark blue color */
            color: #fff;
            margin: 0;
            padding: 0;
        } nav {
            background-color: #ffcc5c; /* Yellow color */
            padding: 10px;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            color: #333; /* Dark gray text */
            text-decoration: none;
            font-size: 18px;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            text-align: center;
            padding: 50px;
        }

        h1 {
            font-size: 36px;
            margin-bottom: 20px;
            color: #ffcc00; /* Yellow color */
            animation: fadeIn 1s ease-out;
        }

        p {
            font-size: 20px;
            margin-bottom: 30px;
            animation: fadeIn 1s ease-out 0.5s;
        }

        .about-content {
            display: flex;
            justify-content: space-around;
            margin-top: 50px;
            align-items: center;
            opacity: 0;
            animation: slideIn 1s ease-out forwards;
        }

        .about-content img {
            width: 300px;
            border-radius: 10px;
            margin-right: 20px;
        }

        .about-content h2 {
            font-size: 28px;
            margin-bottom: 20px;
        }

        .about-content p {
            font-size: 18px;
        }

        .icon {
            font-size: 36px;
            color: #ffcc00; /* Yellow color */
            margin-bottom: 10px;
        }

        /* Zig-zag layout */
        .about-content:nth-child(odd) {
            flex-direction: row-reverse;
        }

        @keyframes slideIn {
            from {
                transform: translateY(50px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }
    </style>
</head>
<body>
<header>
        <h1>ABOUT US</h1>
   </header>

    <nav>
        <ul>
            <li><a href="home.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="services.html">Services</a></li>
            <li><a href="news.html">News</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>

    <div class="container">
       
        <p>Space Agency is dedicated to making space travel accessible to everyone. Our team of experts has decades of experience in the aerospace industry.</p>
        <div class="about-content">
            <img src="C:Users/hp/Downloads/team.png" alt="Team">
            <div>
                <h2>Our Mission</h2>
                <p>Our mission is to inspire and educate people about the wonders of space, and to push the boundaries of space exploration.</p>
            </div>
        </div>
        <div class="about-content">
            <div>
                <h2>Our Vision</h2>
                <p>Our vision is to enable humanity to become a spacefaring civilization, exploring new worlds and unlocking the mysteries of the universe.</p>
            </div>
            <img src="C:Users/hp/Downloads/rocket.jpg" alt="Rocket">
        </div>
        <div class="about-content">
            <img src="C:Users/hp/Downloads/planet.jpg" alt="Planet">
            <div>
                <h2>Our Values</h2>
                <p>We are committed to safety, innovation, collaboration, and sustainability in all aspects of our work.</p>
            </div>
        </div>
        <div class="about-content">
            <div>
                <h2>Meet Our Team</h2>
                <p>We have a diverse team of engineers, scientists, astronauts, and visionaries who are passionate about exploring space and pushing the boundaries of human knowledge.</p>
            </div>
            <i class="icon fas fa-users"></i>
        </div>
    </div>
</body>
</html>

SERVICES PAGE:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Astro Space Agency - Services</title>
    <style>
        header {
            background-color: #ff6f61; /* Coral color */
            color: #fff; /* White text */
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #ffcc5c; /* Yellow color */
            padding: 10px;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            color: #333; /* Dark gray text */
            text-decoration: none;
            font-size: 18px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .services-container {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            padding: 20px;
        }

        .service {
            width: 300px;
            background-color: #222;
            color: #fff;
            padding: 20px;
            margin: 20px;
            border-radius: 10px;
            text-align: center;
        }

        .service h3 {
            font-size: 24px;
        }

        .service p {
            font-size: 16px;
            margin-bottom: 15px;
        }

        .service img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 15px;
        }

        .service a {
            color: #ffcc00;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        .service a:hover {
            color: #e6b800;
        }
    </style>
</head>
<body>
<header>
        <h1>SERVICES</h1>
   </header>

    <nav>
        <ul>
            <li><a href="home.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="services.html">Services</a></li>
            <li><a href="news.html">News</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>
    

    <div class="services-container">
    <div class="service">
        <img src="C:Users/hp/Downloads/service1.jpg" alt="Service 1">
        <h3>Space Tourism</h3>
        <p>Experience the thrill of space travel with our guided tours to nearby celestial bodies.</p>
        <a href="space_tourism.html">Learn More</a>
    </div>

        <div class="service">
            <img src="C:Users/hp/Downloads/service2.jpg" alt="Service 2">
            <h3>Satellite Launch Services</h3>
            <p>Launch your satellite into orbit with our reliable and efficient launch services.</p>
            <a href="isro.html">Learn More</a>
        </div>

        <div class="service">
            <img src="C:Users/hp/Downloads/service3.jpg" alt="Service 3">
            <h3>Research Missions</h3>
            <p>Conduct groundbreaking research in space with our dedicated research missions.</p>
            <a href="service3.html">Learn More</a>
        </div>

        <div class="service">
            <img src="C:Users/hp/Downloads/service4.jpg" alt="Service 4">
            <h3>Space Station Visits</h3>
            <p>Visit the International Space Station and experience life in microgravity.</p>
            <a href="service4.html">Learn More</a>
        </div>
    </div>

    
</body>
</html>

SPACE_TOURISM:
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Space Tourism</title>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
    color: #333;
  }
  .container {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }
  h1, h2 {
    text-align: center;
    color: #4285f4;
  }
  p {
    text-align: justify;
    line-height: 1.6;
  }
  .section {
    margin-bottom: 30px;
    padding: 20px;
    border-radius: 8px;
  }
  .section:nth-child(odd) {
    background-color: #f9f9f9; /* Light gray background color */
  }
  .section:nth-child(even) {
    background-color: #e0f7fa; /* Light blue background color */
  }
  .image-container {
    text-align: center;
    margin-bottom: 20px;
  }
  .image-container img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    margin-bottom: 10px;
  }
  .interest-rating {
    text-align: center;
    margin-bottom: 20px;
  }
  .interest-rating label {
    color: #4285f4;
  }
  .interest-rating input[type="radio"] {
    display: none;
  }
  .interest-rating label:before {
    content: '\2605';
    font-size: 36px;
    color: #ccc;
    cursor: pointer;
    background-color: #f9f9f9; /* Light gray background color */
    padding: 5px;
    border-radius: 50%; /* Makes the background circle-shaped */
  }
  .interest-rating input[type="radio"]:checked ~ label:before {
    color: #ffbb00;
  }
</style>
</head>
<body>

<div class="container">
  <div class="section">
    <h1>Experience the Thrill of Space Travel</h1>
    <div class="image-container">
      <img src="C:\Users\hp\Downloads\galaxy.jpg" alt="Galaxy">
      <img src="C:\Users\hp\Downloads\starlink.jpg" alt="Stalink">
    </div>
    <p>Embark on an extraordinary journey with our exclusive space tourism packages, offering the adventure of a lifetime. Our guided tours provide unparalleled access to nearby celestial bodies, allowing you to witness the wonders of the universe up close. From the rugged terrain of the moon to the breathtaking vistas of Mars, each tour promises an unforgettable experience for space enthusiasts of all levels.</p>
  </div>
  
  <div class="section">
    <h2>Explore the Cosmos</h2>
    <p>Our expert team ensures your safety and comfort throughout the entire journey, providing you with the opportunity to delve into the mysteries of outer space without worry. Whether you're a seasoned explorer or embarking on your first interstellar voyage, our tours cater to all levels of curiosity and interest. Prepare to be amazed as you witness the beauty and grandeur of our solar system like never before.</p>
  </div>
  
  <div class="section">
    <h2>Plan Your Celestial Adventure</h2>
    <p>Discover the diverse range of packages we offer and start planning your celestial adventure today. Choose from a variety of tour options, each carefully curated to provide you with an immersive and educational experience. Whether you dream of walking on the surface of the moon or gazing at the Martian landscape from orbit, our tours offer something for everyone.</p>
  </div>
  
  <div class="section">
    <h2>Join Us in Pushing the Boundaries</h2>
    <p>Join us as we push the boundaries of human exploration and embark on a journey that will inspire generations to come. Take the first step towards realizing your dreams of space travel and book your tour with us today. Get ready to embark on an adventure that will leave you in awe of the vastness and beauty of the cosmos.</p>
  </div>

  <div class="section interest-rating">
    <p>Rate your interest in space travel:</p>
    <input type="radio" id="star5" name="rating" value="5">
    <label for="star5"></label>
    <input type="radio" id="star4" name="rating" value="4">
    <label for="star4"></label>
    <input type="radio" id="star3" name="rating" value="3">
    <label for="star3"></label>
    <input type="radio" id="star2" name="rating" value="2">
    <label for="star2"></label>
    <input type="radio" id="star1" name="rating" value="1">
    <label for="star1"></label>
  </div>
</div>

</body>
</html>


SERVICE-2:
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Research Missions</title>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f3f3f3;
  }

  .container {
    width: 80%;
    max-width: 1200px;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }

  h1 {
    text-align: center;
    margin-bottom: 20px;
    color: #333;
  }

  p {
    margin-bottom: 20px;
    color: #666;
  }

  
  .video-container {
    position: relative;
    width: 75%;
    padding-bottom: 56.25%; /* 16:9 aspect ratio */
    overflow: hidden;
    margin-bottom: 20px;
  }

  .video-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 75%;
    height: 75%;
    border: 0;

  }

  .link {
    color: #007bff;
    text-decoration: none;
    font-weight: bold;
  }

  .link:hover {
    text-decoration: underline;
  }
</style>
</head>
<body>

<div class="container">
  <h1>Research Missions</h1>
  <p>Conduct groundbreaking research in space with our dedicated <span class="highlight-box">research missions</span>.</p>
  <p>Our research missions are designed to explore the mysteries of the universe and push the boundaries of human knowledge. We collaborate with leading scientists and institutions around the world to develop cutting-edge technologies and conduct experiments that address some of the most pressing questions in astrophysics, astronomy, and planetary science.</p>
  <p>From studying distant galaxies and black holes to investigating the origins of life on other planets, our research missions cover a wide range of topics that are essential for advancing our understanding of the cosmos.</p>
  <p>Join us on an exciting journey of discovery as we unlock the secrets of the universe and pave the way for future generations of explorers.</p>
  
  <div class="video-container">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/jI-HeXhsUIg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>

  <p>For more information, visit our <a href="https://www.nasa.gov/hrp/research-operations-integration/" class="link" target="_blank">website</a> or explore our <a href="https://testbook.com/ias-preparation/respond-research-sponsored-programme-isro" class="link" target="_blank">research projects</a>.</p>
</div>

</body>
</html>

SERVICE-3:
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Research Missions</title>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f3f3f3;
  }

  .container {
    width: 80%;
    max-width: 1200px;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }

  h1 {
    text-align: center;
    margin-bottom: 20px;
    color: #333;
  }

  p {
    margin-bottom: 20px;
    color: #666;
  }

  
  .video-container {
    position: relative;
    width: 75%;
    padding-bottom: 56.25%; /* 16:9 aspect ratio */
    overflow: hidden;
    margin-bottom: 20px;
  }

  .video-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 75%;
    height: 75%;
    border: 0;

  }

  .link {
    color: #007bff;
    text-decoration: none;
    font-weight: bold;
  }

  .link:hover {
    text-decoration: underline;
  }
</style>
</head>
<body>

<div class="container">
  <h1>Research Missions</h1>
  <p>Conduct groundbreaking research in space with our dedicated <span class="highlight-box">research missions</span>.</p>
  <p>Our research missions are designed to explore the mysteries of the universe and push the boundaries of human knowledge. We collaborate with leading scientists and institutions around the world to develop cutting-edge technologies and conduct experiments that address some of the most pressing questions in astrophysics, astronomy, and planetary science.</p>
  <p>From studying distant galaxies and black holes to investigating the origins of life on other planets, our research missions cover a wide range of topics that are essential for advancing our understanding of the cosmos.</p>
  <p>Join us on an exciting journey of discovery as we unlock the secrets of the universe and pave the way for future generations of explorers.</p>
  
  <div class="video-container">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/jI-HeXhsUIg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>

  <p>For more information, visit our <a href="https://www.nasa.gov/hrp/research-operations-integration/" class="link" target="_blank">website</a> or explore our <a href="https://testbook.com/ias-preparation/respond-research-sponsored-programme-isro" class="link" target="_blank">research projects</a>.</p>
</div>

</body>
</html>


SERVICE-4:
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Space Station Visits</title>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f3f3f3;
  }

  .container {
    width: 80%;
    max-width: 1200px;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }

  h1 {
    text-align: center;
    color: #333;
  }

  p {
    margin-bottom: 20px;
    color: #666;
    text-align: justify;
  }

  .video-container {
    position: relative;
    width: 100%;
    padding-bottom: 56.25%; /* 16:9 aspect ratio */
    overflow: hidden;
    margin-bottom: 20px;
    border-radius: 10px;
  }

  .video-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: none;
  }

  .location {
    text-align: center;
    color: #007bff;
    font-weight: bold;
  }
</style>
</head>
<body>

<div class="container">
  <h1>Space Station Visits</h1>
  <p>Embark on an extraordinary journey to the International Space Station (ISS) and experience life in microgravity. The ISS serves as a crucial hub for scientific research, technological development, and international collaboration in space exploration. Astronauts from around the world reside aboard the ISS, conducting experiments and performing tasks that push the boundaries of human knowledge.</p>
  
  <div class="video-container">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/oLrOnEmy_GA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>

  
  <p>Located approximately 408 kilometers above the Earth's surface, the ISS orbits the planet once every 90 minutes, offering breathtaking views of our planet and beyond. While the ISS itself does not have a fixed location like a terrestrial landmark, it passes over various regions, including Chennai, India. Witnessing the ISS glide across the night sky is a captivating sight that reminds us of humanity's presence in space.</p>

  <p>During your visit to the ISS, you'll have the opportunity to participate in scientific experiments, observe Earth from a unique vantage point, and interact with astronauts from different countries. Whether you're a space enthusiast, a scientist, or simply curious about life beyond our planet, a trip to the ISS promises to be an unforgettable experience that will inspire wonder and awe.</p>

  <p>For more information and to plan your own space station visit, check out the official <a href="https://www.nasa.gov/mission_pages/station/main/index.html" target="_blank" class="location">NASA website</a>.</p>
</div>

</body>
</html>



WEATHER:
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather Forecast</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('C:/Users/hp/Downloads/icons.jpg'); 
            background-size: 50%;            
            background-position: center;
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
        }
        .weather-box {
            width: 300px;
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.8); 
            margin: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .header {
            background-color: violet;
            color: #fff;
            padding: 20px;
            text-align: center;
            border-radius: 10px 10px 0 0;         }
        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .content-container {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        
        
        .overlay {
            background-color: rgba(255, 255, 255, 0.8);
            padding: 20px;
        }
        .footer {
            background-color: rgba(0, 0, 0, 0.5); 
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        /* Additional styling for the combined code */
        .info-section {
            flex: 1 1 400px; /* Flex grow, flex shrink, flex basis */
            padding: 20px;
        }
        .picture-section {
            flex: 1 1 400px; /* Flex grow, flex shrink, flex basis */
            display: flex;
            justify-content: flex-end; /* Aligns the picture to the right */
            align-items: center; /* Centers the picture vertically */
        }
        .picture-section img {
            max-width: 100%; /* Ensures the image doesn't overflow its container */
            max-height: 100%; /* Ensures the image doesn't overflow its container */
            width: auto; /* Set width to auto for responsive resizing */
            height: 90%; /* Set height to auto for responsive resizing */
        }
        .info-section img {
    max-width: 50%; /* Ensures the image doesn't exceed its container's width */
    height: auto; /* Allows the image to scale proportionally with its width */
    display: block; /* Ensures proper alignment and spacing */
    margin: 0 auto; /* Centers the image horizontally within its container */
}
.h4{
align-items: center; 
}


    </style>
</head>
<body>
    <div class="weather-box">
        <div class="header">
            <h1>Weather Forecast</h1>
        </div>
        <div class="container">
            <h2>Today's Weather</h2>
            <input type="text" id="cityInput" placeholder="Enter city name">
            <button onclick="getWeather()" class="weather-function">Get Weather</button>
            <div class="weather-icon"></div>
            <div class="weather-info"></div>
            <div class="weather-details"></div>
        </div>
    </div>

    <div class="content-container">
        <div class="rectangle-box" onclick="scrollToSection('satellites')"> <!-- Weather Satellites -->
            <p>Weather Satellites</p>
        </div>
        <div class="rectangle-box" onclick="scrollToSection('stations')"> <!-- Weather Stations -->
            <p>Weather Stations</p>
        </div>
        <div class="rectangle-box" onclick="scrollToSection('models')"> <!-- Computer Models -->
            <p>Computer Models</p>
        </div>
    </div>

    <div class="overlay">
        <div class="container">
            <div class="info-section" id="satellitesContent">
                <h2>Measuring Weather</h2>
                <h3>Weather Satellites</h3>
                <p>Weather satellites can observe weather systems on a global scale. There are some 160 meteorological satellites in orbit today, creating about 80 million satellite observations per day.</p>
                <p><strong>How it works:</strong></p>
                <p>Sensors on weather satellites scan the Earth, taking measurements of reflected light and infrared temperatures. These measurements are then digitized and sent back to Earth where they can be turned into images.</p>
                <p><strong>There are two types of weather satellites:</strong></p>
                <ol>
                    <li>
                        <strong>Polar-orbiting satellites:</strong> Orbit at low-altitude around the North or South Pole and monitor the entire planet over the course of 10 days to 1 month. The information and data from these satellites are used in weather forecasting.
                    </li>
                    <li>
                        <strong>Geostationary satellites:</strong> Orbit at high-altitude at the equator, at the same speed as the Earth’s rotation, continuously monitoring one section of Earth. These satellites can track cloud formations and large storms as well as fires, etc.
                    </li>
                </ol>
                <iframe width="560" height="315" src="https://www.youtube.com/embed/fdErsR8_NaU?rel=0" title="How to Monitor Weather from Space" frameborder="0" allowfullscreen></iframe>
            </div>
            <div class="info-section" id="stationsContent">
                               <h3>Weather Stations</h3>
                <p>A weather station is a facility, either on land or sea, with instruments and equipment for measuring atmospheric conditions to provide information for weather forecasts and to study the weather and climate. The measurements taken include temperature, atmospheric pressure, humidity, wind speed, wind direction, and precipitation amounts. Wind measurements are taken with as few other obstructions as possible, while temperature and humidity measurements are kept free from direct solar radiation, or insolation.</p>
                <p>For further details, refer to <a href="https://en.wikipedia.org/wiki/Weather_station#:~:text=A%20weather%20station%20is%20a,study%20the%20weather%20and%20climate." target="_blank">this link</a>.</p>
                <img src="C:\Users\hp\Downloads\wstation.jpg" alt="Weather Stations Image">
            </div>
            <div class="info-section" id="modelsContent">
                               <h3>Computer Models</h3>
                <p>Data on the weather are collected every day from weather satellites, Doppler radar, weather stations, weather balloons, and other sources such as aircraft and ships. It then needs to be processed and turned into something that we can understand. Computers, of course, do that work.</p>
                <p>Computers process the data based on numerical models that scientists have developed (and continue to develop) from what they have learned about the laws of nature and physics. Taking the data on current weather, climate, and atmospheric conditions, computers use these scientific models to help forecast the weather for the coming days.</p>
                <img src="C:\Users\hp\Downloads\cmodels.jpg" alt="Computer Models Image">
            </div>
             <h4><b>EXPLORE,DESIGN,INNOVATE,RENOVATE</b></h4>
            <div class="picture-section">
                <img src="C:\Users\hp\Downloads\weasatellite.jpg" alt="Satellite">
            </div>
        </div>
    </div>

    <div class="footer">
        Join us... End up with being a part of practical life applications
    </div>

    <script>
        const API_KEY = 'ca39fedc0c1db2ed181527ff0d86407c';
        
        function getWeather() {
            const city = document.getElementById('cityInput').value;
            const apiUrl = `https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=${API_KEY}&units=metric`;

            fetch(apiUrl)
                .then(response => response.json())
                .then(data => {
                    const weatherIcon = data.weather[0].icon;
                    const weatherDescription = data.weather[0].description;
                    const temperature = data.main.temp;
                    const feelsLike = data.main.feels_like;
                    const humidity = data.main.humidity;

                    // Construct the URL for the weather icon
                    const iconUrl = `http://openweathermap.org/img/wn/${weatherIcon}.png`;

                    // Set the src attribute of the img element to the iconUrl
                    document.querySelector('.weather-icon').innerHTML = `<img src="${iconUrl}" alt="Weather Icon">`;
                    document.querySelector('.weather-info').innerHTML = `${Math.round(temperature)}°C, ${weatherDescription}`;
                    document.querySelector('.weather-details').innerHTML = `Feels like: ${Math.round(feelsLike)}°C | Humidity: ${humidity}%`;
                })
                .catch(error => console.log('Error fetching weather data:', error));
        }

        // Function to scroll to a specific section
        function scrollToSection(sectionId) {
            const section = document.getElementById(`${sectionId}Content`);
            section.scrollIntoView({ behavior: 'smooth' });
        }
    </script>
</body>
</html>

NEWS PAGE:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Astro Space Agency - News</title>
    <style>
                body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f0f0f0; /* Light gray background */
            color: #333; /* Dark gray text */
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #ff6f61; /* Coral color */
            color: #fff; /* White text */
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #ffcc5c; /* Yellow color */
            padding: 10px;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            color: #333; /* Dark gray text */
            text-decoration: none;
            font-size: 18px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .news-container {
            overflow: hidden;
            position: relative;
        }

        .news-article {
            background-color: #fff;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
            animation: scrollNews 10s linear infinite; /* Adjust animation duration as needed */
        }

        .news-article h2 {
            margin-bottom: 10px;
            color: #333; /* Dark gray text */
        }

        .news-article p {
            margin-bottom: 15px;
        }

        .news-article img {
            width: 100%;
            border-radius: 5px;
        }

        .read-more-link {
            color: #ff6f61; /* Coral color */
            text-decoration: none;
            font-weight: bold;
        }

        .read-more-link:hover {
            text-decoration: underline;
        }

        @keyframes scrollNews {
            from {
                transform: translateY(0);
            }
            to {
                transform: translateY(-100%);
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Latest News</h1>
    </header>

    <nav>
        <ul>
            <li><a href="home.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="services.html">Services</a></li>
            <li><a href="news.html">News</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>

    <div class="container">
        <div class="news-container">
            <div class="news-article">
                <img src="C:/Users/hp/Downloads/news1.jpg" alt="News 1">
                <h2>SpaceX Successfully Launches Falcon 9 Rocket</h2>
                <p>SpaceX, the private aerospace manufacturer, successfully launched its Falcon 9 rocket into orbit yesterday.</p>
                <a href="#" class="read-more-link">Read More</a>
            </div>

            <div class="news-article">
                <img src="C:/Users/hp/Downloads/news2.jpg" alt="News 2">
                <h2>Artemis 2 Orion spacecraft starts testing ahead of moon mission with astronauts in 2025</h2>
                <p>The Artemis 2 Orion spacecraft began testing on April 10 in an altitude chamber at NASA. The spacecraft will bring four astronauts around the moon no earlier than 2025.</p>
                <a href="#" class="read-more-link">Read More</a>
            </div>
        </div>
    </div>
</body>
</html>


CONTACT PAGE:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Astro Space Agency - Join Mission</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #00171f; /* Dark blue color */
            color: #fff;
            margin: 0;
            padding: 0;
        }

header {
            background-color: #ff6f61; /* Coral color */
            color: #fff; /* White text */
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #ffcc5c; /* Yellow color */
            padding: 10px;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            color: #333; /* Dark gray text */
            text-decoration: none;
            font-size: 18px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }


        h1 {
            font-size: 36px;
            margin-bottom: 20px;
            color: #ffcc00; /* Yellow color */
        }

        p {
            font-size: 20px;
            margin-bottom: 30px;
        }

        form {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        input[type="text"],
        input[type="email"],
        textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }

        input[type="submit"] {
            background-color: #ffcc00; /* Yellow color */
            color: #00171f; /* Dark blue color */
            border: none;
            padding: 15px 30px;
            border-radius: 5px;
            font-size: 20px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        input[type="submit"]:hover {
            background-color: #e6b800; /* Darker yellow color */
        }

        .details {
            display: none; /* Initially hide details */
        }

        .submitted-details {
            margin-top: 30px;
            background-color: #333; /* Dark grey color */
            color: #fff;
            padding: 20px;
            border-radius: 5px;
            text-align: left;
        }

        .contact-info {
            margin-top: 30px;
            font-size: 18px;
        }

        .social-links {
            margin-top: 10px;
            display: flex;
            justify-content: center;
        }

        .social-links a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
            font-size: 20px;
        }

        .footer {
            margin-top: 50px;
            text-align: center;
            font-size: 14px;
        }
    </style>
</head>
<body>
<header>
        
   </header>

    <nav>
        <ul>
            <li><a href="home.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="services.html">Services</a></li>
	    <li><a href="Weather.html">Weather</a></li>
            <li><a href="news.html">News</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>

    <div class="container">
        <h1>Join Our Space Mission</h1>
        <p>We're preparing for an exciting space mission and we want you to be part of it! Please fill out the form below to register your interest.</p>
        <form action="#" method="post" id="missionForm">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <input type="text" name="age" placeholder="Your Age" required>
            <textarea name="message" placeholder="Why do you want to join the mission?" required></textarea>
            <input type="submit" value="Register">
        </form>

        <!-- Display submitted details -->
        <div class="details" id="submittedDetails">
            <div class="submitted-details">
                <h2>Details Submitted:</h2>
                <p><strong>Name:</strong> <span id="name"></span></p>
                <p><strong>Email:</strong> <span id="email"></span></p>
                <p><strong>Age:</strong> <span id="age"></span></p>
                <p><strong>Message:</strong> <span id="message"></span></p>
            </div>
            <div class="contact-info">
                <p>For further inquiries, please contact us:</p>
                <p>Email: <a href="mailto:astrospaceagency@gmail.com">astrospaceagency@gmail.com</a></p>
            </div>
        </div>
    </div>

    <div class="footer">
        &copy; 2024 Astro Space Agency. All rights reserved. Thanks for visiting our webpage! Have a great day ahead.
    </div>

    <script>
        const form = document.getElementById('missionForm');
        const submittedDetails = document.getElementById('submittedDetails');

        form.addEventListener('submit', function(event) {
            event.preventDefault(); // Prevent form submission

            // Retrieve form data
            const formData = new FormData(form);
            const name = formData.get('name');
            const email = formData.get('email');
            const age = formData.get('age');
            const message = formData.get('message');

            // Display submitted details
            document.getElementById('name').textContent = name;
            document.getElementById('email').textContent = email;
            document.getElementById('age').textContent = age;
            document.getElementById('message').textContent = message;
            submittedDetails.style.display = 'block'; // Show submitted details
            form.reset(); // Reset form fields
        });
    </script>
</body>
</html>






