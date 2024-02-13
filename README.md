<html><head>
  <meta charset="utf-8">
  <title>Sophia</title>
  <meta property="og:title" content="Sophia">
  <meta property="og:description" content="Sua namoradinha 😈">
  <meta property="og:image" content="images/photo_4936395364756466517_y.jpg">
  <meta property="og:type" content="website">

  <link rel="stylesheet" href="style.css">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <script src="https://cdnjs.cloudflare.com/ajax/libs/js-cookie/3.0.1/js.cookie.min.js"></script>
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans&amp;display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css?family=Inter" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css?family=Monda%3A400%2C700" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css?family=Hepta+Slab:400,700|Lato:400,700&amp;display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">
  <link rel="stylesheet" href="./global.css">
  <link rel="stylesheet" href="./index.css">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&amp;display=swap">
  <link href="https://fonts.googleapis.com/css2?family=Nerko+One&amp;display=swap" rel="stylesheet">

<style>
  .notification {
    position: fixed;
    bottom: 20px;
    left: 20px;
    background-color: #58ff8f;
    color: #333;
    padding: 8px;
    border-radius: 4px;
    font-family: Arial, sans-serif;
    display: none;
    z-index: 9999;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
    animation: fadeInOut 4s ease-in-out;
  }

  @keyframes fadeInOut {

    0%,
    100% {
      opacity: 0;
    }

    10%,
    90% {
      opacity: 1;
    }
  }
</style><style>
  @keyframes zoom {
    0% {
      transform: scale(1);
    }

    50% {
      transform: scale(1.2);
    }

    100% {
      transform: scale(1);
    }
  }

  #realtime-widget {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 20px;
    padding: 10px;
  }

  #realtime-widget h2 {
    font-size: 18px;
    color: #9a00a8;
    margin-bottom: 10px;
    text-align: center;
  }

  #contagem {
    font-size: 16px;
    color: #666;
    text-align: center;
    animation: zoom 2s ease-in-out infinite;
    /* Aplica a animação de zoom apenas na contagem */
  }

  .categorias {
    text-align: center;
    margin-top: 20px;
    font-size: 24px;
    color: #9900ff;
  }

  .categorias p {
    margin-bottom: 10px;
  }

  .categorias ul {
    list-style: none;
    padding: 0;
    margin: 0;
  }

  .categorias li {
    margin-bottom: 5px;
  }

  .categorias li a {
    text-decoration: none;
    color: #666;
    transition: color 0.2s ease;
  }

  .categorias li a:hover {
    color: #333;
  }

  #category {
    text-align: center;
    color: red;
  }

  h2#comprados {
    color: red;
    text-align: center;
  }

  h2#basico {
    color: blue;
    text-align: center;
  }

  h2#médio {
    color: green;
    text-align: center;
  }


  .mensagem-estilosa {
    position: fixed;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background-color: #FEB3C3;
    color: white;
    padding: 20px;
    border-radius: 10px;
    font-size: 24px;
    font-weight: bold;
    text-align: center;
    z-index: 9999;
  }

  .htext {

    width: 286px;
    height: 39px;
    left: 43px;
    top: 176px;

    font-family: 'Monda';
    font-style: normal;
    font-weight: 700;
    font-size: 24px;
    line-height: 31px;
    /* or 130% */

    display: flex;
    align-items: center;

    color: #161616;
  }

  .htext2 {

    width: 331px;
    height: 48px;
    left: 26px;
    top: 225px;

    font-family: 'Inter';
    font-style: normal;
    font-weight: 400;
    font-size: 21px;
    line-height: 24px;
    /* or 150% */

    display: flex;
    align-items: center;

    color: #161616;
  }
</style></head>




<body>
  <!-- HTML-->

  <div class="models">
    <div class="pack-item"> <!--Modelo para o javascript adicionar os packs -->
      <a href="">
        <div class="pack-item--img"><img src=""></div>
        <div class="pack-item--add">+</div>
      </a>
      <div class="pack-item--price">R$ --</div>
      <div class="pack-item--name">--</div>
      <div class="pack-item--desc">--</div>
    </div>
    <div class="cart--item">
      <img src="">
      <div class="cart--item-nome">--</div>
      <div class="cart--item--qtarea">
        <button class="cart--item-qtmenos">-</button>
        <div class="cart--item--qt">1</div>
        <button class="cart--item-qtmais">+</button>
      </div>
    </div>

  </div>

  <header>
    <header class="top-bar">
      <div class="whatsapp">
        <a href="https://wa.me/555198166619?text=oii+nenem" target="_blank">
          <img src="https://static.vecteezy.com/system/resources/previews/018/930/748/original/whatsapp-logo-whatsapp-icon-whatsapp-transparent-free-png.png" alt="WhatsApp">
        </a>
        <h1 class="titulo-top">Sophia Conteudos</h1>
      </div>
      <!-- <div class="menu-openner"><span>0</span></div> -->
    </header>
  </header>
  <main>
    
    
         
      
    <p class="texto">MEUS PACKS:</p>
    <div class="notification"></div>
    <br>
    <br>
    <div class="pack-area"><div class="pack-item" data-key="0"> <!--Modelo para o javascript adicionar os packs -->
      <a href="">
        <div class="pack-item--img"><img src="images/photo_5075788751686446277_y.jpg"></div>
        <div class="pack-item--add">+</div>
      </a>
      <div class="pack-item--price">R$ 19.00</div>
      <div class="pack-item--name">Pacote Basico</div>
      <div class="pack-item--desc">10 videos e 15 fotos me exibindo e me masturbando</div>
    </div><div class="pack-item" data-key="1"> <!--Modelo para o javascript adicionar os packs -->
      <a href="">
        <div class="pack-item--img"><img src="images/photo1691265289.jpeg"></div>
        <div class="pack-item--add">+</div>
      </a>
      <div class="pack-item--price">R$ 39.00</div>
      <div class="pack-item--name">Pacote Plus</div>
      <div class="pack-item--desc">20 videos e 30 fotos pagando boquete e transando</div>
    </div><div class="pack-item" data-key="2"> <!--Modelo para o javascript adicionar os packs -->
      <a href="">
        <div class="pack-item--img"><img src="images/photo1691400596.jpeg"></div>
        <div class="pack-item--add">+</div>
      </a>
      <div class="pack-item--price">R$ 59.00</div>
      <div class="pack-item--name">Pacote Premium</div>
      <div class="pack-item--desc">Todos os meus conteudos + Acesso ao meu grupo VIP</div>
    </div><div class="pack-item" data-key="3"> <!--Modelo para o javascript adicionar os packs -->
      <a href="">
        <div class="pack-item--img"><img src="images/photo1691400492.jpeg"></div>
        <div class="pack-item--add">+</div>
      </a>
      <div class="pack-item--price">R$ 100.00</div>
      <div class="pack-item--name">Chamada de Video</div>
      <div class="pack-item--desc">Uma chamada de video de 20 minutos, na chamada eu serei totalmente submissa a você, e fazer o que você mandar!</div>
    </div><div class="pack-item" data-key="4"> <!--Modelo para o javascript adicionar os packs -->
      <a href="">
        <div class="pack-item--img"><img src="images/photo1691400456.jpeg"></div>
        <div class="pack-item--add">+</div>
      </a>
      <div class="pack-item--price">R$ 119.00</div>
      <div class="pack-item--name">Webnamoro 1 mês</div>
      <div class="pack-item--desc">Venha webnamorar comigo durante um mês, você tera todos os meus conteudos, tera a minha atenção 24h, mensagens safadas, fotinhas quando quiser e chamadas quando quiser &lt;3</div>
    </div><div class="pack-item" data-key="5"> <!--Modelo para o javascript adicionar os packs -->
      <a href="">
        <div class="pack-item--img"><img src="images/sub.jpeg"></div>
        <div class="pack-item--add">+</div>
      </a>
      <div class="pack-item--price">R$ 89.00</div>
      <div class="pack-item--name">Submissa</div>
      <div class="pack-item--desc">5 videos de 10 minutos de mim sendo comido com força, amarrada e sendo totalmente submissa 🔥</div>
    </div><div class="pack-item" data-key="6"> <!--Modelo para o javascript adicionar os packs -->
      <a href="">
        <div class="pack-item--img"><img src="images/estud.jpeg"></div>
        <div class="pack-item--add">+</div>
      </a>
      <div class="pack-item--price">R$ 89.00</div>
      <div class="pack-item--name">Estudante safada</div>
      <div class="pack-item--desc">5 videos de 10 minutos de mim transando em uma sala de aula usando cosplay de estudante</div>
    </div><div class="pack-item" data-key="7"> <!--Modelo para o javascript adicionar os packs -->
      <a href="">
        <div class="pack-item--img"><img src="images/emp.jpeg"></div>
        <div class="pack-item--add">+</div>
      </a>
      <div class="pack-item--price">R$ 47.00</div>
      <div class="pack-item--name">Empregada</div>
      <div class="pack-item--desc">6 videos e 12 fotos de mim vestida de empregada, transando e levando tapa na bundinha, venha me ver sendo sua empregadinha sexy 🔥</div>
    </div><div class="pack-item" data-key="8"> <!--Modelo para o javascript adicionar os packs -->
      <a href="">
        <div class="pack-item--img"><img src="images/corno.jpg"></div>
        <div class="pack-item--add">+</div>
      </a>
      <div class="pack-item--price">R$ 47.00</div>
      <div class="pack-item--name">Pack Corninho</div>
      <div class="pack-item--desc">Vem ver videozinhos de mim traindo meu ex namorado com um negão rsrs, humilhando o corno enquanto ele bate punheta rsrs</div>
    </div><div class="pack-item" data-key="9"> <!--Modelo para o javascript adicionar os packs -->
      <a href="">
        <div class="pack-item--img"><img src="images/coel.jpg"></div>
        <div class="pack-item--add">+</div>
      </a>
      <div class="pack-item--price">R$ 47.00</div>
      <div class="pack-item--name">Pack Coelhinha</div>
      <div class="pack-item--desc">7 videos e 10 fotos de mim peladinha vestida de coelhinha sexy, me masturbando e me exibindo gostosinho</div>
    </div><div class="pack-item" data-key="10"> <!--Modelo para o javascript adicionar os packs -->
      <a href="">
        <div class="pack-item--img"><img src="images/sexting.jpg"></div>
        <div class="pack-item--add">+</div>
      </a>
      <div class="pack-item--price">R$ 35.00</div>
      <div class="pack-item--name">Sexting</div>
      <div class="pack-item--desc">Vou ser sua putinha durante 20 minutos! vou fazer oq vc mandar bb 🔥</div>
    </div></div>
  </main>

  <aside><!--Carrinho-->
    
    <div class="cart--area">
      <div class="menu-closer">❌</div>
      <h1>Seus Pacotes</h1>
      <div class="cart"></div>
      <div class="cart--details">
        <div class="cart--totalitem subtotal">
          <span>Subtotal</span>
          <span>R$ --</span>
        </div>
        <div class="cart--totalitem desconto">
          <span>Desconto (-5%)</span>
          <span>R$ --</span>
        </div>
        <div class="cart--totalitem total big">
          <span>Total</span>
          <span>R$ --</span>
        </div>
        <div class="cart--totalitem total big">
        </div>
        <div class="cart--finalizar">Finalizar Compra</div>
      </div>
      <div class="card">


      </div>

      
    </div>
    
  </aside>
  <div class="packWindowArea"><!--Modal-->
    <div class="packWindowBody">


      <button class="packInfo--cancelMobileButton">
        <p class="paragraph"> Cancelar </p>
        <span class="icon-wrapper">
          <svg class="icon" width="30px" height="30px" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M6 7V18C6 19.1046 6.89543 20 8 20H16C17.1046 20 18 19.1046 18 18V7M6 7H5M6 7H8M18 7H19M18 7H16M10 11V16M14 11V16M8 7V5C8 3.89543 8.89543 3 10 3H14C15.1046 3 16 3.89543 16 5V7M8 7H16" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
          </svg>
        </span>
      </button>

      <div class="packBig"><!--img do conteudo-->
        <img src="">
      </div>
      <div class="packInfo"><!--nome do conteudo-->
        <h1>--</h1>
        <div class="packInfo--desc">--</div>
        <div class="packInfo--sizearea">
          <div class="packInfo--sector">Escolha um brinde</div>
          <div class="packInfo--sizes">
            <div data-key="0" class="packInfo--size">Sem brinde <span>--</span></div>
            <div data-key="1" class="packInfo--size"> Audio personalizado<span>--</span></div>
            <div data-key="2" class="packInfo--size selected">Analise de pau <span>--</span></div>
          </div>
        </div>
        <div class="packInfo--pricearea">
          <div class="packInfo--sector">Preço</div>
          <div class="packInfo--price">
            <div class="packInfo--actualPrice">R$ --</div> <!--preço do conteudo-->
            <div class="packInfo--qtarea">
              <button class="packInfo--qtmenos">-</button>
              <div class="packInfo--qt">1</div>
              <button class="packInfo--qtmais">+</button>
            </div>
          </div>
        </div>

        <button class="custom-button">
          <div class="svg-wrapper-1">
            <div class="svg-wrapper">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24">
                <path fill="none" d="M0 0h24v24H0z"></path>
                <!-- Ícone de carrinho -->
                <path fill="currentColor" d="M16.293 7.293l-3-3a1 1 0 0 0-1.414 1.414L13.586 8H5a3 3 0 0 0-3 3v7a3 3 0 0 0 3 3h14a3 3 0 0 0 3-3v-7a3 3 0 0 0-3-3h-1.586l1.293-1.293a1 1 0 1 0-1.414-1.414zM7 11a1 1 0 1 1 0-2 1 1 0 0 1 0 2zm10 0a1 1 0 1 1 0-2 1 1 0 0 1 0 2zm1 4a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-7a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v7z">
                </path>
              </svg>
            </div>
          </div>
          <span>Adicionar ao carrinho</span>
        </button>


        <div class="packInfo--cancelButton">Cancelar</div>
      </div>
    </div>
  </div>


  <script type="text/javascript" src="bs/packs.js"></script>
  <script type="text/javascript" src="bs/script.js"></script>
  <script type="text/javascript" src="bs/pag.js"></script>
  <script type="text/javascript" src="bs/historico.js"></script>


<menu-analytics></menu-analytics></body></html>
