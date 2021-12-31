<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8">
			<meta name="viewport" content="width=device-width, initial-scale=1.0">
				<!-- <link rel="stylesheet" href="styles.css"> -->
				<style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            /* background: linear-gradient(217deg, rgba(255,0,0,.8), rgba(255,0,0,0) 70.71%),
            linear-gradient(127deg, rgba(0,255,0,.8), rgba(0,255,0,0) 70.71%),
            linear-gradient(336deg, rgba(0,0,255,.8), rgba(0,0,255,0) 70.71%); */

        }


        .topnav {
            overflow: hidden;
            background-color: #333;
        }

        .topnav a {
            float: left;
            color: #f2f2f2;
            text-align: center;
            padding: 14px 16px;
            text-decoration: wavy;
            font-size: 50%;
        }

        .topnav a:hover {
            background-color: #ddd;
            color: black;
        }

        .topnav a.active {
            background-color: #4CAF50;
            color: white;
        }


        .glow {
            position: sticky;
            top: 4%;
            left: 90%;
            transform: translate(-10%, -10%);
            width: 60px;
            height: 10px;
            text-align: top;
            ;
            line-height: 2px;
            text-decoration: none;
            text-transform: uppercase;
            color: #fff;
            font-family: Arial, Helvetica, sans-serif;
            font-size: 20px;
            border-radius: 40px;
            outline: none;
            box-sizing: border-box;
            background: linear-gradient(90deg, #03a9f4, #f441a5, #ffeb3b, #03a9f4);
            background-size: 600%;
            z-index: 1;
            animation: animate 4s linear infinite;
        }

        .glow:hover {
            animation: animate 2s linear infinite;
        }

        @keyframes animate {
            0% {
                background-position: 0;
            }

            100% {
                background-position: 400%;
            }
        }

        .glow:before {
            content: '';
            position: relative;
            top: -5px;
            right: -5px;
            bottom: -5px;
            left: -5px;
            z-index: -1;
            background: linear-gradient(90deg, #03a9f4, #f441a5, #ffeb3b, #03a9f4, #043d43);
            background-size: 400%;
            border-radius: 40px;
            filter: blur(40px);
            opacity: 0;
            transition: 1.5s;
        }

        .glow:hover:before {
            filter: blur(20px);
            opacity: 1;
            animation: animate 5s linear infinite;
        }
    </style>
				<style>
body {
  font-family: Arial;
  margin: 0;
}

* {
  box-sizing: border-box;
}

img {
  vertical-align: middle;
}

/* Position the image container (needed to position the left and right arrows) */
.container {
  position: relative;
}

/* Hide the images by default */
.mySlides {
  display: none;
}

/* Add a pointer when hovering over the thumbnail images */
.cursor {
  cursor: pointer;
}

/* Next & previous buttons */
.prev,
.next {
  cursor: pointer;
  position: relative;
  top: 40%;
  width: auto;
  padding: 16px;
  margin-top: -50px;
  color: white;
  font-weight: bold;
  font-size: 20px;
  border-radius: 0 3px 3px 0;
  user-select: none;
  -webkit-user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover,
.next:hover {
  background-color: rgba(0, 0, 0, 0.8);
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: relative;
  top: 0;
}

/* Container for image text */
.caption-container {
  text-align: center;
  background-color: #222;
  padding: 2px 16px;
  color: white;
}

.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Six columns side by side */
.column {
  float: left;
  width: 16.66%;
}

/* Add a transparency effect for thumnbail images */
.demo {
  opacity: 0.6;
}

.active,
.demo:hover {
  opacity: 1;
}
</style>
				<script>
        function myFunc(prefix) {
            var one = document.getElementById('Home').style.display = 'none';
            var two = document.getElementById('About').style.display = 'none';
            var tree = document.getElementById('Contact').style.display = 'none';
            var four = document.getElementById('Tools').style.display = 'none';
            document.getElementById(prefix).style.display = 'block';
        }
    </script>
				<title>Memories</title>
				<script>
var slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("demo");
  var captionText = document.getElementById("caption");
  if (n > slides.length) {slideIndex = 1}
  if (n < 1) {slideIndex=slides.length} for (i=0; i
					< slides.length; i++) { slides[i].style.display="none" ; } for (i=0; i
					< dots.length; i++) { dots[i].className=dots[i].className.replace(" active" ,"" ); } slides[slideIndex-1].style.display="block" ; dots[slideIndex-1].className +=" active" ; captionText.innerHTML=dots[slideIndex-1].alt; }
				</script>
			</head>
			<body>
				<header>
					<nav class="topnav">
						<a href="#" onclick="myFunc('Home')">Home</a>
						<a href="#" onclick="myFunc('About')">About</a>
						<a href="#" onclick="myFunc('Contact')">Contact</a>
						<a href="#" onclick="myFunc('Tools')">Tools</a>
						<a href="#" onclick="myFunc('AddNew')">Add New</a>
						<a class="glow" href="https://scontent.fsof11-1.fna.fbcdn.net/v/t1.6435-9/126174197_10221538045992967_4802511262842372060_n.jpg?_nc_cat=104&ccb=1-5&_nc_sid=174925&_nc_ohc=tbBWtD1uYxgAX9UpYgl&_nc_ht=scontent.fsof11-1.fna&oh=00_AT_j7EK35_mYRyuD3mPh3cKc1T0_4T99Aemkfc81clpT8A&oe=61F38675" onclick="myFunc('Tools')">TURBO</a>
					</nav>
				</header>
				<div id="Home" class="page" style="display: block;">
					<div>
						<h1>Home</h1>
					</div>
				</div>
				<div id="About" class="page" style="display: none;">
					<h2>About</h2>
				</div>
				<div id="Contact" class="page" style="display: none;">
					<h3>Contact</h3>
				</div>
				<div id="Tools" class="page" style="display: none;">
					<h4>Tools</h4>
					<h2 style="text-align:center">Slideshow Gallery</h2>
					<div class="container">
						<div class="mySlides">
							<div class="numbertext">1 / 6</div>
							<img src="https://learnenglishteens.britishcouncil.org/sites/teens/files/styles/article/public/field/image/rs185_177502406-low.jpg?itok=ubWa1SJj" style="width:100%">
  </div>
							<div class="mySlides">
								<div class="numbertext">2 / 6</div>
								<img src="https://learnenglishteens.britishcouncil.org/sites/teens/files/styles/article/public/field/image/rs185_177502406-low.jpg?itok=ubWa1SJj" style="width:100%">
  </div>
								<div class="mySlides">
									<div class="numbertext">3 / 6</div>
									<img src="https://learnenglishteens.britishcouncil.org/sites/teens/files/styles/article/public/field/image/rs185_177502406-low.jpg?itok=ubWa1SJj" style="width:100%">
  </div>
									<div class="mySlides">
										<div class="numbertext">4 / 6</div>
										<img src="https://learnenglishteens.britishcouncil.org/sites/teens/files/styles/article/public/field/image/rs185_177502406-low.jpg?itok=ubWa1SJj" style="width:100%">
  </div>
										<div class="mySlides">
											<div class="numbertext">5 / 6</div>
											<img src="https://learnenglishteens.britishcouncil.org/sites/teens/files/styles/article/public/field/image/rs185_177502406-low.jpg?itok=ubWa1SJj" style="width:100%" alt="pile">
  </div>
											<div class="mySlides">
												<div class="numbertext">6 / 6</div>
												<img src="https://learnenglishteens.britishcouncil.org/sites/teens/files/styles/article/public/field/image/rs185_177502406-low.jpg?itok=ubWa1SJj" style="width:100%">
  </div>
												<a class="prev" onclick="plusSlides(-1)">❮</a>
												<a class="next" onclick="plusSlides(1)">❯</a>
												<div class="caption-container">
													<p id="caption"/>
												</div>
												<div class="row">
													<div class="column">
														<img class="demo cursor" src="https://learnenglishteens.britishcouncil.org/sites/teens/files/styles/article/public/field/image/rs185_177502406-low.jpg?itok=ubWa1SJj" style="width:100%" onclick="currentSlide(1)" alt="The Woods">
    </div>
														<div class="column">
															<img class="demo cursor" src="https://learnenglishteens.britishcouncil.org/sites/teens/files/styles/article/public/field/image/rs185_177502406-low.jpg?itok=ubWa1SJj" style="width:100%" onclick="currentSlide(2)" alt="Cinque Terre">
    </div>
															<div class="column">
																<img class="demo cursor" src="https://learnenglishteens.britishcouncil.org/sites/teens/files/styles/article/public/field/image/rs185_177502406-low.jpg?itok=ubWa1SJj" style="width:100%" onclick="currentSlide(3)" alt="Mountains and fjords">
    </div>
																<div class="column">
																	<img class="demo cursor" src="https://learnenglishteens.britishcouncil.org/sites/teens/files/styles/article/public/field/image/rs185_177502406-low.jpg?itok=ubWa1SJj" style="width:100%" onclick="currentSlide(4)" alt="Northern Lights">
    </div>
																	<div class="column">
																		<img class="demo cursor" src="https://learnenglishteens.britishcouncil.org/sites/teens/files/styles/article/public/field/image/rs185_177502406-low.jpg?itok=ubWa1SJj" style="width:100%" onclick="currentSlide(5)" alt="Nature and sunrise">
    </div>
																		<div class="column">
																			<img class="demo cursor" src="https://learnenglishteens.britishcouncil.org/sites/teens/files/styles/article/public/field/image/rs185_177502406-low.jpg?itok=ubWa1SJj" style="width:100%" onclick="currentSlide(6)" alt="Snowy Mountains">
    </div>
																		</div>
																	</div>
																</div>
																<div id="AddNew" class="page" style="display: none;">
																	<h3>Add new MEME</h3>
																	<div>
																		<form action="/action_page.php" method="get" target="_blank">
																			<label for="fname">First name:</label>
																			<input type="text" id="fname" name="fname">
																				<br>
																					<br>
																						<label for="lname">Last name:</label>
																						<input type="text" id="lname" name="lname">
																							<br>
																								<br>
																									<label for="files">Select meme/memes :</label>
																									<input type="file" id="files" name="files" multiple>
																									<input type="submit" value="Submit using GET">
																										<input type="submit" formmethod="post" value="Submit using POST">
  </form>
																										<form>
   
  </form>
																									</div>
																								</div>
																							</body>
																						</html>
