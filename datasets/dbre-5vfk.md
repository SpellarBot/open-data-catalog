# 2 -- Government $$ By Biennium

## Dataset

* [Dataset URL](https://data.wa.gov/api/views/dbre-5vfk/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/2-government-by-biennium-9914b)
* [Metadata URL](https://data.wa.gov/api/views/dbre-5vfk)
* Id = dbre-5vfk
* Name = 2 -- Government $$ By Biennium
* Created = 2012-10-17T12:37:48Z
* Publication Date = 2012-10-17T12:38:16Z
* Rows Updated = 2012-10-17T12:37:52Z

## Description



## Columns

```ls
| Name             | Field Name       | Data Type | Render Type | Schema Type    | Included | 
| ================ | ================ | ========= | =========== | ============== | ======== | 
| updated_at       | :updated_at      | meta_data | meta_data   | time           | No       | 
| Biennium         | biennium         | text      | text        | series tag     | Yes      | 
| State -- All     | state_all        | money     | money       | numeric metric | Yes      | 
| Local -- All     | local_all        | money     | money       | numeric metric | Yes      | 
| Federal -- All   | federal_all      | money     | money       | numeric metric | Yes      | 
| Total            | total            | money     | money       | numeric metric | Yes      | 
| Cumulative Total | cumulative_total | money     | money       | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:dbre-5vfk d:2012-10-17T05:37:50.000Z t:biennium=1999-01 m:state_all=37040000 m:total=169990013 m:cumulative_total=169990013 m:federal_all=75304074 m:local_all=57645939

series e:dbre-5vfk d:2012-10-17T05:37:50.000Z t:biennium=2001-03 m:state_all=26351000 m:total=106139000 m:cumulative_total=276129012 m:federal_all=67801316 m:local_all=11986684

series e:dbre-5vfk d:2012-10-17T05:37:50.000Z t:biennium=2003-05 m:state_all=14000000 m:total=98357563 m:cumulative_total=374486575 m:federal_all=55302606 m:local_all=29054957
```

## Meta Commands

```ls
entity e:dbre-5vfk l:"2 -- Government $$ By Biennium" t:url=https://data.wa.gov/api/views/dbre-5vfk

property e:dbre-5vfk t:meta.view d:2017-03-08T01:29:14.986Z v:id=dbre-5vfk v:averageRating=0 v:name="2 -- Government $$ By Biennium"

property e:dbre-5vfk t:meta.view.owner d:2017-03-08T01:29:14.986Z v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"

property e:dbre-5vfk t:meta.view.tableauthor d:2017-03-08T01:29:14.986Z v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```