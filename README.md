## Sistema de Gerenciamento de Biblioteca

Este sistema, desenvolvido em C#, permite gerenciar uma biblioteca de forma eficiente. Os administradores podem cadastrar livros, enquanto os usuários têm a opção de pegar livros emprestados ou devolvê-los, respeitando um limite de até três livros por usuário.

### Funcionalidades

#### Administrador:
- Cadastrar novos livros na biblioteca.

#### Usuário:
- Pegar até 3 livros emprestados.
- Devolver livros.

### Estrutura do Projeto

#### Classes:
- **Program**: Classe principal que contém a lógica do sistema.
- **Livro**: Classe que representa um livro, incluindo propriedades para autor, nome e gênero.

#### Listas e Dicionários:
- O sistema utiliza uma lista (`List<Livro>`) para armazenar os livros disponíveis.
- Um dicionário (`Dictionary<string, int>`) mantém a contagem de livros emprestados por cada usuário.
