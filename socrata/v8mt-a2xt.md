# IDOR April 2011 Disbursement Info

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-april-2011-disbursement-info-c2dcb) |
| Metadata | [Link](https://data.illinois.gov/api/views/v8mt-a2xt) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/v8mt-a2xt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/v8mt-a2xt/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | v8mt-a2xt |
| Name | IDOR April 2011 Disbursement Info |
| Attribution | Illinois Department of Revenue |
| Category | Economics |
| Tags | disbursements, revenue |
| Created | 2011-06-15T16:21:44Z |
| Publication Date | 2011-06-15T16:21:44Z |

## Description

Contains disbursement information for the April 2011 collections of Sales and Related Taxes. Voucher Date: 06/03/2011

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type | Render Type |
| ======== | ============== | =================================== | =================================== | ========= | =========== |
| Yes      | series tag     | local_governments                   | Local Governments                   | text      | text        |
| Yes      | series tag     | tax                                 | Tax                                 | text      | text        |
| Yes      | series tag     | vendor                              | Vendor#                             | text      | text        |
| Yes      | numeric metric | warrant                             | Warrant                             | money     | money       |
| Yes      | numeric metric | interest_income_included_in_warrant | Interest Income Included in Warrant | money     | money       |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:v8mt-a2xt d:2011-01-01T00:00:00.000Z t:tax=MT t:vendor=390000010 t:local_governments=ABINGDON m:warrant=15527.35 m:interest_income_included_in_warrant=0

series e:v8mt-a2xt d:2011-01-01T00:00:00.000Z t:tax=CST t:vendor=290000001 t:local_governments="ADAMS COUNTY GOVERNMENT" m:warrant=164238.97 m:interest_income_included_in_warrant=0

series e:v8mt-a2xt d:2011-01-01T00:00:00.000Z t:tax=CT t:vendor=290000001 t:local_governments="ADAMS COUNTY GOVERNMENT" m:warrant=40821.14 m:interest_income_included_in_warrant=0
```

## Meta Commands

```ls
metric m:warrant p:double l:Warrant t:dataTypeName=money

metric m:interest_income_included_in_warrant p:double l:"Interest Income Included in Warrant" t:dataTypeName=money

entity e:v8mt-a2xt l:"IDOR April 2011 Disbursement Info" t:attribution="Illinois Department of Revenue" t:url=https://data.illinois.gov/api/views/v8mt-a2xt

property e:v8mt-a2xt t:meta.view v:id=v8mt-a2xt v:category=Economics v:averageRating=0 v:name="IDOR April 2011 Disbursement Info" v:attribution="Illinois Department of Revenue"

property e:v8mt-a2xt t:meta.view.owner v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:displayName=wilcoxd

property e:v8mt-a2xt t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| local_governments       | tax   | vendor    | warrant   | interest_income_included_in_warrant | 
| ======================= | ===== | ========= | ========= | =================================== | 
| ABINGDON                | MT    | 390000010 | 15527.35  | 0                                   | 
| ADAMS COUNTY GOVERNMENT | CST   | 290000001 | 164238.97 | 0                                   | 
| ADAMS COUNTY GOVERNMENT | CT    | 290000001 | 40821.14  | 0                                   | 
| ADDIEVILLE              | MT    | 390000018 | 3709.58   | 0                                   | 
| ADDISON                 | HMR   | 390000029 | 393603.73 | 636.41                              | 
| ADDISON                 | MT    | 390000029 | 641189.40 | 0                                   | 
| ADDISON                 | MTART | 390000029 | 184.04    | 0                                   | 
| ADELINE                 | MT    | 390000030 | 54.08     | 0                                   | 
| ALBANY                  | MT    | 390000020 | 2860.88   | 0                                   | 
| ALBERS                  | MT    | 390000045 | 6904.05   | 0                                   | 
```