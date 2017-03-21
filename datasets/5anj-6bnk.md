# Joseph Creek Summer Steelhead -- 1112015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/joseph-creek-summer-steelhead-1112015-ced11) |
| Metadata | [Link](https://data.wa.gov/api/views/5anj-6bnk) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/5anj-6bnk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/5anj-6bnk/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 5anj-6bnk |
| Name | Joseph Creek Summer Steelhead -- 1112015 |
| Created | 2015-01-12T04:48:16Z |
| Publication Date | 2015-01-12T04:49:15Z |
| Rows Updated | 2015-01-12T04:48:25Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | population_stock_number | Population/Stock Number | text      | number      |
| Yes      | time           | year                    | Year                    | number    | number      |
| Yes      | numeric metric | wild                    | Wild                    | number    | number      |
| Yes      | numeric metric | hatchery                | Hatchery                | number    | number      |
| Yes      | numeric metric | wild_hatchery           | Wild + Hatchery         | number    | number      |
| Yes      | numeric metric | goal_wild               | Goal (Wild)             | number    | number      |
| Yes      | series tag     | population_stock_name   | Population/Stock Name   | text      | text        |
| No       |                | listing_year            | Listing Year            | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = listing_year
```

## Data Commands

```ls
series e:5anj-6bnk d:1997-01-01T00:00:00.000Z t:population_stock_number=6884 t:population_stock_name="Joseph Creek Summer Steelhead" m:wild=1251 m:wild_hatchery=1251 m:goal_wild=1000

series e:5anj-6bnk d:1998-01-01T00:00:00.000Z t:population_stock_number=6884 t:population_stock_name="Joseph Creek Summer Steelhead" m:wild=3171 m:wild_hatchery=3171 m:goal_wild=1000

series e:5anj-6bnk d:1999-01-01T00:00:00.000Z t:population_stock_number=6884 t:population_stock_name="Joseph Creek Summer Steelhead" m:wild=2133 m:wild_hatchery=2133 m:goal_wild=1000
```

## Meta Commands

```ls
metric m:wild p:integer l:Wild t:dataTypeName=number

metric m:hatchery p:long l:Hatchery t:dataTypeName=number

metric m:wild_hatchery p:integer l:"Wild + Hatchery" t:dataTypeName=number

metric m:goal_wild p:integer l:"Goal (Wild)" t:dataTypeName=number

entity e:5anj-6bnk l:"Joseph Creek Summer Steelhead -- 1112015" t:url=https://data.wa.gov/api/views/5anj-6bnk

property e:5anj-6bnk t:meta.view v:id=5anj-6bnk v:averageRating=0 v:name="Joseph Creek Summer Steelhead -- 1112015"

property e:5anj-6bnk t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:5anj-6bnk t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```