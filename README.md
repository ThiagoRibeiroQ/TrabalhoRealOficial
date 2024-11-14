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

### Passo 3: Configurar o apache tomcat:
Baixe e instale o Apache Tomcat (se ainda não tiver).
Configure o Tomcat no Eclipse ou na sua IDE de escolha:
Eclipse: Vá em Window > Preferences > Server > Runtime Environments e adicione o Tomcat.
Adicione o seu projeto ao Tomcat no Eclipse:
Clique com o botão direito no servidor Tomcat e selecione Add and Remove Projects.
Adicione o seu projeto à lista de projetos do Tomcat.


## Executando o Projeto
### Passo 1: Iniciar o Tomcat
Abra o Eclipse ou seu ambiente de desenvolvimento.
Inicie o servidor Tomcat através do painel de servidores.
Certifique-se de que o Tomcat está configurado para o seu projeto (no painel de servidores, adicione o projeto ao Tomcat).

### Passo 2: Acessar no Navegador
Abra o navegador e digite o seguinte endereço: http://localhost:8080/[nome_do_projeto]/[pagina.jsp]



## Funcionalidades
Cadastro de Filmes: Permite adicionar novos filmes ao banco de dados.
Listagem de Filmes: Exibe todos os filmes cadastrados no banco de dados.
Edição de Filmes: Permite editar os dados dos filmes cadastrados.
Exclusão de Filmes: Permite excluir filmes do banco de dados

```bash
git clone https://link-para-o-repositorio.git
