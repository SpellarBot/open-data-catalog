# NCHS - Birth Rates, by Age of Mother: United States, 1940-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/birth-rates-by-age-of-mother-united-states-1940-2013) |
| Metadata | [Link](https://data.cdc.gov/api/views/yt7u-eiyg) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/yt7u-eiyg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/yt7u-eiyg/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | yt7u-eiyg |
| Name | NCHS - Birth Rates, by Age of Mother: United States, 1940-2013 |
| Attribution | National Center for Health Statistics |
| Category | NCHS |
| Tags | birth rates, age of mother, united states, nchs |
| Created | 2015-12-02T21:25:43Z |
| Publication Date | 2015-12-02T21:29:42Z |

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
series e:yt7u-eiyg d:1940-01-01T00:00:00.000Z t:age_group=45?49 m:birth_rate=1.9

series e:yt7u-eiyg d:1941-01-01T00:00:00.000Z t:age_group=45?49 m:birth_rate=1.7

series e:yt7u-eiyg d:1942-01-01T00:00:00.000Z t:age_group=45?49 m:birth_rate=1.6
```

## Meta Commands

```ls
metric m:birth_rate p:float l:"Birth Rate" t:dataTypeName=number

entity e:yt7u-eiyg l:"NCHS - Birth Rates, by Age of Mother: United States, 1940-2013" t:attribution="National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/yt7u-eiyg

property e:yt7u-eiyg t:meta.view v:id=yt7u-eiyg v:category=NCHS v:averageRating=0 v:name="NCHS - Birth Rates, by Age of Mother: United States, 1940-2013" v:attribution="National Center for Health Statistics"

property e:yt7u-eiyg t:meta.view.license v:name="Public Domain"

property e:yt7u-eiyg t:meta.view.owner v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:displayName=hku4@cdc.gov

property e:yt7u-eiyg t:meta.view.tableauthor v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:roleName=administrator v:displayName=hku4@cdc.gov

property e:yt7u-eiyg t:meta.view.metadata.custom_fields.common_core v:Publisher="National Center for Health Statistics" v:Contact_Email=hku4@cdc.gov v:Contact_Name="National Center for Health Statistics" v:Bureau_Code=009:020 v:Program_Code=009:000
```

## Top Records

```ls
| year | age_group | birth_rate | 
| ==== | ========= | ========== | 
| 1940 | 45?49     | 1.9        | 
| 1941 | 45?49     | 1.7        | 
| 1942 | 45?49     | 1.6        | 
| 1943 | 45?49     | 1.5        | 
| 1944 | 45?49     | 1.4        | 
| 1945 | 45?49     | 1.6        | 
| 1946 | 45?49     | 1.5        | 
| 1947 | 45?49     | 1.4        | 
| 1948 | 45?49     | 1.3        | 
| 1949 | 45?49     | 1.3        | 
```