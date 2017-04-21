# Statewide Barriers Removed

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/statewide-barriers-removed-60d10) |
| Metadata | [Link](https://data.wa.gov/api/views/kbzr-6x76) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/kbzr-6x76/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/kbzr-6x76/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | kbzr-6x76 |
| Name | Statewide Barriers Removed |
| Created | 2012-12-05T07:45:47Z |
| Publication Date | 2012-12-05T07:46:38Z |

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | time           | year               | Year               | number    | number      |
| Yes      | numeric metric | barriers_corrected | Barriers Corrected | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kbzr-6x76 d:2000-01-01T00:00:00.000Z m:barriers_corrected=279

series e:kbzr-6x76 d:2001-01-01T00:00:00.000Z m:barriers_corrected=305

series e:kbzr-6x76 d:2002-01-01T00:00:00.000Z m:barriers_corrected=288
```

## Meta Commands

```ls
metric m:barriers_corrected p:integer l:"Barriers Corrected" t:dataTypeName=number

entity e:kbzr-6x76 l:"Statewide Barriers Removed" t:url=https://data.wa.gov/api/views/kbzr-6x76

property e:kbzr-6x76 t:meta.view v:id=kbzr-6x76 v:averageRating=0 v:name="Statewide Barriers Removed"

property e:kbzr-6x76 t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:kbzr-6x76 t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| year | barriers_corrected | 
| ==== | ================== | 
| 2000 | 279                | 
| 2001 | 305                | 
| 2002 | 288                | 
| 2003 | 297                | 
| 2004 | 312                | 
| 2005 | 376                | 
| 2006 | 480                | 
| 2007 | 460                | 
| 2008 | 532                | 
| 2009 | 383                | 
```