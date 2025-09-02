📦 #PraevisioX

PraevisioX é uma plataforma de controle de estoque e vendas, desenvolvida para pequenas lojas, especialmente do nicho de roupas, que precisam de organização, controle e agilidade.
A plataforma integra o cadastro de produtos, registro de vendas, controle automático de estoque e fluxo de caixa, oferecendo uma visão clara e prática do negócio.

📝 Funcionalidades (MVP)
Cadastro e Usuários

Login e logout seguro.

Perfis: administrador (total) e caixa (restrito).

Sessões PHP para controlar acesso.

Produtos

Cadastro de produtos com variações (cor, tamanho, SKU).

Controle automático de estoque.

Alertas de produtos com estoque baixo.

Vendas (Caixa)

Registro rápido de vendas.

Seleção de produtos e quantidade.

Escolha de forma de pagamento:

Dinheiro

Pix (QR Code)

Cartão (simulação inicial)

Estoque atualizado automaticamente.

Registro de entrada no fluxo de caixa (cash_flow).

Relatórios

Vendas do dia, semana ou mês.

Produtos mais vendidos.

Produtos com estoque baixo.

🏗️ Arquitetura

Frontend: HTML5, CSS3, JS (responsivo).

Backend: PHP puro, sem frameworks.

Banco de Dados: MySQL / MariaDB.

Hospedagem: VPS, nuvem ou servidor local para testes.

🗄️ Banco de Dados (MVP)

Tabelas essenciais:

users → lojistas e funcionários.

products → produtos cadastrados.

sales → registro de vendas.

sale_items → itens vendidos em cada venda.

cash_flow → entradas e saídas de caixa.

Relações principais: users → sales → sale_items.
Estoque atualizado automaticamente a cada venda registrada.

⚙️ Tecnologias Utilizadas

PHP (puro)

MySQL / MariaDB

HTML5 / CSS3 / JavaScript

Bootstrap opcional para facilitar responsividade

Pix API (futuro) para pagamentos


