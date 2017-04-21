# NCHS - Birth Rates, by Age and Race and Hispanic Origin: United States, 1989-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/birth-rates-by-age-and-race-and-hispanic-origin-united-states-1989-2013) |
| Metadata | [Link](https://data.cdc.gov/api/views/e8kx-wbww) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/e8kx-wbww/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/e8kx-wbww/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | e8kx-wbww |
| Name | NCHS - Birth Rates, by Age and Race and Hispanic Origin: United States, 1989-2013 |
| Attribution | National Center for Health Statistics |
| Category | NCHS |
| Tags | birth rate, age, race, united states, nchs |
| Created | 2015-12-02T19:36:56Z |
| Publication Date | 2015-12-02T19:39:23Z |

## Description

http://blogs.cdc.gov/nchs-data-visualization/us-natality-trends/

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | time           | year       | Year       | number    | number      |
| Yes      | series tag     | race       | Race       | text      | text        |
| Yes      | numeric metric | birth_rate | Birth Rate | number    | number      |
| Yes      | series tag     | age        | Age        | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:e8kx-wbww d:1991-01-01T00:00:00.000Z t:age=18-19 t:race=Hispanic m:birth_rate=155.5

series e:e8kx-wbww d:2005-01-01T00:00:00.000Z t:age=18-19 t:race=Hispanic m:birth_rate=124.4

series e:e8kx-wbww d:2007-01-01T00:00:00.000Z t:age=18-19 t:race=Hispanic m:birth_rate=124.7
```

## Meta Commands

```ls
metric m:birth_rate p:float l:"Birth Rate" t:dataTypeName=number

entity e:e8kx-wbww l:"NCHS - Birth Rates, by Age and Race and Hispanic Origin: United States, 1989-2013" t:attribution="National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/e8kx-wbww

property e:e8kx-wbww t:meta.view v:id=e8kx-wbww v:category=NCHS v:averageRating=0 v:name="NCHS - Birth Rates, by Age and Race and Hispanic Origin: United States, 1989-2013" v:attribution="National Center for Health Statistics"

property e:e8kx-wbww t:meta.view.license v:name="Public Domain"

property e:e8kx-wbww t:meta.view.owner v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:displayName=hku4@cdc.gov

property e:e8kx-wbww t:meta.view.tableauthor v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:roleName=administrator v:displayName=hku4@cdc.gov

property e:e8kx-wbww t:meta.view.metadata.custom_fields.common_core v:Publisher="National Center for Health Statistics" v:Contact_Email=hku4@cdc.gov v:Contact_Name="National Center for Health Statistics" v:Bureau_Code=009:020 v:Program_Code=009:000
```

## Top Records

```ls
| year | race                      | birth_rate | age   | 
| ==== | ========================= | ========== | ===== | 
| 1991 | Hispanic                  | 155.5      | 18-19 | 
| 2005 | Hispanic                  | 124.4      | 18-19 | 
| 2007 | Hispanic                  | 124.7      | 18-19 | 
| 2009 | Hispanic                  | 114        | 18-19 | 
| 2010 | Hispanic                  | 90.7       | 18-19 | 
| 2011 | Hispanic                  | 81.5       | 18-19 | 
| 1991 | Asian or Pacific Islander | 42.2       | 18-19 | 
| 2005 | Asian or Pacific Islander | 26.4       | 18-19 | 
| 2007 | Asian or Pacific Islander | 24.9       | 18-19 | 
| 2009 | Asian or Pacific Islander | 20.9       | 18-19 | 
```