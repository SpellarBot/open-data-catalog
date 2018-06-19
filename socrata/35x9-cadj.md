# CT DCF Differential Response System Reports Accepted by Response Time and Type

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ct-dcf-differential-response-system-reports-accepted-by-response-time-and-type) |
| Metadata | [Link](https://data.ct.gov/api/views/35x9-cadj) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/35x9-cadj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/35x9-cadj/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 35x9-cadj |
| Name | CT DCF Differential Response System Reports Accepted by Response Time and Type |
| Attribution | CT Department of Children and Families, Office for Research and Evaluation |
| Category | Health and Human Services |
| Tags | ct, dcf, department of children and families, abuse, neglect, reports, family assessment response, response time |
| Created | 2015-07-14T19:30:07Z |
| Publication Date | 2015-07-23T14:34:01Z |

## Description

This dataset contains aggregate data by State Fiscal Year for all reports of abuse/neglect accepted by DCF for either a traditional Child Protective Services (CPS) Investigation, or as of SFY2012, a Family Assessment Response (FAR). Figures are provided by mandated Response Time and Response Type, for each DCF Area Office each SFY beginning with 2005.  Each report accepted is screened for safety and risk factors, and assigned an amount of time within which the agency is required to respond to the report.  Mandated response times include ?Same Day?, ?24 Hours?, and ?72 Hours?.  Traditionally, DCF has had only one manner of responding to such reports, which was a mandated Child Protective Services (CPS) Investigation.  As of April 2012, DCF began responding to low-risk reports through a voluntary Family Assessment Response (FAR) process.  Reports handled through a FAR response still contain allegations that meet the statutory definitions of neglect, but they do not receive a decision concerning whether they are substantiated or not.  This policy has resulted in fewer substantiated allegations since its implementation, but the agency continues to serve as many or more families reported for abuse/neglect.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| Yes      | time           | data_as_of              | DATA_AS_OF              | calendar_date | calendar_date |
| Yes      | series tag     | sfy                     | SFY                     | text          | text          |
| Yes      | series tag     | region                  | REGION                  | text          | text          |
| Yes      | series tag     | office                  | OFFICE                  | text          | text          |
| No       |                | response_time           | RESPONSE_TIME           | text          | text          |
| Yes      | numeric metric | total_responses         | TOTAL_RESPONSES         | number        | number        |
| Yes      | numeric metric | intake_responses        | INTAKE_RESPONSES        | number        | number        |
| Yes      | numeric metric | far_to_intake_responses | FAR_TO_INTAKE_RESPONSES | number        | number        |
| Yes      | numeric metric | far_responses           | FAR_RESPONSES           | number        | number        |
```

## Time Field

```ls
Value = data_as_of
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = response_time
```

## Data Commands

```ls
series e:35x9-cadj d:2014-09-15T00:00:00.000Z t:office=NULL t:region=OTHER t:sfy=SFY2010 m:total_responses=15 m:intake_responses=15 m:far_to_intake_responses=0 m:far_responses=0

series e:35x9-cadj d:2014-09-15T00:00:00.000Z t:office=NULL t:region=OTHER t:sfy=SFY2010 m:total_responses=43 m:intake_responses=43 m:far_to_intake_responses=0 m:far_responses=0

series e:35x9-cadj d:2014-09-15T00:00:00.000Z t:office=NULL t:region=OTHER t:sfy=SFY2010 m:total_responses=1 m:intake_responses=1 m:far_to_intake_responses=0 m:far_responses=0
```

## Meta Commands

```ls
metric m:total_responses p:integer l:TOTAL_RESPONSES t:dataTypeName=number

metric m:intake_responses p:integer l:INTAKE_RESPONSES t:dataTypeName=number

metric m:far_to_intake_responses p:integer l:FAR_TO_INTAKE_RESPONSES t:dataTypeName=number

metric m:far_responses p:integer l:FAR_RESPONSES t:dataTypeName=number

entity e:35x9-cadj l:"CT DCF Differential Response System Reports Accepted by Response Time and Type" t:attribution="CT Department of Children and Families, Office for Research and Evaluation" t:url=https://data.ct.gov/api/views/35x9-cadj

property e:35x9-cadj t:meta.view v:id=35x9-cadj v:category="Health and Human Services" v:averageRating=0 v:name="CT DCF Differential Response System Reports Accepted by Response Time and Type" v:attribution="CT Department of Children and Families, Office for Research and Evaluation"

property e:35x9-cadj t:meta.view.license v:name="Public Domain"

property e:35x9-cadj t:meta.view.owner v:id=hd87-ziyn v:screenName="Fred North" v:displayName="Fred North"

property e:35x9-cadj t:meta.view.tableauthor v:id=hd87-ziyn v:screenName="Fred North" v:roleName=editor v:displayName="Fred North"
```

## Top Records

```ls
| data_as_of          | sfy     | region | office                      | response_time | total_responses | intake_responses | far_to_intake_responses | far_responses | 
| =================== | ======= | ====== | =========================== | ============= | =============== | ================ | ======================= | ============= | 
| 2014-09-15T00:00:00 | SFY2010 | OTHER  | NULL                        | 24 Hours      | 15              | 15               | 0                       | 0             | 
| 2014-09-15T00:00:00 | SFY2010 | OTHER  | NULL                        | 72 Hours      | 43              | 43               | 0                       | 0             | 
| 2014-09-15T00:00:00 | SFY2010 | OTHER  | NULL                        | Same Day      | 1               | 1                | 0                       | 0             | 
| 2014-09-15T00:00:00 | SFY2010 | OTHER  | Central Office              | 24 Hours      | 45              | 45               | 0                       | 0             | 
| 2014-09-15T00:00:00 | SFY2010 | OTHER  | Central Office              | 72 Hours      | 80              | 80               | 0                       | 0             | 
| 2014-09-15T00:00:00 | SFY2010 | OTHER  | Central Office              | Same Day      | 5               | 5                | 0                       | 0             | 
| 2014-09-15T00:00:00 | SFY2010 | OTHER  | Special Invest. Unit Office | 24 Hours      | 115             | 115              | 0                       | 0             | 
| 2014-09-15T00:00:00 | SFY2010 | OTHER  | Special Invest. Unit Office | 72 Hours      | 390             | 390              | 0                       | 0             | 
| 2014-09-15T00:00:00 | SFY2010 | OTHER  | Special Invest. Unit Office | Same Day      | 40              | 40               | 0                       | 0             | 
| 2014-09-15T00:00:00 | SFY2010 | OTHER  | Special Invest. Unit Office | Unassigned    | 1               | 1                | 0                       | 0             | 
```