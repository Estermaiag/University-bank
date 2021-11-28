<head>
  <meta charset="utf-8"/> 
  <!--isso serve para aceitar palavras com caracteres especiais-->

  <title>Título incrível</title>
  
  <link rel="stylesheet" href="css/stylo.css">
<!--coloca extensao pro css-->

</head>
 <body>

  <div class="corFundo">
    Esta é uma div linha toda
  </div>
  <hr />

  <div class="corFundo class33">
    Esta é uma div que gasta 3 linha
  </div>

  <div class="corFundo class33">
    Esta é uma div que gasta 3 linha
  </div>

  <div class="corFundo class33">
    Esta é uma div que gasta 3 linha
  </div>


  
  <div id="divPrincipal" style="display: block;">
    <h1 class="fonteArial" >Isso é um título bem grande</h1>
     <h2 title="Meu primeiro H2" class="fonteArial">Isso é um <j class="corLetra">título</j> bem grande</h2>
     <img src="img/asd.png" height="100px;" width="100px;" title="Minha primeira imagem">
  </div>
  <div id="minhaDiv">Minha div esta vazia</div>

  <button onclick="colocarNomeDiv();">Altera o conteudo da div</button>

  <br />
  <hr />
  <a style="text-decoration: none; cursor: progress;" href="https://mappsistemas.com.br/" target="_blank">meu primeiro link</a>

  
  
  <script>

    function colocarNomeDiv(){
      document.getElementById('minhaDiv').innerHTML = "Que legal estou alterando o conteudo da div";
      alert('oi acabei de alterar para vc');
      document.getElementById('divPrincipal').style.display = 'block';
    }

  
  </script>

 </body>
</html>
