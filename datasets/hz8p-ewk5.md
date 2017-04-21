# TIF Balances by Fiscal Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tif-balances-by-fiscal-year-3267c) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/hz8p-ewk5) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/hz8p-ewk5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/hz8p-ewk5/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | hz8p-ewk5 |
| Name | TIF Balances by Fiscal Year |
| Attribution | City of Chciago - Office of Budget & Management |
| Category | Community & Economic Development |
| Tags | tif, fund balance |
| Created | 2013-01-15T23:24:05Z |
| Publication Date | 2015-09-29T16:52:21Z |

## Description

TIF fund balances by fiscal year based on annual financial statements.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | fiscal_year | Fiscal Year | number    | number      |
| Yes      | series tag     | tif_ref     | TIF Number  | text      | text        |
| Yes      | series tag     | tif_name    | TIF Name    | text      | text        |
| Yes      | series tag     | balance     | Period      | text      | text        |
| Yes      | numeric metric | amount      | Amount      | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hz8p-ewk5 d:2014-01-01T00:00:00.000Z t:balance="Beginning Balance" t:tif_ref=T-111 t:tif_name=105th/Vincennes m:amount=79281

series e:hz8p-ewk5 d:2014-01-01T00:00:00.000Z t:balance="Ending Balance" t:tif_ref=T-111 t:tif_name=105th/Vincennes m:amount=114502

series e:hz8p-ewk5 d:2014-01-01T00:00:00.000Z t:balance="Beginning Balance" t:tif_ref=T-073 t:tif_name="111th Street/Kedzie Avenue Business District" m:amount=3203993
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:hz8p-ewk5 l:"TIF Balances by Fiscal Year" t:attribution="City of Chciago - Office of Budget & Management" t:url=https://data.cityofchicago.org/api/views/hz8p-ewk5

property e:hz8p-ewk5 t:meta.view v:id=hz8p-ewk5 v:category="Community & Economic Development" v:averageRating=0 v:name="TIF Balances by Fiscal Year" v:attribution="City of Chciago - Office of Budget & Management"

property e:hz8p-ewk5 t:meta.view.owner v:id=7ek2-d4pb v:screenName="David Miller" v:displayName="David Miller"

property e:hz8p-ewk5 t:meta.view.tableauthor v:id=7ek2-d4pb v:screenName="David Miller" v:roleName=editor v:displayName="David Miller"
```

## Top Records

```ls
| fiscal_year | tif_ref | tif_name                                     | balance           | amount     | 
| =========== | ======= | ============================================ | ================= | ========== | 
| 2014        | T-111   | 105th/Vincennes                              | Beginning Balance | 79281.00   | 
| 2014        | T-111   | 105th/Vincennes                              | Ending Balance    | 114502.00  | 
| 2014        | T-073   | 111th Street/Kedzie Avenue Business District | Beginning Balance | 3203993.00 | 
| 2014        | T-073   | 111th Street/Kedzie Avenue Business District | Ending Balance    | 3278114.00 | 
| 2014        | T-114   | 119th and Halsted                            | Beginning Balance | 3515651.00 | 
| 2014        | T-114   | 119th and Halsted                            | Ending Balance    | 4124936.00 | 
| 2014        | T-125   | 119th/I-57                                   | Beginning Balance | 5745995.00 | 
| 2014        | T-125   | 119th/I-57                                   | Ending Balance    | 4895102.00 | 
| 2014        | T-010   | 126th and Torrence                           | Beginning Balance | 1215193.00 | 
| 2014        | T-010   | 126th and Torrence                           | Ending Balance    | 918519.00  | 
```