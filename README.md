# 📊 Análise Exploratória de Dados (EDA) — Titanic Dataset

## 🎯 Objetivo

Este projeto tem como objetivo realizar uma Análise Exploratória de Dados (EDA) utilizando Python, com foco na identificação de padrões e fatores que influenciaram a sobrevivência dos passageiros do Titanic.

A análise considera variáveis como sexo, idade e classe social, buscando gerar insights a partir dos dados.

---

## 🛠️ Tecnologias utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

---

## 📂 Etapas do projeto

### 🔹 1. Coleta e carregamento de dados

Leitura do dataset e criação do DataFrame utilizando Pandas.

### 🔹 2. Tratamento de dados

* Identificação de valores ausentes
* Preenchimento de dados:

  * Idade → mediana
  * Cabine → moda
* Remoção de registros com valores ausentes em `Embarked`

### 🔹 3. Limpeza e transformação

* Remoção de colunas não relevantes
* Padronização de variáveis
* Ajuste de dados categóricos para análise

### 🔹 4. Análise exploratória

* Sobreviventes vs não sobreviventes
* Análise por sexo
* Análise por classe social
* Relação entre idade e sobrevivência

### 🔹 5. Visualização de dados

Criação de gráficos para apoiar a interpretação dos padrões identificados.

---

## 📊 Principais insights

* Mulheres apresentaram maior taxa de sobrevivência em relação aos homens
* Passageiros da 1ª classe tiveram maiores chances de sobrevivência
* Passageiros mais jovens apresentaram tendência de maior sobrevivência
* Classe social e sexo demonstraram forte influência nos resultados

---

## 📈 Conclusão

A análise demonstrou como fatores sociais e demográficos impactaram diretamente as chances de sobrevivência dos passageiros.

O projeto reforça a importância da análise exploratória na identificação de padrões e geração de insights relevantes para apoio à tomada de decisão baseada em dados.

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

Abra o arquivo `.ipynb` utilizando:

* Jupyter Notebook
* Google Colab

---
