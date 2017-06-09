# Child health plus income levels

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/child-health-plus-income-levels-2e8d3) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vpb3-uf7s) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vpb3-uf7s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vpb3-uf7s/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vpb3-uf7s |
| Name | Child health plus income levels |
| Attribution | Human Resources Administration (HRA) |
| Category | City Government |
| Tags | jobs and economic mobility, human resources administration, hra, children, health, plus |
| Created | 2013-03-19T18:20:39Z |
| Publication Date | 2016-03-02T20:15:34Z |

## Description

This table represents details of CHP (Child Health Plus) insurance. Child Health Plus provides free or low-cost health insurance for children under the age of 19 who are not eligible for Medicaid, coverage for children. All children receive their health care through a managed care plan. There are no immigration requirements for Child Health Plus.

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type | Render Type |
| ======== | ============== | =================================== | =================================== | ========= | =========== |
| No       | time           | :updated_at                         | updated_at                          | meta_data | meta_data   |
| Yes      | series tag     | premium_categories                  | Premium Categories                  | text      | text        |
| Yes      | series tag     | family_size__1_ind___monthly_income | Family Size (1 ind.) Monthly Income | text      | text        |
| Yes      | series tag     | family_size__2_nos___monthly_income | Family Size (2 nos.) Monthly Income | text      | text        |
| Yes      | series tag     | family_size__3_nos___monthly_income | Family Size (3 nos.) Monthly Income | text      | text        |
| Yes      | series tag     | family_size__4_nos___monthly_income | Family Size (4 nos.) Monthly Income | text      | text        |
| Yes      | series tag     | family_size__5_nos___monthly_income | Family Size (5 nos.) Monthly Income | text      | text        |
| Yes      | numeric metric | each_additional_person_add          | Each Additional Person Add          | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:vpb3-uf7s d:2013-03-19T11:20:45.000Z t:premium_categories="Free Insurance" t:family_size_1_ind_monthly_income=1489 t:family_size_2_nos_monthly_income=2017 t:family_size_5_nos_monthly_income=3601 t:family_size_4_nos_monthly_income=3073 t:family_size_3_nos_monthly_income=2545 m:each_additional_person_add=528

series e:vpb3-uf7s d:2013-03-19T11:20:45.000Z t:premium_categories="$9 Per Child Per Month
(Maximum of $27 per family)" t:family_size_1_ind_monthly_income=2067 t:family_size_2_nos_monthly_income=2800 t:family_size_5_nos_monthly_income=4997 t:family_size_4_nos_monthly_income=4265 t:family_size_3_nos_monthly_income=3532 m:each_additional_person_add=733

series e:vpb3-uf7s d:2013-03-19T11:20:45.000Z t:premium_categories="$15 Per Child Per MonthMaximum of $45 per family)" t:family_size_1_ind_monthly_income=2328 t:family_size_2_nos_monthly_income=3153 t:family_size_5_nos_monthly_income=5628 t:family_size_4_nos_monthly_income=4803 t:family_size_3_nos_monthly_income=3978 m:each_additional_person_add=825
```

## Meta Commands

```ls
metric m:each_additional_person_add p:integer l:"Each Additional Person Add" t:dataTypeName=number

entity e:vpb3-uf7s l:"Child health plus income levels" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/vpb3-uf7s

property e:vpb3-uf7s t:meta.view d:2017-06-09T13:54:54.516Z v:id=vpb3-uf7s v:category="City Government" v:attributionLink=http://www.nyc.gov/html/hia/html/public_insurance/children.shtml v:averageRating=0 v:name="Child health plus income levels" v:attribution="Human Resources Administration (HRA)"

property e:vpb3-uf7s t:meta.view.owner d:2017-06-09T13:54:54.516Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:displayName="NYC OpenData"

property e:vpb3-uf7s t:meta.view.tableauthor d:2017-06-09T13:54:54.516Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1496414226 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | premium_categories                                    | family_size__1_ind___monthly_income | family_size__2_nos___monthly_income | family_size__3_nos___monthly_income | family_size__4_nos___monthly_income | family_size__5_nos___monthly_income | each_additional_person_add | 
| =========== | ===================================================== | =================================== | =================================== | =================================== | =================================== | =================================== | ========================== | 
| 1363692045  | Free Insurance                                        | 1489                                | 2017                                | 2545                                | 3073                                | 3601                                | 528                        | 
| 1363692045  | $9 Per Child Per Month (Maximum of $27 per family)    | 2067                                | 2800                                | 3532                                | 4265                                | 4997                                | 733                        | 
| 1363692045  | $15 Per Child Per MonthMaximum of $45 per family)     | 2328                                | 3153                                | 3978                                | 4803                                | 5628                                | 825                        | 
| 1363692045  | $30 Per Child Per Month (Maximum of $90 per family)   | 2793                                | 3783                                | 4773                                | 5763                                | 6753                                | 990                        | 
| 1363692045  | $45 Per Child Per Month (Maximum of $135 per family)  | 3258                                | 4413                                | 5568                                | 6723                                | 7878                                | 1155                       | 
| 1363692045  | $60 Per Child Per Month (Maximum of $1820 per family) | 3724                                | 5044                                | 6364                                | 7684                                | 9004                                | 1320                       | 
| 1363692045  | Full Premium Per Child Per Month                      | Over $ 3724.00                      | Over $ 5044.00                      | Over $ 6364.00                      | Over $ 7684.00                      | Over $ 9004.00                      | 1247                       | 
```