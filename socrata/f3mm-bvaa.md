# Total Funding By Category

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/total-funding-by-category-7503e) |
| Metadata | [Link](https://data.wa.gov/api/views/f3mm-bvaa) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/f3mm-bvaa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/f3mm-bvaa/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | f3mm-bvaa |
| Name | Total Funding By Category |
| Created | 2012-10-29T17:29:01Z |
| Publication Date | 2012-10-29T17:30:24Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | time           | fiscal_year    | Fiscal Year    | number    | number      |
| Yes      | numeric metric | projects       | Projects       | money     | money       |
| Yes      | numeric metric | administration | Administration | money     | money       |
| Yes      | numeric metric | monitoring     | Monitoring     | money     | money       |
| Yes      | numeric metric | total          | Total          | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:f3mm-bvaa d:1999-01-01T00:00:00.000Z m:total=29212482.18 m:projects=27363996.69 m:monitoring=1030485.49 m:administration=818000

series e:f3mm-bvaa d:2000-01-01T00:00:00.000Z m:total=46868109.27 m:projects=41073921.13 m:monitoring=3955082.39 m:administration=1839105.75

series e:f3mm-bvaa d:2001-01-01T00:00:00.000Z m:total=50017409.05 m:projects=44231091.12 m:monitoring=3985131.56 m:administration=1801186.36
```

## Meta Commands

```ls
metric m:projects p:double l:Projects t:dataTypeName=money

metric m:administration p:double l:Administration t:dataTypeName=money

metric m:monitoring p:double l:Monitoring t:dataTypeName=money

metric m:total p:double l:Total t:dataTypeName=money

entity e:f3mm-bvaa l:"Total Funding By Category" t:url=https://data.wa.gov/api/views/f3mm-bvaa

property e:f3mm-bvaa t:meta.view v:id=f3mm-bvaa v:averageRating=0 v:name="Total Funding By Category"

property e:f3mm-bvaa t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:f3mm-bvaa t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| fiscal_year | projects    | administration | monitoring  | total       | 
| =========== | =========== | ============== | =========== | =========== | 
| 1999        | 27363996.69 | 818000         | 1030485.49  | 29212482.18 | 
| 2000        | 41073921.13 | 1839105.75     | 3955082.39  | 46868109.27 | 
| 2001        | 44231091.12 | 1801186.36     | 3985131.56  | 50017409.05 | 
| 2002        | 33123762.31 | 3670374.59     | 5935996.20  | 42730133.10 | 
| 2003        | 7874495.22  | 13200313.6     | 10044644.41 | 31119453.23 | 
| 2004        | 29555335.59 | 1659077.80     | 3834185.72  | 35048599.12 | 
| 2005        | 32335596.00 | 6161805.87     | 1300302.29  | 39797704.17 | 
| 2006        | 25653099.14 | 873493.40      | 1205127.3   | 27731719.85 | 
| 2007        | 60511739.52 | 9154814.41     | 11033300.95 | 80699854.90 | 
| 2008        | 36544969.09 | 1732808.86     | 208000      | 38485777.95 | 
```