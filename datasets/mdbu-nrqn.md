# Open Market Order (OMO) Charges

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-market-order-omo-charges-a9242) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/mdbu-nrqn) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/mdbu-nrqn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/mdbu-nrqn/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | mdbu-nrqn |
| Name | Open Market Order (OMO) Charges |
| Attribution | Department of Housing Preservation and Development (HPD) |
| Category | Housing & Development |
| Tags | open market order (omo) charges, charges, department of housing preservation and development, hpd |
| Created | 2013-11-19T15:58:14Z |
| Publication Date | 2017-04-02T20:01:48Z |

## Description

Contains information about work orders created to conduct emergency repair work when an owner fails to address a hazardous condition pursuant to the requirements of an HPD issued violation. HPD issues violations when an owner fails to address a condition pursuant New York City Housing Maintenance Code (HMC) or the New York State Multiple Dwelling Law (MDL), a Department of Buildings Declaration of Emergency, a Department of Health Commissioner's Order to Abate or an emergency violation issued by another City Agency. The work orders were issued to a private vendor following the City's Procurement Rules.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag     | omoid                  | OMOID                  | text          | number        |
| Yes      | series tag     | omonumber              | OMONumber              | text          | text          |
| Yes      | series tag     | buildingid             | BuildingID             | text          | number        |
| Yes      | series tag     | boro_id                | Boro ID                | text          | number        |
| Yes      | series tag     | boro                   | Boro                   | text          | text          |
| Yes      | series tag     | housenumber            | HouseNumber            | text          | text          |
| Yes      | series tag     | streetname             | StreetName             | text          | text          |
| Yes      | series tag     | apartment              | Apartment              | text          | text          |
| Yes      | series tag     | zip                    | Zip                    | text          | text          |
| Yes      | series tag     | block                  | Block                  | text          | number        |
| Yes      | series tag     | lot                    | Lot                    | text          | number        |
| Yes      | series tag     | lifecycle              | LifeCycle              | text          | text          |
| Yes      | series tag     | worktypegeneral        | WorkTypeGeneral        | text          | text          |
| Yes      | series tag     | omostatusreason        | OMOStatusReason        | text          | text          |
| Yes      | numeric metric | omoawardamount         | OMOAwardAmount         | number        | number        |
| Yes      | time           | omocreatedate          | OMOCreateDate          | calendar_date | calendar_date |
| Yes      | numeric metric | netchangeorders        | NetChangeOrders        | number        | number        |
| No       |                | omoawarddate           | OMOAwardDate           | calendar_date | calendar_date |
| Yes      | series tag     | isaep                  | IsAEP                  | text          | text          |
| Yes      | series tag     | iscommercialdemolition | IsCommercialDemolition | text          | text          |
| Yes      | series tag     | servicechargeflag      | ServiceChargeFlag      | text          | text          |
| Yes      | series tag     | femaeventid            | FEMAEventID            | text          | number        |
| Yes      | series tag     | femaevent              | FEMAEvent              | text          | text          |
| Yes      | series tag     | omodescription         | OMODescription         | text          | text          |
```

## Time Field

```ls
Value = omocreatedate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = omoawarddate
```

## Data Commands

```ls
series e:mdbu-nrqn d:2004-03-30T00:00:00.000Z t:zip=10459 t:servicechargeflag=False t:boro=BRONX t:buildingid=79393 t:omostatusreason="OMO Completed" t:block=2975 t:apartment=12 t:boro_id=2 t:housenumber=918 t:worktypegeneral=GC t:lifecycle=Building t:lot=22 t:omoid=1266282 t:omodescription="replace the shower bodyand restore the bathroom tiles. remove all work related debris. note: contractor must contact hpd @ (718) 636-3021, 636-302" t:omonumber=E420056 t:streetname="FREEMAN STREET" m:netchangeorders=0 m:omoawardamount=589

series e:mdbu-nrqn d:2004-04-20T00:00:00.000Z t:zip=10032 t:servicechargeflag=False t:boro=MANHATTAN t:buildingid=42969 t:omostatusreason="OMO Completed" t:block=2122 t:apartment=23 t:boro_id=1 t:housenumber=535 t:worktypegeneral=GC t:lifecycle=Building t:lot=15 t:omoid=1277761 t:omodescription="apt.#23 ; first bedroom livingroom and 3rd. room which is a bedroom, wash all north window walls. in each room with bleach and water solution to" t:omonumber=E422270 t:streetname="WEST 162 STREET" m:netchangeorders=0 m:omoawardamount=412

series e:mdbu-nrqn d:2004-05-11T00:00:00.000Z t:zip=10472 t:servicechargeflag=False t:boro=BRONX t:buildingid=51077 t:omostatusreason="OMO Completed" t:block=3774 t:apartment=1R t:boro_id=2 t:housenumber=1250 t:worktypegeneral=GC t:lifecycle=Building t:lot=31 t:omoid=1289459 t:omodescription="(apt. #1r) trace, locate and repair leak affecting kitchen ceiling. demolish approx. 25 sq. ft. and install new fire resistant, water proof sheetroc" t:omonumber=E423722 t:streetname="BOYNTON AVENUE" m:netchangeorders=0 m:omoawardamount=680
```

## Meta Commands

```ls
metric m:omoawardamount p:float l:OMOAwardAmount d:"Amount this OMO was awarded for" t:dataTypeName=number

metric m:netchangeorders p:integer l:NetChangeOrders d:"Net value of approved Change Orders associated with this OMO" t:dataTypeName=number

entity e:mdbu-nrqn l:"Open Market Order (OMO) Charges" t:attribution="Department of Housing Preservation and Development (HPD)" t:url=https://data.cityofnewyork.us/api/views/mdbu-nrqn

property e:mdbu-nrqn t:meta.view v:id=mdbu-nrqn v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/hpd/html/pr/HPD-Open-Data.shtml v:averageRating=0 v:name="Open Market Order (OMO) Charges" v:attribution="Department of Housing Preservation and Development (HPD)"

property e:mdbu-nrqn t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:mdbu-nrqn t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| omoid   | omonumber | buildingid | boro_id | boro          | housenumber | streetname         | apartment | zip   | block | lot | lifecycle | worktypegeneral | omostatusreason     | omoawardamount | omocreatedate       | netchangeorders | omoawarddate        | isaep | iscommercialdemolition | servicechargeflag | femaeventid | femaevent | omodescription                                                                                                                                        | 
| ======= | ========= | ========== | ======= | ============= | =========== | ================== | ========= | ===== | ===== | === | ========= | =============== | =================== | ============== | =================== | =============== | =================== | ===== | ====================== | ================= | =========== | ========= | ===================================================================================================================================================== | 
| 1266282 | E420056   | 79393      | 2       | BRONX         | 918         | FREEMAN STREET     | 12        | 10459 | 2975  | 22  | Building  | GC              | OMO Completed       | 589.00         | 2004-03-30T00:00:00 | 0               | 2004-04-08T00:00:00 |       |                        | False             |             |           | replace the shower bodyand restore the bathroom tiles. remove all work related debris. note: contractor must contact hpd @ (718) 636-3021, 636-302    | 
| 1277761 | E422270   | 42969      | 1       | MANHATTAN     | 535         | WEST 162 STREET    | 23        | 10032 | 2122  | 15  | Building  | GC              | OMO Completed       | 412.00         | 2004-04-20T00:00:00 | 0               | 2004-05-04T00:00:00 |       |                        | False             |             |           | apt.#23 ; first bedroom livingroom and 3rd. room which is a bedroom, wash all north window walls. in each room with bleach and water solution to      | 
| 1289459 | E423722   | 51077      | 2       | BRONX         | 1250        | BOYNTON AVENUE     | 1R        | 10472 | 3774  | 31  | Building  | GC              | OMO Completed       | 680.00         | 2004-05-11T00:00:00 | 0               | 2004-05-26T00:00:00 |       |                        | False             |             |           | (apt. #1r) trace, locate and repair leak affecting kitchen ceiling. demolish approx. 25 sq. ft. and install new fire resistant, water proof sheetroc  | 
| 1270285 | E420819   | 103016     | 2       | BRONX         | 1840        | PHELAN PLACE       |           | 10453 | 2879  | 235 | Building  | GC              | OMO Completed       | 280.00         | 2004-04-06T00:00:00 | 0               | 2004-04-20T00:00:00 |       |                        | False             |             |           | (public area) supply and install new bottom rungs on drop ladders of left and right side fire escapes located on building front, and restore opera    | 
| 1291760 | E424102   | 718205     | 5       | STATEN ISLAND | 115         | BROOK STREET       |           | 10301 | 35    | 112 | Building  | GC              | OMO Completed       | 725.00         | 2004-05-14T00:00:00 | 0               | 2004-05-26T00:00:00 |       |                        | False             |             |           | repair broken concrete treads #; 13; 17; 18; 19; nad 20 up first to third story right yard. *note: contractor must contact hpd @ (718) 636-3021, 63   | 
| 1266673 | E420116   | 92701      | 2       | BRONX         | 2303        | LORING PLACE NORTH |           | 10468 | 3225  | 181 | Building  | GC              | OMO Completed       | 253.00         | 2004-03-31T00:00:00 | 0               | 2004-04-09T00:00:00 |       |                        | False             |             |           | (public area) supply and install safety glass at two side lites at front entrance door. approx. 8'' x 6'. remove all work related debris. *co         | 
| 1297110 | E424702   | 322209     | 3       | BROOKLYN      | 474         | LAFAYETTE AVENUE   | 4B        | 11205 | 1950  | 20  | Building  | DELEAD          | OMO Completed       | 1743.00        | 2004-05-25T00:00:00 | 0               | 2004-06-01T00:00:00 |       |                        | False             |             |           | erp ll/38 violation: as per rc #20030025806 (pdg) and attached scope of work thoroughly remove all lead violations as per new york city health sectio | 
| 1285180 | E423191   | 315929     | 3       | BROOKLYN      | 46          | IRVING AVENUE      | 1/R       | 11237 | 3187  | 30  | Building  | DELEAD          | OMO Completed       | 1614.00        | 2004-05-04T00:00:00 | 0               | 2004-05-18T00:00:00 |       |                        | False             |             |           | erp ll/38 violation: as per rc #20030025806 (pdg) and attached scope of work thoroughly remove all lead violations as per new york city health sectio | 
| 1303664 | E425391   | 20594      | 1       | MANHATTAN     | 24          | EAST 125 STREET    |           | 10035 | 1749  | 60  | Building  | GC              | OMO Completed       | 650.00         | 2004-06-07T00:00:00 | 0               | 2004-06-10T00:00:00 |       |                        | False             |             |           | remove 10 cubic yards of rubbish at building entrance stairs. note: contractor must contact hpd @ (718) 636-3021, 636-3026, 636-3056, with start da   | 
| 1314701 | E426879   | 42164      | 1       | MANHATTAN     | 507         | WEST 147 STREET    | 12        | 10031 | 2079  | 25  | Building  | GC              | Complainant Refused | 399.00         | 2004-06-28T00:00:00 | 0               | 2004-07-09T00:00:00 |       |                        | True              |             |           | apt.#12 repair/ restore defective fire escape window in 1st. room to proper working order *note: contractor must contact @ (718) 636-3021, 636-30     | 
```