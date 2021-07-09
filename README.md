# Energia para trasmutacao

_Em Fullmetal Alchemist alquimistas conseguem, com a ajuda de padrões chamados círculos de transmutação, transformar um objeto em outro. Um alquimista precisa saber qual a chance da transmutação que ele está querendo realizar dar certo para que ele consiga transformar um objeto no objeto que ele quer.
A quantidade de energia necessária para realizar uma transmutação (E) é dada pelo nível da diferença entre os objetos (D) e pelo nível de imprecisão do círculo de transmutação (P), tal que E = D * P / (D + P + 1). Você foi contratado para, dados o nível da diferença entre os objetos D e o nível de imprecisão do círculo de transmutação P, qual é a quantidade de energia necessária para realizar a transmutação._

### Entrada

A entrada possui dois inteiros, separados por espaço. O primeiro valor é um inteiro representando a diferença entre os objetos D (0 < D < 1000), e o segundo valor é um inteiro representando a imprecisão do círculo de transmutação P (0 < P < 1000).

### Saída

A saída consiste em uma única linha contendo um número inteiro E que representa a quantidade de energia necessária para realizar a transmutação em questão.

Entrada | Saída 
:-----: | :-----: 
12 15 | 6
100 72 | 41
643 11 | 10
