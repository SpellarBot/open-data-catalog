# Dashboard Template - Department of Budget and Management (DBM) June 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dashboard-template-department-of-budget-and-management-dbm-june-2016) |
| Metadata | [Link](https://data.maryland.gov/api/views/r6ug-dr3g) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/r6ug-dr3g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/r6ug-dr3g/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | r6ug-dr3g |
| Name | Dashboard Template - Department of Budget and Management (DBM) June 2016 |
| Attribution | Department of Budget and Management |
| Category | Administrative |
| Tags | debt, personnel, fleet, procurement, dbm, department of budget and management |
| Created | 2016-07-24T15:25:49Z |
| Publication Date | 2017-02-17T18:23:59Z |

## Description

Department of Budget and Management data (personnel, debt, fleet, procurement)

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                                                    | Name                                                                                                                              | Data Type     | Render Type   |
| ======== | ============== | ============================================================================================================================= | ================================================================================================================================= | ============= | ============= |
| Yes      | time           | date                                                                                                                          | Date for Fiscal Year                                                                                                              | calendar_date | calendar_date |
| No       |                | year                                                                                                                          | Year                                                                                                                              | text          | text          |
| Yes      | numeric metric | percentage_of_debts_with_payment_recovered_compared_to_total_debt_assigned_to_central_collections_unit_during_the_fiscal_year | Percentage of debts with payment recovered compared to total debt assigned to Central Collections Unit during the fiscal year (%) | percent       | percent       |
| Yes      | numeric metric | executive_branch_agency_staff_retention_rate                                                                                  | Executive branch agency staff retention rate (%)                                                                                  | percent       | percent       |
| Yes      | numeric metric | executive_branch_agency_staff_vacancy_rate                                                                                    | Executive branch agency staff vacancy rate                                                                                        | percent       | percent       |
| Yes      | numeric metric | executive_branch_agency_staff_turnover_rate                                                                                   | Executive branch agency staff turnover rate                                                                                       | percent       | percent       |
| Yes      | numeric metric | number_of_competitive_procurements_valued_in_excess_of_50_000_with_2_or_more_bids_or_proposals                                | Number of competitive procurements valued in excess of $50,000 with 2 or more bids or proposals                                   | number        | number        |
| Yes      | numeric metric | number_of_competitive_procurements_valued_in_excess_of_50_000_with_only_one_bid_or_proposal                                   | Number of competitive procurements valued in excess of $50,000 with only one bid or proposal                                      | number        | number        |
| Yes      | numeric metric | percentage_of_competitive_procurements_valued_in_excess_of_50_000_with_2_or_more_bids_or_proposals                            | Percentage of competitive procurements valued in excess of $50,000 with 2 or more bids or proposals                               | percent       | percent       |
| No       |                | date_for_calendar_year                                                                                                        | Date for Calendar Year                                                                                                            | calendar_date | calendar_date |
| Yes      | numeric metric | average_operating_cost_per_mile_of_maryland_state_owned_vehicle_fleet                                                         | Average operating cost per mile of Maryland State-owned vehicle fleet (CY)                                                        | money         | money         |
| Yes      | numeric metric | average_operating_cost_per_mile_of_private_vehicles                                                                           | Average operating cost per mile of private vehicles (CY)                                                                          | money         | money         |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_for_calendar_year,year
```

## Data Commands

```ls
series e:r6ug-dr3g d:2011-06-30T00:00:00.000Z m:executive_branch_agency_staff_vacancy_rate=8.45 m:executive_branch_agency_staff_retention_rate=89 m:average_operating_cost_per_mile_of_maryland_state_owned_vehicle_fleet=0.16 m:average_operating_cost_per_mile_of_private_vehicles=0.17 m:executive_branch_agency_staff_turnover_rate=9.15

series e:r6ug-dr3g d:2012-06-30T00:00:00.000Z m:number_of_competitive_procurements_valued_in_excess_of_50_000_with_only_one_bid_or_proposal=13 m:executive_branch_agency_staff_vacancy_rate=8.41 m:number_of_competitive_procurements_valued_in_excess_of_50_000_with_2_or_more_bids_or_proposals=103 m:percentage_of_competitive_procurements_valued_in_excess_of_50_000_with_2_or_more_bids_or_proposals=89 m:executive_branch_agency_staff_retention_rate=91 m:average_operating_cost_per_mile_of_maryland_state_owned_vehicle_fleet=0.16 m:average_operating_cost_per_mile_of_private_vehicles=0.16 m:executive_branch_agency_staff_turnover_rate=10.42

series e:r6ug-dr3g d:2013-06-30T00:00:00.000Z m:number_of_competitive_procurements_valued_in_excess_of_50_000_with_only_one_bid_or_proposal=21 m:executive_branch_agency_staff_vacancy_rate=8.94 m:number_of_competitive_procurements_valued_in_excess_of_50_000_with_2_or_more_bids_or_proposals=93 m:percentage_of_competitive_procurements_valued_in_excess_of_50_000_with_2_or_more_bids_or_proposals=82 m:executive_branch_agency_staff_retention_rate=91 m:average_operating_cost_per_mile_of_maryland_state_owned_vehicle_fleet=0.14 m:average_operating_cost_per_mile_of_private_vehicles=0.15 m:executive_branch_agency_staff_turnover_rate=10.85
```

## Meta Commands

```ls
metric m:percentage_of_debts_with_payment_recovered_compared_to_total_debt_assigned_to_central_collections_unit_during_the_fiscal_year p:integer l:"Percentage of debts with payment recovered compared to total debt assigned to Central Collections Unit during the fiscal year (%)" t:dataTypeName=percent

metric m:executive_branch_agency_staff_retention_rate p:integer l:"Executive branch agency staff retention rate (%)" t:dataTypeName=percent

metric m:executive_branch_agency_staff_vacancy_rate p:float l:"Executive branch agency staff vacancy rate" t:dataTypeName=percent

metric m:executive_branch_agency_staff_turnover_rate p:float l:"Executive branch agency staff turnover rate" t:dataTypeName=percent

metric m:number_of_competitive_procurements_valued_in_excess_of_50_000_with_2_or_more_bids_or_proposals p:integer l:"Number of competitive procurements valued in excess of $50,000 with 2 or more bids or proposals" t:dataTypeName=number

metric m:number_of_competitive_procurements_valued_in_excess_of_50_000_with_only_one_bid_or_proposal p:integer l:"Number of competitive procurements valued in excess of $50,000 with only one bid or proposal" t:dataTypeName=number

metric m:percentage_of_competitive_procurements_valued_in_excess_of_50_000_with_2_or_more_bids_or_proposals p:integer l:"Percentage of competitive procurements valued in excess of $50,000 with 2 or more bids or proposals" t:dataTypeName=percent

metric m:average_operating_cost_per_mile_of_maryland_state_owned_vehicle_fleet p:double l:"Average operating cost per mile of Maryland State-owned vehicle fleet (CY)" d:"calculated on a calendar year basis" t:dataTypeName=money

metric m:average_operating_cost_per_mile_of_private_vehicles p:double l:"Average operating cost per mile of private vehicles (CY)" d:"calculated on a calendar year basis" t:dataTypeName=money

entity e:r6ug-dr3g l:"Dashboard Template - Department of Budget and Management (DBM) June 2016" t:attribution="Department of Budget and Management" t:url=https://data.maryland.gov/api/views/r6ug-dr3g

property e:r6ug-dr3g t:meta.view v:id=r6ug-dr3g v:category=Administrative v:attributionLink=http://www.dbm.maryland.gov v:averageRating=0 v:name="Dashboard Template - Department of Budget and Management (DBM) June 2016" v:attribution="Department of Budget and Management"

property e:r6ug-dr3g t:meta.view.license v:name="Public Domain"

property e:r6ug-dr3g t:meta.view.owner v:id=e92k-eqcw v:screenName="Cheri Gerard" v:displayName="Cheri Gerard"

property e:r6ug-dr3g t:meta.view.tableauthor v:id=e92k-eqcw v:screenName="Cheri Gerard" v:roleName=editor v:displayName="Cheri Gerard"
```

## Top Records

```ls
| date                | year | percentage_of_debts_with_payment_recovered_compared_to_total_debt_assigned_to_central_collections_unit_during_the_fiscal_year | executive_branch_agency_staff_retention_rate | executive_branch_agency_staff_vacancy_rate | executive_branch_agency_staff_turnover_rate | number_of_competitive_procurements_valued_in_excess_of_50_000_with_2_or_more_bids_or_proposals | number_of_competitive_procurements_valued_in_excess_of_50_000_with_only_one_bid_or_proposal | percentage_of_competitive_procurements_valued_in_excess_of_50_000_with_2_or_more_bids_or_proposals | date_for_calendar_year | average_operating_cost_per_mile_of_maryland_state_owned_vehicle_fleet | average_operating_cost_per_mile_of_private_vehicles | 
| =================== | ==== | ============================================================================================================================= | ============================================ | ========================================== | =========================================== | ============================================================================================== | =========================================================================================== | ================================================================================================== | ====================== | ===================================================================== | =================================================== | 
| 2011-06-30T00:00:00 | 2011 |                                                                                                                               | 89                                           | 8.45                                       | 9.15                                        |                                                                                                |                                                                                             |                                                                                                    | 2011-12-31T00:00:00    | 0.16                                                                  | 0.17                                                | 
| 2012-06-30T00:00:00 | 2012 |                                                                                                                               | 91                                           | 8.41                                       | 10.42                                       | 103                                                                                            | 13                                                                                          | 89                                                                                                 | 2012-12-31T00:00:00    | 0.16                                                                  | 0.16                                                | 
| 2013-06-30T00:00:00 | 2013 |                                                                                                                               | 91                                           | 8.94                                       | 10.85                                       | 93                                                                                             | 21                                                                                          | 82                                                                                                 | 2013-12-31T00:00:00    | 0.14000000000000001                                                   | 0.15                                                | 
| 2014-06-30T00:00:00 | 2014 |                                                                                                                               | 90                                           | 8.78                                       | 10.01                                       | 130                                                                                            | 33                                                                                          | 80                                                                                                 | 2014-12-31T00:00:00    | 0.1                                                                   | 0.13                                                | 
| 2015-06-30T00:00:00 | 2015 | 27                                                                                                                            | 90                                           | 12.99                                      | 10.90                                       | 86                                                                                             | 28                                                                                          | 75                                                                                                 | 2015-12-31T00:00:00    | 0.1                                                                   |                                                     | 
| 2016-06-30T00:00:00 | 2016 | 3                                                                                                                             | 88                                           |                                            |                                             |                                                                                                |                                                                                             | 90                                                                                                 | 2016-12-31T00:00:00    |                                                                       |                                                     | 
```