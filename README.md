# My-Web-buildup
This is a web file am working on

<!DOCTYPE html>
<html>
	<head> <title> Pro book </title> 
		<metacharset UTF-8>
	</head>
		<body>
			<header>
				<nav>
					<ul>
						<li> <a href="#"> Home </a> </li>
						<li> <a href="#"> About Us </a></li>
						<li> <a href="#"> Our Mission </a></li><br>
						<li> <details open>
							<summary> Acomplishments </summary>
							<ul>
								<li><a href="#"> Awards </a></li>
								<li><a href="#"> Growth </a></li>
								<li><a href="#"> Accolades </a></li>
							</ul></details>
						</li>
					</ul>
				</nav>
			</header>
			<main>
				<article>
					<section>
						<h2> How to be a PRO at anything </h2>
						<p> It is an exceptionally good feeling to know you are
						    good at whatever you wan to be.
					</section>
					<section>
						<!-- here shows an image of someone who is a pro @football.
						I intend to use this image as a link-->
						<a href="#link to details>
						<figure>
							<img src="messi.jpg" alt="Football Pro"/>
						<figcaption> Messi</figcaption>
						</figure>
						</a>
					</section> 
					<section>
						<!-- This section shows a video on how he struggled to make it -->
						<video controls>
							<source src=" messi vid.mp4"/>
							<source src="messi vid.ogg"/>
							<source src="messi vid.mkv"/>
						<p> This Browser cannot play this video</p>
						</video>
					</section>
				</article>
			</main>
			<footer>
				<h4> Want to know more about how to be great for yourself?<h4>
				<h5>Fill out the form below and have us contact you<h5>
				<form>
					<label> Email</label>
					<input type="text" placeholder="e-mail">
					<label> Best Color</label>
					<input type="text"
					list="colors"/>
					<datalist id="colors">
					<option value="blue"></option>
					<option value="red"></option>
					<option value="pink"></option>
					<option value="green"></option>
					</datalist>
					<label> Date of Birth</label>
					<input type="datetime"/>
				</form>
