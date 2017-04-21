# Stream Miles Opened 12192012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/stream-miles-opened-12192012-72850) |
| Metadata | [Link](https://data.wa.gov/api/views/qb7y-xuum) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/qb7y-xuum/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/qb7y-xuum/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | qb7y-xuum |
| Name | Stream Miles Opened 12192012 |
| Created | 2012-12-17T21:00:27Z |
| Publication Date | 2012-12-19T23:15:57Z |

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | region       | Region       | text      | text        |
| Yes      | time           | year         | Year         | number    | number      |
| Yes      | numeric metric | miles_opened | Miles Opened | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qb7y-xuum d:2009-01-01T00:00:00.000Z t:region="Hood Canal" m:miles_opened=11

series e:qb7y-xuum d:2010-01-01T00:00:00.000Z t:region="Hood Canal" m:miles_opened=10

series e:qb7y-xuum d:2011-01-01T00:00:00.000Z t:region="Hood Canal" m:miles_opened=9
```

## Meta Commands

```ls
metric m:miles_opened p:integer l:"Miles Opened" t:dataTypeName=number

entity e:qb7y-xuum l:"Stream Miles Opened 12192012" t:url=https://data.wa.gov/api/views/qb7y-xuum

property e:qb7y-xuum t:meta.view v:id=qb7y-xuum v:averageRating=0 v:name="Stream Miles Opened 12192012"

property e:qb7y-xuum t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:qb7y-xuum t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| region         | year | miles_opened | 
| ============== | ==== | ============ | 
| Hood Canal     | 2009 | 11           | 
| Hood Canal     | 2010 | 10           | 
| Hood Canal     | 2011 | 9            | 
| Hood Canal     | 2012 | 26           | 
|                |      | 56           | 
| Lower Columbia | 2009 | 67           | 
| Lower Columbia | 2010 | 68           | 
| Lower Columbia | 2011 | 93           | 
| Lower Columbia | 2012 | 52           | 
|                |      | 280          | 
```