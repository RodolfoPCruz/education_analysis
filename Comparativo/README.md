<img src=/Comparativo/images/top-universities-2022.jpg da imagem width=1584 height=396>

# Melhores Universidades do Mundo

Esse projeto apresenta as melhores universidades do mundo de acordo com três rankings diferentes: o World University Rankings publicado anualmente pela Times Higher Education (será chamado a partir de agora de THE), o QS Ranking publicado pela QS World University Rankings e o Academic Ranking of World Universities publicado pela Shanghai Ranking Consultancy.  Esses são três dos rankings universitários mais importantes e influentes.

Para acrescentar informações a análise serão investigados alguns dados relativos a educação de diversos países. Os dados são os seguintes:

- escolaridade média da população;
- investimentos diretos públicos e privados em educação como fração do PIB;
- investimentos públicos em educação (em milhões US$);
- número total de matriculados por nível de ensino;
- proporção de pessoas matriculadas por nivel de ensino. A proporção é calculada como a razão entre o total de alunos matriculados no nivel de ensino e o total de pessoas no país com na faixa de idade correspondente ao nivel de ensino.

# Objetivo

Buscar as melhores universidades do mundo em  três dos mais importantes rankings universitários e comparar o desempenho delas em cada um dos rankings. Analisar dados a respeito da educação nos países para buscar entender porque as universidades de certos países tem posição de destaque.

# Instalação

Para o desenvolvimento desse projeto foi utilizada a distribuição Anaconda. Para reproduzir o ambiente usado é necessário instalar o Anaconda e em seguida criar o ambiente com o uso do arquivo enviroment.yml disponibilizado. O comando que deverá ser usado no terminal do linux para criação do ambiente é o seguinte:

conda env create -f environment.yml

Após a execução desse comando será criado um novo ambiente com o nome education.

Para informações detalhadas sobre instalação do anaconda acesse:

https://docs.anaconda.com/anaconda/install/

Já para informações sobre a criação de ambientes acesse :

https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html

# Data

Os datasets consistem em rankings das melhores universidades do mundo publicados por três instituições:

- Ranking Times Higher Education entre os anos de 2011 e 2024 foi baixado do kaggle e está diponível no seguinte link:

  - https://www.kaggle.com/datasets/r1chardson/the-world-university-rankings-2011-2023

- Ranking QS publicado entre os anos de 2017 e 2024 que podem ser baixados nos seguintes links:

  - https://www.kaggle.com/datasets/darrylljk/worlds-best-universities-qs-rankings-2025

  - https://www.kaggle.com/datasets/joebeachcapital/qs-world-university-rankings-2024

  - https://www.kaggle.com/datasets/jkanthony/world-university-rankings-202223
  - https://www.kaggle.com/datasets/padhmam/qs-world-university-rankings-2017-2022

- Ranking Shanghai publicados entre os anos de 2004 e 2023. Os dados foram baixados diretamente do site da instituição. Os script para o web scraping (web_scraping_Shanghai.ipynb) está na pasta Shanghai World University Rankings deste repositório. 

Além dos rankings, foram explorados outros dados para aprofundamento da análise:

- escolaridade média da população, investimentos  públicos  em educação como fração do PIB, investimentos públicos em educação (em milhões de US$), número total de matriculados por nível de ensino e proporção de pessoas matriculadas por nível de ensino. Todos esses dados estão disponíveis no site da Unesco:
  - http://data.uis.unesco.org/

- investimentos diretos públicos e privados em educação como fração do PIB obtidos no seguinte link:
  - https://nces.ed.gov/programs/digest/d14/tables/dt14_605.20.asp
  
# Resultados

## Dados dos Rankings

Os últimos rankings universitários publicados pela THE, QS e Shanghai são referentes aos anos de 2024, 2025 e 2023 respectivamente. Nos comparativos entre os rankings das três instituições serão consideradas as publicações mais recentes de cada uma delas. O número de universidades ranqueadas varia de acordo com a instituição, esses números para as publicações mais recentes são apresentados na Tabela 1. Nessa tabela é apresentado também o número de países cujas universidades  foram ranqueadas. O número de universidades é bem maior que o de países, indicando que as melhores universidades estão concentradas em poucos países. Para ilustrar esse fato o número de universidades por pais no ranking THE é mostrado no mapa múndi da Figura 1, onde se destacam EUA, Reino Unido e Japão com mais de 160 universidades ranqueadas, ou seja, três países apenas concentram 19% de todas as universidades rankeadas pelo THE.

![num_universidades_num_paises](/Comparativo/images/num_universidades_num_paises.png)

![num_universidades_por_pais](/Comparativo/images/num_universidades_por_pais.png)

### Top 10

As 10 universidades melhores colocadas nos três rankings são apresentadas na Tabela 2. Comparando esses três top 10, nota-se que eles tem muitas universidades em comum, inclusive 5 delas aparecem nos três top 10 (Tabela 3). A diferença entre eles está mais na posição ocupada pelas  universidades , diferença essa causada pela metodologia adotada na elaboração de cada ranking. Quanto a localização, a maior parte das universidades na Tabela 2 são ou dos EUA os do Reino Unido, com os top 10 dos rankings THE e Shanghai  formados somente por universidades desses dois países (Tabela 4). Ou seja, as melhores universidades do mundo, os centros de excelência, estão nos Estados Unidos e no Reino Unido.

![top_10_tres_rankings](/Comparativo/images/top_10_tres_rankings.png)

![intersecção_tres_rankings](/Comparativo/images/intersecção_tres_rankings.png)

![location_top_10](/Comparativo/images/location_top_10.png)

### Top 100

A predominância de universidades americanas e do Reino Unido encontrada nos top 10 se repete para o top 100 (Tabela 5). Entre 40 e 50% das universidades no top 100 do último ranking publicado por instituição estão nesses dois países. Considerando todas as universidades que entraram no top 100 de ao menos um dos três rankings, elas estão concentradas em apenas 27 países. Os países com universidades no top 100 da Tabela 5 são mostrados no mapa múndi da Figura 2. Esses países estão principalmente na América do Norte e na Europa Ocidental.

![location_top_100](/Comparativo/images/location_top_100.png)

![paises_universidades_top_100](/Comparativo/images/paises_universidades_top_100.png)

### Primeira Posição nos Rankings

Ao longo dos anos não vem ocorrendo variações nas universidades que ocupam a primeira posição de cada ranking. O ranking THE vem sendo liderado pela Universidade de Oxford desde 2017 (Tabela 6). Para o ranking QS o dataset conta com publicações referentes aos anos de 2017 a 2025, e em todos eles a primeira posição foi ocupada pelo MIT (Massachusetts Institute of Technology). Já para o ranking Shanghai  o dataset conta com os rankings referentes aos anos de 2004 a 2023. Em todos esses 20 rankings o primeiro lugar pertenceu a Universidade de Harvard.

![primeiro_lugar_THE](/Comparativo/images/primeiro_lugar_THE.png)

### Universidades Brasileiras

Em todos os rankings anuais  disponíveis no conjunto de dados a primeira posição entre as universidades brasileiras foi  ocupada pela Universidade de São Paulo (USP). No último ranking publicado pela THE a USP aparece entre as 250 melhores do mundo. A melhor posição já atingida por uma universidade brasileira foi a  85º lugar no ranking QS referente ao ano de 2024. Nesse mesmo ranking referente ao ano de 2025 a USP caiu para a posição 92. Já no último ranking Shangai publicado a USP aparece entre as 150 melhores do mundo.  Na Tabela 7 são apresentados os top 10 das universidades brasileiras no último ranking publicado por instituição e a posição de cada universidade nos rankings globais.

![top_10_Brazil](/Comparativo/images/top_10_Brazil.png)

## Dados Educacionais dos Países

### Escolaridade Média

A escolaridade média da população foi calculada considerando a população com idade superior a 25 anos. No dataset essa informação está disponível para uma maior quantidade de países nos dados referentes aos anos de 2019 e 2020. O mesmo vale para os demais fatores que serão analisados daqui por diante. Portanto nas análises que se seguirão será considerado o ano de 2020 por ser o mais recente com dados disponíveis para maior quantidade de países. Na Figura 3 são apresentadas as escolaridades médias para diversos países. Entre os países com as maiores escolaridades médias estão países que tem as melhores universidades do mundo. Por exemplo, no ranking THE de 2020 foram analisadas 1397 universidades, das quais 172 são americanas , 110 japonesas, 100 do Reino Unido e 48 alemãs. Esses 5 países estão no top 10 entre os de maior escolaridade média e detêm aproximadamente 30% de todas as universidades rankeadas pelo THE em 2020. 

Os dados de escolaridade média para o ano de 2020 estão disponíveis para 56 países. Dentre esses países 11 deles tem alguma universidade no top 100 de algum dos três rankings de 2020.  A média da escolaridade média nesses 11 países é de 12,4 anos. Nos demais 45 países a média da escolaridade média é de 9,73, ou seja, uma diferença percentual de aproximadamente 24 % na escolaridade média entre países que possuem universidades entre as 100 melhores e os que não possuem.

![escolaridade_media](/Comparativo/images/escolaridade_media.png)

### Número de Estudantes

Como era de se esperar os países com as maiores populações têm os maiores números de estudantes. Índia e China tinham mais de 100 milhões de alunos cada no ensino primário. No ensino secundário a Índia tinha 133 milhões de alunos e a China 88 milhões. A Índia tem também o maior número de alunos matriculados no ensino técnico, porém nesse caso a segunda posição é ocupada pelos EUA, seguidos pelo Brasil e pela China. Quanto ao ensino universitário a China tem o maior número de matriculados, seguida pela Índia, EUA e Brasil. 

Um número importante diz respeito a proporção de matriculados em cada nível de ensino. Por exemplo,  na Índia do total de pessoas na faixa etária correspondente ao ensino primário, 95% delas estavam cursando o ensino primário. Já para o nível secundário, os 133 milhões de alunos na Índia correspondiam a apenas 58% do total da população na faixa etária que deveria estar cursando esse nível de ensino. Isso significa que boa parte dos alunos na Índia abandonaram a escola entre o ensino primário e secundário, um enorme desperdício de talento. Já para países com universidades bens colocadas nos rankings, as proporções de pessoas estudando nos níveis educacionais correspondentes a faixa de idade são altas, quase totais. Para o ensino secundário é de 98% nos EUA, 98,9 % na Alemanha e 99,87% no Japão. No gráfico da Figura 4 é mostrado como a proporção de matriculados no ensino secundário é maior em países cujas universidades se destacam nos rankings, ou seja, o melhor desempenho das universidades passa por não perder talentos no ensino secundário.

![proporcao_matriculados](/Comparativo/images/proporcao_matriculados.png)

### Investimentos

Entre os países com os maiores investimentos públicos diretos em educação (dados para 2020) como fração do PIB destacam-se países nórdicos (Figura 5). A Noruega investe 6,5% do PIB em educação, enquanto a média para países da OCDE é de 4,3%. Interessante notar que o Brasil também investe acima da média dos países da OCDE, 4,6% do PIB brasileiro é direcionado para investimentos públicos em educação. No mesmo gráfico da Figura 5 os gastos aparecem divididos por nível educacional. O Brasil investe 1% do PIB em educação superior, o mesmo da média dos países da OCDE. A Coreia do Sul por exemplo concentra maior parte dos seus investimentos na educação básica e secundária, direcionando apenas 0,7% do PIB para a educação superior. O mesmo vale para os EUA e Reino Unido, com 0,9% e 0,5% do PIB voltados para a educação superior respetivamente.

![investimento_publico_prop_PIB](/Comparativo/images/investimento_publico_prop_PIB.png)

Os dois países com as melhores universidades do mundo, EUA e Reino Unido, não estão entre os que investem as maiores frações de seus PIBs em educação (Figura 5), ambos abaixo da média dos países da OCDE. Porém, esses dois países contam com elevado investimento privado em educação, como pode ser visto no gráfico da Figura 6. A média do investimento privado para países da OCDE é 0,3% do PIB em educação básica e secundária e 0,5% do PIB em educação superior. Considerando a educação superior, os setores privados investem 1.5% e 1.6% do PIB no Reino Unido e nos EUA. Na América latina se destaca o Chile, com 1,6% do PIB em investimento privado em educação superior.

![investimento_privado_prob_pib](/Comparativo/images/investimento_privado_prob_pib.png)

