# New York State Corporate Tax Credit Utilization: Beginning Tax Year 2001

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-corporate-tax-credit-utilization-beginning-tax-year-2001) |
| Metadata | [Link](https://data.ny.gov/api/views/6axi-iwd2) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/6axi-iwd2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/6axi-iwd2/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 6axi-iwd2 |
| Name | New York State Corporate Tax Credit Utilization: Beginning Tax Year 2001 |
| Attribution | New York State Department of Taxation and Finance |
| Category | Government & Finance |
| Tags | credits, article 9?a, general business corporation franchise tax credits |
| Created | 2016-04-06T20:24:22Z |
| Publication Date | 2016-10-14T22:01:24Z |

## Description

The Department of Taxation and Finance annually produces a mandated dataset of credit activity under the General Business Corporation Franchise Tax (Article 9?A) to help analyze the effects of the claims. 
The data used to generate this report come from an annual study file based on the latest available data drawn from New York State corporation tax returns.  The totals in the summary datasets may not match the detail datasets due to rounding and disclosure requirements.  The totals in the summary datasets may not match the detail data due to rounding and disclosure requirements.  Total values for numbers of taxpayers and amount of credit, in addition to mean and median credit, were computed using all taxpayers in the study file.

A series of datasets presents profiles of the credits distributed by different subgroupings. These include:
?	Summarization of tax credit activity by credit and component
?	Summarization of tax credit activity by credit, component and basis of taxation.
?	Summarization of tax credit activity by credit, component and NAICS industry description.  
?	Summarization of tax credit activity by credit, component and the size of the credit used.  
?	Summarization of tax credit activity by credit, component and the size of the entire net income of the taxpayer.  

Secrecy provisions preclude providing all subgroupings for all credits and also generally require the omission of credit refund data.  These datasets only contains data for corporate franchise taxpayers filing under Article 9-A. It does not include statistics for taxpayers filing as banks under Article 32 (however, starting in 2015 banks and general business corporations will file under the same tax article, Article 9A), insurance companies filing under Article 33, or taxpayers filing under any of the various sections of Article 9. Nor does it provide data for taxpayers claiming credits under Article 22, the Personal Income Tax.  These taxpayers claim credit by virtue of being sole proprietors or as recipients of credit that originated with flow-through entities (i.e., S corporations, limited liability companies, or partnerships).

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | time           | tax_year               | Tax Year               | number    | number      |
| Yes      | series tag     | tax_article            | Tax Article            | text      | text        |
| Yes      | series tag     | credit_type            | Credit Type            | text      | text        |
| Yes      | series tag     | credit_name            | Credit Name            | text      | text        |
| Yes      | series tag     | notes                  | Notes                  | text      | text        |
| Yes      | numeric metric | number_of_taxpayers    | Number of Taxpayers    | number    | number      |
| Yes      | numeric metric | amount_of_credit       | Amount of Credit       | number    | number      |
| Yes      | numeric metric | credit_type_sort_order | Credit Type Sort Order | number    | number      |
```

## Time Field

```ls
Value = tax_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6axi-iwd2 d:2010-01-01T00:00:00.000Z t:credit_name="Alternative Fuels Credit" t:credit_type="Credits Earned" t:tax_article=9A m:credit_type_sort_order=1 m:number_of_taxpayers=3 m:amount_of_credit=1762730

series e:6axi-iwd2 d:2010-01-01T00:00:00.000Z t:credit_name="Alternative Minimum Tax Credit" t:credit_type="Credits Earned" t:tax_article=9A m:credit_type_sort_order=1 m:number_of_taxpayers=1663 m:amount_of_credit=2137046

series e:6axi-iwd2 d:2010-01-01T00:00:00.000Z t:credit_name="Biofuel Production Credit" t:credit_type="Credits Earned" t:notes=d/ t:tax_article=9A m:credit_type_sort_order=1
```

## Meta Commands

```ls
metric m:number_of_taxpayers p:integer l:"Number of Taxpayers" d:"Number of taxpayers taking the credit." t:dataTypeName=number

metric m:amount_of_credit p:integer l:"Amount of Credit" d:"The amount of the credit generated, claimed, used, refunded, or carried forward in the tax year based on the credit type." t:dataTypeName=number

metric m:credit_type_sort_order p:integer l:"Credit Type Sort Order" d:"Indicator to sort the credit type." t:dataTypeName=number

entity e:6axi-iwd2 l:"New York State Corporate Tax Credit Utilization: Beginning Tax Year 2001" t:attribution="New York State Department of Taxation and Finance" t:url=https://data.ny.gov/api/views/6axi-iwd2

property e:6axi-iwd2 t:meta.view v:id=6axi-iwd2 v:category="Government & Finance" v:attributionLink=https://www.tax.ny.gov/research/stats/stat_corp/9a_tax_credits/article_9a_general_business_corporation_franchise_tax_credits_through_tax_year_2012.htm v:averageRating=0 v:name="New York State Corporate Tax Credit Utilization: Beginning Tax Year 2001" v:attribution="New York State Department of Taxation and Finance"

property e:6axi-iwd2 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:6axi-iwd2 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| tax_year | tax_article | credit_type    | credit_name                                                             | notes | number_of_taxpayers | amount_of_credit | credit_type_sort_order | 
| ======== | =========== | ============== | ======================================================================= | ===== | =================== | ================ | ====================== | 
| 2010     | 9A          | Credits Earned | Alternative Fuels Credit                                                |       | 3                   | 1762730          | 1                      | 
| 2010     | 9A          | Credits Earned | Alternative Minimum Tax Credit                                          |       | 1663                | 2137046          | 1                      | 
| 2010     | 9A          | Credits Earned | Biofuel Production Credit                                               | d/    |                     |                  | 1                      | 
| 2010     | 9A          | Credits Earned | Brownfield Tax Credits - Environmental Remediation Insurance Tax Credit |       | 0                   | 0                | 1                      | 
| 2010     | 9A          | Credits Earned | Brownfield Tax Credits - Redevelopment Tax Credit                       | 2/    | 15                  | 171556660        | 1                      | 
| 2010     | 9A          | Credits Earned | Brownfield Tax Credits - Remediation Real Property Tax Credit           |       | 4                   | 2775012          | 1                      | 
| 2010     | 9A          | Credits Earned | Clean Heating Fuel Credit                                               |       | 9                   | 18351            | 1                      | 
| 2010     | 9A          | Credits Earned | Conservation Easement Tax Credit                                        |       | 6                   | 51005            | 1                      | 
| 2010     | 9A          | Credits Earned | Credit for Employment of Persons with Disabilities                      |       | 9                   | 51569            | 1                      | 
| 2010     | 9A          | Credits Earned | Credit for Purchase of an Automated External Defibrillator              |       | 10                  | 32506            | 1                      | 
```