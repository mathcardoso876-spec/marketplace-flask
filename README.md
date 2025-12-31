# Loja Web - Estilo Shopee/Mercado Livre

## Descrição
Uma aplicação web de e-commerce simples e completa feita com Flask (Python). Inclui cadastro/login, lista de produtos, carrinho, checkout fictício e admin para gerenciar produtos. 

## Requisitos
- Python 3.x
- Dependências: `pip install flask flask-sqlalchemy flask-login werkzeug`

## Instalação e Execução
1. Entre na pasta `loja_web`.
2. Rode `python init_db.py` para criar o DB e adicionar produtos/admin (usuário: admin, senha: admin123).
3. Rode `python app.py` para iniciar o servidor.
4. Acesse `http://127.0.0.1:5000/` no navegador.

## Funcionalidades
- **Home**: Lista de produtos com add ao carrinho.
- **Detalhes do Produto**: Ver descrição e adicionar.
- **Carrinho**: Ver itens, remover, total.
- **Checkout**: Simula compra e limpa carrinho.
- **Admin**: Adicionar/editar produtos (apenas para admin).
- **Autenticação**: Cadastro e login seguros.
