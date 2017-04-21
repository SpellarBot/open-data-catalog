# DP Scoring Report Final

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dp-scoring-report-final-b4f2a) |
| Metadata | [Link](https://data.wa.gov/api/views/swyb-gmfy) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/swyb-gmfy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/swyb-gmfy/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | swyb-gmfy |
| Name | DP Scoring Report Final |
| Created | 2015-01-10T00:35:23Z |
| Publication Date | 2015-02-18T01:23:59Z |

## Description

Final results of IT Decision Package scoring process

## Columns

```ls
| Included | Schema Type    | Field Name                                                    | Name                                                              | Data Type | Render Type |
| ======== | ============== | ============================================================= | ================================================================= | ========= | =========== |
| No       | time           | :updated_at                                                   | updated_at                                                        | meta_data | meta_data   |
| Yes      | numeric metric | rank_order                                                    | Rank Order                                                        | number    | number      |
| Yes      | series tag     | agency                                                        | Agency                                                            | text      | text        |
| Yes      | series tag     | decision_package_title                                        | Decision Package Title                                            | text      | text        |
| Yes      | series tag     | ml_pl                                                         | ML/ PL                                                            | text      | text        |
| Yes      | numeric metric | agency_priority                                               | Agency Priority                                                   | number    | number      |
| Yes      | numeric metric | score                                                         | Score                                                             | number    | number      |
| Yes      | numeric metric | security_score_weight_0_200                                   | Security Score (Weight: 0.200)                                    | number    | number      |
| Yes      | numeric metric | cultural_readiness_organizational_capacity_score_weight_0_036 | Cultural Readiness/ Organizational Capacity Score (Weight: 0.036) | number    | number      |
| Yes      | numeric metric | technical_simplicity_score_weight_0_023                       | Technical Simplicity Score (Weight: 0.023)                        | number    | number      |
| Yes      | numeric metric | urgency_score_weight_0_067                                    | Urgency Score (Weight: 0.067)                                     | number    | number      |
| Yes      | numeric metric | impact_of_not_doing_score_weight_0_115                        | Impact of Not Doing Score (Weight: 0.115)                         | number    | number      |
| Yes      | numeric metric | agile_value_score_weight_0_042                                | Agile Value Score (Weight: 0.042)                                 | number    | number      |
| Yes      | numeric metric | modernization_of_state_government_score_weight_0_042          | Modernization of State Government Score (Weight: 0.042)           | number    | number      |
| Yes      | numeric metric | mobility_score_weight_0_021                                   | Mobility Score (Weight: 0.021)                                    | number    | number      |
| Yes      | numeric metric | transparency_score_weight_0_009                               | Transparency Score (Weight: 0.009)                                | number    | number      |
| Yes      | numeric metric | accountability_score_weight_0_028                             | Accountability Score (Weight: 0.028)                              | number    | number      |
| Yes      | numeric metric | leverages_federal_grant_funding_score_weight_0_042            | Leverages Federal/Grant Funding Score (Weight: 0.042)             | number    | number      |
| Yes      | numeric metric | reduces_costs_score_weight_0_039                              | Reduces Costs Score (Weight: 0.039)                               | number    | number      |
| Yes      | numeric metric | captures_new_or_unrealized_revenue_score_weight_0_052         | Captures New or Unrealized Revenue Score (Weight: 0.052)          | number    | number      |
| Yes      | numeric metric | business_importance_score_weight_0_236                        | Business Importance Score (Weight: 0.236)                         | number    | number      |
| Yes      | numeric metric | judgement_score_weight_0_050                                  | Judgement Score (Weight: 0.050)                                   | number    | number      |
| Yes      | numeric metric | fy2016_funding_request                                        | FY2016 Funding Request                                            | number    | number      |
| Yes      | numeric metric | fy2017_funding_request                                        | FY2017 Funding Request                                            | number    | number      |
| Yes      | numeric metric | biennium_funding_request                                      | Biennium Funding Request                                          | number    | number      |
| Yes      | numeric metric | near_gen_fund_funding_request                                 | Near Gen Fund Funding Request                                     | number    | number      |
| Yes      | numeric metric | other_funding_request                                         | Other Funding Request                                             | number    | number      |
| Yes      | numeric metric | transportation_funding_request                                | Transportation Funding Request                                    | number    | number      |
| Yes      | numeric metric | federal_funding_request                                       | Federal Funding Request                                           | number    | number      |
| Yes      | numeric metric | near_gfs_gov_budget                                           | Near-GFS (Gov Budget)                                             | number    | number      |
| Yes      | numeric metric | other_gov_budget                                              | Other (Gov Budget)                                                | number    | number      |
| Yes      | numeric metric | transportation_gov_budget                                     | Transportation (Gov Budget)                                       | number    | number      |
| Yes      | numeric metric | federal_gov_budget                                            | Federal (Gov Budget)                                              | number    | number      |
| Yes      | numeric metric | total_funds_gov_budget                                        | Total Funds (Gov Budget)                                          | number    | number      |
| Yes      | numeric metric | percent_funded_gov_budget                                     | Percent Funded (Gov Budget)                                       | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:swyb-gmfy d:2015-02-17T17:22:19.000Z t:ml_pl=PL t:decision_package_title="Modernization of Regulatory Systems" t:agency=LCB m:federal_funding_request=0 m:score=0.677 m:other_funding_request=3321000 m:percent_funded_gov_budget=100 m:judgement_score_weight_0_050=0.5 m:agile_value_score_weight_0_042=1 m:agency_priority=1 m:reduces_costs_score_weight_0_039=0 m:rank_order=1 m:cultural_readiness_organizational_capacity_score_weight_0_036=0.6 m:leverages_federal_grant_funding_score_weight_0_042=0 m:urgency_score_weight_0_067=0.9 m:transportation_funding_request=0 m:transparency_score_weight_0_009=0.7 m:biennium_funding_request=3321000 m:mobility_score_weight_0_021=0.8 m:other_gov_budget=3321000 m:technical_simplicity_score_weight_0_023=0.5 m:transportation_gov_budget=0 m:fy2017_funding_request=1460400 m:security_score_weight_0_200=0.5 m:business_importance_score_weight_0_236=1 m:near_gfs_gov_budget=0 m:captures_new_or_unrealized_revenue_score_weight_0_052=0 m:modernization_of_state_government_score_weight_0_042=1 m:impact_of_not_doing_score_weight_0_115=0.8 m:federal_gov_budget=0 m:fy2016_funding_request=1860600 m:total_funds_gov_budget=3321000 m:near_gen_fund_funding_request=0 m:accountability_score_weight_0_028=0.9

series e:swyb-gmfy d:2015-02-17T17:22:19.000Z t:ml_pl=ML t:decision_package_title="IT Security Requirements" t:agency=DSHS m:federal_funding_request=242000 m:score=0.671 m:other_funding_request=0 m:percent_funded_gov_budget=0 m:judgement_score_weight_0_050=0 m:agile_value_score_weight_0_042=0.75 m:agency_priority=14 m:reduces_costs_score_weight_0_039=0 m:rank_order=2 m:cultural_readiness_organizational_capacity_score_weight_0_036=0.875 m:leverages_federal_grant_funding_score_weight_0_042=0.5 m:urgency_score_weight_0_067=0.75 m:transportation_funding_request=0 m:transparency_score_weight_0_009=0 m:biennium_funding_request=484000 m:mobility_score_weight_0_021=0 m:other_gov_budget=0 m:technical_simplicity_score_weight_0_023=0.875 m:transportation_gov_budget=0 m:fy2017_funding_request=242000 m:security_score_weight_0_200=1 m:business_importance_score_weight_0_236=0.875 m:near_gfs_gov_budget=0 m:captures_new_or_unrealized_revenue_score_weight_0_052=0 m:modernization_of_state_government_score_weight_0_042=0 m:impact_of_not_doing_score_weight_0_115=0.75 m:federal_gov_budget=0 m:fy2016_funding_request=242000 m:total_funds_gov_budget=0 m:near_gen_fund_funding_request=242000 m:accountability_score_weight_0_028=0.875

series e:swyb-gmfy d:2015-02-17T17:22:19.000Z t:ml_pl=ML t:decision_package_title="Align Funding with ICD 10 Imp." t:agency=DSHS m:federal_funding_request=0 m:score=0.668 m:other_funding_request=0 m:percent_funded_gov_budget=100 m:judgement_score_weight_0_050=0.5 m:agile_value_score_weight_0_042=0.5 m:agency_priority=5 m:reduces_costs_score_weight_0_039=0 m:rank_order=3 m:cultural_readiness_organizational_capacity_score_weight_0_036=1 m:leverages_federal_grant_funding_score_weight_0_042=0 m:urgency_score_weight_0_067=1 m:transportation_funding_request=0 m:transparency_score_weight_0_009=0.125 m:biennium_funding_request=2003000 m:mobility_score_weight_0_021=0.5 m:other_gov_budget=0 m:technical_simplicity_score_weight_0_023=1 m:transportation_gov_budget=0 m:fy2017_funding_request=0 m:security_score_weight_0_200=0.437 m:business_importance_score_weight_0_236=1 m:near_gfs_gov_budget=2003000 m:captures_new_or_unrealized_revenue_score_weight_0_052=0 m:modernization_of_state_government_score_weight_0_042=1 m:impact_of_not_doing_score_weight_0_115=0.875 m:federal_gov_budget=0 m:fy2016_funding_request=2003000 m:total_funds_gov_budget=2003000 m:near_gen_fund_funding_request=2003000 m:accountability_score_weight_0_028=0.687
```

## Meta Commands

```ls
metric m:rank_order p:integer l:"Rank Order" t:dataTypeName=number

metric m:agency_priority p:integer l:"Agency Priority" t:dataTypeName=number

metric m:score p:float l:Score t:dataTypeName=number

metric m:security_score_weight_0_200 p:float l:"Security Score (Weight: 0.200)" t:dataTypeName=number

metric m:cultural_readiness_organizational_capacity_score_weight_0_036 p:float l:"Cultural Readiness/ Organizational Capacity Score (Weight: 0.036)" t:dataTypeName=number

metric m:technical_simplicity_score_weight_0_023 p:float l:"Technical Simplicity Score (Weight: 0.023)" t:dataTypeName=number

metric m:urgency_score_weight_0_067 p:float l:"Urgency Score (Weight: 0.067)" t:dataTypeName=number

metric m:impact_of_not_doing_score_weight_0_115 p:float l:"Impact of Not Doing Score (Weight: 0.115)" t:dataTypeName=number

metric m:agile_value_score_weight_0_042 p:float l:"Agile Value Score (Weight: 0.042)" t:dataTypeName=number

metric m:modernization_of_state_government_score_weight_0_042 p:float l:"Modernization of State Government Score (Weight: 0.042)" t:dataTypeName=number

metric m:mobility_score_weight_0_021 p:float l:"Mobility Score (Weight: 0.021)" t:dataTypeName=number

metric m:transparency_score_weight_0_009 p:float l:"Transparency Score (Weight: 0.009)" t:dataTypeName=number

metric m:accountability_score_weight_0_028 p:float l:"Accountability Score (Weight: 0.028)" t:dataTypeName=number

metric m:leverages_federal_grant_funding_score_weight_0_042 p:float l:"Leverages Federal/Grant Funding Score (Weight: 0.042)" t:dataTypeName=number

metric m:reduces_costs_score_weight_0_039 p:float l:"Reduces Costs Score (Weight: 0.039)" t:dataTypeName=number

metric m:captures_new_or_unrealized_revenue_score_weight_0_052 p:float l:"Captures New or Unrealized Revenue Score (Weight: 0.052)" t:dataTypeName=number

metric m:business_importance_score_weight_0_236 p:float l:"Business Importance Score (Weight: 0.236)" t:dataTypeName=number

metric m:judgement_score_weight_0_050 p:float l:"Judgement Score (Weight: 0.050)" t:dataTypeName=number

metric m:fy2016_funding_request p:integer l:"FY2016 Funding Request" t:dataTypeName=number

metric m:fy2017_funding_request p:integer l:"FY2017 Funding Request" t:dataTypeName=number

metric m:biennium_funding_request p:integer l:"Biennium Funding Request" t:dataTypeName=number

metric m:near_gen_fund_funding_request p:integer l:"Near Gen Fund Funding Request" t:dataTypeName=number

metric m:other_funding_request p:integer l:"Other Funding Request" t:dataTypeName=number

metric m:transportation_funding_request p:integer l:"Transportation Funding Request" t:dataTypeName=number

metric m:federal_funding_request p:integer l:"Federal Funding Request" t:dataTypeName=number

metric m:near_gfs_gov_budget p:integer l:"Near-GFS (Gov Budget)" t:dataTypeName=number

metric m:other_gov_budget p:integer l:"Other (Gov Budget)" t:dataTypeName=number

metric m:transportation_gov_budget p:integer l:"Transportation (Gov Budget)" t:dataTypeName=number

metric m:federal_gov_budget p:integer l:"Federal (Gov Budget)" t:dataTypeName=number

metric m:total_funds_gov_budget p:integer l:"Total Funds (Gov Budget)" t:dataTypeName=number

metric m:percent_funded_gov_budget p:integer l:"Percent Funded (Gov Budget)" t:dataTypeName=percent

entity e:swyb-gmfy l:"DP Scoring Report Final" t:url=https://data.wa.gov/api/views/swyb-gmfy

property e:swyb-gmfy t:meta.view v:id=swyb-gmfy v:averageRating=0 v:name="DP Scoring Report Final"

property e:swyb-gmfy t:meta.view.owner v:id=bjfs-pe5a v:screenName=justinb.ocio v:displayName=justinb.ocio

property e:swyb-gmfy t:meta.view.tableauthor v:id=bjfs-pe5a v:screenName=justinb.ocio v:roleName=publisher v:displayName=justinb.ocio
```

## Top Records

```ls
| :updated_at | rank_order | agency | decision_package_title                     | ml_pl | agency_priority | score | security_score_weight_0_200 | cultural_readiness_organizational_capacity_score_weight_0_036 | technical_simplicity_score_weight_0_023 | urgency_score_weight_0_067 | impact_of_not_doing_score_weight_0_115 | agile_value_score_weight_0_042 | modernization_of_state_government_score_weight_0_042 | mobility_score_weight_0_021 | transparency_score_weight_0_009 | accountability_score_weight_0_028 | leverages_federal_grant_funding_score_weight_0_042 | reduces_costs_score_weight_0_039 | captures_new_or_unrealized_revenue_score_weight_0_052 | business_importance_score_weight_0_236 | judgement_score_weight_0_050 | fy2016_funding_request | fy2017_funding_request | biennium_funding_request | near_gen_fund_funding_request | other_funding_request | transportation_funding_request | federal_funding_request | near_gfs_gov_budget | other_gov_budget | transportation_gov_budget | federal_gov_budget | total_funds_gov_budget | percent_funded_gov_budget | 
| =========== | ========== | ====== | ========================================== | ===== | =============== | ===== | =========================== | ============================================================= | ======================================= | ========================== | ====================================== | ============================== | ==================================================== | =========================== | =============================== | ================================= | ================================================== | ================================ | ===================================================== | ====================================== | ============================ | ====================== | ====================== | ======================== | ============================= | ===================== | ============================== | ======================= | =================== | ================ | ========================= | ================== | ====================== | ========================= | 
| 1424193739  | 1          | LCB    | Modernization of Regulatory Systems        | PL    | 1               | 0.677 | 0.500                       | 0.600                                                         | 0.500                                   | 0.900                      | 0.800                                  | 1.000                          | 1.000                                                | 0.800                       | 0.700                           | 0.900                             | 0.000                                              | 0.000                            | 0.000                                                 | 1.000                                  | 0.500                        | 1860600                | 1460400                | 3321000                  | 0                             | 3321000               | 0                              | 0                       | 0                   | 3321000          | 0                         | 0                  | 3321000                | 100                       | 
| 1424193739  | 2          | DSHS   | IT Security Requirements                   | ML    | 14              | 0.671 | 1.000                       | 0.875                                                         | 0.875                                   | 0.750                      | 0.750                                  | 0.750                          | 0.000                                                | 0.000                       | 0.000                           | 0.875                             | 0.500                                              | 0.000                            | 0.000                                                 | 0.875                                  | 0.000                        | 242000                 | 242000                 | 484000                   | 242000                        | 0                     | 0                              | 242000                  | 0                   | 0                | 0                         | 0                  | 0                      | 0                         | 
| 1424193739  | 3          | DSHS   | Align Funding with ICD 10 Imp.             | ML    | 5               | 0.668 | 0.437                       | 1.000                                                         | 1.000                                   | 1.000                      | 0.875                                  | 0.500                          | 1.000                                                | 0.500                       | 0.125                           | 0.687                             | 0.000                                              | 0.000                            | 0.000                                                 | 1.000                                  | 0.500                        | 2003000                | 0                      | 2003000                  | 2003000                       | 0                     | 0                              | 0                       | 2003000             | 0                | 0                         | 0                  | 2003000                | 100                       | 
| 1424193739  | 4          | DSHS   | EMR ICD10 Maintenance & Operations         | ML    | 2               | 0.652 | 0.313                       | 1.000                                                         | 1.000                                   | 1.000                      | 0.875                                  | 0.562                          | 1.000                                                | 0.500                       | 0.250                           | 0.875                             | 0.000                                              | 0.000                            | 0.000                                                 | 1.000                                  | 0.500                        | 2888000                | 2888000                | 5776000                  | 5776000                       | 0                     | 0                              | 0                       | 5776000             | 0                | 0                         | 0                  | 5776000                | 100                       | 
| 1424193739  | 5          | LCB    | Traceability System & Staff Funding        | PL    | 2               | 0.648 | 0.250                       | 1.000                                                         | 1.000                                   | 1.000                      | 1.000                                  | 1.000                          | 1.000                                                | 0.600                       | 0.350                           | 0.750                             | 0.000                                              | 0.000                            | 0.000                                                 | 0.900                                  | 0.500                        | 461750                 | 569000                 | 1030750                  | 0                             | 1030750               | 0                              | 0                       | 0                   | 460000           | 0                         | 0                  | 460000                 | 45                        | 
| 1424193739  | 6          | DSHS   | ACES Disaster Recovery                     | ML    | 1               | 0.644 | 0.458                       | 0.750                                                         | 0.500                                   | 1.000                      | 1.000                                  | 0.917                          | 0.500                                                | 0.042                       | 0.000                           | 0.500                             | 0.400                                              | 0.000                            | 0.000                                                 | 0.917                                  | 0.500                        | 934000                 | 342000                 | 1276000                  | 765000                        | 0                     | 0                              | 511000                  | 0                   | 0                | 0                         | 0                  | 0                      | 0                         | 
| 1424193739  | 7          | DOL    | Prorate and Fuel Tax System - Continuation | PL    | 3               | 0.639 | 0.500                       | 0.500                                                         | 0.550                                   | 0.750                      | 0.400                                  | 0.400                          | 1.000                                                | 0.800                       | 0.500                           | 0.700                             | 0.000                                              | 0.000                            | 0.999                                                 | 1.000                                  | 0.500                        | 5059000                | 0                      | 5059000                  | 0                             | 0                     | 5059000                        | 0                       | 0                   | 0                | 5059000                   | 0                  | 5059000                | 100                       | 
| 1424193739  | 8          | DSHS   | Securing Sensitive and Confid Data         | PL    | 3               | 0.628 | 1.000                       | 0.250                                                         | 0.500                                   | 0.450                      | 0.750                                  | 0.500                          | 0.450                                                | 0.000                       | 0.000                           | 0.250                             | 0.180                                              | 0.000                            | 0.000                                                 | 0.900                                  | 0.500                        | 3000000                | 3000000                | 6000000                  | 4920000                       | 0                     | 0                              | 1080000                 | 0                   | 0                | 0                         | 0                  | 0                      | 0                         | 
| 1424193739  | 9          | ARTS   | My Public Art Portal                       | PL    | 1               | 0.623 | 0.500                       | 0.750                                                         | 1.000                                   | 0.250                      | 0.500                                  | 1.000                          | 1.000                                                | 1.000                       | 0.625                           | 1.000                             | 0.000                                              | 0.000                            | 0.000                                                 | 1.000                                  | 0.500                        | 167677                 | 136918                 | 304595                   | 304595                        | 0                     | 0                              | 0                       | 0                   | 0                | 0                         | 0                  | 0                      | 0                         | 
| 1424193739  | 10         | HCA    | Fund ProviderOne Enhancements              | ML    | 2               | 0.622 | 0.250                       | 0.500                                                         | 0.500                                   | 1.000                      | 1.000                                  | 1.000                          | 0.000                                                | 0.000                       | 0.000                           | 0.750                             | 0.900                                              | 0.000                            | 0.000                                                 | 1.000                                  | 0.500                        | 2000000                | 350000                 | 2350000                  | 235000                        | 0                     | 0                              | 2115000                 | 135000              | 0                | 0                         | 1215000            | 1350000                | 57                        | 
```