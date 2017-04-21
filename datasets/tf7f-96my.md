# King County cities that issue their own pet licenses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-cities-that-issue-their-own-pet-licenses-90a36) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/tf7f-96my) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/tf7f-96my/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/tf7f-96my/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | tf7f-96my |
| Name | King County cities that issue their own pet licenses |
| Attribution | King County |
| Category | Pets |
| Tags | pet pets animal license tag tags |
| Created | 2010-12-02T20:57:44Z |
| Publication Date | 2013-02-12T22:32:57Z |

## Description

The following cities issue their own pet licenses. Please contact them directly for pet license information if you live within their city limits.

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | city         | City         | text      | text        |
| Yes      | series tag  | phone_number | Phone Number | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:tf7f-96my d:2010-12-02T13:02:58.000Z t:phone_number=253-833-2897 t:city=Algona m:row_number.tf7f-96my=1

series e:tf7f-96my d:2010-12-02T13:02:58.000Z t:phone_number=206-241-4647 t:city=Burien m:row_number.tf7f-96my=2

series e:tf7f-96my d:2010-12-02T13:02:58.000Z t:phone_number=206-870-6549 t:city="Des Moines" m:row_number.tf7f-96my=3
```

## Meta Commands

```ls
metric m:row_number.tf7f-96my p:long l:"Row Number"

entity e:tf7f-96my l:"King County cities that issue their own pet licenses" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/tf7f-96my

property e:tf7f-96my t:meta.view v:id=tf7f-96my v:category=Pets v:attributionLink=http://www.kingcounty.gov/safety/regionalAnimalServices/ v:averageRating=0 v:name="King County cities that issue their own pet licenses" v:attribution="King County"

property e:tf7f-96my t:meta.view.license v:name="Public Domain"

property e:tf7f-96my t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:tf7f-96my t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| :updated_at | city          | phone_number | 
| =========== | ============= | ============ | 
| 1291294978  | Algona        | 253-833-2897 | 
| 1291294978  | Burien        | 206-241-4647 | 
| 1291294978  | Des Moines    | 206-870-6549 | 
| 1291294978  | Federal Way   | 253-835-2567 | 
| 1291294978  | Hunts Point   | 425-455-1834 | 
| 1291294978  | Medina        | 425-233-6400 | 
| 1291294978  | Milton        | 253-922-8733 | 
| 1291294978  | Normandy Park | 206-248-7600 | 
| 1291294978  | Pacific       | 253-833-2856 | 
| 1291294978  | Renton        | 425-430-6850 | 
```