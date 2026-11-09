# 📊 Análise de Vendas para E-commerce

Análise exploratória e visualização de dados de vendas de e-commerce desenvolvida em Python. O projeto simula o ciclo completo de análise de dados: desde a geração de registros de transações e pré-processamento até o levantamento de indicadores-chave de desempenho (KPIs) para apoio à tomada de decisão estratégica.

---

## 📌 Contexto do Negócio

Uma operação de e-commerce em expansão necessita de visibilidade clara sobre o desempenho de suas vendas para resolver gargalos estratégicos:

- **Gestão de Estoque:** Identificação dos itens de alta e baixa rotatividade.
- **Planejamento Financeiro:** Acompanhamento da evolução do faturamento ao longo do tempo e identificação de sazonalidades.
- **Estratégia Geográfica:** Mapeamento dos estados de maior representatividade na receita para otimização de frete e logística.
- **Categorização do Portfólio:** Entendimento de quais segmentos impulsionam o volume total de negócios.

---

## 🛠️ Tecnologias e Bibliotecas

- **Linguagem:** Python
- **Manipulação e Análise de Dados:** Pandas, NumPy
- **Visualização de Dados:** Matplotlib, Seaborn
- **Geração e Auxiliares:** `datetime`, `random`, `watermark`

---

## ⚙️ Fluxo de Trabalho e Engenharia de Dados

1. **Geração e Tratamento de Dados:** Criação de um dataset estruturado simulando transações comerciais contendo campos como `ID_Pedido`, `Data_Pedido`, `Nome_Produto`, `Categoria`, `Preco_Unitario`, `Quantidade`, `Cidade` e `Estado`.
2. **Engenharia de Atributos (Feature Engineering):**
   - Cálculo da receita total por transação (`Faturamento = Preco_Unitario * Quantidade`).
   - Mapeamento e estruturação temporal para análises agregadas (`Ano`, `Mês`, `Ano-Mês`).
   - Normalização e validação dos dados de localização geográfica.
3. **Análise Exploratória e Agrupamentos:** Agregações multidimensionais por produto, categoria, estado e período temporal para responder às hipóteses de negócio.
4. **Visualização de Dados e Comunicação Executiva:** Construção e estilização das quatro análises visuais chave (Top 10 Produtos, Evolução Temporal, Faturamento por Estado e Faturamento por Categoria em escala K) para facilitar a interpretação dos resultados.

---

## 📊 Principais Visualizações

O projeto conta com quatro análises visuais focadas em respostas diretas para a tomada de decisão:

- **Top 10 Produtos Mais Vendidos:** Gráfico de barras horizontais detalhando os itens com maior volume físico de vendas para apoio ao controle de estoque.
- **Evolução do Faturamento Mensal:** Gráfico de linha temporal com marcadores demonstrando a tendência de receita ao longo dos meses e comportamento das vendas.
- **Faturamento por Estado:** Gráfico de barras destacando a distribuição regional da receita e os principais polos de desempenho.
- **Faturamento por Categoria:** Gráfico de barras com formatação personalizada no eixo de valores (escala em milhares - K) para facilitar a leitura executiva.

---

## 💡 Insights Executivos

- **Concentração de Receita:** A análise por categoria permite identificar rapidamente quais linhas de produto concentram maior margem e faturamento, auxiliando na alocação de orçamento de marketing.
- **Sazonalidade:** A curva de evolução mensal destaca períodos de pico e vale, fundamentais para o planejamento de compras prévio junto a fornecedores.
- **Desempenho Regional:** A separação por estado fornece clareza para negociações de contratos operacionais e centros de distribuição regionais.

---

## 🚀 Status do Projeto

✅ **Concluído** — Pipeline de dados sintéticos, limpeza, engenharia de atributos, análises exploratórias e visualizações via Matplotlib/Seaborn devidamente integrados e documentados.
