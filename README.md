# 📊 Análise de Cancelamento de Clientes (Churn Analysis)

Este projeto foi desenvolvido durante meus estudos em Python com foco em **Análise de Dados**.

O objetivo é analisar uma base de dados de clientes para entender os principais fatores que levam ao cancelamento de serviços e propor possíveis melhorias.

---

## 🚀 Tecnologias utilizadas

- Python
- Pandas
- Plotly
- Jupyter Notebook (VSCode)


## 📷 Exemplos de gráficos

![Gráfico de Cancelamento](imagens/grafico1.png)

![Gráfico de Ligações](imagens/grafico2.png)
---

## 📁 Sobre os dados

A base de dados contém informações de clientes, como:

- Idade
- Sexo
- Tempo como cliente
- Frequência de uso
- Ligações ao call center
- Dias de atraso
- Tipo de assinatura
- Duração do contrato
- Total gasto
- Última interação
- Cancelamento (0 = não, 1 = sim)

---

## 🧠 Etapas do projeto

### 1. Importação e limpeza de dados
- Leitura do arquivo CSV com Pandas
- Remoção de colunas desnecessárias
- Tratamento de valores nulos

### 2. Análise exploratória
- Cálculo da taxa de cancelamento
- Análise por tipo de contrato
- Agrupamento de dados com `groupby`

### 3. Análise gráfica
- Criação de gráficos com Plotly
- Identificação de padrões de cancelamento

### 4. Insights encontrados

- Clientes com contrato mensal apresentam alta taxa de cancelamento
- Clientes com muitos dias de atraso tendem a cancelar
- Alto número de ligações ao call center está relacionado ao cancelamento

---

## 📉 Resultados

- Taxa inicial de cancelamento: **56,7%**
- Após análises e filtros: **18,4%**

---

## 💡 Conclusão

A análise mostrou que é possível reduzir significativamente o cancelamento ao identificar padrões de comportamento dos clientes.

Esses insights podem ajudar empresas a tomar decisões mais estratégicas para retenção de clientes.

---

## 📌 Observação

Este projeto foi desenvolvido para fins de estudo e prática em análise de dados.
