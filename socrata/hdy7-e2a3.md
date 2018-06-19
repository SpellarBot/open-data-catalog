# NCHS - Pregnancy Rates, by Age for Hispanic Women: United States, 1990-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pregnancy-rates-by-age-for-hispanic-women-united-states-1990-2010) |
| Metadata | [Link](https://data.cdc.gov/api/views/hdy7-e2a3) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/hdy7-e2a3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/hdy7-e2a3/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | hdy7-e2a3 |
| Name | NCHS - Pregnancy Rates, by Age for Hispanic Women: United States, 1990-2010 |
| Attribution | National Center for Health Statistics |
| Category | NCHS |
| Tags | pregnancy rate, hispanic women, united states, nchs |
| Created | 2015-12-02T19:42:25Z |
| Publication Date | 2015-12-02T19:45:27Z |

## Description

http://blogs.cdc.gov/nchs-data-visualization/us-natality-trends/

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | time           | year            | Year            | number    | number      |
| Yes      | series tag     | race_ethnicity  | Race Ethnicity  | text      | text        |
| Yes      | series tag     | marrital_status | Marrital Status | text      | text        |
| Yes      | numeric metric | all_pregnancies | All pregnancies | number    | number      |
| Yes      | numeric metric | live_birth      | Live birth      | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hdy7-e2a3 d:1990-01-01T00:00:00.000Z t:race_ethnicity="All Races" t:marrital_status=Married m:all_pregnancies=126.6 m:live_birth=93.2

series e:hdy7-e2a3 d:1991-01-01T00:00:00.000Z t:race_ethnicity="All Races" t:marrital_status=Married m:all_pregnancies=121.8 m:live_birth=89.6

series e:hdy7-e2a3 d:1992-01-01T00:00:00.000Z t:race_ethnicity="All Races" t:marrital_status=Married m:all_pregnancies=120 m:live_birth=88.5
```

## Meta Commands

```ls
metric m:all_pregnancies p:float l:"All pregnancies" t:dataTypeName=number

metric m:live_birth p:double l:"Live birth" t:dataTypeName=number

entity e:hdy7-e2a3 l:"NCHS - Pregnancy Rates, by Age for Hispanic Women: United States, 1990-2010" t:attribution="National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/hdy7-e2a3

property e:hdy7-e2a3 t:meta.view v:id=hdy7-e2a3 v:category=NCHS v:averageRating=0 v:name="NCHS - Pregnancy Rates, by Age for Hispanic Women: United States, 1990-2010" v:attribution="National Center for Health Statistics"

property e:hdy7-e2a3 t:meta.view.license v:name="Public Domain"

property e:hdy7-e2a3 t:meta.view.owner v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:displayName=hku4@cdc.gov

property e:hdy7-e2a3 t:meta.view.tableauthor v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:roleName=administrator v:displayName=hku4@cdc.gov

property e:hdy7-e2a3 t:meta.view.metadata.custom_fields.common_core v:Publisher="National Center for Health Statistics" v:Contact_Email=hku4@cdc.gov v:Contact_Name="National Center for Health Statistics" v:Bureau_Code=009:020 v:Program_Code=009:000
```

## Top Records

```ls
| year | race_ethnicity | marrital_status | all_pregnancies | live_birth | 
| ==== | ============== | =============== | =============== | ========== | 
| 1990 | All Races      | Married         | 126.6           | 93.2       | 
| 1991 | All Races      | Married         | 121.8           | 89.6       | 
| 1992 | All Races      | Married         | 120             | 88.5       | 
| 1993 | All Races      | Married         | 117             | 86.1       | 
| 1994 | All Races      | Married         | 112.6           | 82.9       | 
| 1995 | All Races      | Married         | 111.8           | 82.6       | 
| 1996 | All Races      | Married         | 111.7           | 82.3       | 
| 1997 | All Races      | Married         | 111.7           | 82.7       | 
| 1998 | All Races      | Married         | 113.5           | 84.2       | 
| 1999 | All Races      | Married         | 114.5           | 84.8       | 
```