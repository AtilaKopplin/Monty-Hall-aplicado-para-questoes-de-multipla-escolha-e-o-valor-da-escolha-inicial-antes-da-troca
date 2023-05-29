# Monty Hall, diferença de revelar portas erradas antes ou depois da escolha
Monty Hall aplicado para questões de múltipla escolha e o valor em revelar opções erradas antes ou depois da escolha

  No problema de Monty Hall com 3 portas, mudar a escolha inicial após a revelação de uma porta errada resulta em 66,66% de probabilidade de acertar a porta premiada. De modo interessante, maior até do que se a escolha fosse feita dentre apenas 2 portas (50%), revelando uma porta errada antes da escolha inicial. O problema estendido para n portas, como n=100, depois da escolha da porta inicial são abertas 98 portas erradas e torna a conclusão óbvia. Mas abrir 98 portas antes da escolha inicial, restando apenas 2 para se fazer a escolha, resulta na probabilidade de 50% de ganhar o prêmio, demonstrando a importância de se fazer a escolha antes da revelação de portas erradas. A ideia foi verificar o problema estendido para 5 portas e quantas portas reveladas erradas trariam a maior probabilidade de levar o prêmio, se revela-las antes ou depois da escolha inicial iria influenciar nos resultados.

Conclusão

  O problema de Monty Hall se define em 3 atos — A escolha, a eliminação de portas erradas e a troca no final. O objetivo é trazer e aplicar essa estrutura em uma abordagem para auxiliar em questões de múltiplas escolhas com 5 opções:

1- Escolha uma opção aleatória antes mesmo de ler a questão
2- Tente eliminar o máximo de opções erradas — perde-se o valor da técnica quando a escolha aleatória inical estará entre elas — 60% das vezes que conseguir eliminar 3 respostas erradas
3- Então mude para uma das opções que restaram desde que sejam tão ou mais atraentes como a resposta correta do que a opção aleatória escolhida inicialmente.

  Essa abordagem aumenta de 50% para 80% a chance de se acertar a questão quando se consegue eliminar 3 respostas erradas — o melhor cenário para o método com a máxima eliminação de portas erradas.

Um dos relatórios com 10 mil simulações com 5 portas foi o seguinte 

1 porta errada é revelada

Mantém a escolha inicial:			              	      19.93 %
Troca a porta inicial:					                    27.24 %
A porta errada foi revelada antes da escolha:	      24.86 %


2 portas erradas são reveladas

Mantém a escolha inicial:				                    19.62 %
Troca a porta inicial:				                    	39.23 %
As portas erradas foram reveladas antes da escolha:	33.43 %

3 portas erradas são reveladas

Mantém a escolha inicial:			                    	20.17 %
Troca a porta inicial:				                    	79.96 %
As portas erradas foram reveladas antes da escolha:	50.3 %
