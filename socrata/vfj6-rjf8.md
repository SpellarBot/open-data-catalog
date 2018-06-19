# Municipal Building Water Usage

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/municipal-building-water-usage) |
| Metadata | [Link](https://data.lacity.org/api/views/vfj6-rjf8) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/vfj6-rjf8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/vfj6-rjf8/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | vfj6-rjf8 |
| Name | Municipal Building Water Usage |
| Category | A Livable and Sustainable City |
| Created | 2015-11-02T22:33:08Z |
| Publication Date | 2015-11-02T22:34:01Z |

## Description

2014 and 2015 Municipal Building Water Usage

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | month       | Month      | text      | text        |
| Yes      | numeric metric | 2014        | 2014       | number    | number      |
| Yes      | numeric metric | 2015        | 2015       | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:vfj6-rjf8 d:2015-11-02T14:33:11.000Z t:month=January m:2015=35698263

series e:vfj6-rjf8 d:2015-11-02T14:33:11.000Z t:month=February m:2015=34669957

series e:vfj6-rjf8 d:2015-11-02T14:33:11.000Z t:month=March m:2015=34368647
```

## Meta Commands

```ls
metric m:2014 p:integer l:2014 t:dataTypeName=number

metric m:2015 p:integer l:2015 t:dataTypeName=number

entity e:vfj6-rjf8 l:"Municipal Building Water Usage" t:url=https://data.lacity.org/api/views/vfj6-rjf8

property e:vfj6-rjf8 t:meta.view v:id=vfj6-rjf8 v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Municipal Building Water Usage"

property e:vfj6-rjf8 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:vfj6-rjf8 t:meta.view.owner v:id=cyxz-kxfb v:profileImageUrlMedium=/api/users/cyxz-kxfb/profile_images/THUMB v:profileImageUrlLarge=/api/users/cyxz-kxfb/profile_images/LARGE v:screenName="Lilian Coral" v:profileImageUrlSmall=/api/users/cyxz-kxfb/profile_images/TINY v:displayName="Lilian Coral"

property e:vfj6-rjf8 t:meta.view.tableauthor v:id=cyxz-kxfb v:profileImageUrlMedium=/api/users/cyxz-kxfb/profile_images/THUMB v:profileImageUrlLarge=/api/users/cyxz-kxfb/profile_images/LARGE v:screenName="Lilian Coral" v:profileImageUrlSmall=/api/users/cyxz-kxfb/profile_images/TINY v:roleName=administrator v:displayName="Lilian Coral"
```

## Top Records

```ls
| :updated_at | month     | 2014     | 2015     | 
| =========== | ========= | ======== | ======== | 
| 1446474791  | January   |          | 35698263 | 
| 1446474791  | February  |          | 34669957 | 
| 1446474791  | March     |          | 34368647 | 
| 1446474791  | April     |          | 33768090 | 
| 1446474791  | May       |          | 32824861 | 
| 1446474791  | June      | 38144910 | 31693987 | 
| 1446474791  | July      | 38864919 | 31013658 | 
| 1446474791  | August    | 39698252 | 30032687 | 
| 1446474791  | September | 39223534 |          | 
| 1446474791  | October   | 38425044 |          | 
```