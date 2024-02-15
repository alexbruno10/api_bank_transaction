## 🏦 Descrição do projeto API Bank Transactions:

API desenvolvida em Node.js para realizar transações financeiras 

### 🛠️ Tecnologias utilizadas:

* Node.js
* Fastify
* Typescript
* Knex
* Zod
* Vitest
* Supertest
* SQLite

# ✏️ RF (Requisitos funcionais)

- [x] O usuário deve poder criar uma novo transação;
- [x] O usuário deve pode obter um resumo da sua conta;
- [x] O usuário deve poder listar todas transações que já ocorreram;
- [x] O usuário deve poder visualizar uma transação única;

# 💼 RN (Regras de negócio)

- [x] A transação pode ser do tipo crédito que somará ao valor total, ou débito que irá subtrair o valor;
- [x] Deve ser possível identificarmos o usuário entre as requisições;
- [x] O usuario só pode visualizar transações o qual ele criou;
