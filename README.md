# Web API de Cadastro e Autenticação de Usuários

Este repositório contém uma Web API desenvolvida em C# utilizando o framework ASP.NET. A API permite o cadastro de usuários em um banco de dados MySQL, oferece funcionalidades de login com geração de token JWT e autenticação de idade.

## Funcionalidades Principais

- **Cadastro de Usuários**: Os usuários podem se cadastrar na plataforma fornecendo informações básicas, como nome, e-mail e data de nascimento. Esses dados são armazenados de forma segura em um banco de dados MySQL.

- **Login e Geração de Token JWT**: Após o cadastro, os usuários podem fazer login na plataforma. Ao fazer login com sucesso, um token JWT é gerado e fornecido ao usuário, que será utilizado para autenticar as solicitações subsequentes.

- **Autenticação de Idade**: A API verifica se o usuário é maior de idade com base na data de nascimento fornecida durante o cadastro. Essa verificação é realizada no momento do login, garantindo que apenas usuários maiores de idade tenham acesso às funcionalidades específicas da plataforma.

## Tecnologias Utilizadas

- **ASP.NET MVC**: Framework utilizado para desenvolver a lógica da aplicação e fornecer uma estrutura MVC para a Web API.
  
- **MySQL**: Banco de dados relacional utilizado para armazenar os dados dos usuários de forma segura e eficiente.

- **Entity Framework Migrations**: Utilizado para gerenciar as migrações do banco de dados e garantir a consistência do esquema durante o desenvolvimento e a implantação da aplicação.

- **Swagger**: Ferramenta utilizada para documentação e teste da API RESTful, facilitando o entendimento das rotas disponíveis e dos parâmetros aceitos.

- **JWT (JSON Web Token)**: Utilizado para autenticar os usuários e gerar tokens de acesso, proporcionando uma camada adicional de segurança para a comunicação entre o cliente e o servidor.

Este repositório serve como ponto de partida para o desenvolvimento de uma aplicação segura e escalável, oferecendo uma estrutura sólida e bem documentada para a criação de uma API de cadastro e autenticação de usuários.
