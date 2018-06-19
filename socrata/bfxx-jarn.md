# Jackson Revenue Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/jackson-revenue-budget) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/bfxx-jarn) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/bfxx-jarn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/bfxx-jarn/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | bfxx-jarn |
| Name | Jackson Revenue Budget |
| Attribution | City of Jackson, Department of Administration |
| Category | Budget and Finance |
| Created | 2016-03-31T20:47:11Z |
| Publication Date | 2017-03-10T21:02:54Z |

## Description

This dataset shows the City of Jackson's FY2017 revenue budget, revenue collected to date, and the balance remaining to be collected. The data can be broken down by Revenue Type, Revenue Source, Fund, and Fund Type.

This data displays all general fund revenue. This data is updated the 15th day of each month. This is to provide time for close out of the previous month in all budgetary software systems.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name                         | Data Type     | Render Type   |
| ======== | ============== | ================= | ============================ | ============= | ============= |
| No       |                | fiscal_year       | Fiscal Year                  | number        | number        |
| Yes      | time           | trans_date        | Update Date                  | calendar_date | calendar_date |
| Yes      | numeric metric | fund              | Fund                         | number        | text          |
| Yes      | series tag     | fund_name         | Fund Name                    | text          | text          |
| Yes      | series tag     | fund_type         | Fund Type                    | text          | text          |
| Yes      | series tag     | revenue_type      | Revenue Type                 | text          | text          |
| Yes      | series tag     | rev_source        | Revenue Source               | text          | text          |
| Yes      | numeric metric | fy_2016_budget    | FY 2017 Budget               | money         | money         |
| Yes      | numeric metric | feb_rev_collected | Current Period Rev Collected | money         | money         |
| Yes      | numeric metric | ytd_rev_collected | YTD Rev Collected            | money         | money         |
| Yes      | numeric metric | rev_to_collect    | Rev to Collect               | money         | money         |
| Yes      | numeric metric | of_rev_collected  | % of Rev Collected           | percent       | percent       |
```

## Time Field

```ls
Value = trans_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fiscal_year
```

## Data Commands

```ls
series e:bfxx-jarn d:2017-02-01T00:00:00.000Z t:fund_name="GENERAL FUND" t:fund_type="GENERAL FUND" t:rev_source="REAL PROPERTY" t:revenue_type="GENERAL PROPERTY TAXES" m:ytd_rev_collected=7381018 m:rev_to_collect=28415558 m:fund=1 m:feb_rev_collected=7380008 m:fy_2016_budget=35796576 m:of_rev_collected=20.6

series e:bfxx-jarn d:2017-02-01T00:00:00.000Z t:fund_name="GENERAL FUND" t:fund_type="GENERAL FUND" t:rev_source="PERSONAL PROPERTY" t:revenue_type="GENERAL PROPERTY TAXES" m:ytd_rev_collected=6661573 m:rev_to_collect=7953913 m:fund=1 m:feb_rev_collected=6607139 m:fy_2016_budget=14615486 m:of_rev_collected=45.6

series e:bfxx-jarn d:2017-02-01T00:00:00.000Z t:fund_name="GENERAL FUND" t:fund_type="GENERAL FUND" t:rev_source="DELINQUENT REALTY" t:revenue_type="GENERAL PROPERTY TAXES" m:ytd_rev_collected=68487 m:rev_to_collect=931513 m:fund=1 m:feb_rev_collected=38073 m:fy_2016_budget=1000000 m:of_rev_collected=6.9
```

## Meta Commands

```ls
metric m:fund p:integer l:Fund t:dataTypeName=number

metric m:fy_2016_budget p:double l:"FY 2017 Budget" t:dataTypeName=money

metric m:feb_rev_collected p:double l:"Current Period Rev Collected" t:dataTypeName=money

metric m:ytd_rev_collected p:double l:"YTD Rev Collected" t:dataTypeName=money

metric m:rev_to_collect p:double l:"Rev to Collect" t:dataTypeName=money

metric m:of_rev_collected p:float l:"% of Rev Collected" t:dataTypeName=percent

entity e:bfxx-jarn l:"Jackson Revenue Budget" t:attribution="City of Jackson, Department of Administration" t:url=https://data.jacksonms.gov/api/views/bfxx-jarn

property e:bfxx-jarn t:meta.view v:id=bfxx-jarn v:category="Budget and Finance" v:attributionLink="http://www.jacksonms.gov/index.aspx?nid=114" v:averageRating=0 v:name="Jackson Revenue Budget" v:attribution="City of Jackson, Department of Administration"

property e:bfxx-jarn t:meta.view.owner v:id=csn7-fh8q v:screenName="Tiffanee Jones" v:displayName="Tiffanee Jones"

property e:bfxx-jarn t:meta.view.tableauthor v:id=csn7-fh8q v:screenName="Tiffanee Jones" v:roleName=publisher v:displayName="Tiffanee Jones"
```

## Top Records

```ls
| fiscal_year | trans_date          | fund | fund_name    | fund_type    | revenue_type           | rev_source               | fy_2016_budget | feb_rev_collected | ytd_rev_collected | rev_to_collect | of_rev_collected   | 
| =========== | =================== | ==== | ============ | ============ | ====================== | ======================== | ============== | ================= | ================= | ============== | ================== | 
| 2017        | 2017-02-01T00:00:00 | 1    | GENERAL FUND | GENERAL FUND | GENERAL PROPERTY TAXES | REAL PROPERTY            | 35796576.00    | 7380008.00        | 7381018.00        | 28415558.00    | 20.6               | 
| 2017        | 2017-02-01T00:00:00 | 1    | GENERAL FUND | GENERAL FUND | GENERAL PROPERTY TAXES | PERSONAL PROPERTY        | 14615486.00    | 6607139.00        | 6661573.00        | 7953913.00     | 45.6               | 
| 2017        | 2017-02-01T00:00:00 | 1    | GENERAL FUND | GENERAL FUND | GENERAL PROPERTY TAXES | DELINQUENT REALTY        | 1000000.00     | 38073.00          | 68487.00          | 931513.00      | 6.9                | 
| 2017        | 2017-02-01T00:00:00 | 1    | GENERAL FUND | GENERAL FUND | GENERAL PROPERTY TAXES | DELINQUENT PERSONAL      | 25000.00       | 945.00            | 2075.00           | 22925.00       | 8.3000000000000007 | 
| 2017        | 2017-02-01T00:00:00 | 1    | GENERAL FUND | GENERAL FUND | GENERAL PROPERTY TAXES | AUTOMOTIVE               | 6755327.00     | 574905.00         | 2157538.00        | 4597789.00     | 31.9               | 
| 2017        | 2017-02-01T00:00:00 | 1    | GENERAL FUND | GENERAL FUND | GENERAL PROPERTY TAXES | MOTOR VEHICLE RENTAL TAX | 900000.00      | 0.00              | 0.00              | 900000.00      |                    | 
| 2017        | 2017-02-01T00:00:00 | 1    | GENERAL FUND | GENERAL FUND | GENERAL PROPERTY TAXES | INTEREST ON CURRENT      | 750000.00      | 12087.00          | 21428.00          | 728572.00      | 2.9                | 
| 2017        | 2017-02-01T00:00:00 | 1    | GENERAL FUND | GENERAL FUND | GENERAL PROPERTY TAXES | INTEREST ON PRIOR YEARS  | 500000.00      | 41941.00          | 120486.00         | 379514.00      | 24.1               | 
| 2017        | 2017-02-01T00:00:00 | 1    | GENERAL FUND | GENERAL FUND | GENERAL PROPERTY TAXES | RAIL CAR TAXES           | 50000.00       | 0.00              | 0.00              | 50000.00       |                    | 
| 2017        | 2017-02-01T00:00:00 | 1    | GENERAL FUND | GENERAL FUND | GENERAL PROPERTY TAXES | MISCELLANEOUS FEES       | 125000.00      | 5940.00           | 24480.00          | 100520.00      | 19.600000000000001 | 
```