<img src=https://github.com/RodolfoPCruz/education_analysis/blob/master/QS%20Ranking/images/QS%20World.png width=1584 height=396>

# QS World University Rankings

Esse projeto apresenta uma análise dos rankings das melhores universidades do mundo publicados pela QS World University Rankings entre os anos de 2017 e 2024. Investigou-se quais são as universidades que ocuparam as melhores colocações e quais são os países com maior número de universidades entre as melhores do mundo. Comparou-se o desempenho das universidades com relação a fatores como reputação acadêmica, reputação entre empregadores, intercâmbio com a indústria,etc. Foi analisada a relação entre os fatores usados para a construção dos rankings. Por fim, foi examinado o desempenho das universidades brasileiras.

## Objetivo

Identificar quais são as melhores universidades do mundo segundo o QS World University Rankings e em que pontos elas se destacam. Verificar a distribuição geográfica das melhores universidades do mundo. Comparar o desempenho das universidades brasileiras, em especial da Unicamp em que sou aluno de doutorado atualmente, com as melhores do mundo.

## Instalação 

Para o desenvolvimento desse projeto foi utilizada a distribuição Anaconda. Para reproduzir o ambiente usado é necessário instalar o Anaconda e em seguida criar o ambiente com o uso do arquivo enviroment.yml disponibilizado. O comando que deverá ser usado no terminal do linux para criação do ambiente é o seguinte:

conda env create -f environment.yml

Após a execução desse comando será criado um novo ambiente com o nome education. 

Para informações detalhadas sobre instalação do anaconda acesse:

https://docs.anaconda.com/anaconda/install/

Já para informações sobre a criação de ambientes acesse :

https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html

## Data

Os datasets consistem nos rankings das melhores universidades do mundo para cada ano entre 2017 e 2024. Esses datasets estão disponíveis nos seguintes links:

- ranking 2025 (publicado em 2024): 

​	https://www.kaggle.com/datasets/darrylljk/worlds-best-universities-qs-rankings-2025

- ranking 2024:

  https://www.kaggle.com/datasets/joebeachcapital/qs-world-university-rankings-2024

- ranking 2023:

  https://www.kaggle.com/datasets/jkanthony/world-university-rankings-202223

- rankings de 2017 a 2022:

  https://www.kaggle.com/datasets/padhmam/qs-world-university-rankings-2017-2022

Os datasets contam com a pontuação geral obtida por cada universidade , bem como a pontuação para diversos fatores que foram levados em conta para a obtenção da pontuação geral. Alguns fatores considerados são reputação acadêmica, quantidade de citações, proporção de professores e alunos estrangeiros, etc. A metodologia para a construção dos rankings sofreu alteração em 2023, para informações a respeito da metodologia empregada nos rankings anteriores a 2023 acesse o seguinte link:

https://support.qs.com/hc/en-gb/articles/9051022681500-QS-World-University-Rankings-previous-methodology

Já informações a respeito da metodologia empregada a partir de 2023 podem ser encontradas no link:

https://support.qs.com/hc/en-gb/articles/4405955370898-QS-World-University-Rankings

## Resultados

As 10 melhores universidades no ranking publicado pela QS em 2024 e os países de origem dessas universidades são apresentados na tabela a seguir. O MIT ocupa a primeira colocação e vem se mantendo nesta posição em todos os rankings analisados.

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/QS%20Ranking/images/top10_2025.png)

O top 10 das melhores universidades do mundo é completamente dominado por universidades americanas e do Reino Unido. No último ranking publicado são 8 universidades desses dois países no top 10. Na Tabela a seguir é mostrado os países de origem das universidades que ocuparam o top 10 nos rankings anuais.

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/QS%20Ranking/images/paises_aparicoes_top_10.png)

O top 100 das melhores universidades do mundo também é dominado por universidades americanas e do Reino .Das 100 melhores no ranking publicado em 2024, 40 delas são desses dois países. No top 100 entraram algumas universidades de países em desenvolvimento, entre elas universidade do Brasil, Argentina e México.

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/QS%20Ranking/images/top100_mapa.png)

Entre as universidades brasileiras, a melhor colocada no ranking publicado em 2024 foi a USP, na posição 92. As 10 melhores brasileiras e suas posições no ranking geral são as seguintes:

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/QS%20Ranking/images/top10_brasileiras.png)


