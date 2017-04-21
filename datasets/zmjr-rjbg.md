# Oregon Prison Population, Total Inmate Count, 1980 to 2011, Monthly

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-prison-population-total-inmate-count-1980-to-2011-monthly-18bbf) |
| Metadata | [Link](https://data.oregon.gov/api/views/zmjr-rjbg) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/zmjr-rjbg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/zmjr-rjbg/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | zmjr-rjbg |
| Name | Oregon Prison Population, Total Inmate Count, 1980 to 2011, Monthly |
| Attribution | Oregon Office of Economic Analysis |
| Category | Public Safety |
| Tags | oregon prison population total inmate count inmates prisoners number oregon forecast economic analysis |
| Created | 2012-02-13T21:41:48Z |
| Publication Date | 2012-02-13T22:08:41Z |

## Description

Dates and the count of inmates in the State of Oregon's prison system for the date. Based on a DOC report for 1980 -1993. Based on query of DOC data for 1994-current. JSUM population snapshot person-level detail, count status='IN' and responsible location not 'IBRO or 'OYA'. Alternate valid counts exist.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | date        | Date        | date      | date        |
| Yes      | numeric metric | inmatecount | InmateCount | number    | number      |
```

## Time Field

```ls
Value = date
Format & Zone = seconds
```

## Data Commands

```ls
series e:zmjr-rjbg d:1980-01-01T08:00:00.000Z m:inmatecount=3120

series e:zmjr-rjbg d:1980-02-01T08:00:00.000Z m:inmatecount=2976

series e:zmjr-rjbg d:1980-03-01T08:00:00.000Z m:inmatecount=2899
```

## Meta Commands

```ls
metric m:inmatecount p:integer l:InmateCount t:dataTypeName=number

entity e:zmjr-rjbg l:"Oregon Prison Population, Total Inmate Count, 1980 to 2011, Monthly" t:attribution="Oregon Office of Economic Analysis" t:url=https://data.oregon.gov/api/views/zmjr-rjbg

property e:zmjr-rjbg t:meta.view v:id=zmjr-rjbg v:category="Public Safety" v:averageRating=0 v:name="Oregon Prison Population, Total Inmate Count, 1980 to 2011, Monthly" v:attribution="Oregon Office of Economic Analysis"

property e:zmjr-rjbg t:meta.view.license v:name="Public Domain"

property e:zmjr-rjbg t:meta.view.owner v:id=am3y-vzet v:screenName="Damon Bell" v:displayName="Damon Bell"

property e:zmjr-rjbg t:meta.view.tableauthor v:id=am3y-vzet v:screenName="Damon Bell" v:displayName="Damon Bell"
```

## Top Records

```ls
| date      | inmatecount | 
| ========= | =========== | 
|           |             | 
| 315561600 | 3120        | 
| 318240000 | 2976        | 
| 320745600 | 2899        | 
| 323424000 | 2905        | 
| 326012400 | 2933        | 
| 328690800 | 2954        | 
| 331282800 | 3036        | 
| 333961200 | 3044        | 
| 336639600 | 2962        | 
```