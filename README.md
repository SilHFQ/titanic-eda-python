# 📊 Análise Exploratória de Dados (EDA) — Titanic Dataset

## 🎯 Objetivo

Este projeto tem como objetivo realizar uma análise exploratória de dados (EDA) para identificar padrões e fatores que influenciaram a sobrevivência dos passageiros.

A análise busca extrair insights relevantes a partir dos dados, considerando variáveis como sexo, idade e classe social.

Dataset amplamente utilizado em estudos de ciência de dados e aprendizado estatístico.

---

## 🛠️ Tecnologias utilizadas

* Python (análise de dados)
* Pandas (manipulação de dados)
* NumPy (operações numéricas)
* Matplotlib (visualização de dados)

---

## 📂 Etapas do projeto

### 🔹 1. Coleta e carregamento de dados

Leitura do dataset utilizando Pandas e criação do DataFrame para análise.

### 🔹 2. Tratamento de dados

* Identificação de valores ausentes
* Preenchimento de dados:

  * Idade → mediana
  * Cabine → moda
* Remoção de registros com valores ausentes em Embarked

### 🔹 3. Limpeza e transformação

* Remoção de colunas não relevantes para análise
* Padronização e renomeação de variáveis
* Conversão de valores categóricos para melhor interpretação

### 🔹 4. Análise exploratória

* Distribuição de sobreviventes vs não sobreviventes
* Análise por sexo
* Análise por classe social
* Avaliação de idade e sua relação com sobrevivência

### 🔹 5. Visualização de dados

Criação de gráficos para facilitar a interpretação dos padrões identificados.

---

## 📊 Principais insights

* Mulheres apresentaram uma taxa de sobrevivência significativamente superior aos homens
* Passageiros da 1ª classe tiveram maior probabilidade de sobrevivência
* Passageiros mais jovens apresentaram maior taxa de sobrevivência
* A combinação entre classe social, faixa etária e sexo mostrou forte impacto nas chances de sobrevivência

---

## 📈 Conclusão

A análise evidencia que fatores como sexo, faixa etária e classe social tiveram forte influência nas chances de sobrevivência, refletindo padrões sociais e estruturais da época.

Os resultados reforçam como a análise exploratória de dados pode revelar relações relevantes entre variáveis e apoiar a compreensão de eventos complexos.

---

## 🚀 Como executar o projeto

1. Clone o repositório:

```bash
git clone https://github.com/SilHFQ/titanic-eda-python.git
```

2. Instale as dependências:

```bash
pip install pandas numpy matplotlib
```

3. Execute o notebook:

```bash
jupyter notebook
```
