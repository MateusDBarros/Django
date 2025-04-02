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
GET /api/livros/
```
A API estará disponível em: http://127.0.0.1:5000/

### 🔹 Rodando o Frontend

Abra o arquivo index.html no navegador ou utilize um servidor local:
```bash
python -m http.server 8080  # Para rodar localmente
```
O frontend estará disponível em: http://127.0.0.1:8080/
