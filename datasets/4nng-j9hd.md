# FOIA Request Log - Innovation and Technology

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-innovation-and-technology-89002) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/4nng-j9hd) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/4nng-j9hd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/4nng-j9hd/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 4nng-j9hd |
| Name | FOIA Request Log - Innovation and Technology |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2011-09-23T15:39:17Z |
| Publication Date | 2017-04-19T17:00:50Z |

## Description

FOIA requests received by Innovation and Technology as of May 1, 2010

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
series e:4nng-j9hd d:2010-05-19T00:00:00.000Z t:description_of_request="Information regarding the city servers; the type and cost of the servers" t:requestor_name="Kevin Gainey" m:row_number.4nng-j9hd=1

series e:4nng-j9hd d:2010-05-25T00:00:00.000Z t:description_of_request="Invoices from Sprint Nextel to the Department of Streets and Sanitation for a GPS software program called Xora, from 2000 to the present.&nbsp; Number of cell phones using XORA; cost to install and monthly service fee. List of departments currently using XORA including start date, cost and date city department stopped using it" t:organization="Fox News" t:requestor_name="Diane Carbonara" m:row_number.4nng-j9hd=2

series e:4nng-j9hd d:2010-06-25T00:00:00.000Z t:description_of_request="Cost and technical proposal submitted by Unisys" t:organization=FedSources t:requestor_name="Elizabeth Steponkus" m:row_number.4nng-j9hd=3
```

## Meta Commands

```ls
metric m:row_number.4nng-j9hd p:long l:"Row Number"

entity e:4nng-j9hd l:"FOIA Request Log - Innovation and Technology" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/4nng-j9hd

property e:4nng-j9hd t:meta.view v:id=4nng-j9hd v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Innovation and Technology" v:attribution="City of Chicago"

property e:4nng-j9hd t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:4nng-j9hd t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name      | organization                   | description_of_request                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | date_received       | due_date            | 
| =================== | ============================== | =========================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | =================== | =================== | 
| Kevin Gainey        |                                | Information regarding the city servers; the type and cost of the servers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | 2010-05-19T00:00:00 | 2010-05-26T00:00:00 | 
| Diane Carbonara     | Fox News                       | Invoices from Sprint Nextel to the Department of Streets and Sanitation for a GPS software program called Xora, from 2000 to the present.  Number of cell phones using XORA; cost to install and monthly service fee. List of departments currently using XORA including start date, cost and date city department stopped using it                                                                                                                                                                                                                                                                                                                         | 2010-05-25T00:00:00 | 2010-06-02T00:00:00 | 
| Elizabeth Steponkus | FedSources                     | Cost and technical proposal submitted by Unisys                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | 2010-06-25T00:00:00 | 2010-07-02T00:00:00 | 
| Vincent             |                                | Information in At&T, Bank of America and Commonwealth Edison: Number of ALL employees, the number of female employees, the number of male employees, the racial make up of employees, as of right now or as of 2009 in the chicagoland area                                                                                                                                                                                                                                                                                                                                                                                                                 | 2010-07-09T00:00:00 | 2010-07-16T00:00:00 | 
| Amy E. Keller       | Wexler Wallace                 | Without violating the provisions of the Health Insurance Portability and Accountability Act (HIPAA), this is a FOIA request seeking any and all documents related to benefits paid or not paid by any City of Chicago health care plan for heart scans, CT scans, or angiograms performed by Andrew Rosenson, M.D. and AR Imaging, d/b/a HeartScan of Chicago.                                                                                                                                                                                                                                                                                              | 2010-07-12T00:00:00 | 2010-07-19T00:00:00 | 
| Chao He             |                                | The proposed SmartChicago initiatives waiting for Round 2 funding on BroadbandUSA?s online database. Are maps of the proposed route of the network? And if the route of the network has not yet been finalized, whether there is a decision on whether the network will pass through any of the following areas? Eola, Chicago Ridge, Worth, Palos Heights, Crestwood, Robbins, Alsip, Hazelgreen, Bridgeview, Bedford Park, Lyons, Summit, Justice, Hickory Hills, Rolling Meadows, Palatine, Long Grove, Buffalo Grove, Horatio Gardens? Also, if there is a website where I could find more information like this, could you please direct me toward it? | 2010-07-20T00:00:00 | 2010-07-27T00:00:00 | 
| Kevin B. Sander     | Cannon Business Solutions, Inc | Results of the printer bid for the recent awarded contract including pricing information and reason for award.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | 2010-08-02T00:00:00 | 2010-08-09T00:00:00 | 
| Robert D. Fink      | Arquilla & Fink, Ltd.          | Please provide us with copies of all lists, reports, notes, memoranda, applications, registrations, or any other documentation relating to any and all vehicles (regardless of date) which were registered to or owned by(or otherwise relate to) Steven Brick, Beverly Hills, Inc., Beverly Hills Limousine, Beverly Hills Limo Service, Skyline Transportation.  This request includes, but is not limited to, applications and/or registrations for Ground Transportation Registration emblems, MPEA Permit program and any audit performed in association with the MPEA online program, which involve any of the aforementioned entities or individual. | 2010-08-04T00:00:00 | 2010-08-11T00:00:00 | 
| Kevin B. Sander     | Cannon Business Solutions, Inc | Follow up questions to 8/2/10 FOIA request                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 2010-08-23T00:00:00 | 2010-08-30T00:00:00 | 
| Christopher Widmer  |                                | Copies of my W-2s from my employment with the City of Chicago (Sept. 1994 through June 2004)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 2010-08-30T00:00:00 | 2010-09-07T00:00:00 | 
```