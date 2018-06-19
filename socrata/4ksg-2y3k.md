# Funding By Project Type -- All -- 12212012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/funding-by-project-type-all-12212012-04d7f) |
| Metadata | [Link](https://data.wa.gov/api/views/4ksg-2y3k) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/4ksg-2y3k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/4ksg-2y3k/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 4ksg-2y3k |
| Name | Funding By Project Type -- All -- 12212012 |
| Created | 2012-11-13T18:59:37Z |
| Publication Date | 2012-12-25T23:50:30Z |

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | region        | Region        | text      | text        |
| Yes      | series tag     | project_type  | Project Type  | text      | text        |
| Yes      | numeric metric | dollar_amount | Dollar Amount | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:4ksg-2y3k d:2012-12-25T15:50:18.000Z t:region="Hood Canal" t:project_type=Restoration m:dollar_amount=28919828

series e:4ksg-2y3k d:2012-12-25T15:50:18.000Z t:region="Hood Canal" t:project_type=Acquisition m:dollar_amount=13807613

series e:4ksg-2y3k d:2012-12-25T15:50:18.000Z t:region="Hood Canal" t:project_type=Other m:dollar_amount=4782218
```

## Meta Commands

```ls
metric m:dollar_amount p:double l:"Dollar Amount" t:dataTypeName=money

entity e:4ksg-2y3k l:"Funding By Project Type -- All -- 12212012" t:url=https://data.wa.gov/api/views/4ksg-2y3k

property e:4ksg-2y3k t:meta.view v:id=4ksg-2y3k v:averageRating=0 v:name="Funding By Project Type -- All -- 12212012"

property e:4ksg-2y3k t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:4ksg-2y3k t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| :updated_at | region          | project_type | dollar_amount | 
| =========== | =============== | ============ | ============= | 
| 1356450618  | Hood Canal      | Restoration  | 28919828      | 
| 1356450618  | Hood Canal      | Acquisition  | 13807613      | 
| 1356450618  | Hood Canal      | Other        | 4782218       | 
| 1356450618  | Hood Canal      | Total        | 47509659      | 
| 1356450618  | Lower Columbia  | Restoration  | 29401576      | 
| 1356450618  | Lower Columbia  | Acquisition  | 4622631       | 
| 1356450618  | Lower Columbia  | Other        | 16495959      | 
| 1356450618  | Lower Columbia  | Total        | 50520166      | 
| 1356450618  | Middle Columbia | Restoration  | 15537470      | 
| 1356450618  | Middle Columbia | Acquisition  | 4757402       | 
```