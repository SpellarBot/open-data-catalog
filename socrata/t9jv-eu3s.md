# C -- $$ By Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/c-by-year-decdc) |
| Metadata | [Link](https://data.wa.gov/api/views/t9jv-eu3s) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/t9jv-eu3s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/t9jv-eu3s/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | t9jv-eu3s |
| Name | C -- $$ By Year |
| Created | 2012-10-19T18:58:29Z |
| Publication Date | 2012-10-19T19:00:09Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | year        | Year        | number    | number      |
| Yes      | numeric metric | state       | State       | money     | money       |
| Yes      | numeric metric | federal     | Federal     | money     | money       |
| Yes      | numeric metric | local_match | Local Match | money     | money       |
| Yes      | numeric metric | total       | Total       | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:t9jv-eu3s d:1999-01-01T00:00:00.000Z m:total=31555133 m:local_match=11805133 m:federal=19750000 m:state=0

series e:t9jv-eu3s d:2000-01-01T00:00:00.000Z m:total=84735943 m:local_match=26669939 m:federal=21026004 m:state=37040000

series e:t9jv-eu3s d:2001-01-01T00:00:00.000Z m:total=53698937 m:local_match=19170867 m:federal=34528070 m:state=0
```

## Meta Commands

```ls
metric m:state p:double l:State t:dataTypeName=money

metric m:federal p:integer l:Federal t:dataTypeName=money

metric m:local_match p:integer l:"Local Match" t:dataTypeName=money

metric m:total p:integer l:Total t:dataTypeName=money

entity e:t9jv-eu3s l:"C -- $$ By Year" t:url=https://data.wa.gov/api/views/t9jv-eu3s

property e:t9jv-eu3s t:meta.view v:id=t9jv-eu3s v:averageRating=0 v:name="C -- $$ By Year"

property e:t9jv-eu3s t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:t9jv-eu3s t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| year | state    | federal  | local_match | total     | 
| ==== | ======== | ======== | =========== | ========= | 
| 1999 | 0.0      | 19750000 | 11805133    | 31555133  | 
| 2000 | 37040000 | 21026004 | 26669939    | 84735943  | 
| 2001 | 0.0      | 34528070 | 19170867    | 53698937  | 
| 2002 | 26351000 | 37301484 | 11325322    | 74977806  | 
| 2003 | 0.0      | 30499832 | 661362      | 31161194  | 
| 2004 | 14000000 | 28549967 | 13245642    | 55795609  | 
| 2005 | 0.0      | 26752639 | 15809315    | 42561954  | 
| 2006 | 22150000 | 23631322 | 14850013    | 60631335  | 
| 2007 | 0.0      | 23750303 | 28688006    | 52438309  | 
| 2008 | 64750000 | 23890960 | 20726449    | 109367409 | 
```