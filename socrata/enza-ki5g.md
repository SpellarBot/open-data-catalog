# Developers Test API

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/developers-test-api-e329c) |
| Metadata | [Link](https://data.oregon.gov/api/views/enza-ki5g) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/enza-ki5g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/enza-ki5g/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | enza-ki5g |
| Name | Developers Test API |
| Created | 2014-07-08T13:19:08Z |
| Publication Date | 2015-02-11T21:12:45Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | query       | query      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:enza-ki5g d:2015-02-11T13:12:45.000Z t:query=https://data.oregon.gov/resource/spxe-q5vj.json m:row_number.enza-ki5g=1
```

## Meta Commands

```ls
metric m:row_number.enza-ki5g p:long l:"Row Number"

entity e:enza-ki5g l:"Developers Test API" t:url=https://data.oregon.gov/api/views/enza-ki5g

property e:enza-ki5g t:meta.view v:id=enza-ki5g v:averageRating=0 v:name="Developers Test API"

property e:enza-ki5g t:meta.view.owner v:id=yr5y-ep82 v:profileImageUrlMedium=/api/users/yr5y-ep82/profile_images/THUMB v:profileImageUrlLarge=/api/users/yr5y-ep82/profile_images/LARGE v:screenName="Jason Rood" v:profileImageUrlSmall=/api/users/yr5y-ep82/profile_images/TINY v:displayName="Jason Rood"

property e:enza-ki5g t:meta.view.tableauthor v:id=yr5y-ep82 v:profileImageUrlMedium=/api/users/yr5y-ep82/profile_images/THUMB v:profileImageUrlLarge=/api/users/yr5y-ep82/profile_images/LARGE v:screenName="Jason Rood" v:profileImageUrlSmall=/api/users/yr5y-ep82/profile_images/TINY v:roleName=publisher v:displayName="Jason Rood"
```

## Top Records

```ls
| :updated_at | query                                           | 
| =========== | =============================================== | 
| 1423660365  | https://data.oregon.gov/resource/spxe-q5vj.json | 
```