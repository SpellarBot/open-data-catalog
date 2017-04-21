# Active Credit Access Business Licenses January 5, 2017

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/active-credit-access-business-licenses-10-4-2016) |
| Metadata | [Link](https://data.austintexas.gov/api/views/3fnm-exg7) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/3fnm-exg7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/3fnm-exg7/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 3fnm-exg7 |
| Name | Active Credit Access Business Licenses January 5, 2017 |
| Category | Business |
| Tags | credit access businesses, payday lenders, auto title lenders |
| Created | 2016-10-04T15:23:38Z |
| Publication Date | 2017-01-05T15:44:43Z |

## Description

Dataset of Active Credit Access Business Licenses

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| Yes      | series tag  | licensee       | Licensee       | text      | text        |
| Yes      | series tag  | operating_name | Operating Name | text      | text        |
| Yes      | series tag  | zip_code       | Zip Code       | text      | text        |
| Yes      | series tag  | status         | Status         | text      | text        |
| Yes      | series tag  | license        | License #      | text      | text        |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3fnm-exg7 d:2017-01-01T00:00:00.000Z t:zip_code=78748 t:status=Active t:license=1400031541-59408 t:operating_name="THE CASH STORE" t:licensee="COTTONWOOD FINANCIAL TEXAS LLC" m:row_number.3fnm-exg7=1

series e:3fnm-exg7 d:2017-01-01T00:00:00.000Z t:zip_code=78741 t:status=Active t:license=17170-63955 t:operating_name="SPEEDY CASH" t:licensee="THE MONEY STORE LP" m:row_number.3fnm-exg7=2

series e:3fnm-exg7 d:2017-01-01T00:00:00.000Z t:zip_code=78745 t:status=Active t:license=16419-62997 t:operating_name="SPEEDY CASH" t:licensee="SCIL TEXAS LLC" m:row_number.3fnm-exg7=3
```

## Meta Commands

```ls
metric m:row_number.3fnm-exg7 p:long l:"Row Number"

entity e:3fnm-exg7 l:"Active Credit Access Business Licenses January 5, 2017" t:url=https://data.austintexas.gov/api/views/3fnm-exg7

property e:3fnm-exg7 t:meta.view v:id=3fnm-exg7 v:category=Business v:averageRating=0 v:name="Active Credit Access Business Licenses January 5, 2017"

property e:3fnm-exg7 t:meta.view.owner v:id=xyvj-5d85 v:screenName=jesse.rodriguez v:displayName=jesse.rodriguez

property e:3fnm-exg7 t:meta.view.tableauthor v:id=xyvj-5d85 v:screenName=jesse.rodriguez v:roleName=editor_stories v:displayName=jesse.rodriguez
```

## Top Records

```ls
| licensee                         | operating_name            | zip_code | status | license          | 
| ================================ | ========================= | ======== | ====== | ================ | 
| COTTONWOOD FINANCIAL TEXAS LLC   | THE CASH STORE            | 78748    | Active | 1400031541-59408 | 
| THE MONEY STORE LP               | SPEEDY CASH               | 78741    | Active | 17170-63955      | 
| SCIL TEXAS LLC                   | SPEEDY CASH               | 78745    | Active | 16419-62997      | 
| TITLEMAX OF TEXAS INC            | TITLEMAX                  | 78752    | Active | 16363-59919      | 
| NATIONAL CSO LOAN CORP           | CASH UNTIL?AND CASH TODAY | 78745    | Active | 16620-62771      | 
| FIRST CASH CREDIT LTD            | FIRST CASH PAWN           | 78748    | Active | 16407-60885      | 
| THE MONEY STORE LP               | SPEEDY CASH               | 78741    | Active | 17170-63969      | 
| THE MONEY STORE LP               | SPEEDY CASH               | 78704    | Active | 17170-63963      | 
| THE MONEY STORE LP               | SPEEDY CASH               | 78722    | Active | 17170-63945      | 
| WELLSHIRE FINANCIAL SERVICES LLC | LOANSTAR TITLE LOANS      | 78741    | Active | 16404-61883      | 
```