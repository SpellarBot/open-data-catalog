# Expenditures: ESD: Columbia Gorge: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-columbia-gorge-fiscal-year-2013-75c51) |
| Metadata | [Link](https://data.oregon.gov/api/views/5qsu-6n7j) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/5qsu-6n7j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/5qsu-6n7j/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 5qsu-6n7j |
| Name | Expenditures: ESD: Columbia Gorge: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | expenditures, esd, columbia gorge, fiscal year 2013 |
| Created | 2013-10-22T14:55:54Z |
| Publication Date | 2013-10-23T23:32:07Z |

## Description

ESD Expenditures for FY 2013

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | numeric metric | esd             | ESD #           | number    | number      |
| Yes      | series tag     | esd_name        | ESD NAME        | text      | text        |
| Yes      | series tag     | fund_name       | FUND NAME       | text      | text        |
| Yes      | numeric metric | compt_obj       | COMPT_OBJ       | number    | number      |
| Yes      | series tag     | compt_obj_title | COMPT_OBJ_TITLE | text      | text        |
| Yes      | series tag     | vendor_name     | VENDOR_NAME     | text      | text        |
| No       |                | vendor_address  | VENDOR_ADDRESS  | text      | text        |
| Yes      | series tag     | vendor_city     | VENDOR_CITY     | text      | text        |
| Yes      | series tag     | vendor_state    | VENDOR_STATE    | text      | text        |
| Yes      | series tag     | vendor_zip_code | VENDOR_ZIP_CODE | text      | number      |
| Yes      | numeric metric | cash_expense    | CASH_EXPENSE    | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = vendor_address
```

## Data Commands

```ls
series e:5qsu-6n7j d:2013-01-01T00:00:00.000Z t:vendor_city=VANCOUVER t:fund_name=E-RATE t:vendor_zip_code=98660 t:vendor_state=WA t:esd_name="COLUMBIA GORGE EDUCATION SERVICE DISTRICT" t:compt_obj_title="DEPRECIABLE TECHNOLOGY" t:vendor_name="ADVAN TEL NETWORKS" m:compt_obj=550 m:esd=2223 m:cash_expense=5677.92

series e:5qsu-6n7j d:2013-01-01T00:00:00.000Z t:vendor_city=VANCOUVER t:fund_name=E-RATE t:vendor_zip_code=98660 t:vendor_state=WA t:esd_name="COLUMBIA GORGE EDUCATION SERVICE DISTRICT" t:compt_obj_title="DEPRECIABLE TECHNOLOGY" t:vendor_name="ADVAN TEL NETWORKS" m:compt_obj=550 m:esd=2223 m:cash_expense=631.58

series e:5qsu-6n7j d:2013-01-01T00:00:00.000Z t:vendor_city=VANCOUVER t:fund_name=E-RATE t:vendor_zip_code=98660 t:vendor_state=WA t:esd_name="COLUMBIA GORGE EDUCATION SERVICE DISTRICT" t:compt_obj_title="DEPRECIABLE TECHNOLOGY" t:vendor_name="ADVAN TEL NETWORKS" m:compt_obj=550 m:esd=2223 m:cash_expense=6568.44
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:compt_obj p:integer l:COMPT_OBJ t:dataTypeName=number

metric m:cash_expense p:double l:CASH_EXPENSE t:dataTypeName=money

entity e:5qsu-6n7j l:"Expenditures: ESD: Columbia Gorge: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/5qsu-6n7j

property e:5qsu-6n7j t:meta.view v:id=5qsu-6n7j v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Columbia Gorge: Fiscal Year 2013"

property e:5qsu-6n7j t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:5qsu-6n7j t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                                  | fund_name                                                                | compt_obj | compt_obj_title               | vendor_name        | vendor_address         | vendor_city | vendor_state | vendor_zip_code | cash_expense | 
| ==== | ========================================= | ======================================================================== | ========= | ============================= | ================== | ====================== | =========== | ============ | =============== | ============ | 
| 2223 | COLUMBIA GORGE EDUCATION SERVICE DISTRICT | E-RATE                                                                   | 550       | DEPRECIABLE TECHNOLOGY        | ADVAN TEL NETWORKS | 700 WASHINGTON STREET  | VANCOUVER   | WA           | 98660           | 5677.92      | 
| 2223 | COLUMBIA GORGE EDUCATION SERVICE DISTRICT | E-RATE                                                                   | 550       | DEPRECIABLE TECHNOLOGY        | ADVAN TEL NETWORKS | 700 WASHINGTON STREET  | VANCOUVER   | WA           | 98660           | 631.58       | 
| 2223 | COLUMBIA GORGE EDUCATION SERVICE DISTRICT | E-RATE                                                                   | 550       | DEPRECIABLE TECHNOLOGY        | ADVAN TEL NETWORKS | 700 WASHINGTON STREET  | VANCOUVER   | WA           | 98660           | 6568.44      | 
| 2223 | COLUMBIA GORGE EDUCATION SERVICE DISTRICT | E-RATE                                                                   | 550       | DEPRECIABLE TECHNOLOGY        | ADVAN TEL NETWORKS | 700 WASHINGTON STREET  | VANCOUVER   | WA           | 98660           | 1263.16      | 
| 2223 | COLUMBIA GORGE EDUCATION SERVICE DISTRICT | E-RATE                                                                   | 550       | DEPRECIABLE TECHNOLOGY        | ADVAN TEL NETWORKS | 700 WASHINGTON STREET  | VANCOUVER   | WA           | 98660           | 631.58       | 
| 2223 | COLUMBIA GORGE EDUCATION SERVICE DISTRICT | INFORMATION TECHNOLOGY                                                   | 550       | DEPRECIABLE TECHNOLOGY        | ADVAN TEL NETWORKS | 700 WASHINGTON STREET  | VANCOUVER   | WA           | 98660           | 197.83       | 
| 2223 | COLUMBIA GORGE EDUCATION SERVICE DISTRICT | INFORMATION TECHNOLOGY                                                   | 550       | DEPRECIABLE TECHNOLOGY        | ADVAN TEL NETWORKS | 700 WASHINGTON STREET  | VANCOUVER   | WA           | 98660           | 17500.00     | 
| 2223 | COLUMBIA GORGE EDUCATION SERVICE DISTRICT | EARLY INTERVENTION-RAINY DAY FUND                                        | 410       | CONSUMABLE SUPPLIES/MATERIALS | AERO PRINT INC.    | 308 EAST SECOND STREET | THE DALLES  | OR           | 97058           | 252.00       | 
| 2223 | COLUMBIA GORGE EDUCATION SERVICE DISTRICT | ACCOUNTS RECEIVABLE                                                      | 153       | ACCOUNTS RECEIVABLE           | ALFONSO SANCHEZ    | 909 EAST EIGHTH STREET | THE DALLES  | OR           | 97058           | 144.30       | 
| 2223 | COLUMBIA GORGE EDUCATION SERVICE DISTRICT | EARLY INTERVENTION/EARLY CHILDHOOD SPECIAL EDUCATION-OTHER GRANT SOURCES | 460       | NON-CONSUMABLE ITEMS          | APPLE COMPUTERS    | PO BOX 846095          | DALLAS      | TX           | 75284           | 49.00        | 
```