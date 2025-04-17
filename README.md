# Segmentação de Clientes com RFM + K-means

## 📊 Análise de Segmentação em Plataforma de Delivery

Dashboard iterativa : https://analise-e-segmentacao-clientes.onrender.com/

Este projeto foi desenvolvido com o objetivo de analisar e segmentar usuários de uma plataforma de delivery (baseada na Wolt) utilizando a metodologia RFM (Recência, Frequência e Monetariedade) e o algoritmo de agrupamento K-means.

Trata-se de uma **pipeline completa de dados**, com foco em **comportamento de consumo**, **clusterização de perfis** e **criação de um dashboard interativo** com Dash e Plotly. O projeto organiza os clientes em grupos estratégicos para apoiar ações de retenção, fidelização e reativação.

---

## 📋 Visão Geral

Você já se perguntou:
- Quais tipos de clientes mais compram em uma plataforma de delivery?
- Como identificar usuários em risco ou inativos?
- É possível antecipar o abandono com base no comportamento de compra?

Neste projeto, buscamos responder essas perguntas com:
- **Coleta e limpeza de dados** reais simulados da base da Wolt.
- **Engenharia de atributos RFM**, associando recência, frequência e valor gasto.
- **Clusterização com K-means**, agrupando os usuários por padrões de comportamento.
- **Dashboard interativo**, visualizando segmentos e clusters com filtros dinâmicos.

---

## 🚀 Funcionalidades

- **Pré-processamento de dados:** Limpeza de colunas, tratamento de nulos e formatação de datas.
- **Cálculo de RFM:** Criação de scores para recência, frequência e monetariedade.
- **Segmentação comportamental:** Mapeamento de clientes em 10 segmentos RFM usando expressões regulares.
- **Classificação em 3 grandes grupos:** Ótimos clientes, Em risco, Inativos.
- **Clusterização com K-means:** Aplicação do método do cotovelo e agrupamento em 4 clusters otimizados.
- **Dashboard interativo com Dash:** Visualização de KPIs, gráficos de dispersão, segmentação e exportação CSV.

---

## 🔧 Tecnologias Utilizadas

- **Python**
- **pandas**
- **NumPy**
- **scikit-learn**
- **seaborn**
- **matplotlib**
- **Dash**
- **Plotly**
- **Yellowbrick**
- **Google Colab Notebook**

---

## 📂 Estrutura do Projeto

```plaintext
├── DADOS/                   # Base de dados da plataforma Wolt
├── RELATORIO E RASCUNHO/    # Documentos com análises, descrições e etapas do projeto
├── README.md                # Este arquivo        # Este arquivo
