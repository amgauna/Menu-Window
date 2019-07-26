# menu-window
Exemplo de menu window.open()

<!DOCTYPE html>

<html lang="pt">

<title>Menu (exemplo)</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Poppins">
<style>
body,h1,h2,h3,h4,h5 {font-family: "Poppins", sans-serif}
body {font-size:16px;}
.w3-half img{margin-bottom:-6px;margin-top:16px;opacity:0.8;cursor:pointer}
.w3-half img:hover{opacity:1}
</style>

<body>

<menu type="context" class="navigation" style="word-spacing:20px; width:100%; height:auto; 
      margin:0px; padding:10px; cursor:pointer; background-color: #ffffff !important;">

    <menuitem label="#Home">
    <a href="#" onclick="window.open('home.html');">	
    <span class="glyphicon glyphicon-home">Home</span> </a> </menuitem> 
	
	<menuitem label="#Sobre" target="_self">
    <a href="#" onclick="window.open('sobre.html');">		
	<span class="glyphicon glyphicon-briefcase" target="_self">Sobre</span> </a> </menuitem>
	
	<menuitem label="#Serviços" target="_self">
    <a href="#" onclick="window.open('servicos.html');">		
	<span class="glyphicon glyphicon-usd">Serviços</span> </a> </menuitem> 
	
	<menuitem label="#Contato"  target="_self">
	<a href="#" onclick="window.open('contato.html');">  
	<span class="glyphicon glyphicon-th-large">Contato</span> </a> </menuitem> 
</menu>

</body>

</html>

