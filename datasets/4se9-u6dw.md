# Medicaid coverage for children and pregnant women (Income levels)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medicaid-coverage-for-children-and-pregnant-women-income-levels-901d0) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/4se9-u6dw) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/4se9-u6dw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/4se9-u6dw/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 4se9-u6dw |
| Name | Medicaid coverage for children and pregnant women (Income levels) |
| Attribution | Human Resources Administration (HRA) |
| Category | City Government |
| Tags | jobs and economic mobility, human resources administration, hra, pregnant, woman, income |
| Created | 2013-03-19T18:22:21Z |
| Publication Date | 2016-03-02T20:22:32Z |

## Description

This table represents details of Medicaid (coverage for children). Medicaid (coverage for children)  is available for many children in working families. Most children who are eligible for Medicaid (coverage for children) do receive their medical care through a health plan, and visit doctors and hospitals that accept that health plan. While ones application is being processed, Medicaid (coverage for children) may provide up to 90 days of retroactive coverage for unpaid medical bills, if eligible during those 90 days

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type | Render Type |
| ======== | ============== | =================================== | =================================== | ========= | =========== |
| No       | time           | :updated_at                         | updated_at                          | meta_data | meta_data   |
| Yes      | series tag     | age_categories_for_children         | Age Categories for Children         | text      | text        |
| Yes      | numeric metric | family_size__1_ind___monthly_income | Family Size (1 ind.) Monthly Income | number    | text        |
| Yes      | numeric metric | family_size__2_nos___monthly_income | Family Size (2 nos.) Monthly Income | number    | text        |
| Yes      | numeric metric | family_size__3_nos___monthly_income | Family Size (3 nos.) Monthly Income | number    | text        |
| Yes      | numeric metric | family_size__4_nos___monthly_income | Family Size (4 nos.) Monthly Income | number    | text        |
| Yes      | numeric metric | family_size__5_nos___monthly_income | Family Size (5 nos.) Monthly Income | number    | text        |
| Yes      | numeric metric | each_additional_person_add          | Each Additional Person Add          | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:4se9-u6dw d:2016-03-02T12:21:45.000Z t:age_categories_for_children="Children under 1 year Old; Pregnant Women Pernitial Coverage Only" m:family_size__1_ind___monthly_income=2188 m:family_size__2_nos___monthly_income=2961 m:family_size__5_nos___monthly_income=5280 m:family_size__4_nos___monthly_income=4507 m:each_additional_person_add=774 m:family_size__3_nos___monthly_income=3734

series e:4se9-u6dw d:2016-03-02T12:21:45.000Z t:age_categories_for_children="Children 1 - 5 years old" m:family_size__1_ind___monthly_income=1511 m:family_size__2_nos___monthly_income=2045 m:family_size__5_nos___monthly_income=3646 m:family_size__4_nos___monthly_income=3113 m:each_additional_person_add=534 m:family_size__3_nos___monthly_income=2579

series e:4se9-u6dw d:2016-03-02T12:21:45.000Z t:age_categories_for_children="Children 6 - 19 years old; 110%FPL" m:family_size__1_ind___monthly_income=1079 m:family_size__2_nos___monthly_income=1461 m:family_size__5_nos___monthly_income=2605 m:family_size__4_nos___monthly_income=2223 m:each_additional_person_add=382 m:family_size__3_nos___monthly_income=1842
```

## Meta Commands

```ls
metric m:family_size__1_ind___monthly_income p:integer l:"Family Size (1 ind.) Monthly Income" t:dataTypeName=number

metric m:family_size__2_nos___monthly_income p:integer l:"Family Size (2 nos.) Monthly Income" t:dataTypeName=number

metric m:family_size__3_nos___monthly_income p:integer l:"Family Size (3 nos.) Monthly Income" t:dataTypeName=number

metric m:family_size__4_nos___monthly_income p:integer l:"Family Size (4 nos.) Monthly Income" t:dataTypeName=number

metric m:family_size__5_nos___monthly_income p:integer l:"Family Size (5 nos.) Monthly Income" t:dataTypeName=number

metric m:each_additional_person_add p:integer l:"Each Additional Person Add" t:dataTypeName=number

entity e:4se9-u6dw l:"Medicaid coverage for children and pregnant women (Income levels)" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/4se9-u6dw

property e:4se9-u6dw t:meta.view v:id=4se9-u6dw v:category="City Government" v:attributionLink=http://www.nyc.gov/html/hia/html/public_insurance/children.shtml v:averageRating=0 v:name="Medicaid coverage for children and pregnant women (Income levels)" v:attribution="Human Resources Administration (HRA)"

property e:4se9-u6dw t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:4se9-u6dw t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | age_categories_for_children                                            | family_size__1_ind___monthly_income | family_size__2_nos___monthly_income | family_size__3_nos___monthly_income | family_size__4_nos___monthly_income | family_size__5_nos___monthly_income | each_additional_person_add | 
| =========== | ====================================================================== | =================================== | =================================== | =================================== | =================================== | =================================== | ========================== | 
| 1456921305  | Children under 1 year Old; Pregnant Women Pernitial Coverage Only      | 2188                                | 2961                                | 3734                                | 4507                                | 5280                                | 774                        | 
| 1456921305  | Children 1 - 5 years old                                               | 1511                                | 2045                                | 2579                                | 3113                                | 3646                                | 534                        | 
| 1456921305  | Children 6 - 19 years old; 110%FPL                                     | 1079                                | 1461                                | 1842                                | 2223                                | 2605                                | 382                        | 
| 1456921305  | Children 6 - 19 years old; Expanded                                    | 1511                                | 2045                                | 2579                                | 3113                                | 3646                                | 534                        | 
| 1456921305  | Children 19 - 20 years old Living With Parents                         | 1354                                | 1832                                | 2311                                | 2789                                | 3268                                | 479                        | 
| 1456921305  | Childern 19 - 20 years old Living with Parent Expanded                 | 1521                                | 2058                                | 2595                                | 3133                                | 3670                                | 538                        | 
| 1456921305  | Note: Income Levels are awaiting 2016 updates pending Federal approval |                                     |                                     |                                     |                                     |                                     |                            | 
```