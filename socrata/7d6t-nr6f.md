# Funding By Category -- All -- 12212012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/funding-by-category-all-12212012-cd551) |
| Metadata | [Link](https://data.wa.gov/api/views/7d6t-nr6f) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/7d6t-nr6f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/7d6t-nr6f/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 7d6t-nr6f |
| Name | Funding By Category -- All -- 12212012 |
| Created | 2012-11-13T17:54:08Z |
| Publication Date | 2012-12-25T23:49:31Z |

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | region        | Region        | text      | text        |
| Yes      | series tag     | category      | Category      | text      | text        |
| Yes      | numeric metric | dollar_amount | Dollar Amount | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7d6t-nr6f d:2012-12-25T15:49:18.000Z t:region="Hood Canal" t:category=Projects m:dollar_amount=43536960

series e:7d6t-nr6f d:2012-12-25T15:49:18.000Z t:region="Hood Canal" t:category=Administration m:dollar_amount=3300099

series e:7d6t-nr6f d:2012-12-25T15:49:18.000Z t:region="Hood Canal" t:category=Monitoring m:dollar_amount=672600
```

## Meta Commands

```ls
metric m:dollar_amount p:integer l:"Dollar Amount" t:dataTypeName=money

entity e:7d6t-nr6f l:"Funding By Category -- All -- 12212012" t:url=https://data.wa.gov/api/views/7d6t-nr6f

property e:7d6t-nr6f t:meta.view v:id=7d6t-nr6f v:averageRating=0 v:name="Funding By Category -- All -- 12212012"

property e:7d6t-nr6f t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:7d6t-nr6f t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| :updated_at | region          | category       | dollar_amount | 
| =========== | =============== | ============== | ============= | 
| 1356450558  | Hood Canal      | Projects       | 43536960      | 
| 1356450558  | Hood Canal      | Administration | 3300099       | 
| 1356450558  | Hood Canal      | Monitoring     | 672600        | 
| 1356450558  | Hood Canal      | Total          | 47509659      | 
| 1356450558  | Lower Columbia  | Projects       | 41030604      | 
| 1356450558  | Lower Columbia  | Administration | 4354043       | 
| 1356450558  | Lower Columbia  | Monitoring     | 5135519       | 
| 1356450558  | Lower Columbia  | Total          | 50520166      | 
| 1356450558  | Middle Columbia | Projects       | 20512480      | 
| 1356450558  | Middle Columbia | Administration | 2398253       | 
```