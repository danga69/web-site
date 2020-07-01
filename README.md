<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=0.8">
<p><img class="image" src="covid.jpg" width="50%" height="50%">.</p>
 
    
</head>
<body>

<div class="bg"></div>

<header style="color:black;">If you want good coffee this is the place to be</header>
  <br>      
  <section style="color:black;">we are the best in west</section>
    <br>    
  <footer style="color:black;">so come on down to DAngelos cafe where you can taste quality</footer>
      <br>
  <p style="color:black;">
	Everyone loves this Cafe this cafe is greatly convenient for on the go coffe at small prices come and enjoy our food and drink
    </p>
   
    </body>




<!DOCTYPE html>
<html lang="en">
<head>
<title>CSS Template</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Georgia, Helvetica, sans-serif;
}

/* Style the header */
header {
  background-color: #310;
  padding: 30px;
  text-align: center;
  font-size: 35px;
  color: black;
}

/* Container for flexboxes */
section {
  display: -webkit-flex;
  display: flex;
}

/* Style the navigation menu */
nav {
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
  background: #aaa;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}

/* Style the content */
article {
  -webkit-flex: 3;
  -ms-flex: 3;
  flex: 3;
  background-color: #f1f1f1;
  padding: 10px;
}

/* Style the footer */
footer {
  background-color: #100;
  padding: 10px;
  text-align: center;
  color: red;
}

/* Responsive layout - makes the menu and the content (inside the section) sit on top of each other instead of next to each other */
@media (max-width: 600px) {
  section {
    -webkit-flex-direction: column;
    flex-direction: column;
  }
    
}
    
    .image {
        width: 100%;
        height: 200px;
    }
    
</style>
</head>
<body>

<ul>
<li>Espresso $5</li>
<li>Cafe Latte $6</li>
<li>Double Espresso $3</li>
 <li>Short Black $3</li>   
   <li>Cappucino $8</li>
    <li>Flat White $3</li>
    <li>Americano $4</li>
  
    <header>
  <h2>The Brewed Awakening</h2>
</header>

<section>
  <nav>
    <ul>
      <li><a href="#">New Zealand</a></li>
      <li><a href="#">Auckland</a></li>
      <li><a href="#">Henderson</a></li>
    </ul>
  </nav>
  
  <article>
    <h1>Location of the school cafe</h1>
    <p><img class="image" src="google-maps.png" width="100%" height="100%">.</p>
  </article>
</section>

<footer>
  <p>Copyright Notice:I own this website.</p>
</footer>

</body>
</html>
