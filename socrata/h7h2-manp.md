# Municipal Fiscal Indicators 2007-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/municipal-fiscal-indicators-2007-2012) |
| Metadata | [Link](https://data.ct.gov/api/views/h7h2-manp) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/h7h2-manp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/h7h2-manp/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | h7h2-manp |
| Name | Municipal Fiscal Indicators 2007-2012 |
| Category | Government |
| Tags | opm, fiscal indicators |
| Created | 2014-09-11T14:40:09Z |
| Publication Date | 2014-09-11T14:47:30Z |

## Description

Municipal Fiscal Indicators is an annual compendium of information compiled by the Office of Policy and Management, Intergovernmental Policy Division (IGP), Municipal Finance Services Unit (MFS). The data contained in Indicators provides key financial and demographic information on municipalities in Connecticut. Municipal Fiscal Indicators contains the most current financial data available for each of Connecticut's 169 municipalities. The majority of this data was compiled from the audited financial statements that are filed annually with the State of Connecticut, Office of Policy and Management, IGP Division. This database of information includes selected demographic and economic data relating to, or having an impact upon, a municipality?s financial condition. The most recent edition is for the Fiscal Years Ended 2008-2012 published in December of 2012

## Columns

```ls
| Included | Schema Type    | Field Name                                           | Name                                                   | Data Type | Render Type |
| ======== | ============== | ==================================================== | ====================================================== | ========= | =========== |
| Yes      | series tag     | municipality                                         | Municipality                                           | text      | text        |
| Yes      | series tag     | initials                                             | Initials                                               | text      | text        |
| Yes      | numeric metric | fisc_year_end                                        | Fisc_Year_End                                          | number    | text        |
| Yes      | numeric metric | numbered                                             | numbered                                               | number    | number      |
| Yes      | series tag     | comptroller_town_code                                | Comptroller Town Code                                  | text      | number      |
| Yes      | series tag     | county_identifier                                    | County_Identifier                                      | text      | text        |
| Yes      | numeric metric | invested_in_capital_assets_net_of_related_debt       | Invested In Capital Assets Net of Related Debt         | number    | number      |
| Yes      | numeric metric | unrestricted_net_assets                              | Unrestricted Net Assets                                | number    | number      |
| Yes      | numeric metric | total_net_assets                                     | Total Net Assets                                       | number    | number      |
| Yes      | numeric metric | change_in_net_assets                                 | Change In Net Assets                                   | number    | number      |
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
| Yes      | numeric metric | rsd_debt                                             | RSD_DEBT                                               | number    | number      |
| Yes      | numeric metric | town_bonded_long_term_debt                           | TOWN_Bonded_Long_Term_Debt                             | number    | number      |
| Yes      | numeric metric | total_bonded_long_term_debt_rsd__town                | Total_Bonded_Long_Term_Debt_(RSD_+_Town)               | number    | number      |
| Yes      | numeric metric | reserv_fund_bal                                      | Reserv_Fund_Bal                                        | number    | number      |
| Yes      | numeric metric | design_fund_bal                                      | Design_Fund_Bal                                        | number    | number      |
| Yes      | numeric metric | total_fund_bal                                       | Total_Fund_Bal                                         | number    | number      |
| Yes      | series tag     | restatement_y_or_n                                   | Restatement (Y or N)                                   | text      | text        |
| Yes      | numeric metric | unreserved_fund_bal                                  | Unreserved_Fund_Bal                                    | number    | number      |
| Yes      | series tag     | deficit_individual_enterprise_funds_y_or_n           | Deficit - Individual Enterprise Funds (Y or N)         | text      | text        |
| Yes      | series tag     | deficit_individual_internal_service_funds_y_or_n     | Deficit - Individual Internal Service Funds (Y or N)   | text      | text        |
| Yes      | numeric metric | curr_year_adjusted_taxes_collectible                 | Curr_Year_Adjusted_Taxes_Collectible                   | number    | number      |
| Yes      | numeric metric | curr_year_taxes_collected                            | Curr_Year_Taxes_Collected                              | number    | number      |
| Yes      | numeric metric | curr_year_tax_collection_rate                        | Curr_Year_Tax_Collection_Rate                          | number    | number      |
| Yes      | numeric metric | total_adjusted_taxes_collectible                     | Total_Adjusted_Taxes_Collectible                       | number    | number      |
| Yes      | numeric metric | total_taxes_collected                                | Total_Taxes_Collected                                  | number    | number      |
| Yes      | numeric metric | overal_total_tax_collection_rate                     | Overal_Total_Tax_Collection_Rate                       | number    | number      |
| Yes      | numeric metric | population                                           | Population                                             | number    | number      |
| Yes      | series tag     | moody_s_bond_ratings                                 | Moody's_Bond_Ratings                                   | text      | text        |
| Yes      | numeric metric | area_lmt                                             | area lmt                                               | number    | number      |
| Yes      | numeric metric | acglfy                                               | ACGLFY                                                 | number    | number      |
| Yes      | numeric metric | egl                                                  | EGL                                                    | number    | number      |
| Yes      | numeric metric | tanf_recipients                                      | TANF Recipients                                        | number    | number      |
| Yes      | numeric metric | empl                                                 | empl                                                   | number    | number      |
| Yes      | numeric metric | acmr                                                 | ACMR                                                   | number    | number      |
| Yes      | numeric metric | enrollmt                                             | enrollmt                                               | number    | number      |
| Yes      | series tag     | rpa_identifier                                       | RPA Identifier                                         | text      | text        |
```

## Time Field

```ls
Value = 2007
Format & Zone = yyyy
```

## Data Commands

```ls
series e:h7h2-manp d:2007-01-01T00:00:00.000Z t:county_identifier=T t:initials=KE t:rpa_identifier="Capital Region COG" t:municipality=ANDOVER t:comptroller_town_code=1 t:deficit_individual_internal_service_funds_y_or_n=N t:restatement_y_or_n=Y t:deficit_individual_enterprise_funds_y_or_n=N t:moody_s_bond_ratings=A3 m:total_trans_from_genl_fund=189666 m:total_net_assets=7681327 m:total_trans_to_genl_fund=12641 m:enrollmt=645.4 m:egl=411321603.97 m:curr_year_adjusted_taxes_collectible=7560022 m:invested_in_capital_assets_net_of_related_debt=6267423 m:acglfy=177097532 m:curr_year_tax_collection_rate=0.989030190652884 m:rsd_debt=5355433.17 m:tanf_recipients=4 m:education=7507964 m:operating_surplus_deficit_including_sources_and_uses=931099 m:total_bonded_long_term_debt_rsd__town=6896359.17 m:change_in_net_assets=2760235 m:reserv_fund_bal=67557 m:acmr=41.3 m:other_financing_uses=189666 m:debt_service=253133 m:unrestricted_net_assets=1218760 m:tax_rev=7653190 m:total_expenditures=9291904 m:prior_yr_op_surplus_def_including_sources_and_uses=-529852 m:empl=0.0342710997442455 m:population=3181 m:town_bonded_long_term_debt=1540926 m:other_financing_sources=12641 m:total_fund_bal=612051 m:unreserved_fund_bal=544494 m:numbered=1 m:inter_gov_rev=2438728 m:curr_year_taxes_collected=7477090 m:total_revenue=10400028 m:area_lmt=15.45 m:overal_total_tax_collection_rate=0.983747570465219 m:special_extraordinary_items=0 m:total_adjusted_taxes_collectible=7749426 m:operating_surplus_deficit_including_transfers=931099 m:fisc_year_end=2007 m:total_taxes_collected=7623479 m:design_fund_bal=0

series e:h7h2-manp d:2007-01-01T00:00:00.000Z t:county_identifier=NH t:initials=KE t:rpa_identifier="Valley COG" t:municipality=ANSONIA t:comptroller_town_code=2 t:deficit_individual_internal_service_funds_y_or_n=N t:restatement_y_or_n=Y t:deficit_individual_enterprise_funds_y_or_n=N t:moody_s_bond_ratings=A3 m:total_trans_from_genl_fund=0 m:total_net_assets=54034897 m:total_trans_to_genl_fund=0 m:enrollmt=2831.14 m:egl=1738906846.99 m:curr_year_adjusted_taxes_collectible=26051162 m:invested_in_capital_assets_net_of_related_debt=27000343 m:acglfy=803305236 m:curr_year_tax_collection_rate=0.96626376973127 m:tanf_recipients=389 m:education=29660930 m:operating_surplus_deficit_including_sources_and_uses=915743 m:total_bonded_long_term_debt_rsd__town=35390058 m:change_in_net_assets=-1292965 m:reserv_fund_bal=1279283 m:acmr=32.3 m:other_financing_uses=0 m:debt_service=8506553 m:unrestricted_net_assets=27026325 m:tax_rev=25391667 m:total_expenditures=52816370 m:prior_yr_op_surplus_def_including_sources_and_uses=265223 m:empl=0.0562613430127042 m:population=18550 m:town_bonded_long_term_debt=35390058 m:other_financing_sources=0 m:total_fund_bal=6833293 m:unreserved_fund_bal=5554010 m:numbered=2 m:inter_gov_rev=24511137 m:curr_year_taxes_collected=25172294 m:total_revenue=53732113 m:area_lmt=6.03 m:overal_total_tax_collection_rate=0.929711623334676 m:special_extraordinary_items=0 m:total_adjusted_taxes_collectible=27579624 m:operating_surplus_deficit_including_transfers=915743 m:fisc_year_end=2007 m:total_taxes_collected=25641097 m:design_fund_bal=472157

series e:h7h2-manp d:2007-01-01T00:00:00.000Z t:county_identifier=W t:initials=KE t:rpa_identifier="Windham Region COG" t:municipality=ASHFORD t:comptroller_town_code=3 t:deficit_individual_internal_service_funds_y_or_n=N t:restatement_y_or_n=N t:deficit_individual_enterprise_funds_y_or_n=N t:moody_s_bond_ratings=A2 m:total_trans_from_genl_fund=300685 m:total_net_assets=14025685 m:total_trans_to_genl_fund=614805 m:enrollmt=759.63 m:egl=502064701.13 m:curr_year_adjusted_taxes_collectible=7990034 m:invested_in_capital_assets_net_of_related_debt=9568225 m:acglfy=240875408 m:curr_year_tax_collection_rate=0.983508956282289 m:rsd_debt=4239072 m:tanf_recipients=18 m:education=9971001 m:operating_surplus_deficit_including_sources_and_uses=857698 m:total_bonded_long_term_debt_rsd__town=9350608 m:change_in_net_assets=552903 m:reserv_fund_bal=589731 m:acmr=33 m:other_financing_uses=300685 m:debt_service=623443 m:unrestricted_net_assets=3776726 m:tax_rev=8033841 m:total_expenditures=12888049 m:prior_yr_op_surplus_def_including_sources_and_uses=162946 m:empl=0.0385790679908327 m:population=4453 m:town_bonded_long_term_debt=5111536 m:other_financing_sources=655510 m:total_fund_bal=3189550 m:unreserved_fund_bal=2599819 m:numbered=3 m:inter_gov_rev=4629417 m:curr_year_taxes_collected=7858270 m:total_revenue=13390922 m:area_lmt=38.8 m:overal_total_tax_collection_rate=0.96217138900705 m:special_extraordinary_items=0 m:total_adjusted_taxes_collectible=8258511 m:operating_surplus_deficit_including_transfers=816993 m:fisc_year_end=2007 m:total_taxes_collected=7946103 m:design_fund_bal=0
```

## Meta Commands

```ls
metric m:fisc_year_end p:integer l:Fisc_Year_End t:dataTypeName=number

metric m:numbered p:integer l:numbered t:dataTypeName=number

metric m:invested_in_capital_assets_net_of_related_debt p:double l:"Invested In Capital Assets Net of Related Debt" t:dataTypeName=number

metric m:unrestricted_net_assets p:double l:"Unrestricted Net Assets" t:dataTypeName=number

metric m:total_net_assets p:double l:"Total Net Assets" t:dataTypeName=number

metric m:change_in_net_assets p:double l:"Change In Net Assets" t:dataTypeName=number

metric m:inter_gov_rev p:double l:Inter_Gov_Rev t:dataTypeName=number

metric m:tax_rev p:double l:Tax_Rev t:dataTypeName=number

metric m:total_revenue p:double l:Total_Revenue t:dataTypeName=number

metric m:education p:double l:Education t:dataTypeName=number

metric m:debt_service p:double l:Debt_Service t:dataTypeName=number

metric m:total_expenditures p:double l:Total_Expenditures t:dataTypeName=number

metric m:total_trans_to_genl_fund p:float l:TOTAL_Trans_to_Genl_Fund t:dataTypeName=number

metric m:other_financing_sources p:double l:Other_Financing_Sources t:dataTypeName=number

metric m:total_trans_from_genl_fund p:float l:TOTAL_Trans_from_Genl_Fund t:dataTypeName=number

metric m:other_financing_uses p:float l:Other_Financing_Uses t:dataTypeName=number

metric m:operating_surplus_deficit_including_transfers p:double l:Operating_Surplus_(Deficit)_Including_Transfers t:dataTypeName=number

metric m:prior_yr_op_surplus_def_including_sources_and_uses p:double l:Prior_Yr_OP_Surplus_(Def)_including_sources_and_uses t:dataTypeName=number

metric m:operating_surplus_deficit_including_sources_and_uses p:double l:Operating_Surplus_(Deficit)_Including_Sources_And_Uses t:dataTypeName=number

metric m:special_extraordinary_items p:float l:"Special / Extraordinary Items" t:dataTypeName=number

metric m:rsd_debt p:double l:RSD_DEBT t:dataTypeName=number

metric m:town_bonded_long_term_debt p:double l:TOWN_Bonded_Long_Term_Debt t:dataTypeName=number

metric m:total_bonded_long_term_debt_rsd__town p:double l:Total_Bonded_Long_Term_Debt_(RSD_+_Town) t:dataTypeName=number

metric m:reserv_fund_bal p:float l:Reserv_Fund_Bal t:dataTypeName=number

metric m:design_fund_bal p:float l:Design_Fund_Bal t:dataTypeName=number

metric m:total_fund_bal p:double l:Total_Fund_Bal t:dataTypeName=number

metric m:unreserved_fund_bal p:double l:Unreserved_Fund_Bal t:dataTypeName=number

metric m:curr_year_adjusted_taxes_collectible p:double l:Curr_Year_Adjusted_Taxes_Collectible t:dataTypeName=number

metric m:curr_year_taxes_collected p:double l:Curr_Year_Taxes_Collected t:dataTypeName=number

metric m:curr_year_tax_collection_rate p:double l:Curr_Year_Tax_Collection_Rate t:dataTypeName=number

metric m:total_adjusted_taxes_collectible p:double l:Total_Adjusted_Taxes_Collectible t:dataTypeName=number

metric m:total_taxes_collected p:double l:Total_Taxes_Collected t:dataTypeName=number

metric m:overal_total_tax_collection_rate p:double l:Overal_Total_Tax_Collection_Rate t:dataTypeName=number

metric m:population p:integer l:Population t:dataTypeName=number

metric m:area_lmt p:float l:"area lmt" t:dataTypeName=number

metric m:acglfy p:double l:ACGLFY t:dataTypeName=number

metric m:egl p:double l:EGL t:dataTypeName=number

metric m:tanf_recipients p:integer l:"TANF Recipients" t:dataTypeName=number

metric m:empl p:double l:empl t:dataTypeName=number

metric m:acmr p:float l:ACMR t:dataTypeName=number

metric m:enrollmt p:float l:enrollmt t:dataTypeName=number

entity e:h7h2-manp l:"Municipal Fiscal Indicators 2007-2012" t:url=https://data.ct.gov/api/views/h7h2-manp

property e:h7h2-manp t:meta.view v:id=h7h2-manp v:category=Government v:averageRating=0 v:name="Municipal Fiscal Indicators 2007-2012"

property e:h7h2-manp t:meta.view.owner v:id=6ypf-grnx v:screenName="Jamie Gamble" v:displayName="Jamie Gamble"

property e:h7h2-manp t:meta.view.tableauthor v:id=6ypf-grnx v:screenName="Jamie Gamble" v:roleName=editor v:displayName="Jamie Gamble"
```

## Top Records

```ls
| municipality | initials | fisc_year_end | numbered | comptroller_town_code | county_identifier | invested_in_capital_assets_net_of_related_debt | unrestricted_net_assets | total_net_assets | change_in_net_assets | inter_gov_rev | tax_rev     | total_revenue | education   | debt_service | total_expenditures | total_trans_to_genl_fund | other_financing_sources | total_trans_from_genl_fund | other_financing_uses | operating_surplus_deficit_including_transfers | prior_yr_op_surplus_def_including_sources_and_uses | operating_surplus_deficit_including_sources_and_uses | special_extraordinary_items | rsd_debt    | town_bonded_long_term_debt | total_bonded_long_term_debt_rsd__town | reserv_fund_bal | design_fund_bal | total_fund_bal | restatement_y_or_n | unreserved_fund_bal | deficit_individual_enterprise_funds_y_or_n | deficit_individual_internal_service_funds_y_or_n | curr_year_adjusted_taxes_collectible | curr_year_taxes_collected | curr_year_tax_collection_rate | total_adjusted_taxes_collectible | total_taxes_collected | overal_total_tax_collection_rate | population | moody_s_bond_ratings | area_lmt           | acglfy        | egl           | tanf_recipients | empl                 | acmr               | enrollmt           | rpa_identifier                         | 
| ============ | ======== | ============= | ======== | ===================== | ================= | ============================================== | ======================= | ================ | ==================== | ============= | =========== | ============= | =========== | ============ | ================== | ======================== | ======================= | ========================== | ==================== | ============================================= | ================================================== | ==================================================== | =========================== | =========== | ========================== | ===================================== | =============== | =============== | ============== | ================== | =================== | ========================================== | ================================================ | ==================================== | ========================= | ============================= | ================================ | ===================== | ================================ | ========== | ==================== | ================== | ============= | ============= | =============== | ==================== | ================== | ================== | ====================================== | 
| ANDOVER      | KE       | 2007          | 1        | 1                     | T                 | 6267423.00                                     | 1218760.00              | 7681327.00       | 2760235.00           | 2438728.00    | 7653190.00  | 10400028.00   | 7507964.00  | 253133.00    | 9291904.00         | 12641.00                 | 12641.00                | 189666.00                  | 189666.00            | 931099.00                                     | -529852.00                                         | 931099.00                                            | 0.00                        | 5355433.17  | 1540926.00                 | 6896359.17                            | 67557.00        | 0.00            | 612051.00      | Y                  | 544494.00           | N                                          | N                                                | 7560022.00                           | 7477090.00                | 0.989030190652884             | 7749426.00                       | 7623479.00            | 0.98374757046521899              | 3181       | A3                   | 15.45              | 177097532.00  | 411321603.97  | 4               | 0.034271099744245498 | 41.3               | 645.4              | Capital Region COG                     | 
| ANSONIA      | KE       | 2007          | 2        | 2                     | NH                | 27000343.00                                    | 27026325.00             | 54034897.00      | -1292965.00          | 24511137.00   | 25391667.00 | 53732113.00   | 29660930.00 | 8506553.00   | 52816370.00        | 0.00                     | 0.00                    | 0.00                       | 0.00                 | 915743.00                                     | 265223.00                                          | 915743.00                                            | 0.00                        |             | 35390058.00                | 35390058.00                           | 1279283.00      | 472157.00       | 6833293.00     | Y                  | 5554010.00          | N                                          | N                                                | 26051162.00                          | 25172294.00               | 0.96626376973127004           | 27579624.00                      | 25641097.00           | 0.92971162333467605              | 18550      | A3                   | 6.03               | 803305236.00  | 1738906846.99 | 389             | 0.056261343012704197 | 32.299999999999997 | 2831.14            | Valley COG                             | 
| ASHFORD      | KE       | 2007          | 3        | 3                     | W                 | 9568225.00                                     | 3776726.00              | 14025685.00      | 552903.00            | 4629417.00    | 8033841.00  | 13390922.00   | 9971001.00  | 623443.00    | 12888049.00        | 614805.00                | 655510.00               | 300685.00                  | 300685.00            | 816993.00                                     | 162946.00                                          | 857698.00                                            | 0.00                        | 4239072.00  | 5111536.00                 | 9350608.00                            | 589731.00       | 0.00            | 3189550.00     | N                  | 2599819.00          | N                                          | N                                                | 7990034.00                           | 7858270.00                | 0.98350895628228896           | 8258511.00                       | 7946103.00            | 0.96217138900705002              | 4453       | A2                   | 38.799999999999997 | 240875408.00  | 502064701.13  | 18              | 0.038579067990832702 | 33                 | 759.63             | Windham Region COG                     | 
| AVON         | VR       | 2007          | 4        | 4                     | H                 | 86386400.00                                    | 15331611.00             | 101718011.00     | 5390527.00           | 4265347.00    | 54940024.00 | 62365447.00   | 38966040.00 | 4575704.00   | 60098481.00        | 0.00                     | 0.00                    | 2796240.00                 | 2796240.00           | -529274.00                                    | -259393.00                                         | -529274.00                                           | 0.00                        |             | 18785000.00                | 18785000.00                           | 17118.00        | 245000.00       | 3777433.00     | N                  | 3760315.00          | N                                          | N                                                | 54780632.00                          | 54676535.00               | 0.99809974810075197           | 54859950.00                      | 54710689.00           | 0.99727923558078302              | 17333      | Aaa                  | 23.12              | 2187594990.00 | 3909626628.35 | 8               | 0.030117852466172001 | 24.85              | 3511.67            | Capital Region COG                     | 
| BARKHAMSTED  | VR       | 2007          | 5        | 5                     | L                 | 3984233.00                                     | 3207797.00              | 7192030.00       | 840084.00            | 1718189.00    | 7913331.00  | 9952079.00    | 7767269.00  | 247800.00    | 9682000.00         | 0.00                     | 0.00                    | 477036.00                  | 477036.00            | -206957.00                                    | 222085.00                                          | -206957.00                                           | 0.00                        | 2347503.81  | 420000.00                  | 2767503.81                            | 35517.00        | 500000.00       | 1682115.00     | N                  | 1646598.00          | N                                          | N                                                | 7884337.00                           | 7764219.00                | 0.98476498404368096           | 8158612.00                       | 7861723.00            | 0.96361035431026798              | 3665       | A2                   | 36.22              | 293631480.00  | 528656686.50  | 7               | 0.040164308534915601 | 26.7               | 666.72             | Litchfield Hills Cncl of Elected Ofcls | 
| BEACON FALLS | KE       | 2007          | 6        | 6                     | NH                | 6369331.00                                     | 2516981.00              | 9555624.00       | -40905.00            | 4072234.00    | 11680039.00 | 15983969.00   | 11089390.00 | 335193.00    | 16157980.00        | 155000.00                | 204762.00               | 0.00                       | 0.00                 | -19011.00                                     | 128877.00                                          | 30751.00                                             | 0.00                        | 11626951.63 | 3387321.00                 | 15014272.63                           | 0.00            | 0.00            | 1211252.00     | N                  | 1211252.00          | N                                          | N                                                | 11036797.00                          | 10718821.00               | 0.97118946737898704           | 11968681.00                      | 11045758.00           | 0.92288849539895002              | 5770       |                      | 9.77               | 320477264.00  | 785305285.39  | 16              | 0.044068819800784802 | 34.06              | 1035.83            | COG of Central Naugatuck Valley        | 
| BERLIN       | KE       | 2007          | 7        | 7                     | H                 | 59854926.00                                    | 18597437.00             | 78606020.00      | 5464095.00           | 9291106.00    | 48565796.00 | 64085370.00   | 37095815.00 | 2819982.00   | 62204634.00        | 185643.00                | 185643.00               | 750493.00                  | 750493.00            | 1315886.00                                    | 1567393.00                                         | 1315886.00                                           | 0.00                        |             | 9860000.00                 | 9860000.00                            | 0.00            | 1300000.00      | 9170925.00     | N                  | 9170925.00          | N                                          | N                                                | 48323207.00                          | 47880413.00               | 0.99083682504764203           | 49447786.00                      | 48477983.00           | 0.98038733220532903              | 20254      | Aa3                  | 26.45              | 1663795166.00 | 3194876776.48 | 26              | 0.0374955783516095   | 28.74              | 3322.87            | Central CT RPA                         | 
| BETHANY      | VR       | 2007          | 8        | 8                     | NH                | 17537911.00                                    | 4080391.00              | 21618302.00      | 329658.00            | 2146915.00    | 14840441.00 | 18440138.00   | 13332507.00 | 3769140.00   | 17747299.00        | 0.00                     | 0.00                    | 350100.00                  | 350100.00            | 342739.00                                     | 656476.00                                          | 342739.00                                            | 0.00                        | 12208837.51 | 8161624.00                 | 20370461.51                           | 250000.00       | 0.00            | 3086258.00     | N                  | 2836258.00          | N                                          | N                                                | 14712741.00                          | 14550047.00               | 0.98894196533467105           | 14991008.00                      | 14700698.00           | 0.98063439096290295              | 5566       | A1                   | 20.96              | 518280107.00  | 964392268.30  | 8               | 0.034846547314578001 | 28.21              | 1078.67            | South Central Regional COG             | 
| BETHEL       | VR       | 2007          | 9        | 9                     | F                 | 45591122.00                                    | -94775.00               | 54799432.00      | 1793671.00           | 10468243.00   | 44990513.00 | 57255342.00   | 36050621.00 | 4146715.00   | 56162029.00        | 0.00                     | 0.00                    | 554755.00                  | 554755.00            | 538558.00                                     | -617111.00                                         | 538558.00                                            | 0.00                        |             | 23730115.00                | 23730115.00                           | 991628.00       | 0.00            | 6251892.00     | N                  | 5260264.00          | Y                                          | N                                                | 44581196.00                          | 44094785.00               | 0.98908932366910896           | 45335820.00                      | 44511291.00           | 0.98181285791235295              | 18514      | Aa3                  | 16.79              | 1613614119.00 | 3295424221.16 | 36              | 0.032876967495575997 | 27.75              | 3231.5             | Housatonic Council of Elected Ofcls    | 
| BETHLEHEM    | VR       | 2007          | 10       | 10                    | L                 | 3921547.00                                     | 1505289.00              | 5426836.00       | 646788.00            | 1441614.00    | 7767811.00  | 9616589.00    | 6841120.00  | 169499.00    | 9050967.00         | 8735.00                  | 8735.00                 | 466628.00                  | 466628.00            | 107729.00                                     | -25885.00                                          | 107729.00                                            | 0.00                        | 2101489.51  | 468092.00                  | 2569581.51                            | 0.00            | 150000.00       | 492406.00      | N                  | 492406.00           | N                                          | N                                                | 7675166.00                           | 7528995.00                | 0.98095533047754302           | 7963817.00                       | 7692237.00            | 0.96589826210220597              | 3549       |                      | 19.36              | 351599618.00  | 638595096.33  | 3               | 0.037369207772795197 | 21.82              | 566.82000000000005 | COG of Central Naugatuck Valley        | 
```