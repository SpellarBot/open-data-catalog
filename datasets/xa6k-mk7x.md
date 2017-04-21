# Adoption & Child Custody Advocacy - Performance Measures Fingerprints Clearance - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/adoption-child-custody-advocacy-performance-measures-fingerprints-clearance-2009-50c5e) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/xa6k-mk7x) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/xa6k-mk7x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/xa6k-mk7x/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | xa6k-mk7x |
| Name | Adoption & Child Custody Advocacy - Performance Measures Fingerprints Clearance - 2009 |
| Attribution | Cook County Department of Adoption & Child Custody Advocacy |
| Category | Courts |
| Created | 2011-10-11T20:49:08Z |
| Publication Date | 2014-10-09T23:00:29Z |

## Description

When an individual or family wish to adopt, they must obtain a fingerprint clearance. This Office is the pass through agency for the FBI, Illinois State Police, and the courts

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | statistics_fingerprints | Statistics Fingerprints | text      | text        |
| Yes      | numeric metric | dec_                    | Dec                     | number    | number      |
| Yes      | numeric metric | jan_                    | Jan                     | number    | number      |
| Yes      | numeric metric | feb_                    | Feb                     | number    | number      |
| Yes      | numeric metric | mar_                    | Mar                     | number    | number      |
| Yes      | numeric metric | apr_                    | Apr                     | number    | number      |
| Yes      | numeric metric | may_                    | May                     | number    | number      |
| Yes      | numeric metric | jun_                    | Jun                     | number    | number      |
| Yes      | numeric metric | jul_                    | Jul                     | number    | number      |
| Yes      | numeric metric | aug_                    | Aug                     | number    | number      |
| Yes      | numeric metric | sep_                    | Sep                     | number    | number      |
| Yes      | numeric metric | oct_                    | Oct                     | number    | number      |
| Yes      | numeric metric | nov_                    | Nov                     | number    | number      |
| Yes      | numeric metric | est_2_                  | Est. 2                  | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xa6k-mk7x d:2009-01-01T00:00:00.000Z m:aug_=28 m:nov_=11 m:mar_=21 m:jan_=22 m:may_=20 m:oct_=22 m:dec_=24 m:jul_=30 m:sep_=23 m:feb_=20 m:apr_=26 m:jun_=23 m:est_2_=270

series e:xa6k-mk7x d:2009-01-01T00:00:00.000Z m:aug_=84 m:nov_=33 m:mar_=63 m:jan_=66 m:may_=60 m:oct_=66 m:dec_=72 m:jul_=90 m:sep_=69 m:feb_=60 m:apr_=78 m:jun_=69 m:est_2_=810

series e:xa6k-mk7x d:2009-01-01T00:00:00.000Z m:aug_=28 m:nov_=11 m:mar_=21 m:jan_=22 m:may_=20 m:oct_=22 m:dec_=24 m:jul_=30 m:sep_=23 m:feb_=20 m:apr_=26 m:jun_=23 m:est_2_=270
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

metric m:est_2_ p:integer l:"Est. 2" t:dataTypeName=number

entity e:xa6k-mk7x l:"Adoption & Child Custody Advocacy - Performance Measures Fingerprints Clearance - 2009" t:attribution="Cook County Department of Adoption & Child Custody Advocacy" t:url=https://datacatalog.cookcountyil.gov/api/views/xa6k-mk7x

property e:xa6k-mk7x t:meta.view v:id=xa6k-mk7x v:category=Courts v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/adoption___child_custody_advocacy/245 v:averageRating=0 v:name="Adoption & Child Custody Advocacy - Performance Measures Fingerprints Clearance - 2009" v:attribution="Cook County Department of Adoption & Child Custody Advocacy"

property e:xa6k-mk7x t:meta.view.license v:name="Public Domain"

property e:xa6k-mk7x t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:xa6k-mk7x t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```

## Top Records

```ls
| statistics_fingerprints | dec_ | jan_ | feb_ | mar_ | apr_ | may_ | jun_ | jul_ | aug_ | sep_ | oct_ | nov_ | est_2_ | 
| ======================= | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ====== | 
| Output Demands          |      |      |      |      |      |      |      |      |      |      |      |      |        | 
|                         | 24   | 22   | 20   | 21   | 26   | 20   | 23   | 30   | 28   | 23   | 22   | 11   | 270    | 
| Inputs                  |      |      |      |      |      |      |      |      |      |      |      |      |        | 
|                         | 72   | 66   | 60   | 63   | 78   | 60   | 69   | 90   | 84   | 69   | 66   | 33   | 810    | 
| Output Workloads        |      |      |      |      |      |      |      |      |      |      |      |      |        | 
|                         | 24   | 22   | 20   | 21   | 26   | 20   | 23   | 30   | 28   | 23   | 22   | 11   | 270    | 
| Efficiencies            |      |      |      |      |      |      |      |      |      |      |      |      |        | 
|                         | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 24     | 
| Effectiveness           |      |      |      |      |      |      |      |      |      |      |      |      |        | 
|                         | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 2    | 24     | 
```