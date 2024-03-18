# Bd-Atividade1 
Nessa atividade desevolvi um sistema de gerenciamento de biblioteca utilizando o Modelo Entidade-Relacionamento (MER).

Para desenvolver esse mapa criei um total de 7 entidades, sendo elas: Livro, Usuario, Professor, Aluno, Autor, Categoria e Emprestimo. Estes são conectados pelos seguintes relacionamentos:

1- Livro-Autor: basicamente relacionando o Autor aos titulos que ele produz.

2- Livro-Emprestimo: relação para saber se o livro está ou não emprestado a alguém.

3- Livro-Categoria: ajuda a indentificar mais rapído o livro dentro do sistema.

4- Usuario-Emprestimo: faz o controle dos sistema, saber quem pegou determinado livro e quando é o prazo de devolução.

Implementei também uma Especialização-Generalização como pedido na questão, utilizando as entidades Usuario, Professor e Aluno. Onde usuario é a generalização e professor/aluno são as especificações.
