# Building and Trades Permits 01012011 to Current

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-and-trades-permits-01012011-to-current) |
| Metadata | [Link](https://data.hartford.gov/api/views/p2vw-4aab) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/p2vw-4aab/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/p2vw-4aab/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | p2vw-4aab |
| Name | Building and Trades Permits 01012011 to Current |
| Attribution | City of Hartford |
| Category | Housing / Development |
| Tags | building, housing, development services, permits |
| Created | 2016-09-08T18:11:18Z |
| Publication Date | 2016-11-22T20:01:44Z |

## Description

Building and Trades Permits 01012011 to Current updates nightly

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | permit_number      | PERMIT NUMBER      | text      | text        |
| Yes      | time           | apply_date         | APPLY DATE         | date      | date        |
| No       |                | issue_date         | ISSUE DATE         | date      | date        |
| No       |                | expire_date        | EXPIRE DATE        | date      | date        |
| Yes      | numeric metric | value              | VALUE              | money     | money       |
| Yes      | series tag     | work_description   | WORK DESCRIPTION   | text      | text        |
| Yes      | series tag     | work_class         | WORK CLASS         | text      | text        |
| Yes      | series tag     | division           | DIVISION           | text      | text        |
| Yes      | series tag     | parcelid           | PARCELID           | text      | text        |
| Yes      | series tag     | status             | STATUS             | text      | text        |
| Yes      | series tag     | permit_type        | PERMIT TYPE        | text      | text        |
| No       |                | address            | ADDRESS            | text      | text        |
| Yes      | series tag     | unit_or_suite      | UNIT or SUITE      | text      | text        |
| Yes      | series tag     | global_entity_name | GLOBAL ENTITY NAME | text      | text        |
| Yes      | series tag     | first_name         | FIRST NAME         | text      | text        |
| Yes      | series tag     | last_name          | LAST NAME          | text      | text        |
```

## Time Field

```ls
Value = apply_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = issue_date,expire_date,address
```

## Data Commands

```ls
series e:p2vw-4aab d:2013-01-29T00:00:00.000Z t:parcelid=246363463 t:global_entity_name="HPI BUSHNELL LLC" t:permit_number=20130397-C020 t:permit_type="Certificate of Completion" t:division="Building (L&I)/(DPW) - Residential, HCE CAO, HPA" t:status=Issued t:unit_or_suite=R902 t:work_class=Residential t:work_description="REPLACE SHEETROCK THAT HAS ALREADY BEEN REMOVED BY | RESTORATION COMPANY DUE TO WATER DAMAGE.MUNIS Permit Number: 20144243" m:value=1800

series e:p2vw-4aab d:2012-10-03T00:00:00.000Z t:parcelid=189737118 t:global_entity_name="DONAYRE RICARDO" t:permit_number=20124170-C000 t:permit_type="Certificate of Occupancy" t:division="Building (L&I)/(DPW) - Residential, HCE CAO, HPA" t:status=Issued t:work_class=Residential t:work_description="NEW KITCHEN CABINETS SHEETROCK IN THE 2ND FL BEDRD & HALLWAL | DOORS INTERIOR, TILESMUNIS Permit Number: 20120207" m:value=6000

series e:p2vw-4aab d:2016-08-01T12:02:32.000Z t:parcelid=174152083 t:first_name=ADELAID t:permit_number=BT-RESBLD-2016-00251 t:permit_type="Building (Residential)" t:division="Building (L&I) - Alteration" t:status=Issued t:last_name=MILLER t:work_class=Alteration t:work_description="INSTALLATION OF (26) ROOF MOUNTED SOLAR PANELS." m:value=10140
```

## Meta Commands

```ls
metric m:value p:integer l:VALUE t:dataTypeName=money

entity e:p2vw-4aab l:"Building and Trades Permits 01012011 to Current" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/p2vw-4aab

property e:p2vw-4aab t:meta.view v:id=p2vw-4aab v:category="Housing / Development" v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="Building and Trades Permits 01012011 to Current" v:attribution="City of Hartford"

property e:p2vw-4aab t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:p2vw-4aab t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:p2vw-4aab t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| permit_number        | apply_date | issue_date | expire_date | value | work_description                                                                                                                                        | work_class  | division                                         | parcelid  | status | permit_type               | address            | unit_or_suite | global_entity_name         | first_name           | last_name | 
| ==================== | ========== | ========== | =========== | ===== | ======================================================================================================================================================= | =========== | ================================================ | ========= | ====== | ========================= | ================== | ============= | ========================== | ==================== | ========= | 
| 20130397-C020        | 1359417600 | 1410393600 |             | 1800  | REPLACE SHEETROCK THAT HAS ALREADY BEEN REMOVED BY | RESTORATION COMPANY DUE TO WATER DAMAGE.MUNIS Permit Number: 20144243                              | Residential | Building (L&I)/(DPW) - Residential, HCE CAO, HPA | 246363463 | Issued | Certificate of Completion | 100 WELLS ST       | R902          | HPI BUSHNELL LLC           |                      |           | 
| 20124170-C000        | 1349222400 | 1349222400 |             | 6000  | NEW KITCHEN CABINETS SHEETROCK IN THE 2ND FL BEDRD & HALLWAL | DOORS INTERIOR, TILESMUNIS Permit Number: 20120207                                       | Residential | Building (L&I)/(DPW) - Residential, HCE CAO, HPA | 189737118 | Issued | Certificate of Occupancy  | 218 FREEMAN ST     |               | DONAYRE RICARDO            |                      |           | 
| BT-RESBLD-2016-00251 | 1470052952 | 1470182400 | 1485734400  | 10140 | INSTALLATION OF (26) ROOF MOUNTED SOLAR PANELS.                                                                                                         | Alteration  | Building (L&I) - Alteration                      | 174152083 | Issued | Building (Residential)    | 109 RIDGEFIELD ST  |               |                            | ADELAID              | MILLER    | 
| 20120140-P000        | 1326067200 | 1328054400 | 1343606400  | 1000  | INSTALL 4" PVC BWV ON STORM PIPE IN BASEMENT SUMP PIT TO | 5' OUTSIDEMUNIS Permit Number: 20120075                                                      | Residential | Building (L&I)/(DPW) - Residential, HCE CAO, HPA | 149078082 | Issued | Plumbing                  | 216 WESTMINSTER ST |               |                            | ARNOLD GROUP LLC     |           | 
| 20115993-E000        | 1325116800 | 1327536000 | 1343088000  | 10000 | ELECTRICAL WIRING INSTALLATION OF BRANCH CIRCUITS POWER, | LIGHTING, HVAC SERVICE, SMOKE DETECTORS, PHONE & CATVMUNIS Permit Number: 20120095           | Residential | Building (L&I)/(DPW) - Residential, HCE CAO, HPA | 271466061 | Issued | Electrical                | 52 POPIELUSZKO CT  |               | CIL AFFORDABLE HOUSING INC |                      |           | 
| 20131277-E000        | 1364860800 | 1364860800 | 1380412800  | 1800  | REPLACE CEILING LIGHTS IN BATHROOM, REPLACE CEILING EXHAUST | FAN/LIGHT COMBO, CHECK OUTLETS & SWITCHES & WALL LIGHT ABOVEMUNIS Permit Number: 20131508 | Commercial  | Building (L&I)/(DPW) - Commercial                | 111365029 | Issued | Electrical                | 641 FARMINGTON AV  |               |                            | OLIVA'S ELECTRIC LLC |           | 
| 20120210-B000        | 1326758400 | 1327536000 | 1343088000  | 1000  | EXISTING FINISHED BASEMENT WITH BATHROOM TO REMAIN, | WILL REMOVE EXISTING BASEMENT KITCHENMUNIS Permit Number: 20120063                                | Alteration  | Building (L&I) - Alteration                      | 120702061 | Issued | Building (Residential)    | 98 ROSLYN ST       |               | RODRIGUEZ GLORIA           |                      |           | 
| 20120139-P000        | 1326067200 | 1328054400 | 1343606400  | 1000  | INSTALL 4" PVC BWV ON STORM PIPE IN BASEMENT SUMP PIT TO | 5' OUTSIDEMUNIS Permit Number: 20120074                                                      | Residential | Building (L&I)/(DPW) - Residential, HCE CAO, HPA | 148078001 | Issued | Plumbing                  | 208 WESTMINSTER ST |               |                            | ARNOLD GROUP LLC     |           | 
| 20112476-B000        | 1307923200 | 1308700800 | 1324252800  | 4000  | RE-DO ROOF PAPER FELT SHINGLES PLYWOOD EMERGENCY REPAIR | ROOF LEAKINGMUNIS Permit Number: 20110610                                                     | Alteration  | Building (L&I) - Alteration                      | 210754070 | Issued | Building (Residential)    | 36 FREEMAN ST      |               | PEREZ JUAN A               |                      |           | 
| 20110297-E000        | 1296172800 | 1296691200 | 1312243200  | 6000  | KITCHEN RE-WIRE (1ST FLOOR - ONE FAMILY )MUNIS Permit Number: 20110057                                                                                  | Residential | Building (L&I)/(DPW) - Residential, HCE CAO, HPA | 132311111 | Issued | Electrical                | 80 ELIZABETH ST    |               |                            | IHS ELECTRIC LLC     |           | 
```