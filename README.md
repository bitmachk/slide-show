# slide-show
JavaScript on Webpage

## Heading
```
<head>
  <title>Slider: Image Slider Plugin with Unique Effects</title>
    <script type="text/javascript" src="jquery.js"></script> **//set the soure for the targeted jQuery file here
    <script type="text/javascript" src="slider.js"></script> **//connect to the javaScript file of slider show
  <link rel="stylesheet" href="slider-styles.css" type="text/css" /> **//connect to the css file
</head>
```

## Main body
```
<center> 
		<div id="coin-slider">
			<a href="http://www.minininjas.com/" target="_blank">
				<img src="./images/1.jpg" alt="Mini Ninjas" />
				<span>
					<b>Mini Ninjas</b><br />
					Your quest to defeat the Evil Samurai Warlord has begun. Control the powers of nature, possess creatures, use your
					furious Ninja skills to free your Ninja friends.
				</span>
			</a>
			
			<a href="http://www.princeofpersiagame.com/" target="_blank">
				<img src="./images/2.jpg" alt="Price of Persia" />
			</a>
			
			<a href="http://spidermandimensions.marvel.com/" target="_blank">
				<img src="./images/3.jpg" alt="Spiderman: Shattered Dimensions" />
			</a>
			
			<a href="http://brinkthegame.com/" target="_blank">
				<img src="./images/4.jpg" alt="Brink" />
			</a>	
		</div>
</center>
```

## Controller script
```
<script type="text/javascript">
	$(document).ready(function() {
		$('#coin-slider').coinslider({ width: 618, height: 246, delay: 5000 });
	});
</script>
```
