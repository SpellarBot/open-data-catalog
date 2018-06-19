# Building Permits : Current

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-permits-current-69321) |
| Metadata | [Link](https://data.seattle.gov/api/views/mags-97de) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/mags-97de/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/mags-97de/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | mags-97de |
| Name | Building Permits : Current |
| Attribution | Seattle Department of Construction and Inspections |
| Category | Permitting |
| Tags | permit, construction, dpd, dci |
| Created | 2011-09-26T17:54:41Z |
| Publication Date | 2017-01-31T16:17:46Z |

## Description

Building Permits issued in the past five years or currently in progress

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
| Yes      | numeric metric | master_use_permit               | Master Use Permit               | number        | text          |
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
series e:mags-97de d:2017-01-30T00:00:00.000Z t:permit_type=Construction t:category="SINGLE FAMILY / DUPLEX" t:action_type=ADD/ALT t:status="Permit Issued" t:description="Construct interior alterations on main floor of each unitof an exsiting duplex, subject to field inspection (STFI)" t:work_type="No plan review" t:permit_and_complaint_status_url="http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6578806" t:applicant_name="DEHERRERA, LUCAS" t:application_permit_number=6578806 m:value=50000

series e:mags-97de d:2017-01-30T00:00:00.000Z t:permit_type=Construction t:category=COMMERCIAL t:action_type=ADD/ALT t:status="Permit Issued" t:description="Construct interior alterations to an existing restaurant subject to field inspection (STFI)" t:work_type="No plan review" t:permit_and_complaint_status_url="http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6577972" t:applicant_name="CLARK, JANE" t:application_permit_number=6577972 m:value=80000

series e:mags-97de d:2017-01-30T00:00:00.000Z t:permit_type="Site Development" t:action_type="SHORELINE EXEMPTION ONLY" t:contractor="CITY OF SEA SPU DRAIN & WASTE" t:status="AP Closed" t:description="Shoreline Exemption to allow soil boring in street ROW.  Includes boring at 488R Lakeside Ave S." t:work_type="Plan Review" t:permit_and_complaint_status_url="http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6409682" t:applicant_name="ANTIEAU, CLAY" t:application_permit_number=6409682 m:value=0
```

## Meta Commands

```ls
metric m:value p:integer l:Value d:"The value of the work being proposed based on fair market value (parts plus labor). The value displayed (if any) represents the best available information to date, and is subject to change if the project is modified. Value is not collected for all permit types." t:dataTypeName=money

metric m:master_use_permit p:integer l:"Master Use Permit" d:"A Master Use/Land Use Permit is required before some building permits to make decisions about site-specific factors of the project, such as environmental impacts or neighborhood design considerations." t:dataTypeName=number

entity e:mags-97de l:"Building Permits : Current" t:attribution="Seattle Department of Construction and Inspections" t:url=https://data.seattle.gov/api/views/mags-97de

property e:mags-97de t:meta.view v:id=mags-97de v:category=Permitting v:attributionLink=http://www.seattle.gov/dpd/permits/ v:averageRating=0 v:name="Building Permits : Current" v:attribution="Seattle Department of Construction and Inspections"

property e:mags-97de t:meta.view.license v:name="Public Domain"

property e:mags-97de t:meta.view.owner v:id=nmed-fmz8 v:profileImageUrlMedium=/api/users/nmed-fmz8/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmed-fmz8/profile_images/LARGE v:screenName="Department of Planning and Development" v:profileImageUrlSmall=/api/users/nmed-fmz8/profile_images/TINY v:displayName="Department of Planning and Development"

property e:mags-97de t:meta.view.tableauthor v:id=nmed-fmz8 v:profileImageUrlMedium=/api/users/nmed-fmz8/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmed-fmz8/profile_images/LARGE v:screenName="Department of Planning and Development" v:profileImageUrlSmall=/api/users/nmed-fmz8/profile_images/TINY v:roleName=publisher v:displayName="Department of Planning and Development"
```

## Top Records

```ls
| application_permit_number | permit_type      | address             | description                                                                                                                                                                                                                    | category               | action_type              | work_type      | value   | applicant_name     | application_date    | issue_date          | final_date          | expiration_date     | status               | contractor                    | permit_and_complaint_status_url                                          | master_use_permit | latitude    | longitude     | 
| ========================= | ================ | =================== | ============================================================================================================================================================================================================================== | ====================== | ======================== | ============== | ======= | ================== | =================== | =================== | =================== | =================== | ==================== | ============================= | ======================================================================== | ================= | =========== | ============= | 
| 6578806                   | Construction     | 706 N 77TH ST       | Construct interior alterations on main floor of each unitof an exsiting duplex, subject to field inspection (STFI)                                                                                                             | SINGLE FAMILY / DUPLEX | ADD/ALT                  | No plan review | 50000   | DEHERRERA, LUCAS   | 2017-01-30T00:00:00 | 2017-01-30T00:00:00 |                     | 2018-07-30T00:00:00 | Permit Issued        |                               | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6578806, null] |                   | 47.68492709 | -122.34943726 | 
| 6577972                   | Construction     | 1401 N 45TH ST      | Construct interior alterations to an existing restaurant subject to field inspection (STFI)                                                                                                                                    | COMMERCIAL             | ADD/ALT                  | No plan review | 80000   | CLARK, JANE        | 2017-01-30T00:00:00 | 2017-01-30T00:00:00 |                     | 2018-07-30T00:00:00 | Permit Issued        |                               | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6577972, null] |                   | 47.66122443 | -122.34047032 | 
| 6409682                   | Site Development | 388R LAKESIDE AVE S | Shoreline Exemption to allow soil boring in street ROW. Includes boring at 488R Lakeside Ave S.                                                                                                                                |                        | SHORELINE EXEMPTION ONLY | Plan Review    | 0       | ANTIEAU, CLAY      | 2017-01-30T00:00:00 |                     | 2017-01-30T00:00:00 |                     | AP Closed            | CITY OF SEA SPU DRAIN & WASTE | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6409682, null] |                   | 47.59916842 | -122.28652139 | 
| 6566376                   | Construction     | 10055 41ST AVE NE   | Construct addition and alterations to existing single family residence, per subject to field inspection (STFI).                                                                                                                | SINGLE FAMILY / DUPLEX | ADD/ALT                  | No plan review | 18000   | MERRILL, DAVID     | 2017-01-30T00:00:00 | 2017-01-30T00:00:00 |                     | 2018-07-30T00:00:00 | Permit Issued        |                               | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6566376, null] |                   | 47.70253238 | -122.28469434 | 
| 6578443                   | Demolition       | 1908 NOB HILL AVE N | Demolish existing single family residence, subject to field inspection (STFI).                                                                                                                                                 | SINGLE FAMILY / DUPLEX | DEMOLITION               | No plan review | 0       | CHRISTIANSON, KIRK | 2017-01-30T00:00:00 |                     |                     |                     | Reviews Completed    |                               | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6578443, null] |                   | 47.63607117 | -122.35044647 | 
| 6577834                   | Construction     | 8040 DIBBLE AVE NW  | Construct interior alteration to existing basement, per (STFI)                                                                                                                                                                 | SINGLE FAMILY / DUPLEX | ADD/ALT                  | No plan review | 18942   | VASQUEZ, JOSEPH    | 2017-01-30T00:00:00 | 2017-01-30T00:00:00 |                     | 2018-07-30T00:00:00 | Permit Issued        |                               | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6577834, null] |                   | 47.68813801 | -122.36699697 | 
| 6486355                   | Construction     | 1111 E MADISON ST   | Alterations to basement and first floor of existing self-serve storage building. Change use of portion of first floor from storage to general retail and occupy, per plans. Tenant improvements to be under a separate permit. | COMMERCIAL             | ADD/ALT                  | Plan Review    | 1000000 | SUNDBERG, MIKAELA  | 2017-01-30T00:00:00 |                     |                     |                     | Application Accepted | SEATTLE UNIVERSITY            | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6486355, null] |                   | 47.61234065 | -122.31711333 | 
| 6578731                   | Construction     | 4048 40TH AVE SW    | Construct basement interior alterations to an existing single family residence subject to field inspection (STFI)                                                                                                              | SINGLE FAMILY / DUPLEX | ADD/ALT                  | No plan review | 25000   | GRINKE, TADD       | 2017-01-30T00:00:00 | 2017-01-30T00:00:00 |                     | 2018-07-30T00:00:00 | Permit Issued        |                               | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6578731, null] |                   | 47.56694964 | -122.38247823 | 
| 6578702                   | Construction     | 12044 FREMONT AVE N | Construct interior alterations to an existing single family residence, subject to field inspection (STFI).                                                                                                                     | SINGLE FAMILY / DUPLEX | ADD/ALT                  | No plan review | 9500    | WACHTER, KEN       | 2017-01-30T00:00:00 | 2017-01-30T00:00:00 |                     | 2018-07-30T00:00:00 | Permit Issued        |                               | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6578702, null] |                   | 47.71728867 | -122.35002144 | 
| 6576299                   | Construction     | 4712 FREMONT AVE N  | Construct alterations for accessory dwelling unit in the basement of existing single family residence, per plan.                                                                                                               | SINGLE FAMILY / DUPLEX | ADD/ALT                  | Plan Review    | 65000   | CLICK, CHERYL      | 2017-04-12T00:00:00 |                     |                     |                     | Application Accepted | HALLER REMODELING             | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6576299, null] |                   | 47.66331393 | -122.34978411 | 
```