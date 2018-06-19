# DCEO IL Coal Plants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dceo-il-coal-plants-8fd9a) |
| Metadata | [Link](https://data.illinois.gov/api/views/eh9z-teyr) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/eh9z-teyr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/eh9z-teyr/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | eh9z-teyr |
| Name | DCEO IL Coal Plants |
| Category | Economics |
| Tags | coal plants |
| Created | 2012-01-27T21:53:13Z |
| Publication Date | 2012-01-27T21:56:30Z |

## Description

Illinois Coal Plants

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type | Render Type |
| ======== | ============== | =================================== | =================================== | ========= | =========== |
| No       | time           | :updated_at                         | updated_at                          | meta_data | meta_data   |
| Yes      | series tag     | plant_operator                      | Plant Operator                      | text      | text        |
| Yes      | series tag     | plant_name                          | Plant Name                          | text      | text        |
| Yes      | series tag     | year_built                          | Year Built                          | text      | text        |
| Yes      | series tag     | county                              | County                              | text      | text        |
| Yes      | numeric metric | generation_capacity                 | Generation Capacity                 | number    | number      |
| Yes      | numeric metric | coal_used_1_000_tons_               | 2009 Coal Used(1,000 tons)          | number    | number      |
| Yes      | numeric metric | il_coal_1_000_tons_                 | IL Coal (1,000 tons)                | number    | number      |
| Yes      | numeric metric | prb_coal_1_000_tons_                | PRB Coal (1,000 tons)               | number    | number      |
| Yes      | series tag     | possible_terminating_transportation | Possible terminating transportation | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:eh9z-teyr d:2012-01-27T13:53:23.000Z t:year_built=1995 t:county=Montgomery t:possible_terminating_transportation=NS t:plant_operator="AmerenEnergy Generating" t:plant_name=Coffeen m:generation_capacity=900 m:coal_used_1_000_tons_=2627 m:prb_coal_1_000_tons_=2484 m:il_coal_1_000_tons_=143

series e:eh9z-teyr d:2012-01-27T13:53:23.000Z t:year_built=1953 t:county=Massac t:possible_terminating_transportation=UP t:plant_operator="AmerenEnergy Generating" t:plant_name="Electric Energy - Joppa" m:generation_capacity=1000 m:coal_used_1_000_tons_=4228 m:prb_coal_1_000_tons_=4288 m:il_coal_1_000_tons_=0

series e:eh9z-teyr d:2012-01-27T13:53:23.000Z t:year_built=1953 t:county=Crawford t:possible_terminating_transportation=BNSF t:plant_operator="AmerenEnergy Generating" t:plant_name=Hutsonville m:generation_capacity=156 m:coal_used_1_000_tons_=255 m:prb_coal_1_000_tons_=255 m:il_coal_1_000_tons_=0
```

## Meta Commands

```ls
metric m:generation_capacity p:integer l:"Generation Capacity" t:dataTypeName=number

metric m:coal_used_1_000_tons_ p:integer l:"2009 Coal Used(1,000 tons)" t:dataTypeName=number

metric m:il_coal_1_000_tons_ p:integer l:"IL Coal (1,000 tons)" t:dataTypeName=number

metric m:prb_coal_1_000_tons_ p:integer l:"PRB Coal (1,000 tons)" t:dataTypeName=number

entity e:eh9z-teyr l:"DCEO IL Coal Plants" t:url=https://data.illinois.gov/api/views/eh9z-teyr

property e:eh9z-teyr t:meta.view v:id=eh9z-teyr v:category=Economics v:averageRating=0 v:name="DCEO IL Coal Plants"

property e:eh9z-teyr t:meta.view.owner v:id=t6h9-hze3 v:screenName=Nicole v:displayName=Nicole

property e:eh9z-teyr t:meta.view.tableauthor v:id=t6h9-hze3 v:screenName=Nicole v:roleName=publisher v:displayName=Nicole
```

## Top Records

```ls
| :updated_at | plant_operator               | plant_name              | year_built             | county     | generation_capacity | coal_used_1_000_tons_ | il_coal_1_000_tons_ | prb_coal_1_000_tons_ | possible_terminating_transportation | 
| =========== | ============================ | ======================= | ====================== | ========== | =================== | ===================== | =================== | ==================== | =================================== | 
| 1327672403  | Plant Operator               | Plant Name              | Year Built             | County     |                     |                       |                     |                      | Possible terminating transportation | 
| 1327672403  | AmerenEnergy Generating      | Coffeen                 | 1995                   | Montgomery | 900                 | 2627                  | 143                 | 2484                 | NS                                  | 
| 1327672403  | AmerenEnergy Generating      | Electric Energy - Joppa | 1953                   | Massac     | 1000                | 4228                  | 0                   | 4288                 | UP                                  | 
| 1327672403  | AmerenEnergy Generating      | Hutsonville             | 1953                   | Crawford   | 156                 | 255                   | 0                   | 255                  | BNSF                                | 
| 1327672403  | AmerenEnergy Generating      | Meredosia               | 1948                   | Morgan     | 513                 | 329                   | 0                   | 329                  | BG, TK                              | 
| 1327672403  | AmerenEnergy Generating      | Newton                  | 1977                   | Jasper     | 1151                | 4927                  | 0                   | 4927                 | CN                                  | 
| 1327672403  | AmerenEnergy Resources       | Duck Creek              | 1976                   | Fulton     | 349                 | 1100                  | 410                 | 690                  | BNSF, TK                            | 
| 1327672403  | AmerenEnergy Resources       | E.D. Edwards            | 1,960                  | Peoria     | 749                 | 2966                  | 0                   | 2966                 | UP                                  | 
| 1327672403  | City of Springfield          | Dallman                 | 1968, 1972, 1978, 2009 | Sangamon   | 548                 | 1053                  | 1053                | 0                    | TK                                  | 
| 1327672403  | Dominion Energy Services Co. | Kincaid                 | 1967, 1968             | Christian  | 1158                | 4237                  | 0                   | 4237                 | I&M                                 | 
```