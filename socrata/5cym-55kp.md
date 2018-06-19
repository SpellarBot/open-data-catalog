# Municipal Fiscal Indicators - 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/municipal-fiscal-indicators-2014) |
| Metadata | [Link](https://data.ct.gov/api/views/5cym-55kp) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/5cym-55kp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/5cym-55kp/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 5cym-55kp |
| Name | Municipal Fiscal Indicators - 2014 |
| Attribution | Office of Policy and Management |
| Category | Government |
| Tags | municipal, fiscal indicators, opm |
| Created | 2016-01-19T17:51:45Z |
| Publication Date | 2016-11-02T18:47:04Z |

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
| Yes      | numeric metric | 2014_population                                      | 2014 Population                                        | number    | number      |
| Yes      | series tag     | moody_s_bond_ratings_dec_2014                        | Moody's_Bond_Ratings_Dec_2014                          | text      | text        |
| Yes      | series tag     | moody_s_bond_ratings_july_2014                       | Moody's_Bond_Ratings_July_2014                         | text      | text        |
| Yes      | numeric metric | area_lmt                                             | area lmt                                               | number    | number      |
| Yes      | numeric metric | acglfy14                                             | ACGLFY14                                               | number    | number      |
| Yes      | numeric metric | egl                                                  | EGL                                                    | number    | number      |
| Yes      | numeric metric | tanf14_recipients                                    | TANF14 Recipients                                      | number    | number      |
| Yes      | numeric metric | empl                                                 | empl                                                   | number    | number      |
| Yes      | numeric metric | acmr                                                 | ACMR                                                   | number    | number      |
| Yes      | numeric metric | enrollmt                                             | enrollmt                                               | number    | number      |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5cym-55kp d:2014-01-01T00:00:00.000Z t:county_identifier=T t:restatement_of_fund_balance_y_or_n=N t:initials=BP t:municipality=ANDOVER t:comptroller_town_code=1 t:deficit_individual_internal_service_funds_y_or_n=N t:deficit_individual_enterprise_funds_y_or_n=N m:total_trans_from_genl_fund=74603 m:restricted_fund_bal=0 m:total_trans_to_genl_fund=0 m:enrollmt=569.02 m:egl=359165307.38 m:curr_year_adjusted_taxes_collectible=7989074 m:curr_year_tax_collection_rate=0.986690447478644 m:acglfy14=258994445 m:rsd_debt=3063445.37 m:education=8800679 m:operating_surplus_deficit_including_sources_and_uses=-2576 m:total_bonded_long_term_debt_rsd__town=3903870.37 m:acmr=30.77 m:other_financing_uses=74603 m:change_in_net_position=12323 m:debt_service=158379 m:tax_rev=7874644 m:assigned_fund_bal=0 m:total_expenditures=11010158 m:2014_population=3272 m:prior_yr_op_surplus_def_including_sources_and_uses=395766 m:unassigned_fund_bal=2415170 m:empl=0.0562793121417405 m:unrestricted_net_position=3094930 m:town_bonded_long_term_debt=840425 m:other_financing_sources=153569 m:total_fund_bal=2423109 m:unrestricted_fund_bal=2415170 m:net_investment_in_capital_assets=5771769 m:numbered=1 m:total_net_position=8988126 m:inter_gov_rev=2979697 m:curr_year_taxes_collected=7882743 m:total_revenue=10928616 m:area_lmt=15.45 m:overal_total_tax_collection_rate=0.981340595400254 m:nonspendable_fund_bal=7939 m:committed_fund_bal=0 m:special_extraordinary_items=0 m:tanf14_recipients=2 m:total_adjusted_taxes_collectible=8128448 m:operating_surplus_deficit_including_transfers=-156145 m:fisc_year_end=2014 m:total_taxes_collected=7976776

series e:5cym-55kp d:2014-01-01T00:00:00.000Z t:moody_s_bond_ratings_july_2014=Aa3 t:county_identifier=NH t:restatement_of_fund_balance_y_or_n=N t:initials=BP t:municipality=ANSONIA t:comptroller_town_code=2 t:deficit_individual_internal_service_funds_y_or_n=N t:moody_s_bond_ratings_dec_2014=Aa3 t:deficit_individual_enterprise_funds_y_or_n=N m:total_trans_from_genl_fund=275000 m:restricted_fund_bal=0 m:total_trans_to_genl_fund=0 m:enrollmt=2527.6 m:egl=1276588988.57 m:curr_year_adjusted_taxes_collectible=35133842 m:curr_year_tax_collection_rate=0.959358273427654 m:acglfy14=892673611 m:education=35784832 m:operating_surplus_deficit_including_sources_and_uses=3018600 m:total_bonded_long_term_debt_rsd__town=11887495 m:acmr=39.34 m:other_financing_uses=275000 m:change_in_net_position=726536 m:debt_service=8787631 m:tax_rev=34270829 m:assigned_fund_bal=0 m:total_expenditures=63866446 m:2014_population=18959 m:prior_yr_op_surplus_def_including_sources_and_uses=-26420 m:unassigned_fund_bal=9532434 m:empl=0.091671911055171 m:unrestricted_net_position=6192408 m:town_bonded_long_term_debt=11887495 m:other_financing_sources=0 m:total_fund_bal=11751566 m:unrestricted_fund_bal=11751566 m:net_investment_in_capital_assets=42287717 m:numbered=2 m:total_net_position=48483653 m:inter_gov_rev=28229568 m:curr_year_taxes_collected=33705942 m:total_revenue=67160046 m:area_lmt=6.03 m:overal_total_tax_collection_rate=0.909393430468242 m:nonspendable_fund_bal=0 m:committed_fund_bal=2219132 m:special_extraordinary_items=0 m:tanf14_recipients=251 m:total_adjusted_taxes_collectible=38076047 m:operating_surplus_deficit_including_transfers=3018600 m:fisc_year_end=2014 m:total_taxes_collected=34626107

series e:5cym-55kp d:2014-01-01T00:00:00.000Z t:moody_s_bond_ratings_july_2014=Aa3 t:county_identifier=W t:restatement_of_fund_balance_y_or_n=N t:initials=BP t:municipality=ASHFORD t:comptroller_town_code=3 t:deficit_individual_internal_service_funds_y_or_n=N t:moody_s_bond_ratings_dec_2014=Aa3 t:deficit_individual_enterprise_funds_y_or_n=N m:total_trans_from_genl_fund=759951 m:restricted_fund_bal=0 m:total_trans_to_genl_fund=0 m:enrollmt=615.78 m:egl=403533698.79 m:curr_year_adjusted_taxes_collectible=9402777 m:curr_year_tax_collection_rate=0.980526284947521 m:acglfy14=295376144 m:rsd_debt=1644168.37 m:education=11758559 m:operating_surplus_deficit_including_sources_and_uses=-223780 m:total_bonded_long_term_debt_rsd__town=4034168.37 m:acmr=31.65 m:other_financing_uses=759951 m:change_in_net_position=535641 m:debt_service=306386 m:tax_rev=9504537 m:assigned_fund_bal=102883 m:total_expenditures=14457564 m:2014_population=4259 m:prior_yr_op_surplus_def_including_sources_and_uses=437243 m:unassigned_fund_bal=1910173 m:empl=0.0549841772151899 m:unrestricted_net_position=3728792 m:town_bonded_long_term_debt=2390000 m:other_financing_sources=0 m:total_fund_bal=2035984 m:unrestricted_fund_bal=2035839 m:net_investment_in_capital_assets=12716872 m:numbered=3 m:total_net_position=17945653 m:inter_gov_rev=5109447 m:curr_year_taxes_collected=9219670 m:total_revenue=14993735 m:area_lmt=38.8 m:overal_total_tax_collection_rate=0.937915618626251 m:nonspendable_fund_bal=145 m:committed_fund_bal=22783 m:special_extraordinary_items=0 m:tanf14_recipients=30 m:total_adjusted_taxes_collectible=10035793 m:operating_surplus_deficit_including_transfers=-223780 m:fisc_year_end=2014 m:total_taxes_collected=9412727
```

## Meta Commands

```ls
metric m:fisc_year_end p:integer l:Fisc_Year_End t:dataTypeName=number

metric m:numbered p:integer l:numbered t:dataTypeName=number

metric m:net_investment_in_capital_assets p:double l:"Net Investment In Capital Assets" t:dataTypeName=number

metric m:unrestricted_net_position p:float l:"Unrestricted Net Position" t:dataTypeName=number

metric m:total_net_position p:double l:"Total Net Position" t:dataTypeName=number

metric m:change_in_net_position p:float l:"Change In Net Position" t:dataTypeName=number

metric m:nonspendable_fund_bal p:float l:Nonspendable_Fund_Bal t:dataTypeName=number

metric m:restricted_fund_bal p:float l:Restricted_Fund_Bal t:dataTypeName=number

metric m:committed_fund_bal p:float l:Committed_Fund_Bal t:dataTypeName=number

metric m:assigned_fund_bal p:double l:Assigned_Fund_Bal t:dataTypeName=number

metric m:total_fund_bal p:float l:Total_Fund_Bal t:dataTypeName=number

metric m:unassigned_fund_bal p:double l:Unassigned_Fund_Bal t:dataTypeName=number

metric m:unrestricted_fund_bal p:double l:Unrestricted_Fund_Bal t:dataTypeName=number

metric m:inter_gov_rev p:float l:Inter_Gov_Rev t:dataTypeName=number

metric m:tax_rev p:double l:Tax_Rev t:dataTypeName=number

metric m:total_revenue p:double l:Total_Revenue t:dataTypeName=number

metric m:education p:double l:Education t:dataTypeName=number

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

metric m:2014_population p:integer l:"2014 Population" t:dataTypeName=number

metric m:area_lmt p:float l:"area lmt" t:dataTypeName=number

metric m:acglfy14 p:double l:ACGLFY14 t:dataTypeName=number

metric m:egl p:double l:EGL t:dataTypeName=number

metric m:tanf14_recipients p:integer l:"TANF14 Recipients" t:dataTypeName=number

metric m:empl p:double l:empl t:dataTypeName=number

metric m:acmr p:float l:ACMR t:dataTypeName=number

metric m:enrollmt p:float l:enrollmt t:dataTypeName=number

entity e:5cym-55kp l:"Municipal Fiscal Indicators - 2014" t:attribution="Office of Policy and Management" t:url=https://data.ct.gov/api/views/5cym-55kp

property e:5cym-55kp t:meta.view v:id=5cym-55kp v:category=Government v:attributionLink="http://www.ct.gov/opm/cwp/view.asp?a=2984&q=383170" v:averageRating=0 v:name="Municipal Fiscal Indicators - 2014" v:attribution="Office of Policy and Management"

property e:5cym-55kp t:meta.view.license v:name="Public Domain"

property e:5cym-55kp t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:5cym-55kp t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| municipality | initials | fisc_year_end | numbered | comptroller_town_code | county_identifier | net_investment_in_capital_assets | unrestricted_net_position | total_net_position | change_in_net_position | nonspendable_fund_bal | restricted_fund_bal | committed_fund_bal | assigned_fund_bal | total_fund_bal | unassigned_fund_bal | unrestricted_fund_bal | restatement_of_fund_balance_y_or_n | inter_gov_rev | tax_rev     | total_revenue | education   | debt_service | total_expenditures | total_trans_to_genl_fund | other_financing_sources | total_trans_from_genl_fund | other_financing_uses | operating_surplus_deficit_including_transfers | prior_yr_op_surplus_def_including_sources_and_uses | operating_surplus_deficit_including_sources_and_uses | special_extraordinary_items | deficit_individual_enterprise_funds_y_or_n | deficit_individual_internal_service_funds_y_or_n | rsd_debt    | town_bonded_long_term_debt | total_bonded_long_term_debt_rsd__town | curr_year_adjusted_taxes_collectible | curr_year_taxes_collected | curr_year_tax_collection_rate | total_adjusted_taxes_collectible | total_taxes_collected | overal_total_tax_collection_rate | 2014_population | moody_s_bond_ratings_dec_2014 | moody_s_bond_ratings_july_2014 | area_lmt | acglfy14      | egl           | tanf14_recipients | empl               | acmr  | enrollmt | 
| ============ | ======== | ============= | ======== | ===================== | ================= | ================================ | ========================= | ================== | ====================== | ===================== | =================== | ================== | ================= | ============== | =================== | ===================== | ================================== | ============= | =========== | ============= | =========== | ============ | ================== | ======================== | ======================= | ========================== | ==================== | ============================================= | ================================================== | ==================================================== | =========================== | ========================================== | ================================================ | =========== | ========================== | ===================================== | ==================================== | ========================= | ============================= | ================================ | ===================== | ================================ | =============== | ============================= | ============================== | ======== | ============= | ============= | ================= | ================== | ===== | ======== | 
| ANDOVER      | BP       | 2014          | 1        | 1                     | T                 | 5771769.00                       | 3094930.00                | 8988126.00         | 12323.00               | 7939.00               | 0.00                | 0.00               | 0.00              | 2423109.00     | 2415170.00          | 2415170.00            | N                                  | 2979697.00    | 7874644.00  | 10928616.00   | 8800679.00  | 158379.00    | 11010158.00        | 0.00                     | 153569.00               | 74603.00                   | 74603.00             | -156145.00                                    | 395766.00                                          | -2576.00                                             | 0.00                        | N                                          | N                                                | 3063445.37  | 840425.00                  | 3903870.37                            | 7989074.00                           | 7882743.00                | 0.986690447478644             | 8128448.00                       | 7976776.00            | 0.981340595400254                | 3272            |                               |                                | 15.45    | 258994445.00  | 359165307.38  | 2                 | 0.0562793121417405 | 30.77 | 569.02   | 
| ANSONIA      | BP       | 2014          | 2        | 2                     | NH                | 42287717.00                      | 6192408.00                | 48483653.00        | 726536.00              | 0.00                  | 0.00                | 2219132.00         | 0.00              | 11751566.00    | 9532434.00          | 11751566.00           | N                                  | 28229568.00   | 34270829.00 | 67160046.00   | 35784832.00 | 8787631.00   | 63866446.00        | 0.00                     | 0.00                    | 275000.00                  | 275000.00            | 3018600.00                                    | -26420.00                                          | 3018600.00                                           | 0.00                        | N                                          | N                                                |             | 11887495.00                | 11887495.00                           | 35133842.00                          | 33705942.00               | 0.959358273427654             | 38076047.00                      | 34626107.00           | 0.909393430468242                | 18959           | Aa3                           | Aa3                            | 6.03     | 892673611.00  | 1276588988.57 | 251               | 0.091671911055171  | 39.34 | 2527.6   | 
| ASHFORD      | BP       | 2014          | 3        | 3                     | W                 | 12716872.00                      | 3728792.00                | 17945653.00        | 535641.00              | 145.00                | 0.00                | 22783.00           | 102883.00         | 2035984.00     | 1910173.00          | 2035839.00            | N                                  | 5109447.00    | 9504537.00  | 14993735.00   | 11758559.00 | 306386.00    | 14457564.00        | 0.00                     | 0.00                    | 759951.00                  | 759951.00            | -223780.00                                    | 437243.00                                          | -223780.00                                           | 0.00                        | N                                          | N                                                | 1644168.37  | 2390000.00                 | 4034168.37                            | 9402777.00                           | 9219670.00                | 0.980526284947521             | 10035793.00                      | 9412727.00            | 0.937915618626251                | 4259            | Aa3                           | Aa3                            | 38.8     | 295376144.00  | 403533698.79  | 30                | 0.0549841772151899 | 31.65 | 615.78   | 
| AVON         | JG       | 2014          | 4        | 4                     | H                 | 117881652.00                     | 17573977.00               | 135455629.00       | 3697025.00             | 5157.00               | 0.00                | 0.00               | 4164774.00        | 12857017.00    | 8687086.00          | 12851860.00           | N                                  | 10344758.00   | 71328459.00 | 84909300.00   | 56632683.00 | 3858788.00   | 81014128.00        | 2156.00                  | 356357.00               | 2101685.00                 | 2101685.00           | 1795643.00                                    | 1587933.00                                         | 2149844.00                                           | 0.00                        | N                                          | N                                                |             | 30640043.00                | 30640043.00                           | 71181158.00                          | 71013610.00               | 0.997646174848687             | 71355391.00                      | 71111744.00           | 0.99658544369829                 | 18421           | Aaa                           | Aaa                            | 23.12    | 2688826620.00 | 3603844067.64 | 17                | 0.0435208356000435 | 26.32 | 3420.67  | 
| BARKHAMSTED  | JG       | 2014          | 5        | 5                     | L                 | 3978633.00                       | 3047411.00                | 7026044.00         | -233732.00             | 0.00                  | 0.00                | 0.00               | 237300.00         | 1671412.00     | 1434112.00          | 1671412.00            | N                                  | 2207868.00    | 9101908.00  | 11435286.00   | 9363120.00  | 129900.00    | 11429152.00        | 0.00                     | 0.00                    | 18500.00                   | 18500.00             | -12366.00                                     | 227585.00                                          | -12366.00                                            | 0.00                        | N                                          | N                                                | 1176192.09  | 1770000.00                 | 2946192.09                            | 9127518.00                           | 8902816.00                | 0.975381916529773             | 9737230.00                       | 9046848.00            | 0.929098727256109                | 3705            |                               |                                | 36.22    | 374882562.00  | 485270508.21  | 3                 | 0.0529054640069384 | 24.26 | 602.45   | 
| BEACON FALLS | BP       | 2014          | 6        | 6                     | NH                | 10096061.00                      | 4932324.00                | 15158072.00        | 400457.00              | 24157.00              | 0.00                | 0.00               | 0.00              | 3136742.00     | 3112585.00          | 3112585.00            | N                                  | 4717436.00    | 15270452.00 | 20537046.00   | 13978646.00 | 251224.00    | 19597961.00        | 0.00                     | 2398496.00              | 50311.00                   | 2350225.00           | 888774.00                                     | 1252667.00                                         | 987356.00                                            | 0.00                        | N                                          | N                                                | 10949568.49 | 5889757.00                 | 16839325.49                           | 14984636.00                          | 14594422.00               | 0.973959060467001             | 16271361.00                      | 14967686.00           | 0.91987916683798                 | 6055            |                               |                                | 9.77     | 472457962.00  | 641059735.31  | 23                | 0.0608108108108108 | 31.9  | 940.2    | 
| BERLIN       | BP       | 2014          | 7        | 7                     | H                 | 64684687.00                      | 26565978.00               | 91397673.00        | 12226929.00            | 0.00                  | 0.00                | 328093.00          | 2600000.00        | 12703359.00    | 9775266.00          | 12703359.00           | N                                  | 13429655.00   | 62265408.00 | 79841221.00   | 48175177.00 | 4316876.00   | 78995047.00        | 73544.00                 | 343229.00               | 1277311.00                 | 1277311.00           | -357593.00                                    | 1493264.00                                         | -87908.00                                            | 0.00                        | N                                          | N                                                |             | 49918168.00                | 49918168.00                           | 61995090.00                          | 61321496.00               | 0.989134720185099             | 63645524.00                      | 61897428.00           | 0.972533873709642                | 20610           | Aa2                           | Aa2                            | 26.45    | 2155657751.00 | 3080343787.14 | 67                | 0.0524904877205119 | 28.77 | 3063.18  | 
| BETHANY      | JG       | 2014          | 8        | 8                     | NH                | 18594620.00                      | 4253928.00                | 22848548.00        | 586495.00              | 13966.00              | 3300.00             | 0.00               | 340000.00         | 3566528.00     | 3209262.00          | 3549262.00            | N                                  | 3467034.00    | 18347495.00 | 22710966.00   | 15923151.00 | 1179707.00   | 21893677.00        | 0.00                     | 0.00                    | 638328.00                  | 638328.00            | 178961.00                                     | 398149.00                                          | 178961.00                                            | 0.00                        | N                                          | N                                                | 8045321.10  | 5708239.00                 | 13753560.10                           | 18412298.00                          | 18149814.00               | 0.985744093431466             | 18772067.00                      | 18349732.00           | 0.977501944777845                | 5531            | Aa2                           | Aa2                            | 20.96    | 620166763.00  | 815132209.46  | 1                 | 0.0531949399935128 | 29.6  | 914.19   | 
| BETHEL       | JG       | 2014          | 9        | 9                     | F                 | 73628002.00                      | 10061517.00               | 84083501.00        | 6241107.00             | 132117.00             | 0.00                | 0.00               | 0.00              | 13723009.00    | 13590892.00         | 13590892.00           | N                                  | 14565184.00   | 58682339.00 | 74729636.00   | 46384500.00 | 3373128.00   | 71144751.00        | 0.00                     | 8000.00                 | 890529.00                  | 890529.00            | 2694356.00                                    | 1803055.00                                         | 2702356.00                                           | 0.00                        | N                                          | N                                                |             | 28878941.00                | 28878941.00                           | 58116179.00                          | 57446514.00               | 0.988477133020049             | 59150541.00                      | 58241776.00           | 0.984636404255373                | 19372           | Aa2                           | Aa2                            | 16.79    | 1852145585.00 | 2646524192.86 | 44                | 0.0539903891453877 | 31.5  | 2946.04  | 
| BETHLEHEM    | BP       | 2014          | 10       | 10                    | L                 | 5635231.00                       | 3773050.00                | 9683137.00         | 474754.00              | 0.00                  | 0.00                | 0.00               | 250000.00         | 1780936.00     | 1530936.00          | 1780936.00            | N                                  | 1667107.00    | 8356242.00  | 10283754.00   | 7017668.00  | 0.00         | 9392750.00         | 105625.00                | 105625.00               | 922036.00                  | 922036.00            | 74593.00                                      | 323206.00                                          | 74593.00                                             | 0.00                        | N                                          | N                                                | 223596.36   | 0.00                       | 223596.36                             | 8310051.00                           | 8093700.00                | 0.973965141730177             | 8802273.00                       | 8255837.00            | 0.937921034714556                | 3501            |                               |                                | 19.36    | 407011169.00  | 531735907.32  | 2                 | 0.0541497975708502 | 20.5  | 404.16   | 
```