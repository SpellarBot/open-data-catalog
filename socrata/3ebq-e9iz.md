# Purchase Order Quantity Price detail for Commodity/Goods procurements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/purchase-order-quantity-price-detail-for-commodity-goods-procurements) |
| Metadata | [Link](https://data.austintexas.gov/api/views/3ebq-e9iz) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/3ebq-e9iz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/3ebq-e9iz/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 3ebq-e9iz |
| Name | Purchase Order Quantity Price detail for Commodity/Goods procurements |
| Attribution | City of Austin Financial Services |
| Category | Financial |
| Tags | purchasing, commodities, financial, goods, commodity, price, procurement, transparency, austin finance online, buying, procure, city of austin, texas, central texas, financial services, open data,... |
| Created | 2013-06-06T21:38:53Z |
| Publication Date | 2014-10-08T23:21:07Z |

## Description

Purchase Order commodity line level detail for City of Austin Commodities/Goods purchases dating back to October 1st, 2009.  Each line includes the NIGP Commodity Code/COA Inventory Code, commodity description, quantity, unit of measure, unit price, total amount, referenced Master Agreement if applicable, the contract name, purchase order, award date, and vendor information.  The data contained in this data set is for informational purposes only.  Certain Austin Energy transactions have been excluded as competitive matters under Texas Government Code Section 552.133 and City Council Resolution 20051201-002.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | commodity             | COMMODITY             | text          | text          |
| Yes      | series tag     | commodity_description | COMMODITY_DESCRIPTION | text          | text          |
| Yes      | series tag     | extended_description  | EXTENDED_DESCRIPTION  | text          | text          |
| Yes      | numeric metric | quantity              | QUANTITY              | number        | number        |
| Yes      | series tag     | unit_of_measure       | UNIT_OF_MEASURE       | text          | text          |
| Yes      | series tag     | unit_of_meas_desc     | UNIT_OF_MEAS_DESC     | text          | text          |
| Yes      | numeric metric | unit_price            | UNIT_PRICE            | number        | number        |
| Yes      | numeric metric | itm_tot_am            | ITM_TOT_AM            | number        | number        |
| Yes      | series tag     | master_agreement      | MASTER_AGREEMENT      | text          | text          |
| Yes      | series tag     | contract_name         | CONTRACT_NAME         | text          | text          |
| Yes      | series tag     | purchase_order        | PURCHASE_ORDER        | text          | text          |
| Yes      | time           | award_date            | AWARD_DATE            | calendar_date | calendar_date |
| Yes      | series tag     | vendor_code           | VENDOR_CODE           | text          | text          |
| Yes      | series tag     | lgl_nm                | LGL_NM                | text          | text          |
| Yes      | series tag     | ad_ln_1               | AD_LN_1               | text          | text          |
| Yes      | series tag     | ad_ln_2               | AD_LN_2               | text          | text          |
| Yes      | series tag     | city                  | CITY                  | text          | text          |
| No       |                | st                    | ST                    | text          | text          |
| Yes      | series tag     | zip                   | ZIP                   | text          | text          |
| Yes      | series tag     | ctry                  | CTRY                  | text          | text          |
| No       |                | data_build_date       | DATA_BUILD_DATE       | calendar_date | calendar_date |
```

## Time Field

```ls
Value = award_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = st,data_build_date
```

## Data Commands

```ls
series e:3ebq-e9iz d:2014-09-29T00:00:00.000Z t:zip=78216 t:contract_name="Materials needed for Glen Bell warehouse" t:ad_ln_1="121 Interpark Blvd Ste 1203" t:master_agreement=MA7400GC130000008 t:purchase_order=DO220014092921666 t:city="SAN ANTONIO" t:vendor_code=MSC6003170 t:unit_of_meas_desc=Pair t:unit_of_measure=PR t:commodity=20142770002 t:commodity_description="GLOVES WORK MECHANIC SYNTHETIC LEATHER SZ LARGE" t:extended_description="RC LN_____ QTY DEL_____ P/F_____ B/O______ DEL DATE_________    MSC # 09398629" t:ctry=US t:lgl_nm="SID TOOL CO INC" m:itm_tot_am=513.3 m:quantity=30 m:unit_price=17.11

series e:3ebq-e9iz d:2015-02-06T00:00:00.000Z t:zip=78660 t:contract_name="Material for Webberville Store" t:ad_ln_1="1301 WELLS BRANCH PKWY" t:master_agreement=MA2200GA130000107 t:purchase_order=DO220015020608110 t:city=PFLUGERVILLE t:vendor_code=HUG8319237 t:unit_of_meas_desc=Each t:unit_of_measure=EA t:commodity=32075370001 t:commodity_description="CLAMP, STAINLESS STEEL, SERATED 51 INCH" t:extended_description="RC LN_____ QTY DEL_____ P/F_____ B/O______ DEL DATE_________" t:ctry=US t:lgl_nm="HD SUPPLY WATERWORKS LTD" m:itm_tot_am=343 m:quantity=100 m:unit_price=3.43

series e:3ebq-e9iz d:2012-11-29T00:00:00.000Z t:vendor_code=MAR8322907 t:zip=78758 t:contract_name="Trimble TSC2 Battery Charger" t:commodity=45007 t:ad_ln_1="8868 RESEARCH BLVD #101" t:commodity_description="Battery Chargers for Dry Cell Batteries" t:extended_description="Trimble TSC2 Battery Charger" t:ctry=US t:lgl_nm="MARTIN INSTRUMENT" t:purchase_order=PO600012112901183 t:city=AUSTIN m:itm_tot_am=64 m:quantity=0 m:unit_price=0
```

## Meta Commands

```ls
metric m:quantity p:integer l:QUANTITY t:dataTypeName=number

metric m:unit_price p:double l:UNIT_PRICE t:dataTypeName=number

metric m:itm_tot_am p:double l:ITM_TOT_AM t:dataTypeName=number

entity e:3ebq-e9iz l:"Purchase Order Quantity Price detail for Commodity/Goods procurements" t:attribution="City of Austin Financial Services" t:url=https://data.austintexas.gov/api/views/3ebq-e9iz

property e:3ebq-e9iz t:meta.view v:id=3ebq-e9iz v:category=Financial v:attributionLink="https://www.austintexas.gov/financeonline/finance/financial_docs.cfm?ws=1&pg=2" v:averageRating=0 v:name="Purchase Order Quantity Price detail for Commodity/Goods procurements" v:attribution="City of Austin Financial Services"

property e:3ebq-e9iz t:meta.view.owner v:id=t5rb-t58r v:screenName=Chris v:displayName=Chris

property e:3ebq-e9iz t:meta.view.tableauthor v:id=t5rb-t58r v:screenName=Chris v:roleName=publisher v:displayName=Chris
```

## Top Records

```ls
| commodity   | commodity_description                                        | extended_description                                                                                                                                                                                                                                                                                                                                                            | quantity | unit_of_measure | unit_of_meas_desc | unit_price | itm_tot_am | master_agreement  | contract_name                                                | purchase_order    | award_date          | vendor_code  | lgl_nm                            | ad_ln_1                     | ad_ln_2     | city         | st | zip        | ctry | data_build_date     | 
| =========== | ============================================================ | =============================================================================================================================================================================================================================================================================================================================================================================== | ======== | =============== | ================= | ========== | ========== | ================= | ============================================================ | ================= | =================== | ============ | ================================= | =========================== | =========== | ============ | == | ========== | ==== | =================== | 
| 20142770002 | GLOVES WORK MECHANIC SYNTHETIC LEATHER SZ LARGE              | RC LN_____ QTY DEL_____ P/F_____ B/O______ DEL DATE_________ MSC # 09398629                                                                                                                                                                                                                                                                                                     | 30       | PR              | Pair              | 17.11      | 513.3      | MA7400GC130000008 | Materials needed for Glen Bell warehouse                     | DO220014092921666 | 2014-09-29T00:00:00 | MSC6003170   | SID TOOL CO INC                   | 121 Interpark Blvd Ste 1203 |             | SAN ANTONIO  | TX | 78216      | US   | 2017-04-10T00:00:00 | 
| 32075370001 | CLAMP, STAINLESS STEEL, SERATED 51 INCH                      | RC LN_____ QTY DEL_____ P/F_____ B/O______ DEL DATE_________                                                                                                                                                                                                                                                                                                                    | 100      | EA              | Each              | 3.43       | 343        | MA2200GA130000107 | Material for Webberville Store                               | DO220015020608110 | 2015-02-06T00:00:00 | HUG8319237   | HD SUPPLY WATERWORKS LTD          | 1301 WELLS BRANCH PKWY      |             | PFLUGERVILLE | TX | 78660      | US   | 2017-04-10T00:00:00 | 
| 45007       | Battery Chargers for Dry Cell Batteries                      | Trimble TSC2 Battery Charger                                                                                                                                                                                                                                                                                                                                                    | 0        |                 |                   | 0          | 64         |                   | Trimble TSC2 Battery Charger                                 | PO600012112901183 | 2012-11-29T00:00:00 | MAR8322907   | MARTIN INSTRUMENT                 | 8868 RESEARCH BLVD #101     |             | AUSTIN       | TX | 78758      | US   | 2017-04-10T00:00:00 | 
| 89050170008 | ADAPTER PVC 8 IN CONCRETE X 8 IN CI                          | RC LN____ QTY DEL____ P/F_____ B/O_____ DEL DATE__________                                                                                                                                                                                                                                                                                                                      | 16       | EA              | Each              | 47.54      | 760.64     | MA2200GA110000052 | material needed at awwbsc                                    | DO220013072918306 | 2013-07-29T00:00:00 | FER1841250   | FERGUSON ENTERPRISES INC          | 200 PARK CENTRAL BLVD       |             | GEORGETOWN   | TX | 78626-9999 | US   | 2017-04-10T00:00:00 | 
| 26987275127 | M042 Cordarone (Amiodarone) I.V. 150mg/3ml Ampul or V        | M042 Cordarone (Amiodarone) I.V. 150mg/3ml Ampul or Vial. 50mg/ml Bedford. NDC: 55390005710                                                                                                                                                                                                                                                                                     | 25       | PK              | Pack              | 19         | 475        | MA9300GA100000027 | medical supplies                                             | DO930010061522893 | 2010-06-15T00:00:00 | GEN2007500   | MCKESSON MEDICAL-SURGICAL INC     | P.O. BOX 740215             |             | Cincinnati   | OH | 45274-0215 | US   | 2017-04-10T00:00:00 | 
| 67052103001 | COUPLING CI FLEX 250 FOR 2 IN CI PIPE                        | RC LN_____ QTY DEL_____ P/F_____ B/O_____ DEL DATE____________                                                                                                                                                                                                                                                                                                                  | 30       | EA              | Each              | 20.94      | 628.2      | MA2200GA080000063 | material needed at gbsc                                      | DO220009111904633 | 2009-11-19T00:00:00 | HUG8319237   | HD SUPPLY WATERWORKS LTD          | 1800 ROYSTON LN             |             | ROUND ROCK   | TX | 78664-9506 | US   | 2017-04-10T00:00:00 | 
| 5154584     | PARTS, TORO MOWER (TORO OR EQUAL)                            |                                                                                                                                                                                                                                                                                                                                                                                 | 0        |                 |                   | 0          | 64326.19   | MA7800GA110000077 | Toro Parts                                                   | DO780011100100038 | 2011-10-01T00:00:00 | PRO8308760   | PROFESSIONAL TURF PRODUCTS L P    | 5026 SERVICE CENTER DR      |             | SAN ANTONIO  | TX | 78218-5517 | US   | 2017-04-10T00:00:00 | 
| 20464       | Network Components: Adapter Cards, Bridges, Connec           | 20577-switch                                                                                                                                                                                                                                                                                                                                                                    | 1        | EA              | Each              | 402.96     | 402.96     | MA5600NC150000003 | 20577-Tyler Higdon-switch                                    | DO560014120304274 | 2014-12-03T00:00:00 | V00000905575 | Solid IT Networks, Inc.           | 845 East FM 407             |             | Argyle       | TX | 76226      | US   | 2017-04-10T00:00:00 | 
| 46507435008 | Ascensia CONTOUR Glucometer Check Strip EMS Model Bayer -Blo | D003.1 Glucometer Check Strip BAYER HEALTHCARE Item Number 7099C                                                                                                                                                                                                                                                                                                                | 170      | BOX             | Box               | 14.97      | 2544.9     | MA9300GA120000098 | medical supplies-emergency patient care for stock replenishm | DO930016020307348 | 2016-02-03T00:00:00 | HEN8311513   | HENRY SCHEIN INC                  | 135 DURYEA RD E270          |             | MELVILLE     | NY | 11747-3834 | US   | 2017-04-10T00:00:00 | 
| 06074       | Replacement Parts for other than American Motors,            | Captive repair parts and repair services for Crane Carrier Trucks. Labor rate for services provided between 7:30 AM to 4:30 PM Monday through Friday, no holidays: $84.50/hr. As quoted, a 15% discount off Crane Carrier Company's latest parts list applies.Three day delivery on parts. Contract is valid from 9/6/07 to 9/5/2010 with three additional 12 month extensions. | 0        |                 |                   | 0          | 10223.23   | MA7800GA070000175 | Repair & Parts for Crane Carrier                             | DO780009123107783 | 2009-12-31T00:00:00 | LON2935250   | LONGHORN INTERNATIONAL TRUCKS LTD | LTD                         | PO BOX 6260 | AUSTIN       | TX | 78762-6260 | US   | 2017-04-10T00:00:00 | 
```