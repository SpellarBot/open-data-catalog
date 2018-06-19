# Lifeline Telephone Assistance Subscribers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lifeline-telephone-assistance-subscribers) |
| Metadata | [Link](https://data.iowa.gov/api/views/5aes-sde8) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/5aes-sde8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/5aes-sde8/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 5aes-sde8 |
| Name | Lifeline Telephone Assistance Subscribers |
| Attribution | Federal Communications Commission Form 555, as filed with the Iowa Utilities Board in January 2016 (FLR docket) |
| Category | Transportation & Utilities |
| Tags | lifeline, low-income, telecommunications |
| Created | 2016-09-28T16:15:12Z |
| Publication Date | 2016-09-30T20:16:36Z |

## Description

Beginning in 2015, the dataset shows, by Iowa telecommunications carrier, the number of subscribers who received low-income Lifeline assistance for his/her telephone service in the prior year and also indicates the number of subscribers who remain eligible to continue their Lifeline benefits in the current year.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                               | Data Type | Render Type |
| ======== | ============== | ===================== | ================================== | ========= | =========== |
| Yes      | time           | reporting_year        | Reporting Year                     | number    | number      |
| Yes      | series tag     | company_name          | Provider                           | text      | text        |
| Yes      | series tag     | technology_provided   | Technology Type                    | text      | text        |
| Yes      | numeric metric | subscribers_contacted | No. of Subscribers Contacted       | number    | number      |
| Yes      | numeric metric | subscribers_eligible  | No. of Subscribers Deemed Eligible | number    | number      |
```

## Time Field

```ls
Value = reporting_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5aes-sde8 d:2015-01-01T00:00:00.000Z t:technology_provided=wireline t:company_name="Ace Telephone Association" m:subscribers_eligible=63 m:subscribers_contacted=71

series e:5aes-sde8 d:2015-01-01T00:00:00.000Z t:technology_provided=wireline t:company_name="Advanced Network Communications  LLC" m:subscribers_eligible=16 m:subscribers_contacted=16

series e:5aes-sde8 d:2015-01-01T00:00:00.000Z t:technology_provided=wireline t:company_name="Algona Municipal Utilities" m:subscribers_eligible=35 m:subscribers_contacted=39
```

## Meta Commands

```ls
metric m:subscribers_contacted p:integer l:"No. of Subscribers Contacted" t:dataTypeName=number

metric m:subscribers_eligible p:integer l:"No. of Subscribers Deemed Eligible" t:dataTypeName=number

entity e:5aes-sde8 l:"Lifeline Telephone Assistance Subscribers" t:attribution="Federal Communications Commission Form 555, as filed with the Iowa Utilities Board in January 2016 (FLR docket)" t:url=https://data.iowa.gov/api/views/5aes-sde8

property e:5aes-sde8 t:meta.view v:id=5aes-sde8 v:category="Transportation & Utilities" v:attributionLink=https://efs.iowa.gov v:averageRating=0 v:name="Lifeline Telephone Assistance Subscribers" v:attribution="Federal Communications Commission Form 555, as filed with the Iowa Utilities Board in January 2016 (FLR docket)"

property e:5aes-sde8 t:meta.view.license v:name="Public Domain"

property e:5aes-sde8 t:meta.view.owner v:id=3wc4-hb8a v:profileImageUrlMedium=/api/users/3wc4-hb8a/profile_images/THUMB v:profileImageUrlLarge=/api/users/3wc4-hb8a/profile_images/LARGE v:screenName="Iowa Utilities Board" v:profileImageUrlSmall=/api/users/3wc4-hb8a/profile_images/TINY v:displayName="Iowa Utilities Board"

property e:5aes-sde8 t:meta.view.tableauthor v:id=3wc4-hb8a v:profileImageUrlMedium=/api/users/3wc4-hb8a/profile_images/THUMB v:profileImageUrlLarge=/api/users/3wc4-hb8a/profile_images/LARGE v:screenName="Iowa Utilities Board" v:profileImageUrlSmall=/api/users/3wc4-hb8a/profile_images/TINY v:roleName=editor v:displayName="Iowa Utilities Board"
```

## Top Records

```ls
| reporting_year | company_name                            | technology_provided | subscribers_contacted | subscribers_eligible | 
| ============== | ======================================= | =================== | ===================== | ==================== | 
| 2015           | Ace Telephone Association               | wireline            | 71                    | 63                   | 
| 2015           | Advanced Network Communications LLC     | wireline            | 16                    | 16                   | 
| 2015           | Algona Municipal Utilities              | wireline            | 39                    | 35                   | 
| 2015           | Allamakee-Clayton Electric Coop, Inc.   | wireless            | 0                     | 0                    | 
| 2015           | Alliance Communications Cooperative Inc | wireline            | 29                    | 23                   | 
| 2015           | Alpine Communications LC                | wireline            | 141                   | 123                  | 
| 2015           | Alta Municipal Utilities                | wireline            | 5                     | 5                    | 
| 2015           | Andrew Telephone Company Inc            | wireline            | 8                     | 6                    | 
| 2015           | Arcadia Telephone Cooperative           | wireline            | 3                     | 2                    | 
| 2015           | Atkins Telephone Company Inc.           | wireline            | 7                     | 7                    | 
```