# POLA Finance Annual Financial Report (CAFR) FY12 - FY13

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pola-finance-annual-financial-report-cafr-0220f) |
| Metadata | [Link](https://data.lacity.org/api/views/jdgw-bwcf) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/jdgw-bwcf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/jdgw-bwcf/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | jdgw-bwcf |
| Name | POLA Finance Annual Financial Report (CAFR) FY12 - FY13 |
| Attribution | Port of Los Angeles |
| Category | A Well Run City |
| Tags | financial statement |
| Created | 2014-05-16T16:48:01Z |
| Publication Date | 2014-05-19T21:06:54Z |

## Description

POLA Finance Annual Financial Report (CAFR) FY12 - FY13 Published historical data.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | account_category | Account/Category | text      | text        |
| Yes      | numeric metric | fy_2013          | FY 2013          | money     | money       |
| Yes      | numeric metric | fy_2012          | FY 2012          | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:jdgw-bwcf d:2014-05-16T09:48:04.000Z t:account_category="Assets.Current Assets.Cash and cash equivalents, unrestricted" m:fy_2013=351793 m:fy_2012=444355

series e:jdgw-bwcf d:2014-05-16T09:48:04.000Z t:account_category="Assets.Current Assets.Cash and cash equivalents, restricted" m:fy_2013=38066 m:fy_2012=43236

series e:jdgw-bwcf d:2014-05-16T09:48:04.000Z t:account_category="Assets.Current Assets.Accounts receivable, net of allowance for doubtful accounts:  2013 - $5,170; 2012 - $5,368" m:fy_2013=36200 m:fy_2012=33646
```

## Meta Commands

```ls
metric m:fy_2013 p:integer l:"FY 2013" t:dataTypeName=money

metric m:fy_2012 p:integer l:"FY 2012" t:dataTypeName=money

entity e:jdgw-bwcf l:"POLA Finance Annual Financial Report (CAFR) FY12 - FY13" t:attribution="Port of Los Angeles" t:url=https://data.lacity.org/api/views/jdgw-bwcf

property e:jdgw-bwcf t:meta.view v:id=jdgw-bwcf v:category="A Well Run City" v:averageRating=0 v:name="POLA Finance Annual Financial Report (CAFR) FY12 - FY13" v:attribution="Port of Los Angeles"

property e:jdgw-bwcf t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:jdgw-bwcf t:meta.view.owner v:id=2ib6-ssvz v:profileImageUrlMedium=/api/users/2ib6-ssvz/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ib6-ssvz/profile_images/LARGE v:screenName="Port of Los Angeles" v:profileImageUrlSmall=/api/users/2ib6-ssvz/profile_images/TINY v:displayName="Port of Los Angeles"

property e:jdgw-bwcf t:meta.view.tableauthor v:id=2ib6-ssvz v:profileImageUrlMedium=/api/users/2ib6-ssvz/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ib6-ssvz/profile_images/LARGE v:screenName="Port of Los Angeles" v:profileImageUrlSmall=/api/users/2ib6-ssvz/profile_images/TINY v:roleName=publisher v:displayName="Port of Los Angeles"
```

## Top Records

```ls
| :updated_at | account_category                                                                                                | fy_2013 | fy_2012 | 
| =========== | =============================================================================================================== | ======= | ======= | 
| 1400233684  | Assets.Current Assets.Cash and cash equivalents, unrestricted                                                   | 351793  | 444355  | 
| 1400233684  | Assets.Current Assets.Cash and cash equivalents, restricted                                                     | 38066   | 43236   | 
| 1400233684  | Assets.Current Assets.Accounts receivable, net of allowance for doubtful accounts: 2013 - $5,170; 2012 - $5,368 | 36200   | 33646   | 
| 1400233684  | Assets.Current Assets.Grants receivable                                                                         | 19161   | 19460   | 
| 1400233684  | Assets.Current Assets.Materials and supplies inventories                                                        | 2054    | 2103    | 
| 1400233684  | Assets.Current Assets.Prepaid expenses                                                                          | 671     | 724     | 
| 1400233684  | Assets.Current Assets.Accrued interest receivable                                                               | 934     | 859     | 
| 1400233684  | Assets.Current Assets.Current portion of notes receivable                                                       | 4803    | 4663    | 
| 1400233684  | Assets.Current Assets.Total                                                                                     | 453682  | 549046  | 
| 1400233684  | Assets.Noncurrent Restricted Assets.Restricted investments ? bond funds                                         | 57913   | 67796   | 
```