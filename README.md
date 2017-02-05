Website hosting
https://feedaki.gr/Pizza/pizza.html


Check with:
PageSpeed Insights
gtmetrix

Photoshop
https://kraken.io/web-interface

change images size pizza.png and pizzeria.jpg save on web



pizza.html

remove  
</html>
style="width:33.33%; height: 325px;"

add
<div id="pizza0" class="col-4 randomPizzaContainer">
<div id="pizza1" class="col-4 randomPizzaContainer">
<div class="lesswidth">
<div class="maxwidth">


style.css
add
.randomPizzaContainer



main.js

add
 pizzaDescriptionContainer.className("max-width");
pizzaImageContainer.className("less-width");

edit 
var rows = Math.ceil(window.innerHeight /256) * 8;
function changePizzaSizes(size) {
var left = -items[i].basicLeft + 1000 * phase + 'px';
items[i].style.transform = "translateX("+left+") translateZ(0)";


remove
//pizzaContainer.style.width = "33.33%";
//	pizzaContainer.style.height = "325px";
// pizzaDescriptionContainer.style.width = "65%";
	//pizzaImageContainer.style.width = "35%";
	
 