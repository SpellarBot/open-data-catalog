# Abortions By County, 1995-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/abortions-by-county-1995-2012-fd5ac) |
| Metadata | [Link](https://data.illinois.gov/api/views/u65f-usui) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/u65f-usui/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/u65f-usui/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | u65f-usui |
| Name | Abortions By County, 1995-2012 |
| Attribution | Illinois Department of Public Health, Office of Finance and Administration, Division of Vital Records |
| Category | Health |
| Tags | health, abortion, pregnancy |
| Created | 2014-08-19T14:18:25Z |
| Publication Date | 2014-08-19T14:22:19Z |

## Description

The number of induced pregnancy terminations reported in Illinois by county (if in excess of 50).

## Columns

```ls
| Included | Schema Type | Field Name | Name      | Data Type | Render Type |
| ======== | =========== | ========== | ========= | ========= | =========== |
| Yes      | time        | year       | YEAR      | number    | number      |
| Yes      | series tag  | county     | COUNTY    | text      | text        |
| Yes      | series tag  | frequency  | FREQUENCY | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:u65f-usui l:"Abortions By County, 1995-2012" t:attribution="Illinois Department of Public Health, Office of Finance and Administration, Division of Vital Records" t:url=https://data.illinois.gov/api/views/u65f-usui

property e:u65f-usui t:meta.view v:id=u65f-usui v:category=Health v:averageRating=0 v:name="Abortions By County, 1995-2012" v:attribution="Illinois Department of Public Health, Office of Finance and Administration, Division of Vital Records"

property e:u65f-usui t:meta.view.license v:name="Public Domain"

property e:u65f-usui t:meta.view.owner v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"

property e:u65f-usui t:meta.view.tableauthor v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"
```

## Top Records

```ls
| year | county    | frequency | 
| ==== | ========= | ========= | 
| 1995 | Adams     | 123       | 
| 1995 | Alexander | ≤50       | 
| 1995 | Bond      | ≤50       | 
| 1995 | Boone     | 119       | 
| 1995 | Brown     | ≤50       | 
| 1995 | Bureau    | 57        | 
| 1995 | Calhoun   | ≤50       | 
| 1995 | Carroll   | ≤50       | 
| 1995 | Cass      | ≤50       | 
| 1995 | Champaign | 424       | 
```