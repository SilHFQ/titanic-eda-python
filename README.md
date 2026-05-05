# 📊 Análise Exploratória de Dados (EDA) — Titanic Dataset

## 🎯 Objetivo
Este projeto tem como objetivo realizar uma análise exploratória de dados (EDA) para Identificar padrões e fatores que influenciaram a sobrevivência dos passageiros, utilizando análise exploratória de dados para apoiar interpretações baseadas em evidências.

A análise busca extrair insights relevantes a partir dos dados, considerando variáveis como gênero, idade e classe social.

---

Dataset amplamente utilizado em estudos de ciência de dados e aprendizado estatístico.

---

## 🛠️ Tecnologias utilizadas
- Python (análise de dados)
- Pandas (manipulação de dados)
- NumPy (operações numéricas)
- Matplotlib (visualização de dados)

---

## 📂 Etapas do projeto

### 🔹 1. Coleta e carregamento de dados
Leitura do dataset utilizando Pandas e criação do DataFrame para análise.

### 🔹 2. Tratamento de dados
- Identificação de valores ausentes
- Preenchimento de dados:
  - Idade → mediana
  - Cabine → moda
- Remoção de registros com dados irrelevantes (Embarked)

### 🔹 3. Limpeza e transformação
- Remoção de colunas não relevantes para análise
- Padronização e renomeação de variáveis
- Conversão de valores categóricos para melhor interpretação

### 🔹 4. Análise exploratória
- Distribuição de sobreviventes vs não sobreviventes
- Análise por gênero
- Análise por classe social
- Avaliação de idade e sua relação com sobrevivência

### 🔹 5. Visualização de dados
Criação de gráficos para facilitar a interpretação dos padrões identificados.

---

## 📊 Principais insights

- Mulheres apresentaram uma taxa de sobrevivência significativamente superior aos homens, indicando priorização no resgate
- Passageiros da 1ª classe tiveram maior probabilidade de sobrevivência, sugerindo influência de fatores socioeconômicos
- Passageiros mais jovens apresentaram maior taxa de sobrevivência em comparação com faixas etárias mais elevadas
- A combinação entre classe social e gênero mostrou forte impacto nas chances de sobrevivência

---

## 📈 Conclusão

A análise evidencia que fatores como gênero e classe social tiveram forte influência nas chances de sobrevivência, refletindo padrões sociais e estruturais da época.

Os resultados reforçam como a análise exploratória de dados pode revelar relações relevantes entre variáveis e apoiar a compreensão de eventos complexos, mesmo em cenários históricos.

---

## 🚀 Como executar o projeto

### 1. Clone o repositório
```bash
git clone https://github.com/SilHFQ/titanic-eda-python.git
```

### 2. Instale as dependências
```bash
pip install pandas numpy matplotlib
```

### 3. Execute o notebook
```bash
jupyter notebook
```
