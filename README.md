# 🧠 Backtest do Modelo de Investimento "Magic Formula"

Este projeto tem como objetivo testar a eficácia da "Magic Formula" de Joel Greenblatt no mercado brasileiro, aplicando essa estratégia em ações negociadas na B3 ao longo dos últimos anos.

## 📈 Objetivo
O principal desafio aqui é verificar se a "Magic Formula", uma regra de investimento que promete identificar as melhores ações com base em dois indicadores (EBIT/EV e ROIC), teria gerado retornos superiores ao Ibovespa.

## 🚀 Passo a Passo

1. **Importação de Módulos e Bibliotecas**: Utilizei `pandas` para manipulação dos dados e `quantstats` para análise de performance.
2. **Coleta de Dados**: Importei os dados das empresas disponíveis, incluindo preço de fechamento ajustado, volume negociado, e outros indicadores financeiros.
3. **Cálculo dos Retornos Mensais**: Calculei os retornos mensais de cada empresa para determinar o desempenho ao longo do tempo.
4. **Filtragem de Liquidez**: Excluí empresas com baixo volume negociado para garantir que apenas ações com boa liquidez fossem analisadas.
5. **Criação do Ranking de Indicadores**: Classifiquei as empresas com base nos indicadores EBIT/EV e ROIC, gerando um ranking final para cada data.
6. **Construção das Carteiras**: Selecionei as 10 melhores ações para formar as carteiras, conforme os rankings criados.
7. **Cálculo da Rentabilidade**: Calculei a rentabilidade das carteiras mês a mês.
8. **Comparação com o Ibovespa**: Comparei o desempenho da "Magic Formula" com o Ibovespa no mesmo período.
9. **Análise dos Resultados**: Avaliei os resultados usando visualizações de mapas de calor mensais e gráficos de desempenho acumulado.

## 📊 Resultados
Os resultados mostram o desempenho das carteiras formadas pela "Magic Formula" em comparação com o Ibovespa, permitindo uma análise clara de sua eficácia no mercado brasileiro.
