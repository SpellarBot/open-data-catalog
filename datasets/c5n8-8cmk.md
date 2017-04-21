# Motions Hearings Held ( RSN 39976)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/motions-hearings-held-rsn-39976-a0310) |
| Metadata | [Link](https://data.hawaii.gov/api/views/c5n8-8cmk) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/c5n8-8cmk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/c5n8-8cmk/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | c5n8-8cmk |
| Name | Motions Hearings Held ( RSN 39976) |
| Attribution | Labor and Industrial Relations Appeals Board |
| Created | 2012-08-23T18:17:26Z |
| Publication Date | 2013-07-30T18:07:33Z |

## Description

Labor and Industrial Relations Appeals Board - Motions Hearings Held

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| No       | time           | :updated_at                    | updated_at                     | meta_data | meta_data   |
| Yes      | series tag     | fiscal_year                    | Fiscal Year                    | text      | text        |
| Yes      | numeric metric | number_of_motion_hearings_held | Number of Motion Hearings Held | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:c5n8-8cmk d:2012-08-23T11:17:27.000Z t:fiscal_year="1975 - 1976" m:number_of_motion_hearings_held=82

series e:c5n8-8cmk d:2012-08-23T11:17:27.000Z t:fiscal_year="1976 - 1977" m:number_of_motion_hearings_held=84

series e:c5n8-8cmk d:2012-08-23T11:17:27.000Z t:fiscal_year="1977 - 1978" m:number_of_motion_hearings_held=78
```

## Meta Commands

```ls
metric m:number_of_motion_hearings_held p:integer l:"Number of Motion Hearings Held" t:dataTypeName=number

entity e:c5n8-8cmk l:"Motions Hearings Held ( RSN 39976)" t:attribution="Labor and Industrial Relations Appeals Board" t:url=https://data.hawaii.gov/api/views/c5n8-8cmk

property e:c5n8-8cmk t:meta.view v:id=c5n8-8cmk v:averageRating=0 v:name="Motions Hearings Held ( RSN 39976)" v:attribution="Labor and Industrial Relations Appeals Board"

property e:c5n8-8cmk t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:c5n8-8cmk t:meta.view.owner v:id=r3in-7sfs v:profileImageUrlMedium=/api/users/r3in-7sfs/profile_images/THUMB v:profileImageUrlLarge=/api/users/r3in-7sfs/profile_images/LARGE v:screenName="Labor and Industrial Relations Appeals Board" v:profileImageUrlSmall=/api/users/r3in-7sfs/profile_images/TINY v:displayName="Labor and Industrial Relations Appeals Board"

property e:c5n8-8cmk t:meta.view.tableauthor v:id=r3in-7sfs v:profileImageUrlMedium=/api/users/r3in-7sfs/profile_images/THUMB v:profileImageUrlLarge=/api/users/r3in-7sfs/profile_images/LARGE v:screenName="Labor and Industrial Relations Appeals Board" v:profileImageUrlSmall=/api/users/r3in-7sfs/profile_images/TINY v:roleName=publisher v:displayName="Labor and Industrial Relations Appeals Board"
```

## Top Records

```ls
| :updated_at | fiscal_year | number_of_motion_hearings_held | 
| =========== | =========== | ============================== | 
| 1345720647  | 1975 - 1976 | 82                             | 
| 1345720647  | 1976 - 1977 | 84                             | 
| 1345720647  | 1977 - 1978 | 78                             | 
| 1345720647  | 1978 - 1979 | 137                            | 
| 1345720647  | 1979 - 1980 | 153                            | 
| 1345720647  | 1980 - 1981 | 181                            | 
| 1345720647  | 1981 - 1982 | 231                            | 
| 1345720647  | 1982 - 1983 | 220                            | 
| 1345720647  | 1983 - 1984 | 277                            | 
| 1345720647  | 1984 - 1985 | 232                            | 
```