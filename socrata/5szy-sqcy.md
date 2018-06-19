# IDOR 2009 Illinois Individual Income Tax - Returns by Net Income, Part Year Resident

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-2009-illinois-individual-income-tax-returns-by-net-income-part-year-resident-e40f4) |
| Metadata | [Link](https://data.illinois.gov/api/views/5szy-sqcy) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/5szy-sqcy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/5szy-sqcy/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 5szy-sqcy |
| Name | IDOR 2009 Illinois Individual Income Tax - Returns by Net Income, Part Year Resident |
| Attribution | Illinois Department of Revenue |
| Category | Economics |
| Tags | revenue, income, tax |
| Created | 2011-06-15T21:02:03Z |
| Publication Date | 2011-06-15T21:02:03Z |

## Description

This report is created twice a year, usually in January as a PRELIMINARY reporting and then in August for a FINAL reporting.

ILLINOIS DEPARTMENT OF REVENUE
NET INCOME REPORT
INDIVIDUAL INCOME TAX RETURNS FILED BY NET INCOME:  Part Year Resident
ANNUAL REPORT  -  TAX YEAR: 2009 - PRELIMINARY
"Source: Preliminary 1040 IIT Return File Dated Jan, 2011

**CONFIDENTIALITY REPORT RESTRICTION: No details published when 20 or less returns.

Report ID: TDWR-IITEOY-002C
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
series e:5szy-sqcy d:2009-01-01T00:00:00.000Z t:net_income_range="Equal Zero" m:sch_cr=3917 m:tax=381515 m:net_tax=362011 m:net_income=0 m:eic=54 m:agi=291052748 m:credits=19504 m:eec=1729 m:returns=7930 m:ptc=13804 m:1299_c=0

series e:5szy-sqcy d:2009-01-01T00:00:00.000Z t:net_income_range=$1-$1,000 m:sch_cr=1373 m:tax=68575 m:net_tax=56529 m:net_income=2455794 m:eic=7108 m:agi=125313325 m:credits=12046 m:eec=557 m:returns=5227 m:ptc=2994 m:1299_c=14

series e:5szy-sqcy d:2009-01-01T00:00:00.000Z t:net_income_range=$1,001-$3,000 m:sch_cr=3381 m:tax=400237 m:net_tax=342188 m:net_income=19162768 m:eic=45486 m:agi=187163088 m:credits=58049 m:eec=699 m:returns=9585 m:ptc=8483 m:1299_c=0
```

## Meta Commands

```ls
metric m:returns p:integer l:Returns t:dataTypeName=number

metric m:agi p:integer l:AGI t:dataTypeName=money

metric m:net_income p:integer l:"Net Income" t:dataTypeName=money

metric m:tax p:integer l:Tax t:dataTypeName=money

metric m:credits p:integer l:Credits t:dataTypeName=money

metric m:sch_cr p:integer l:"Sch Cr" t:dataTypeName=money

metric m:ptc p:integer l:PTC t:dataTypeName=money

metric m:eec p:integer l:EEC t:dataTypeName=money

metric m:eic p:integer l:EIC t:dataTypeName=money

metric m:1299_c p:integer l:1299-C t:dataTypeName=money

metric m:net_tax p:integer l:"Net Tax" t:dataTypeName=money

entity e:5szy-sqcy l:"IDOR 2009 Illinois Individual Income Tax - Returns by Net Income, Part Year Resident" t:attribution="Illinois Department of Revenue" t:url=https://data.illinois.gov/api/views/5szy-sqcy

property e:5szy-sqcy t:meta.view v:id=5szy-sqcy v:category=Economics v:averageRating=0 v:name="IDOR 2009 Illinois Individual Income Tax - Returns by Net Income, Part Year Resident" v:attribution="Illinois Department of Revenue"

property e:5szy-sqcy t:meta.view.owner v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:displayName=wilcoxd

property e:5szy-sqcy t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| net_income_range | returns | agi       | net_income | tax     | credits | sch_cr | ptc   | eec  | eic    | 1299_c | net_tax | 
| ================ | ======= | ========= | ========== | ======= | ======= | ====== | ===== | ==== | ====== | ====== | ======= | 
| Less Than Zero   |         |           |            |         |         |        |       |      |        |        |         | 
| Equal Zero       | 7930    | 291052748 | 0          | 381515  | 19504   | 3917   | 13804 | 1729 | 54     | 0      | 362011  | 
| $1-$1,000        | 5227    | 125313325 | 2455794    | 68575   | 12046   | 1373   | 2994  | 557  | 7108   | 14     | 56529   | 
| $1,001-$3,000    | 9585    | 187163088 | 19162768   | 400237  | 58049   | 3381   | 8483  | 699  | 45486  | 0      | 342188  | 
| $3,001-$5,000    | 8626    | 181193762 | 34420398   | 761365  | 106107  | 4999   | 15924 | 1266 | 83918  | 0      | 655258  | 
| $5,001-$7,000    | 7471    | 182952838 | 44613330   | 1038574 | 136719  | 7674   | 24789 | 2306 | 101950 | 0      | 901855  | 
| $7,001-$9,000    | 6519    | 177535404 | 51998706   | 1256380 | 146008  | 8010   | 31719 | 2780 | 103499 | 0      | 1110372 | 
| $9,001-$11,000   | 5555    | 163337659 | 55423151   | 1376243 | 154674  | 11804  | 35845 | 5557 | 101468 | 0      | 1221569 | 
| $11,001-$13,000  | 4894    | 161033700 | 58621838   | 1492502 | 133067  | 10077  | 34942 | 5843 | 82205  | 0      | 1359435 | 
| $13,001-$15,000  | 4488    | 162878891 | 62782796   | 1624250 | 128988  | 14941  | 32541 | 8022 | 73484  | 0      | 1495262 | 
```