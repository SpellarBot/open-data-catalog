# Initial Conferences Held ( RSN 39973)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/initial-conferences-held-rsn-39973-c08a2) |
| Metadata | [Link](https://data.hawaii.gov/api/views/yrmn-32dg) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/yrmn-32dg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/yrmn-32dg/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | yrmn-32dg |
| Name | Initial Conferences Held ( RSN 39973) |
| Attribution | Labor and Industrial Relations Appeals Board |
| Created | 2012-08-23T18:19:20Z |
| Publication Date | 2013-07-30T18:15:43Z |

## Description

Labor and Industrial Relations Appeals Board - Initial Conferences Held

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                                   | Data Type | Render Type |
| ======== | ============== | ====================================== | ====================================== | ========= | =========== |
| No       | time           | :updated_at                            | updated_at                             | meta_data | meta_data   |
| Yes      | series tag     | fiscal_year                            | Fiscal Year                            | text      | text        |
| Yes      | numeric metric | number_of_pre_hearing_conferences_held | Number of Pre-Hearing Conferences Held | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:yrmn-32dg d:2012-08-23T11:19:21.000Z t:fiscal_year="1975 - 1976" m:number_of_pre_hearing_conferences_held=484

series e:yrmn-32dg d:2012-08-23T11:19:21.000Z t:fiscal_year="1976 - 1977" m:number_of_pre_hearing_conferences_held=677

series e:yrmn-32dg d:2012-08-23T11:19:21.000Z t:fiscal_year="1977 - 1978" m:number_of_pre_hearing_conferences_held=587
```

## Meta Commands

```ls
metric m:number_of_pre_hearing_conferences_held p:integer l:"Number of Pre-Hearing Conferences Held" t:dataTypeName=number

entity e:yrmn-32dg l:"Initial Conferences Held ( RSN 39973)" t:attribution="Labor and Industrial Relations Appeals Board" t:url=https://data.hawaii.gov/api/views/yrmn-32dg

property e:yrmn-32dg t:meta.view v:id=yrmn-32dg v:averageRating=0 v:name="Initial Conferences Held ( RSN 39973)" v:attribution="Labor and Industrial Relations Appeals Board"

property e:yrmn-32dg t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:yrmn-32dg t:meta.view.owner v:id=r3in-7sfs v:profileImageUrlMedium=/api/users/r3in-7sfs/profile_images/THUMB v:profileImageUrlLarge=/api/users/r3in-7sfs/profile_images/LARGE v:screenName="Labor and Industrial Relations Appeals Board" v:profileImageUrlSmall=/api/users/r3in-7sfs/profile_images/TINY v:displayName="Labor and Industrial Relations Appeals Board"

property e:yrmn-32dg t:meta.view.tableauthor v:id=r3in-7sfs v:profileImageUrlMedium=/api/users/r3in-7sfs/profile_images/THUMB v:profileImageUrlLarge=/api/users/r3in-7sfs/profile_images/LARGE v:screenName="Labor and Industrial Relations Appeals Board" v:profileImageUrlSmall=/api/users/r3in-7sfs/profile_images/TINY v:roleName=publisher v:displayName="Labor and Industrial Relations Appeals Board"
```

## Top Records

```ls
| :updated_at | fiscal_year | number_of_pre_hearing_conferences_held | 
| =========== | =========== | ====================================== | 
| 1345720761  | 1975 - 1976 | 484                                    | 
| 1345720761  | 1976 - 1977 | 677                                    | 
| 1345720761  | 1977 - 1978 | 587                                    | 
| 1345720761  | 1978 - 1979 | 462                                    | 
| 1345720761  | 1979 - 1980 | 595                                    | 
| 1345720761  | 1980 - 1981 | 594                                    | 
| 1345720761  | 1981 - 1982 | 515                                    | 
| 1345720761  | 1982 - 1983 | 521                                    | 
| 1345720761  | 1983 - 1984 | 521                                    | 
| 1345720761  | 1984 - 1985 | 338                                    | 
```