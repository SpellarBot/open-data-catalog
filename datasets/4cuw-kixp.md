# Statewide Stream Miles Opened

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/statewide-stream-miles-opened-37ab4) |
| Metadata | [Link](https://data.wa.gov/api/views/4cuw-kixp) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/4cuw-kixp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/4cuw-kixp/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 4cuw-kixp |
| Name | Statewide Stream Miles Opened |
| Created | 2012-12-05T07:47:14Z |
| Publication Date | 2012-12-05T07:56:53Z |

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | time           | year                | Year                | number    | number      |
| Yes      | numeric metric | stream_miles_opened | Stream Miles Opened | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4cuw-kixp d:2000-01-01T00:00:00.000Z m:stream_miles_opened=301

series e:4cuw-kixp d:2001-01-01T00:00:00.000Z m:stream_miles_opened=313

series e:4cuw-kixp d:2002-01-01T00:00:00.000Z m:stream_miles_opened=344
```

## Meta Commands

```ls
metric m:stream_miles_opened p:integer l:"Stream Miles Opened" t:dataTypeName=number

entity e:4cuw-kixp l:"Statewide Stream Miles Opened" t:url=https://data.wa.gov/api/views/4cuw-kixp

property e:4cuw-kixp t:meta.view v:id=4cuw-kixp v:averageRating=0 v:name="Statewide Stream Miles Opened"

property e:4cuw-kixp t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:4cuw-kixp t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| year | stream_miles_opened | 
| ==== | =================== | 
| 2000 | 301                 | 
| 2001 | 313                 | 
| 2002 | 344                 | 
| 2003 | 345                 | 
| 2004 | 314                 | 
| 2005 | 390                 | 
| 2006 | 446                 | 
| 2007 | 483                 | 
| 2008 | 565                 | 
| 2009 | 298                 | 
```