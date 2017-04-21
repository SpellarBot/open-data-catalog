# William Mead Homes-Age/Sex Profile

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/william-mead-homes-age-sex-profile) |
| Metadata | [Link](https://data.lacity.org/api/views/jxqs-eipk) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/jxqs-eipk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/jxqs-eipk/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | jxqs-eipk |
| Name | William Mead Homes-Age/Sex Profile |
| Attribution | HACLA |
| Category | A Livable and Sustainable City |
| Tags | housing authority for the city of los angeles, hacla, locations, public housing, housing, sites |
| Created | 2014-12-08T20:39:33Z |
| Publication Date | 2015-12-07T19:58:37Z |

## Description

2014 Age/Sex Profile

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | categories  | Categories | text      | text        |
| Yes      | numeric metric | male        | Male       | number    | number      |
| Yes      | numeric metric | female      | Female     | number    | number      |
| Yes      | numeric metric | total       | Total      | number    | number      |
| Yes      | numeric metric | percent     | Percent    | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:jxqs-eipk d:2014-12-08T12:39:36.000Z t:categories=0-5 m:total=94 m:percent=8.2 m:female=46 m:male=48

series e:jxqs-eipk d:2014-12-08T12:39:36.000Z t:categories=6-13 m:total=198 m:percent=17.2 m:female=91 m:male=107

series e:jxqs-eipk d:2014-12-08T12:39:36.000Z t:categories=14-17 m:total=90 m:percent=7.8 m:female=52 m:male=38
```

## Meta Commands

```ls
metric m:male p:integer l:Male t:dataTypeName=number

metric m:female p:integer l:Female t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

metric m:percent p:float l:Percent t:dataTypeName=percent

entity e:jxqs-eipk l:"William Mead Homes-Age/Sex Profile" t:attribution=HACLA t:url=https://data.lacity.org/api/views/jxqs-eipk

property e:jxqs-eipk t:meta.view v:id=jxqs-eipk v:category="A Livable and Sustainable City" v:averageRating=0 v:name="William Mead Homes-Age/Sex Profile" v:attribution=HACLA

property e:jxqs-eipk t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:jxqs-eipk t:meta.view.owner v:id=ihg6-62bp v:screenName="Rodd Talebi" v:displayName="Rodd Talebi"

property e:jxqs-eipk t:meta.view.tableauthor v:id=ihg6-62bp v:screenName="Rodd Talebi" v:displayName="Rodd Talebi"
```

## Top Records

```ls
| :updated_at | categories | male | female | total | percent | 
| =========== | ========== | ==== | ====== | ===== | ======= | 
| 1418042376  | 0-5        | 48   | 46     | 94    | 8.2     | 
| 1418042376  | 6-13       | 107  | 91     | 198   | 17.2    | 
| 1418042376  | 14-17      | 38   | 52     | 90    | 7.8     | 
| 1418042376  | 18-21      | 52   | 61     | 113   | 9.8     | 
| 1418042376  | 22-40      | 78   | 153    | 231   | 20.1    | 
| 1418042376  | 41-60      | 70   | 170    | 240   | 20.8    | 
| 1418042376  | 61+        | 56   | 130    | 186   | 16.1    | 
| 1418042376  | Total      | 449  | 703    | 1152  | 100.0   | 
```