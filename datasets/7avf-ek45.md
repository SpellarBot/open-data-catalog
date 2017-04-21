# FOIA Request Log - Finance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-finance-af3e9) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/7avf-ek45) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/7avf-ek45/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/7avf-ek45/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 7avf-ek45 |
| Name | FOIA Request Log - Finance |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2011-09-26T20:38:27Z |
| Publication Date | 2017-04-13T16:59:03Z |

## Description

FOIA requests received by Finance, which includes Benefits Management, as of May 1, 2010

## Columns

```ls
| Included | Schema Type | Field Name              | Name                   | Data Type     | Render Type   |
| ======== | =========== | ======================= | ====================== | ============= | ============= |
| Yes      | series tag  | requestor_name          | REQUESTOR NAME         | text          | text          |
| Yes      | series tag  | organization            | ORGANIZATION           | text          | text          |
| Yes      | series tag  | description_of_request_ | DESCRIPTION OF REQUEST | text          | text          |
| No       |             | date_received           | DATE RECEIVED          | calendar_date | calendar_date |
| Yes      | time        | due_date                | DUE DATE               | calendar_date | calendar_date |
```

## Time Field

```ls
Value = due_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_received
```

## Data Commands

```ls
series e:7avf-ek45 d:2010-05-11T00:00:00.000Z t:description_of_request_="1.Pursuant to the O'Hare Bonds valued at $1.5B projected for the 2nd and 3rd Quarter of 2010, copies of any and all documents related to: A. initial request for RFP issued by the City of Chicago; B. Proposal submitted by the awarded/ assigned Trustee in response to RFP; C.Any and all agreements between the City of Chicago and the awarded/ assigned Trustee that relate to the O'Hare bonds. 2. Pursuant to the General Obligation Bonds dated January 27,2010 with Amalgamated Bank of Chicago listed as Trustee, copies of all documents as stated above for O'Hare Bonds A,B, C.  3 Pursuant to the O'Hare International Airport Passenger Facility Charge Revenue Refunding Bonds dated January 16, 2008 with BNY Midwest Trust Company, Chicago any and all documents as stated above for O'Hare Bonds And Amalgamated Bank of Chicago, A, B, and C." t:organization="Acumen Probe LLC" t:requestor_name="Steven M. Simon" m:row_number.7avf-ek45=1

series e:7avf-ek45 d:2010-05-11T00:00:00.000Z t:description_of_request_="All timesheets affecting City Treasurer Employees from circa 1998 from the period of January 1,1998 to December 31,1998. All timesheets notating ""clocking in and clocking out"" affecting City Treasurer Employees from circa 1998 from the period of January 1, 1998 to December 31,1998." t:organization=Resident t:requestor_name="Victor M. Crown" m:row_number.7avf-ek45=2

series e:7avf-ek45 d:2010-05-18T00:00:00.000Z t:description_of_request_="Historical Information regarding City of Chicago checks" t:organization="Ivy Tech" t:requestor_name="Lashaunda Crymes" m:row_number.7avf-ek45=3
```

## Meta Commands

```ls
metric m:row_number.7avf-ek45 p:long l:"Row Number"

entity e:7avf-ek45 l:"FOIA Request Log - Finance" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/7avf-ek45

property e:7avf-ek45 t:meta.view v:id=7avf-ek45 v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Finance" v:attribution="City of Chicago"

property e:7avf-ek45 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:7avf-ek45 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name       | organization                        | description_of_request_                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | date_received       | due_date            | 
| ==================== | =================================== | ================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | =================== | =================== | 
| Steven M. Simon      | Acumen Probe LLC                    | 1.Pursuant to the O'Hare Bonds valued at $1.5B projected for the 2nd and 3rd Quarter of 2010, copies of any and all documents related to: A. initial request for RFP issued by the City of Chicago; B. Proposal submitted by the awarded/ assigned Trustee in response to RFP; C.Any and all agreements between the City of Chicago and the awarded/ assigned Trustee that relate to the O'Hare bonds. 2. Pursuant to the General Obligation Bonds dated January 27,2010 with Amalgamated Bank of Chicago listed as Trustee, copies of all documents as stated above for O'Hare Bonds A,B, C. 3 Pursuant to the O'Hare International Airport Passenger Facility Charge Revenue Refunding Bonds dated January 16, 2008 with BNY Midwest Trust Company, Chicago any and all documents as stated above for O'Hare Bonds And Amalgamated Bank of Chicago, A, B, and C. | 2010-05-04T00:00:00 | 2010-05-11T00:00:00 | 
| Victor M. Crown      | Resident                            | All timesheets affecting City Treasurer Employees from circa 1998 from the period of January 1,1998 to December 31,1998. All timesheets notating "clocking in and clocking out" affecting City Treasurer Employees from circa 1998 from the period of January 1, 1998 to December 31,1998.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | 2010-05-04T00:00:00 | 2010-05-11T00:00:00 | 
| Lashaunda Crymes     | Ivy Tech                            | Historical Information regarding City of Chicago checks                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | 2010-05-11T00:00:00 | 2010-05-18T00:00:00 | 
| Thomas H. Georghegan | Despres, Schwartz & Geoghegan, Ltd. | All expenditures and revenues for each TIF district in existence in the City of Chicago at any time since 2004. This includes all expenditures and revenues in each district since its creation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | 2010-05-13T00:00:00 | 2010-05-20T00:00:00 | 
| Victor M. Crown      | Resident                            | All payroll statements from 2007-2010 for the following employees from the Department of Buildings: Michael Reese, Mario Olivella, and Michael Brennan. In addition, any relevant records affecting City Employee Jorge Herrera (Department of Buildings) which will notate Mr. Herrera's Proper start date. All payroll statements from circa 1998 affecting all City Treasurer employees.                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 2010-05-17T00:00:00 | 2010-05-24T00:00:00 | 
| Michael Scarpace     | Resident                            | All office expenses, travel expenses, or other reimbursements submitted by, paid to, or paid on behalf of Brian G. Doherty. All reimbursements submitted by Brian G. Doherty. Copies of office budgets and expenses of Brian G. Doherty during the tenure as alderman.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | 2010-05-18T00:00:00 | 2010-05-25T00:00:00 | 
| Firdavs Umarov       | Waste and Recycling Services        | Information about Chicago's Financial Sustainability as the city implements its Recycling and Solid Waste Diversion Programs.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | 2010-05-18T00:00:00 | 2010-05-25T00:00:00 | 
| Ross Weidner         | ABC 7 Chicago                       | Access to and a copy of supporting documentation for selected direct voucher payments from January 1, 2010 until the most recent date available.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | 2010-05-20T00:00:00 | 2010-05-27T00:00:00 | 
| Bhav Tibrewal        | AirportGroup UNITE HERE             | Copies of all materials received by the Chicago Department of Finance, from Midway Investment & Development Corp., YVR Airport Services Ltd., and the Vancouver Airport Authority, Since January 1, 2006.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | 2010-06-01T00:00:00 | 2010-06-08T00:00:00 | 
| Timothy Novak        | Chicago Sun Times                   | Records on City Lease # 13027: when the lease began, and whether the property is still being leased by the city, how much money the city paid to lease this property with an annual breakdown.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | 2010-06-04T00:00:00 | 2010-06-11T00:00:00 | 
```