# FOIA Request Log - Streets & Sanitation

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-streets-sanitation-2d7ac) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/zpd8-zq4w) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/zpd8-zq4w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/zpd8-zq4w/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | zpd8-zq4w |
| Name | FOIA Request Log - Streets & Sanitation |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2011-09-26T22:10:51Z |
| Publication Date | 2017-04-19T21:09:15Z |

## Description

FOIA requests received by Streets and Sanitation as of May 1, 2010

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
series e:zpd8-zq4w d:2010-05-03T00:00:00.000Z t:description_of_request="copies of all expense reports cell phones (with gps)purchased for dept. drivers for the last 3 yrs. Copies of expense reports for all gps systems purchased for department trucks for the last 3 yrs. Include how many phones/gps units were purchased, date of purchase,what brand/type, company purchased from, dollar amoutn paid per phone/unit, and monthly service charges for ea. phone/unit" t:organization="Fox Chicago News" t:requestor_name="Diane Carbonara" m:row_number.zpd8-zq4w=1

series e:zpd8-zq4w d:2010-05-03T00:00:00.000Z t:description_of_request="total amt of tonnage and revenue subcontracted out by allied waste from transfer sites. Loop 64th street and calumet state street through period nov. 9 - april 1 2010" t:organization="Linda construction" t:requestor_name="Shanee McGee" m:row_number.zpd8-zq4w=2

series e:zpd8-zq4w d:2010-05-05T00:00:00.000Z t:description_of_request="reports of de paul university for the last 3 years and also to be informed as to what these docs are clearly as. Plastic, water, e-waste, paper and glass waste" t:requestor_name="David Connell" m:row_number.zpd8-zq4w=3
```

## Meta Commands

```ls
metric m:row_number.zpd8-zq4w p:long l:"Row Number"

entity e:zpd8-zq4w l:"FOIA Request Log - Streets & Sanitation" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/zpd8-zq4w

property e:zpd8-zq4w t:meta.view v:id=zpd8-zq4w v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Streets & Sanitation" v:attribution="City of Chicago"

property e:zpd8-zq4w t:meta.view.owner v:id=e872-itfe v:screenName=Rosa v:displayName=Rosa

property e:zpd8-zq4w t:meta.view.tableauthor v:id=e872-itfe v:screenName=Rosa v:roleName=editor v:displayName=Rosa
```

## Top Records

```ls
| requestor_name      | organization           | description_of_request                                                                                                                                                                                                                                                                                                                                                                              | date_received       | due_date            | 
| =================== | ====================== | =================================================================================================================================================================================================================================================================================================================================================================================================== | =================== | =================== | 
| Diane Carbonara     | Fox Chicago News       | copies of all expense reports cell phones (with gps)purchased for dept. drivers for the last 3 yrs. Copies of expense reports for all gps systems purchased for department trucks for the last 3 yrs. Include how many phones/gps units were purchased, date of purchase,what brand/type, company purchased from, dollar amoutn paid per phone/unit, and monthly service charges for ea. phone/unit | 2010-05-03T00:00:00 | 2010-05-10T00:00:00 | 
| Shanee McGee        | Linda construction     | total amt of tonnage and revenue subcontracted out by allied waste from transfer sites. Loop 64th street and calumet state street through period nov. 9 - april 1 2010                                                                                                                                                                                                                              | 2010-05-03T00:00:00 | 2010-05-10T00:00:00 | 
| David Connell       |                        | reports of de paul university for the last 3 years and also to be informed as to what these docs are clearly as. Plastic, water, e-waste, paper and glass waste                                                                                                                                                                                                                                     | 2010-05-05T00:00:00 | 2010-05-10T00:00:00 | 
| Marina Para         | Asst. State's Attorney | vehicle tow reports/2004 dodge caravan                                                                                                                                                                                                                                                                                                                                                              | 2010-05-01T00:00:00 | 2010-05-05T00:00:00 | 
| Marina Para         | Asst. State's Attorney | vehicle tow reports/2002 ford explorer                                                                                                                                                                                                                                                                                                                                                              | 2010-05-01T00:00:00 | 2010-05-05T00:00:00 | 
| Alexandra Molesky   | Asst. State's Attorney | vehicle tow reports/1990 chevrolet corsica                                                                                                                                                                                                                                                                                                                                                          | 2010-05-03T00:00:00 | 2010-05-06T00:00:00 | 
| Lisa Mateck         | Asst. State's Attorney | vehicle tow reports                                                                                                                                                                                                                                                                                                                                                                                 | 2010-05-03T00:00:00 | 2010-05-04T00:00:00 | 
| Teresa Molina       | Asst. State's Attorney | vehicle tow reports/                                                                                                                                                                                                                                                                                                                                                                                | 2010-05-04T00:00:00 | 2010-05-06T00:00:00 | 
| Lorna Amado-Chevlin | Asst. State's Attorney | vehicle tow reports//2000 chevy van                                                                                                                                                                                                                                                                                                                                                                 | 2010-05-10T00:00:00 | 2010-05-17T00:00:00 | 
| Lorna Amado-Chevlin | Asst. State's Attorney | vehicle tow reports/1996 dodge                                                                                                                                                                                                                                                                                                                                                                      | 2010-05-10T00:00:00 | 2010-05-17T00:00:00 | 
```