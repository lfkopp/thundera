# thundera
## Análise de frequencia de passageiros

![Crowd](crowd.jpg)

### Problema: 
Durante a pandemia, deve-se garantir o distanciamento social e em momentos de rush há um risco potencial de transmissão nas viagens. 
Usuários irão trocar de meio de transporte por medo da lotação.  Assim, o problema é como operações e comunicação poderá garantir a qualidade de serviço e espaçamento social em momentos de rush. 
Por exemplo, um passageiro às 16h, sem saber se haverá condições de distanciamento, poderá optar por transporte de aplicativo, mesmo que naquele momento o transporte estivesse vazia, reduzindo a receita.
### Escopo: 
Estimar quantidade de passageiros em cada composição ao longo das viagens. Com isso, operações pode aumentar o tempo entre viagens em momentos de movimento fraco para priorizar o rush. 
### Dados:
![Estações](mapa.png)
* Estação / id_catraca / Entrada ou saída / date_time
* Id_composicao / num_carros / date_time chegada e saída da plataforma / estação

### Literatura:
![Deep and Confident Prediction for Time Series at Uber](https://arxiv.org/pdf/1709.01907.pdf)
![COVID-19 Data Analysis and Forecasting: Algeria and the World](https://arxiv.org/pdf/2007.09755)

### Atividades:
- [ ] Coleta e limpeza de dados
- [ ] Modelagem dos grafos
- [ ] Estimativa de Entrada e saída de passageiros por estação e sazonalidade
- [ ] Teste com FB Prophet
- [ ] Modelagem de anomalias / eventos / efeitos climáticos
- [ ] Interface de comunicação
- [ ] Ajuste para correção em tempo real
- [ ] Visualização
- [ ] Teste final

### Resultados:
* Estimativa dos dados em t+1 atualizando online

