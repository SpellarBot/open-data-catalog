# FOIA Request Log - Community Development - Historical

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-community-development-cddf1) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/rpya-q7ut) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/rpya-q7ut/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/rpya-q7ut/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | rpya-q7ut |
| Name | FOIA Request Log - Community Development - Historical |
| Attribution | City of Chicago |
| Category | FOIA |
| Tags | historical |
| Created | 2010-04-16T16:14:13Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

FOIA requests received by Community Development May 1, 2010-December 31, 2010; For requests made after January 1, 2011, please see Housing & Economic Development FOIA Request Log  at https://data.cityofchicago.org/Government/FOIA-Request-Log-Housing-And-Economic-Development/5ztz-espx

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | =========== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag  | requestor_name         | REQUESTOR NAME         | text          | text          |
| Yes      | series tag  | organization           | ORGANIZATION           | text          | text          |
| Yes      | series tag  | description_of_request | DESCRIPTION OF REQUEST | html          | html          |
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
series e:rpya-q7ut d:2010-09-24T00:00:00.000Z t:description_of_request="An electronic spreadsheet of TIF RDAs from 2000 to the present indicating name of TIF district, name of company, amount of subsidy, length of agreement and job requirements" t:organization=Self t:requestor_name="Rebecca James" m:row_number.rpya-q7ut=1

series e:rpya-q7ut d:2010-11-01T00:00:00.000Z t:description_of_request="Copy of the SSA application #48 including all attachments, i.e. application, feasibility study and capacity analysis" t:organization="New Pisah Church" t:requestor_name="Ouida Jones" m:row_number.rpya-q7ut=2

series e:rpya-q7ut d:2010-11-22T00:00:00.000Z t:description_of_request="A list of addresses, unit numbers, PINs and sale prices of every affordable for-sale unit that has been created through the Affordable Requirements Ordinance (ARO) from 2003 to present.  In addition, please include a copy of the developer's form, affordable housing agreement, closing request from, and the affordable housing restrictive covenant for each development" t:organization=Self t:requestor_name="Sara Amaral" m:row_number.rpya-q7ut=3
```

## Meta Commands

```ls
metric m:row_number.rpya-q7ut p:long l:"Row Number"

entity e:rpya-q7ut l:"FOIA Request Log - Community Development - Historical" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/rpya-q7ut

property e:rpya-q7ut t:meta.view v:id=rpya-q7ut v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Community Development - Historical" v:attribution="City of Chicago"

property e:rpya-q7ut t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:rpya-q7ut t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name  | organization                | description_of_request                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | date_received       | due_date            | 
| =============== | =========================== | ================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | =================== | =================== | 
| Rebecca James   | Self                        | An electronic spreadsheet of TIF RDAs from 2000 to the present indicating name of TIF district, name of company, amount of subsidy, length of agreement and job requirements                                                                                                                                                                                                                                                                                                                                                                       | 2010-09-24T00:00:00 | 2010-10-01T00:00:00 | 
| Ouida Jones     | New Pisah Church            | Copy of the SSA application #48 including all attachments, i.e. application, feasibility study and capacity analysis                                                                                                                                                                                                                                                                                                                                                                                                                               | 2010-11-01T00:00:00 | 2010-11-08T00:00:00 | 
| Sara Amaral     | Self                        | A list of addresses, unit numbers, PINs and sale prices of every affordable for-sale unit that has been created through the Affordable Requirements Ordinance (ARO) from 2003 to present. In addition, please include a copy of the developer's form, affordable housing agreement, closing request from, and the affordable housing restrictive covenant for each development                                                                                                                                                                     | 2010-11-22T00:00:00 | 2010-11-30T00:00:00 | 
| Eddie Ho        | Self                        | Any pending or outstanding administrative hearings or court case against 4229 S. Mozart Street                                                                                                                                                                                                                                                                                                                                                                                                                                                     | 2010-11-22T00:00:00 | 2010-11-30T00:00:00 | 
| Angelo Townsend | Self                        | Budget for the $3.3 million menu money Alderman Howard Brookins used for infrastructure improvements in the 21st Ward for the 2008. Specifically requesting information on where the money went towards infrastructure improvements and how it was spent; Budget for the $1.3 million dollar menu money Alderman Howard Brookins used for infrastructure improvements in the 21st Ward for the year 2009; Budget for the $1.3 million menu money Alderman Howard Brookins used for infrastructure improvements in the 21st Ward for the year 2010. | 2010-11-23T00:00:00 | 2010-12-01T00:00:00 | 
| Andrea Raila    | Andrea Raila and Associates | All PINs belonging to SSA #46. Please provide by email                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | 2010-11-26T00:00:00 | 2010-12-02T00:00:00 | 
| Sanjiv Chadha   | NWS Architects              | Any drawings, forms, documents related to the original construction and/or subsequent tenant buildout at 555 W. Roosevelt Rd.                                                                                                                                                                                                                                                                                                                                                                                                                      | 2010-12-01T00:00:00 | 2010-12-08T00:00:00 | 
| Pamela Merema   | Self                        | All notifications for staff reports, feasibility studies, meeting minutes, recordings of meetings, membership list with names and titles and department represented, documents showing appt. of community rep and other responsive documents associated in any way with the Joint Review Board for: the proposed Montrose-Clarendon TIF and Wilson TIF's Clifton-Magnolia RDA                                                                                                                                                                      | 2010-05-11T00:00:00 | 2010-05-18T00:00:00 | 
| Ray Gibson      | Chicago Tribune             | Seeking to examine and copy an application for tax credits filed by Boulevard Courts, aka the Hispanic Housing Development Corp.                                                                                                                                                                                                                                                                                                                                                                                                                   | 2010-05-11T00:00:00 | 2010-05-18T00:00:00 | 
| Jennifer LaSota | RCI Advisors                | Enterprise Zone Sales Tax Exemption letter issued for 4150-58 W. Wrigthwood                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 2010-05-12T00:00:00 | 2010-05-19T00:00:00 | 
```