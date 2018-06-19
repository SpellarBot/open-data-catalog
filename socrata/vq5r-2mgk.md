# IDOR 2009 Illinois Individual Income Tax - Returns by Net Income, Nonresident

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-2009-illinois-individual-income-tax-returns-by-net-income-nonresident-47dd8) |
| Metadata | [Link](https://data.illinois.gov/api/views/vq5r-2mgk) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/vq5r-2mgk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/vq5r-2mgk/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | vq5r-2mgk |
| Name | IDOR 2009 Illinois Individual Income Tax - Returns by Net Income, Nonresident |
| Attribution | Illinois Department of Revenue |
| Category | Economics |
| Tags | revenue, income, tax |
| Created | 2011-06-15T19:34:51Z |
| Publication Date | 2011-06-15T19:34:51Z |

## Description

This report is created twice a year, usually in January as a PRELIMINARY reporting and then in August for a FINAL reporting.

ILLINOIS DEPARTMENT OF REVENUE
NET INCOME REPORT
INDIVIDUAL INCOME TAX RETURNS FILED BY NET INCOME:  NONRESIDENT
ANNUAL REPORT  -  TAX YEAR: 2009 - PRELIMINARY
"Source: Preliminary 1040 IIT Return File Dated Jan, 2011?

**CONFIDENTIALITY REPORT RESTRICTION: No details published when 20 or less returns.

Report ID: TDWR-IITEOY-002D
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
| Yes      | numeric metric | gross_tax        | Gross Tax        | money     | money       |
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
series e:vq5r-2mgk d:2009-01-01T00:00:00.000Z t:net_income_range="Equal Zero" m:sch_cr=0 m:net_tax=5262236 m:net_income=0 m:eic=49 m:agi=19963097161 m:credits=7230 m:eec=500 m:returns=42503 m:gross_tax=5269466 m:ptc=6681 m:1299_c=0

series e:vq5r-2mgk d:2009-01-01T00:00:00.000Z t:net_income_range=$1-$1,000 m:sch_cr=0 m:net_tax=212041 m:net_income=7282641 m:eic=8042 m:agi=7057522839 m:credits=8348 m:eec=0 m:returns=16476 m:gross_tax=220389 m:ptc=192 m:1299_c=114

series e:vq5r-2mgk d:2009-01-01T00:00:00.000Z t:net_income_range=$1,001-$3,000 m:sch_cr=0 m:net_tax=947445 m:net_income=40622937 m:eic=38180 m:agi=3884139200 m:credits=39895 m:eec=0 m:returns=20920 m:gross_tax=987340 m:ptc=1246 m:1299_c=469
```

## Meta Commands

```ls
metric m:returns p:integer l:Returns t:dataTypeName=number

metric m:agi p:long l:AGI t:dataTypeName=money

metric m:net_income p:integer l:"Net Income" t:dataTypeName=money

metric m:gross_tax p:integer l:"Gross Tax" t:dataTypeName=money

metric m:credits p:integer l:Credits t:dataTypeName=money

metric m:sch_cr p:integer l:"Sch Cr" t:dataTypeName=money

metric m:ptc p:integer l:PTC t:dataTypeName=money

metric m:eec p:integer l:EEC t:dataTypeName=money

metric m:eic p:integer l:EIC t:dataTypeName=money

metric m:1299_c p:integer l:1299-C t:dataTypeName=money

metric m:net_tax p:integer l:"Net Tax" t:dataTypeName=money

entity e:vq5r-2mgk l:"IDOR 2009 Illinois Individual Income Tax - Returns by Net Income, Nonresident" t:attribution="Illinois Department of Revenue" t:url=https://data.illinois.gov/api/views/vq5r-2mgk

property e:vq5r-2mgk t:meta.view v:id=vq5r-2mgk v:category=Economics v:averageRating=0 v:name="IDOR 2009 Illinois Individual Income Tax - Returns by Net Income, Nonresident" v:attribution="Illinois Department of Revenue"

property e:vq5r-2mgk t:meta.view.owner v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:displayName=wilcoxd

property e:vq5r-2mgk t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| net_income_range | returns | agi         | net_income | gross_tax | credits | sch_cr | ptc  | eec | eic   | 1299_c | net_tax | 
| ================ | ======= | =========== | ========== | ========= | ======= | ====== | ==== | === | ===== | ====== | ======= | 
| Less Than Zero   |         |             |            |           |         |        |      |     |       |        |         | 
| Equal Zero       | 42503   | 19963097161 | 0          | 5269466   | 7230    | 0      | 6681 | 500 | 49    | 0      | 5262236 | 
| $1-$1,000        | 16476   | 7057522839  | 7282641    | 220389    | 8348    | 0      | 192  | 0   | 8042  | 114    | 212041  | 
| $1,001-$3,000    | 20920   | 3884139200  | 40622937   | 987340    | 39895   | 0      | 1246 | 0   | 38180 | 469    | 947445  | 
| $3,001-$5,000    | 14644   | 2362317384  | 57727876   | 1423126   | 56501   | 0      | 1581 | 118 | 53909 | 893    | 1366625 | 
| $5,001-$7,000    | 11241   | 1814049013  | 67092228   | 1698848   | 68940   | 0      | 1174 | 63  | 67526 | 177    | 1629908 | 
| $7,001-$9,000    | 9070    | 2036227498  | 72320257   | 1843299   | 81281   | 0      | 1829 | 256 | 77619 | 1577   | 1762018 | 
| $9,001-$11,000   | 7564    | 1522716184  | 75306530   | 1941790   | 77988   | 0      | 1605 | 0   | 75165 | 1218   | 1863802 | 
| $11,001-$13,000  | 6146    | 1327207223  | 73629915   | 1915870   | 82511   | 0      | 1409 | 0   | 80066 | 1036   | 1833359 | 
| $13,001-$15,000  | 5535    | 1250783648  | 77503972   | 2033115   | 84886   | 0      | 1645 | 0   | 82161 | 1080   | 1948229 | 
```