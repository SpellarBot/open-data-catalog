# Maui County Births, Deaths, Marriages, Civil Unions 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maui-county-births-deaths-marriages-civil-unions-2012-533c3) |
| Metadata | [Link](https://data.hawaii.gov/api/views/rt4b-b8s5) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/rt4b-b8s5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/rt4b-b8s5/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | rt4b-b8s5 |
| Name | Maui County Births, Deaths, Marriages, Civil Unions 2012 |
| Attribution | Department of Health |
| Category | Health |
| Tags | birth, deaths, mariiage, civil unions |
| Created | 2012-08-30T02:03:43Z |
| Publication Date | 2012-08-30T02:21:38Z |

## Description

Births, deaths, marriages and civil unions in Maui County

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
series e:rt4b-b8s5 d:2012-01-01T00:00:00.000Z t:month_of_occurrence=February m:birth=136 m:deaths=84 m:civil_unions=19 m:marriages=491

series e:rt4b-b8s5 d:2012-01-01T00:00:00.000Z t:month_of_occurrence=March m:birth=137 m:deaths=92 m:civil_unions=14 m:marriages=531

series e:rt4b-b8s5 d:2012-01-01T00:00:00.000Z t:month_of_occurrence=April m:birth=157 m:deaths=111 m:civil_unions=12 m:marriages=580
```

## Meta Commands

```ls
metric m:birth p:integer l:Birth t:dataTypeName=number

metric m:deaths p:integer l:Deaths t:dataTypeName=number

metric m:marriages p:integer l:Marriages t:dataTypeName=number

metric m:civil_unions p:integer l:"Civil Unions" t:dataTypeName=number

entity e:rt4b-b8s5 l:"Maui County Births, Deaths, Marriages, Civil Unions 2012" t:attribution="Department of Health" t:url=https://data.hawaii.gov/api/views/rt4b-b8s5

property e:rt4b-b8s5 t:meta.view v:id=rt4b-b8s5 v:category=Health v:attributionLink=http://hawaii.gov/health v:averageRating=0 v:name="Maui County Births, Deaths, Marriages, Civil Unions 2012" v:attribution="Department of Health"

property e:rt4b-b8s5 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:rt4b-b8s5 t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:rt4b-b8s5 t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| month_of_occurrence | birth | deaths | marriages | civil_unions | 
| =================== | ===== | ====== | ========= | ============ | 
| February            | 136   | 84     | 491       | 19           | 
| March               | 137   | 92     | 531       | 14           | 
| April               | 157   | 111    | 580       | 12           | 
| May                 | 135   | 88     | 745       | 14           | 
| June                | 159   | 61     | 604       | 19           | 
| July                | 162   | 78     | 511       | 14           | 
| August              |       |        |           |              | 
| September           |       |        |           |              | 
| November            |       |        |           |              | 
| December            |       |        |           |              | 
```