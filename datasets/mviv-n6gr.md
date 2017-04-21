# IDOR 2009 Illinois Individual Income Tax - Returns by Net Income, All Resident types

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-2009-illinois-individual-income-tax-returns-by-net-income-all-resident-types-49e55) |
| Metadata | [Link](https://data.illinois.gov/api/views/mviv-n6gr) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/mviv-n6gr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/mviv-n6gr/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | mviv-n6gr |
| Name | IDOR 2009 Illinois Individual Income Tax - Returns by Net Income, All Resident types |
| Attribution | Illinois Department of Revenue |
| Category | Economics |
| Tags | revenue, income, tax |
| Created | 2011-06-15T21:09:35Z |
| Publication Date | 2011-06-15T21:09:35Z |

## Description

This report is created twice a year, usually in January as a PRELIMINARY reporting and then in August for a FINAL reporting.

ILLINOIS DEPARTMENT OF REVENUE
NET INCOME REPORT
INDIVIDUAL INCOME TAX RETURNS FILED BY NET INCOME: ALL RESIDENT TYPES
ANNUAL REPORT  -  TAX YEAR: 2009 - PRELIMINARY
"Source: Preliminary 1040 IIT Return File Dated Jan, 2011

**CONFIDENTIALITY REPORT RESTRICTION: No details published when 20 or less returns.

Report ID: TDWR-IITEOY-002A
Data Source: 2009
Report Date: 05/27/2011 11:32:18 AM

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | net_income_range | Net Income Range | text      | text        |
| Yes      | numeric metric | returns          | Returns          | number    | number      |
| Yes      | numeric metric | agi              | AGI              | money     | money       |
| Yes      | numeric metric | net_income       | Net Income       | money     | money       |
| Yes      | numeric metric | tax              | Tax              | money     | money       |
| Yes      | numeric metric | credits          | Credits          | money     | money       |
| Yes      | numeric metric | sch_cr           | Sch Cr           | money     | money       |
| Yes      | numeric metric | ptc              | PTC              | money     | money       |
| Yes      | numeric metric | eec              | EEC              | money     | money       |
| Yes      | numeric metric | eic              | EIC              | money     | money       |
| Yes      | numeric metric | 1299_c           | 1299-C           | money     | money       |
| Yes      | numeric metric | net_tax          | Net Tax          | money     | money       |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mviv-n6gr d:2009-01-01T00:00:00.000Z t:net_income_range="Equal Zero" m:sch_cr=3917 m:tax=5657070 m:net_tax=786707 m:net_income=0 m:eic=4631105 m:agi=26633714726 m:credits=4870363 m:eec=2661 m:returns=675218 m:ptc=232680 m:1299_c=0

series e:mviv-n6gr d:2009-01-01T00:00:00.000Z t:net_income_range=$1-$1,000 m:sch_cr=7054 m:tax=1444666 m:net_tax=-741885 m:net_income=48408062 m:eic=1727190 m:agi=8318612867 m:credits=2186551 m:eec=7679 m:returns=98644 m:ptc=444474 m:1299_c=154

series e:mviv-n6gr d:2009-01-01T00:00:00.000Z t:net_income_range=$1,001-$3,000 m:sch_cr=70218 m:tax=14232292 m:net_tax=5990584 m:net_income=487994120 m:eic=5477973 m:agi=6500158459 m:credits=8241709 m:eec=64093 m:returns=232990 m:ptc=2628591 m:1299_c=834
```

## Meta Commands

```ls
metric m:returns p:integer l:Returns t:dataTypeName=number

metric m:agi p:long l:AGI t:dataTypeName=money

metric m:net_income p:long l:"Net Income" t:dataTypeName=money

metric m:tax p:integer l:Tax t:dataTypeName=money

metric m:credits p:integer l:Credits t:dataTypeName=money

metric m:sch_cr p:integer l:"Sch Cr" t:dataTypeName=money

metric m:ptc p:integer l:PTC t:dataTypeName=money

metric m:eec p:integer l:EEC t:dataTypeName=money

metric m:eic p:integer l:EIC t:dataTypeName=money

metric m:1299_c p:integer l:1299-C t:dataTypeName=money

metric m:net_tax p:integer l:"Net Tax" t:dataTypeName=money

entity e:mviv-n6gr l:"IDOR 2009 Illinois Individual Income Tax - Returns by Net Income, All Resident types" t:attribution="Illinois Department of Revenue" t:url=https://data.illinois.gov/api/views/mviv-n6gr

property e:mviv-n6gr t:meta.view v:id=mviv-n6gr v:category=Economics v:averageRating=0 v:name="IDOR 2009 Illinois Individual Income Tax - Returns by Net Income, All Resident types" v:attribution="Illinois Department of Revenue"

property e:mviv-n6gr t:meta.view.owner v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:displayName=wilcoxd

property e:mviv-n6gr t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| net_income_range | returns | agi         | net_income | tax      | credits  | sch_cr | ptc     | eec    | eic      | 1299_c | net_tax  | 
| ================ | ======= | =========== | ========== | ======== | ======== | ====== | ======= | ====== | ======== | ====== | ======== | 
| Less Than Zero   |         |             |            |          |          |        |         |        |          |        |          | 
| Equal Zero       | 675218  | 26633714726 | 0          | 5657070  | 4870363  | 3917   | 232680  | 2661   | 4631105  | 0      | 786707   | 
| $1-$1,000        | 98644   | 8318612867  | 48408062   | 1444666  | 2186551  | 7054   | 444474  | 7679   | 1727190  | 154    | -741885  | 
| $1,001-$3,000    | 232990  | 6500158459  | 487994120  | 14232292 | 8241709  | 70218  | 2628591 | 64093  | 5477973  | 834    | 5990584  | 
| $3,001-$5,000    | 268785  | 5413179430  | 1076937482 | 31727527 | 15448602 | 170520 | 5111189 | 213329 | 9952322  | 1242   | 16278925 | 
| $5,001-$7,000    | 254906  | 5208926987  | 1523586252 | 45092883 | 19302740 | 258404 | 5255334 | 469415 | 13318773 | 814    | 25790143 | 
| $7,001-$9,000    | 218082  | 5453329322  | 1739373765 | 51550427 | 17964494 | 322282 | 5652416 | 507553 | 11480276 | 1967   | 33585933 | 
| $9,001-$11,000   | 194239  | 4988387789  | 1939890132 | 57592360 | 16902320 | 411380 | 5875017 | 582659 | 10030018 | 3246   | 40690040 | 
| $11,001-$13,000  | 179734  | 4915095952  | 2155202570 | 64096904 | 16256985 | 508405 | 6016421 | 648750 | 9081029  | 2380   | 47839919 | 
| $13,001-$15,000  | 170071  | 4979057433  | 2379906152 | 70845775 | 15675297 | 647638 | 6120827 | 742299 | 8161702  | 2831   | 55170478 | 
```