# State and Local Sales Tax Distributions: Beginning Fiscal Years Ended March 31, 1995

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-and-local-sales-tax-distributions-beginning-fiscal-year-ended-march-31-2003) |
| Metadata | [Link](https://data.ny.gov/api/views/5g2s-tnb7) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/5g2s-tnb7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/5g2s-tnb7/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 5g2s-tnb7 |
| Name | State and Local Sales Tax Distributions: Beginning Fiscal Years Ended March 31, 1995 |
| Attribution | New York State Department of Taxation and Finance |
| Category | Government & Finance |
| Tags | sales and use tax, sales tax distributions, state and local sales tax, state and local sales tax distributions |
| Created | 2013-02-15T14:49:01Z |
| Publication Date | 2016-09-27T22:00:39Z |

## Description

The Department of Taxation and Finance administers the statewide New York State general retail sales and compensating use tax, as well as any general retail sales and compensating use tax imposed by a county or municipality in New York State. In addition, the Department administers any taxes imposed on consumer utilities services and other special taxes on selected commodities and services by municipalities and city school districts. This data set presents information on the yearly amount of the distribution of these taxes back to the appropriate taxing jurisdictions from fiscal years ended March 31, 1995.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                    | Data Type | Render Type |
| ======== | ============== | =================== | ======================= | ========= | =========== |
| Yes      | time           | fiscal_year_ended   | Fiscal Year Ended       | number    | number      |
| Yes      | series tag     | taxing_jurisdiction | Taxing Jurisdiction     | text      | text        |
| Yes      | numeric metric | amount_distributed  | Amount Distributed      | money     | money       |
| Yes      | series tag     | jurisdiction_code   | Jurisdiction Sort Order | text      | number      |
```

## Time Field

```ls
Value = fiscal_year_ended
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5g2s-tnb7 d:2015-01-01T00:00:00.000Z t:jurisdiction_code=1 t:taxing_jurisdiction="New York State Sales and Use Tax" m:amount_distributed=12263327571

series e:5g2s-tnb7 d:2015-01-01T00:00:00.000Z t:jurisdiction_code=2 t:taxing_jurisdiction="New York City Sales and Use Tax" m:amount_distributed=6710667508

series e:5g2s-tnb7 d:2015-01-01T00:00:00.000Z t:jurisdiction_code=3 t:taxing_jurisdiction="Municipal Assistance Corporation Sales and Use Tax" m:amount_distributed=0
```

## Meta Commands

```ls
metric m:amount_distributed p:long l:"Amount Distributed" d:"Net amount of sales tax distributions to each taxing jurisdiction, in US dollars, during the fiscal year identified. A $0 value may indicate the city no longer imposed the tax during that period. Refer to ""Enactment and Effective Dates of Sales and Use Tax Rates ? Publication 718-A"" http://www.tax.ny.gov/pdf/publications/sales/pub718a.pdf" t:dataTypeName=money

entity e:5g2s-tnb7 l:"State and Local Sales Tax Distributions:  Beginning  Fiscal Years Ended March 31, 1995" t:attribution="New York State Department of Taxation and Finance" t:url=https://data.ny.gov/api/views/5g2s-tnb7

property e:5g2s-tnb7 t:meta.view v:id=5g2s-tnb7 v:category="Government & Finance" v:attributionLink=http://www.tax.ny.gov/research/stats/statistics/stat_fy_collections.htm v:averageRating=0 v:name="State and Local Sales Tax Distributions:  Beginning  Fiscal Years Ended March 31, 1995" v:attribution="New York State Department of Taxation and Finance"

property e:5g2s-tnb7 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:5g2s-tnb7 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:5g2s-tnb7 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| fiscal_year_ended | taxing_jurisdiction                                             | amount_distributed | jurisdiction_code | 
| ================= | =============================================================== | ================== | ================= | 
| 2015              | New York State Sales and Use Tax                                | 12263327571        | 1                 | 
| 2015              | New York City Sales and Use Tax                                 | 6710667508         | 2                 | 
| 2015              | Municipal Assistance Corporation Sales and Use Tax              | 0                  | 3                 | 
| 2015              | Metropolitan Commuter Transportation District Sales and Use Tax | 704485048          | 4                 | 
| 2015              | Albany County Sales and Use Tax                                 | 252678750          | 5                 | 
| 2015              | Allegany County Sales and Use Tax                               | 20068318           | 6                 | 
| 2015              | Broome County Sales and Use Tax                                 | 119935166          | 7                 | 
| 2015              | Cattaraugus County Sales and Use Tax                            | 36884493           | 8                 | 
| 2015              | Cayuga County Sales and Use Tax                                 | 35187385           | 9                 | 
| 2015              | Chautauqua County Sales and Use Tax                             | 55684595           | 10                | 
```