# Statewide Births, Deaths, Marriages, Civil Unions 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/statewide-births-deaths-marriages-civil-unions-2012-38810) |
| Metadata | [Link](https://data.hawaii.gov/api/views/bhtq-x545) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/bhtq-x545/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/bhtq-x545/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | bhtq-x545 |
| Name | Statewide Births, Deaths, Marriages, Civil Unions 2012 |
| Attribution | Health |
| Category | Health |
| Tags | birth, death, marriage, civil |
| Created | 2012-08-28T23:54:10Z |
| Publication Date | 2012-08-28T23:58:30Z |

## Description

Births, Deaths, Marriages and Civil Unions counts by month

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
series e:bhtq-x545 d:2012-01-01T00:00:00.000Z t:month_of_occurrence=January m:birth=1570 m:deaths=892 m:civil_unions=116 m:marriages=1384

series e:bhtq-x545 d:2012-01-01T00:00:00.000Z t:month_of_occurrence=February m:birth=1449 m:deaths=898 m:civil_unions=80 m:marriages=1752

series e:bhtq-x545 d:2012-01-01T00:00:00.000Z t:month_of_occurrence=March m:birth=1585 m:deaths=911 m:civil_unions=53 m:marriages=1876
```

## Meta Commands

```ls
metric m:birth p:integer l:Birth t:dataTypeName=number

metric m:deaths p:integer l:Deaths t:dataTypeName=number

metric m:marriages p:integer l:Marriages t:dataTypeName=number

metric m:civil_unions p:integer l:"Civil Unions" t:dataTypeName=number

entity e:bhtq-x545 l:"Statewide Births, Deaths, Marriages, Civil Unions 2012" t:attribution=Health t:url=https://data.hawaii.gov/api/views/bhtq-x545

property e:bhtq-x545 t:meta.view v:id=bhtq-x545 v:category=Health v:attributionLink=http://hawaii.gov/health v:averageRating=0 v:name="Statewide Births, Deaths, Marriages, Civil Unions 2012" v:attribution=Health

property e:bhtq-x545 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:bhtq-x545 t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:bhtq-x545 t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| month_of_occurrence | birth | deaths | marriages | civil_unions | 
| =================== | ===== | ====== | ========= | ============ | 
| January             | 1570  | 892    | 1384      | 116          | 
| February            | 1449  | 898    | 1752      | 80           | 
| March               | 1585  | 911    | 1876      | 53           | 
| April               | 1525  | 913    | 1924      | 54           | 
| May                 | 1560  | 913    | 2339      | 51           | 
| June                | 1556  | 845    | 2153      | 66           | 
| July                | 1624  | 798    | 2014      | 55           | 
| August              | 0     | 0      | 0         | 0            | 
| September           | 0     | 0      | 0         | 0            | 
| November            | 0     | 0      | 0         | 0            | 
```