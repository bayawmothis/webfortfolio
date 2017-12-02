<!DOCTYPE html>
<html>
<head>
	<title>Takeji G. Surizaki jr</title>
	<link rel="stylesheet" type="text/css" href="css/animate.css">
	<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
	<link rel="stylesheet" type="text/css" href="css/style.css">
	<script type="text/javascript" src="js/jquery.min.js"></script>
</head>
<body>
	<script>
	$(document).ready(function(){
		var index = 0;
		var images = ["s2.jpg", "cv.jpg"];
		$('#btn').on('click', function(){
			if (index == 1) {
				index = 0;
			}
			$('#salamin').attr("src", "images/" + images[++index]);
		})
	})	
	</script>
	<header id="main-header">
		<center>
    	<h1>Takeji.S&#8482</h1>
    	</center>	
	</header> <!-- mainheader -->
	<section id="banner"> 
		<h2>Hello there!, I'm Takeji. I design and build</h2>
		<br>
		<h2><span id="spin" ></span></h2><br><br><br><br><br>
		<center><a href="#section1"  class="button"><span>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspAbout Me&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp</span></a></center>

	</section>
<section id="section1">
	<div class="container">
		<div class="row">
				<div class="col-md-12">
					<img id="salamin" src="images/s2.jpg"  class="img-block ">
					</div>
				</div>	
		</div>
	</div>
	<center><a href="#section3"  class="button"><span>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspMy Expertise&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp</span></a><a href="#section1" id="btn" class="button"><span>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspMy CV&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp</span></a></center><br><br><br>
	

</section> <!-- section1 -->
<section id="section3" class="page-section">
	<div class="container" id="sentro">
		<div class="row">
			<div class="col-md-4">
				<p>Ideas</p>
			</div>
			<div class="col-md-4">
				<p>UX/UI</p>
			</div>
			<div class="col-md-4">
				<p>Code</p>
			</div>
		</div>
	</div>
	<div class="container">
		<div class="row">
			<div class="col-md-4">
				<p>I collaborate with clients and peers to nurture and transform ideas into well thought out design specs. After all, that's where the majority of amazing user experiences start.</p>
			</div>
			<div class="col-md-4">
				<p>I sketch and wireframe interfaces focusing on content structure, intuitive UI patterns and simple interactions. I'm a minimalist who truly believes that less is more.</p>
			</div>
			<div class="col-md-4">
				<p>I design in the browser with HTML(5), CSS(3) and a touch of JavaScript. I love coding things from scratch, but I can work with front-end frameworks like Bootstrap too.</p>
			</div>
		</div>
	</div>
	
	<div class="container">
		<div class="row">
			<div class="class-col-md-12">
				<h2 class="text-center" style="color:#7f8287"><strong>Get in Touch</strong></h2>
				<center>
				<p>I'm currently accepting new projects and would love to hear about yours. Please take a few minutes to tell me about it.</p>
				<form id="contact-form" action="" method="post">
					<div class="input-group">
						<label class="">Full Name</label>
						<input type="text" name="fullname">						
					</div>
					<div class="input-group">
						<label class="">Email Address</label>
						<input type="email" name="Email">					
					</div>
					<div class="input-group">
						<label class="">Contact Number</label>
						<input type="number" name="Contact Number">					
					</div>
					<div class="input-group">
						<label class="">Message</label>
						<input type="text" name="text">				
					</div>
					<button type="button" class="btn btn-success">SEND</button>
				</form>
			</div>
			</center>			
		</div>
	</div>

</section>
</body>
</html>
