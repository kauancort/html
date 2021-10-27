<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

  <!-- meu CSS -->
  <style type="text/css">
    body{
        background-color: whitesmoke;
        
    }
    
   h1{ text-align: center;}  

    p{ text-align: justify;
       size: 80px;
       }

    .carousel-inner img {width: 45%; 
                        height: 45%;
    
    }

    .i {  width: 200px;
      height: 200px; 
	   padding: 2px;   
	   margin: 2px; 
	   
	   
	  }
  </style>

</head>

<body>

  <div class="container-fluid">
     
     <!--Carrosel-->

    <div class="row fundo">

      <div class="col">
       
        <div id="demo" class="carousel slide" data-ride="carousel">

          <!-- Quantidade de slide do Carrosel-->
          <ul class="carousel-indicators">
           <li data-target="#demo" data-slide-to="0" class="active"> </li>
           <li data-target="#demo" data-slide-to="1"> </li>
           <li data-target="#demo" data-slide-to="2"> </li>
      

          </ul>

          <!--slide show-->
          <div class="carousel-item active">
            <img src="aba1.png" alt="Abacate">
          </div>
            
          <div class="carousel-item">
            <img src="gua1.png" alt="Guarana">
          </div>
 
          <div class="carousel-item">
            <img src="bab1.png" alt="Babosa">
          </div>

          <a class="carousel-control-prev" href="#demo" data-slide="prev">
            <span class="carousel-control-next-icon"> </span>
          </a> 
 
        </div>
    
    
      </div>

    </div>


    <!--Barra de-->
    <!-- Menu de navegação-->
    <div class="row fundo">

      <div class="col">

        <ul class="nav nav-pills bg-dark">
           <!--<ul class="nav justify-content-center"-->
          
            <li class="nav-item">
              <a class="nav-link active" href="#"> Home </a>
            </li>
                    
           <li class="nav-item">
             <a class="nav-link" href="#aba"> Abacate </a>
           </li>
                     
            <li class="nav-item">
              <a class="nav-link" href="#b"> Babosa </a>
            </li>
                    
            <li class="nav-item">
              <a class="nav-link" href="#g"> Guaraná </a>
            </li>

        </ul>
        
      </div>
     </div>
    <!-- abrindo a primeira linha do leiaute -->
    <div class="col">
        <!-- 4 colunas/largura 3 col-3 -->
        <br>
   <h1> Tarefa de Design no html envolvendo plantas medicinais</h1> 
<br>
<br>
   <div class="col">
   <p> Agora, irei mostrar os benefícios de cada uma:</p>

  </div>
  </div>
  <a name="aba">
   <h1>Abacate</h1>
   
    <div class="i">
      <center>
        <img src="ca.png" alt="abacate">
      </center>
    </div>
           <br> <br> <br> <br> <br> <br> <br> <br> <br> 

    <p> A fruta possui gorduras insaturadas que agem diminuindo a absorção do colesterol no intestino e sua síntese pelo fígado. 
      Sendo assim, auxilia no controle do colesterol LDL (colesterol ruim) e aumenta o colesterol HDL (colesterol bom), 
      além de reduzir os níveis de triglicerídeos do organismo.</p>
  </a>
            <br> <br> <br> <br> <br> <br>  
    <a name="b">
      <h1>Babosa</h1>
       <br>
        <img src="babosa2.png">
            <br> <br>
        <p>A babosa é muito conhecida por suas propriedades calmantes, 
          cicatrizantes, anestésicas, antitérmicas e anti-inflamatórias, 
          além de ser ótima para hidratar o cabelo e cuidar da pele.</p>

    </a>
     
     <a name="g">
       <h1>Guaraná</h1>
        <br>
          <img src="gua2.png">
           <br> <br>
            <p>Além de manter alerta, fruta brasileira é usada no tratamento de depressão, contra enxaqueca, para acelerar o metabolismo e até no combate à celulite. O guaraná ou Paullinia Cupana, como é conhecido cientificamente, é o fruto do guaranazeiro, uma planta nativa da Amazônia.</p>
     </a>
</body>
</html>
