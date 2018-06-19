# IDOR 2009 Illinois Individual Income Tax - AGI Zip Code Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-2009-illinois-individual-income-tax-agi-zip-code-report-b0beb) |
| Metadata | [Link](https://data.illinois.gov/api/views/gsp6-dpce) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/gsp6-dpce/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/gsp6-dpce/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | gsp6-dpce |
| Name | IDOR 2009 Illinois Individual Income Tax - AGI Zip Code Report |
| Attribution | Illinois Department of Revenue |
| Category | Economics |
| Tags | revenue, income, tax |
| Created | 2011-06-16T19:03:59Z |
| Publication Date | 2011-06-16T19:03:59Z |

## Description

This report is created twice a year, usually in January as a PRELIMINARY reporting and then in August for a FINAL reporting.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | zip_code              | ZIP CODE              | text      | number      |
| Yes      | series tag     | county                | COUNTY                | text      | text        |
| Yes      | numeric metric | returns               | RETURNS               | number    | number      |
| Yes      | numeric metric | adjusted_gross_income | ADJUSTED GROSS INCOME | money     | money       |
| Yes      | numeric metric | basic_exemptions      | BASIC EXEMPTIONS      | money     | money       |
| Yes      | numeric metric | 65_exemptions         | 65+ EXEMPTIONS        | money     | money       |
| Yes      | numeric metric | blind_exemptions      | BLIND EXEMPTIONS      | money     | money       |
| Yes      | numeric metric | reported_liability    | REPORTED LIABILITY    | money     | money       |
| Yes      | numeric metric | prop_tax_returns      | PROP TAX RETURNS      | number    | number      |
| Yes      | numeric metric | prop_tax_credits      | PROP TAX CREDITS      | money     | money       |
| Yes      | numeric metric | earn_income_returns   | EARN INCOME RETURNS   | number    | number      |
| Yes      | numeric metric | earn_income_credits   | EARN INCOME CREDITS   | money     | money       |
| Yes      | numeric metric | education_returns     | EDUCATION RETURNS     | number    | number      |
| Yes      | numeric metric | education_credits     | EDUCATION CREDITS     | money     | money       |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:gsp6-dpce d:2009-01-01T00:00:00.000Z t:zip_code=60002 t:county=LAKE m:adjusted_gross_income=695497986 m:prop_tax_returns=5594 m:basic_exemptions=22599 m:education_returns=574 m:education_credits=131251 m:reported_liability=16842959 m:65_exemptions=2247 m:earn_income_returns=1101 m:blind_exemptions=33 m:returns=10890 m:prop_tax_credits=1726065 m:earn_income_credits=112223

series e:gsp6-dpce d:2009-01-01T00:00:00.000Z t:zip_code=60004 t:county=COOK m:adjusted_gross_income=1937162533 m:prop_tax_returns=12778 m:basic_exemptions=49407 m:education_returns=1213 m:education_credits=350438 m:reported_liability=48864204 m:65_exemptions=7198 m:earn_income_returns=1480 m:blind_exemptions=154 m:returns=25070 m:prop_tax_credits=3992508 m:earn_income_credits=128809

series e:gsp6-dpce d:2009-01-01T00:00:00.000Z t:zip_code=60005 t:county=COOK m:adjusted_gross_income=1030797125 m:prop_tax_returns=6784 m:basic_exemptions=27736 m:education_returns=732 m:education_credits=235780 m:reported_liability=26241849 m:65_exemptions=3971 m:earn_income_returns=1224 m:blind_exemptions=81 m:returns=14325 m:prop_tax_credits=1866317 m:earn_income_credits=100885
```

## Meta Commands

```ls
metric m:returns p:integer l:RETURNS t:dataTypeName=number

metric m:adjusted_gross_income p:long l:"ADJUSTED GROSS INCOME" t:dataTypeName=money

metric m:basic_exemptions p:integer l:"BASIC EXEMPTIONS" t:dataTypeName=money

metric m:65_exemptions p:integer l:"65+ EXEMPTIONS" t:dataTypeName=money

metric m:blind_exemptions p:integer l:"BLIND EXEMPTIONS" t:dataTypeName=money

metric m:reported_liability p:long l:"REPORTED LIABILITY" t:dataTypeName=money

metric m:prop_tax_returns p:integer l:"PROP TAX RETURNS" t:dataTypeName=number

metric m:prop_tax_credits p:integer l:"PROP TAX CREDITS" t:dataTypeName=money

metric m:earn_income_returns p:integer l:"EARN INCOME RETURNS" t:dataTypeName=number

metric m:earn_income_credits p:integer l:"EARN INCOME CREDITS" t:dataTypeName=money

metric m:education_returns p:integer l:"EDUCATION RETURNS" t:dataTypeName=number

metric m:education_credits p:integer l:"EDUCATION CREDITS" t:dataTypeName=money

entity e:gsp6-dpce l:"IDOR 2009 Illinois Individual Income Tax - AGI Zip Code Report" t:attribution="Illinois Department of Revenue" t:url=https://data.illinois.gov/api/views/gsp6-dpce

property e:gsp6-dpce t:meta.view v:id=gsp6-dpce v:category=Economics v:averageRating=0 v:name="IDOR 2009 Illinois Individual Income Tax - AGI Zip Code Report" v:attribution="Illinois Department of Revenue"

property e:gsp6-dpce t:meta.view.owner v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:displayName=wilcoxd

property e:gsp6-dpce t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| zip_code | county  | returns | adjusted_gross_income | basic_exemptions | 65_exemptions | blind_exemptions | reported_liability | prop_tax_returns | prop_tax_credits | earn_income_returns | earn_income_credits | education_returns | education_credits | 
| ======== | ======= | ======= | ===================== | ================ | ============= | ================ | ================== | ================ | ================ | =================== | =================== | ================= | ================= | 
| 60001    | MCHENRY |         |                       |                  |               |                  |                    |                  |                  |                     |                     |                   |                   | 
| 60002    | LAKE    | 10890   | 695497986             | 22599            | 2247          | 33               | 16842959           | 5594             | 1726065          | 1101                | 112223              | 574               | 131251            | 
| 60003    | LAKE    |         |                       |                  |               |                  |                    |                  |                  |                     |                     |                   |                   | 
| 60004    | COOK    | 25070   | 1937162533            | 49407            | 7198          | 154              | 48864204           | 12778            | 3992508          | 1480                | 128809              | 1213              | 350438            | 
| 60005    | COOK    | 14325   | 1030797125            | 27736            | 3971          | 81               | 26241849           | 6784             | 1866317          | 1224                | 100885              | 732               | 235780            | 
| 60006    | COOK    | 101     | 5439120               | 164              | 35            | 1                | 131322             | 42               | 11460            | 11                  | 784                 |                   |                   | 
| 60007    | COOK    | 17401   | 1034729932            | 33018            | 4046          | 46               | 26052428           | 8262             | 1759030          | 1454                | 121607              | 655               | 148163            | 
| 60007    | DUPAGE  | 50      | 2989829               | 114              | 18            | 0                | 66220              | 30               | 6844             | 6                   | 698                 |                   |                   | 
| 60008    | COOK    | 10692   | 569397449             | 22550            | 2234          | 36               | 13823461           | 4775             | 1024508          | 1181                | 123444              | 478               | 99231             | 
| 60008    | DUPAGE  |         |                       |                  |               |                  |                    |                  |                  |                     |                     |                   |                   | 
```