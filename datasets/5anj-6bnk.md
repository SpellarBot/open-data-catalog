# Joseph Creek Summer Steelhead -- 1112015

## Dataset

* [Dataset URL](https://data.wa.gov/api/views/5anj-6bnk/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/joseph-creek-summer-steelhead-1112015-ced11)
* Id = 5anj-6bnk
* Name = Joseph Creek Summer Steelhead -- 1112015
* Created = 2015-01-12T04:48:16Z
* Publication Date = 2015-01-12T04:49:15Z
* Rows Updated = 2015-01-12T04:48:25Z

## Description



## Columns

```ls
| Name                    | Field Name              | Data Type | Render Type | Schema Type    | Included | 
| ======================= | ======================= | ========= | =========== | ============== | ======== | 
| Population/Stock Number | population_stock_number | number    | number      | numeric metric | Yes      | 
| Year                    | year                    | number    | number      | time           | Yes      | 
| Wild                    | wild                    | number    | number      | numeric metric | Yes      | 
| Hatchery                | hatchery                | number    | number      | numeric metric | Yes      | 
| Wild + Hatchery         | wild_hatchery           | number    | number      | numeric metric | Yes      | 
| Goal (Wild)             | goal_wild               | number    | number      | numeric metric | Yes      | 
| Population/Stock Name   | population_stock_name   | text      | text        | series tag     | Yes      | 
| Listing Year            | listing_year            | number    | number      |                | No       | 
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = listing_year
Annotation Fields = 
```

## Data Commands

```ls
series e:5anj-6bnk d:1997-01-01T00:00:00.000Z t:population_stock_name="Joseph Creek Summer Steelhead" m:population_stock_number=6884 m:wild=1251 m:wild_hatchery=1251 m:goal_wild=1000

series e:5anj-6bnk d:1998-01-01T00:00:00.000Z t:population_stock_name="Joseph Creek Summer Steelhead" m:population_stock_number=6884 m:wild=3171 m:wild_hatchery=3171 m:goal_wild=1000

series e:5anj-6bnk d:1999-01-01T00:00:00.000Z t:population_stock_name="Joseph Creek Summer Steelhead" m:population_stock_number=6884 m:wild=2133 m:wild_hatchery=2133 m:goal_wild=1000
```

## Meta Commands

```ls
metric m:population_stock_number p:integer l:"Population/Stock Number" t:dataTypeName=number

metric m:wild p:integer l:Wild t:dataTypeName=number

metric m:hatchery l:Hatchery t:dataTypeName=number

metric m:wild_hatchery p:integer l:"Wild + Hatchery" t:dataTypeName=number

metric m:goal_wild p:integer l:"Goal (Wild)" t:dataTypeName=number

entity e:5anj-6bnk l:"Joseph Creek Summer Steelhead -- 1112015" t:url=https://data.wa.gov/api/views/5anj-6bnk

property e:5anj-6bnk t:meta.view d:2017-03-03T14:33:46.710Z v:id=5anj-6bnk v:averageRating=0 v:name="Joseph Creek Summer Steelhead -- 1112015"

property e:5anj-6bnk t:meta.view.owner d:2017-03-03T14:33:46.710Z v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"

property e:5anj-6bnk t:meta.view.tableauthor d:2017-03-03T14:33:46.710Z v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```