# FOIA Request Log - Family and Support Services

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-family-and-support-services-d17f4) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/yfhi-bd8g) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/yfhi-bd8g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/yfhi-bd8g/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | yfhi-bd8g |
| Name | FOIA Request Log - Family and Support Services |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2011-09-22T14:45:04Z |
| Publication Date | 2016-01-27T18:52:03Z |

## Description

FOIA requests received by Family and Support Services as of May 1, 2010

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
series e:yfhi-bd8g d:2010-05-13T00:00:00.000Z t:description_of_request="FY 09 to FY 11 Subcontractor Agreements for Easter Seals, Henry Booth, El Valor" t:requestor_name="Greg Will" m:row_number.yfhi-bd8g=1

series e:yfhi-bd8g d:2010-06-18T00:00:00.000Z t:description_of_request="FY 09 to FY 11 Subcontractor Agreements for Ada S. McKinley, Chicago Commons, Chicago State, Chicago Youth Centers, Jane Addams Hull House, Marcy Newberry, Onward Neighborhood House, Salvation Army and YMCA" t:requestor_name="Greg Will" m:row_number.yfhi-bd8g=2

series e:yfhi-bd8g d:2010-06-08T00:00:00.000Z t:description_of_request="Information related to a Violence in the Workplace Complaint" t:requestor_name="George Fielder" m:row_number.yfhi-bd8g=3
```

## Meta Commands

```ls
metric m:row_number.yfhi-bd8g p:long l:"Row Number"

entity e:yfhi-bd8g l:"FOIA Request Log - Family and Support Services" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/yfhi-bd8g

property e:yfhi-bd8g t:meta.view v:id=yfhi-bd8g v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Family and Support Services" v:attribution="City of Chicago"

property e:yfhi-bd8g t:meta.view.owner v:id=49wk-8ve8 v:screenName="Jacquelyn Walls" v:displayName="Jacquelyn Walls"

property e:yfhi-bd8g t:meta.view.tableauthor v:id=49wk-8ve8 v:screenName="Jacquelyn Walls" v:roleName=editor v:displayName="Jacquelyn Walls"
```

## Top Records

```ls
| requestor_name        | organization             | description_of_request                                                                                                                                                                                                 | date_received       | due_date            | 
| ===================== | ======================== | ====================================================================================================================================================================================================================== | =================== | =================== | 
| Greg Will             |                          | FY 09 to FY 11 Subcontractor Agreements for Easter Seals, Henry Booth, El Valor                                                                                                                                        | 2010-05-13T00:00:00 | 2010-05-19T00:00:00 | 
| Greg Will             |                          | FY 09 to FY 11 Subcontractor Agreements for Ada S. McKinley, Chicago Commons, Chicago State, Chicago Youth Centers, Jane Addams Hull House, Marcy Newberry, Onward Neighborhood House, Salvation Army and YMCA         | 2010-06-18T00:00:00 | 2010-07-01T00:00:00 | 
| George Fielder        |                          | Information related to a Violence in the Workplace Complaint                                                                                                                                                           | 2010-06-08T00:00:00 | 2010-06-21T00:00:00 | 
| Steve Rangel          | The Jumper Store         | Names, phone numbers and addresses of daycares and churches in the Chicago area                                                                                                                                        | 2010-07-12T00:00:00 | 2010-07-19T00:00:00 | 
| R. Justin Koscher     | Groszek Law Firm         | All documents related to the rental assistance of a resident arising out of her tenancy with T & B Ventures LLC at 5870 W. Lake St., Unit # 538, Chicago, Illinois 60644 in 2009                                       | 2010-07-14T00:00:00 | 2010-07-23T00:00:00 | 
| Colin Gardiner        | Smith Admunsen, LLC      | Records related to the weatherization of a Chicago resident, 2008-2009                                                                                                                                                 | 2010-07-22T00:00:00 | 2010-07-23T00:00:00 | 
| Queen Sister Afrika   | It Takes a Village, Org. | 2010 Mini Grant Applicants and Recipients                                                                                                                                                                              | 2010-07-27T00:00:00 | 2010-07-29T00:00:00 | 
| Cleveland Jefferson   |                          | Application and contract for Chicago Christian Industrial League/ A Safe Have                                                                                                                                          | 2010-10-05T00:00:00 | 2010-10-08T00:00:00 | 
| Jeff Kelly-Lowenstein | Chicago Reporter         | A list of the Chicago addresses at which DFSS made emergency visits to the homes of Chicago residents older than 65 years in 2005, 2006, 2007, 2008 and 2009.                                                          | 2010-10-26T00:00:00 | 2010-11-08T00:00:00 | 
| Greg Will             |                          | All subcontracts for early childhood education/day care services during the 2010-2011 school year received under delegate agency agreements for FY 2009 to 2011 Head Start Collaboration with select delegate agencies | 2010-10-30T00:00:00 | 2010-11-03T00:00:00 | 
```