# 🚀 Task Manager API

API RESTful para gerenciamento de tarefas desenvolvida com NestJS, TypeScript, TypeORM e PostgreSQL (Docker).

## 🛠️ Tecnologias
- **Framework:** NestJS + TypeScript
- **Banco de Dados:** PostgreSQL (via Docker)
- **ORM:** TypeORM

## 📌 Endpoints da API (CRUD)
- `POST /task` - Cria uma nova tarefa
- `GET /task` - Lista todas as tarefas
- `GET /task/:id` - Busca tarefa por ID
- `PATCH /task/:id` - Atualiza uma tarefa
- `DELETE /task/:id` - Remove uma tarefa

## ⚙️ Como Executar
1. Subir o banco de dados: `docker compose up -d`
2. Instalar dependências: `npm install`
3. Iniciar o projeto: `npm run start:dev`

Feito por [Vitor](https://github.com/Vituh123)
