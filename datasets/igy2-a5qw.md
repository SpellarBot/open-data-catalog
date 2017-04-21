# Adoption & Child Custody Advocacy - Performance Measures Adoptions Investigations - 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/adoption-child-custody-advocacy-performance-measures-adoptions-investigations-2008-d55f1) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/igy2-a5qw) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/igy2-a5qw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/igy2-a5qw/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | igy2-a5qw |
| Name | Adoption & Child Custody Advocacy - Performance Measures Adoptions Investigations - 2008 |
| Attribution | Cook County Department of Adoption & Child Custody Advocacy |
| Category | Courts |
| Created | 2011-10-11T22:38:54Z |
| Publication Date | 2014-10-09T23:00:59Z |

## Description

The department is court ordered to complete a home investigation to determine if potential adoptive family whom is seeking permanency is suitable for placement.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| Yes      | series tag     | statistics_ | Statistics | text      | text        |
| Yes      | numeric metric | dec_        | Dec        | number    | number      |
| Yes      | numeric metric | jan_        | Jan        | number    | number      |
| Yes      | numeric metric | feb_        | Feb        | number    | number      |
| Yes      | numeric metric | mar_        | Mar        | number    | number      |
| Yes      | numeric metric | apr_        | Apr        | number    | number      |
| Yes      | numeric metric | may_        | May        | number    | number      |
| Yes      | numeric metric | jun_        | Jun        | number    | number      |
| Yes      | numeric metric | jul_        | Jul        | number    | number      |
| Yes      | numeric metric | aug_        | Aug        | number    | number      |
| Yes      | numeric metric | sep_        | Sep        | number    | number      |
| Yes      | numeric metric | oct_        | Oct        | number    | number      |
| Yes      | numeric metric | nov_        | Nov        | number    | number      |
| Yes      | numeric metric | est_2008_   | Est. 2008  | number    | number      |
```

## Time Field

```ls
Value = 2008
Format & Zone = yyyy
```

## Data Commands

```ls
series e:igy2-a5qw d:2008-01-01T00:00:00.000Z m:aug_=17 m:est_2008_=115 m:feb_=6 m:nov_=14 m:mar_=12 m:jan_=4 m:apr_=10 m:may_=4 m:oct_=10 m:dec_=16 m:jun_=12 m:jul_=6 m:sep_=4

series e:igy2-a5qw d:2008-01-01T00:00:00.000Z m:aug_=32 m:est_2008_=580 m:feb_=34 m:nov_=56 m:mar_=48 m:jan_=32 m:apr_=80 m:may_=24 m:oct_=80 m:dec_=96 m:jun_=48 m:jul_=34 m:sep_=16

series e:igy2-a5qw d:2008-01-01T00:00:00.000Z m:aug_=5 m:est_2008_=57 m:feb_=3 m:nov_=4 m:mar_=2 m:jan_=2 m:apr_=5 m:may_=2 m:oct_=6 m:dec_=8 m:jun_=6 m:jul_=10 m:sep_=4
```

## Meta Commands

```ls
metric m:dec_ p:integer l:Dec t:dataTypeName=number

metric m:jan_ p:integer l:Jan t:dataTypeName=number

metric m:feb_ p:integer l:Feb t:dataTypeName=number

metric m:mar_ p:integer l:Mar t:dataTypeName=number

metric m:apr_ p:integer l:Apr t:dataTypeName=number

metric m:may_ p:integer l:May t:dataTypeName=number

metric m:jun_ p:integer l:Jun t:dataTypeName=number

metric m:jul_ p:integer l:Jul t:dataTypeName=number

metric m:aug_ p:integer l:Aug t:dataTypeName=number

metric m:sep_ p:integer l:Sep t:dataTypeName=number

metric m:oct_ p:integer l:Oct t:dataTypeName=number

metric m:nov_ p:integer l:Nov t:dataTypeName=number

metric m:est_2008_ p:integer l:"Est. 2008" t:dataTypeName=number

entity e:igy2-a5qw l:"Adoption & Child Custody Advocacy - Performance Measures Adoptions Investigations - 2008" t:attribution="Cook County Department of Adoption & Child Custody Advocacy" t:url=https://datacatalog.cookcountyil.gov/api/views/igy2-a5qw

property e:igy2-a5qw t:meta.view v:id=igy2-a5qw v:category=Courts v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/adoption___child_custody_advocacy/245 v:averageRating=0 v:name="Adoption & Child Custody Advocacy - Performance Measures Adoptions Investigations - 2008" v:attribution="Cook County Department of Adoption & Child Custody Advocacy"

property e:igy2-a5qw t:meta.view.license v:name="Public Domain"

property e:igy2-a5qw t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:igy2-a5qw t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```

## Top Records

```ls
| statistics_      | dec_ | jan_ | feb_ | mar_ | apr_ | may_ | jun_ | jul_ | aug_ | sep_ | oct_ | nov_ | est_2008_ | 
| ================ | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ========= | 
| Output Demands   |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 16   | 4    | 6    | 12   | 10   | 4    | 12   | 6    | 17   | 4    | 10   | 14   | 115       | 
| Inputs           |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 96   | 32   | 34   | 48   | 80   | 24   | 48   | 34   | 32   | 16   | 80   | 56   | 580       | 
| Output Workloads |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 8    | 2    | 3    | 2    | 5    | 2    | 6    | 10   | 5    | 4    | 6    | 4    | 57        | 
| Efficiencies     |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 6    | 4    | 5    | 4    | 16   | 12   | 8    | 6    | 8    | 4    | 16   | 8    | 97        | 
| Effectiveness    |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 6    | 4    | 5    | 4    | 16   | 12   | 8    | 6    | 8    | 4    | 16   | 8    | 97        | 
```