# NCHS - Births to Unmarried Women, by Maternal Age: United States, 1940-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/births-to-unmarried-women-by-maternal-age-united-states-1940-2013) |
| Metadata | [Link](https://data.cdc.gov/api/views/g6qk-ngsf) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/g6qk-ngsf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/g6qk-ngsf/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | g6qk-ngsf |
| Name | NCHS - Births to Unmarried Women, by Maternal Age: United States, 1940-2013 |
| Attribution | National Center for Health Statistics |
| Category | NCHS |
| Tags | births, unmarried women, united states, nchs |
| Created | 2015-12-02T20:02:33Z |
| Publication Date | 2015-12-02T20:04:41Z |

## Description

http://blogs.cdc.gov/nchs-data-visualization/nonmarital-births/

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| Yes      | time        | year         | Year         | number    | number      |
| Yes      | series tag  | age_group    | Age Group    | text      | text        |
| Yes      | series tag  | birth_number | Birth Number | text      | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:g6qk-ngsf l:"NCHS - Births to Unmarried Women, by Maternal Age: United States, 1940-2013" t:attribution="National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/g6qk-ngsf

property e:g6qk-ngsf t:meta.view v:id=g6qk-ngsf v:category=NCHS v:averageRating=0 v:name="NCHS - Births to Unmarried Women, by Maternal Age: United States, 1940-2013" v:attribution="National Center for Health Statistics"

property e:g6qk-ngsf t:meta.view.license v:name="Public Domain"

property e:g6qk-ngsf t:meta.view.owner v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:displayName=hku4@cdc.gov

property e:g6qk-ngsf t:meta.view.tableauthor v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:roleName=administrator v:displayName=hku4@cdc.gov

property e:g6qk-ngsf t:meta.view.metadata.custom_fields.common_core v:Publisher="National Center for Health Statistics" v:Contact_Email=hku4@cdc.gov v:Contact_Name="National Center for Health Statistics" v:Bureau_Code=009:020 v:Program_Code=009:000
```

## Top Records

```ls
| year | age_group         | birth_number | 
| ==== | ================= | ============ | 
| 1940 | 15-19 years       | 40500        | 
| 1940 | 20-24 years       | 27200        | 
| 1940 | 25-29 years       | 10500        | 
| 1940 | 30-34 years       | 5200         | 
| 1940 | 35-39 years       | 3000         | 
| 1940 | 40 years and over | 1000         | 
| 1940 | Under 15 years    | 2100         | 
| 1950 | 15-19 years       | 56000        | 
| 1950 | 20-24 years       | 43100        | 
| 1950 | 25-29 years       | 20900        | 
```