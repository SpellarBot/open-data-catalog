# Non- Controllable Agency Expenses Financial Plan

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/non-controllable-agency-expenses-financial-plan-e0961) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/m6yw-2k8k) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/m6yw-2k8k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/m6yw-2k8k/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | m6yw-2k8k |
| Name | Non- Controllable Agency Expenses Financial Plan |
| Attribution | Office of the Mayor (OTM) |
| Category | City Government |
| Tags | controllable, expenses, uniformed forces, health and welfare, elected officals |
| Created | 2013-02-13T21:49:24Z |
| Publication Date | 2013-06-26T17:10:18Z |

## Description

Financial plan representing Non-Controllable Agency Expenses

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                         | Data Type | Render Type |
| ======== | ============== | ========================================== | ============================================ | ========= | =========== |
| No       | time           | :updated_at                                | updated_at                                   | meta_data | meta_data   |
| Yes      | series tag     | non_controllable_agency_expenses           | Non-Controllable Agency Expenses             | text      | text        |
| Yes      | numeric metric | pensions                                   | Pensions                                     | money     | money       |
| Yes      | numeric metric | fringe_benefits                            | Fringe Benefits                              | money     | money       |
| Yes      | series tag     | retiree_health_benefits_trust              | Retiree Health Benefits Trust                | text      | text        |
| Yes      | numeric metric | employee_related_costs                     | Employee-Related Costs                       | money     | money       |
| Yes      | numeric metric | medicaid                                   | Medicaid                                     | money     | money       |
| Yes      | series tag     | fmap_federal_matching_percent_for_medicaid | FMAP (Federal Matching Percent for Medicaid) | text      | text        |
| Yes      | series tag     | reserve_for_claims_from_past_periods       | Reserve for Claims From Past Periods         | text      | text        |
| Yes      | series tag     | general_reserve                            | General Reserve                              | text      | text        |
| Yes      | numeric metric | all_other                                  | All Other                                    | money     | money       |
| Yes      | numeric metric | subtotal_non_controllable_expenses         | Subtotal: Non-Controllable Expenses          | money     | money       |
| Yes      | numeric metric | debt_service                               | Debt Service                                 | money     | money       |
| Yes      | numeric metric | total_non_controllable_and_debt_service    | Total Non-Controllable and Debt Service      | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:m6yw-2k8k d:2013-02-13T13:49:26.000Z t:fmap_federal_matching_percent_for_medicaid=-$124.00 t:retiree_health_benefits_trust=-$672.00 t:reserve_for_claims_from_past_periods=-$215.00 t:non_controllable_agency_expenses="FY 2012" t:general_reserve="$ - - -" m:total_non_controllable_and_debt_service=26447 m:fringe_benefits=6226 m:debt_service=4976 m:pensions=7798 m:subtotal_non_controllable_expenses=21471 m:all_other=2241 m:medicaid=6217 m:employee_related_costs=13352

series e:m6yw-2k8k d:2013-02-13T13:49:26.000Z t:fmap_federal_matching_percent_for_medicaid=-$32.00 t:retiree_health_benefits_trust=-$1,000.00 t:reserve_for_claims_from_past_periods=-$500.00 t:non_controllable_agency_expenses="FY 2013" t:general_reserve=$100.00 m:total_non_controllable_and_debt_service=27261 m:fringe_benefits=6523 m:debt_service=5644 m:pensions=7905 m:subtotal_non_controllable_expenses=21617 m:all_other=2398 m:medicaid=6223 m:employee_related_costs=13428

series e:m6yw-2k8k d:2013-02-13T13:49:26.000Z t:fmap_federal_matching_percent_for_medicaid="$ - - -" t:retiree_health_benefits_trust=-$1,000.00 t:reserve_for_claims_from_past_periods="$ - - -" t:non_controllable_agency_expenses="FY 2014" t:general_reserve=$300.00 m:total_non_controllable_and_debt_service=29105 m:fringe_benefits=7009 m:debt_service=6021 m:pensions=8055 m:subtotal_non_controllable_expenses=23084 m:all_other=2447 m:medicaid=6273 m:employee_related_costs=14064
```

## Meta Commands

```ls
metric m:pensions p:double l:Pensions t:dataTypeName=money

metric m:fringe_benefits p:double l:"Fringe Benefits" t:dataTypeName=money

metric m:employee_related_costs p:double l:"Employee-Related Costs" t:dataTypeName=money

metric m:medicaid p:double l:Medicaid t:dataTypeName=money

metric m:all_other p:double l:"All Other" t:dataTypeName=money

metric m:subtotal_non_controllable_expenses p:double l:"Subtotal: Non-Controllable Expenses" t:dataTypeName=money

metric m:debt_service p:double l:"Debt Service" t:dataTypeName=money

metric m:total_non_controllable_and_debt_service p:double l:"Total Non-Controllable and Debt Service" t:dataTypeName=money

entity e:m6yw-2k8k l:"Non- Controllable Agency Expenses Financial Plan" t:attribution="Office of the Mayor (OTM)" t:url=https://data.cityofnewyork.us/api/views/m6yw-2k8k

property e:m6yw-2k8k t:meta.view v:id=m6yw-2k8k v:category="City Government" v:attributionLink=http://www.nyc.gov/html/omb/downloads/pdf/sum1_13.pdf v:averageRating=0 v:name="Non- Controllable Agency Expenses Financial Plan" v:attribution="Office of the Mayor (OTM)"

property e:m6yw-2k8k t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:m6yw-2k8k t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| :updated_at | non_controllable_agency_expenses | pensions | fringe_benefits | retiree_health_benefits_trust | employee_related_costs | medicaid | fmap_federal_matching_percent_for_medicaid | reserve_for_claims_from_past_periods | general_reserve | all_other | subtotal_non_controllable_expenses | debt_service | total_non_controllable_and_debt_service | 
| =========== | ================================ | ======== | =============== | ============================= | ====================== | ======== | ========================================== | ==================================== | =============== | ========= | ================================== | ============ | ======================================= | 
| 1360763366  | FY 2012                          | 7798.00  | 6226.00         | -$672.00                      | 13352.00               | 6217.00  | -$124.00                                   | -$215.00                             | $ - - -         | 2241.00   | 21471.00                           | 4976.00      | 26447.00                                | 
| 1360763366  | FY 2013                          | 7905.00  | 6523.00         | -$1,000.00                    | 13428.00               | 6223.00  | -$32.00                                    | -$500.00                             | $100.00         | 2398.00   | 21617.00                           | 5644.00      | 27261.00                                | 
| 1360763366  | FY 2014                          | 8055.00  | 7009.00         | -$1,000.00                    | 14064.00               | 6273.00  | $ - - -                                    | $ - - -                              | $300.00         | 2447.00   | 23084.00                           | 6021.00      | 29105.00                                | 
| 1360763366  | FY 2015                          | 8047.00  | 7788.00         | $ - - -                       | 15835.00               | 6354.00  | $ - - -                                    | $ - - -                              | $300.00         | 2630.00   | 25119.00                           | 6879.00      | 31998.00                                | 
| 1360763366  | FY 2016                          | 8242.00  | 8444.00         | $ - - -                       | 16686.00               | 6323.00  | $ - - -                                    | $ - - -                              | $300.00         | 2690.00   | 25999.00                           | 7200.00      | 33199.00                                | 
| 1360763366  | FY 2017                          | 8495.00  | 9131.00         | $ - - -                       | 17626.00               | 6323.00  | $ - - -                                    | $ - - -                              | $300.00         | 2813.00   | 27062.00                           | 7413.00      | 34475.00                                | 
```