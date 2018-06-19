# NCHS - Births, Birth Rates, and Fertility Rates, by Race and Hispanic Origin of Mother: United States, 1989-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/births-birth-rates-and-fertility-rates-by-race-and-hispanic-origin-of-mother-united-s-1989) |
| Metadata | [Link](https://data.cdc.gov/api/views/s54h-bixi) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/s54h-bixi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/s54h-bixi/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | s54h-bixi |
| Name | NCHS - Births, Birth Rates, and Fertility Rates, by Race and Hispanic Origin of Mother: United States, 1989-2013 |
| Attribution | National Center for Health Statistics |
| Category | NCHS |
| Tags | birth, birth rate, fertility rate, race, hispanic origin, united states, nchs |
| Created | 2015-12-02T19:20:15Z |
| Publication Date | 2015-12-02T19:24:11Z |

## Description

http://blogs.cdc.gov/nchs-data-visualization/us-natality-trends/

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | time           | year            | Year            | number    | number      |
| Yes      | series tag     | hispanic_origin | Hispanic Origin | text      | text        |
| Yes      | numeric metric | live_births     | Live Births     | number    | number      |
| Yes      | numeric metric | birth_rates     | Birth Rates     | number    | number      |
| Yes      | numeric metric | fertility_rates | Fertility Rates | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:s54h-bixi d:1989-01-01T00:00:00.000Z t:hispanic_origin="All origins" m:fertility_rates=69.2 m:live_births=3903012 m:birth_rates=16.3

series e:s54h-bixi d:1989-01-01T00:00:00.000Z t:hispanic_origin="Central and South American" m:fertility_rates=95.8 m:live_births=72443 m:birth_rates=28.3

series e:s54h-bixi d:1989-01-01T00:00:00.000Z t:hispanic_origin=Cuban m:fertility_rates=49.8 m:live_births=10842 m:birth_rates=10
```

## Meta Commands

```ls
metric m:live_births p:integer l:"Live Births" t:dataTypeName=number

metric m:birth_rates p:float l:"Birth Rates" t:dataTypeName=number

metric m:fertility_rates p:float l:"Fertility Rates" t:dataTypeName=number

entity e:s54h-bixi l:"NCHS - Births, Birth Rates, and Fertility Rates, by Race and Hispanic Origin of Mother: United States, 1989-2013" t:attribution="National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/s54h-bixi

property e:s54h-bixi t:meta.view v:id=s54h-bixi v:category=NCHS v:averageRating=0 v:name="NCHS - Births, Birth Rates, and Fertility Rates, by Race and Hispanic Origin of Mother: United States, 1989-2013" v:attribution="National Center for Health Statistics"

property e:s54h-bixi t:meta.view.license v:name="Public Domain"

property e:s54h-bixi t:meta.view.owner v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:displayName=hku4@cdc.gov

property e:s54h-bixi t:meta.view.tableauthor v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:roleName=administrator v:displayName=hku4@cdc.gov

property e:s54h-bixi t:meta.view.metadata.custom_fields.common_core v:Publisher="National Center for Health Statistics" v:Contact_Email=hku4@cdc.gov v:Contact_Name="National Center for Health Statistics" v:Bureau_Code=009:020 v:Program_Code=009:000
```

## Top Records

```ls
| year | hispanic_origin            | live_births | birth_rates | fertility_rates | 
| ==== | ========================== | =========== | =========== | =============== | 
| 1989 | All origins                | 3903012     | 16.3        | 69.2            | 
| 1989 | Central and South American | 72443       | 28.3        | 95.8            | 
| 1989 | Cuban                      | 10842       | 10          | 49.8            | 
| 1989 | Mexican                    | 327233      | 25.7        | 106.6           | 
| 1989 | Non-Hispanic Black         | 611269      | 22.8        | 84.8            | 
| 1989 | Non-Hispanic White         | 2526367     | 14.2        | 60.5            | 
| 1989 | Other and unknown Hispanic | 65502       |             |                 | 
| 1989 | Puerto Rican               | 56229       | 23.7        | 86.6            | 
| 1989 | Total Hispanic             | 532249      | 26.2        | 104.9           | 
| 1989 | Total Non-Hispanic         | 3297493     | 15.4        | 65.7            | 
```