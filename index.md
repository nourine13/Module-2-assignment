<!DOCTYPE html>
<html>
<head>
	<title>Module2 Solution</title>
	<meta http-equiv="Content-Type" content="text/html"; charset="utf-8">
	<meta name="viewport" content="width=device-width, height=device-height, initial-scale=1.0, user-scalable=yes">
	<link rel="stylesheet" type="text/css" href="stylesheet.css">
	<link href="https://fonts.googleapis.com/css2?family=Balsamiq+Sans&display=swap" rel="stylesheet">
<style type="text/css">
body {
	font-family: 'Balsamiq Sans', cursive;
}
* {
	box-sizing: content-box;
}
h1 {
	text-align: center;
	margin-bottom: 50px;
}
.chicken, .beef, .sushi {
	border-style: solid;
	width: 400px;
	height: 150px;
	display: inline-block;
	background-color: gray;
	margin: 0px 10px 0px 10px;
}
.chicken > h3, .beef > h3, .sushi > h3 {
	width: 80px;
	height: 25px;
	position: relative;
	left: 140px;
	bottom: 3px;
	margin: 0;
	text-align: center;
	border-style: solid;
	padding: 0px 20px 0px 20px;

}

.chicken > h3 {
	background-color: pink;
}
.beef h3 {
	background-color: red;
	color: white;
	border-color: black;
}
.sushi > h3 {
	background-color: yellow;

}
.chicken > p, .beef > p, .sushi > p {
	text-align: left;
	padding: 0 20px 10px 20px;
	font-weight: bold;
}
@media screen and (min-width: 992px) {
	.chicken, .beef, .sushi {
		width: 400px;
		height: 150px;
	}
	.chicken > h3, .beef > h3, .sushi > h3 {
		left: 140px;
	}
}
@media screen and (min-width: 768px) and (max-width: 991px) {
	.chicken, .beef {
		width: 290px;
		height: 200px;
		margin: 0px 20px 20px 20px;
	}
	.sushi {
		width: 632px;
	}
	.chicken > h3, .beef > h3 {
		left: 85px;
	}
	.sushi > h3 {
		left: 256px;
	}
}
@media screen and (max-width: 767px) {
	.chicken, .beef, .sushi {
		margin-bottom: 20px;
	}
}
</style>

</head>
<body>
<h1>Our Menu</h1>
<center>
	<div class="chicken">
		<h3>Chicken</h3>
		<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
		tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
		quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
		consequat.</p>
	</div>
	<div class="beef">
		<h3>Beef</h3>
		<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
		tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
		quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
		consequat.</p>
	</div>
	<div class="sushi">
		<h3>Sushi</h3>
		<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
		tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
		quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
		consequat.</p>
	</div>
</center>
</body>
</html>
