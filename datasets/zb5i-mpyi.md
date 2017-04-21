# IDOR 2009 Illinois Individual Income Tax - AGI County Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-2009-illinois-individual-income-tax-agi-county-report-1d081) |
| Metadata | [Link](https://data.illinois.gov/api/views/zb5i-mpyi) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/zb5i-mpyi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/zb5i-mpyi/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | zb5i-mpyi |
| Name | IDOR 2009 Illinois Individual Income Tax - AGI County Report |
| Attribution | Illinois Department of Revenue |
| Category | Economics |
| Tags | revenue, income, tax |
| Created | 2011-06-15T19:27:09Z |
| Publication Date | 2011-06-15T19:27:09Z |

## Description

This report is created twice a year, usually in January as a PRELIMINARY reporting and then in August for a FINAL reporting.

ILLINOIS DEPARTMENT OF REVENUE
ADJUSTED GROSS INCOME COUNTY REPORT
ILLINOIS INDIVIDUAL INCOME TAX
COUNTY REPORT  -  Tax Year: 2009 - PRELIMINARY
"Source: Preliminary 1040 IIT Return File Dated Jan, 2011"

*****CONFIDENTIALITY REPORT RESTRICTION: No details published when 5 or less returns.

Report ID: TDWR-IITEOY-009
Data Source: 2009
Report Date: 05/27/2011 11:31:49 AM

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | county                 | COUNTY                 | text      | text        |
| Yes      | numeric metric | returns                | RETURNS                | number    | number      |
| Yes      | numeric metric | total_agi              | TOTAL AGI              | money     | money       |
| Yes      | numeric metric | basic_exemptions       | BASIC EXEMPTIONS       | number    | number      |
| Yes      | numeric metric | 65_exemptions          | 65+ EXEMPTIONS         | number    | number      |
| Yes      | numeric metric | blind_exemptions       | BLIND EXEMPTIONS       | number    | number      |
| Yes      | numeric metric | reported_liability     | REPORTED LIABILITY     | money     | money       |
| Yes      | numeric metric | enterprise_zone_credit | ENTERPRISE ZONE CREDIT | money     | money       |
| Yes      | numeric metric | overpayments           | OVERPAYMENTS           | money     | money       |
| Yes      | numeric metric | balance_due            | BALANCE DUE            | money     | money       |
| Yes      | numeric metric | retirement_returns     | RETIREMENT RETURNS     | number    | number      |
| Yes      | numeric metric | retirement_amounts     | RETIREMENT AMOUNTS     | money     | money       |
| Yes      | numeric metric | property_tax_returns   | PROPERTY TAX RETURNS   | number    | number      |
| Yes      | numeric metric | property_tax_credits   | PROPERTY TAX CREDITS   | money     | money       |
| Yes      | numeric metric | additions              | ADDITIONS              | money     | money       |
| Yes      | numeric metric | subtractions           | SUBTRACTIONS           | money     | money       |
| Yes      | numeric metric | education_returns      | EDUCATION RETURNS      | number    | number      |
| Yes      | numeric metric | education_credits      | EDUCATION CREDITS      | money     | money       |
| Yes      | numeric metric | earn_income_returns    | EARN INCOME RETURNS    | number    | number      |
| Yes      | numeric metric | earn_income_credits    | EARN INCOME CREDITS    | money     | money       |
| Yes      | numeric metric | single                 | SINGLE                 | number    | number      |
| Yes      | numeric metric | married                | MARRIED                | number    | number      |
| Yes      | numeric metric | married_sep            | MARRIED SEP            | number    | number      |
| Yes      | numeric metric | widowed                | WIDOWED                | number    | number      |
| Yes      | numeric metric | dec_spouse             | DEC SPOUSE             | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:zb5i-mpyi d:2009-01-01T00:00:00.000Z t:county=ADAMS m:married_sep=263 m:single=16994 m:overpayments=5358315 m:education_credits=342518 m:total_agi=1404057354 m:dec_spouse=55 m:balance_due=2243980 m:property_tax_returns=13733 m:blind_exemptions=127 m:additions=1424870764 m:basic_exemptions=58712 m:married=13253 m:widowed=66 m:education_returns=846 m:subtractions=185620164 m:enterprise_zone_credit=11072 m:property_tax_credits=1449969 m:reported_liability=33754840 m:65_exemptions=8300 m:earn_income_returns=5296 m:returns=30631 m:retirement_returns=8420 m:retirement_amounts=168289001 m:earn_income_credits=547137

series e:zb5i-mpyi d:2009-01-01T00:00:00.000Z t:county=ALEXANDER m:married_sep=28 m:single=1496 m:overpayments=334883 m:education_credits=4442 m:total_agi=85486665 m:dec_spouse=6 m:balance_due=202050 m:property_tax_returns=727 m:blind_exemptions=6 m:additions=85822254 m:basic_exemptions=5328 m:married=957 m:widowed=6 m:education_returns=27 m:subtractions=15687093 m:enterprise_zone_credit=0 m:property_tax_credits=31361 m:reported_liability=1823961 m:65_exemptions=649 m:earn_income_returns=860 m:returns=2493 m:retirement_returns=719 m:retirement_amounts=15190170 m:earn_income_credits=112116

series e:zb5i-mpyi d:2009-01-01T00:00:00.000Z t:county=BOND m:married_sep=45 m:single=3433 m:overpayments=1099135 m:education_credits=13467 m:total_agi=301411388 m:dec_spouse=14 m:balance_due=486692 m:property_tax_returns=3179 m:blind_exemptions=19 m:additions=304244550 m:basic_exemptions=13649 m:married=3282 m:widowed=12 m:education_returns=64 m:subtractions=49412029 m:enterprise_zone_credit=15 m:property_tax_credits=336541 m:reported_liability=6876279 m:65_exemptions=1878 m:earn_income_returns=1211 m:returns=6786 m:retirement_returns=2048 m:retirement_amounts=46725320 m:earn_income_credits=124056
```

## Meta Commands

```ls
metric m:returns p:integer l:RETURNS t:dataTypeName=number

metric m:total_agi p:long l:"TOTAL AGI" t:dataTypeName=money

metric m:basic_exemptions p:integer l:"BASIC EXEMPTIONS" t:dataTypeName=number

metric m:65_exemptions p:integer l:"65+ EXEMPTIONS" t:dataTypeName=number

metric m:blind_exemptions p:integer l:"BLIND EXEMPTIONS" t:dataTypeName=number

metric m:reported_liability p:integer l:"REPORTED LIABILITY" t:dataTypeName=money

metric m:enterprise_zone_credit p:integer l:"ENTERPRISE ZONE CREDIT" t:dataTypeName=money

metric m:overpayments p:integer l:OVERPAYMENTS t:dataTypeName=money

metric m:balance_due p:integer l:"BALANCE DUE" t:dataTypeName=money

metric m:retirement_returns p:integer l:"RETIREMENT RETURNS" t:dataTypeName=number

metric m:retirement_amounts p:long l:"RETIREMENT AMOUNTS" t:dataTypeName=money

metric m:property_tax_returns p:integer l:"PROPERTY TAX RETURNS" t:dataTypeName=number

metric m:property_tax_credits p:integer l:"PROPERTY TAX CREDITS" t:dataTypeName=money

metric m:additions p:long l:ADDITIONS t:dataTypeName=money

metric m:subtractions p:long l:SUBTRACTIONS t:dataTypeName=money

metric m:education_returns p:integer l:"EDUCATION RETURNS" t:dataTypeName=number

metric m:education_credits p:integer l:"EDUCATION CREDITS" t:dataTypeName=money

metric m:earn_income_returns p:integer l:"EARN INCOME RETURNS" t:dataTypeName=number

metric m:earn_income_credits p:integer l:"EARN INCOME CREDITS" t:dataTypeName=money

metric m:single p:integer l:SINGLE t:dataTypeName=number

metric m:married p:integer l:MARRIED t:dataTypeName=number

metric m:married_sep p:integer l:"MARRIED SEP" t:dataTypeName=number

metric m:widowed p:integer l:WIDOWED t:dataTypeName=number

metric m:dec_spouse p:integer l:"DEC SPOUSE" t:dataTypeName=number

entity e:zb5i-mpyi l:"IDOR 2009 Illinois Individual Income Tax - AGI County Report" t:attribution="Illinois Department of Revenue" t:url=https://data.illinois.gov/api/views/zb5i-mpyi

property e:zb5i-mpyi t:meta.view v:id=zb5i-mpyi v:category=Economics v:averageRating=0 v:name="IDOR 2009 Illinois Individual Income Tax - AGI County Report" v:attribution="Illinois Department of Revenue"

property e:zb5i-mpyi t:meta.view.owner v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:displayName=wilcoxd

property e:zb5i-mpyi t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| county    | returns | total_agi  | basic_exemptions | 65_exemptions | blind_exemptions | reported_liability | enterprise_zone_credit | overpayments | balance_due | retirement_returns | retirement_amounts | property_tax_returns | property_tax_credits | additions  | subtractions | education_returns | education_credits | earn_income_returns | earn_income_credits | single | married | married_sep | widowed | dec_spouse | 
| ========= | ======= | ========== | ================ | ============= | ================ | ================== | ====================== | ============ | =========== | ================== | ================== | ==================== | ==================== | ========== | ============ | ================= | ================= | =================== | =================== | ====== | ======= | =========== | ======= | ========== | 
| ADAMS     | 30631   | 1404057354 | 58712            | 8300          | 127              | 33754840           | 11072                  | 5358315      | 2243980     | 8420               | 168289001          | 13733                | 1449969              | 1424870764 | 185620164    | 846               | 342518            | 5296                | 547137              | 16994  | 13253   | 263         | 66      | 55         | 
| ALEXANDER | 2493    | 85486665   | 5328             | 649           | 6                | 1823961            | 0                      | 334883       | 202050      | 719                | 15190170           | 727                  | 31361                | 85822254   | 15687093     | 27                | 4442              | 860                 | 112116              | 1496   | 957     | 28          | 6       | 6          | 
| BOND      | 6786    | 301411388  | 13649            | 1878          | 19               | 6876279            | 15                     | 1099135      | 486692      | 2048               | 46725320           | 3179                 | 336541               | 304244550  | 49412029     | 64                | 13467             | 1211                | 124056              | 3433   | 3282    | 45          | 12      | 14         | 
| BOONE     | 22684   | 1213527665 | 52200            | 4728          | 72               | 29531837           | 0                      | 5619606      | 1245395     | 6065               | 145538444          | 10501                | 2188466              | 1228306613 | 159783620    | 1341              | 365871            | 3396                | 376038              | 11554  | 10852   | 193         | 43      | 42         | 
| BROWN     | 2286    | 99033698   | 4395             | 624           | 12               | 2428032            | 0                      | 362228       | 248056      | 613                | 12006317           | 1041                 | 75777                | 99841338   | 13045866     | 36                | 9422              | 318                 | 33163               | 1215   | 1053    | 9           | 5       | 4          | 
| BUREAU    | 16005   | 715262888  | 31244            | 4663          | 77               | 16940426           | 5890                   | 2835574      | 1607979     | 4919               | 98433199           | 7276                 | 871580               | 722543543  | 105172275    | 332               | 96460             | 2517                | 261251              | 8526   | 7241    | 166         | 40      | 32         | 
| CALHOUN   | 2097    | 96448258   | 4208             | 660           | 13               | 2224878            | 0                      | 298769       | 191447      | 695                | 15690752           | 982                  | 80469                | 97229689   | 16534139     | 56                | 16338             | 269                 | 29641               | 961    | 1104    | 20          | 8       | 4          | 
| CARROLL   | 7569    | 318848334  | 14313            | 2724          | 47               | 7148717            | 6410                   | 1294655      | 926283      | 2686               | 59754839           | 3390                 | 369257               | 323674588  | 63643846     | 57                | 12467             | 1198                | 119269              | 3853   | 3561    | 93          | 52      | 10         | 
| CASS      | 6128    | 257349617  | 12759            | 1480          | 15               | 6061846            | 0                      | 1068041      | 563118      | 1608               | 31543064           | 2459                 | 210296               | 262043707  | 35679815     | 82                | 21015             | 1203                | 136236              | 3464   | 2595    | 37          | 11      | 21         | 
| CHAMPAIGN | 78146   | 4269275082 | 146430           | 15889         | 343              | 103415225          | 123762                 | 16097075     | 5872081     | 18640              | 572393024          | 30352                | 5373613              | 4363025015 | 628829411    | 2187              | 779877            | 11682               | 1266205             | 46898  | 29770   | 1121        | 142     | 215        | 
```