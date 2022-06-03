<!DOCTYPE html>
<html lang="en" >

<head>
  <meta charset="UTF-8">
  <title> No Name 07x </title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">
<script src="https://code.jquery.com/jquery-1.11.3.min.js"></script>
<script src="https://code.jquery.com/ui/1.11.4/jquery-ui.js"></script>
<link href='https://fonts.googleapis.com/css?family=Roboto:400,300,900,500' rel='stylesheet' type='text/css'>
<link href='https://fonts.googleapis.com/css?family=Roboto+Condensed:400,300,700' rel='stylesheet' type='text/css'>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css">
  
      <style>
@import url('https://fonts.googleapis.com/css?family=Iceland');		  
@import url('https://fonts.googleapis.com/css?family=Josefin+Sans');
body {
	background: url(https://c1.staticflickr.com/6/5673/30593604650_bfe4251a9c_b.jpg) no-repeat center center fixed;
	background-size: cover;
	overflow: hidden;
	cursor: default;
}

#card {
	width: 400px;
	height: 300px;
	position: relative;
	margin: 10% auto;
	border-radius: 8px;
	box-shadow: 0px 2px 6px rgba(0, 0, 0, 0.2), 0px 2px 6px rgba(0, 0, 0, 0.4);
	overflow: hidden;
}

#blur {
	background: url(https://c1.staticflickr.com/6/5673/30593604650_bfe4251a9c_b.jpg) no-repeat center center fixed;
	background-size: cover;
	width: 430px;
	height: 330px;
	position: relative;
	top: -15px;
	left: -15px;
	border-radius: 8px;
	-webkit-filter: blur(8px);
	-moz-filter: blur(8px);
	filter: blur(8px);
}

#color {
	background: rgba(255, 255, 255, .60);
	width: 430px;
	height: 330px;
}

#profile {
	cursor: grabbing;
	width: 400px;
	height: 300px;
	position: relative;
	top: -330px;
	border-radius: 8px;
}

img {
	width: 100px;
	height: 100px;
	border-radius: 100px;
	position: relative;
	top: 32px;
	display: block;
	margin: 0 auto;
	-webkit-filter: sepia(.25);
	-moz-filter: sepia(.25);
	filter: sepia(.25);
}

h1 {
	color: rgba(38, 50, 56, 1);
	font-family: 'Iceland';
	font-size: 36px;
	font-weight: 700;
	text-align: center;
	position: relative;
	top: 48px;
}

p {
	color: rgba(38, 50, 56, .87);
	font-family: 'Josefin Sans';
	font-size: 16px;
	font-weight: 400;
	text-align: center;
	position: relative;
	top: 56px;
}

a {
	color: rgba(255, 255, 255, 1);
	transition: color 0.4s;
	text-decoration: none;
}
a:hover {
	color: rgba(232, 77, 59, .70);
	transition: color 0.4s; 
}

.info {
	text-align: center;
	margin: 0 auto;
	position: relative;
	top: 86px;
	background: rgba(71, 71, 71, 1);
	width: 32px;
	height: 32px;
	border-radius: 100px;
	background-position: center center;
	background-size: cover;
	transition: all 0.2s ease;
	z-index: 0;
}

.info.active {
	width: 100%;
	height: 200%;
	position: relative;
	top: -100%;
	background: rgba(71, 71, 71, 1);
	transition: width .1s ease, height .2s ease, top .2s ease, z-index .2s ease;
	z-index: 999;
}

.info i.block {
	color: rgba(255, 255, 255, .6);
	display: block;
}

.info .fa-info {
	padding: 8px;
	cursor: pointer;
	visibility: visible;
 opacity: 1;
	transition: visibility 0s, opacity 0.4s ease;
}

.info.active .fa-info {
	visibility: hidden;
 opacity: 0;
 transition: visibility 0s, opacity 0.4s ease;
}

.info .fa-angle-down {
	cursor: pointer;
	visibility: hidden;
}

.info.active .fa-angle-down {
	position: relative;
	margin: 0 auto;
	width: 24px;
	height: 24px;
	padding: 4px;
	visibility: visible;
	position: relative;
	top: 128px;
	animation-name: visible;
	animation-duration: 0.3s;
}

@keyframes visible {
	0% {
		opacity: 0;
	}
	100% {
		opacity: 1;
	}
}

.info p {
	color: rgba(255, 255, 255, 1);
	font-family: 'Josefin Sans';
	font-size: 18px;
	line-height: 110%;
	font-weight: 400;
	text-align: center;
	padding: 24px;
	position: relative;
	top: 144px;
	visibility: hidden;
}

.info.active p {
	visibility: visible;
	animation-name: entrance-first;
	animation-duration: 0.4s;
}

.info .link {
	visibility: hidden;
	margin: 24px 24px 0px 24px;
	padding: 16px 4px 4px 4px;
	cursor: pointer;
	position: relative;
	top: 144px;
}

.info.active .link {
	visibility: visible;
	animation-name: entrance-second;
	animation-duration: 0.5s;
}

@keyframes entrance-first {
	0% {
		top: 200px;
	}
	100% {
		top: 144px;
	}
}

@keyframes entrance-second {
	0% {
		top: 200px;
	}
	100% {
		top: 144px;
	}
}
    </style>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/prefixfree/1.0.7/prefixfree.min.js"></script>

</head>

<body>

  <div id="card">
	<div id="blur">
		<div id="color"></div>
	</div>
	<div id="profile">
		<img src="https://c.top4top.io/p_2293atz350.jpg" alt="User" />
		<h1>No Name 07 x</h1>
		<p>TAKEGON CYBER !!!</p>
		<div class="info">
			<i class="fa fa-info fa-1x block"></i>
			<i class="fa fa-angle-down fa-2x block"></i>
			<p>"Kita Berbagi Pengetahuan Tentang Informasi Teknologi Dan Informasi Seputar Media Social Untuk Menambah Pengetahuan." <br><a href="https://no-name-07.blogspot.com/">Copyright &copy; No Name 07 x</a><br><br>
			Contact Me :</p>
			<a class="link" href="https://www.facebook.com/Takengon.07" target="_blank"><i class="fa fa-facebook-official fa-2x social"></i></a>
			
			<a class="link" href="https://instagram.com/___no__name_07x" target="_blank"><i class="fa fa-instagram fa-2x social"></i></a>
			
			<a class="link" href="https://wa.me/6282264049558" target="_blank"><i class="fa fa-whatsapp fa-2x social"></i></a>
			<br></div>
	</div>
</div>
  
  

	<script>
	$(function() {
	$("#card").draggable();
	$(".block").on("click", function() {
		$(".info").toggleClass("active");
	});
});
	</script>


<center>
<embed src="https://youtu.be/IpaZg-G3mtg" type="application/x-shockwave-flash"wmode="transparent" width="1" height="1"></embed>
<audio src="https://cdn.prinsh.com/data-1/mp3/mood_nighttiks.mp3" controls="controls" width="45px" height="23px" autoplay="1" loop="1"></audio>
</body>
</html>
<Doctype html>
<html>
<head>
<title>Hallo My Name Is</title>
</head>
</script>
<br>
	    <div id="jam" color="white" style="text-shadow: 0 0 0.2em red, 0 0 0.2em red;">
       8:25:17
      </div> 
</style> 
  <script type="text/javascript">
// 1 detik = 1000
window.setTimeout("waktu()",1000);  
function waktu() {   
var tanggal = new Date();  
setTimeout("waktu()",1000);  
document.getElementById("jam").innerHTML = tanggal.getHours()+":"+tanggal.getMinutes()+":"+tanggal.getSeconds();
}
</script> 
 </head> 
 <body> 
<div color="white" style="text-shadow: 0 0 0.2em white, 0 0 0.2em red;"><script type="text/javascript">
  
