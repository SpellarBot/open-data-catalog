# Austin Pool Schedule

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pool-schedule2015) |
| Metadata | [Link](https://data.austintexas.gov/api/views/xaxa-886r) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/xaxa-886r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/xaxa-886r/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | xaxa-886r |
| Name | Austin Pool Schedule |
| Attribution | Parks Department |
| Category | Neighborhood |
| Tags | pools schedule summer |
| Created | 2015-06-15T18:33:28Z |
| Publication Date | 2017-01-09T20:41:57Z |

## Description

Listing of city pools and splash pads with schedule

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| Yes      | series tag  | pool_name       | Pool Name       | text          | text          |
| Yes      | series tag  | status          | Status          | text          | text          |
| Yes      | time        | open_date       | Open Date       | calendar_date | calendar_date |
| Yes      | series tag  | weekday         | Weekday         | text          | text          |
| Yes      | series tag  | weekend         | Weekend         | text          | text          |
| No       |             | close_date      | Close Date      | calendar_date | calendar_date |
| Yes      | series tag  | weekday_closure | Weekday Closure | text          | text          |
| Yes      | series tag  | pool_type       | Pool Type       | text          | text          |
| Yes      | series tag  | phone           | Phone           | text          | text          |
| Yes      | series tag  | website         | Website         | url           | url           |
```

## Time Field

```ls
Value = open_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = close_date
```

## Data Commands

```ls
series e:xaxa-886r d:2016-08-22T14:45:47.000Z t:phone=512-472-8546 t:weekday="8 am to 8 pm" t:website=http://www.austintexas.gov/department/deep-eddy-pool t:status=Open t:weekend="8 am to 8 pm" t:pool_name="Deep Eddy" t:pool_type=Municipal m:row_number.xaxa-886r=1

series e:xaxa-886r d:2016-06-06T08:00:00.000Z t:phone=512-974-9331 t:weekday="8 am - 8 pm" t:website=http://www.austintexas.gov/department/ramsey-pool t:status=Closed t:weekend="11 am - 8 pm" t:pool_name=Ramsey t:weekday_closure=Thursday t:pool_type=Neighborhood m:row_number.xaxa-886r=2

series e:xaxa-886r d:2016-06-03T12:00:00.000Z t:phone=512-974-9331 t:weekday="7 am - 8 pm" t:website=http://www.austintexas.gov/department/dick-nichols-pool t:status=Closed t:weekend="11 am - 8 pm" t:pool_name="Dick Nichols" t:weekday_closure=Monday t:pool_type=Neighborhood m:row_number.xaxa-886r=3
```

## Meta Commands

```ls
metric m:row_number.xaxa-886r p:long l:"Row Number"

entity e:xaxa-886r l:"Austin Pool Schedule" t:attribution="Parks Department" t:url=https://data.austintexas.gov/api/views/xaxa-886r

property e:xaxa-886r t:meta.view v:id=xaxa-886r v:category=Neighborhood v:averageRating=0 v:name="Austin Pool Schedule" v:attribution="Parks Department"

property e:xaxa-886r t:meta.view.owner v:id=rxw3-i2wi v:profileImageUrlMedium=/api/users/rxw3-i2wi/profile_images/THUMB v:profileImageUrlLarge=/api/users/rxw3-i2wi/profile_images/LARGE v:screenName=Michael v:profileImageUrlSmall=/api/users/rxw3-i2wi/profile_images/TINY v:displayName=Michael

property e:xaxa-886r t:meta.view.tableauthor v:id=rxw3-i2wi v:profileImageUrlMedium=/api/users/rxw3-i2wi/profile_images/THUMB v:profileImageUrlLarge=/api/users/rxw3-i2wi/profile_images/LARGE v:screenName=Michael v:profileImageUrlSmall=/api/users/rxw3-i2wi/profile_images/TINY v:roleName=publisher_stories v:displayName=Michael
```

## Top Records

```ls
| pool_name          | status | open_date           | weekday      | weekend      | close_date          | weekday_closure | pool_type    | phone        | website                                                                        | 
| ================== | ====== | =================== | ============ | ============ | =================== | =============== | ============ | ============ | ============================================================================== | 
| Deep Eddy          | Open   |                     | 8 am to 8 pm | 8 am to 8 pm |                     |                 | Municipal    | 512-472-8546 | [http://www.austintexas.gov/department/deep-eddy-pool, null]                   | 
| Ramsey             | Closed | 2016-06-06T08:00:00 | 8 am - 8 pm  | 11 am - 8 pm | 2016-08-21T00:00:00 | Thursday        | Neighborhood | 512-974-9331 | [http://www.austintexas.gov/department/ramsey-pool, null]                      | 
| Dick Nichols       | Closed | 2016-06-03T12:00:00 | 7 am - 8 pm  | 11 am - 8 pm | 2016-08-20T20:00:00 | Monday          | Neighborhood | 512-974-9331 | [http://www.austintexas.gov/department/dick-nichols-pool, Dick Nichols Pool]   | 
| Dove Springs       | Closed | 2016-06-26T11:00:00 | 8 am - 8 pm  | 11 am - 8 pm | 2016-08-20T20:00:00 | Thursday        | Neighborhood | 512-974-9331 | [http://www.austintexas.gov/department/dove-springs-pool, Dove Springs Pool]   | 
| Givens             | Closed | 2016-06-26T11:00:00 | 8 am - 8 pm  | 11 am - 8 pm | 2016-08-14T20:00:00 | Tuesday         | Neighborhood | 512-974-9331 | [http://www.austintexas.gov/department/givens-pool, Givens Pool]               | 
| Govalle            | Closed | 2016-07-03T13:00:00 | 1 pm - 8 pm  | 1 pm - 8 pm  | 2016-08-14T20:00:00 | Tuesday         | Neighborhood | 512-974-9331 | [http://www.austintexas.gov/department/gillis-pool, Govalle Pool]              | 
| Metz               | Closed | 2016-06-13T13:00:00 | 1 pm - 8 pm  | 1 pm - 8 pm  | 2016-08-14T20:00:00 | Thursday        | Neighborhood | 512-974-9331 | [http://www.austintexas.gov/department/metz-pool, Metz Pool]                   | 
| Balcones           | Closed | 2016-06-03T12:00:00 | 8 am - 8 pm  | 11 am - 8pm  | 2016-08-21T00:00:00 | Monday          | Neighborhood | 512-974-9331 | [http://www.austintexas.gov/department/balcones-pool, null]                    | 
| Chestnut Splashpad | Closed | 2016-05-14T09:00:00 | 9 am - 8 pm  | 9 am - 8 pm  | 2016-09-25T20:00:00 |                 | Splashpad    | 512-974-9331 | [http://www.austintexas.gov/department/bailey-splash-pad, Chestnut Splash Pad] | 
| Lott Splashpad     | Closed | 2016-05-14T09:00:00 | 9 am - 8 pm  | 9 am - 8 pm  | 2016-09-25T20:00:00 |                 | Splashpad    | 512-974-9331 | [http://www.austintexas.gov/department/lott-splash-pad, Lott Splash Pad]       | 
```