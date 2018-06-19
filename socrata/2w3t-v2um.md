# Performance Metrics - Housing & Economic Development - Small Business Improvement Fund (SBIF)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-housing-economic-development-small-business-improvement-fund-sbif-997c4) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/2w3t-v2um) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/2w3t-v2um/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/2w3t-v2um/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 2w3t-v2um |
| Name | Performance Metrics - Housing & Economic Development - Small Business Improvement Fund (SBIF) |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, business, sbif |
| Created | 2011-11-25T18:23:16Z |
| Publication Date | 2015-05-08T14:14:47Z |

## Description

The Small Business Improvement Fund (SBIF) program uses Tax Increment Financing (TIF) revenues to help owners of commercial and industrial properties within specific TIF districts to repair or remodel their facilities for their own business or on behalf of tenants. Spending is counted in the month in which the project was completed.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       |                | month               | Month               | text      | text        |
| No       |                | year                | Year                | number    | text        |
| Yes      | numeric metric | grant_amount        | Grant Amount        | money     | money       |
| Yes      | numeric metric | leveraged_resources | Leveraged Resources | money     | money       |
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
series e:2w3t-v2um d:2011-01-01T00:00:00.000Z m:grant_amount=446992.74 m:leveraged_resources=301234.12

series e:2w3t-v2um d:2011-02-01T00:00:00.000Z m:grant_amount=550624.85 m:leveraged_resources=558775.1

series e:2w3t-v2um d:2011-03-01T00:00:00.000Z m:grant_amount=2479399.55 m:leveraged_resources=2964604.2
```

## Meta Commands

```ls
metric m:grant_amount p:double l:"Grant Amount" t:dataTypeName=money

metric m:leveraged_resources p:double l:"Leveraged Resources" t:dataTypeName=money

entity e:2w3t-v2um l:"Performance Metrics - Housing & Economic Development - Small Business Improvement Fund (SBIF)" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/2w3t-v2um

property e:2w3t-v2um t:meta.view v:id=2w3t-v2um v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Performance Metrics - Housing & Economic Development - Small Business Improvement Fund (SBIF)" v:attribution="City of Chicago"

property e:2w3t-v2um t:meta.view.owner v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve

property e:2w3t-v2um t:meta.view.tableauthor v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve
```

## Top Records

```ls
| month     | year | grant_amount | leveraged_resources | 
| ========= | ==== | ============ | =================== | 
| January   | 2011 | 446992.74    | 301234.12           | 
| February  | 2011 | 550624.85    | 558775.10           | 
| March     | 2011 | 2479399.55   | 2964604.20          | 
| April     | 2011 | 283541.81    | 436046.92           | 
| May       | 2011 | 940904.74    | 1555789.72          | 
| June      | 2011 | 1176055.40   | 2008563.03          | 
| July      | 2011 | 778379.19    | 499254.31           | 
| August    | 2011 | 644623.67    | 1264033.48          | 
| September | 2011 | 691751.64    | 1189184.86          | 
| October   | 2011 | 1247087.81   | 702573.45           | 
```