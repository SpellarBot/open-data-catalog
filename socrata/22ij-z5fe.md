# Hawaii International Study Market Share Compare To US

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hawaii-international-study-market-share-compare-to-us-e431c) |
| Metadata | [Link](https://data.hawaii.gov/api/views/22ij-z5fe) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/22ij-z5fe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/22ij-z5fe/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 22ij-z5fe |
| Name | Hawaii International Study Market Share Compare To US |
| Created | 2013-06-27T00:08:55Z |
| Publication Date | 2014-01-03T19:58:57Z |

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | time           | year         | Year         | number    | text        |
| Yes      | numeric metric | market_share | Market Share | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:22ij-z5fe d:2010-01-01T00:00:00.000Z m:market_share=0.6

series e:22ij-z5fe d:2011-01-01T00:00:00.000Z m:market_share=0.6

series e:22ij-z5fe d:2012-01-01T00:00:00.000Z m:market_share=0.5
```

## Meta Commands

```ls
metric m:market_share p:float l:"Market Share" t:dataTypeName=percent

entity e:22ij-z5fe l:"Hawaii International Study Market Share Compare To US" t:url=https://data.hawaii.gov/api/views/22ij-z5fe

property e:22ij-z5fe t:meta.view v:id=22ij-z5fe v:averageRating=0 v:name="Hawaii International Study Market Share Compare To US"

property e:22ij-z5fe t:meta.view.owner v:id=686a-saa8 v:screenName=Cy v:displayName=Cy

property e:22ij-z5fe t:meta.view.tableauthor v:id=686a-saa8 v:screenName=Cy v:roleName=publisher v:displayName=Cy
```

## Top Records

```ls
| year | market_share | 
| ==== | ============ | 
| 2010 | 0.60         | 
| 2011 | 0.60         | 
| 2012 | 0.5          | 
| 2013 | 0.45         | 
```