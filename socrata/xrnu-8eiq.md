# Park Features By PMAID

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/park-features-by-pmaid) |
| Metadata | [Link](https://data.seattle.gov/api/views/xrnu-8eiq) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/xrnu-8eiq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/xrnu-8eiq/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | xrnu-8eiq |
| Name | Park Features By PMAID |
| Category | Parks |
| Created | 2016-07-20T23:20:51Z |
| Publication Date | 2016-09-02T21:27:58Z |

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | service_layer_id | Service Layer ID | text      | number      |
| Yes      | series tag  | feature_desc     | feature desc     | text      | text        |
| Yes      | series tag  | pmaid            | PMAID            | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xrnu-8eiq d:2016-07-26T11:57:35.000Z t:pmaid=429 t:feature_desc="Adult Fitness Equipment" t:service_layer_id=0 m:row_number.xrnu-8eiq=1

series e:xrnu-8eiq d:2016-07-26T11:57:35.000Z t:pmaid=4243 t:feature_desc="Adult Fitness Equipment" t:service_layer_id=0 m:row_number.xrnu-8eiq=2

series e:xrnu-8eiq d:2016-07-26T11:57:35.000Z t:pmaid=4456 t:feature_desc="Adult Fitness Equipment" t:service_layer_id=0 m:row_number.xrnu-8eiq=3
```

## Meta Commands

```ls
metric m:row_number.xrnu-8eiq p:long l:"Row Number"

entity e:xrnu-8eiq l:"Park Features By PMAID" t:url=https://data.seattle.gov/api/views/xrnu-8eiq

property e:xrnu-8eiq t:meta.view v:id=xrnu-8eiq v:category=Parks v:averageRating=0 v:name="Park Features By PMAID"

property e:xrnu-8eiq t:meta.view.license v:name="Public Domain"

property e:xrnu-8eiq t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:xrnu-8eiq t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| :updated_at | service_layer_id | feature_desc            | pmaid | 
| =========== | ================ | ======================= | ===== | 
| 1469534255  | 0                | Adult Fitness Equipment | 429   | 
| 1469534255  | 0                | Adult Fitness Equipment | 4243  | 
| 1469534255  | 0                | Adult Fitness Equipment | 4456  | 
| 1469534255  | 0                | Adult Fitness Equipment | 435   | 
| 1469534255  | 0                | Adult Fitness Equipment | 4450  | 
| 1469534255  | 34               | Art in the Park         | 447   | 
| 1469534255  | 34               | Art in the Park         | 264   | 
| 1469534255  | 34               | Art in the Park         | 320   | 
| 1469534255  | 34               | Art in the Park         | 3102  | 
| 1469534255  | 34               | Art in the Park         | 4029  | 
```