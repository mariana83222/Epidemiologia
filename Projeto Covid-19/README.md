# Project Covid-19

The present project was performed in the Sistemas de Informação Geográfica (**SIG**) course and its main objective was the analysis of the COVID-19 pandemic situation. A study of the distribution and evolution of the pandemic data relative to the United States of America (USA) was developed.

## Languages and Tools

* Python 
* Python libraries (numpy, pandas, scikit-learn)
* Jupyter Notebook


## Motivation

The USA is one of the countries with the most confirmed cases of COVID-19 and one of the most affected by the pandemic. The impact of COVID-19 in the country in question has been felt mainly in terms of the number of deaths, paralysis of economic sectors, and a substantial increase in the unemployment rate. In this sense, here are presented several maps and graphs that allow us to understand how the virus evolved over time in the US. In addition, one of the states was used as a case study: Connecticut. Note that some of the data presented is already outdated due to the daily advance of the pandemic.

## Objectives:

### Maps:
- Cases confirmed by state 
- Death by state

### Stats: 
##### Impact on USA
 - Distribution of the number of employed and unemployed people (per state) 
 - Employed VS Unemployed
 - Evolution of the number of cases over time in the most affected states
 - Evolution of the number of deaths over time in the most affected states
 
##### Case of study: Connecticut

- Evolution of the number of cases over time
- Evolution of the number of deaths over time
- Number of confirmed cases per countie
- Number of deaths per countie
- Number of hospitalized cases per countie
- Top 4 counties with most confirmed cases
- Top 4 counties with most deaths
- Top 4 counties with most hospitalized cases
- Comparisson of cases and deaths by gender
- Number of cases by age group
- Number of deaths by age group
- Number of cases by ethnic group
- Number of deaths by ethnic group
- Predictive models (Machine Learning)


## Datasets - Origin of the data

Data related to the number of cases and deaths in the US: https://github.com/nytimes/covid-19-data

Data used in the construction of the USA map: https://www.arcgis.com/home/item.html?id=f7f805eb65eb4ab787a0a3e1116ca7e5

Data related to the unemployment: https://github.com/UrbanInstitute/covid-neighborhood-job-analysis

Data from Connecticut: https://data.ct.gov/stories/s/COVID-19-data/wa3g-tfvc/

## Impact on the USA

### Map with color graduation (confirmed cases and deaths)

In the present section two USA maps are presented, with color gradutation and the respective distribution of number of confirmed cases (red map) and number of deaths (blue map), being that the darker the color, the higher the number it represents.

<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/cases_us.png" width="500">
 <img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/deaths_us.png" width="500">

### Evolution of the number of cases and deaths in the 5 most affected states

In this section are presented two graphs that allow us to observe the evolution of the number of confirmed case in the states where most cases are confirmed and also the evolution of the number of deaths over time in the states with most deatths. 

<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/comparacaocasosstate%20(1).jpg" width="800">

 <img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/comparacaomortosstate%20(1).jpg" width="800">
 
### Distribution of the number of employed people by state

In this section it is possible to observe the distribution of the number of employment cases in relation to every state of the USA in May 2020. 

<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/empregadoslog.jpg" width="500">

### Distribution of the number of unemployed people by state

In this section it is possible to observe the distribution of the number of unemployment cases in relation to every state of the USA in May 2020. 

<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/desempregadoslog.jpg" width="500">

### Comparisson of the number of employment and unemployment cases by state

The graphic shows a comparisson between the number of employed and unemployed in the USA in May.

<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/empregadosvsdesempregados.jpg" width="500">

## Case of study: Connecticut

### Evolution of the number of cases

<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/casoscon.jpg" width="500">

### Evolution of the number of deaths

<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/mortoscon.jpg" width="500">

### Distribution of cases, deaths and hospitalized

<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/confirmados.jpg" width="400"> <img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/mortos.jpg" width="400">
<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/hospitalizados.jpg" width="400">

### Top 4 (cases, deaths and hospitalized)
This section presents three graphics, where each of them represents the top 4 counties with the most cases, most deaths, and most hospitalizations, respectively. 

<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/confirmadospie.jpg" width="400"> <img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/mortospie.jpg" width="400">
<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/hospitalizadospie.jpg" width="400">

### Distribution of the number of cases and deaths by gender
This section presents a graphic that allows the comparisson between the number of cases and deaths between the female and male genders.

<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/malevsfemale.jpg" width="400"> 

### Distribution of the number of cases and deaths by age group
This section presents the distribution of the number of confirmed cases and deaths for each age group.

<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/casosage.jpg" width="400"><img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/mortesage.jpg" width="400"> 
 
### Distribution of the number of cases and deaths by ethnic group
This section presents the distribution of the number of confirmed cases and deaths for each ethnic group.

<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/casosetnia.jpg" width="400"><img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/mortesetnia.jpg" width="400"> 

### Predictive models 

This section presents two predictive models based on Machine Learning models: one regarding the number of cases and the other regarding the number of deaths. These models were built from the Decision Tree algorithm.

<img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/previsaocasos.jpg" width="500"> <img src="https://github.com/mariana83222/Epidemiologia/blob/master/Projeto%20Covid-19/Figuras/previsaomortos.jpg" width="500">

## Author
Mariana Gomes, A83222, MIEBIOM - Informática Médica 2019/2020

