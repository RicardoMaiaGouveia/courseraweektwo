<!doctype html>
<html>
<head>
<link rel="stylesheet" href="css/css.css">
<meta charset="utf-8">
<meta name='viewport' content='width=device-width, initial-scale=1'>
<title>Module 2 Coding Assignment</title>
</head>
<body>
<h1>Our Menu</h1>
<div class='row'>
	<div class='col-lg-4 col-md-6 sx-12'>
		<div class='section'>
			<span id='nr1'>Chicken</span>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
		</div>
	</div>
	<div class='col-lg-4 col-md-6 sx-12'>
		<div class='section'>
			<span id='nr2'>Beef</span>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
		</div>
	</div>
	<div class='col-lg-4 col-md-12 sx-12'>
		<div class='section'>
			<span id='nr3'>Sushi</span>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
		</div>
	</div>
</div>
</body>
</html>


<style>


* {
  box-sizing: border-box;
}

h1 {
	font-size: 27px;
	font-family: Georgia serif;
	text-align: center;
	color: rgb(0, 0, 0);
	margin-bottom: 30px;
}

p {
	padding: 15px 5px 0px 5px;
	font-family: Georgia sans-serif;
	font-size: 16px;
	position: relative;
}

.section { 
	background-color: rgb(150, 150, 150);
   	border: 2px solid black;
   	margin-top: 20px; 
   	margin-right: 20px; 
   	padding: 3px;
   	text-align: justify;
   	position: relative;
 }

span {
	font-size: 20px;
	width: 150px;
	border: 1px solid black;
	font-weight: bold;
	text-align: center;
	float: right; top :0; right: 0; margin: 0;
	position: absolute;
}

#nr1 {
	background-color: rgb(235, 160, 160);
	color: rgb(0, 0, 0);
}

#nr2 {
	background-color: rgb(223, 115, 115);
	color: rgb(250, 250, 250);
}

#nr3 {
	background-color: rgb(230, 230, 156);
	color: rgb(0, 0, 0);
}


.row {
	width: 100%;
}

/* Desktop size */

@media (min-width: 992px) {
 
  .col-lg-4 {
    width: 33.33%;
    float: left;
	}
}

/* Tablet size */

@media (min-width: 768px) and (max-width: 991px) {
 
  .col-md-6 {
    width: 50%;
    float: left;
  }
  .col-md-12 {
    width: 100%;
    float: left;
  }
}

/* Cellphone size */

@media (max-width: 767px)  {
  
  .col-sx-12 {
  	float: left;
    width: 100%;
  }
}


</style>
