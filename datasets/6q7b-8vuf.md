# Earned Income Tax Credit (EITC) Claims by Credit Type and Place of Residence: Beginning Tax Year 1994

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/earned-income-tax-credit-eitc-claims-by-credit-type-and-place-of-residence-beginning-tax-y) |
| Metadata | [Link](https://data.ny.gov/api/views/6q7b-8vuf) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/6q7b-8vuf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/6q7b-8vuf/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 6q7b-8vuf |
| Name | Earned Income Tax Credit (EITC) Claims by Credit Type and Place of Residence: Beginning Tax Year 1994 |
| Attribution | New York State Department of Taxation and Finance |
| Category | Government & Finance |
| Tags | eitc, earned income, non-custodial parent, credit, tax |
| Created | 2015-10-06T18:46:15Z |
| Publication Date | 2017-04-20T22:00:25Z |

## Description

The Department of Taxation and Finance (the Department) annually publishes statistical information on the New York State earned income tax credit (EITC). This includes data on the separate New York City EITC and the New York State noncustodial parent EITC. Summary data are presented for all taxpayers which includes full-year New York state residents, part-year residents and nonresidents (where applicable). Data are shown for the total number of claimants and credit claimed by county and/or region for all filing statuses.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                          | Data Type | Render Type |
| ======== | ============== | ================================== | ============================= | ========= | =========== |
| Yes      | time           | tax_year                           | Tax Year                      | number    | number      |
| Yes      | series tag     | credit_type                        | Credit Type                   | text      | text        |
| Yes      | series tag     | place_of_residence                 | Place of Residence            | text      | text        |
| Yes      | series tag     | county                             | County                        | text      | text        |
| Yes      | series tag     | notes                              | Notes                         | text      | text        |
| Yes      | numeric metric | number_of_claims                   | Number of Claims              | number    | number      |
| Yes      | numeric metric | credit_amount_claimed_in_thousands | Credit Amount Claimed ($000)  | number    | number      |
| Yes      | numeric metric | average_credit                     | Average Credit                | number    | number      |
| Yes      | numeric metric | place_of_residence_sort_order      | Place of Residence Sort Order | number    | number      |
```

## Time Field

```ls
Value = tax_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6q7b-8vuf d:2011-01-01T00:00:00.000Z t:place_of_residence="New York City - Bronx" t:county=Bronx t:credit_type="NYC EITC" m:average_credit=117 m:number_of_claims=196819 m:place_of_residence_sort_order=1 m:credit_amount_claimed_in_thousands=23017

series e:6q7b-8vuf d:2011-01-01T00:00:00.000Z t:place_of_residence="New York City - Kings" t:county=Kings t:credit_type="NYC EITC" m:average_credit=112 m:number_of_claims=299352 m:place_of_residence_sort_order=2 m:credit_amount_claimed_in_thousands=33660

series e:6q7b-8vuf d:2011-01-01T00:00:00.000Z t:place_of_residence="New York City - Manhattan" t:county=Manhattan t:credit_type="NYC EITC" m:average_credit=92 m:number_of_claims=121282 m:place_of_residence_sort_order=3 m:credit_amount_claimed_in_thousands=11179
```

## Meta Commands

```ls
metric m:number_of_claims p:long l:"Number of Claims" d:"Count of the number of EITC claims" t:dataTypeName=number

metric m:credit_amount_claimed_in_thousands p:long l:"Credit Amount Claimed ($000)" d:"Amount of EITC claimed, in thousands of dollars" t:dataTypeName=number

metric m:average_credit p:long l:"Average Credit" d:"Average amount of EITC claimed" t:dataTypeName=number

metric m:place_of_residence_sort_order p:long l:"Place of Residence Sort Order" d:"Sort order on Place of Residence" t:dataTypeName=number

entity e:6q7b-8vuf l:"Earned Income Tax Credit (EITC) Claims by Credit Type and Place of Residence: Beginning Tax Year 1994" t:attribution="New York State Department of Taxation and Finance" t:url=https://data.ny.gov/api/views/6q7b-8vuf

property e:6q7b-8vuf t:meta.view v:id=6q7b-8vuf v:category="Government & Finance" v:attributionLink=https://www.tax.ny.gov/research/stats/statistics/personal_income_tax_statistical_reports.htm v:averageRating=0 v:name="Earned Income Tax Credit (EITC) Claims by Credit Type and Place of Residence: Beginning Tax Year 1994" v:attribution="New York State Department of Taxation and Finance"

property e:6q7b-8vuf t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:6q7b-8vuf t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:6q7b-8vuf t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| tax_year | credit_type | place_of_residence                | county                            | notes | number_of_claims | credit_amount_claimed_in_thousands | average_credit | place_of_residence_sort_order | 
| ======== | =========== | ================================= | ================================= | ===== | ================ | ================================== | ============== | ============================= | 
| 2011     | NYC EITC    | New York City - Bronx             | Bronx                             |       | 196819           | 23017                              | 117            | 1                             | 
| 2011     | NYC EITC    | New York City - Kings             | Kings                             |       | 299352           | 33660                              | 112            | 2                             | 
| 2011     | NYC EITC    | New York City - Manhattan         | Manhattan                         |       | 121282           | 11179                              | 92             | 3                             | 
| 2011     | NYC EITC    | New York City - Queens            | Queens                            |       | 244512           | 24806                              | 101            | 4                             | 
| 2011     | NYC EITC    | New York City - Richmond          | Richmond                          |       | 29000            | 3018                               | 104            | 5                             | 
| 2011     | NYC EITC    | Total, Non-New York City Counties | Total, Non-New York City Counties |       | 9115             | 1000                               | 110            | 7                             | 
| 2011     | NYC EITC    | All Other *                       | Not Applicable                    |       | 5441             | 308                                | 57             | 9                             | 
| 2011     | NYC EITC    | Grand Total                       | Grand Total                       |       | 905521           | 96989                              | 107            | 65                            | 
| 2011     | NYS EITC    | New York City - Bronx             | Bronx                             |       | 193128           | 132961                             | 688            | 1                             | 
| 2011     | NYS EITC    | New York City - Kings             | Kings                             |       | 291362           | 194672                             | 668            | 2                             | 
```