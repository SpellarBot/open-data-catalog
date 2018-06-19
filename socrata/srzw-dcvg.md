# FOIA Request Log - Office of the Mayor

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-office-of-the-mayor-8e1e5) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/srzw-dcvg) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/srzw-dcvg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/srzw-dcvg/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | srzw-dcvg |
| Name | FOIA Request Log - Office of the Mayor |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2010-04-16T15:20:41Z |
| Publication Date | 2016-09-12T19:40:04Z |

## Description

FOIA requests received by the Office of the Mayor as of May 1, 2010

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
series e:srzw-dcvg d:2010-05-04T00:00:00.000Z t:description_of_request="Copy of the mayor's appointment calendar daily schedule from Nov. and Dec. of 2009 and Feb. through April of 2010." t:organization="Chicago Reader" t:requestor_name="Mick Dumke" m:row_number.srzw-dcvg=1

series e:srzw-dcvg d:2010-05-06T00:00:00.000Z t:description_of_request="Copies of documents including but not limited to correspondence, emails, minutes from meetings, presentation, computer records, and written offers or agreements related to the merger of UAL Corp.'s United Airlines and Continental Airlines Inc. and efforts to retain the Chicago headquarters to United." t:organization="Bloomberg News" t:requestor_name="Mary Jane Credeur" m:row_number.srzw-dcvg=2

series e:srzw-dcvg d:2010-05-12T00:00:00.000Z t:description_of_request="Current annual base pay salary for Mayor Richard M. Daley and other compensation he receives, either in the form of monitory or non monitory compensation or use of city resources (i.e. use of a car and driver) in addition to his base pay over and above standard benefits afforded regular full time city employees. Compensation for any positions Mr. Daley is compensated for by the city that might be in addition to his role as mayor.  Provide the above information for the current fiscal year and the prior fiscal year." t:organization="Journal & Topics Newspapers" t:requestor_name="Tom Robb" m:row_number.srzw-dcvg=3
```

## Meta Commands

```ls
metric m:row_number.srzw-dcvg p:long l:"Row Number"

entity e:srzw-dcvg l:"FOIA Request Log - Office of the Mayor" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/srzw-dcvg

property e:srzw-dcvg t:meta.view v:id=srzw-dcvg v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Office of the Mayor" v:attribution="City of Chicago"

property e:srzw-dcvg t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:srzw-dcvg t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name          | organization                       | description_of_request                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | date_received       | due_date            | 
| ======================= | ================================== | ===================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | =================== | =================== | 
| Mick Dumke              | Chicago Reader                     | Copy of the mayor's appointment calendar daily schedule from Nov. and Dec. of 2009 and Feb. through April of 2010.                                                                                                                                                                                                                                                                                                                                                                                                                                                    | 2010-05-04T00:00:00 | 2010-05-18T00:00:00 | 
| Mary Jane Credeur       | Bloomberg News                     | Copies of documents including but not limited to correspondence, emails, minutes from meetings, presentation, computer records, and written offers or agreements related to the merger of UAL Corp.'s United Airlines and Continental Airlines Inc. and efforts to retain the Chicago headquarters to United.                                                                                                                                                                                                                                                         | 2010-05-06T00:00:00 | 2010-05-20T00:00:00 | 
| Tom Robb                | Journal & Topics Newspapers        | Current annual base pay salary for Mayor Richard M. Daley and other compensation he receives, either in the form of monitory or non monitory compensation or use of city resources (i.e. use of a car and driver) in addition to his base pay over and above standard benefits afforded regular full time city employees. Compensation for any positions Mr. Daley is compensated for by the city that might be in addition to his role as mayor. Provide the above information for the current fiscal year and the prior fiscal year.                                | 2010-05-12T00:00:00 | 2010-05-26T00:00:00 | 
| Chris Fusco             | Chicago Sun-Times                  | Seeking copies of any and all records that the city, its law department and/or Mayor Daley's Office has on file regarding the Chicago Police Dept. security detail(s) for Mayor Daley (and/or members of his family) between Jan. 1, 2005 and April 30, 2010.                                                                                                                                                                                                                                                                                                         | 2010-05-12T00:00:00 | 2010-05-26T00:00:00 | 
| John Kugler             | Substance News                     | Any and all communications between Mayor Daley and or his staff regarding the May 11, 2010 meeting at City Hall including Chicago Teachers Union president (and AFT vice president) Marilyn Stewart, AFT president Randi Weingarten and Chicago school board president Mary Richardson-Lowry; 2) Any and all notes, meeting agenda, transcripts, records of any and all meetings referenced in item no. 1; 3) Any and all records in regarding item no. 1; and 4) any and all records in regards to the May 11, 2010 AFT president Randi Weingarten visit to Chicago. | 2010-05-24T00:00:00 | 2010-06-08T00:00:00 | 
| Alicia Ciuffini         | Self                               | Provide a list of all buildings demolished during Richard J. Daley and Richard M. Daley terms in office (including the year in which they were demolished).                                                                                                                                                                                                                                                                                                                                                                                                           | 2010-05-25T00:00:00 | 2010-06-01T00:00:00 | 
| Bhav Tibrewal           | UniteHere                          | Copies of all materials received by the Chicago City Clerk by Midway Investment & Development Corp., YVR Airport Services Ltd., and the Vancouver Airport Authority, since January 1, 2006.                                                                                                                                                                                                                                                                                                                                                                           | 2010-06-01T00:00:00 | 2010-06-08T00:00:00 | 
| John Kugler             | Substance News                     | All information and documents (notes, agenda, records, communications) of past meetings and scheduled meetings between Mayor Daley and Marilyn Stewart, President of the Chicago Teachers Union in April 2010, May 2010, and June 2010                                                                                                                                                                                                                                                                                                                                | 2010-06-01T00:00:00 | 2010-06-08T00:00:00 | 
| Chris Fusco             | Sun Times                          | Summary of all costs incurred by the Mayor's Office or any other City department (excluding police) regarding security protection for the mayor and/or his family on an annual basis between Jan. 1, 2005 and May 1, 2010.                                                                                                                                                                                                                                                                                                                                            | 2010-06-03T00:00:00 | 2010-06-10T00:00:00 | 
| Kristina T. Labanauskas | Law Offices of Barry G. Doyle P.C. | Copy of documentation, statements or reports generated from the years 2001-2008 regarding any repairs, incidents, accidents, maintenance or the like on the Dearborn Street Bridge located at 321 N. Dearborn                                                                                                                                                                                                                                                                                                                                                         | 2010-06-07T00:00:00 | 2010-06-14T00:00:00 | 
```