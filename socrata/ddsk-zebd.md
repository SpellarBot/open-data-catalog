# NCHS - Infant Mortality Rates, by Race: United States, 1915-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/infant-mortality-rates-by-race-united-states-1915-2013) |
| Metadata | [Link](https://data.cdc.gov/api/views/ddsk-zebd) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/ddsk-zebd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/ddsk-zebd/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | ddsk-zebd |
| Name | NCHS - Infant Mortality Rates, by Race: United States, 1915-2013 |
| Attribution | National Center for Health Statistics |
| Category | NCHS |
| Tags | infant mortality rates, race, united states, nchs |
| Created | 2015-07-14T19:08:21Z |
| Publication Date | 2016-06-22T17:57:26Z |

## Description

All birth data by race before 1980 are based on race of the child; starting in 1980, birth data by race are based on race of the mother. Birth data are used to calculate infant mortality rate.

http://blogs.cdc.gov/nchs-data-visualization/deaths-in-the-us/

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | race                  | Race                  | text      | text        |
| Yes      | time           | year                  | Year                  | number    | number      |
| Yes      | numeric metric | infant_mortality_rate | Infant Mortality Rate | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ddsk-zebd d:1915-01-01T00:00:00.000Z t:race=White m:infant_mortality_rate=98.6

series e:ddsk-zebd d:1916-01-01T00:00:00.000Z t:race=White m:infant_mortality_rate=99

series e:ddsk-zebd d:1917-01-01T00:00:00.000Z t:race=White m:infant_mortality_rate=98.2
```

## Meta Commands

```ls
metric m:infant_mortality_rate p:float l:"Infant Mortality Rate" t:dataTypeName=number

entity e:ddsk-zebd l:"NCHS - Infant Mortality Rates, by Race: United States, 1915-2013" t:attribution="National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/ddsk-zebd

property e:ddsk-zebd t:meta.view v:id=ddsk-zebd v:category=NCHS v:averageRating=0 v:name="NCHS - Infant Mortality Rates, by Race: United States, 1915-2013" v:attribution="National Center for Health Statistics"

property e:ddsk-zebd t:meta.view.license v:name="Public Domain"

property e:ddsk-zebd t:meta.view.owner v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:displayName=hku4@cdc.gov

property e:ddsk-zebd t:meta.view.tableauthor v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:roleName=administrator v:displayName=hku4@cdc.gov

property e:ddsk-zebd t:meta.view.metadata.custom_fields.common_core v:Publisher="National Center for Health Statistics" v:Contact_Email=hku4@cdc.gov v:Contact_Name="National Center for Health Statistics" v:Bureau_Code=009:020 v:Program_Code=009:000
```

## Top Records

```ls
| race  | year | infant_mortality_rate | 
| ===== | ==== | ===================== | 
| White | 1915 | 98.60                 | 
| White | 1916 | 99.00                 | 
| White | 1917 | 98.20                 | 
| White | 1918 | 97.40                 | 
| White | 1919 | 83.00                 | 
| White | 1920 | 82.10                 | 
| White | 1921 | 72.50                 | 
| White | 1922 | 73.20                 | 
| White | 1923 | 73.50                 | 
| White | 1924 | 66.80                 | 
```