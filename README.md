A implementação da remoção da árvore binária foi feita de forma recursiva, porque ficou mais fácil de entender e combinar com a estrutura da árvore. Como cada nó pode ter um filho na esquerda e outro na direita, a recursão ajuda a percorrer os nós até encontrar o valor que precisa ser removido.

Durante a remoção, o algoritmo verifica os 3 casos possíveis:

nó folha;
nó com apenas um filho;
nó com dois filhos.

Quando o nó possui dois filhos, foi utilizado o método do sucessor (menor dos maiores), como pedido no trabalho. Nesse caso, o algoritmo pega o menor valor da subárvore da direita e coloca no lugar do nó removido, mantendo a organização correta da árvore.

A escolha da recursão também ajudou a deixar o código mais organizado e menor, sem precisar usar muitos laços de repetição ou variáveis auxiliares. Além disso, a inserção já tinha sido feita de forma recursiva, então foi mantido o mesmo padrão no código.
