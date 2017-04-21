# King County buildings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-buildings-4aa8f) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/53th-fexa) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/53th-fexa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/53th-fexa/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 53th-fexa |
| Name | King County buildings |
| Category | Operations |
| Tags | operations |
| Created | 2010-10-26T23:12:07Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

Address information and links to further information only.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | building    | Building   | text      | text        |
| Yes      | series tag  | street      | Street     | text      | text        |
| Yes      | series tag  | city        | City       | text      | text        |
| Yes      | series tag  | zip         | Zip        | text      | text        |
| Yes      | series tag  | link        | Link       | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:53th-fexa d:2010-10-28T11:11:30.000Z t:zip=98104 t:building=Courthouse t:link=http://www.kingcounty.gov/About/locations/Courthouse.aspx t:street="516 Third Ave." t:city=Seattle m:row_number.53th-fexa=1

series e:53th-fexa d:2010-10-28T11:11:38.000Z t:zip=98104 t:building="King Street Center" t:link=http://www.kingcounty.gov/About/locations/KingStreet.aspx t:street="201 S. Jackson St." t:city=Seattle m:row_number.53th-fexa=2

series e:53th-fexa d:2010-10-28T11:11:43.000Z t:zip=98032 t:building="Regional Justice Center" t:link=http://www.kingcounty.gov/About/locations/RJC.aspx t:street="401 Fourth Ave. N." t:city=Kent m:row_number.53th-fexa=3
```

## Meta Commands

```ls
metric m:row_number.53th-fexa p:long l:"Row Number"

entity e:53th-fexa l:"King County buildings" t:url=https://data.kingcounty.gov/api/views/53th-fexa

property e:53th-fexa t:meta.view v:id=53th-fexa v:category=Operations v:attributionLink=http://www.kingcounty.gov v:averageRating=0 v:name="King County buildings"

property e:53th-fexa t:meta.view.license v:name="Public Domain"

property e:53th-fexa t:meta.view.owner v:id=i2cs-ctba v:profileImageUrlMedium=/api/users/i2cs-ctba/profile_images/THUMB v:profileImageUrlLarge=/api/users/i2cs-ctba/profile_images/LARGE v:screenName=tombraman v:profileImageUrlSmall=/api/users/i2cs-ctba/profile_images/TINY v:displayName=tombraman

property e:53th-fexa t:meta.view.tableauthor v:id=i2cs-ctba v:profileImageUrlMedium=/api/users/i2cs-ctba/profile_images/THUMB v:profileImageUrlLarge=/api/users/i2cs-ctba/profile_images/LARGE v:screenName=tombraman v:profileImageUrlSmall=/api/users/i2cs-ctba/profile_images/TINY v:roleName=publisher v:displayName=tombraman
```

## Top Records

```ls
| :updated_at | building                | street             | city    | zip   | link                                                                  | 
| =========== | ======================= | ================== | ======= | ===== | ===================================================================== | 
| 1288264290  | Courthouse              | 516 Third Ave.     | Seattle | 98104 | [http://www.kingcounty.gov/About/locations/Courthouse.aspx, null]     | 
| 1288264298  | King Street Center      | 201 S. Jackson St. | Seattle | 98104 | [http://www.kingcounty.gov/About/locations/KingStreet.aspx, null]     | 
| 1288264303  | Regional Justice Center | 401 Fourth Ave. N. | Kent    | 98032 | [http://www.kingcounty.gov/About/locations/RJC.aspx, null]            | 
| 1311688647  | Administration          | 500 Fourth Ave.    | Seattle | 98104 | [http://www.kingcounty.gov/About/locations/Administration.aspx, null] | 
| 1311688649  | Chinook                 | 401 Fifth Ave.     | Seattle | 98104 | [http://www.kingcounty.gov/About/locations/Chinook.aspx, null]        | 
```