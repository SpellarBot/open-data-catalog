# Public Assistance Cases with Earned Income: Beginning April 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-assistance-cases-with-earned-income-beginning-april-2006) |
| Metadata | [Link](https://data.ny.gov/api/views/5mdi-3rq9) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/5mdi-3rq9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/5mdi-3rq9/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 5mdi-3rq9 |
| Name | Public Assistance Cases with Earned Income: Beginning April 2006 |
| Attribution | New York State Office of Temporary and Disability Assistance (OTDA) |
| Category | Human Services |
| Tags | public assistance |
| Created | 2015-04-01T17:52:27Z |
| Publication Date | 2017-08-29T22:02:27Z |

## Description

The data in this dataset are monthly listings of the number of Temporary Assistance for Needy Families (TANF), Safety Net Assistance-Maintenance of Effort (SNA-MOE), and Safety Net Assistance Non-Maintenance of Effort (SNA Non-MOE) cash assistance cases with earned monthly income, and the average gross earned monthly income and average net earned monthly income (after applying earned income disregards) for these cases.  Data is presented by case type for each local social services district.  The dataset is from the NYS Office of Temporary and Disability Assistance (OTDA) and is updated monthly.

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                                    | Data Type | Render Type |
| ======== | ============== | ======================================= | ======================================= | ========= | =========== |
| No       |                | year                                    | Year                                    | number    | number      |
| No       |                | month                                   | Month                                   | text      | text        |
| Yes      | series tag     | month_code                              | Month Code                              | text      | number      |
| Yes      | series tag     | district_code                           | District Code                           | text      | number      |
| Yes      | series tag     | district                                | District                                | text      | text        |
| Yes      | numeric metric | tanf_cases_with_earned_income           | TANF Cases with Earned Income           | number    | number      |
| Yes      | numeric metric | tanf_average_gross_earned_income        | TANF Average Gross Earned Income        | money     | money       |
| Yes      | numeric metric | tanf_average_net_earned_income          | TANF Average Net Earned Income          | money     | money       |
| Yes      | numeric metric | sna_moe_cases_with_earned_income        | SNA MOE Cases with Earned Income        | number    | number      |
| Yes      | numeric metric | sna_moe_average_gross_earned_income     | SNA MOE Average Gross Earned Income     | money     | money       |
| Yes      | numeric metric | sna_moe_average_net_earned_income       | SNA MOE Average Net Earned Income       | money     | money       |
| Yes      | numeric metric | sna_non_moe_cases_with_earned_income    | SNA Non-MOE Cases with Earned Income    | number    | number      |
| Yes      | numeric metric | sna_non_moe_average_gross_earned_income | SNA Non-MOE Average Gross Earned Income | money     | money       |
| Yes      | numeric metric | sna_non_moe_average_net_earned_income   | SNA Non-MOE Average Net Earned Income   | money     | money       |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:5mdi-3rq9 d:2006-04-01T00:00:00.000Z t:district_code=66 t:district="New York City" t:month_code=4 m:tanf_average_net_earned_income=369 m:sna_non_moe_average_gross_earned_income=796 m:sna_non_moe_average_net_earned_income=546 m:tanf_cases_with_earned_income=9382 m:sna_non_moe_cases_with_earned_income=4622 m:sna_moe_average_gross_earned_income=718 m:sna_moe_average_net_earned_income=330 m:sna_moe_cases_with_earned_income=10399 m:tanf_average_gross_earned_income=765

series e:5mdi-3rq9 d:2006-04-01T00:00:00.000Z t:district_code=1 t:district=Albany t:month_code=4 m:tanf_average_net_earned_income=356 m:sna_non_moe_average_gross_earned_income=226 m:sna_non_moe_average_net_earned_income=151 m:tanf_cases_with_earned_income=162 m:sna_non_moe_cases_with_earned_income=10 m:sna_moe_average_gross_earned_income=744 m:sna_moe_average_net_earned_income=352 m:sna_moe_cases_with_earned_income=47 m:tanf_average_gross_earned_income=754

series e:5mdi-3rq9 d:2006-04-01T00:00:00.000Z t:district_code=2 t:district=Allegany t:month_code=4 m:tanf_average_net_earned_income=292 m:sna_non_moe_average_gross_earned_income=226 m:sna_non_moe_average_net_earned_income=136 m:tanf_cases_with_earned_income=48 m:sna_non_moe_cases_with_earned_income=9 m:sna_moe_average_gross_earned_income=751 m:sna_moe_average_net_earned_income=400 m:sna_moe_cases_with_earned_income=13 m:tanf_average_gross_earned_income=677
```

## Meta Commands

```ls
metric m:tanf_cases_with_earned_income p:integer l:"TANF Cases with Earned Income" d:"Table 30 number of Temporary Assistance for Needy Families (TANF) cases with earned monthly income. TANF is the federally-funded cash assistance program for households consisting of children living with related adults, and certain foster care cases (the latter cases are not examined for earned income)." t:dataTypeName=number

metric m:tanf_average_gross_earned_income p:double l:"TANF Average Gross Earned Income" d:"Table 30 TANF per-case average (arithmetic mean) of gross earned monthly income." t:dataTypeName=money

metric m:tanf_average_net_earned_income p:double l:"TANF Average Net Earned Income" d:"Table 30 TANF per-case average (arithmetic mean) of net earned monthly income (gross earned income after application of disregards)." t:dataTypeName=money

metric m:sna_moe_cases_with_earned_income p:integer l:"SNA MOE Cases with Earned Income" d:"Table 30 number of Safety Net Assistance-Maintenance of Effort (SNA-MOE) cases with earned monthly income. SNA MOE is a state-funded cash assistance program consisting of cases that would qualify for TANF except that they are barred from TANF assistance because they have exceeded the 60-month lifetime limit on that assistance or because they are a qualified alien but in the country for less than five years." t:dataTypeName=number

metric m:sna_moe_average_gross_earned_income p:double l:"SNA MOE Average Gross Earned Income" d:"Table 30 SNA-MOE per-case average (arithmetic mean) of gross earned monthly income." t:dataTypeName=money

metric m:sna_moe_average_net_earned_income p:double l:"SNA MOE Average Net Earned Income" d:"Table 30 SNA-MOE per-case average (arithmetic mean) of net earned monthly income (gross earned Income after application of disregards)." t:dataTypeName=money

metric m:sna_non_moe_cases_with_earned_income p:integer l:"SNA Non-MOE Cases with Earned Income" d:"Table 30 number of Safety Net Assistance Non-Maintenance of Effort (SNA Non-MOE) cases with earned monthly income. SNA Non-MOE is a state-funded cash assistance program primarily for childless adults and two-parent families with children where both parents are non-disabled" t:dataTypeName=number

metric m:sna_non_moe_average_gross_earned_income p:double l:"SNA Non-MOE Average Gross Earned Income" d:"Table 30 SNA Non-MOE per-case average (arithmetic mean) of gross earned monthly income." t:dataTypeName=money

metric m:sna_non_moe_average_net_earned_income p:double l:"SNA Non-MOE Average Net Earned Income" d:"Table 30 SNA Non-MOE per-case average (arithmetic mean) of net earned monthly income (gross earned income after application of disregards)." t:dataTypeName=money

entity e:5mdi-3rq9 l:"Public Assistance Cases with Earned Income:  Beginning April 2006" t:attribution="New York State Office of Temporary and Disability Assistance (OTDA)" t:url=https://data.ny.gov/api/views/5mdi-3rq9

property e:5mdi-3rq9 t:meta.view d:2017-09-25T07:32:03.444Z v:averageRating=0 v:name="Public Assistance Cases with Earned Income:  Beginning April 2006" v:attribution="New York State Office of Temporary and Disability Assistance (OTDA)" v:attributionLink=http://otda.ny.gov/resources/caseload/ v:id=5mdi-3rq9 v:category="Human Services"

property e:5mdi-3rq9 t:meta.view.owner d:2017-09-25T07:32:03.444Z v:displayName="NY Open Data" v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:id=xzik-pf59 v:screenName="NY Open Data" v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB

property e:5mdi-3rq9 t:meta.view.tableauthor d:2017-09-25T07:32:03.444Z v:displayName="NY Open Data" v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:id=xzik-pf59 v:screenName="NY Open Data" v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB

property e:5mdi-3rq9 t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:32:03.444Z v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY" v:Publisher="State of New York"
```

## Top Records

```ls
| year | month | month_code | district_code | district      | tanf_cases_with_earned_income | tanf_average_gross_earned_income | tanf_average_net_earned_income | sna_moe_cases_with_earned_income | sna_moe_average_gross_earned_income | sna_moe_average_net_earned_income | sna_non_moe_cases_with_earned_income | sna_non_moe_average_gross_earned_income | sna_non_moe_average_net_earned_income | 
| ==== | ===== | ========== | ============= | ============= | ============================= | ================================ | ============================== | ================================ | =================================== | ================================= | ==================================== | ======================================= | ===================================== | 
| 2006 | April | 4          | 66            | New York City | 9382                          | 765                              | 369                            | 10399                            | 718                                 | 330                               | 4622                                 | 796                                     | 546                                   | 
| 2006 | April | 4          | 1             | Albany        | 162                           | 754                              | 356                            | 47                               | 744                                 | 352                               | 10                                   | 226                                     | 151                                   | 
| 2006 | April | 4          | 2             | Allegany      | 48                            | 677                              | 292                            | 13                               | 751                                 | 400                               | 9                                    | 226                                     | 136                                   | 
| 2006 | April | 4          | 3             | Broome        | 159                           | 701                              | 316                            | 44                               | 804                                 | 384                               | 17                                   | 219                                     | 132                                   | 
| 2006 | April | 4          | 4             | Cattaraugus   | 38                            | 614                              | 283                            | 9                                | 799                                 | 381                               | 6                                    | 159                                     | 73                                    | 
| 2006 | April | 4          | 5             | Cayuga        | 27                            | 634                              | 294                            | 5                                | 1014                                | 496                               | 5                                    | 191                                     | 103                                   | 
| 2006 | April | 4          | 6             | Chautauqua    | 164                           | 666                              | 308                            | 55                               | 706                                 | 344                               | 16                                   | 230                                     | 121                                   | 
| 2006 | April | 4          | 7             | Chemung       | 126                           | 673                              | 313                            | 33                               | 780                                 | 371                               | 21                                   | 304                                     | 165                                   | 
| 2006 | April | 4          | 8             | Chenango      | 7                             | 640                              | 293                            | 2                                | 645                                 | 305                               | 3                                    | 238                                     | 145                                   | 
| 2006 | April | 4          | 9             | Clinton       | 32                            | 708                              | 328                            | 7                                | 921                                 | 450                               | 5                                    | 385                                     | 302                                   | 
```