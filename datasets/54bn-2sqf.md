# Purchase Orders

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/purchase-orders) |
| Metadata | [Link](https://data.brla.gov/api/views/54bn-2sqf) |
| Data: JSON | [100 Rows](https://data.brla.gov/api/views/54bn-2sqf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.brla.gov/api/views/54bn-2sqf/rows.csv?max_rows=100) |
| Host | data.brla.gov |
| Id | 54bn-2sqf |
| Name | Purchase Orders |
| Attribution | Purchasing |
| Category | Government |
| Tags | purchase orders, procurement, purchasing |
| Created | 2015-03-08T04:50:19Z |
| Publication Date | 2015-07-27T13:13:15Z |

## Description

Listing of all purchase orders issued to procure goods and/or services within City-Parish.

In the City-Parish Purchasing system, a purchase order (PO) is made up of two components: a header and one or many detail items that comprise the overarching PO. The header contains information that pertains to the entire PO. This includes, but is not limited to,  the total amount of the PO, the department requesting the purchase and the vendor providing the goods or services. The detail item(s) contain information that is specific to the individual item ordered or service procured through the Purchase Order. The item/service description, item/service quantity and the cost of the item is located within the Purchase Order details. There may be one or many detail items on an individual Purchase Order. For example, a Purchase Order for a computer equipment may include three items: the computer, the monitor and the base software package.

Both header information and detail item information are included in this dataset in order to provide a comprehensive view of the purchase order data. The Record Type field indicates whether the record is a header record (H) or detail item record (D). In the computer purchase example from above, the system would display 4 records – one header record and 3 detail item records.  

It should be noted header information will be duplicated on all detail items. No detail item information will be displayed on the header record.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                             | Data Type     | Render Type   |
| ======== | ============== | ================== | ================================ | ============= | ============= |
| Yes      | series tag     | rec_type           | RECORD TYPE                      | text          | text          |
| Yes      | series tag     | po_num             | PURCHASE ORDER NUMBER            | text          | text          |
| Yes      | series tag     | req_num            | REQUISITION NUMBER               | text          | text          |
| Yes      | time           | po_in_date         | INPUT DATE                       | calendar_date | calendar_date |
| Yes      | numeric metric | total_amt          | TOTAL AMOUNT                     | number        | number        |
| Yes      | series tag     | deptno             | DEPARTMENT NUMBER                | text          | text          |
| Yes      | series tag     | dept_desc          | DEPARTMENT NAME                  | text          | text          |
| Yes      | series tag     | cstctr             | COST CENTER                      | text          | text          |
| Yes      | series tag     | cstctr_desc        | COST CENTER NAME                 | text          | text          |
| Yes      | series tag     | empl_inp           | INPUT BY                         | text          | text          |
| Yes      | series tag     | purc_agent         | PURCHASING AGENT                 | text          | text          |
| Yes      | series tag     | po_type_cd         | PO TYPE CODE                     | text          | text          |
| Yes      | series tag     | po_type_desc       | PO TYPE DESCRIPTION              | text          | text          |
| Yes      | series tag     | po_category        | PO CATEGORY CODE                 | text          | text          |
| Yes      | series tag     | po_category_desc   | PO CATEGORY DESCRIPTION          | text          | text          |
| Yes      | series tag     | po_stat            | PO STATUS CODE                   | text          | number        |
| Yes      | series tag     | po_stat_desc       | PO STATUS DESCRIPTION            | text          | text          |
| Yes      | numeric metric | vchd_amt           | VOUCHED AMOUNT                   | number        | number        |
| Yes      | series tag     | vend               | VENDOR NUMBER                    | text          | number        |
| Yes      | series tag     | vend_name_1        | VENDOR NAME 1                    | text          | text          |
| Yes      | series tag     | vend_name_2        | VENDOR NAME 2                    | text          | text          |
| No       |                | vend_addr_1        | VENDOR ADDRESS 1                 | text          | text          |
| No       |                | vend_addr_2        | VENDOR ADDRESS 2                 | text          | text          |
| Yes      | series tag     | vend_city          | VENDOR CITY                      | text          | text          |
| Yes      | series tag     | vend_state         | VENDOR STATE                     | text          | text          |
| Yes      | series tag     | vend_zip           | VENDOR ZIP                       | text          | text          |
| Yes      | series tag     | vend_cont_name     | VENDOR CONTACT NAME              | text          | text          |
| Yes      | series tag     | vend_cont_title    | VENDOR CONTACT TITLE             | text          | text          |
| Yes      | series tag     | vend_cont_phone    | VENDOR CONTACT PHONE             | text          | number        |
| Yes      | series tag     | vend_cont_ph_ext   | VENDOR CONTACT EXTENSION         | text          | number        |
| Yes      | series tag     | vend_minority_abbr | VENDOR MINORITY CODE             | text          | text          |
| Yes      | series tag     | vend_minority_desc | VENDOR MINORITY DESCRIPTION      | text          | text          |
| Yes      | numeric metric | total_items        | TOTAL ITEMS                      | number        | number        |
| Yes      | numeric metric | po_balance         | PO BALANCE                       | number        | number        |
| Yes      | series tag     | dt_seq             | ITEM NUMBER                      | text          | number        |
| Yes      | series tag     | dt_stock_desc      | ITEM DESCRIPTION                 | text          | text          |
| Yes      | numeric metric | dt_qty_ord         | ITEM QUANTITY ORDERED            | number        | number        |
| Yes      | series tag     | dt_qty_um          | ITEM UNIT OF MEASURE             | text          | text          |
| Yes      | series tag     | dt_um_desc         | ITEM UNIT OF MEASURE DESCRIPTION | text          | text          |
| Yes      | numeric metric | dt_unit_cost       | ITEM UNIT COST                   | number        | number        |
| Yes      | numeric metric | dt_tot_cost        | ITEM TOTAL COST                  | number        | number        |
| Yes      | series tag     | unique_id          | UNIQUE ID                        | text          | text          |
```

## Time Field

```ls
Value = po_in_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = vend_addr_1,vend_addr_2
```

## Data Commands

```ls
series e:54bn-2sqf d:2012-10-17T00:00:00.000Z t:po_stat=11 t:vend_cont_name="**NAME CHANGED FROM FUGRO" t:cstctr_desc="CONSTRUCTION PROJECTS - PUBLIC BUILDINGS" t:po_type_cd=B t:purc_agent=PW t:po_category=PS t:req_num=RQ030549 t:vend_name_1="FUGRO USA LAND INC" t:po_num=PO110701 t:vend_city=HOUSTON t:po_type_desc=GOODS-SERV t:unique_id=PO110701 t:empl_inp=BDCA t:rec_type=H t:vend=64320 t:po_stat_desc=CLOSED t:cstctr=7510 t:po_category_desc="PROFESSIONAL SERVICES" t:vend_zip=77469 t:deptno=75 t:vend_state=TX t:dept_desc="CONSTRUCTION PROJECTS" m:po_balance=9.75 m:total_items=5 m:total_amt=13682 m:vchd_amt=13672.25

series e:54bn-2sqf d:2012-10-17T00:00:00.000Z t:po_stat=11 t:vend_cont_name="**NAME CHANGED FROM FUGRO" t:cstctr_desc="CONSTRUCTION PROJECTS - PUBLIC BUILDINGS" t:po_type_cd=B t:dt_qty_um=JB t:purc_agent=PW t:po_category=PS t:req_num=RQ030549 t:vend_name_1="FUGRO USA LAND INC" t:po_num=PO110701 t:vend_city=HOUSTON t:po_type_desc=GOODS-SERV t:unique_id=PO1107010001 t:dt_seq=1 t:empl_inp=BDCA t:rec_type=D t:vend=64320 t:po_stat_desc=CLOSED t:cstctr=7510 t:dt_stock_desc="CONSTRUCTION MATERIALS TESTING & INSPECTION        SERVICES FOR THE NEW SHARP ROAD FIRE STATION #13   PROJECT # 11-ASD-CP-0011.                          PER WRITTEN CONTRACT." t:po_category_desc="PROFESSIONAL SERVICES" t:vend_zip=77469 t:deptno=75 t:vend_state=TX t:dt_um_desc=JOB t:dept_desc="CONSTRUCTION PROJECTS" m:dt_unit_cost=10992 m:po_balance=9.75 m:total_items=5 m:dt_qty_ord=1 m:total_amt=13682 m:dt_tot_cost=10992 m:vchd_amt=13672.25

series e:54bn-2sqf d:2012-10-17T00:00:00.000Z t:po_stat=11 t:vend_cont_name="**NAME CHANGED FROM FUGRO" t:cstctr_desc="CONSTRUCTION PROJECTS - PUBLIC BUILDINGS" t:po_type_cd=B t:dt_qty_um=JB t:purc_agent=PW t:po_category=PS t:req_num=RQ030549 t:vend_name_1="FUGRO USA LAND INC" t:po_num=PO110701 t:vend_city=HOUSTON t:po_type_desc=GOODS-SERV t:unique_id=PO1107010002 t:dt_seq=2 t:empl_inp=BDCA t:rec_type=D t:vend=64320 t:po_stat_desc=CLOSED t:cstctr=7510 t:dt_stock_desc="INTERNAL CHANGE ORDER TO CORRECT PO TYPE FOR       SERVICES FOR THE NEW SHARP ROAD FIRE STATION #13   PROJECT # 11-ASD-CP-0011.                          PER WRITTEN CONTRACT." t:po_category_desc="PROFESSIONAL SERVICES" t:vend_zip=77469 t:deptno=75 t:vend_state=TX t:dt_um_desc=JOB t:dept_desc="CONSTRUCTION PROJECTS" m:dt_unit_cost=0 m:po_balance=9.75 m:total_items=5 m:dt_qty_ord=1 m:total_amt=13682 m:dt_tot_cost=0 m:vchd_amt=13672.25
```

## Meta Commands

```ls
metric m:total_amt p:double l:"TOTAL AMOUNT" d:"Total amount of PO" t:dataTypeName=number

metric m:vchd_amt p:double l:"VOUCHED AMOUNT" d:"Actual amount invoiced against PO. This amount may be less than the original PO amount" t:dataTypeName=number

metric m:total_items p:integer l:"TOTAL ITEMS" d:"Total number of detail items on PO. Each PO will have at least 1 detail item" t:dataTypeName=number

metric m:po_balance p:double l:"PO BALANCE" d:"Balance left on PO" t:dataTypeName=number

metric m:dt_qty_ord p:integer l:"ITEM QUANTITY ORDERED" d:"Quantity being ordered for this PO line item" t:dataTypeName=number

metric m:dt_unit_cost p:double l:"ITEM UNIT COST" d:"Unit Cost for this PO line item" t:dataTypeName=number

metric m:dt_tot_cost p:double l:"ITEM TOTAL COST" d:"Total (extended) cost of the PO line item being ordered" t:dataTypeName=number

entity e:54bn-2sqf l:"Purchase Orders" t:attribution=Purchasing t:url=https://data.brla.gov/api/views/54bn-2sqf

property e:54bn-2sqf t:meta.view v:id=54bn-2sqf v:category=Government v:attributionLink=http://brgov.com/dept/purchase v:averageRating=0 v:name="Purchase Orders" v:attribution=Purchasing

property e:54bn-2sqf t:meta.view.license v:name="Public Domain"

property e:54bn-2sqf t:meta.view.owner v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:displayName="Open Data BR"

property e:54bn-2sqf t:meta.view.tableauthor v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"
```

## Top Records

```ls
| rec_type | po_num   | req_num  | po_in_date          | total_amt   | deptno | dept_desc                      | cstctr | cstctr_desc                              | empl_inp | purc_agent | po_type_cd | po_type_desc | po_category | po_category_desc                    | po_stat | po_stat_desc | vchd_amt    | vend  | vend_name_1                         | vend_name_2           | vend_addr_1              | vend_addr_2 | vend_city   | vend_state | vend_zip   | vend_cont_name            | vend_cont_title | vend_cont_phone | vend_cont_ph_ext | vend_minority_abbr | vend_minority_desc | total_items | po_balance | dt_seq | dt_stock_desc                                                                                                                                                                                                                                 | dt_qty_ord | dt_qty_um | dt_um_desc | dt_unit_cost | dt_tot_cost | unique_id    | 
| ======== | ======== | ======== | =================== | =========== | ====== | ============================== | ====== | ======================================== | ======== | ========== | ========== | ============ | =========== | =================================== | ======= | ============ | =========== | ===== | =================================== | ===================== | ======================== | =========== | =========== | ========== | ========== | ========================= | =============== | =============== | ================ | ================== | ================== | =========== | ========== | ====== | ============================================================================================================================================================================================================================================= | ========== | ========= | ========== | ============ | =========== | ============ | 
| H        | PO110701 | RQ030549 | 2012-10-17T00:00:00 | 13682       | 75     | CONSTRUCTION PROJECTS          | 7510   | CONSTRUCTION PROJECTS - PUBLIC BUILDINGS | BDCA     | PW         | B          | GOODS-SERV   | PS          | PROFESSIONAL SERVICES               | 11      | CLOSED       | 13672.25    | 64320 | FUGRO USA LAND INC                  |                       | 6100 HILLCROFT           |             | HOUSTON     | TX         | 77469      | **NAME CHANGED FROM FUGRO |                 |                 |                  |                    |                    | 5           | 9.75       |        |                                                                                                                                                                                                                                               |            |           |            |              |             | PO110701     | 
| D        | PO110701 | RQ030549 | 2012-10-17T00:00:00 | 13682       | 75     | CONSTRUCTION PROJECTS          | 7510   | CONSTRUCTION PROJECTS - PUBLIC BUILDINGS | BDCA     | PW         | B          | GOODS-SERV   | PS          | PROFESSIONAL SERVICES               | 11      | CLOSED       | 13672.25    | 64320 | FUGRO USA LAND INC                  |                       | 6100 HILLCROFT           |             | HOUSTON     | TX         | 77469      | **NAME CHANGED FROM FUGRO |                 |                 |                  |                    |                    | 5           | 9.75       | 1      | CONSTRUCTION MATERIALS TESTING & INSPECTION SERVICES FOR THE NEW SHARP ROAD FIRE STATION #13 PROJECT # 11-ASD-CP-0011. PER WRITTEN CONTRACT.                                                                                                  | 1          | JB        | JOB        | 10992        | 10992       | PO1107010001 | 
| D        | PO110701 | RQ030549 | 2012-10-17T00:00:00 | 13682       | 75     | CONSTRUCTION PROJECTS          | 7510   | CONSTRUCTION PROJECTS - PUBLIC BUILDINGS | BDCA     | PW         | B          | GOODS-SERV   | PS          | PROFESSIONAL SERVICES               | 11      | CLOSED       | 13672.25    | 64320 | FUGRO USA LAND INC                  |                       | 6100 HILLCROFT           |             | HOUSTON     | TX         | 77469      | **NAME CHANGED FROM FUGRO |                 |                 |                  |                    |                    | 5           | 9.75       | 2      | INTERNAL CHANGE ORDER TO CORRECT PO TYPE FOR SERVICES FOR THE NEW SHARP ROAD FIRE STATION #13 PROJECT # 11-ASD-CP-0011. PER WRITTEN CONTRACT.                                                                                                 | 1          | JB        | JOB        | 0            | 0           | PO1107010002 | 
| D        | PO110701 | RQ030549 | 2012-10-17T00:00:00 | 13682       | 75     | CONSTRUCTION PROJECTS          | 7510   | CONSTRUCTION PROJECTS - PUBLIC BUILDINGS | BDCA     | PW         | B          | GOODS-SERV   | PS          | PROFESSIONAL SERVICES               | 11      | CLOSED       | 13672.25    | 64320 | FUGRO USA LAND INC                  |                       | 6100 HILLCROFT           |             | HOUSTON     | TX         | 77469      | **NAME CHANGED FROM FUGRO |                 |                 |                  |                    |                    | 5           | 9.75       | 3      | INTERNAL CHANGE ORDER TO CORRECT PO TYPE FOR SERVICES FOR THE NEW SHARP ROAD FIRE STATION #13 PROJECT # 11-ASD-CP-0011. PER WRITTEN CONTRACT.                                                                                                 | 1          | JB        | JOB        | 10992        | 10992       | PO1107010003 | 
| D        | PO110701 | RQ030549 | 2012-10-17T00:00:00 | 13682       | 75     | CONSTRUCTION PROJECTS          | 7510   | CONSTRUCTION PROJECTS - PUBLIC BUILDINGS | BDCA     | PW         | B          | GOODS-SERV   | PS          | PROFESSIONAL SERVICES               | 11      | CLOSED       | 13672.25    | 64320 | FUGRO USA LAND INC                  |                       | 6100 HILLCROFT           |             | HOUSTON     | TX         | 77469      | **NAME CHANGED FROM FUGRO |                 |                 |                  |                    |                    | 5           | 9.75       | 4      | INTERNAL CHANGE ORDER #1 TO REVISE PURCHASE ORDER FOR INVOICE # 551708 DATED 03/29/2012 IN THE AMOUNT OF $1,870.00 PER PEGGY KIDD TO INCREASE AMOUNT OF PURCHASE ORDER TO SATISFY PAYMENT OF ADDITIONAL TESTING SERVICES REQUIRED TO COMPLETE | 1          | JB        | JOB        | 1870         | 1870        | PO1107010004 | 
| D        | PO110701 | RQ030549 | 2012-10-17T00:00:00 | 13682       | 75     | CONSTRUCTION PROJECTS          | 7510   | CONSTRUCTION PROJECTS - PUBLIC BUILDINGS | BDCA     | PW         | B          | GOODS-SERV   | PS          | PROFESSIONAL SERVICES               | 11      | CLOSED       | 13672.25    | 64320 | FUGRO USA LAND INC                  |                       | 6100 HILLCROFT           |             | HOUSTON     | TX         | 77469      | **NAME CHANGED FROM FUGRO |                 |                 |                  |                    |                    | 5           | 9.75       | 5      | INTERNAL CHANGE ORDER #2 TO REVISE PURCHASE ORDER FOR INVOICE # 551847 DATED 08/07/2012 IN THE AMOUNT OF $530.00;AND INVOICE NO.551880, DATED 08/23/12 IN THE AMT OF $660.00. BAL ON PURCHASE ORDER IS 379.75;FOR AN INCREASE IN THE AMT      | 1          | JB        | JOB        | 820          | 820         | PO1107010005 | 
| D        | PO140686 | RQ035673 | 2017-03-06T00:00:00 | 15173611.94 | 75     | CONSTRUCTION PROJECTS          | 7578   | SSO IMPROVEMENT PROJECTS/REVISED RMAP 2  | BDMG     | PW         | B          | GOODS-SERV   | CO          | CONSTRUCTION PROJECTS OVER $25,000. | 3       | ENCMBRD-PT   | 14431936.58 | 3968  | HEMPHILL CONSTRUCTION CO INC        |                       | P O BOX 879              |             | FLORENCE    | MS         | 39073-0879 |                           |                 |                 |                  |                    |                    | 7           | 741675.36  | 6      | *CHANGE ORDER # 1* CON'T***TRACKING # 170288****** RESOLUTION #: 52566. NEW LUMP SUM ITEMS FOR ADDITIONAL WORK AND EXTEND CONTRACT FOR 71 (SEVENTY-ONE) ADDITIONAL DAYS TO FACILITATE THE PROJECT. RESULTING IN AN ADDITIONAL AMOUNT OF       | 1          | JB        | JOB        | 150870.13    | 150870.13   | PO1406860006 | 
| D        | PO101266 | RQ029458 | 2015-12-22T00:00:00 | 4538442.46  | 75     | CONSTRUCTION PROJECTS          | 7548   | LA DEPARTMENT OF TRANSPORTATION AND DEVE | BDAM     | PW         | B          | GOODS-SERV   | PS          | PROFESSIONAL SERVICES               | 8       | CH-NT-PART   | 3770544.78  | 2712  | SHREAD-KUYRKENDALL & ASSOCIATES INC |                       | 13016 JUSTICE AVE STE 16 |             | BATON ROUGE | LA         | 70816-2309 | RICHARD R SHREAD          | PRESIDENT       | 2252961335      |                  |                    |                    | 6           | 767897.68  | 2      | SUPPLEMENTAL AGREEMENT #1 PROFESSIONAL SERVICES PECUE LANE/I-10 INTERCHANGE RESOLUTION# 49310 CITY PARISH PROJECT NO. 09-CS-US-0041 STATE PROJECT NO. 700-17-0221 FEDERAL AID PROJECT NO. IM-1709(506)                                        | 1          | JB        | JOB        | 118350.83    | 118350.83   | PO1012660002 | 
| H        | PO170139 | RQ040723 | 2017-01-30T00:00:00 | 1659.48     | 60     | HUMAN DEVELOPMENT AND SERVICES | 6021   | US DEPARTMENT OF HEALTH AND HUMAN SERVIC | GACF     | SB         | B          | GOODS-SERV   | MS          | MISCELLANEOUS NON-QUOTES            | 3       | ENCMBRD-PT   | 0           | 4548  | GRAYBAR                             |                       | 7676 AIRLINE HWY         |             | BATON ROUGE | LA         | 70814-2196 | MICHAEL J RUSSELL         | SALES REP       | 2259262020      |                  |                    |                    | 6           | 1659.48    |        |                                                                                                                                                                                                                                               |            |           |            |              |             | PO170139     | 
| H        | PO170130 | RQ040666 | 2017-01-26T00:00:00 | 1342.27     | 08     | ANIMAL CONTROL CENTER          | 0800   | ANIMAL CONTROL CENTER                    | BDEM     | SB         | B          | GOODS-SERV   | SC          | STATE CONTRACT                      | 3       | ENCMBRD-PT   | 0           | 988   | DELL INC                            | ATTN PHILLIP DOMINGUE | ONE DELL WAY RR-MS41     |             | ROUND ROCK  | TX         | 78682      | PHILLIP DOMINGUE          |                 | 5127280460      |                  |                    |                    | 3           | 1342.27    |        |                                                                                                                                                                                                                                               |            |           |            |              |             | PO170130     | 
```