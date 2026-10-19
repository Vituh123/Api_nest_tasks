# 🚀 Task Manager API (NestJS + PostgreSQL + TypeORM)

Uma API RESTful robusta e modular desenvolvida para o gerenciamento de tarefas, utilizando a arquitetura profissional do **NestJS**, **TypeScript**, **TypeORM** e **PostgreSQL** executado em ambiente containerizado com **Docker**.

Este projeto demonstra a implementação prática dos padrões recomendados de mercado para o desenvolvimento backend moderno.

---

## 🛠️ Tecnologias e Ferramentas

- **Framework:** [NestJS](https://nestjs.com/) (Node.js)
- **Linguagem:** [TypeScript](https://www.typescriptlang.org/)
- **ORM:** [TypeORM](https://typeorm.io/)
- **Banco de Dados:** [PostgreSQL](https://www.postgresql.org/)
- **Containerização:** [Docker](https://www.docker.com/) & Docker Compose
- **Testes de API:** Thunder Client / Postman

---

## 📐 Arquitetura do Projeto

O projeto segue a estrutura modular e fortemente tipada padrão do NestJS:

```text
src/
├── task/
│   ├── dto/
│   │   ├── create-task.dto.ts
│   │   └── update-task.dto.ts
│   ├── entities/
│   │   └── task.entity.ts
│   ├── task.controller.ts
│   ├── task.module.ts
│   └── task.service.ts
├── app.module.ts
└── main.ts
