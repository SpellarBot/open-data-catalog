# Ratio of non-state investment leveraged to MHT administered funds awarded

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ratio-of-non-state-investment-leveraged-to-mht-administered-funds-awarded) |
| Metadata | [Link](https://data.maryland.gov/api/views/u3t7-xhw7) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/u3t7-xhw7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/u3t7-xhw7/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | u3t7-xhw7 |
| Name | Ratio of non-state investment leveraged to MHT administered funds awarded |
| Category | Business and Economy |
| Tags | mhaa, mht maryland historical trust, maryland heritage areas authority, tax credit, sustainable communities, rehabilitation |
| Created | 2016-07-15T20:14:06Z |
| Publication Date | 2016-10-19T20:06:32Z |

## Description

This data shows how much private investment is generated with awards of state funds.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                 | Name                                                                                       | Data Type     | Render Type   |
| ======== | ============== | ========================================================================================== | ========================================================================================== | ============= | ============= |
| Yes      | time           | date                                                                                       | Date                                                                                       | calendar_date | calendar_date |
| No       |                | year                                                                                       | Fiscal Year                                                                                | number        | text          |
| Yes      | numeric metric | ratio_of_non_state_investment_leveraged_to_maryland_heritage_areas_authority_funds_awarded | Ratio of non-state investment leveraged to Maryland Heritage Areas Authority funds awarded | number        | number        |
| Yes      | numeric metric | ratio_of_non_state_commercial_investmetn_leveraged_to_tax_credit_funds_awarded             | Ratio of non-state commercial investment leveraged to Tax Credit funds awarded             | number        | number        |
| Yes      | numeric metric | ratio_or_non_state_residential_investment_leveraged_to_tax_credit_funds_awarded            | Ratio or non-state residential investment leveraged to Tax Credit funds awarded            | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:u3t7-xhw7 d:2011-06-30T00:00:00.000Z m:ratio_of_non_state_investment_leveraged_to_maryland_heritage_areas_authority_funds_awarded=3.2 m:ratio_or_non_state_residential_investment_leveraged_to_tax_credit_funds_awarded=4 m:ratio_of_non_state_commercial_investmetn_leveraged_to_tax_credit_funds_awarded=7

series e:u3t7-xhw7 d:2012-06-30T00:00:00.000Z m:ratio_of_non_state_investment_leveraged_to_maryland_heritage_areas_authority_funds_awarded=1.8 m:ratio_or_non_state_residential_investment_leveraged_to_tax_credit_funds_awarded=4 m:ratio_of_non_state_commercial_investmetn_leveraged_to_tax_credit_funds_awarded=9

series e:u3t7-xhw7 d:2013-06-30T00:00:00.000Z m:ratio_of_non_state_investment_leveraged_to_maryland_heritage_areas_authority_funds_awarded=3.5 m:ratio_or_non_state_residential_investment_leveraged_to_tax_credit_funds_awarded=4 m:ratio_of_non_state_commercial_investmetn_leveraged_to_tax_credit_funds_awarded=5
```

## Meta Commands

```ls
metric m:ratio_of_non_state_investment_leveraged_to_maryland_heritage_areas_authority_funds_awarded p:float l:"Ratio of non-state investment leveraged to Maryland Heritage Areas Authority funds awarded" d:"Ratio of Leverage (Number of private dollars spent for each dollar spent by the state)" t:dataTypeName=number

metric m:ratio_of_non_state_commercial_investmetn_leveraged_to_tax_credit_funds_awarded p:double l:"Ratio of non-state commercial investment leveraged to Tax Credit funds awarded" d:"Ratio of Leveraged Funds (Number of private dollars spent on commercial projects for dollar of tax credit)" t:dataTypeName=number

metric m:ratio_or_non_state_residential_investment_leveraged_to_tax_credit_funds_awarded p:integer l:"Ratio or non-state residential investment leveraged to Tax Credit funds awarded" d:"Ratio of Leveraged Funds (Number of private dollars spent on residential projects for each dollar of tax credit)" t:dataTypeName=number

entity e:u3t7-xhw7 l:"Ratio of non-state investment leveraged to MHT administered funds awarded" t:url=https://data.maryland.gov/api/views/u3t7-xhw7

property e:u3t7-xhw7 t:meta.view v:id=u3t7-xhw7 v:category="Business and Economy" v:averageRating=0 v:name="Ratio of non-state investment leveraged to MHT administered funds awarded"

property e:u3t7-xhw7 t:meta.view.license v:name="Public Domain"

property e:u3t7-xhw7 t:meta.view.owner v:id=s6e2-jayj v:screenName="Rob McCord" v:displayName="Rob McCord"

property e:u3t7-xhw7 t:meta.view.tableauthor v:id=s6e2-jayj v:screenName="Rob McCord" v:roleName=editor v:displayName="Rob McCord"
```

## Top Records

```ls
| date                | year | ratio_of_non_state_investment_leveraged_to_maryland_heritage_areas_authority_funds_awarded | ratio_of_non_state_commercial_investmetn_leveraged_to_tax_credit_funds_awarded | ratio_or_non_state_residential_investment_leveraged_to_tax_credit_funds_awarded | 
| =================== | ==== | ========================================================================================== | ============================================================================== | =============================================================================== | 
|                     |      |                                                                                            |                                                                                |                                                                                 | 
| 2011-06-30T00:00:00 | 2011 | 3.2                                                                                        | 7                                                                              | 4                                                                               | 
| 2012-06-30T00:00:00 | 2012 | 1.8                                                                                        | 9                                                                              | 4                                                                               | 
| 2013-06-30T00:00:00 | 2013 | 3.5                                                                                        | 5                                                                              | 4                                                                               | 
| 2014-06-30T00:00:00 | 2014 | 4.3                                                                                        | 12                                                                             | 4                                                                               | 
| 2015-06-30T00:00:00 | 2015 | 5.3                                                                                        | 7.5                                                                            | 4                                                                               | 
| 2016-06-30T00:00:00 | 2016 | 6.4                                                                                        | 4                                                                              | 4                                                                               | 
```