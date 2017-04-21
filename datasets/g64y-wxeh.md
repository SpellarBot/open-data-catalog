# Contracts: Transportation: As of June 30, 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-transportation-as-of-june-30-2010-b5e76) |
| Metadata | [Link](https://data.oregon.gov/api/views/g64y-wxeh) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/g64y-wxeh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/g64y-wxeh/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | g64y-wxeh |
| Name | Contracts: Transportation: As of June 30, 2010 |
| Category | Revenue & Expense |
| Created | 2011-02-14T20:59:37Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | series tag     | contract_id      | Contract_ID      | text          | text          |
| Yes      | series tag     | project_name     | Project_Name     | text          | text          |
| Yes      | series tag     | fed_state_number | Fed_State_Number | text          | text          |
| Yes      | time           | award_date       | Award_Date       | calendar_date | calendar_date |
| Yes      | numeric metric | contract_amount  | Contract_Amount  | money         | money         |
| Yes      | series tag     | vendor_name      | Vendor_Name      | text          | text          |
```

## Time Field

```ls
Value = award_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:g64y-wxeh d:2009-07-06T00:00:00.000Z t:project_name="SALEM AVE: SHERMAN ST-UP RAILROAD PAVEMENT OVERLAY" t:fed_state_number=X-STP-0100(030) t:contract_id=14073 t:vendor_name="NORTH SANTIAM PAVING CO." m:contract_amount=765616

series e:g64y-wxeh d:2009-07-06T00:00:00.000Z t:project_name="BAKER CREEK RD: MICHELBOOK LANE - POWER HOUSE HILL RD" t:fed_state_number=X-STP-C071(014) t:contract_id=14078 t:vendor_name="NORTH SANTIAM PAVING CO." m:contract_amount=667260

series e:g64y-wxeh d:2009-07-07T00:00:00.000Z t:project_name="US30: HAVLIK DRIVE INT./HAVLIK DR. EXTENSION" t:fed_state_number=X-STP-OTIA-S092(029) t:contract_id=14064 t:vendor_name="R & R GENERAL CONTRACTORS, INC." m:contract_amount=1232517.09
```

## Meta Commands

```ls
metric m:contract_amount p:double l:Contract_Amount t:dataTypeName=money

entity e:g64y-wxeh l:"Contracts: Transportation: As of June 30, 2010" t:url=https://data.oregon.gov/api/views/g64y-wxeh

property e:g64y-wxeh t:meta.view v:id=g64y-wxeh v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: Transportation: As of June 30, 2010"

property e:g64y-wxeh t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:g64y-wxeh t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| contract_id | project_name                                          | fed_state_number     | award_date          | contract_amount | vendor_name                        | 
| =========== | ===================================================== | ==================== | =================== | =============== | ================================== | 
| 14073       | SALEM AVE: SHERMAN ST-UP RAILROAD PAVEMENT OVERLAY    | X-STP-0100(030)      | 2009-07-06T00:00:00 | 765616.00       | NORTH SANTIAM PAVING CO.           | 
| 14078       | BAKER CREEK RD: MICHELBOOK LANE - POWER HOUSE HILL RD | X-STP-C071(014)      | 2009-07-06T00:00:00 | 667260.00       | NORTH SANTIAM PAVING CO.           | 
| 14064       | US30: HAVLIK DRIVE INT./HAVLIK DR. EXTENSION          | X-STP-OTIA-S092(029) | 2009-07-07T00:00:00 | 1232517.09      | R & R GENERAL CONTRACTORS, INC.    | 
| 14069       | HAZEL ST: EAST OF 10TH STREET                         | X-CM-1240(008)       | 2009-07-07T00:00:00 | 130803.10       | COPELAND CONSTRUCTION, LLC         | 
| 14074       | OR99E MAIN ST - 4TH ST SIDEWALK                       | X-STP-0330(007)      | 2009-07-09T00:00:00 | 75258.40        | D & D CONCRETE & UTILITIES INC.    | 
| 14075       | OR234: ROGUE RIVER BRIDGE (ROCK POINT) REHAB          | X-BRO-S271(009)      | 2009-07-09T00:00:00 | 3917120.42      | WILDISH STANDARD PAVING CO.        | 
| 14079       | BEAR GULCH SLIDE DRAINAGE TUNNEL REPAIR               | X-STP-S063(030)      | 2009-07-10T00:00:00 | 470411.00       | JAMES W. FOWLER CO.                | 
| 14055       | I-84:EAST PORTLAND FWY - NE 181ST AVENUE              | IM-S002(105)         | 2009-07-14T00:00:00 | 8748532.31      | OREGON MAINLINE PAVING, LLC        | 
| 14083       | PRINEVILLE CITY STREETS: PAVEMENT RESURFACING         | X-STP-5985(010)      | 2009-07-27T00:00:00 | 212212.00       | HOOKER CREEK COMPANIES, LLC        | 
| 14084       | ASHLAND CITY STREETS: PAVEMENT OVERLAY                | X-STP-0305(022)      | 2009-07-27T00:00:00 | 358801.25       | LTM, INC DBA KNIFE RIVER MATERIALS | 
```