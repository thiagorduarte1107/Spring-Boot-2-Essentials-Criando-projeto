Descrição do Projeto: Sistema de Gerenciamento de Animes
Visão Geral
O Sistema de Gerenciamento de Animes é uma aplicação web desenvolvida com o framework Spring Boot, projetada para oferecer uma interface simples e intuitiva para a gestão e visualização de informações sobre animes. A aplicação permite que os usuários visualizem uma lista de animes disponíveis e fornece uma base para futuras expansões, como adição, edição e exclusão de animes da lista.

Tecnologias Utilizadas
Spring Boot: Escolhido por sua capacidade de simplificar o processo de configuração e desenvolvimento de aplicações Java, permitindo foco maior na lógica de negócios ao invés da configuração de ambiente.
Java: Linguagem de programação utilizada para desenvolver a aplicação, aproveitando sua robustez, segurança e portabilidade.
Maven: Ferramenta de automação de compilação utilizada para gerenciar as dependências do projeto, facilitando a construção e o gerenciamento do ciclo de vida da aplicação.
Funcionalidades
Listagem de Animes: A aplicação oferece uma rota REST que responde com uma lista pré-definida de animes, demonstrando a capacidade de servir dados em formato adequado para aplicações web e mobile.
Arquitetura Expansível: A estrutura do projeto foi concebida para ser facilmente expansível, permitindo a inclusão de novas funcionalidades como autenticação de usuários, gestão detalhada de animes (CRUD completo) e integração com bancos de dados.
Estrutura do Projeto
Controller: Camada responsável pelo tratamento das requisições HTTP, direcionando para a lógica de negócios apropriada.
Model: Define a estrutura de dados do domínio de Animes, representando as informações que serão manipuladas pela aplicação.
Startup: Contém a classe principal que inicia a aplicação, configurando e lançando o servidor embutido do Spring Boot.
Como Executar
Para executar o projeto, é necessário ter o Java e o Maven instalados. Com o ambiente configurado, basta navegar até a raiz do projeto através do terminal ou prompt de comando e executar o seguinte comando:

shell
Copy code
mvn spring-boot:run
Isso iniciará a aplicação na porta padrão 8080, permitindo o acesso à lista de animes disponíveis através da URL http://localhost:8080/anime/list.

Conclusão
O Sistema de Gerenciamento de Animes é um projeto inicial que demonstra a capacidade do Spring Boot em simplificar o desenvolvimento de aplicações web modernas. Com uma base sólida e uma arquitetura limpa e expansível, o projeto serve como um excelente ponto de partida para desenvolvedores que buscam aprender sobre desenvolvimento web com Spring Boot e Java.
