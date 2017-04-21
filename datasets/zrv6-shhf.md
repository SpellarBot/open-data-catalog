# FOIA Request Log - Revenue

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-revenue-574a6) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/zrv6-shhf) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/zrv6-shhf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/zrv6-shhf/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | zrv6-shhf |
| Name | FOIA Request Log - Revenue |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2010-04-16T19:16:24Z |
| Publication Date | 2012-02-29T18:24:40Z |

## Description

FOIA requests received by Revenue as of May 1, 2010

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
series e:zrv6-shhf d:2010-05-03T00:00:00.000Z t:description_of_request="Parking tickets for Street Cleaning violations, January 2007 to Present - 48th Ward" t:requestor_name="Kevin Kelly" m:row_number.zrv6-shhf=1

series e:zrv6-shhf d:2010-05-05T00:00:00.000Z t:description_of_request="Parking ticket information for 3 tickets" t:requestor_name="Thomas Fallon" m:row_number.zrv6-shhf=2

series e:zrv6-shhf d:2010-05-07T00:00:00.000Z t:description_of_request="Information on water accts, residential commercial, industrial and charitable. (Also sent to DWM)" t:organization="Chicago SunTimes" t:requestor_name="Timothy Novak" m:row_number.zrv6-shhf=3
```

## Meta Commands

```ls
metric m:row_number.zrv6-shhf p:long l:"Row Number"

entity e:zrv6-shhf l:"FOIA Request Log - Revenue" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/zrv6-shhf

property e:zrv6-shhf t:meta.view v:id=zrv6-shhf v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Revenue" v:attribution="City of Chicago"

property e:zrv6-shhf t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:zrv6-shhf t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name     | organization                 | description_of_request                                                                                                                         | date_received       | due_date            | 
| ================== | ============================ | ============================================================================================================================================== | =================== | =================== | 
| Kevin Kelly        |                              | Parking tickets for Street Cleaning violations, January 2007 to Present - 48th Ward                                                            | 2010-05-03T00:00:00 | 2010-05-10T00:00:00 | 
| Thomas Fallon      |                              | Parking ticket information for 3 tickets                                                                                                       | 2010-05-05T00:00:00 | 2010-05-12T00:00:00 | 
| Timothy Novak      | Chicago SunTimes             | Information on water accts, residential commercial, industrial and charitable. (Also sent to DWM)                                              | 2010-05-07T00:00:00 | 2010-05-14T00:00:00 | 
| Barbara Strugalla  | Wilson Elser Moskowitz et al | Fee for Hospitalization Case Report                                                                                                            | 2010-05-07T00:00:00 | 2010-05-07T00:00:00 | 
| Ameet Sachdev      | Chicago Tribune              | Records pertaining to Friedman & Wexler                                                                                                        | 2010-05-07T00:00:00 | 2010-05-14T00:00:00 | 
| Kathy Buettner     |                              | Statement showing payments, late fees, etc. for the City of Hometown, January 2009 to present.                                                 | 2010-05-11T00:00:00 | 2010-05-18T00:00:00 | 
| Robert Willey      |                              | Copy of the agreement between the City of Chicago and CTI Collections                                                                          | 2010-05-12T00:00:00 | 2010-05-19T00:00:00 | 
| Shabbir Chandabhai | Burhani Design Build         | Debt owed on the property at 616 S. Oakley Blvd., Chicago                                                                                      | 2010-05-14T00:00:00 | 2010-05-21T00:00:00 | 
| Greg Goldner       | Back to Work Illinois        | List of all valid gambling gaming stickers, automatic amusement gaming stickers and amustement device operators issued by the City of Chicago. | 2010-05-17T00:00:00 | 2010-05-24T00:00:00 | 
| Valerie Nerini     |                              | Requesting camera footage at an intersection in regards to an automobile accident.                                                             | 2010-05-19T00:00:00 | 2010-05-26T00:00:00 | 
```