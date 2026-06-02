# Bella Amora - Sistema de Gestão de Salão de Beleza

> ⚠️ **Aviso:** Este projeto está em desenvolvimento e é destinado a **fins acadêmicos**.

## Sobre o Projeto

O **Bella Amora** é um aplicativo web voltado para a gestão e organização de um salão de beleza. O sistema foi desenvolvido com o objetivo de otimizar o controle de atendimentos, clientes e profissionais, proporcionando uma administração mais eficiente e intuitiva.

A aplicação permite o gerenciamento completo de agendamentos, facilitando o fluxo de trabalho do salão e melhorando a experiência tanto para clientes quanto para administradores.

## Tecnologias e Arquitetura

O projeto foi desenvolvido em **Node.js**, utilizando o padrão de arquitetura **MVC (Model-View-Controller)** para melhor organização e escalabilidade do sistema.

Principais tecnologias utilizadas:

* **Express**: Framework para criação de rotas e gerenciamento de requisições.
* **Sequelize**: ORM responsável pela comunicação com o banco de dados.
* **MySQL2**: Driver para conexão com banco de dados relacional MySQL.
* **EJS (Embedded JavaScript)**: Engine de renderização para construção das interfaces web.

## Funcionalidades e Escopo

Atualmente, o sistema conta com as seguintes funcionalidades:

### 👤 Controle de Usuários

* Cadastro e autenticação de usuários
* Armazenamento de dados como nome, e-mail e senha

### 💅 Agendamentos e Serviços

* Registro de atendimentos com:

  * Nome do cliente
  * Contato (telefone)
  * Data e horário do atendimento
  * Tipo de serviço (corte, manicure, maquiagem, etc.)
  * Profissional responsável

## Estrutura do Projeto

* `aplicativo_web/`: Núcleo da aplicação backend

  * `app.js` e `server.js`: Inicialização do servidor (porta `8080`)
  * `database/`: Configuração do banco de dados (`dbconfig.js`)
  * `mvc/`: Estrutura principal:

    * `controllers/`: Lógica das requisições
    * `models/`: Regras de negócio
    * `routes/`: Definição das rotas
    * `views/`: Interfaces com EJS
  * `schemas/`: Definição das tabelas com Sequelize
  * `services/`: Regras adicionais e serviços auxiliares

* `Documentação`: Contém diagramas e documentos do sistema

## Como Executar o Projeto

### Pré-requisitos

* Node.js instalado
* MySQL configurado e em execução

### Passo a passo

1. Acesse a pasta do projeto:

```bash
cd aplicativo_web
```

2. Instale as dependências:

```bash
npm install
```

3. Configure o banco de dados no arquivo:

```
database/dbconfig.js
```

4. Inicie o servidor:

```bash
node app.js
```

5. Acesse no navegador:

```

http://localhost:8080/user/index
```

> O Sequelize está configurado com `{ alter: true }`, atualizando automaticamente as tabelas ao iniciar o projeto.


<img width="1919" height="987" alt="image" src="https://github.com/user-attachments/assets/4189c8d1-f0ce-45c9-89a1-651d1c5eb663" />
<img width="1915" height="977" alt="image" src="https://github.com/user-attachments/assets/7400dbed-e8e4-4287-a123-f52d9089ce74" />
<img width="1919" height="979" alt="image" src="https://github.com/user-attachments/assets/ead176cb-463b-4e37-bc71-1d6e4dd1e372" />
<img width="1918" height="965" alt="image" src="https://github.com/user-attachments/assets/23b57f05-5aa0-446f-9f77-a0df09c9bdbe" />
<img width="1919" height="576" alt="image" src="https://github.com/user-attachments/assets/3aa2a8ad-8f7f-41b0-b1e9-f238d5aa9993" />
<img width="617" height="765" alt="image" src="https://github.com/user-attachments/assets/b604d416-bb83-488e-8288-f30161d6a0ad" />
<img width="669" height="758" alt="image" src="https://github.com/user-attachments/assets/3e409647-e3d1-4678-a4cb-16d973769bfc" />
<img width="641" height="761" alt="image" src="https://github.com/user-attachments/assets/e3eea078-a47a-4378-abf8-392369205b8a" />






