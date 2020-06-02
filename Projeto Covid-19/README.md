# Projeto Covid-19

O presente trabalho foi realizado âmbito da Unidade Curricular de Sistemas de Informação Geográfica, tendo como objetivo principal a análise da situação pandémica COVID-19 vivida atualmente. Foi desenvolvido um estudo da distribuição e evolução dos dados da pandemia relativos aos Estados Unidos da América (EUA), recorrendo ao Jupyter Notebook e a diversas bibliotecas.

## Motivação

Os Estados Unidos da América são um dos países com mais casos confirmados de COVID-19 e mais afetados pela pandemia. O impacto do COVID-19 no país em questão fez-se sentir principalmente ao nível do número de mortos, paralisação de setores económicos e aumento substancial da taxa de desemprego. Nesse sentido, encontram-se apresentados diveros mapas e gráficos que permitem compreender a forma como o vírus evoluiu ao longo do tempo nos EUA, tendo para além disso sido utilizado um dos estados como caso de estudo: Connecticut. De notar que alguns dos dados apresentados já se encontram desatualizados devido ao avanço diário da pandemia.

## Objetivos:

### Maps:
- Casos confirmados por estado
- Mortos por estado

### Stats: 
##### Impacto nos EUA
 - Distribuição do número de empregados e desempregados (por estado)
 - Empregados VS Desempregados
 - Evolução do número de casos ao longo do tempo nos estados mais afetados
 - Evolução do número de mortes ao longo do tempo nos estados mais afetados
 
##### Caso de estudo: Connecticut

- Evolução do número de casos ao longo do tempo
- Evolução do número de mortos ao longo do tempo
- Número de confirmados por countie
- Número de mortos por countie
- Número de hospitalizados por countie
- Top 4 counties com mais casos confirmados
- Top 4 counties com mais mortos
- Top 4 counties com mais casos hospitalizados
- Comparação de casos e mortes por género
- Número de casos por grupo de idade
- Número de mortos por grupo de idade
- Número de casos por etnia
- Número de mortos por etnia

## Datasets - Origem dos dados

Dados relativos ao nº de casos e mortes nos EUA: https://github.com/nytimes/covid-19-data

Dados utilizados para a construção do mapa dos EUA: https://www.arcgis.com/home/item.html?id=f7f805eb65eb4ab787a0a3e1116ca7e5

Dados relativos ao desemprego: https://github.com/UrbanInstitute/covid-neighborhood-job-analysis

Dados Connecticut: https://data.ct.gov/stories/s/COVID-19-data/wa3g-tfvc/

## Impacto nos EUA

### Mapa com graduação de cores (casos confirmados e mortos)

Na presente secção encontram-se apresentados dois mapas dos EUA, com graduação de cores e a respetiva distribuição do número de casos confirmados (mapa vermelho) e do número de mortos (mapa azul), sendo que quanto mais escura a cor, maior o número que representa.

<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/cases_us.png" width="500">
 <img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/deaths_us.png" width="500">

### Comparação do nº de casos e mortes por estado
<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/comparacaocasosstate.jpg" width="500">
 <img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/comparacaomortosstate.jpg" width="500">
 
### Distribuição do nº de empregados por estado
<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/empregadoslog.jpg" width="500">

### Distribuição do nº de desempregados por estado
<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/desempregadoslog.jpg" width="500">

### Comparação do nº de empregados e desempregados por estado
<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/empregadosvsdesempregados.jpg" width="500">

## Caso de estudo: Connecticut

### Evolução do número de casos
<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/casoscon.jpg" width="400">

### Evolução do número de mortos
<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/mortoscon.jpg" width="400">

### Distribuição casos, mortos e hospitalizados

<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/confirmados.jpg" width="400"> <img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/mortos.jpg" width="400">
<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/hospitalizados.jpg" width="400">

### Top 4 (casos, mortos e hospitalizados)
<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/confirmadospie.jpg" width="400"> <img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/mortospie.jpg" width="400">
<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/hospitalizadospie.jpg" width="400">

### Distribuição do nº de casos e mortes por género
<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/malevsfemale.jpg" width="400"> 

### Distribuição do nº de casos e mortes por grupos etários
<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/casosage.jpg" width="400"> <img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/mortesage.jpg" width="400"> 
 
### Distribuição do nº de casos e mortes por etnia
<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/casosetnia.jpg" width="400"> <img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/mortesetnia.jpg" width="400"> 

