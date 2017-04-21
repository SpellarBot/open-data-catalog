# FOIA Request Log - Fleet Management - Historical

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-fleet-management-16c03) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ten5-q8vs) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ten5-q8vs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ten5-q8vs/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ten5-q8vs |
| Name | FOIA Request Log - Fleet Management - Historical |
| Attribution | City of Chicago |
| Category | FOIA |
| Tags | historical |
| Created | 2010-04-16T17:40:35Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

FOIA requests received by Fleet Management from May 1, 2010-December 31, 2011. For requests made after January 1, 2012, please see Fleet & Facility Management FOIA Request Log at https://data.cityofchicago.org/FOIA/FOIA-Request-Log-Fleet-Facility-Management/nd4p-ckx9

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | =========== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag  | requestor_name         | REQUESTOR NAME         | text          | text          |
| Yes      | series tag  | organization           | ORGANIZATION           | text          | text          |
| Yes      | series tag  | description_of_request | DESCRIPTION OF REQUEST | text          | text          |
| Yes      | time        | date_requested         | DATE REQUESTED         | calendar_date | calendar_date |
| No       |             | due_date               | DUE DATE               | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_requested
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = due_date
```

## Data Commands

```ls
series e:ten5-q8vs d:2010-05-06T00:00:00.000Z t:description_of_request="Number of list parking patrol vehicles in use or operated by City, number of vehicles used by City, number of electric vehicles operated by City, initiative for replacing vehicles with electric vehicles" t:organization="Korea Trade Center Chicago" t:requestor_name="Sangjun Park" m:row_number.ten5-q8vs=1

series e:ten5-q8vs d:2010-05-11T00:00:00.000Z t:description_of_request="Any and all vehicle title records for any and all vehicles rented/leased/owned by the City of Chicago and Any and all vehicle inventory records of any and all vehicles owned by the City of Chicago along with maintenance records." t:requestor_name="Don Vance" m:row_number.ten5-q8vs=2

series e:ten5-q8vs d:2010-05-12T00:00:00.000Z t:description_of_request="Complete list of SCLP participants including title and department, SCLP policy or written rules, complete list of cars leased thru program and breakdown of payments City verses individual." t:organization="Fox Chicago" t:requestor_name="Dane Placko" m:row_number.ten5-q8vs=3
```

## Meta Commands

```ls
metric m:row_number.ten5-q8vs p:long l:"Row Number"

entity e:ten5-q8vs l:"FOIA Request Log - Fleet Management - Historical" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/ten5-q8vs

property e:ten5-q8vs t:meta.view v:id=ten5-q8vs v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Fleet Management - Historical" v:attribution="City of Chicago"

property e:ten5-q8vs t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:ten5-q8vs t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name | organization                                   | description_of_request                                                                                                                                                                                                                          | date_requested      | due_date            | 
| ============== | ============================================== | =============================================================================================================================================================================================================================================== | =================== | =================== | 
| Sangjun Park   | Korea Trade Center Chicago                     | Number of list parking patrol vehicles in use or operated by City, number of vehicles used by City, number of electric vehicles operated by City, initiative for replacing vehicles with electric vehicles                                      | 2010-05-06T00:00:00 | 2010-05-13T00:00:00 | 
| Don Vance      |                                                | Any and all vehicle title records for any and all vehicles rented/leased/owned by the City of Chicago and Any and all vehicle inventory records of any and all vehicles owned by the City of Chicago along with maintenance records.            | 2010-05-11T00:00:00 | 2010-05-18T00:00:00 | 
| Dane Placko    | Fox Chicago                                    | Complete list of SCLP participants including title and department, SCLP policy or written rules, complete list of cars leased thru program and breakdown of payments City verses individual.                                                    | 2010-05-12T00:00:00 | 2010-05-19T00:00:00 | 
| Kevin Naro     | Ford Motor Company                             | Most current parts pricing and quantity purchased information for NAPA or other Non Ford Non Motorcraft parts installed on Ford Motor Company Model vehicles in cities fleet. The purpose is to sell the City Ford brand non aftermarket parts. | 2010-05-21T00:00:00 | 2010-06-22T00:00:00 | 
| Robyn Kenney   | US EPA Climate Protection Partnership Division | Vehicles owned by City of Chicago: 1) type of vehicle, 2) type of fuel, 3) make, 4) model 5) year                                                                                                                                               | 2010-05-25T00:00:00 | 2010-06-02T00:00:00 | 
| Kevin Naro     | Ford Motor Company                             | Parts pricing and quantity purchased information for NAPA or other Non Ford Non Motorcraft parts installed on Ford Motor Company Model vehicles in cities fleet for the pers. The purpose is to sell the City Ford brand non aftermarket parts. | 2010-06-02T00:00:00 | 2010-07-01T00:00:00 | 
| Alan Nastali   |                                                | Copies of 10 invoice payment vouchers for payments made to Bus & Truck of Chicago related to Contract Number 17963.                                                                                                                             | 2010-06-08T00:00:00 | 2010-06-15T00:00:00 | 
| Ali Zaimi      | OER Services LLC                               | Payments to Casey Equipment that are tied to contract 8662 for the period 2005 to present.                                                                                                                                                      | 2010-06-10T00:00:00 | 2010-07-12T00:00:00 | 
| Ali Zaimi      | OER Services LLC                               | Payments to United Rentals Northwest Inc that are tied to contract 8666 for the period 2005 to present.                                                                                                                                         | 2010-06-10T00:00:00 | 2010-07-12T00:00:00 | 
| Ali Zaimi      | OER Services LLC                               | Payments to Steve's Equipment Service Inc that are tied to contract 8707 for the period 2005 to present.                                                                                                                                        | 2010-06-10T00:00:00 | 2010-07-12T00:00:00 | 
```