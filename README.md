#Repositório contendo os sistemas desenvolvidos em Python para a prática de lógica de programação.

#Sistema de Cadastro de Produtos.
Objetivo: gerenciar o estoque de uma pequena loja, permitindo cadastrar, listar, buscar, atualizar e excluir produtos.
  
#Menu principal
1 - Cadastrar produto
2 - Listar produtos
3 - Buscar produto
4 - Atualizar produto
5 - Excluir produto
0 - Sair

#strutura dos dados
Cada produto é armazenado como um dicionário:
```python
{"codigo": 101, "nome": "Arroz", "preco": 7.99, "quantidade": 10, "categoria": "Alimentos"}
Todos os produtos ficam em uma lista estoque.
Códigos são controlados em um set para evitar duplicatas.
Categorias disponíveis estão em uma tupla: ("Alimentos", "Limpeza", "Bebidas").

#Exemplo de uso:
> 1 - Cadastrar produto
Código: 101
Nome: Arroz
Preço: 7.99
Quantidade: 20
Categoria: Alimentos
Produto 'Arroz' cadastrado!

#Sistema de Controle de Alunos e Notas.
Objetivo: permitir que professores cadastrem alunos, registrem notas, calculem médias e gerem relatórios de desempenho.

#Menu principal
1 - Cadastrar aluno
2 - Registrar notas
3 - Listar alunos e médias
4 - Buscar aluno
5 - Mostrar aprovados e reprovados
6 - Relatórios
0 - Sair

#Estrutura dos dados
Os alunos são armazenados em um dicionário:
{"2024A01": (8.0, 7.5, 9.0)}
Chave → matrícula
Valor → tupla com notas
Nomes controlados em um set para evitar duplicatas

#Critério de aprovação
Média ≥ 7 = Aprovado
Média < 7 = Reprovado

#Relatórios disponíveis
Alunos cadastrados
Médias individuais
Aprovados e Reprovados

#Exemplo de uso:
> 1 - Cadastrar aluno
Matrícula: 001
Nome: Ana
Aluno cadastrado!
> 2 - Registrar notas
Nota 1: 8
Nota 2: 7
Nota 3: 9
Notas registradas!

