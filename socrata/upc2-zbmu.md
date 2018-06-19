# Oregon Recovery and Reinvestment Act Data - December, 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-recovery-and-reinvestment-act-data-december-2012-1dbd0) |
| Metadata | [Link](https://data.oregon.gov/api/views/upc2-zbmu) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/upc2-zbmu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/upc2-zbmu/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | upc2-zbmu |
| Name | Oregon Recovery and Reinvestment Act Data - December, 2012 |
| Category | Revenue & Expense |
| Created | 2013-01-30T19:56:54Z |
| Publication Date | 2013-01-30T20:09:14Z |

## Description

This data reflects the last update that will be provided on Data.Oregon.Gov. For subsequent updates, please visit http://www.recovery.gov/.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | numeric metric | sort_order             | SORT ORDER             | number        | text          |
| Yes      | series tag     | award_description      | AWARD DESCRIPTION      | text          | text          |
| Yes      | series tag     | project_description    | PROJECT DESCRIPTION    | text          | text          |
| Yes      | series tag     | category               | CATEGORY               | text          | text          |
| Yes      | series tag     | root_id                | ROOT ID                | text          | text          |
| Yes      | series tag     | prime_number           | PRIME NUMBER           | text          | text          |
| Yes      | series tag     | prime_agency           | PRIME AGENCY           | text          | text          |
| Yes      | series tag     | award_id               | AWARD ID               | text          | number        |
| Yes      | series tag     | award_number           | AWARD NUMBER           | text          | text          |
| Yes      | series tag     | awrd_instrument_id     | AWRD INSTRUMENT ID     | text          | text          |
| Yes      | time           | project_id             | PROJECT ID             | calendar_date | calendar_date |
| Yes      | series tag     | recipient_type         | RECIPIENT TYPE         | text          | text          |
| Yes      | series tag     | award_recipient        | AWARD RECIPIENT        | text          | text          |
| Yes      | numeric metric | award_amount           | AWARD AMOUNT           | money         | money         |
| Yes      | numeric metric | amt_expended           | AMT EXPENDED           | money         | money         |
| Yes      | numeric metric | jobs_created           | JOBS CREATED           | number        | number        |
| Yes      | series tag     | proj_name              | PROJ_NAME              | text          | text          |
| Yes      | series tag     | project_status         | PROJECT STATUS         | text          | text          |
| Yes      | series tag     | county                 | COUNTY                 | text          | text          |
| Yes      | series tag     | zipcode                | ZIPCODE                | text          | text          |
| Yes      | series tag     | congressional_district | CONGRESSIONAL DISTRICT | text          | text          |
| No       |                | address                | ADDRESS                | text          | text          |
| Yes      | series tag     | city                   | CITY                   | text          | text          |
| Yes      | series tag     | state                  | STATE                  | text          | text          |
```

## Time Field

```ls
Value = project_id
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:upc2-zbmu d:2013-01-30T11:56:59.000Z t:prime_agency="OR Business Development Department" t:award_number=OR-00J03801 t:project_status=Completed t:root_id=5 t:prime_number=00J03801 t:zipcode=97365-4338 t:state=OR t:awrd_instrument_id=Q10002 t:recipient_type=SUB t:award_id=6062 t:congressional_district=05 t:proj_name="Port of Newport's International Terminal Clean-up" t:project_description="Port of Newport's International Terminal Clean-up- Award ID:6062" t:city=NEWPORT t:category="Natural Resources" t:award_description="Brownfields Clean-up" t:county=Lincoln t:award_recipient="Port of Newport" m:award_amount=200000 m:amt_expended=200000 m:jobs_created=0.68 m:sort_order=2

series e:upc2-zbmu d:2013-01-30T11:56:59.000Z t:prime_agency="OR Business Development Department" t:award_number=OR-00J03801 t:project_status=Completed t:root_id=5 t:prime_number=00J03801 t:zipcode=97526-2000 t:state=OR t:awrd_instrument_id=Q10003 t:recipient_type=SUB t:award_id=9245 t:congressional_district=02 t:proj_name="Grant Pass River Road Reserve Clean-up Project" t:project_description="Grant Pass River Road Reserve Clean-up Project- Award ID:9245" t:city="GRANTS PASS" t:category="Natural Resources" t:award_description="Brownfields Clean-up" t:county=Josephine t:award_recipient="City of Grants Pass" m:award_amount=220938 m:amt_expended=220938 m:jobs_created=0 m:sort_order=5

series e:upc2-zbmu d:2013-01-30T11:56:59.000Z t:prime_agency="OR Business Development Department" t:award_number=OR-00J03801 t:project_status=Completed t:root_id=5 t:prime_number=00J03801 t:zipcode=97463 t:state=OR t:awrd_instrument_id=Q10004 t:recipient_type=SUB t:award_id=9247 t:congressional_district=04 t:proj_name="Oakridge Industrial Park Clean-up project" t:project_description="Oakridge Industrial Park Clean-up project- Award ID:9247" t:city=OAKRIDGE t:category="Natural Resources" t:award_description="Brownfields Clean-up" t:county=Lane t:award_recipient="City of Oakridge" m:award_amount=160000 m:amt_expended=160000 m:jobs_created=0.95 m:sort_order=9
```

## Meta Commands

```ls
metric m:sort_order p:long l:"SORT ORDER" t:dataTypeName=number

metric m:award_amount p:double l:"AWARD AMOUNT" t:dataTypeName=money

metric m:amt_expended p:double l:"AMT EXPENDED" t:dataTypeName=money

metric m:jobs_created p:float l:"JOBS CREATED" t:dataTypeName=number

entity e:upc2-zbmu l:"Oregon Recovery and Reinvestment Act Data - December, 2012" t:url=https://data.oregon.gov/api/views/upc2-zbmu

property e:upc2-zbmu t:meta.view v:id=upc2-zbmu v:category="Revenue & Expense" v:averageRating=0 v:name="Oregon Recovery and Reinvestment Act Data - December, 2012"

property e:upc2-zbmu t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:upc2-zbmu t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| sort_order | award_description            | project_description                                                   | category          | root_id | prime_number       | prime_agency                       | award_id | award_number          | awrd_instrument_id | project_id | recipient_type | award_recipient                                       | award_amount | amt_expended | jobs_created | proj_name                                              | project_status  | county    | zipcode    | congressional_district | address                      | city        | state | 
| ========== | ============================ | ===================================================================== | ================= | ======= | ================== | ================================== | ======== | ===================== | ================== | ========== | ============== | ===================================================== | ============ | ============ | ============ | ====================================================== | =============== | ========= | ========== | ====================== | ============================ | =========== | ===== | 
| 2          | Brownfields Clean-up         | Port of Newport's International Terminal Clean-up- Award ID:6062      | Natural Resources | 5       | 00J03801           | OR Business Development Department | 6062     | OR-00J03801           | Q10002             |            | SUB            | Port of Newport                                       | 200000.00    | 200000.00    | 0.68         | Port of Newport's International Terminal Clean-up      | Completed       | Lincoln   | 97365-4338 | 05                     | 1430 SE BAY BLVD             | NEWPORT     | OR    | 
| 5          | Brownfields Clean-up         | Grant Pass River Road Reserve Clean-up Project- Award ID:9245         | Natural Resources | 5       | 00J03801           | OR Business Development Department | 9245     | OR-00J03801           | Q10003             |            | SUB            | City of Grants Pass                                   | 220938.00    | 220938.00    | 0.00         | Grant Pass River Road Reserve Clean-up Project         | Completed       | Josephine | 97526-2000 | 02                     | 3676 UPPER RIVER ROAD        | GRANTS PASS | OR    | 
| 9          | Brownfields Clean-up         | Oakridge Industrial Park Clean-up project- Award ID:9247              | Natural Resources | 5       | 00J03801           | OR Business Development Department | 9247     | OR-00J03801           | Q10004             |            | SUB            | City of Oakridge                                      | 160000.00    | 160000.00    | 0.95         | Oakridge Industrial Park Clean-up project              | Completed       | Lane      | 97463      | 04                     | 48513 OREGON HWY 58          | OAKRIDGE    | OR    | 
| 13         | Community Development Grants | Haines Wastewater System Improvements- Award ID:1                     | Community Service | 6       | B-09-DY-41-0001    | OR Business Development Department | 1        | OR-B-09-DY-41-0001    | CR0901             |            | SUB            | City of Haines                                        | 1249650.00   | 1249650.00   | 0.22         | Haines Wastewater System Improvements                  | Completed       | Baker     | 978330208  | 02                     | 819 Front Street             | Haines      | OR    | 
| 17         | Community Development Grants | Silverton Senior Center- Award ID:2                                   | Community Service | 6       | B-09-DY-41-0001    | OR Business Development Department | 2        | OR-B-09-DY-41-0001    | CR0902             |            | SUB            | City of Silverton                                     | 1095000.00   | 1095000.00   | 0.35         | Silverton Senior Center                                | Completed       | Marion    | 973812002  | 05                     | 306 S Water Street           | Silverton   | OR    | 
| 19         | Community Development Grants | Hebo Water System Upgrades- Award ID:11                               | Community Service | 6       | B-09-DY-41-0001    | OR Business Development Department | 11       | OR-B-09-DY-41-0001    | CR0903             |            | SUB            | Tillamook County                                      | 1216132.00   | 1060009.00   | 0.00         | Hebo Water System Upgrades                             | Completed       | Tillamook | 97122      | 05                     | 307550 Hwy. 101 S.           | Hebo        | OR    | 
| 23         | Biomass Grant                | Wood Fuel Pellet Facility in Grant and Harney Counties- Award ID:3955 | Natural Resources | 7       | 09-DG-11060489-066 | OR Business Development Department | 3955     | OR-09-DG-11060489-066 | 031800038          |            | SUB            | Ochoco Lumber Company                                 | 4890000.00   | 4890000.00   | 0.00         | Wood Fuel Pellet Facility in Grant and Harney Counties | Completed       | Grant     | 97845-1238 | 02                     | 450 EAST MAIN STREET         | JOHN DAY    | OR    | 
| 46         | Byrne JAG                    | M57 Benton County Treatment Court- Award ID:4021                      | Public Safety     | 12      | 2009-SU-B9-0060    | OR Criminal Justice Commission     | 4021     | OR-2009-SU-B9-0060    | m57002-09jag       |            | SUB            | Benton County                                         | 144053.00    | 15296.53     | 0.00         | M57 Benton County Treatment Court                      | Behind Schedule | Benton    | 97333-4712 | 05                     | 110 SW 4TH STREET            | CORVALLIS   | OR    | 
| 47         | Byrne JAG                    | M57 Douglas County Treatment Court- Award ID:4023                     | Public Safety     | 12      | 2009-SU-B9-0060    | OR Criminal Justice Commission     | 4023     | OR-2009-SU-B9-0060    | m57010-09jag       |            | SUB            | Oregon Department of Corrections (for Douglas County) | 492387.00    | 446644.55    | 0.25         | M57 Douglas County Treatment Court                     | On Schedule     | Douglas   | 97470-3301 | 04                     | 1036 SE DOUGLAS JUSTICE BLDG | ROSEBURG    | OR    | 
| 48         | Byrne JAG                    | M57 Jackson County Treatment Court- Award ID:4029                     | Public Safety     | 12      | 2009-SU-B9-0060    | OR Criminal Justice Commission     | 4029     | or-2009-su-b9-0060    | m57015-09jag       |            | SUB            | jackson county community justice                      | 1112016.00   | 860677.67    | 0.00         | M57 Jackson County Treatment Court                     | On Schedule     | Jackson   | 97501-2932 | 02                     | 1101 W MAIN ST               | MEDFORD     | OR    | 
```