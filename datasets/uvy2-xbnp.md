# Performance Metrics - Public Health - School-Based Oral Health Programming

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-public-health-school-based-oral-health-programming-d87c8) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/uvy2-xbnp) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/uvy2-xbnp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/uvy2-xbnp/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | uvy2-xbnp |
| Name | Performance Metrics - Public Health - School-Based Oral Health Programming |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, service delivery, cdph, cps, oral health, dentist |
| Created | 2011-07-20T21:37:41Z |
| Publication Date | 2012-02-22T22:36:29Z |

## Description

The Chicago Department of Public Health contracts with licensed dentists to provide and the Chicago Public Schools' students a dental exam/screening, a dental cleaning, a fluoride varnish treatment and apply dental sealant(s) as needed at no cost to students or their families in school. This metric tracks the number of students served by the program per month during the school year. The annual performance goal is to serve 96,000 students per school year.

## Columns

```ls
| Included | Schema Type    | Field Name                                   | Name                                         | Data Type | Render Type |
| ======== | ============== | ============================================ | ============================================ | ========= | =========== |
| No       | time           | :updated_at                                  | updated_at                                   | meta_data | meta_data   |
| Yes      | series tag     | months                                       | months                                       | text      | text        |
| Yes      | numeric metric | new_students_examined_per_month              | New Students Examined Per Month              | number    | number      |
| Yes      | numeric metric | cumulative_students_examined_per_school_year | Cumulative Students Examined Per School Year | number    | number      |
| Yes      | numeric metric | students_receiving_dental_sealants           | Students Receiving Dental Sealants           | number    | number      |
| Yes      | numeric metric | percent_students_receiving_sealants          | Percent Students Receiving Sealants          | percent   | percent     |
| Yes      | numeric metric | months_target_was_achieved                   | Months Target Was Achieved                   | number    | number      |
| Yes      | numeric metric | months_target_was_not_achieved               | Months Target Was Not Achieved               | number    | number      |
| Yes      | numeric metric | annual_target                                | Annual Target                                | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:uvy2-xbnp d:2011-10-26T12:42:11.000Z t:months=Oct-10 m:cumulative_students_examined_per_school_year=9750 m:students_receiving_dental_sealants=5385 m:percent_students_receiving_sealants=6 m:annual_target=96000 m:new_students_examined_per_month=9228

series e:uvy2-xbnp d:2011-10-26T12:42:13.000Z t:months=Nov-10 m:cumulative_students_examined_per_school_year=22204 m:students_receiving_dental_sealants=7729 m:percent_students_receiving_sealants=13 m:annual_target=96000 m:new_students_examined_per_month=12454

series e:uvy2-xbnp d:2011-10-26T12:42:14.000Z t:months=Dec-10 m:cumulative_students_examined_per_school_year=27835 m:students_receiving_dental_sealants=3485 m:percent_students_receiving_sealants=17 m:annual_target=96000 m:new_students_examined_per_month=5631
```

## Meta Commands

```ls
metric m:new_students_examined_per_month p:integer l:"New Students Examined Per Month" t:dataTypeName=number

metric m:cumulative_students_examined_per_school_year p:integer l:"Cumulative Students Examined Per School Year" t:dataTypeName=number

metric m:students_receiving_dental_sealants p:integer l:"Students Receiving Dental Sealants" t:dataTypeName=number

metric m:percent_students_receiving_sealants p:integer l:"Percent Students Receiving Sealants" t:dataTypeName=percent

metric m:months_target_was_achieved p:long l:"Months Target Was Achieved" t:dataTypeName=number

metric m:months_target_was_not_achieved p:long l:"Months Target Was Not Achieved" t:dataTypeName=number

metric m:annual_target p:integer l:"Annual Target" t:dataTypeName=number

entity e:uvy2-xbnp l:"Performance Metrics - Public Health - School-Based Oral Health Programming" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/uvy2-xbnp

property e:uvy2-xbnp t:meta.view v:id=uvy2-xbnp v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Performance Metrics - Public Health - School-Based Oral Health Programming" v:attribution="City of Chicago"

property e:uvy2-xbnp t:meta.view.owner v:id=zzya-y4bn v:screenName="Elizabeth Scott" v:displayName="Elizabeth Scott"

property e:uvy2-xbnp t:meta.view.tableauthor v:id=zzya-y4bn v:screenName="Elizabeth Scott" v:displayName="Elizabeth Scott"
```

## Top Records

```ls
| :updated_at | months | new_students_examined_per_month | cumulative_students_examined_per_school_year | students_receiving_dental_sealants | percent_students_receiving_sealants | months_target_was_achieved | months_target_was_not_achieved | annual_target | 
| =========== | ====== | =============================== | ============================================ | ================================== | =================================== | ========================== | ============================== | ============= | 
| 1319632931  | Oct-10 | 9228                            | 9750                                         | 5385                               | 6                                   |                            |                                | 96000         | 
| 1319632933  | Nov-10 | 12454                           | 22204                                        | 7729                               | 13                                  |                            |                                | 96000         | 
| 1319632934  | Dec-10 | 5631                            | 27835                                        | 3485                               | 17                                  |                            |                                | 96000         | 
| 1319632936  | Jan-11 | 15873                           | 43708                                        | 9222                               | 27                                  |                            |                                | 96000         | 
| 1319632937  | Feb-11 | 10739                           | 54447                                        | 6169                               | 33                                  |                            |                                | 96000         | 
| 1319632941  | Mar-11 | 12534                           | 66981                                        | 7223                               | 41                                  |                            |                                | 96000         | 
| 1319632946  | Apr-11 | 9809                            | 76790                                        | 5812                               | 47                                  |                            |                                | 96000         | 
| 1319632948  | May-11 | 15250                           | 92040                                        | 9099                               | 56                                  |                            |                                | 96000         | 
| 1319633249  | Sep-10 | 522                             | 522                                          | 196                                | 0                                   |                            |                                | 96000         | 
| 1322058872  | Jun-11 | 3736                            | 95776                                        | 2237                               | 58                                  |                            |                                | 96000         | 
```