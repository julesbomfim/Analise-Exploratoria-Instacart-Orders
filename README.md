# 🛒 Projeto de Análise Exploratória – Instacart Orders

Este projeto faz parte do **Sprint 3 – Bootcamp Data Analyst (TripleTen)** e tem como objetivo aplicar técnicas de **Análise Exploratória de Dados (AED)** usando o conjunto de dados da **Instacart**, uma plataforma de delivery de supermercado.

---

## 📌 Objetivo do Projeto
- Realizar **limpeza e pré-processamento** dos dados.  
- Explorar os **hábitos de compra dos clientes** por meio de estatísticas e visualizações.  
- Responder a perguntas de negócio sobre frequência de pedidos, produtos mais vendidos e comportamento de clientes em diferentes dias/horas.  

---

## 🗂️ Conjunto de Dados
O projeto utiliza 5 arquivos CSV:

- **instacart_orders.csv** → informações sobre pedidos  
- **products.csv** → catálogo de produtos  
- **order_products.csv** → relação entre pedidos e produtos  
- **aisles.csv** → categorias de corredores do supermercado  
- **departments.csv** → departamentos de produtos  

---

## 📊 Etapas do Projeto

### 1. Visão Geral dos Dados
- Leitura e inspeção das tabelas.  
- Ajustes na importação (`pd.read_csv()` com parâmetros específicos).  

### 2. Pré-processamento
- Correção de tipos de dados.  
- Tratamento de valores ausentes.  
- Remoção de duplicados.  
- Documentação das decisões tomadas no tratamento.  

### 3. Análise Exploratória de Dados (AED)

**Parte A (obrigatória):**
- Distribuição de pedidos por **hora do dia**.  
- Pedidos por **dia da semana**.  
- Tempo médio entre pedidos.  

**Parte B (obrigatória):**
- Comparação da distribuição de pedidos entre **quarta-feira** e **sábado**.  
- Distribuição do número de pedidos por cliente.  
- Top 20 produtos mais comprados.  

**Parte C (opcional – necessário concluir pelo menos 2):**
- Número médio de itens por pedido.  
- Top 20 itens mais frequentemente **recomprados**.  
- Proporção de pedidos repetidos por produto.  
- Proporção de produtos repetidos por cliente.  
- Top 20 itens mais frequentemente adicionados primeiro ao carrinho.  

---

## 🛠️ Tecnologias Utilizadas
- **Python**  
- **Pandas**  
- **Matplotlib** / **Seaborn**  
- **Jupyter Notebook**  

---

## 📈 Exemplos de Análises
- Gráficos de distribuição de compras por hora/dia.  
- Histogramas comparativos (quarta vs sábado).  
- Ranking de produtos mais comprados.  
- Métricas sobre pedidos repetidos.  

---

## ✅ Conclusões
Este estudo permitiu:
- Identificar padrões de comportamento de compra por horário e dia da semana.  
- Observar a recorrência de pedidos e produtos mais populares.  
- Fornecer insights úteis para estratégias de **marketing e logística** em e-commerce de supermercados.  

---

## 🚀 Como Executar
1. Clone este repositório:  
   ```bash
   git clone https://github.com/SEU-USUARIO/nome-do-repositorio.git
