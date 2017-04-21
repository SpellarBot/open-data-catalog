# 3 -- Government $$ By Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/3-government-by-year-5b51b) |
| Metadata | [Link](https://data.wa.gov/api/views/ht3z-vfgq) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/ht3z-vfgq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/ht3z-vfgq/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | ht3z-vfgq |
| Name | 3 -- Government $$ By Year |
| Created | 2012-10-17T12:39:48Z |
| Publication Date | 2012-10-17T12:40:18Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | time           | year             | Year             | number    | number      |
| Yes      | numeric metric | state_all        | State -- All     | money     | money       |
| Yes      | numeric metric | local_all        | Local -- All     | money     | money       |
| Yes      | numeric metric | federal_all      | Federal -- All   | money     | money       |
| Yes      | numeric metric | total            | Total            | money     | money       |
| Yes      | numeric metric | cumulative_total | Cumulative Total | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ht3z-vfgq d:1999-01-01T00:00:00.000Z m:state_all=0 m:total=31555133 m:cumulative_total=31555133 m:federal_all=19750000 m:local_all=11805133

series e:ht3z-vfgq d:2000-01-01T00:00:00.000Z m:state_all=37040000 m:total=84735943 m:cumulative_total=116291076 m:federal_all=21026004 m:local_all=26669939

series e:ht3z-vfgq d:2001-01-01T00:00:00.000Z m:state_all=0 m:total=53698937 m:cumulative_total=169990013 m:federal_all=34528070 m:local_all=19170867
```

## Meta Commands

```ls
metric m:state_all p:double l:"State -- All" t:dataTypeName=money

metric m:local_all p:integer l:"Local -- All" t:dataTypeName=money

metric m:federal_all p:integer l:"Federal -- All" t:dataTypeName=money

metric m:total p:integer l:Total t:dataTypeName=money

metric m:cumulative_total p:integer l:"Cumulative Total" t:dataTypeName=money

entity e:ht3z-vfgq l:"3 -- Government $$ By Year" t:url=https://data.wa.gov/api/views/ht3z-vfgq

property e:ht3z-vfgq t:meta.view v:id=ht3z-vfgq v:averageRating=0 v:name="3 -- Government $$ By Year"

property e:ht3z-vfgq t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:ht3z-vfgq t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| year | state_all | local_all | federal_all | total     | cumulative_total | 
| ==== | ========= | ========= | =========== | ========= | ================ | 
| 1999 | 0.0       | 11805133  | 19750000    | 31555133  | 31555133         | 
| 2000 | 37040000  | 26669939  | 21026004    | 84735943  | 116291076        | 
| 2001 | 0.0       | 19170867  | 34528070    | 53698937  | 169990013        | 
| 2002 | 26351000  | 11325322  | 37301484    | 74977806  | 244967818        | 
| 2003 | 0.0       | 661362    | 30499832    | 31161194  | 276129012        | 
| 2004 | 14000000  | 13245642  | 28549967    | 55795609  | 331924621        | 
| 2005 | 0.0       | 15809315  | 26752639    | 42561954  | 374486575        | 
| 2006 | 22150000  | 14850013  | 23631322    | 60631335  | 435117910        | 
| 2007 | 0.0       | 28688005  | 23750303    | 52438308  | 487556218        | 
| 2008 | 64750000  | 20726449  | 23890960    | 109367409 | 596923627        | 
```