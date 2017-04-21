# Adoption & Child Custody Advocacy - Performance Measures Fingerprints Clearance - 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/adoption-child-custody-advocacy-performance-measures-fingerprints-clearance-2008-b2474) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/ydjt-tzxr) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ydjt-tzxr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ydjt-tzxr/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | ydjt-tzxr |
| Name | Adoption & Child Custody Advocacy - Performance Measures Fingerprints Clearance - 2008 |
| Attribution | Cook County Department of Adoption & Child Custody Advocacy |
| Category | Courts |
| Created | 2011-10-12T16:37:16Z |
| Publication Date | 2014-10-09T23:11:05Z |

## Description

When an individual of family wish to adopt they must obtain fingerprint clearance. This office is the pass through agency from the FBI, Illinois State Police, and the courts.

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
series e:ydjt-tzxr d:2008-01-01T00:00:00.000Z m:aug_=24 m:est_2008_=338 m:feb_=26 m:nov_=22 m:mar_=34 m:jan_=27 m:apr_=42 m:may_=21 m:oct_=35 m:dec_=17 m:jun_=35 m:jul_=38 m:sep_=17

series e:ydjt-tzxr d:2008-01-01T00:00:00.000Z m:aug_=72 m:est_2008_=954 m:feb_=78 m:nov_=66 m:mar_=102 m:jan_=81 m:apr_=126 m:may_=63 m:oct_=105 m:dec_=21 m:jun_=105 m:jul_=114 m:sep_=21

series e:ydjt-tzxr d:2008-01-01T00:00:00.000Z m:aug_=24 m:est_2008_=338 m:feb_=26 m:nov_=22 m:mar_=34 m:jan_=27 m:apr_=42 m:may_=21 m:oct_=35 m:dec_=17 m:jun_=35 m:jul_=38 m:sep_=17
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

entity e:ydjt-tzxr l:"Adoption & Child Custody Advocacy - Performance Measures Fingerprints Clearance - 2008" t:attribution="Cook County Department of Adoption & Child Custody Advocacy" t:url=https://datacatalog.cookcountyil.gov/api/views/ydjt-tzxr

property e:ydjt-tzxr t:meta.view v:id=ydjt-tzxr v:category=Courts v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/adoption___child_custody_advocacy/245 v:averageRating=0 v:name="Adoption & Child Custody Advocacy - Performance Measures Fingerprints Clearance - 2008" v:attribution="Cook County Department of Adoption & Child Custody Advocacy"

property e:ydjt-tzxr t:meta.view.license v:name="Public Domain"

property e:ydjt-tzxr t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:ydjt-tzxr t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```

## Top Records

```ls
| statistics_      | dec_ | jan_ | feb_ | mar_ | apr_ | may_ | jun_ | jul_ | aug_ | sep_ | oct_ | nov_ | est_2008_ | 
| ================ | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ========= | 
| Output Demands   |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 17   | 27   | 26   | 34   | 42   | 21   | 35   | 38   | 24   | 17   | 35   | 22   | 338       | 
| Inputs           |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 21   | 81   | 78   | 102  | 126  | 63   | 105  | 114  | 72   | 21   | 105  | 66   | 954       | 
| Output Workloads |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 17   | 27   | 26   | 34   | 42   | 21   | 35   | 38   | 24   | 17   | 35   | 22   | 338       | 
| Efficiencies     |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 24        | 
| Effectiveness    |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 24        | 
```