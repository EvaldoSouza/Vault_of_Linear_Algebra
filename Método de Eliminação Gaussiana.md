#operação 
A **eliminação de Gauss**, ou **método de escalonamento**, é um [algoritmo](https://pt.wikipedia.org/wiki/Algoritmo "Algoritmo") para se resolver [sistemas de equações lineares](https://pt.wikipedia.org/wiki/Sistemas_de_equa%C3%A7%C3%B5es_lineares "Sistemas de equações lineares"). Este método consiste em aplicar sucessivas [operações elementares](https://pt.wikipedia.org/wiki/Opera%C3%A7%C3%A3o_elementar_(matrizes) "Operação elementar (matrizes)") num [sistema linear](https://pt.wikipedia.org/wiki/Sistema_linear "Sistema linear"), para o transformar num sistema de mais fácil resolução, que apresenta exatamente as mesmas soluções que o original. (Wikipedia).
As operações elementares são:
- Trocar uma linha por outra
- Multiplicar uma linha por um escalar diferente de zero
- Somar uma linha (ou seu multiplo) com outra.
O objetivo é transformar a matriz em uma matriz escalonada reduzida, onde a diagonal principal, menos a ultima coluna, é 1, e o restante dos valores (menos a ultima coluna) são 0s.

Da Wikipedia, temos a seguinte definição:
Uma [matriz](https://pt.wikipedia.org/wiki/Matriz_(matem%C3%A1tica) "Matriz (matemática)") retangular está na sua **forma escalonada** ou na **forma de escada por linhas** quando satisfaz as seguintes condições:

- Todas as linhas não-nulas estão acima de qualquer linha composta só de zeros.
- O pivô de cada linha está numa coluna à direita do pivô da linha acima.
- Todos os elementos de uma coluna abaixo de um pivô são zero.

Se uma matriz está na **forma escalonada reduzida** satisfaz ainda as seguintes características adicionais:

- O pivô de cada linha não-nula é 1.
- Cada pivô 1 é o único elemento não-nulo de sua coluna.

(Particularmente, prefiro minha definição :) )

O algoritmo falado é ir zerando a matriz, aplicando as operações básicas.
O passo 1 é fazer a [[Matriz Ampliada]].
O passo 2 é ir zerando os elementos abaixo da diagonal principal, aplicando as operações básicas.
O passo 3 é resolver o sistema gerado pelo passo 2.
