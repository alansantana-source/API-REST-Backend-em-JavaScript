# 🚀 API REST – Backend em JavaScript

Projeto de API REST em desenvolvimento utilizando **JavaScript, Node.js e Express**, criado para praticar conceitos de backend e construção de aplicações reais.

## 🎯 Objetivo

Aplicar na prática os fundamentos de desenvolvimento backend:

* Criação de rotas REST
* Organização do projeto em camadas
* Uso de middlewares
* Integração com banco de dados
* Validação e tratamento de erros

Este projeto faz parte do meu processo de aprendizado e evolução como desenvolvedor.

---

## 🛠 Tecnologias utilizadas

* JavaScript (ES6+)
* Node.js
* Express
* Dotenv
* Nodemon
* Moongose
* Banco de dados (MongoDB)

---

## 📂 Estrutura atual

```
src/
 ├── controllers/   # Regras de negócio
 ├── routes/        # Definição das rotas
 ├── models/        # Modelos do banco
 ├── middlewares/   # Funções intermediárias
 └── server.js      # Inicialização da aplicação
```

---

## ▶ Como executar o projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/alansantana-source/API-REST-Backend-em-JavaScript.git
```

### 2. Instalar dependências

```bash
npm install express mongoose
npm install --save-dev nodemon
```

### 3. Configurar variáveis de ambiente

Criar arquivo `.env`:

```
PORT=3000
```

### 4. Iniciar o servidor

```bash
npm run dev
```

A API estará disponível em:

```
http://localhost:3000
```

---

## 🔀 Endpoints (em construção)

Exemplo do padrão utilizado:

* `GET /` – Teste inicial da API
* `POST /` – Envio de dados
* Demais rotas sendo implementadas

---

## ✅ O que já foi feito

* Configuração inicial do projeto
* Estruturação de pastas
* Configuração do Express
* Organização de rotas
* Ambiente com Nodemon

---

## 🚧 Próximos passos

* Implementar CRUD completo
* Conectar banco de dados
* Validação de dados
* Tratamento global de erros
* Autenticação JWT
* Documentação das rotas

---

## 🛠 Dependências do projeto

Atualmente o projeto utiliza:

- **Express** – criação e gerenciamento das rotas da API  
- **Mongoose** – modelagem e conexão com MongoDB  
- **Nodemon (dev)** – A ser adicionado

---

## 👨‍💻 Autor

**Alan Santana**

* GitHub: [https://github.com/alansantana-source](https://github.com/alansantana-source)

---

> Projeto em desenvolvimento com foco no aprendizado de backend e boas práticas.
