# Test Charts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/test-charts-ac6ff) |
| Metadata | [Link](https://data.wa.gov/api/views/mhet-3a34) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/mhet-3a34/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/mhet-3a34/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | mhet-3a34 |
| Name | Test Charts |
| Created | 2013-06-13T02:32:35Z |
| Publication Date | 2013-06-13T02:33:20Z |

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | region        | Region        | text      | text        |
| Yes      | series tag     | category      | Category      | text      | text        |
| Yes      | numeric metric | dollar_amount | Dollar Amount | money     | money       |
| Yes      | numeric metric | none          | (none)        | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mhet-3a34 d:2013-06-12T19:32:36.000Z t:region="Hood Canal" t:category=Projects m:dollar_amount=43536960

series e:mhet-3a34 d:2013-06-12T19:32:36.000Z t:region="Hood Canal" t:category=Administration m:dollar_amount=3300099

series e:mhet-3a34 d:2013-06-12T19:32:36.000Z t:region="Hood Canal" t:category=Monitoring m:dollar_amount=672600
```

## Meta Commands

```ls
metric m:dollar_amount p:integer l:"Dollar Amount" t:dataTypeName=money

metric m:none p:integer l:(none) t:dataTypeName=money

entity e:mhet-3a34 l:"Test Charts" t:url=https://data.wa.gov/api/views/mhet-3a34

property e:mhet-3a34 t:meta.view v:id=mhet-3a34 v:averageRating=0 v:name="Test Charts"

property e:mhet-3a34 t:meta.view.owner v:id=ugen-sv2k v:screenName=Scott v:displayName=Scott

property e:mhet-3a34 t:meta.view.tableauthor v:id=ugen-sv2k v:screenName=Scott v:roleName=publisher v:displayName=Scott
```

## Top Records

```ls
| :updated_at | region          | category       | dollar_amount | none     | 
| =========== | =============== | ============== | ============= | ======== | 
| 1371065556  | Hood Canal      | Projects       | 43536960      |          | 
| 1371065556  | Hood Canal      | Administration | 3300099       |          | 
| 1371065556  | Hood Canal      | Monitoring     | 672600        |          | 
| 1371065556  | Hood Canal      | Total          | 47509659      | 47509659 | 
| 1371065556  | Lower Columbia  | Projects       | 41030604      |          | 
| 1371065556  | Lower Columbia  | Administration | 4354043       |          | 
| 1371065556  | Lower Columbia  | Monitoring     | 5135519       |          | 
| 1371065556  | Lower Columbia  | Total          | 50520166      | 50520166 | 
| 1371065556  | Middle Columbia | Projects       | 20512480      |          | 
| 1371065556  | Middle Columbia | Administration | 2398253       |          | 
```