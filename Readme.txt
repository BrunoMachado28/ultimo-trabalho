Factory Method

A principal vantagem em utilizar o padrão Factory Method é a extrema facilidade para incluir novos produtos. Não é necessário alterar NENHUM código, apenas precisamos criar o produto e a sua fábrica. Todo o código já escrito não será alterado.

No entanto isto tem um custo. Perceba que criamos uma estrutura relativamente grande para resolver o pequeno problema.


Proxy

São 4 tipos de proxy que podem ser utilizados:

Protection Proxy: esse é o tipo de proxy que utilizamos no exemplo. Eles controlam o acesso aos objetos, por exemplo, verificando se quem chama possui a devida permissão.

Virtual Proxy: mantem informações sobre o objeto real, adiando o acesso/criação do objeto em si

Remote Proxy: fornece um representante local para um objeto em outro espaço de endereçamento.

Smart Reference: este proxy é apenas um susbtituto simples para executar ações adicionais quando o objeto é acessado, por exemplo para implementar mecanismos de sincronização de acesso ao objeto original.