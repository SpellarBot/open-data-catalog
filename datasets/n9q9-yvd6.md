# Lottery Sales By Game

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lottery-sales-by-game) |
| Metadata | [Link](https://data.ct.gov/api/views/n9q9-yvd6) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/n9q9-yvd6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/n9q9-yvd6/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | n9q9-yvd6 |
| Name | Lottery Sales By Game |
| Attribution | CT Dept of Consumer Protection |
| Category | Government |
| Tags | lottery sales |
| Created | 2014-10-14T19:04:44Z |
| Publication Date | 2014-10-14T19:07:48Z |

## Description

Lottery Sales By Game

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | fiscal_year   | Fiscal Year   | text      | text        |
| Yes      | numeric metric | weekly        | Weekly        | money     | money       |
| Yes      | numeric metric | instant       | Instant       | money     | money       |
| Yes      | numeric metric | daily         | Daily         | money     | money       |
| Yes      | numeric metric | lotto         | Lotto         | money     | money       |
| Yes      | numeric metric | cash5         | Cash5         | money     | money       |
| Yes      | numeric metric | powerball     | Powerball     | money     | money       |
| Yes      | numeric metric | lucky_4_life  | Lucky-4-Life  | money     | money       |
| Yes      | numeric metric | mega_millions | Mega Millions | money     | money       |
| Yes      | numeric metric | csd           | CSD           | money     | money       |
| Yes      | numeric metric | total         | Total         | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:n9q9-yvd6 d:2014-10-14T12:04:57.000Z t:fiscal_year=1972 m:weekly=17288925 m:total=17288925

series e:n9q9-yvd6 d:2014-10-14T12:04:57.000Z t:fiscal_year=1973 m:weekly=34711849 m:total=34711849

series e:n9q9-yvd6 d:2014-10-14T12:04:57.000Z t:fiscal_year=1974 m:weekly=30752727 m:total=30752727
```

## Meta Commands

```ls
metric m:weekly p:integer l:Weekly t:dataTypeName=money

metric m:instant p:long l:Instant t:dataTypeName=money

metric m:daily p:long l:Daily t:dataTypeName=money

metric m:lotto p:long l:Lotto t:dataTypeName=money

metric m:cash5 p:integer l:Cash5 t:dataTypeName=money

metric m:powerball p:integer l:Powerball t:dataTypeName=money

metric m:lucky_4_life p:integer l:Lucky-4-Life t:dataTypeName=money

metric m:mega_millions p:integer l:"Mega Millions" t:dataTypeName=money

metric m:csd p:integer l:CSD t:dataTypeName=money

metric m:total p:long l:Total t:dataTypeName=money

entity e:n9q9-yvd6 l:"Lottery Sales By Game" t:attribution="CT Dept of Consumer Protection" t:url=https://data.ct.gov/api/views/n9q9-yvd6

property e:n9q9-yvd6 t:meta.view v:id=n9q9-yvd6 v:category=Government v:attributionLink="http://www.ct.gov/dcp/cwp/view.asp?a=4332&q=480854" v:averageRating=0 v:name="Lottery Sales By Game" v:attribution="CT Dept of Consumer Protection"

property e:n9q9-yvd6 t:meta.view.license v:name="Public Domain"

property e:n9q9-yvd6 t:meta.view.owner v:id=ewkk-db5a v:screenName=WilliamR v:displayName=WilliamR

property e:n9q9-yvd6 t:meta.view.tableauthor v:id=ewkk-db5a v:screenName=WilliamR v:roleName=editor v:displayName=WilliamR
```

## Top Records

```ls
| :updated_at | fiscal_year | weekly   | instant  | daily    | lotto | cash5 | powerball | lucky_4_life | mega_millions | csd | total     | 
| =========== | =========== | ======== | ======== | ======== | ===== | ===== | ========= | ============ | ============= | === | ========= | 
| 1413288297  | 1972        | 17288925 |          |          |       |       |           |              |               |     | 17288925  | 
| 1413288297  | 1973        | 34711849 |          |          |       |       |           |              |               |     | 34711849  | 
| 1413288297  | 1974        | 30752727 |          |          |       |       |           |              |               |     | 30752727  | 
| 1413288297  | 1975        | 30894815 |          |          |       |       |           |              |               |     | 30894815  | 
| 1413288297  | 1976        | 29493098 | 41927201 |          |       |       |           |              |               |     | 71420299  | 
| 1413288297  | 1977        | 25824711 | 23826954 | 13082292 |       |       |           |              |               |     | 62733957  | 
| 1413288297  | 1978        | 19201917 | 41863247 | 46391128 |       |       |           |              |               |     | 107456292 | 
| 1413288297  | 1979        | 12871166 | 49725859 | 58327191 |       |       |           |              |               |     | 120924216 | 
| 1413288297  | 1980        | 11525566 | 45505590 | 73167966 |       |       |           |              |               |     | 130199122 | 
| 1413288297  | 1981        | 10103356 | 56162297 | 84695066 |       |       |           |              |               |     | 150960719 | 
```