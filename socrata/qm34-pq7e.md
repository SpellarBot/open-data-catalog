# DAS HR Almanac - Executive Branch Employment By Race

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/das-hr-almanac-executive-branch-employment-by-race) |
| Metadata | [Link](https://data.ct.gov/api/views/qm34-pq7e) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/qm34-pq7e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/qm34-pq7e/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | qm34-pq7e |
| Name | DAS HR Almanac - Executive Branch Employment By Race |
| Attribution | DAS Human Resources |
| Category | Government |
| Tags | hr, personnel, diversity |
| Created | 2016-01-13T21:37:10Z |
| Publication Date | 2016-01-13T21:47:24Z |

## Description

This data is reflective of the State of Connecticut Executive Branch workforce only.  The data does not reflect employees of the University of Connecticut Health Center, University of Connecticut and Board of Regents which includes the state university system and community colleges.  Judicial Branch and Legislative Branch employees are also not reflected in this data.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | year        | Year        | number    | number      |
| Yes      | numeric metric | white       | White       | number    | number      |
| Yes      | numeric metric | black       | Black       | number    | number      |
| Yes      | numeric metric | hispanic    | Hispanic    | number    | number      |
| Yes      | numeric metric | asian       | Asian       | number    | number      |
| Yes      | numeric metric | amer_indian | Amer Indian | number    | number      |
| Yes      | numeric metric | unknown     | Unknown     | number    | number      |
| Yes      | numeric metric | other       | Other       | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qm34-pq7e d:2003-01-01T00:00:00.000Z m:other=920 m:white=27361 m:unknown=235 m:amer_indian=117 m:black=6559 m:hispanic=2956 m:asian=568

series e:qm34-pq7e d:2004-01-01T00:00:00.000Z m:other=1258 m:white=27731 m:unknown=531 m:amer_indian=120 m:black=6728 m:hispanic=3111 m:asian=607

series e:qm34-pq7e d:2005-01-01T00:00:00.000Z m:other=1309 m:white=27925 m:unknown=562 m:amer_indian=126 m:black=6850 m:hispanic=3181 m:asian=621
```

## Meta Commands

```ls
metric m:white p:integer l:White t:dataTypeName=number

metric m:black p:integer l:Black t:dataTypeName=number

metric m:hispanic p:integer l:Hispanic t:dataTypeName=number

metric m:asian p:integer l:Asian t:dataTypeName=number

metric m:amer_indian p:integer l:"Amer Indian" t:dataTypeName=number

metric m:unknown p:integer l:Unknown t:dataTypeName=number

metric m:other p:integer l:Other t:dataTypeName=number

entity e:qm34-pq7e l:"DAS HR Almanac - Executive Branch Employment By Race" t:attribution="DAS Human Resources" t:url=https://data.ct.gov/api/views/qm34-pq7e

property e:qm34-pq7e t:meta.view v:id=qm34-pq7e v:category=Government v:averageRating=0 v:name="DAS HR Almanac - Executive Branch Employment By Race" v:attribution="DAS Human Resources"

property e:qm34-pq7e t:meta.view.owner v:id=ksrh-ut6b v:screenName="Open Data Hub" v:displayName="Open Data Hub"

property e:qm34-pq7e t:meta.view.tableauthor v:id=ksrh-ut6b v:screenName="Open Data Hub" v:roleName=publisher v:displayName="Open Data Hub"
```

## Top Records

```ls
| year | white | black | hispanic | asian | amer_indian | unknown | other | 
| ==== | ===== | ===== | ======== | ===== | =========== | ======= | ===== | 
| 2003 | 27361 | 6559  | 2956     | 568   | 117         | 235     | 920   | 
| 2004 | 27731 | 6728  | 3111     | 607   | 120         | 531     | 1258  | 
| 2005 | 27925 | 6850  | 3181     | 621   | 126         | 562     | 1309  | 
| 2006 | 28534 | 7031  | 3333     | 655   | 123         | 571     |       | 
| 2007 | 28185 | 7181  | 3391     | 680   | 122         | 577     |       | 
| 2008 | 28074 | 7291  | 3479     | 710   | 116         | 565     |       | 
| 2009 | 25603 | 6899  | 3351     | 681   | 114         | 438     |       | 
| 2010 | 24918 | 6753  | 3303     | 694   | 109         | 416     |       | 
| 2011 | 23027 | 6373  | 3158     | 664   | 102         | 309     |       | 
| 2012 | 23194 | 6466  | 3269     | 704   | 114         | 366     |       | 
```