<<<<<<< HEAD
<h1 align="center">Trivia, D&D Theme.</h1>
<br><br>

# Descrição

Jogo de perguntas e respostas. Após fazer login, o jogo já é iniciado e o usuário terá até 30 segundos para responder cada pergunta.
Caso acerte, sua pontuação será acrescida levando-se em consideração a dificuldade da pergunta e o tempo de resposta. O jogo é encerrado
ao final de 5 perguntas. O usuário poderá então decidir se pretende jogar novamente ou visualizar o ranking. Na tela inicial há também
uma opção para que o usuário possa configurar as perguntas por tipo, categoria e nível de dificuldade.
<br><br>

# Stacks de Desenvolvimento

<div>
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

# Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com). 
Além disto é bom ter um editor para trabalhar com o código como o [VSCode](https://code.visualstudio.com/).

## Rodando o projeto localmente

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
- [x] Exibe um header que contém imagem de perfil do email do jogador, seu nome e seu placar atual.
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
<br><br>

## Desenvolvido em conjunto com:

Eric Faria - https://github.com/eric-faria
<br>
Kevin Oliveira - https://github.com/Kevin-Ol
<br>
Rodrigo Freitas - https://github.com/R-R-Freitas

## Status

<h3> 
	🚧  Projeto finalizado 🚧
</h3>

=======
#### Este projeto foi desenvolvido como parte do curso de Desenvolvimento Web Full-Stack da Trybe, no módulo Front-End, entre os dias 4 e 10 de Agosto de 2021.

#### Equipe: 
Rodrigo Rafael Freitas (https://github.com/R-R-Freitas)
Eric Faria (https://github.com/eric-faria)
Caio Veloso (https://github.com/Caio-Veloso)
Kevin Oliveira (https://github.com/Kevin-Ol)
Johann Munzlinger (https://github.com/jmlinger)

## O que foi desenvolvido

Foi desenvolvido um jogo de perguntas e respostas baseado no jogo **Trivia**.

Tecnologias e ferramentas utilizadas:
-VSCode
-JavaScript
-HTML
-CSS
-SASS
-React
-Redux
-API do Gravatar(https://br.gravatar.com/site/implement/images/)
-API do Trivia(https://opentdb.com/api_config.php)
-CryptoJS(https://github.com/brix/crypto-js)


-Foram utilizados ESLint e StyleLint para garantir a legibilidade do código. 

-Os testes foram desenvolvidos pela própria Trybe com Cypress.

### Tela de início/login

#### 1. Crie a tela de login, onde a pessoa que joga deve preencher as informações para iniciar um jogo

  **PRIORIDADE 0** - Criar a tela de login contendo as informações de nome e email, onde a pessoa que joga deve conseguir escrever seu nome e email nos inputs e o botão de jogar deve estar desabilitado caso não tenha alguma dessas informações.
  
#### 2. Crie o botão de iniciar o jogo

  **PRIORIDADE 1** - O botão "Jogar" deve fazer requisição para a API para obter o token e redirecionar a pessoa para tela de jogo

#### 3. Crie um botão que leva a pessoa para tela de configuração

  **PRIORIDADE 1** - A tela inicial deve conter um botão que leve para a configuração do jogo

### Tela de jogo

#### 4. Crie um _header_ que deve conter as informações da pessoa jogadora

  **PRIORIDADE 1** - O header deve conter as informações sobre a pessoa jogadora, como a imagem do Gravatar, o nome e o placar

#### 5. Crie a página de jogo que deve conter as informações relacionadas à pergunta

  **PRIORIDADE 1** - Deve ser feita a requisição para a API para popular o jogo com as perguntas, categoria e alternativas

#### 6. Desenvolva o jogo onde só deve ser possível escolher uma resposta correta por pergunta

  **PRIORIDADE 2** - A pergunta deve ter apenas uma alternativa correta

#### 7. Desenvolva o estilo que, ao clicar em uma resposta, a correta deve ficar verde e as incorretas, vermelhas

  **PRIORIDADE 2** - Ao responder a pergunta, se a alternativa for correta, deve ficar verde, caso contrário, vermelha

#### 8. Desenvolva um timer onde a pessoa que joga tem 30 segundos para responder

  **PRIORIDADE 3** - A página deve conter um timer que com o tempo máximo de 30 segundos para responder, caso ultrapasse o tempo, a pergunta é considerada errada

#### 9. Crie o placar com as seguintes características:

  **PRIORIDADE 3** - Ao clicar na resposta correta, pontos devem ser somados no placar da pessoa que está jogando

#### 10. Crie um botão de "próxima" que apareça após a resposta ser dada

  **PRIORIDADE 3** - Deve aparecer um botão de "Próxima" (pergunta) após a resposta ser dada

#### 11. Desenvolva o jogo de forma que a pessoa que joga deve responder 5 perguntas no total

  **PRIORIDADE 2** - O jogo deve ser composto por 5 perguntas, onde, a cada nova pergunta, o timer é reiniciado e após respondê-las, a pessoa que joga deve ser redirecionada para a tela de feedback

### Tela de feedback

#### 12. Desenvolva o header de _feedback_ que deve conter as informações da pessoa jogadora

  **PRIORIDADE 0** - A tela de feedback deve conter as informações da pessoa que joga, incluindo o placar com o valor referente ao desempenho no jogo

#### 13. Crie a mensagem de _feedback_ para ser exibida a pessoa usuária

  **PRIORIDADE 1** - A tela de feedback deve exibir uma mensagem relacionada ao desempenho da pessoa que jogou

#### 14. Exiba as informações relacionadas aos resultados obtidos para a pessoa usuária

  **PRIORIDADE 1** - A tela de feedback deve exibir informações sobre o desempenho da pessoa, como o placar final e o número de perguntas que acertou

#### 15. Crie a opção para a pessoa jogadora poder jogar novamente

  **PRIORIDADE 3** - A pessoa terá a opção "Jogar novamente", que ao ser clicada, levará para a tela de inicial

#### 16. Crie a opção para a pessoa jogadora poder visualizar a tela de _ranking_

  **PRIORIDADE 3** - Deve existir um botão que redirecione a pessoa para a tela de ranking

### Tela de ranking

#### 17. Crie a tela de _ranking_

  **PRIORIDADE 2** - A tela de ranking deve possuir uma lista com a imagem, nome e pontuação das pessoas que jogaram e deve ficar armazenado no localStorage

#### 18. Crie um botão para ir ao início

  **PRIORIDADE 3** - O botão deve redirecionar a pessoa para a tela de inicial (login)

### Extra não avaliativo: Tela de configurações

##### 19. Ao mudar o valor do dropdown categoria, apenas perguntas da categoria selecionada devem aparecer para a pessoa que está jogando. Essa configuração será identificada pela chave category no retorno da API;

##### 20. Ao mudar o valor do dropdown dificuldade, apenas perguntas da dificuldade selecionada devem aparecer para a pessoa que está jogando. Essa configuração será identificada pela chave difficulty no retorno da API;

##### 21. Ao mudar o valor do dropdown tipo, apenas perguntas do tipo selecionado devem aparecer para a pessoa que está jogando. Essa configuração será identificada pela chave type no retorno da API.
>>>>>>> ff8fce7b480a8d81c3d2059fcd3856bddd794112
