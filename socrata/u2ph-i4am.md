# Kauai County Births, Deaths, Marriages, Civil Unions 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/kauai-county-births-deaths-marriages-civil-unions-2012-d9ccf) |
| Metadata | [Link](https://data.hawaii.gov/api/views/u2ph-i4am) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/u2ph-i4am/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/u2ph-i4am/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | u2ph-i4am |
| Name | Kauai County Births, Deaths, Marriages, Civil Unions 2012 |
| Attribution | Department of Health |
| Category | Health |
| Tags | birth, death, civil unions, marriage |
| Created | 2012-08-30T01:57:43Z |
| Publication Date | 2012-08-30T02:02:25Z |

## Description

Births, Deaths, marriages and civil unions in Kauai County

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | month_of_occurrence | Month of Occurrence | text      | text        |
| Yes      | numeric metric | birth               | Birth               | number    | number      |
| Yes      | numeric metric | deaths              | Deaths              | number    | number      |
| Yes      | numeric metric | marriages           | Marriages           | number    | number      |
| Yes      | numeric metric | civil_unions        | Civil Unions        | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:u2ph-i4am d:2012-01-01T00:00:00.000Z t:month_of_occurrence=January m:birth=73 m:deaths=45 m:civil_unions=11 m:marriages=148

series e:u2ph-i4am d:2012-01-01T00:00:00.000Z t:month_of_occurrence=February m:birth=53 m:deaths=35 m:civil_unions=7 m:marriages=190

series e:u2ph-i4am d:2012-01-01T00:00:00.000Z t:month_of_occurrence=March m:birth=73 m:deaths=33 m:civil_unions=11 m:marriages=223
```

## Meta Commands

```ls
metric m:birth p:integer l:Birth t:dataTypeName=number

metric m:deaths p:integer l:Deaths t:dataTypeName=number

metric m:marriages p:integer l:Marriages t:dataTypeName=number

metric m:civil_unions p:integer l:"Civil Unions" t:dataTypeName=number

entity e:u2ph-i4am l:"Kauai County Births, Deaths, Marriages, Civil Unions 2012" t:attribution="Department of Health" t:url=https://data.hawaii.gov/api/views/u2ph-i4am

property e:u2ph-i4am t:meta.view v:id=u2ph-i4am v:category=Health v:attributionLink=http://hawaii.gov/health v:averageRating=0 v:name="Kauai County Births, Deaths, Marriages, Civil Unions 2012" v:attribution="Department of Health"

property e:u2ph-i4am t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:u2ph-i4am t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:u2ph-i4am t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| month_of_occurrence | birth | deaths | marriages | civil_unions | 
| =================== | ===== | ====== | ========= | ============ | 
| January             | 73    | 45     | 148       | 11           | 
| February            | 53    | 35     | 190       | 7            | 
| March               | 73    | 33     | 223       | 11           | 
| April               | 67    | 41     | 232       | 6            | 
| May                 | 74    | 46     | 286       | 3            | 
| June                | 63    | 47     | 245       | 11           | 
| July                | 74    | 40     | 238       | 10           | 
| August              |       |        |           |              | 
| September           |       |        |           |              | 
| November            |       |        |           |              | 
```