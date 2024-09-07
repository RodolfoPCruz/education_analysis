<img src=https://github.com/RodolfoPCruz/education_analysis/blob/master/Times%20Higher%20Education/images/capa_THE.jpg width=1584 height=396>

# World University Rankings (THE)

Esse projeto apresenta uma análise dos rankings das melhores universidades do mundo (World University Rankings) publicados anualmente pela Times Higher Education entre os anos de 2011 e 2024. Investigou-se quais são as universidades que ocuparam as melhores colocações e quais são os países com maior número de universidades entre as melhores do mundo. Comparou-se o desempenho das universidades com relação a fatores como qualidade da educação, pesquisa, inovação,etc. Foi analisada a relação entre os fatores usados para a construção dos rankings. Por fim, foi examinado o desempenho das universidades brasileiras.

## Objetivos
- Identificar quais são as melhores universidades do mundo de acordo com o World University Rankings  e em que pontos elas se destacam;
- Verificar a distribuição geográfica das universidades melhores colocadas nos rankings;
- Comparar o desempenho das universidades brasileiras com as primeiras colocadas no ranking.

## Instalação 

Para o desenvolvimento desse projeto foi utilizada a distribuição Anaconda. Para reproduzir o ambiente usado é necessário instalar a distribuição Anaconda e em seguida criá-lo com o uso do arquivo enviroment.yml disponibilizado neste repositório. O comando que deverá ser usado no terminal do linux para criação do ambiente é o seguinte:

`conda env create -f environment.yml`

Após a execução desse comando será criado um novo ambiente com o nome education.

## Data

O dataset consiste nos rankings das melhores universidades do mundo para cada ano entre 2011 e 2024. O dataset foi baixado do kaggle e está disponível em:

https://www.kaggle.com/datasets/r1chardson/the-world-university-rankings-2011-2023

Esse dataset conta com a pontuação geral obtida por cada universidade, bem como a pontuação para os fatores usados nos cálculos da pontuação geral. Os fatores empregados pela metodologia da THE na construção de seus rankings são os seguintes:

- Ensino;
- Pesquisa;
- Internacionalização;
- Quantidade de citações de suas publicações;
- Inovação.

A descrição detalhada dos fatores e metodologia empregada para desenvolvimento dos rankings pode ser encontrada no seguinte link:

https://www.timeshighereducation.com/world-university-rankings/world-university-rankings-2024-methodology 

## Resultados

### Top 10

As 10 melhores universidades do mundo segundo ranking Times Higher Education publicado em 2024 (último disponível no momento) e os países de origem dessas universidades são apresentadas na Tabela 1.

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/Times%20Higher%20Education/images/1-top10_2024.png)

O top 10 de 2024  é  dominado por universidades  americanas e do Reino Unido. Considerando todos os rankings publicados a partir de 2011, a hegemonia completa desses dois países nos top 10  só foi quebrada em 3 ocasiões, ou seja, dos 14 rankings publicados, em 11 deles o top 10 era composto somente por universidades do Reino Unido e americanas, enquanto nos 3 restantes uma universidade suíça entrou no top 10 (Tabela 2).

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/Times%20Higher%20Education/images/2-paises_top10.png)

### Primeira Colocada

A Universidade de Oxford é a melhor universidade do mundo segundo o ranking THE e vem ocupando essa posição desde 2017. A melhor universidade do mundo em cada ano é apresentada na Tabela 3.

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/Times%20Higher%20Education/images/3-primeira_colocada.png)

### Top 100

O predomínio de universidades americanas e do Reino Unido encontrada entre as 10 melhores universidades do mundo permanece quando são consideradas as 100 melhores. Dentre as 100, 47 universidades estão nesses dois países, conforme pode ser visto na tabela 4.  Além disso, 75 delas estão na Europa ou na América do Norte, e somente 6 no hemisfério sul (Figura 1).

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/Times%20Higher%20Education/images/4-localizacao-top100.png)

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/Times%20Higher%20Education/images/5-map_top_100.png)

### Rankings Específicos para Cada Fator

Para o calculo da pontuação geral das universidades a THE adota uma metodologia que emprega 5 fatores, são eles: ensino, pesquisa, citações, internacionalização e inovação. As universidades receberam uma nota para cada um desses cinco fatores. A nota final é uma média ponderada desses cinco fatores. Na Tabela 5 as universidades aparecem ordenadas de acordo com suas notas para cada um dos fatores. Interessante notar que a Universidade de Oxford lidera na pontuação geral, porém não está em primeiro em nenhum dos cinco fatores isolados.

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/Times%20Higher%20Education/images/6-ranking_fatores.png)

### Universidades Brasileiras

Entre as universidades brasileiras, a melhor colocada em 2024 foi a USP, na posição 236. As 10 melhores brasileiras e suas posições no ranking geral são apresentadas na Tabela 6. A USP e a Unicamp vem se mantendo como as duas melhores brasileiras em todos os ranking publicados desde 2012.

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/Times%20Higher%20Education/images/7-top_brasileiras.png)

As universidades brasileiras ficam muito atrás dos centros de excelência mundiais. Na Tabela 7 são apresentadas as notas da USP e da Unicamp relativas a 2024 e dados estatísticos a respeito das 10 primeiras colocadas. Elas se saem melhor quando comparadas com as universidades da América Latina. Na Tabela 8 é apresentado o top 10 de 2024 considerando somente universidades dessa região, onde cinco das 10 universidades são brasileiras. 

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/Times%20Higher%20Education/images/8-comparativo_brasileiras_top10.png)

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/Times%20Higher%20Education/images/9-top_10_latinas.png)





