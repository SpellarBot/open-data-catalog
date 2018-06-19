# LASAN: Solid Resources Abandoned Waste Collection Activity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lasan-solid-resources-abandoned-waste-collection-activity) |
| Metadata | [Link](https://data.lacity.org/api/views/97ra-aqza) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/97ra-aqza/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/97ra-aqza/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 97ra-aqza |
| Name | LASAN: Solid Resources Abandoned Waste Collection Activity |
| Attribution | LA Sanitation |
| Category | A Livable and Sustainable City |
| Tags | lasan, sanitation, solid resource, collections, trash, pickup, waste, abandoned waste, illegal dumping |
| Created | 2015-12-02T02:32:51Z |
| Publication Date | 2015-12-29T00:00:23Z |

## Description

LA Sanitation information on abandoned waste requests updated monthly. This includes requests for Illegal Dumping, Illegal Bulky, Illegal E-Waste, and Illegal Metal Household Appliance collections.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | =========== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag  | service_request_number | Service Request Number | text          | text          |
| Yes      | series tag  | service_request_type   | Service Request Type   | text          | text          |
| Yes      | series tag  | service_request_status | Service Request Status | text          | text          |
| Yes      | time        | creation_date          | Creation Date          | calendar_date | calendar_date |
| No       |             | scheduled_date         | Scheduled Date         | calendar_date | calendar_date |
| Yes      | series tag  | yard                   | Yard                   | text          | text          |
| Yes      | series tag  | council_district       | Council District       | text          | number        |
| No       |             | completion_date        | Completion Date        | calendar_date | calendar_date |
```

## Time Field

```ls
Value = creation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = scheduled_date,completion_date
```

## Data Commands

```ls
series e:97ra-aqza d:2015-11-01T13:05:00.000Z t:service_request_type="Bulky Items" t:yard=WV t:service_request_number=1-59483661 t:council_district=3 t:service_request_status=Closed m:row_number.97ra-aqza=1

series e:97ra-aqza d:2015-11-01T13:05:00.000Z t:service_request_type="Bulky Items" t:yard=SLA t:service_request_number=1-59481061 t:council_district=10 t:service_request_status=Closed m:row_number.97ra-aqza=2

series e:97ra-aqza d:2015-11-01T13:05:00.000Z t:service_request_type="Illegal Dumping Pickup" t:yard=SLA t:service_request_number=1-59481731 t:council_district=10 t:service_request_status=Closed m:row_number.97ra-aqza=3
```

## Meta Commands

```ls
metric m:row_number.97ra-aqza p:long l:"Row Number"

entity e:97ra-aqza l:"LASAN:  Solid Resources Abandoned Waste Collection Activity" t:attribution="LA Sanitation" t:url=https://data.lacity.org/api/views/97ra-aqza

property e:97ra-aqza t:meta.view v:id=97ra-aqza v:category="A Livable and Sustainable City" v:averageRating=0 v:name="LASAN:  Solid Resources Abandoned Waste Collection Activity" v:attribution="LA Sanitation"

property e:97ra-aqza t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:97ra-aqza t:meta.view.owner v:id=jwvk-b9mh v:profileImageUrlMedium=/api/users/jwvk-b9mh/profile_images/THUMB v:profileImageUrlLarge=/api/users/jwvk-b9mh/profile_images/LARGE v:screenName="Public Works: Sanitation OpenData" v:profileImageUrlSmall=/api/users/jwvk-b9mh/profile_images/TINY v:displayName="Public Works: Sanitation OpenData"

property e:97ra-aqza t:meta.view.tableauthor v:id=jwvk-b9mh v:profileImageUrlMedium=/api/users/jwvk-b9mh/profile_images/THUMB v:profileImageUrlLarge=/api/users/jwvk-b9mh/profile_images/LARGE v:screenName="Public Works: Sanitation OpenData" v:profileImageUrlSmall=/api/users/jwvk-b9mh/profile_images/TINY v:roleName=publisher v:displayName="Public Works: Sanitation OpenData"
```

## Top Records

```ls
| service_request_number | service_request_type   | service_request_status | creation_date       | scheduled_date      | yard | council_district | completion_date     | 
| ====================== | ====================== | ====================== | =================== | =================== | ==== | ================ | =================== | 
| 1-59483661             | Bulky Items            | Closed                 | 2015-11-01T13:05:00 | 2015-11-06T00:00:00 | WV   | 3                | 2015-11-06T14:00:00 | 
| 1-59481061             | Bulky Items            | Closed                 | 2015-11-01T13:05:00 | 2015-11-09T00:00:00 | SLA  | 10               | 2015-11-09T14:30:00 | 
| 1-59481731             | Illegal Dumping Pickup | Closed                 | 2015-11-01T13:05:00 | 2015-11-02T00:00:00 | SLA  | 10               | 2015-11-25T12:54:00 | 
| 1-59483711             | Bulky Items            | Closed                 | 2015-11-01T13:06:00 | 2015-11-05T00:00:00 | EV   | 2                | 2015-11-05T17:30:00 | 
| 1-59482131             | Illegal Dumping Pickup | Closed                 | 2015-11-01T13:23:00 | 2015-11-03T00:00:00 | HB   | 15               | 2015-11-03T14:30:00 | 
| 1-59486201             | Bulky Items            | Closed                 | 2015-11-01T13:24:00 | 2015-11-04T00:00:00 | NC   | 1                | 2015-11-03T17:23:00 | 
| 1-59484801             | Bulky Items            | Closed                 | 2015-11-01T13:38:00 | 2015-11-05T00:00:00 | NC   | 4                | 2015-11-05T14:30:00 | 
| 1-59487401             | Bulky Items            | Closed                 | 2015-11-01T13:38:00 | 2015-11-02T00:00:00 | WLA  | 11               | 2015-11-02T14:00:00 | 
| 1-59486541             | Bulky Items            | Closed                 | 2015-11-01T13:40:00 | 2015-11-02T00:00:00 | WLA  | 11               | 2015-11-02T16:30:00 | 
| 1-59485021             | Bulky Items            | Closed                 | 2015-11-01T13:43:00 | 2015-11-04T00:00:00 | WV   | 12               | 2015-11-04T14:00:00 | 
```