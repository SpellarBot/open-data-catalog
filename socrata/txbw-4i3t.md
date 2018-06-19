# Real Property Tax Credit (Circuit Breaker): Beginning Tax Year 1992

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/real-property-tax-credit-circuit-breaker-beginning-tax-year-1992) |
| Metadata | [Link](https://data.ny.gov/api/views/txbw-4i3t) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/txbw-4i3t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/txbw-4i3t/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | txbw-4i3t |
| Name | Real Property Tax Credit (Circuit Breaker): Beginning Tax Year 1992 |
| Attribution | New York State Department of Taxation and Finance |
| Category | Government & Finance |
| Tags | real property, circuit breaker, county, tax credit |
| Created | 2015-01-12T19:32:46Z |
| Publication Date | 2017-03-01T23:03:31Z |

## Description

The Department of Taxation and Finance annually publishes statistical information on the New York State real property tax credit (RPTC).  Summary data are presented for taxpayers who were full-year New York state residents.  Taxpayers may claim the credit even if they had no New York State personal income tax liability and, therefore, were not required to file an income tax return.   Data are shown for the total number of claimants and credit claimed by county, age under and over 65, type of residence, filing category, and household gross income.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type | Render Type |
| ======== | ============== | ================================ | ================================ | ========= | =========== |
| Yes      | time           | tax_year                         | Tax Year                         | number    | number      |
| Yes      | series tag     | credit_type                      | Credit Type                      | text      | text        |
| Yes      | series tag     | place_of_residence               | Place of Residence               | text      | text        |
| Yes      | series tag     | county                           | County                           | text      | text        |
| Yes      | series tag     | item                             | Item                             | text      | text        |
| Yes      | series tag     | notes                            | Notes                            | text      | text        |
| Yes      | numeric metric | number_of_credits                | Number of Credits                | number    | number      |
| Yes      | numeric metric | amount_of_credits_000            | Amount of Credits ($000)         | number    | number      |
| Yes      | numeric metric | average_credit                   | Average Credit                   | number    | number      |
| Yes      | numeric metric | place_of_residence_sort_order    | Place of Residence Sort Order    | number    | number      |
| Yes      | numeric metric | item_sort_order                  | Item Sort Order                  | number    | number      |
| Yes      | numeric metric | age_sort_order                   | Age Sort Order                   | number    | number      |
| Yes      | numeric metric | houshold_gross_income_sort_order | Houshold Gross Income Sort Order | number    | number      |
```

## Time Field

```ls
Value = tax_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:txbw-4i3t d:2013-01-01T00:00:00.000Z t:place_of_residence="New York City - Bronx" t:county=Bronx t:item=Total t:credit_type="NYS RPTC" m:houshold_gross_income_sort_order=7 m:item_sort_order=1 m:average_credit=112.27 m:age_sort_order=2 m:amount_of_credits_000=3684 m:place_of_residence_sort_order=1 m:number_of_credits=32810

series e:txbw-4i3t d:2013-01-01T00:00:00.000Z t:place_of_residence="New York City - Bronx" t:county=Bronx t:item="Age: Under 65" t:credit_type="NYS RPTC" m:houshold_gross_income_sort_order=7 m:item_sort_order=2 m:average_credit=56.28 m:age_sort_order=1 m:amount_of_credits_000=1180 m:place_of_residence_sort_order=1 m:number_of_credits=20966

series e:txbw-4i3t d:2013-01-01T00:00:00.000Z t:place_of_residence="New York City - Bronx" t:county=Bronx t:item="Age: 65 and over" t:credit_type="NYS RPTC" m:houshold_gross_income_sort_order=7 m:item_sort_order=2 m:average_credit=211.38 m:age_sort_order=2 m:amount_of_credits_000=2504 m:place_of_residence_sort_order=1 m:number_of_credits=11844
```

## Meta Commands

```ls
metric m:number_of_credits p:integer l:"Number of Credits" d:"Count of the number of credit claims" t:dataTypeName=number

metric m:amount_of_credits_000 p:double l:"Amount of Credits ($000)" d:"Amount of credit claimed, in thousands of dollars" t:dataTypeName=number

metric m:average_credit p:double l:"Average Credit" d:"Average credit" t:dataTypeName=number

metric m:place_of_residence_sort_order p:integer l:"Place of Residence Sort Order" d:"Sort order on Place of Residence" t:dataTypeName=number

metric m:item_sort_order p:integer l:"Item Sort Order" d:"Sort order on Item" t:dataTypeName=number

metric m:age_sort_order p:integer l:"Age Sort Order" d:"Sort order on Age" t:dataTypeName=number

metric m:houshold_gross_income_sort_order p:integer l:"Houshold Gross Income Sort Order" d:"Sort order on Household Gross Income" t:dataTypeName=number

entity e:txbw-4i3t l:"Real Property Tax Credit (Circuit Breaker): Beginning Tax Year 1992" t:attribution="New York State Department of Taxation and Finance" t:url=https://data.ny.gov/api/views/txbw-4i3t

property e:txbw-4i3t t:meta.view v:id=txbw-4i3t v:category="Government & Finance" v:attributionLink=http://www.tax.ny.gov/research/stats/stat_pit/real_property_circuit_breaker_tax_credit.htm v:averageRating=0 v:name="Real Property Tax Credit (Circuit Breaker): Beginning Tax Year 1992" v:attribution="New York State Department of Taxation and Finance"

property e:txbw-4i3t t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:txbw-4i3t t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| tax_year | credit_type | place_of_residence    | county | item                                    | notes | number_of_credits | amount_of_credits_000 | average_credit | place_of_residence_sort_order | item_sort_order | age_sort_order | houshold_gross_income_sort_order | 
| ======== | =========== | ===================== | ====== | ======================================= | ===== | ================= | ===================== | ============== | ============================= | =============== | ============== | ================================ | 
| 2013     | NYS RPTC    | New York City - Bronx | Bronx  | Total                                   |       | 32810             | 3684                  | 112.27         | 1                             | 1               | 2              | 7                                | 
| 2013     | NYS RPTC    | New York City - Bronx | Bronx  | Age: Under 65                           |       | 20966             | 1180                  | 56.28          | 1                             | 2               | 1              | 7                                | 
| 2013     | NYS RPTC    | New York City - Bronx | Bronx  | Age: 65 and over                        |       | 11844             | 2504                  | 211.38         | 1                             | 2               | 2              | 7                                | 
| 2013     | NYS RPTC    | New York City - Bronx | Bronx  | Type of Residence: Homeowner            |       | 150               | 18                    | 119.22         | 1                             | 3               | 2              | 7                                | 
| 2013     | NYS RPTC    | New York City - Bronx | Bronx  | Type of Residence: Renter               |       | 32660             | 3666                  | 112.24         | 1                             | 3               | 2              | 7                                | 
| 2013     | NYS RPTC    | New York City - Bronx | Bronx  | Filing Category: IT-214 with Return     |       | 28695             | 2992                  | 104.28         | 1                             | 4               | 2              | 7                                | 
| 2013     | NYS RPTC    | New York City - Bronx | Bronx  | Filing Category: IT-214 Alone           |       | 4115              | 691                   | 167.95         | 1                             | 4               | 2              | 7                                | 
| 2013     | NYS RPTC    | New York City - Bronx | Bronx  | Household Gross Income: $0 - $3,000     |       | 2966              | 325                   | 109.42         | 1                             | 5               | 2              | 1                                | 
| 2013     | NYS RPTC    | New York City - Bronx | Bronx  | Household Gross Income: $3,001 - $5,000 |       | 2646              | 335                   | 126.54         | 1                             | 5               | 2              | 2                                | 
| 2013     | NYS RPTC    | New York City - Bronx | Bronx  | Household Gross Income: $5,001 - $7,000 |       | 4711              | 724                   | 153.71         | 1                             | 5               | 2              | 3                                | 
```