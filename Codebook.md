# Codebook of Colombian subnational policies
---
*Index Methodology*

*4 March 2021*

This codebooks shows the process in which indices are built in four main types of measures:

- [C - Containment Policies](#containment-policies)
- [E - Economic Policies](#economic-policies)
- [H - Health Policies](#health-policies)

---
### Containment Policies

| ID | Name | Description | Measurement | Coding |
| -- | --- | --- | --- | --- |
|C1|`Mobility Restrictions` |Restrictions to move inside or outside the municipality| Binary | <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|C2|`Capacity Control` |Restriction of the number of people allowed in a store| Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|C3|`Social Gatherings` |Restriction of the number of people allowed in an event| Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|C4|`Isolation` |Mandatory or preventive self-Isolation| Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|C5| `Prohibition` |Restrictions to buy or consume alcohol in public places| Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|C6|`ID Restrictions` |Restrictions to go outside based on the last number of the ID card| Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|C7|`Gender Restrictions` |Restrictions to go outside based on Gender| Binary | <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|C8|`Curfew` |Implementation of Curfew| Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|C9|`Physicall Activity` |Regulations to allow outside physicall activity| Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
=======
|C1|`Mobility Restrictions` |Restrictions to move inside or outside the municipality| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|C2|`Capacity Control` |Restriction of the number of people allowed in a store| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|C3|`Social Gatherings` |Restriction of the number of people allowed in an event| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|C4|`Isolation` |Mandatory or preventive self-Isolation| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|C5| `Prohibition` |Restrictions to buy or consume alcohol in public places| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|C6|`ID Restrictions` |Restrictions to go outside based on the last number of the ID card| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|C7|`Gender Restrictions` |Restrictions to go outside based on Gender| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|C8|`Curfew` |Implementation of Curfew| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|C9|`Physicall Activity` |Regulations to allow outside physicall activity| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|


### Index Construction

 Index name | _k_ | C1 | C2 | C3 |  C4 | C5 | C6 | C7 | C8 | C9 | 
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | 
| Applicability Index 1 |  6 | `x` |  `x` |  `x` |  `x` |`x`| | |  `x`|   |  
| Applicability Index 2 |  4 |  |  |  | `x`| |`x` | `x`| |`x` | 
| Mobility Restrictions |  5 | |  |  |`x` | |`x` |`x` |`x` | `x`| 


### Economic Policies

| ID | Name | Description | Measurement | Coding |
| --- | --- | --- | --- | --- |
|E1|`Transfers in Kind` | Transfers of goods| Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|E2|`Monetary Transfers` |Transfers of money| Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|E3|`Tax Discount` |Discounts or period extension to pay a tax| Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|E4|`Guarantee of Public Services` |Reinstalation and guarantee of services, even if unpaid|Binary | <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|E5|`Budget Transfers` |Budget adjustments inside the administration| Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|E6|`Calamity State Declaration` |Legal declaration of Calamity State| Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|E7|`Health Emergency Declaration` |Legal declaration of Health Emergency State|Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
=======
| Aplicability Index 1 |  8 | `x` |  `x` |  `x` |  `x` |`x`| | |  `x`|   |  
| Aplicability Index 2 |  4 |  |  |  | `x`| |`x` | `x`| |`x` | 
| Mobility Restrictions |  7 | |  |  |`x` | |`x` |`x` |`x` | `x`| 


### Economic policies

| ID | Name | Description | Measurement | Coding |
| --- | --- | --- | --- | --- |
|E1|`Transfers in Kind` | Transfers of goods| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|E2|`Monetary Transfers` |Transfers of money| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|E3|`Tax Discount` |Discounts or period extension to pay a tax| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|E4|`Guarantee of Public Services` |Reinstalation and guarantee of services, even if unpaid|Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|E5|`Budget Transfers` |Budget adjustments inside the administration| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|E6|`Calamity State Declaration` |Legal declaration of Calamity State| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|E7|`Health Emergency Declaration` |Legal declaration of Health Emergency State|Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|

### Index Construction

 Index name | _k_ | E1 |E2 | E3 | E4 | E5 | E6 | E7 | 
 | --- | --- | --- | --- | --- |---| --- | --- | --- | 
| Economic Support |  4 | `x` | `x` | `x` | `x` | | | |
| Budget Adjustment |  3 | |  |  | |  `x` |  `x` |  `x` | 

### Health Policies

| ID | Name | Description | Measurement | Coding |
| --- | --- | --- | --- | --- |
|H1|`Mask Use`|Mandatory Mask Use| Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|H2|`Biosafety Measures`|Implementation of safety measures in commerce establishments| Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|H3|`Social Distancing` |Enforcement of social distancing in public places| Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|H4|`Hospital Capacity Increase`|Acquisition of hospitalary elements, such as beds or respirators| Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|H5|`State of Alert`|Legal declaration of State of Alert| Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
=======
### Health system policies

| ID | Name | Description | Measurement | Coding |
| --- | --- | --- | --- | --- |
|H1|`Mask Use`|Mandatory Mask Use| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|H2|`Biosafety Measures`|Implementation of safety measures in commerce establishments| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|H3|`Social Distancing` |Enforcement of social distancing in public places| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|H4|`Hospital Capacity Increase`|Acquisition of hospitalary elements, such as beds or respirators| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|H5|`State of Alert`|Legal declaration of State of Alert| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|

### Index Construction

 Index name | _k_ | H1 |H2 | H3 | H4 | H5|
 | --- | --- | --- | --- | --- |---| ---| 
| Self Care|  3 | `x` | `x` |  `x`  |  | |
| Health System Strenghtening |  3 |  | | `x` |  `x` |  `x` | 

