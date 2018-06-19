# NCHS - Birth Rates for Women Aged 15-17, 17-18, and 15-19: United States, 1960-2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/birth-rates-for-women-aged-15-17-17-18-and-15-19-united-states-1960-2013) |
| Metadata | [Link](https://data.cdc.gov/api/views/rg8a-czmp) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/rg8a-czmp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/rg8a-czmp/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | rg8a-czmp |
| Name | NCHS - Birth Rates for Women Aged 15-17, 17-18, and 15-19: United States, 1960-2015 |
| Attribution | National Center for Health Statistics |
| Category | NCHS |
| Tags | birth rate, women, united states, nchs |
| Created | 2015-12-02T19:26:25Z |
| Publication Date | 2017-08-15T18:25:18Z |

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
series e:rg8a-czmp d:2015-01-01T00:00:00.000Z t:age_group="15-19 years" m:birth_rate=22.3

series e:rg8a-czmp d:2015-01-01T00:00:00.000Z t:age_group="15-17 years" m:birth_rate=9.9

series e:rg8a-czmp d:2015-01-01T00:00:00.000Z t:age_group="18-19 years" m:birth_rate=40.7
```

## Meta Commands

```ls
metric m:birth_rate p:float l:"Birth Rate" t:dataTypeName=number

entity e:rg8a-czmp l:"NCHS - Birth Rates for Women Aged 15-17, 17-18, and 15-19: United States, 1960-2015" t:attribution="National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/rg8a-czmp

property e:rg8a-czmp t:meta.view d:2017-09-25T07:26:57.193Z v:averageRating=0 v:name="NCHS - Birth Rates for Women Aged 15-17, 17-18, and 15-19: United States, 1960-2015" v:attribution="National Center for Health Statistics" v:id=rg8a-czmp v:category=NCHS

property e:rg8a-czmp t:meta.view.license d:2017-09-25T07:26:57.193Z v:name="Public Domain"

property e:rg8a-czmp t:meta.view.owner d:2017-09-25T07:26:57.193Z v:displayName=NCHS v:lastNotificationSeenAt=1503441408 v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:id=ki96-txhe v:screenName=NCHS v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB

property e:rg8a-czmp t:meta.view.tableauthor d:2017-09-25T07:26:57.193Z v:displayName=NCHS v:lastNotificationSeenAt=1503441408 v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:roleName=administrator v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:id=ki96-txhe v:screenName=NCHS v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB

property e:rg8a-czmp t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:26:57.193Z v:Contact_Email=nchsdata@cdc.gov v:Contact_Name="National Center for Health Statistics" v:Program_Code=009:020 v:Publisher="National Center for Health Statistics" v:Bureau_Code=009:00
```

## Top Records

```ls
| year | age_group   | birth_rate | 
| ==== | =========== | ========== | 
| 2015 | 15-19 years | 22.3       | 
| 2015 | 15-17 years | 9.9        | 
| 2015 | 18-19 years | 40.7       | 
| 2014 | 15-19 years | 24.2       | 
| 2014 | 15-17 years | 10.9       | 
| 2014 | 18-19 years | 43.8       | 
| 2013 | 15-19 years | 26.5       | 
| 2013 | 15-17 years | 12.3       | 
| 2013 | 18-19 years | 47.1       | 
| 2012 | 15-19 years | 29.4       | 
```