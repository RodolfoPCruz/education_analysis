<img src='/Shanghai World University Rankings/images/capa.jpeg' width=1584 height=396>

# Shanghai Ranking of World Universities

Esse projeto apresenta uma análise dos rankings das melhores universidades do mundo publicados até 2009 pela Center for World-Class Universities (CWCU), Graduate School of Education da  Universidade Shanghai Jiao Tong e a partir de 2009 pela Shanghai Ranking Consultancy. Esse ranking é chamado de Academic Ranking of World Universities. Foram analisados os rankings publicados a partir de 2004 até o último disponível,de 2023.Investigou-se quais são as universidades que ocuparam as melhores colocações e quais são os países com maior número de universidades entre as melhores do mundo. Comparou-se o desempenho das universidades com relação a fatores como quantidade de vencedores de prêmios Nobel entre ex-alunos e entre professores, publicações científicas em revistas conceituadas,número de pesquisadores com elevado número de citações em publicações relevantes,etc. Foi analisada a relação entre os fatores usados para a construção dos rankings. Por fim, foi examinado o desempenho das universidades brasileiras.

## Objetivo

Para o desenvolvimento desse projeto foi utilizada a distribuição Anaconda. Para reproduzir o ambiente usado é necessário instalar a distribuição Anaconda e em seguida criá-lo com o uso do arquivo enviroment.yml disponibilizado. O comando que deverá ser usado no terminal do linux para criação do ambiente é o seguinte:

conda env create -f environment.yml

Após a execução desse comando será criado um novo ambiente com o nome education. 

Após a execução desse comando será criado um novo ambiente com o nome education.

Para informações detalhadas sobre instalação do anaconda acesse:

https://docs.anaconda.com/anaconda/install/

Já para informações sobre a criação de ambientes acesse :

https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html

## Data

Os datasets foram coletados diretamente do site da Shanghai Ranking através de web scraping. O script usado para obtenção dos dados está disponível neste repositório (web_scraping_Shanghai.ipynb). O link do Shanghai ranking é o seguinte:

https://www.shanghairanking.com/rankings/arwu/2023

Os datasets contam com a pontuação geral obtida por cada universidade , bem como a pontuação para diversos fatores que foram levados em consideração para a obtenção da pontuação geral. A metodologia para a construção dos rankings pode ser encontrada no seguinte link:

https://www.shanghairanking.com/methodology/arwu/2023

## Resultados

As 10 melhores universidades no Academic Ranking of World Universities publicado em 2023 e os países de origem dessas universidades são apresentados na tabela  a seguir. A universidade de Harvard ocupa a primeira colocação e vem se mantendo nesta posição em todos os rankings analisados. Além disso, as mesmas instituições compuseram o top 10 em todas as edições consideradas, ocorrendo somente alternância de posições entre elas.

![](/Shanghai%20World%20University%20Rankings/images/top10_2023.png)

O top 10 das melhores universidades do mundo de 2004 a 2023 foi composto em todas as edições por 8 universidades americanas e duas do Reino Unido. Já o top 100 em 2004 também era dominado por universidades desses dois países, 51 e 11 respectivamente. Porém ao longo dos anos observou-se a entrada de um número crescente de universidades chinesas no top 100. No ranking publicado em 2023 são 10 universidades chinesas no top 100, 38 americanas e 8 do Reino Unido. O número de universidades de cada país no top 100 do ranking de 2023 é apresentado no mapa abaixo.

![](/Shanghai%20World%20University%20Rankings/images/mapa-mundi.png)

Entre as universidades brasileiras, a melhor colocada no ranking publicado em 2023 foi a USP, que ficou entre as 150 melhores colocadas. As 10 melhores colocadas brasileiras e suas posições no ranking geral são as seguintes:

![](/Shanghai%20World%20University%20Rankings/images/top_brasileiras.png)



