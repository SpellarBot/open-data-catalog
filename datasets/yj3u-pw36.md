# Borough Enrollment Centers (Additional Ways To Graduate)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/borough-enrollment-centers-additional-ways-to-graduate-c06a8) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/yj3u-pw36) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/yj3u-pw36/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/yj3u-pw36/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | yj3u-pw36 |
| Name | Borough Enrollment Centers (Additional Ways To Graduate) |
| Attribution | Department of Education (DOE) |
| Category | Social Services |
| Tags | borough enrollment centers (additional ways to graduate), doe, education jobs and economic mobility |
| Created | 2013-03-19T20:52:20Z |
| Publication Date | 2013-03-19T20:55:03Z |

## Description

Listing of enrollment centers providing additional ways for High School graduation

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | location         | Location         | text      | text        |
| Yes      | series tag  | phone_number     | Phone Number     | text      | text        |
| Yes      | series tag  | districts_served | Districts Served | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:yj3u-pw36 d:2013-03-19T13:52:21.000Z t:phone_number=718-935-2178 t:location="1 Fordham Plaza, 7th floor" t:districts_served="7, 9, 10" m:row_number.yj3u-pw36=1

series e:yj3u-pw36 d:2013-03-19T13:52:21.000Z t:phone_number=718-935-2278 t:location="1230 Zerega Avenue" t:districts_served="8, 11, 12" m:row_number.yj3u-pw36=2

series e:yj3u-pw36 d:2013-03-19T13:52:21.000Z t:phone_number=718-935-2313 t:location="1790 Ocean Avenue, 3rd floor" t:districts_served="17, 18, 22" m:row_number.yj3u-pw36=3
```

## Meta Commands

```ls
metric m:row_number.yj3u-pw36 p:long l:"Row Number"

entity e:yj3u-pw36 l:"Borough Enrollment Centers (Additional Ways To Graduate)" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/yj3u-pw36

property e:yj3u-pw36 t:meta.view v:id=yj3u-pw36 v:category="Social Services" v:averageRating=0 v:name="Borough Enrollment Centers (Additional Ways To Graduate)" v:attribution="Department of Education (DOE)"

property e:yj3u-pw36 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:yj3u-pw36 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | location                     | phone_number | districts_served                    | 
| =========== | ============================ | ============ | =================================== | 
| 1363701141  | 1 Fordham Plaza, 7th floor   | 718-935-2178 | 7, 9, 10                            | 
| 1363701141  | 1230 Zerega Avenue           | 718-935-2278 | 8, 11, 12                           | 
| 1363701141  | 1790 Ocean Avenue, 3rd floor | 718-935-2313 | 17, 18, 22                          | 
| 1363701141  | 415 89th street              | 718-935-2331 | 20, 21                              | 
| 1363701141  | 1665 St. Mark's Avenue       | 718-935-2340 | 19, 23, 32                          | 
| 1363701141  | 29 Fort Greene Place         | 718-935-2371 | 13,14,15,16, General Education Only | 
| 1363701141  | 131 Livingston Street        | 718-935-4908 | 13,14,15,16, Special Education Only | 
| 1363701141  | 333 Seventh Avenue           | 718-935-2383 | 1, 2, 4                             | 
| 1363701141  | 388 West 125th street        | 718-935-2385 | 3, 5, 6                             | 
| 1363701141  | 28-11 Queens Plaza North     | 718-935-2386 | 24, 30                              | 
```