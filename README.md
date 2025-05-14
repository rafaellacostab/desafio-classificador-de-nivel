# Desafio Classificador de Nível de Herói

Este projeto classifica o nível de um herói baseado na quantidade de experiência (XP) adquirida durante suas aventuras. O objetivo é determinar o nível do herói em uma escala de acordo com a quantidade de XP, que pode variar entre os seguintes níveis:

- Ferro
- Bronze
- Prata
- Ouro
- Platina
- Ascendente
- Imortal
- Radiante

## Funcionalidades

- O código utiliza uma estrutura de decisão para avaliar a experiência do herói e atribuir o nível correspondente.
- O nome do herói e a experiência (XP) são fornecidos como entrada, e o nível é calculado e exibido na saída.

## Como usar

1. Abra o arquivo `classificadorNivel.js`.
2. Defina o nome e a quantidade de XP do herói nas variáveis `nome` e `xp`.
3. Execute o código e a mensagem com o nível do herói será exibida no console.

### Exemplos de Saída:

- Se o XP for menor que 1.000, o nível será "Ferro".
- Se o XP estiver entre 1.001 e 2.000, o nível será "Bronze".
- E assim por diante, até o nível "Radiante" para XP acima de 10.001.

## Tecnologias

- JavaScript
- Lógica de programação com estruturas condicionais
