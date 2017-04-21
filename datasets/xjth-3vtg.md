# L&I Affidavit - Apprentice Level Worker Details

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/li-affidavit-apprentice-level-worker-details) |
| Metadata | [Link](https://data.wa.gov/api/views/xjth-3vtg) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/xjth-3vtg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/xjth-3vtg/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | xjth-3vtg |
| Name | L&I Affidavit - Apprentice Level Worker Details |
| Attribution | L&I |
| Category | Labor |
| Tags | affidavit, apprentice, worker, wage, hours |
| Created | 2015-11-05T22:25:13Z |
| Publication Date | 2015-12-03T00:30:31Z |

## Description

Apprentice Level Worker Details

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type | Render Type |
| ======== | ============== | =================================== | =================================== | ========= | =========== |
| No       | time           | :updated_at                         | updated_at                          | meta_data | meta_data   |
| Yes      | series tag     | affidavit_id_number                 | Affidavit ID Number                 | text      | number      |
| Yes      | series tag     | apprentice_id_number                | Apprentice ID Number                | text      | text        |
| Yes      | numeric metric | number_of_hours_worked              | Number Of Hours Worked              | number    | text        |
| Yes      | series tag     | apprentice_occupation_name          | Apprentice Occupation Name          | text      | text        |
| Yes      | series tag     | apprentice_program_name             | Apprentice Program Name             | text      | text        |
| Yes      | series tag     | state_the_apprentice_is_registered  | Registered State                    | text      | text        |
| Yes      | numeric metric | hourly_wage_rate                    | Hourly Wage Rate                    | number    | number      |
| Yes      | numeric metric | hourly_fringe_benefits_rate         | Hourly Fringe Benefits Rate         | number    | number      |
| Yes      | numeric metric | apprentice_beginning_hours_per_step | Apprentice Beginning Hours Per Step | number    | number      |
| Yes      | numeric metric | apprentice_ending_hours_per_step    | Apprentice Ending Hours Per Step    | number    | number      |
| Yes      | series tag     | job_classification                  | Job Classification                  | text      | text        |
| Yes      | series tag     | county_name                         | County Name                         | text      | text        |
| Yes      | series tag     | prevailing_wage_trade               | Prevailing Wage Trade               | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xjth-3vtg d:2015-11-05T14:25:24.000Z t:affidavit_id_number=2279 t:county_name=Clark t:prevailing_wage_trade="ELECTRICIANS - INSIDE" m:apprentice_ending_hours_per_step=1000 m:hourly_fringe_benefits_rate=1.88 m:hourly_wage_rate=15.44 m:apprentice_beginning_hours_per_step=0

series e:xjth-3vtg d:2015-11-05T14:25:25.000Z t:apprentice_id_number=132613 t:affidavit_id_number=11899 t:apprentice_occupation_name=ROOFER t:county_name=Mason t:prevailing_wage_trade=ROOFERS t:state_the_apprentice_is_registered=WA m:apprentice_ending_hours_per_step=3270 m:hourly_fringe_benefits_rate=6.69 m:hourly_wage_rate=22.27 m:apprentice_beginning_hours_per_step=2451

series e:xjth-3vtg d:2015-11-05T14:25:25.000Z t:apprentice_id_number=128630 t:affidavit_id_number=12574 t:apprentice_occupation_name=LATHER t:county_name=King t:prevailing_wage_trade=LATHERS t:state_the_apprentice_is_registered=WA m:apprentice_ending_hours_per_step=4000 m:hourly_fringe_benefits_rate=8.25 m:hourly_wage_rate=21.84 m:apprentice_beginning_hours_per_step=3001
```

## Meta Commands

```ls
metric m:number_of_hours_worked p:float l:"Number Of Hours Worked" d:"Number Of Hours Worked" t:dataTypeName=number

metric m:hourly_wage_rate p:double l:"Hourly Wage Rate" d:"Hourly Wage Rate" t:dataTypeName=number

metric m:hourly_fringe_benefits_rate p:float l:"Hourly Fringe Benefits Rate" d:"Hourly Fringe Benefits Rate" t:dataTypeName=number

metric m:apprentice_beginning_hours_per_step p:integer l:"Apprentice Beginning Hours Per Step" t:dataTypeName=number

metric m:apprentice_ending_hours_per_step p:integer l:"Apprentice Ending Hours Per Step" d:"Apprentice Ending Hours Per Step" t:dataTypeName=number

entity e:xjth-3vtg l:"L&I Affidavit - Apprentice Level Worker Details" t:attribution=L&I t:url=https://data.wa.gov/api/views/xjth-3vtg

property e:xjth-3vtg t:meta.view v:id=xjth-3vtg v:category=Labor v:averageRating=0 v:name="L&I Affidavit - Apprentice Level Worker Details" v:attribution=L&I

property e:xjth-3vtg t:meta.view.owner v:id=sbxf-tc9c v:profileImageUrlMedium=/api/users/sbxf-tc9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/sbxf-tc9c/profile_images/LARGE v:screenName=Nithya v:profileImageUrlSmall=/api/users/sbxf-tc9c/profile_images/TINY v:displayName=Nithya

property e:xjth-3vtg t:meta.view.tableauthor v:id=sbxf-tc9c v:profileImageUrlMedium=/api/users/sbxf-tc9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/sbxf-tc9c/profile_images/LARGE v:screenName=Nithya v:profileImageUrlSmall=/api/users/sbxf-tc9c/profile_images/TINY v:roleName=publisher v:displayName=Nithya
```

## Top Records

```ls
| :updated_at | affidavit_id_number | apprentice_id_number | number_of_hours_worked | apprentice_occupation_name | apprentice_program_name | state_the_apprentice_is_registered | hourly_wage_rate | hourly_fringe_benefits_rate | apprentice_beginning_hours_per_step | apprentice_ending_hours_per_step | job_classification | county_name | prevailing_wage_trade | 
| =========== | =================== | ==================== | ====================== | ========================== | ======================= | ================================== | ================ | =========================== | =================================== | ================================ | ================== | =========== | ===================== | 
| 1446733524  | 2279                |                      |                        |                            |                         |                                    | 15.44            | 1.88                        | 0                                   | 1000                             |                    | Clark       | ELECTRICIANS - INSIDE | 
| 1446733525  | 11899               | 132613               |                        | ROOFER                     |                         | WA                                 | 22.27            | 6.69                        | 2451                                | 3270                             |                    | Mason       | ROOFERS               | 
| 1446733525  | 12574               | 128630               |                        | LATHER                     |                         | WA                                 | 21.84            | 8.25                        | 3001                                | 4000                             |                    | King        | LATHERS               | 
| 1446733526  | 7477                | 134963               |                        | ROOFER                     |                         | WA                                 | 17.83            | 3.5                         | 0                                   | 820                              |                    | King        | ROOFERS               | 
| 1446733530  | 23172               |                      |                        |                            |                         |                                    | 15.8             | 3.95                        | 1001                                | 2000                             |                    | Whitman     | ELECTRICIANS - INSIDE | 
| 1446733531  | 20728               | 139282               |                        | Laborer                    |                         | WA                                 | 14.83            | 7.2                         | 0                                   | 1000                             |                    | Thurston    | LABORERS              | 
| 1446733531  | 18924               | 134538               |                        | Roofer                     |                         |                                    | 19.02            | 6.61                        | 821                                 | 1630                             |                    | King        | ROOFERS               | 
| 1446733533  | 30534               | 129934               |                        | Roofer                     |                         | WA                                 | 23.04            | 7.29                        | 4201                                | 4900                             |                    | Pierce      | ROOFERS               | 
| 1446733534  | 34474               | 132611               |                        | Roofer                     |                         | WA                                 | 21.34            | 7.29                        | 3501                                | 4200                             |                    | Pierce      | ROOFERS               | 
| 1446733534  | 38786               | 141186               |                        | Roofer                     |                         |                                    | 15.37            | 6.61                        | 0                                   | 820                              |                    | King        | ROOFERS               | 
```