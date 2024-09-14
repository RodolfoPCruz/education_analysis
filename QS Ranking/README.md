<img src=https://github.com/RodolfoPCruz/education_analysis/blob/master/QS%20Ranking/images/QS%20World.png width=1584 height=396>

# QS World University Rankings

Esse projeto apresenta uma análise dos rankings das melhores universidades do mundo publicados pela QS World University Rankings entre os anos de 2017 e 2024. Investigou-se quais são as universidades que ocuparam as melhores colocações e quais são os países com maior número de universidades entre as melhores do mundo. Comparou-se o desempenho das universidades com relação a fatores como reputação acadêmica, reputação entre empregadores, intercâmbio com a indústria,etc. Foi analisada a relação entre os fatores usados para a construção dos rankings. Por fim, foi examinado o desempenho das universidades brasileiras.

## Objetivo

-Identificar quais são as melhores universidades do mundo segundo o QS World University Rankings e em que pontos elas se destacam;
-Verificar a distribuição geográfica das melhores universidades do mundo;
-Comparar o desempenho das universidades brasileiras com as melhores do mundo.

## Resumo

- O  Massachusetts Institute of Technology (MIT) é a melhor universidade do mundo no ranking referente a 2025;
- O MIT mantém a primeira colocação desde 2017;
- O top 10 de 2025 é dominado por universidades americanas e do Reino Unido, 8 no total. As duas restantes são da Suíça e de Singapura;
- O top 100 é dominado por universidades da América do Norte e da Europa;
- A USP é a universidade brasileira melhor colocada, ficando entre as 100 (92° posição) melhores para o ano de 2025;
- USP e Unicamp são as duas melhores colocadas brasileiras desde 2017;
- As universidades brasileiras estão muito atrás dos centros de excelência globais e não se sobressaem no ranking latino-americano.

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

Os datasets contam com a pontuação geral obtida por cada universidade, bem como a pontuação para os fatores usados nos cálculos da pontuação geral. Os fatores empregados pela metodologia da QS na construção de seus rankings a partir de 2023 são os seguintes:

- Reputação acadêmica;
- Reputação entre empregadores ;
- Proporção entre alunos e professores ;
- Citações;
- Proporção de professores estrangeiros;
- Proporção de alunos estrangeiros ;
- Colaboração com pesquisadores estrangeiros;
- Sucesso de ex-alunos;
- Sustentabilidade.

A metodologia para a construção dos rankings sofreu alteração em 2023, para informações a respeito da metodologia empregada nos rankings anteriores a 2023 acesse o seguinte link:

https://support.qs.com/hc/en-gb/articles/9051022681500-QS-World-University-Rankings-previous-methodology

Já informações a respeito da metodologia empregada a partir de 2023 podem ser encontradas no link:

https://support.qs.com/hc/en-gb/articles/4405955370898-QS-World-University-Rankings

## Resultados

### Top 10

As 10 melhores universidades do mundo segundo ranking QS publicado em 2024 e referente ao ano de 2025 (último disponível no momento da criação do projeto) e os países de origem dessas universidades são apresentadas na Tabela 1.

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/QS%20Ranking/images/1-top10_2025.png)

O top 10 de 2025 é  dominado por universidades  americanas e do Reino Unido, apenas duas universidades não são desses dois países. Essa hegemonia vem se repetindo desde 2017, conforme pode ser visto na Tabela 2.

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/QS%20Ranking/images/2-top_10_por_pais.png)

### Primeira Colocada

O MIT é a melhor universidade do mundo segundo o ranking QS e vem ocupando essa posição desde 2017. A melhor universidade do mundo a cada ano é apresentada na Tabela 3.

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/QS%20Ranking/images/3-primeiras_colocadas.png)

### Top 100

O predomínio de universidades americanas e do Reino Unido encontrada entre as 10 melhores universidades do mundo permanece quando são consideradas as 100 melhores. Dentre as 100, 40 universidades estão nesses dois países, conforme pode ser visto na tabela 4.  Além disso, 63 delas estão na Europa ou na América do Norte, e somente 16 no hemisfério sul (Figura 1).

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/QS%20Ranking/images/4-top100.png)

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/QS%20Ranking/images/5-top100_mapa.png)

### Rankings Específicos para Cada Fator

Para o calculo da pontuação geral das universidades a QS adota uma metodologia que emprega nove fatores, são eles: reputação acadêmica, reputação entre empregadores, proporção entre alunos professores, citações, proporção de professores estrangeiros,proporção de alunos estrangeiros, colaboração com pesquisadores estrangeiros, sucesso de ex-alunos e sustentabilidade . As universidades receberam uma nota para cada um desses nove fatores. A nota final é uma média ponderada desses  fatores. Na Tabela 5 as universidades aparecem ordenadas de acordo com os 4 fatores que tem maior peso (75% do total) para o calculo da nota geral, com O MIT aparecendo na liderança de todos eles.

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/QS%20Ranking/images/6-top_fatores.png)

### Universidades Brasileiras

Entre as universidades brasileiras, a melhor colocada no ranking 2025 foi a USP, na posição 95. As 10 melhores brasileiras e suas posições no ranking geral são apresentadas na Tabela 6. A USP e a Unicamp vem se mantendo como as duas melhores brasileiras em todos os rankings publicados desde 2017.

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/QS%20Ranking/images/7-top10_brasileiras.png)

As universidades brasileiras ficam muito atrás dos centros de excelência mundiais. Na Tabela 7 são apresentadas as notas da USP e da Unicamp relativas a 2025 e dados estatísticos a respeito das 10 primeiras colocadas (Tabela 1). As universidades brasileiras não se sobressaem nem entre as latino-americanas, a USP ocupa a segunda posição entre as latino-americanas e a segunda colocada brasileira está somente na nona posição (Tabela 8), desempenho ruim levando-se em conta o tamanho das economias dos países.

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/QS%20Ranking/images/8-comparativo_top10_brasileiras.png)

![](https://github.com/RodolfoPCruz/education_analysis/blob/master/QS%20Ranking/images/9-top10_latino_americanas.png)





