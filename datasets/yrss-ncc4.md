# Employee Compensation by Industry in Iowa

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/employee-compensation-by-industry-in-iowa) |
| Metadata | [Link](https://data.iowa.gov/api/views/yrss-ncc4) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/yrss-ncc4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/yrss-ncc4/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | yrss-ncc4 |
| Name | Employee Compensation by Industry in Iowa |
| Attribution | U.S. Department of Commerce, Bureau of Economic Analysis, Compensation of Employees by Industry (SQ6, SQ6N) |
| Category | Economy |
| Tags | employee compensation |
| Created | 2016-03-15T13:04:59Z |
| Publication Date | 2016-08-31T14:49:23Z |

## Description

This dataset contains employee compensation estimates in thousands of dollars, seasonally adjusted at annual rates.  All dollar estimates are in current dollars (not adjusted for inflation).  Compensation is the total remuneration, both monetary and in kind, payable by employers to employees in return for their work during the period. It consists of wages and salaries and of supplements to wages and salaries. Compensation is presented on an accrual basis--that is, it reflects compensation liabilities incurred by the employer in a given period regardless of when the compensation is actually received by the employee.


The estimates of compensation by industry for 1998-2006 are based on the 2002 North American Industry Classification System (NAICS). The estimates for 2007-2010 are based on the 2007 NAICS. The estimates for 2011 forward are based on the 2012 NAICS.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name                     | Data Type     | Render Type   |
| ======== | ============== | ============== | ======================== | ============= | ============= |
| Yes      | time           | quarter_ending | Date Quarter Ended       | calendar_date | calendar_date |
| Yes      | series tag     | industry_type  | Industry Type            | text          | text          |
| Yes      | series tag     | industry       | Industry                 | text          | text          |
| Yes      | numeric metric | compensation   | Compensation (Thousands) | money         | money         |
```

## Time Field

```ls
Value = quarter_ending
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:yrss-ncc4 d:1998-03-31T00:00:00.000Z t:industry_type=Farm t:industry=Farm m:compensation=351164

series e:yrss-ncc4 d:1998-03-31T00:00:00.000Z t:industry_type="Private nonfarm" t:industry="Forestry, fishing, and related activities" m:compensation=67196

series e:yrss-ncc4 d:1998-03-31T00:00:00.000Z t:industry_type="Private nonfarm" t:industry="Mining, quarrying, and oil and gas extraction" m:compensation=84408
```

## Meta Commands

```ls
metric m:compensation p:integer l:"Compensation (Thousands)" d:"Employee compensation in thousands of dollars, seasonally adjusted at annual rates. All estimates are in current dollars (not adjusted for inflation). Data reflects actual employer contributions and actuarial imputed employer contributions to reflect benefits accrued by defined benefit pension plan participants through service to employers in the current period." t:dataTypeName=money

entity e:yrss-ncc4 l:"Employee Compensation by Industry in Iowa" t:attribution="U.S. Department of Commerce, Bureau of Economic Analysis, Compensation of Employees by Industry (SQ6, SQ6N)" t:url=https://data.iowa.gov/api/views/yrss-ncc4

property e:yrss-ncc4 t:meta.view v:id=yrss-ncc4 v:category=Economy v:attributionLink=http://www.bea.gov/itable/index.cfm v:averageRating=0 v:name="Employee Compensation by Industry in Iowa" v:attribution="U.S. Department of Commerce, Bureau of Economic Analysis, Compensation of Employees by Industry (SQ6, SQ6N)"

property e:yrss-ncc4 t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:yrss-ncc4 t:meta.view.owner v:id=hqmd-ehvn v:profileImageUrlMedium=/api/users/hqmd-ehvn/profile_images/THUMB v:profileImageUrlLarge=/api/users/hqmd-ehvn/profile_images/LARGE v:screenName="State Data Administrator" v:profileImageUrlSmall=/api/users/hqmd-ehvn/profile_images/TINY v:lastNotificationSeenAt=1492549701 v:displayName="State Data Administrator"

property e:yrss-ncc4 t:meta.view.tableauthor v:id=hqmd-ehvn v:profileImageUrlMedium=/api/users/hqmd-ehvn/profile_images/THUMB v:profileImageUrlLarge=/api/users/hqmd-ehvn/profile_images/LARGE v:screenName="State Data Administrator" v:profileImageUrlSmall=/api/users/hqmd-ehvn/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492549701 v:displayName="State Data Administrator"
```

## Top Records

```ls
| quarter_ending      | industry_type   | industry                                      | compensation | 
| =================== | =============== | ============================================= | ============ | 
| 1998-03-31T00:00:00 | Farm            | Farm                                          | 351164       | 
| 1998-03-31T00:00:00 | Private nonfarm | Forestry, fishing, and related activities     | 67196        | 
| 1998-03-31T00:00:00 | Private nonfarm | Mining, quarrying, and oil and gas extraction | 84408        | 
| 1998-03-31T00:00:00 | Private nonfarm | Utilities                                     | 497512       | 
| 1998-03-31T00:00:00 | Private nonfarm | Construction                                  | 2291636      | 
| 1998-03-31T00:00:00 | Private nonfarm | Manufacturing                                 | 9963256      | 
| 1998-03-31T00:00:00 | Private nonfarm | Wholesale trade                               | 2731888      | 
| 1998-03-31T00:00:00 | Private nonfarm | Retail trade                                  | 3979696      | 
| 1998-03-31T00:00:00 | Private nonfarm | Transportation and warehousing                | 1728216      | 
| 1998-03-31T00:00:00 | Private nonfarm | Information                                   | 1249036      | 
```