# Desafio---Caca-ao-tesouro

Existe um tesouro em um mapa. Você está no centro desse mapa e sabe exatamente a
localização do tesouro. Será que você consegue resgatá-lo para mim?

Entrada:
O usuário deverá digitar dois valores N e M inteiros, representando respectivamente
quantidade de linhas e quantidade de colunas do mapa. O mapa poderá ter dimensões
entre 5x5 e 100x100. Cada posição do mapa é representada por '.'. O seu personagem
deverá estar posicionado no centro do mapa e será representado por '@'. A posição do
tesouro deverá ser gerada aleatoriamente e deverá ser representada por '$'.

Exemplo:
N = 5, M =9
. . . . . . . $ .
. . . . . . . . .
. . . . @ . . . .
. . . . . . . . .
. . . . . . . . .

O exemplo acima serve apenas para ajudá-lo a entender o problema. O tesouro '$' pode
estar em qualquer lugar do mapa exceto na posição do seu personagem '@'.

Seu programa deverá retornar o menor caminho que você deverá fazer até chegar a
posição do tesouro. Os movimentos permitidos são: CIMA, BAIXO, ESQUERDA e DIREITA.

Saída:
Para o mapa de Exemplo temos como saída válida a seguinte sequência:
CIMA, CIMA, DIREITA, DIREITA, DIREITA

Pontuação:
Sua pontuação será calculada da seguinte maneira:
pontuacao = (N*M - movimentos) /10
Tomando o exemplo como base a pontuação seria igual a 4 pontos ( (5*9 - 5)/10 )
