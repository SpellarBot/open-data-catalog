# Oregon Recovery and Reinvestment Act Data - June, 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-recovery-and-reinvestment-act-data-june-2012-371c3) |
| Metadata | [Link](https://data.oregon.gov/api/views/r74f-dpgp) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/r74f-dpgp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/r74f-dpgp/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | r74f-dpgp |
| Name | Oregon Recovery and Reinvestment Act Data - June, 2012 |
| Category | Revenue & Expense |
| Created | 2012-08-08T20:56:38Z |
| Publication Date | 2012-08-08T21:00:58Z |

## Description

This spreadsheet contains Oregon Recovery and Reinvestment Act (ARRA) Data reported on the State of Oregon Recovery site (http://oregon.gov/recovery/StimulusReporting/ARRA_Projects.shtml). Please note that this data reflects the preliminary data from the most recent reporting period of the American Recovery and Reinvestment Act of 2009, including data through March 30, 2011. This data available for viewing through an interactive map site. For this, and other information on ARRA projects, please visit Oregon's Economic Recovery site: http://www.oregon.gov/recovery. For the latest recovery award data, please visit http://www.recovery.gov.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | numeric metric | sort_order             | SORT ORDER             | number    | number      |
| Yes      | series tag     | award_description      | AWARD DESCRIPTION      | text      | text        |
| Yes      | series tag     | project_description    | PROJECT DESCRIPTION    | text      | text        |
| Yes      | series tag     | root_id                | ROOT ID                | text      | number      |
| Yes      | series tag     | prime_award            | PRIME AWARD #          | text      | text        |
| Yes      | series tag     | award_id               | AWARD ID               | text      | number      |
| Yes      | series tag     | award_number           | AWARD NUMBER           | text      | text        |
| Yes      | series tag     | project_id             | PROJECT ID             | text      | text        |
| Yes      | series tag     | award_instrument       | AWARD INSTRUMENT       | text      | text        |
| Yes      | series tag     | recipient_type         | RECIPIENT TYPE         | text      | text        |
| Yes      | series tag     | vendor                 | VENDOR                 | text      | text        |
| Yes      | series tag     | county                 | COUNTY                 | text      | text        |
| Yes      | series tag     | project_name           | PROJECT NAME           | text      | text        |
| Yes      | series tag     | award_recipient        | AWARD RECIPIENT        | text      | text        |
| Yes      | numeric metric | award_amount           | AWARD AMOUNT           | number    | number      |
| Yes      | numeric metric | amount_expended        | AMOUNT EXPENDED        | number    | number      |
| Yes      | numeric metric | jobs_created           | JOBS CREATED           | number    | number      |
| Yes      | series tag     | project_status         | PROJECT STATUS         | text      | text        |
| Yes      | series tag     | zipcode                | ZIPCODE                | text      | text        |
| Yes      | series tag     | congressional_district | CONGRESSIONAL DISTRICT | text      | number      |
| Yes      | series tag     | month_code             | MONTH CODE             | text      | text        |
| Yes      | series tag     | project                | Project                | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:r74f-dpgp d:2012-01-01T00:00:00.000Z t:congressional_district=5 t:award_number=OR-00J03801 t:award_recipient="Port of Newport" t:county=Lincoln t:project_status=Completed t:prime_award=00J03801 t:project="Port of Newport's International Terminal Clean-up - Award ID#:6062" t:month_code=1106 t:project_name="Port of Newport's International Terminal Clean-up - Award ID#:6062" t:award_id=6062 t:recipient_type=SUB t:zipcode=97365-4338 t:project_description="Port of Newport's International Terminal Clean-up - Award ID: 6062" t:vendor=NO t:award_description="Brownfields Clean-up" t:root_id=5 t:award_instrument=Q10002 m:award_amount=200000 m:amount_expended=200000 m:sort_order=2 m:jobs_created=0

series e:r74f-dpgp d:2012-01-01T00:00:00.000Z t:congressional_district=2 t:award_number=OR-00J03801 t:award_recipient="City of Grants Pass" t:county=Josephine t:project_status=Completed t:prime_award=00J03801 t:project="Grant Pass River Road Reserve Clean-up Project - Award ID#:9245" t:month_code=1203 t:project_name="Grant Pass River Road Reserve Clean-up Project - Award ID#:9245" t:award_id=9245 t:recipient_type=SUB t:zipcode=97526-2000 t:project_description="Grant Pass River Road Reserve Clean-up Project - Award ID: 9245" t:vendor=NO t:award_description="Brownfields Clean-up" t:root_id=5 t:award_instrument=Q10003 m:award_amount=220938 m:amount_expended=220938 m:sort_order=5 m:jobs_created=0

series e:r74f-dpgp d:2012-01-01T00:00:00.000Z t:congressional_district=4 t:award_number=OR-00J03801 t:award_recipient="City of Oakridge" t:county=Lane t:project_status=Completed t:prime_award=00J03801 t:project="Oakridge Industrial Park Clean-up project - Award ID#:9247" t:month_code=1112 t:project_name="Oakridge Industrial Park Clean-up project - Award ID#:9247" t:award_id=9247 t:recipient_type=SUB t:zipcode=97463 t:project_description="Oakridge Industrial Park Clean-up project - Award ID: 9247" t:vendor=NO t:award_description="Brownfields Clean-up" t:root_id=5 t:award_instrument=Q10004 m:award_amount=160000 m:amount_expended=160000 m:sort_order=9 m:jobs_created=0
```

## Meta Commands

```ls
metric m:sort_order p:integer l:"SORT ORDER" t:dataTypeName=number

metric m:award_amount p:double l:"AWARD AMOUNT" t:dataTypeName=number

metric m:amount_expended p:double l:"AMOUNT EXPENDED" t:dataTypeName=number

metric m:jobs_created p:float l:"JOBS CREATED" t:dataTypeName=number

entity e:r74f-dpgp l:"Oregon Recovery and Reinvestment Act Data - June, 2012" t:url=https://data.oregon.gov/api/views/r74f-dpgp

property e:r74f-dpgp t:meta.view d:2017-09-25T07:25:01.233Z v:averageRating=0 v:name="Oregon Recovery and Reinvestment Act Data - June, 2012" v:id=r74f-dpgp v:category="Revenue & Expense"

property e:r74f-dpgp t:meta.view.owner d:2017-09-25T07:25:01.233Z v:displayName="Paula N." v:lastNotificationSeenAt=1500509429 v:id=d6zz-js5q v:screenName="Paula N."

property e:r74f-dpgp t:meta.view.tableauthor d:2017-09-25T07:25:01.233Z v:displayName="Paula N." v:lastNotificationSeenAt=1500509429 v:roleName=administrator v:id=d6zz-js5q v:screenName="Paula N."
```

## Top Records

```ls
| sort_order | award_description            | project_description                                                             | root_id | prime_award        | award_id | award_number          | project_id | award_instrument | recipient_type | vendor | county    | project_name                                                                    | award_recipient                  | award_amount | amount_expended | jobs_created | project_status | zipcode    | congressional_district | month_code | project                                                                         | 
| ========== | ============================ | =============================================================================== | ======= | ================== | ======== | ===================== | ========== | ================ | ============== | ====== | ========= | =============================================================================== | ================================ | ============ | =============== | ============ | ============== | ========== | ====================== | ========== | =============================================================================== | 
| 2          | Brownfields Clean-up         | Port of Newport's International Terminal Clean-up - Award ID: 6062              | 5       | 00J03801           | 6062     | OR-00J03801           |            | Q10002           | SUB            | NO     | Lincoln   | Port of Newport's International Terminal Clean-up - Award ID#:6062              | Port of Newport                  | 200000.00    | 200000.00       | 0.00         | Completed      | 97365-4338 | 5                      | 1106       | Port of Newport's International Terminal Clean-up - Award ID#:6062              | 
| 5          | Brownfields Clean-up         | Grant Pass River Road Reserve Clean-up Project - Award ID: 9245                 | 5       | 00J03801           | 9245     | OR-00J03801           |            | Q10003           | SUB            | NO     | Josephine | Grant Pass River Road Reserve Clean-up Project - Award ID#:9245                 | City of Grants Pass              | 220938.00    | 220938.00       | 0.00         | Completed      | 97526-2000 | 2                      | 1203       | Grant Pass River Road Reserve Clean-up Project - Award ID#:9245                 | 
| 9          | Brownfields Clean-up         | Oakridge Industrial Park Clean-up project - Award ID: 9247                      | 5       | 00J03801           | 9247     | OR-00J03801           |            | Q10004           | SUB            | NO     | Lane      | Oakridge Industrial Park Clean-up project - Award ID#:9247                      | City of Oakridge                 | 160000.00    | 160000.00       | 0.00         | Completed      | 97463      | 4                      | 1112       | Oakridge Industrial Park Clean-up project - Award ID#:9247                      | 
| 13         | Community Development Grants | Haines Wastewater System Improvements - Award ID: 1                             | 6       | B-09-DY-41-0001    | 1        | OR-B-09-DY-41-0001    |            | CR0901           | SUB            | NO     | Baker     | Haines Wastewater System Improvements - Award ID#:1                             | City of Haines                   | 1249650.00   | 1249650.00      | 0.19         | Completed      | 978330208  | 2                      | 1203       | Haines Wastewater System Improvements - Award ID#:1                             | 
| 17         | Community Development Grants | Silverton Senior Center - Award ID: 2                                           | 6       | B-09-DY-41-0001    | 2        | OR-B-09-DY-41-0001    |            | CR0902           | SUB            | NO     | Marion    | Silverton Senior Center - Award ID#:2                                           | City of Silverton                | 1095000.00   | 1095000.00      | 0.19         | Completed      | 973812002  | 5                      | 1112       | Silverton Senior Center - Award ID#:2                                           | 
| 19         | Community Development Grants | Hebo Water System Upgrades - Award ID: 11                                       | 6       | B-09-DY-41-0001    | 11       | OR-B-09-DY-41-0001    |            | CR0903           | SUB            | NO     | Tillamook | Hebo Water System Upgrades - Award ID#:11                                       | Tillamook County                 | 1216132.00   | 1060009.00      | 0.19         | Completed      | 97122      | 5                      | 1203       | Hebo Water System Upgrades - Award ID#:11                                       | 
| 23         | Biomass Grant                | Wood Fuel Pellet Facility in Grant and Harney Counties, Oregon - Award ID: 3955 | 7       | 09-DG-11060489-066 | 3955     | OR-09-DG-11060489-066 |            | 031800038        | SUB            | NO     | Grant     | Wood Fuel Pellet Facility in Grant and Harney Counties, Oregon - Award ID#:3955 | Ochoco Lumber Company            | 4890000.00   | 4890000.00      | 0.03         | Completed      | 97845-1238 | 2                      | 1109       | Wood Fuel Pellet Facility in Grant and Harney Counties, Oregon - Award ID#:3955 | 
| 46         | Byrne JAG                    | M57 Benton County Treatment Court - Award ID: 4021                              | 12      | 2009-SU-B9-0060    | 4021     | OR-2009-SU-B9-0060    |            | m57002-09jag     | SUB            | NO     | Benton    | M57 Benton County Treatment Court - Award ID#:4021                              | Benton County                    | 144053.00    | 11145.38        | 0.00         | On Schedule    | 97333-4712 | 5                      | 1206       | M57 Benton County Treatment Court - Award ID#:4021                              | 
| 48         | Byrne JAG                    | M57 Jackson County Treatment Court - Award ID: 4029                             | 12      | 2009-SU-B9-0060    | 4029     | or-2009-su-b9-0060    |            | m57015-09jag     | SUB            | NO     | Jackson   | M57 Jackson County Treatment Court - Award ID#:4029                             | jackson county community justice | 1112016.00   | 711496.80       | 6.37         | On Schedule    | 97501-2932 | 2                      | 1206       | M57 Jackson County Treatment Court - Award ID#:4029                             | 
| 52         | Byrne JAG                    | M57 Multnomah County Treatment Court - Award ID: 4036                           | 12      | 2009-SU-B9-0060    | 4036     | OR-2009-SU-B9-0060    |            | m57026-09jag     | SUB            | NO     | Multnomah | M57 Multnomah County Treatment Court - Award ID#:4036                           | County of Multnomah              | 3074384.00   | 2253184.42      | 13.49        | On Schedule    | 97214-3501 | 3                      | 1206       | M57 Multnomah County Treatment Court - Award ID#:4036                           | 
```