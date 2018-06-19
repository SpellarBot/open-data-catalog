# Municipal Fiscal Indicators 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/municipal-fiscal-indicators-2015) |
| Metadata | [Link](https://data.ct.gov/api/views/8pz3-js3d) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/8pz3-js3d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/8pz3-js3d/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 8pz3-js3d |
| Name | Municipal Fiscal Indicators 2015 |
| Attribution | Office of Policy and Management |
| Category | Government |
| Tags | opm, municipal, fiscal, indicatos |
| Created | 2017-02-02T18:30:00Z |
| Publication Date | 2017-02-02T18:33:10Z |

## Description

Municipal Fiscal Indicators is an annual compendium of information compiled by the Office of Policy and Management, Intergovernmental Policy Division (IGP), Municipal Finance Services Unit (MFS). The data contained in Indicators provides key financial and demographic information on municipalities in Connecticut.

Municipal Fiscal Indicators contains the most current financial data available for each of Connecticut's 169 municipalities. The majority of this data was compiled from the audited financial statements that are filed annually with the State of Connecticut, Office of Policy and Management, IGP Division. This database of information includes selected demographic and economic data relating to, or having an impact upon, a municipality?s financial condition. The most recent edition is for the Fiscal Years Ended 2011-2015 published in January of 2017 (amending the January 2016 version).

## Columns

```ls
| Included | Schema Type    | Field Name                                           | Name                                                   | Data Type | Render Type |
| ======== | ============== | ==================================================== | ====================================================== | ========= | =========== |
| Yes      | series tag     | municipality                                         | Municipality                                           | text      | text        |
| Yes      | numeric metric | numbered                                             | numbered                                               | number    | number      |
| Yes      | series tag     | comptroller_town_code                                | Comptroller Town Code                                  | text      | number      |
| Yes      | series tag     | county_identifier                                    | County_Identifier                                      | text      | text        |
| Yes      | numeric metric | net_investment_in_capital_assets                     | Net Investment In Capital Assets                       | number    | number      |
| Yes      | numeric metric | unrestricted_net_position                            | Unrestricted Net Position                              | number    | number      |
| Yes      | numeric metric | total_net_position                                   | Total Net Position                                     | number    | number      |
| Yes      | numeric metric | change_in_net_position                               | Change In Net Position                                 | number    | number      |
| Yes      | numeric metric | nonspendable_fund_bal                                | Nonspendable_Fund_Bal                                  | number    | number      |
| Yes      | numeric metric | restricted_fund_bal                                  | Restricted_Fund_Bal                                    | number    | number      |
| Yes      | numeric metric | committed_fund_bal                                   | Committed_Fund_Bal                                     | number    | number      |
| Yes      | numeric metric | assigned_fund_bal                                    | Assigned_Fund_Bal                                      | number    | number      |
| Yes      | numeric metric | total_fund_bal                                       | Total_Fund_Bal                                         | number    | number      |
| Yes      | numeric metric | unassigned_fund_bal                                  | Unassigned_Fund_Bal                                    | number    | number      |
| Yes      | numeric metric | unrestricted_fund_bal                                | Unrestricted_Fund_Bal                                  | number    | number      |
| Yes      | series tag     | restatement_of_fund_balance_y_or_n                   | Restatement of Fund Balance (Y or N)                   | text      | text        |
| Yes      | numeric metric | inter_gov_rev                                        | Inter_Gov_Rev                                          | number    | number      |
| Yes      | numeric metric | tax_rev                                              | Tax_Rev                                                | number    | number      |
| Yes      | numeric metric | total_revenue                                        | Total_Revenue                                          | number    | number      |
| Yes      | numeric metric | education                                            | Education                                              | number    | number      |
| Yes      | numeric metric | debt_service                                         | Debt_Service                                           | number    | number      |
| Yes      | numeric metric | total_expenditures                                   | Total_Expenditures                                     | number    | number      |
| Yes      | numeric metric | total_trans_to_genl_fund                             | TOTAL_Trans_to_Genl_Fund                               | number    | number      |
| Yes      | numeric metric | other_financing_sources                              | Other_Financing_Sources                                | number    | number      |
| Yes      | numeric metric | total_trans_from_genl_fund                           | TOTAL_Trans_from_Genl_Fund                             | number    | number      |
| Yes      | numeric metric | other_financing_uses                                 | Other_Financing_Uses                                   | number    | number      |
| Yes      | numeric metric | operating_surplus_deficit_including_transfers        | Operating_Surplus_(Deficit)_Including_Transfers        | number    | number      |
| Yes      | numeric metric | prior_yr_op_surplus_def_including_sources_and_uses   | Prior_Yr_OP_Surplus_(Def)_including_sources_and_uses   | number    | number      |
| Yes      | numeric metric | operating_surplus_deficit_including_sources_and_uses | Operating_Surplus_(Deficit)_Including_Sources_And_Uses | number    | number      |
| Yes      | numeric metric | special_extraordinary_items                          | Special / Extraordinary Items                          | number    | number      |
| Yes      | series tag     | deficit_individual_enterprise_funds_y_or_n           | Deficit - Individual Enterprise Funds (Y or N)         | text      | text        |
| Yes      | series tag     | deficit_individual_internal_service_funds_y_or_n     | Deficit - Individual Internal Service Funds (Y or N)   | text      | text        |
| Yes      | numeric metric | rsd_debt                                             | RSD_DEBT                                               | number    | number      |
| Yes      | numeric metric | town_bonded_long_term_debt                           | TOWN_Bonded_Long_Term_Debt                             | number    | number      |
| Yes      | numeric metric | total_bonded_long_term_debt_rsd__town                | Total_Bonded_Long_Term_Debt_(RSD_+_Town)               | number    | number      |
| Yes      | numeric metric | total_net_pension_liability                          | Total_Net_Pension_Liability                            | number    | number      |
| Yes      | numeric metric | curr_year_adjusted_taxes_collectible                 | Curr_Year_Adjusted_Taxes_Collectible                   | number    | number      |
| Yes      | numeric metric | curr_year_taxes_collected                            | Curr_Year_Taxes_Collected                              | number    | number      |
| Yes      | numeric metric | curr_year_tax_collection_rate                        | Curr_Year_Tax_Collection_Rate                          | number    | number      |
| Yes      | numeric metric | total_adjusted_taxes_collectible                     | Total_Adjusted_Taxes_Collectible                       | number    | number      |
| Yes      | numeric metric | total_taxes_collected                                | Total_Taxes_Collected                                  | number    | number      |
| Yes      | numeric metric | overal_total_tax_collection_rate                     | Overal_Total_Tax_Collection_Rate                       | number    | number      |
| Yes      | numeric metric | 2015_population                                      | 2015 Population                                        | number    | number      |
| Yes      | series tag     | moody_s_bond_ratings_nov_2016                        | Moody's_Bond_Ratings_Nov_2016                          | text      | text        |
| Yes      | series tag     | moody_s_bond_ratings_july_2015                       | Moody's_Bond_Ratings_July_2015                         | text      | text        |
| Yes      | numeric metric | area_lmt                                             | area lmt                                               | number    | number      |
| Yes      | numeric metric | acglfy15                                             | ACGLFY15                                               | number    | number      |
| Yes      | numeric metric | egl                                                  | EGL                                                    | number    | number      |
| Yes      | numeric metric | tanf15_recipients                                    | TANF15 Recipients                                      | number    | number      |
| Yes      | numeric metric | empl                                                 | empl                                                   | number    | number      |
| Yes      | numeric metric | acmr                                                 | ACMR                                                   | number    | number      |
| Yes      | numeric metric | enrollmt                                             | enrollmt                                               | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8pz3-js3d d:2015-01-01T00:00:00.000Z t:moody_s_bond_ratings_nov_2016=Aa3 t:moody_s_bond_ratings_july_2015=Aa3 t:county_identifier=M t:restatement_of_fund_balance_y_or_n=N t:municipality=PORTLAND t:comptroller_town_code=113 t:deficit_individual_internal_service_funds_y_or_n=N t:deficit_individual_enterprise_funds_y_or_n=N m:total_trans_from_genl_fund=1106737 m:restricted_fund_bal=0 m:total_trans_to_genl_fund=0 m:enrollmt=1382.54 m:2015_population=9391 m:egl=1139281294.81 m:curr_year_adjusted_taxes_collectible=25626817 m:curr_year_tax_collection_rate=0.983344751710679 m:acglfy15=801938884 m:education=21094353 m:operating_surplus_deficit_including_sources_and_uses=351917 m:tanf15_recipients=29 m:total_bonded_long_term_debt_rsd__town=14932412 m:acmr=31.78 m:other_financing_uses=1106737 m:change_in_net_position=-198624 m:debt_service=2803149 m:tax_rev=25715084 m:assigned_fund_bal=474056 m:total_expenditures=31991474 m:prior_yr_op_surplus_def_including_sources_and_uses=-262153 m:unassigned_fund_bal=5108122 m:empl=0.0466997609854753 m:unrestricted_net_position=-2152488 m:town_bonded_long_term_debt=14932412 m:other_financing_sources=0 m:total_fund_bal=5749892 m:unrestricted_fund_bal=5749892 m:net_investment_in_capital_assets=61515503 m:numbered=114 m:total_net_position=59885833 m:inter_gov_rev=6788227 m:curr_year_taxes_collected=25199996 m:total_revenue=33450128 m:area_lmt=23.4 m:overal_total_tax_collection_rate=0.968373465451534 m:nonspendable_fund_bal=0 m:total_net_pension_liability=9498553 m:committed_fund_bal=167714 m:special_extraordinary_items=0 m:total_adjusted_taxes_collectible=26346105 m:operating_surplus_deficit_including_transfers=351917 m:total_taxes_collected=25512869

series e:8pz3-js3d d:2015-01-01T00:00:00.000Z t:county_identifier=NL t:restatement_of_fund_balance_y_or_n=N t:municipality=PRESTON t:comptroller_town_code=114 t:deficit_individual_internal_service_funds_y_or_n=N t:deficit_individual_enterprise_funds_y_or_n=N m:total_trans_from_genl_fund=315155 m:restricted_fund_bal=2112 m:total_trans_to_genl_fund=4 m:enrollmt=609.25 m:2015_population=4707 m:egl=550138880.83 m:curr_year_adjusted_taxes_collectible=9115447 m:curr_year_tax_collection_rate=0.980624208554995 m:acglfy15=392192485 m:education=11560965 m:operating_surplus_deficit_including_sources_and_uses=283965 m:tanf15_recipients=20 m:total_bonded_long_term_debt_rsd__town=5923000 m:acmr=23.14 m:other_financing_uses=315155 m:change_in_net_position=576234 m:debt_service=688833 m:tax_rev=9207560 m:assigned_fund_bal=757060 m:total_expenditures=15479315 m:prior_yr_op_surplus_def_including_sources_and_uses=256975 m:unassigned_fund_bal=2879784 m:empl=0.0550041356492969 m:unrestricted_net_position=4764799 m:town_bonded_long_term_debt=5923000 m:other_financing_sources=4 m:total_fund_bal=3658031 m:unrestricted_fund_bal=3636844 m:net_investment_in_capital_assets=8515554 m:numbered=115 m:total_net_position=13359330 m:inter_gov_rev=5644492 m:curr_year_taxes_collected=8938828 m:total_revenue=16078431 m:area_lmt=30.89 m:overal_total_tax_collection_rate=0.961059866320506 m:nonspendable_fund_bal=19075 m:total_net_pension_liability=363759 m:committed_fund_bal=0 m:special_extraordinary_items=0 m:total_adjusted_taxes_collectible=9479988 m:operating_surplus_deficit_including_transfers=283965 m:total_taxes_collected=9110836

series e:8pz3-js3d d:2015-01-01T00:00:00.000Z t:moody_s_bond_ratings_july_2015=A2 t:county_identifier=NH t:restatement_of_fund_balance_y_or_n=N t:municipality=PROSPECT t:comptroller_town_code=115 t:deficit_individual_internal_service_funds_y_or_n=N t:deficit_individual_enterprise_funds_y_or_n=N m:total_trans_from_genl_fund=35000 m:restricted_fund_bal=0 m:total_trans_to_genl_fund=405358 m:enrollmt=1409.39 m:2015_population=9739 m:egl=1175864777.67 m:curr_year_adjusted_taxes_collectible=23634467 m:curr_year_tax_collection_rate=0.989104598804788 m:acglfy15=812671708 m:rsd_debt=19283483 m:education=22117025 m:operating_surplus_deficit_including_sources_and_uses=328429 m:tanf15_recipients=17 m:total_bonded_long_term_debt_rsd__town=21401878 m:acmr=28.98 m:other_financing_uses=35000 m:change_in_net_position=309849 m:debt_service=596936 m:tax_rev=23746587 m:assigned_fund_bal=0 m:total_expenditures=31331634 m:prior_yr_op_surplus_def_including_sources_and_uses=44266 m:unassigned_fund_bal=1124085 m:empl=0.0480507706255666 m:unrestricted_net_position=1275274 m:town_bonded_long_term_debt=2118395 m:other_financing_sources=1634197 m:total_fund_bal=1130027 m:unrestricted_fund_bal=1130027 m:net_investment_in_capital_assets=15607173 m:numbered=116 m:total_net_position=18265521 m:inter_gov_rev=5723898 m:curr_year_taxes_collected=23376960 m:total_revenue=30060866 m:area_lmt=14.32 m:overal_total_tax_collection_rate=0.985321697030513 m:nonspendable_fund_bal=0 m:total_net_pension_liability=213734 m:committed_fund_bal=5942 m:special_extraordinary_items=0 m:total_adjusted_taxes_collectible=23981042 m:operating_surplus_deficit_including_transfers=-900410 m:total_taxes_collected=23629041
```

## Meta Commands

```ls
metric m:numbered p:integer l:numbered t:dataTypeName=number

metric m:net_investment_in_capital_assets p:double l:"Net Investment In Capital Assets" t:dataTypeName=number

metric m:unrestricted_net_position p:double l:"Unrestricted Net Position" t:dataTypeName=number

metric m:total_net_position p:double l:"Total Net Position" t:dataTypeName=number

metric m:change_in_net_position p:double l:"Change In Net Position" t:dataTypeName=number

metric m:nonspendable_fund_bal p:float l:Nonspendable_Fund_Bal t:dataTypeName=number

metric m:restricted_fund_bal p:float l:Restricted_Fund_Bal t:dataTypeName=number

metric m:committed_fund_bal p:float l:Committed_Fund_Bal t:dataTypeName=number

metric m:assigned_fund_bal p:float l:Assigned_Fund_Bal t:dataTypeName=number

metric m:total_fund_bal p:double l:Total_Fund_Bal t:dataTypeName=number

metric m:unassigned_fund_bal p:double l:Unassigned_Fund_Bal t:dataTypeName=number

metric m:unrestricted_fund_bal p:float l:Unrestricted_Fund_Bal t:dataTypeName=number

metric m:inter_gov_rev p:float l:Inter_Gov_Rev t:dataTypeName=number

metric m:tax_rev p:double l:Tax_Rev t:dataTypeName=number

metric m:total_revenue p:double l:Total_Revenue t:dataTypeName=number

metric m:education p:double l:Education t:dataTypeName=number

metric m:debt_service p:float l:Debt_Service t:dataTypeName=number

metric m:total_expenditures p:double l:Total_Expenditures t:dataTypeName=number

metric m:total_trans_to_genl_fund p:float l:TOTAL_Trans_to_Genl_Fund t:dataTypeName=number

metric m:other_financing_sources p:double l:Other_Financing_Sources t:dataTypeName=number

metric m:total_trans_from_genl_fund p:double l:TOTAL_Trans_from_Genl_Fund t:dataTypeName=number

metric m:other_financing_uses p:double l:Other_Financing_Uses t:dataTypeName=number

metric m:operating_surplus_deficit_including_transfers p:float l:Operating_Surplus_(Deficit)_Including_Transfers t:dataTypeName=number

metric m:prior_yr_op_surplus_def_including_sources_and_uses p:float l:Prior_Yr_OP_Surplus_(Def)_including_sources_and_uses t:dataTypeName=number

metric m:operating_surplus_deficit_including_sources_and_uses p:float l:Operating_Surplus_(Deficit)_Including_Sources_And_Uses t:dataTypeName=number

metric m:special_extraordinary_items p:float l:"Special / Extraordinary Items" t:dataTypeName=number

metric m:rsd_debt p:float l:RSD_DEBT t:dataTypeName=number

metric m:town_bonded_long_term_debt p:double l:TOWN_Bonded_Long_Term_Debt t:dataTypeName=number

metric m:total_bonded_long_term_debt_rsd__town p:double l:Total_Bonded_Long_Term_Debt_(RSD_+_Town) t:dataTypeName=number

metric m:total_net_pension_liability p:double l:Total_Net_Pension_Liability t:dataTypeName=number

metric m:curr_year_adjusted_taxes_collectible p:double l:Curr_Year_Adjusted_Taxes_Collectible t:dataTypeName=number

metric m:curr_year_taxes_collected p:double l:Curr_Year_Taxes_Collected t:dataTypeName=number

metric m:curr_year_tax_collection_rate p:double l:Curr_Year_Tax_Collection_Rate t:dataTypeName=number

metric m:total_adjusted_taxes_collectible p:double l:Total_Adjusted_Taxes_Collectible t:dataTypeName=number

metric m:total_taxes_collected p:double l:Total_Taxes_Collected t:dataTypeName=number

metric m:overal_total_tax_collection_rate p:double l:Overal_Total_Tax_Collection_Rate t:dataTypeName=number

metric m:2015_population p:integer l:"2015 Population" t:dataTypeName=number

metric m:area_lmt p:float l:"area lmt" t:dataTypeName=number

metric m:acglfy15 p:double l:ACGLFY15 t:dataTypeName=number

metric m:egl p:double l:EGL t:dataTypeName=number

metric m:tanf15_recipients p:integer l:"TANF15 Recipients" t:dataTypeName=number

metric m:empl p:double l:empl t:dataTypeName=number

metric m:acmr p:float l:ACMR t:dataTypeName=number

metric m:enrollmt p:float l:enrollmt t:dataTypeName=number

entity e:8pz3-js3d l:"Municipal Fiscal Indicators 2015" t:attribution="Office of Policy and Management" t:url=https://data.ct.gov/api/views/8pz3-js3d

property e:8pz3-js3d t:meta.view v:id=8pz3-js3d v:category=Government v:attributionLink="http://www.ct.gov/opm/cwp/view.asp?a=2984&q=383170" v:averageRating=0 v:name="Municipal Fiscal Indicators 2015" v:attribution="Office of Policy and Management"

property e:8pz3-js3d t:meta.view.license v:name="Public Domain"

property e:8pz3-js3d t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:8pz3-js3d t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| municipality | numbered | comptroller_town_code | county_identifier | net_investment_in_capital_assets | unrestricted_net_position | total_net_position | change_in_net_position | nonspendable_fund_bal | restricted_fund_bal | committed_fund_bal | assigned_fund_bal | total_fund_bal | unassigned_fund_bal | unrestricted_fund_bal | restatement_of_fund_balance_y_or_n | inter_gov_rev | tax_rev      | total_revenue | education   | debt_service | total_expenditures | total_trans_to_genl_fund | other_financing_sources | total_trans_from_genl_fund | other_financing_uses | operating_surplus_deficit_including_transfers | prior_yr_op_surplus_def_including_sources_and_uses | operating_surplus_deficit_including_sources_and_uses | special_extraordinary_items | deficit_individual_enterprise_funds_y_or_n | deficit_individual_internal_service_funds_y_or_n | rsd_debt    | town_bonded_long_term_debt | total_bonded_long_term_debt_rsd__town | total_net_pension_liability | curr_year_adjusted_taxes_collectible | curr_year_taxes_collected | curr_year_tax_collection_rate | total_adjusted_taxes_collectible | total_taxes_collected | overal_total_tax_collection_rate | 2015_population | moody_s_bond_ratings_nov_2016 | moody_s_bond_ratings_july_2015 | area_lmt | acglfy15      | egl           | tanf15_recipients | empl               | acmr  | enrollmt | 
| ============ | ======== | ===================== | ================= | ================================ | ========================= | ================== | ====================== | ===================== | =================== | ================== | ================= | ============== | =================== | ===================== | ================================== | ============= | ============ | ============= | =========== | ============ | ================== | ======================== | ======================= | ========================== | ==================== | ============================================= | ================================================== | ==================================================== | =========================== | ========================================== | ================================================ | =========== | ========================== | ===================================== | =========================== | ==================================== | ========================= | ============================= | ================================ | ===================== | ================================ | =============== | ============================= | ============================== | ======== | ============= | ============= | ================= | ================== | ===== | ======== | 
| PORTLAND     | 114      | 113                   | M                 | 61515503.00                      | -2152488.00               | 59885833.00        | -198624.00             | 0.00                  | 0.00                | 167714.00          | 474056.00         | 5749892.00     | 5108122.00          | 5749892.00            | N                                  | 6788227.00    | 25715084.00  | 33450128.00   | 21094353.00 | 2803149.00   | 31991474.00        | 0.00                     | 0.00                    | 1106737.00                 | 1106737.00           | 351917.00                                     | -262153.00                                         | 351917.00                                            | 0.00                        | N                                          | N                                                |             | 14932412.00                | 14932412.00                           | 9498553.00                  | 25626817.00                          | 25199996.00               | 0.983344751710679             | 26346105.00                      | 25512869.00           | 0.968373465451534                | 9391            | Aa3                           | Aa3                            | 23.4     | 801938884.00  | 1139281294.81 | 29                | 0.0466997609854753 | 31.78 | 1382.54  | 
| PRESTON      | 115      | 114                   | NL                | 8515554.00                       | 4764799.00                | 13359330.00        | 576234.00              | 19075.00              | 2112.00             | 0.00               | 757060.00         | 3658031.00     | 2879784.00          | 3636844.00            | N                                  | 5644492.00    | 9207560.00   | 16078431.00   | 11560965.00 | 688833.00    | 15479315.00        | 4.00                     | 4.00                    | 315155.00                  | 315155.00            | 283965.00                                     | 256975.00                                          | 283965.00                                            | 0.00                        | N                                          | N                                                |             | 5923000.00                 | 5923000.00                            | 363759.00                   | 9115447.00                           | 8938828.00                | 0.980624208554995             | 9479988.00                       | 9110836.00            | 0.961059866320506                | 4707            |                               |                                | 30.89    | 392192485.00  | 550138880.83  | 20                | 0.0550041356492969 | 23.14 | 609.25   | 
| PROSPECT     | 116      | 115                   | NH                | 15607173.00                      | 1275274.00                | 18265521.00        | 309849.00              | 0.00                  | 0.00                | 5942.00            | 0.00              | 1130027.00     | 1124085.00          | 1130027.00            | N                                  | 5723898.00    | 23746587.00  | 30060866.00   | 22117025.00 | 596936.00    | 31331634.00        | 405358.00                | 1634197.00              | 35000.00                   | 35000.00             | -900410.00                                    | 44266.00                                           | 328429.00                                            | 0.00                        | N                                          | N                                                | 19283483.00 | 2118395.00                 | 21401878.00                           | 213734.00                   | 23634467.00                          | 23376960.00               | 0.989104598804788             | 23981042.00                      | 23629041.00           | 0.985321697030513                | 9739            |                               | A2                             | 14.32    | 812671708.00  | 1175864777.67 | 17                | 0.0480507706255666 | 28.98 | 1409.39  | 
| PUTNAM       | 117      | 116                   | W                 | 32035281.00                      | 11255059.00               | 44236622.00        | 8602046.00             | 971014.00             | 0.00                | 72710.00           | 0.00              | 5433447.00     | 4389723.00          | 4462433.00            | Y                                  | 11351549.00   | 9768262.00   | 24762837.00   | 18932080.00 | 0.00         | 23676638.00        | 13825.00                 | 13825.00                | 315281.00                  | 315281.00            | 784743.00                                     | 466209.00                                          | 784743.00                                            | 0.00                        | N                                          | N                                                |             | 0.00                       | 0.00                                  | 0.00                        | 9777586.00                           | 9497050.00                | 0.971308255432374             | 10436170.00                      | 9680668.00            | 0.927607350206062                | 9372            |                               |                                | 20.29    | 640264705.00  | 833480942.66  | 128               | 0.0673832162050434 | 15.07 | 1196.73  | 
| REDDING      | 118      | 117                   | F                 | 30966996.00                      | 16784958.00               | 47751954.00        | 4139242.00             | 1526022.00            | 0.00                | 208822.00          | 159412.00         | 8488722.00     | 6594466.00          | 6962700.00            | N                                  | 4064199.00    | 45698262.00  | 51182117.00   | 36249453.00 | 2190217.00   | 49765977.00        | 0.00                     | 0.00                    | 87500.00                   | 87500.00             | 1328640.00                                    | 675662.00                                          | 1328640.00                                           | 0.00                        | N                                          | N                                                | 7555065.00  | 14827366.00                | 22382431.00                           | 3405997.00                  | 45720390.00                          | 45147782.00               | 0.987475872362419             | 48018377.00                      | 45650887.00           | 0.95069616784424                 | 9293            | Aa1                           |                                | 31.5     | 1628096295.00 | 2374930560.52 | 3                 | 0.0419455600178492 | 28.91 | 1534.99  | 
| RIDGEFIELD   | 119      | 118                   | F                 | 102182274.00                     | 29132923.00               | 131357058.00       | 9647543.00             | 0.00                  | 0.00                | 0.00               | 3228924.00        | 16499503.00    | 13270579.00         | 16499503.00           | N                                  | 12774311.00   | 121797734.00 | 143866822.00  | 94568454.00 | 13210471.00  | 142523343.00       | 179589.00                | 179589.00               | 1079854.00                 | 1079854.00           | 443214.00                                     | 1405205.00                                         | 443214.00                                            | 0.00                        | N                                          | N                                                |             | 78983264.00                | 78983264.00                           | 816794.00                   | 121507726.00                         | 120015866.00              | 0.987722097605547             | 125491588.00                     | 121093654.00          | 0.964954352159445                | 25244           | Aaa                           | Aaa                            | 34.43    | 4700389133.00 | 7297420053.74 | 0                 | 0.0387485161946753 | 26.01 | 5139.56  | 
| ROCKY HILL   | 120      | 119                   | H                 | 20007218.00                      | 12775623.00               | 32833268.00        | 3056397.00             | 0.00                  | 0.00                | 0.00               | 1084837.00        | 6288871.00     | 5204034.00          | 6288871.00            | N                                  | 9434186.00    | 59840044.00  | 72019191.00   | 38973084.00 | 1962439.00   | 70463669.00        | 0.00                     | 0.00                    | 1405502.00                 | 1405502.00           | 150020.00                                     | 268168.00                                          | 150020.00                                            | 0.00                        | N                                          | N                                                |             | 28538944.00                | 28538944.00                           | 4946026.00                  | 59329833.00                          | 58987538.00               | 0.994230642786404             | 60184930.00                      | 59553947.00           | 0.989515930316775                | 20021           | Aa2                           | Aa2                            | 13.45    | 1988502360.00 | 2841314800.01 | 40                | 0.0415495432185524 | 29.7  | 2646.28  | 
| ROXBURY      | 121      | 120                   | L                 | 10791403.00                      | 3133901.00                | 16243734.00        | 29754.00               | 0.00                  | 0.00                | 168905.00          | 238764.00         | 2216449.00     | 1808780.00          | 2216449.00            | N                                  | 206168.00     | 9337031.00   | 9954919.00    | 6978595.00  | 0.00         | 9573112.00         | 0.00                     | 0.00                    | 269670.00                  | 269670.00            | 112137.00                                     | 272845.00                                          | 112137.00                                            | 0.00                        | N                                          | N                                                | 622744.00   | 0.00                       | 622744.00                             | 0.00                        | 9295118.00                           | 9249206.00                | 0.995060632904284             | 9387548.00                       | 9320470.00            | 0.992854577148367                | 2187            |                               |                                | 26.22    | 694544900.00  | 970743202.89  | 0                 | 0.032551097653293  | 13.4  | 230.06   | 
| SALEM        | 122      | 121                   | NL                | 15735907.00                      | 3139580.00                | 19619946.00        | 654337.00              | 0.00                  | 31306.00            | 0.00               | 536100.00         | 2631672.00     | 2064266.00          | 2600366.00            | N                                  | 4577707.00    | 11340498.00  | 16185118.00   | 11559640.00 | 5925240.00   | 14996162.00        | 0.00                     | 208118.00               | 802556.00                  | 802556.00            | 386400.00                                     | 750813.00                                          | 594518.00                                            | 0.00                        | N                                          | N                                                |             | 4740679.00                 | 4740679.00                            | 0.00                        | 11289461.00                          | 11114399.00               | 0.984493325234925             | 11601336.00                      | 11278136.00           | 0.97214113960668                 | 4183            | A1                            | A1                             | 28.95    | 362175579.00  | 506358606.89  | 16                | 0.0535037878787879 | 31.1  | 649.07   | 
| SALISBURY    | 123      | 122                   | L                 | 14199480.00                      | 6710454.00                | 24088962.00        | 1149943.00             | 0.00                  | 45831.00            | 447673.00          | 586414.00         | 2393022.00     | 1313104.00          | 2347191.00            | N                                  | 1133784.00    | 12354606.00  | 14424717.00   | 8230306.00  | 191981.00    | 12767388.00        | 276154.00                | 276154.00               | 1523732.00                 | 1523732.00           | 409751.00                                     | 115931.00                                          | 409751.00                                            | 0.00                        | N                                          | N                                                | 846159.00   | 2972299.00                 | 3818458.00                            | 193456.00                   | 12298145.00                          | 12216496.00               | 0.993360868651329             | 12424957.00                      | 12275801.00           | 0.98799545141283                 | 3638            |                               |                                | 57.32    | 1168534540.00 | 1608901918.32 | 5                 | 0.0343680709534368 | 10.5  | 341.66   | 
```