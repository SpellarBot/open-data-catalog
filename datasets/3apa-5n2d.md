# 2Biennial Funding by Category (8-22-2016)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/funding-by-category-2014-sosiw-1052015) |
| Metadata | [Link](https://data.wa.gov/api/views/3apa-5n2d) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/3apa-5n2d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/3apa-5n2d/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 3apa-5n2d |
| Name | 2Biennial Funding by Category (8-22-2016) |
| Tags | state-of-the-salmon |
| Created | 2014-10-03T14:15:57Z |
| Publication Date | 2016-09-19T18:35:07Z |

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | region        | Region        | text      | text        |
| Yes      | series tag     | category      | Category      | text      | text        |
| Yes      | numeric metric | dollar_amount | Dollar Amount | money     | money       |
| Yes      | numeric metric | percent       | Percent       | percent   | percent     |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3apa-5n2d d:2016-01-01T00:00:00.000Z t:region="Hood Canal" t:category=Acquisition m:percent=21 m:dollar_amount=9648423

series e:3apa-5n2d d:2016-01-01T00:00:00.000Z t:region="Hood Canal" t:category=Capacity m:percent=0 m:dollar_amount=15000

series e:3apa-5n2d d:2016-01-01T00:00:00.000Z t:region="Hood Canal" t:category=Hatchery m:percent=4 m:dollar_amount=1627319
```

## Meta Commands

```ls
metric m:dollar_amount p:integer l:"Dollar Amount" t:dataTypeName=money

metric m:percent p:double l:Percent t:dataTypeName=percent

entity e:3apa-5n2d l:"2Biennial Funding by Category (8-22-2016)" t:url=https://data.wa.gov/api/views/3apa-5n2d

property e:3apa-5n2d t:meta.view v:id=3apa-5n2d v:averageRating=0 v:name="2Biennial Funding by Category (8-22-2016)"

property e:3apa-5n2d t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:3apa-5n2d t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| region         | category            | dollar_amount | percent | 
| ============== | =================== | ============= | ======= | 
| Hood Canal     | Acquisition         | 9648423       | 21      | 
| Hood Canal     | Capacity            | 15000         | 0       | 
| Hood Canal     | Hatchery            | 1627319       | 4       | 
| Hood Canal     | Monitoring          | 2770005       | 6       | 
| Hood Canal     | Other               | 0             | 0       | 
| Hood Canal     | Planning/Assessment | 8843215       | 19      | 
| Hood Canal     | Restoration         | 22528442      | 50      | 
|                | Total               | 45432403      | 100     | 
| Lower Columbia | Acquisition         | 5221780       | 7       | 
| Lower Columbia | Capacity            | 633250        | 1       | 
```