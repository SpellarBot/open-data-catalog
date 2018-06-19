# FOIA Request Log - 311

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-311-7895c) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/j2p9-gdf5) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/j2p9-gdf5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/j2p9-gdf5/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | j2p9-gdf5 |
| Name | FOIA Request Log - 311 |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2011-09-23T22:35:23Z |
| Publication Date | 2017-03-24T20:08:52Z |

## Description

FOIA requests received by 311 as of May 1, 2010

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
series e:j2p9-gdf5 d:2010-05-03T00:00:00.000Z t:description_of_request="COPIES OF SERVICE REQUESTS WITH CONFIRMATION NUMBERS 10-00363031, 10-00351549, 10-00327144, 10-00378866, 10-00378873 AND 10-555804 AND ALL FINDINGS/RESULTS TO THESE COMPLAINTS/VIOLATIONS." t:organization=N/A t:requestor_name="MORRIS, PHILLIP J." m:row_number.j2p9-gdf5=1

series e:j2p9-gdf5 d:2010-05-06T00:00:00.000Z t:description_of_request="COPIES OF 311 COMPLAINTS ABOUT THIS BUILDING" t:organization=N/A t:requestor_name="DOMBROWSKI, JAMES" m:row_number.j2p9-gdf5=2

series e:j2p9-gdf5 d:2010-05-07T00:00:00.000Z t:description_of_request="COPIES OF AN ARREST RECORD" t:organization=N/A t:requestor_name="MICHALSKI, MARY" m:row_number.j2p9-gdf5=3
```

## Meta Commands

```ls
metric m:row_number.j2p9-gdf5 p:long l:"Row Number"

entity e:j2p9-gdf5 l:"FOIA Request Log - 311" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/j2p9-gdf5

property e:j2p9-gdf5 t:meta.view v:id=j2p9-gdf5 v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - 311" v:attribution="City of Chicago"

property e:j2p9-gdf5 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:j2p9-gdf5 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name         | organization                  | description_of_request                                                                                                                                                                                                                                                                                                                                                                                                          | date_received       | due_date            | 
| ====================== | ============================= | =============================================================================================================================================================================================================================================================================================================================================================================================================================== | =================== | =================== | 
| MORRIS, PHILLIP J.     | N/A                           | COPIES OF SERVICE REQUESTS WITH CONFIRMATION NUMBERS 10-00363031, 10-00351549, 10-00327144, 10-00378866, 10-00378873 AND 10-555804 AND ALL FINDINGS/RESULTS TO THESE COMPLAINTS/VIOLATIONS.                                                                                                                                                                                                                                     | 2010-05-03T00:00:00 | 2010-05-10T00:00:00 | 
| DOMBROWSKI, JAMES      | N/A                           | COPIES OF 311 COMPLAINTS ABOUT THIS BUILDING                                                                                                                                                                                                                                                                                                                                                                                    | 2010-05-06T00:00:00 | 2010-05-13T00:00:00 | 
| MICHALSKI, MARY        | N/A                           | COPIES OF AN ARREST RECORD                                                                                                                                                                                                                                                                                                                                                                                                      | 2010-05-07T00:00:00 | 2010-05-14T00:00:00 | 
| MONROE, VENUS          | N/A                           | COPY OF THE REPORT NUMBER 10-00547727 REGARDING A TREE FALLING ON MY CAR AND A STATEMENT SAYING THE TREE WAS DEAD.                                                                                                                                                                                                                                                                                                              | 2010-05-07T00:00:00 | 2010-05-14T00:00:00 | 
| GUERRERO, CYNTHIA      | N/A                           | SERVICE REQUESTS FOR THE LAST MONTH REQUESTING GARBAGE PICKED UP.                                                                                                                                                                                                                                                                                                                                                               | 2010-05-14T00:00:00 | 2010-05-21T00:00:00 | 
| CHANDABHAI, SHABBIR    | BURHANI DESIGN-BUILD          | CHECK RECORDS - 1. BUILDING CODE VIOLATIONS OR ANY HOLDS BY THE DEPT OF BUILDINGS; 2. RECORDS IF ANY BUILDING PERMITS WERE EVER TAKEN FOR THIS BLDG; 3. ZONING VIOLATION OR AN HOLDS BY THE DEPT OF ZONING; 4. CHECK FOR ANY RECORD OF FIRE, VACANT PROPERTY, ETC. FOR THIS BLDG; 5. ANY HOLDS BY THE DEPT OF BLDG LANDMARKS; 6. ANY LIENS OR HOLDS BY THE DEPT OF REVENUE; 6. ANY LIENS OR HOLDS BY THE COOK COUNTY TREASURER; | 2010-05-14T00:00:00 | 2010-05-21T00:00:00 | 
| CRUMP, STANLEY ANTHONY | N/A                           | EVENT QUERY PRINTOUTS OF THE 311 AND 911 CALLS I MADE ON MONDAY, MAY 10, 2010.                                                                                                                                                                                                                                                                                                                                                  | 2010-05-17T00:00:00 | 2010-05-24T00:00:00 | 
| CRUMP, STANLEY ANTHONY | N/A                           | FOIA TRANSCRIPTS OF THE DIALOGUES I HAD WITH THE 311 AND 911 OPERATORS.                                                                                                                                                                                                                                                                                                                                                         | 2010-05-19T00:00:00 | 2010-05-26T00:00:00 | 
| LEE, ANTHONY           | N/A                           | KEEP GETTING RAIN WATER IN BASEMENT                                                                                                                                                                                                                                                                                                                                                                                             | 2010-05-21T00:00:00 | 2010-05-28T00:00:00 | 
| NOT PROVIDED           | PROPERTY FIELD SERVICES, INC. | ADVISE OR PROVIDE CURRENT OR ANY COPY OF OUTSTANDING VIOLATION ON HOUSE                                                                                                                                                                                                                                                                                                                                                         | 2010-05-24T00:00:00 | 2010-06-01T00:00:00 | 
```