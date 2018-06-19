# L&I Affidavit Details - Journey Level Trades And Wage Rates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/li-affidavit-details-journey-level-trades-and-wage-rates) |
| Metadata | [Link](https://data.wa.gov/api/views/pcn2-jime) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/pcn2-jime/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/pcn2-jime/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | pcn2-jime |
| Name | L&I Affidavit Details - Journey Level Trades And Wage Rates |
| Attribution | L&I |
| Category | Labor |
| Tags | affidavit, contractor, wage, trade, job classification, benefits |
| Created | 2015-11-06T00:06:48Z |
| Publication Date | 2015-12-07T20:09:08Z |

## Description

Affidavit Details - Journey Level Trades And Wage Rates

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                  | meta_data | meta_data   |
| No       |                | id                          | Affidavit ID Number         | text      | number      |
| Yes      | series tag     | trade                       | Prevailing Wage Trade       | text      | text        |
| Yes      | series tag     | job_classification          | Job Classification          | text      | text        |
| Yes      | series tag     | county                      | County Name                 | text      | text        |
| Yes      | numeric metric | hourly_rate                 | Hourly Rate                 | number    | number      |
| Yes      | numeric metric | hourly_fringe_benefits_rate | Hourly Fringe Benefits Rate | number    | number      |
| Yes      | numeric metric | number_of_hours_worked      | Number Of Hours Worked      | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id
```

## Data Commands

```ls
series e:pcn2-jime d:2016-03-23T07:02:56.000Z t:job_classification="Spreader, Topsider & Screedman" t:county=King t:trade="Power Equipment Operators" m:number_of_hours_worked=31.5 m:hourly_fringe_benefits_rate=18 m:hourly_rate=38.94

series e:pcn2-jime d:2016-03-23T07:02:56.000Z t:job_classification=Pipefitter t:county=King t:trade="Shipbuilding & Ship Repair" m:number_of_hours_worked=145 m:hourly_fringe_benefits_rate=12.37 m:hourly_rate=34.65

series e:pcn2-jime d:2016-03-23T07:02:56.000Z t:job_classification=Welder/Burner t:county=King t:trade="Shipbuilding & Ship Repair" m:number_of_hours_worked=1.5 m:hourly_fringe_benefits_rate=9.63 m:hourly_rate=30.56
```

## Meta Commands

```ls
metric m:hourly_rate p:float l:"Hourly Rate" d:"Hourly Wage Rate" t:dataTypeName=number

metric m:hourly_fringe_benefits_rate p:float l:"Hourly Fringe Benefits Rate" d:"Hourly Fringe Benefits Rate" t:dataTypeName=number

metric m:number_of_hours_worked p:integer l:"Number Of Hours Worked" d:"Number Of Hours Worked" t:dataTypeName=number

entity e:pcn2-jime l:"L&I Affidavit Details -  Journey Level Trades And Wage Rates" t:attribution=L&I t:url=https://data.wa.gov/api/views/pcn2-jime

property e:pcn2-jime t:meta.view v:id=pcn2-jime v:category=Labor v:averageRating=0 v:name="L&I Affidavit Details -  Journey Level Trades And Wage Rates" v:attribution=L&I

property e:pcn2-jime t:meta.view.owner v:id=sbxf-tc9c v:profileImageUrlMedium=/api/users/sbxf-tc9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/sbxf-tc9c/profile_images/LARGE v:screenName=Nithya v:profileImageUrlSmall=/api/users/sbxf-tc9c/profile_images/TINY v:displayName=Nithya

property e:pcn2-jime t:meta.view.tableauthor v:id=sbxf-tc9c v:profileImageUrlMedium=/api/users/sbxf-tc9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/sbxf-tc9c/profile_images/LARGE v:screenName=Nithya v:profileImageUrlSmall=/api/users/sbxf-tc9c/profile_images/TINY v:roleName=publisher v:displayName=Nithya
```

## Top Records

```ls
| :updated_at | id     | trade                      | job_classification                                                                  | county  | hourly_rate | hourly_fringe_benefits_rate | number_of_hours_worked | 
| =========== | ====== | ========================== | =================================================================================== | ======= | =========== | =========================== | ====================== | 
| 1458716576  | 635797 | Power Equipment Operators  | Spreader, Topsider & Screedman                                                      | King    | 38.94       | 18                          | 31.5                   | 
| 1458716576  | 633536 | Shipbuilding & Ship Repair | Pipefitter                                                                          | King    | 34.65       | 12.37                       | 145                    | 
| 1458716576  | 633536 | Shipbuilding & Ship Repair | Welder/Burner                                                                       | King    | 30.56       | 9.63                        | 1.5                    | 
| 1458716576  | 635689 | Carpenters                 | Carpenter                                                                           | King    | 54.02       | 0                           | 237                    | 
| 1458716576  | 634618 | Carpenters                 | Carpenter                                                                           | King    | 52.32       | 0                           | 70.5                   | 
| 1458716576  | 633536 | Shipbuilding & Ship Repair | Laborer                                                                             | King    | 33.88       | 12.33                       | 1.5                    | 
| 1458716576  | 635532 | Sheet Metal Workers        | Journey Level (Field or Shop)                                                       | Lincoln | 43.58       | 6.63                        | 4                      | 
| 1458716576  | 633536 | Shipbuilding & Ship Repair | Laborer                                                                             | King    | 30.92       | 11.46                       | 169                    | 
| 1458716576  | 635640 | Power Equipment Operators  | Cranes: 100 Tons Through 199 Tons, Or 150' Of Boom (Including Jib With Attachments) | King    | 54          | 5                           | 49.5                   | 
| 1458716576  | 635865 | Power Equipment Operators  | Forklift: 3000 Lbs And Over With Attachments                                        | King    | 43.62       | 7.36                        | 210                    | 
```