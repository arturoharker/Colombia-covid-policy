# Codebook of Colombian subnational policies
## Database Description

The Desk Review database is a panel data set with the 76 main municipalities of interest analysed by week from March 1st to December 31st, 2020. Te data was obtaines from all the municipality decrees issued in the mentioned time. Thus, the policies were systematized in database format to make quantitative analysis. Currently, the information that is held in this database contains 34 general policies divided in 3 categories: Health, Containment and Economical. Additionally, there are several characteristics for each general measure. For example, the Lockdown measure is accompanied by how many hours a week the lockdown is activated and also how many hours a day. 

### Apicability Indices

Applicability indices are constructed by marking the existence of certain measures. If the measure is present then 1 point is added, if not the index remains the same. After all the measures are added, the index is recodified for the biggest possible value is 100. This means that for the municipality that took all of the measures in the index in a week the result will be 100, and the rest will be calculated proportionally. 

### Intensity Indices

Since they are measured in binary code, applicability indices can only present the existence of a policy, but not the way it is being applied. Intensity indices are focused in capturing the level of application of those indices. The calculation of each varies depending on what is beeing measure. Every index is then normalized by dividing for the maximum possible value and multiplied by 100 to have continuous 0 to 100 indices. 

## Containment Indices
The measures included in this category are oriented to stop the spread of the virus. In general, this are oriented to make people stay at home and organized outside activities, such as grocery shopping. The goal of these measures is to breake the chain of contagion and reduce the number of new cases every week.

### Aplicability
#### Applicability Index 1 (Stay at Home)
This index measures applicability of staying at home policies. As it is an applicability measure, one unit is added for each of the policies that compose it if said policy is implemented on a week on a municipality. The score is then rescaled to 0-100. Being 0 no policies adopted and 100 al of the policies adopted.}

To see the policies that compose the index, clich here. (LINK)
#### Applicability Index 2 (Leave Home)
This index measures applicability of policies that regulate out of home activities, such as buying groceries or physicall  activity. As it is an applicability measure, one unit is added for each of the policies that compose it if said policy is implemented on a week on a municipality. The score is then rescaled to 0-100. Being 0 no policies adopted and 100 al of the policies adopted.}

To see the policies that compose the index, clich here. (LINK)
### Intensity
#### Mobility Restrictions
Captures how strict are the restrictions to go out by the total of restricted hours in a week. Being 0 when there is no restriction to go out and 100 that people are not allowed to go out any hour of any day in the week.

### Descriptive Stats
Index name | _N_ | Calculation | Max Possible Value (100 if normalized) | Min Value (Normalized) |  Max Value (Normalized) | Mean (Normalized) |  
| --- | --- | --- | --- | --- | --- | --- |  
| Applicability Index 1 |  6 |<a href="https://www.codecogs.com/eqnedit.php?latex=\sum_{i=1}^{N}C_i/N" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sum_{i=1}^{N}C_i/N" title="\sum_{i=1}^{N}C_i/N" /></a> |  6 | 0 | 100  |54.848|    
| Applicability Index 2 |  4 | <a href="https://www.codecogs.com/eqnedit.php?latex=\sum_{i=1}^{N}C_i/N" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sum_{i=1}^{N}C_i/N" title="\sum_{i=1}^{N}C_i/N" /></a> | 6 | 0 | 100| 35.210 | 
| Mobility Restrictions |  5 | <a href="https://www.codecogs.com/eqnedit.php?latex=\frac{WeeklyRestricted&space;Hours}{WeeklyTotalHours&space;(168)}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{WeeklyRestricted&space;Hours}{WeeklyTotalHours&space;(168)}" title="\frac{WeeklyRestricted Hours}{WeeklyTotalHours (168)}" /></a> | 1 |  0 | 93.452 | 40.874 | 

## Economic Indices
These indices are for evaluating the number of economic measures in order to face the consequences of the pandemic. Some are oriented towards the citizens and some are oriented in budget movements in order to strengthen the Government response.
### Applicability
#### Economic Support
XXX.  As it is an applicability measure, one unit is added for each of the policies that compose it if said policy is implemented on a week on a municipality. The score is then rescaled to 0-100. Being 0 no policies adopted and 100 al of the policies adopted.}

To see the policies that compose the index, clich here. (LINK) 
#### Budget Adjustment
XXX.  As it is an applicability measure, one unit is added for each of the policies that compose it if said policy is implemented on a week on a municipality. The score is then rescaled to 0-100. Being 0 no policies adopted and 100 al of the policies adopted.}

To see the policies that compose the index, clich here. (LINK)


### Descriptive Stats
Index name | _N_ | Calculation | Max Possible Value (100 if normalized) | Min Value (Normalized) |  Max Value (Normalized) | Mean (Normalized) |  
| --- | --- | --- | --- | --- | --- | --- |  
| Economic Support|  4 | <a href="https://www.codecogs.com/eqnedit.php?latex=\sum_{i=1}^{N}E_i/N" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sum_{i=1}^{N}E_i/N" title="\sum_{i=1}^{N}E_i/N" /></a> |  4 | 0 | 100  |25.022 |   
| Budget Adjustment | 3 | <a href="https://www.codecogs.com/eqnedit.php?latex=\sum_{i=1}^{N}E_i/N" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sum_{i=1}^{N}E_i/N" title="\sum_{i=1}^{N}E_i/N" /></a>| 3 | 0 | 100| 33.395 | 


## Health Indices

### Applicability
#### Self Care
XXX.  As it is an applicability measure, one unit is added for each of the policies that compose it if said policy is implemented on a week on a municipality. The score is then rescaled to 0-100. Being 0 no policies adopted and 100 al of the policies adopted.}

To see the policies that compose the index, clich here. (LINK)
#### Health System Strenghtening
XXX.  As it is an applicability measure, one unit is added for each of the policies that compose it if said policy is implemented on a week on a municipality. The score is then rescaled to 0-100. Being 0 no policies adopted and 100 al of the policies adopted.}

To see the policies that compose the index, clich here. (LINK)


### Descriptive Stats
Index name | _N_ | Calculation | Max Possible Value (100 if normalized) | Min Value (Normalized) |  Max Value (Normalized) | Mean (Normalized) |  
| --- | --- | --- | --- | --- | --- | --- |  
| Self Care|  3 | <a href="https://www.codecogs.com/eqnedit.php?latex=\sum_{i=1}^{N}S_i/N" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sum_{i=1}^{N}S_i/N" title="\sum_{i=1}^{N}S_i/N" /></a> | 3 | 0 | 75  |29.274 |   
| Health System Strenghtening | 3 | <a href="https://www.codecogs.com/eqnedit.php?latex=\sum_{i=1}^{N}S_i/N" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sum_{i=1}^{N}S_i/N" title="\sum_{i=1}^{N}S_i/N" /></a>| 3 | 0 | 50| 7.916 | 

