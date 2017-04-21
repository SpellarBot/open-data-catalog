# NCHS - Percent Distribution of Nonmarital Births, by Maternal Age: 1970-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/percent-distribution-of-nonmarital-births-by-maternal-age-1970-2013) |
| Metadata | [Link](https://data.cdc.gov/api/views/hzd8-r9mj) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/hzd8-r9mj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/hzd8-r9mj/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | hzd8-r9mj |
| Name | NCHS - Percent Distribution of Nonmarital Births, by Maternal Age: 1970-2013 |
| Attribution | National Center for Health Statistics |
| Category | NCHS |
| Tags | percent distribution, nonmarital births, maternal age, nchs |
| Created | 2015-12-02T19:55:08Z |
| Publication Date | 2015-12-02T19:58:43Z |

## Description

http://blogs.cdc.gov/nchs-data-visualization/nonmarital-births/

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | time           | year                   | Year                   | number    | number      |
| Yes      | series tag     | birth_number           | Birth Number           | text      | number      |
| Yes      | numeric metric | general_fertility_rate | General Fertility Rate | number    | number      |
| Yes      | numeric metric | crude_birth_rate       | Crude Birth Rate       | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hzd8-r9mj d:1909-01-01T00:00:00.000Z t:birth_number=2718000 m:general_fertility_rate=126.8 m:crude_birth_rate=30

series e:hzd8-r9mj d:1910-01-01T00:00:00.000Z t:birth_number=2777000 m:general_fertility_rate=126.8 m:crude_birth_rate=30.1

series e:hzd8-r9mj d:1911-01-01T00:00:00.000Z t:birth_number=2809000 m:general_fertility_rate=126.3 m:crude_birth_rate=29.9
```

## Meta Commands

```ls
metric m:general_fertility_rate p:float l:"General Fertility Rate" t:dataTypeName=number

metric m:crude_birth_rate p:float l:"Crude Birth Rate" t:dataTypeName=number

entity e:hzd8-r9mj l:"NCHS - Percent Distribution of Nonmarital Births, by Maternal Age: 1970-2013" t:attribution="National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/hzd8-r9mj

property e:hzd8-r9mj t:meta.view v:id=hzd8-r9mj v:category=NCHS v:averageRating=0 v:name="NCHS - Percent Distribution of Nonmarital Births, by Maternal Age: 1970-2013" v:attribution="National Center for Health Statistics"

property e:hzd8-r9mj t:meta.view.license v:name="Public Domain"

property e:hzd8-r9mj t:meta.view.owner v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:displayName=hku4@cdc.gov

property e:hzd8-r9mj t:meta.view.tableauthor v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:roleName=administrator v:displayName=hku4@cdc.gov

property e:hzd8-r9mj t:meta.view.metadata.custom_fields.common_core v:Publisher="National Center for Health Statistics" v:Contact_Email=hku4@cdc.gov v:Contact_Name="National Center for Health Statistics" v:Bureau_Code=009:020 v:Program_Code=009:000
```

## Top Records

```ls
| year | birth_number | general_fertility_rate | crude_birth_rate | 
| ==== | ============ | ====================== | ================ | 
| 1909 | 2718000      | 126.8                  | 30               | 
| 1910 | 2777000      | 126.8                  | 30.1             | 
| 1911 | 2809000      | 126.3                  | 29.9             | 
| 1912 | 2840000      | 125.8                  | 29.8             | 
| 1913 | 2869000      | 124.7                  | 29.5             | 
| 1914 | 2986000      | 126.6                  | 29.9             | 
| 1915 | 2965000      | 125                    | 29.5             | 
| 1916 | 2964000      | 123.4                  | 29.1             | 
| 1917 | 2944000      | 121                    | 28.5             | 
| 1918 | 2948000      | 119.8                  | 28.2             | 
```