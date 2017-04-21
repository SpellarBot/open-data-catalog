# Total Funding By Source1

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/total-funding-by-source1-aeb50) |
| Metadata | [Link](https://data.wa.gov/api/views/gssb-7xw5) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/gssb-7xw5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/gssb-7xw5/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | gssb-7xw5 |
| Name | Total Funding By Source1 |
| Created | 2012-10-29T16:33:27Z |
| Publication Date | 2012-10-29T16:33:47Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | biennium    | Biennium   | text      | text        |
| Yes      | numeric metric | funding     | Funding    | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:gssb-7xw5 d:2012-10-29T09:33:28.000Z t:biennium=1999-01 m:funding=169990013

series e:gssb-7xw5 d:2012-10-29T09:33:28.000Z t:biennium=2001-03 m:funding=106139000

series e:gssb-7xw5 d:2012-10-29T09:33:28.000Z t:biennium=2003-05 m:funding=98357563
```

## Meta Commands

```ls
metric m:funding p:integer l:Funding t:dataTypeName=money

entity e:gssb-7xw5 l:"Total Funding By Source1" t:url=https://data.wa.gov/api/views/gssb-7xw5

property e:gssb-7xw5 t:meta.view v:id=gssb-7xw5 v:averageRating=0 v:name="Total Funding By Source1"

property e:gssb-7xw5 t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:gssb-7xw5 t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| :updated_at | biennium | funding   | 
| =========== | ======== | ========= | 
| 1351503208  | 1999-01  | 169990013 | 
| 1351503208  | 2001-03  | 106139000 | 
| 1351503208  | 2003-05  | 98357563  | 
| 1351503208  | 2005-07  | 113039237 | 
| 1351503208  | 2007-09  | 157336789 | 
| 1351503208  | 2009-11  | 142732557 | 
| 1351503208  | 2011-13  | 64299579  | 
```