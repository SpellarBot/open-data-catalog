# Adoption & Child Custody Advocacy - Performance Measures Adoptive Investigations - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/adoption-child-custody-advocacy-performance-measures-adoptive-investigations-2009-f668e) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/dqxz-2g7x) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/dqxz-2g7x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/dqxz-2g7x/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | dqxz-2g7x |
| Name | Adoption & Child Custody Advocacy - Performance Measures Adoptive Investigations - 2009 |
| Attribution | Cook County Department of Adoption & Child Custody Advocacy |
| Category | Courts |
| Created | 2011-10-12T17:49:00Z |
| Publication Date | 2014-10-09T23:10:29Z |

## Description

The department is court ordered to complete a home investigation to determine if potential adoptive family whom is seeking permanency is suitable for placement

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
| Yes      | numeric metric | est_2009_   | Est. 2009  | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:dqxz-2g7x d:2009-01-01T00:00:00.000Z m:aug_=28 m:nov_=13 m:mar_=26 m:jan_=18 m:may_=23 m:oct_=13 m:dec_=10 m:jul_=34 m:sep_=30 m:feb_=10 m:apr_=19 m:jun_=20 m:est_2009_=244

series e:dqxz-2g7x d:2009-01-01T00:00:00.000Z m:aug_=224 m:nov_=104 m:mar_=208 m:jan_=72 m:may_=184 m:oct_=104 m:dec_=80 m:jul_=272 m:sep_=240 m:feb_=80 m:apr_=152 m:jun_=160 m:est_2009_=1880

series e:dqxz-2g7x d:2009-01-01T00:00:00.000Z m:aug_=2 m:nov_=6 m:mar_=1 m:jan_=2 m:may_=6 m:oct_=3 m:dec_=2 m:jul_=7 m:sep_=2 m:feb_=4 m:apr_=6 m:jun_=3 m:est_2009_=44
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

metric m:est_2009_ p:integer l:"Est. 2009" t:dataTypeName=number

entity e:dqxz-2g7x l:"Adoption & Child Custody Advocacy - Performance Measures Adoptive Investigations - 2009" t:attribution="Cook County Department of Adoption & Child Custody Advocacy" t:url=https://datacatalog.cookcountyil.gov/api/views/dqxz-2g7x

property e:dqxz-2g7x t:meta.view v:id=dqxz-2g7x v:category=Courts v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/adoption___child_custody_advocacy/245 v:averageRating=0 v:name="Adoption & Child Custody Advocacy - Performance Measures Adoptive Investigations - 2009" v:attribution="Cook County Department of Adoption & Child Custody Advocacy"

property e:dqxz-2g7x t:meta.view.license v:name="Public Domain"

property e:dqxz-2g7x t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:dqxz-2g7x t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```

## Top Records

```ls
| statistics_      | dec_ | jan_ | feb_ | mar_ | apr_ | may_ | jun_ | jul_ | aug_ | sep_ | oct_ | nov_ | est_2009_ | 
| ================ | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ========= | 
| Output Demands   |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 10   | 18   | 10   | 26   | 19   | 23   | 20   | 34   | 28   | 30   | 13   | 13   | 244       | 
| Inputs           |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 80   | 72   | 80   | 208  | 152  | 184  | 160  | 272  | 224  | 240  | 104  | 104  | 1880      | 
| Output Workloads |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 2    | 2    | 4    | 1    | 6    | 6    | 3    | 7    | 2    | 2    | 3    | 6    | 44        | 
| Efficiencies     |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 8    | 4    | 8    | 8    | 8    | 8    | 8    | 8    | 8    | 8    | 8    | 8    | 92        | 
| Effectiveness    |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 8    | 4    | 8    | 8    | 8    | 8    | 8    | 8    | 8    | 8    | 8    | 8    | 92        | 
```