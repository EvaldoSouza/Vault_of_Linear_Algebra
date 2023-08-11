#conceito 
Sistemas lineares são formados por duas ou mais equações lineares que possuem suas incógnitas relacionadas. 
Um problema fundamental de sistemas lineares é saber se eles possuem solução.
Tomando por exemplo o sistema ax = b.
Se a != 0, o sistema possui uma única solução.
Se 0x = 0, possui infinitas.
E se 0x = b, não possui nenhuma solução.

E é possível organizar sistemas em matrizes!
Se tivermos um sistema de equações lineares composto por *m* equações e *n* incognitas, podemos defini-lo como:
a11x1 + a12x2...a1nxn = b1
a21x1 + a22x2...a2nxn = b2
.
.
.
am1x1 + am2x2...amnxn = bm

E, se separar-mos esse sistema em 3 matrizes, uma Am.n, uma Xn.1 e uma Bm.1, podemos usar as propriedades de matriz para facilitar a solução desse sistema.
O primeiro conceito para realizar essa solução é o de [[Matriz Ampliada]].
Depois se aplica o [[Método de Eliminação Gaussiana]].
