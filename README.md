<!DOCTYPE html>
<HTML língua="pt-br">
<cabeça>
  <meta conjunto de caracteres="UTF-8">
  <título>Minha Página Simples</título>
  <estilo>
    corpo{
      cor de fundo: #f0f8ff;
      família de fontes:Arial,sem serifa;
    }

    h1{
      cor: #2e8b57;
      alinhamento de texto:centro;
    }

    p{
      tamanho da fonte: 18px;
      alinhamento de texto:justificar;
    }

    ul{
      altura da linha: 2;
    }

    imagem{
      raio da borda: 10px;
      largura: 300px;
      altura:auto;
    }

    mesa{
      margem superior: 20px;
      colapso da fronteira:colapso;
      largura: 100%;
      cor de fundo: #fff;
      caixa-sombra: 0 0 8px RGBA(0, 0, 0, 0,1);
    }

    º{
      cor de fundo: #d3e0ea;
      cor: #333;
    }

    mesa, º, td{
      fronteira: 1pxsólido#999;
      preenchimento: 10px;
      alinhamento de texto:centro;
    }

    um{
      cor: #2e8b57;
      decoração de texto:nenhum;
      transição:cor0,3s;
    }

    um:pairar{
      cor: #ff4500;
    }

    #mensagem{
      margem superior: 15px;
      espessura da fonte:audacioso;
      cor: #2e8b57;
    }
  </estilo>
</cabeça>
<corpo>
  <h1>Luciano</h1>

  <p>Olá! Meu nome é Luciano, tenho 33 anos, moro em Toledo - PR e sou apaixonado por tecnologia, jogos e viagens pelo mundo.</p>

  <!-- Botão e espaço para a mensagem -->
  <botão ao clicar="mostrarMensagem()">Clique para ver uma mensagem!</botão>
  <divisão eu ia="mensagem"></divisão>

  <ul>
    <li>Jogar videogame</li>
    <li>Programar</li>
    <li>Viajar</li>
  </ul>

  <imagem fonte="xbox-playstation.jpg"alt="jogar">

  <h2>Países que gostaria de visitar</h2>
  <mesa>
    <tr>
      <º>País</º>
      <º>Imagem</º>
    </tr>
    <tr>
      <td>Japão</td>
      <td><imagem fonte="japão.jpg"largura="200"estilo="raio da borda: 10px;"></td>
    </tr>
    <tr>
      <td>Noruega</td>
      <td><imagem fonte="Noruega.jpg"largura="200"estilo="raio da borda: 10px;"></td>
    </tr>
    <tr>
      <td>Nova York</td>
      <td><imagem fonte="nova york.jpg"largura="200"estilo="raio da borda: 10px;"></td>
    </tr>
  </mesa>

  <p>Confira um dos meus sites favoritos:<um href="https://www.tecmundo.com.br"alvo="_em branco">TecMundo</um></p>

  <roteiro>
    função mostrarMensagem() {
      constante mensagens = [
        "Você é capaz de conquistar grandes coisas!",
        "Nunca desista dos seus sonhos.",
        "Continue aprendendo e evoluindo todos os dias.",
        "O segredo do sucesso está na persistência.",
        "Grandes jornadas iniciadas com um simples passo!"
      ];
      constante aleatoria = mensagens[Matemática.chão(Matemática.aleatório() * mensagens.comprimento)];
      documento.obterElementoPorId("mensagem").texto interno = aleatoria;
    }
  </roteiro>
</corpo>
</HTML>
