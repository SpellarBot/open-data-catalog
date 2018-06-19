# President's Office--Juvenile Temporary Detention Center Cost Comparison

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/presidents-office-juvenile-temporary-detention-center-cost-comparison-ead0f) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/ix6b-at92) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ix6b-at92/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ix6b-at92/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | ix6b-at92 |
| Name | President's Office--Juvenile Temporary Detention Center Cost Comparison |
| Attribution | Toni Preckwinkle, Cook County Board President |
| Category | Public Safety |
| Created | 2011-11-01T20:37:50Z |
| Publication Date | 2014-10-09T21:04:11Z |

## Description

Comparing the per-day cost to host a juvenile detainee at the JTDC, to those of the Chicago Public Schools, and the Cook County Health and Hospitals System.  Average daily population of JTDC is 305 detainees.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type | Render Type |
| ======== | ============== | =============================== | =============================== | ========= | =========== |
| No       | time           | :updated_at                     | updated_at                      | meta_data | meta_data   |
| Yes      | series tag     | expenditure                     | Expenditure                     | text      | text        |
| Yes      | numeric metric | fy2011_appropriated             | FY2011 Appropriated             | money     | money       |
| Yes      | series tag     | number_of_detainees             | Number of Detainees             | text      | text        |
| Yes      | series tag     | average_daily_cost_per_detainee | Average Daily Cost Per Detainee | text      | text        |
| Yes      | numeric metric | average_daily_population        | Average Daily Population        | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ix6b-at92 d:2011-11-01T13:37:52.000Z t:expenditure="CPS - Nancy B Jefferson Alternative School - 2011/12" m:fy2011_appropriated=8267811

series e:ix6b-at92 d:2011-11-01T13:37:52.000Z t:expenditure="CCHHS JTDC Cermak Operating Budget 2011" m:fy2011_appropriated=3541587

series e:ix6b-at92 d:2011-11-01T13:37:52.000Z t:expenditure="CCHHS 30% Cermak Health and Pension Fringe on Salaries" m:fy2011_appropriated=812592
```

## Meta Commands

```ls
metric m:fy2011_appropriated p:integer l:"FY2011 Appropriated" t:dataTypeName=money

metric m:average_daily_population p:integer l:"Average Daily Population" t:dataTypeName=number

entity e:ix6b-at92 l:"President's Office--Juvenile Temporary Detention Center Cost Comparison" t:attribution="Toni Preckwinkle, Cook County Board President" t:url=https://datacatalog.cookcountyil.gov/api/views/ix6b-at92

property e:ix6b-at92 t:meta.view v:id=ix6b-at92 v:category="Public Safety" v:averageRating=0 v:name="President's Office--Juvenile Temporary Detention Center Cost Comparison" v:attribution="Toni Preckwinkle, Cook County Board President"

property e:ix6b-at92 t:meta.view.license v:name="Public Domain"

property e:ix6b-at92 t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:ix6b-at92 t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| :updated_at | expenditure                                            | fy2011_appropriated | number_of_detainees | average_daily_cost_per_detainee | average_daily_population | 
| =========== | ====================================================== | =================== | =================== | =============================== | ======================== | 
| 1320154672  | CPS - Nancy B Jefferson Alternative School - 2011/12   | 8267811             |                     |                                 |                          | 
| 1320154672  | CPS                                                    |                     |                     | $74.27                          |                          | 
| 1320154672  | CCHHS JTDC Cermak                                      |                     |                     |                                 |                          | 
| 1320154672  | CCHHS JTDC Cermak Operating Budget 2011                | 3541587             |                     |                                 |                          | 
| 1320154672  | CCHHS 30% Cermak Health and Pension Fringe on Salaries | 812592              |                     |                                 |                          | 
| 1320154672  | CCHHS Cermak JTDC Capital Equipment 2011               | 55000               |                     |                                 |                          | 
| 1320154672  | CCHHS                                                  |                     |                     | $39.61                          |                          | 
| 1320154672  | JTDC Personnel 2011                                    | 33031562            |                     |                                 |                          | 
| 1320154672  | JTDC 30% Health and Pension Fringe on Salaries         | 8472900             |                     |                                 |                          | 
| 1320154672  | JTDC Contractual Services                              | 9439448             |                     |                                 |                          | 
```