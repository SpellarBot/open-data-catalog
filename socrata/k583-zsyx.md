# IDOR 2009 Illinois Individual Income Tax - Retirement Subtraction by Net Income

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-2009-illinois-individual-income-tax-retirement-subtraction-by-net-income-838db) |
| Metadata | [Link](https://data.illinois.gov/api/views/k583-zsyx) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/k583-zsyx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/k583-zsyx/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | k583-zsyx |
| Name | IDOR 2009 Illinois Individual Income Tax - Retirement Subtraction by Net Income |
| Attribution | Illinois Department of Revenue |
| Category | Economics |
| Tags | revenue, income, tax |
| Created | 2011-06-15T21:28:35Z |
| Publication Date | 2011-06-15T21:28:35Z |

## Description

This report is created twice a year, usually in January as a PRELIMINARY reporting and then in August for a FINAL reporting.

ILLINOIS DEPARTMENT OF REVENUE
ILLINOIS INDIVIDUAL INCOME TAX:  RETIREMENT SUBTRACTION :  TAX YEAR 2009 - PRELIMINARY
"Source: Preliminary 1040 IIT Return File Dated Jan, 2011"


**CONFIDENTIALITY REPORT RESTRICTION: No details published when 20 or less returns.

Report ID: TDWR-IITEOY-016
Data Source: 2009
Report Date: 05/27/2011 11:31:19 AM

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | net_income_class       | NET INCOME CLASS       | text      | text        |
| Yes      | numeric metric | all_retirement_returns | ALL RETIREMENT RETURNS | number    | number      |
| Yes      | numeric metric | all_retirement_amount  | ALL RETIREMENT AMOUNT  | money     | money       |
| Yes      | numeric metric | all_retirement_average | ALL RETIREMENT AVERAGE | money     | money       |
| Yes      | numeric metric | 65_or_over_returns     | 65 OR OVER RETURNS     | number    | number      |
| Yes      | numeric metric | 65_or_over_amount      | 65 OR OVER AMOUNT      | money     | money       |
| Yes      | numeric metric | 65_or_over_average     | 65 OR OVER AVERAGE     | money     | money       |
| Yes      | numeric metric | under_65_returns       | UNDER 65 RETURNS       | number    | number      |
| Yes      | numeric metric | under_65_amount        | UNDER 65 AMOUNT        | money     | money       |
| Yes      | numeric metric | under_65_average       | UNDER 65 AVERAGE       | money     | money       |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:k583-zsyx d:2009-01-01T00:00:00.000Z t:net_income_class="EQUAL ZERO" m:under_65_amount=2721894266 m:all_retirement_returns=370007 m:65_or_over_average=30256 m:under_65_average=34799 m:under_65_returns=78217 m:65_or_over_amount=8828262527 m:all_retirement_average=31216 m:all_retirement_amount=11550156793 m:65_or_over_returns=291790

series e:k583-zsyx d:2009-01-01T00:00:00.000Z t:net_income_class=$1-$1,000 m:under_65_amount=250141834 m:all_retirement_returns=34561 m:65_or_over_average=27911 m:under_65_average=29631 m:under_65_returns=8442 m:65_or_over_amount=728995018 m:all_retirement_average=28331 m:all_retirement_amount=979136852 m:65_or_over_returns=26119

series e:k583-zsyx d:2009-01-01T00:00:00.000Z t:net_income_class=$1,001-$3,000 m:under_65_amount=392756110 m:all_retirement_returns=56293 m:65_or_over_average=27317 m:under_65_average=26671 m:under_65_returns=14726 m:65_or_over_amount=1135480735 m:all_retirement_average=27148 m:all_retirement_amount=1528236845 m:65_or_over_returns=41567
```

## Meta Commands

```ls
metric m:all_retirement_returns p:integer l:"ALL RETIREMENT RETURNS" t:dataTypeName=number

metric m:all_retirement_amount p:long l:"ALL RETIREMENT AMOUNT" t:dataTypeName=money

metric m:all_retirement_average p:integer l:"ALL RETIREMENT AVERAGE" t:dataTypeName=money

metric m:65_or_over_returns p:integer l:"65 OR OVER RETURNS" t:dataTypeName=number

metric m:65_or_over_amount p:long l:"65 OR OVER AMOUNT" t:dataTypeName=money

metric m:65_or_over_average p:integer l:"65 OR OVER AVERAGE" t:dataTypeName=money

metric m:under_65_returns p:integer l:"UNDER 65 RETURNS" t:dataTypeName=number

metric m:under_65_amount p:long l:"UNDER 65 AMOUNT" t:dataTypeName=money

metric m:under_65_average p:integer l:"UNDER 65 AVERAGE" t:dataTypeName=money

entity e:k583-zsyx l:"IDOR 2009 Illinois Individual Income Tax - Retirement Subtraction by Net Income" t:attribution="Illinois Department of Revenue" t:url=https://data.illinois.gov/api/views/k583-zsyx

property e:k583-zsyx t:meta.view v:id=k583-zsyx v:category=Economics v:averageRating=0 v:name="IDOR 2009 Illinois Individual Income Tax - Retirement Subtraction by Net Income" v:attribution="Illinois Department of Revenue"

property e:k583-zsyx t:meta.view.owner v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:displayName=wilcoxd

property e:k583-zsyx t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| net_income_class | all_retirement_returns | all_retirement_amount | all_retirement_average | 65_or_over_returns | 65_or_over_amount | 65_or_over_average | under_65_returns | under_65_amount | under_65_average | 
| ================ | ====================== | ===================== | ====================== | ================== | ================= | ================== | ================ | =============== | ================ | 
| LESS THAN ZERO   |                        |                       |                        |                    |                   |                    |                  |                 |                  | 
| EQUAL ZERO       | 370007                 | 11550156793           | 31216                  | 291790             | 8828262527        | 30256              | 78217            | 2721894266      | 34799            | 
| $1-$1,000        | 34561                  | 979136852             | 28331                  | 26119              | 728995018         | 27911              | 8442             | 250141834       | 29631            | 
| $1,001-$3,000    | 56293                  | 1528236845            | 27148                  | 41567              | 1135480735        | 27317              | 14726            | 392756110       | 26671            | 
| $3,001-$5,000    | 47049                  | 1259536960            | 26771                  | 32947              | 921714985         | 27976              | 14102            | 337821975       | 23956            | 
| $5,001-$7,000    | 41688                  | 1099600020            | 26377                  | 27722              | 787024376         | 28390              | 13966            | 312575644       | 22381            | 
| $7,001-$9,000    | 36749                  | 964533630             | 26247                  | 22998              | 668273824         | 29058              | 13751            | 296259806       | 21545            | 
| $9,001-$11,000   | 33746                  | 868201353             | 25728                  | 20001              | 594067020         | 29702              | 13745            | 274134333       | 19944            | 
| $11,001-$13,000  | 32077                  | 787459124             | 24549                  | 17912              | 519753323         | 29017              | 14165            | 267705801       | 18899            | 
| $13,001-$15,000  | 30742                  | 720945547             | 23451                  | 16641              | 466923292         | 28059              | 14101            | 254022255       | 18014            | 
```