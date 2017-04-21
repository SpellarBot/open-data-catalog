# IDOR 2009 Illinois Individual Income Tax - Returns by Net Income, Resident

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-2009-illinois-individual-income-tax-returns-by-net-income-resident-fcd06) |
| Metadata | [Link](https://data.illinois.gov/api/views/eg43-k3nr) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/eg43-k3nr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/eg43-k3nr/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | eg43-k3nr |
| Name | IDOR 2009 Illinois Individual Income Tax - Returns by Net Income, Resident |
| Attribution | Illinois Department of Revenue |
| Category | Economics |
| Tags | revenue, income, tax |
| Created | 2011-06-15T21:07:08Z |
| Publication Date | 2011-06-15T21:07:08Z |

## Description

This report is created twice a year, usually in January as a PRELIMINARY reporting and then in August for a FINAL reporting.

ILLINOIS DEPARTMENT OF REVENUE
NET INCOME REPORT
INDIVIDUAL INCOME TAX RETURNS FILED BY NET INCOME:  Resident
ANNUAL REPORT  -  TAX YEAR: 2009 ? PRELIMINARY
"Source: Preliminary 1040 IIT Return File Dated Jan, 2011

Report ID: TDWR-IITEOY-002B
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
series e:eg43-k3nr d:2009-01-01T00:00:00.000Z t:net_income_range="Equal Zero" m:sch_cr=0 m:tax=6089 m:net_tax=-4837540 m:net_income=0 m:eic=4631002 m:agi=6379564817 m:credits=4843629 m:eec=432 m:returns=624785 m:ptc=212195 m:1299_c=0

series e:eg43-k3nr d:2009-01-01T00:00:00.000Z t:net_income_range=$1-$1,000 m:sch_cr=5681 m:tax=1155702 m:net_tax=-1010455 m:net_income=38669627 m:eic=1712040 m:agi=1135776703 m:credits=2166157 m:eec=7122 m:returns=76941 m:ptc=441288 m:1299_c=26

series e:eg43-k3nr d:2009-01-01T00:00:00.000Z t:net_income_range=$1,001-$3,000 m:sch_cr=66837 m:tax=12844715 m:net_tax=4700951 m:net_income=428208415 m:eic=5394307 m:agi=2428856171 m:credits=8143765 m:eec=63394 m:returns=202485 m:ptc=2618862 m:1299_c=365
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

entity e:eg43-k3nr l:"IDOR 2009 Illinois Individual Income Tax - Returns by Net Income, Resident" t:attribution="Illinois Department of Revenue" t:url=https://data.illinois.gov/api/views/eg43-k3nr

property e:eg43-k3nr t:meta.view v:id=eg43-k3nr v:category=Economics v:averageRating=0 v:name="IDOR 2009 Illinois Individual Income Tax - Returns by Net Income, Resident" v:attribution="Illinois Department of Revenue"

property e:eg43-k3nr t:meta.view.owner v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:displayName=wilcoxd

property e:eg43-k3nr t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| net_income_range | returns | agi        | net_income | tax      | credits  | sch_cr | ptc     | eec    | eic      | 1299_c | net_tax  | 
| ================ | ======= | ========== | ========== | ======== | ======== | ====== | ======= | ====== | ======== | ====== | ======== | 
| Equal Zero       | 624785  | 6379564817 | 0          | 6089     | 4843629  | 0      | 212195  | 432    | 4631002  | 0      | -4837540 | 
| $1-$1,000        | 76941   | 1135776703 | 38669627   | 1155702  | 2166157  | 5681   | 441288  | 7122   | 1712040  | 26     | -1010455 | 
| $1,001-$3,000    | 202485  | 2428856171 | 428208415  | 12844715 | 8143765  | 66837  | 2618862 | 63394  | 5394307  | 365    | 4700951  | 
| $3,001-$5,000    | 245515  | 2869668284 | 984789208  | 29543036 | 15285994 | 165521 | 5093684 | 211945 | 9814495  | 349    | 14257042 | 
| $5,001-$7,000    | 236194  | 3211925136 | 1411880694 | 42355461 | 19097081 | 250730 | 5229371 | 467046 | 13149297 | 637    | 23258380 | 
| $7,001-$9,000    | 202493  | 3239566420 | 1615054802 | 48450748 | 17737205 | 314272 | 5618868 | 504517 | 11299158 | 390    | 30713543 | 
| $9,001-$11,000   | 181120  | 3302333946 | 1809160451 | 54274327 | 16669658 | 399576 | 5837567 | 577102 | 9853385  | 2028   | 37604669 | 
| $11,001-$13,000  | 168694  | 3426855029 | 2022950817 | 60688532 | 16041407 | 498328 | 5980070 | 642907 | 8918758  | 1344   | 44647125 | 
| $13,001-$15,000  | 160048  | 3565394894 | 2239619384 | 67188410 | 15461423 | 632697 | 6086641 | 734277 | 8006057  | 1751   | 51726987 | 
| $15,001-$17,000  | 151666  | 3691975110 | 2426376241 | 72791111 | 14809625 | 794140 | 6240285 | 839761 | 6933225  | 2214   | 57981486 | 
```