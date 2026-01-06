# 📞 Projeto: Agenda Telefônica

Este projeto consiste no desenvolvimento de um site de agenda telefônica, criado como parte de um trabalho do curso técnico em informática. O foco principal foi a lógica da programação, incluindo manipulação de dados, organização das informações de contatos e implementação das funções essenciais de uma agenda digital, como visualizar, adicionar, editar e excluir contatos.

Além do desenvolvimento do site, também utilizamos o método de organização Kanban para estruturar as etapas do projeto. Esse quadro ajudou a distribuir tarefas, acompanhar o progresso da equipe e garantir uma divisão clara entre o que estava a fazer, em andamento e concluído.

O resultado é um projeto colaborativo que une lógica, organização e prática real de desenvolvimento web.


# Requisitos

Os requisitos básicos são: um navegador atualizado (Chrome, Firefox, Edge etc.), um pacote como XAMPP/WAMP que já inclui Apache, MySQL e PHP, além de conexão com a internet para carregar o Bootstrap e as fontes do Google que o projeto utiliza, é necessário também ter o Banco de dados com os requisitos necessários.


# Passo a passo para abrir/executar

Para executar o projeto, primeiro descompacte o arquivo .zip e entre na pasta Projeto-agenda, onde estará as pastas e os arquivos referentes ao projeto. Em seguida, ative no XAMPP/WAMP o módulo Apache e MySQL, copie a pasta Projeto-agenda para dentro da pasta htdocs e acesse pelo navegador em http://localhost/Projeto-agenda.


# Dados do DataBase

- Nome do banco de dados: agenda.
- Nome da tabela: contatos.
- Colunas: id (INT UNSIGNED AUTO_INCREMENT PRIMARY KEY), nome (VARCHAR(100) NOT NULL), telefone (INT UNIQUE NOT NULL), comentario (TEXT).


# Copiar: 

**Criação do banco de dados**
CREATE DATABASE agenda; 

**Criação da tabela**
CREATE TABLE contatos(
    id INT UNSIGNED AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(100) NOT NULL,
    telefone INT UNIQUE NOT NULL,
    comentario TEXT
);


## Stack utilizada

**Front-end:** HTML, CSS e Bootstrap.

**Back-end:** MySQL.


## Integrantes do Grupo

- Cintia
- Jhonatan
- Jairo
- Jonas
