# 📊 Análise de Salários na Área de Dados  
### Imersão Dados Python II — Alura

Este repositório contém os projetos desenvolvidos durante a **Imersão Dados com Python II da Alura**.  
O projeto representa uma jornada completa em **Ciência de Dados**, desde a **Análise Exploratória de Dados (EDA)** até a criação de um **Dashboard interativo** para exploração de métricas salariais globais na área de dados.

---

## 🎯 Objetivo do Projeto

O objetivo principal foi analisar as **tendências salariais do mercado de dados em escala global**, possibilitando a identificação de:

- **Impacto da Experiência:** Como a senioridade (Entry, Mid, Senior, Lead) afeta a remuneração  
- **Diversidade de Cargos:** Quais funções possuem as maiores médias salariais (USD)  
- **Distribuição Geográfica:** Onde estão as melhores oportunidades para Cientistas de Dados  
- **Modelo de Trabalho:** Proporção entre trabalho remoto, presencial e híbrido  

---

## 💻 Estrutura do Projeto

O projeto está dividido em **duas etapas principais**:

### 1️⃣ Análise Exploratória (Google Colab)

Etapa realizada durante as aulas da imersão, com foco em:

- Limpeza e tratamento de dados  
- Análise estatística  
- Visualizações exploratórias  

📌 **Notebook:**  
👉 *[Google Colab – Análise Exploratória](https://github.com/jerfzz/imersao-dados-python-alura/blob/main/Imers%C3%A3o_em_Python.ipynb)*

---

### 2️⃣ Dashboard Interativo (Streamlit)

Aplicação web desenvolvida para permitir a exploração dinâmica dos dados por meio de filtros interativos.

**Funcionalidades:**
- Filtros por **Ano**, **Senioridade**, **Tipo de Contrato** e **Tamanho da Empresa**
- **KPIs dinâmicos** (Média Salarial, Salário Máximo, Frequência)
- Gráfico de barras com **Top 10 cargos**
- **Mapa-múndi interativo** com salários de Data Scientists

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Python 3.9+  
- **Manipulação de Dados:** Pandas  
- **Visualização:** Plotly Express (gráficos interativos e mapas choropleth)  
- **Interface Web:** Streamlit  

---

## 🚀 Como Executar o Dashboard Localmente

Siga os passos abaixo para rodar o dashboard em sua máquina:

### 1️⃣ Clone o repositório
```bash
git clone https://github.com/jerfzz/imersao-dados-python-alura.git
````

### 2️⃣ Instale as dependências

```bash
pip install streamlit pandas plotly
```

### 3️⃣ Execute a aplicação

```bash
streamlit run app.py
```

---

## 📂 Organização de Arquivos

* `app.py` — Código principal da aplicação Streamlit
* `dados-imersao-final.csv` — Dataset processado utilizado nas visualizações
* `Imersao_Dados_Colab.ipynb` — Notebook com a análise exploratória inicial

---

## 👤 Autor

**Jerfeson Silva Santos**

* 🔗 *[LinkedIn](https://www.linkedin.com/in/jerfss/)*
* 💻 *[GitHub / Portfólio](https://github.com/jerfzz?tab=repositories)*

---

📌 *Este projeto foi desenvolvido com fins educacionais durante a **Imersão Dados Python II da Alura***.
