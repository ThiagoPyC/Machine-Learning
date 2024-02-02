## IT Survey

O objetivo principal é realizar uma análise aprofundada dos dados provenientes das pesquisas de TI realizadas nos anos de 2019 e 2020. O processo se inicia com a identificação dos tipos de variáveis presentes na base de dados de 2018, categorizando-as em categóricas, numéricas, entre outras. 

Posteriormente, estou examinando cada dataframe para identificar linhas em que o ano da pesquisa, derivado do nome do arquivo, difere do ano do atributo "Timestamp". A exclusão dessas linhas é recomendada, após a criação de variáveis contendo o ano da pesquisa e do timestamp, e a aplicação de operações lógicas para selecionar as linhas pertinentes. 

Uma vez concluída essa etapa, os três dataframes foram consolidados em um único. As análises anteriores são, então, refeitas para avaliar se a exclusão das linhas com diferenças nos anos de pesquisa e timestamp influencia nas conclusões. 

Em seguida, os nomes das colunas dos dataframes de 2019 e 2020 são simplificados para possibilitar o maior número possível de colunas em comum. Um novo dataframe é criado com os dados desses dois anos, e suas dimensões são apresentadas. 

A análise descritiva é realizada para três atributos numéricos e três categóricos do dataframe consolidado. Além disso, são conduzidas cinco análises multivariadas utilizando a função "pivot table" do Pandas, apresentando conclusões decorrentes dessas análises. 

Elaborei um gráfico contendo a quantidade de entrevistas realizadas por mês ao longo dos três anos de pesquisa, excluindo linhas onde o ano da pesquisa difere do ano do timestamp. 

Por fim, algumas etapas adicionais são delineadas, incluindo a identificação e tratamento de valores nulos em atributos específicos, o encoding de variáveis categóricas como seniority, gender e city, o rescaling de variáveis categóricas utilizando pelo menos três métodos, e a discretização (quantílica e uniforme) das variáveis numéricas, com visualização gráfica dos resultados para cada uma dessas ações. Importante ressaltar que todas essas análises foram realizadas exclusivamente com as bases de IT Survey para os anos de 2019 e 2020, após empilhamento e tratamento inicial de dados. 