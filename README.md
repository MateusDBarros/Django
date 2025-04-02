# 📚 API CRUD de Livros com Django

✨ Descrição

## ✨ Descrição

Este projeto é uma API RESTful desenvolvida com Django e Django REST Framework (DRF). Ele permite realizar operações CRUD (Create, Read, Update, Delete) para gerenciar um catálogo de livros. Criado para fins de estudo, este sistema demonstra a implementação de APIs com Django.

##  Tecnologias Utilizadas

### Backend: Django

### Banco de Dados: SQLite

## 🔧 Instalação e Configuração

Antes de rodar o projeto, siga os passos abaixo para configurar o ambiente:

## 1️⃣ Clonar o repositório

```bash
git clone https://github.com/MateusDBarros/crud-api-livros.git
cd crud-api-livros
```

## 2️⃣ Criar e ativar um ambiente virtual (opcional, mas recomendado)
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate    # Windows
```

## 3️⃣ Instalar as dependências
```bash
pip install -r requirements.txt
```

## 4️⃣ Configurar o banco de dados

Por padrão, o projeto usa SQLite, mas pode ser configurado para PostgreSQL editando settings.py:

## 5️⃣ Executar as migrações do banco
```bash
python manage.py migrate
```

## 📡 Endpoints da API

### 🔹  Listar todos os livros (GET)
```bash
GET /blogspot/
```

### 🔹 Criar um novo livro (POST)
```bash
POST /blogspot/
{
    "title": "Dom Quixote",
    "content": "Livro por Miguel de Cervantes",
    "published": 1605
}
```

### 🔹  Buscar um livro especifico (GET)
```bash
GET /blogspot/1/
```

### 🔹 Atualizar um livro (PUT)
```bash
PUT /blogspot/1/
{
   "title": "Dom Quixote",
    "content": "Livro por Miguel de Cervantes",
    "published": 1615
}
```
### 🔹   Deletar um livro (DELETE)
```bash
DELETE /blogspot/1/
```
