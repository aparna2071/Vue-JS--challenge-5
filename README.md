# Vue-JS--challenge-5

Event handling:
-	For eg: we created a button in html file & want to increment the cart if the button is clicked, so we take the default value of cart in js file & add an onclick event in html file.
-	In html: <button v-on:click=”cart+=1”>Add to cart</button> , In js: cart:0 but this is not realistic, so let’s define a method addTocart() in js & call that method in html on click.
-	Whenever creating event handling method in js: always use this, this refers to the current Vue instance’s data as well as other methods declared inside the instance
-	Events: click, mouseover etc. 
-	Shorthand for v-on is @
Challenge of event handling: on hovering to color, the color of socks changes, create add to cart & remove from cart buttons

- https://codepen.io/aparnasoneja/pen/GRxJyNZ
