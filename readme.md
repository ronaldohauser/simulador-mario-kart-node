# Minha versão de projeto do Felipão: Mario Kart.JS
(https://github.com/digitalinnovationone/formacao-nodejs/tree/main/03-projeto-mario-kart)

<table>
    <tr>
        <td>
            <img src="./docs/header.gif" alt="Mario Kart" width="200">
        </td>
        <td>
            <b>Objetivo:</b>
            <p>Mario Kart é uma série de jogos de corrida desenvolvida e publicada pela Nintendo. Nosso desafio será criar a lógica de um jogo para simular corridas de Mario Kart, levando em consideração as regras e mecânicas descritas abaixo.</p>
        </td>
    </tr>
</table>

## Players

<table style="border-collapse: collapse; width: 800px; margin: 0 auto;">
    <tr>
        <td style="border: 1px solid black; text-align: center;">
            <p>Mario</p>
            <img src="./docs/mario.gif" alt="Mario Kart" width="60" height="60">
        </td>
        <td style="border: 1px solid black; text-align: center;">
            <p>Velocidade: 4</p>
            <p>Manobrabilidade: 3</p>
            <p>Poder: 3</p>
        </td>
        <td style="border: 1px solid black; text-align: center;">
            <p>Peach</p>
            <img src="./docs/peach.gif" alt="Mario Kart" width="60" height="60">
        </td>
        <td style="border: 1px solid black; text-align: center;">
            <p>Velocidade: 3</p>
            <p>Manobrabilidade: 4</p>
            <p>Poder: 2</p>
        </td>
        <td style="border: 1px solid black; text-align: center;">
            <p>Yoshi</p>
            <img src="./docs/yoshi.gif" alt="Mario Kart" width="60" height="60">
        </td>
        <td style="border: 1px solid black; text-align: center;">
            <p>Velocidade: 2</p>
            <p>Manobrabilidade: 4</p>
            <p>Poder: 3</p>
        </td>
    </tr>
    <tr>
        <td style="border: 1px solid black; text-align: center;">
            <p>Bowser</p>
            <img src="./docs/bowser.gif" alt="Mario Kart" width="60" height="60">
        </td>
        <td style="border: 1px solid black; text-align: center;">
            <p>Velocidade: 5</p>
            <p>Manobrabilidade: 2</p>
            <p>Poder: 5</p>
        </td>
        <td style="border: 1px solid black; text-align: center;">
            <p>Luigi</p>
            <img src="./docs/luigi.gif" alt="Mario Kart" width="60" height="60">
        </td>
        <td style="border: 1px solid black; text-align: center;">
            <p>Velocidade: 3</p>
            <p>Manobrabilidade: 4</p>
            <p>Poder: 4</p>
        </td>
        <td style="border: 1px solid black; text-align: center;">
            <p>Donkey Kong</p>
            <img src="./docs/dk.gif" alt="Mario Kart" width="60" height="60">
        </td>
        <td style="border: 1px solid black; text-align: center;">
            <p>Velocidade: 2</p>
            <p>Manobrabilidade: 2</p>
            <p>Poder: 5</p>
        </td>
    </tr>
</table>

## 🕹️ Regras & mecânicas:

### Jogadores:
- [ ] O Computador deve receber dois personagens para disputar a corrida em um objeto cada

### Pistas:
- [ ] 2 dos 6 personagens serão aleatoriamente escolhidos (novo!)
- [ ] Os personagens escolhidos irão correr em uma pista aleatória de 5 rodadas
- [ ] A cada rodada, será sorteado um bloco da pista que pode ser uma reta, curva ou confronto
- [ ] A cada rodada, será mostrado o saldo de pontos de cada personagem (novo!)

#### Detalhes da Pista:
  - [ ] Caso o bloco da pista seja uma RETA, o jogador deve jogar um dado de 6 lados e somar o atributo VELOCIDADE; quem vencer, ganha um ponto
  - [ ] Caso o bloco da pista seja uma CURVA, o jogador deve jogar um dado de 6 lados e somar o atributo MANOBRABILIDADE; quem vencer, ganha um ponto
  - [ ] Caso o bloco da pista seja um CONFRONTO, o jogador deve jogar um dado de 6 lados e somar o atributo PODER; quem perder, perde um ponto
  - [ ] Nenhum jogador pode ter pontuação negativa (valores abaixo de 0)

### Condição de vitória:
- [ ] Ao final, vence quem acumulou mais pontos
