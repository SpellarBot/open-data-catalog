# Connecticut Hospital Liquidity And Solvency Trend Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/connecticut-hospital-liquidity-and-solvency-trend-data) |
| Metadata | [Link](https://data.ct.gov/api/views/m4iq-w9dy) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/m4iq-w9dy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/m4iq-w9dy/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | m4iq-w9dy |
| Name | Connecticut Hospital Liquidity And Solvency Trend Data |
| Attribution | CT Department of Public Health: Office of Health Care Access |
| Category | Health and Human Services |
| Tags | hospital, liquidity, solvency, trend, health, public health, affiliated health system, hospital finance |
| Created | 2014-04-02T11:34:54Z |
| Publication Date | 2014-04-02T11:41:07Z |

## Description

Hospital liquidity and solvency trend data for Connecticut individual hospitals and affiliated health systems (see attached definitions and notes document)

## Columns

```ls
| Included | Schema Type    | Field Name                                          | Name                                                | Data Type | Render Type |
| ======== | ============== | =================================================== | =================================================== | ========= | =========== |
| Yes      | series tag     | affiliated_health_system_hospital_or_non_affiliated | Affiliated Health System Hospital or Non-Affiliated | text      | text        |
| Yes      | series tag     | hospital_name                                       | Hospital Name                                       | text      | text        |
| Yes      | time           | hospital_fiscal_year                                | Hospital Fiscal Year                                | number    | text        |
| Yes      | numeric metric | current_ratio                                       | Current Ratio                                       | number    | number      |
| Yes      | numeric metric | days_cash_on_hand                                   | Days Cash on Hand                                   | number    | number      |
| Yes      | numeric metric | days_revenue_in_patient_accounts_receivable         | Days Revenue in Patient Accounts Receivable         | number    | number      |
| Yes      | numeric metric | average_payment_period                              | Average Payment Period                              | number    | number      |
| Yes      | numeric metric | equity_financing_ratio                              | Equity Financing Ratio                              | number    | number      |
| Yes      | numeric metric | cash_flow_to_total_debt_ratio                       | Cash Flow to Total Debt Ratio                       | number    | number      |
| Yes      | numeric metric | long_term_debt_to_capitalization_ratio              | Long-Term Debt to Capitalization Ratio              | number    | number      |
| Yes      | numeric metric | debt_service_coverage_ratio                         | Debt Service Coverage Ratio                         | number    | number      |
```

## Time Field

```ls
Value = hospital_fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:m4iq-w9dy d:2010-01-01T00:00:00.000Z t:hospital_name="Saint Vincent's" t:affiliated_health_system_hospital_or_non_affiliated="Ascension Health" m:average_payment_period=57 m:days_cash_on_hand=23 m:days_revenue_in_patient_accounts_receivable=33 m:debt_service_coverage_ratio=20.86 m:current_ratio=1.63 m:long_term_debt_to_capitalization_ratio=15.09 m:equity_financing_ratio=69.89 m:cash_flow_to_total_debt_ratio=51.48

series e:m4iq-w9dy d:2010-01-01T00:00:00.000Z t:hospital_name=Manchester t:affiliated_health_system_hospital_or_non_affiliated="Eastern Connecticut Health Network" m:average_payment_period=105 m:days_cash_on_hand=16 m:days_revenue_in_patient_accounts_receivable=54 m:debt_service_coverage_ratio=2.99 m:current_ratio=0.98 m:long_term_debt_to_capitalization_ratio=75.34 m:equity_financing_ratio=10.08 m:cash_flow_to_total_debt_ratio=14.34

series e:m4iq-w9dy d:2010-01-01T00:00:00.000Z t:hospital_name=Rockville t:affiliated_health_system_hospital_or_non_affiliated="Eastern Connecticut Health Network" m:average_payment_period=112 m:days_cash_on_hand=34 m:days_revenue_in_patient_accounts_receivable=56 m:debt_service_coverage_ratio=2.95 m:current_ratio=1.73 m:long_term_debt_to_capitalization_ratio=38.2 m:equity_financing_ratio=40.92 m:cash_flow_to_total_debt_ratio=16.11
```

## Meta Commands

```ls
metric m:current_ratio p:float l:"Current Ratio" t:dataTypeName=number

metric m:days_cash_on_hand p:integer l:"Days Cash on Hand" t:dataTypeName=number

metric m:days_revenue_in_patient_accounts_receivable p:integer l:"Days Revenue in Patient Accounts Receivable" t:dataTypeName=number

metric m:average_payment_period p:integer l:"Average Payment Period" t:dataTypeName=number

metric m:equity_financing_ratio p:float l:"Equity Financing Ratio" t:dataTypeName=number

metric m:cash_flow_to_total_debt_ratio p:float l:"Cash Flow to Total Debt Ratio" t:dataTypeName=number

metric m:long_term_debt_to_capitalization_ratio p:float l:"Long-Term Debt to Capitalization Ratio" t:dataTypeName=number

metric m:debt_service_coverage_ratio p:float l:"Debt Service Coverage Ratio" t:dataTypeName=number

entity e:m4iq-w9dy l:"Connecticut Hospital Liquidity And Solvency Trend Data" t:attribution="CT Department of Public Health:   Office of Health Care Access" t:url=https://data.ct.gov/api/views/m4iq-w9dy

property e:m4iq-w9dy t:meta.view v:id=m4iq-w9dy v:category="Health and Human Services" v:attributionLink="http://www.ct.gov/dph/cwp/view.asp?a=3902&q=277344" v:averageRating=0 v:name="Connecticut Hospital Liquidity And Solvency Trend Data" v:attribution="CT Department of Public Health:   Office of Health Care Access"

property e:m4iq-w9dy t:meta.view.license v:name="Public Domain"

property e:m4iq-w9dy t:meta.view.owner v:id=dby8-627v v:screenName="Gary Archambault" v:displayName="Gary Archambault"

property e:m4iq-w9dy t:meta.view.tableauthor v:id=dby8-627v v:screenName="Gary Archambault" v:roleName=editor v:displayName="Gary Archambault"
```

## Top Records

```ls
| affiliated_health_system_hospital_or_non_affiliated | hospital_name          | hospital_fiscal_year | current_ratio | days_cash_on_hand | days_revenue_in_patient_accounts_receivable | average_payment_period | equity_financing_ratio | cash_flow_to_total_debt_ratio | long_term_debt_to_capitalization_ratio | debt_service_coverage_ratio | 
| =================================================== | ====================== | ==================== | ============= | ================= | =========================================== | ====================== | ====================== | ============================= | ====================================== | =========================== | 
| Ascension Health                                    | Saint Vincent's        | 2010                 | 1.63          | 23                | 33                                          | 57                     | 69.89                  | 51.48                         | 15.09                                  | 20.86                       | 
| Eastern Connecticut Health Network                  | Manchester             | 2010                 | 0.98          | 16                | 54                                          | 105                    | 10.08                  | 14.34                         | 75.34                                  | 2.99                        | 
| Eastern Connecticut Health Network                  | Rockville              | 2010                 | 1.73          | 34                | 56                                          | 112                    | 40.92                  | 16.11                         | 38.20                                  | 2.95                        | 
| Hartford Healthcare Corporation                     | Hartford               | 2010                 | 1.52          | 14                | 53                                          | 56                     | 46.97                  | 39.00                         | 12.48                                  | 25.69                       | 
| Hartford Healthcare Corporation                     | Hospital of Central CT | 2010                 | 0.91          | 23                | 17                                          | 77                     | 39.68                  | 20.75                         | 20.40                                  | 4.69                        | 
| Hartford Healthcare Corporation                     | Midstate               | 2010                 | 1.93          | 57                | 45                                          | 60                     | 31.02                  | 20.06                         | 52.21                                  | 5.26                        | 
| Hartford Healthcare Corporation                     | Windham                | 2010                 | 2.10          | 14                | 66                                          | 45                     | -29.39                 | 9.46                          | -3881.69                               | 1.81                        | 
| Regionalcare Hospital Partners, Inc.                | Sharon*                | 2010                 | 1.51          | 0                 | 40                                          | 50                     | 29.94                  | 15.22                         | 64.84                                  | 3.89                        | 
| Western Connecticut Health Network                  | Danbury                | 2010                 | 3.21          | 168               | 31                                          | 71                     | 70.27                  | 42.53                         | 16.08                                  | 10.67                       | 
| Western Connecticut Health Network                  | New Milford            | 2010                 | 1.68          | 30                | 27                                          | 58                     | 50.36                  | 27.32                         | 16.67                                  | 2.56                        | 
```