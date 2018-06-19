# FY2015 Agency Performance Measures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy2015-agency-performance-measures-1f8ec) |
| Metadata | [Link](https://data.illinois.gov/api/views/paxx-4u36) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/paxx-4u36/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/paxx-4u36/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | paxx-4u36 |
| Name | FY2015 Agency Performance Measures |
| Attribution | Governor's Office of Management and Budget |
| Category | Reference |
| Tags | illinois, fy2015, budget, gomb |
| Created | 2014-04-09T19:55:24Z |
| Publication Date | 2014-04-09T20:02:01Z |

## Description

This dataset contains all Fiscal Year 2015 performance measures reported in the FY 15 Budget Book, by agency and program. The file is provided by the Governor?s Office of Management and Budget and is available at the following websites: Budget.Illinois.gov or http://www.state.il.us/budget/).

The first two (2) columns contain the name of the Agency and the name of the performance measure.

Columns three (3) through seven (7) contain the reported data values for the performance measures for FY 2011-FY 2013, and estimated and projected values for FY 2014 and FY 2015.

Column eight (8) contains an asterisk (*) if there is a footnote attached to the performance measure. Corresponding footnotes can be found in the respective state agency Performance Measure tables within the agency narrative section in the FY 15 Budget Book, available for download at Budget.Illinois.gov or http://www.state.il.us/budget/.

Columns nine (9) through eleven (11) contain the program name, the name of the associated Outcome Area and the name of the associated Statewide Result Area.

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| Yes      | series tag  | agency_name       | Agency Name       | text      | text        |
| Yes      | series tag  | metric_name       | Metric Name       | text      | text        |
| Yes      | series tag  | fy_2011_actual    | FY 2011 Actual    | text      | text        |
| Yes      | series tag  | fy_2012_actual    | FY 2012 Actual    | text      | text        |
| Yes      | series tag  | fy_2013_actual    | FY 2013 Actual    | text      | text        |
| Yes      | series tag  | fy_2014_estimated | FY 2014 Estimated | text      | text        |
| Yes      | series tag  | fy_2015_projected | FY 2015 Projected | text      | text        |
| No       |             | footnote          | Footnote          | text      | text        |
| Yes      | series tag  | program_name      | Program Name      | text      | text        |
| Yes      | series tag  | outcome_name      | Outcome Name      | text      | text        |
| Yes      | series tag  | result_name       | Result Name       | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = footnote
```

## Data Commands

```ls
series e:paxx-4u36 d:2015-01-01T00:00:00.000Z t:fy_2013_actual=82,791 t:result_name="Protection of the Most Vulnerable of our Residents" t:outcome_name="Meet the Needs of the Most Vulnerable" t:program_name="Community Care Program" t:fy_2015_projected=82,600 t:fy_2014_estimated=89,400 t:metric_name="Number of seniors receiving in-home and community-based services through the Community Care Program" t:agency_name="Department On Aging" t:fy_2012_actual=76,624 t:fy_2011_actual=68,224 m:row_number.paxx-4u36=1

series e:paxx-4u36 d:2015-01-01T00:00:00.000Z t:fy_2013_actual=$854.01 t:result_name="Protection of the Most Vulnerable of our Residents" t:outcome_name="Meet the Needs of the Most Vulnerable" t:program_name="Community Care Program" t:fy_2015_projected=$857.00 t:fy_2014_estimated=$868.00 t:metric_name="Community Care Program's (CCP) average monthly cost of care per person" t:agency_name="Department On Aging" t:fy_2012_actual=$849.89 t:fy_2011_actual=$817.87 m:row_number.paxx-4u36=2

series e:paxx-4u36 d:2015-01-01T00:00:00.000Z t:fy_2013_actual=388 t:result_name="Protection of the Most Vulnerable of our Residents" t:outcome_name="Meet the Needs of the Most Vulnerable" t:program_name="Comprehensive Care Coordination" t:fy_2015_projected=438 t:fy_2014_estimated=488 t:metric_name="Number of deinstitutionalizations: transfers from institutional care to community settings" t:agency_name="Department On Aging" t:fy_2012_actual=421 t:fy_2011_actual=322 m:row_number.paxx-4u36=3
```

## Meta Commands

```ls
metric m:row_number.paxx-4u36 p:long l:"Row Number"

entity e:paxx-4u36 l:"FY2015 Agency Performance Measures" t:attribution="Governor's Office of Management and Budget" t:url=https://data.illinois.gov/api/views/paxx-4u36

property e:paxx-4u36 t:meta.view v:id=paxx-4u36 v:category=Reference v:attributionLink=http://www.state.il.us/budget/ v:averageRating=0 v:name="FY2015 Agency Performance Measures" v:attribution="Governor's Office of Management and Budget"

property e:paxx-4u36 t:meta.view.owner v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:displayName=wilcoxd

property e:paxx-4u36 t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| agency_name                                | metric_name                                                                                                 | fy_2011_actual | fy_2012_actual | fy_2013_actual | fy_2014_estimated | fy_2015_projected | footnote | program_name                                               | outcome_name                                                  | result_name                                           | 
| ========================================== | =========================================================================================================== | ============== | ============== | ============== | ================= | ================= | ======== | ========================================================== | ============================================================= | ===================================================== | 
| Department On Aging                        | Number of seniors receiving in-home and community-based services through the Community Care Program         | 68,224         | 76,624         | 82,791         | 89,400            | 82,600            | *        | Community Care Program                                     | Meet the Needs of the Most Vulnerable                         | Protection of the Most Vulnerable of our Residents    | 
| Department On Aging                        | Community Care Program's (CCP) average monthly cost of care per person                                      | $817.87        | $849.89        | $854.01        | $868.00           | $857.00           |          | Community Care Program                                     | Meet the Needs of the Most Vulnerable                         | Protection of the Most Vulnerable of our Residents    | 
| Department On Aging                        | Number of deinstitutionalizations: transfers from institutional care to community settings                  | 322            | 421            | 388            | 488               | 438               |          | Comprehensive Care Coordination                            | Meet the Needs of the Most Vulnerable                         | Protection of the Most Vulnerable of our Residents    | 
| Department On Aging                        | Percentage of seniors receiving Older Americans Act services                                                | 23.00%         | 22.00%         | 21.70%         | 22.00%            | 22.00%            |          | Community Support Services - Older Americans Act Title III | Increase Individual and Family Stability and Self-Sufficiency | Protection of the Most Vulnerable of our Residents    | 
| Capital Development Board                  | Percentage of total dollars contracted to Minority Business Enterprise/Female Business Enterprise firms     | 18.20%         | 18.10%         | 16.70%         | 20.00%            | 20.00%            |          | Operations of the Capital Development Board                | Support Basic Functions of Government                         | Improved Efficiency and Stability of State Government | 
| Capital Development Board                  | Percentage of labor hours that are performed by minorities or females                                       | 14.80%         | 21.20%         | 13.50%         | 15.00%            | 15.00%            |          | Operations of the Capital Development Board                | Support Basic Functions of Government                         | Improved Efficiency and Stability of State Government | 
| Capital Development Board                  | Percentage of projects with Project Labor Agreements (PLA)                                                  | 40.10%         | 83.30%         | 90.20%         | 70.00%            | 70.00%            | *        | Operations of the Capital Development Board                | Support Basic Functions of Government                         | Improved Efficiency and Stability of State Government | 
| Capital Development Board                  | Percentage of projects resulting in CDB taking action to hold architect/engineer accountable - design phase | 46.10%         | 70.00%         | 40.70%         | 70.00%            | 70.00%            |          | Operations of the Capital Development Board                | Support Basic Functions of Government                         | Improved Efficiency and Stability of State Government | 
| Capital Development Board                  | Percentage of projects resulting in CDB taking action to hold contractors accountable - construction phase  | 12.30%         | 70.00%         | 24.00%         | 70.00%            | 70.00%            |          | Operations of the Capital Development Board                | Support Basic Functions of Government                         | Improved Efficiency and Stability of State Government | 
| Department Of Children And Family Services | Percentage of State Central Register Hotline calls that were answered the first time or had a message taken | 96.20%         | 95.60%         | 97.40%         | 97.50%            | 97.50%            |          | State Central Registry                                     | Meet the Needs of the Most Vulnerable                         | Protection of the Most Vulnerable of our Residents    | 
```