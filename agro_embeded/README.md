
# 🌱 Central de Performance — Operação Agrícola (Power BI + Embedded)

## 🚀 Acesse o relatório

🔗 https://app.powerbi.com/view?r=eyJrIjoiZTRkNDFkZWEtYTE2My00MzAyLWEwYmMtNmM5MDFmYzE1ODFiIiwidCI6IjYzNTkyYTMzLWI4YjQtNDExNC1hZWQwLTI1MjE4ZjEwMWVjYyJ9


## 📌 Sobre o projeto

Este projeto consiste na construção de uma **plataforma analítica para operações agrícolas**, combinando:

* Dashboard em Power BI
* Aplicação web com Flask
* Integração via Power BI Embedded

O objetivo é simular um cenário real de produto de dados, onde diferentes clientes (fazendas) acessam seus indicadores de forma personalizada.

> ⚠️ Dados fictícios utilizados apenas para fins de demonstração.

## 🧭 Estrutura do Dashboard

O relatório foi dividido em 3 pilares principais:

### 🌾 1. Aderência ao Planejamento

Análise do cumprimento do planejamento agrícola.

**Principais métricas:**

* Área planejada vs realizada
* % de aderência
* Desvio (hectares)

**Análises:**

* Comparação mensal entre planejado e realizado
* Evolução da aderência ao longo do tempo
* Desvio por cliente (fazenda)

👉 Objetivo: monitorar execução do planejamento.

### 🚜 2. Colheita

Avaliação da produtividade agrícola.

**Principais métricas:**

* Toneladas planejadas vs colhidas
* % de atingimento
* Desvio de produção

**Análises:**

* Produção por cultura (cana, milho, soja, algodão)
* Evolução mensal da colheita
* Desvio de produção ao longo do tempo

👉 Objetivo: medir eficiência produtiva.

### ⏱️ 3. Aproveitamento de Tempo

Análise da eficiência operacional.

**Principais métricas:**

* Horas planejadas vs realizadas
* % de atingimento
* Desvio de horas

**Análises:**

* Tendência de desvio operacional
* Distribuição de horas por operação
* Performance por fazenda

👉 Objetivo: otimizar uso de recursos.

## 🏗️ Modelagem de Dados

**Fato principal:**

* `fato_operacao`

**Dimensão:**

* `dim_clientes`

**Medidas principais:**

* % Aderência
* % Atingimento (Colheita)
* % Atingimento (Tempo)
* Desvio (ha, toneladas, horas)

---

## ⚙️ Arquitetura da Solução

Este projeto simula uma arquitetura de produto de dados:

### 🔹 Camada de Visualização

* Power BI (dashboards interativos)

### 🔹 Camada de Aplicação

* Aplicação web construída com Flask
* Renderização de páginas com embed do Power BI

### 🔹 Camada de Integração

* Uso de Power BI Embedded
* Filtro dinâmico por cliente via URL

## 🔗 Exemplo de uso (multi-cliente)

A aplicação permite acessar o relatório filtrado por cliente:

```bash id="a1lq9s"
http://localhost:5001/relatorio/terraf
```

👉 Cada cliente visualiza apenas seus próprios dados.

## 💡 Principais insights

* Identificação de desvios no planejamento
* Avaliação da produtividade por cultura
* Otimização do uso de tempo operacional
* Comparação de performance entre clientes

## 📸 Preview

<img width="1312" height="882" alt="app" src="https://github.com/user-attachments/assets/b8299455-56a1-4d5e-8df3-660fda1ae5ab" />


<img width="1332" height="890" alt="aderencia" src="https://github.com/user-attachments/assets/04747c2b-c5ae-40dc-b9a4-a013b84007a9" />


## 👩‍💻 Observações

* Código da aplicação não disponibilizado
* Projeto desenvolvido como prova de conceito (POC)
* Foco em arquitetura e integração de soluções analíticas
