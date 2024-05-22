Web API de Cadastro e Autenticação de Usuários
Este projeto consiste em uma Web API construída em C# utilizando o framework ASP.NET, que permite o cadastro de usuários em um banco de dados MySQL, além de oferecer funcionalidades de login, geração de token JWT e autenticação de idade.

Funcionalidades
Cadastro de usuários: Os usuários podem se cadastrar na plataforma fornecendo informações como nome, e-mail e data de nascimento. Esses dados são armazenados em um banco de dados MySQL utilizando o sistema de Migrations do Entity Framework.

Login e geração de token: Após o cadastro, os usuários podem realizar o login na plataforma. Ao efetuar o login com sucesso, é gerado um token JWT (JSON Web Token) que é utilizado para autenticar as solicitações subsequentes do usuário.

Autenticação de idade: A Web API verifica se o usuário é maior de idade com base na data de nascimento fornecida durante o cadastro. Essa verificação é feita no momento do login utilizando a data de nascimento armazenada no banco de dados.

Tecnologias Utilizadas
ASP.NET MVC: Utilizado como framework para o desenvolvimento da Web API.
Swagger: Ferramenta para documentação e teste de APIs RESTful.
Identity: Biblioteca do ASP.NET para gerenciamento de autenticação e autorização de usuários.
JWT (JSON Web Token): Utilizado para autenticação de usuários e geração de tokens de acesso.
MySQL: Banco de dados relacional utilizado para armazenar os dados dos usuários.
Entity Framework Migrations: Utilizado para gerenciar as migrações do banco de dados e manter a consistência do esquema.
C#: Linguagem de programação utilizada para desenvolver a lógica da aplicação.
Secret: Utilizado para proteger informações sensíveis, como chaves de API e segredos de autenticação.
Configuração e Uso
Clone o repositório para o seu ambiente de desenvolvimento.
Abra o projeto em seu ambiente de desenvolvimento preferido (Visual Studio, Visual Studio Code, etc.).
Configure a conexão com o banco de dados MySQL no arquivo appsettings.json.
Execute as migrações do banco de dados para criar as tabelas necessárias utilizando o comando dotnet ef database update.
Inicie a aplicação e utilize o Swagger para testar as rotas da API.
Contribuindo
Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões de melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

Licença
Este projeto está licenciado sob a Licença MIT.