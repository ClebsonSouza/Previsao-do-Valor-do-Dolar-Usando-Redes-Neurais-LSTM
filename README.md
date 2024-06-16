# Previsão do Valor do Dólar usando LSTM

Este projeto visa desenvolver um modelo de rede neural Long Short-Term Memory (LSTM) para prever o valor do dólar. LSTMs são eficazes em capturar dependências de longo prazo em séries temporais, tornando-as ideais para a previsão de preços de moedas.

Problema de Negócio
Prever o valor futuro do dólar é essencial para investidores, traders e empresas que operam no mercado financeiro. Com previsões precisas, é possível tomar decisões informadas sobre investimentos e estratégias de hedge (proteção da carteira para que possíveis movimentos negativos do mercado afetem totalmente os rendimentos).

Estrutura do Projeto
1. Importação de Bibliotecas e Carregamento dos Dados
Importamos as bibliotecas necessárias, como Keras e TensorFlow, e carregamos a base de dados contendo o histórico de preços do dólar.

2. Pré-processamento dos Dados
Realizamos o pré-processamento dos dados, incluindo normalização e transformação das séries temporais em um formato adequado para o treinamento do modelo LSTM.

3. Construção e Treinamento do Modelo LSTM
Construímos a arquitetura do modelo LSTM e treinamos o modelo usando os dados históricos. Ajustamos os hiperparâmetros para otimizar a performance do modelo.

4. Avaliação do Modelo
Avaliamos a performance do modelo utilizando métricas apropriadas, como a raiz do erro quadrático médio (RMSE).

5. Previsão para Novos Dados
Utilizamos o modelo treinado para fazer previsões futuras do valor do dólar. Visualizamos as previsões para melhor interpretação e análise.

Conclusão
Este projeto demonstra a aplicação de redes neurais LSTM na previsão de séries temporais financeiras. As previsões obtidas podem ser extremamente úteis para diversas partes interessadas no mercado financeiro, ajudando a tomar decisões informadas e estratégicas.
