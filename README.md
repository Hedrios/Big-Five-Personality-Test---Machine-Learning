# **Big Five Personality Test - Machine Learning**

Este projeto realiza uma análise exploratória dos traços de personalidade com base no modelo OCEAN (Openness, Conscientiousness, Extraversion, Agreeableness, Neuroticism), utilizando técnicas de Machine Learning para identificar padrões e agrupamentos de personalidade.

## **Objetivo**

O objetivo principal do projeto é aplicar algoritmos de clustering, como K-Means e DBSCAN, para descobrir padrões entre os diferentes traços de personalidade dos participantes de um teste. Além disso, o projeto explora a utilização da Análise de Componentes Principais (PCA) para otimizar a separação dos clusters e melhorar a visualização dos dados.

## **Estrutura do Projeto**

## **1. Contexto**
   
Neste item, é descrito o objetivo do projeto e a importância de analisar os traços de personalidade com base no modelo OCEAN.

## **2. Pacotes e Bibliotecas**

Aqui, são listadas as bibliotecas utilizadas no projeto, como numpy, pandas, matplotlib, seaborn, scikit-learn, e gradio. Cada uma delas é brevemente descrita em termos de seu papel no projeto.

## *3. Exploração de Dados*

### **3.1 Coleta** 

Download e carregamento dos dados em um DataFrame do pandas.

### *3.2 Limpeza e Preparação dos Dados*

Remoção de colunas irrelevantes e filtragem de registros inválidos.

### *3.3 Análise Estatística* 

Cálculo de estatísticas descritivas para entender a distribuição dos dados.

## *4. Manipulação de Dados*
   
### 4.1 Criação de Clusters

Aplicação do algoritmo K-Means para agrupar os dados em clusters.

### 4.2 Refinamento dos Clusters

#### 4.2.1 Análise de Distribuição de Clusters

Verificação da distribuição dos dados entre os clusters.

#### 4.2.2 Otimização dos Clusters com PCA

Redução da dimensionalidade com PCA para melhorar a separação dos clusters.

### 4.3 Análise de Outliers

Detecção e remoção de outliers usando Isolation Forest antes de reaplicar o K-Means.

### 4.4 Análise Comparativa com Outros Algoritmos de Clustering: Comparação entre K-Means e DBSCAN.

## 5. Análise Gráfica
   
### 5.1 Visualização dos Grupos

Gráficos mostrando a média dos traços de personalidade por cluster.

## 5.2 Visualização dos Clusters após PCA

Visualização dos clusters em um espaço bidimensional após PCA.

## 5.3 Visualização da Distribuição dos Clusters

Análise da distribuição dos dados em cada cluster.

## 5.4 Comparação dos Clusters K-Means e DBSCAN

Comparação gráfica dos clusters gerados por K-Means e DBSCAN.

## 6. Conclusão
   
Resumo dos insights obtidos e sugestões para trabalhos futuros, como explorar outros algoritmos de clustering e analisar mais profundamente os outliers.

# Como Executar o Projeto

## 1. Clone o Repositório

git clone [https://github.com/Hedrios/Big-Five-Personality-Test---Machine-Learning.git](https://github.com/Hedrios/Big-Five-Personality-Test---Machine-Learning.git)

## 2. Instale as Dependências

Certifique-se de ter o Python instalado e execute:

pip install -r requirements.txt

## 3. Execute o Projeto

Utilize um ambiente como Jupyter Notebook ou Google Colab para executar as células de código no notebook.

# Dados

Os dados utilizados neste projeto foram obtidos a partir de um teste de personalidade disponível publicamente. Os dados são carregados no formato CSV e processados para análise.


# Resultados e Insights

Os principais insights obtidos incluem a identificação de padrões claros de personalidade, com grupos bem definidos após a aplicação do PCA e dos algoritmos de clustering. A análise também destacou a importância de tratar outliers para garantir a precisão dos resultados.

# Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests para melhorar o projeto.






