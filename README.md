📊 Dashboard de Performance de Receita (SQL + Power BI)

Este projeto apresenta uma análise completa de receita e performance de negócio, utilizando SQL (PostgreSQL) para preparação dos dados e Power BI para construção do dashboard interativo.

O objetivo é demonstrar a capacidade de transformar dados brutos em insights estratégicos e recomendações de negócio, seguindo um fluxo próximo ao ambiente corporativo.

-----

🚀 Visão Geral

O projeto simula um cenário de e-commerce, onde foi realizada uma análise para entender:

Evolução da receita ao longo do tempo
Desempenho por categoria de produto
Produtos mais relevantes para o faturamento
Clientes com maior contribuição de receita
Indicadores gerais de performance

---
🧠 Etapas do Projeto
🔹 1. Modelagem e Estruturação de Dados (PostgreSQL)
Criação de tabelas relacionais (customers, orders, products, categories, order_items)
Definição de chaves primárias e estrangeiras
Organização dos dados em estrutura analítica

🔹 2. Análise com SQL
Uso de JOINs para integração de dados
Cálculo de métricas como receita, ticket médio e volume de vendas
Utilização de CTE (Common Table Expressions)
Aplicação de window functions (RANK) para análise de clientes

🔹 3. Criação de Views (camada analítica)
Foram criadas views para organizar e simplificar o consumo dos dados no Power BI:

vw_revenue_by_month
vw_revenue_by_category
vw_customer_revenue
vw_top_products

----
🔹 4. Dashboard no Power BI

Construção de um dashboard interativo com:

📌 KPIs:
Receita Total
Ticket Médio
Total de Clientes
📈 Visualizações:
Receita ao longo do tempo
Receita por categoria
Top produtos por receita
Clientes por valor gasto
🎛️ Filtros:
Cliente
Categoria

----
💡 Principais Insights
A receita está concentrada na categoria Eletrônicos, responsável pela maior parte do faturamento
Existe forte dependência de poucos clientes, com destaque para clientes de maior valor
O ticket médio elevado indica predominância de produtos de alto valor

----
🚀 Recomendações de Negócio
Priorizar investimentos em produtos da categoria Eletrônicos
Desenvolver estratégias de retenção para clientes de alto valor
Criar ações para impulsionar categorias com menor desempenho
-----
🛠️ Tecnologias Utilizadas
PostgreSQL
SQL
Power BI
DAX

----
🎯 Diferenciais do Projeto
Integração entre SQL e BI
Uso de boas práticas de modelagem e análise
Criação de camada analítica com views
Foco em data storytelling e tomada de decisão
Estrutura semelhante a projetos reais de negócio

----
📷 Preview do Dashboard

<img width="1418" height="793" alt="image" src="https://github.com/user-attachments/assets/d799583a-bb56-41a4-8bc9-eba41db2959b" />
