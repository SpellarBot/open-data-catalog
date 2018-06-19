# Purchasing Commodity Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/purchasing-commodity-data) |
| Metadata | [Link](https://data.sfgov.org/api/views/ebsh-uavg) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/ebsh-uavg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/ebsh-uavg/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | ebsh-uavg |
| Name | Purchasing Commodity Data |
| Attribution | SF Controller's Office |
| Category | City Management and Ethics |
| Tags | spending, amount, vendor, purchase order, purchasing, commodity, procurement |
| Created | 2016-03-31T21:56:54Z |
| Publication Date | 2016-05-09T15:49:47Z |

## Description

The San Francisco Controller's Office maintains a database of purchasing activity from fiscal year 2007 forward. This data is presented on the Purchasing Commodity Data report in CSV format, and represents detailed commodity-level data by purchase order. Additional lines have been added to this dataset to reconcile some document totals from the City's purchasing system to the totals from the City's accounting system in cases when the two amounts are different, which sometimes occurs due to adjustments entered into the accounting system but not the purchasing system. We have removed sensitive information from this data ? this is intended to show payments made to entities providing goods and services to the City and County and to protect individuals. For example, we have removed payments to employees (reimbursements, garnishments) and jury members, revenue refunds, payments for judgments and claims, witnesses, relocation and rehousing, and a variety of human services payments. New data is added on a weekly basis.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type     | Render Type   |
| ======== | ============== | =========================== | =========================== | ============= | ============= |
| No       |                | fiscal_year                 | Fiscal Year                 | number        | text          |
| Yes      | series tag     | purchase_order              | Purchase Order              | text          | text          |
| Yes      | series tag     | purchase_order_line         | Purchase Order Line         | text          | text          |
| Yes      | series tag     | purchasing_department       | Purchasing Department       | text          | text          |
| Yes      | series tag     | purchasing_department_title | Purchasing Department Title | text          | text          |
| Yes      | time           | post_date_original          | Post Date - Original        | calendar_date | calendar_date |
| No       |                | post_date_current           | Post Date - Current         | calendar_date | calendar_date |
| Yes      | series tag     | commodity_code              | Commodity Code              | text          | text          |
| Yes      | series tag     | commodity_title             | Commodity Title             | text          | text          |
| Yes      | series tag     | vendor_name                 | Vendor Name                 | text          | text          |
| Yes      | series tag     | vendor_street               | Vendor Street               | text          | text          |
| Yes      | series tag     | vendor_city                 | Vendor City                 | text          | text          |
| Yes      | series tag     | vendor_state                | Vendor State                | text          | text          |
| Yes      | series tag     | vendor_zip_code             | Vendor Zip Code             | text          | text          |
| Yes      | series tag     | vendor_contact              | Vendor Contact              | text          | text          |
| Yes      | series tag     | vendor_email                | Vendor Email                | text          | text          |
| Yes      | series tag     | vendor_phone                | Vendor Phone                | text          | text          |
| Yes      | numeric metric | encumbered_quantity         | Encumbered Quantity         | number        | number        |
| Yes      | numeric metric | encumbered_amount           | Encumbered Amount           | number        | number        |
```

## Time Field

```ls
Value = post_date_original
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = post_date_current,fiscal_year
```

## Data Commands

```ls
series e:ebsh-uavg d:2012-12-18T00:00:00.000Z t:vendor_state=CA t:vendor_zip_code=94124 t:purchasing_department_title="DPW - BUREAU OF URBAN FORESTRY" t:commodity_title="WOOD & PREFABRICATED WOOD PRDTS; LUMBER, PLYWOOD," t:vendor_phone=415-467-6832 t:vendor_street="1755 EGBERT AVE" t:purchase_order=DPUF13000283 t:vendor_city="SAN FRANCISCO" t:vendor_contact="DANA DOMINGUEZ" t:purchase_order_line=001 t:commodity_code=915022 t:purchasing_department=DPWUF t:vendor_name="D L D LUMBER CO INC" m:encumbered_amount=69.08 m:encumbered_quantity=107

series e:ebsh-uavg d:2014-12-09T00:00:00.000Z t:vendor_city="SAN FRANCISCO" t:vendor_zip_code=94109 t:vendor_state=CA t:purchase_order_line=003 t:purchasing_department_title=PORT t:commodity_title=CHARGE;DELIVERY/FREIGHT/SHIPPING t:purchasing_department=PRT t:commodity_code=99470601 t:vendor_street="2000 VAN NESS AVENUE, #101" t:vendor_name="SPOTLIGHT PROMOTIONS INC" t:purchase_order=DPPO15000842 m:encumbered_amount=92.5 m:encumbered_quantity=1

series e:ebsh-uavg d:2009-04-16T00:00:00.000Z t:vendor_state=CA t:vendor_zip_code=940700000 t:purchasing_department_title="SF WATER DEPT - SUPPLY & TREATMENT DIV" t:commodity_title="PPF;STNLSS STEEL,CLAMP,TYPE 304,REPAIR,PIPE ......" t:vendor_phone=650-593-3183 t:vendor_street="1000 AMERICAN ST" t:purchase_order=DPUW09004534 t:vendor_city="SAN CARLOS" t:vendor_contact="EARL L MITCHELL SR" t:purchase_order_line=005 t:commodity_code=967036080430 t:purchasing_department=WTRST t:vendor_name="STATE PLUMBING & HEATING SUPPLIES" m:encumbered_amount=13.11 m:encumbered_quantity=6
```

## Meta Commands

```ls
metric m:encumbered_quantity p:integer l:"Encumbered Quantity" d:"The quantity of goods or services to be purchased under the terms of the Purchase Order. For some non-discrete purchases, like professional service contracts, the Encumbered Quantity is zero." t:dataTypeName=number

metric m:encumbered_amount p:double l:"Encumbered Amount" d:"The dollar amount of goods or services to be purchased under the terms of the Purchase Order." t:dataTypeName=number

entity e:ebsh-uavg l:"Purchasing Commodity Data" t:attribution="SF Controller's Office" t:url=https://data.sfgov.org/api/views/ebsh-uavg

property e:ebsh-uavg t:meta.view v:id=ebsh-uavg v:category="City Management and Ethics" v:averageRating=0 v:name="Purchasing Commodity Data" v:attribution="SF Controller's Office"

property e:ebsh-uavg t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:ebsh-uavg t:meta.view.owner v:id=9ufn-6bwh v:screenName="Jeff Pera" v:displayName="Jeff Pera"

property e:ebsh-uavg t:meta.view.tableauthor v:id=9ufn-6bwh v:screenName="Jeff Pera" v:roleName=editor v:displayName="Jeff Pera"
```

## Top Records

```ls
| fiscal_year | purchase_order | purchase_order_line | purchasing_department | purchasing_department_title            | post_date_original  | post_date_current   | commodity_code | commodity_title                                    | vendor_name                              | vendor_street              | vendor_city   | vendor_state | vendor_zip_code | vendor_contact            | vendor_email             | vendor_phone     | encumbered_quantity | encumbered_amount | 
| =========== | ============== | =================== | ===================== | ====================================== | =================== | =================== | ============== | ================================================== | ======================================== | ========================== | ============= | ============ | =============== | ========================= | ======================== | ================ | =================== | ================= | 
| 2013        | DPUF13000283   | 001                 | DPWUF                 | DPW - BUREAU OF URBAN FORESTRY         | 2012-12-18T00:00:00 | 2012-12-18T00:00:00 | 915022         | WOOD & PREFABRICATED WOOD PRDTS; LUMBER, PLYWOOD,  | D L D LUMBER CO INC                      | 1755 EGBERT AVE            | SAN FRANCISCO | CA           | 94124           | DANA DOMINGUEZ            |                          | 415-467-6832     | 107                 | 69.08             | 
| 2015        | DPPO15000842   | 003                 | PRT                   | PORT                                   | 2014-12-09T00:00:00 | 2014-12-09T00:00:00 | 99470601       | CHARGE;DELIVERY/FREIGHT/SHIPPING                   | SPOTLIGHT PROMOTIONS INC                 | 2000 VAN NESS AVENUE, #101 | SAN FRANCISCO | CA           | 94109           |                           |                          |                  | 1                   | 92.5              | 
| 2009        | DPUW09004534   | 005                 | WTRST                 | SF WATER DEPT - SUPPLY & TREATMENT DIV | 2009-04-16T00:00:00 | 2009-06-16T00:00:00 | 967036080430   | PPF;STNLSS STEEL,CLAMP,TYPE 304,REPAIR,PIPE ...... | STATE PLUMBING & HEATING SUPPLIES        | 1000 AMERICAN ST           | SAN CARLOS    | CA           | 940700000       | EARL L MITCHELL SR        |                          | 650-593-3183     | 6                   | 13.11             | 
| 2014        | DPPO14000729   | 005                 | PRT                   | PORT                                   | 2013-11-13T00:00:00 | 2013-11-13T00:00:00 | 96702580       | P.V.C. PIPES & FITTINGS; PLUMBING                  | EWING IRRIGATION PRODUCTS INC            | 1618 JERROLD AVE           | SAN FRANCISCO | CA           | 941242135       | SHAWN CULL                |                          | 415-695-9530     | 12                  | 10.28             | 
| 2013        | POTI13000199   | 001                 | TIS02                 | DEPARTMENT OF TECHNOLOGY               | 2013-02-01T00:00:00 | 2013-02-01T00:00:00 | 97255557       | TELECOMMUNICATIONS EQUIPMENT, AVAYA AND OTHER MFR' | ADVANTEL INC                             | 2222 TRADE ZONE BOULEVARD  | SAN JOSE      | CA           | 95131           |                           |                          |                  | 12                  | 822.93            | 
| 2011        | DPHM11000261   | 001                 | HMH                   | COMMUNITY MENTAL HEALTH SYSTEM         | 2010-11-30T00:00:00 | 2010-11-30T00:00:00 | 740020         | SVC,MED/HLTH;CMH (COMMUNITY MENTAL HEALTH)         | UCSF CLINIC PRAC GRP SFGH/COMM FOCUS PGM | 1001 POTRERO AVE RM 7M17   | SAN FRANCISCO | CA           | 94110           | ELLEN BUSTEED, CPG ADM    |                          | 415-206-5217     | 0                   | 1604505           | 
| 2009        | DPWP09001060   | 009                 | CWP                   | CLEAN WATER                            | 2008-11-25T00:00:00 | 2008-11-25T00:00:00 | 945015         | HARDWARE;RUBBER/METAL-HOSE/CLAMP/CONNECTOR/FITTING | VALLEY RUBBER & GASKET OF NORTH BAY INC  | 5045-D FULTON DR           | FAIRFIELD     | CA           | 94534           | DANIEL JACKSON, PRESIDENT |                          | 707-864-8783     | 4                   | 415.64            | 
| 2013        | DPPT13002695   | 003                 | DPT                   | PUBLIC TRANSPORTATION                  | 2013-03-29T00:00:00 | 2013-03-29T00:00:00 | 955825         | COMMON DIESEL & ELECTRIC TRANSIT VEHICLE EQPT, PAR | PREVOST CAR (US) INC                     | 2200 POINT BLVD, SUITE 100 | ELGIN         | IL           | 60123           | JENNIFER OWENS            | JENNIFER.OWENS@VOLVO.COM | 847-844-7680 119 | 15                  | 747.44            | 
| 2014        | DPBR14002226   | 004                 | DPWBR                 | DPW - BUILDING REPAIR                  | 2014-04-25T00:00:00 | 2014-04-25T00:00:00 | 99470601       | CHARGE;DELIVERY/FREIGHT/SHIPPING                   | SIGILLO SUPPLY INC                       | 1623 YOSEMITE AVENUE       | SAN FANCISCO  | CA           | 94124           |                           |                          |                  | 1                   | 27.19             | 
| 2016        | DPUW16002767   | 009                 | WTR                   | SF WATER DEPT                          | 2015-11-25T00:00:00 | 2015-11-25T00:00:00 | 915013         | METAL FENCING/GATE,PART&MATL;CHAIN LINKED/WIRE, .. | CONLIN SUPPLY CO                         | P O BOX 1942               | OAKDALE       | CA           | 953610000       |                           |                          | 209-847-8977     | 3                   | 7.19              | 
```