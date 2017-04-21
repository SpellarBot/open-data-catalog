# 2016 ODOT Highway Contracts - HB25000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-odot-highway-contracts-hb25000) |
| Metadata | [Link](https://data.oregon.gov/api/views/fdus-r2ei) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/fdus-r2ei/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/fdus-r2ei/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | fdus-r2ei |
| Name | 2016 ODOT Highway Contracts - HB25000 |
| Category | Revenue & Expense |
| Tags | 2016, odot, odot 2016, construction contracts, odot construction contracts, odot construction contracts 2016 |
| Created | 2016-12-10T02:31:51Z |
| Publication Date | 2016-12-10T02:37:02Z |

## Description

Summary of Oregon Department of Transportation construction contracts that are not in ORPIN for Fiscal Year 2016. For more information go to: http://www.oregon.gov/transparency/Pages/contracts.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| No       |                | fiscal_year      | Fiscal Year      | number        | number        |
| Yes      | series tag     | contract_id      | Contract_ID      | text          | text          |
| Yes      | series tag     | project_name     | Project_Name     | text          | text          |
| Yes      | series tag     | fed_state_number | Fed_State_Number | text          | text          |
| Yes      | time           | award_date       | Award_Date       | calendar_date | calendar_date |
| Yes      | numeric metric | contract_amount  | Contract_Amount  | money         | money         |
| Yes      | series tag     | vendor_name      | Vendor_Name      | text          | text          |
| Yes      | series tag     | addrtype         | ADDRTYPE         | text          | text          |
| No       |                | address          | Address          | text          | text          |
| Yes      | series tag     | city             | City             | text          | text          |
| Yes      | series tag     | state            | State            | text          | text          |
| Yes      | series tag     | zip              | ZIP              | text          | text          |
```

## Time Field

```ls
Value = award_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,fiscal_year
```

## Data Commands

```ls
series e:fdus-r2ei d:2015-07-29T00:00:00.000Z t:zip=97301 t:addrtype=PREQ t:project_name="OR 213 (82ND AVE):  SE DUKE STREET" t:fed_state_number=HSIP-S068(029) t:state=OR t:contract_id=14826 t:vendor_name="R & R GENERAL CONTRACTORS INC" t:city=SALEM m:contract_amount=596933

series e:fdus-r2ei d:2015-07-31T00:00:00.000Z t:zip=97301 t:addrtype=PREQ t:project_name="OR8: SW 185TH AVE." t:fed_state_number=HSIP-S029(024) t:state=OR t:contract_id=14825 t:vendor_name="R & R GENERAL CONTRACTORS INC" t:city=SALEM m:contract_amount=2005615

series e:fdus-r2ei d:2015-08-07T00:00:00.000Z t:zip=97365 t:addrtype=PREQ t:project_name="SAND LAKE ROAD @ MP 10.6 ER PROJECT" t:fed_state_number=ER-C057(065) t:state=OR t:contract_id=14823 t:vendor_name="WW CONSTRUCTION LLC" t:city=NEWPORT m:contract_amount=82389
```

## Meta Commands

```ls
metric m:contract_amount p:integer l:Contract_Amount t:dataTypeName=money

entity e:fdus-r2ei l:"2016 ODOT Highway Contracts - HB25000" t:url=https://data.oregon.gov/api/views/fdus-r2ei

property e:fdus-r2ei t:meta.view v:id=fdus-r2ei v:category="Revenue & Expense" v:averageRating=0 v:name="2016 ODOT Highway Contracts - HB25000"

property e:fdus-r2ei t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:fdus-r2ei t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year | contract_id | project_name                                    | fed_state_number | award_date          | contract_amount | vendor_name                                     | addrtype | address                       | city         | state | zip   | 
| =========== | =========== | =============================================== | ================ | =================== | =============== | =============================================== | ======== | ============================= | ============ | ===== | ===== | 
| 2016        | 14826       | OR 213 (82ND AVE): SE DUKE STREET               | HSIP-S068(029)   | 2015-07-29T00:00:00 | 596933          | R & R GENERAL CONTRACTORS INC                   | PREQ     | 3400 STATE ST STE G 780       | SALEM        | OR    | 97301 | 
| 2016        | 14825       | OR8: SW 185TH AVE.                              | HSIP-S029(024)   | 2015-07-31T00:00:00 | 2005615         | R & R GENERAL CONTRACTORS INC                   | PREQ     | 3400 STATE ST STE G 780       | SALEM        | OR    | 97301 | 
| 2016        | 14823       | SAND LAKE ROAD @ MP 10.6 ER PROJECT             | ER-C057(065)     | 2015-08-07T00:00:00 | 82389           | WW CONSTRUCTION LLC                             | PREQ     | 7945 NE AVERY                 | NEWPORT      | OR    | 97365 | 
| 2016        | 14828       | US30: TRAFFIC SIGNALS AT MCALISTER RD (RX 1659) | STP-S066(021)    | 2015-08-12T00:00:00 | 767223          | MICHAEL A BECKER GENERAL CONTRACTOR INC         | PREQ     | 10406 N MCALISTER RD          | LA GRANDE    | OR    | 97850 | 
| 2016        | 14830       | OR224: ROCKFALL MITIGATION                      | STP-S171(038)    | 2015-09-01T00:00:00 | 1713751         | HI-TECH ROCKFALL CONSTRUCTION INC               | PREQ     | 2328 HAWTHORNE ST             | FOREST GROVE | OR    | 97116 | 
| 2016        | 14829       | US101: SEA LION POINT ROCKWALL                  | STP-S009(452)    | 2015-09-09T00:00:00 | 2634813         | HP CIVIL INC                                    | PREQ     | 618 N SECOND AVE              | STAYTON      | OR    | 97383 | 
| 2016        | 14831       | NEHALEM RIVER (MIAMI-FOLEY RD) BR (LOMMEN)      | STP-C057(069)    | 2015-09-14T00:00:00 | 8397170         | FARLINE BRIDGE INC                              | PREQ     | 1445 MILLER DR                | STAYTON      | OR    | 97383 | 
| 2016        | 14832       | REGION 4 CENTERLINE RUMBLE STRIP PROJECT        | HSIP-S000(962)   | 2015-09-14T00:00:00 | 376468          | SPECIALIZED PAVEMENT MARKING INC                | PREQ     | 11095 SW INDUSTRIAL WAY STE A | TUALATIN     | OR    | 97062 | 
| 2016        | 14834       | I-5: SISKIYOU REST AREA (ASHLAND)               | IM-SO-S001(304)  | 2015-09-30T00:00:00 | 6296884         | WILDISH STANDARD PAVING CO                      | PREQ     | 3600 WILDISH LN               | EUGENE       | OR    | 97408 | 
| 2016        | 14835       | 2015 REGION 1 CURVE WARNING SIGN PROJECT        | HSIP-S000(967)   | 2015-09-30T00:00:00 | 176200          | BAKER ROCK CRUSHING CO DBA BAKER ROCK RESOURCES | PREQ     | 21880 SW FARMINGTON RD        | BEAVERTON    | OR    | 97007 | 
```