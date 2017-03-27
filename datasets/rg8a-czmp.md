# NCHS - Birth Rates for Women Aged 15-17, 17-18, and 15-19: United States, 1960-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/birth-rates-for-women-aged-15-17-17-18-and-15-19-united-states-1960-2013) |
| Metadata | [Link](https://data.cdc.gov/api/views/rg8a-czmp) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/rg8a-czmp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/rg8a-czmp/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | rg8a-czmp |
| Name | NCHS - Birth Rates for Women Aged 15-17, 17-18, and 15-19: United States, 1960-2013 |
| Attribution | National Center for Health Statistics |
| Category | NCHS |
| Tags | birth rate, women, united states, nchs |
| Created | 2015-12-02T19:26:25Z |
| Publication Date | 2015-12-02T19:31:05Z |

## Description

http://blogs.cdc.gov/nchs-data-visualization/us-natality-trends/

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | time           | year       | Year       | number    | number      |
| Yes      | series tag     | age_group  | Age Group  | text      | text        |
| Yes      | numeric metric | birth_rate | Birth Rate | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rg8a-czmp d:1960-01-01T00:00:00.000Z t:age_group="15-17 years" m:birth_rate=43.9

series e:rg8a-czmp d:1961-01-01T00:00:00.000Z t:age_group="15-17 years" m:birth_rate=43.8

series e:rg8a-czmp d:1962-01-01T00:00:00.000Z t:age_group="15-17 years" m:birth_rate=38.1
```

## Meta Commands

```ls
metric m:birth_rate p:float l:"Birth Rate" t:dataTypeName=number

entity e:rg8a-czmp l:"NCHS - Birth Rates for Women Aged 15-17, 17-18, and 15-19: United States, 1960-2013" t:attribution="National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/rg8a-czmp

property e:rg8a-czmp t:meta.view v:id=rg8a-czmp v:category=NCHS v:averageRating=0 v:name="NCHS - Birth Rates for Women Aged 15-17, 17-18, and 15-19: United States, 1960-2013" v:attribution="National Center for Health Statistics"

property e:rg8a-czmp t:meta.view.license v:name="Public Domain"

property e:rg8a-czmp t:meta.view.owner v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:displayName=hku4@cdc.gov

property e:rg8a-czmp t:meta.view.tableauthor v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:roleName=administrator v:displayName=hku4@cdc.gov

property e:rg8a-czmp t:meta.view.metadata.custom_fields.common_core v:Publisher="National Center for Health Statistics" v:Contact_Email=hku4@cdc.gov v:Contact_Name="National Center for Health Statistics" v:Bureau_Code=009:020 v:Program_Code=009:000
```