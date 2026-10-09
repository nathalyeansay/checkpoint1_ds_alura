Sobre o repositório:
esse repositorio contém:
dataset original: 'synthetic_coffee_health_10000(in).csv
notebook do projeto para rodar no colab: 'checkpoint1_alura_data_science.ipynb'
dataset ajustado de treino e teste: 'X_teste.csv', 'X_treino.csv', 'y_teste.csv', 'y_treino.csv'
melhor modelo salvo: 'modelo_logistico.pkl' 
scaler: 'meu_scaler.pkl'



# checkpoint1_ds_alura
projeto 1 alura

objetivo do projeto:
Uma empresa contratou você para analisar como o consumo de café influencia a qualidade do sono dos clientes.
O projeto é multiplataforma e pode ser executado tanto no Google Colab quanto no Jupyter Notebook local.

Você precisará ter instalados:

Python 3.8 ou superior
Bibliotecas: pandas, numpy, matplotlib, seaborn, scikit-learn
Além disso, baixe o dataset synthetic_coffee_health_10000, que será utilizado ao longo do projeto.

Dicionário de dados:
Este dataset contém informações sobre participantes de uma pesquisa que relaciona consumo de café, hábitos de sono e condições de saúde.

Modelo preditivo:
O time deseja prever a qualidade do sono (Sleep_Quality) com base nos hábitos e características dos clientes.
Nosso último passo será preparar os dados e implementar modelos de classificação.

A atividade:
Faça o pré-processamento dos dados:

Remova ou trate colunas irrelevantes.
Aplique codificação em variáveis categóricas.
Crie pelo menos uma feature derivada.
Divida os dados em treino e teste.

Treine pelo menos dois modelos de classificação sendo, Sleep_Quality, a variável alvo (target).

Compare resultados usando acurácia, matriz de confusão e/ou relatório de classificação.
Documente a avaliação:

Qual modelo performou melhor?
Há overfitting ou underfitting?
Salve o dataset final processado em CSV.

Salve o modelo que se saiu melhor.

Adicione uma seção Recomendações para o Negócio, explicando como os resultados podem ajudar a empresa a orientar clientes sobre hábitos de café e sono.
