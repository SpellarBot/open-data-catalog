# FOIA Request Log - Cultural Affairs & Special Events

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-cultural-affairs-special-events-d458f) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ikdf-ernx) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ikdf-ernx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ikdf-ernx/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ikdf-ernx |
| Name | FOIA Request Log - Cultural Affairs & Special Events |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2012-03-06T23:37:19Z |
| Publication Date | 2017-04-04T15:36:44Z |

## Description

FOIA requests received by Cultural Affairs & Special Events as of January 1, 2011.

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
series e:ikdf-ernx d:2017-04-03T00:00:00.000Z t:description_of_request="This is a request under the Freedom of Information Act for the timeframe dating back to January 1, 2012, please provide 1) Any and all records detailing all cultural grants the City of Chicago has awarded through the Department of Cultural Affairs and Special Events, including showing whom/who/what organization received a grant and how much they received 2) Any and all agreements between the city and the grant recipient detailing what the grant was for." t:requestor_name="Holly Bresnahan" m:row_number.ikdf-ernx=1

series e:ikdf-ernx d:2017-03-16T00:00:00.000Z t:description_of_request="Requesting any and all information/documents related to Mahoney?s Irish Pub, 551 N. Ogden Ave. Chicago IL 60642 and related to Mahoney?s Irish Fest held Saturday March 11th 2017  including Permit Applications, and Permits issued." t:organization="1147 West Ohio Street Condominium Association" t:requestor_name="Eric Hausman" m:row_number.ikdf-ernx=2

series e:ikdf-ernx d:2017-03-15T00:00:00.000Z t:description_of_request="This is a request under the Freedom of Information Act for the timeframe dating back to January 1, 2011, please provide
 
1)      Any and all records detailing all cultural grants the City of Chicago has awarded through the Department of Cultural Affairs and Special Events, including showing whom/who/what organization received a grant and how much they received
2)      Any and all agreements between the city and the grant recipient detailing what the grant was for" t:organization="Chicago Tribune" t:requestor_name="Gregory Pratt" m:row_number.ikdf-ernx=3
```

## Meta Commands

```ls
metric m:row_number.ikdf-ernx p:long l:"Row Number"

entity e:ikdf-ernx l:"FOIA Request Log - Cultural Affairs & Special Events" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/ikdf-ernx

property e:ikdf-ernx t:meta.view v:id=ikdf-ernx v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Cultural Affairs & Special Events" v:attribution="City of Chicago"

property e:ikdf-ernx t:meta.view.owner v:id=h3r9-bcg7 v:screenName=nora v:displayName=nora

property e:ikdf-ernx t:meta.view.tableauthor v:id=h3r9-bcg7 v:screenName=nora v:roleName=editor v:displayName=nora
```

## Top Records

```ls
| requestor_name     | organization                                  | description_of_request                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | date_received       | due_date            | 
| ================== | ============================================= | ============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================ | =================== | =================== | 
| Holly Bresnahan    |                                               | This is a request under the Freedom of Information Act for the timeframe dating back to January 1, 2012, please provide 1) Any and all records detailing all cultural grants the City of Chicago has awarded through the Department of Cultural Affairs and Special Events, including showing whom/who/what organization received a grant and how much they received 2) Any and all agreements between the city and the grant recipient detailing what the grant was for.                                    | 2017-04-03T00:00:00 | 2017-04-10T00:00:00 | 
| Eric Hausman       | 1147 West Ohio Street Condominium Association | Requesting any and all information/documents related to Mahoney?s Irish Pub, 551 N. Ogden Ave. Chicago IL 60642 and related to Mahoney?s Irish Fest held Saturday March 11th 2017 including Permit Applications, and Permits issued.                                                                                                                                                                                                                                                                         | 2017-03-16T00:00:00 | 2017-03-23T00:00:00 | 
| Gregory Pratt      | Chicago Tribune                               | This is a request under the Freedom of Information Act for the timeframe dating back to January 1, 2011, please provide 1) Any and all records detailing all cultural grants the City of Chicago has awarded through the Department of Cultural Affairs and Special Events, including showing whom/who/what organization received a grant and how much they received 2) Any and all agreements between the city and the grant recipient detailing what the grant was for                                     | 2017-03-15T00:00:00 | 2017-03-22T00:00:00 | 
| Luis Caycho        |                                               | Requesting requirements and permits needed to host a small 5k event.                                                                                                                                                                                                                                                                                                                                                                                                                                         | 2017-02-14T00:00:00 | 2017-02-22T00:00:00 | 
| Jonah Meadows      | Editor, Patch.com                             | Pursuant to the Illinois Freedom of Information Act (5 ILCS 140/1 to 11), I hereby request the following records: All email communication involving the accounts of Mark Kelly, Janeth Stines, Mary Slowik, Erin Bauer, Jeneene Brown-Mosley, Lillie Dix, Tom Gray, Ivy Hall, Ann Hickey, Jennifer Johnson Washington, Connor Kelly, James Brundage or Yescenia Mota that contains any of the following keywords, "MLS All-Star Game," "ASG", "MLS", "All-Star" from September 8, 2016, to January 30, 2017. | 2017-01-28T00:00:00 | 2017-02-07T00:00:00 | 
| Tim Hecke          |                                               | This is a request under the Freedom of Information Act for applications and permit requests submitted for the 2017 Chicago Pride Parade.                                                                                                                                                                                                                                                                                                                                                                     | 2017-01-12T00:00:00 | 2017-01-20T00:00:00 | 
| Scarlett Melton    |                                               | Requesting copy of Magnificent Mile Parade 2016 contracted vendors (i.e., trucking companies contracted / hired to drive trucks that pull floats) - specifically the trucking / transportation company who is hired to drive the trucks that pull the floats designed by Expo Designers Co.                                                                                                                                                                                                                  | 2016-12-15T00:00:00 | 2016-12-22T00:00:00 | 
| Camaron Santos     | Loyola University Chicago                     | Requesting the personnel and payroll records within the cultural affairs and speical events sector for either 2015 or 2016.                                                                                                                                                                                                                                                                                                                                                                                  | 2016-11-24T00:00:00 | 2016-12-02T00:00:00 | 
| Hanako Maki        | Loyola University Chicago                     | Requesting all documents and information pertaining to the Christkindlmarket from 2010-2016.                                                                                                                                                                                                                                                                                                                                                                                                                 | 2016-11-23T00:00:00 | 2016-12-01T00:00:00 | 
| Madeline Wakenight | Loyola University Chicago                     | Requesting a copy of the following record(s): The expenditures on the strings of Christmas lights on the trees along Michigan avenue this winter.                                                                                                                                                                                                                                                                                                                                                            | 2016-11-22T00:00:00 | 2016-11-30T00:00:00 | 
```