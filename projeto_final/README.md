# Projeto Final – Programação em Python para Data Science (SENAI)

Este repositório contém o **projeto final** desenvolvido ao término do curso  
**"Programação em Python para Data Science"** do SENAI.

O objetivo deste projeto é aplicar, de forma integrada, os conceitos estudados durante o curso, desde a importação e tratamento dos dados até a análise exploratória e apresentação de insights.

---

## 🎯 Objetivo do projeto

Este notebook foi desenvolvido para analisar dados de preços de carros, focando especificamente em veículos do ano de 2010, e para identificar padrões e tendências de mercado. As etapas realizadas e os insights gerados são detalhados a seguir:

---

## 📂 Dados e metadados

O projeto utiliza um conjunto de dados com as seguintes características:

- **Formato dos arquivos:** `.csv`  
- **Quantidade de registros:** 558.837  
- **Quantidade de variáveis/colunas:** 16 colunas  
- **Período coberto:** 2003 - 2014 
- **Principais campos:**  
  - `make`, `model`, `body`, `seller`, `color`, `sellingprice`  
- **Origem dos dados:** Kaggle

---

## 🧩 Metodologia e etapas do notebook

O fluxo do projeto no notebook segue as seguintes etapas:

1. **Importação de bibliotecas e dados**
   - Importação de `pandas`, `numpy`, `matplotlib`, [`seaborn`].
   - Carregamento dos arquivos de dados por meio de funções como `read_csv`/`read_excel`.

2. **Exploração inicial (EDA básica)**
   - Inspeção de estrutura com `.head()`, `.info()`, `.describe()`.
   - Entendimento de tipos de dados e distribuição inicial das variáveis.

3. **Limpeza e preparação dos dados**
   - Tratamento de valores ausentes (`.isna()`, `.fillna()`, `.dropna()`).
   - Ajustes de tipos (datas, numéricos, categorias).
   - Padronização de textos, remoção de duplicados e outliers (quando necessário).

4. **Transformações e enriquecimento**
   - Criação de novas variáveis/colunas derivadas (ex.: receita total, faixas, indicadores).
   - Agrupamentos e agregações com `.groupby()` e `.agg()`.
   - Junção de tabelas e arquivos, se aplicável, com `.merge()`.

5. **Análise Exploratória de Dados (EDA) aprofundada**
   - Geração de tabelas resumo por dimensão (tempo, categoria, região, etc.).
   - Criação de gráficos (linha, barras, pizza, histogramas, boxplots, etc.).
   - Identificação de tendências, comparações e correlações relevantes.

6. **Conclusões e insights**
   - Síntese dos principais achados.
   - Interpretação dos resultados sob uma ótica de negócio.
   - Recomendações e próximos passos.

---

## 🛠️ Funções, métodos e técnicas utilizadas

Neste projeto final, foram utilizados diversos recursos de programação em Python, entre eles:

- **Funções personalizadas** para:
  - Automatizar tarefas de limpeza.
  - Reaplicar transformações em múltiplos conjuntos de dados.

- **Principais métodos do `pandas`:**
  - Leitura: `read_csv`, `read_excel`
  - Inspeção: `.head()`, `.tail()`, `.info()`, `.describe()`
  - Filtragem e seleção: `loc`, `iloc`, filtros booleanos
  - Agrupamentos: `.groupby()`, `.agg()`
  - Junções: `.merge()`, `.join()`
  - Tratamento de nulos: `.isna()`, `.fillna()`, `.dropna()`

- **Visualização de dados:**
  - Gráficos com `matplotlib`/[`seaborn`]
  - Customização de rótulos, títulos e cores para melhor comunicação visual

---

## ▶️ Como executar os notebooks

1. Faça o clone deste repositório:
   ```bash
   git clone https://github.com/rodrigo-sza-almeida/curso_python_data_science_senai/tree/main/projeto_final.git

2. Instale as dependências necessárias (se estiver usando ambiente local com pip):
   
   pip install -r requirements.txt

4. Abra os notebooks:
5. 
   - Usando Jupyter Notebook:
     
     jupyter notebook

   - Ou carregando os arquivos diretamente no Google Colab.

📊 Resultados e insights

Através da análise, os seguintes insights foram gerados para o ano de 2010:

- Top 5 Marcas de Veículos Mais Vendidas: Identificou-se as marcas de veículos com maior volume de vendas, destacando as preferências do mercado.
  
- Top 5 Tipos de Carroceria Mais Vendidos: Foram apurados os tipos de carroceria mais populares, como 'sedan' e 'SUV', refletindo a demanda dos consumidores.
  
- Top 5 Financiadoras com Mais Financiamentos: Foram listadas as instituições financeiras que mais atuaram no financiamento de veículos, revelando os principais players nesse segmento de mercado.

🔮 Próximos passos
Algumas possíveis extensões e melhorias:

Inclusão de modelos de machine learning para previsão ou classificação.
Criação de dashboards interativos em ferramentas como Power BI, Streamlit ou Dash.
Uso de novas fontes de dados para enriquecer a análise.


📬 Contato

LinkedIn: [[LinkedIn de Rodrigo de Souza](https://www.linkedin.com/in/rodrigo-de-souza-almeida/)]
GitHub: [[Gihub de Rodrigo de Souza](https://github.com/rodrigo-sza-almeida)]

Ficarei feliz em receber feedbacks, sugestões e conexões! 😊



