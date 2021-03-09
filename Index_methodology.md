# Codebook of Colombian subnational policies
## Database Description

The Desk Review database is a panel data set with the 76 main municipalities of interest analysed by week from March 1st to December 31st, 2020. Te data was obtaines from all the municipality decrees issued in the mentioned time. Thus, the policies were systematized in database format to make quantitative analysis. Currently, the information that is held in this database contains 34 general policies divided in 3 categories: Health, Containment and Economical. Additionally, there are several characteristics for each general measure. For example, the Lockdown measure is accompanied by how many hours a week the lockdown is activated and also how many hours a day. 

### Apicability Indices

Applicability indices are constructed by marking the existence of certain measures. If the measure is present then 1 point is added, if not the index remains the same. After all the measures are added, the index is recodified for the biggest possible value is 100. This means that for the municipality that took all of the measures in the index in a week the result will be 100, and the rest will be calculated proportionally. 

### Intensity Indices

Since they are measured in binary code, applicability indices can only present the existence of a policy, but not the way it is being applied. Intensity indices are focused in capturing the level of application of those indices. The calculation of each varies depending on what is beeing measure. Every index is then normalized by dividing for the maximum possible value and multiplied by 100 to have continuous 0 to 100 indices. 

## Containment Indices
The measures included in this category are oriented to stop the spread of the virus. In general, this are orientadasaefnsd to make people stay at home and organized outside activities, such as grocery shopping. The goal of these measures is to breake the chain of contagion and reduce the number of new cases every week.

### Aplicability
#### Applicability Index 1 
This index measures applicability of staying at home measures. The included measures in this index are: afora control, agglomerations control, isolation (mandatory or optional), social distancing, curfew, mobility restrictions and prohibition for commerce of alcoholic beverages.
#### Applicability Index 2
This index measures the applicability of measures that regulate the schedules to go out. The included measures in this index are: ID restrictions, Gender restriction,  and schedules to exercise outside.
### Intensity
#### Mobility Restrictions
Captures how strict are the restrictions to go out by the total of restricted hours in a week. Being 0 when there is no restriction to go out and 100 that people are not allowed to go out any hour of any day in the week.
### Descriptive Stats
Index name | _k_ | Calculation | Max Possible Value (100 if normalized) | Min Value (Normalized) |  Max Value (Normalized) | Mean (Normalized) |  
| --- | --- | --- | --- | --- | --- | --- |  
| Applicability Index 1 |  6 |  |  6 | 0 | 100  |54.848|    
| Applicability Index 2 |  4 |  | 6 | 0 | 100| 35.210 | 
| Mobility Restrictions |  5 | | 168 |  0 | 93.452 | 40.874 | 

## Economic Indices
These indices are for evaluating the number of economic measures in order to face the consequences of the pandemic. Some are oriented towards the citizens and some are oriented in budget movements in order to strengthen the Government response.
### Applicability
#### Economic Support
This index calculates the amount of economic measures that the municipality took in benefit of the citizens. It is composed of monetary and non-monetary transfers, tax discounts and guarantee of public services.
#### Budget Adjustment
This index calculates the economic measures taken inside the public administration to face the consequences of the pandemic. It is composed of two items: budget transfers inside the municipality and opening and closure of social services.
### Descriptive Stats
Index name | _k_ | Calculation | Max Possible Value (100 if normalized) | Min Value (Normalized) |  Max Value (Normalized) | Mean (Normalized) |  
| --- | --- | --- | --- | --- | --- | --- |  
| Economic Support|  4 |  |  4 | 0 | 100  |25.022 |   
| Budget Adjustment | 3 |  | 3 | 0 | 100| 33.395 | 


## Health Indices
### Applicability
#### Self Care
This index calculates the health measures taken in order to promote self care. Thus this index accounts policies focused on the citizens and their own responsibility for sustaining their health. This measure contains the mandatory use of masks, testing for the virus and the first half of the biosecurity measures imposed on commerce*.
#### Health System Strenghtening
This index calculates the health measures taken by the municipality in order to preserve the health of the citizens. They can be called the imposed care measures. The index is constructed using the increase of hospitals capacity (measured in Intensive Care beds), the guarantee of social services such as a water, the asistences and capacitation of medical personel and the second half of the biosecurity measures imposed on commerce*.


`*The biosecurity measures imposed on commerce are divided in two parts. The first part is mandatory social distancing, disinfection of customers on the entrance and the mandatory use of elements of personal care (masks, gloves, etc.). The second part are: capacity control on the entrance and symptoms control. `
### Descriptive Stats
Index name | _k_ | Calculation | Max Possible Value (100 if normalized) | Min Value (Normalized) |  Max Value (Normalized) | Mean (Normalized) |  
| --- | --- | --- | --- | --- | --- | --- |  
| Self Care|  3 |  | 3 | 0 | 75  |29.274 |   
| Health System Strenghtening | 3 |  | 3 | 0 | 50| 7.916 | 

