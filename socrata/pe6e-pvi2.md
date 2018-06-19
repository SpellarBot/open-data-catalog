# Pet Data - 2017 Intakes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-data-2017-intakes) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/pe6e-pvi2) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/pe6e-pvi2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/pe6e-pvi2/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | pe6e-pvi2 |
| Name | Pet Data - 2017 Intakes |
| Created | 2017-01-18T17:04:54Z |
| Publication Date | 2017-03-03T19:41:25Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name    | Data Type | Render Type |
| ======== | ============== | ========== | ======= | ========= | =========== |
| Yes      | series tag     | month      | Month   | text      | text        |
| Yes      | numeric metric | intakes    | Intakes | number    | number      |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:pe6e-pvi2 d:2017-01-01T00:00:00.000Z t:month=Mar m:intakes=0

series e:pe6e-pvi2 d:2017-01-01T00:00:00.000Z t:month=Apr m:intakes=0

series e:pe6e-pvi2 d:2017-01-01T00:00:00.000Z t:month=May m:intakes=0
```

## Meta Commands

```ls
metric m:intakes p:integer l:Intakes t:dataTypeName=number

entity e:pe6e-pvi2 l:"Pet Data - 2017 Intakes" t:url=https://data.kingcounty.gov/api/views/pe6e-pvi2

property e:pe6e-pvi2 t:meta.view v:id=pe6e-pvi2 v:averageRating=0 v:name="Pet Data - 2017 Intakes"

property e:pe6e-pvi2 t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:pe6e-pvi2 t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| month | intakes | 
| ===== | ======= | 
| Mar   | 0       | 
| Apr   | 0       | 
| May   | 0       | 
| Jun   | 0       | 
| Jul   | 0       | 
| Aug   | 0       | 
| Sep   | 0       | 
| Oct   | 0       | 
| Nov   | 0       | 
| Dec   | 0       | 
```