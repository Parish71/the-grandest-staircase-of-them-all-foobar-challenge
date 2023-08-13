## A Escadaria Mais Majestosa de Todas==================================
Com o dispositivo de Juízo Final LAMBCHOP concluído, o Comandante Lambda está se preparando para fazer sua estreia no palco galáctico - mas para causar um grande impacto, Lambda precisa de uma escadaria grandiosa! Como assistente pessoal do Comandante, você foi incumbido de descobrir como construir a melhor escadaria DE TODAS. Lambda lhe deu uma visão geral dos tipos de tijolos disponíveis, bem como um orçamento. Você pode comprar quantidades diferentes dos diversos tipos de tijolos (por exemplo, 3 tijolos pequenos rosa, ou 5 tijolos azuis de renda). O Comandante Lambda quer saber quantos tipos diferentes de escadarias podem ser construídos com cada quantidade de tijolos, para que possam escolher aquele com mais opções.

Cada tipo de escadaria deve consistir em 2 ou mais degraus.
Não é permitido que dois degraus tenham a mesma altura - cada degrau deve ser mais baixo que o anterior. Todos os degraus devem conter pelo menos um tijolo.
A altura de um degrau é classificada como a quantidade total de tijolos que compõem aquele degrau. Por exemplo, quando N = 3, você tem apenas 1 opção de como construir a escadaria, com o primeiro degrau tendo uma altura de 2 e o segundo degrau tendo uma altura de 1: (# indica um tijolo)###21

Quando N = 4, você ainda tem apenas 1 escolha de escadaria:
####31
Mas quando N = 5, há duas maneiras de construir uma escadaria com os tijolos fornecidos.

As duas escadarias podem ter alturas (4, 1) ou (3, 2), como mostrado abaixo:
#####41
#####32

Escreva uma função chamada solution(n) que aceita um inteiro positivo n e retorna o número de escadarias diferentes que podem ser construídas exatamente com n tijolos. n será sempre pelo menos 3 (para que uma escadaria possa ser construída), mas no máximo 200, porque o Comandante Lambda não é feito de dinheiro! Linguagens

=========Para fornecer uma solução em Java, edite Solution.java
Para fornecer uma solução em Python, edite solution.py

Casos de teste

==========Seu código deve passar pelos seguintes casos de teste. Note que ele também pode ser executado em casos de teste ocultos não mostrados aqui.

-- Casos em Java --

Entrada:Solution.solution(200)
Saída:    487067745
Entrada:Solution.solution(3)
Saída:    1

-- Casos em Python --

Entrada:solution.solution(200)
Saída:    487067745

Entrada:solution.solution(3)
Saída:    1