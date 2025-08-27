# 📊 Regressão Linear e Polinomial

Este repositório contém um estudo prático sobre **Regressão Linear** e **Regressão Polinomial** utilizando Python e um dataset de imóveis, com foco em avaliação de desempenho e seleção de variáveis.

## 📂 Estrutura do Projeto
- `Regressão_polinomial.ipynb`: Notebook principal com toda a análise.
- `imooveis.csv`: Base de dados utilizada.

## 🚀 Tecnologias Utilizadas
- Python 3.x
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Statsmodels

## 📊 Etapas do Projeto
1. **Exploração dos Dados (EDA)**  
   - Visualização inicial  
   - Estatísticas descritivas  
   - Tratamento de valores ausentes  

2. **Regressão Linear**  
   - Divisão treino/teste (holdout 50%)  
   - Cálculo do R² para treino e teste  
   - Análise de significância estatística via p-valor  
   - Interpretação dos coeficientes  

3. **Regressão Polinomial**  
   - Expansão de atributos com `PolynomialFeatures`  
   - Ajuste do grau do polinômio  
   - Cálculo do R² em treino e teste  
   - Verificação da diferença absoluta entre R² de treino e teste  

4. **Avaliação Final**  
   - Comparação entre os dois modelos  
   - Discussão sobre overfitting/underfitting  

## 📈 Resultados
- A **Regressão Linear** mostrou bom desempenho e interpretabilidade.  
- A **Regressão Polinomial**, apesar de aumentar a capacidade de ajuste, deve ser usada com cautela para evitar overfitting.  
- A diferença absoluta entre os R² de treino e teste foi controlada (< 0.2), garantindo maior generalização.  

## 📌 Conclusão
Este estudo demonstrou como a regressão linear e polinomial podem ser aplicadas para prever variáveis quantitativas. A escolha entre simplicidade (linear) e maior poder preditivo (polinomial) depende do contexto e da necessidade de interpretabilidade do modelo.

## 🔧 Como Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/jaoAprendiz/regressao-linear-polinomial.git
   ```
   
2. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

3. Abra o notebook no Jupyter:

   ```bash
   jupyter notebook regressao_polinomial.ipynb
   ```

## 📝 Licença

Este projeto está sob a licença MIT.
