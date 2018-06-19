# Iowa Fleet Summary By Year, County And Vehicle Type

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iowa-fleet-summary-by-year-county-and-vehicle-type) |
| Metadata | [Link](https://data.iowa.gov/api/views/6rrx-2vwt) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/6rrx-2vwt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/6rrx-2vwt/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 6rrx-2vwt |
| Name | Iowa Fleet Summary By Year, County And Vehicle Type |
| Attribution | Iowa Department of Transportation, Motor Vehicle Division |
| Category | Transportation & Utilities |
| Tags | vehicle registrations, motor vehicles, trailers, trucks, automobiles |
| Created | 2014-12-08T16:23:38Z |
| Publication Date | 2017-01-10T17:52:22Z |

## Description

The dataset provides vehicle (both motor vehicle and trailer) registration numbers and annual fees by year, county and vehicle types.  Vehicle types include: Automobile, Bus, Moped, Motor Home - A, Motor Home - B, Motor Home - C, Motorcycle, Multi-purpose, Regular Trailer, Semi Trailer, Small Regular Trailer, Small Semi Trailer, Truck Tractor, Travel Trailer, Truck, Truck - Business Trade, and Truck - Weight and List.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| No       |                | year                | Year                | number        | number        |
| Yes      | time           | year_ending         | Year Ending         | calendar_date | calendar_date |
| Yes      | series tag     | county_name         | County Name         | text          | text          |
| Yes      | series tag     | county_fip          | County FIP          | text          | text          |
| Yes      | series tag     | feature_id          | Feature ID          | text          | text          |
| Yes      | series tag     | motor_vehicle       | Motor Vehicle       | text          | text          |
| Yes      | series tag     | vehicle_category    | Vehicle Category    | text          | text          |
| Yes      | series tag     | vehicle_type        | Vehicle Type        | text          | text          |
| Yes      | series tag     | tonnage             | Tonnage             | text          | text          |
| Yes      | numeric metric | registrations       | Registrations       | number        | number        |
| Yes      | numeric metric | annual_fee          | Annual Fee          | money         | money         |
| No       |                | primary_county_lat  | Primary County Lat  | number        | number        |
| No       |                | primary_county_long | Primary County Long | number        | number        |
```

## Time Field

```ls
Value = year_ending
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = primary_county_lat,primary_county_long,year
```

## Data Commands

```ls
series e:6rrx-2vwt d:2005-12-31T00:00:00.000Z t:vehicle_category=Trailer t:county_fip=19001 t:vehicle_type="Semi Trailer" t:feature_id=465190 t:motor_vehicle=No t:county_name=Adair m:registrations=599

series e:6rrx-2vwt d:2005-12-31T00:00:00.000Z t:vehicle_category=Trailer t:county_fip=19001 t:vehicle_type="Travel Trailer" t:feature_id=465190 t:motor_vehicle=No t:county_name=Adair m:registrations=292

series e:6rrx-2vwt d:2005-12-31T00:00:00.000Z t:vehicle_category=Trailer t:county_fip=19001 t:vehicle_type="Small Regular Trailer" t:feature_id=465190 t:motor_vehicle=No t:county_name=Adair m:registrations=915
```

## Meta Commands

```ls
metric m:registrations p:integer l:Registrations d:"Number of vehicle registrations" t:dataTypeName=number

metric m:annual_fee p:double l:"Annual Fee" d:"Annual fee associated with vehicle registrations" t:dataTypeName=money

entity e:6rrx-2vwt l:"Iowa Fleet Summary By Year, County And Vehicle Type" t:attribution="Iowa Department of Transportation, Motor Vehicle Division" t:url=https://data.iowa.gov/api/views/6rrx-2vwt

property e:6rrx-2vwt t:meta.view v:id=6rrx-2vwt v:category="Transportation & Utilities" v:averageRating=0 v:name="Iowa Fleet Summary By Year, County And Vehicle Type" v:attribution="Iowa Department of Transportation, Motor Vehicle Division"

property e:6rrx-2vwt t:meta.view.license v:name="Public Domain"

property e:6rrx-2vwt t:meta.view.owner v:id=qxrf-n5wa v:profileImageUrlMedium=/api/users/qxrf-n5wa/profile_images/THUMB v:profileImageUrlLarge=/api/users/qxrf-n5wa/profile_images/LARGE v:screenName="Iowa DOT" v:profileImageUrlSmall=/api/users/qxrf-n5wa/profile_images/TINY v:displayName="Iowa DOT"

property e:6rrx-2vwt t:meta.view.tableauthor v:id=765b-zyun v:profileImageUrlMedium=/api/users/765b-zyun/profile_images/THUMB v:profileImageUrlLarge=/api/users/765b-zyun/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/765b-zyun/profile_images/TINY v:roleName=editor v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| year | year_ending         | county_name | county_fip | feature_id | motor_vehicle | vehicle_category | vehicle_type          | tonnage | registrations | annual_fee | primary_county_lat | primary_county_long | 
| ==== | =================== | =========== | ========== | ========== | ============= | ================ | ===================== | ======= | ============= | ========== | ================== | =================== | 
| 2005 | 2005-12-31T00:00:00 | Adair       | 19001      | 465190     | No            | Trailer          | Semi Trailer          |         | 599           |            | 41.3307464         | -94.4709413         | 
| 2005 | 2005-12-31T00:00:00 | Adair       | 19001      | 465190     | No            | Trailer          | Travel Trailer        |         | 292           |            | 41.3307464         | -94.4709413         | 
| 2005 | 2005-12-31T00:00:00 | Adair       | 19001      | 465190     | No            | Trailer          | Small Regular Trailer |         | 915           |            | 41.3307464         | -94.4709413         | 
| 2005 | 2005-12-31T00:00:00 | Adair       | 19001      | 465190     | No            | Trailer          | Regular Trailer       |         | 410           |            | 41.3307464         | -94.4709413         | 
| 2005 | 2005-12-31T00:00:00 | Adair       | 19001      | 465190     | No            | Trailer          | Small Semi Trailer    |         | 3             |            | 41.3307464         | -94.4709413         | 
| 2005 | 2005-12-31T00:00:00 | Adair       | 19001      | 465190     | Yes           | Truck            | Truck Tractor         |         | 122           |            | 41.3307464         | -94.4709413         | 
| 2005 | 2005-12-31T00:00:00 | Adair       | 19001      | 465190     | Yes           | Truck            | Truck                 |         | 4115          |            | 41.3307464         | -94.4709413         | 
| 2005 | 2005-12-31T00:00:00 | Adair       | 19001      | 465190     | Yes           | Automobile       | Automobile            |         | 4373          |            | 41.3307464         | -94.4709413         | 
| 2005 | 2005-12-31T00:00:00 | Adair       | 19001      | 465190     | Yes           | Motor Home       | Motor Home - A        |         | 41            |            | 41.3307464         | -94.4709413         | 
| 2005 | 2005-12-31T00:00:00 | Adair       | 19001      | 465190     | Yes           | Bus              | Bus                   |         | 2             |            | 41.3307464         | -94.4709413         | 
```