# State Tax Revenue On International Study

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-tax-revenue-on-international-study-b6ce7) |
| Metadata | [Link](https://data.hawaii.gov/api/views/6c5h-urdb) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/6c5h-urdb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/6c5h-urdb/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 6c5h-urdb |
| Name | State Tax Revenue On International Study |
| Created | 2013-06-27T00:15:56Z |
| Publication Date | 2014-02-11T00:50:40Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | year        | Year        | number    | text        |
| Yes      | numeric metric | tax_revenue | Tax Revenue | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6c5h-urdb d:2013-01-01T00:00:00.000Z m:tax_revenue=15850000

series e:6c5h-urdb d:2011-01-01T00:00:00.000Z m:tax_revenue=16790000

series e:6c5h-urdb d:2010-01-01T00:00:00.000Z m:tax_revenue=17050000
```

## Meta Commands

```ls
metric m:tax_revenue p:integer l:"Tax Revenue" t:dataTypeName=money

entity e:6c5h-urdb l:"State Tax Revenue On International Study" t:url=https://data.hawaii.gov/api/views/6c5h-urdb

property e:6c5h-urdb t:meta.view v:id=6c5h-urdb v:averageRating=0 v:name="State Tax Revenue On International Study"

property e:6c5h-urdb t:meta.view.owner v:id=686a-saa8 v:screenName=Cy v:displayName=Cy

property e:6c5h-urdb t:meta.view.tableauthor v:id=686a-saa8 v:screenName=Cy v:roleName=publisher v:displayName=Cy
```

## Top Records

```ls
| year | tax_revenue | 
| ==== | =========== | 
| 2013 | 15850000    | 
| 2011 | 16790000    | 
| 2010 | 17050000    | 
| 2008 | 17170000    | 
| 2009 | 16240000    | 
| 2012 | 15650000    | 
```