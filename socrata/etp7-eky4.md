# IDOR 2009 Illinois Individual Income Tax - Web Returns, Retirement by AGI

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-2009-illinois-individual-income-tax-web-returns-retirement-by-agi-a11b5) |
| Metadata | [Link](https://data.illinois.gov/api/views/etp7-eky4) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/etp7-eky4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/etp7-eky4/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | etp7-eky4 |
| Name | IDOR 2009 Illinois Individual Income Tax - Web Returns, Retirement by AGI |
| Attribution | Illinois Department of Revenue |
| Category | Economics |
| Tags | revenue, income, tax |
| Created | 2011-06-15T21:35:11Z |
| Publication Date | 2011-06-15T21:35:11Z |

## Description

This report is created twice a year, usually in January as a PRELIMINARY reporting and then in August for a FINAL reporting.

ILLINOIS DEPARTMENT OF REVENUE
Illinois Individual Income Tax Returns with Retirement Subtraction: Tax Year  -  2009 ? PRELIMINARY
"Source: Preliminary 1040 IIT Return File Dated Jan, 2011"

Report ID: TDWR-IITEOY-017
Data Source: 2009
Report Date: 05/27/2011 11:32:41 AM

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | agi_bracket             | AGI Bracket             | text      | text        |
| Yes      | numeric metric | retirement_returns      | Retirement Returns      | number    | number      |
| Yes      | numeric metric | retirement_subtractions | Retirement Subtractions | money     | money       |
| Yes      | numeric metric | agi                     | AGI                     | money     | money       |
| Yes      | numeric metric | basic_exemption         | BASIC Exemption         | money     | money       |
| Yes      | numeric metric | 65_exemption            | 65+ Exemption           | money     | money       |
| Yes      | numeric metric | blind_exemption         | BLIND Exemption         | money     | money       |
| Yes      | numeric metric | net_income              | Net Income              | money     | money       |
| Yes      | numeric metric | total_tax               | Total Tax               | money     | money       |
| Yes      | numeric metric | property_tax_return     | Property Tax Return     | money     | money       |
| Yes      | numeric metric | property_tax_amount     | Property Tax Amount     | money     | money       |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:etp7-eky4 d:2009-01-01T00:00:00.000Z t:agi_bracket="$20,000 OR LESS" m:basic_exemption=406638 m:65_exemption=274194 m:property_tax_return=62273 m:property_tax_amount=5208512 m:blind_exemption=4597 m:net_income=702500161 m:retirement_subtractions=2301466035 m:agi=1911636928 m:total_tax=21075308 m:retirement_returns=289788

series e:etp7-eky4 d:2009-01-01T00:00:00.000Z t:agi_bracket="$20,001 - $25,000" m:basic_exemption=123339 m:65_exemption=67154 m:property_tax_return=28734 m:property_tax_amount=3382452 m:blind_exemption=1125 m:net_income=582227739 m:retirement_subtractions=938707889 m:agi=1717925480 m:total_tax=17466794 m:retirement_returns=76433

series e:etp7-eky4 d:2009-01-01T00:00:00.000Z t:agi_bracket=$25,001-$30,000 m:basic_exemption=124575 m:65_exemption=59570 m:property_tax_return=30616 m:property_tax_amount=3919008 m:blind_exemption=1048 m:net_income=767319246 m:retirement_subtractions=1054385585 m:agi=2024335242 m:total_tax=23019693 m:retirement_returns=73644
```

## Meta Commands

```ls
metric m:retirement_returns p:integer l:"Retirement Returns" t:dataTypeName=number

metric m:retirement_subtractions p:long l:"Retirement Subtractions" t:dataTypeName=money

metric m:agi p:long l:AGI t:dataTypeName=money

metric m:basic_exemption p:integer l:"BASIC Exemption" t:dataTypeName=money

metric m:65_exemption p:integer l:"65+ Exemption" t:dataTypeName=money

metric m:blind_exemption p:integer l:"BLIND Exemption" t:dataTypeName=money

metric m:net_income p:long l:"Net Income" t:dataTypeName=money

metric m:total_tax p:integer l:"Total Tax" t:dataTypeName=money

metric m:property_tax_return p:integer l:"Property Tax Return" t:dataTypeName=money

metric m:property_tax_amount p:integer l:"Property Tax Amount" t:dataTypeName=money

entity e:etp7-eky4 l:"IDOR 2009 Illinois Individual Income Tax - Web Returns, Retirement by AGI" t:attribution="Illinois Department of Revenue" t:url=https://data.illinois.gov/api/views/etp7-eky4

property e:etp7-eky4 t:meta.view v:id=etp7-eky4 v:category=Economics v:averageRating=0 v:name="IDOR 2009 Illinois Individual Income Tax - Web Returns, Retirement by AGI" v:attribution="Illinois Department of Revenue"

property e:etp7-eky4 t:meta.view.owner v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:displayName=wilcoxd

property e:etp7-eky4 t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| agi_bracket       | retirement_returns | retirement_subtractions | agi         | basic_exemption | 65_exemption | blind_exemption | net_income  | total_tax | property_tax_return | property_tax_amount | 
| ================= | ================== | ======================= | =========== | =============== | ============ | =============== | =========== | ========= | =================== | =================== | 
| $20,000 OR LESS   | 289788             | 2301466035              | 1911636928  | 406638          | 274194       | 4597            | 702500161   | 21075308  | 62273               | 5208512             | 
| $20,001 - $25,000 | 76433              | 938707889               | 1717925480  | 123339          | 67154        | 1125            | 582227739   | 17466794  | 28734               | 3382452             | 
| $25,001-$30,000   | 73644              | 1054385585              | 2024335242  | 124575          | 59570        | 1048            | 767319246   | 23019693  | 30616               | 3919008             | 
| $30,001-$35,000   | 68413              | 1114860135              | 2220080817  | 120190          | 51616        | 849             | 900275587   | 27008450  | 31076               | 4254160             | 
| $35,001-$40,000   | 62198              | 1149600355              | 2330391303  | 111877          | 43817        | 744             | 993428927   | 29802827  | 30921               | 4422740             | 
| $40,001-$50,000   | 114204             | 2503675706              | 5126694448  | 207979          | 76531        | 1339            | 2263639022  | 67909310  | 62241               | 10419465            | 
| $50,001-$75,000   | 244670             | 7032293709              | 15153166114 | 484173          | 157255       | 2589            | 7246046372  | 217381356 | 159898              | 28479815            | 
| $75,001-$100,000  | 166619             | 6106180882              | 14407405288 | 368204          | 108147       | 1647            | 7605594328  | 228167875 | 126414              | 26856092            | 
| $100,001-$150,000 | 146681             | 6314084072              | 17629263551 | 350941          | 85482        | 1299            | 10655382948 | 319661473 | 122634              | 32280723            | 
| $150,001-$200,000 | 48710              | 2535112925              | 8320890578  | 121134          | 27315        | 403             | 5590104835  | 167703405 | 42855               | 14336093            | 
```