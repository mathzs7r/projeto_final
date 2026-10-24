# projeto_final — API de Clientes (Express + MySQL + bcrypt)

API REST de cadastro de clientes com senha criptografada (bcrypt) e banco MySQL.

## Stack

- Node.js + Express
- MySQL (`mysql2` pool em `db.js`)
- bcrypt para hash de senha

## Rotas

| Método | Rota | Descrição |
|--------|------|-----------|
| POST | `/cliente` | Cadastrar (senha hasheada) |
| GET | `/cliente` | Listar |
| GET | `/cliente/:id` | Buscar por ID |
| PATCH | `/cliente/:id` | Atualizar |
| DELETE | `/cliente/:id` | Excluir |

## Como rodar

```bash
npm install
# configure a conexão em db.js
node index.js
# API em http://localhost:3000
```

## Autor

[mathzs7r](https://github.com/mathzs7r)
