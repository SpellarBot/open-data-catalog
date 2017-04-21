# Most Popular Baby Girl Names, 1980-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/most-popular-baby-girl-names-1980-2013-3f00a) |
| Metadata | [Link](https://data.illinois.gov/api/views/rx64-7qfr) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/rx64-7qfr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/rx64-7qfr/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | rx64-7qfr |
| Name | Most Popular Baby Girl Names, 1980-2013 |
| Attribution | Illinois Department of Public Health, Office of Policy, Planning, and Statistics |
| Category | Health |
| Tags | health, baby, names, girl, popular |
| Created | 2014-08-19T20:45:33Z |
| Publication Date | 2014-08-19T20:47:00Z |

## Description

Note: 2010-2013 should be considered provisional data.

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | numeric metric | rank       | Rank      | number    | number      |
| Yes      | time           | year       | Year      | number    | number      |
| Yes      | series tag     | name       | Name      | text      | text        |
| Yes      | numeric metric | frequency  | Frequency | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rx64-7qfr d:1980-01-01T00:00:00.000Z t:name=Jennifer m:rank=1 m:frequency=3017

series e:rx64-7qfr d:1980-01-01T00:00:00.000Z t:name=Amanda m:rank=2 m:frequency=1750

series e:rx64-7qfr d:1980-01-01T00:00:00.000Z t:name=Melissa m:rank=3 m:frequency=1566
```

## Meta Commands

```ls
metric m:rank p:integer l:Rank t:dataTypeName=number

metric m:frequency p:integer l:Frequency t:dataTypeName=number

entity e:rx64-7qfr l:"Most Popular Baby Girl Names, 1980-2013" t:attribution="Illinois Department of Public Health, Office of Policy, Planning, and Statistics" t:url=https://data.illinois.gov/api/views/rx64-7qfr

property e:rx64-7qfr t:meta.view v:id=rx64-7qfr v:category=Health v:averageRating=0 v:name="Most Popular Baby Girl Names, 1980-2013" v:attribution="Illinois Department of Public Health, Office of Policy, Planning, and Statistics"

property e:rx64-7qfr t:meta.view.license v:name="Public Domain"

property e:rx64-7qfr t:meta.view.owner v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"

property e:rx64-7qfr t:meta.view.tableauthor v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"
```

## Top Records

```ls
| rank | year | name      | frequency | 
| ==== | ==== | ========= | ========= | 
| 1    | 1980 | Jennifer  | 3017      | 
| 2    | 1980 | Amanda    | 1750      | 
| 3    | 1980 | Melissa   | 1566      | 
| 4    | 1980 | Sarah     | 1390      | 
| 5    | 1980 | Jessica   | 1373      | 
| 6    | 1980 | Nicole    | 1336      | 
| 7    | 1980 | Elizabeth | 1221      | 
| 8    | 1980 | Michelle  | 1170      | 
| 9    | 1980 | Amy       | 1013      | 
| 10   | 1980 | Tiffany   | 941       | 
```