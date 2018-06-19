# Profile Pictures for Hawaii State and County Candidates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/profile-pictures-for-hawaii-state-and-county-candidates-2992b) |
| Metadata | [Link](https://data.hawaii.gov/api/views/ataf-eya8) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/ataf-eya8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/ataf-eya8/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | ataf-eya8 |
| Name | Profile Pictures for Hawaii State and County Candidates |
| Created | 2013-11-14T18:10:16Z |
| Publication Date | 2013-11-20T22:45:32Z |

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | reg_no         | Reg No         | text      | text        |
| Yes      | series tag  | candidate_name | Candidate Name | text      | text        |
| Yes      | series tag  | pic            | Pic            | photo     | photo       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ataf-eya8 d:2013-11-14T10:10:22.000Z t:candidate_name="Abe, Michael" t:reg_no=CC10496 m:row_number.ataf-eya8=1

series e:ataf-eya8 d:2013-11-14T10:10:22.000Z t:candidate_name="Abinsay, Felipe (Jun)" t:reg_no=CC10211 m:row_number.ataf-eya8=2

series e:ataf-eya8 d:2013-11-14T10:10:22.000Z t:candidate_name="Able, Johnathan" t:reg_no=CC10757 m:row_number.ataf-eya8=3
```

## Meta Commands

```ls
metric m:row_number.ataf-eya8 p:long l:"Row Number"

entity e:ataf-eya8 l:"Profile Pictures for Hawaii State and County Candidates" t:url=https://data.hawaii.gov/api/views/ataf-eya8

property e:ataf-eya8 t:meta.view v:id=ataf-eya8 v:averageRating=0 v:name="Profile Pictures for Hawaii State and County Candidates"

property e:ataf-eya8 t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:ataf-eya8 t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| :updated_at | reg_no  | candidate_name        | pic | 
| =========== | ======= | ===================== | === | 
| 1384423822  | CC10496 | Abe, Michael          |     | 
| 1384423822  | CC10211 | Abinsay, Felipe (Jun) |     | 
| 1384423822  | CC10757 | Able, Johnathan       |     | 
| 1384423822  | CC10499 | Agor, Ron             |     | 
| 1384423822  | CC10314 | Agor, Ron             |     | 
| 1384423822  | CC10432 | Ahu Isa, Lei          |     | 
| 1384423822  | CC10864 | Ahu-Isa, Lei          |     | 
| 1384423822  | CC10215 | Aila, William         |     | 
| 1384423822  | CC10434 | Aiona, Darrow         |     | 
| 1384423822  | CC10162 | Aiona, James (Duke)   |     | 
```