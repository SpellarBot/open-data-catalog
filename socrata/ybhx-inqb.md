# FOIA Request Log - Business Affairs & Consumer Protection

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-business-affairs-consumer-protection-e17a4) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ybhx-inqb) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ybhx-inqb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ybhx-inqb/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ybhx-inqb |
| Name | FOIA Request Log - Business Affairs & Consumer Protection |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2010-04-16T15:58:23Z |
| Publication Date | 2017-03-01T23:53:26Z |

## Description

FOIA requests received by Business Affairs and Consumer Protection as of May 1, 2010

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
series e:ybhx-inqb d:2010-07-08T00:00:00.000Z t:description_of_request="Funky Buddha Lounge, 728 W. Grand, liquor license application" t:organization="Zaczek Attorney at Law" t:requestor_name="Bert Zaczek" m:row_number.ybhx-inqb=1

series e:ybhx-inqb d:2010-09-03T00:00:00.000Z t:description_of_request="Exhibits for 10PVA18" t:requestor_name="Al Saleh" m:row_number.ybhx-inqb=2

series e:ybhx-inqb d:2011-02-08T00:00:00.000Z t:requestor_name="Charles Ryan" m:row_number.ybhx-inqb=3
```

## Meta Commands

```ls
metric m:row_number.ybhx-inqb p:long l:"Row Number"

entity e:ybhx-inqb l:"FOIA Request Log - Business Affairs & Consumer Protection" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/ybhx-inqb

property e:ybhx-inqb t:meta.view v:id=ybhx-inqb v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Business Affairs & Consumer Protection" v:attribution="City of Chicago"

property e:ybhx-inqb t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:ybhx-inqb t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name  | organization                          | description_of_request                                                    | date_received       | due_date            | 
| =============== | ===================================== | ========================================================================= | =================== | =================== | 
| Bert Zaczek     | Zaczek Attorney at Law                | Funky Buddha Lounge, 728 W. Grand, liquor license application             | 2010-07-08T00:00:00 | 2010-07-15T00:00:00 | 
| Al Saleh        |                                       | Exhibits for 10PVA18                                                      | 2010-09-03T00:00:00 | 2010-09-13T00:00:00 | 
| Charles Ryan    |                                       |                                                                           | 2011-02-08T00:00:00 | 2011-02-16T00:00:00 | 
| Clyde Toney     |                                       | Copies of my Peddlers License # 320898                                    | 2011-04-06T00:00:00 | 2011-04-13T00:00:00 | 
| William Delaney | Delaney Law                           |                                                                           | 2010-06-21T00:00:00 | 2010-06-28T00:00:00 | 
| Makeda Moore    |                                       | List of all street performers                                             | 2010-08-16T00:00:00 | 2010-08-23T00:00:00 | 
| Joel Byron      |                                       | Business Licenses at 1530 W. Lawrence                                     | 2010-08-30T00:00:00 | 2010-09-07T00:00:00 | 
| Amy Smith       | Geico                                 | License Holder for horse & carriage # 24                                  | 2010-09-28T00:00:00 | 2010-10-05T00:00:00 | 
| Harry Rivera    | Coldwell Banker Residential Brokerage | Violations and permits 1416 N. Waller                                     | 2011-03-30T00:00:00 | 2011-04-06T00:00:00 | 
| Mario Correa    | Law Offices of Mario Correa           | Documents for case # 04-LR0214, LS10-0068 El Marisco 4501-4503 W. Belmont | 2011-03-30T00:00:00 | 2011-04-06T00:00:00 | 
```