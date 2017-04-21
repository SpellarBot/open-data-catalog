# Municipal Building Gas Usage

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/municipal-building-gas-usage) |
| Metadata | [Link](https://data.lacity.org/api/views/s2f8-v3rp) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/s2f8-v3rp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/s2f8-v3rp/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | s2f8-v3rp |
| Name | Municipal Building Gas Usage |
| Category | A Livable and Sustainable City |
| Created | 2015-11-02T22:31:07Z |
| Publication Date | 2015-11-02T22:32:02Z |

## Description

2014 and 2015 Municipal Building Gas Usage

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
series e:s2f8-v3rp d:2015-11-02T14:31:09.000Z t:month=January m:2015=17360944

series e:s2f8-v3rp d:2015-11-02T14:31:09.000Z t:month=February m:2015=16495498

series e:s2f8-v3rp d:2015-11-02T14:31:09.000Z t:month=March m:2015=15658555
```

## Meta Commands

```ls
metric m:2014 p:integer l:2014 t:dataTypeName=number

metric m:2015 p:integer l:2015 t:dataTypeName=number

entity e:s2f8-v3rp l:"Municipal Building Gas Usage" t:url=https://data.lacity.org/api/views/s2f8-v3rp

property e:s2f8-v3rp t:meta.view v:id=s2f8-v3rp v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Municipal Building Gas Usage"

property e:s2f8-v3rp t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:s2f8-v3rp t:meta.view.owner v:id=cyxz-kxfb v:profileImageUrlMedium=/api/users/cyxz-kxfb/profile_images/THUMB v:profileImageUrlLarge=/api/users/cyxz-kxfb/profile_images/LARGE v:screenName="Lilian Coral" v:profileImageUrlSmall=/api/users/cyxz-kxfb/profile_images/TINY v:displayName="Lilian Coral"

property e:s2f8-v3rp t:meta.view.tableauthor v:id=cyxz-kxfb v:profileImageUrlMedium=/api/users/cyxz-kxfb/profile_images/THUMB v:profileImageUrlLarge=/api/users/cyxz-kxfb/profile_images/LARGE v:screenName="Lilian Coral" v:profileImageUrlSmall=/api/users/cyxz-kxfb/profile_images/TINY v:roleName=administrator v:displayName="Lilian Coral"
```

## Top Records

```ls
| :updated_at | month     | 2014     | 2015     | 
| =========== | ========= | ======== | ======== | 
| 1446474669  | January   |          | 17360944 | 
| 1446474669  | February  |          | 16495498 | 
| 1446474669  | March     |          | 15658555 | 
| 1446474669  | April     |          | 15110614 | 
| 1446474669  | May       |          | 15008692 | 
| 1446474669  | June      |          | 14781859 | 
| 1446474669  | July      | 19849111 | 14491004 | 
| 1446474669  | August    | 19665925 | 14230652 | 
| 1446474669  | September | 19569985 |          | 
| 1446474669  | October   | 19159966 |          | 
```