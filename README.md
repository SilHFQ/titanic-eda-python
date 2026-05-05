# 📊 Análise Exploratória de Dados — Titanic

## 🎯 Objetivo
Este projeto tem como objetivo realizar uma análise exploratória de dados (EDA) para identificar padrões e fatores que influenciaram a sobrevivência dos passageiros do Titanic.

A análise busca extrair insights relevantes a partir dos dados, considerando variáveis como gênero, idade e classe social.

---

## 🛠️ Tecnologias utilizadas
- Python
- Pandas
- NumPy
- Matplotlib

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

- Mulheres apresentaram maior taxa de sobrevivência em relação aos homens  
- Passageiros da 1ª classe tiveram maior probabilidade de sobrevivência  
- Idade influenciou parcialmente as chances de sobrevivência  
- Fatores sociais e estruturais tiveram impacto direto no desfecho dos passageiros  

---

## 📈 Conclusão

A análise evidencia que fatores como gênero e classe social tiveram forte influência nas chances de sobrevivência, indicando que critérios de priorização e condições estruturais impactaram diretamente o desfecho da tragédia.

Este projeto reforça a importância da análise exploratória como etapa fundamental para compreensão de padrões em dados e apoio à tomada de decisão.

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
