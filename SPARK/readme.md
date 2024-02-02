## Bike Sharing Demand

Os sistemas de compartilhamento de bicicletas são um meio de alugar bicicletas
em que o processo de obtenção de adesão, aluguel e devolução de bicicletas é
automatizado por meio de uma rede de quiosques espalhados pela cidade.
Usando esses sistemas, as pessoas podem alugar uma bicicleta em um local e
devolvê-la em um local diferente conforme necessário. Atualmente, existem mais
de 500 programas de compartilhamento de bicicletas em todo o mundo. Os
dados gerados por esses sistemas os tornam atraentes para os pesquisadores
porque a duração da viagem, o local de partida, o local de chegada e o tempo
decorrido são explicitamente registrados. Os sistemas de compartilhamento de
bicicletas funcionam, portanto, como uma rede de sensores, que pode ser
utilizada para estudar a mobilidade em uma cidade. Neste projeto vamos
combinar padrões históricos de uso com dados meteorológicos, a fim de prever a
demanda por aluguel de bicicletas no programa Capital Bikeshare em
Washington, DC.

O objetivo desta proposta é desenvolver uma solução para prever a demanda
por aluguel de bicicletas em um sistema de compartilhamento de bicicletas. A
solução será baseada na combinação de dados históricos de uso com dados
meteorológicos.

O modelo de machine learning será desenvolvido usando o algoritmo
RandomForestRegressor. O random search será utilizado para seleção de
hiperparâmetros. A métrica utilizada será a RMSLE.

DataFrame: https://www.kaggle.com/competitions/bike-sharing-demand