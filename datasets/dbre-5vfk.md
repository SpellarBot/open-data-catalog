# 2 -- Government $$ By Biennium

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2-government-by-biennium-9914b) |
| Metadata | [Link](https://data.wa.gov/api/views/dbre-5vfk) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/dbre-5vfk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/dbre-5vfk/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | dbre-5vfk |
| Name | 2 -- Government $$ By Biennium |
| Created | 2012-10-17T12:37:48Z |
| Publication Date | 2012-10-17T12:38:16Z |
| Rows Updated | 2012-10-17T12:37:52Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | biennium         | Biennium         | text      | text        |
| Yes      | numeric metric | state_all        | State -- All     | money     | money       |
| Yes      | numeric metric | local_all        | Local -- All     | money     | money       |
| Yes      | numeric metric | federal_all      | Federal -- All   | money     | money       |
| Yes      | numeric metric | total            | Total            | money     | money       |
| Yes      | numeric metric | cumulative_total | Cumulative Total | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:dbre-5vfk d:2012-10-17T05:37:50.000Z t:biennium=1999-01 m:state_all=37040000 m:total=169990013 m:cumulative_total=169990013 m:federal_all=75304074 m:local_all=57645939

series e:dbre-5vfk d:2012-10-17T05:37:50.000Z t:biennium=2001-03 m:state_all=26351000 m:total=106139000 m:cumulative_total=276129012 m:federal_all=67801316 m:local_all=11986684

series e:dbre-5vfk d:2012-10-17T05:37:50.000Z t:biennium=2003-05 m:state_all=14000000 m:total=98357563 m:cumulative_total=374486575 m:federal_all=55302606 m:local_all=29054957
```

## Meta Commands

```ls
metric m:state_all p:integer l:"State -- All" t:dataTypeName=money

metric m:local_all p:integer l:"Local -- All" t:dataTypeName=money

metric m:federal_all p:integer l:"Federal -- All" t:dataTypeName=money

metric m:total p:integer l:Total t:dataTypeName=money

metric m:cumulative_total p:integer l:"Cumulative Total" t:dataTypeName=money

entity e:dbre-5vfk l:"2 -- Government $$ By Biennium" t:url=https://data.wa.gov/api/views/dbre-5vfk

property e:dbre-5vfk t:meta.view v:id=dbre-5vfk v:averageRating=0 v:name="2 -- Government $$ By Biennium"

property e:dbre-5vfk t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:dbre-5vfk t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```