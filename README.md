Relatório

A implementação da remoção na árvore binária foi feita utilizando recursividade, pois esse modelo se adapta melhor à estrutura da árvore. 
Como cada nó pode possuir outros nós à esquerda e à direita, a recursão facilita a navegação até encontrar o elemento desejado.
Durante a remoção, o método percorre a árvore comparando os valores até localizar o nó correto. Após encontrar o nó, o algoritmo trata os três possíveis casos:
-nó folha;
-nó com apenas um filho;
-nó com dois filhos.
Para nós com dois filhos, foi utilizado o método do sucessor (menor dos maiores), conforme solicitado no enunciado.
Nesse caso, o nó removido recebe o valor do menor elemento da subárvore direita, mantendo a organização da árvore binária.
A escolha pela implementação recursiva deixou o código mais organizado e reduzindo a necessidade de estruturas auxiliares e repetições maiores com laços de repetição.
