# 📚 Livraria Palavra Viva – Sistema Web

Sistema web desenvolvido em **Java com Spring Boot**, com integração ao **MySQL**, permitindo o gerenciamento completo de livros de uma livraria.

## 🚀 Funcionalidades

* Cadastro de livros
* Listagem com busca, edição e exclusão
* Relatórios por:

  * Categoria
  * Ano
  * Autor
* API REST integrada ao front-end

## 🛠️ Tecnologias utilizadas

* Java 17
* Spring Boot
* Spring Data JPA
* MySQL
* HTML, CSS e JavaScript
* Maven
* Git e GitHub

## 📂 Estrutura do projeto

* `src/main/java` → Backend Spring Boot
* `src/main/resources/static` → Front-end
* `src/main/resources/sql` → Script do banco

## ▶️ Como executar o projeto

1. Clone o repositório:

   ```
   git clone https://github.com/eliezrealmeida94/palavraviva-web-spring.git
   ```

2. Configure o banco MySQL no arquivo:

   ```
   src/main/resources/application.properties
   ```

3. Execute a aplicação Spring Boot.

4. Acesse no navegador:

   ```
   http://localhost:8081
   ```

## ⚙️ Configurações do ambiente

* A aplicação foi configurada para executar na porta **8081**, evitando conflito com a porta padrão 8080.
* Para facilitar a execução em ambiente acadêmico, o banco de dados local foi configurado **sem senha**.
* Em ambientes de produção, recomenda-se utilizar **credenciais seguras** e **variáveis de ambiente** para proteger o acesso ao banco.

## 👨‍💻 Autor

**Eliezer Almeida**
Projeto – ADS
