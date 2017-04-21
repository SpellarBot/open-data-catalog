# Statewide Hatcheries 01092013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/statewide-hatcheries-01092013-e6b0d) |
| Metadata | [Link](https://data.wa.gov/api/views/b5sx-erfa) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/b5sx-erfa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/b5sx-erfa/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | b5sx-erfa |
| Name | Statewide Hatcheries 01092013 |
| Created | 2013-01-09T15:25:50Z |
| Publication Date | 2013-01-09T15:47:07Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | year        | Year        | number    | text        |
| Yes      | numeric metric | meeting     | Meeting     | percent   | percent     |
| Yes      | numeric metric | not_meeting | Not meeting | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:b5sx-erfa d:1998-01-01T00:00:00.000Z m:not_meeting=82 m:meeting=18

series e:b5sx-erfa d:2008-01-01T00:00:00.000Z m:not_meeting=75 m:meeting=25

series e:b5sx-erfa d:2010-01-01T00:00:00.000Z m:not_meeting=55 m:meeting=45
```

## Meta Commands

```ls
metric m:meeting p:integer l:Meeting t:dataTypeName=percent

metric m:not_meeting p:integer l:"Not meeting" t:dataTypeName=percent

entity e:b5sx-erfa l:"Statewide Hatcheries 01092013" t:url=https://data.wa.gov/api/views/b5sx-erfa

property e:b5sx-erfa t:meta.view v:id=b5sx-erfa v:averageRating=0 v:name="Statewide Hatcheries 01092013"

property e:b5sx-erfa t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:b5sx-erfa t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| year | meeting | not_meeting | 
| ==== | ======= | =========== | 
| 1998 | 18      | 82          | 
| 2008 | 25      | 75          | 
| 2010 | 45      | 55          | 
| 2011 | 61      | 39          | 
```