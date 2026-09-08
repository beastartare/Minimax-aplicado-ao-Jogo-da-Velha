# Minimax-aplicado-ao-Jogo-da-Velha

## Introdução
o seguinte projeto tem como objetivo a implementação do algoritmo Minimax aplicado ao Jogo da Velha

## Como funciona o algoritmo Minimax
O Minimax é um algoritmo utilizado para tomar decisões em jogos entre dois jogadores. Ele funciona analisando as possíveis jogadas e seus respectivos resultados futuros, considerando que os dois jogadores sempre tentarão fazer a melhor escolha possível.

Para isso, o algoritmo representa cada situação do jogo como um estado e simula as jogadas seguintes, formando uma espécie de árvore de possibilidades. Em cada nível dessa árvore, um dos jogadores escolhe sua jogada.

No jogo da velha, por exemplo, podemos considerar X como MAX e O como MIN. O jogador MAX procura obter o maior valor possível, enquanto o jogador MIN procura obter o menor valor. Os resultados podem ser representados por 1 para uma vitória de X, 0 para um empate e -1 para uma vitória de O.

O algoritmo continua analisando as possibilidades até chegar a um estado em que o jogo terminou. A partir desses resultados, os valores são retornados pela árvore: MAX escolhe o maior valor entre suas possibilidades, enquanto MIN escolhe o menor. Dessa forma, cada jogador considera não apenas sua própria jogada, mas também a melhor resposta que o adversário poderia dar.

Ao final da análise, o Minimax consegue determinar qual é a melhor jogada para o jogador atual, considerando todas as possibilidades futuras do jogo.
