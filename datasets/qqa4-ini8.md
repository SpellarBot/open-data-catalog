# Illinois Population Changes By Decade, 1980-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/illinois-population-changes-by-decade-1980-2010-bdb30) |
| Metadata | [Link](https://data.illinois.gov/api/views/qqa4-ini8) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/qqa4-ini8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/qqa4-ini8/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | qqa4-ini8 |
| Name | Illinois Population Changes By Decade, 1980-2010 |
| Attribution | Illinois Department of Public Health, Office of Policy, Planning, and Statistics, Illinois Center for Health Statistics |
| Category | Health |
| Tags | population, changes, decade |
| Created | 2014-08-11T20:50:42Z |
| Publication Date | 2014-08-11T20:53:10Z |

## Description

Data provided by the IL Center for Health Statistics

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                         | Data Type | Render Type |
| ======== | ============== | =========================== | ============================ | ========= | =========== |
| Yes      | series tag     | county                      | County                       | text      | text        |
| Yes      | numeric metric | 1980_census                 | 1980 Census                  | number    | number      |
| Yes      | numeric metric | 1990_census                 | 1990 Census                  | number    | number      |
| Yes      | numeric metric | 2000_census                 | 2000 Census                  | number    | number      |
| Yes      | numeric metric | 2010_census                 | 2010 Census                  | number    | number      |
| Yes      | numeric metric | percent_change_1980_to_1990 | Percent Change, 1980 to 1990 | number    | number      |
| Yes      | numeric metric | percent_change_1990_to_2000 | Percent Change, 1990 to 2000 | number    | number      |
| Yes      | numeric metric | percent_change_2000_to_2010 | Percent Change, 2000 to 2010 | number    | number      |
```

## Time Field

```ls
Value = 1980
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qqa4-ini8 d:1980-01-01T00:00:00.000Z t:county=Illinois m:percent_change_1980_to_1990=0.04 m:percent_change_1990_to_2000=8.6 m:1990_census=11430602 m:2010_census=12830632 m:1980_census=11426518 m:2000_census=12419293 m:percent_change_2000_to_2010=3.3

series e:qqa4-ini8 d:1980-01-01T00:00:00.000Z t:county=Adams m:percent_change_1980_to_1990=-7.7 m:percent_change_1990_to_2000=3.3 m:1990_census=66090 m:2010_census=67103 m:1980_census=71622 m:2000_census=68277 m:percent_change_2000_to_2010=-1.7

series e:qqa4-ini8 d:1980-01-01T00:00:00.000Z t:county=Alexander m:percent_change_1980_to_1990=-13.4 m:percent_change_1990_to_2000=-9.7 m:1990_census=10626 m:2010_census=8238 m:1980_census=12264 m:2000_census=9590 m:percent_change_2000_to_2010=-14.1
```

## Meta Commands

```ls
metric m:1980_census p:integer l:"1980 Census" t:dataTypeName=number

metric m:1990_census p:integer l:"1990 Census" t:dataTypeName=number

metric m:2000_census p:integer l:"2000 Census" t:dataTypeName=number

metric m:2010_census p:integer l:"2010 Census" t:dataTypeName=number

metric m:percent_change_1980_to_1990 p:float l:"Percent Change, 1980 to 1990" t:dataTypeName=number

metric m:percent_change_1990_to_2000 p:float l:"Percent Change, 1990 to 2000" t:dataTypeName=number

metric m:percent_change_2000_to_2010 p:float l:"Percent Change, 2000 to 2010" t:dataTypeName=number

entity e:qqa4-ini8 l:"Illinois Population Changes By Decade, 1980-2010" t:attribution="Illinois Department of Public Health, Office of Policy, Planning, and Statistics, Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/qqa4-ini8

property e:qqa4-ini8 t:meta.view v:id=qqa4-ini8 v:category=Health v:averageRating=0 v:name="Illinois Population Changes By Decade, 1980-2010" v:attribution="Illinois Department of Public Health, Office of Policy, Planning, and Statistics, Illinois Center for Health Statistics"

property e:qqa4-ini8 t:meta.view.license v:name="Public Domain"

property e:qqa4-ini8 t:meta.view.owner v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"

property e:qqa4-ini8 t:meta.view.tableauthor v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"
```

## Top Records

```ls
| county    | 1980_census | 1990_census | 2000_census | 2010_census | percent_change_1980_to_1990 | percent_change_1990_to_2000 | percent_change_2000_to_2010 | 
| ========= | =========== | =========== | =========== | =========== | =========================== | =========================== | =========================== | 
| Illinois  | 11426518    | 11430602    | 12419293    | 12830632    | 0.04                        | 8.6                         | 3.3                         | 
| Adams     | 71622       | 66090       | 68277       | 67103       | -7.7                        | 3.3                         | -1.7                        | 
| Alexander | 12264       | 10626       | 9590        | 8238        | -13.4                       | -9.6999999999999993         | -14.1                       | 
| Bond      | 16224       | 14991       | 17633       | 17768       | -7.6                        | 17.600000000000001          | 0.8                         | 
| Boone     | 28630       | 30806       | 41786       | 54165       | 7.6                         | 35.6                        | 29.6                        | 
| Brown     | 5411        | 5836        | 6950        | 6937        | 7.9                         | 19.100000000000001          | -0.2                        | 
| Bureau    | 39114       | 35688       | 35503       | 34978       | -8.8000000000000007         | -0.5                        | -1.5                        | 
| Calhoun   | 5867        | 5322        | 5084        | 5089        | -9.3000000000000007         | -4.5                        | 0.1                         | 
| Carroll   | 18779       | 16805       | 16674       | 15387       | -10.5                       | -0.8                        | -7.7                        | 
| Cass      | 15084       | 13437       | 13695       | 13642       | -10.9                       | 1.9                         | -0.4                        | 
```