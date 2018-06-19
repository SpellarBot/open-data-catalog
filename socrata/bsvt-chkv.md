# Building and Safety Customer Service Request

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-and-safety-customer-service-request-9303a) |
| Metadata | [Link](https://data.lacity.org/api/views/bsvt-chkv) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/bsvt-chkv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/bsvt-chkv/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | bsvt-chkv |
| Name | Building and Safety Customer Service Request |
| Attribution | LADBS |
| Category | A Prosperous City |
| Tags | ladbs, department of building and safety, building and safety, building, safety, construction, customer service request, case number, customer service, csr, csr number |
| Created | 2014-03-18T21:23:28Z |
| Publication Date | 2017-01-04T19:52:42Z |

## Description

A Customer Service Request is a request received by the Department of Building and Safety from the City's constituents to investigate a site/property for a possible violation of the City's building, electrical, mechanical and zoning regulations, which are elements of the Los Angeles Municipal Code. Any investigative action taken by a Building and Safety inspector constitutes the opening of a case. Where no Code violation is found, the case is immediately closed.  If a Code violation is found, the case remains open until the site/property satisfies the requirements for Code compliance.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                              | Data Type     | Render Type   |
| ======== | ============== | ==================================== | ================================= | ============= | ============= |
| Yes      | series tag     | csr_number                           | CSR Number                        | text          | number        |
| Yes      | series tag     | ladbs_inspection_district            | LADBS Inspection District         | text          | text          |
| No       |                | address_house_number                 | Address House Number              | text          | text          |
| No       |                | address_house_fraction_number        | Address House Fraction Number     | text          | text          |
| Yes      | series tag     | address_street_direction             | Address Street Direction          | text          | text          |
| Yes      | series tag     | address_street_name                  | Address Street Name               | text          | text          |
| Yes      | series tag     | address_street_suffix                | Address Street Suffix             | text          | text          |
| Yes      | series tag     | address_street_suffix_direction      | Address Street Suffix Direction   | text          | text          |
| Yes      | series tag     | address_street_zip                   | Address Street Zip                | text          | text          |
| Yes      | time           | date_received                        | Date Received                     | calendar_date | calendar_date |
| No       |                | date_closed                          | Date Closed                       | calendar_date | calendar_date |
| No       |                | due_date                             | Due Date                          | calendar_date | calendar_date |
| Yes      | series tag     | case_flag                            | Case Flag                         | text          | text          |
| Yes      | series tag     | csr_priority                         | CSR Priority                      | text          | text          |
| Yes      | series tag     | gis_parcel_identification_number_pin | Parcel Identification Number(PIN) | text          | text          |
| Yes      | series tag     | csr_problem_type                     | CSR Problem Type                  | text          | text          |
| Yes      | series tag     | area_planning_commission_apc         | Area Planning Commission (APC)    | text          | text          |
| Yes      | series tag     | case_number_related_to_csr           | Case Number Related to CSR        | text          | text          |
| Yes      | numeric metric | response_days                        | Response Days                     | number        | number        |
| Yes      | series tag     | csr_case_number                      | CSR Number/Case Number            | text          | text          |
```

## Time Field

```ls
Value = date_received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_house_number,address_house_fraction_number,date_closed,due_date
```

## Data Commands

```ls
```

## Meta Commands

```ls
metric m:response_days p:long l:"Response Days" d:"The number of days from when a service request was received and when it was investigated." t:dataTypeName=number

entity e:bsvt-chkv l:"Building and Safety Customer Service Request" t:attribution=LADBS t:url=https://data.lacity.org/api/views/bsvt-chkv

property e:bsvt-chkv t:meta.view v:id=bsvt-chkv v:category="A Prosperous City" v:averageRating=0 v:name="Building and Safety Customer Service Request" v:attribution=LADBS

property e:bsvt-chkv t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:bsvt-chkv t:meta.view.owner v:id=tdwf-cih6 v:profileImageUrlMedium=/api/users/tdwf-cih6/profile_images/THUMB v:profileImageUrlLarge=/api/users/tdwf-cih6/profile_images/LARGE v:screenName="Building and Safety OpenData" v:profileImageUrlSmall=/api/users/tdwf-cih6/profile_images/TINY v:displayName="Building and Safety OpenData"

property e:bsvt-chkv t:meta.view.tableauthor v:id=tdwf-cih6 v:profileImageUrlMedium=/api/users/tdwf-cih6/profile_images/THUMB v:profileImageUrlLarge=/api/users/tdwf-cih6/profile_images/LARGE v:screenName="Building and Safety OpenData" v:profileImageUrlSmall=/api/users/tdwf-cih6/profile_images/TINY v:roleName=publisher v:displayName="Building and Safety OpenData"
```

## Top Records

```ls
| csr_number | ladbs_inspection_district | address_house_number | address_house_fraction_number | address_street_direction | address_street_name | address_street_suffix | address_street_suffix_direction | address_street_zip | date_received       | date_closed | due_date            | case_flag | csr_priority | gis_parcel_identification_number_pin | csr_problem_type                                                                        | area_planning_commission_apc | case_number_related_to_csr | response_days | csr_case_number | 
| ========== | ========================= | ==================== | ============================= | ======================== | =================== | ===================== | =============================== | ================== | =================== | =========== | =================== | ========= | ============ | ==================================== | ======================================================================================= | ============================ | ========================== | ============= | =============== | 
| 386024     | 2201                      | 2321                 |                               | N                        | ROSCOMARE           | ROAD                  |                                 | 90077              | 2016-11-20T00:00:00 |             | 2016-12-20T00:00:00 | N         | 3            | 153B145 80                           | ANY PROBLEMS THAT ONLY OCCUR FROM 5:00PM TO 7:00 AM (AT NIGHT) OR ON WEEKENDS           | West Los Angeles             |                            |               | 386024-386024   | 
| 379929     | 4102                      | 10071                |                               | N                        | WOODALE             | AVE                   |                                 | 91331              | 2016-08-15T00:00:00 |             | 2016-09-13T00:00:00 | N         | 2            | 204B153 699                          | ABANDONED OR VACANT BUILDING LEFT OPEN TO THE PUBLIC                                    | North Valley                 |                            |               | 379929-379929   | 
| 386073     | 1141                      | 9547                 |                               | S                        | COMPTON             | AVE                   |                                 | 90002              | 2016-11-21T00:00:00 |             | 2016-12-21T00:00:00 | N         | 3            | 093A213 192                          | BUILDINGS IN NEED OF GENERAL REPAIR                                                     | South Los Angeles            |                            |               | 386073-386073   | 
| 380267     | 4500                      | 7557                 |                               | N                        | WOODLEY             | AVE                   |                                 | 91406              | 2016-08-18T00:00:00 |             | 2016-09-16T00:00:00 | N         | 3            | 186B141 82                           | ISSUES REGARDING ADULT ENTERTAINMENT LOCATIONS (CLUBS, CABARETS, BOOK AND VIDEO STORES) | South Valley                 |                            |               | 380267-380267   | 
| 380304     | 3121                      | 11244                |                               | N                        | COMETA              | AVE                   |                                 | 91331              | 2016-08-19T00:00:00 |             | 2016-09-19T00:00:00 | N         | 2            | 210B165 161                          | BUILDING OR PROPERTY CONVERTED TO ANOTHER USE                                           | North Valley                 |                            |               | 380304-380304   | 
| 386142     | 2103                      | 252                  |                               | S                        | JUNE                | ST                    |                                 | 90004              | 2016-11-22T00:00:00 |             | 2016-12-22T00:00:00 | N         | 4            | 135B185 75                           | FENCES WALLS AND HEDGES THAT ARE TOO HIGH                                               | Central                      |                            |               | 386142-386142   | 
| 380406     | 3123                      | 14456                |                               | W                        | ASTORIA             | ST                    |                                 | 91342              | 2016-08-22T00:00:00 |             | 2016-09-20T00:00:00 | N         | 4            | 222B149 850                          | FENCES WALLS AND HEDGES THAT ARE TOO HIGH                                               | North Valley                 |                            |               | 380406-380406   | 
| 380481     | 3103                      | 7350                 |                               | N                        | JUMILLA             | AVE                   |                                 | 91306              | 2016-08-23T00:00:00 |             | 2016-09-21T00:00:00 | N         | 4            | 186B117 661                          | OVERGROWN OR EXCESSIVE VEGETATION                                                       | South Valley                 |                            |               | 380481-380481   | 
| 386203     | 2111                      | 1146                 |                               | S                        | HOLT                | AVE                   |                                 | 90035              | 2016-11-23T00:00:00 |             | 2016-12-23T00:00:00 | N         | 4            | 132B173 930                          | FENCES WALLS AND HEDGES THAT ARE TOO HIGH                                               | Central                      |                            |               | 386203-386203   | 
| 380714     | 3132                      | 10832                |                               | N                        | ENCINO              | AVE                   |                                 | 91344              | 2016-08-25T00:00:00 |             | 2016-09-23T00:00:00 | N         | 4            | 207B129 155                          | FENCES WALLS AND HEDGES THAT ARE TOO HIGH                                               | North Valley                 |                            |               | 380714-380714   | 
```