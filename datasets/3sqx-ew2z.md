# Earned Income Tax Credit (EITC) Claims by Credit Type and Size of Earned Income: Beginning Tax Year 1994

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/earned-income-tax-credit-eitc-claims-by-credit-type-and-size-of-earned-income-beginning-ta) |
| Metadata | [Link](https://data.ny.gov/api/views/3sqx-ew2z) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/3sqx-ew2z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/3sqx-ew2z/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 3sqx-ew2z |
| Name | Earned Income Tax Credit (EITC) Claims by Credit Type and Size of Earned Income: Beginning Tax Year 1994 |
| Attribution | New York State Department of Taxation and Finance |
| Category | Government & Finance |
| Tags | eitc, earned income, non-custodial parent, credit, tax |
| Created | 2015-10-06T19:52:35Z |
| Publication Date | 2017-04-20T22:01:39Z |

## Description

The Department of Taxation and Finance (the Department) annually publishes statistical information on the New York State earned income tax credit (EITC). This includes data on the separate New York City EITC and the New York State noncustodial parent EITC. Summary data are presented for all taxpayers which includes full-year New York state residents, part-year residents and nonresidents (where applicable). Data are shown for the total number of claimants and credit claimed by county and/or region for all filing statuses.

## Columns

```ls
| Included | Schema Type    | Field Name                                                  | Name                                                               | Data Type | Render Type |
| ======== | ============== | =========================================================== | ================================================================== | ========= | =========== |
| Yes      | time           | tax_year                                                    | Tax Year                                                           | number    | number      |
| Yes      | series tag     | credit_type                                                 | Credit Type                                                        | text      | text        |
| Yes      | series tag     | place_of_residence                                          | Place of Residence                                                 | text      | text        |
| Yes      | series tag     | county                                                      | County                                                             | text      | text        |
| Yes      | series tag     | size_of_earned_income                                       | Size of Earned Income                                              | text      | text        |
| Yes      | series tag     | notes                                                       | Notes                                                              | text      | text        |
| Yes      | numeric metric | number_of_claims_zero_qualifying_children                   | Number of Claims, Zero Qualifying Children                         | number    | number      |
| Yes      | numeric metric | credit_amount_claimed_zero_qualifying_children_000          | Credit Amount Claimed, Zero Qualifying Children ($000)             | number    | number      |
| Yes      | numeric metric | average_credit_zero_qualifying_children                     | Average Credit, Zero Qualifying Children                           | number    | number      |
| Yes      | numeric metric | number_of_claims_one_qualifying_child                       | Number of Claims, One Qualifying Child                             | number    | number      |
| Yes      | numeric metric | credit_amount_claimed_one_qualifying_child_000              | Credit Amount Claimed, One Qualifying Child ($000)                 | number    | number      |
| Yes      | numeric metric | average_credit_one_qualifying_child                         | Average Credit, One Qualifying Child                               | number    | number      |
| Yes      | numeric metric | number_of_claims_more_than_one_qualifying_child             | Number of Claims, More than One Qualifying Child *                 | number    | number      |
| Yes      | numeric metric | credit_amount_claimed_more_than_one_qualifying_child_000    | Credit Amount Claimed, More than One Qualifying Child ($000) *     | number    | number      |
| Yes      | numeric metric | average_credit_more_than_one_qualifying_child               | Average Credit, More than One Qualifying Child *                   | number    | number      |
| Yes      | numeric metric | number_of_claims_two_qualifying_children                    | Number of Claims, Two Qualifying Children **                       | number    | number      |
| Yes      | numeric metric | credit_amount_claimed_two_qualifying_children_000           | Credit Amount Claimed, Two Qualifying Children ($000) **           | number    | number      |
| Yes      | numeric metric | average_credit_two_qualifying_children                      | Average Credit, Two Qualifying Children **                         | number    | number      |
| Yes      | numeric metric | number_of_claims_more_than_two_qualifying_children          | Number of Claims, More than Two Qualifying Children **             | number    | number      |
| Yes      | numeric metric | credit_amount_claimed_more_than_two_qualifying_children_000 | Credit Amount Claimed, More than Two Qualifying Children ($000) ** | number    | number      |
| Yes      | numeric metric | average_credit_more_than_two_qualifying_children            | Average Credit, More than Two Qualifying Children **               | number    | number      |
| Yes      | numeric metric | number_of_claims_total                                      | Number of Claims, Total                                            | number    | number      |
| Yes      | numeric metric | credit_amount_claimed_total_000                             | Credit Amount Claimed, Total ($000)                                | number    | number      |
| Yes      | numeric metric | average_credit_total                                        | Average Credit, Total                                              | number    | number      |
| Yes      | numeric metric | place_of_residence_sort_order                               | Place of Residence Sort Order                                      | number    | number      |
| Yes      | numeric metric | earned_income_sort_order                                    | Earned Income Sort Order                                           | number    | number      |
```

## Time Field

```ls
Value = tax_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3sqx-ew2z d:2013-01-01T00:00:00.000Z t:place_of_residence="New York City - Bronx" t:county=Bronx t:size_of_earned_income="$0 - $4,000" t:credit_type="NYC EITC" m:average_credit_one_qualifying_child=40 m:credit_amount_claimed_total_000=338 m:average_credit_zero_qualifying_children=13 m:credit_amount_claimed_zero_qualifying_children_000=141 m:credit_amount_claimed_two_qualifying_children_000=56 m:average_credit_total=22 m:place_of_residence_sort_order=1 m:number_of_claims_more_than_two_qualifying_children=356 m:number_of_claims_two_qualifying_children=1242 m:number_of_claims_total=15438 m:average_credit_more_than_two_qualifying_children=47 m:credit_amount_claimed_more_than_two_qualifying_children_000=17 m:number_of_claims_one_qualifying_child=3119 m:number_of_claims_zero_qualifying_children=10721 m:average_credit_two_qualifying_children=45 m:earned_income_sort_order=1 m:credit_amount_claimed_one_qualifying_child_000=124

series e:3sqx-ew2z d:2013-01-01T00:00:00.000Z t:place_of_residence="New York City - Bronx" t:county=Bronx t:size_of_earned_income="$4,001 - $8,000" t:credit_type="NYC EITC" m:average_credit_one_qualifying_child=105 m:credit_amount_claimed_total_000=1642 m:average_credit_zero_qualifying_children=21 m:credit_amount_claimed_zero_qualifying_children_000=334 m:credit_amount_claimed_two_qualifying_children_000=353 m:average_credit_total=60 m:place_of_residence_sort_order=1 m:number_of_claims_more_than_two_qualifying_children=791 m:number_of_claims_two_qualifying_children=2860 m:number_of_claims_total=27554 m:average_credit_more_than_two_qualifying_children=137 m:credit_amount_claimed_more_than_two_qualifying_children_000=108 m:number_of_claims_one_qualifying_child=8037 m:number_of_claims_zero_qualifying_children=15866 m:average_credit_two_qualifying_children=123 m:earned_income_sort_order=2 m:credit_amount_claimed_one_qualifying_child_000=847

series e:3sqx-ew2z d:2013-01-01T00:00:00.000Z t:place_of_residence="New York City - Bronx" t:county=Bronx t:size_of_earned_income="$8,001 - $12,000" t:credit_type="NYC EITC" m:average_credit_one_qualifying_child=155 m:credit_amount_claimed_total_000=4807 m:average_credit_zero_qualifying_children=17 m:credit_amount_claimed_zero_qualifying_children_000=212 m:credit_amount_claimed_two_qualifying_children_000=1183 m:average_credit_total=121 m:place_of_residence_sort_order=1 m:number_of_claims_more_than_two_qualifying_children=1580 m:number_of_claims_two_qualifying_children=5846 m:number_of_claims_total=39667 m:average_credit_more_than_two_qualifying_children=229 m:credit_amount_claimed_more_than_two_qualifying_children_000=362 m:number_of_claims_one_qualifying_child=19624 m:number_of_claims_zero_qualifying_children=12617 m:average_credit_two_qualifying_children=202 m:earned_income_sort_order=3 m:credit_amount_claimed_one_qualifying_child_000=3050
```

## Meta Commands

```ls
metric m:number_of_claims_zero_qualifying_children p:long l:"Number of Claims, Zero Qualifying Children" d:"Count of the number of EITC claims with no qualifying children" t:dataTypeName=number

metric m:credit_amount_claimed_zero_qualifying_children_000 p:long l:"Credit Amount Claimed, Zero Qualifying Children ($000)" d:"Amount of EITC claimed with no qualifying children, in thousands of dollars" t:dataTypeName=number

metric m:average_credit_zero_qualifying_children p:long l:"Average Credit, Zero Qualifying Children" d:"Average amount of EITC claimed with no qualifying children" t:dataTypeName=number

metric m:number_of_claims_one_qualifying_child p:long l:"Number of Claims, One Qualifying Child" d:"Count of the number of EITC claims with one qualifying child" t:dataTypeName=number

metric m:credit_amount_claimed_one_qualifying_child_000 p:long l:"Credit Amount Claimed, One Qualifying Child ($000)" d:"Amount of EITC claimed with one qualifying child, in thousands of dollars" t:dataTypeName=number

metric m:average_credit_one_qualifying_child p:long l:"Average Credit, One Qualifying Child" d:"Average amount of EITC claimed with one qualifying child" t:dataTypeName=number

metric m:number_of_claims_more_than_one_qualifying_child p:long l:"Number of Claims, More than One Qualifying Child *" d:"Count of the number of EITC claims with more than one qualifying child * For tax years prior to 2008 this column is populated. After 2008, there is a finer breakdown." t:dataTypeName=number

metric m:credit_amount_claimed_more_than_one_qualifying_child_000 p:long l:"Credit Amount Claimed, More than One Qualifying Child ($000) *" d:"Amount of EITC claimed with more than one qualifying child, in thousands of dollars * For tax years prior to 2008 this column is populated. After 2008, there is a finer breakdown." t:dataTypeName=number

metric m:average_credit_more_than_one_qualifying_child p:long l:"Average Credit, More than One Qualifying Child *" d:"Average amount of EITC claimed with more than one qualifying child * For tax years prior to 2008 this column is populated. After 2008, there is a finer breakdown." t:dataTypeName=number

metric m:number_of_claims_two_qualifying_children p:long l:"Number of Claims, Two Qualifying Children **" d:"Count of the number of EITC claims with two qualifying children. ** For tax years prior to 2008 this column is not populated. Beginning 2009, the finer breakdown exists." t:dataTypeName=number

metric m:credit_amount_claimed_two_qualifying_children_000 p:long l:"Credit Amount Claimed, Two Qualifying Children ($000) **" d:"Amount of EITC claimed with two qualifying children, in thousands of dollars ** For tax years prior to 2008 this column is not populated. Beginning 2009, the finer breakdown exists." t:dataTypeName=number

metric m:average_credit_two_qualifying_children p:long l:"Average Credit, Two Qualifying Children **" d:"Average amount of EITC claimed with two qualifying children ** For tax years prior to 2008 this column is not populated. Beginning 2009, the finer breakdown exists." t:dataTypeName=number

metric m:number_of_claims_more_than_two_qualifying_children p:long l:"Number of Claims, More than Two Qualifying Children **" d:"Count of the number of EITC claims with more than two qualifying children. ** For tax years prior to 2008 this column is not populated. Beginning 2009, the finer breakdown exists." t:dataTypeName=number

metric m:credit_amount_claimed_more_than_two_qualifying_children_000 p:long l:"Credit Amount Claimed, More than Two Qualifying Children ($000) **" d:"Amount of EITC claimed with more than two qualifying children, in thousands of dollars ** For tax years prior to 2008 this column is not populated. Beginning 2009, the finer breakdown exists." t:dataTypeName=number

metric m:average_credit_more_than_two_qualifying_children p:long l:"Average Credit, More than Two Qualifying Children **" d:"Average amount of EITC claimed with more than two qualifying children ** For tax years prior to 2008 this column is not populated. Beginning 2009, the finer breakdown exists." t:dataTypeName=number

metric m:number_of_claims_total p:long l:"Number of Claims, Total" d:"Total count of the number of EITC claims" t:dataTypeName=number

metric m:credit_amount_claimed_total_000 p:long l:"Credit Amount Claimed, Total ($000)" d:"Amount of EITC claimed, in thousands of dollars" t:dataTypeName=number

metric m:average_credit_total p:long l:"Average Credit, Total" d:"Average amount of EITC claimed" t:dataTypeName=number

metric m:place_of_residence_sort_order p:long l:"Place of Residence Sort Order" d:"Sort order on Place of Residence" t:dataTypeName=number

metric m:earned_income_sort_order p:long l:"Earned Income Sort Order" d:"Sort order on Earned Income ranges" t:dataTypeName=number

entity e:3sqx-ew2z l:"Earned Income Tax Credit (EITC) Claims by Credit Type and Size of Earned Income: Beginning Tax Year 1994" t:attribution="New York State Department of Taxation and Finance" t:url=https://data.ny.gov/api/views/3sqx-ew2z

property e:3sqx-ew2z t:meta.view v:id=3sqx-ew2z v:category="Government & Finance" v:attributionLink=https://www.tax.ny.gov/research/stats/statistics/personal_income_tax_statistical_reports.htm v:averageRating=0 v:name="Earned Income Tax Credit (EITC) Claims by Credit Type and Size of Earned Income: Beginning Tax Year 1994" v:attribution="New York State Department of Taxation and Finance"

property e:3sqx-ew2z t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:3sqx-ew2z t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:3sqx-ew2z t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| tax_year | credit_type | place_of_residence    | county | size_of_earned_income | notes  | number_of_claims_zero_qualifying_children | credit_amount_claimed_zero_qualifying_children_000 | average_credit_zero_qualifying_children | number_of_claims_one_qualifying_child | credit_amount_claimed_one_qualifying_child_000 | average_credit_one_qualifying_child | number_of_claims_more_than_one_qualifying_child | credit_amount_claimed_more_than_one_qualifying_child_000 | average_credit_more_than_one_qualifying_child | number_of_claims_two_qualifying_children | credit_amount_claimed_two_qualifying_children_000 | average_credit_two_qualifying_children | number_of_claims_more_than_two_qualifying_children | credit_amount_claimed_more_than_two_qualifying_children_000 | average_credit_more_than_two_qualifying_children | number_of_claims_total | credit_amount_claimed_total_000 | average_credit_total | place_of_residence_sort_order | earned_income_sort_order | 
| ======== | =========== | ===================== | ====== | ===================== | ====== | ========================================= | ================================================== | ======================================= | ===================================== | ============================================== | =================================== | =============================================== | ======================================================== | ============================================= | ======================================== | ================================================= | ====================================== | ================================================== | =========================================================== | ================================================ | ====================== | =============================== | ==================== | ============================= | ======================== | 
| 2013     | NYC EITC    | New York City - Bronx | Bronx  | $0 - $4,000           |        | 10721                                     | 141.000                                            | 13                                      | 3119                                  | 124.000                                        | 40                                  |                                                 |                                                          |                                               | 1242                                     | 56.000                                            | 45                                     | 356                                                | 17.000                                                      | 47                                               | 15438                  | 338.000                         | 22                   | 1                             | 1                        | 
| 2013     | NYC EITC    | New York City - Bronx | Bronx  | $4,001 - $8,000       |        | 15866                                     | 334.000                                            | 21                                      | 8037                                  | 847.000                                        | 105                                 |                                                 |                                                          |                                               | 2860                                     | 353.000                                           | 123                                    | 791                                                | 108.000                                                     | 137                                              | 27554                  | 1642.000                        | 60                   | 1                             | 2                        | 
| 2013     | NYC EITC    | New York City - Bronx | Bronx  | $8,001 - $12,000      |        | 12617                                     | 212.000                                            | 17                                      | 19624                                 | 3050.000                                       | 155                                 |                                                 |                                                          |                                               | 5846                                     | 1183.000                                          | 202                                    | 1580                                               | 362.000                                                     | 229                                              | 39667                  | 4807.000                        | 121                  | 1                             | 3                        | 
| 2013     | NYC EITC    | New York City - Bronx | Bronx  | $12,001 - $16,000     |        | 5872                                      | 42.000                                             | 7                                       | 12232                                 | 1939.000                                       | 159                                 |                                                 |                                                          |                                               | 11618                                    | 3017.000                                          | 260                                    | 3330                                               | 975.000                                                     | 293                                              | 33052                  | 5973.000                        | 181                  | 1                             | 4                        | 
| 2013     | NYC EITC    | New York City - Bronx | Bronx  | $16,001 - $20,000     |        | 716                                       | 5.000                                              | 7                                       | 10024                                 | 1530.000                                       | 153                                 |                                                 |                                                          |                                               | 6805                                     | 1747.000                                          | 257                                    | 2367                                               | 689.000                                                     | 291                                              | 19912                  | 3971.000                        | 199                  | 1                             | 5                        | 
| 2013     | NYC EITC    | New York City - Bronx | Bronx  | $20,001 - $24,000     | d/, a/ |                                           |                                                    | 1                                       |                                       |                                                | 126                                 |                                                 |                                                          |                                               | 5262                                     | 1179.000                                          | 224                                    | 1888                                               | 501.000                                                     | 265                                              | 15564                  | 2742.000                        | 176                  | 1                             | 6                        | 
| 2013     | NYC EITC    | New York City - Bronx | Bronx  | $24,001 - $28,000     |        | 0                                         | 0.000                                              | 0                                       | 7228                                  | 697.000                                        | 96                                  |                                                 |                                                          |                                               | 4493                                     | 832.000                                           | 185                                    | 1578                                               | 360.000                                                     | 228                                              | 13299                  | 1889.000                        | 142                  | 1                             | 7                        | 
| 2013     | NYC EITC    | New York City - Bronx | Bronx  | $28,001 - $32,000     |        | 0                                         | 0.000                                              | 0                                       | 6495                                  | 424.000                                        | 65                                  |                                                 |                                                          |                                               | 4121                                     | 588.000                                           | 143                                    | 1511                                               | 281.000                                                     | 186                                              | 12127                  | 1293.000                        | 107                  | 1                             | 8                        | 
| 2013     | NYC EITC    | New York City - Bronx | Bronx  | $32,001 - $36,000     |        | 0                                         | 0.000                                              | 0                                       | 5845                                  | 203.000                                        | 35                                  |                                                 |                                                          |                                               | 4009                                     | 408.000                                           | 102                                    | 1412                                               | 201.000                                                     | 142                                              | 11266                  | 811.000                         | 72                   | 1                             | 9                        | 
| 2013     | NYC EITC    | New York City - Bronx | Bronx  | $36,001 - $40,000     | d/, a/ |                                           |                                                    | 1                                       |                                       |                                                | 15                                  |                                                 |                                                          |                                               | 3250                                     | 201.000                                           | 62                                     | 1130                                               | 116.000                                                     | 103                                              | 6754                   | 353.000                         | 52                   | 1                             | 10                       | 
```