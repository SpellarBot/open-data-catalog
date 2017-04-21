# New York State Corporate Tax Credits by Major Industry Group: Beginning Tax Year 2001

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-corporate-tax-credits-by-major-industry-group-beginning-tax-year-2001) |
| Metadata | [Link](https://data.ny.gov/api/views/84qh-f5nv) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/84qh-f5nv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/84qh-f5nv/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 84qh-f5nv |
| Name | New York State Corporate Tax Credits by Major Industry Group: Beginning Tax Year 2001 |
| Attribution | New York State Department of Taxation and Finance |
| Category | Government & Finance |
| Tags | credits, article 9?a, general business corporation franchise tax credits |
| Created | 2016-04-06T21:43:17Z |
| Publication Date | 2016-10-14T22:09:39Z |

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
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | time           | tax_year                | Tax Year                | number    | number      |
| Yes      | series tag     | tax_article             | Tax Article             | text      | text        |
| Yes      | series tag     | credit_type             | Credit Type             | text      | text        |
| Yes      | series tag     | credit_name             | Credit Name             | text      | text        |
| Yes      | series tag     | naics_description       | NAICS Description       | text      | text        |
| Yes      | series tag     | notes                   | Notes                   | text      | text        |
| Yes      | numeric metric | number_of_taxpayers     | Number of Taxpayers     | number    | number      |
| Yes      | numeric metric | amount_of_credit        | Amount of Credit        | number    | number      |
| Yes      | numeric metric | percent_of_credit       | Percent of Credit       | percent   | percent     |
| Yes      | numeric metric | median_amount_of_credit | Median Amount of Credit | number    | number      |
| Yes      | numeric metric | mean_amount_of_credit   | Mean Amount of Credit   | number    | number      |
| Yes      | numeric metric | group_sort_order        | Group Sort Order        | number    | number      |
| Yes      | numeric metric | credit_type_sort_order  | Credit Type Sort Order  | number    | number      |
```

## Time Field

```ls
Value = tax_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:84qh-f5nv d:2010-01-01T00:00:00.000Z t:credit_name="Alternative Minimum Tax Credit" t:naics_description="Agriculture, Forestry, Fishing and Hunting" t:credit_type="Credit Earned" t:tax_article=9A m:group_sort_order=11 m:median_amount_of_credit=265 m:mean_amount_of_credit=824 m:credit_type_sort_order=1 m:percent_of_credit=0.5 m:number_of_taxpayers=13 m:amount_of_credit=10715

series e:84qh-f5nv d:2010-01-01T00:00:00.000Z t:credit_name="Alternative Minimum Tax Credit" t:naics_description=Mining t:credit_type="Credit Earned" t:tax_article=9A m:group_sort_order=21 m:median_amount_of_credit=849 m:mean_amount_of_credit=1185 m:credit_type_sort_order=1 m:percent_of_credit=0.22 m:number_of_taxpayers=4 m:amount_of_credit=4740

series e:84qh-f5nv d:2010-01-01T00:00:00.000Z t:credit_name="Alternative Minimum Tax Credit" t:naics_description=Utilities t:credit_type="Credit Earned" t:tax_article=9A m:group_sort_order=22 m:median_amount_of_credit=1899 m:mean_amount_of_credit=3189 m:credit_type_sort_order=1 m:percent_of_credit=0.9 m:number_of_taxpayers=6 m:amount_of_credit=19134
```

## Meta Commands

```ls
metric m:number_of_taxpayers p:integer l:"Number of Taxpayers" d:"Number of taxpayers taking the credit." t:dataTypeName=number

metric m:amount_of_credit p:integer l:"Amount of Credit" d:"The amount of the credit generated, claimed, used, refunded, or carried forward in the tax year based on the credit type." t:dataTypeName=number

metric m:percent_of_credit p:double l:"Percent of Credit" d:"Percentage of the amount of credit by NAICS description within each credit type." t:dataTypeName=percent

metric m:median_amount_of_credit p:integer l:"Median Amount of Credit" d:"The central value representing an equal number of credit values above and below it." t:dataTypeName=number

metric m:mean_amount_of_credit p:integer l:"Mean Amount of Credit" d:"Average amount of credit in a given category." t:dataTypeName=number

metric m:group_sort_order p:integer l:"Group Sort Order" d:"Indicator to sort by NAICS description." t:dataTypeName=number

metric m:credit_type_sort_order p:integer l:"Credit Type Sort Order" d:"Indicator to sort the credit type." t:dataTypeName=number

entity e:84qh-f5nv l:"New York State Corporate Tax Credits by Major Industry Group: Beginning Tax Year 2001" t:attribution="New York State Department of Taxation and Finance" t:url=https://data.ny.gov/api/views/84qh-f5nv

property e:84qh-f5nv t:meta.view v:id=84qh-f5nv v:category="Government & Finance" v:attributionLink=https://www.tax.ny.gov/research/stats/stat_corp/9a_tax_credits/article_9a_general_business_corporation_franchise_tax_credits_through_tax_year_2012.htm v:averageRating=0 v:name="New York State Corporate Tax Credits by Major Industry Group: Beginning Tax Year 2001" v:attribution="New York State Department of Taxation and Finance"

property e:84qh-f5nv t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:84qh-f5nv t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| tax_year | tax_article | credit_type   | credit_name                    | naics_description                          | notes | number_of_taxpayers | amount_of_credit | percent_of_credit | median_amount_of_credit | mean_amount_of_credit | group_sort_order | credit_type_sort_order | 
| ======== | =========== | ============= | ============================== | ========================================== | ===== | =================== | ================ | ================= | ======================= | ===================== | ================ | ====================== | 
| 2010     | 9A          | Credit Earned | Alternative Minimum Tax Credit | Agriculture, Forestry, Fishing and Hunting |       | 13                  | 10715            | 0.5               | 265                     | 824                   | 11               | 1                      | 
| 2010     | 9A          | Credit Earned | Alternative Minimum Tax Credit | Mining                                     |       | 4                   | 4740             | 0.22              | 849                     | 1185                  | 21               | 1                      | 
| 2010     | 9A          | Credit Earned | Alternative Minimum Tax Credit | Utilities                                  |       | 6                   | 19134            | 0.9               | 1899                    | 3189                  | 22               | 1                      | 
| 2010     | 9A          | Credit Earned | Alternative Minimum Tax Credit | Construction                               |       | 129                 | 54045            | 2.53              | 88                      | 419                   | 23               | 1                      | 
| 2010     | 9A          | Credit Earned | Alternative Minimum Tax Credit | Manufacturing                              |       | 95                  | 244771           | 11.45             | 174                     | 2577                  | 31               | 1                      | 
| 2010     | 9A          | Credit Earned | Alternative Minimum Tax Credit | Wholesale Trade                            |       | 129                 | 322674           | 15.1              | 90                      | 2501                  | 42               | 1                      | 
| 2010     | 9A          | Credit Earned | Alternative Minimum Tax Credit | Retail Trade                               |       | 124                 | 113023           | 5.29              | 77                      | 911                   | 44               | 1                      | 
| 2010     | 9A          | Credit Earned | Alternative Minimum Tax Credit | Transportation and Warehousing             |       | 78                  | 48872            | 2.29              | 63                      | 627                   | 48               | 1                      | 
| 2010     | 9A          | Credit Earned | Alternative Minimum Tax Credit | Information                                |       | 58                  | 146021           | 6.83              | 133                     | 2518                  | 51               | 1                      | 
| 2010     | 9A          | Credit Earned | Alternative Minimum Tax Credit | Finance and Insurance                      |       | 99                  | 681065           | 31.87             | 363                     | 6879                  | 52               | 1                      | 
```