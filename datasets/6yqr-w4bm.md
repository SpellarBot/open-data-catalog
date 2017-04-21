# Number of Appeals ( RSN 39972)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/number-of-appeals-rsn-39972-bec95) |
| Metadata | [Link](https://data.hawaii.gov/api/views/6yqr-w4bm) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/6yqr-w4bm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/6yqr-w4bm/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 6yqr-w4bm |
| Name | Number of Appeals ( RSN 39972) |
| Attribution | Labor and Industrial Relations Appeals Board |
| Created | 2012-08-23T18:13:42Z |
| Publication Date | 2013-07-30T18:09:17Z |

## Description

Labor and Industrial Relations Appeals Board - Appeals Received

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                       | Data Type | Render Type |
| ======== | ============== | ======================= | ========================== | ========= | =========== |
| No       | time           | :updated_at             | updated_at                 | meta_data | meta_data   |
| Yes      | series tag     | fiscal_year             | Fiscal Year                | text      | text        |
| Yes      | numeric metric | number_of_appeals_filed | Number of Appeals Received | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:6yqr-w4bm d:2012-08-23T11:13:43.000Z t:fiscal_year="1975 - 1976" m:number_of_appeals_filed=289

series e:6yqr-w4bm d:2012-08-23T11:13:43.000Z t:fiscal_year="1976 - 1977" m:number_of_appeals_filed=377

series e:6yqr-w4bm d:2012-08-23T11:13:43.000Z t:fiscal_year="1977 - 1978" m:number_of_appeals_filed=430
```

## Meta Commands

```ls
metric m:number_of_appeals_filed p:integer l:"Number of Appeals Received" t:dataTypeName=number

entity e:6yqr-w4bm l:"Number of Appeals ( RSN 39972)" t:attribution="Labor and Industrial Relations Appeals Board" t:url=https://data.hawaii.gov/api/views/6yqr-w4bm

property e:6yqr-w4bm t:meta.view v:id=6yqr-w4bm v:averageRating=0 v:name="Number of Appeals ( RSN 39972)" v:attribution="Labor and Industrial Relations Appeals Board"

property e:6yqr-w4bm t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:6yqr-w4bm t:meta.view.owner v:id=r3in-7sfs v:profileImageUrlMedium=/api/users/r3in-7sfs/profile_images/THUMB v:profileImageUrlLarge=/api/users/r3in-7sfs/profile_images/LARGE v:screenName="Labor and Industrial Relations Appeals Board" v:profileImageUrlSmall=/api/users/r3in-7sfs/profile_images/TINY v:displayName="Labor and Industrial Relations Appeals Board"

property e:6yqr-w4bm t:meta.view.tableauthor v:id=r3in-7sfs v:profileImageUrlMedium=/api/users/r3in-7sfs/profile_images/THUMB v:profileImageUrlLarge=/api/users/r3in-7sfs/profile_images/LARGE v:screenName="Labor and Industrial Relations Appeals Board" v:profileImageUrlSmall=/api/users/r3in-7sfs/profile_images/TINY v:roleName=publisher v:displayName="Labor and Industrial Relations Appeals Board"
```

## Top Records

```ls
| :updated_at | fiscal_year | number_of_appeals_filed | 
| =========== | =========== | ======================= | 
| 1345720423  | 1975 - 1976 | 289                     | 
| 1345720423  | 1976 - 1977 | 377                     | 
| 1345720423  | 1977 - 1978 | 430                     | 
| 1345720423  | 1978 - 1979 | 441                     | 
| 1345720423  | 1979 - 1980 | 444                     | 
| 1345720423  | 1980 - 1981 | 551                     | 
| 1345720423  | 1981 - 1982 | 603                     | 
| 1345720423  | 1982 - 1983 | 509                     | 
| 1345720423  | 1983 - 1984 | 477                     | 
| 1345720423  | 1984 - 1985 | 618                     | 
```