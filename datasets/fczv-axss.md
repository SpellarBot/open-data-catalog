# 2013-15 Boating Facilitties Grants-Test

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-15-boating-facilitties-grants-test-74bf5) |
| Metadata | [Link](https://data.oregon.gov/api/views/fczv-axss) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/fczv-axss/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/fczv-axss/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | fczv-axss |
| Name | 2013-15 Boating Facilitties Grants-Test |
| Attribution | Oregon State Marine Board |
| Category | Recreation |
| Tags | 2013-15 boating facilitties grants |
| Created | 2013-05-08T21:49:33Z |
| Publication Date | 2013-05-10T20:07:49Z |

## Description

2013-15 Boating Facilitties Grants

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| No       |                | fg                     | FG#                    | text      | text        |
| Yes      | series tag     | project                | Project                | text      | text        |
| Yes      | series tag     | facility_name          | Facility Name          | text      | text        |
| Yes      | series tag     | waterbody              | Waterbody              | text      | text        |
| Yes      | series tag     | applicant              | Applicant              | text      | text        |
| Yes      | series tag     | before_project_photo   | Before Project Photo   | photo     | photo       |
| Yes      | series tag     | during_project_photo   | During Project Photo   | photo     | photo       |
| Yes      | series tag     | finished_project_photo | Finished Project Photo | photo     | photo       |
| Yes      | series tag     | rating                 | Rating                 | text      | text        |
| Yes      | numeric metric | in_kind_funding        | In-kind Funding        | money     | money       |
| Yes      | numeric metric | cash                   | Cash                   | money     | money       |
| Yes      | numeric metric | federal_other          | Federal/Other          | money     | money       |
| Yes      | numeric metric | approved               | Approved               | money     | money       |
| Yes      | numeric metric | total                  | Total                  | money     | money       |
| Yes      | series tag     | comments               | Comments               | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = fg
```

## Data Commands

```ls
series e:fczv-axss d:2013-01-01T00:00:00.000Z t:project="Summer 2013 Projects" t:applicant=OYCC t:comments="9 projects, 58, youth, 37 sites" m:total=206092 m:in_kind_funding=135020 m:federal_other=0 m:approved=71072 m:cash=0

series e:fczv-axss d:2013-01-01T00:00:00.000Z t:project="Rooke-Higgins Property Acquisition" t:waterbody="Millicoma River" t:applicant=ODFW t:comments="Withdrawn 2009-11" m:total=256150 m:in_kind_funding=6150 m:federal_other=187500 m:approved=62500 m:cash=0

series e:fczv-axss d:2013-01-01T00:00:00.000Z t:facility_name="Round One Total" m:total=9771628 m:in_kind_funding=683997 m:federal_other=573350 m:approved=6224258 m:cash=2290023
```

## Meta Commands

```ls
metric m:in_kind_funding p:double l:"In-kind Funding" t:dataTypeName=money

metric m:cash p:double l:Cash t:dataTypeName=money

metric m:federal_other p:double l:Federal/Other t:dataTypeName=money

metric m:approved p:integer l:Approved t:dataTypeName=money

metric m:total p:integer l:Total t:dataTypeName=money

entity e:fczv-axss l:"2013-15 Boating Facilitties Grants-Test" t:attribution="Oregon State Marine Board" t:url=https://data.oregon.gov/api/views/fczv-axss

property e:fczv-axss t:meta.view v:id=fczv-axss v:category=Recreation v:averageRating=0 v:name="2013-15 Boating Facilitties Grants-Test" v:attribution="Oregon State Marine Board"

property e:fczv-axss t:meta.view.owner v:id=iehq-inwk v:profileImageUrlMedium=/api/users/iehq-inwk/profile_images/THUMB v:profileImageUrlLarge=/api/users/iehq-inwk/profile_images/LARGE v:screenName=CRussell v:profileImageUrlSmall=/api/users/iehq-inwk/profile_images/TINY v:displayName=CRussell

property e:fczv-axss t:meta.view.tableauthor v:id=iehq-inwk v:profileImageUrlMedium=/api/users/iehq-inwk/profile_images/THUMB v:profileImageUrlLarge=/api/users/iehq-inwk/profile_images/LARGE v:screenName=CRussell v:profileImageUrlSmall=/api/users/iehq-inwk/profile_images/TINY v:roleName=editor v:displayName=CRussell
```

## Top Records

```ls
| fg   | project                                             | facility_name          | waterbody            | applicant         | before_project_photo | during_project_photo | finished_project_photo | rating | in_kind_funding | cash    | federal_other | approved | total   | comments                        | 
| ==== | =================================================== | ====================== | ==================== | ================= | ==================== | ==================== | ====================== | ====== | =============== | ======= | ============= | ======== | ======= | =============================== | 
| 1477 | Summer 2013 Projects                                |                        |                      | OYCC              |                      |                      |                        |        | 135020          | 0.0     | 0.0           | 71072    | 206092  | 9 projects, 58, youth, 37 sites | 
| 1478 | Rooke-Higgins Property Acquisition                  |                        | Millicoma River      | ODFW              |                      |                      |                        |        | 6150            | 0.0     | 187500        | 62500    | 256150  | Withdrawn 2009-11               | 
|      |                                                     | Round One Total        |                      |                   |                      |                      |                        |        | 683997          | 2290023 | 573350        | 6224258  | 9771628 |                                 | 
| 1480 | John Day Ramp Boarding Float Replacement            | John Day Ramp          | John Day River       | Clatsop County    |                      |                      |                        |        | 2355            | 28750   | 0.0           | 86250    | 117355  | Withdrawn 2011-13               | 
| 1484 | Ojalla Park Facility Improvement                    | Ojalla Bridge          | Siletz River         | Lincoln County    |                      |                      |                        |        | 12100           | 12000   |               |          | 24100   | 2011-13 grant for permitting    | 
| 1485 | Rogers Landing Boarding Float Replacement           | Rogers Landing         | Willamette River     | Yamhill County    |                      |                      |                        |        | 9050            | 25000   | 0.0           | 255400   | 289450  | Untreated wood issue            | 
| 1489 | Milwaukie Riverfront Park Ramp & Parking            | Jefferson Street       | Willamette River     | City of Milwaukie |                      |                      |                        |        | 40913           | 959160  | 0.0           | 1200000  | 2200073 |                                 | 
| 1492 | Hendricks Bridge Ramp Replacement                   | Hendrick's Bridge Park | McKenzie River       | Lane County       |                      |                      |                        |        | 50000           | 0.0     | 0.0           | 581000   | 631000  | $21,000 permit fees?            | 
| 1493 | Orchard Point Transient Float Replacement & Pumpout | Orchard Point Park     | Fern Ridge Reservoir | Lane County       |                      |                      |                        |        | 20000           | 0.0     | 0.0           | 151000   | 171000  |                                 | 
| 1494 | Triangle Lake Boarding Floats & Vault Restroom      | Triangle Lake Landing  | Triangle Lake        | Lane County       |                      |                      |                        |        | 0.0             | 0.0     | 0.0           | 166400   | 166400  |                                 | 
```