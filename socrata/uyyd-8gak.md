# Land Use Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/land-use-permits-c7757) |
| Metadata | [Link](https://data.seattle.gov/api/views/uyyd-8gak) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/uyyd-8gak/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/uyyd-8gak/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | uyyd-8gak |
| Name | Land Use Permits |
| Attribution | City of Seattle, Department of Planning and Development |
| Category | Permitting |
| Tags | dpd, permit, master use permit, plan review |
| Created | 2010-08-11T20:06:08Z |
| Publication Date | 2017-01-31T22:30:29Z |

## Description

Current and historical information on a variety of over the counter and plan review applications and permits that generally include a public comment process and do not authorize construction activities.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | ============== | =============================== | =============================== | ============= | ============= |
| Yes      | series tag     | application_permit_number       | Application/Permit Number       | text          | text          |
| Yes      | series tag     | permit_type                     | Permit Type                     | text          | text          |
| No       |                | address                         | Address                         | text          | text          |
| Yes      | series tag     | description                     | Description                     | text          | text          |
| Yes      | series tag     | category                        | Category                        | text          | text          |
| Yes      | series tag     | decision_type                   | Decision Type                   | text          | text          |
| Yes      | series tag     | dsgnrvw_required                | Design Review Included          | text          | text          |
| Yes      | numeric metric | value                           | Value                           | money         | money         |
| Yes      | series tag     | applicant_name                  | Applicant Name                  | text          | text          |
| Yes      | time           | application_date                | Application Date                | calendar_date | calendar_date |
| No       |                | decision_date                   | Decision Date                   | calendar_date | calendar_date |
| Yes      | series tag     | appealed_                       | Appealed?                       | text          | text          |
| No       |                | issue_date                      | Issue Date                      | calendar_date | calendar_date |
| Yes      | series tag     | status                          | Status                          | text          | text          |
| Yes      | series tag     | contractor                      | Contractor                      | text          | text          |
| Yes      | series tag     | permit_and_complaint_status_url | Permit and Complaint Status URL | url           | url           |
| No       |                | latitude                        | Latitude                        | number        | number        |
| No       |                | longitude                       | Longitude                       | number        | number        |
```

## Time Field

```ls
Value = application_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,decision_date,issue_date,latitude,longitude
```

## Data Commands

```ls
series e:uyyd-8gak d:2017-01-20T00:00:00.000Z t:permit_type="SEPA THRESHOLD DETERMINATION" t:category=MULTIFAMILY t:appealed_=N t:status="Application Accepted" t:description="Land Use Application to allow one 3-story, seven unit rowhouse structure in an environmentally critical area. Parking for 7 vehicles to be provided. Environmental review includes future unit lot subdivision." t:decision_type=II t:permit_and_complaint_status_url="http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=3026806" t:applicant_name="LEMONS, JONATHAN" t:application_permit_number=3026806 t:dsgnrvw_required=N m:value=1310620

series e:uyyd-8gak d:2017-01-18T00:00:00.000Z t:permit_type="SHORT PLAT" t:category="SINGLE FAMILY / DUPLEX" t:appealed_=N t:status="Application Accepted" t:description="Land Use Application to subdivide one parcel into two parcels of land. Proposed parcel sizes are: A) 3,825 sq. ft. and B) 3,825 sq. ft. Existing structure to be demolished." t:decision_type=II t:permit_and_complaint_status_url="http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=3026603" t:applicant_name="BIDDLE, DAVE" t:application_permit_number=3026603 t:dsgnrvw_required=N m:value=0

series e:uyyd-8gak d:2017-01-17T00:00:00.000Z t:permit_type="LOT BOUNDARY ADJUSTMENT PLAT" t:category="SINGLE FAMILY / DUPLEX" t:appealed_=N t:status="Application Accepted" t:description="Land Use application to adjust the boundary between two parcels of land. Proposed parcel sizes are: A) 4,051 sq. ft.; B) 2,382 sq. ft. Existing parcels to be demolished." t:decision_type=I t:permit_and_complaint_status_url="http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=3025620" t:applicant_name="WINTERS, BRANDON" t:application_permit_number=3025620 t:dsgnrvw_required=N m:value=0
```

## Meta Commands

```ls
metric m:value p:integer l:Value d:"The value of the work being reviewed (generally an estimate for the value of the future work) For example, the future construction cost of the building subject to Environmental review. Value is not collected for all permit types." t:dataTypeName=money

entity e:uyyd-8gak l:"Land Use Permits" t:attribution="City of Seattle, Department of Planning and Development" t:url=https://data.seattle.gov/api/views/uyyd-8gak

property e:uyyd-8gak t:meta.view v:id=uyyd-8gak v:category=Permitting v:attributionLink=http://www.seattle.gov/dpd v:averageRating=0 v:name="Land Use Permits" v:attribution="City of Seattle, Department of Planning and Development"

property e:uyyd-8gak t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:uyyd-8gak t:meta.view.owner v:id=nmed-fmz8 v:profileImageUrlMedium=/api/users/nmed-fmz8/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmed-fmz8/profile_images/LARGE v:screenName="Department of Planning and Development" v:profileImageUrlSmall=/api/users/nmed-fmz8/profile_images/TINY v:displayName="Department of Planning and Development"

property e:uyyd-8gak t:meta.view.tableauthor v:id=nmed-fmz8 v:profileImageUrlMedium=/api/users/nmed-fmz8/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmed-fmz8/profile_images/LARGE v:screenName="Department of Planning and Development" v:profileImageUrlSmall=/api/users/nmed-fmz8/profile_images/TINY v:roleName=publisher v:displayName="Department of Planning and Development"
```

## Top Records

```ls
| application_permit_number | permit_type                                          | address           | description                                                                                                                                                                                                                                                                              | category               | decision_type | dsgnrvw_required | value    | applicant_name   | application_date    | decision_date | appealed_ | issue_date | status               | contractor | permit_and_complaint_status_url                                          | latitude    | longitude     | 
| ========================= | ==================================================== | ================= | ======================================================================================================================================================================================================================================================================================== | ====================== | ============= | ================ | ======== | ================ | =================== | ============= | ========= | ========== | ==================== | ========== | ======================================================================== | =========== | ============= | 
| 3026806                   | SEPA THRESHOLD DETERMINATION                         | 2265 14TH AVE W   | Land Use Application to allow one 3-story, seven unit rowhouse structure in an environmentally critical area. Parking for 7 vehicles to be provided. Environmental review includes future unit lot subdivision.                                                                          | MULTIFAMILY            | II            | N                | 1310620  | LEMONS, JONATHAN | 2017-01-20T00:00:00 |               | N         |            | Application Accepted |            | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=3026806, null] | 47.64053203 | -122.37529384 | 
| 3026603                   | SHORT PLAT                                           | 516 N 82ND ST     | Land Use Application to subdivide one parcel into two parcels of land. Proposed parcel sizes are: A) 3,825 sq. ft. and B) 3,825 sq. ft. Existing structure to be demolished.                                                                                                             | SINGLE FAMILY / DUPLEX | II            | N                | 0        | BIDDLE, DAVE     | 2017-01-18T00:00:00 |               | N         |            | Application Accepted |            | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=3026603, null] | 47.68861379 | -122.35171529 | 
| 3025620                   | LOT BOUNDARY ADJUSTMENT PLAT                         | 3626 14TH AVE S   | Land Use application to adjust the boundary between two parcels of land. Proposed parcel sizes are: A) 4,051 sq. ft.; B) 2,382 sq. ft. Existing parcels to be demolished.                                                                                                                | SINGLE FAMILY / DUPLEX | I             | N                | 0        | WINTERS, BRANDON | 2017-01-17T00:00:00 |               | N         |            | Application Accepted |            | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=3025620, null] | 47.57070856 | -122.31452008 | 
| 3026706                   | SHORT PLAT                                           | 2467 S COLLEGE ST | Land Use Application to subdivide one parcel into four parcels of land. Proposed parcel sizes are: A) 1,178 sq. ft., B) 1,188 sq. ft., C) 1,190 sq. ft.; and D) 1,925 sq. ft.                                                                                                            | COMMERCIAL             | II            | N                | 0        | MCANDREWS, ANDY  | 2017-01-17T00:00:00 |               | N         |            | Application Accepted |            | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=3026706, null] | 47.58277721 | -122.30065926 | 
| 3026674                   | SEPA THRESHOLD DETERMINATION, SHORELINE DEVELOPMENT  | 1451 NW 46TH ST   | Shoreline Substantial Development to allow a one-story, 25,000 sq. ft. retail structure (grocery store) with parking for 144 vehicles at and below grade.                                                                                                                                | COMMERCIAL             | II            | N                | 3500000  | O'HARE, JON      | 2017-01-17T00:00:00 |               | N         |            | Application Accepted |            | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=3026674, null] | 47.66208073 | -122.37549231 | 
| 3026471                   | SEPA THRESHOLD DETERMINATION                         | 3855 21ST AVE SW  | Land Use Application to allow one, 2-story, eight unit rowhouse structure in an environmentally critical area. Surface parking for 4 vehicles to provided. Environmental review includes future unit lot subdivision.                                                                    | MULTIFAMILY            | II            | N                | 393000   | KLIEWER, JUSTIN  | 2017-01-17T00:00:00 |               | N         |            | Application Accepted |            | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=3026471, null] | 47.5685787  | -122.36036998 | 
| 3026762                   |                                                      | 5727 37TH AVE S   | CONSOLIDATE LOT PARCELS, DEMOLISH EXISTINGS STRUCTURES AND BUILD NEW MULTIFAMILY / MIXED STUCTURE                                                                                                                                                                                        | MULTIFAMILY            | II            |                  | 0        | HALE, ROBERT     |                     |               | N         |            |                      |            | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=3026762, null] | 47.55040857 | -122.28647099 | 
| 3023877                   | SEPA THRESHOLD DETERMINATION                         | 1400 NW 45TH ST   | Land Use Application to allow one, 2-story structure containing 25,000 sq. ft. of marine sales and service and one single story restaurant structure. Parking for 92 vehicles to be provided at and below grade.                                                                         | COMMERCIAL             | II            | N                | 10299531 | O'HARE, JON      | 2017-01-17T00:00:00 |               | N         |            | Application Accepted |            | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=3023877, null] | 47.66167111 | -122.37413461 | 
| 3026448                   | LOT BOUNDARY ADJUSTMENT PLAT                         | 9212 11TH AVE NW  | Land use application to adjust the boundary between two parcels of land. Proposed parcel sizes are: A) 5,424 sq ft.and B) 5,425 sq ft.                                                                                                                                                   | SINGLE FAMILY / DUPLEX | I             | N                | 0        | WINTERS, BRANDON | 2017-01-13T00:00:00 |               | N         |            | Application Accepted |            | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=3026448, null] | 47.69655384 | -122.36972977 | 
| 3023101                   | DESIGN REVIEW WITH EDG, SEPA THRESHOLD DETERMINATION | 1101 8TH AVE      | Land Use Application to allow two, 32-story structures containing a total of 565 apartment units above retail office and restaurant. Parking for 387 vehicles to be provided in a shared, below grade garage. Project includes proposed alley vacation between Seneca St. and Spring St. | COMMERCIAL             | II            | Y                | 85000000 | HINTHORNE, BRAD  | 2017-01-13T00:00:00 |               | N         |            | Application Accepted |            | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=3023101, null] | 47.60874813 | -122.32967216 | 
```