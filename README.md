# Contexto - Introdução

Uma empresa está investindo mensalmente em plataformas de publicidade online,
como Youtube, Facebook e newspaper, para a prospecção de leads (pessoas
interessadas em seus produtos). A fim de acompanhar o desempenho desses
investimentos, a empresa registra todos os gastos com publicidade e todos os retornos
de vendas gerados a partir desses investimentos.
Para entender melhor a relação entre as variáveis presentes nesses registros e
identificar os fatores que mais impactam na geração de leads, a empresa solicitou a
análise de um especialista em dados. Além disso, a empresa busca criar um
modelo de predição de valores para estimar o retorno de vendas que pode ser gerado
a partir de um determinado investimento em publicidade.

# Sobre os dados

A tabela contém informações dos investimentos feitos pelo youtube, facebook,
newspaper e também a quantidade de cada.

Coluna        Descrição
youtube       Investimento youtube
facebook      Investimento facebook
newspaper     Investimento newspaper
sales         Valor das vendas

# Material Complementar

. Python Graph Gallery → Repositório com o passo a passo de como gerar gráficos
  utilizando as principais bibliotecas de Python
  
. SciKit Learn → Documentação com os principais modelos utilizados para
  clusterização

  # Etapas de Desenvolvimento

  01 - Análise Descritiva
  
  Esta etapa consiste em explorar os dados do dataset para compreender melhor as
  variáveis e identificar problemas. Para isso, é recomendado utilizar a biblioteca
  Pandas para importar e manipular os dados e realizar cálculos estatísticos, além das
  bibliotecas de visualização.
  É importante investigar o tipo de dado em cada variável, os valores e a distribuição dos
  dados. Ao final, espera-se ter uma interpretação sólida dos dados para avançar para a
  próxima etapa.

  Nessa etapa foi utilizada as bibliotecas pandas, junto com as bibliotecas de visualização de dados
  como as bibliotecas matplotlib e seaborn

  02 - Análise Exploratória
  
  Neta etapa iremos explorar mais a fundo os dados, identificando relações entre as
  variáveis e descobrindo padrões relevantes. Para isso, utilize técnicas de visualização 
  de dados e análises estatísticas, buscando possíveis correlações e
  identificando possíveis outliers ou desvios da normalidade.

  03 - Modelagem

  Para esta etapa, deve-se construir um modelo simples de regressão que permita a
  previsão solicitada pela empresa, com base nos dados disponíveis. Para isto, importe
  as bibliotecas necessárias e carregue os conjuntos de dados para iniciar a sua
  construção!

  Nessa Etapa utilizei técnicas de criação de um modelo de regressão simples utilizando
  a biblioteca sklearn

  04 - Calculando predição

  Para concluirmos a demanda solicitada pela empresa, iremos aplicar o modelo de
  regressão construído nas etapas anteriores para realizar as previsões de retorno de
  vendas que pode ser gerado a partir de um determinado investimento em publicidade e
  assim, poderemos apresentá-lo a empresa.
  Através dessas previsões, poderemos avaliar o impacto dos diferentes níveis de
  investimento em marketing nas vendas, auxiliando na tomada de decisões e na
  definição de estratégias de negócio.

  Realizei nessa etapa as técnicas de MSE e RMSE para calcular as metricas de vendas.


  # Bibliografia

  # MODELING TECHNIQUES
  
  Regressão Linear do SKLEARN https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html#sklearn.linear_model.LinearRegression
  
  Support Vector Regression do SKLEARN https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVR.html
  
  Decision Tree Regression do XGBoost https://xgboost.readthedocs.io/en/stable/python/python_api.html

  # TEST DESIGN
  
  Dataset split:
  Separação de TRAIN/TEST dataset padrão com 20% de massa para teste via medoto SKLEARN https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html

  # Métrica de avaliação do modelo:
  Validação da métrica MSE e RMSE para penalizar grandes erros de previsão. 
  
  Utilizando o método SKLEARN https://scikit- learn.org/stable/modules/generated/sklearn.metrics.root_mean_squared_error.html#sklearn.metrics.root_mean_squared_error
  
  
  
  

  
  
  
