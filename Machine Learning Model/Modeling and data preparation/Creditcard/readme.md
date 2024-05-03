## Creditcard

Inicialmente, utilizando a base de dados (creditcard_transformed.csv), são utilizados métodos de subamostragem e superamostragem para lidar com desequilíbrios, seguidos por uma análise visual comparativa antes e depois de cada técnica, além da exposição das alterações no volume de dados resultante.  

Em seguida, utilizando a base de dados (creditcard.csv), focando na relação entre variáveis, opta-se por um método de avaliação de correlação, com a escolha daquelas que apresentam baixa correlação entre si, determinando um limite máximo aceitável. O método da variância é então empregado para selecionar variáveis com variação igual ou superior a 1, identificando aquelas potencialmente mais informativas. 

A análise prossegue com o método ANOVA para a seleção das 10 variáveis mais relevantes, utilizando a técnica estatística para avaliar diferenças significativas entre as médias de diferentes grupos. A importância intrínseca das variáveis é estimada pelo algoritmo Random Forest, que destaca as 10 mais relevantes com base nessa medida. 

Por fim, o método de Informação Mútua é empregado para a seleção das 10 principais variáveis do problema, utilizando uma abordagem que avalia a dependência entre variáveis. Essas etapas combinadas visam realizar uma análise abrangente e preparar os dados de maneira eficiente para modelagem, destacando as características mais pertinentes para a resolução do problema em questão. 

 