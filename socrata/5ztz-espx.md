# FOIA Request Log - Planning and Development

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-planning-and-development-a210f) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/5ztz-espx) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/5ztz-espx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/5ztz-espx/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 5ztz-espx |
| Name | FOIA Request Log - Planning and Development |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2010-12-22T18:28:57Z |
| Publication Date | 2017-04-12T20:13:07Z |

## Description

FOIA requests received as of January 3, 2011 by the Department of Planning and Development (Department of Housing and Economic Development prior to January 2014).

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
series e:5ztz-espx d:2012-01-03T00:00:00.000Z t:description_of_request="All communications between the developer for this project, his agents and interested parties and HED from the period from May 1, 2011 to date" t:organization="Carpenters Local 58 Union" t:requestor_name="Ian Main" m:row_number.5ztz-espx=1

series e:5ztz-espx d:2012-01-03T00:00:00.000Z t:description_of_request="DOW records for 5637 N. Campbell Ave." t:organization="Chicago Permit Services" t:requestor_name="Sofia Simotas" m:row_number.5ztz-espx=2

series e:5ztz-espx d:2012-01-03T00:00:00.000Z t:description_of_request="Documents from HED related to the past development proposals for approx. 10-acres of City-owned land at 63rd and Halsted Streets.  These documents should include all development proposals from Pat Daley or related development companies as well as other developers since 2001" t:organization="CRD Accord" t:requestor_name="Christopher Hill" m:row_number.5ztz-espx=3
```

## Meta Commands

```ls
metric m:row_number.5ztz-espx p:long l:"Row Number"

entity e:5ztz-espx l:"FOIA Request Log - Planning and Development" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/5ztz-espx

property e:5ztz-espx t:meta.view v:id=5ztz-espx v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Planning and Development" v:attribution="City of Chicago"

property e:5ztz-espx t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:5ztz-espx t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name    | organization              | description_of_request                                                                                                                                                                                                                                                            | date_received       | due_date            | 
| ================= | ========================= | ================================================================================================================================================================================================================================================================================= | =================== | =================== | 
| Ian Main          | Carpenters Local 58 Union | All communications between the developer for this project, his agents and interested parties and HED from the period from May 1, 2011 to date                                                                                                                                     | 2012-01-03T00:00:00 | 2012-01-10T00:00:00 | 
| Sofia Simotas     | Chicago Permit Services   | DOW records for 5637 N. Campbell Ave.                                                                                                                                                                                                                                             | 2012-01-03T00:00:00 | 2012-01-10T00:00:00 | 
| Christopher Hill  | CRD Accord                | Documents from HED related to the past development proposals for approx. 10-acres of City-owned land at 63rd and Halsted Streets. These documents should include all development proposals from Pat Daley or related development companies as well as other developers since 2001 | 2012-01-03T00:00:00 | 2012-01-10T00:00:00 | 
| Sofia Simotas     | Chicago Permit Services   | DOW records for 614 N. Springfield St.                                                                                                                                                                                                                                            | 2012-01-04T00:00:00 | 2012-01-11T00:00:00 | 
| Ramon Contreras   |                           | DOW records for 2112 E. 72nd Pl.                                                                                                                                                                                                                                                  | 2012-01-04T00:00:00 | 2012-01-11T00:00:00 | 
| Ramon Contreras   |                           | DOW records for 1144 N. Springfield St.                                                                                                                                                                                                                                           | 2012-01-04T00:00:00 | 2012-01-11T00:00:00 | 
| Thomas Moffit     |                           | DOW records for 1047 N. Hoyne Ave.                                                                                                                                                                                                                                                | 2012-01-04T00:00:00 | 2012-01-11T00:00:00 | 
| Lesley Magnabosco | Thompson Coburn           | Any variations for 853 W. Dickens St.                                                                                                                                                                                                                                             | 2012-01-04T00:00:00 | 2012-01-11T00:00:00 | 
| Justin Kaplan     | Lynch & Stern             | Copies of all City of Chicago Sales Tax Exemption Certificates from Dec. 15, 2011 through Jan. 3, 2012                                                                                                                                                                            | 2012-01-04T00:00:00 | 2012-01-11T00:00:00 | 
| Justin Leggett    | Right Pro Realty          | Please advise of any and all outstanding fines, or violations for 4838 W. Winnemac Ave.                                                                                                                                                                                           | 2012-01-05T00:00:00 | 2012-01-12T00:00:00 | 
```