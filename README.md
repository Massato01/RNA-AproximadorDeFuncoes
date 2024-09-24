# RNA-AproximadorDeFuncoes
O que o código faz:

1. run_simulations: Função para executar múltiplas simulações com uma dada arquitetura (quantidade de camadas e neurônios) e calcular a média e o desvio padrão do erro de predição.

2. Testes de Arquitetura: Três arquiteturas são testadas:
* (2,): Rede com uma camada e 2 neurônios.
* (5, 2): Rede com duas camadas, 5 neurônios na primeira e 2 na segunda.
* (10, 5, 2): Rede com três camadas, 10, 5 e 2 neurônios.

3. Plotagem dos resultados: Para cada teste, são exibidos três gráficos:
* Os dados originais.
* A curva de aprendizado.
* O resultado da regressão.

### Resultados:

Para cada arquitetura, o código calcula a média e o desvio padrão do erro final em 10 execuções.
Plota os gráficos para analisar o ajuste da rede neural em cada caso.
Execute isso para os arquivos de teste disponíveis (teste2.npy a teste5.npy) e avalie as diferentes arquiteturas.
