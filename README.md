# Locadora

Um sistema simples que permite realizar operações de inclusão, exclusão, pesquisa e alteração de filmes em uma base de dados MySQL utilizando Servlets e JSP.

---

## Tecnologias Utilizadas

- **Java** - Linguagem de programação principal.
- **Apache Tomcat** - Servidor de aplicação.
- **JSP** (Java Server Pages) - Para renderizar conteúdo dinâmico.
- **JDBC** - Para interagir com o banco de dados.
- **MySQL** - Banco de dados relacional utilizado.

---

## Pré-requisitos

Antes de executar o projeto, você precisa ter os seguintes programas instalados na sua máquina:

- **JDK 17** (ou versão superior)
- **Apache Tomcat** (ou outro servidor de sua escolha)
- **MySQL** (ou outro banco de dados relacional)
- **Maven** (se usar dependências e gerenciador de builds)

---

## Configuração do Ambiente

### Passo 1: Clonar o Repositório

Clone o repositório para a sua máquina local:



### Passo 2: Configurar o banco de dados:

CREATE DATABASE CadastroLocadora;


USE CadastroLocadora;

	
CREATE TABLE Filme (
    id INT AUTO_INCREMENT PRIMARY KEY,       
    nome VARCHAR(100),              
    descricao TEXT,                          
    data_inclusao DATE             
);


```bash
git clone https://link-para-o-repositorio.git
