# Expense Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expense-bpob) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/mwzb-yiwb) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/mwzb-yiwb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/mwzb-yiwb/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | mwzb-yiwb |
| Name | Expense Budget |
| Attribution | Mayor?s Office of Management & Budget (OMB) |
| Category | City Government |
| Created | 2016-05-04T00:07:05Z |
| Publication Date | 2017-02-08T17:06:59Z |

## Description

This dataset contains expense agency data by unit of appropriation for the Adopted, Financial Plan and Modified conditions by object code.  The numbers within can be summarized to be consistent with data from either the Supporting Schedule, Departmental Estimate or the Expense, Revenue, Contact Budget.

## Columns

```ls
| Included | Schema Type    | Field Name                                             | Name                                                   | Data Type | Render Type |
| ======== | ============== | ====================================================== | ====================================================== | ========= | =========== |
| Yes      | time           | publication_date                                       | Publication Date                                       | text      | text        |
| No       |                | fiscal_year                                            | Fiscal Year                                            | number    | number      |
| Yes      | series tag     | agency_number                                          | Agency Number                                          | text      | text        |
| Yes      | series tag     | agency_name                                            | Agency Name                                            | text      | text        |
| Yes      | series tag     | unit_appropriation_number                              | Unit Appropriation Number                              | text      | text        |
| Yes      | series tag     | unit_appropriation_name                                | Unit Appropriation Name                                | text      | text        |
| Yes      | series tag     | budget_code_number                                     | Budget Code Number                                     | text      | text        |
| Yes      | series tag     | budget_code_name                                       | Budget Code Name                                       | text      | text        |
| Yes      | series tag     | object_class_number                                    | Object Class Number                                    | text      | text        |
| Yes      | series tag     | object_class_name                                      | Object Class Name                                      | text      | text        |
| Yes      | series tag     | object_code                                            | Object Code                                            | text      | text        |
| Yes      | series tag     | object_code_name                                       | Object Code Name                                       | text      | text        |
| Yes      | series tag     | intra_city_purchase_code                               | Intra-City Purchase Code                               | text      | text        |
| Yes      | series tag     | responsibility_center_code                             | Responsibility Center Code                             | text      | text        |
| Yes      | series tag     | responsibility_center_name                             | Responsibility Center Name                             | text      | text        |
| Yes      | series tag     | personal_service_other_than_personal_service_indicator | Personal Service/Other Than Personal Service Indicator | text      | text        |
| Yes      | series tag     | financial_plan_savings_flag                            | Financial Plan Savings Flag                            | text      | text        |
| Yes      | numeric metric | adopted_budget_amount                                  | Adopted Budget Amount                                  | number    | number      |
| Yes      | numeric metric | current_modified_budget_amount                         | Current Modified Budget Amount                         | number    | number      |
| Yes      | numeric metric | financial_plan_amount                                  | Financial Plan Amount                                  | number    | number      |
| Yes      | numeric metric | adopted_budget_position                                | Adopted Budget Position                                | number    | number      |
| Yes      | numeric metric | current_modified_budget_position                       | Current Modified Budget Position                       | number    | number      |
| Yes      | numeric metric | financial_plan_position                                | Financial Plan Position                                | number    | number      |
| Yes      | numeric metric | adopted_budget_number_of_contracts                     | Adopted Budget - Number of Contracts                   | number    | number      |
| Yes      | numeric metric | current_modified_budget_number_of_contracts            | Current Modified Budget - Number of Contracts          | number    | number      |
| Yes      | numeric metric | financial_plan_number_of_contracts                     | Financial Plan - Number of Contracts                   | number    | number      |
```

## Time Field

```ls
Value = publication_date
Format & Zone = yyyyMMdd
```

## Series Fields

```ls
Excluded Fields = fiscal_year
```

## Data Commands

```ls
series e:mwzb-yiwb d:2016-04-26T00:00:00.000Z t:unit_appropriation_name="OFFICE OF THE MAYOR-OTPS" t:personal_service_other_than_personal_service_indicator=O t:budget_code_number=0211 t:financial_plan_savings_flag=N t:unit_appropriation_number=021 t:agency_number=002 t:object_class_name="CONTRACTUAL SERVICES" t:object_code=619 t:object_code_name="SECURITY SERVICES" t:agency_name=MAYORALTY t:responsibility_center_name="FIRST DEPUTY MAYOR" t:object_class_number=60 t:responsibility_center_code=0053 t:budget_code_name="CHIEF OF STAFF" m:current_modified_budget_amount=320 m:financial_plan_position=0 m:current_modified_budget_number_of_contracts=1 m:adopted_budget_amount=0 m:adopted_budget_number_of_contracts=0 m:financial_plan_number_of_contracts=0 m:current_modified_budget_position=0 m:financial_plan_amount=0 m:adopted_budget_position=0

series e:mwzb-yiwb d:2016-04-26T00:00:00.000Z t:unit_appropriation_name="OFFICE OF THE MAYOR-OTPS" t:personal_service_other_than_personal_service_indicator=O t:budget_code_number=0211 t:financial_plan_savings_flag=N t:unit_appropriation_number=021 t:agency_number=002 t:object_class_name="CONTRACTUAL SERVICES" t:object_code=622 t:object_code_name="TEMPORARY SERVICES" t:agency_name=MAYORALTY t:responsibility_center_name="FIRST DEPUTY MAYOR" t:object_class_number=60 t:responsibility_center_code=0053 t:budget_code_name="CHIEF OF STAFF" m:current_modified_budget_amount=8950 m:financial_plan_position=0 m:current_modified_budget_number_of_contracts=0 m:adopted_budget_amount=9750 m:adopted_budget_number_of_contracts=0 m:financial_plan_number_of_contracts=0 m:current_modified_budget_position=0 m:financial_plan_amount=9750 m:adopted_budget_position=0

series e:mwzb-yiwb d:2016-04-26T00:00:00.000Z t:unit_appropriation_name="OFFICE OF THE MAYOR-OTPS" t:personal_service_other_than_personal_service_indicator=O t:budget_code_number=0211 t:financial_plan_savings_flag=N t:unit_appropriation_number=021 t:agency_number=002 t:object_class_name="CONTRACTUAL SERVICES" t:object_code=624 t:object_code_name="CLEANING SERVICES" t:agency_name=MAYORALTY t:responsibility_center_name="FIRST DEPUTY MAYOR" t:object_class_number=60 t:responsibility_center_code=0053 t:budget_code_name="CHIEF OF STAFF" m:current_modified_budget_amount=4500 m:financial_plan_position=0 m:current_modified_budget_number_of_contracts=1 m:adopted_budget_amount=0 m:adopted_budget_number_of_contracts=0 m:financial_plan_number_of_contracts=0 m:current_modified_budget_position=0 m:financial_plan_amount=0 m:adopted_budget_position=0
```

## Meta Commands

```ls
metric m:adopted_budget_amount p:long l:"Adopted Budget Amount" t:dataTypeName=number

metric m:current_modified_budget_amount p:long l:"Current Modified Budget Amount" t:dataTypeName=number

metric m:financial_plan_amount p:long l:"Financial Plan Amount" t:dataTypeName=number

metric m:adopted_budget_position p:integer l:"Adopted Budget Position" t:dataTypeName=number

metric m:current_modified_budget_position p:integer l:"Current Modified Budget Position" t:dataTypeName=number

metric m:financial_plan_position p:integer l:"Financial Plan Position" t:dataTypeName=number

metric m:adopted_budget_number_of_contracts p:integer l:"Adopted Budget - Number of Contracts" t:dataTypeName=number

metric m:current_modified_budget_number_of_contracts p:integer l:"Current Modified Budget - Number of Contracts" t:dataTypeName=number

metric m:financial_plan_number_of_contracts p:integer l:"Financial Plan - Number of Contracts" t:dataTypeName=number

entity e:mwzb-yiwb l:"Expense Budget" t:attribution="Mayor?s Office of Management & Budget (OMB)" t:url=https://data.cityofnewyork.us/api/views/mwzb-yiwb

property e:mwzb-yiwb t:meta.view v:id=mwzb-yiwb v:category="City Government" v:averageRating=0 v:name="Expense Budget" v:attribution="Mayor?s Office of Management & Budget (OMB)"

property e:mwzb-yiwb t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:mwzb-yiwb t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| publication_date | fiscal_year | agency_number | agency_name | unit_appropriation_number | unit_appropriation_name  | budget_code_number | budget_code_name | object_class_number | object_class_name    | object_code | object_code_name             | intra_city_purchase_code | responsibility_center_code | responsibility_center_name | personal_service_other_than_personal_service_indicator | financial_plan_savings_flag | adopted_budget_amount | current_modified_budget_amount | financial_plan_amount | adopted_budget_position | current_modified_budget_position | financial_plan_position | adopted_budget_number_of_contracts | current_modified_budget_number_of_contracts | financial_plan_number_of_contracts | 
| ================ | =========== | ============= | =========== | ========================= | ======================== | ================== | ================ | =================== | ==================== | =========== | ============================ | ======================== | ========================== | ========================== | ====================================================== | =========================== | ===================== | ============================== | ===================== | ======================= | ================================ | ======================= | ================================== | =========================================== | ================================== | 
| 20160426         | 2017        | 002           | MAYORALTY   | 021                       | OFFICE OF THE MAYOR-OTPS | 0211               | CHIEF OF STAFF   | 60                  | CONTRACTUAL SERVICES | 619         | SECURITY SERVICES            |                          | 0053                       | FIRST DEPUTY MAYOR         | O                                                      | N                           | 0                     | 320                            | 0                     | 0                       | 0                                | 0                       | 0                                  | 1                                           | 0                                  | 
| 20160426         | 2017        | 002           | MAYORALTY   | 021                       | OFFICE OF THE MAYOR-OTPS | 0211               | CHIEF OF STAFF   | 60                  | CONTRACTUAL SERVICES | 622         | TEMPORARY SERVICES           |                          | 0053                       | FIRST DEPUTY MAYOR         | O                                                      | N                           | 9750                  | 8950                           | 9750                  | 0                       | 0                                | 0                       | 0                                  | 0                                           | 0                                  | 
| 20160426         | 2017        | 002           | MAYORALTY   | 021                       | OFFICE OF THE MAYOR-OTPS | 0211               | CHIEF OF STAFF   | 60                  | CONTRACTUAL SERVICES | 624         | CLEANING SERVICES            |                          | 0053                       | FIRST DEPUTY MAYOR         | O                                                      | N                           | 0                     | 4500                           | 0                     | 0                       | 0                                | 0                       | 0                                  | 1                                           | 0                                  | 
| 20160426         | 2017        | 002           | MAYORALTY   | 021                       | OFFICE OF THE MAYOR-OTPS | 0211               | CHIEF OF STAFF   | 60                  | CONTRACTUAL SERVICES | 633         | TRANSPORTATION EXPENDITURES  |                          | 0053                       | FIRST DEPUTY MAYOR         | O                                                      | N                           | 0                     | 2000                           | 0                     | 0                       | 0                                | 0                       | 0                                  | 1                                           | 0                                  | 
| 20160426         | 2017        | 002           | MAYORALTY   | 021                       | OFFICE OF THE MAYOR-OTPS | 0211               | CHIEF OF STAFF   | 60                  | CONTRACTUAL SERVICES | 684         | PROF SERV COMPUTER SERVICES  |                          | 0053                       | FIRST DEPUTY MAYOR         | O                                                      | N                           | 0                     | 15390                          | 0                     | 0                       | 0                                | 0                       | 0                                  | 1                                           | 0                                  | 
| 20160426         | 2017        | 002           | MAYORALTY   | 021                       | OFFICE OF THE MAYOR-OTPS | 0211               | CHIEF OF STAFF   | 60                  | CONTRACTUAL SERVICES | 600         | CONTRACTUAL SERVICES GENERAL |                          | 0053                       | FIRST DEPUTY MAYOR         | O                                                      | N                           | 0                     | 66210                          | 0                     | 0                       | 0                                | 0                       | 0                                  | 0                                           | 0                                  | 
| 20160426         | 2017        | 002           | MAYORALTY   | 021                       | OFFICE OF THE MAYOR-OTPS | 0211               | CHIEF OF STAFF   | 60                  | CONTRACTUAL SERVICES | 608         | MAINT & REP GENERAL          |                          | 0053                       | FIRST DEPUTY MAYOR         | O                                                      | N                           | 0                     | 6000                           | 0                     | 0                       | 0                                | 0                       | 0                                  | 0                                           | 0                                  | 
| 20160426         | 2017        | 002           | MAYORALTY   | 021                       | OFFICE OF THE MAYOR-OTPS | 0211               | CHIEF OF STAFF   | 60                  | CONTRACTUAL SERVICES | 612         | OFFICE EQUIPMENT MAINTENANCE |                          | 0053                       | FIRST DEPUTY MAYOR         | O                                                      | N                           | 10000                 | 5500                           | 10000                 | 0                       | 0                                | 0                       | 0                                  | 0                                           | 0                                  | 
| 20160426         | 2017        | 002           | MAYORALTY   | 021                       | OFFICE OF THE MAYOR-OTPS | 0211               | CHIEF OF STAFF   | 60                  | CONTRACTUAL SERVICES | 613         | DATA PROCESSING EQUIPMENT    |                          | 0053                       | FIRST DEPUTY MAYOR         | O                                                      | N                           | 0                     | 55195                          | 0                     | 0                       | 0                                | 0                       | 0                                  | 1                                           | 0                                  | 
| 20160426         | 2017        | 002           | MAYORALTY   | 021                       | OFFICE OF THE MAYOR-OTPS | 0211               | CHIEF OF STAFF   | 60                  | CONTRACTUAL SERVICES | 615         | PRINTING CONTRACTS           |                          | 0053                       | FIRST DEPUTY MAYOR         | O                                                      | N                           | 0                     | 4150                           | 0                     | 0                       | 0                                | 0                       | 0                                  | 0                                           | 0                                  | 
```