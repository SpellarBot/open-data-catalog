# Most Popular Baby Boy Names, 1980-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/most-popular-baby-boy-names-1980-2013-07f06) |
| Metadata | [Link](https://data.illinois.gov/api/views/9ean-aer9) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/9ean-aer9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/9ean-aer9/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 9ean-aer9 |
| Name | Most Popular Baby Boy Names, 1980-2013 |
| Attribution | Illinois Department of Public Health, Office of Policy, Planning, and Statistics |
| Category | Health |
| Tags | health, baby, names, boy, popular |
| Created | 2014-08-19T20:41:37Z |
| Publication Date | 2014-08-19T20:43:46Z |

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
series e:9ean-aer9 d:1980-01-01T00:00:00.000Z t:name=Michael m:rank=1 m:frequency=3886

series e:9ean-aer9 d:1980-01-01T00:00:00.000Z t:name=Jason m:rank=2 m:frequency=2389

series e:9ean-aer9 d:1980-01-01T00:00:00.000Z t:name=Christopher m:rank=3 m:frequency=2273
```

## Meta Commands

```ls
metric m:rank p:integer l:Rank t:dataTypeName=number

metric m:frequency p:integer l:Frequency t:dataTypeName=number

entity e:9ean-aer9 l:"Most Popular Baby Boy Names, 1980-2013" t:attribution="Illinois Department of Public Health, Office of Policy, Planning, and Statistics" t:url=https://data.illinois.gov/api/views/9ean-aer9

property e:9ean-aer9 t:meta.view v:id=9ean-aer9 v:category=Health v:averageRating=0 v:name="Most Popular Baby Boy Names, 1980-2013" v:attribution="Illinois Department of Public Health, Office of Policy, Planning, and Statistics"

property e:9ean-aer9 t:meta.view.license v:name="Public Domain"

property e:9ean-aer9 t:meta.view.owner v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"

property e:9ean-aer9 t:meta.view.tableauthor v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"
```

## Top Records

```ls
| rank | year | name        | frequency | 
| ==== | ==== | =========== | ========= | 
| 1    | 1980 | Michael     | 3886      | 
| 2    | 1980 | Jason       | 2389      | 
| 3    | 1980 | Christopher | 2273      | 
| 4    | 1980 | Matthew     | 2112      | 
| 5    | 1980 | David       | 2088      | 
| 6    | 1980 | James       | 1925      | 
| 7    | 1980 | Robert      | 1763      | 
| 8    | 1980 | Daniel      | 1724      | 
| 9    | 1980 | John        | 1722      | 
| 10   | 1980 | Joseph      | 1710      | 
```