<img src='/Shanghai World University Rankings/images/capa.jpeg' width=1584 height=396>

# Shanghai Ranking of World Universities

Esse projeto apresenta uma análise dos rankings das melhores universidades do mundo publicados até 2009 pela Center for World-Class Universities (CWCU), Graduate School of Education da  Universidade Shanghai Jiao Tong e a partir de 2009 pela Shanghai Ranking Consultancy. Esse ranking é chamado de Academic Ranking of World Universities. Foram analisados os rankings publicados a partir de 2004 até o último disponível, de 2023.Investigou-se quais são as universidades que ocuparam as melhores colocações e quais são os países com maior número de universidades entre as melhores do mundo. Comparou-se o desempenho das universidades com relação a fatores como quantidade de vencedores de prêmios Nobel entre ex-alunos e entre professores, publicações científicas em revistas conceituadas,número  de pesquisadores com elevado número de citações em publicações relevantes,etc. Foi analisada a relação entre os fatores usados para a construção dos rankings. Por fim, foi examinado o desempenho das universidades brasileiras.

## Resumo

## Instalação

Para o desenvolvimento desse projeto foi utilizada a distribuição Anaconda. Para reproduzir o ambiente usado é necessário instalar a distribuição Anaconda e em seguida criá-lo com o uso do arquivo enviroment.yml disponibilizado. O comando que deverá ser usado no terminal do linux para criação do ambiente é o seguinte:

conda env create -f environment.yml

Após a execução desse comando será criado um novo ambiente com o nome education. 

Para informações detalhadas sobre instalação do anaconda acesse:

https://docs.anaconda.com/anaconda/install/

Já para informações sobre a criação de ambientes acesse :

https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html

## Data

Os datasets foram coletados diretamente do site da Shanghai Ranking através de web scraping. O script usado para obtenção dos dados está disponível neste repositório (web_scraping_Shanghai.ipynb). O link do Shanghai ranking é o seguinte:

https://www.shanghairanking.com/rankings/arwu/2023

Os datasets contam com a pontuação geral obtida por universidade, bem como a pontuação para diversos fatores que foram levados em conta para a obtenção da pontuação geral. Os fatores analisados na construção do ranking de 2023 são os seguintes:

- Qualidade da educação oferecida pela universidade;
- Nível dos Professores;
- Qualidade da Pesquisa;
- Performance per capita (pontos anteriores ajustados pelo tamanho da instituição, visando facilitar a comparação entre universidades de tamanhos diferentes). 

A descrição detalhada da metodologia empregada na construção dos rankings pode ser encontrada no seguinte link:

https://www.shanghairanking.com/methodology/arwu/2023

## Resultados

###  Top 10

As 10 melhores universidades no Academic Ranking of World Universities publicado em 2023 e os países de origem dessas universidades são apresentados na Tabela 1. Ele é composto exclusivamente por universidades americanas e do Reino Unido. A universidade de Harvard ocupa a primeira colocação e vem se mantendo nesta posição em todos os rankings desde 2004. Além disso, as mesmas instituições compuseram o top 10 em todas as edições consideradas, ocorrendo somente alternância de posições entre elas.

![](/Shanghai%20World%20University%20Rankings/images/1-top10_2023.png)

### Primeira Colocada

A universidade de Harvard é a melhor universidade do mundo segundo o ranking Shanghai  e vem ocupando essa posição desde 2004.

### Top 100

O top 100 em 2004 também era dominado por universidades americanas e do Reino Unido, 51 e 11 respectivamente. Porém ao longo dos anos observou-se a entrada de um número crescente de universidades chinesas no top 100. No ranking publicado em 2023 são 10 universidades chinesas no top 100, 38 americanas e 8 do Reino Unido. O número de universidades de cada país no top 100 do ranking de 2023 é apresentado na Tabela 2. As universidades no top 100 estão concentradas no hemisfério norte (Figura 1), somente seis estão no hemisfério sul, e essas seis estão na Asutrália.

![](/Shanghai%20World%20University%20Rankings/images/2-top100_2023.png)

![](/Shanghai%20World%20University%20Rankings/images/3-mapa-mundi.png)

### Rankings Específicos para Cada Fator

Para o calculo da pontuação geral das universidades o ranking Shanghai adota uma metodologia que avalia quatro fatores: qualidade da educação, qualidade dos professores, qualidade da pesquisa produzida e performance per capita. O índices adotados para avaliar cada fator são foram os seguintes:

- Alumni : Avalia a qualidade da educação fornecida. Mede a quantidade de ex-alunos que receberam premiações. As premiações consideradas são prêmio Nobel em Física,Química, Medicina e Economia e Medalhas Field para a Matemática. ;
- Award  : Avalia o nivel dos professores. Medido através da quantidade de profissionais da universidade que receberam premiações. As premiações consideradas são prêmio Nobel em Física,Química, Medicina e Economia e Medalhas Field para a Matemática. 
- Hi Ci  : Avalia o nivel dos professores. Medido através do número de professores com grande número de citações;-
- N&S    : Avalia a pesquisa produzida. Mede a quantidade de artigos publicado na Nature e Science;
- PUB    :  Avalia a pesquisa produzida. Mede a quantidade de artigos indexados na  Science Citation Index-Expanded e Social Science Citation Index;
- PCP    : Per Capita Performance. Performance relativa ao tamanho da instituição.

As universidades receberam um nota para avaliar cada índice, a avaliação final recebida por cada uma é uma média ponderada dos indices. Na Tabela 3 as universidades aparecem ranqueadas de acordo com cada um dos indices. A Universidade de Harvard, que é a primeira no ranking geral (Tabela 1), ocupa a primeira posição em 4 dos 6 índices considerados.

![](/Shanghai%20World%20University%20Rankings/images/4-ranking_fatores.png)

### Universidades Brasileiras

Entre as universidades brasileiras, a melhor colocada no ranking 23 foi a USP, ficando entre as 150 melhores. A USP ocupou a primeira posição dentre as brasileiras em todos os rankings publicados desde 2004. As 10 melhores brasileiras e suas posições no ranking geral são apresentadas na Tabela 4. 

![](/Shanghai%20World%20University%20Rankings/images/5-top_brasileiras.png)

As universidades brasileiras ficam muito atrás dos centros de excelência mundiais. Na Tabela 5 são apresentadas as notas da USP e da Unicamp relativas a 2023 e dados estatísticos a respeito das 10 primeiras colocadas (Tabela 1). Por exemplo, tanto USP como Unicamp tem nota 0 para Alumi e Award, uma vez que nenhum de seus professores e ex-alunos já venceram o prêmio Nobel ou a medalha Fields. As universidades brasileiras se destacam entre as latino-americanas, A USP é a melhor e o top 10 dessa região conta com 6 universidades brasileiras (Tabela 6).

![](/Shanghai%20World%20University%20Rankings/images/6-brasileiras_top_10.png)

![](/Shanghai%20World%20University%20Rankings/images/7-top10-latinas.png)

