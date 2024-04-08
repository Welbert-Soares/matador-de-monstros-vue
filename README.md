<h1 align="center">Bem-vindo ao Matador de Monstros 🐲</h1>

Bem-vindo ao Matador de Monstros, um jogo de luta simples, mas emocionante, onde você, o herói, enfrenta um monstro temível. Ambos têm uma barra de vida que é exibida na tela. Quem será o último a ficar de pé?

<h2 align="center">Interface do Jogo 🎮</h2>

A tela do jogo é simples, mas cheia de ação. Você verá duas barras de vida, uma para você e outra para o monstro, e quatro botões de ação.

<h3 align="center">Barras de Vida 💚</h3>

As barras de vida são como o pulso do jogo. Elas são divs com uma largura que é uma porcentagem da vida do personagem. Se a vida do personagem for menor que 20%, a barra de vida fica vermelha - sinal de perigo!

<h3 align="center">Botões de Ação 🕹️</h3>

Existem quatro botões que você pode pressionar: "Ataque", "Ataque Especial", "Curar" e "Desistir". Esses botões só aparecem se o jogo estiver rolando. Se não, você verá um botão "Iniciar Jogo". Vamos lá, clique nele!

<h2 align="center">Resultado do Jogo 🏆</h2>

O jogo termina quando alguém fica sem vida. Se a vida do monstro for 0, você vence! 🎉 Caso contrário, bem, você sabe... 😢

<h2 align="center">Logs do Jogo 📜</h2>

Quer saber o que aconteceu durante o jogo? Confira a seção de logs. Ela exibe mensagens sobre o que aconteceu durante o jogo. Cada mensagem é um item da lista.

<h2 align="center">Lógica do Jogo 🧠</h2>

Por trás das cenas, o jogo é controlado por uma instância do Vue.js. O estado do jogo é mantido em um objeto `data` que contém várias propriedades, como se o jogo está em andamento, a vida do jogador e do monstro, e os logs do jogo.

<h2 align="center">Tecnologias Utilizadas 💻</h2>

Este código usa Vue.js, um framework JavaScript para construir interfaces de usuário. As diretivas `v-if`, `v-else`, `v-for` e `@click` são todas específicas do Vue.js e são usadas para controlar o fluxo do jogo e responder a eventos do usuário.