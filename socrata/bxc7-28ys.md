# Honolulu County Births, Deaths, Marriages, Civil Unions 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/honolulu-county-births-deaths-marriages-civil-unions-2012-09d48) |
| Metadata | [Link](https://data.hawaii.gov/api/views/bxc7-28ys) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/bxc7-28ys/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/bxc7-28ys/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | bxc7-28ys |
| Name | Honolulu County Births, Deaths, Marriages, Civil Unions 2012 |
| Attribution | Health |
| Category | Health |
| Tags | birth, death, marriages, civil union |
| Created | 2012-08-29T00:05:19Z |
| Publication Date | 2012-08-29T00:09:36Z |

## Description

City & County of Honolulu statistics

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
series e:bxc7-28ys d:2012-01-01T00:00:00.000Z t:month_of_occurrence=January m:birth=1130 m:deaths=626 m:civil_unions=72 m:marriages=718

series e:bxc7-28ys d:2012-01-01T00:00:00.000Z t:month_of_occurrence=February m:birth=1086 m:deaths=649 m:civil_unions=40 m:marriages=882

series e:bxc7-28ys d:2012-01-01T00:00:00.000Z t:month_of_occurrence=March m:birth=1175 m:deaths=666 m:civil_unions=23 m:marriages=959
```

## Meta Commands

```ls
metric m:birth p:integer l:Birth t:dataTypeName=number

metric m:deaths p:integer l:Deaths t:dataTypeName=number

metric m:marriages p:integer l:Marriages t:dataTypeName=number

metric m:civil_unions p:integer l:"Civil Unions" t:dataTypeName=number

entity e:bxc7-28ys l:"Honolulu County Births, Deaths, Marriages, Civil Unions 2012" t:attribution=Health t:url=https://data.hawaii.gov/api/views/bxc7-28ys

property e:bxc7-28ys t:meta.view v:id=bxc7-28ys v:category=Health v:attributionLink=http://hawaii.gov/health v:averageRating=0 v:name="Honolulu County Births, Deaths, Marriages, Civil Unions 2012" v:attribution=Health

property e:bxc7-28ys t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:bxc7-28ys t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:bxc7-28ys t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| month_of_occurrence | birth | deaths | marriages | civil_unions | 
| =================== | ===== | ====== | ========= | ============ | 
| January             | 1130  | 626    | 718       | 72           | 
| February            | 1086  | 649    | 882       | 40           | 
| March               | 1175  | 666    | 959       | 23           | 
| April               | 1140  | 643    | 949       | 28           | 
| May                 | 1135  | 650    | 1117      | 30           | 
| June                | 1154  | 611    | 1093      | 31           | 
| July                | 1186  | 574    | 1054      | 26           | 
| August              |       |        |           |              | 
| September           |       |        |           |              | 
| November            |       |        |           |              | 
```