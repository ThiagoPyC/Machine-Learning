## PCA - LDA

O objetivo consiste na aplicação da Análise de Componentes Principais (PCA) nos conjuntos de dados de câncer de mama e íris, utilizando a biblioteca scikit-learn. O PCA é uma técnica de redução de dimensionalidade que visa representar os dados por meio de componentes principais, mantendo a maior parte da variabilidade original. 

Em seguida, para ambos os conjuntos de dados, será gerado um gráfico dos eigenvalues (autovalores) resultantes do PCA. A análise busca identificar possíveis pontos de inflexão no gráfico, indicando o número ideal de componentes principais a serem utilizadas. Este ponto é crucial para determinar a quantidade de informação preservada na redução de dimensionalidade. 

Posteriormente, o Linear Discriminant Analysis (LDA) será aplicado nos conjuntos de dados de câncer de mama e íris utilizando o scikit-learn. O LDA é uma técnica de redução de dimensionalidade que visa maximizar a separação entre as classes, sendo particularmente útil em problemas de classificação. 

Por fim, será realizado um comparativo entre PCA e LDA para ambos os conjuntos de dados. Este comparativo será realizado utilizando dois componentes principais para cada técnica. O objetivo é visualizar e analisar as diferenças nas projeções dos dados proporcionadas por PCA e LDA, avaliando como cada técnica realiza a redução de dimensionalidade e sua capacidade de preservar informações discriminativas. 

Dessa forma, o conjunto de análises proposto visa explorar e comparar as técnicas de PCA e LDA nos conjuntos de dados de câncer de mama e íris, proporcionando insights sobre a estrutura dos dados e a eficácia dessas técnicas na representação e discriminação das informações contidas nos conjuntos de dados. 