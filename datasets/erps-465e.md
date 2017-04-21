# Austin Energy Operating Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-energy-operating-budget) |
| Metadata | [Link](https://data.austintexas.gov/api/views/erps-465e) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/erps-465e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/erps-465e/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | erps-465e |
| Name | Austin Energy Operating Budget |
| Attribution | Austin Energy |
| Category | Utility |
| Created | 2015-08-17T18:56:26Z |
| Publication Date | 2016-09-06T15:54:57Z |

## Description

Austin Energy Operating Fund - Actual Dollars

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | time           | fiscal_year           | Fiscal Year           | number    | number      |
| Yes      | numeric metric | total_available_funds | Total Available Funds | money     | money       |
| Yes      | numeric metric | total_requirements    | Total Requirements    | money     | money       |
| Yes      | numeric metric | excess_deficiency     | Excess/Deficiency     | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:erps-465e d:2013-01-01T00:00:00.000Z m:excess_deficiency=62155465 m:total_requirements=1257770945 m:total_available_funds=1319926410

series e:erps-465e d:2012-01-01T00:00:00.000Z m:excess_deficiency=-7517906 m:total_requirements=1219053608 m:total_available_funds=1211535702

series e:erps-465e d:2011-01-01T00:00:00.000Z m:excess_deficiency=2835944 m:total_requirements=1256452643 m:total_available_funds=1259288587
```

## Meta Commands

```ls
metric m:total_available_funds p:integer l:"Total Available Funds" t:dataTypeName=money

metric m:total_requirements p:integer l:"Total Requirements" t:dataTypeName=money

metric m:excess_deficiency p:integer l:Excess/Deficiency t:dataTypeName=money

entity e:erps-465e l:"Austin Energy Operating Budget" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/erps-465e

property e:erps-465e t:meta.view v:id=erps-465e v:category=Utility v:averageRating=0 v:name="Austin Energy Operating Budget" v:attribution="Austin Energy"

property e:erps-465e t:meta.view.license v:name="Public Domain"

property e:erps-465e t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:erps-465e t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| fiscal_year | total_available_funds | total_requirements | excess_deficiency | 
| =========== | ===================== | ================== | ================= | 
| 2013        | 1319926410            | 1257770945         | 62155465          | 
| 2012        | 1211535702            | 1219053608         | -7517906          | 
| 2011        | 1259288587            | 1256452643         | 2835944           | 
| 2010        | 1161438931            | 1247517927         | -86078996         | 
| 2009        | 1224290869            | 1300176900         | -75866031         | 
| 2008        | 1311492272            | 1248009469         | 63482803          | 
| 2007        | 1111693319            | 1066420724         | 45272595          | 
| 2014        | 1391240664            | 1371356935         | 19883729          | 
| 2015        | 1363348289            | 1337122101         | 26226188          | 
```