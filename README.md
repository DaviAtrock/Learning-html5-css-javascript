# Learning-html5-css-javascript
These are some of my current learning exercises from the College.

index.html

<!DOCTYPE html>
<html lang="en" xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta charset="utf-8" /> <!--Metadados-->
    <title>D&L Atacadista</title>
    <link rel="stylesheet" type="text/css" href="style.css">
        <div class="home">
        <div class="nav"> <!--Páginas do Topo-->
<ul>
    <li><a href="#">Menu</a></li>
    <li><a href="./HTMLPage1.html">Produtos</a></li>
    <li><a href="./index.html">Preços</a></li>
    <li><a href="https://www.google.com">Cadastro</a></li>
    <li><a href="https://www.google.com">Sobre</a></li>
</ul>
<!--Abaixo são os procedimento do CSS-->
<style> /*Fontes*/
    @import
    url('https://fonts.googleapis.com/css2?family=Poppins:wght@200&display=swap');
</style>
</head>
<body>
</body>
</html>
  
  style.css
  
 body {background-color: white;}
.nav {height: 50px; background: red;}
.nav ul {position: absolute; left: 0px}
.nav ul li {display: inline-block;}
.nav ul li a {color: white; padding: 5px;} 
.text-container {text-align: center; display: flex; align-items: center; justify-content: center; height: 50px;}
