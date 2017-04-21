# FOIA Request Log - City Clerk

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-city-clerk-9c565) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/72qm-3bwf) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/72qm-3bwf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/72qm-3bwf/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 72qm-3bwf |
| Name | FOIA Request Log - City Clerk |
| Attribution | Office of the Chicago City Clerk |
| Category | FOIA |
| Created | 2010-04-30T18:32:24Z |
| Publication Date | 2017-01-05T21:43:08Z |

## Description

FOIA requests received by the Office of the Chicago City Clerk as of May 1, 2010

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
series e:72qm-3bwf d:2010-05-04T00:00:00.000Z t:description_of_request="Current City of Chicago dog license registry" t:organization="Pet Care Plus" t:requestor_name="Chris Stavrianos" m:row_number.72qm-3bwf=1

series e:72qm-3bwf d:2010-05-04T00:00:00.000Z t:description_of_request="Copy of the business license for Paris Furniture, 7450 S. Cicero, Chicago, IL." t:requestor_name="Pamela Jones" m:row_number.72qm-3bwf=2

series e:72qm-3bwf d:2010-05-05T00:00:00.000Z t:description_of_request="Copies of the 2009 Ethics Statements for all 50 Aldermen" t:organization="Chicago Tribune" t:requestor_name="Hal Dardick" m:row_number.72qm-3bwf=3
```

## Meta Commands

```ls
metric m:row_number.72qm-3bwf p:long l:"Row Number"

entity e:72qm-3bwf l:"FOIA Request Log - City Clerk" t:attribution="Office of the Chicago City Clerk" t:url=https://data.cityofchicago.org/api/views/72qm-3bwf

property e:72qm-3bwf t:meta.view v:id=72qm-3bwf v:category=FOIA v:attributionLink=http://www.chicityclerk.com v:averageRating=0 v:name="FOIA Request Log - City Clerk" v:attribution="Office of the Chicago City Clerk"

property e:72qm-3bwf t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:72qm-3bwf t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name          | organization                   | description_of_request                                                                                                                                                                                                                          | date_received       | due_date            | 
| ======================= | ============================== | =============================================================================================================================================================================================================================================== | =================== | =================== | 
| Chris Stavrianos        | Pet Care Plus                  | Current City of Chicago dog license registry                                                                                                                                                                                                    | 2010-05-04T00:00:00 | 2010-05-11T00:00:00 | 
| Pamela Jones            |                                | Copy of the business license for Paris Furniture, 7450 S. Cicero, Chicago, IL.                                                                                                                                                                  | 2010-05-04T00:00:00 | 2010-05-11T00:00:00 | 
| Hal Dardick             | Chicago Tribune                | Copies of the 2009 Ethics Statements for all 50 Aldermen                                                                                                                                                                                        | 2010-05-05T00:00:00 | 2010-05-12T00:00:00 | 
| John Kugler             |                                | May 10, 2010 Finance Committee hearing transcripts, video record and audio record                                                                                                                                                               | 2010-05-10T00:00:00 | 2010-05-17T00:00:00 | 
| Patricia Spano          | Sell State Expert Realty       | All code violations for 1244 S. Kolin Ave.                                                                                                                                                                                                      | 2010-05-10T00:00:00 | 2010-05-17T00:00:00 | 
| Robert Jones            | Contractors Adjustment Company | Certified copy of the General/Prime Contractor's payment bond & first 5 pgs/signature pg of general contract btwn Benchmark Construction Co & the City of Chicago                                                                               | 2010-05-17T00:00:00 | 2010-05-24T00:00:00 | 
| Jeffrey Girling         | Paine Wtzel Associates, Inc.   | All plans, surveys, floor plans, site plans relating to PD 1156 (Ordinance 16114): 2148 N. Natchez                                                                                                                                              | 2010-05-20T00:00:00 | 2010-05-27T00:00:00 | 
| Leroy and Karen Johnson |                                | Names of Chicago Zoning Board of Appeals board members                                                                                                                                                                                          | 2010-05-21T00:00:00 | 2010-05-28T00:00:00 | 
| Greg Goldner            | Back to Work Illinois          | Listing of all valid Gambling Gaming stickers, Automatic Amusement Gaming stickers, Amusement Device operators issued by City of Chicago, incl. number of stickers, machines, locations, operators & annual revenue to City from these licenses | 2010-05-21T00:00:00 | 2010-05-28T00:00:00 | 
| Bhav Tibrewal           |                                | Copies of all materials received by the Chicago City Clerk & Chicago City Council, from Midway Investment & Development Corp., YVR Airport Services, Ltd., Vancouver Airport Authority                                                          | 2010-06-01T00:00:00 | 2010-06-08T00:00:00 | 
```