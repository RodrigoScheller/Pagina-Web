# Pagina-Web -> HTML

LINK DO SITE ->  http://ajaxjquery.epizy.com/


<!DOCTYPE html>
    <html>

        <head>
        <!-- CSS only -->
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous">

        <!-- JavaScript Bundle with Popper -->
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-OERcA2EqjJCMA+/3y+gxIOqMEjwtxJY7qPCqsdltbNJuaOe923+mo//f6V8Qbsw3" crossorigin="anonymous"></script>

        <script src="https://code.jquery.com/jquery-3.6.1.js" integrity="sha256-3zlB5s2uwoUzrXK3BT7AX3FyvojsraNFxCc2vC/7pNI=" crossorigin="anonymous"></script>


            <link href="style.css" rel="stylesheet">
            <link href="grid.css" rel="stylesheet">
            <link href="http://fonts.googleapis.com/css?family=Open+Sans" rel="stylesheet">
        </head>
 

            <body>
                <div class="mycontainer">

                    <div id="header">	 
                        <img src="logo.png" class="logo">
                        <h1 class="titulo">Rodrigo Gustavo Scheller</h1>
                        <a href="https://www.linkedin.com/in/rodrigo-scheller-5068b8209/" class="linkedin" target="_blank">Linkedin</a>
                        <a href="https://github.com/RodrigoScheller" class="git">GitHub</a>
                    </div>


                        <div id="div2">

                                <h2>IDADE:</h2>
                                <h3>19 anos.</h3>
                                    <h2>CIDADE:</h2>
                                    <h3>Jaragua do Sul.</h3>
                                        <h2>FORMACAO:</h2>
                                        <h3>Instituto Educacional Jangada</h3>
                                        <h3>Centro Universitario Catolica</h3>
                                        <p class="adm">Administracao.</p>
                                        <h3>Senac Jaragua do Sul</h3>
                                        <p>Programacao de WEB e de sistemas.</p>
                                            <h2>COMPETENCIAS:</h2>
                                                <ul>
                                                    <li>Aprendo rapido</li>
                                                    <li>Dedicado</li>
                                                    <li>Ingles intermediario</li>
                                                    <li>experiencia em lidar com grupo</li>
                                                    <li>conhecimento basico em programacao:</li>
                                                    <li>HTML</li>
                                                    <li>CSS</li>
                                                    <li>JavaScript</li>
                                                </ul>
                                                    <h2>PORQUE ESCOLHI A AREA DE TECNOLOGIA:</h2>
                                                        <h3>Sempre tive interesse nessa area, sou curioso e gosto de ler sobre esse assunto, e o interresse foi crescendo cada vez mais.</h3>
                                                       
                                                        <br/>
                                                        <br/>
                                                        <h2 class="portifolio">Meu Portifolio:</h2>

                                                            <h3 class="mycontainer2">
                                                                <div class="links">
                                                                    <a href="/wareframe/wireframe.pdf" target="_blank">Wireframe</a> 
                                                                        <br/>
                                                                        <br/>
                                                                    <a href="/wareframe/prototipo.pdf" target="_blank">Prototipo</a>
                                                                        <br/> 
                                                                        <br/>
                                                                    <a href="wareframe/mockupcelular.pdf" target="_blank">Mockup Celular</a>	
                                                                        <br/> 
                                                                        <br/>
                                                                    <a href="wareframe/mockup.pdf" target="_blank">Mockup Desktop</a>	
                                                                        <br/> 
                                                                        <br/>
                                                                    <a href="calculadora/calculadora.html" target="_blank">Calculadora NASA</a>
                                                                        <br/> 
                                                                        <br/>
                                                                    <a href="php/documento.php" target="_blank">Documento</a>
                                                                        <br/> 
                                                                        <br/>
                                                                    <a href="php/laco_de_repeticao.php" target="_blank">Laco de repeticao</a>
                                                                        <br/> 
                                                                        <br/>
                                                                    <a href="php/semaforo.php" target="_blank">Semaforo</a>
                                                                        <br/> 
                                                                        <br/>
                                                                    <a href="php/sorteio.php" target="_blank">Sorteio</a>
                                                                        <br/>
                                                                        <br/>
                                                                    <a href="logica/programa_troca_pneu.txt" target="_blank">Logica Programacao</a>
                                                                        <br/> 
                                                                        <br/>
                                                                    <a href="bd/der" target="_blank">DER Tinder Pet</a>
                                                                        <br/> 
                                                                        <br/>
                                                                    <a href="bd/modelo_conceitual_brm.pdf" target="_blank">Modelo Conceitual Tinder Pet</a>
                                                                        <br/> 
                                                                        <br/>
                                                                    <a href="bd/modelo_conceitual_brm.pdf" target="_blank">Jogo Mario</a>
                                                                </div>
                                                            </h3>

                            <br/><!-- Quebra de Linha -->
                                <button class="btn btn-info" id="btn1">Informação</button>
                                <button class="btn btn-warning" id="btn2">Aviso</button>
                                <button class="btn btn-danger" id="btn3">Perigo</button>

                        </div>
                </div>
                        <script>
                            document.getElementById("btn1").onmouseover=function()	{alert("Sou um Botao 1")};
                        

                            $(".btn-warning").click(function(){alert("Sou um Botao 2");});

                            $("#btn3").hover(function(){
                            alert("Sou um Botao 3");
                            });
                        </script>
            </body>

    </html>
    
    
    # Pagina-Web -> CSS
    
    
    
body{
  background-image: url("img.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-size: cover;
}

html {
  font-size: 15px;
  font-family: "Open Sans", sans-serif;
  color: #fff
}

.mycontainer{
  background-color: #000;
  margin: 1em 2em;
  border: 5px double #5b0a07;
  padding: 5px;
}

#header {
 background-color: #141313;
 color: white;
 max-width: 1440px;
 height: 170px;
}
     
h1{
  font-family: "diplomataSC";
  margin-top: -80px;
  margin-left: 28%;
 
}

h1:hover{
  border-bottom: red double;
}

.linkedin {
 position: absolute;
 margin-top: -50px;
 margin-left: 900px;
 margin-bottom: 400px;
 text-decoration: none;
 font-size: 25px;
 color: white;
}

.git {
  position: absolute;
  margin-top: -9px;
  margin-left: 1070px;
  margin-bottom: 400px;
  text-decoration: none;
  font-size: 25px;
  color: white;
}


h2 {
  font-size: 25px;
  border-left: 3px solid red ;
  padding-left: 5px;
}
   
h2,h3, li {
   
  letter-SPACING: 1px;
}

h3{
  font-size: 16px;
  padding-bottom: 5px;
  font-weight: 600;
}

p {
  text-align: left;
  margin-left: 0px;
}

#div2 {
  background-color: #fff;
  color: #000;
  padding: 15px;
}
   
li {
  font-size: 16px;
  font-weight: 600;
}
   
   /*@media screen and (min-width: 800px) {
   .container{
   background-color: #fff;
   border:8px dashed #5b0a07;
   padding: 10px 5px;
   }*/
   
   
   
h2,h3 {
  text-align:left;
}
   

.logo {
  margin-left: 20px;  
  width: 160px; 
}

    

a {
  color: #FF3C3C;
  font-family: "diplomataSC";
}

.portifolio {
 margin-left: 42%;
}

.mycontainer2{
  background-color: #EDE2E2;
  margin: 1em 2em;
  border: 5px double #5b0a07;
  padding: 5px;
    
}

.links {
  text-align: center;
  font-size: 18px;

}

    
