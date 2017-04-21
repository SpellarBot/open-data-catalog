# DYCD after-school programs: Runaway And Homeless Youth

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-runaway-and-homeless-youth-00a40) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ujsc-un6m) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ujsc-un6m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ujsc-un6m/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ujsc-un6m |
| Name | DYCD after-school programs: Runaway And Homeless Youth |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Social Services |
| Tags | jobs and economic mobility, education, services, youth, community, development, community development, school, child, children, after-school, after-school programs, programs, young adult, runaway,... |
| Created | 2011-09-02T19:21:30Z |
| Publication Date | 2013-06-21T19:31:53Z |

## Description

Facilities in New York City, by agency and site,  that offer after-school programs for runaway and homeless youth, including street outreach programs, drop-in centers, crisis shelters, and transitional independent living (TIL) programs.
Update Frequency: Annually

## Columns

```ls
| Included | Schema Type | Field Name            | Name                    | Data Type | Render Type |
| ======== | =========== | ===================== | ======================= | ========= | =========== |
| No       | time        | :updated_at           | updated_at              | meta_data | meta_data   |
| Yes      | series tag  | program_type          | PROGRAM TYPE            | text      | text        |
| Yes      | series tag  | program               | PROGRAM                 | text      | text        |
| Yes      | series tag  | site_name             | SITE NAME               | text      | text        |
| Yes      | series tag  | borough_community     | BOROUGH / COMMUNITY     | text      | text        |
| Yes      | series tag  | agency                | AGENCY                  | text      | text        |
| Yes      | series tag  | contact_number        | Contact Number          | text      | text        |
| Yes      | series tag  | grade_level_age_group | Grade Level / Age Group | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ujsc-un6m d:2011-09-02T12:21:31.000Z t:contact_number=646.485.6900 t:program_type="Runaway & Homeless Youth" t:borough_community=Manhattan t:program="Transitional Independent Living (TIL)" t:agency="Good Shepherd Services" t:site_name="Good Shepherd Services" m:row_number.ujsc-un6m=1

series e:ujsc-un6m d:2011-09-02T12:21:31.000Z t:contact_number="212.491.5911 ext. 13" t:program_type="Runaway & Homeless Youth" t:borough_community=Manhattan t:program="Transitional Independent Living (TIL)" t:agency="Green Chimneys" t:site_name="Green Chimneys" m:row_number.ujsc-un6m=2

series e:ujsc-un6m d:2011-09-02T12:21:31.000Z t:contact_number="212.926.8089 ext. 25" t:program_type="Runaway & Homeless Youth" t:borough_community=Manhattan t:program="Transitional Independent Living (TIL)" t:agency="Girls Educational & Mentoring Services, Inc." t:site_name="Girls Educational & Mentoring Services, Inc." m:row_number.ujsc-un6m=3
```

## Meta Commands

```ls
metric m:row_number.ujsc-un6m p:long l:"Row Number"

entity e:ujsc-un6m l:"DYCD after-school programs: Runaway And Homeless Youth" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/ujsc-un6m

property e:ujsc-un6m t:meta.view v:id=ujsc-un6m v:category="Social Services" v:averageRating=0 v:name="DYCD after-school programs: Runaway And Homeless Youth" v:attribution="Department of Youth and Community Development (DYCD)"

property e:ujsc-un6m t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ujsc-un6m t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | program_type                                              | program                               | site_name                                    | borough_community | agency                                       | contact_number       | grade_level_age_group | 
| =========== | ========================================================= | ===================================== | ============================================ | ================= | ============================================ | ==================== | ===================== | 
| 1314966091  | Runaway & Homeless Youth                                  | Transitional Independent Living (TIL) | Good Shepherd Services                       | Manhattan         | Good Shepherd Services                       | 646.485.6900         |                       | 
| 1314966091  | Runaway & Homeless Youth                                  | Transitional Independent Living (TIL) | Green Chimneys                               | Manhattan         | Green Chimneys                               | 212.491.5911 ext. 13 |                       | 
| 1314966091  | Runaway & Homeless Youth                                  | Transitional Independent Living (TIL) | Girls Educational & Mentoring Services, Inc. | Manhattan         | Girls Educational & Mentoring Services, Inc. | 212.926.8089 ext. 25 |                       | 
| 1314966091  | Runaway & Homeless Youth                                  | Transitional Independent Living (TIL) | Inwood House                                 | Manhattan         | Inwood house                                 | 212.861.4325         |                       | 
| 1314966091  | Runaway & Homeless Youth                                  | Transitional Independent Living (TIL) | SCO Family of Services                       | Brooklyn          | SCO Family of Services                       | 718.827.8465         |                       | 
| 1314966091  | Runaway & Homeless Youth                                  | Transitional Independent Living (TIL) | SCO Family of Services                       | Brooklyn          | SCO Family of Services                       | 718.782.0198         |                       | 
| 1314966091  | Runaway & Homeless Youth                                  | Transitional Independent Living (TIL) | SCO Family of Services                       | Brooklyn          | SCO Family of Services                       | 718.326.5931         |                       | 
| 1314966091  | Runaaway & Homeless Youth Transitional Independent Living |                                       | SCO Family of Services IV                    | Queens            | SCO Family of Services                       | 718.217.5613         |                       | 
| 1314966091  | Runaaway & Homeless Youth Transitional Independent Living |                                       | Safe Space NYC, Inc                          | Queens            | Safe Space NYC, Inc                          | 718.526.3000         |                       | 
| 1314966091  | Runaway & Homeless Youth                                  | Transitional Independent Living (TIL) | Rachel's Place                               | Brooklyn          | Rachel's Place                               | 718.253.5364         |                       | 
```