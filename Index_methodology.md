# Codebook of Colombian subnational policies
## Database Description

The Desk Review database is a panel data set with the 76 main municipalities of interest analysed by week from March 1st to December 31st, 2020. Te data was obtainen from all the municipality decrees issued in the mentioned time. Thus, the policies were systematized in database format to make quantitative analysis. Currently, the information that is held in this database contains 34 general policies divided in 3 categories: Health, Containment and Economical. Additionally, there are several characteristics for each general measure. For example, the Lockdown measure is accompanied by how many hours a week the lockdown is activated and also how many hours a day. 

### Apicability Indices

Applicability indices are constructed by marking the existence of certain measures. If the measure is present then 1 point is added, if not the index remains the same. After all the policies are added, the index is recodified for the biggest possible value to be 100. This means that for the municipality that took all of the measures in the index in a week the result will be 100, and the rest will be calculated proportionally. 

### Intensity Indices

Since they are measured in binary code, applicability indices can only present the existence of a policy, but not the way it is being applied. Intensity indices are focused in capturing the level of application of those indices. The calculation of each varies depending on what is being measured. Every index is then normalized by dividing for the maximum possible value and multiplied by 100 to have continuous 0 to 100 indices. 

## Containment Indices
The policies included in this category are oriented to stop the spread of the virus. In general, this are oriented to make people stay at home and organized outside activities, such as grocery shopping. The goal of these measures is to break the chain of contagion and reduce the number of new cases every week.

### Aplicability
#### Applicability Index 1 (Stay at Home)
This index measures applicability of staying at home policies. As it is an applicability measure, one unit is added for each of the policies that compose it if said policy is implemented on a week on a municipality. The score is then rescaled to 0-100. Being 0 no policies adopted and 100 al of the policies adopted.

To see the policies that compose the index, click here. (LINK)
#### Applicability Index 2 (Leave Home)
This index measures applicability of policies that regulate out of home activities, such as buying groceries or physicall  activity. As it is an applicability measure, one unit is added for each of the policies that compose it if said policy is implemented on a week on a municipality. The score is then rescaled to 0-100. Being 0 no policies adopted and 100 al of the policies adopted.

To see the policies that compose the index, click here. (LINK)
### Intensity
#### Mobility Restrictions
Captures how strict are the restrictions to leave home. The index is initially presented as the relation of hours resricted to leave home to do certain activities and the totalnumber of hours in a week (168). For instance, if there are no restrictions in a municipality in a week, the value would be 0, and if there is total restricion (no one can leave home for  the  entire week) the index would be 1. It is then normalized by multipliying the index by 100.

### Descriptive Stats
Index name | _N_ | Calculation | Max Possible Value (100 if normalized) | Min Value (Normalized) |  Max Value (Normalized) | Mean (Normalized) |  
| --- | --- | --- | --- | --- | --- | --- |  
| Applicability Index 1 |  6 |<a href="https://www.codecogs.com/eqnedit.php?latex=\sum_{i=1}^{N}C_i/N" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sum_{i=1}^{N}C_i/N" title="\sum_{i=1}^{N}C_i/N" /></a> |  6 | 0 | 100  |54.848|    
| Applicability Index 2 |  4 | <a href="https://www.codecogs.com/eqnedit.php?latex=\sum_{i=1}^{N}C_i/N" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sum_{i=1}^{N}C_i/N" title="\sum_{i=1}^{N}C_i/N" /></a> | 6 | 0 | 100| 35.210 | 
| Mobility Restrictions |  5 | <a href="https://www.codecogs.com/eqnedit.php?latex=\frac{WeeklyRestricted&space;Hours}{WeeklyTotalHours&space;(168)}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{WeeklyRestricted&space;Hours}{WeeklyTotalHours&space;(168)}" title="\frac{WeeklyRestricted Hours}{WeeklyTotalHours (168)}" /></a> | 1 |  0 | 93.452 | 40.874 | 

## Economic Indices
The policies included in this category are the ones with the scope of facing the economic consequences of the pandemic. Some are oriented towards the citizens, in order to give them some economic relief, and some are oriented towards the administration, in order to strengthen the Government response to the economic crisis.
### Applicability
#### Economic Support
This index counts the policies taken to give economic relief to the people, mostly monetary and in kind transfers. It is important because having money to substain their family may incentivate people to stay at home.  As it is an applicability measure, one unit is added for each of the policies that compose it if said policy is implemented on a week on a municipality. The score is then rescaled to 0-100. Being 0 no policies adopted and 100 al of the policies adopted.

To see the policies that compose the index, click here. (LINK) 
#### Budget Adjustment
This index counts the policies taken to adjust budget inside the administration. It focuses mostly in transfers to the healh sector in order to strenghten the response. As it is an applicability measure, one unit is added for each of the policies that compose it if said policy is implemented on a week on a municipality. The score is then rescaled to 0-100. Being 0 no policies adopted and 100 al of the policies adopted.

To see the policies that compose the index, click here. (LINK)


### Descriptive Stats
Index name | _N_ | Calculation | Max Possible Value (100 if normalized) | Min Value (Normalized) |  Max Value (Normalized) | Mean (Normalized) |  
| --- | --- | --- | --- | --- | --- | --- |  
| Economic Support|  4 | <a href="https://www.codecogs.com/eqnedit.php?latex=\sum_{i=1}^{N}E_i/N" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sum_{i=1}^{N}E_i/N" title="\sum_{i=1}^{N}E_i/N" /></a> |  4 | 0 | 100  |25.022 |   
| Budget Adjustment | 3 | <a href="https://www.codecogs.com/eqnedit.php?latex=\sum_{i=1}^{N}E_i/N" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sum_{i=1}^{N}E_i/N" title="\sum_{i=1}^{N}E_i/N" /></a>| 3 | 0 | 100| 33.395 | 


## Health Indices
The policies included in this category are the ones that aim to control the spread of the virus and the mortality without restricting movement. Then are divided in two groups: the policies oriented to promote self care and the policies aiming to strenghten the system in order to reduce mortality.

### Applicability
#### Self Care
This index counts the policies that promote self care, such as mask enforcement, social distancing and others. As it is an applicability measure, one unit is added for each of the policies that compose it if said policy is implemented on a week on a municipality. The score is then rescaled to 0-100. Being 0 no policies adopted and 100 al of the policies adopted.

To see the policies that compose the index, click here. (LINK)
#### Health System Strenghtening
This index counts the policies aiming to improve health system, mostly with the acquisition of equimpent to treat COVID-19 patients. As it is an applicability measure, one unit is added for each of the policies that compose it if said policy is implemented on a week on a municipality. The score is then rescaled to 0-100. Being 0 no policies adopted and 100 al of the policies adopted.

To see the policies that compose the index, click here. (LINK)


### Descriptive Stats
Index name | _N_ | Calculation | Max Possible Value (100 if normalized) | Min Value (Normalized) |  Max Value (Normalized) | Mean (Normalized) |  
| --- | --- | --- | --- | --- | --- | --- |  
| Self Care|  3 | <a href="https://www.codecogs.com/eqnedit.php?latex=\sum_{i=1}^{N}S_i/N" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sum_{i=1}^{N}S_i/N" title="\sum_{i=1}^{N}S_i/N" /></a> | 3 | 0 | 75  |29.274 |   
| Health System Strenghtening | 3 | <a href="https://www.codecogs.com/eqnedit.php?latex=\sum_{i=1}^{N}S_i/N" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sum_{i=1}^{N}S_i/N" title="\sum_{i=1}^{N}S_i/N" /></a>| 3 | 0 | 50| 7.916 | 

