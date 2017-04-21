# Hawaii International Study Direct Spending final

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hawaii-international-study-direct-spending-final-3b239) |
| Metadata | [Link](https://data.hawaii.gov/api/views/c2xi-ug2r) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/c2xi-ug2r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/c2xi-ug2r/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | c2xi-ug2r |
| Name | Hawaii International Study Direct Spending final |
| Created | 2013-06-26T20:40:02Z |
| Publication Date | 2013-06-26T21:27:09Z |

## Description

State of Hawaii International Study Direct Spending final

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
series e:c2xi-ug2r d:2010-01-01T00:00:00.000Z m:direct_spending=116800000

series e:c2xi-ug2r d:2011-01-01T00:00:00.000Z m:direct_spending=115000000

series e:c2xi-ug2r d:2012-01-01T00:00:00.000Z m:direct_spending=107100000
```

## Meta Commands

```ls
metric m:direct_spending p:integer l:"Direct Spending" t:dataTypeName=money

entity e:c2xi-ug2r l:"Hawaii International Study Direct Spending final" t:url=https://data.hawaii.gov/api/views/c2xi-ug2r

property e:c2xi-ug2r t:meta.view v:id=c2xi-ug2r v:averageRating=0 v:name="Hawaii International Study Direct Spending final"

property e:c2xi-ug2r t:meta.view.owner v:id=686a-saa8 v:screenName=Cy v:displayName=Cy

property e:c2xi-ug2r t:meta.view.tableauthor v:id=686a-saa8 v:screenName=Cy v:roleName=publisher v:displayName=Cy
```

## Top Records

```ls
| year | direct_spending | 
| ==== | =============== | 
| 2010 | 116800000       | 
| 2011 | 115000000       | 
| 2012 | 107100000       | 
```