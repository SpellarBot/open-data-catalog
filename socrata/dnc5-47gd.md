# Adoption & Child Custody Advocacy - Performance Measures Fingerprints Clearance - 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/adoption-child-custody-advocacy-performance-measures-fingerprints-clearance-2010-5b485) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/dnc5-47gd) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/dnc5-47gd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/dnc5-47gd/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | dnc5-47gd |
| Name | Adoption & Child Custody Advocacy - Performance Measures Fingerprints Clearance - 2010 |
| Attribution | Cook County Department of Adoption & Child Custody Advocacy |
| Category | Courts |
| Created | 2011-10-12T21:06:00Z |
| Publication Date | 2014-10-09T23:05:33Z |

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
| Yes      | numeric metric | est_2010_   | Est. 2010  | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:dnc5-47gd d:2010-01-01T00:00:00.000Z m:aug_=29 m:feb_=13 m:nov_=24 m:jan_=13 m:mar_=23 m:apr_=20 m:est_2010_=255 m:may_=16 m:dec_=25 m:oct_=27 m:jun_=16 m:jul_=19 m:sep_=30

series e:dnc5-47gd d:2010-01-01T00:00:00.000Z t:statistics_="in hours" m:aug_=87 m:feb_=39 m:nov_=72 m:jan_=39 m:mar_=69 m:apr_=60 m:est_2010_=765 m:may_=48 m:dec_=75 m:oct_=81 m:jun_=48 m:jul_=57 m:sep_=90

series e:dnc5-47gd d:2010-01-01T00:00:00.000Z m:aug_=29 m:feb_=13 m:nov_=24 m:jan_=13 m:mar_=23 m:apr_=20 m:est_2010_=255 m:may_=16 m:dec_=25 m:oct_=27 m:jun_=16 m:jul_=19 m:sep_=30
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

metric m:est_2010_ p:integer l:"Est. 2010" t:dataTypeName=number

entity e:dnc5-47gd l:"Adoption & Child Custody Advocacy - Performance Measures Fingerprints Clearance - 2010" t:attribution="Cook County Department of Adoption & Child Custody Advocacy" t:url=https://datacatalog.cookcountyil.gov/api/views/dnc5-47gd

property e:dnc5-47gd t:meta.view v:id=dnc5-47gd v:category=Courts v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/adoption___child_custody_advocacy/245 v:averageRating=0 v:name="Adoption & Child Custody Advocacy - Performance Measures Fingerprints Clearance - 2010" v:attribution="Cook County Department of Adoption & Child Custody Advocacy"

property e:dnc5-47gd t:meta.view.license v:name="Public Domain"

property e:dnc5-47gd t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:dnc5-47gd t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```

## Top Records

```ls
| statistics_      | dec_ | jan_ | feb_ | mar_ | apr_ | may_ | jun_ | jul_ | aug_ | sep_ | oct_ | nov_ | est_2010_ | 
| ================ | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ========= | 
| Output Demands   |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 25   | 13   | 13   | 23   | 20   | 16   | 16   | 19   | 29   | 30   | 27   | 24   | 255       | 
| Inputs           |      |      |      |      |      |      |      |      |      |      |      |      |           | 
| in hours         | 75   | 39   | 39   | 69   | 60   | 48   | 48   | 57   | 87   | 90   | 81   | 72   | 765       | 
| Output Workloads |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 25   | 13   | 13   | 23   | 20   | 16   | 16   | 19   | 29   | 30   | 27   | 24   | 255       | 
| Efficiencies     |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 24        | 
| Effectiveness    |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 24        | 
```