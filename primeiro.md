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
    <!-- Menu de navega????o-->
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
              <a class="nav-link" href="#g"> Guaran?? </a>
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
   <p> Agora, irei mostrar os benef??cios de cada uma:</p>

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

    <p> A fruta possui gorduras insaturadas que agem diminuindo a absor????o do colesterol no intestino e sua s??ntese pelo f??gado. 
      Sendo assim, auxilia no controle do colesterol LDL (colesterol ruim) e aumenta o colesterol HDL (colesterol bom), 
      al??m de reduzir os n??veis de triglicer??deos do organismo.</p>
  </a>
            <br> <br> <br> <br> <br> <br>  
    <a name="b">
      <h1>Babosa</h1>
       <br>
        <img src="babosa2.png">
            <br> <br>
        <p>A babosa ?? muito conhecida por suas propriedades calmantes, 
          cicatrizantes, anest??sicas, antit??rmicas e anti-inflamat??rias, 
          al??m de ser ??tima para hidratar o cabelo e cuidar da pele.</p>

    </a>
     
     <a name="g">
       <h1>Guaran??</h1>
        <br>
          <img src="gua2.png">
           <br> <br>
            <p>Al??m de manter alerta, fruta brasileira ?? usada no tratamento de depress??o, contra enxaqueca, para acelerar o metabolismo e at?? no combate ?? celulite. O guaran?? ou Paullinia Cupana, como ?? conhecido cientificamente, ?? o fruto do guaranazeiro, uma planta nativa da Amaz??nia.</p>
     </a>
</body>
</html>
