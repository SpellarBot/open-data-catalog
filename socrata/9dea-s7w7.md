# Local Option Sales Tax Receipts by Month and Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/local-option-sales-tax-receipts-by-month-and-location) |
| Metadata | [Link](https://data.iowa.gov/api/views/9dea-s7w7) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/9dea-s7w7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/9dea-s7w7/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 9dea-s7w7 |
| Name | Local Option Sales Tax Receipts by Month and Location |
| Attribution | Iowa Department of Revenue, Research and Analysis, Local Option Sales Tax Receipts |
| Category | Government |
| Tags | local option sales tax, taxes, sales tax, cities |
| Created | 2014-12-04T21:21:28Z |
| Publication Date | 2017-01-09T20:56:58Z |

## Description

This dataset contains monthly receipts of local option sales taxes by location (incorporated communities and unincorporated areas). Local option sales taxes are collected on top of the state-wide sales tax applicable in all jurisdictions.  Not all communities in Iowa levy a local option sales tax.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| No       |                | co                      | Co#                     | text          | text          |
| Yes      | series tag     | jurisdiction            | Jurisdiction            | text          | text          |
| Yes      | time           | fiscal_year             | Fiscal Year             | calendar_date | calendar_date |
| Yes      | numeric metric | fy_total                | FY Total                | money         | money         |
| Yes      | numeric metric | reconciliation_november | Reconciliation November | money         | money         |
| Yes      | numeric metric | june                    | June                    | money         | money         |
| Yes      | numeric metric | may                     | May                     | money         | money         |
| Yes      | numeric metric | april                   | April                   | money         | money         |
| Yes      | numeric metric | march                   | March                   | money         | money         |
| Yes      | numeric metric | february                | February                | money         | money         |
| Yes      | numeric metric | january                 | January                 | money         | money         |
| Yes      | numeric metric | december                | December                | money         | money         |
| Yes      | numeric metric | november                | November                | money         | money         |
| Yes      | numeric metric | october                 | October                 | money         | money         |
| Yes      | numeric metric | september               | September               | money         | money         |
| Yes      | numeric metric | august                  | August                  | money         | money         |
| Yes      | numeric metric | july                    | July                    | money         | money         |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = co
```

## Data Commands

```ls
series e:9dea-s7w7 d:2016-01-01T00:00:00.000Z t:jurisdiction=Greenfield m:december=15513.04 m:may=17809.46 m:november=15513.04 m:march=18346.28 m:fy_total=217035.28 m:april=17809.46 m:february=18346.28 m:june=17809.46 m:january=18346.3 m:reconciliation_november=18880.63 m:august=14382.76 m:july=14382.77 m:october=15513.04 m:september=14382.76

series e:9dea-s7w7 d:2016-01-01T00:00:00.000Z t:jurisdiction=Adair m:december=6268.34 m:may=7196.26 m:november=6268.34 m:march=7413.17 m:fy_total=87697.37 m:april=7196.26 m:february=7413.17 m:june=7196.26 m:january=7413.19 m:reconciliation_november=7629.11 m:august=5811.64 m:july=5811.63 m:october=6268.36 m:september=5811.64

series e:9dea-s7w7 d:2016-01-01T00:00:00.000Z t:jurisdiction=Casey m:december=0 m:may=0 m:november=0 m:march=0 m:fy_total=0 m:april=0 m:february=0 m:june=0 m:january=0 m:reconciliation_november=0 m:august=0 m:july=0 m:october=0 m:september=0
```

## Meta Commands

```ls
metric m:fy_total p:double l:"FY Total" d:"Total local option sales tax receipts for the fiscal year." t:dataTypeName=money

metric m:reconciliation_november p:double l:"Reconciliation November" d:"Receipts updated as part of the reconciliation done in November." t:dataTypeName=money

metric m:june p:double l:June d:"Total local option sales tax receipts for June." t:dataTypeName=money

metric m:may p:double l:May d:"Total local option sales tax receipts for May." t:dataTypeName=money

metric m:april p:double l:April d:"Total local option sales tax receipts for April." t:dataTypeName=money

metric m:march p:double l:March d:"Total local option sales tax receipts for March." t:dataTypeName=money

metric m:february p:double l:February d:"Total local option sales tax receipts for February." t:dataTypeName=money

metric m:january p:double l:January d:"Total local option sales tax receipts for January." t:dataTypeName=money

metric m:december p:double l:December d:"Total local option sales tax receipts for December." t:dataTypeName=money

metric m:november p:double l:November d:"Total local option sales tax receipts for November." t:dataTypeName=money

metric m:october p:double l:October d:"Total local option sales tax receipts for October." t:dataTypeName=money

metric m:september p:double l:September d:"Total local option sales tax receipts for September." t:dataTypeName=money

metric m:august p:double l:August d:"Total local option sales tax receipts for August." t:dataTypeName=money

metric m:july p:double l:July d:"Total local option sales tax receipts for July." t:dataTypeName=money

entity e:9dea-s7w7 l:"Local Option Sales Tax Receipts by Month and Location" t:attribution="Iowa Department of Revenue, Research and Analysis, Local Option Sales Tax Receipts" t:url=https://data.iowa.gov/api/views/9dea-s7w7

property e:9dea-s7w7 t:meta.view v:id=9dea-s7w7 v:category=Government v:averageRating=0 v:name="Local Option Sales Tax Receipts by Month and Location" v:attribution="Iowa Department of Revenue, Research and Analysis, Local Option Sales Tax Receipts"

property e:9dea-s7w7 t:meta.view.license v:name="Public Domain"

property e:9dea-s7w7 t:meta.view.owner v:id=y22p-i8y2 v:profileImageUrlMedium=/api/users/y22p-i8y2/profile_images/THUMB v:profileImageUrlLarge=/api/users/y22p-i8y2/profile_images/LARGE v:screenName="Revenue, Research and Analysis" v:profileImageUrlSmall=/api/users/y22p-i8y2/profile_images/TINY v:displayName="Revenue, Research and Analysis"

property e:9dea-s7w7 t:meta.view.tableauthor v:id=y22p-i8y2 v:profileImageUrlMedium=/api/users/y22p-i8y2/profile_images/THUMB v:profileImageUrlLarge=/api/users/y22p-i8y2/profile_images/LARGE v:screenName="Revenue, Research and Analysis" v:profileImageUrlSmall=/api/users/y22p-i8y2/profile_images/TINY v:roleName=editor v:displayName="Revenue, Research and Analysis"
```

## Top Records

```ls
| co | jurisdiction   | fiscal_year         | fy_total  | reconciliation_november | june     | may      | april    | march    | february | january  | december | november | october  | september | august   | july     | 
| == | ============== | =================== | ========= | ======================= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ========= | ======== | ======== | 
| 1  | Greenfield     | 2016-01-01T00:00:00 | 217035.28 | 18880.63                | 17809.46 | 17809.46 | 17809.46 | 18346.28 | 18346.28 | 18346.30 | 15513.04 | 15513.04 | 15513.04 | 14382.76  | 14382.76 | 14382.77 | 
| 1  | Adair          | 2016-01-01T00:00:00 | 87697.37  | 7629.11                 | 7196.26  | 7196.26  | 7196.26  | 7413.17  | 7413.17  | 7413.19  | 6268.34  | 6268.34  | 6268.36  | 5811.64   | 5811.64  | 5811.63  | 
| 1  | Casey          | 2016-01-01T00:00:00 | 0.00      | 0.00                    | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00      | 0.00     | 0.00     | 
| 1  | Stuart         | 2016-01-01T00:00:00 | 66441.94  | 5780.03                 | 5452.08  | 5452.08  | 5452.09  | 5616.42  | 5616.42  | 5616.44  | 4749.07  | 4749.07  | 4749.07  | 4403.06   | 4403.06  | 4403.05  | 
| 1  | Bridgewater    | 2016-01-01T00:00:00 | 18647.67  | 1622.24                 | 1530.18  | 1530.18  | 1530.20  | 1576.31  | 1576.31  | 1576.31  | 1332.88  | 1332.88  | 1332.88  | 1235.77   | 1235.77  | 1235.76  | 
| 1  | Fontanelle     | 2016-01-01T00:00:00 | 71775.11  | 6243.96                 | 5889.71  | 5889.71  | 5889.72  | 6067.24  | 6067.24  | 6067.26  | 5130.27  | 5130.27  | 5130.28  | 4756.48   | 4756.48  | 4756.49  | 
| 1  | Orient         | 2016-01-01T00:00:00 | 41409.32  | 3602.35                 | 3397.96  | 3397.96  | 3397.96  | 3500.38  | 3500.38  | 3500.40  | 2959.81  | 2959.81  | 2959.82  | 2744.16   | 2744.16  | 2744.17  | 
| 1  | Unincorporated | 2016-01-01T00:00:00 | 469314.76 | 40827.13                | 38511.00 | 38511.00 | 38511.01 | 39671.83 | 39671.83 | 39671.84 | 33545.24 | 33545.24 | 33545.25 | 31101.13  | 31101.13 | 31101.13 | 
| 2  | Corning        | 2016-01-01T00:00:00 | 169889.27 | 7531.04                 | 12253.29 | 12253.29 | 12253.30 | 12622.58 | 12622.58 | 12622.59 | 10673.22 | 10673.22 | 10673.24 | 18570.31  | 18570.31 | 18570.30 | 
| 2  | Carbon         | 2016-01-01T00:00:00 | 3305.44   | 146.53                  | 238.40   | 238.40   | 238.41   | 245.59   | 245.59   | 245.59   | 207.66   | 207.66   | 207.67   | 361.31    | 361.31   | 361.32   | 
```