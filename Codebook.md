# Codebook of Colombian subnational policies
---
*Index Methodology version 1.0*

*26 November 2020*

This codebooks shows the process in which indices are built in four main types of measures:

- [C - containment and closure policies](#containment-and-closure-policies)
- [E - economic policies](#economic-policies)
- [H - health system policies](#health-system-policies)

---
### Containment and closure policies

| ID | Name | Description | Measurement | Coding |
| --- | --- | --- | --- | --- |
| C1 | `C1_StayAtHome` | The application of measures that prevent citizenz to leave home. Measures are: aforo, events, Curfew, quarantine, distance, ley seca, restrictions to mobility | Continuous | <br/>0 -  0-	no measure applied. <br/>7 -	All the seven measures were applied |
| C2 | `C2_Leave home` | Record the allowance to leave home | Ordinal scale | 0 - no measures <br/>1 -No quarantine with restrictions to purchase goods or scheduled to do exercise <br/>2 - Quarantine with restrictions to purchase goods and schedule to do exercise  <br/>3 -Quarantine with restrictions to purchase goods and no allowance to do exercise |
| C3 | `C1_Quarantine` | How severe is the recorded quarantine | Ordinal scale | 0 - no measures <br/>1 -	Covid patients and people with sympthoms <br/>2 -Demographyc scoped quarantine  <br/>3 -Everybody is under quarantine |
| C4 | `C4_Circulation` | How strict are the circulation restrictions | Ordinal scale | 0 - no measures <br/>1 -	Only people with Symptoms <br/>2 - 	Public transport and/or tourist. Motorcycle restriction  <br/>3 -	Circulation restriction to 1 or more age groups <br/>4 -	Circulation restrictions are for everybody |
| C5 | `C5_PurchaseHours` | Hours restricted weekly to purchase goods | Continuous | 0 hours to 168 hours which is the total hours in a 7 days week |
| C6 | `C6_CurfewRestriction` | Hours restricted weekly by the Curfew | Continuous | 0 hours to 168 hours which is the total hours in a 7 days week |
| C7 | `C7_MobilityRestriction` | Hours restricted daily by the mobility restrictions | Continuous | 0 hours to 24 hours of the day |
### Economic policies

| ID | Name | Description | Measurement | Coding |
| --- | --- | --- | --- | --- |
|E1|`E1_TransfersInKind` |Number of beneficiaries of the transfers in kind|Ratio|Beneficiaries over population total|
|E2|`E2_MonetaryTransfers` |Number of beneficiaries of monetary transfers|Ratio|Beneficiaries over population total|
|E3|`E3_FocalizedDiscount` |Measures if the tax discount is targeted or general|Binary|</br>0- For the general population </br>1- Targeted to certain people|
|E4|`E4_BudgetTransferedPC` |Budget transfers|COP per person|Amount of budget modification normalized by population of each municipality|
|E5|`E5_AmountTransferedPC` |Money transferred per person|COP per person|Amount of money transferred normalized by population of each municipality|
### Health system policies

| ID | Name | Description | Measurement | Coding |
| --- | --- | --- | --- | --- |
|H1|`H1_IntensityofTesting`|Number of tests given by the municipality|Ratio|Number of tests over population|
|H2|`H2_HospitalCapacity`|Increase of hospital capacity, measured in hospital beds|Ratio|Number of new beds over number of pre-acquired beds|
