# Trabalho-Pratico-3

## Programa feito na linguagem de programação C++ para a disciplina Programação de Computadores.

### Esse programa é voldado para o gerenciamento de um estoque de um loja de qualquer ramo, onde produtos podem ser adicionados, excluidos e listados pelo usuário a qualquer momento. Onde a cada vez que o programa é executado o estoque permanece o mesmo a partir da leitura e gravação das informações em um arquivo binário.

-Ao selecioanr a opção Adicionar o usuário deverá digitar o nome do produto, a quantidade desse produto que será adicionado ao estoque e o preço do kilo desse produto. Caso o usuário adicione um produto com o mesmo nome de outro que ja está no estoque, o preço desse produto será atualizado para o qual ele digitou recentemente e a quantidade que ele digitar será adicionada com a que ja estava no estoque.

-Ao selecionar a opção Excluir os nomes dos produtos serão listados e enumerados, e para excluir um basta digitar o número que corresponde ao nome do produto que deseja excluir. Após inserir o número o programa exibirá uma pergunta de confirmação: "Realmente deseja excluir nome_do_produto? (S/N)" para excluir o usuário digitará a letra 'S' e para não excluir digitará a letra 'N'.

-Ao selecionar a opção Listar, os produtos que estiverem no estoque serão exibidos no formato: "nome_do_produto----Preço(em reais)----Quantidade(em KG)".

-A opção pedir trabalha com arquivos de texto(.txt), ao escolher a opção pedir o usuário deverá digitar o nome do arquivo de texto que devera seguir tal formatação:

Indentificação do Cliente

linha com caracteres '-' ou em branco

nome_do_produto   quantidade

nome_do_produto   quantidade

...

Ao digitar o nome do arquivo texto que deverá estar na pasta em que o programa estiver rodando, o programa irá ler o arquivo e verificar se os produtos e as quantidades estão disponíveis no estoque. Caso não estejam o pedido irá falhar e o estoque não será alterado. Caso tenha os produtos e as quantidades solicitadas no pedido o programa irá gerar um arquivo texto com a extensão .nfc na pasta em que o programa estiver rodando, que será a nota fiscal do pedido onde aparecerá todas as informações dos produtos pedidos e o valor final do pedido, após isso o estoque será atualizado subtraindo as quantidades dos produtos pedidos pela quantidade que tinha no pedido.

-Para sair do ciclo do programa basta selecionar a opção Sair digitando a letra 'S' no menu do Sistema de Controle.
