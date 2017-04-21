# Food Pantry List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/food-pantry-list) |
| Metadata | [Link](https://data.mo.gov/api/views/eb3y-vtsa) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/eb3y-vtsa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/eb3y-vtsa/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | eb3y-vtsa |
| Name | Food Pantry List |
| Category | Social Services |
| Created | 2015-05-27T19:37:07Z |
| Publication Date | 2016-10-26T16:40:37Z |

## Columns

```ls
| Included | Schema Type | Field Name              | Name                     | Data Type | Render Type |
| ======== | =========== | ======================= | ======================== | ========= | =========== |
| No       | time        | :updated_at             | updated_at               | meta_data | meta_data   |
| Yes      | series tag  | agency_name             | Agency Name              | text      | text        |
| Yes      | series tag  | county                  | County                   | text      | text        |
| Yes      | series tag  | phone_number            | Phone Number             | text      | text        |
| Yes      | series tag  | hours_of_operation      | Hours of Operation       | text      | text        |
| No       |             | additional_address_info | Additional Address Info. | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = additional_address_info
```

## Data Commands

```ls
series e:eb3y-vtsa d:2015-11-06T11:14:16.000Z t:phone_number=417-993-4403 t:county=Dallas t:hours_of_operation="3RD T 2-7" t:agency_name="Prairie Chapel United Methodist" m:row_number.eb3y-vtsa=1

series e:eb3y-vtsa d:2015-11-06T11:25:06.000Z t:phone_number=417-466-7536 t:county=Lawrence t:hours_of_operation="3RD W 10-11 & PREVIOUS M 6-7" t:agency_name="St. Susanne Catholic Church" m:row_number.eb3y-vtsa=2

series e:eb3y-vtsa d:2015-11-06T11:28:09.000Z t:phone_number=417-967-4484 t:county=Texas t:hours_of_operation="T-F 10-2" t:agency_name="Texas County Food Pantry" m:row_number.eb3y-vtsa=3
```

## Meta Commands

```ls
metric m:row_number.eb3y-vtsa p:long l:"Row Number"

entity e:eb3y-vtsa l:"Food Pantry List" t:url=https://data.mo.gov/api/views/eb3y-vtsa

property e:eb3y-vtsa t:meta.view v:id=eb3y-vtsa v:category="Social Services" v:averageRating=0 v:name="Food Pantry List"

property e:eb3y-vtsa t:meta.view.owner v:id=jzbz-iqr6 v:screenName=Breanna v:lastNotificationSeenAt=1492723347 v:displayName=Breanna

property e:eb3y-vtsa t:meta.view.tableauthor v:id=jzbz-iqr6 v:screenName=Breanna v:roleName=administrator v:lastNotificationSeenAt=1492723347 v:displayName=Breanna
```

## Top Records

```ls
| :updated_at | agency_name                                | county     | phone_number | hours_of_operation                            | additional_address_info | 
| =========== | ========================================== | ========== | ============ | ============================================= | ======================= | 
| 1446808456  | Prairie Chapel United Methodist            | Dallas     | 417-993-4403 | 3RD T 2-7                                     |                         | 
| 1446809106  | St. Susanne Catholic Church                | Lawrence   | 417-466-7536 | 3RD W 10-11 & PREVIOUS M 6-7                  |                         | 
| 1446809289  | Texas County Food Pantry                   | Texas      | 417-967-4484 | T-F 10-2                                      |                         | 
| 1446809347  | Zalma General Baptist Food Pantry          | Bollinger  | 573-225-3615 | 2ND FRIDAY 5-7                                | Box 202                 | 
| 1446810333  | Pilgram Rest Missionary Baptist Church     | New Madrid | 573-421-4593 | 1ST SAT OF MONTH 9-11                         |                         | 
| 1446810534  | Friendship Ch. Of God In Christ            | New Madrid | 573-521-7150 | 2ND SAT OF MONTH 9-11                         |                         | 
| 1446810671  | Victory Christian Fellowship Fp            | Ripley     | 573-300-1158 | 4TH SAT 8-9                                   | Box 783,                | 
| 1446810837  | Stoddard Co Gospel Mission - Puxico Office | Stoddard   | 573-624-8979 | TUES 9-4                                      |                         | 
| 1446810889  | Wappapello Methodist Food Pantry           | Wayne      | 573-380-1350 | 2ND & 3RD TUES 9-12                           | 2 1/2 Mi N Of Dam       | 
| 1446808129  | Living Faith Church                        | Jefferson  | 636-937-4999 | 2ND WED: WINTER 9-12; 2ND THUR SUMMER 7-10 AM |                         | 
```