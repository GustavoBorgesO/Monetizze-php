# Monetizze-php
Resultado do teste para DEV da empresa Monetizze realizado no dia 02/09. O codigo relacionado foi desenvolvido seguindo o roteiro e orientações contidas no documento de teste disponibilizado pela empresa.

•1  -  Desenvolva  uma  classe  que  possua  4  atributos  privados  que  dever ̃ao  conter  osseguintes dados:
- Quantidade de dezenas, que dever ́a permitir apenas as seguintes opcoes:  6, 7, 8,9 ou 10.
- Resultado
- Total jogos
- Jogos

•2  -  Desenvolver  na  classe  anterior  2  metodos  publicos  GET  e  SET  para  definir os valores dos atributos.

•3 - Desenvolver metodo de construcao onde 2 parâmetros serao recebidos os atributos e consequentemente suas definicoes de valor:
- Quantidade de dezenas
- Total de jogos.

•4 - Desenvolver um metodo privado que retorne um array com dezenas entre 01 e 60 que respeite a cardinalidade definida pelo atributo “Quantidade de dezenas” onde asdezenas nunca se repitam e estejam na ordem crescente.

•5  -  Desenvolver  um  metodo  publico  que  selecione  a  quantidade  de  jogos  que  est ́asetado no atributo “Total jogos” obtendo assim um array multidimensional onde cada posicao deste array dever ́a conter outro array com um jogo. Use o metodo anterior para gerar cada jogo e salve este array multidimensional no atributo “Jogos”.

•6 - Desenvolver um metodo publico que realize o sorteio de 6 dezenas aleatorias entre 01  e  60.   Os  n ́umeros  nao  podem  se  repetir  e  devem  estar  em  ordem  crescente. O array resultante dever ́a ser armazenado no atributo “Resultado”.

•7 - Desenvolver um metodo que confere todos os jogos e retorna uma tabela HTML que contem os jogos e quantas dezenas foram sorteadas em cada jogo.
