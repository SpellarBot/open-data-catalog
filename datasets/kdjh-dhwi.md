# Key Credit Collection: Beginning 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/key-credit-collection-beginning-2010) |
| Metadata | [Link](https://data.ny.gov/api/views/kdjh-dhwi) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/kdjh-dhwi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/kdjh-dhwi/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | kdjh-dhwi |
| Name | Key Credit Collection: Beginning 2010 |
| Attribution | New York State Department of Public Service |
| Category | Energy & Environment |
| Tags | collections, utility, electric, gas, arrears |
| Created | 2015-10-02T19:57:09Z |
| Publication Date | 2017-02-03T14:50:04Z |

## Description

Quarterly snapshot of residential collection data submitted by New York State?s ten largest distribution utility companies.

## Columns

```ls
| Included | Schema Type    | Field Name                                              | Name                                                    | Data Type | Render Type |
| ======== | ============== | ======================================================= | ======================================================= | ========= | =========== |
| No       |                | month                                                   | Month                                                   | number    | number      |
| No       |                | year                                                    | Year                                                    | number    | number      |
| Yes      | series tag     | company_name                                            | Company Name                                            | text      | text        |
| Yes      | series tag     | company_id                                              | Company ID                                              | text      | text        |
| Yes      | numeric metric | residential_customers                                   | Residential Customers                                   | number    | number      |
| Yes      | numeric metric | residential_customers_with_arrears_greater_than_60_days | Residential Customers with Arrears Greater than 60 days | number    | number      |
| Yes      | numeric metric | residential_final_termination_notices                   | Residential Final Termination Notices                   | number    | number      |
| Yes      | numeric metric | residential_accounts_terminated                         | Residential Accounts Terminated                         | number    | number      |
| Yes      | numeric metric | residential_accounts_terminated_percentage              | Residential Accounts Terminated Percentage              | percent   | percent     |
| Yes      | numeric metric | residential_active_payment_arrangements                 | Residential Active Payment Arrangements                 | number    | number      |
| Yes      | numeric metric | residential_uncollectables                              | Residential Uncollectibles                              | number    | number      |
| Yes      | numeric metric | residential_sales                                       | Residential Sales                                       | money     | money       |
| Yes      | numeric metric | residential_arrears_greater_than_60_days_sales          | Residential Arrears Greater than 60 Days Sales          | money     | money       |
| Yes      | numeric metric | residential_final_termination_notices_issued_sales      | Residential Final Termination Notices Issued Sales      | money     | money       |
| Yes      | numeric metric | residential_accounts_terminated_sales                   | Residential Accounts Terminated Sales                   | money     | money       |
| Yes      | numeric metric | residential_average_sales                               | Residential Average Sales                               | money     | money       |
| Yes      | numeric metric | residential_active_payment_arrangements_sales           | Residential Active Payment Arrangements Sales           | money     | money       |
| Yes      | numeric metric | residential_uncollectables_sales                        | Residential Uncollectibles Sales                        | money     | money       |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:kdjh-dhwi d:2010-03-01T00:00:00.000Z t:company_id=1002 t:company_name=CE m:residential_customers=2829157 m:residential_sales=319127203.39 m:residential_accounts_terminated=6501 m:residential_active_payment_arrangements_sales=67150403 m:residential_final_termination_notices_issued_sales=67955839.79 m:residential_accounts_terminated_sales=5141000 m:residential_uncollectables_sales=2587980.92 m:residential_arrears_greater_than_60_days_sales=169882346 m:residential_customers_with_arrears_greater_than_60_days=240652 m:residential_active_payment_arrangements=151139 m:residential_accounts_terminated_percentage=0.22 m:residential_average_sales=112.8 m:residential_uncollectables=4620 m:residential_final_termination_notices=217374

series e:kdjh-dhwi d:2010-03-01T00:00:00.000Z t:company_id=1001 t:company_name=CH m:residential_customers=255049 m:residential_sales=40075500 m:residential_accounts_terminated=405 m:residential_active_payment_arrangements_sales=5938077 m:residential_final_termination_notices_issued_sales=12445547 m:residential_accounts_terminated_sales=435029 m:residential_uncollectables_sales=797018 m:residential_arrears_greater_than_60_days_sales=13275546 m:residential_customers_with_arrears_greater_than_60_days=25443 m:residential_active_payment_arrangements=3901 m:residential_accounts_terminated_percentage=0.15 m:residential_average_sales=157.13 m:residential_uncollectables=1240 m:residential_final_termination_notices=23451

series e:kdjh-dhwi d:2010-03-01T00:00:00.000Z t:company_id=1003 t:company_name=NGrid-LI m:residential_customers=502515 m:residential_sales=97927089 m:residential_accounts_terminated=682 m:residential_active_payment_arrangements_sales=22594116 m:residential_final_termination_notices_issued_sales=2014369 m:residential_accounts_terminated_sales=1306504 m:residential_uncollectables_sales=739646 m:residential_arrears_greater_than_60_days_sales=34632112 m:residential_customers_with_arrears_greater_than_60_days=60900 m:residential_active_payment_arrangements=22316 m:residential_accounts_terminated_percentage=0.13 m:residential_average_sales=194.87 m:residential_uncollectables=988 m:residential_final_termination_notices=2482
```

## Meta Commands

```ls
metric m:residential_customers p:float l:"Residential Customers" d:"The total number of residential customers" t:dataTypeName=number

metric m:residential_customers_with_arrears_greater_than_60_days p:float l:"Residential Customers with Arrears Greater than 60 days" d:"The total number of residential customers with arrears greater than 60 days" t:dataTypeName=number

metric m:residential_final_termination_notices p:float l:"Residential Final Termination Notices" d:"The total number of residential final termination notices issued" t:dataTypeName=number

metric m:residential_accounts_terminated p:float l:"Residential Accounts Terminated" d:"The total number of residential accounts terminated" t:dataTypeName=number

metric m:residential_accounts_terminated_percentage p:float l:"Residential Accounts Terminated Percentage" d:"The percentage of residential accounts terminated" t:dataTypeName=percent

metric m:residential_active_payment_arrangements p:float l:"Residential Active Payment Arrangements" d:"Total number of residential customers with active deferred payment arrangements" t:dataTypeName=number

metric m:residential_uncollectables p:float l:"Residential Uncollectibles" d:"The total number of residential accounts uncollected" t:dataTypeName=number

metric m:residential_sales p:double l:"Residential Sales" d:"The total dollar amount of residential customer sales" t:dataTypeName=money

metric m:residential_arrears_greater_than_60_days_sales p:double l:"Residential Arrears Greater than 60 Days Sales" d:"The total dollar amount of residential sales arrears greater than 60 days" t:dataTypeName=money

metric m:residential_final_termination_notices_issued_sales p:double l:"Residential Final Termination Notices Issued Sales" d:"The total dollar amount of residential final termination notices issued" t:dataTypeName=money

metric m:residential_accounts_terminated_sales p:double l:"Residential Accounts Terminated Sales" d:"The total dollar amount of residential accounts terminated for non payment" t:dataTypeName=money

metric m:residential_average_sales p:double l:"Residential Average Sales" d:"Average dollar amount of sales per residential customer for the month reported" t:dataTypeName=money

metric m:residential_active_payment_arrangements_sales p:double l:"Residential Active Payment Arrangements Sales" d:"The total dollar amount in active deferred payment arrangements" t:dataTypeName=money

metric m:residential_uncollectables_sales p:double l:"Residential Uncollectibles Sales" d:"The total dollar amount of uncollectible accounts" t:dataTypeName=money

entity e:kdjh-dhwi l:"Key Credit Collection: Beginning 2010" t:attribution="New York State Department of Public Service" t:url=https://data.ny.gov/api/views/kdjh-dhwi

property e:kdjh-dhwi t:meta.view v:id=kdjh-dhwi v:category="Energy & Environment" v:attributionLink="http://documents.dps.ny.gov/public/MatterManagement/CaseMaster.aspx?MatterCaseNo=91-M-0744&submit=Search" v:averageRating=0 v:name="Key Credit Collection: Beginning 2010" v:attribution="New York State Department of Public Service"

property e:kdjh-dhwi t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:kdjh-dhwi t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:kdjh-dhwi t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| month | year | company_name  | company_id | residential_customers | residential_customers_with_arrears_greater_than_60_days | residential_final_termination_notices | residential_accounts_terminated | residential_accounts_terminated_percentage | residential_active_payment_arrangements | residential_uncollectables | residential_sales | residential_arrears_greater_than_60_days_sales | residential_final_termination_notices_issued_sales | residential_accounts_terminated_sales | residential_average_sales | residential_active_payment_arrangements_sales | residential_uncollectables_sales | 
| ===== | ==== | ============= | ========== | ===================== | ======================================================= | ===================================== | =============================== | ========================================== | ======================================= | ========================== | ================= | ============================================== | ================================================== | ===================================== | ========================= | ============================================= | ================================ | 
| 3     | 2010 | CE            | 1002       | 2829157.00            | 240652.00                                               | 217374.00                             | 6501.00                         | 0.22                                       | 151139.00                               | 4620.00                    | 319127203.39      | 169882346.00                                   | 67955839.79                                        | 5141000.00                            | 112.80                    | 67150403.00                                   | 2587980.92                       | 
| 3     | 2010 | CH            | 1001       | 255049.00             | 25443.00                                                | 23451.00                              | 405.00                          | 0.15                                       | 3901.00                                 | 1240.00                    | 40075500.00       | 13275546.00                                    | 12445547.00                                        | 435029.00                             | 157.13                    | 5938077.00                                    | 797018.00                        | 
| 3     | 2010 | NGrid-LI      | 1003       | 502515.00             | 60900.00                                                | 2482.00                               | 682.00                          | 0.13                                       | 22316.00                                | 988.00                     | 97927089.00       | 34632112.00                                    | 2014369.00                                         | 1306504.00                            | 194.87                    | 22594116.00                                   | 739646.00                        | 
| 3     | 2010 | NGrid-NY      | 3010       | 991957.00             | 152994.00                                               | 53625.00                              | 2906.03                         | 0.29                                       | 27600.00                                | 5823.00                    | 154932336.82      | 72410628.00                                    | 53510901.76                                        | 2650053.58                            | 156.19                    | 21469205.86                                   | 1061036.51                       | 
| 3     | 2010 | NGrid-Upstate | 1004       | 1456407.05            | 229712.00                                               | 98771.00                              | 2606.00                         | 0.17                                       | 98461.00                                | 6750.00                    | 241478704.49      | 201131792.00                                   | 71007501.77                                        | 4131403.92                            | 165.80                    | 91586516.75                                   | 1188377.13                       | 
| 3     | 2010 | NFG           | 3120       | 464366.00             | 27734.00                                                | 23420.00                              | 367.00                          | 0.07                                       | 23968.00                                | 1650.00                    | 54704512.26       | 23808365.50                                    | 13718972.31                                        | 603293.96                             | 117.80                    | 19213564.93                                   | 871883.27                        | 
| 3     | 2010 | NYSEG         | 1005       | 987584.00             | 78033.00                                                | 93142.00                              | 2456.00                         | 0.24                                       | 38714.00                                | 2893.00                    | 85999760.00       | 23072327.92                                    | 23495541.46                                        | 1171960.77                            | 87.08                     | 24409713.53                                   | -215946.94                       | 
| 3     | 2010 | OR            | 1006       | 194579.00             | 17063.00                                                | 16534.00                              | 374.00                          | 0.19                                       | 6893.00                                 | -2.00                      | 54876383.14       | 8007441.22                                     | 6648191.00                                         | 426882.75                             | 282.03                    | 7292365.00                                    | 116841.56                        | 
| 3     | 2010 | RG&E          | 1007       | 602542.00             | 51343.00                                                | 51212.00                              | 2058.00                         | 0.34                                       | 29531.00                                | 1816.00                    | 55002456.00       | 35861518.17                                    | 21150965.88                                        | 2520067.36                            | 91.28                     | 29323677.00                                   | -582346.47                       | 
| 6     | 2010 | CE            | 1002       | 2830745.00            | 231598.00                                               | 232701.00                             | 9434.00                         | 0.33                                       | 148648.00                               | 5462.00                    | 337962469.49      | 170962135.00                                   | 70849431.14                                        | 8077000.00                            | 119.39                    | 71890249.00                                   | 3037699.30                       | 
```