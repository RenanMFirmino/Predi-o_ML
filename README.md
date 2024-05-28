# Prever preço de ações com Python e Machine Learning

Neste uso de aprendizado de máquina (machine learning), especialmente aprendizado profundo (deep learning), para prever os preços das ações. A abordagem utilizada neste projeto é a da rede LSMT (long short-term memory).

As redes LSMT são um tipo de rede neural recorrente (RNN) que são adequadas para dados de séries temporais RNNs são um tipo de rede neural que pode manipular dados sequenciais, como texto ou dados de séries temporais. A principal diferença entre uma RNN e uma rede neural tradicional é que uma RNN pode lembrar informações de entradas anteriores, o que é importante para lidar com dados de séries temporais.

As redes LSTM têm uma "memória" que pode lembrar informações por longos períodos de tempo. Isso é importante para prever os preços das ações, porque os preços das ações são dados de séries temporais. 

Para treinar uma rede LSTM para prever os preços das ações, primeiro precisamos coletar dados. Existem muitas fontes de dados que podem ser usadas para essa finalidade, mas uma fonte popular é o Yahoo! Finance. Depois de coletarmos os dados, podemos usá-los para treinar a rede LSTM.

 O processo de treinamento envolve alimentar os dados na rede LSTM e dizer a ela para prever a próxima etapa de tempo. Por exemplo, se tivermos dados de 60 dias, alimentaríamos os dados de 59 dias na rede e pediríamos para prever o preço das ações para o 60º dia. Em seguida, compararíamos o preço previsto com o preço real e ajustaríamos a rede de acordo. Este processo é repetido por várias épocas, até que a rede convirja em uma boa previsão.

Vamos utilizar o Python com os pacotes Keras, YahooFinance, Numpy e um pouco de matplotlib para criar o modelo que prevê o preço das ações.

Para rodar o código necessita desses pacotes:
Instalando os packages
!pip install tensorflow
!pip install keras
!pip install yfinance
!pip install numpy

