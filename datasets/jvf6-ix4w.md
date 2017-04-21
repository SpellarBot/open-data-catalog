# NCHS - Nonmarital Birth Rates, by Age Group for All Women Age 15-44: United States, 1980-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nonmarital-birth-rates-by-age-group-for-all-women-age-15-44-united-states-1980-2013) |
| Metadata | [Link](https://data.cdc.gov/api/views/jvf6-ix4w) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/jvf6-ix4w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/jvf6-ix4w/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | jvf6-ix4w |
| Name | NCHS - Nonmarital Birth Rates, by Age Group for All Women Age 15-44: United States, 1980-2013 |
| Attribution | National Center for Health Statistics |
| Category | NCHS |
| Tags | birth rates, age group, women, united states, nchs |
| Created | 2015-12-02T20:12:32Z |
| Publication Date | 2015-12-02T20:14:37Z |

## Description

http://blogs.cdc.gov/nchs-data-visualization/nonmarital-births/

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | time           | year       | Year       | number    | number      |
| Yes      | series tag     | age        | Age        | text      | text        |
| Yes      | series tag     | race       | Race       | text      | text        |
| Yes      | numeric metric | birth_rate | Birth Rate | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jvf6-ix4w d:1970-01-01T00:00:00.000Z t:age=15-17 t:race="All Races" m:birth_rate=17.1

series e:jvf6-ix4w d:1970-01-01T00:00:00.000Z t:age=15-19 t:race="All Races" m:birth_rate=22.4

series e:jvf6-ix4w d:1970-01-01T00:00:00.000Z t:age=15-44 t:race="All Races" m:birth_rate=26.4
```

## Meta Commands

```ls
metric m:birth_rate p:float l:"Birth Rate" t:dataTypeName=number

entity e:jvf6-ix4w l:"NCHS - Nonmarital Birth Rates, by Age Group for All Women Age 15-44: United States, 1980-2013" t:attribution="National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/jvf6-ix4w

property e:jvf6-ix4w t:meta.view v:id=jvf6-ix4w v:category=NCHS v:averageRating=0 v:name="NCHS - Nonmarital Birth Rates, by Age Group for All Women Age 15-44: United States, 1980-2013" v:attribution="National Center for Health Statistics"

property e:jvf6-ix4w t:meta.view.license v:name="Public Domain"

property e:jvf6-ix4w t:meta.view.owner v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:displayName=hku4@cdc.gov

property e:jvf6-ix4w t:meta.view.tableauthor v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:roleName=administrator v:displayName=hku4@cdc.gov

property e:jvf6-ix4w t:meta.view.metadata.custom_fields.common_core v:Publisher="National Center for Health Statistics" v:Contact_Email=hku4@cdc.gov v:Contact_Name="National Center for Health Statistics" v:Bureau_Code=009:020 v:Program_Code=009:000
```

## Top Records

```ls
| year | age   | race      | birth_rate | 
| ==== | ===== | ========= | ========== | 
| 1970 | 15-17 | All Races | 17.1       | 
| 1970 | 15-19 | All Races | 22.4       | 
| 1970 | 15-44 | All Races | 26.4       | 
| 1970 | 18-19 | All Races | 32.9       | 
| 1970 | 20-24 | All Races | 38.4       | 
| 1970 | 25-29 | All Races | 37.0       | 
| 1970 | 30-34 | All Races | 27.1       | 
| 1970 | 35-39 | All Races | 13.6       | 
| 1970 | 40-44 | All Races | 3.5        | 
| 1975 | 15-17 | All Races | 19.3       | 
```