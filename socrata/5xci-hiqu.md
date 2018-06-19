# Table 18: Leaking Underground Storage Tanks

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-18-leaking-underground-storage-tanks-03601) |
| Metadata | [Link](https://data.hawaii.gov/api/views/5xci-hiqu) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/5xci-hiqu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/5xci-hiqu/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 5xci-hiqu |
| Name | Table 18: Leaking Underground Storage Tanks |
| Attribution | DOH |
| Category | Health |
| Tags | leaking, underground, storage, tanks |
| Created | 2012-08-01T00:24:05Z |
| Publication Date | 2012-08-01T00:25:18Z |

## Description

DOH Environmental Indicators

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| No       |                | _                              | #                              | number    | number      |
| Yes      | time           | calendar_year                  | Calendar Year                  | number    | text        |
| Yes      | numeric metric | total_tanks                    | Total Tanks                    | number    | number      |
| Yes      | numeric metric | active_tanks                   | Active Tanks                   | number    | number      |
| Yes      | numeric metric | closed_tanks                   | Closed Tanks                   | number    | number      |
| Yes      | numeric metric | confirmed_releases             | Confirmed Releases             | number    | number      |
| No       |                | clean_ups_partially_addressed  | Clean-ups Partially Addressed  | number    | number      |
| Yes      | numeric metric | clean_ups_not_initiated        | Clean-ups Not Initiated        | number    | number      |
| Yes      | numeric metric | cumulative_completed_clean_ups | Cumulative Completed Clean-ups | number    | number      |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _,clean_ups_partially_addressed
```

## Data Commands

```ls
series e:5xci-hiqu d:2006-01-01T00:00:00.000Z m:total_tanks=7832 m:clean_ups_not_initiated=94 m:confirmed_releases=1875 m:active_tanks=2001 m:cumulative_completed_clean_ups=1574 m:closed_tanks=5831

series e:5xci-hiqu d:2007-01-01T00:00:00.000Z m:total_tanks=7916 m:clean_ups_not_initiated=86 m:confirmed_releases=1909 m:active_tanks=1895 m:cumulative_completed_clean_ups=1631 m:closed_tanks=6021

series e:5xci-hiqu d:2008-01-01T00:00:00.000Z m:total_tanks=7845 m:clean_ups_not_initiated=76 m:confirmed_releases=1955 m:active_tanks=1770 m:cumulative_completed_clean_ups=1695 m:closed_tanks=6075
```

## Meta Commands

```ls
metric m:total_tanks p:integer l:"Total Tanks" t:dataTypeName=number

metric m:active_tanks p:integer l:"Active Tanks" t:dataTypeName=number

metric m:closed_tanks p:integer l:"Closed Tanks" t:dataTypeName=number

metric m:confirmed_releases p:integer l:"Confirmed Releases" t:dataTypeName=number

metric m:clean_ups_not_initiated p:integer l:"Clean-ups Not Initiated" t:dataTypeName=number

metric m:cumulative_completed_clean_ups p:integer l:"Cumulative Completed Clean-ups" t:dataTypeName=number

entity e:5xci-hiqu l:"Table 18: Leaking Underground Storage Tanks" t:attribution=DOH t:url=https://data.hawaii.gov/api/views/5xci-hiqu

property e:5xci-hiqu t:meta.view v:id=5xci-hiqu v:category=Health v:attributionLink=http://hawaii.gov/doh v:averageRating=0 v:name="Table 18: Leaking Underground Storage Tanks" v:attribution=DOH

property e:5xci-hiqu t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:5xci-hiqu t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:5xci-hiqu t:meta.view.tableauthor v:id=8c9u-vteh v:screenName=lorrink v:roleName=editor v:displayName=lorrink
```

## Top Records

```ls
| _ | calendar_year | total_tanks | active_tanks | closed_tanks | confirmed_releases | clean_ups_partially_addressed | clean_ups_not_initiated | cumulative_completed_clean_ups | 
| = | ============= | =========== | ============ | ============ | ================== | ============================= | ======================= | ============================== | 
| 1 | 2006          | 7832        | 2001         | 5831         | 1875               | 206                           | 94                      | 1574                           | 
| 2 | 2007          | 7916        | 1895         | 6021         | 1909               | 192                           | 86                      | 1631                           | 
| 3 | 2008          | 7845        | 1770         | 6075         | 1955               | 184                           | 76                      | 1695                           | 
| 4 | 2009          | 7873        | 1701         | 6172         | 1989               | 154                           | 80                      | 1755                           | 
| 5 | 2010          | 7897        | 1679         | 6248         | 2019               | 180                           | 45                      | 1794                           | 
```