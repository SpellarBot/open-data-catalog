# Municipal Fiscal Indicators - 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/municipal-fiscal-indicators-2013) |
| Metadata | [Link](https://data.ct.gov/api/views/72by-n3wh) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/72by-n3wh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/72by-n3wh/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 72by-n3wh |
| Name | Municipal Fiscal Indicators - 2013 |
| Attribution | Office of Policy and Management |
| Category | Government |
| Tags | municipal, fiscal indicators, opm |
| Created | 2016-01-19T17:14:24Z |
| Publication Date | 2016-01-19T17:46:08Z |

## Description

Municipal Fiscal Indicators is an annual compendium of information compiled by the Office of Policy and Management, Intergovernmental Policy Division (IGP), Municipal Finance Services Unit (MFS). The data contained in Indicators provides key financial and demographic information on municipalities in Connecticut. Municipal Fiscal Indicators contains the most current financial data available for each of Connecticut's 169 municipalities. The majority of this data was compiled from the audited financial statements that are filed annually with the State of Connecticut, Office of Policy and Management, IGP Division. This database of information includes selected demographic and economic data relating to, or having an impact upon, a municipality?s financial condition.

## Columns

```ls
| Included | Schema Type    | Field Name                                           | Name                                                   | Data Type | Render Type |
| ======== | ============== | ==================================================== | ====================================================== | ========= | =========== |
| Yes      | series tag     | municipality                                         | Municipality                                           | text      | text        |
| Yes      | series tag     | initials                                             | Initials                                               | text      | text        |
| Yes      | numeric metric | fisc_year_end                                        | Fisc_Year_End                                          | number    | number      |
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
| Yes      | numeric metric | curr_year_adjusted_taxes_collectible                 | Curr_Year_Adjusted_Taxes_Collectible                   | number    | number      |
| Yes      | numeric metric | curr_year_taxes_collected                            | Curr_Year_Taxes_Collected                              | number    | number      |
| Yes      | numeric metric | curr_year_tax_collection_rate                        | Curr_Year_Tax_Collection_Rate                          | number    | number      |
| Yes      | numeric metric | total_adjusted_taxes_collectible                     | Total_Adjusted_Taxes_Collectible                       | number    | number      |
| Yes      | numeric metric | total_taxes_collected                                | Total_Taxes_Collected                                  | number    | number      |
| Yes      | numeric metric | overal_total_tax_collection_rate                     | Overal_Total_Tax_Collection_Rate                       | number    | number      |
| Yes      | numeric metric | 2013_population                                      | 2013 Population                                        | number    | number      |
| Yes      | series tag     | moody_s_bond_ratings_july_2013                       | Moody's_Bond_Ratings_July_2013                         | text      | text        |
| Yes      | numeric metric | area_lmt                                             | area lmt                                               | number    | number      |
| Yes      | numeric metric | acglfy13                                             | ACGLFY13                                               | number    | number      |
| Yes      | numeric metric | egl                                                  | EGL                                                    | number    | number      |
| Yes      | numeric metric | tanf13_recipients                                    | TANF13 Recipients                                      | number    | number      |
| Yes      | numeric metric | empl                                                 | empl                                                   | number    | number      |
| Yes      | numeric metric | acmr                                                 | ACMR                                                   | number    | number      |
| Yes      | numeric metric | enrollmt                                             | enrollmt                                               | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:72by-n3wh d:2013-01-01T00:00:00.000Z t:county_identifier=T t:restatement_of_fund_balance_y_or_n=N t:initials=BP t:municipality=ANDOVER t:comptroller_town_code=1 t:deficit_individual_internal_service_funds_y_or_n=N t:deficit_individual_enterprise_funds_y_or_n=N m:total_trans_from_genl_fund=0 m:restricted_fund_bal=0 m:total_trans_to_genl_fund=0 m:enrollmt=588.63 m:egl=369373775.71 m:curr_year_adjusted_taxes_collectible=7980881 m:curr_year_tax_collection_rate=0.987963358932429 m:acglfy13=258506273 m:rsd_debt=3492091.79 m:education=8562868 m:operating_surplus_deficit_including_sources_and_uses=395766 m:total_bonded_long_term_debt_rsd__town=4302091.79 m:acmr=30.8 m:other_financing_uses=0 m:change_in_net_position=328011 m:debt_service=129060 m:tax_rev=7845981 m:assigned_fund_bal=147430 m:total_expenditures=10532064 m:prior_yr_op_surplus_def_including_sources_and_uses=273293 m:unassigned_fund_bal=2266912 m:empl=0.0643799472295515 m:unrestricted_net_position=3003579 m:town_bonded_long_term_debt=810000 m:other_financing_sources=0 m:total_fund_bal=2425685 m:tanf13_recipients=10 m:unrestricted_fund_bal=2414342 m:net_investment_in_capital_assets=5857107 m:numbered=1 m:total_net_position=8975803 m:inter_gov_rev=2930349 m:curr_year_taxes_collected=7884818 m:total_revenue=10927830 m:area_lmt=15.45 m:overal_total_tax_collection_rate=0.982969386830959 m:nonspendable_fund_bal=11343 m:2013_population=3273 m:committed_fund_bal=0 m:special_extraordinary_items=0 m:total_adjusted_taxes_collectible=8093543 m:operating_surplus_deficit_including_transfers=395766 m:fisc_year_end=2013 m:total_taxes_collected=7955705

series e:72by-n3wh d:2013-01-01T00:00:00.000Z t:county_identifier=NH t:restatement_of_fund_balance_y_or_n=N t:initials=BP t:moody_s_bond_ratings_july_2013=Aa3 t:municipality=ANSONIA t:comptroller_town_code=2 t:deficit_individual_internal_service_funds_y_or_n=N t:deficit_individual_enterprise_funds_y_or_n=N m:total_trans_from_genl_fund=50000 m:restricted_fund_bal=0 m:total_trans_to_genl_fund=0 m:enrollmt=2628.64 m:egl=1356816401.08 m:curr_year_adjusted_taxes_collectible=32474853 m:curr_year_tax_collection_rate=0.962731039921874 m:acglfy13=1174493645 m:education=34124712 m:operating_surplus_deficit_including_sources_and_uses=-26420 m:total_bonded_long_term_debt_rsd__town=15075232 m:acmr=27.65 m:other_financing_uses=50000 m:change_in_net_position=1865659 m:debt_service=9109490 m:tax_rev=32175591 m:assigned_fund_bal=0 m:total_expenditures=65544136 m:prior_yr_op_surplus_def_including_sources_and_uses=127743 m:unassigned_fund_bal=7431490 m:empl=0.108039936941671 m:unrestricted_net_position=6938007 m:town_bonded_long_term_debt=15075232 m:other_financing_sources=0 m:total_fund_bal=8732966 m:tanf13_recipients=285 m:unrestricted_fund_bal=8732966 m:net_investment_in_capital_assets=40700593 m:numbered=2 m:total_net_position=47757117 m:inter_gov_rev=29957368 m:curr_year_taxes_collected=31264549 m:total_revenue=65567716 m:area_lmt=6.03 m:overal_total_tax_collection_rate=0.912908366373193 m:nonspendable_fund_bal=0 m:2013_population=19020 m:committed_fund_bal=1301476 m:special_extraordinary_items=0 m:total_adjusted_taxes_collectible=35210753 m:operating_surplus_deficit_including_transfers=-26420 m:fisc_year_end=2013 m:total_taxes_collected=32144191

series e:72by-n3wh d:2013-01-01T00:00:00.000Z t:county_identifier=W t:restatement_of_fund_balance_y_or_n=N t:initials=BP t:moody_s_bond_ratings_july_2013=Aa3 t:municipality=ASHFORD t:comptroller_town_code=3 t:deficit_individual_internal_service_funds_y_or_n=N t:deficit_individual_enterprise_funds_y_or_n=N m:total_trans_from_genl_fund=241578 m:restricted_fund_bal=0 m:total_trans_to_genl_fund=0 m:enrollmt=642.8 m:egl=421452028.57 m:curr_year_adjusted_taxes_collectible=9201569 m:curr_year_tax_collection_rate=0.978957827735683 m:acglfy13=294930180 m:rsd_debt=2135406.77 m:education=11250309 m:operating_surplus_deficit_including_sources_and_uses=437243 m:total_bonded_long_term_debt_rsd__town=4775406.77 m:acmr=31.05 m:other_financing_uses=2325387 m:change_in_net_position=510190 m:debt_service=952942 m:tax_rev=9247248 m:assigned_fund_bal=205062 m:total_expenditures=14635662 m:prior_yr_op_surplus_def_including_sources_and_uses=396031 m:unassigned_fund_bal=2022519 m:empl=0.0686626746506986 m:unrestricted_net_position=3359604 m:town_bonded_long_term_debt=2640000 m:other_financing_sources=2790103 m:total_fund_bal=2259764 m:tanf13_recipients=26 m:unrestricted_fund_bal=2254055 m:net_investment_in_capital_assets=12606779 m:numbered=3 m:total_net_position=17410012 m:inter_gov_rev=4953913 m:curr_year_taxes_collected=9007948 m:total_revenue=14608189 m:area_lmt=38.8 m:overal_total_tax_collection_rate=0.934940443489029 m:nonspendable_fund_bal=5709 m:2013_population=4281 m:committed_fund_bal=26474 m:special_extraordinary_items=0 m:total_adjusted_taxes_collectible=9780039 m:operating_surplus_deficit_including_transfers=-269051 m:fisc_year_end=2013 m:total_taxes_collected=9143754
```

## Meta Commands

```ls
metric m:fisc_year_end p:integer l:Fisc_Year_End t:dataTypeName=number

metric m:numbered p:integer l:numbered t:dataTypeName=number

metric m:net_investment_in_capital_assets p:double l:"Net Investment In Capital Assets" t:dataTypeName=number

metric m:unrestricted_net_position p:float l:"Unrestricted Net Position" t:dataTypeName=number

metric m:total_net_position p:double l:"Total Net Position" t:dataTypeName=number

metric m:change_in_net_position p:double l:"Change In Net Position" t:dataTypeName=number

metric m:nonspendable_fund_bal p:float l:Nonspendable_Fund_Bal t:dataTypeName=number

metric m:restricted_fund_bal p:float l:Restricted_Fund_Bal t:dataTypeName=number

metric m:committed_fund_bal p:float l:Committed_Fund_Bal t:dataTypeName=number

metric m:assigned_fund_bal p:float l:Assigned_Fund_Bal t:dataTypeName=number

metric m:total_fund_bal p:double l:Total_Fund_Bal t:dataTypeName=number

metric m:unassigned_fund_bal p:float l:Unassigned_Fund_Bal t:dataTypeName=number

metric m:unrestricted_fund_bal p:double l:Unrestricted_Fund_Bal t:dataTypeName=number

metric m:inter_gov_rev p:double l:Inter_Gov_Rev t:dataTypeName=number

metric m:tax_rev p:double l:Tax_Rev t:dataTypeName=number

metric m:total_revenue p:double l:Total_Revenue t:dataTypeName=number

metric m:education p:float l:Education t:dataTypeName=number

metric m:debt_service p:double l:Debt_Service t:dataTypeName=number

metric m:total_expenditures p:double l:Total_Expenditures t:dataTypeName=number

metric m:total_trans_to_genl_fund p:float l:TOTAL_Trans_to_Genl_Fund t:dataTypeName=number

metric m:other_financing_sources p:float l:Other_Financing_Sources t:dataTypeName=number

metric m:total_trans_from_genl_fund p:double l:TOTAL_Trans_from_Genl_Fund t:dataTypeName=number

metric m:other_financing_uses p:double l:Other_Financing_Uses t:dataTypeName=number

metric m:operating_surplus_deficit_including_transfers p:float l:Operating_Surplus_(Deficit)_Including_Transfers t:dataTypeName=number

metric m:prior_yr_op_surplus_def_including_sources_and_uses p:float l:Prior_Yr_OP_Surplus_(Def)_including_sources_and_uses t:dataTypeName=number

metric m:operating_surplus_deficit_including_sources_and_uses p:float l:Operating_Surplus_(Deficit)_Including_Sources_And_Uses t:dataTypeName=number

metric m:special_extraordinary_items p:float l:"Special / Extraordinary Items" t:dataTypeName=number

metric m:rsd_debt p:double l:RSD_DEBT t:dataTypeName=number

metric m:town_bonded_long_term_debt p:double l:TOWN_Bonded_Long_Term_Debt t:dataTypeName=number

metric m:total_bonded_long_term_debt_rsd__town p:double l:Total_Bonded_Long_Term_Debt_(RSD_+_Town) t:dataTypeName=number

metric m:curr_year_adjusted_taxes_collectible p:double l:Curr_Year_Adjusted_Taxes_Collectible t:dataTypeName=number

metric m:curr_year_taxes_collected p:double l:Curr_Year_Taxes_Collected t:dataTypeName=number

metric m:curr_year_tax_collection_rate p:double l:Curr_Year_Tax_Collection_Rate t:dataTypeName=number

metric m:total_adjusted_taxes_collectible p:double l:Total_Adjusted_Taxes_Collectible t:dataTypeName=number

metric m:total_taxes_collected p:double l:Total_Taxes_Collected t:dataTypeName=number

metric m:overal_total_tax_collection_rate p:double l:Overal_Total_Tax_Collection_Rate t:dataTypeName=number

metric m:2013_population p:integer l:"2013 Population" t:dataTypeName=number

metric m:area_lmt p:float l:"area lmt" t:dataTypeName=number

metric m:acglfy13 p:double l:ACGLFY13 t:dataTypeName=number

metric m:egl p:double l:EGL t:dataTypeName=number

metric m:tanf13_recipients p:integer l:"TANF13 Recipients" t:dataTypeName=number

metric m:empl p:double l:empl t:dataTypeName=number

metric m:acmr p:float l:ACMR t:dataTypeName=number

metric m:enrollmt p:double l:enrollmt t:dataTypeName=number

entity e:72by-n3wh l:"Municipal Fiscal Indicators - 2013" t:attribution="Office of Policy and Management" t:url=https://data.ct.gov/api/views/72by-n3wh

property e:72by-n3wh t:meta.view v:id=72by-n3wh v:category=Government v:attributionLink="http://www.ct.gov/opm/cwp/view.asp?a=2984&q=383170" v:averageRating=0 v:name="Municipal Fiscal Indicators - 2013" v:attribution="Office of Policy and Management"

property e:72by-n3wh t:meta.view.license v:name="Public Domain"

property e:72by-n3wh t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:72by-n3wh t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| municipality | initials | fisc_year_end | numbered | comptroller_town_code | county_identifier | net_investment_in_capital_assets | unrestricted_net_position | total_net_position | change_in_net_position | nonspendable_fund_bal | restricted_fund_bal | committed_fund_bal | assigned_fund_bal | total_fund_bal | unassigned_fund_bal | unrestricted_fund_bal | restatement_of_fund_balance_y_or_n | inter_gov_rev | tax_rev     | total_revenue | education   | debt_service | total_expenditures | total_trans_to_genl_fund | other_financing_sources | total_trans_from_genl_fund | other_financing_uses | operating_surplus_deficit_including_transfers | prior_yr_op_surplus_def_including_sources_and_uses | operating_surplus_deficit_including_sources_and_uses | special_extraordinary_items | deficit_individual_enterprise_funds_y_or_n | deficit_individual_internal_service_funds_y_or_n | rsd_debt   | town_bonded_long_term_debt | total_bonded_long_term_debt_rsd__town | curr_year_adjusted_taxes_collectible | curr_year_taxes_collected | curr_year_tax_collection_rate | total_adjusted_taxes_collectible | total_taxes_collected | overal_total_tax_collection_rate | 2013_population | moody_s_bond_ratings_july_2013 | area_lmt | acglfy13      | egl           | tanf13_recipients | empl               | acmr  | enrollmt | 
| ============ | ======== | ============= | ======== | ===================== | ================= | ================================ | ========================= | ================== | ====================== | ===================== | =================== | ================== | ================= | ============== | =================== | ===================== | ================================== | ============= | =========== | ============= | =========== | ============ | ================== | ======================== | ======================= | ========================== | ==================== | ============================================= | ================================================== | ==================================================== | =========================== | ========================================== | ================================================ | ========== | ========================== | ===================================== | ==================================== | ========================= | ============================= | ================================ | ===================== | ================================ | =============== | ============================== | ======== | ============= | ============= | ================= | ================== | ===== | ======== | 
| ANDOVER      | BP       | 2013          | 1        | 1                     | T                 | 5857107.00                       | 3003579.00                | 8975803.00         | 328011.00              | 11343.00              | 0.00                | 0.00               | 147430.00         | 2425685.00     | 2266912.00          | 2414342.00            | N                                  | 2930349.00    | 7845981.00  | 10927830.00   | 8562868.00  | 129060.00    | 10532064.00        | 0.00                     | 0.00                    | 0.00                       | 0.00                 | 395766.00                                     | 273293.00                                          | 395766.00                                            | 0.00                        | N                                          | N                                                | 3492091.79 | 810000.00                  | 4302091.79                            | 7980881.00                           | 7884818.00                | 0.987963358932429             | 8093543.00                       | 7955705.00            | 0.982969386830959                | 3273            |                                | 15.45    | 258506273.00  | 369373775.71  | 10                | 0.0643799472295515 | 30.8  | 588.63   | 
| ANSONIA      | BP       | 2013          | 2        | 2                     | NH                | 40700593.00                      | 6938007.00                | 47757117.00        | 1865659.00             | 0.00                  | 0.00                | 1301476.00         | 0.00              | 8732966.00     | 7431490.00          | 8732966.00            | N                                  | 29957368.00   | 32175591.00 | 65567716.00   | 34124712.00 | 9109490.00   | 65544136.00        | 0.00                     | 0.00                    | 50000.00                   | 50000.00             | -26420.00                                     | 127743.00                                          | -26420.00                                            | 0.00                        | N                                          | N                                                |            | 15075232.00                | 15075232.00                           | 32474853.00                          | 31264549.00               | 0.962731039921874             | 35210753.00                      | 32144191.00           | 0.912908366373193                | 19020           | Aa3                            | 6.03     | 1174493645.00 | 1356816401.08 | 285               | 0.108039936941671  | 27.65 | 2628.64  | 
| ASHFORD      | BP       | 2013          | 3        | 3                     | W                 | 12606779.00                      | 3359604.00                | 17410012.00        | 510190.00              | 5709.00               | 0.00                | 26474.00           | 205062.00         | 2259764.00     | 2022519.00          | 2254055.00            | N                                  | 4953913.00    | 9247248.00  | 14608189.00   | 11250309.00 | 952942.00    | 14635662.00        | 0.00                     | 2790103.00              | 241578.00                  | 2325387.00           | -269051.00                                    | 396031.00                                          | 437243.00                                            | 0.00                        | N                                          | N                                                | 2135406.77 | 2640000.00                 | 4775406.77                            | 9201569.00                           | 9007948.00                | 0.978957827735683             | 9780039.00                       | 9143754.00            | 0.934940443489029                | 4281            | Aa3                            | 38.8     | 294930180.00  | 421452028.57  | 26                | 0.0686626746506986 | 31.05 | 642.8    | 
| AVON         | JG       | 2013          | 4        | 4                     | H                 | 118098045.00                     | 13660559.00               | 131758604.00       | 4050121.00             | 7406.00               | 0.00                | 0.00               | 2664114.00        | 10707173.00    | 8035653.00          | 10699767.00           | N                                  | 8450231.00    | 68836758.00 | 80754044.00   | 53396764.00 | 4437321.00   | 77657612.00        | 0.00                     | 0.00                    | 1508499.00                 | 1508499.00           | 1587933.00                                    | 1113986.00                                         | 1587933.00                                           | 0.00                        | N                                          | N                                                |            | 33305000.00                | 33305000.00                           | 68686698.00                          | 68527991.00               | 0.997689407052294             | 68881493.00                      | 68689037.00           | 0.997205983906301                | 18386           | Aaa                            | 23.12    | 2668106790.00 | 3573844476.67 | 13                | 0.0499779346866726 | 25.65 | 3472.15  | 
| BARKHAMSTED  | JG       | 2013          | 5        | 5                     | L                 | 4088119.00                       | 3171657.00                | 7259776.00         | 42697.00               | 0.00                  | 0.00                | 0.00               | 133313.00         | 1683778.00     | 1550465.00          | 1683778.00            | N                                  | 2215545.00    | 8770258.00  | 11122940.00   | 8852107.00  | 127150.00    | 10874884.00        | 0.00                     | 0.00                    | 20471.00                   | 20471.00             | 227585.00                                     | 9463.00                                            | 227585.00                                            | 0.00                        | N                                          | N                                                | 1326606.81 | 1850000.00                 | 3176606.81                            | 8797618.00                           | 8566023.00                | 0.973675260735349             | 9343436.00                       | 8705339.00            | 0.931706387243408                | 3745            |                                | 36.22    | 374141996.00  | 505822209.88  | 4                 | 0.0643326039387309 | 23.39 | 648.78   | 
| BEACON FALLS | BP       | 2013          | 6        | 6                     | NH                | 14087898.00                      | 663943.00                 | 14757615.00        | 1281586.00             | 24157.00              | 0.00                | 0.00               | 0.00              | 2149386.00     | 2125229.00          | 2125229.00            | Y                                  | 4478464.00    | 14623812.00 | 19728537.00   | 13516055.00 | 397413.00    | 19243334.00        | 0.00                     | 929153.00               | 161689.00                  | 161689.00            | 323514.00                                     | 50108.00                                           | 1252667.00                                           | 0.00                        | N                                          | N                                                | 8956290.08 | 2399296.00                 | 11355586.08                           | 14555631.00                          | 14116778.00               | 0.969849950167052             | 15740410.00                      | 14436989.00           | 0.917192690660536                | 6052            |                                | 9.77     | 471512634.00  | 675570668.57  | 25                | 0.0646217986896963 | 31.1  | 954.22   | 
| BERLIN       | BP       | 2013          | 7        | 7                     | H                 | 58673095.00                      | 20350601.00               | 79170744.00        | 2603636.00             | 0.00                  | 0.00                | 289973.00          | 1800000.00        | 12791267.00    | 10701294.00         | 12791267.00           | N                                  | 12927657.00   | 59750689.00 | 77058458.00   | 46108451.00 | 2941589.00   | 74962416.00        | 103959.00                | 434359.00               | 1037137.00                 | 1037137.00           | 1162864.00                                    | 930291.00                                          | 1493264.00                                           | 0.00                        | N                                          | N                                                |            | 34477141.00                | 34477141.00                           | 59323912.00                          | 58577996.00               | 0.987426385502022             | 61230527.00                      | 59364511.00           | 0.969524743760576                | 20590           | Aa2                            | 26.45    | 2351626782.00 | 3087503864.29 | 47                | 0.0598597721297108 | 25.15 | 3050.82  | 
| BETHANY      | JG       | 2013          | 8        | 8                     | NH                | 18090881.00                      | 4182421.00                | 22490279.00        | 163118.00              | 51393.00              | 3300.00             | 0.00               | 300000.00         | 3387567.00     | 3032874.00          | 3332874.00            | N                                  | 3437582.00    | 17861301.00 | 22060185.00   | 15599595.00 | 1176287.00   | 21122240.00        | 0.00                     | 0.00                    | 539796.00                  | 539796.00            | 398149.00                                     | 287352.00                                          | 398149.00                                            | 0.00                        | N                                          | N                                                | 9000231.68 | 6549985.00                 | 15550216.68                           | 17724295.00                          | 17454329.00               | 0.984768590231657             | 18069215.00                      | 17698838.00           | 0.979502319276183                | 5540            | Aa2                            | 20.96    | 619479650.00  | 820596491.90  | 4                 | 0.0561612157251404 | 28.54 | 943.59   | 
| BETHEL       | JG       | 2013          | 9        | 9                     | F                 | 71324881.00                      | 6091879.00                | 77842394.00        | 5603929.00             | 120887.00             | 0.00                | 0.00               | 0.00              | 11020653.00    | 10899766.00         | 10899766.00           | N                                  | 13396122.00   | 56319319.00 | 70858954.00   | 44246629.00 | 3660464.00   | 68400169.00        | 0.00                     | 0.00                    | 655730.00                  | 655730.00            | 1803055.00                                    | 2184185.00                                         | 1803055.00                                           | 0.00                        | N                                          | N                                                |            | 30309208.00                | 30309208.00                           | 56056266.00                          | 55353730.00               | 0.987467306509499             | 56830904.00                      | 55895490.00           | 0.983540399075827                | 19264           | Aa2                            | 16.79    | 2340464670.00 | 2654603288.29 | 48                | 0.0645192123876888 | 24.07 | 2962.07  | 
| BETHLEHEM    | BP       | 2013          | 10       | 10                    | L                 | 5430824.00                       | 3691980.00                | 9208383.00         | 428713.00              | 0.00                  | 0.00                | 0.00               | 300000.00         | 1706343.00     | 1406343.00          | 1706343.00            | N                                  | 1734028.00    | 8392776.00  | 10319687.00   | 6784789.00  | 0.00         | 9186972.00         | 24722.00                 | 24722.00                | 834231.00                  | 834231.00            | 323206.00                                     | 137625.00                                          | 323206.00                                            | 0.00                        | N                                          | N                                                | 474320.33  | 0.00                       | 474320.33                             | 8284463.00                           | 8110836.00                | 0.979041852199714             | 8793879.00                       | 8279789.00            | 0.94154001891543                 | 3553            |                                | 19.36    | 405598145.00  | 490788174.60  | 1                 | 0.0573940020682523 | 20.5  | 428.22   | 
```