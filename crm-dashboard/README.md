# 📊 CRM Analytics Dashboard (Power BI)

## 🚀 Acesse o relatório interativo

🔗 https://app.powerbi.com/view?r=eyJrIjoiZDM4MDIwYWUtOTg3Yi00YThlLTlhMjEtNGI2MmMzYzgyOWZjIiwidCI6IjYzNTkyYTMzLWI4YjQtNDExNC1hZWQwLTI1MjE4ZjEwMWVjYyJ9


## 📌 Sobre o projeto

Dashboard completo de CRM desenvolvido para análise estratégica e operacional de vendas.

O projeto foi estruturado em múltiplas camadas analíticas, permitindo desde uma visão executiva até análises detalhadas por produto, cliente e projeções futuras.

> ⚠️ Dados públicos (Kaggle), utilizados apenas para fins de portfólio.


## 🎯 Problema de negócio

Equipes comerciais frequentemente enfrentam desafios como:

* Baixa visibilidade do funil de vendas
* Dificuldade em identificar gargalos no pipeline
* Falta de clareza sobre performance de vendedores
* Pouco entendimento sobre produtos e clientes mais rentáveis
* Ausência de previsibilidade de receita

Este dashboard foi desenvolvido para resolver esses pontos de forma integrada.


## 🧭 Estrutura do Dashboard

O relatório foi dividido em 5 camadas principais:


### 📊 1. Visão Executiva de Vendas

Visão consolidada do funil de vendas com foco estratégico.

**Principais métricas:**

* Receita fechada
* Pipeline ativo
* Taxa de conversão
* Ciclo médio de vendas
* Receita esperada

**Análises:**

* Distribuição do pipeline por estágio (Won, Lost, Engaging, Prospecting)
* Ranking dos top vendedores com indicadores de performance (win rate, ciclo, ticket médio)

👉 Objetivo: fornecer uma leitura rápida da saúde comercial.


### ⚙️ 2. Performance Comercial Detalhada

Camada operacional focada na análise por vendedor e produto.

**Principais métricas:**

* Oportunidades ativas
* Pipeline ativo
* Tempo médio de fechamento
* Win rate geral

**Análises:**

* Matriz de oportunidades por estágio e vendedor
* Receita vs pipeline por produto
* Win rate por representante
* Relação entre ticket médio e conversão

👉 Objetivo: identificar performance individual e eficiência do time.


### 📦 3. Análise de Produtos

Avaliação do desempenho comercial por produto.

**Principais métricas:**

* Receita por produto
* Pipeline ativo ponderado
* Ticket médio
* Win rate médio
* Produtos ativos

**Análises:**

* Funil por produto e estágio
* Ranking de produtos por receita
* Comparação entre pipeline e receita realizada
* Relação entre volume, ticket médio e conversão

👉 Objetivo: entender quais produtos geram mais valor e eficiência.


### 👥 4. Análise por Cliente / Conta

Visão focada no comportamento e valor dos clientes.

**Principais métricas:**

* Receita por cliente
* Pipeline ativo
* Win rate por cliente
* Ticket médio por cliente

**Análises:**

* Receita vs pipeline por cliente
* Ranking de clientes
* Distribuição de performance por conta
* Tabela detalhada com indicadores consolidados

👉 Objetivo: identificar clientes estratégicos e oportunidades de crescimento.


### 🔮 5. Forecast e Projeções

Camada preditiva com foco em planejamento.

**Principais métricas:**

* Receita atual
* Receita projetada (3 meses)
* Crescimento vs ano anterior
* Cobertura da meta

**Análises:**

* Receita real vs forecast mensal
* Receita acumulada vs projeção
* Desvio entre realizado e previsto

👉 Objetivo: antecipar resultados e apoiar tomada de decisão.


## 🏗️ Modelagem de Dados

Modelo estruturado com base em boas práticas de BI:

**Fato principal:**

* `sales_pipeline` (oportunidades)

**Dimensões:**

* `accounts` (clientes)
* `products` (produtos)
* `sales_teams` (vendedores)
* `DealStage` (etapas do funil)
* `dCalendario` (tempo)


## 📸 Preview do Dashboard

<img width="1538" height="857" alt="home" src="https://github.com/user-attachments/assets/e2484411-9914-4ff4-abd3-52bc94a5037b" /><img width="1494" height="858" alt="forecast" src="https://github.com/user-attachments/assets/5b1f70f3-da26-4be6-ac92-00d67355ad5c" />

## 👩‍💻 Observações

* O arquivo `.pbix` não foi disponibilizado
* Projeto desenvolvido para fins de portfólio

