# Display-none-Challenge 

<html>

	<head>
		<meta charset="utf-8">
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<title>display:none</title>
		<link rel="stylesheet" href="style.css" /> 
		
	</head>

	<body> 
		<div class="row center-child">
			<img src="images/iterate.jpg" class="restrict-img"> 
		</div>
	</body>
	
</html> 

body {
	width: 100%;
	height: 100%;
	margin: 0; 
	background-color: black;
	/* default display value is 'block' so you don't have to write anything here! */
}

.row { 
	height: 50%;
	width: 100%; 	
	background-color: gold; 
	position: relative; 
	top: 500px 
} 


.black {
	background-color: #000000;
}

.gold {
	background-color: #D4AF37;
}

.center-child {
	display: flex;
	align-items: center;
	justify-content: center; 
}

.restrict-img {
	max-height: 100%;
	max-width: 80%; 	
} 

/* make everything disappear */
@media only screen and (max-width: 1000px) { 
	body { 
	display: none;
	}

}

/* make everything reappear */
@media only screen and (max-width: 700px) {
	
	body { 
	  display: flex
	} 
	

/* make just the image disappear */
@media only screen and (max-width: 500px) { 
    
	img { 
	 display: none 
	}
   

}

