<p>Portiifólio</p>
- CSS ---------------------
$ red: # ea1d2c;
$ black: # 3e3e3e;
$ raio pequeno: 4px;
$ big-radius: 10px;

* {
  dimensionamento da caixa: caixa de borda;
  família da fonte: sans-serif;
  cor: $ preto;
}

uma {
  decoração de texto: nenhum;
  cor preta;
}

html {
  tamanho da fonte: 10px;
  largura máxima: 100vw;
  overflow-x: oculto;
}

html,
corpo {
  margem: 0px;
  preenchimento: 0px;
}

.a Principal {
  plano de fundo: # f5f3f4;
}

.hero-section {
  display: flex;
  justificar o conteúdo: centro;
  alinhar-itens: centro;
  acolchoamento inferior: 100px;
  
  .hero-container {
    display: flex;
    direção flexível: coluna;
    alinhar-itens: centro;
    largura máxima: 640px;
    alinhamento de texto: centro;
  }
  
  .título {
    tamanho da fonte: 6rem;
    margin-bottom: 0px;
  }
  
  .legenda {
    tamanho da fonte: 2,5 rem;
  }
  
  .search-button {
    fundo: $ red;
    cor branca;
    margem superior: 30px;
    
    .icon {
      margem direita: 20px;
    }
  }
  
  .image1-container,
  .image2-container {
    posição: absoluta;
    
    .image {
      largura: 100%;
    }
  }
  
  .image1-container {
    largura: 500px;
    transform: translateX (-600px);
  }
  
  .image2-container {
    largura: 751px;
    transformar: traduzir (720px, -180px);
  }
}


.desconts-section {
  display: flex;
  justificar o conteúdo: centro;
  
  .descont-banner {
    largura: 100%;
    fundo: $ red;
    imagem de fundo: url (https://static-images.ifood.com.br/image/upload/f_auto,q_auto:best/webapp/assets/ifood-julianapaes.png);
    repetição de fundo: sem repetição;
    posição de fundo: canto inferior direito;
    preenchimento: 50px 50px 80px;
    border-radius: $ big-radius;
  }
  
  .título {
    cor branca;
    tamanho da fonte: 5rem;
    margem: 0px;
  }
  
  .legenda {
    cor branca;
    tamanho da fonte: 2rem;
  }
  
  .register-button {
    margem superior: 30px;
    cor: $ red;
    fundo: branco;
  }
}


.container-box {
  largura máxima: 1366px;
}

.icon {
  cor: herdar;
}

.botão {
  border-radius: $ small-radius;
  preenchimento: 15px 40px;
  tamanho da fonte: 2.3rem;
  display: bloco embutido;
}
