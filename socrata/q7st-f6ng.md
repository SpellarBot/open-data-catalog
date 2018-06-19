# IDOR February 2011 Disbursement Info

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-february-2011-disbursement-info-f586c) |
| Metadata | [Link](https://data.illinois.gov/api/views/q7st-f6ng) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/q7st-f6ng/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/q7st-f6ng/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | q7st-f6ng |
| Name | IDOR February 2011 Disbursement Info |
| Attribution | Illinois Department of Revenue |
| Category | Economics |
| Tags | disbursements, revenue |
| Created | 2011-06-15T16:15:31Z |
| Publication Date | 2011-06-15T16:15:31Z |

## Description

Contains disbursement information for the February 2011 collections of Sales and Related Taxes. Voucher Date: 04/07/2011

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
series e:q7st-f6ng d:2011-01-01T00:00:00.000Z t:tax=MT t:vendor=390000010 t:local_governments=ABINGDON m:warrant=12447.11 m:interest_income_included_in_warrant=0

series e:q7st-f6ng d:2011-01-01T00:00:00.000Z t:tax=CST t:vendor=290000001 t:local_governments="ADAMS COUNTY GOVERNMENT" m:warrant=133647.28 m:interest_income_included_in_warrant=0

series e:q7st-f6ng d:2011-01-01T00:00:00.000Z t:tax=CT t:vendor=290000001 t:local_governments="ADAMS COUNTY GOVERNMENT" m:warrant=29748.19 m:interest_income_included_in_warrant=0
```

## Meta Commands

```ls
metric m:warrant p:double l:Warrant t:dataTypeName=money

metric m:interest_income_included_in_warrant p:integer l:"Interest Income Included in Warrant" t:dataTypeName=money

entity e:q7st-f6ng l:"IDOR February 2011 Disbursement Info" t:attribution="Illinois Department of Revenue" t:url=https://data.illinois.gov/api/views/q7st-f6ng

property e:q7st-f6ng t:meta.view v:id=q7st-f6ng v:category=Economics v:averageRating=0 v:name="IDOR February 2011 Disbursement Info" v:attribution="Illinois Department of Revenue"

property e:q7st-f6ng t:meta.view.owner v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:displayName=wilcoxd

property e:q7st-f6ng t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| local_governments       | tax   | vendor    | warrant   | interest_income_included_in_warrant | 
| ======================= | ===== | ========= | ========= | =================================== | 
| ABINGDON                | MT    | 390000010 | 12447.11  | 0                                   | 
| ADAMS COUNTY GOVERNMENT | CST   | 290000001 | 133647.28 | 0                                   | 
| ADAMS COUNTY GOVERNMENT | CT    | 290000001 | 29748.19  | 0                                   | 
| ADDIEVILLE              | MT    | 390000018 | 1024.98   | 0                                   | 
| ADDISON                 | HMR   | 390000029 | 334609.25 | 0                                   | 
| ADDISON                 | MT    | 390000029 | 546869.52 | 0                                   | 
| ADDISON                 | MTART | 390000029 | 187.9     | 0                                   | 
| ADELINE                 | MT    | 390000030 | 91.2      | 0                                   | 
| ALBANY                  | MT    | 390000020 | 2194.02   | 0                                   | 
| ALBERS                  | MT    | 390000045 | 5809.65   | 0                                   | 
```