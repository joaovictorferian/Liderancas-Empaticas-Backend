# Lideranças Empáticas - Backend

![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow)

Backend da aplicação desenvolvido em **Node.js** no âmbito do projeto **Lideranças Empáticas**, com o objetivo de facilitar o recebimento e a gestão de doações para o **Instituto Alma**.  
Este servidor é responsável pela autenticação de usuários, gerenciamento de dados de doações e integração com o banco de dados **MySQL**.

---

## Funcionalidades

- API REST para comunicação com o frontend (React)
- Cadastro e login de usuários
- Gerenciamento de doações
- Integração com banco de dados **MySQL**
- Rotas protegidas por autenticação

---

## Tecnologias Utilizadas

- **Node.js**
- **Express.js**
- **MySQL**

---

## Como Rodar Localmente

1. Clone o repositório:
   ```bash
   git clone <URL_DO_REPO_BACKEND>

2. Instale as dependências:
   ```bash
    npm install

3. Configure o arquivo .env na raiz do projeto:
    ```bash
    DB_HOST=localhost
    DB_USER=root
    DB_PASSWORD=
    DB_NAME=Projeto404

4. Inicie o servidor:
    ```bash
    npm start

  ou, em ambiente de desenvolvimento:

    ```bash
    npm run dev

#### Estrutura do Projeto

/routes → definição das rotas da API

.env → variáveis de ambiente

#### Status do Projeto
🚧 Em desenvolvimento

Novas funcionalidades serão adicionadas em breve!

#### Observações Acadêmicas
Este projeto foi desenvolvido como parte do projeto Lideranças Empáticas da FECAP, em colaboração com outros integrantes do grupo.
