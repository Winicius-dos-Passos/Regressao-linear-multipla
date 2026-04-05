# 🚗 Predição Automotiva com Regressão Linear: Simples e Múltipla

## 📖 Sobre o Projeto
Este projeto tem como objetivo demonstrar a aplicação prática de modelos fundamentais de Machine Learning e modelagem estatística: a **Regressão Linear Simples e a Regressão Linear Múltipla**. Utilizando a linguagem Python e o clássico conjunto de dados automotivos (`mt_cars.csv`), o projeto explora a relação entre as características técnicas de um veículo e o seu consumo de combustível (Milhas por Galão - `mpg`).

Este repositório foi criado como parte do desenvolvimento do meu portfólio em Ciência de Dados, focando em boas práticas de análise exploratória, modelagem de dados e avaliação comparativa de modelos.

## 🎯 Objetivos
* Analisar a distribuição e a correlação das variáveis presentes no conjunto de dados.
* Construir e treinar um modelo de Regressão Linear Simples utilizando a cilindrada (`disp`) como variável preditora.
* Construir um modelo de Regressão Linear Múltipla adicionando o número de cilindros (`cyl`) e a potência em cavalos (`hp`) para prever o consumo.
* Avaliar a performance dos algoritmos utilizando abordagens de Machine Learning (`scikit-learn`) e inferência estatística (`statsmodels`).
* Visualizar a reta de regressão e a dispersão dos dados de forma clara e intuitiva.

## 📂 Estrutura do Repositório
* `Regressão_Linear_Multipla.ipynb`: Notebook principal contendo todo o código, desde a importação e tratamento dos dados até a geração de gráficos, previsões isoladas e métricas dos modelos.
* `mt_cars.csv`: O conjunto de dados utilizado para treinar e testar os algoritmos.

## 🛠️ Tecnologias e Bibliotecas Utilizadas
* **Linguagem:** Python
* **Ambiente de Desenvolvimento:** Google Colab / Jupyter Notebook
* **Manipulação e Análise Numérica:** `pandas`, `numpy`
* **Visualização de Dados:** `matplotlib`
* **Machine Learning e Estatística:** `scikit-learn`, `statsmodels`

## 📊 Metodologia e Resultados
1. **Entendimento dos Dados:** Leitura do arquivo `mt_cars.csv` e exclusão de colunas irrelevantes para a modelagem. Definição da variável alvo (`mpg`).
2. **Análise de Correlação:** A matriz de correlação revelou uma forte associação linear negativa (-0.847) entre a cilindrada (`disp`) e o consumo do carro.
3. **Treinamento e Avaliação (Modelo Simples):** O primeiro modelo ajustou uma reta para prever o consumo usando apenas a cilindrada. O desempenho foi avaliado através do Coeficiente de Determinação (R²), obtendo a marca de **0.718** (71,8% da variância explicada).
4. **Treinamento e Avaliação (Modelo Múltiplo):** Para melhorar a capacidade preditiva, o segundo modelo incluiu os atributos de cilindros e potência. Essa regressão linear múltipla obteve um **R² de 0.767**, demonstrando que a adição de novas características técnicas aprimorou a precisão das previsões.

## 🚀 Como Executar o Projeto
1. Clone este repositório para a sua máquina local ou abra-o diretamente no Google Colab.
   ```bash
   git clone [https://github.com/Winicius-dos-Passos/Regressao-linear-multipla.git](https://github.com/Winicius-dos-Passos/Regressao-linear-multipla.git).

2. Certifique-se de que o arquivo 'mt_cars.csv' esteja no mesmo diretório que o Notebook (ou faça o upload do arquivo caso esteja utilizando o Colab).

3. Instale as dependências necessárias, caso esteja rodando localmente ('pip install pandas numpy matplotlib scikit-learn statsmodels').

4. Execute as células do 'Regressão_Linear_Multipla.ipynb' sequencialmente.
