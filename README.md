<h1 align="center">Trivia, D&D Visual Theme.</h1>

<br>

![](./src/images/trivia.gif)

<br>

# Descrição

Jogo de perguntas e respostas na temática visual do D&D.
<br><br>
Após fazer login, o jogo já é iniciado e o usuário terá até 30 segundos para responder cada pergunta. Caso acerte, sua pontuação será acrescida levando-se em consideração a dificuldade da pergunta e o tempo de resposta. O jogo é encerrado
ao final de 5 perguntas. O usuário poderá então decidir se pretende jogar novamente ou visualizar o ranking. Na tela inicial há também
uma opção para que o usuário possa configurar as perguntas por tipo, categoria e nível de dificuldade.
<br><br>
Projeto desenvolvido como forma de critério avaliativo da escola de tecnologia Trybe.

<br>

# Stacks de Desenvolvimento

<div>
  <a href="https://javascript.info/">
    <img src="https://img.shields.io/badge/javascript-339933?style=for-the-badge&logo=javascript&color=black" />
  </a>
  <a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML">
    <img src="https://img.shields.io/badge/html5-339933?style=for-the-badge&logo=html5&color=black" />
  </a>
  <a href="https://www.w3schools.com/cssref/">
    <img src="https://img.shields.io/badge/css-339933?style=for-the-badge&logo=css3&color=black" />
  </a>
  <a href="https://pt-br.reactjs.org/docs/getting-started.html">
    <img src="https://img.shields.io/badge/React.js-339933?style=for-the-badge&logo=react&color=black" />
  </a>
  <a href="https://redux.js.org/usage/index">
    <img src="https://img.shields.io/badge/Redux-339933?style=for-the-badge&logo=redux&color=black" />
  </a>
  <a href="https://sass-lang.com/documentation">
    <img src="https://img.shields.io/badge/sass-339933?style=for-the-badge&logo=sass&color=black" />
  </a>
</div>

<br>

# A aplicação em nuvem

Acesse a aplicação rodando em nuvem por <a href="https://jmlinger.github.io/trybe-project-trivia/"> aqui <a/>.

<br>

# Rodando a aplicação localmente

## Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com). Além disto é bom ter um editor para trabalhar com o código como o [VSCode](https://code.visualstudio.com/).
A seguir encontran-se os passos para rodar a aplicação localmente.

```bash
# Clone este repositório com a chave SSH ou HTTP a depender de como seu git está configurado.
$ git clone git@github.com:jmlinger/trybe-project-trivia.git

# Acesse a pasta do projeto no terminal/cmd
$ cd trybe-project-trivia

# Instale as dependências
$ npm install

# Execute a aplicação
$ npm start

```

## Funcionalidades da aplicação

## V 1.1

### Tela de login
- [x] Exibe campos para inserir nome e email do jogador.
- [x] Exibe botão que inicia o jogo. Este é somente habilitado quando os campos forem preechindos corretamente.
- [x] Botão que leva à tela de configurações.
### Tela de jogo
- [x] Exibe um header que contém imagem de perfil do email do jogador, seu nome e seu placar atual.
- [x] Exibe uma pergunta de cada vez. Cada pergunta contém apenas uma alternativa correta.
- [x] Exibe um timer de 30 segundos por pergunta. Quando o tempo se esgota é exibida a alternativa correta e a resposta é contabilizada como errada.
- [x] Quando uma alternativa é escolhida ou quando o tempo é esgotado, é alterado o estilo das alternativas de forma a diferencar a correta das incorretas. 
- [x] Acresce o placar do jogador caso a alternativa correta tenha sido selecionada. A pontuação depende do tempo de resposta e do nível de
dificuldade da pergunta.
- [x] Exibe botão para ir pra próxima pergunta quando uma alternativa é escolhida ou quando o tempo é esgotado.
- [x] Exibe um total de 5 perguntas. Ao final da última pergunta, quando o usuário clica no botão para ir pra próxima pergunta, é redirecionado à tela de feedback.
### Tela de feedback
- [x] Exibe um header que contém imagem de perfil do jogador no Gravatar, seu nome e seu placar atual.
- [x] Exibe mensagem personalizada de acordo com a quantidade de acertos.
- [x] Exibe a quantidade de acertos e pontuação final do jogador.
- [x] Contém botão para ir à tela de ranking.
- [x] Contém botão para jogar novamente, que redireciona o usuário para a tela de login.
### Tela de ranking
- [x] Exibe um ranqueamento de jogadores em ordem descrescente de pontuação.
- [x] Contém botão para jogar novamente, que redireciona o usuário para a tela de login.
### Tela de configurações
- [x] Permite a pessoa usuária modificar a categoria das perguntas que serão exibidas em jogo, seu nível de dificuldade e seu tipo.
- [x] Exibe botão que salva as modificações e redireciona para a tela de login.

<br>

## Desenvolvido em conjunto com:

Eric Faria - https://github.com/eric-faria
<br>
Kevin Oliveira - https://github.com/Kevin-Ol
<br>
Rodrigo Freitas - https://github.com/R-R-Freitas

<br>

## Status

<h3> 
	🚧  Projeto finalizado 🚧
</h3>
