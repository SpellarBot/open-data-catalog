# IDVA - Veterans Data by County

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idva-veterans-data-by-county-9a764) |
| Metadata | [Link](https://data.illinois.gov/api/views/szpd-xiya) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/szpd-xiya/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/szpd-xiya/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | szpd-xiya |
| Name | IDVA - Veterans Data by County |
| Attribution | Illinois Department of Veterans Affairs |
| Category | Reference |
| Tags | idva, county, vet, veteran |
| Created | 2012-02-02T17:10:10Z |
| Publication Date | 2012-02-02T17:16:03Z |

## Description

This data contains the number of veterans per county who have an Illinois address recorded in the IDVA Veteran Database(not all Illinois veterans).

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | county              | County              | text      | text        |
| Yes      | numeric metric | veterans_per_county | Veterans per County | number    | number      |
| Yes      | numeric metric | males               | Males               | number    | number      |
| Yes      | numeric metric | females             | Females             | number    | number      |
| Yes      | numeric metric | without_dependents  | Without Dependents  | number    | number      |
| Yes      | numeric metric | with_dependents     | With Dependents     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:szpd-xiya d:2012-02-02T09:10:18.000Z t:county=Adams m:with_dependents=338 m:veterans_per_county=5922 m:males=5589 m:females=231 m:without_dependents=5584

series e:szpd-xiya d:2012-02-02T09:10:18.000Z t:county=Alexander m:with_dependents=24 m:veterans_per_county=579 m:males=515 m:females=54 m:without_dependents=555

series e:szpd-xiya d:2012-02-02T09:10:18.000Z t:county=Bond m:with_dependents=41 m:veterans_per_county=932 m:males=872 m:females=48 m:without_dependents=891
```

## Meta Commands

```ls
metric m:veterans_per_county p:integer l:"Veterans per County" t:dataTypeName=number

metric m:males p:integer l:Males t:dataTypeName=number

metric m:females p:integer l:Females t:dataTypeName=number

metric m:without_dependents p:integer l:"Without Dependents" t:dataTypeName=number

metric m:with_dependents p:integer l:"With Dependents" t:dataTypeName=number

entity e:szpd-xiya l:"IDVA -  Veterans Data by County" t:attribution="Illinois Department of Veterans Affairs" t:url=https://data.illinois.gov/api/views/szpd-xiya

property e:szpd-xiya t:meta.view v:id=szpd-xiya v:category=Reference v:averageRating=0 v:name="IDVA -  Veterans Data by County" v:attribution="Illinois Department of Veterans Affairs"

property e:szpd-xiya t:meta.view.owner v:id=ajuq-3qfp v:screenName="Chris Pence" v:displayName="Chris Pence"

property e:szpd-xiya t:meta.view.tableauthor v:id=ajuq-3qfp v:screenName="Chris Pence" v:displayName="Chris Pence"
```

## Top Records

```ls
| :updated_at | county    | veterans_per_county | males | females | without_dependents | with_dependents | 
| =========== | ========= | =================== | ===== | ======= | ================== | =============== | 
| 1328173818  | Adams     | 5922                | 5589  | 231     | 5584               | 338             | 
| 1328173818  | Alexander | 579                 | 515   | 54      | 555                | 24              | 
| 1328173818  | Bond      | 932                 | 872   | 48      | 891                | 41              | 
| 1328173818  | Boone     | 1363                | 1243  | 89      | 1242               | 121             | 
| 1328173818  | Brown     | 112                 | 99    | 9       | 92                 | 20              | 
| 1328173818  | Bureau    | 3268                | 3024  | 161     | 3174               | 94              | 
| 1328173818  | Calhoun   | 266                 | 254   | 10      | 246                | 20              | 
| 1328173818  | Carroll   | 993                 | 925   | 44      | 938                | 55              | 
| 1328173818  | Cass      | 1018                | 935   | 62      | 884                | 134             | 
| 1328173818  | Champaign | 7995                | 7099  | 647     | 7723               | 272             | 
```