<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Ray Tomatsu Website</title>
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"></script>
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
	<script src="https://use.fontawesome.com/releases/v5.0.8/js/all.js"></script>
	<link href="style.css" rel="stylesheet">
</head>
<body>

<!-- Navigation -->
<nav class="navbar navbar-expand-md navbar-light bg-light sticky-top">
<div class="container-fluid">
	<button class="navbar-toggler" type="button" data-toggle="collapse"
	data-targer="#navbarResponsive">
		<span class="navbar-toggler-icon"></span>
</button>
	<div class="collapse navbar-collapse" id="navbarResponsive">
		<ul class="navbar-nav ml-auto">
			<li class="nav-item active">
				<a class="nav-link" href="#">Home</a>
			</li>
			<li class="nav-item">
				<a class="nav-link" href="#">About</a>
			</li>
			<li class="nav-item">
				<a class="nav-link" href="#">Services</a>
			</li>
			<li class="nav-item">
				<a class="nav-link" href="#">Team</a>
			</li>
			<li class="nav-item">
				<a class="nav-link" href="#">Connect</a>
			</li>
		</ul>
</div>
</nav>


<!--- Image Slider -->
<div id="slides" class="carousel slide" data-ride="carousel">
<ul class="carousel-indicators">
	<li data-target="#slides" data-slide-to="0" class="active"></li>
	<li data-target="#slides" data-slide-to="1"></li>
	<li data-target="#slides" data-slide-to="2"></li>
</ul>
<div class="carousel-innter">
	<div class="carousel-item active">
		<img src="img/japan.jpg" class = "imgresize">
		<div class="carousel-caption">
			<h1 class="display-2">Ray Tomatsu</h1>
			<h3>Lafayette College Student</h3>
		</div>
	</div>
	<div class="carousel-item">
		<img src="img/music.jpg" class = "imgresize">
	</div>
	<div class="carousel-item">
		<img src="img/mtFuji.jpg" class ="imgresize">
	</div>
</div>

<!--- Jumbotron -->
<div class="container-fluid">
<div class="row jumbotron">
	<div class="col-xs-12 cols-sm-12 col-md-9 col-lg-9 col-xl-10">
		<p class ="lead">
		</p>
	</div>
</div>
</div>


<!--- Welcome Section -->
<div class ="container-fluid padding">
<div class="row welcome text-center">
	<div class="col-12">
		<h1 class ="display-4">Hello!
	</h1>
</div>
	<hr> 
	<div class ="col-12">
	<p class = "lead">I am Ray Tomatsu and I am currently a student 
			at Lafayette College graduating in 2021.  I wrote this website using
			JavaScript, HTML, CSS and I am looking forward for further developing my skills 
			within computer science.  I am interested in Software Engineering,
			Data Science, and Machine Learning.</p>
			<p class ="lead">I am proficient in the following programming langauges:</p>
</div>
</div>
</div>

<!--- Three Column Section -->
<div class="container-fluid padding">
<div class="row text-center padding">
	<div class = "col-xs-12 col-sm-6 col-md-4">
		<img src="img/c++.png" class = "imgresize2">
		<h3>C++</h3>
	</div>
	<div class="col-xs 12 cols-sm-6 col-md-4">
		<img src="img/java-logo.png" class="imgresize2">
		<h3>Java</h3>
	</div> 
	<div class="col-sm-12 col-md-4">		
		<img src="img/javaScript.png" class="imgresize2">
		<h3>Java Script</h3>
	</div> 

</div>
<hr class="my-4">
</div>


<!--- Two Column Section -->
<div class="container-fluid padding">
<h2>Selected Projects</h2>
<div class="container-fluid padding">
<div class="row text-center padding">
		<div class = "col-xs-12 col-sm-6 col-md-4">
		<p class ="project">Hive Simulation and Monitorying (C++)</p>
		<p class = "lead">

			•	Created a Bee Hive Simulation and Monitoring System for the company Circle of Bees.  
			<br>
•	Included a GUI that allowed the user to navigate through our program, display charts to visualize their specific bee hive activity, and configure their own bee hive for simulation.
			<br>  
•	Used SQLite database to store the Hive information as well as acquired them out of the data base when necessary.  
			<br>
•	Wrote an algorithm that generated UDP messages and decodes them to monitor Bee Activity.  
</p>
	</div>
	<div class="col-xs 12 cols-sm-6 col-md-4">
		<p class ="project">Amusement Park Configuration (Java)</p>
		<p class="lead">
			•	Designed a simulation to determine the optimal combination of features for an amusement park using Java and Object Oriented Programming.
			<br>
•	Wrote an algorithm in which park had rides of different types and each ride had its own attractiveness, length of time and other features.  
			<br>
•	The data structures used were arrays and array lists.  
			<br>
•	Implemented a configuration file to determine the kinds of rides and the amount of them.
			<br> 
•	Unit Tested all methods and constructors.  
		</p>
	</div> 
	<div class="col-sm-12 col-md-4">		
		<p class ="project">Created A Simulator and Primitive Debugger for An MC6502 Processor (C)</p>
		<p class = "lead">
			•	Able to create a debugger for an MCS6502 assembler with an input from a binary file.  
			<br>
•	Implemented assembly op codes for the MCS6502 so that the debugger will be able to simulate the processor.

		</p>
	</div> 
		
</div>
</div>

<hr class="my-4">
<!--- Fixed background -->
<figure>
	<div class="fixed-wrap">
		<div id="fixed">
		</div>
	</div>
</figure>

<!--- Emoji Section -->
<button class="fun" data-toggle="collapse" data-target="#emoji">Click for fun!
</button>
<div id="emoji" class= "collapse">
<div class="container-fluid padding">
<div clas="row text-center">
	<div class="col-sm-6 col-md-3">
		<img classes="gif" src="img/gif/panda.gif">
	</div>
	<div class="col-sm-6 col-md-3">
		<img classes="gif" src="img/gif/poo.gif">
	</div>
	<div class="col-sm-6 col-md-3">
		<img classes="gif" src="img/gif/unicorn.gif">
	</div>
	<div class="col-sm-6 col-md-3">
		<img classes="gif" src="img/gif/chicken.gif">
	</div>
</div>
</div>
</div>


  
<!--- Meet the team -->


<!--- Cards -->


<!--- Two Column Section -->


<!--- Connect -->
<div class="container-fluid padding">
<div class="row text-center padding">
	<div class="col-12">
		<h2>Connect</h2>
	</div>

	<div class="col-12 social padding">
		<a href="#"><i class = "fab fa-instagram"></i></a>
</div>
</div>
<!--- Footer -->
<footer>
<div class="container-fluid padding">
<div class="row text-center">
	<div class="col-md-6 col-md-3">
		<p>Ray Tomatsu</p>
		<hr class="light">
		<p>(1)551-579-7315</p>
		<p>raytomatsu21@gmail.com</p>
	</div>
	<div class="col-md-6 col-md-3">
		<p>Accounts</p>
		<hr class="light">
		<p>LinkedIn: https://www.linkedin.com/in/ray-tomatsu-68602416a</p>
		<p>GitHub: https://github.com/raytomatsu</p>
	</div>
</div>
</div>
</footer>


</body>
</html>






