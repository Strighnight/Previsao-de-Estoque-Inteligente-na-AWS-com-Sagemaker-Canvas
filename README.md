# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao projeto para prever a demanda de estoque usando AWS SageMaker Canvas. Inclui coleta e pré-processamento de dados, treinamento e validação de modelos de machine learning, previsões em tempo real e dashboards para visualização dos resultados. Otimize seu inventário e reduza custos de excesso ou falta de produtos.


## 🎯 Objetivos Deste Projeto

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

- Construir um DataSet do Zero.
- Construir e Treinar o modelo criado no SageMaker Canvas.
- Analisar as métricas de performance do modelo.
- Prever modelo treinado para fazer previsões de estoque.


## 🚀 Passo a Passo

### 1. Selecionar Dataset

-   Utilizando a versão mais recente do Chat GPT(GPT-4o), solicitei que fosse feito um DataSet em CSV com os dados a serem análisados.
-   Como havia feito o Fork do diretório da DIO e resolvi fazer meu próprio CSV, upei meu arquivo aqui no Git com nome de "previsao_estoque_small.csv".
-   Upei meu dataset no SageMaker Canvas.

### 2. Construir/Treinar

-   No SageMaker Canvas, importei meu dataset, fiz com apenas 25 itens.
-   Configurei coluna alvo para "Preço de Venda" e o modelo para "Estoque".
-   Configurei a previsão para 2 dias.
-   Usei as sugestões propostas pelo proprio SageMaker Canvas pra ajustar meus dados.
-   Feito as configurações iniciei o treinamento do modelo, como meu modelo foi apenas pra fins didáticos, utilizei o "Quick Build".

### 3. Analisar

-   Após o treinamento, examine as métricas de performance do modelo, observando os seguintes resultados Avg. wQL - 1.000, MAPE - 1.000, WAPE - 1.000, RMSE - 12.337, MASE - 0.008, tendo isso em vista, resume -se que o modelo poderia ser mais eficiente, uma vez que quanto mais perto de 0 essas métricas, mais precisas seriam.
-   Foi analisado também como as promoções impactaram no estoque.


### 4. Prever

-   Use o modelo treinado para fazer previsões de estoque.
-   Exporte os resultados e analise as previsões geradas.
-   Documente suas conclusões e qualquer insight obtido a partir das previsões.


### 5. Conclusões
