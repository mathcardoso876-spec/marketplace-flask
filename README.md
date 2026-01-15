# Loja Virtual – E-commerce com Flask

Aplicação web de e-commerce desenvolvida em **Python** utilizando o framework **Flask**.
O projeto simula uma loja virtual completa, com autenticação de usuários, carrinho de compras,
checkout fictício e painel administrativo para gerenciamento de produtos.

Projeto desenvolvido com foco em **aprendizado prático de backend web** e organização de aplicações Flask.

---

## 🚀 Tecnologias Utilizadas
- Python 3
- Flask
- Flask-SQLAlchemy
- Flask-Login
- Werkzeug
- HTML / CSS
- SQLite
- Git

---

## ⚙️ Funcionalidades

### Usuário
- Cadastro e login de usuários
- Listagem de produtos
- Visualização de detalhes do produto
- Adição e remoção de itens no carrinho
- Simulação de checkout (finalização de compra)

### Admin
- Painel administrativo para gerenciamento de produtos
- Adição e edição de produtos
- Controle de acesso restrito ao administrador

---

## ▶️ Como executar o projeto localmente

### Pré-requisitos
- Python 3.x
- Pip

### Passo a passo

```bash
# Clone o repositório
git clone https://github.com/mathcardoso876-spec/NOME-DO-REPOSITORIO.git

# Acesse a pasta do projeto
cd loja_web

# Instale as dependências
pip install flask flask-sqlalchemy flask-login werkzeug

# Inicialize o banco de dados e crie usuário admin
python init_db.py

# Execute a aplicação
python app.py

