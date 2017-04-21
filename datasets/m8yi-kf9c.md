# Illinois Guardianship and Advocacy Commision Percent Of Wards By Disability

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/illinois-guardianship-and-advocacy-commision-percent-of-wards-by-disability-03d3a) |
| Metadata | [Link](https://data.illinois.gov/api/views/m8yi-kf9c) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/m8yi-kf9c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/m8yi-kf9c/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | m8yi-kf9c |
| Name | Illinois Guardianship and Advocacy Commision Percent Of Wards By Disability |
| Category | Social/Healthcare |
| Tags | igac, disabilities, wards, caseload, guardian, guardianship |
| Created | 2013-02-05T19:50:55Z |
| Publication Date | 2013-02-07T20:12:46Z |

## Description

Breakdown of State of Illinois wards by type of disability.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | wards       | WARDS      | text      | text        |
| Yes      | series tag  | fy_08       | FY 08      | text      | text        |
| Yes      | series tag  | fy_09       | FY 09      | text      | text        |
| Yes      | series tag  | fy_10       | FY 10      | text      | text        |
| Yes      | series tag  | fy_11       | FY 11      | text      | text        |
| Yes      | series tag  | fy_12_tba   | FY 12 /TBA | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:m8yi-kf9c d:2013-02-05T11:50:56.000Z t:fy_09=74% t:fy_08=73% t:wards="PERSONS WITH INTELLECTUAL AND DEVELOPMENTAL DISABILITIES" t:fy_10=73% t:fy_11=72% t:fy_12_tba=71% m:row_number.m8yi-kf9c=1

series e:m8yi-kf9c d:2013-02-05T11:50:56.000Z t:fy_09=16% t:fy_08=17% t:wards="PERSONS WITH MENTAL ILLNESS" t:fy_10=16% t:fy_11=15% t:fy_12_tba=16% m:row_number.m8yi-kf9c=2

series e:m8yi-kf9c d:2013-02-05T11:50:56.000Z t:fy_09=8% t:fy_08=8% t:wards="PERSONS WITH AGE RELATED DISABILITIES" t:fy_10=9% t:fy_11=10% t:fy_12_tba=10% m:row_number.m8yi-kf9c=3
```

## Meta Commands

```ls
metric m:row_number.m8yi-kf9c p:long l:"Row Number"

entity e:m8yi-kf9c l:"Illinois Guardianship and Advocacy Commision Percent Of Wards By Disability" t:url=https://data.illinois.gov/api/views/m8yi-kf9c

property e:m8yi-kf9c t:meta.view v:id=m8yi-kf9c v:category=Social/Healthcare v:averageRating=0 v:name="Illinois Guardianship and Advocacy Commision Percent Of Wards By Disability"

property e:m8yi-kf9c t:meta.view.owner v:id=vtpq-vdyg v:screenName=rdixo4 v:displayName=rdixo4

property e:m8yi-kf9c t:meta.view.tableauthor v:id=vtpq-vdyg v:screenName=rdixo4 v:roleName=publisher v:displayName=rdixo4
```

## Top Records

```ls
| :updated_at | wards                                                    | fy_08 | fy_09 | fy_10 | fy_11 | fy_12_tba | 
| =========== | ======================================================== | ===== | ===== | ===== | ===== | ========= | 
| 1360065056  | PERSONS WITH INTELLECTUAL AND DEVELOPMENTAL DISABILITIES | 73%   | 74%   | 73%   | 72%   | 71%       | 
| 1360065056  | PERSONS WITH MENTAL ILLNESS                              | 17%   | 16%   | 16%   | 15%   | 16%       | 
| 1360065056  | PERSONS WITH AGE RELATED DISABILITIES                    | 8%    | 8%    | 9%    | 10%   | 10%       | 
| 1360065056  | PERSONS WITH PHYSICAL DISABILITIES                       | 2%    | 2%    | 2%    | 3%    | 3%        | 
```