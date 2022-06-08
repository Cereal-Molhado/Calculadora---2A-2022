<!DOCTYPE html>
<html lang = "en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="Calculadora/Calculadora-Css.css">
<title> Calculadora DiCria </title>

</head>
<body>

<div id= "Calculadora">
<h1> Calculadora DiCria </h1>
<form name= "clique">
	
  <input id="caixaCalculo" type= "text" name= "numero"> <br> <br>

  <input type="button" value= "7" onclick= "clique.numero.value += '7' ">
  <input id="botão" type= "button" value= "8" onclick= "clique.numero.value += '8' ">
  <input id="botão" type= "button" value= "9" onclick= "clique.numero.value += '9' ">
  <input id="botãoEspecial" type= "button" value= "/" onclick= "clique.numero.value += '/' ">
  
  <input type = "button" value= "4" onclick= "clique.numero.value += '4' ">
  <input id="botão" type= "button" value= "5" onclick= "clique.numero.value += '5' ">
  <input id="botão" type= "button" value= "6" onclick= "clique.numero.value += '6' ">
  <input id="botãoEspecial" type= "button" value= "-" onclick= "clique.numero.value += '-' ">
  
  
  <input type="button" value= "1" onclick= "clique.numero.value += '1' ">
  <input id="botão" type= "button" value= "2" onclick= "clique.numero.value += '2' ">
  <input id="botão" type= "button" value= "3" onclick= "clique.numero.value += '3' ">
  <input id="botãoEspecial" type= "button" value= "*" onclick= "clique.numero.value += '*' ">
  
  
  <input id= "botãoC" type= "button" value= "C" onclick= "clique.numero.value = ' ' " >
  <input id="botão" type= "button" value= "0" onclick= "clique.numero.value += '0' ">
  <input id="botãoEspecial" type= "button" value= "=" onclick= "clique.numero.value = eval(clique.numero.value) ">
	<input id="botãoEspecial" type= "button" value= "+" onclick= "clique.numero.value += '+' ">
  
</form>
</div>

</body>
</html>
