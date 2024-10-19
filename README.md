![Finalizado](https://img.shields.io/badge/Status-Finalizado-brightgreen)
# API de Filmes 🎬

Uma API RESTful para gerenciar um catálogo de filmes, permitindo operações de CRUD (Criar, Ler, Atualizar, Excluir) com os filmes.

## Funcionalidades📎

### 1. Obter Todos os Filmes
- **Método**: `GET /filmes`
- **Descrição**: Retorna uma lista de todos os filmes cadastrados.

### 2. Obter Filme por ID
- **Método**: `GET /filmes/{id}`
- **Descrição**: Retorna os detalhes de um filme específico pelo seu ID. Retorna um erro 404 se o filme não for encontrado.

### 3. Cadastrar Filme
- **Método**: `POST /filmes`
- **Descrição**: Adiciona um novo filme ao catálogo. Retorna um status 201 se criado com sucesso.

### 4. Excluir Filme
- **Método**: `DELETE /filmes/{id}`
- **Descrição**: Remove um filme do catálogo pelo seu ID. Retorna um status 204 se excluído com sucesso, ou um erro 404 se não encontrado.

### 5. Atualizar Filme
- **Método**: `PUT /filmes/{id}`
- **Descrição**: Atualiza os dados de um filme existente. Retorna um status 200 se atualizado com sucesso, ou um erro 404 se não encontrado.

## Tecnologias Utilizadas 🛠️
- ![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)
- ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
- ![JPA](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
- ![Banco de Dados](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

## Como Usar📌
1. Clone o repositório.
2. Configure o banco de dados no arquivo de propriedades.
3. Execute a aplicação.
4. Use um cliente HTTP como Postman ou Insomnia para interagir com a API.

## Contribuição 🤝
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.
