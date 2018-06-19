# 311 Call Center Tracking Data (Archived)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-call-center-tracking-data-39df4) |
| Metadata | [Link](https://data.lacity.org/api/views/ukiu-8trj) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/ukiu-8trj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/ukiu-8trj/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | ukiu-8trj |
| Name | 311 Call Center Tracking Data (Archived) |
| Category | A Well Run City |
| Tags | 311, call center, 3-1-1 |
| Created | 2014-05-29T19:00:35Z |
| Publication Date | 2015-06-10T15:43:46Z |

## Description

Basic 311 call tracking information including date and time of call, type of information requested, how the request was handled, and which departments were notified, from 2011-May 2016.

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | =========== | ======================= | ======================= | ============= | ============= |
| Yes      | time        | date                    | Date                    | calendar_date | calendar_date |
| Yes      | series tag  | time                    | Time                    | text          | text          |
| Yes      | series tag  | department_abbreviation | Department Abbreviation | text          | text          |
| Yes      | series tag  | department_name         | Department Name         | text          | text          |
| Yes      | series tag  | service_name            | Service Name            | text          | text          |
| Yes      | series tag  | call_resolution         | Call Resolution         | text          | text          |
| Yes      | series tag  | zip_code                | Zip Code                | text          | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:ukiu-8trj d:2014-01-01T00:00:00.000Z t:time=08:08:54 t:zip_code=91605 t:department_abbreviation=DOT t:service_name="Parking Enforcement" t:department_name="Department of Transportation" t:call_resolution="Transfer (City)" m:row_number.ukiu-8trj=1

series e:ukiu-8trj d:2014-01-01T00:00:00.000Z t:time=08:09:00 t:zip_code=90402 t:department_abbreviation=LAPD t:service_name="Police Stations (Front Desk / Public Counter - 25 locations)" t:department_name="Los Angeles Police Department" t:call_resolution="Gave Caller Information" m:row_number.ukiu-8trj=2

series e:ukiu-8trj d:2014-01-01T00:00:00.000Z t:time=08:09:34 t:zip_code=99999 t:department_abbreviation=DOT t:service_name="Meter Request Service" t:department_name="Department of Transportation" t:call_resolution="Gave Caller Information" m:row_number.ukiu-8trj=3
```

## Meta Commands

```ls
metric m:row_number.ukiu-8trj p:long l:"Row Number"

entity e:ukiu-8trj l:"311 Call Center Tracking Data (Archived)" t:url=https://data.lacity.org/api/views/ukiu-8trj

property e:ukiu-8trj t:meta.view v:id=ukiu-8trj v:category="A Well Run City" v:averageRating=0 v:name="311 Call Center Tracking Data (Archived)"

property e:ukiu-8trj t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:ukiu-8trj t:meta.view.owner v:id=yb4r-dcys v:profileImageUrlMedium=/api/users/yb4r-dcys/profile_images/THUMB v:profileImageUrlLarge=/api/users/yb4r-dcys/profile_images/LARGE v:screenName="ITA OpenData" v:profileImageUrlSmall=/api/users/yb4r-dcys/profile_images/TINY v:displayName="ITA OpenData"

property e:ukiu-8trj t:meta.view.tableauthor v:id=yb4r-dcys v:profileImageUrlMedium=/api/users/yb4r-dcys/profile_images/THUMB v:profileImageUrlLarge=/api/users/yb4r-dcys/profile_images/LARGE v:screenName="ITA OpenData" v:profileImageUrlSmall=/api/users/yb4r-dcys/profile_images/TINY v:roleName=publisher v:displayName="ITA OpenData"
```

## Top Records

```ls
| date                | time     | department_abbreviation | department_name               | service_name                                                 | call_resolution           | zip_code | 
| =================== | ======== | ======================= | ============================= | ============================================================ | ========================= | ======== | 
| 2014-01-01T00:00:00 | 08:08:54 | DOT                     | Department of Transportation  | Parking Enforcement                                          | Transfer (City)           | 91605    | 
| 2014-01-01T00:00:00 | 08:09:00 | LAPD                    | Los Angeles Police Department | Police Stations (Front Desk / Public Counter - 25 locations) | Gave Caller Information   | 90402    | 
| 2014-01-01T00:00:00 | 08:09:34 | DOT                     | Department of Transportation  | Meter Request Service                                        | Gave Caller Information   | 99999    | 
| 2014-01-01T00:00:00 | 08:10:11 | BOS                     | PW/Bureau of Sanitation       | Replacement/Repair of Curbside Trash Containers              | Gave Caller Information   | 90023    | 
| 2014-01-01T00:00:00 | 08:11:01 | BOS                     | PW/Bureau of Sanitation       | Bulky Item Pick-up                                           | Service Request Processed | 90044    | 
| 2014-01-01T00:00:00 | 08:11:07 | BSS                     | PW/Bureau of Street Services  | Maintenance of Public Street Landscape                       | Gave Caller Information   | 91605    | 
| 2014-01-01T00:00:00 | 08:11:25 | BPW                     | PW/Board of Public Works      | Graffiti Removal - Community Beautification                  | Service Request Processed | 90029    | 
| 2014-01-01T00:00:00 | 08:12:23 | BOS                     | PW/Bureau of Sanitation       | Bulky Item Pick-up                                           | Service Request Processed | 90019    | 
| 2014-01-01T00:00:00 | 08:12:36 | LAPD                    | Los Angeles Police Department | 877 ASK-LAPD - Non-emergency Police Service                  | Gave Caller Information   | 90004    | 
| 2014-01-01T00:00:00 | 08:13:56 | BSS                     | PW/Bureau of Street Services  | Street Use Permits                                           | Gave Caller Information   | 90042    | 
```