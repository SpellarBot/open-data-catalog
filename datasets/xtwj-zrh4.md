# Hawaii International Study Direct Spending-2

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hawaii-international-study-direct-spending-2-dbd42) |
| Metadata | [Link](https://data.hawaii.gov/api/views/xtwj-zrh4) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/xtwj-zrh4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/xtwj-zrh4/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | xtwj-zrh4 |
| Name | Hawaii International Study Direct Spending-2 |
| Created | 2013-06-26T23:59:06Z |
| Publication Date | 2014-02-11T00:44:20Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | time           | year            | Year            | number    | text        |
| Yes      | numeric metric | direct_spending | Direct Spending | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xtwj-zrh4 d:2011-01-01T00:00:00.000Z m:direct_spending=115000000

series e:xtwj-zrh4 d:2008-01-01T00:00:00.000Z m:direct_spending=118000000

series e:xtwj-zrh4 d:2009-01-01T00:00:00.000Z m:direct_spending=111000000
```

## Meta Commands

```ls
metric m:direct_spending p:integer l:"Direct Spending" t:dataTypeName=money

entity e:xtwj-zrh4 l:"Hawaii International Study Direct Spending-2" t:url=https://data.hawaii.gov/api/views/xtwj-zrh4

property e:xtwj-zrh4 t:meta.view v:id=xtwj-zrh4 v:averageRating=0 v:name="Hawaii International Study Direct Spending-2"

property e:xtwj-zrh4 t:meta.view.owner v:id=686a-saa8 v:screenName=Cy v:displayName=Cy

property e:xtwj-zrh4 t:meta.view.tableauthor v:id=686a-saa8 v:screenName=Cy v:roleName=publisher v:displayName=Cy
```

## Top Records

```ls
| year | direct_spending | 
| ==== | =============== | 
| 2011 | 115000000       | 
| 2008 | 118000000       | 
| 2009 | 111000000       | 
| 2010 | 117000000       | 
| 2012 | 107000000       | 
| 2013 | 109000000       | 
```