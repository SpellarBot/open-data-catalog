# NCHS - Age-adjusted Death Rates for the Top 10 Leading Causes of Death: United States, 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/age-adjusted-death-rates-for-the-top-10-leading-causes-of-death-united-states-2013) |
| Metadata | [Link](https://data.cdc.gov/api/views/bi63-dtpu) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/bi63-dtpu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/bi63-dtpu/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | bi63-dtpu |
| Name | NCHS - Age-adjusted Death Rates for the Top 10 Leading Causes of Death: United States, 2013 |
| Attribution | National Center for Health Statistics |
| Category | NCHS |
| Tags | leading causes of death, mortality, state, united states, nchs |
| Created | 2015-12-02T18:23:53Z |
| Publication Date | 2015-12-02T18:26:47Z |

## Description

Age-adjusted death rates for the top 10 leading causes of death in the United States, including mortality patterns from 1999 through 2013, and by state of residence for selected year and cause of death.
http://blogs.cdc.gov/nchs-data-visualization/leading-causes-of-death/

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | time           | year           | YEAR           | number    | number      |
| Yes      | series tag     | 113_cause_name | 113_CAUSE_NAME | text      | text        |
| Yes      | series tag     | cause_name     | CAUSE_NAME     | text      | text        |
| Yes      | series tag     | state          | STATE          | text      | text        |
| Yes      | numeric metric | deaths         | DEATHS         | number    | number      |
| Yes      | numeric metric | aadr           | AADR           | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bi63-dtpu d:1999-01-01T00:00:00.000Z t:state=Alabama t:cause_name="Unintentional Injuries" t:113_cause_name="Accidents (unintentional injuries) (V01-X59,Y85-Y86)" m:deaths=2313 m:aadr=52.17

series e:bi63-dtpu d:1999-01-01T00:00:00.000Z t:state=Alaska t:cause_name="Unintentional Injuries" t:113_cause_name="Accidents (unintentional injuries) (V01-X59,Y85-Y86)" m:deaths=294 m:aadr=55.91

series e:bi63-dtpu d:1999-01-01T00:00:00.000Z t:state=Arizona t:cause_name="Unintentional Injuries" t:113_cause_name="Accidents (unintentional injuries) (V01-X59,Y85-Y86)" m:deaths=2214 m:aadr=44.79
```

## Meta Commands

```ls
metric m:deaths p:integer l:DEATHS t:dataTypeName=number

metric m:aadr p:float l:AADR t:dataTypeName=number

entity e:bi63-dtpu l:"NCHS - Age-adjusted Death Rates for the Top 10 Leading Causes of Death: United States, 2013" t:attribution="National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/bi63-dtpu

property e:bi63-dtpu t:meta.view v:id=bi63-dtpu v:category=NCHS v:averageRating=0 v:name="NCHS - Age-adjusted Death Rates for the Top 10 Leading Causes of Death: United States, 2013" v:attribution="National Center for Health Statistics"

property e:bi63-dtpu t:meta.view.license v:name="Public Domain"

property e:bi63-dtpu t:meta.view.owner v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:displayName=hku4@cdc.gov

property e:bi63-dtpu t:meta.view.tableauthor v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:roleName=administrator v:displayName=hku4@cdc.gov

property e:bi63-dtpu t:meta.view.metadata.custom_fields.common_core v:Publisher="National Center for Health Statistics" v:Contact_Email=hku4@cdc.gov v:Contact_Name="National Center for Health Statistics" v:Bureau_Code=009:020 v:Program_Code=009:000
```

## Top Records

```ls
| year | 113_cause_name                                       | cause_name             | state                | deaths | aadr  | 
| ==== | ==================================================== | ====================== | ==================== | ====== | ===== | 
| 1999 | Accidents (unintentional injuries) (V01-X59,Y85-Y86) | Unintentional Injuries | Alabama              | 2313   | 52.17 | 
| 1999 | Accidents (unintentional injuries) (V01-X59,Y85-Y86) | Unintentional Injuries | Alaska               | 294    | 55.91 | 
| 1999 | Accidents (unintentional injuries) (V01-X59,Y85-Y86) | Unintentional Injuries | Arizona              | 2214   | 44.79 | 
| 1999 | Accidents (unintentional injuries) (V01-X59,Y85-Y86) | Unintentional Injuries | Arkansas             | 1287   | 47.56 | 
| 1999 | Accidents (unintentional injuries) (V01-X59,Y85-Y86) | Unintentional Injuries | California           | 9198   | 28.71 | 
| 1999 | Accidents (unintentional injuries) (V01-X59,Y85-Y86) | Unintentional Injuries | Colorado             | 1519   | 38.98 | 
| 1999 | Accidents (unintentional injuries) (V01-X59,Y85-Y86) | Unintentional Injuries | Connecticut          | 1034   | 29.31 | 
| 1999 | Accidents (unintentional injuries) (V01-X59,Y85-Y86) | Unintentional Injuries | Delaware             | 267    | 35.25 | 
| 1999 | Accidents (unintentional injuries) (V01-X59,Y85-Y86) | Unintentional Injuries | District of Columbia | 161    | 28.38 | 
| 1999 | Accidents (unintentional injuries) (V01-X59,Y85-Y86) | Unintentional Injuries | Florida              | 5961   | 35.73 | 
```