# Sistema de Gestão de Biblioteca

Desenvolva, em uma linguagem back-end de sua escolha, um sistema para gestão de biblioteca. Este sistema deve incluir um CRUD para livros e outro para gêneros, ambos com uma relação 1:n, onde um livro pode ter apenas um gênero e um gênero pode ser atribuído a vários livros. O sistema também deve ter níveis de usuário: o usuário administrador terá acesso aos CRUDs, enquanto o usuário comum poderá apenas consultar a disponibilidade dos livros.

## CRUD - Livros

O CRUD dos livros deve conter os seguintes campos:

- Nome do Livro
- Número de Páginas
- Quantidade em Estoque
- Gênero do Livro (Relacionamento)

## CRUD - Gênero

O CRUD do gênero deve conter os seguintes campos:

- Nome do gênero textual
- Descrição breve

Além desses dois campos deve haver uma tabela para criação de usuário com: Nome e nível de usuário (Administrador ou Usuário).

Faça uma cópia do repositório do projeto e, no final do teste, envie-me o link do seu fork.
