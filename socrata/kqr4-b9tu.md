# Settlement And Status Conferences Held ( RSN 39974)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/settlement-and-status-conferences-held-rsn-39974-18d65) |
| Metadata | [Link](https://data.hawaii.gov/api/views/kqr4-b9tu) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/kqr4-b9tu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/kqr4-b9tu/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | kqr4-b9tu |
| Name | Settlement And Status Conferences Held ( RSN 39974) |
| Attribution | Labor and Industrial Relations Appeals Board |
| Created | 2012-08-23T01:35:06Z |
| Publication Date | 2013-07-30T18:11:18Z |

## Description

Labor and Industrial Relations Appeals Board - Settlement And Status Conferences Held

## Columns

```ls
| Included | Schema Type    | Field Name                                   | Name                                         | Data Type | Render Type |
| ======== | ============== | ============================================ | ============================================ | ========= | =========== |
| No       | time           | :updated_at                                  | updated_at                                   | meta_data | meta_data   |
| Yes      | series tag     | fiscal_year                                  | Fiscal Year                                  | text      | text        |
| Yes      | numeric metric | number_of_settlement_status_conferences_held | Number of Settlement/Status Conferences Held | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kqr4-b9tu d:2012-08-22T18:36:31.000Z t:fiscal_year="1975 - 1976" m:number_of_settlement_status_conferences_held=28

series e:kqr4-b9tu d:2012-08-22T18:36:31.000Z t:fiscal_year="1976 - 1977" m:number_of_settlement_status_conferences_held=37

series e:kqr4-b9tu d:2012-08-22T18:36:31.000Z t:fiscal_year="1977 - 1978" m:number_of_settlement_status_conferences_held=37
```

## Meta Commands

```ls
metric m:number_of_settlement_status_conferences_held p:integer l:"Number of Settlement/Status Conferences Held" t:dataTypeName=number

entity e:kqr4-b9tu l:"Settlement And Status Conferences Held ( RSN 39974)" t:attribution="Labor and Industrial Relations Appeals Board" t:url=https://data.hawaii.gov/api/views/kqr4-b9tu

property e:kqr4-b9tu t:meta.view v:id=kqr4-b9tu v:averageRating=0 v:name="Settlement And Status Conferences Held ( RSN 39974)" v:attribution="Labor and Industrial Relations Appeals Board"

property e:kqr4-b9tu t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:kqr4-b9tu t:meta.view.owner v:id=r3in-7sfs v:profileImageUrlMedium=/api/users/r3in-7sfs/profile_images/THUMB v:profileImageUrlLarge=/api/users/r3in-7sfs/profile_images/LARGE v:screenName="Labor and Industrial Relations Appeals Board" v:profileImageUrlSmall=/api/users/r3in-7sfs/profile_images/TINY v:displayName="Labor and Industrial Relations Appeals Board"

property e:kqr4-b9tu t:meta.view.tableauthor v:id=r3in-7sfs v:profileImageUrlMedium=/api/users/r3in-7sfs/profile_images/THUMB v:profileImageUrlLarge=/api/users/r3in-7sfs/profile_images/LARGE v:screenName="Labor and Industrial Relations Appeals Board" v:profileImageUrlSmall=/api/users/r3in-7sfs/profile_images/TINY v:roleName=publisher v:displayName="Labor and Industrial Relations Appeals Board"
```

## Top Records

```ls
| :updated_at | fiscal_year | number_of_settlement_status_conferences_held | 
| =========== | =========== | ============================================ | 
| 1345660591  | 1975 - 1976 | 28                                           | 
| 1345660591  | 1976 - 1977 | 37                                           | 
| 1345660591  | 1977 - 1978 | 37                                           | 
| 1345660591  | 1978 - 1979 | 0                                            | 
| 1345660591  | 1979 - 1980 | 57                                           | 
| 1345660591  | 1980 - 1981 | 112                                          | 
| 1345660591  | 1981 - 1982 | 59                                           | 
| 1345660591  | 1982 - 1983 | 85                                           | 
| 1345660591  | 1983 - 1984 | 46                                           | 
| 1345660591  | 1984 - 1985 | 30                                           | 
```