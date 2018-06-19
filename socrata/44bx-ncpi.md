# FOIA Request Log - Law

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-law-6523c) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/44bx-ncpi) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/44bx-ncpi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/44bx-ncpi/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 44bx-ncpi |
| Name | FOIA Request Log - Law |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2010-04-16T19:03:57Z |
| Publication Date | 2017-01-20T15:17:02Z |

## Description

FOIA requests received by Law as of May 1, 2010

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
series e:44bx-ncpi d:2010-05-04T00:00:00.000Z t:description_of_request="Copy of agreement between the City of Chicago and CTI Collections." t:organization=Self t:requestor_name="Robert Willey" m:row_number.44bx-ncpi=1

series e:44bx-ncpi d:2010-05-07T00:00:00.000Z t:description_of_request="Police Department address and phone numbers for named police officers" t:organization=Self t:requestor_name="Douglas Lemon" m:row_number.44bx-ncpi=2

series e:44bx-ncpi d:2010-05-07T00:00:00.000Z t:description_of_request="Elevator inspection" t:organization=Self t:requestor_name="Renee McManus" m:row_number.44bx-ncpi=3
```

## Meta Commands

```ls
metric m:row_number.44bx-ncpi p:long l:"Row Number"

entity e:44bx-ncpi l:"FOIA Request Log - Law" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/44bx-ncpi

property e:44bx-ncpi t:meta.view v:id=44bx-ncpi v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Law" v:attribution="City of Chicago"

property e:44bx-ncpi t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:44bx-ncpi t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name     | organization        | description_of_request                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | date_received       | due_date            | 
| ================== | =================== | =============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | =================== | =================== | 
| Robert Willey      | Self                | Copy of agreement between the City of Chicago and CTI Collections.                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | 2010-05-04T00:00:00 | 2010-05-11T00:00:00 | 
| Douglas Lemon      | Self                | Police Department address and phone numbers for named police officers                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | 2010-05-07T00:00:00 | 2010-05-14T00:00:00 | 
| Renee McManus      | Self                | Elevator inspection                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | 2010-05-07T00:00:00 | 2010-05-14T00:00:00 | 
| Renee McManus      | Self                | Status on Elevator inspection                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | 2010-05-07T00:00:00 | 2010-05-14T00:00:00 | 
| David Gordon       | Sidley Austin LLP   | Documents relating to Aqua Parking Facility                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | 2010-05-11T00:00:00 | 2010-05-18T00:00:00 | 
| Donald Vance       | Self                | 1) Any and all records pertaining to settlements and judgments resulting from civil lawsuits, involving members of Chicago Police Department, or the Mayor listed as a defendant between January 1, 2009 to January 1, 2010; and 2) Any and all records pertaining to the above mentioned records detailing to whom the electronic fund transfers, checks, money orders, cash payment judgments and/or settlements were made to. Include names and addresses to whom these judgments and/or settlements payments were remitted to and receipts. | 2010-05-11T00:00:00 | 2010-05-18T00:00:00 | 
| Renee McManus      | Self                | Seeking information regarding property. Where are the city permits posted by the building entrance, permits for violations and people working in the building? What court cases by the city have been filed for this property?                                                                                                                                                                                                                                                                                                                  | 2010-05-12T00:00:00 | 2010-05-19T00:00:00 | 
| Victor Crown       | Self                | Copies of all letters sent to Mr. Crown in 2009                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | 2010-05-12T00:00:00 | 2010-05-19T00:00:00 | 
| Victor Crown       | Self                | Copy of "proof of service" for eight City employees                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | 2010-05-12T00:00:00 | 2010-05-19T00:00:00 | 
| Kathryn D. A'Hearn | Michaels & May P.C. | Any and all documents regarding the former Acme Barrel Company site (Acme site). Including demolitions and proposed remediation of the site.                                                                                                                                                                                                                                                                                                                                                                                                    | 2010-05-06T00:00:00 | 2010-05-20T00:00:00 | 
```