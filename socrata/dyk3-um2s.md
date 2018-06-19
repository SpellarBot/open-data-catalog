# Oregon Recovery and Reinvestment Act Data - September, 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-recovery-and-reinvestment-act-data-september-2012-16147) |
| Metadata | [Link](https://data.oregon.gov/api/views/dyk3-um2s) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/dyk3-um2s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/dyk3-um2s/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | dyk3-um2s |
| Name | Oregon Recovery and Reinvestment Act Data - September, 2012 |
| Category | Administrative |
| Created | 2013-01-03T23:32:12Z |
| Publication Date | 2013-01-03T23:35:58Z |

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | sort_order             | SORT ORDER             | text      | text        |
| Yes      | series tag     | award_description      | AWARD DESCRIPTION      | text      | text        |
| Yes      | series tag     | project_description    | PROJECT DESCRIPTION    | text      | text        |
| Yes      | series tag     | root_id                | ROOT ID                | text      | text        |
| Yes      | series tag     | prime_award            | PRIME AWARD #          | text      | text        |
| Yes      | series tag     | award_id               | AWARD ID               | text      | text        |
| Yes      | series tag     | award_number           | AWARD NUMBER           | text      | text        |
| Yes      | series tag     | award_instrument       | AWARD INSTRUMENT       | text      | text        |
| Yes      | series tag     | project_id             | PROJECT ID             | text      | text        |
| Yes      | series tag     | recipient_type         | RECIPIENT TYPE         | text      | text        |
| Yes      | series tag     | vendor                 | VENDOR                 | text      | text        |
| Yes      | series tag     | county                 | COUNTY                 | text      | text        |
| Yes      | series tag     | project_name           | PROJECT NAME           | text      | text        |
| Yes      | series tag     | award_recipient_1      | AWARD RECIPIENT        | text      | text        |
| Yes      | series tag     | category               | Category               | text      | text        |
| Yes      | series tag     | award_recipient_2      | Award Recipient        | text      | text        |
| Yes      | numeric metric | award_amount           | Award Amount           | money     | money       |
| Yes      | numeric metric | amount_expended        | Amount Expended        | money     | money       |
| Yes      | numeric metric | jobs_created           | Jobs Created           | number    | number      |
| Yes      | series tag     | project_status         | Project Status         | text      | text        |
| No       |                | address_location       | ADDRESS/LOCATION       | text      | text        |
| Yes      | series tag     | city                   | CITY                   | text      | text        |
| Yes      | series tag     | state                  | STATE                  | text      | text        |
| Yes      | series tag     | zipcode                | ZIPCODE                | text      | text        |
| Yes      | series tag     | congressional_district | Congressional District | text      | number      |
| Yes      | series tag     | month_code             | Month Code             | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address_location
```

## Data Commands

```ls
series e:dyk3-um2s d:2012-01-01T00:00:00.000Z t:project_status=Completed t:project_name="Haines Wastewater System Improvements" t:award_number=OR-B-09-DY-41-0001 t:vendor=NO t:root_id=6 t:award_instrument=CR0901 t:zipcode=978330208 t:state=OR t:recipient_type=SUB t:award_id=1 t:congressional_district=2 t:project_description="Haines Wastewater System Improvements - Award ID: 1" t:city=Haines t:category="Community Service" t:award_description="Community Development Grants" t:month_code=1203 t:county=Baker t:award_recipient_2="City of Haines" t:prime_award=B-09-DY-41-0001 t:sort_order=13 t:award_recipient_1="OR Business Development Department" m:amount_expended=1249650 m:award_amount=1249650 m:jobs_created=0

series e:dyk3-um2s d:2012-01-01T00:00:00.000Z t:project_status=Completed t:project_name="Hebo Water System Upgrades" t:award_number=OR-B-09-DY-41-0001 t:vendor=NO t:root_id=6 t:award_instrument=CR0903 t:zipcode=97122 t:state=OR t:recipient_type=SUB t:award_id=11 t:congressional_district=5 t:project_description="Hebo Water System Upgrades - Award ID: 11" t:city=Hebo t:category="Community Service" t:award_description="Community Development Grants" t:month_code=1203 t:county=Tillamook t:award_recipient_2="Tillamook County" t:prime_award=B-09-DY-41-0001 t:sort_order=19 t:award_recipient_1="OR Business Development Department" m:amount_expended=1060009 m:award_amount=1216132 m:jobs_created=0

series e:dyk3-um2s d:2012-01-01T00:00:00.000Z t:project_status=Completed t:project_name="Silverton Senior Center" t:award_number=OR-B-09-DY-41-0001 t:vendor=NO t:root_id=6 t:award_instrument=CR0902 t:zipcode=973812002 t:state=OR t:recipient_type=SUB t:award_id=2 t:congressional_district=5 t:project_description="Silverton Senior Center - Award ID: 2" t:city=Silverton t:category="Community Service" t:award_description="Community Development Grants" t:month_code=1112 t:county=Marion t:award_recipient_2="City of Silverton" t:prime_award=B-09-DY-41-0001 t:sort_order=17 t:award_recipient_1="OR Business Development Department" m:amount_expended=1095000 m:award_amount=1095000 m:jobs_created=0
```

## Meta Commands

```ls
metric m:award_amount p:double l:"Award Amount" t:dataTypeName=money

metric m:amount_expended p:double l:"Amount Expended" t:dataTypeName=money

metric m:jobs_created p:integer l:"Jobs Created" t:dataTypeName=number

entity e:dyk3-um2s l:"Oregon Recovery and Reinvestment Act Data - September, 2012" t:url=https://data.oregon.gov/api/views/dyk3-um2s

property e:dyk3-um2s t:meta.view v:id=dyk3-um2s v:category=Administrative v:averageRating=0 v:name="Oregon Recovery and Reinvestment Act Data - September, 2012"

property e:dyk3-um2s t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:dyk3-um2s t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| sort_order | award_description               | project_description                                                                         | root_id | prime_award         | award_id | award_number       | award_instrument | project_id | recipient_type | vendor | county    | project_name                                                               | award_recipient_1                  | category          | award_recipient_2                            | award_amount | amount_expended | jobs_created | project_status | address_location         | city        | state | zipcode    | congressional_district | month_code | 
| ========== | =============================== | =========================================================================================== | ======= | =================== | ======== | ================== | ================ | ========== | ============== | ====== | ========= | ========================================================================== | ================================== | ================= | ============================================ | ============ | =============== | ============ | ============== | ======================== | =========== | ===== | ========== | ====================== | ========== | 
| 13         | Community Development Grants    | Haines Wastewater System Improvements - Award ID: 1                                         | 6       | B-09-DY-41-0001     | 1        | OR-B-09-DY-41-0001 | CR0901           |            | SUB            | NO     | Baker     | Haines Wastewater System Improvements                                      | OR Business Development Department | Community Service | City of Haines                               | 1249650.00   | 1249650.00      | 0            | Completed      | 819 Front Street         | Haines      | OR    | 978330208  | 2                      | 1203       | 
| 19         | Community Development Grants    | Hebo Water System Upgrades - Award ID: 11                                                   | 6       | B-09-DY-41-0001     | 11       | OR-B-09-DY-41-0001 | CR0903           |            | SUB            | NO     | Tillamook | Hebo Water System Upgrades                                                 | OR Business Development Department | Community Service | Tillamook County                             | 1216132.00   | 1060009.00      | 0            | Completed      | 307550 Hwy. 101 S.       | Hebo        | OR    | 97122      | 5                      | 1203       | 
| 17         | Community Development Grants    | Silverton Senior Center - Award ID: 2                                                       | 6       | B-09-DY-41-0001     | 2        | OR-B-09-DY-41-0001 | CR0902           |            | SUB            | NO     | Marion    | Silverton Senior Center                                                    | OR Business Development Department | Community Service | City of Silverton                            | 1095000.00   | 1095000.00      | 0            | Completed      | 306 S Water Street       | Silverton   | OR    | 973812002  | 5                      | 1112       | 
| 13,279     | National Endowment for the Arts | Arts and the American Recovery & Reinvestment Act of 2009 - Award ID: 2372                  | 2,377   | 09-6188-2099        | 2,372    | OR-09-6188-2099    | FY10-ARRA-9006   |            | SUB            | NO     | Multnomah | Arts and the American Recovery & Reinvestment Act of 2009                  | OR Business Development Department | Community Service | Museum of Contemporary Craft                 | 30000.00     | 30000.00        | 0            | Completed      | 724 NW Davis Street      | Portland    | OR    | 97209-9999 | 1                      | 1009       | 
| 13,280     | National Endowment for the Arts | Arts and the American Recovery & Reinvestment Act of 2009 - Award ID: 2374                  | 2,377   | 09-6188-2099        | 2,374    | OR-09-6188-2099    | FY10-ARRA-9005   |            | SUB            | NO     | Lincoln   | Arts and the American Recovery & Reinvestment Act of 2009                  | OR Business Development Department | Community Service | Neskowin Coast Foundation                    | 30000.00     | 30000.00        | 0            | Completed      | 56605 Sitka Drive        | Otis        | OR    | 97368-9999 | 5                      | 1009       | 
| 13,281     | National Endowment for the Arts | Arts and the American Recovery & Reinvestment Act of 2009 - Award ID: 2375                  | 2,377   | 09-6188-2099        | 2,375    | OR-09-6188-2099    | FY10-ARRA-8975   |            | SUB            | NO     | Jackson   | Arts and the American Recovery & Reinvestment Act of 2009                  | OR Business Development Department | Community Service | Southern Oregon Film Society                 | 29000.00     | 29000.00        | 0            | Completed      | 295 East Main Street #10 | Ashland     | OR    | 97520-9999 | 2                      | 1009       | 
| 13,282     | National Endowment for the Arts | Preserve The Arts Center (Linn-Benton County) executive director position. - Award ID: 2376 | 2,377   | 09-6188-2099        | 2,376    | OR-09-6188-2099    | FY10-ARRA-8973   |            | SUB            | NO     | Benton    | Preserve The Arts Center (Linn-Benton County) executive director position. | OR Business Development Department | Community Service | The Arts Center                              | 26000.00     | 26000.00        | 0            | Completed      | 700 SW Madison Avenue    | Corvallis   | OR    | 97333-4599 | 5                      | 1009       | 
| 13,325     | Elderly Employment              | Older Workers Program. - Award ID: 2593                                                     | 2,589   | AD-18388-09-60-A-41 | 2,593    | OR-AD183880960A41  | SMS-OAA          |            | SUB            | NO     | Multnomah | Older Workers Program.                                                     | OR Department of Human Services    | Community Service | Specialty Mobility Services, INC             | 131879.00    | 131879.00       | 0            | Completed      | 2101 NE Flanders St.     | Portland    | OR    | 97232-2811 | 3                      | 1012       | 
| 13,322     | Elderly Employment              | Senior Community Service Employment Program - Award ID: 2590                                | 2,589   | AD-18388-09-60-A-41 | 2,590    | OR-AD183880960A41  | CCSS-OAA         |            | SUB            | NO     | Clackamas | Senior Community Service Employment Program                                | OR Department of Human Services    | Community Service | Clackamas County                             | 36447.00     | 36447.00        | 0            | Completed      | 2051 Kaen Road           | Oregon City | OR    | 97045-4035 | 5                      | 1012       | 
| 13,323     | Elderly Employment              | Senior Community Service Employment Program - Award ID: 2591                                | 2,589   | AD-18388-09-60-A-41 | 2,591    | OR-AD183880960A41  | CAPEC0-OAA       |            | SUB            | NO     | Umatilla  | Senior Community Service Employment Program                                | OR Department of Human Services    | Community Service | Community Action Program East Central Oregon | 37680.00     | 37679.72        | 0            | Completed      | 721 SE 3rd, Suite D      | Pendleton   | OR    | 97801-3060 | 2                      | 1012       | 
```