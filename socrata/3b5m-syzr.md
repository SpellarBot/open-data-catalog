# 2012 Election Polling Places

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-election-polling-places-0df1a) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/3b5m-syzr) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/3b5m-syzr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/3b5m-syzr/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | 3b5m-syzr |
| Name | 2012 Election Polling Places |
| Attribution | Montgomery County, MD |
| Category | Elections |
| Tags | election, polling place, vote |
| Created | 2012-03-13T19:41:56Z |
| Publication Date | 2012-09-17T17:26:49Z |

## Description

Location of all 2012 Election Polling Places, including the Early Voting Centers.

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| Yes      | series tag  | district_precinct | District-Precinct | text      | text        |
| Yes      | series tag  | building_name     | Building Name     | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3b5m-syzr d:2012-01-01T00:00:00.000Z t:building_name="LAYTONSVILLE ELEMENTARY SCHOOL" t:district_precinct=01-01 m:row_number.3b5m-syzr=1

series e:3b5m-syzr d:2012-01-01T00:00:00.000Z t:building_name="GOSHEN ELEMENTARY SCHOOL" t:district_precinct=01-02 m:row_number.3b5m-syzr=2

series e:3b5m-syzr d:2012-01-01T00:00:00.000Z t:building_name="LAKE MARION COMMUNITY CENTER" t:district_precinct=01-03 m:row_number.3b5m-syzr=3
```

## Meta Commands

```ls
metric m:row_number.3b5m-syzr p:long l:"Row Number"

entity e:3b5m-syzr l:"2012 Election Polling Places" t:attribution="Montgomery County, MD" t:url=https://data.montgomerycountymd.gov/api/views/3b5m-syzr

property e:3b5m-syzr t:meta.view v:id=3b5m-syzr v:category=Elections v:averageRating=0 v:name="2012 Election Polling Places" v:attribution="Montgomery County, MD"

property e:3b5m-syzr t:meta.view.license v:name="Public Domain"

property e:3b5m-syzr t:meta.view.owner v:id=yr5d-z7h2 v:screenName="John Gillick" v:displayName="John Gillick"

property e:3b5m-syzr t:meta.view.tableauthor v:id=yr5d-z7h2 v:screenName="John Gillick" v:roleName=administrator v:displayName="John Gillick"
```

## Top Records

```ls
| district_precinct | building_name                      | 
| ================= | ================================== | 
| 01-01             | LAYTONSVILLE ELEMENTARY SCHOOL     | 
| 01-02             | GOSHEN ELEMENTARY SCHOOL           | 
| 01-03             | LAKE MARION COMMUNITY CENTER       | 
| 01-04             | JUDITH A. RESNIK ELEMENTARY SCHOOL | 
| 01-05             | AGRICULTURAL HISTORY FARM PARK     | 
| 01-06             | LAYTONSVILLE GOLF COURSE           | 
| 01-07             | DAMASCUS LIBRARY                   | 
| 02-01             | ROCKY HILL MIDDLE SCHOOL           | 
| 02-02             | KINGSVIEW MIDDLE SCHOOL            | 
| 02-03             | WATERS LANDING ELEMENTARY SCHOOL   | 
```