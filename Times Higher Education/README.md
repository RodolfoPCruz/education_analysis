<img src=https://github.com/RodolfoPCruz/education_analysis/blob/master/Times%20Higher%20Education/images/capa_THE.jpg width=1584 height=396>

# World University Rankings (THE)

Esse projeto apresenta uma análise dos rankings das melhores universidades do mundo (World University Rankings) publicados anualmente pela Times Higher Education entre os anos de 2011 e 2024. Investigou-se quais são as universidades que ocuparam as melhores colocações e quais são os países com maior número de universidades entre as melhores do mundo. Comparou-se o desempenho das universidades com relação a fatores como qualidade da educação, pesquisa, intercâmbio com a indústria,etc. Foi analisada a relação entre os fatores usados para a construção dos rankings. Por fim, foi examinado o desempenho das universidades brasileiras.

## Objetivos
- Identificar quais são as melhores universidades do mundo de acordo com o World University Rankings  e em que pontos elas se destacam;
- Verificar a distribuição geográfica das universidades melhores colocadas nos rankings;
- Comparar o desempenho das universidades brasileiras, em especial a universidade em que curso doutorado (Unicamp), com as primeiras colocadas no ranking.

## Instalação 

Para o desenvolvimento desse projeto foi utilizada a distribuição Anaconda. Para reproduzir o ambiente usado é necessário instalar a distribuição Anaconda e em seguida criá-lo com o uso do arquivo enviroment.yml disponibilizado neste repositório. O comando que deverá ser usado no terminal do linux para criação do ambiente é o seguinte:

`conda env create -f environment.yml`

Após a execução desse comando será criado um novo ambiente com o nome education.

## Data

O dataset consiste nos rankings das melhores universidades do mundo para cada ano entre 2011 e 2024. O dataset foi baixado do kaggle e está disponível em:

https://www.kaggle.com/datasets/r1chardson/the-world-university-rankings-2011-2023

Esse dataset conta com a pontuação geral obtida por cada universidade, bem como a pontuação para diversos fatores que foram levados em conta para a obtenção da pontuação geral. Alguns fatores considerados são ensino, pesquisa, internacionalização, número de citações, relação com a indústria e etc. A descrição detalhada dos fatores e metodologia empregada para desenvolvimento dos rankings pode ser encontrada no seguinte link:

https://www.timeshighereducation.com/world-university-rankings/world-university-rankings-2024-methodology 

## Resultados

As 10 melhores universidades no ranking Times Higher Education publicado em 2024 e os países de origem dessas universidades são as seguintes:

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/Times%20Higher%20Education/images/top10_2024.png)

A Universidade de Oxford apareceu na primeira colocação na maior parte dos rankings desde 2011. Três universidades vem se alternando nessa posição desde 2011, são elas:

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/Times%20Higher%20Education/images/aparicoes_em_primeiro.png)

O top 10 das melhores universidades do mundo é completamente dominado por universidades americanas e do Reino Unido. Uma universidade suíça quebrou a hegemonia desses dois países em 3 ocasiões ,ou seja, dos 14 ranking publicados de 2011 a 2024, em 11 deles o top 10 era composto somente por universidades do Reino Unido e americanas, enquanto nos 3 restantes uma universidade suíça entrou no top 10.



![](https://github.com/RodolfoPCruz/education_analysis/blob/master/Times%20Higher%20Education/images/paises_top10.png)



O top 100 das melhores universidades do mundo é dominado por universidades americanas e européias. Somente uma universidade no hemisfério sul entrou no top 100.



![](https://github.com/RodolfoPCruz/education_analysis/blob/master/Times%20Higher%20Education/images/map_top_100.png)

Entre as universidades brasileiras, a melhor colocada em 2024 foi a USP, na posição 236. As 10 melhores brasileiras e suas posições no ranking geral são as seguintes:

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/Times%20Higher%20Education/images/top_brasileiras)



