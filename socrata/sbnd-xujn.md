# Handyman Work Order (HWO) Charges

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/handyman-work-order-hwo-charges-3a56d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/sbnd-xujn) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/sbnd-xujn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/sbnd-xujn/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | sbnd-xujn |
| Name | Handyman Work Order (HWO) Charges |
| Attribution | Department of Housing Preservation and Development (HPD) |
| Category | Housing & Development |
| Tags | handyman work order (hwo) charges, charges, department of housing preservation and development, hpd |
| Created | 2013-11-19T15:27:59Z |
| Publication Date | 2017-04-02T20:04:13Z |

## Description

Contains information about work orders created to conduct emergency repair work when an owner fails to address a hazardous condition pursuant to the requirements of an HPD issued violation. HPD issues violations when an owner fails to address a condition pursuant New York City Housing Maintenance Code (HMC) or the New York State Multiple Dwelling Law (MDL), a Department of Buildings Declaration of Emergency, a Department of Health Commissioner's Order to Abate or an emergency violation issued by another City Agency. The work orders were carried out by agency staff.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag     | hwoid                  | HWOID                  | text          | number        |
| Yes      | series tag     | hwonumber              | HWONumber              | text          | text          |
| Yes      | series tag     | buildingid             | BuildingID             | text          | number        |
| Yes      | series tag     | boroid                 | BoroID                 | text          | number        |
| Yes      | series tag     | boro                   | Boro                   | text          | text          |
| Yes      | series tag     | housenumber            | HouseNumber            | text          | text          |
| Yes      | series tag     | streetname             | StreetName             | text          | text          |
| Yes      | series tag     | zip                    | Zip                    | text          | text          |
| Yes      | series tag     | block                  | Block                  | text          | number        |
| Yes      | series tag     | lot                    | Lot                    | text          | number        |
| Yes      | series tag     | lifecycle              | LifeCycle              | text          | text          |
| Yes      | series tag     | worktypegeneral        | WorkTypeGeneral        | text          | text          |
| Yes      | series tag     | hwostatusreason        | HWOStatusReason        | text          | text          |
| Yes      | time           | hwocreatedate          | HWOCreateDate          | calendar_date | calendar_date |
| Yes      | series tag     | isaep                  | IsAEP                  | text          | text          |
| Yes      | series tag     | iscommercialdemolition | IsCommercialDemolition | text          | text          |
| Yes      | series tag     | femaeventid            | FEMAEventID            | text          | number        |
| Yes      | series tag     | femaevent              | FEMAEvent              | text          | text          |
| Yes      | series tag     | hwodescription         | HWODescription         | text          | text          |
| Yes      | numeric metric | hwoapprovedamount      | HWOApprovedAmount      | number        | number        |
| Yes      | numeric metric | salestax               | SalesTax               | number        | number        |
| Yes      | numeric metric | adminfee               | AdminFee               | number        | number        |
| Yes      | numeric metric | chargeamount           | ChargeAmount           | number        | number        |
| No       |                | datetransferdof        | DateTransferDoF        | calendar_date | calendar_date |
```

## Time Field

```ls
Value = hwocreatedate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = datetransferdof
```

## Data Commands

```ls
series e:sbnd-xujn d:1998-07-06T00:00:00.000Z t:hwodescription="test work order" t:zip=11207 t:hwonumber=E000010 t:buildingid=342460 t:boro=BROOKLYN t:boroid=3 t:hwostatusreason=Other t:lifecycle=Building t:lot=48 t:block=3789 t:hwoid=37 t:housenumber=508 t:worktypegeneral=GC t:streetname="NEW JERSEY AVENUE" m:chargeamount=0 m:hwoapprovedamount=0 m:adminfee=0 m:salestax=0

series e:sbnd-xujn d:1998-07-23T00:00:00.000Z t:hwodescription="reinstall w/g's with stops & screws 1st sty, 2nd sty, 3rd sty & 4th sty." t:zip=11216 t:hwonumber=E000016 t:buildingid=349504 t:boro=BROOKLYN t:boroid=3 t:hwostatusreason="OMO Completed" t:lifecycle=Building t:lot=17 t:block=1207 t:hwoid=41 t:housenumber=1284 t:worktypegeneral=GC t:streetname="PACIFIC STREET" m:chargeamount=138.63 m:hwoapprovedamount=112.48 m:adminfee=16.87 m:salestax=9.28

series e:sbnd-xujn d:1998-07-23T00:00:00.000Z t:hwodescription="trace/locate/repair leak from above. s/r, t/c 3'/4' bathrm ceiling area." t:zip=11216 t:hwonumber=E000017 t:buildingid=374859 t:boro=BROOKLYN t:boroid=3 t:hwostatusreason="OMO Completed" t:lifecycle=Building t:lot=14 t:block=1224 t:hwoid=42 t:housenumber=564 t:worktypegeneral=PLUMB t:streetname="ST MARKS AVENUE" m:chargeamount=383.39 m:hwoapprovedamount=311.07 m:adminfee=46.66 m:salestax=25.66
```

## Meta Commands

```ls
metric m:hwoapprovedamount p:float l:HWOApprovedAmount d:"The total cost of the HWO (labor + materials)" t:dataTypeName=number

metric m:salestax p:float l:SalesTax d:"Imputed sales tax for this HWO" t:dataTypeName=number

metric m:adminfee p:float l:AdminFee d:"HPD's current administrative cost charged for this HWO" t:dataTypeName=number

metric m:chargeamount p:float l:ChargeAmount d:"Total lienable amount to be transferred to DoF" t:dataTypeName=number

entity e:sbnd-xujn l:"Handyman Work Order (HWO) Charges" t:attribution="Department of Housing Preservation and Development (HPD)" t:url=https://data.cityofnewyork.us/api/views/sbnd-xujn

property e:sbnd-xujn t:meta.view v:id=sbnd-xujn v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/hpd/html/pr/HPD-Open-Data.shtml v:averageRating=0 v:name="Handyman Work Order (HWO) Charges" v:attribution="Department of Housing Preservation and Development (HPD)"

property e:sbnd-xujn t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:sbnd-xujn t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| hwoid | hwonumber | buildingid | boroid | boro     | housenumber | streetname        | zip   | block | lot  | lifecycle | worktypegeneral | hwostatusreason     | hwocreatedate       | isaep | iscommercialdemolition | femaeventid | femaevent | hwodescription                                                                                                             | hwoapprovedamount | salestax | adminfee | chargeamount | datetransferdof     | 
| ===== | ========= | ========== | ====== | ======== | =========== | ================= | ===== | ===== | ==== | ========= | =============== | =================== | =================== | ===== | ====================== | =========== | ========= | ========================================================================================================================== | ================= | ======== | ======== | ============ | =================== | 
| 37    | E000010   | 342460     | 3      | BROOKLYN | 508         | NEW JERSEY AVENUE | 11207 | 3789  | 48   | Building  | GC              | Other               | 1998-07-06T00:00:00 |       |                        |             |           | test work order                                                                                                            | 0.00              | 0.00     | 0.00     | 0.00         |                     | 
| 41    | E000016   | 349504     | 3      | BROOKLYN | 1284        | PACIFIC STREET    | 11216 | 1207  | 17   | Building  | GC              | OMO Completed       | 1998-07-23T00:00:00 |       |                        |             |           | reinstall w/g's with stops & screws 1st sty, 2nd sty, 3rd sty & 4th sty.                                                   | 112.48            | 9.28     | 16.87    | 138.63       | 2000-05-18T00:00:00 | 
| 42    | E000017   | 374859     | 3      | BROOKLYN | 564         | ST MARKS AVENUE   | 11216 | 1224  | 14   | Building  | PLUMB           | OMO Completed       | 1998-07-23T00:00:00 |       |                        |             |           | trace/locate/repair leak from above. s/r, t/c 3'/4' bathrm ceiling area.                                                   | 311.07            | 25.66    | 46.66    | 383.39       | 2000-05-18T00:00:00 | 
| 43    | E000018   | 352123     | 3      | BROOKLYN | 913         | PARK PLACE        | 11213 | 1235  | 1    | Building  | GC              | Refused Access      | 1998-07-23T00:00:00 |       |                        |             |           | demo floor 2'x2' + 1'x2' area. path wood floor 1/2'' plywood. install vct tiles same area. remove all job related debris.  | 0.00              | 0.00     | 0.00     | 0.00         |                     | 
| 44    | E000019   | 352123     | 3      | BROOKLYN | 913         | PARK PLACE        | 11213 | 1235  | 1    | Building  | GC              | Refused Access      | 1998-07-23T00:00:00 |       |                        |             |           | trace/locate /repair leak from above apt. bathroom.                                                                        | 0.00              | 0.00     | 0.00     | 0.00         |                     | 
| 64    | E000048   | 339814     | 3      | BROOKLYN | 366         | MONTGOMERY STREET | 11225 | 1305  | 21   | Building  | IRON            | OMO Completed       | 1998-07-27T00:00:00 |       |                        |             |           | put drop ladder in guide front fire escape.                                                                                | 104.26            | 8.60     | 15.64    | 128.50       | 2000-05-18T00:00:00 | 
| 76    | E000062   | 248053     | 3      | BROOKLYN | 125         | EAST 19 STREET    | 11226 | 5123  | 68   | Building  | GC              | Condition Not Found | 1998-07-28T00:00:00 |       |                        |             |           | repair w/g's in kitchen (1), livingrm (2),bdrm 3(1) & bdrm 4(1). install w/g in bdrm 1(1) & bthrm (1).                     | 0.00              | 0.00     | 0.00     | 0.00         |                     | 
| 77    | E000063   | 373678     | 3      | BROOKLYN | 1325        | ST JOHNS PLACE    | 11213 | 1377  | 42   | Building  | GC              | OMO Completed       | 1998-07-28T00:00:00 |       |                        |             |           | disconnect toilet. install wax gasket. install missing tiles & grout 3 sqft. in shower area. remove all rubbish to street. | 300.35            | 24.78    | 45.05    | 370.18       | 2000-10-18T00:00:00 | 
| 104   | E000107   | 944330     | 3      | BROOKLYN | 103         | MESEROLE STREET   | 11206 | 3042  | 7502 | Building  | MOVE            | OMO Completed       | 1998-07-31T00:00:00 |       |                        |             |           | remove household items.                                                                                                    | 257.56            | 21.25    | 38.63    | 317.44       | 2000-05-18T00:00:00 | 
| 133   | E000141   | 382514     | 3      | BROOKLYN | 332         | TROY AVENUE       | 11213 | 1400  | 49   | Building  | GC              | OMO Completed       | 1998-08-06T00:00:00 |       |                        |             |           | repair 1 w/g to code bdrm .                                                                                                | 37.33             | 3.08     | 15.00    | 55.41        | 2000-05-18T00:00:00 | 
```