# FOIA Request Log - Administrative Hearings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-administrative-hearings-9bbe7) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/t58s-ja5s) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/t58s-ja5s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/t58s-ja5s/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | t58s-ja5s |
| Name | FOIA Request Log - Administrative Hearings |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2011-09-27T16:11:32Z |
| Publication Date | 2017-04-19T18:24:26Z |

## Description

FOIA requests received by Administrative Hearings as of May 1, 2010

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | =========== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag  | requestor_name         | REQUESTOR NAME         | text          | text          |
| Yes      | series tag  | organization           | ORGANIZATION           | text          | text          |
| Yes      | series tag  | description_of_request | DESCRIPTION OF REQUEST | text          | text          |
| Yes      | time        | date_received          | DATE RECEIVED          | calendar_date | calendar_date |
| No       |             | date_due               | DATE DUE               | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_due
```

## Data Commands

```ls
series e:t58s-ja5s d:2010-05-03T00:00:00.000Z t:description_of_request="Final orders for 8 files" t:organization="Bank of America" t:requestor_name="Ryan Alldredge" m:row_number.t58s-ja5s=1

series e:t58s-ja5s d:2010-05-04T00:00:00.000Z t:description_of_request="File record" t:organization="Dykema Gossett PLLC" t:requestor_name="Heather Barhorst" m:row_number.t58s-ja5s=2

series e:t58s-ja5s d:2010-05-04T00:00:00.000Z t:description_of_request="File record" t:requestor_name="Pavel Tallalaev" m:row_number.t58s-ja5s=3
```

## Meta Commands

```ls
metric m:row_number.t58s-ja5s p:long l:"Row Number"

entity e:t58s-ja5s l:"FOIA Request Log - Administrative Hearings" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/t58s-ja5s

property e:t58s-ja5s t:meta.view v:id=t58s-ja5s v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Administrative Hearings" v:attribution="City of Chicago"

property e:t58s-ja5s t:meta.view.owner v:id=k5jz-kzcv v:screenName=mhgavin v:displayName=mhgavin

property e:t58s-ja5s t:meta.view.tableauthor v:id=k5jz-kzcv v:screenName=mhgavin v:roleName=editor v:displayName=mhgavin
```

## Top Records

```ls
| requestor_name      | organization                        | description_of_request         | date_received       | date_due            | 
| =================== | =================================== | ============================== | =================== | =================== | 
| Ryan Alldredge      | Bank of America                     | Final orders for 8 files       | 2010-05-03T00:00:00 | 2010-05-10T00:00:00 | 
| Heather Barhorst    | Dykema Gossett PLLC                 | File record                    | 2010-05-04T00:00:00 | 2010-05-11T00:00:00 | 
| Pavel Tallalaev     |                                     | File record                    | 2010-05-04T00:00:00 | 2010-05-11T00:00:00 | 
| Ashley Whiteside    | Bank of America                     | File records for 28 properties | 2010-05-05T00:00:00 | 2010-05-12T00:00:00 | 
| Theresa Davis, #138 | Independent Police Review Authority | File record                    | 2010-05-05T00:00:00 | 2010-05-12T00:00:00 | 
| Darwin Fletcher     |                                     | File record                    | 2010-05-05T00:00:00 | 2010-05-05T00:00:00 | 
| Charles J. Ryan     | O'Connell & Ryan                    | Entire record                  | 2010-05-06T00:00:00 | 2010-05-13T00:00:00 | 
| Brian Owen          |                                     | File record                    | 2010-05-06T00:00:00 | 2010-05-20T00:00:00 | 
| John Wyatt          |                                     | File record                    | 2010-05-06T00:00:00 | 2010-05-13T00:00:00 | 
| Ambrose             | El Maya tire shop                   | Final order                    | 2010-05-07T00:00:00 | 2010-05-14T00:00:00 | 
```