# Chicago Park District: Movies in the Parks 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/chicago-park-district-movies-in-the-parks-2016) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/6t9t-2gbi) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/6t9t-2gbi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/6t9t-2gbi/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 6t9t-2gbi |
| Name | Chicago Park District: Movies in the Parks 2016 |
| Attribution | Chicago Park District |
| Category | Parks & Recreation |
| Tags | movies |
| Created | 2016-06-17T21:16:18Z |
| Publication Date | 2016-06-17T21:18:41Z |

## Description

List of all Movies in the Parks events. This list is a one-time upload and cancellations will not be updated. Please visit the Chicago Park District website or call the Movies in the Parks hotline at 312-742-1134 to check for cancellations due to weather.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type     | Render Type   |
| ======== | =========== | ================== | ================== | ============= | ============= |
| Yes      | series tag  | eventname          | EventName          | text          | text          |
| Yes      | series tag  | moviename          | MovieName          | text          | text          |
| Yes      | series tag  | movieclosedcaption | MovieClosedCaption | text          | text          |
| Yes      | series tag  | movierating        | MovieRating        | text          | text          |
| Yes      | series tag  | location           | Location           | text          | text          |
| Yes      | series tag  | location_notes     | Location Notes     | text          | text          |
| No       |             | startdate          | StartDate          | calendar_date | calendar_date |
| No       |             | enddate            | EndDate            | calendar_date | calendar_date |
| Yes      | series tag  | zipcode            | Zipcode            | text          | text          |
| Yes      | series tag  | phone              | Phone              | text          | text          |
| Yes      | series tag  | contactname        | ContactName        | text          | text          |
| Yes      | series tag  | contactemail       | ContactEmail       | email         | email         |
| Yes      | series tag  | eventurl           | EventUrl           | url           | url           |
| Yes      | series tag  | parkurl            | ParkUrl            | url           | url           |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = startdate,enddate
```

## Data Commands

```ls
series e:6t9t-2gbi d:2016-01-01T00:00:00.000Z t:phone="(773) 256-1248" t:location_notes=NULL t:moviename="Lee Daniels' The Butler" t:contactname="Janie M. Collins" t:location="Washington Park" t:zipcode=60637 t:contactemail=janie.collins@chicagoparkdistrict.com t:movierating=PG-13 t:eventname="Movie at the DuSable Museum" t:movieclosedcaption=N/A m:row_number.6t9t-2gbi=1

series e:6t9t-2gbi d:2016-01-01T00:00:00.000Z t:phone="(312) 747-6022" t:location_notes=NULL t:moviename="War Room" t:contactname="Cheryl Alli" t:location="Bradley Park" t:zipcode=60617 t:contactemail=cheryl.alli@chicagoparkdistrict.com t:movierating=PG t:eventname="Movies in the Parks at Bradley" t:movieclosedcaption=Yes m:row_number.6t9t-2gbi=2

series e:6t9t-2gbi d:2016-01-01T00:00:00.000Z t:phone="(312) 745-2470" t:location_notes=NULL t:moviename=Zootopia t:contactname="Rick Shaheen" t:location="Midway Plaisance Park" t:zipcode=60637 t:contactemail=Rick.Shaheen@chicagoparkdistrict.com t:movierating=PG t:eventname="Midweek on the Midway at Midway Plaisance" t:movieclosedcaption=N/A m:row_number.6t9t-2gbi=3
```

## Meta Commands

```ls
metric m:row_number.6t9t-2gbi p:long l:"Row Number"

entity e:6t9t-2gbi l:"Chicago Park District: Movies in the Parks 2016" t:attribution="Chicago Park District" t:url=https://data.cityofchicago.org/api/views/6t9t-2gbi

property e:6t9t-2gbi t:meta.view v:id=6t9t-2gbi v:category="Parks & Recreation" v:attributionLink=http://www.chicagoparkdistrict.com/events/movies v:averageRating=0 v:name="Chicago Park District: Movies in the Parks 2016" v:attribution="Chicago Park District"

property e:6t9t-2gbi t:meta.view.owner v:id=48zk-zxis v:profileImageUrlMedium=/api/users/48zk-zxis/profile_images/THUMB v:profileImageUrlLarge=/api/users/48zk-zxis/profile_images/LARGE v:screenName="CPD IT" v:profileImageUrlSmall=/api/users/48zk-zxis/profile_images/TINY v:displayName="CPD IT"

property e:6t9t-2gbi t:meta.view.tableauthor v:id=48zk-zxis v:profileImageUrlMedium=/api/users/48zk-zxis/profile_images/THUMB v:profileImageUrlLarge=/api/users/48zk-zxis/profile_images/LARGE v:screenName="CPD IT" v:profileImageUrlSmall=/api/users/48zk-zxis/profile_images/TINY v:roleName=editor v:displayName="CPD IT"
```

## Top Records

```ls
| eventname                                 | moviename               | movieclosedcaption | movierating | location              | location_notes                                                   | startdate | enddate | zipcode | phone          | contactname                      | contactemail                           | eventurl     | parkurl      | 
| ========================================= | ======================= | ================== | =========== | ===================== | ================================================================ | ========= | ======= | ======= | ============== | ================================ | ====================================== | ============ | ============ | 
| Movie at the DuSable Museum               | Lee Daniels' The Butler | N/A                | PG-13       | Washington Park       | NULL                                                             |           |         | 60637   | (773) 256-1248 | Janie M. Collins                 | janie.collins@chicagoparkdistrict.com  | [null, null] | [null, null] | 
| Movies in the Parks at Bradley            | War Room                | Yes                | PG          | Bradley Park          | NULL                                                             |           |         | 60617   | (312) 747-6022 | Cheryl Alli                      | cheryl.alli@chicagoparkdistrict.com    | [null, null] | [null, null] | 
| Midweek on the Midway at Midway Plaisance | Zootopia                | N/A                | PG          | Midway Plaisance Park | NULL                                                             |           |         | 60637   | (312) 745-2470 | Rick Shaheen                     | Rick.Shaheen@chicagoparkdistrict.com   | [null, null] | [null, null] | 
| Movies in the Parks at Park No. 540       | Pixels                  | Yes                | PG-13       | Park No. 540          | NULL                                                             |           |         | 60616   | NULL           | Sherry Overton (the Park at NTA) | sherry.overton@chicagoparkdistrict.com | [null, null] | [null, null] | 
| Midweek on the Midway at Midway Plaisance | Pan                     | N/A                | PG-13       | Midway Plaisance Park | NULL                                                             |           |         | 60637   | (312) 745-2470 | Rick Shaheen                     | Rick.Shaheen@chicagoparkdistrict.com   | [null, null] | [null, null] | 
| Midweek on the Midway at Midway Plaisance | Brave                   | N/A                | PG          | Midway Plaisance Park | NULL                                                             |           |         | 60637   | (312) 745-2470 | Rick Shaheen                     | Rick.Shaheen@chicagoparkdistrict.com   | [null, null] | [null, null] | 
| Midweek on the Midway at Midway Plaisance | Inside Out              | N/A                | PG          | Midway Plaisance Park | NULL                                                             |           |         | 60637   | (312) 745-2470 | Rick Shaheen                     | Rick.Shaheen@chicagoparkdistrict.com   | [null, null] | [null, null] | 
| Movies in the Parks at Osterman Beach     | Beach Blanket Bingo     | No                 | NR          | Kathy Osterman Beach  | Movie showing north of Bryn Mawr Ave., east of Lake Shore Drive. |           |         | 60660   | (312) 742-5121 | NULL                             |                                        | [null, null] | [null, null] | 
| Movie at the DuSable Museum               | Imagine That            | N/A                | PG          | Washington Park       | NULL                                                             |           |         | 60637   | (773) 256-1248 | Janie M. Collins                 | janie.collins@chicagoparkdistrict.com  | [null, null] | [null, null] | 
| Midweek on the Midway at Midway Plaisance | Dr. Seuss' The Lorax    | N/A                | PG          | Midway Plaisance Park | NULL                                                             |           |         | 60637   | (312) 745-2470 | Rick Shaheen                     | Rick.Shaheen@chicagoparkdistrict.com   | [null, null] | [null, null] | 
```