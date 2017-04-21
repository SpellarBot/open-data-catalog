# Energy Efficiency Annual Energy Savings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-efficiency-annual-energy-savings) |
| Metadata | [Link](https://data.austintexas.gov/api/views/fw3c-w5de) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/fw3c-w5de/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/fw3c-w5de/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | fw3c-w5de |
| Name | Energy Efficiency Annual Energy Savings |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | austin energy, energy efficiency, energy savings, home performance with energy star, applicance efficiency program, free weatherization, power partner thermostat |
| Created | 2016-06-24T18:47:44Z |
| Publication Date | 2016-06-24T19:00:24Z |

## Description

Austin Energy provides rebates and low interest loans to customers who make energy efficiency improvements.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| No       | time           | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag     | program      | Program      | text      | text        |
| Yes      | numeric metric | 1982_2007    | 1982-2007    | number    | number      |
| Yes      | numeric metric | 2008         | 2008         | number    | number      |
| Yes      | numeric metric | 2009         | 2009         | number    | number      |
| Yes      | numeric metric | 2010         | 2010         | number    | number      |
| Yes      | numeric metric | 2011         | 2011         | number    | number      |
| Yes      | numeric metric | 2012         | 2012         | number    | number      |
| Yes      | series tag     | program_type | Program type | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fw3c-w5de d:2016-06-24T11:47:49.000Z t:program_type="Residential Efficiency" t:program="Appliance Efficiency Program" m:1982_2007=131552388 m:2008=4091910 m:2009=4541960 m:2012=4631414.76 m:2011=6204552.82 m:2010=5352865.64

series e:fw3c-w5de d:2016-06-24T11:47:49.000Z t:program_type="Residential Efficiency" t:program="Home Performance with Energy Star - Rebate" m:1982_2007=63528814 m:2008=4390425 m:2009=4864425 m:2012=4348950 m:2011=5765025 m:2010=5808475

series e:fw3c-w5de d:2016-06-24T11:47:49.000Z t:program_type="Residential Efficiency" t:program="Home Performance with Energy Star - Loan" m:1982_2007=48651690 m:2008=420675 m:2009=377225 m:2012=67150 m:2011=140225 m:2010=215275
```

## Meta Commands

```ls
metric m:1982_2007 p:double l:1982-2007 t:dataTypeName=number

metric m:2008 p:double l:2008 t:dataTypeName=number

metric m:2009 p:double l:2009 t:dataTypeName=number

metric m:2010 p:double l:2010 t:dataTypeName=number

metric m:2011 p:double l:2011 t:dataTypeName=number

metric m:2012 p:double l:2012 t:dataTypeName=number

entity e:fw3c-w5de l:"Energy Efficiency Annual Energy Savings" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/fw3c-w5de

property e:fw3c-w5de t:meta.view v:id=fw3c-w5de v:category=Utility v:averageRating=0 v:name="Energy Efficiency Annual Energy Savings" v:attribution="Austin Energy"

property e:fw3c-w5de t:meta.view.license v:name="Public Domain"

property e:fw3c-w5de t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:fw3c-w5de t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| :updated_at | program                                    | 1982_2007 | 2008     | 2009             | 2010             | 2011       | 2012             | program_type           | 
| =========== | ========================================== | ========= | ======== | ================ | ================ | ========== | ================ | ====================== | 
| 1466768869  | Appliance Efficiency Program               | 131552388 | 4091910  | 4541960          | 5352865.64       | 6204552.82 | 4631414.76       | Residential Efficiency | 
| 1466768869  | Home Performance with Energy Star - Rebate | 63528814  | 4390425  | 4864425          | 5808475          | 5765025    | 4348950          | Residential Efficiency | 
| 1466768869  | Home Performance with Energy Star - Loan   | 48651690  | 420675   | 377225           | 215275           | 140225     | 67150            | Residential Efficiency | 
| 1466768869  | Free Weatherization                        | 15510490  | 551965   | 588034           | 498408           | 1141092    | 1143278          | Residential Efficiency | 
| 1466768869  | Multi-Family                               | 75851290  | 23847000 | 11359498.2017881 | 13231309.7939048 | 7197412.6  | 7885592.6532     | Residential Efficiency | 
| 1466768869  | Clothes Washer Rebates                     | 1993480   | 234144   | 252864           | 296352           | 186336     | 119232           | Residential Efficiency | 
| 1466768869  | Duct Leaks Seal/Diagnosis                  | 4398200   | 0        | 0                | 0                | 0          | 0                | Residential Efficiency | 
| 1466768869  | Refrigeration Recycling                    | 7578359   | 2925390  | 2667665          | 2529864          | 2057157    | 1667974.83333333 | Residential Efficiency | 
| 1466768869  | Power Partner Program                      | 766865    | 97353.2  | 76822.2          | 45246.6          | 14807.8    | 8731.8           | Residential Efficiency | 
| 1466768869  | Cycle Saver Program                        | 619174.56 | 7422     | 10092            | 12054            | 5682       | 3522             | Residential Efficiency | 
```