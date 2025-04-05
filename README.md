
---

# Projeto de Gerenciamento de Boards

## Descrição

Este projeto é uma aplicação Java para gerenciamento de quadros (boards), colunas e cartões (cards). Ele utiliza uma interface de linha de comando (CLI) para interagir com o usuário e realizar operações de CRUD (Create, Read, Update, Delete) em um banco de dados relacional.

## Tecnologias Utilizadas

- **Java 21**: Linguagem de programação principal do projeto.
- **Gradle**: Ferramenta de automação de build.
- **Liquibase**: Ferramenta de versionamento de banco de dados para gerenciar mudanças no esquema do banco de dados.
- **MySQL**: Banco de dados relacional utilizado para armazenar os dados da aplicação.
- **Lombok**: Biblioteca que reduz a verbosidade do código Java, gerando automaticamente getters, setters, construtores, entre outros.
- **JUnit**: Framework de testes utilizado para escrever e executar testes unitários.

## Estrutura do Projeto

- [`src/main/java/br/com/dio/`](command:_github.copilot.openRelativePath?%5B%22src%2Fmain%2Fjava%2Fbr%2Fcom%2Fdio%2F%22%5D "src/main/java/br/com/dio/"): Contém o código-fonte da aplicação.
  - `dto/`: Contém classes de transferência de dados (DTOs).
  - `exception/`: Contém classes para tratamento de exceções.
  - `persistence/`: Contém classes relacionadas à persistência de dados.
    - `dao/`: Contém classes de acesso a dados (DAOs).
    - `entity/`: Contém classes de entidade que representam tabelas do banco de dados.
  - `service/`: Contém classes de serviço que implementam a lógica de negócios.
  - `ui/`: Contém classes relacionadas à interface do usuário.
- [`src/main/resources/`](command:_github.copilot.openRelativePath?%5B%22src%2Fmain%2Fresources%2F%22%5D "src/main/resources/"): Contém recursos da aplicação.
  - `db/changelog/`: Contém arquivos de changelog do Liquibase para versionamento do banco de dados.
- [`build.gradle.kts`](command:_github.copilot.openRelativePath?%5B%22build.gradle.kts%22%5D "build.gradle.kts"): Script de build do Gradle.
- [`settings.gradle.kts`](command:_github.copilot.openRelativePath?%5B%22settings.gradle.kts%22%5D "settings.gradle.kts"): Configurações do Gradle.
- [`.idea/`](command:_github.copilot.openRelativePath?%5B%22.idea%2F%22%5D ".idea/"): Configurações do projeto para o IntelliJ IDEA.
- [`.vscode/`](command:_github.copilot.openRelativePath?%5B%22.vscode%2F%22%5D ".vscode/"): Configurações do projeto para o Visual Studio Code.

## Funcionalidades

- Gerenciamento de quadros, colunas e cartões.
- Operações de CRUD para quadros, colunas e cartões.
- Migração de banco de dados utilizando Liquibase.

## Como Executar

1. Clone o repositório:
   ```sh
   git clone <URL_DO_REPOSITORIO>
   ```
2. Navegue até o diretório do projeto:
   ```sh
   cd <NOME_DO_DIRETORIO>
   ```
3. Execute o projeto utilizando Gradle:
   ```sh
   ./gradlew run
   ```
