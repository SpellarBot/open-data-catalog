# NCHS - Pregnancy and Live Birth Rates, by Marital Status and Race and Hispanic Origin: United States, 1990-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pregnancy-and-live-birth-rates-by-marital-status-and-race-and-hispanic-origin-united-1990-) |
| Metadata | [Link](https://data.cdc.gov/api/views/7pcd-2tnr) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/7pcd-2tnr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/7pcd-2tnr/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 7pcd-2tnr |
| Name | NCHS - Pregnancy and Live Birth Rates, by Marital Status and Race and Hispanic Origin: United States, 1990-2010 |
| Attribution | National Center for Health Statistics |
| Category | NCHS |
| Tags | live birth rate, marital status, race, hispanic origin, united states, nchs |
| Created | 2015-12-02T20:18:48Z |
| Publication Date | 2015-12-02T20:21:54Z |

## Description

http://blogs.cdc.gov/nchs-data-visualization/nonmarital-births/

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | time           | year            | Year            | number    | number      |
| Yes      | series tag     | marrital_status | Marrital Status | text      | text        |
| Yes      | series tag     | race_ethnicity  | Race Ethnicity  | text      | text        |
| Yes      | numeric metric | all_pregnancies | All Pregnancies | number    | number      |
| Yes      | numeric metric | live_births     | Live Births     | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7pcd-2tnr d:1990-01-01T00:00:00.000Z t:race_ethnicity="All Races" t:marrital_status=Married m:live_births=93.2 m:all_pregnancies=126.6

series e:7pcd-2tnr d:1991-01-01T00:00:00.000Z t:race_ethnicity="All Races" t:marrital_status=Married m:live_births=89.6 m:all_pregnancies=121.8

series e:7pcd-2tnr d:1992-01-01T00:00:00.000Z t:race_ethnicity="All Races" t:marrital_status=Married m:live_births=88.5 m:all_pregnancies=120
```

## Meta Commands

```ls
metric m:all_pregnancies p:float l:"All Pregnancies" t:dataTypeName=number

metric m:live_births p:float l:"Live Births" t:dataTypeName=number

entity e:7pcd-2tnr l:"NCHS - Pregnancy and Live Birth Rates, by Marital Status and Race and Hispanic Origin: United States, 1990-2010" t:attribution="National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/7pcd-2tnr

property e:7pcd-2tnr t:meta.view v:id=7pcd-2tnr v:category=NCHS v:averageRating=0 v:name="NCHS - Pregnancy and Live Birth Rates, by Marital Status and Race and Hispanic Origin: United States, 1990-2010" v:attribution="National Center for Health Statistics"

property e:7pcd-2tnr t:meta.view.license v:name="Public Domain"

property e:7pcd-2tnr t:meta.view.owner v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:displayName=hku4@cdc.gov

property e:7pcd-2tnr t:meta.view.tableauthor v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:roleName=administrator v:displayName=hku4@cdc.gov

property e:7pcd-2tnr t:meta.view.metadata.custom_fields.common_core v:Publisher="National Center for Health Statistics" v:Contact_Email=hku4@cdc.gov v:Contact_Name="National Center for Health Statistics" v:Bureau_Code=009:020 v:Program_Code=009:000
```

## Top Records

```ls
| year | marrital_status | race_ethnicity | all_pregnancies | live_births | 
| ==== | =============== | ============== | =============== | =========== | 
| 1990 | Married         | All Races      | 126.6           | 93.2        | 
| 1991 | Married         | All Races      | 121.8           | 89.6        | 
| 1992 | Married         | All Races      | 120.0           | 88.5        | 
| 1993 | Married         | All Races      | 117.0           | 86.1        | 
| 1994 | Married         | All Races      | 112.6           | 82.9        | 
| 1995 | Married         | All Races      | 111.8           | 82.6        | 
| 1996 | Married         | All Races      | 111.7           | 82.3        | 
| 1997 | Married         | All Races      | 111.7           | 82.7        | 
| 1998 | Married         | All Races      | 113.5           | 84.2        | 
| 1999 | Married         | All Races      | 114.5           | 84.8        | 
```