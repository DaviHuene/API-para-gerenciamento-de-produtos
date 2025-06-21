# 🛍️ Store API

API para gerenciamento de produtos, construída com **FastAPI** e **MongoDB** (via `motor` e `pymongo`).

---

## 📦 Funcionalidades

- Criar produtos
- Listar todos os produtos
- Obter produto por ID
- Atualizar produto
- Deletar produto

---

## 🚀 Executando o Projeto

### 📋 Requisitos

- Python 3.11+
- MongoDB
- pip

---

## 🧪 Endpoints Disponíveis

| Método | Rota             | Descrição               |
|--------|------------------|-------------------------|
| GET    | `/products/`     | Listar todos os produtos |
| POST   | `/products/`     | Criar um novo produto    |
| GET    | `/products/{id}` | Buscar produto por ID    |
| PATCH  | `/products/{id}` | Atualizar produto        |
| DELETE | `/products/{id}` | Deletar produto          |

### ✅ Exemplo de objeto `ProductIn`

```json
{
  "name": "Notebook Lenovo",
  "description": "Ryzen 7, 16GB RAM, SSD 512GB",
  "price": 3899.90,
  "in_stock": true
}
```

---

## 🛠️ Tecnologias Utilizadas

- [FastAPI](https://fastapi.tiangolo.com/)
- [Motor (MongoDB Async)](https://motor.readthedocs.io/)
- [Pydantic](https://docs.pydantic.dev/)
- [Uvicorn](https://www.uvicorn.org/)

---
