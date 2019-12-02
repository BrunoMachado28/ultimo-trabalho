Factory Method

A principal vantagem em utilizar o padr�o Factory Method � a extrema facilidade para incluir novos produtos. N�o � necess�rio alterar NENHUM c�digo, apenas precisamos criar o produto e a sua f�brica. Todo o c�digo j� escrito n�o ser� alterado.

No entanto isto tem um custo. Perceba que criamos uma estrutura relativamente grande para resolver o pequeno problema.


Proxy

S�o 4 tipos de proxy que podem ser utilizados:

Protection Proxy: esse � o tipo de proxy que utilizamos no exemplo. Eles controlam o acesso aos objetos, por exemplo, verificando se quem chama possui a devida permiss�o.

Virtual Proxy: mantem informa��es sobre o objeto real, adiando o acesso/cria��o do objeto em si

Remote Proxy: fornece um representante local para um objeto em outro espa�o de endere�amento.

Smart Reference: este proxy � apenas um susbtituto simples para executar a��es adicionais quando o objeto � acessado, por exemplo para implementar mecanismos de sincroniza��o de acesso ao objeto original.