# 2013 Candidate Filing Key Dates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-candidate-filing-key-dates-e5f26) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/yjn5-rk7x) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/yjn5-rk7x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/yjn5-rk7x/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | yjn5-rk7x |
| Name | 2013 Candidate Filing Key Dates |
| Category | Election operations |
| Tags | elections |
| Created | 2013-03-09T01:25:29Z |
| Publication Date | 2013-03-09T01:25:59Z |

## Columns

```ls
| Included | Schema Type | Field Name | Name   | Data Type | Render Type |
| ======== | =========== | ========== | ====== | ========= | =========== |
| Yes      | time        | date       | Date   | text      | text        |
| Yes      | series tag  | time       | Time   | text      | text        |
| Yes      | series tag  | action     | Action | text      | text        |
```

## Time Field

```ls
Value = date
Format & Zone = EEEE, MMMM dd, yyyy
```

## Data Commands

```ls
series e:yjn5-rk7x d:2013-05-13T00:00:00.000Z t:time="9 a.m." t:action="Online candidate filing opens" m:row_number.yjn5-rk7x=1

series e:yjn5-rk7x d:2013-05-17T00:00:00.000Z t:time="4 p.m." t:action="Online candidate filing closes" m:row_number.yjn5-rk7x=2

series e:yjn5-rk7x d:2013-05-17T00:00:00.000Z t:time="4:30 p.m." t:action="Candidate filing closes" m:row_number.yjn5-rk7x=3
```

## Meta Commands

```ls
metric m:row_number.yjn5-rk7x p:long l:"Row Number"

entity e:yjn5-rk7x l:"2013 Candidate Filing  Key Dates" t:url=https://data.kingcounty.gov/api/views/yjn5-rk7x

property e:yjn5-rk7x t:meta.view v:id=yjn5-rk7x v:category="Election operations" v:averageRating=0 v:name="2013 Candidate Filing  Key Dates"

property e:yjn5-rk7x t:meta.view.license v:name="Public Domain"

property e:yjn5-rk7x t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:yjn5-rk7x t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| date                     | time      | action                                                                         | 
| ======================== | ========= | ============================================================================== | 
| Monday, May 13, 2013     | 9 a.m.    | Online candidate filing opens                                                  | 
| Friday, May 17, 2013     | 4 p.m.    | Online candidate filing closes                                                 | 
| Friday, May 17, 2013     | 4:30 p.m. | Candidate filing closes                                                        | 
| Monday, May 20, 2013     | 4:30 p.m. | Deadline to withdraw                                                           | 
| Wednesday, May 29, 2013  | 4:30 p.m. | Deadline to file local voters? pamphlet submission for the primary election    | 
| Friday, July 19, 2013    | 4:30 p.m. | Deadline to file as a write-in candidate for the primary election              | 
| Monday, July 22, 2013    | 8:30 a.m. | First day to submit local voters? pamphlet submission for the general election | 
| Friday, August 23, 2013  | 4:30 p.m. | Deadline to file local voter?s pamphlet submission for the general election    | 
| Friday, October 18, 2013 | 4:30 p.m. | Deadline to file as a write-in candidate for the general election              | 
```