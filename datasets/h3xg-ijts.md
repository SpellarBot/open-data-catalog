# Power Pole Accidents

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/power-pole-accidents) |
| Metadata | [Link](https://data.austintexas.gov/api/views/h3xg-ijts) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/h3xg-ijts/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/h3xg-ijts/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | h3xg-ijts |
| Name | Power Pole Accidents |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | austin energy, power pole, power pole accidents, hit poles, hit pole, streetlight accidents |
| Created | 2016-05-12T18:13:24Z |
| Publication Date | 2016-05-16T16:20:20Z |

## Description

Each year, streetlights and power poles in the Austin Energy service territory are hit by drivers and require repair. There is considerable variability in the cost of repairing each pole, as the amount of damage varies per incident. This is the reason the costs for repairs can vary significantly from year to year. 

Austin Energy bears the costs until they are offset by the amounts collected from the drivers and their insurance companies. In cases where a responsible party cannot be identified (leaving the scene of the incident), or in cases where it cannot be verified that they are at fault, Austin Energy must pay for the repairs. Austin Energy works with the Austin Police Department to identify drivers who have fled the scene of an accident.

## Columns

```ls
| Included | Schema Type    | Field Name                                      | Name                                            | Data Type | Render Type |
| ======== | ============== | =============================================== | =============================================== | ========= | =========== |
| Yes      | time           | fiscal_year                                     | Fiscal Year                                     | number    | number      |
| Yes      | series tag     | streetlight_poles_hit                           | Streetlight poles hit                           | text      | number      |
| Yes      | series tag     | streetlight_poles_cost_of_repair_or_replacement | Streetlight poles cost of repair or replacement | text      | money       |
| Yes      | numeric metric | power_poles_hit                                 | Power poles hit                                 | number    | number      |
| Yes      | numeric metric | power_poles_cost_of_repair_or_replacement       | Power poles cost of repair or Replacement       | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:h3xg-ijts d:2012-01-01T00:00:00.000Z t:streetlight_poles_hit=92 t:streetlight_poles_cost_of_repair_or_replacement=92823.28 m:power_poles_cost_of_repair_or_replacement=448998.46 m:power_poles_hit=228

series e:h3xg-ijts d:2011-01-01T00:00:00.000Z t:streetlight_poles_hit=113 t:streetlight_poles_cost_of_repair_or_replacement=185673.26 m:power_poles_cost_of_repair_or_replacement=481377.34 m:power_poles_hit=166

series e:h3xg-ijts d:2010-01-01T00:00:00.000Z t:streetlight_poles_hit=122 t:streetlight_poles_cost_of_repair_or_replacement=164554.87 m:power_poles_cost_of_repair_or_replacement=484533.43 m:power_poles_hit=172
```

## Meta Commands

```ls
metric m:power_poles_hit p:integer l:"Power poles hit" t:dataTypeName=number

metric m:power_poles_cost_of_repair_or_replacement p:double l:"Power poles cost of repair or Replacement" t:dataTypeName=money

entity e:h3xg-ijts l:"Power Pole Accidents" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/h3xg-ijts

property e:h3xg-ijts t:meta.view v:id=h3xg-ijts v:category=Utility v:averageRating=0 v:name="Power Pole Accidents" v:attribution="Austin Energy"

property e:h3xg-ijts t:meta.view.license v:name="Public Domain"

property e:h3xg-ijts t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:h3xg-ijts t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| fiscal_year | streetlight_poles_hit | streetlight_poles_cost_of_repair_or_replacement | power_poles_hit | power_poles_cost_of_repair_or_replacement | 
| =========== | ===================== | =============================================== | =============== | ========================================= | 
| 2012        | 92                    | 92823.28                                        | 228             | 448998.46                                 | 
| 2011        | 113                   | 185673.26                                       | 166             | 481377.34                                 | 
| 2010        | 122                   | 164554.87                                       | 172             | 484533.43                                 | 
| 2009        | 134                   | 318116.14                                       | 137             | 476947.47                                 | 
| 2008        | 203                   | 446422.37                                       | 130             | 286254.20                                 | 
| 2007        | 212                   | 237707.15                                       | 110             | 274708.93                                 | 
| 2006        | 161                   | 248662.41                                       | 143             | 379363.10                                 | 
| 2013        | 109                   | 262059.38                                       | 214             | 666524.88                                 | 
| 2014        | 151                   | 307201.44                                       | 141             | 522018.48                                 | 
| 2015        | 216                   | 540908.92                                       | 137             | 648112.17                                 | 
```