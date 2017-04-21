# Electrical Permits: Current

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/electrical-permits-current-31c02) |
| Metadata | [Link](https://data.seattle.gov/api/views/raim-ay5x) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/raim-ay5x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/raim-ay5x/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | raim-ay5x |
| Name | Electrical Permits: Current |
| Attribution | City of Seattle, Department of Planning and Development |
| Category | Permitting |
| Tags | dpd |
| Created | 2010-08-02T17:39:28Z |
| Publication Date | 2017-01-23T20:51:03Z |

## Description

Permits for performing electrical work, issued in the past three years or currently in progress.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | ============== | =============================== | =============================== | ============= | ============= |
| Yes      | series tag     | application_permit_number       | Application/Permit Number       | text          | text          |
| Yes      | series tag     | permit_type                     | Permit Type                     | text          | text          |
| No       |                | address                         | Address                         | text          | text          |
| Yes      | series tag     | description                     | Description                     | text          | text          |
| Yes      | series tag     | category                        | Category                        | text          | text          |
| Yes      | series tag     | action_type                     | Action Type                     | text          | text          |
| Yes      | series tag     | work_type                       | Work Type                       | text          | text          |
| Yes      | numeric metric | value                           | Value                           | money         | money         |
| Yes      | series tag     | applicant_name                  | Applicant Name                  | text          | text          |
| Yes      | time           | application_date                | Application Date                | calendar_date | calendar_date |
| No       |                | issue_date                      | Issue Date                      | calendar_date | calendar_date |
| No       |                | final_date                      | Final Date                      | calendar_date | calendar_date |
| No       |                | expiration_date                 | Expiration Date                 | calendar_date | calendar_date |
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
Excluded Fields = address,issue_date,final_date,expiration_date,latitude,longitude
```

## Data Commands

```ls
series e:raim-ay5x d:2016-06-09T00:00:00.000Z t:permit_type=ELECTRICAL t:category=MULTIFAMILY t:contractor="PERFORMANCE ELECTRIC INC." t:status="Permit Closed" t:description="NEW 3 UNIT TOWNHOUSES" t:work_type="Plan Review" t:permit_and_complaint_status_url="http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6539592" t:applicant_name="PERFORMANCE ELECTRIC INC." t:application_permit_number=6539592 m:value=24000

series e:raim-ay5x d:2017-01-19T00:00:00.000Z t:permit_type=ELECTRICAL t:category="SINGLE FAMILY / DUPLEX" t:contractor="EVERGREEN REFRIGERATION LLC" t:status="Permit Closed" t:description="INSTALL LOW VOLTAGE FOR STAT" t:work_type="No plan review" t:permit_and_complaint_status_url="http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6576846" t:applicant_name="EVERGREEN REFRIGERATION LLC" t:application_permit_number=6576846 m:value=0

series e:raim-ay5x d:2016-12-16T00:00:00.000Z t:permit_type=ELECTRICAL t:category=MULTIFAMILY t:contractor="ALL WIRE ELECTRIC INC" t:status="Permit Issued" t:description="ELECTRICAL UPGRADE FOR REMODEL OF UNIT #303 2/7/16 HKH; ADD (1) FEEDER" t:work_type="No plan review" t:permit_and_complaint_status_url="http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6572054" t:applicant_name="ALL WIRE ELECTRIC INC" t:application_permit_number=6572054 m:value=0
```

## Meta Commands

```ls
metric m:value p:integer l:Value d:"The value of the work being proposed. The value displayed (if any) represents the best available information to date, and is subject to change as more information becomes available. Value is not collected for all permit types." t:dataTypeName=money

entity e:raim-ay5x l:"Electrical Permits: Current" t:attribution="City of Seattle, Department of Planning and Development" t:url=https://data.seattle.gov/api/views/raim-ay5x

property e:raim-ay5x t:meta.view v:id=raim-ay5x v:category=Permitting v:attributionLink=http://www.seattle.gov/dpd v:averageRating=0 v:name="Electrical Permits: Current" v:attribution="City of Seattle, Department of Planning and Development"

property e:raim-ay5x t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:raim-ay5x t:meta.view.owner v:id=nmed-fmz8 v:profileImageUrlMedium=/api/users/nmed-fmz8/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmed-fmz8/profile_images/LARGE v:screenName="Department of Planning and Development" v:profileImageUrlSmall=/api/users/nmed-fmz8/profile_images/TINY v:displayName="Department of Planning and Development"

property e:raim-ay5x t:meta.view.tableauthor v:id=nmed-fmz8 v:profileImageUrlMedium=/api/users/nmed-fmz8/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmed-fmz8/profile_images/LARGE v:screenName="Department of Planning and Development" v:profileImageUrlSmall=/api/users/nmed-fmz8/profile_images/TINY v:roleName=publisher v:displayName="Department of Planning and Development"
```

## Top Records

```ls
| application_permit_number | permit_type | address                | description                                                                                                                                                                                                                                                                                                        | category               | action_type | work_type      | value | applicant_name              | application_date    | issue_date          | final_date          | expiration_date     | status        | contractor                  | permit_and_complaint_status_url                                          | latitude    | longitude     | 
| ========================= | =========== | ====================== | ================================================================================================================================================================================================================================================================================================================== | ====================== | =========== | ============== | ===== | =========================== | =================== | =================== | =================== | =================== | ============= | =========================== | ======================================================================== | =========== | ============= | 
| 6539592                   | ELECTRICAL  | 4252 WINSLOW PL N      | NEW 3 UNIT TOWNHOUSES                                                                                                                                                                                                                                                                                              | MULTIFAMILY            |             | Plan Review    | 24000 | PERFORMANCE ELECTRIC INC.   | 2016-06-09T00:00:00 | 2016-07-19T00:00:00 | 2017-02-07T00:00:00 | 2017-07-19T00:00:00 | Permit Closed | PERFORMANCE ELECTRIC INC.   | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6539592, null] | 47.65885512 | -122.34645552 | 
| 6576846                   | ELECTRICAL  | 1935 E CALHOUN ST      | INSTALL LOW VOLTAGE FOR STAT                                                                                                                                                                                                                                                                                       | SINGLE FAMILY / DUPLEX |             | No plan review | 0     | EVERGREEN REFRIGERATION LLC | 2017-01-19T00:00:00 | 2017-01-19T00:00:00 | 2017-02-07T00:00:00 | 2018-01-19T00:00:00 | Permit Closed | EVERGREEN REFRIGERATION LLC | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6576846, null] | 47.64077845 | -122.30576844 | 
| 6572054                   | ELECTRICAL  | 924 16TH AVE           | ELECTRICAL UPGRADE FOR REMODEL OF UNIT #303 2/7/16 HKH; ADD (1) FEEDER                                                                                                                                                                                                                                             | MULTIFAMILY            |             | No plan review | 0     | ALL WIRE ELECTRIC INC       | 2016-12-16T00:00:00 | 2016-12-16T00:00:00 |                     | 2017-12-16T00:00:00 | Permit Issued | ALL WIRE ELECTRIC INC       | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6572054, null] | 47.61120115 | -122.31120347 | 
| 6577304                   | ELECTRICAL  | 6518 32ND AVE S        | ADDITION                                                                                                                                                                                                                                                                                                           | SINGLE FAMILY / DUPLEX |             | No plan review | 0     | DANG, PHUI                  | 2017-01-20T00:00:00 | 2017-01-20T00:00:00 |                     | 2018-01-20T00:00:00 | Permit Issued |                             | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6577304, null] | 47.54386267 | -122.29111004 | 
| 6579743                   | ELECTRICAL  | 8435 47TH AVE S        | [UFER GROUND. ]                                                                                                                                                                                                                                                                                                    | SINGLE FAMILY / DUPLEX |             | No plan review | 0     | GREAT WALL ELECTRIC INC     | 2017-02-05T00:00:00 | 2017-02-05T00:00:00 | 2017-02-07T00:00:00 | 2018-02-05T00:00:00 | Permit Closed | GREAT WALL ELECTRIC INC     | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6579743, null] | 47.52684598 | -122.27371454 | 
| 6577470                   | ELECTRICAL  | 601 UNION ST           | ADDITION OF ONE SPEAKER STROBE TO AN EXISTING FIRE ALARM SYSTEM. THIS IS A JOINT VENTURE WITH PRIDE ELECTRIC.                                                                                                                                                                                                      | COMMERCIAL             |             | No plan review | 0     | CONVERGINT TECHNOLOGIES LLC | 2017-01-23T00:00:00 | 2017-01-23T00:00:00 | 2017-02-07T00:00:00 | 2018-01-23T00:00:00 | Permit Closed | CONVERGINT TECHNOLOGIES LLC | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6577470, null] | 47.610431   | -122.33207691 | 
| 6576980                   | ELECTRICAL  | 2511 NW 80TH ST        | TEMP POWER ONLY - ADD (3) 100 AMP TEMPORARY PANEL FROM EXISTING SERVER.                                                                                                                                                                                                                                            | COMMERCIAL             |             | No plan review | 0     | EXCEL ELECTRIC OF TACOMA    | 2017-01-20T00:00:00 | 2017-01-20T00:00:00 |                     | 2018-01-20T00:00:00 | Permit Issued | EXCEL ELECTRIC OF TACOMA    | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6576980, null] | 47.68644125 | -122.38906509 | 
| 6559641                   | ELECTRICAL  | 169 19TH AVE           | 200AMP SERVICE/PANEL AND KNOB AND TUBE REWIRE                                                                                                                                                                                                                                                                      | SINGLE FAMILY / DUPLEX |             | No plan review | 0     | SEATOWN ELECTRIC CORP       | 2016-10-01T00:00:00 | 2016-10-01T00:00:00 | 2017-02-07T00:00:00 | 2017-10-01T00:00:00 | Permit Closed | SEATOWN ELECTRIC CORP       | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6559641, null] | 47.60335657 | -122.30796923 | 
| 6493277                   | ELECTRICAL  | 1120 8TH AVE           | CHANGE OUT EXISTING SPLIT-BUSS PANEL AND REPLACE WITH NEW MAIN BREAKER SQD PANEL. LIKE FOR LIKE.ATTN: JIM SEAMANSPLEASE CONTACT JEFF MILL 45 MINUTES PRIOR TO ARRIVAL. 425-327-0810 AFTERNOON INSPECTION PLEASE. THIS WILL BE COORDINATED WITH 2 TO 3 OTHER INSPECTIONS IN THE SAME BUILDING. 09/20/16 CEP; RENEW. | COMMERCIAL             |             | No plan review | 0     | METROPOLITAN COMPANIES      | 2015-09-03T00:00:00 | 2015-09-03T00:00:00 | 2017-02-07T00:00:00 | 2017-09-02T00:00:00 | Permit Closed | METROPOLITAN COMPANIES      | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6493277, null] | 47.60929892 | -122.32947361 | 
| 6570219                   | ELECTRICAL  | 7544 M L KING JR WAY S | INSTALL POWER FOR 28 LITTLE HOUSES - JOB #49267                                                                                                                                                                                                                                                                    | MULTIFAMILY            |             | No plan review | 0     | PRIDE ELECTRIC INCORPORATED | 2016-12-06T00:00:00 | 2016-12-06T00:00:00 | 2017-02-07T00:00:00 | 2017-12-06T00:00:00 | Permit Closed | PRIDE ELECTRIC INCORPORATED | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6570219, null] | 47.53396838 | -122.28045476 | 
```