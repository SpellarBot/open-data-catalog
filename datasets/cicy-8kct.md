# IDOR March 2011 Disbursements Info

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-march-2011-disbursements-info-d62dd) |
| Metadata | [Link](https://data.illinois.gov/api/views/cicy-8kct) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/cicy-8kct/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/cicy-8kct/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | cicy-8kct |
| Name | IDOR March 2011 Disbursements Info |
| Attribution | Illinois Department of Revenue |
| Category | Economics |
| Tags | disbursements, revenue |
| Created | 2011-06-15T16:19:34Z |
| Publication Date | 2011-06-15T16:19:34Z |

## Description

Contains disbursement information for the March 2011 collections of Sales and Related Taxes. Voucher Date: 05/05/2011

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
series e:cicy-8kct d:2011-01-01T00:00:00.000Z t:tax=MT t:vendor=390000010 t:local_governments=ABINGDON m:warrant=13731.71 m:interest_income_included_in_warrant=0

series e:cicy-8kct d:2011-01-01T00:00:00.000Z t:tax=CST t:vendor=290000001 t:local_governments="ADAMS COUNTY GOVERNMENT" m:warrant=146933.53 m:interest_income_included_in_warrant=0

series e:cicy-8kct d:2011-01-01T00:00:00.000Z t:tax=CT t:vendor=290000001 t:local_governments="ADAMS COUNTY GOVERNMENT" m:warrant=30176.41 m:interest_income_included_in_warrant=0
```

## Meta Commands

```ls
metric m:warrant p:double l:Warrant t:dataTypeName=money

metric m:interest_income_included_in_warrant p:double l:"Interest Income Included in Warrant" t:dataTypeName=money

entity e:cicy-8kct l:"IDOR March 2011 Disbursements Info" t:attribution="Illinois Department of Revenue" t:url=https://data.illinois.gov/api/views/cicy-8kct

property e:cicy-8kct t:meta.view v:id=cicy-8kct v:category=Economics v:averageRating=0 v:name="IDOR March 2011 Disbursements Info" v:attribution="Illinois Department of Revenue"

property e:cicy-8kct t:meta.view.owner v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:displayName=wilcoxd

property e:cicy-8kct t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| local_governments       | tax   | vendor    | warrant   | interest_income_included_in_warrant | 
| ======================= | ===== | ========= | ========= | =================================== | 
| ABINGDON                | MT    | 390000010 | 13731.71  | 0                                   | 
| ADAMS COUNTY GOVERNMENT | CST   | 290000001 | 146933.53 | 0                                   | 
| ADAMS COUNTY GOVERNMENT | CT    | 290000001 | 30176.41  | 0                                   | 
| ADDIEVILLE              | MT    | 390000018 | 4048.33   | 0                                   | 
| ADDISON                 | HMR   | 390000029 | 317153.72 | 120.73                              | 
| ADDISON                 | MT    | 390000029 | 520825.64 | 0                                   | 
| ADDISON                 | MTART | 390000029 | 119.06    | 0                                   | 
| ADELINE                 | MT    | 390000030 | 38.56     | 0                                   | 
| ALBANY                  | MT    | 390000020 | 3059.78   | 0                                   | 
| ALBERS                  | MT    | 390000045 | 6423.81   | 0                                   | 
```