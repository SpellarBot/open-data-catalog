# Adoption & Child Custody Advocacy - Performance Measures Custody Investigations - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/adoption-child-custody-advocacy-performance-measures-custody-investigations-2009-cabd5) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/ivna-ijvj) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ivna-ijvj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ivna-ijvj/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | ivna-ijvj |
| Name | Adoption & Child Custody Advocacy - Performance Measures Custody Investigations - 2009 |
| Attribution | Cook County Department of Adoption & Child Custody Advocacy |
| Category | Courts |
| Created | 2011-10-12T17:58:09Z |
| Publication Date | 2014-10-09T23:08:21Z |

## Description

The department is court ordered to complete a home investigation to determine which home is most suitable for permanency or increased visitation

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
| Yes      | numeric metric | totals_     | Totals     | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ivna-ijvj d:2009-01-01T00:00:00.000Z m:totals_=948 m:aug_=84 m:feb_=68 m:nov_=74 m:jan_=72 m:mar_=70 m:apr_=79 m:may_=83 m:dec_=81 m:oct_=86 m:jun_=79 m:jul_=88 m:sep_=84

series e:ivna-ijvj d:2009-01-01T00:00:00.000Z t:statistics_="In hours" m:totals_=7442 m:aug_=672 m:feb_=544 m:nov_=592 m:jan_=576 m:mar_=560 m:apr_=632 m:may_=704 m:dec_=466 m:oct_=688 m:jun_=632 m:jul_=704 m:sep_=672

series e:ivna-ijvj d:2009-01-01T00:00:00.000Z m:totals_=374 m:aug_=30 m:feb_=29 m:nov_=29 m:jan_=34 m:mar_=24 m:apr_=34 m:may_=32 m:dec_=19 m:oct_=37 m:jun_=33 m:jul_=32 m:sep_=41
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

metric m:totals_ p:integer l:Totals t:dataTypeName=number

entity e:ivna-ijvj l:"Adoption & Child Custody Advocacy - Performance Measures Custody Investigations - 2009" t:attribution="Cook County Department of Adoption & Child Custody Advocacy" t:url=https://datacatalog.cookcountyil.gov/api/views/ivna-ijvj

property e:ivna-ijvj t:meta.view v:id=ivna-ijvj v:category=Courts v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/adoption___child_custody_advocacy/245 v:averageRating=0 v:name="Adoption & Child Custody Advocacy - Performance Measures Custody Investigations - 2009" v:attribution="Cook County Department of Adoption & Child Custody Advocacy"

property e:ivna-ijvj t:meta.view.license v:name="Public Domain"

property e:ivna-ijvj t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:ivna-ijvj t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```

## Top Records

```ls
| statistics_      | dec_ | jan_ | feb_ | mar_ | apr_ | may_ | jun_ | jul_ | aug_ | sep_ | oct_ | nov_ | totals_ | 
| ================ | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ======= | 
| Output Demands   |      |      |      |      |      |      |      |      |      |      |      |      |         | 
|                  | 81   | 72   | 68   | 70   | 79   | 83   | 79   | 88   | 84   | 84   | 86   | 74   | 948     | 
| Inputs           |      |      |      |      |      |      |      |      |      |      |      |      |         | 
| In hours         | 466  | 576  | 544  | 560  | 632  | 704  | 632  | 704  | 672  | 672  | 688  | 592  | 7442    | 
| Output Workloads |      |      |      |      |      |      |      |      |      |      |      |      |         | 
|                  | 19   | 34   | 29   | 24   | 34   | 32   | 33   | 32   | 30   | 41   | 37   | 29   | 374     | 
| Efficiencies     |      |      |      |      |      |      |      |      |      |      |      |      |         | 
|                  | 5    | 8    | 8    | 7    | 4    | 8    | 8    | 8    | 8    | 8    | 8    | 8    | 88      | 
| Effectiveness    |      |      |      |      |      |      |      |      |      |      |      |      |         | 
|                  | 5    | 8    | 8    | 7    | 4    | 8    | 8    | 8    | 8    | 8    | 8    | 8    | 88      | 
```