# Financial Plan Expense - Qtr1

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/financial-plan-expense-qtr1) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/sqmu-2ixd) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/sqmu-2ixd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/sqmu-2ixd/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | sqmu-2ixd |
| Name | Financial Plan Expense - Qtr1 |
| Attribution | Mayor?s Office of Management & Budget (OMB) |
| Category | City Government |
| Tags | omb, management, budget, financial, plan, expense |
| Created | 2016-11-29T22:18:52Z |
| Publication Date | 2016-11-29T22:32:45Z |

## Description

This dataset contains agency summary level data for PS, OTPS and Total by type of funds.  The dollar amount fields are rounded to the thousands. The Quarter 1 report,  published in October or November,  contain the current fiscal year plus three out years of data which  coincide with the release of the published financial plan.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | time           | publication_date        | Publication Date        | text      | number      |
| Yes      | series tag     | agency_number           | Agency Number           | text      | text        |
| Yes      | numeric metric | report_sort             | Report Sort             | number    | number      |
| Yes      | series tag     | agency_name             | Agency Name             | text      | text        |
| Yes      | series tag     | line_number             | Line Number             | text      | number      |
| Yes      | series tag     | line_number_description | Line Number Description | text      | text        |
| No       |                | fiscal_year_1           | Fiscal Year 1           | number    | number      |
| Yes      | numeric metric | year_1_forecast         | Year 1 Forecast         | number    | number      |
| Yes      | numeric metric | year_2_estimate         | Year 2 Estimate         | number    | number      |
| Yes      | numeric metric | year_3_estimate         | Year 3 Estimate         | number    | number      |
| Yes      | numeric metric | year_4_estimate         | Year 4 Estimate         | number    | number      |
```

## Time Field

```ls
Value = publication_date
Format & Zone = yyyyMMdd
```

## Series Fields

```ls
Excluded Fields = fiscal_year_1
```

## Data Commands

```ls
series e:sqmu-2ixd d:2016-11-17T00:00:00.000Z t:line_number_description="704  Total Department" t:line_number=704 t:agency_number=002 t:agency_name=Mayoralty m:year_4_estimate=132522 m:year_2_estimate=138424 m:year_3_estimate=136603 m:report_sort=2704 m:year_1_forecast=136644

series e:sqmu-2ixd d:2016-11-17T00:00:00.000Z t:line_number_description="705      Salaries and Wages" t:line_number=705 t:agency_number=002 t:agency_name=Mayoralty m:year_4_estimate=100130 m:year_2_estimate=101670 m:year_3_estimate=101126 m:report_sort=2705 m:year_1_forecast=104380

series e:sqmu-2ixd d:2016-11-17T00:00:00.000Z t:line_number_description="706      Fringe Benefits" t:line_number=706 t:agency_number=002 t:agency_name=Mayoralty m:year_4_estimate=176 m:year_2_estimate=176 m:year_3_estimate=176 m:report_sort=2706 m:year_1_forecast=272
```

## Meta Commands

```ls
metric m:report_sort p:integer l:"Report Sort" t:dataTypeName=number

metric m:year_1_forecast p:integer l:"Year 1 Forecast" t:dataTypeName=number

metric m:year_2_estimate p:integer l:"Year 2 Estimate" t:dataTypeName=number

metric m:year_3_estimate p:integer l:"Year 3 Estimate" t:dataTypeName=number

metric m:year_4_estimate p:integer l:"Year 4 Estimate" t:dataTypeName=number

entity e:sqmu-2ixd l:"Financial Plan Expense - Qtr1" t:attribution="Mayor?s Office of Management & Budget (OMB)" t:url=https://data.cityofnewyork.us/api/views/sqmu-2ixd

property e:sqmu-2ixd t:meta.view v:id=sqmu-2ixd v:category="City Government" v:averageRating=0 v:name="Financial Plan Expense - Qtr1" v:attribution="Mayor?s Office of Management & Budget (OMB)"

property e:sqmu-2ixd t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:sqmu-2ixd t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| publication_date | agency_number | report_sort | agency_name | line_number | line_number_description    | fiscal_year_1 | year_1_forecast | year_2_estimate | year_3_estimate | year_4_estimate | 
| ================ | ============= | =========== | =========== | =========== | ========================== | ============= | =============== | =============== | =============== | =============== | 
| 20161117         | 002           | 2704        | Mayoralty   | 704         | 704 Total Department       | 2017          | 136644          | 138424          | 136603          | 132522          | 
| 20161117         | 002           | 2705        | Mayoralty   | 705         | 705 Salaries and Wages     | 2017          | 104380          | 101670          | 101126          | 100130          | 
| 20161117         | 002           | 2706        | Mayoralty   | 706         | 706 Fringe Benefits        | 2017          | 272             | 176             | 176             | 176             | 
| 20161117         | 002           | 2707        | Mayoralty   | 707         | 707 Total Personal Service | 2017          | 104652          | 101846          | 101302          | 100306          | 
| 20161117         | 002           | 2708        | Mayoralty   | 708         | 708 City Funds             | 2017          | 75925           | 78279           | 78449           | 77453           | 
| 20161117         | 002           | 2709        | Mayoralty   | 709         | 709 Other Categorical      | 2017          | 4746            | 4462            | 4436            | 4436            | 
| 20161117         | 002           | 2710        | Mayoralty   | 710         | 710 Capital Funds-I.F.A.   | 2017          | 11993           | 12131           | 12131           | 12131           | 
| 20161117         | 002           | 2711        | Mayoralty   | 711         | 711 State                  | 2017          | 279             | 273             | 273             | 273             | 
| 20161117         | 002           | 2713        | Mayoralty   | 713         | 713 Federal - C.D.         | 2017          | 6268            | 3321            | 3328            | 3328            | 
| 20161117         | 002           | 2714        | Mayoralty   | 714         | 714 Federal - Other        | 2017          | 3185            | 1114            | 419             | 419             | 
```