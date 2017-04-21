# IDOR 2009 Illinois Individual Income Tax - Retirement Subtraction by Base Income

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-2009-illinois-individual-income-tax-retirement-subtraction-by-base-income-71c9f) |
| Metadata | [Link](https://data.illinois.gov/api/views/mn9v-gvsh) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/mn9v-gvsh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/mn9v-gvsh/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | mn9v-gvsh |
| Name | IDOR 2009 Illinois Individual Income Tax - Retirement Subtraction by Base Income |
| Attribution | Illinois Department of Revenue |
| Category | Economics |
| Tags | revenue, income, tax |
| Created | 2011-06-15T21:24:18Z |
| Publication Date | 2011-06-15T21:24:18Z |

## Description

This report is created twice a year, usually in January as a PRELIMINARY reporting and then in August for a FINAL reporting.

ILLINOIS DEPARTMENT OF REVENUE
ILLINOIS INDIVIDUAL INCOME TAX:  RETIREMENT SUBTRACTION :  TAX YEAR 2009 - PRELIMINARY
"Source: Preliminary 1040 IIT Return File Dated Jan, 2011


Report ID: TDWR-IITEOY-015
Data Source: 2009
Report Date: 05/27/2011 11:31:24 AM

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | base_income_class      | BASE INCOME CLASS      | text      | text        |
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
series e:mn9v-gvsh d:2009-01-01T00:00:00.000Z t:base_income_class="LESS THAN ZERO" m:under_65_amount=903378409 m:all_retirement_returns=71515 m:65_or_over_average=36504 m:under_65_average=43453 m:under_65_returns=20790 m:65_or_over_amount=1851661808 m:all_retirement_average=38524 m:all_retirement_amount=2755040217 m:65_or_over_returns=50725

series e:mn9v-gvsh d:2009-01-01T00:00:00.000Z t:base_income_class=$0-$1,000 m:under_65_amount=1133257593 m:all_retirement_returns=169096 m:65_or_over_average=27132 m:under_65_average=31275 m:under_65_returns=36235 m:65_or_over_amount=3604753269 m:all_retirement_average=28020 m:all_retirement_amount=4738010862 m:65_or_over_returns=132861

series e:mn9v-gvsh d:2009-01-01T00:00:00.000Z t:base_income_class=$1,001-$3,000 m:under_65_amount=530441125 m:all_retirement_returns=88357 m:65_or_over_average=28261 m:under_65_average=34273 m:under_65_returns=15477 m:65_or_over_amount=2059634716 m:all_retirement_average=29314 m:all_retirement_amount=2590075841 m:65_or_over_returns=72880
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

metric m:under_65_amount p:integer l:"UNDER 65 AMOUNT" t:dataTypeName=money

metric m:under_65_average p:integer l:"UNDER 65 AVERAGE" t:dataTypeName=money

entity e:mn9v-gvsh l:"IDOR 2009 Illinois Individual Income Tax - Retirement Subtraction by Base Income" t:attribution="Illinois Department of Revenue" t:url=https://data.illinois.gov/api/views/mn9v-gvsh

property e:mn9v-gvsh t:meta.view v:id=mn9v-gvsh v:category=Economics v:averageRating=0 v:name="IDOR 2009 Illinois Individual Income Tax - Retirement Subtraction by Base Income" v:attribution="Illinois Department of Revenue"

property e:mn9v-gvsh t:meta.view.owner v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:displayName=wilcoxd

property e:mn9v-gvsh t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| base_income_class | all_retirement_returns | all_retirement_amount | all_retirement_average | 65_or_over_returns | 65_or_over_amount | 65_or_over_average | under_65_returns | under_65_amount | under_65_average | 
| ================= | ====================== | ===================== | ====================== | ================== | ================= | ================== | ================ | =============== | ================ | 
| LESS THAN ZERO    | 71515                  | 2755040217            | 38524                  | 50725              | 1851661808        | 36504              | 20790            | 903378409       | 43453            | 
| $0-$1,000         | 169096                 | 4738010862            | 28020                  | 132861             | 3604753269        | 27132              | 36235            | 1133257593      | 31275            | 
| $1,001-$3,000     | 88357                  | 2590075841            | 29314                  | 72880              | 2059634716        | 28261              | 15477            | 530441125       | 34273            | 
| $3,001-$5,000     | 62596                  | 1744519216            | 27869                  | 50403              | 1373569870        | 27252              | 12193            | 370949346       | 30423            | 
| $5,001-$7,000     | 50992                  | 1416194870            | 27773                  | 39406              | 1096471967        | 27825              | 11586            | 319722903       | 27596            | 
| $7,001-$9,000     | 43603                  | 1198415198            | 27485                  | 31931              | 903138647         | 28284              | 11672            | 295276551       | 25298            | 
| $9,001-$11,000    | 38814                  | 1062082551            | 27363                  | 26950              | 785324960         | 29140              | 11864            | 276757591       | 23328            | 
| $11,001-$13,000   | 35229                  | 943592838             | 26785                  | 23055              | 683455767         | 29645              | 12174            | 260137071       | 21368            | 
| $13,001-$15,000   | 32809                  | 856877638             | 26117                  | 19959              | 597234290         | 29923              | 12850            | 259643348       | 20206            | 
| $15,001-$17,000   | 30755                  | 775199416             | 25206                  | 17795              | 526543292         | 29589              | 12960            | 248656124       | 19186            | 
```