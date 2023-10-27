# Game_memory
<br>
<br>
<h1 align="center">Entendendo o Código</h1>


<h4>Geração das imagens das cartas:</h4> A função generateImagePairs() gera um objeto contendo as imagens correspondentes para cada carta. A função usa a API do Picsum para gerar imagens aleatórias.

<h4>Embaralhamento da matriz de cartas:</h4> A função shuffleCards() embaralha a matriz de cartas.

<h4>Criação das cartas:</h4> A função createCards() cria as cartas e adiciona-as ao tabuleiro. Cada carta tem um lado da frente e um lado de trás. O lado da frente da carta mostra a imagem da carta e o lado de trás da carta mostra uma imagem padrão.

<h4>Virada das cartas:</h4> A função flipCard() é executada quando o jogador clica em uma carta. A função vira a carta e atualiza o número de cartas viradas.

<h4>Verificação de combinações:</h4> A função checkForMatch() verifica se as duas cartas viradas são iguais. Se as duas cartas forem iguais, as cartas são removidas do tabuleiro e o jogador recebe um ponto.

<h4>Atualização do número de tentativas:</h4> A função updateAttempts() atualiza o número de tentativas do jogador.

<h4>Exibição da mensagem de parabéns:</h4> A função showCongratulations() exibe uma mensagem de parabéns quando o jogador remove todas as cartas do tabuleiro.
