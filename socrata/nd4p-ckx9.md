# FOIA Request Log - Fleet & Facility Management

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-fleet-facility-management-0489e) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/nd4p-ckx9) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/nd4p-ckx9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/nd4p-ckx9/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | nd4p-ckx9 |
| Name | FOIA Request Log - Fleet & Facility Management |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2012-01-08T20:49:59Z |
| Publication Date | 2017-02-15T20:14:56Z |

## Description

FOIA requests received by the Department of Fleet & Facility Management since January 1, 2012.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | =========== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag  | requestor_name         | REQUESTOR NAME         | text          | text          |
| Yes      | series tag  | organization           | ORGANIZATION           | text          | text          |
| Yes      | series tag  | description_of_request | DESCRIPTION OF REQUEST | text          | text          |
| Yes      | time        | date_received          | DATE RECEIVED          | calendar_date | calendar_date |
| No       |             | due_date               | DUE DATE               | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = due_date
```

## Data Commands

```ls
series e:nd4p-ckx9 d:2012-01-18T00:00:00.000Z t:description_of_request="Copies of work orders for vehicles at E.C. 110" t:organization="NBC5 - Chicago" t:requestor_name="Mike Chamernik" m:row_number.nd4p-ckx9=1

series e:nd4p-ckx9 d:2012-01-18T00:00:00.000Z t:description_of_request="Copies of contracts for a listing of companies" t:organization="Better Government Association" t:requestor_name="Bob Herguth" m:row_number.nd4p-ckx9=2

series e:nd4p-ckx9 d:2012-01-26T00:00:00.000Z t:description_of_request="Utility Data" t:organization=Student t:requestor_name="Autumn Spensieri" m:row_number.nd4p-ckx9=3
```

## Meta Commands

```ls
metric m:row_number.nd4p-ckx9 p:long l:"Row Number"

entity e:nd4p-ckx9 l:"FOIA Request Log - Fleet & Facility Management" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/nd4p-ckx9

property e:nd4p-ckx9 t:meta.view v:id=nd4p-ckx9 v:category=FOIA v:attributionLink=http://www.cityofchicago.org/content/city/en/depts/dgs/supp_info/dgs_foia.html v:averageRating=0 v:name="FOIA Request Log - Fleet & Facility Management" v:attribution="City of Chicago"

property e:nd4p-ckx9 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:nd4p-ckx9 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name    | organization                  | description_of_request                         | date_received       | due_date            | 
| ================= | ============================= | ============================================== | =================== | =================== | 
| Mike Chamernik    | NBC5 - Chicago                | Copies of work orders for vehicles at E.C. 110 | 2012-01-18T00:00:00 | 2012-01-25T00:00:00 | 
| Bob Herguth       | Better Government Association | Copies of contracts for a listing of companies | 2012-01-18T00:00:00 | 2012-01-25T00:00:00 | 
| Autumn Spensieri  | Student                       | Utility Data                                   | 2012-01-26T00:00:00 | 2012-02-02T00:00:00 | 
| Dane Placko       | FOX News                      | Rental Trucks and Mileage                      | 2012-01-26T00:00:00 | 2012-02-02T00:00:00 | 
| Patrick Rehkamp   | Better Government Association | GPS Units in City Vehicles                     | 2012-01-27T00:00:00 | 2012-02-03T00:00:00 | 
| Olga Toropova     | Gaia Tech                     | Environmental Records                          | 2012-01-30T00:00:00 | 2012-02-06T00:00:00 | 
| Caitlin Ford      | Environmental Design          | Environmental Records                          | 2012-02-03T00:00:00 | 2012-02-10T00:00:00 | 
| Alpana Chaudhary  | Environmental Design          | Environmental Records                          | 2012-02-06T00:00:00 | 2012-02-13T00:00:00 | 
| Thomas C. Hallock | Cabrini Green Legal Aid       | Security Footage from Kelly Library            | 2012-03-19T00:00:00 | 2012-03-26T00:00:00 | 
| Alpana Chaudhary  | Environmental Design          | Environmental Records                          | 2012-03-23T00:00:00 | 2012-03-30T00:00:00 | 
```