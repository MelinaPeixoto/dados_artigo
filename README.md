# Projeto_Predição_da_concentração_de_poluentes_em_ambientes _internos
![image](https://github.com/MelinaPeixoto/projetos_analise_de_dados/assets/64225698/279ca6f8-c1be-4ce4-aa1d-c12daf23dd57)

# Objeto de Pesquisa

Este projeto de pesquisa investiga a concentração de poluentes atmosféricos em ambientes internos. A partir de dados experimentais, pretende-se avaliar a relação entre as concentrações interna e externa de diferente poluentes, calculando o 𝐹_𝑖𝑛𝑓  e contribuições de fontes internas por meio da solução da equação de balanço de massas. Com base nos resultados experimentais, pretende-se desenvolver e avaliar o desempenho de diferentes modelos de machine learning para estimar as concentrações internas dos ambientes estudados e definir. 

Posteriormente, pretende-se avaliar a viabilidade da utilização do modelo proposto para um conjunto mais amplo de residências com características semelhantes; eliminando assim, a necessidade de medições diretas em cada ambiente na estimativa da exposição ao material particulado (MP10 e MP2.5) em ambientes internos. Dessa forma, pretende-se contribuir para estudos epidemiológicos no que diz respeito à determinação da exposição humana à poluição do ar.

![image](https://github.com/MelinaPeixoto/projetos_analise_de_dados/assets/64225698/e572bb87-63b1-4065-b245-5ae1d0447f7b)

# Contextualização

![image](https://github.com/MelinaPeixoto/projetos_analise_de_dados/assets/64225698/7901cf57-a26c-4541-a985-ccfec6e60165)

# Coleta de dados

# Limpeza de dados
1. Manipulação de valores ausentes
   
Algumas das técnicas para lidar com valores ausentes incluem excluir linhas ou colunas com valores ausentes, imputar os valores ausentes com uma constante como zero, média, mediana ou modo, interpolar os valores ausentes com uma função linear ou não linear e usar métodos avançados, como vizinhos k-mais próximos, regressão ou modelos de aprendizado de máquina para prever os valores ausentes com base nos recursos e correlações disponíveis. Neste projeto utilizamos a técnica de interpolação linear entre os valores imediatamente anteriores e posteriores para imputar valores ausentes.

2. Identificação de outliers
   
Outliers são pontos de dados que se desviam significativamente do intervalo normal ou esperado de valores nos dados. Esses outliers podem ser causados por erros de medição, erros de entrada de dados ou eventos raros e podem distorcer as propriedades estatísticas e os padrões dos dados, bem como afetar o desempenho e a generalização de modelos de aprendizado de máquina. Para remover valores atípicos, estatísticas descritivas como média, desvio padrão, quartis e intervalo interquartil podem ser usadas para filtrar outliers com base em um limiar ou critério. Métodos gráficos como gráficos de caixa, gráficos de dispersão ou histogramas também podem ser empregados para inspecionar visualmente e remover outliers com base na forma e distribuição dos dados. Finalmente, algoritmos de clustering ou classificação como k-means, DBSCAN ou floresta de isolamento podem ser usados para agrupar os pontos de dados em clusters ou classes e remover valores atípicos que pertencem a clusters ou classes pequenas ou anômalas.

3. Transformação de dados
   
Os dados de séries temporais podem não ter uma forma ou distribuição desejável ou adequada para modelos de aprendizado de máquina, como assimetria, não estacionariedade, não-linearidade ou não-normalidade. Para enfrentar esse desafio, a transformação de dados é usada para aplicar funções matemáticas ou estatísticas aos dados para alterar sua escala, forma ou distribuição. Técnicas comuns para transformar dados incluem dimensionar ou normalizar os dados para reduzir o intervalo ou a variância dos valores; transformação logarítmica ou exponencial para reduzir a assimetria; diferenciar ou destendar para remover tendência ou sazonalidade; e potência ou transformação Box-Cox para tornar os dados mais lineares e melhorar a homocedasticidade.

# Exploração de dados

# Modelagem de dados

# Algoritmos de Machine Learning

# Avaliação dos algoritmos

# Conclusão



