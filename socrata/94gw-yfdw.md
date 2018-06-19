# Commerce Dashboard Measures - Fiscal Year Part 2

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/commerce-dashboard-measures-annual) |
| Metadata | [Link](https://data.maryland.gov/api/views/94gw-yfdw) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/94gw-yfdw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/94gw-yfdw/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 94gw-yfdw |
| Name | Commerce Dashboard Measures - Fiscal Year Part 2 |
| Category | Business and Economy |
| Tags | commerce, department of commerce, business, jobs, economy |
| Created | 2016-07-01T16:35:58Z |
| Publication Date | 2017-03-29T16:17:07Z |

## Description

Commerce Dashboard Measures - Fiscal Year Part 2

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                                                                     | Name                                                                                                                                                                               | Data Type     | Render Type   |
| ======== | ============== | ============================================================================================================================================== | ================================================================================================================================================================================== | ============= | ============= |
| Yes      | time           | date                                                                                                                                           | Date                                                                                                                                                                               | calendar_date | calendar_date |
| Yes      | series tag     | year                                                                                                                                           | Year                                                                                                                                                                               | text          | text          |
| Yes      | numeric metric | jobs_created_and_retained_resulting_from_successful_facility_location_decisions_export_assistance_and_resolving_issues_for_maryland_businesses | Jobs created and retained resulting from successful facility location decisions, Export assistance and resolving issues for Maryland businesses                                    | number        | number        |
| Yes      | numeric metric | total_tourism_related_sales_tax_revenues_millions                                                                                              | Total Tourism-related sales tax revenues ($ millions)                                                                                                                              | number        | number        |
| Yes      | numeric metric | restaurants_lunchrooms_delis_w_o_beer_wine_liquor_bwl                                                                                          | Restaurants, lunchrooms, delis w/o beer, wine, liquor (BWL)                                                                                                                        | number        | number        |
| Yes      | numeric metric | hotels_motels_selling_food_with_bwl                                                                                                            | Hotels, motels selling food with BWL                                                                                                                                               | number        | number        |
| Yes      | numeric metric | restaurants_and_night_clubs_with_bwl                                                                                                           | Restaurants and night clubs with BWL                                                                                                                                               | number        | number        |
| Yes      | numeric metric | general_merchandise                                                                                                                            | General merchandise                                                                                                                                                                | number        | number        |
| Yes      | numeric metric | automobile_bus_and_truck_rentals                                                                                                               | Automobile, bus and truck rentals                                                                                                                                                  | number        | number        |
| Yes      | numeric metric | commercial_airlines                                                                                                                            | Commercial airlines                                                                                                                                                                | number        | number        |
| Yes      | numeric metric | hotels_motels_apartments_cottages                                                                                                              | Hotels, motels, apartments, cottages                                                                                                                                               | number        | number        |
| Yes      | numeric metric | recreation_and_amusement_places                                                                                                                | Recreation and amusement places                                                                                                                                                    | number        | number        |
| Yes      | numeric metric | dollar_amount_of_total_project_costs_capital_investment_anticipated_for_projects_settled_millions                                              | Dollar amount of total project costs (capital investment) anticipated for projects settled ($ millions)                                                                            | number        | number        |
| Yes      | numeric metric | private_sector_dollars_leveraged_on_financial_incentives                                                                                       | Private sector dollars leveraged on financial incentives (figures are ratios, for example 23 is 23 to 1)                                                                           | number        | number        |
| Yes      | numeric metric | return_on_incentive_roi_over_5_years_on_maryland_economic_development_assistance_authority_fund_and_sunny_day_transactions                     | Return On incentive (ROi) over 5 years on Maryland Economic Development Assistance Authority & Fund and Sunny Day transactions (figures are ratios. For example 19.2 is 19.2 to 1) | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:94gw-yfdw d:2011-06-30T00:00:00.000Z t:year=2011 m:total_tourism_related_sales_tax_revenues_millions=359.6 m:jobs_created_and_retained_resulting_from_successful_facility_location_decisions_export_assistance_and_resolving_issues_for_maryland_businesses=10097 m:dollar_amount_of_total_project_costs_capital_investment_anticipated_for_projects_settled_millions=737.3 m:restaurants_and_night_clubs_with_bwl=70.4 m:restaurants_lunchrooms_delis_w_o_beer_wine_liquor_bwl=97.1 m:hotels_motels_selling_food_with_bwl=41.4 m:hotels_motels_apartments_cottages=84.1 m:commercial_airlines=0.1 m:general_merchandise=7.1 m:automobile_bus_and_truck_rentals=56.4 m:recreation_and_amusement_places=3

series e:94gw-yfdw d:2012-06-30T00:00:00.000Z t:year=2012 m:total_tourism_related_sales_tax_revenues_millions=377.4 m:jobs_created_and_retained_resulting_from_successful_facility_location_decisions_export_assistance_and_resolving_issues_for_maryland_businesses=10576 m:dollar_amount_of_total_project_costs_capital_investment_anticipated_for_projects_settled_millions=322.5 m:restaurants_and_night_clubs_with_bwl=74.1 m:restaurants_lunchrooms_delis_w_o_beer_wine_liquor_bwl=103.4 m:hotels_motels_selling_food_with_bwl=42.4 m:hotels_motels_apartments_cottages=88.7 m:commercial_airlines=0.2 m:general_merchandise=7.7 m:automobile_bus_and_truck_rentals=58 m:recreation_and_amusement_places=2.9

series e:94gw-yfdw d:2013-06-30T00:00:00.000Z t:year=2013 m:total_tourism_related_sales_tax_revenues_millions=392 m:jobs_created_and_retained_resulting_from_successful_facility_location_decisions_export_assistance_and_resolving_issues_for_maryland_businesses=10829 m:dollar_amount_of_total_project_costs_capital_investment_anticipated_for_projects_settled_millions=399 m:restaurants_and_night_clubs_with_bwl=82.3 m:restaurants_lunchrooms_delis_w_o_beer_wine_liquor_bwl=107.9 m:hotels_motels_selling_food_with_bwl=42.8 m:hotels_motels_apartments_cottages=91.8 m:commercial_airlines=0.1 m:general_merchandise=7.8 m:automobile_bus_and_truck_rentals=56.2 m:recreation_and_amusement_places=3.1
```

## Meta Commands

```ls
metric m:jobs_created_and_retained_resulting_from_successful_facility_location_decisions_export_assistance_and_resolving_issues_for_maryland_businesses p:integer l:"Jobs created and retained resulting from successful facility location decisions, Export assistance and resolving issues for Maryland businesses" t:dataTypeName=number

metric m:total_tourism_related_sales_tax_revenues_millions p:float l:"Total Tourism-related sales tax revenues ($ millions)" t:dataTypeName=number

metric m:restaurants_lunchrooms_delis_w_o_beer_wine_liquor_bwl p:float l:"Restaurants, lunchrooms, delis w/o beer, wine, liquor (BWL)" t:dataTypeName=number

metric m:hotels_motels_selling_food_with_bwl p:float l:"Hotels, motels selling food with BWL" t:dataTypeName=number

metric m:restaurants_and_night_clubs_with_bwl p:float l:"Restaurants and night clubs with BWL" t:dataTypeName=number

metric m:general_merchandise p:float l:"General merchandise" t:dataTypeName=number

metric m:automobile_bus_and_truck_rentals p:float l:"Automobile, bus and truck rentals" t:dataTypeName=number

metric m:commercial_airlines p:float l:"Commercial airlines" t:dataTypeName=number

metric m:hotels_motels_apartments_cottages p:float l:"Hotels, motels, apartments, cottages" t:dataTypeName=number

metric m:recreation_and_amusement_places p:float l:"Recreation and amusement places" t:dataTypeName=number

metric m:dollar_amount_of_total_project_costs_capital_investment_anticipated_for_projects_settled_millions p:float l:"Dollar amount of total project costs (capital investment) anticipated for projects settled ($ millions)" t:dataTypeName=number

metric m:private_sector_dollars_leveraged_on_financial_incentives p:integer l:"Private sector dollars leveraged on financial incentives (figures are ratios, for example 23 is 23 to 1)" t:dataTypeName=number

metric m:return_on_incentive_roi_over_5_years_on_maryland_economic_development_assistance_authority_fund_and_sunny_day_transactions p:float l:"Return On incentive (ROi) over 5 years on Maryland Economic Development Assistance Authority & Fund and Sunny Day transactions (figures are ratios. For example 19.2 is 19.2 to 1)" t:dataTypeName=number

entity e:94gw-yfdw l:"Commerce Dashboard Measures - Fiscal Year Part 2" t:url=https://data.maryland.gov/api/views/94gw-yfdw

property e:94gw-yfdw t:meta.view v:id=94gw-yfdw v:category="Business and Economy" v:averageRating=0 v:name="Commerce Dashboard Measures - Fiscal Year Part 2"

property e:94gw-yfdw t:meta.view.owner v:id=r2jy-z5qx v:screenName="Eric Sklar" v:displayName="Eric Sklar"

property e:94gw-yfdw t:meta.view.tableauthor v:id=r2jy-z5qx v:screenName="Eric Sklar" v:roleName=editor v:displayName="Eric Sklar"
```

## Top Records

```ls
| date                | year         | jobs_created_and_retained_resulting_from_successful_facility_location_decisions_export_assistance_and_resolving_issues_for_maryland_businesses | total_tourism_related_sales_tax_revenues_millions | restaurants_lunchrooms_delis_w_o_beer_wine_liquor_bwl | hotels_motels_selling_food_with_bwl | restaurants_and_night_clubs_with_bwl | general_merchandise | automobile_bus_and_truck_rentals | commercial_airlines | hotels_motels_apartments_cottages | recreation_and_amusement_places | dollar_amount_of_total_project_costs_capital_investment_anticipated_for_projects_settled_millions | private_sector_dollars_leveraged_on_financial_incentives | return_on_incentive_roi_over_5_years_on_maryland_economic_development_assistance_authority_fund_and_sunny_day_transactions | 
| =================== | ============ | ============================================================================================================================================== | ================================================= | ===================================================== | =================================== | ==================================== | =================== | ================================ | =================== | ================================= | =============================== | ================================================================================================= | ======================================================== | ========================================================================================================================== | 
| 2011-06-30T00:00:00 | 2011         | 10097                                                                                                                                          | 359.6                                             | 97.1                                                  | 41.4                                | 70.4                                 | 7.1                 | 56.4                             | 0.10                | 84.1                              | 3.0                             | 737.3                                                                                             |                                                          |                                                                                                                            | 
| 2012-06-30T00:00:00 | 2012         | 10576                                                                                                                                          | 377.4                                             | 103.4                                                 | 42.4                                | 74.1                                 | 7.7                 | 58.0                             | 0.20                | 88.7                              | 2.9                             | 322.5                                                                                             |                                                          |                                                                                                                            | 
| 2013-06-30T00:00:00 | 2013         | 10829                                                                                                                                          | 392                                               | 107.9                                                 | 42.8                                | 82.3                                 | 7.8                 | 56.2                             | 0.10                | 91.8                              | 3.1                             | 399                                                                                               |                                                          |                                                                                                                            | 
| 2014-06-30T00:00:00 | 2014         | 10627                                                                                                                                          | 401.4                                             | 112.4                                                 | 41.5                                | 83.3                                 | 8.3                 | 58.1                             | 0.20                | 94.4                              | 3.2                             | 348.2                                                                                             | 15                                                       | 9.4                                                                                                                        | 
| 2015-06-30T00:00:00 | 2015         | 11761                                                                                                                                          | 425.9                                             | 120.1                                                 | 42.2                                | 87.2                                 | 11.1                | 60.5                             | 0.24                | 100.4                             | 4.3                             | 508.9                                                                                             | 18                                                       | 19.2                                                                                                                       | 
| 2016-06-30T00:00:00 | 2016         | 11305                                                                                                                                          | 443.5                                             | 127.5                                                 | 35.6                                | 87.6                                 | 25.1                | 56.5                             | 0.30                | 96.4                              | 4.4                             | 307.8                                                                                             | 23                                                       | 24.5                                                                                                                       | 
| 2017-02-28T00:00:00 | 2017 to-date | 16677                                                                                                                                          | 240.3                                             | 67                                                    | 20.3                                | 45.4                                 | 7.3                 | 35.1                             | 0.1                 | 62.7                              | 2.4                             |                                                                                                   |                                                          |                                                                                                                            | 
```