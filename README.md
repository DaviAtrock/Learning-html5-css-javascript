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
    <li><a href="index.html">Início</a></li>
    <li><a href="produtos.html">Produtos</a></li>
    <li><a href="precos.html">Preços</a></li>
    <li><a href="cadastro.html">Cadastro</a></li>
    <li><a href="sobre.html">Sobre</a></li>
</ul>
<img src="logo.jpg">
<!--Abaixo são os procedimento do CSS-->
<style> /*Fontes*/
    @import
    url('https://fonts.googleapis.com/css2?family=Poppins:wght@200&display=swap');
</style>
</head>
<body>
</body>
</html>
    
cadastro.html
    
<!DOCTYPE html>

<html lang="en" xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta charset="utf-8" /> <!--Metadados-->
    <title>D&L Atacadista</title>
    <link rel="stylesheet" type="text/css" href="style.css">
        <div class="home">
        <div class="nav"> <!--Páginas do Topo-->
<ul>
    <li><a href="index.html">Início</a></li>
    <li><a href="produtos.html">Produtos</a></li>
    <li><a href="precos.html">Preços</a></li>
    <li><a href="cadastro.html">Cadastro</a></li>
    <li><a href="sobre.html">Sobre</a></li>
</ul>
<img src="logo.jpg">
<!--Abaixo são os procedimento do CSS-->
<style> /*Fontes*/
    @import
    url('https://fonts.googleapis.com/css2?family=Poppins:wght@200&display=swap');
</style>
</head>
<body>
    <div class="container">

        <form class="well form-horizontal" action=" " method="post"  id="contact_form">
    <fieldset>
    
    <legend><center><h2><b>Registro</b></h2></center></legend><br>
    
    <!-- Text input-->
    
    <div class="form-group">
      <label class="col-md-4 control-label">Nome(*):</label>  
      <div class="col-md-4 inputGroupContainer">
      <div class="input-group">
      <span class="input-group-addon"><i class="glyphicon glyphicon-user"></i></span>
      <input  name="Nome" placeholder="Nome" class="form-control"  type="text">
        </div>
      </div>
    </div>
    
    <!-- Text input-->
    
    <div class="form-group">
      <label class="col-md-4 control-label" >Sobrenome(*):</label> 
        <div class="col-md-4 inputGroupContainer">
        <div class="input-group">
      <span class="input-group-addon"><i class="glyphicon glyphicon-user"></i></span>
      <input name="Sobrenome" placeholder="Sobrenome" class="form-control"  type="text">
        </div>
      </div>
    </div>
      
    <!-- Text input-->
    
    <div class="form-group">
      <label class="col-md-4 control-label">Nome de Usuário(*):</label>  
      <div class="col-md-4 inputGroupContainer">
      <div class="input-group">
      <span class="input-group-addon"><i class="glyphicon glyphicon-user"></i></span>
      <input  name="Nome de Usuário" placeholder="Usuário" class="form-control"  type="text">
        </div>
      </div>
    </div>
    
    <!-- Text input-->
    
    <div class="form-group">
      <label class="col-md-4 control-label" >Senha(*):</label> 
        <div class="col-md-4 inputGroupContainer">
        <div class="input-group">
      <span class="input-group-addon"><i class="glyphicon glyphicon-user"></i></span>
      <input name="senha" placeholder="Senha" class="form-control"  type="password">
        </div>
      </div>
    </div>
    
    <!-- Text input-->
    
    <div class="form-group">
      <label class="col-md-4 control-label" >Confirme a Senha(*):</label> 
        <div class="col-md-4 inputGroupContainer">
        <div class="input-group">
      <span class="input-group-addon"><i class="glyphicon glyphicon-user"></i></span>
      <input name="Confirme a senha" placeholder="Confirme a Senha" class="form-control"  type="password">
        </div>
      </div>
    </div>
    
    <!-- Text input-->
           <div class="form-group">
      <label class="col-md-4 control-label">E-Mail(*):</label>  
        <div class="col-md-4 inputGroupContainer">
        <div class="input-group">
            <span class="input-group-addon"><i class="glyphicon glyphicon-envelope"></i></span>
      <input name="email" placeholder="E-Mail" class="form-control"  type="text">
        </div>
      </div>
    </div>
    
    <!-- Text input-->
           
    <div class="form-group">
      <label class="col-md-4 control-label">Telefone:</label>  
        <div class="col-md-4 inputGroupContainer">
        <div class="input-group">
            <span class="input-group-addon"><i class="glyphicon glyphicon-earphone"></i></span>
      <input name="contact_no" placeholder="( )" class="form-control" type="text">
        </div>
      </div>
    </div>
    
    <!-- Select Basic -->
    
    <!-- Button --><!--Explicar alteracao-->
    <div class="form-group">
      <label class="col-md-4 control-label"></label>
      <div class="col-md-4"><br>
        &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp<button type="submit" class="btn btn-warning">&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspENVIAR <span class="glyphicon glyphicon-send"></span>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp</button>
      </div>
    </div>
    
    </fieldset>
    </form>
    </div>
        </div><!-- /.container -->
</body>
</html>    
    
style.css
  
body {background-color: white;}
.nav {height: 110px; background: red;}
.nav ul {position: absolute; left: 0px;}
.nav ul li {display: inline-block;}
.nav ul li a {color: white; padding: 05px;} 
.text-container {text-align: center; display: flex; align-items: center; justify-content: center; height: 50px;}
img {max-width: 100%; max-height: 100%; display: block; margin-left: auto; margin-right: auto;}
