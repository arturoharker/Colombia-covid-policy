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
| C1 | `C1_Circulation` | How strict are the circulation restrictions | Ordinal scale | 0 - no measures <br/>1 -	Only people with Symptoms <br/>2 - 	Public transport and/or tourist. Motorcycle restriction  <br/>3 -	Circulation restriction to 1 or more age groups <br/>4 -	Circulation restrictions are for everybody |
| C2 | `C2_Leave home` | Record the allowance to leave home | Ordinal scale | 0 - no measures <br/>1 -No quarantine with restrictions to purchase goods or scheduled to do exercise <br/>2 - Quarantine with restrictions to purchase goods and schedule to do exercise  <br/>3 -Quarantine with restrictions to purchase goods and no allowance to do exercise |
| C3 | `C1_Quarantine` | How severe is the recorded quarantine | Ordinal scale | 0 - no measures <br/>1 -	Covid patients and people with sympthoms <br/>2 -Demographyc scoped quarantine  <br/>3 -Everybody is under quarantine |

### Economic policies

| ID | Name | Description | Measurement | Coding |
| --- | --- | --- | --- | --- |
|E1|`E1_TransfersInKind` |Number of beneficiaries of the transfers in kind|Ratio|Beneficiaries over population total|
|E2|`E2_MonetaryTransfers` |Number of beneficiaries of monetary transfers|Ratio|Beneficiaries over population total|
|E3|`E3_FocalizedDiscount` |Measures if the tax discount is targeted or general|Binary|</br>0- For the general population </br>1- Targeted to certain people|
|E4|`E4_AmountTransfered` |Budget transfers|COP|Amount of transfer made|
### Health system policies

| ID | Name | Description | Measurement | Coding |
| --- | --- | --- | --- | --- |
|H1|`H1_IntensityofTesting`|Number of tests given by the municipality|Ratio|Number of tests over population|
|H2|`H2_HospitalCapacity`|Increase of hospital capacity, measured in hospital beds|Ratio|Number of new beds over number of pre-acquired beds|
