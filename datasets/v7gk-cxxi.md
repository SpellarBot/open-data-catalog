# POLA Quarterly Financial Statement 2013 - 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pola-quarterly-financial-statement-b831f) |
| Metadata | [Link](https://data.lacity.org/api/views/v7gk-cxxi) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/v7gk-cxxi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/v7gk-cxxi/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | v7gk-cxxi |
| Name | POLA Quarterly Financial Statement 2013 - 2014 |
| Attribution | Port of Los Angeles |
| Category | A Well Run City |
| Tags | financial statement |
| Created | 2014-05-16T17:38:37Z |
| Publication Date | 2014-05-19T21:07:18Z |

## Description

POLA Quarterly Financial Statement 2013 -2014

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | accounts_category | Accounts/Category | text      | text        |
| Yes      | numeric metric | as_of_march_2014  | As of March 2014  | money     | money       |
| Yes      | numeric metric | as_of_march_2013  | As of March 2013  | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:v7gk-cxxi d:2013-01-01T00:00:00.000Z t:accounts_category="Assets.Current Assets.Cash and cash equivalents, unrestricted" m:as_of_march_2013=430987 m:as_of_march_2014=287857

series e:v7gk-cxxi d:2013-01-01T00:00:00.000Z t:accounts_category="Assets.Current Assets.Cash and cash equivalents, restricted" m:as_of_march_2013=39129 m:as_of_march_2014=30658

series e:v7gk-cxxi d:2013-01-01T00:00:00.000Z t:accounts_category="Assets.Current Assets.Accounts receivable, net of allowance for doubtful accounts:2014 - $5,032; 2013 - $5,307" m:as_of_march_2013=25804 m:as_of_march_2014=29540
```

## Meta Commands

```ls
metric m:as_of_march_2014 p:integer l:"As of March 2014" t:dataTypeName=money

metric m:as_of_march_2013 p:integer l:"As of March 2013" t:dataTypeName=money

entity e:v7gk-cxxi l:"POLA Quarterly Financial Statement 2013 - 2014" t:attribution="Port of Los Angeles" t:url=https://data.lacity.org/api/views/v7gk-cxxi

property e:v7gk-cxxi t:meta.view v:id=v7gk-cxxi v:category="A Well Run City" v:averageRating=0 v:name="POLA Quarterly Financial Statement 2013 - 2014" v:attribution="Port of Los Angeles"

property e:v7gk-cxxi t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:v7gk-cxxi t:meta.view.owner v:id=2ib6-ssvz v:profileImageUrlMedium=/api/users/2ib6-ssvz/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ib6-ssvz/profile_images/LARGE v:screenName="Port of Los Angeles" v:profileImageUrlSmall=/api/users/2ib6-ssvz/profile_images/TINY v:displayName="Port of Los Angeles"

property e:v7gk-cxxi t:meta.view.tableauthor v:id=2ib6-ssvz v:profileImageUrlMedium=/api/users/2ib6-ssvz/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ib6-ssvz/profile_images/LARGE v:screenName="Port of Los Angeles" v:profileImageUrlSmall=/api/users/2ib6-ssvz/profile_images/TINY v:roleName=publisher v:displayName="Port of Los Angeles"
```

## Top Records

```ls
| accounts_category                                                                                              | as_of_march_2014 | as_of_march_2013 | 
| ============================================================================================================== | ================ | ================ | 
| Assets.Current Assets.Cash and cash equivalents, unrestricted                                                  | 287857           | 430987           | 
| Assets.Current Assets.Cash and cash equivalents, restricted                                                    | 30658            | 39129            | 
| Assets.Current Assets.Accounts receivable, net of allowance for doubtful accounts:2014 - $5,032; 2013 - $5,307 | 29540            | 25804            | 
| Assets.Current Assets.Grants receivable                                                                        | 7675             | 19729            | 
| Assets.Current Assets.Materials and supplies inventories                                                       | 2620             | 2049             | 
| Assets.Current Assets.Prepaid expenses                                                                         | 1155             | 1411             | 
| Assets.Current Assets.Accrued interest receivable                                                              | 478              | 1021             | 
| Assets.Current Assets.Current portion of notes receivable                                                      | 4910             | 4767             | 
| Assets.Current Assets.Total                                                                                    | 364893           | 524897           | 
| Assets.Noncurrent Restricted Assets.Restricted investments ? bond funds                                        | 58054            | 59885            | 
```