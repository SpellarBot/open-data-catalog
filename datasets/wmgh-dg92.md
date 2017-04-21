# Pet Data - 2015 Return to Owner

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-data-2015-return-to-owner) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/wmgh-dg92) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/wmgh-dg92/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/wmgh-dg92/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | wmgh-dg92 |
| Name | Pet Data - 2015 Return to Owner |
| Category | Government |
| Created | 2015-02-06T20:03:47Z |
| Publication Date | 2016-02-03T17:40:20Z |

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | month                     | Month                     | text      | text        |
| Yes      | numeric metric | animals_returned_to_owner | Animals Returned to Owner | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wmgh-dg92 d:2015-01-01T00:00:00.000Z t:month=Jan m:animals_returned_to_owner=51

series e:wmgh-dg92 d:2015-01-01T00:00:00.000Z t:month=Feb m:animals_returned_to_owner=50

series e:wmgh-dg92 d:2015-01-01T00:00:00.000Z t:month=Apr m:animals_returned_to_owner=59
```

## Meta Commands

```ls
metric m:animals_returned_to_owner p:integer l:"Animals Returned to Owner" t:dataTypeName=number

entity e:wmgh-dg92 l:"Pet Data - 2015 Return to Owner" t:url=https://data.kingcounty.gov/api/views/wmgh-dg92

property e:wmgh-dg92 t:meta.view v:id=wmgh-dg92 v:category=Government v:averageRating=0 v:name="Pet Data - 2015 Return to Owner"

property e:wmgh-dg92 t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:wmgh-dg92 t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| month | animals_returned_to_owner | 
| ===== | ========================= | 
| Jan   | 51                        | 
| Feb   | 50                        | 
| Apr   | 59                        | 
| May   | 46                        | 
| Jun   | 71                        | 
| Jul   | 71                        | 
| Sep   | 64                        | 
| Oct   | 77                        | 
| Nov   | 40                        | 
| Dec   | 65                        | 
```