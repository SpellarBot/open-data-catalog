# NCHS - Childhood Mortality Rates, by Age at Death: United States, 1900-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/childhood-mortality-rates-by-age-at-death-united-states-1900-2013) |
| Metadata | [Link](https://data.cdc.gov/api/views/v6ab-adf5) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/v6ab-adf5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/v6ab-adf5/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | v6ab-adf5 |
| Name | NCHS - Childhood Mortality Rates, by Age at Death: United States, 1900-2013 |
| Attribution | National Center for Health Statistics |
| Category | NCHS |
| Tags | children, mortality rates, united states, nchs |
| Created | 2015-07-14T19:27:21Z |
| Publication Date | 2016-06-22T17:58:44Z |

## Description

http://blogs.cdc.gov/nchs-data-visualization/deaths-in-the-us/

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | age_at_death   | Age at Death   | text      | text        |
| Yes      | time           | year           | Year           | number    | number      |
| Yes      | numeric metric | mortality_rate | Mortality Rate | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:v6ab-adf5 d:1900-01-01T00:00:00.000Z t:age_at_death="10-14 years" m:mortality_rate=298.3

series e:v6ab-adf5 d:1901-01-01T00:00:00.000Z t:age_at_death="10-14 years" m:mortality_rate=273.6

series e:v6ab-adf5 d:1902-01-01T00:00:00.000Z t:age_at_death="10-14 years" m:mortality_rate=252.5
```

## Meta Commands

```ls
metric m:mortality_rate p:float l:"Mortality Rate" t:dataTypeName=number

entity e:v6ab-adf5 l:"NCHS - Childhood Mortality Rates, by Age at Death: United States, 1900-2013" t:attribution="National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/v6ab-adf5

property e:v6ab-adf5 t:meta.view v:id=v6ab-adf5 v:category=NCHS v:averageRating=0 v:name="NCHS - Childhood Mortality Rates, by Age at Death: United States, 1900-2013" v:attribution="National Center for Health Statistics"

property e:v6ab-adf5 t:meta.view.license v:name="Public Domain"

property e:v6ab-adf5 t:meta.view.owner v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:displayName=hku4@cdc.gov

property e:v6ab-adf5 t:meta.view.tableauthor v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:roleName=administrator v:displayName=hku4@cdc.gov

property e:v6ab-adf5 t:meta.view.metadata.custom_fields.common_core v:Publisher="National Center for Health Statistics" v:Contact_Email=hku4@cdc.gov v:Contact_Name="National Center for Health Statistics" v:Bureau_Code=009:020 v:Program_Code=009:000
```

## Top Records

```ls
| age_at_death | year | mortality_rate | 
| ============ | ==== | ============== | 
| 10-14 years  | 1900 | 298.3          | 
| 10-14 years  | 1901 | 273.6          | 
| 10-14 years  | 1902 | 252.5          | 
| 10-14 years  | 1903 | 268.2          | 
| 10-14 years  | 1904 | 305.2          | 
| 10-14 years  | 1905 | 279.8          | 
| 10-14 years  | 1906 | 272.2          | 
| 10-14 years  | 1907 | 265.8          | 
| 10-14 years  | 1908 | 247.9          | 
| 10-14 years  | 1909 | 230.5          | 
```