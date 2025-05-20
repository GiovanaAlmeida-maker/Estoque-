# 📦 Sistema de Controle de Estoque com Flask

Este projeto é uma **API RESTful** construída com **Python** e **Flask**, que permite realizar o gerenciamento de um estoque simples, incluindo produtos, categorias, movimentações (entradas e saídas) e geração de relatórios.

---

## 🚀 Funcionalidades

### 📁 Categorias
- Listar categorias
- Criar nova categoria
- Editar categoria existente
- Deletar categoria

### 📦 Produtos
- Listar produtos
- Cadastrar novo produto
- Atualizar produto
- Remover produto

### 🔄 Movimentações
- Registrar **entrada** ou **saída** de produtos
- Atualização automática da quantidade em estoque

### 📊 Relatórios
- Estoque atual de todos os produtos
- Produtos com estoque baixo (menos de 10 unidades)
- Histórico de movimentações (com filtro de data)
- Produto mais vendido e produto menos vendido

---

## 🛠️ Tecnologias Utilizadas

- [Python 3](https://www.python.org/)
- [Flask](https://flask.palletsprojects.com/)
- [Flask SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/)
- [SQLite](https://www.sqlite.org/index.html)

---

## ▶️ Como Executar

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seuusuario/seu-repo.git
   cd seu-repo
