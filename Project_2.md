# PROJECT 2: Generating Synthetic Population of Guatemala

## DHS Data Request
I am a William & Mary student taking a Agent Based Modeling course, for which I am constructing a model of Guatemala.The motivation of this research is to improve the use of multinomial logistic regression models to produce a descriptive synthetic population by determining, approximating and validating a continuous spatial model. Preliminarily, this data will be used to produce a synthetic population of Guatemala. I will describe land use and health care demand, as well as describe movement within Guatemala using the results from this model. By using remotely sensed data to estimate the dwelling locations across Guatemala and using survey data to estimate a spatially continuous multinomial, I will accomplish this research target. The DHS data will also help me investigate the interaction of settlements, households, roads, and health care facilities as a synergetic network. 

The DHS household survey I used consisted of: 
  1) 2,598 households 
  2) 21,383 persons
  
This survey was conducted in 2014 in Guatemala. Information on each household's members was included in the survey. There were many variables, however, the ones that I isolated during my analysis were the variable weights, household size, gender, age, education level of individuals, and location. 
## Guatemala Administrative Subdivision: Quetzaltenango
I chose to pivot from households to persons at the first administrative subdivision (or adm1) level. After deciding that, I proceeded to investigate Quetzaltenango (or Quezaltenango), Guatemala. The current estimated population of Quetzaltenango is around 200,000 persons. Though, at the time that this survey was conducted (i.e. 2014) the population was less than that since the population has been gradually increasing over time. My model had an estimated population of 204,433.8 with a weighted error of 0.002479565. Both this and the population information for Guatemala at the adm0 level were calculated the same way. So, it seems to be the case that the model is more accurate at the adm0 level than at the adm1 level. The way that the model performs at the adm0 level is not purely by chance, it also makes sense logically.  

I say that because the nature of the survey was for households not persons so already we have expanded this survey past its original scope. Additionally, the DHS survey was on the whole country of Guatemala, yet I still isolated a part of the country and predicted the population based on selected variables. Logically, when we juxtapose two models like this...
a) one being a country and 
b) the other being a subdivision of that country I think it is fair to assume that the error in the latter model would be higher thatn in the first model, when using the DHS survey one similar in configuration. 

To further improve my measures of accuracy I could include more variables that are telling of the population in Guatemala. Variables such as morbidity, fertility, health, and environmental events or dynamics have an impact on populations and could be helpful for the modeling accuracy to include. 

![](quezaltenango.png)

## Density Plot:
![](hhs_density.png)
## Adm1 Density Plot: 
![](adm1_density.png)

## Raw:
![](raw.png)
Scale:
![](scale.png)
## Normal:
![](normal.png)
