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
|C2|`Capacity Control` |Restriction of the number of people allowed in a store | Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|C3|`Gathering restriction` |limits the size of professional, commercial, or social events and gatherings. | Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|C4|`Isolation` |Mandatory or preventive self-Isolation| Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|C5| `Prohibition` |Restrictions to buy or consume alcohol in public places| Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|C6|`ID Restriction` | Stay-at-home orders or limits access to essential commercial venues, depending on the last digits of the ID. | Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|C7|`Gender Restriction` | Stay-at-home orders or limits access to essential commercial venues, depending on gender. | Binary | <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|C8|`Curfew` | General stay-at-home mandate. | Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|
|C9|`Physicall Activity` |Regulations to allow outside physicall activity| Binary |  <br/>0 -	Measure NOT applied <br/>1 -	Measure applied|



### Index Construction

 Index name | _k_ | C1 | C2 | C3 |  C4 | C5 | C6 | C7 | C8 | C9 | 
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | 
| Applicability Index 1 |  6 | `x` |  `x` |  `x` |  `x` |`x`| | |  `x`|   |  
| Applicability Index 2 |  4 |  |  |  | `x`| |`x` | `x`| |`x` | 
| Mobility Restrictions |  5 | |  |  |`x` | |`x` |`x` |`x` | `x`| 


### Economic policies

| ID | Name | Description | Measurement | Coding |
| --- | --- | --- | --- | --- |
|E1|`In-kind transfers` | Distribution of humanitarian kits, food, or school materials.| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|E2|`Cash Transfers` | Unconditional cash transfers to most vulnerable population.| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|E3|`Tax Discounts` | Discounts on property tax, value added tax and others. | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|E4|`Basic utility discounts` | Partial or complete discounts on households’ basic utility costs. | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|E5|`Budget adjustment` | Adjustment of local government’s budget to respond to the COVID-19 crisis. | Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|E6|`Calamity State Declaration` |Legal declaration of Calamity State| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|E7|`Health Emergency Declaration` |Legal declaration of Health Emergency State|Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|

### Index Construction

 Index name | _k_ | E1 |E2 | E3 | E4 | E5 | E6 | E7 | 
 | --- | --- | --- | --- | --- |---| --- | --- | --- | 
| Economic Support |  4 | `x` | `x` | `x` | `x` | | | |
| Budget Adjustment |  3 | |  |  | |  `x` |  `x` |  `x` | 




### Health system policies

| ID | Name | Description | Measurement | Coding |
| --- | --- | --- | --- | --- |
|H1|`Facemask Use`|Local mandate to use facemask in public spaces. National government instituted this mandate as part of the “Mandatory Isolation” mandate. Local governments had the option of reinforcing the facemask use mandate.| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|H2|`Bio security measures`| Reinforcement of bio security measures, such as hand washing, hand sanitizer use, 2-meter distancing, nose and mouth covering and surface decontamination.| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|H3|`Social Distancing` |Enforcement of social distancing in public places| Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|H4|`Health system capacity`| Mandates specifying investment to increase the health system’s capacity (e.g., acquiring Intensive Care Units, respirators, or supplies). | Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|
|H5|`State of alert`| Local governments declare a general state of alert. | Binary | <br/>0 -  0-	No measure applied. <br/>1 -	Measure Applied|

### Index Construction

 Index name | _k_ | H1 |H2 | H3 | H4 | H5|
 | --- | --- | --- | --- | --- |---| ---| 
| Self Care|  3 | `x` | `x` |  `x`  |  | |
| Health System Strenghtening |  3 |  | | `x` |  `x` |  `x` | 

