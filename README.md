<!DOCTAYPE html>
<html lang="pt-br">
  <head>
    
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/estilo.css">
    <title>teste</title>
    <style>
    *{
  box-sizing: border-box;
}
body{
  margin:0;
}
.navbar{
  display:flex;
  flex-flow: row wrap;
  height: 100px;
  background:white;
  justify-content: center;
  align-items: center;
}
.logo h1{
  font-family: cursive;
  color:#180F4A;
  font-size: 34px;
  margin-left: 10%;
}
.logo{
  flex:20%;
  /*border:1px solid black;*/
  text-align: right;
}
.menu{
  flex:80%;
  /*border:1px solid gray;*/
  text-align: center;
}
.menu a{
  color:#180F4A;
  text-decoration: none;
  padding: 12px 12px;
}
#botao{
  color:white;
  background:#180F4A;
  border-radius: 5%;
  margin-right: 5%;
  margin-left:5%;
}
.header{
  display:flex;
  flex-flow:row wrap;
  height: 600px;
  justify-content: center;
  align-items: center;
  /*background:gray;*/
}
.headline{
  flex:45%;
  margin-left: 5%;
 /* border:1px solid black;*/
}
.headline p{
  color:gray;
  text-align: left;
}
.contact-btn{
  display:inline-block;
  background: #180F4A;
  color:white;
  padding: 20px;
  text-decoration: none;
  text-transform: uppercase;
  border-radius: 5px;
}
.headline h2{
  font-weight: 900;
  font-size:20px;
  color:#180F4A;
  padding: 0;
  margin:0;
}
.img-headline{
  margin-right: 5%;
  flex:45%;
  text-align: center;
}
footer{
  margin-top:100px;
  height: 300px;
  background-image: linear-gradient(180deg, #180F4A,#090422, black);
  text-align: center;
}
.casa{
  font-family: 'Lobster',cursive;
  color:white;
  font-size: 30px;
}
    </style>
  </head>
  <body>
  <nav class="navbar">
    <div class="logo">
      <h1>Agência</h1>
    </div>
    <div class="menu">
      <a href="#">Home</a>
      <a href="#">Assistência</a>
      <a href="#">Sobre nós</a>
      <a id="botao" href="#">Fale conosco</a>
    </div>
  </nav>
  <header class="header">
    <div class="headline">
      <h2 style="letter-spacing:5px;">Você achou o melhor</h2>
      <br>
      <h2 style="font-size:30px;">Site de Animes</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac ligula sit amet libero tincidunt vulputate.</p>
      <a href="#" class="contact-btn">Assinatrura</a>
    </div>
    <div class="img-headline">
      <img style="max-width:90%;" src="img/satoru.png"
    </div>
  </header>
  <header class="header">
    <div class="headline">
      <h2 style="letter-spacing:5px;">Curiosidades sobre</h2>
      <br>
      <h2 style="font-size:30px;">Animes</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac ligula sit amet libero tincidunt vulputate.</p>
      <a href="#" class="contact-btn">Descubra</a>
    </div>
    <div class="img-headline">
      <img style="max-width:90%;" src="img/zoro.jpg"
    </div>
  </header>
  
  <footer>
    <h2 class="casa"> Não fique de fora</h3>
  </footer>
  
  </body>
  
</html> 
