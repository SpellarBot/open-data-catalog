# DWP Call Wait Time (minutes)%09

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dwp-call-wait-time-minutes09) |
| Metadata | [Link](https://data.lacity.org/api/views/9m5g-zgn4) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/9m5g-zgn4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/9m5g-zgn4/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 9m5g-zgn4 |
| Name | DWP Call Wait Time (minutes)%09 |
| Category | A Livable and Sustainable City |
| Created | 2015-11-02T22:27:56Z |
| Publication Date | 2015-11-02T22:29:47Z |

## Description

2015 Monthly Call Wait Time_LADWP Call Center

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | month       | Month      | text      | text        |
| Yes      | numeric metric | 2015        | 2015       | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:9m5g-zgn4 d:2015-11-02T14:27:58.000Z t:month=January m:2015=3.29

series e:9m5g-zgn4 d:2015-11-02T14:27:58.000Z t:month=February m:2015=5.95

series e:9m5g-zgn4 d:2015-11-02T14:27:58.000Z t:month=March m:2015=10.1
```

## Meta Commands

```ls
metric m:2015 p:float l:2015 t:dataTypeName=number

entity e:9m5g-zgn4 l:"DWP Call Wait Time (minutes)%09" t:url=https://data.lacity.org/api/views/9m5g-zgn4

property e:9m5g-zgn4 t:meta.view v:id=9m5g-zgn4 v:category="A Livable and Sustainable City" v:averageRating=0 v:name="DWP Call Wait Time (minutes)%09"

property e:9m5g-zgn4 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:9m5g-zgn4 t:meta.view.owner v:id=cyxz-kxfb v:profileImageUrlMedium=/api/users/cyxz-kxfb/profile_images/THUMB v:profileImageUrlLarge=/api/users/cyxz-kxfb/profile_images/LARGE v:screenName="Lilian Coral" v:profileImageUrlSmall=/api/users/cyxz-kxfb/profile_images/TINY v:displayName="Lilian Coral"

property e:9m5g-zgn4 t:meta.view.tableauthor v:id=cyxz-kxfb v:profileImageUrlMedium=/api/users/cyxz-kxfb/profile_images/THUMB v:profileImageUrlLarge=/api/users/cyxz-kxfb/profile_images/LARGE v:screenName="Lilian Coral" v:profileImageUrlSmall=/api/users/cyxz-kxfb/profile_images/TINY v:roleName=administrator v:displayName="Lilian Coral"
```

## Top Records

```ls
| :updated_at | month     | 2015 | 
| =========== | ========= | ==== | 
| 1446474478  | January   | 3.29 | 
| 1446474478  | February  | 5.95 | 
| 1446474478  | March     | 10.1 | 
| 1446474478  | April     | 8.53 | 
| 1446474478  | May       | 9.23 | 
| 1446474478  | June      | 8.81 | 
| 1446474478  | July      | 2.73 | 
| 1446474478  | August    | 2.3  | 
| 1446474478  | September | 1.82 | 
```