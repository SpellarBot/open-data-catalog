# Personal Income and Per Capita Personal Income by Quarter in Iowa

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/personal-income-and-per-capita-personal-income-by-quarter-in-iowa) |
| Metadata | [Link](https://data.iowa.gov/api/views/vm3e-atwp) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/vm3e-atwp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/vm3e-atwp/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | vm3e-atwp |
| Name | Personal Income and Per Capita Personal Income by Quarter in Iowa |
| Attribution | U.S. Department of Commerce, Bureau of Economic Analysis, Personal Income, Population, Per Capita Personal Income (SQ1) |
| Category | Economy |
| Tags | personal income, per capita personal income |
| Created | 2016-03-10T15:51:43Z |
| Publication Date | 2016-12-01T20:24:51Z |

## Description

This dataset provides personal income estimates and per capita personal income estimates for the State of Iowa by calendar quarter.  Estimates for personal income available starting in 1948.  Estimates for per capita personal income available starting in 2010.  Thousands of dollars, seasonally adjusted at annual rates.  All dollar estimates are in current dollars (not adjusted for inflation).

Personal income consists of the income that persons receive in return for their provision of labor, land, and capital used in current production as well as other income, such as personal current transfer receipts. In the state and local personal income accounts the personal income of an area represents the income received by or on behalf of the persons residing in that area. It is calculated as the sum of wages and salaries, supplements to wages and salaries, proprietors' income with inventory valuation (IVA) and capital consumption adjustments (CCAdj), rental income of persons with capital consumption adjustment (CCAdj), personal dividend income, personal interest income, and personal current transfer receipts, less contributions for government social insurance plus the adjustment for residence.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                                    | Data Type     | Render Type   |
| ======== | ============== | ================================== | ======================================= | ============= | ============= |
| Yes      | time           | quarter_ending                     | Date Quarter Ending                     | calendar_date | calendar_date |
| Yes      | numeric metric | personal_income_dollars            | Personal Income (Thosands of Dollars)   | money         | money         |
| Yes      | numeric metric | population_midperiod_persons       | Quarterly Population Estimate (Persons) | number        | number        |
| Yes      | numeric metric | per_capita_personal_income_dollars | Per Capita Personal Income              | money         | money         |
```

## Time Field

```ls
Value = quarter_ending
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:vm3e-atwp d:1948-03-31T00:00:00.000Z m:personal_income_dollars=3900001

series e:vm3e-atwp d:1948-06-30T00:00:00.000Z m:personal_income_dollars=4202717

series e:vm3e-atwp d:1948-09-30T00:00:00.000Z m:personal_income_dollars=4259245
```

## Meta Commands

```ls
metric m:personal_income_dollars p:integer l:"Personal Income (Thosands of Dollars)" d:"Personal income consists of the income that persons receive in return for their provision of labor, land, and capital used in current production as well as other income, such as personal current transfer receipts. In the state and local personal income accounts the personal income of an area represents the income received by or on behalf of the persons residing in that area. It is calculated as the sum of wages and salaries, supplements to wages and salaries, proprietors' income with inventory valuation (IVA) and capital consumption adjustments (CCAdj), rental income of persons with capital consumption adjustment (CCAdj), personal dividend income, personal interest income, and personal current transfer receipts, less contributions for government social insurance plus the adjustment for residence. Personal income estimates in thousands of dollars. Estimates are seasonally adjusted at annual rates. All dollar estimates are in current dollars (not adjusted for inflation)." t:dataTypeName=money

metric m:population_midperiod_persons p:integer l:"Quarterly Population Estimate (Persons)" d:"Midquarter population estimates by state are derived by BEA based on unpublished Census Bureau estimates of beginning-of-month population. (NA) or null - Data not available for the quarter. This statistic not available until 2010." t:dataTypeName=number

metric m:per_capita_personal_income_dollars p:integer l:"Per Capita Personal Income" d:"Per capita personal income is total personal income divided by total quarterly population estimates. (NA) or null - Data not available for the quarter. This statistic not available until 2010." t:dataTypeName=money

entity e:vm3e-atwp l:"Personal Income and Per Capita Personal Income by Quarter in Iowa" t:attribution="U.S. Department of Commerce, Bureau of Economic Analysis, Personal Income, Population, Per Capita Personal Income (SQ1)" t:url=https://data.iowa.gov/api/views/vm3e-atwp

property e:vm3e-atwp t:meta.view v:id=vm3e-atwp v:category=Economy v:attributionLink=http://www.bea.gov/itable/index.cfm v:averageRating=0 v:name="Personal Income and Per Capita Personal Income by Quarter in Iowa" v:attribution="U.S. Department of Commerce, Bureau of Economic Analysis, Personal Income, Population, Per Capita Personal Income (SQ1)"

property e:vm3e-atwp t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:vm3e-atwp t:meta.view.owner v:id=hqmd-ehvn v:profileImageUrlMedium=/api/users/hqmd-ehvn/profile_images/THUMB v:profileImageUrlLarge=/api/users/hqmd-ehvn/profile_images/LARGE v:screenName="State Data Administrator" v:profileImageUrlSmall=/api/users/hqmd-ehvn/profile_images/TINY v:lastNotificationSeenAt=1492549701 v:displayName="State Data Administrator"

property e:vm3e-atwp t:meta.view.tableauthor v:id=hqmd-ehvn v:profileImageUrlMedium=/api/users/hqmd-ehvn/profile_images/THUMB v:profileImageUrlLarge=/api/users/hqmd-ehvn/profile_images/LARGE v:screenName="State Data Administrator" v:profileImageUrlSmall=/api/users/hqmd-ehvn/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492549701 v:displayName="State Data Administrator"
```

## Top Records

```ls
| quarter_ending      | personal_income_dollars | population_midperiod_persons | per_capita_personal_income_dollars | 
| =================== | ======================= | ============================ | ================================== | 
| 1948-03-31T00:00:00 | 3900001                 |                              |                                    | 
| 1948-06-30T00:00:00 | 4202717                 |                              |                                    | 
| 1948-09-30T00:00:00 | 4259245                 |                              |                                    | 
| 1948-12-31T00:00:00 | 4130305                 |                              |                                    | 
| 1949-03-31T00:00:00 | 3680193                 |                              |                                    | 
| 1949-06-30T00:00:00 | 3489609                 |                              |                                    | 
| 1949-09-30T00:00:00 | 3393377                 |                              |                                    | 
| 1949-12-31T00:00:00 | 3472769                 |                              |                                    | 
| 1950-03-31T00:00:00 | 3779225                 |                              |                                    | 
| 1950-06-30T00:00:00 | 3925085                 |                              |                                    | 
```