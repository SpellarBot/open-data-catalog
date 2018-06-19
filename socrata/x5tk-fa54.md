# Expense Financial Plan - Exec

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/financial-plan-expense) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/x5tk-fa54) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/x5tk-fa54/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/x5tk-fa54/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | x5tk-fa54 |
| Name | Expense Financial Plan - Exec |
| Attribution | Mayor?s Office of Management & Budget (OMB) |
| Category | City Government |
| Created | 2016-05-04T20:50:07Z |
| Publication Date | 2016-05-04T20:52:53Z |

## Description

This dataset contains agency summary level data for PS, OTPS and Total by type of funds.  The dollar amount fields are rounded to the thousands.  The Executive Budget report, published in April or May, contains previous fiscal year actuals, the current fiscal year Executive budget, eight month actuals and forecast plus four out years of data which coincide with the release of the published financial plan.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | time           | publication_date        | Publication Date        | text      | text        |
| Yes      | series tag     | agency_number           | Agency Number           | text      | number      |
| Yes      | numeric metric | report_sort             | Report Sort             | number    | number      |
| Yes      | series tag     | agency_name             | Agency Name             | text      | text        |
| Yes      | series tag     | line_number             | Line Number             | text      | number      |
| Yes      | series tag     | line_number_description | Line Number Description | text      | text        |
| No       |                | fiscal_year_1           | Fiscal Year 1           | number    | number      |
| Yes      | numeric metric | prior_year_actual       | Prior Year Actual       | number    | number      |
| Yes      | numeric metric | year_1_executive_bud    | Year 1 Executive Bud    | number    | number      |
| Yes      | numeric metric | year_1_actual           | Year 1 Actual           | number    | number      |
| Yes      | numeric metric | year_1_forecast         | Year 1 Forecast         | number    | number      |
| Yes      | numeric metric | year_2_estimate         | Year 2 Estimate         | number    | number      |
| Yes      | numeric metric | year_3_estimate         | Year 3 Estimate         | number    | number      |
| Yes      | numeric metric | year_4_estimate         | Year 4 Estimate         | number    | number      |
| Yes      | numeric metric | year_5_estimate         | Year 5 Estimate         | number    | number      |
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
series e:x5tk-fa54 d:2016-04-26T00:00:00.000Z t:line_number_description="704  Total Department" t:line_number=704 t:agency_number=2 t:agency_name=Mayoralty m:prior_year_actual=101721 m:year_4_estimate=134353 m:year_2_estimate=137879 m:year_3_estimate=129334 m:year_1_actual=70332 m:year_5_estimate=130773 m:year_1_executive_bud=121787 m:report_sort=2704 m:year_1_forecast=125676

series e:x5tk-fa54 d:2016-04-26T00:00:00.000Z t:line_number_description="705      Salaries and Wages" t:line_number=705 t:agency_number=2 t:agency_name=Mayoralty m:prior_year_actual=78678 m:year_4_estimate=99613 m:year_2_estimate=102515 m:year_3_estimate=100317 m:year_1_actual=54610 m:year_5_estimate=99118 m:year_1_executive_bud=92838 m:report_sort=2705 m:year_1_forecast=98144

series e:x5tk-fa54 d:2016-04-26T00:00:00.000Z t:line_number_description="706      Fringe Benefits" t:line_number=706 t:agency_number=2 t:agency_name=Mayoralty m:prior_year_actual=0 m:year_4_estimate=176 m:year_2_estimate=193 m:year_3_estimate=176 m:year_1_actual=0 m:year_5_estimate=176 m:year_1_executive_bud=338 m:report_sort=2706 m:year_1_forecast=443
```

## Meta Commands

```ls
metric m:report_sort p:integer l:"Report Sort" t:dataTypeName=number

metric m:prior_year_actual p:integer l:"Prior Year Actual" t:dataTypeName=number

metric m:year_1_executive_bud p:integer l:"Year 1 Executive Bud" t:dataTypeName=number

metric m:year_1_actual p:integer l:"Year 1 Actual" t:dataTypeName=number

metric m:year_1_forecast p:integer l:"Year 1 Forecast" t:dataTypeName=number

metric m:year_2_estimate p:integer l:"Year 2 Estimate" t:dataTypeName=number

metric m:year_3_estimate p:integer l:"Year 3 Estimate" t:dataTypeName=number

metric m:year_4_estimate p:integer l:"Year 4 Estimate" t:dataTypeName=number

metric m:year_5_estimate p:integer l:"Year 5 Estimate" t:dataTypeName=number

entity e:x5tk-fa54 l:"Expense Financial Plan - Exec" t:attribution="Mayor?s Office of Management & Budget (OMB)" t:url=https://data.cityofnewyork.us/api/views/x5tk-fa54

property e:x5tk-fa54 t:meta.view v:id=x5tk-fa54 v:category="City Government" v:averageRating=0 v:name="Expense Financial Plan - Exec" v:attribution="Mayor?s Office of Management & Budget (OMB)"

property e:x5tk-fa54 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:x5tk-fa54 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| publication_date | agency_number | report_sort | agency_name | line_number | line_number_description    | fiscal_year_1 | prior_year_actual | year_1_executive_bud | year_1_actual | year_1_forecast | year_2_estimate | year_3_estimate | year_4_estimate | year_5_estimate | 
| ================ | ============= | =========== | =========== | =========== | ========================== | ============= | ================= | ==================== | ============= | =============== | =============== | =============== | =============== | =============== | 
| 20160426         | 2             | 2704        | Mayoralty   | 704         | 704 Total Department       | 2016          | 101721            | 121787               | 70332         | 125676          | 137879          | 129334          | 134353          | 130773          | 
| 20160426         | 2             | 2705        | Mayoralty   | 705         | 705 Salaries and Wages     | 2016          | 78678             | 92838                | 54610         | 98144           | 102515          | 100317          | 99613           | 99118           | 
| 20160426         | 2             | 2706        | Mayoralty   | 706         | 706 Fringe Benefits        | 2016          | 0                 | 338                  | 0             | 443             | 193             | 176             | 176             | 176             | 
| 20160426         | 2             | 2707        | Mayoralty   | 707         | 707 Total Personal Service | 2016          | 78678             | 93176                | 54610         | 98587           | 102708          | 100493          | 99789           | 99294           | 
| 20160426         | 2             | 2708        | Mayoralty   | 708         | 708 City Funds             | 2016          | 0                 | 67322                | 0             | 67909           | 76638           | 77011           | 77021           | 76526           | 
| 20160426         | 2             | 2709        | Mayoralty   | 709         | 709 Other Categorical      | 2016          | 0                 | 4360                 | 0             | 5138            | 4537            | 4462            | 4436            | 4436            | 
| 20160426         | 2             | 2710        | Mayoralty   | 710         | 710 Capital Funds-I.F.A.   | 2016          | 0                 | 11577                | 0             | 11537           | 11950           | 12046           | 12046           | 12046           | 
| 20160426         | 2             | 2711        | Mayoralty   | 711         | 711 State                  | 2016          | 0                 | 586                  | 0             | 589             | 271             | 273             | 273             | 273             | 
| 20160426         | 2             | 2712        | Mayoralty   | 712         | 712 Federal - JTPA         | 2016          | 0                 | 0                    | 0             | 0               | 0               | 0               | 0               | 0               | 
| 20160426         | 2             | 2713        | Mayoralty   | 713         | 713 Federal - C.D.         | 2016          | 0                 | 6607                 | 0             | 7811            | 5893            | 3321            | 3328            | 3328            | 
```