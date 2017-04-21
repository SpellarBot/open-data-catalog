# Test Rco Data -- 9302014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/test-rco-data-9302014-9190f) |
| Metadata | [Link](https://data.wa.gov/api/views/cgjt-kvnb) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/cgjt-kvnb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/cgjt-kvnb/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | cgjt-kvnb |
| Name | Test Rco Data -- 9302014 |
| Created | 2014-09-30T18:54:23Z |
| Publication Date | 2014-09-30T18:57:34Z |

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
series e:cgjt-kvnb d:2014-09-30T11:54:26.000Z t:region="Hood Canal" t:category=Projects m:dollar_amount=43536960

series e:cgjt-kvnb d:2014-09-30T11:54:26.000Z t:region="Hood Canal" t:category=Administration m:dollar_amount=3300099

series e:cgjt-kvnb d:2014-09-30T11:54:26.000Z t:region="Hood Canal" t:category=Monitoring m:dollar_amount=672600
```

## Meta Commands

```ls
metric m:dollar_amount p:integer l:"Dollar Amount" t:dataTypeName=money

metric m:none p:integer l:(none) t:dataTypeName=money

entity e:cgjt-kvnb l:"Test Rco Data -- 9302014" t:url=https://data.wa.gov/api/views/cgjt-kvnb

property e:cgjt-kvnb t:meta.view v:id=cgjt-kvnb v:averageRating=0 v:name="Test Rco Data -- 9302014"

property e:cgjt-kvnb t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:cgjt-kvnb t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| :updated_at | region          | category       | dollar_amount | none     | 
| =========== | =============== | ============== | ============= | ======== | 
| 1412078066  | Hood Canal      | Projects       | 43536960      |          | 
| 1412078066  | Hood Canal      | Administration | 3300099       |          | 
| 1412078066  | Hood Canal      | Monitoring     | 672600        |          | 
| 1412078066  | Hood Canal      | Total          | 47509659      | 47509659 | 
| 1412078066  | Lower Columbia  | Projects       | 41030604      |          | 
| 1412078066  | Lower Columbia  | Administration | 4354043       |          | 
| 1412078066  | Lower Columbia  | Monitoring     | 5135519       |          | 
| 1412078066  | Lower Columbia  | Total          | 50520166      | 50520166 | 
| 1412078066  | Middle Columbia | Projects       | 20512480      |          | 
| 1412078066  | Middle Columbia | Administration | 2398253       |          | 
```