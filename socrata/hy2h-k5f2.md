# Returning Citizen Child Support & Inmate Obligors

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/returning-citizen-child-support-inmate-obligors-f559e) |
| Metadata | [Link](https://data.maryland.gov/api/views/hy2h-k5f2) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/hy2h-k5f2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/hy2h-k5f2/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | hy2h-k5f2 |
| Name | Returning Citizen Child Support & Inmate Obligors |
| Attribution | Department of Human Resources (DHR) |
| Category | Health and Human Services |
| Tags | dhr, dpscs, child support, re-entry, prisoner re-entry, inmate obligors |
| Created | 2014-06-20T16:15:02Z |
| Publication Date | 2014-06-20T16:31:11Z |

## Description

Data are provided by the Department of Human Resources (DHR) and University of Maryland. This dataset shows how many formerly incarcerated individuals in Maryland with child support payments are paying any portion on time. The dataset also shows how many incoming inmates to DPSCS have inmate obligors modified upon intake, as well as how many returning citizens have inmate obligors modified soon after release.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                                                            | Name                                                                                                                                   | Data Type | Render Type |
| ======== | ============== | ===================================================================================================================================== | ====================================================================================================================================== | ========= | =========== |
| No       | time           | :updated_at                                                                                                                           | updated_at                                                                                                                             | meta_data | meta_data   |
| Yes      | series tag     | timeframe_month_calendar_year_or_fiscal_year                                                                                          | Timeframe (Month, Calendar Year, or Fiscal Year)                                                                                       | text      | text        |
| Yes      | numeric metric | number_of_released_inmates_who_are_gainfully_employed_and_pay_any_percentage_of_their_current_child_support_obligation_on_time        | Number of released inmates who are gainfully employed and pay any percentage of their current child support obligation on time         | number    | number      |
| Yes      | numeric metric | number_of_released_inmates_who_pay_any_percentage_of_current_child_support_on_time                                                    | Number of released inmates who pay any percentage of current child support on time                                                     | number    | number      |
| Yes      | numeric metric | number_of_released_inmates_who_pay_any_percentage_of_current_child_support_on_time_and_who_completed_dhr_s_non_custodial_work_program | Number of released inmates who pay any percentage of current child support on time AND who completed DHR?s non-custodial work program. | number    | number      |
| Yes      | numeric metric | number_of_released_inmates_who_paid_no_current_child_support_and_had_current_support_charges                                          | Number of released inmates who paid no current child support and had current support charges.                                          | number    | number      |
| Yes      | numeric metric | number_of_child_support_orders_with_an_inmate_obligor_that_are_modified_upon_entry_into_dpscs_facility                                | Number of child support orders with an inmate obligor that are modified upon entry into DPSCS facility.                                | number    | number      |
| Yes      | numeric metric | number_of_child_support_orders_with_a_released_inmate_obligor_modified_within_180_days_of_release_from_prison                         | Number of child support orders with a released inmate obligor modified within 180 days of release from prison.                         | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:hy2h-k5f2 d:2014-06-20T09:15:04.000Z t:timeframe_month_calendar_year_or_fiscal_year=CY2007 m:number_of_child_support_orders_with_a_released_inmate_obligor_modified_within_180_days_of_release_from_prison=52 m:number_of_child_support_orders_with_an_inmate_obligor_that_are_modified_upon_entry_into_dpscs_facility=124 m:number_of_released_inmates_who_pay_any_percentage_of_current_child_support_on_time=977 m:number_of_released_inmates_who_paid_no_current_child_support_and_had_current_support_charges=869 m:number_of_released_inmates_who_are_gainfully_employed_and_pay_any_percentage_of_their_current_child_support_obligation_on_time=493 m:number_of_released_inmates_who_pay_any_percentage_of_current_child_support_on_time_and_who_completed_dhr_s_non_custodial_work_program=10

series e:hy2h-k5f2 d:2014-06-20T09:15:04.000Z t:timeframe_month_calendar_year_or_fiscal_year=CY2008 m:number_of_child_support_orders_with_a_released_inmate_obligor_modified_within_180_days_of_release_from_prison=57 m:number_of_child_support_orders_with_an_inmate_obligor_that_are_modified_upon_entry_into_dpscs_facility=202 m:number_of_released_inmates_who_pay_any_percentage_of_current_child_support_on_time=1606 m:number_of_released_inmates_who_paid_no_current_child_support_and_had_current_support_charges=1366 m:number_of_released_inmates_who_are_gainfully_employed_and_pay_any_percentage_of_their_current_child_support_obligation_on_time=857 m:number_of_released_inmates_who_pay_any_percentage_of_current_child_support_on_time_and_who_completed_dhr_s_non_custodial_work_program=31

series e:hy2h-k5f2 d:2014-06-20T09:15:04.000Z t:timeframe_month_calendar_year_or_fiscal_year=CY2009 m:number_of_child_support_orders_with_a_released_inmate_obligor_modified_within_180_days_of_release_from_prison=80 m:number_of_child_support_orders_with_an_inmate_obligor_that_are_modified_upon_entry_into_dpscs_facility=366 m:number_of_released_inmates_who_pay_any_percentage_of_current_child_support_on_time=2504 m:number_of_released_inmates_who_paid_no_current_child_support_and_had_current_support_charges=1775 m:number_of_released_inmates_who_are_gainfully_employed_and_pay_any_percentage_of_their_current_child_support_obligation_on_time=1488 m:number_of_released_inmates_who_pay_any_percentage_of_current_child_support_on_time_and_who_completed_dhr_s_non_custodial_work_program=73
```

## Meta Commands

```ls
metric m:number_of_released_inmates_who_are_gainfully_employed_and_pay_any_percentage_of_their_current_child_support_obligation_on_time p:integer l:"Number of released inmates who are gainfully employed and pay any percentage of their current child support obligation on time" t:dataTypeName=number

metric m:number_of_released_inmates_who_pay_any_percentage_of_current_child_support_on_time p:integer l:"Number of released inmates who pay any percentage of current child support on time" t:dataTypeName=number

metric m:number_of_released_inmates_who_pay_any_percentage_of_current_child_support_on_time_and_who_completed_dhr_s_non_custodial_work_program p:integer l:"Number of released inmates who pay any percentage of current child support on time AND who completed DHR?s non-custodial work program." t:dataTypeName=number

metric m:number_of_released_inmates_who_paid_no_current_child_support_and_had_current_support_charges p:integer l:"Number of released inmates who paid no current child support and had current support charges." t:dataTypeName=number

metric m:number_of_child_support_orders_with_an_inmate_obligor_that_are_modified_upon_entry_into_dpscs_facility p:integer l:"Number of child support orders with an inmate obligor that are modified upon entry into DPSCS facility." t:dataTypeName=number

metric m:number_of_child_support_orders_with_a_released_inmate_obligor_modified_within_180_days_of_release_from_prison p:integer l:"Number of child support orders with a released inmate obligor modified within 180 days of release from prison." t:dataTypeName=number

entity e:hy2h-k5f2 l:"Returning Citizen Child Support & Inmate Obligors" t:attribution="Department of Human Resources (DHR)" t:url=https://data.maryland.gov/api/views/hy2h-k5f2

property e:hy2h-k5f2 t:meta.view v:id=hy2h-k5f2 v:category="Health and Human Services" v:attributionLink=http://www.dhr.state.md.us/ v:averageRating=0 v:name="Returning Citizen Child Support & Inmate Obligors" v:attribution="Department of Human Resources (DHR)"

property e:hy2h-k5f2 t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:hy2h-k5f2 t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| :updated_at | timeframe_month_calendar_year_or_fiscal_year | number_of_released_inmates_who_are_gainfully_employed_and_pay_any_percentage_of_their_current_child_support_obligation_on_time | number_of_released_inmates_who_pay_any_percentage_of_current_child_support_on_time | number_of_released_inmates_who_pay_any_percentage_of_current_child_support_on_time_and_who_completed_dhr_s_non_custodial_work_program | number_of_released_inmates_who_paid_no_current_child_support_and_had_current_support_charges | number_of_child_support_orders_with_an_inmate_obligor_that_are_modified_upon_entry_into_dpscs_facility | number_of_child_support_orders_with_a_released_inmate_obligor_modified_within_180_days_of_release_from_prison | 
| =========== | ============================================ | ============================================================================================================================== | ================================================================================== | ===================================================================================================================================== | ============================================================================================ | ====================================================================================================== | ============================================================================================================= | 
| 1403255704  | CY2007                                       | 493                                                                                                                            | 977                                                                                | 10                                                                                                                                    | 869                                                                                          | 124                                                                                                    | 52                                                                                                            | 
| 1403255704  | CY2008                                       | 857                                                                                                                            | 1606                                                                               | 31                                                                                                                                    | 1366                                                                                         | 202                                                                                                    | 57                                                                                                            | 
| 1403255704  | CY2009                                       | 1488                                                                                                                           | 2504                                                                               | 73                                                                                                                                    | 1775                                                                                         | 366                                                                                                    | 80                                                                                                            | 
| 1403255704  | CY2010                                       | 2169                                                                                                                           | 3280                                                                               | 105                                                                                                                                   | 2286                                                                                         | 521                                                                                                    | 78                                                                                                            | 
| 1403255704  | CY2011                                       | 3223                                                                                                                           | 4291                                                                               | 163                                                                                                                                   | 2716                                                                                         | 661                                                                                                    | 121                                                                                                           | 
| 1403255704  | CY2012                                       | 4646                                                                                                                           | 5422                                                                               | 219                                                                                                                                   | 3113                                                                                         | 780                                                                                                    | 150                                                                                                           | 
| 1403255704  | CY2013                                       | 5366                                                                                                                           | 6141                                                                               | 256                                                                                                                                   | 3356                                                                                         | 845                                                                                                    | 126                                                                                                           | 
| 1403255704  | CYTD2014                                     | 4472                                                                                                                           | 5218                                                                               | 237                                                                                                                                   | 3092                                                                                         | 338                                                                                                    | 46                                                                                                            | 
| 1403255704  | FY2008                                       | 670                                                                                                                            | 1310                                                                               | 15                                                                                                                                    | 1071                                                                                         | 153                                                                                                    | 57                                                                                                            | 
| 1403255704  | FY2009                                       | 1184                                                                                                                           | 2054                                                                               | 45                                                                                                                                    | 1547                                                                                         | 273                                                                                                    | 68                                                                                                            | 
```