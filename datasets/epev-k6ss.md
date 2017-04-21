# NCHS - Infant and neonatal mortality rates: United States, 1915-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/infant-and-neonatal-mortality-rates-united-states-1915-2013) |
| Metadata | [Link](https://data.cdc.gov/api/views/epev-k6ss) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/epev-k6ss/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/epev-k6ss/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | epev-k6ss |
| Name | NCHS - Infant and neonatal mortality rates: United States, 1915-2013 |
| Attribution | National Center for Health Statistics |
| Category | NCHS |
| Tags | infant, neonatal, mortality, united states, nchs |
| Created | 2015-07-14T18:54:23Z |
| Publication Date | 2016-06-22T17:56:01Z |

## Description

Rates are infants (under 1 year) and neonatal (under 28 days) deaths per 1,000 live births. http://blogs.cdc.gov/nchs-data-visualization/deaths-in-the-us/

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | type           | Type           | text      | text        |
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
series e:epev-k6ss d:1915-01-01T00:00:00.000Z t:type=Infant m:mortality_rate=99.9

series e:epev-k6ss d:1916-01-01T00:00:00.000Z t:type=Infant m:mortality_rate=101

series e:epev-k6ss d:1917-01-01T00:00:00.000Z t:type=Infant m:mortality_rate=93.8
```

## Meta Commands

```ls
metric m:mortality_rate p:float l:"Mortality Rate" t:dataTypeName=number

entity e:epev-k6ss l:"NCHS - Infant and neonatal mortality rates: United States, 1915-2013" t:attribution="National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/epev-k6ss

property e:epev-k6ss t:meta.view v:id=epev-k6ss v:category=NCHS v:averageRating=0 v:name="NCHS - Infant and neonatal mortality rates: United States, 1915-2013" v:attribution="National Center for Health Statistics"

property e:epev-k6ss t:meta.view.license v:name="Public Domain"

property e:epev-k6ss t:meta.view.owner v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:displayName=hku4@cdc.gov

property e:epev-k6ss t:meta.view.tableauthor v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:roleName=administrator v:displayName=hku4@cdc.gov

property e:epev-k6ss t:meta.view.metadata.custom_fields.common_core v:Publisher="National Center for Health Statistics" v:Contact_Email=hku4@cdc.gov v:Contact_Name="National Center for Health Statistics" v:Bureau_Code=009:020 v:Program_Code=009:000
```

## Top Records

```ls
| type   | year | mortality_rate | 
| ====== | ==== | ============== | 
| Infant | 1915 | 99.90          | 
| Infant | 1916 | 101.00         | 
| Infant | 1917 | 93.80          | 
| Infant | 1918 | 100.90         | 
| Infant | 1919 | 86.60          | 
| Infant | 1920 | 85.80          | 
| Infant | 1921 | 75.60          | 
| Infant | 1922 | 76.20          | 
| Infant | 1923 | 77.10          | 
| Infant | 1924 | 70.80          | 
```