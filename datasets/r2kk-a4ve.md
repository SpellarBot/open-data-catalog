# DCEO Workforce Annual Report - Participants Served

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dceo-workforce-annual-report-participants-served-fc350) |
| Metadata | [Link](https://data.illinois.gov/api/views/r2kk-a4ve) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/r2kk-a4ve/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/r2kk-a4ve/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | r2kk-a4ve |
| Name | DCEO Workforce Annual Report - Participants Served |
| Category | Economics |
| Tags | workforce, wia |
| Created | 2012-01-13T21:08:16Z |
| Publication Date | 2012-01-13T21:14:18Z |

## Description

Workforce Investment Act Activity - participants served Federal Program Year 2010, State Fiscal Year 2011

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | lwia_region        | LWIA Region        | text      | text        |
| Yes      | numeric metric | adult_             | Adult              | number    | number      |
| Yes      | numeric metric | dislocated_workers | Dislocated Workers | number    | number      |
| Yes      | numeric metric | youth              | Youth              | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:r2kk-a4ve d:2012-01-13T13:08:30.000Z t:lwia_region=1 m:dislocated_workers=627 m:adult_=433 m:youth=226

series e:r2kk-a4ve d:2012-01-13T13:08:30.000Z t:lwia_region=2 m:dislocated_workers=640 m:adult_=102 m:youth=113

series e:r2kk-a4ve d:2012-01-13T13:08:30.000Z t:lwia_region=3 m:dislocated_workers=1886 m:adult_=427 m:youth=413
```

## Meta Commands

```ls
metric m:adult_ p:integer l:Adult t:dataTypeName=number

metric m:dislocated_workers p:integer l:"Dislocated Workers" t:dataTypeName=number

metric m:youth p:integer l:Youth t:dataTypeName=number

entity e:r2kk-a4ve l:"DCEO Workforce Annual Report - Participants Served" t:url=https://data.illinois.gov/api/views/r2kk-a4ve

property e:r2kk-a4ve t:meta.view v:id=r2kk-a4ve v:category=Economics v:averageRating=0 v:name="DCEO Workforce Annual Report - Participants Served"

property e:r2kk-a4ve t:meta.view.owner v:id=t6h9-hze3 v:screenName=Nicole v:displayName=Nicole

property e:r2kk-a4ve t:meta.view.tableauthor v:id=t6h9-hze3 v:screenName=Nicole v:roleName=publisher v:displayName=Nicole
```

## Top Records

```ls
| :updated_at | lwia_region | adult_ | dislocated_workers | youth | 
| =========== | =========== | ====== | ================== | ===== | 
| 1326460110  | 1           | 433    | 627                | 226   | 
| 1326460110  | 2           | 102    | 640                | 113   | 
| 1326460110  | 3           | 427    | 1886               | 413   | 
| 1326460110  | 4           | 213    | 524                | 295   | 
| 1326460110  | 5           | 886    | 1229               | 500   | 
| 1326460110  | 6           | 320    | 1073               | 265   | 
| 1326460110  | 7           | 1490   | 2553               | 1653  | 
| 1326460110  | 8           | 582    | 1748               | 526   | 
| 1326460110  | 9           | 4875   | 4222               | 3220  | 
| 1326460110  | 10          | 335    | 656                | 279   | 
```