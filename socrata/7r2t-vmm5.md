# Adoption & Child Custody Advocacy - Performance Measures Custody Investigations - 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/adoption-child-custody-advocacy-performance-measures-custody-investigations-2010-d92cf) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/7r2t-vmm5) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/7r2t-vmm5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/7r2t-vmm5/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 7r2t-vmm5 |
| Name | Adoption & Child Custody Advocacy - Performance Measures Custody Investigations - 2010 |
| Attribution | Cook County Department of Adoption & Child Custody Advocacy |
| Category | Courts |
| Created | 2011-10-12T19:00:17Z |
| Publication Date | 2014-10-09T23:09:19Z |

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
| Yes      | numeric metric | sep_        | Sep        | number    | text        |
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
series e:7r2t-vmm5 d:2010-01-01T00:00:00.000Z m:aug_=172 m:feb_=132 m:nov_=138 m:jan_=144 m:mar_=138 m:apr_=146 m:est_2010_=1830 m:may_=168 m:dec_=154 m:oct_=144 m:jun_=182 m:jul_=166 m:sep_=146

series e:7r2t-vmm5 d:2010-01-01T00:00:00.000Z m:aug_=31 m:feb_=28 m:nov_=30 m:jan_=31 m:mar_=21 m:apr_=34 m:est_2010_=343 m:may_=28 m:dec_=34 m:oct_=25 m:jun_=25 m:jul_=29 m:sep_=27

series e:7r2t-vmm5 d:2010-01-01T00:00:00.000Z m:aug_=16 m:feb_=16 m:nov_=16 m:jan_=16 m:mar_=8 m:apr_=4 m:est_2010_=160 m:may_=16 m:dec_=4 m:oct_=16 m:jun_=16 m:jul_=16 m:sep_=16
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

metric m:sep_ p:long l:Sep t:dataTypeName=number

metric m:oct_ p:integer l:Oct t:dataTypeName=number

metric m:nov_ p:integer l:Nov t:dataTypeName=number

metric m:est_2010_ p:integer l:"Est. 2010" t:dataTypeName=number

entity e:7r2t-vmm5 l:"Adoption & Child Custody Advocacy - Performance Measures Custody Investigations - 2010" t:attribution="Cook County Department of Adoption & Child Custody Advocacy" t:url=https://datacatalog.cookcountyil.gov/api/views/7r2t-vmm5

property e:7r2t-vmm5 t:meta.view v:id=7r2t-vmm5 v:category=Courts v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/adoption___child_custody_advocacy/245 v:averageRating=0 v:name="Adoption & Child Custody Advocacy - Performance Measures Custody Investigations - 2010" v:attribution="Cook County Department of Adoption & Child Custody Advocacy"

property e:7r2t-vmm5 t:meta.view.license v:name="Public Domain"

property e:7r2t-vmm5 t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:7r2t-vmm5 t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```

## Top Records

```ls
| statistics_      | dec_ | jan_ | feb_ | mar_ | apr_ | may_ | jun_ | jul_ | aug_ | sep_ | oct_ | nov_ | est_2010_ | 
| ================ | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ========= | 
| Output Demands   |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 154  | 144  | 132  | 138  | 146  | 168  | 182  | 166  | 172  | 146  | 144  | 138  | 1830      | 
| Output Workloads |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 34   | 31   | 28   | 21   | 34   | 28   | 25   | 29   | 31   | 27   | 25   | 30   | 343       | 
| Efficiencies     |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 4    | 16   | 16   | 8    | 4    | 16   | 16   | 16   | 16   | 16   | 16   | 16   | 160       | 
| Effectiveness    |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 4    | 16   | 16   | 8    | 4    | 16   | 16   | 16   | 16   | 16   | 16   | 16   | 160       | 
| Outcomes         |      |      |      |      |      |      |      |      |      |      |      |      |           | 
|                  | 29   | 23   | 16   | 25   | 29   | 30   | 43   | 30   | 33   | 29   | 23   | 25   | 335       | 
```