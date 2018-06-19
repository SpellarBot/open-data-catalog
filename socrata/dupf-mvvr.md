# Beginning and Expanding Farmer Loan Program (Aggie Bond) FY2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/beginning-and-expanding-farmer-loan-program-aggie-bond-fy2016) |
| Metadata | [Link](https://data.oregon.gov/api/views/dupf-mvvr) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/dupf-mvvr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/dupf-mvvr/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | dupf-mvvr |
| Name | Beginning and Expanding Farmer Loan Program (Aggie Bond) FY2016 |
| Attribution | Business Oregon |
| Tags | transparency, aggie bonds, beginning and expanding farmer loans, fiscal year 2016 |
| Created | 2016-10-06T16:08:38Z |
| Publication Date | 2016-10-06T18:19:26Z |

## Description

Loans from the Beginning and Expanding Farmer Loan Program under ORS 285A.430. For more information visit www.oregon4biz.com/How-We-Can-Help/Finance-Programs/Aggie-Bond/

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | names_of_persons_who_received_a_loan | Names of persons who received a loan | text      | text        |
| Yes      | numeric metric | amount                               | Amount                               | money     | money       |
| Yes      | series tag     | bond                                 | Bond                                 | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:dupf-mvvr d:2016-01-01T00:00:00.000Z t:bond="Aggie Bond Series 1" t:names_of_persons_who_received_a_loan="Sanchez, Melissa and Uriel" m:amount=256000

series e:dupf-mvvr d:2016-01-01T00:00:00.000Z t:bond="Aggie Bond Series 2" t:names_of_persons_who_received_a_loan="Porter, Suzanne and Tibwe, Asinete" m:amount=180750

series e:dupf-mvvr d:2016-01-01T00:00:00.000Z t:names_of_persons_who_received_a_loan="Total amount of revenue (Aggie) bonds issued" m:amount=436750
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount t:dataTypeName=money

entity e:dupf-mvvr l:"Beginning and Expanding Farmer Loan Program (Aggie Bond)  FY2016" t:attribution="Business Oregon" t:url=https://data.oregon.gov/api/views/dupf-mvvr

property e:dupf-mvvr t:meta.view v:id=dupf-mvvr v:attributionLink=http://www.oregon4biz.com v:averageRating=0 v:name="Beginning and Expanding Farmer Loan Program (Aggie Bond)  FY2016" v:attribution="Business Oregon"

property e:dupf-mvvr t:meta.view.owner v:id=ewcx-ibs2 v:profileImageUrlMedium=/api/users/ewcx-ibs2/profile_images/THUMB v:profileImageUrlLarge=/api/users/ewcx-ibs2/profile_images/LARGE v:screenName=carmens v:profileImageUrlSmall=/api/users/ewcx-ibs2/profile_images/TINY v:displayName=carmens

property e:dupf-mvvr t:meta.view.tableauthor v:id=ewcx-ibs2 v:profileImageUrlMedium=/api/users/ewcx-ibs2/profile_images/THUMB v:profileImageUrlLarge=/api/users/ewcx-ibs2/profile_images/LARGE v:screenName=carmens v:profileImageUrlSmall=/api/users/ewcx-ibs2/profile_images/TINY v:roleName=editor v:displayName=carmens
```

## Top Records

```ls
| names_of_persons_who_received_a_loan         | amount | bond                | 
| ============================================ | ====== | =================== | 
| Sanchez, Melissa and Uriel                   | 256000 | Aggie Bond Series 1 | 
| Porter, Suzanne and Tibwe, Asinete           | 180750 | Aggie Bond Series 2 | 
| Total amount of revenue (Aggie) bonds issued | 436750 |                     | 
```