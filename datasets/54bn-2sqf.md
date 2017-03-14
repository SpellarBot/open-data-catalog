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
| Rows Updated | 2017-03-14T07:09:56Z |

## Description

Listing of all purchase orders issued to procure goods and/or services within City-Parish.

In the City-Parish Purchasing system, a purchase order (PO) is made up of two components: a header and one or many detail items that comprise the overarching PO. The header contains information that pertains to the entire PO. This includes, but is not limited to,  the total amount of the PO, the department requesting the purchase and the vendor providing the goods or services. The detail item(s) contain information that is specific to the individual item ordered or service procured through the Purchase Order. The item/service description, item/service quantity and the cost of the item is located within the Purchase Order details. There may be one or many detail items on an individual Purchase Order. For example, a Purchase Order for a computer equipment may include three items: the computer, the monitor and the base software package.

Both header information and detail item information are included in this dataset in order to provide a comprehensive view of the purchase order data. The Record Type field indicates whether the record is a header record (H) or detail item record (D). In the computer purchase example from above, the system would display 4 records ? one header record and 3 detail item records.  

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
| Yes      | numeric metric | deptno             | DEPARTMENT NUMBER                | number        | text          |
| Yes      | series tag     | dept_desc          | DEPARTMENT NAME                  | text          | text          |
| Yes      | numeric metric | cstctr             | COST CENTER                      | number        | text          |
| Yes      | series tag     | cstctr_desc        | COST CENTER NAME                 | text          | text          |
| Yes      | series tag     | empl_inp           | INPUT BY                         | text          | text          |
| Yes      | series tag     | purc_agent         | PURCHASING AGENT                 | text          | text          |
| Yes      | series tag     | po_type_cd         | PO TYPE CODE                     | text          | text          |
| Yes      | series tag     | po_type_desc       | PO TYPE DESCRIPTION              | text          | text          |
| Yes      | series tag     | po_category        | PO CATEGORY CODE                 | text          | text          |
| Yes      | series tag     | po_category_desc   | PO CATEGORY DESCRIPTION          | text          | text          |
| Yes      | numeric metric | po_stat            | PO STATUS CODE                   | number        | number        |
| Yes      | series tag     | po_stat_desc       | PO STATUS DESCRIPTION            | text          | text          |
| Yes      | numeric metric | vchd_amt           | VOUCHED AMOUNT                   | number        | number        |
| Yes      | numeric metric | vend               | VENDOR NUMBER                    | number        | number        |
| Yes      | series tag     | vend_name_1        | VENDOR NAME 1                    | text          | text          |
| Yes      | series tag     | vend_name_2        | VENDOR NAME 2                    | text          | text          |
| Yes      | series tag     | vend_addr_1        | VENDOR ADDRESS 1                 | text          | text          |
| Yes      | series tag     | vend_addr_2        | VENDOR ADDRESS 2                 | text          | text          |
| Yes      | series tag     | vend_city          | VENDOR CITY                      | text          | text          |
| Yes      | series tag     | vend_state         | VENDOR STATE                     | text          | text          |
| Yes      | series tag     | vend_zip           | VENDOR ZIP                       | text          | text          |
| Yes      | series tag     | vend_cont_name     | VENDOR CONTACT NAME              | text          | text          |
| Yes      | series tag     | vend_cont_title    | VENDOR CONTACT TITLE             | text          | text          |
| Yes      | series tag     | vend_cont_phone    | VENDOR CONTACT PHONE             | text          | number        |
| Yes      | numeric metric | vend_cont_ph_ext   | VENDOR CONTACT EXTENSION         | number        | number        |
| Yes      | series tag     | vend_minority_abbr | VENDOR MINORITY CODE             | text          | text          |
| Yes      | series tag     | vend_minority_desc | VENDOR MINORITY DESCRIPTION      | text          | text          |
| Yes      | numeric metric | total_items        | TOTAL ITEMS                      | number        | number        |
| Yes      | numeric metric | po_balance         | PO BALANCE                       | number        | number        |
| Yes      | numeric metric | dt_seq             | ITEM NUMBER                      | number        | number        |
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

## Data Commands

```ls
series e:54bn-2sqf d:2012-10-17T00:00:00.000Z t:vend_cont_name="**NAME CHANGED FROM FUGRO" t:cstctr_desc="CONSTRUCTION PROJECTS - PUBLIC BUILDINGS" t:po_type_cd=B t:po_category=PS t:purc_agent=PW t:req_num=RQ030549 t:vend_name_1="FUGRO USA LAND INC" t:po_num=PO110701 t:vend_city=HOUSTON t:po_type_desc=GOODS-SERV t:unique_id=PO110701 t:empl_inp=BDCA t:rec_type=H t:po_stat_desc=CLOSED t:po_category_desc="PROFESSIONAL SERVICES" t:vend_zip=77469 t:vend_addr_1="6100 HILLCROFT" t:vend_state=TX t:dept_desc="CONSTRUCTION PROJECTS" m:po_stat=11 m:po_balance=9.75 m:total_items=5 m:cstctr=7510 m:vend=64320 m:total_amt=13682 m:deptno=75 m:vchd_amt=13672.25

series e:54bn-2sqf d:2012-10-17T00:00:00.000Z t:vend_cont_name="**NAME CHANGED FROM FUGRO" t:cstctr_desc="CONSTRUCTION PROJECTS - PUBLIC BUILDINGS" t:po_type_cd=B t:dt_qty_um=JB t:purc_agent=PW t:po_category=PS t:req_num=RQ030549 t:vend_name_1="FUGRO USA LAND INC" t:po_num=PO110701 t:vend_city=HOUSTON t:po_type_desc=GOODS-SERV t:unique_id=PO1107010001 t:empl_inp=BDCA t:rec_type=D t:po_stat_desc=CLOSED t:dt_stock_desc="CONSTRUCTION MATERIALS TESTING & INSPECTION        SERVICES FOR THE NEW SHARP ROAD FIRE STATION #13   PROJECT # 11-ASD-CP-0011.                          PER WRITTEN CONTRACT." t:po_category_desc="PROFESSIONAL SERVICES" t:vend_zip=77469 t:vend_addr_1="6100 HILLCROFT" t:vend_state=TX t:dt_um_desc=JOB t:dept_desc="CONSTRUCTION PROJECTS" m:po_stat=11 m:dt_unit_cost=10992 m:po_balance=9.75 m:total_items=5 m:dt_qty_ord=1 m:cstctr=7510 m:vend=64320 m:dt_seq=1 m:total_amt=13682 m:deptno=75 m:dt_tot_cost=10992 m:vchd_amt=13672.25

series e:54bn-2sqf d:2012-10-17T00:00:00.000Z t:vend_cont_name="**NAME CHANGED FROM FUGRO" t:cstctr_desc="CONSTRUCTION PROJECTS - PUBLIC BUILDINGS" t:po_type_cd=B t:dt_qty_um=JB t:purc_agent=PW t:po_category=PS t:req_num=RQ030549 t:vend_name_1="FUGRO USA LAND INC" t:po_num=PO110701 t:vend_city=HOUSTON t:po_type_desc=GOODS-SERV t:unique_id=PO1107010002 t:empl_inp=BDCA t:rec_type=D t:po_stat_desc=CLOSED t:dt_stock_desc="INTERNAL CHANGE ORDER TO CORRECT PO TYPE FOR       SERVICES FOR THE NEW SHARP ROAD FIRE STATION #13   PROJECT # 11-ASD-CP-0011.                          PER WRITTEN CONTRACT." t:po_category_desc="PROFESSIONAL SERVICES" t:vend_zip=77469 t:vend_addr_1="6100 HILLCROFT" t:vend_state=TX t:dt_um_desc=JOB t:dept_desc="CONSTRUCTION PROJECTS" m:po_stat=11 m:dt_unit_cost=0 m:po_balance=9.75 m:total_items=5 m:dt_qty_ord=1 m:cstctr=7510 m:vend=64320 m:dt_seq=2 m:total_amt=13682 m:deptno=75 m:dt_tot_cost=0 m:vchd_amt=13672.25
```

## Meta Commands

```ls
metric m:total_amt p:double l:"TOTAL AMOUNT" d:"Total amount of PO" t:dataTypeName=number

metric m:deptno p:long l:"DEPARTMENT NUMBER" d:"Number of the department which the PO is for" t:dataTypeName=number

metric m:cstctr p:integer l:"COST CENTER" d:"Cost Center of the Department which the PO is for. This will often show which of the Department's Divisions issued the PO" t:dataTypeName=number

metric m:po_stat p:integer l:"PO STATUS CODE" d:"Code indicating the status of the PO" t:dataTypeName=number

metric m:vchd_amt p:double l:"VOUCHED AMOUNT" d:"Actual amount invoiced against PO. This amount may be less than the original PO amount" t:dataTypeName=number

metric m:vend p:integer l:"VENDOR NUMBER" d:"Internal id associated with the vendor" t:dataTypeName=number

metric m:vend_cont_ph_ext p:integer l:"VENDOR CONTACT EXTENSION" t:dataTypeName=number

metric m:total_items p:integer l:"TOTAL ITEMS" d:"Total number of detail items on PO. Each PO will have at least 1 detail item" t:dataTypeName=number

metric m:po_balance p:double l:"PO BALANCE" d:"Balance left on PO" t:dataTypeName=number

metric m:dt_seq p:integer l:"ITEM NUMBER" d:"Sequential number of the detail PO line item" t:dataTypeName=number

metric m:dt_qty_ord p:integer l:"ITEM QUANTITY ORDERED" d:"Quantity being ordered for this PO line item" t:dataTypeName=number

metric m:dt_unit_cost p:double l:"ITEM UNIT COST" d:"Unit Cost for this PO line item" t:dataTypeName=number

metric m:dt_tot_cost p:double l:"ITEM TOTAL COST" d:"Total (extended) cost of the PO line item being ordered" t:dataTypeName=number

entity e:54bn-2sqf l:"Purchase Orders" t:attribution=Purchasing t:url=https://data.brla.gov/api/views/54bn-2sqf

property e:54bn-2sqf t:meta.view v:id=54bn-2sqf v:category=Government v:attributionLink=http://brgov.com/dept/purchase v:averageRating=0 v:name="Purchase Orders" v:attribution=Purchasing

property e:54bn-2sqf t:meta.view.license v:name="Public Domain"

property e:54bn-2sqf t:meta.view.owner v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"

property e:54bn-2sqf t:meta.view.tableauthor v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"
```