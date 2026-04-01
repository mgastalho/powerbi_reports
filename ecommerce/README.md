# 🛒 E-commerce Analytics Dashboard (Power BI)

## 🚀 Acesse o relatório interativo

🔗 https://app.powerbi.com/view?r=eyJrIjoiZWQ3ZmU2YjAtYTQ0Yy00MzgwLTg2YmItYTkwNTkyNmU5OWM2IiwidCI6IjYzNTkyYTMzLWI4YjQtNDExNC1hZWQwLTI1MjE4ZjEwMWVjYyJ9


## 📌 Sobre o projeto

Dashboard de análise de e-commerce desenvolvido com base no dataset público **Brazilian E-Commerce Public Dataset by Olist**.

O projeto tem como objetivo fornecer uma visão completa do negócio, cobrindo desde métricas financeiras até operação logística e experiência do cliente.

## 🎯 Problema de negócio

Empresas de e-commerce precisam lidar com múltiplas dimensões simultaneamente:

* Volume de pedidos vs receita
* Eficiência logística
* Satisfação do cliente
* Retenção e recorrência
* Distribuição geográfica

Este dashboard foi construído para integrar todas essas visões em uma única solução analítica.


## 🧭 Estrutura do Dashboard

O relatório foi organizado em 3 camadas principais:

### 📊 1. Visão Executiva

Camada estratégica com visão geral do negócio.

**Principais métricas:**

* Receita total
* Quantidade de pedidos
* Ticket médio
* Clientes ativos
* Novos clientes
* Taxa de cancelamento

**Análises:**

* Evolução mensal de receita vs volume de pedidos
* Ranking de categorias por receita
* Distribuição geográfica da receita

👉 Objetivo: monitorar o desempenho geral do e-commerce.

### ⚙️ 2. Desempenho Operacional & Experiência do Cliente

Foco na eficiência logística e satisfação do cliente.

**Principais métricas:**

* Prazo médio de entrega
* Entregas no prazo (%)
* Nota média das avaliações
* Pedidos com reclamação (%)

**Análises:**

* Volume de pedidos por mês
* Tempo médio de entrega por estado
* Distribuição das avaliações (1 a 5 estrelas)

👉 Objetivo: avaliar a qualidade da operação e impacto na experiência do cliente.

### 👥 3. Clientes & Relacionamento

Análise comportamental dos clientes.

**Principais métricas:**

* Clientes ativos
* Novos clientes
* Clientes recorrentes
* Taxa de cancelamento

**Análises:**

* Evolução de clientes ativos
* Novos clientes por período
* LTV médio por estado
* Distribuição geográfica dos clientes
* Frequência de compra por cliente

👉 Objetivo: entender retenção, valor e comportamento do cliente.


## 🏗️ Modelagem de Dados

Modelo baseado em múltiplas tabelas relacionais do dataset Olist.

**Principais entidades:**

* `orders`
* `order_items`
* `order_payments`
* `order_reviews`
* `customers`
* `products`
* `sellers`
* `geolocation`
* `dCalendario`

## 💡 Principais insights que o dashboard permite

* Relação entre volume de pedidos e receita
* Impacto do prazo de entrega na satisfação do cliente
* Identificação de categorias mais rentáveis
* Regiões com maior concentração de vendas
* Comportamento de recompra dos clientes
* Distribuição da qualidade das avaliações

## 📸 Preview do Dashboard


<img width="1691" height="856" alt="home" src="https://github.com/user-attachments/assets/fbe0c81c-9043-43fd-9391-790799607e51" />
<img width="1409" height="792" alt="visaoexecutiva" src="https://github.com/user-attachments/assets/c5b723ff-9fe4-4074-a78e-1bab916ac8b8" />

## 👩‍💻 Observações

* O arquivo `.pbix` não foi disponibilizado
* Dados públicos do Kaggle (Olist)
