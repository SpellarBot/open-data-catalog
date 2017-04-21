# Denied licensees and registrants for trade waste

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/denied-licensees-and-registrants-for-trade-waste-8b412) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/5t7n-dizh) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/5t7n-dizh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/5t7n-dizh/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 5t7n-dizh |
| Name | Denied licensees and registrants for trade waste |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Business |
| Tags | wholesale, vendor, license, registration, trade waste, denied |
| Created | 2011-10-08T21:49:55Z |
| Publication Date | 2013-06-21T19:30:44Z |

## Description

Denied licensees and registrants for trade waste

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | type           | TYPE           | text      | text        |
| Yes      | series tag  | bus_name       | BUS NAME       | text      | text        |
| Yes      | series tag  | mailing_office | MAILING OFFICE | text      | text        |
| Yes      | series tag  | mail_city      | MAIL CITY      | text      | text        |
| Yes      | series tag  | mstat          | MSTAT          | text      | text        |
| Yes      | series tag  | comp_phone     | COMP PHONE     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:5t7n-dizh d:2011-10-08T14:49:56.000Z t:mstat=NY t:comp_phone="(914) 423-3906" t:mailing_office="1270 SAW MILL RIVER ROAD" t:mail_city=YONKERS t:bus_name="A & D CARTING CORP." t:type=LICENSE m:row_number.5t7n-dizh=1

series e:5t7n-dizh d:2011-10-08T14:49:56.000Z t:mstat=NY t:comp_phone="(718) 824-2365" t:mailing_office="1641 RESEACH AVENUE" t:mail_city=BRONX t:bus_name="A.C. CARTING OF NEW YORK INC." t:type=CL.2-EXEMPT m:row_number.5t7n-dizh=2

series e:5t7n-dizh d:2011-10-08T14:49:56.000Z t:mstat=NY t:comp_phone="(516) 746-2935" t:mailing_office="50 2ND AVENUE" t:mail_city="GARDEN CITY PARK" t:bus_name="A.V.F. CARTING CO. INC." t:type=LICENSE m:row_number.5t7n-dizh=3
```

## Meta Commands

```ls
metric m:row_number.5t7n-dizh p:long l:"Row Number"

entity e:5t7n-dizh l:"Denied licensees and registrants for trade waste" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/5t7n-dizh

property e:5t7n-dizh t:meta.view v:id=5t7n-dizh v:category=Business v:averageRating=0 v:name="Denied licensees and registrants for trade waste" v:attribution="Taxi and Limousine Commission (TLC)"

property e:5t7n-dizh t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:5t7n-dizh t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | type        | bus_name                       | mailing_office           | mail_city        | mstat | comp_phone     | 
| =========== | =========== | ============================== | ======================== | ================ | ===== | ============== | 
| 1318085396  | LICENSE     | A & D CARTING CORP.            | 1270 SAW MILL RIVER ROAD | YONKERS          | NY    | (914) 423-3906 | 
| 1318085396  | CL.2-EXEMPT | A.C. CARTING OF NEW YORK INC.  | 1641 RESEACH AVENUE      | BRONX            | NY    | (718) 824-2365 | 
| 1318085396  | LICENSE     | A.V.F. CARTING CO. INC.        | 50 2ND AVENUE            | GARDEN CITY PARK | NY    | (516) 746-2935 | 
| 1318085396  | LICENSE     | A-1 MEDICAL WASTE REMOVAL INC. | 60 HUNT LANE             | STATEN ISLAND    | NY    | (718) 494-2083 | 
| 1318085396  | CL.2-EXEMPT | ABSTRACT EQUIPMENT INC.        | 125 HALF MILE RD STE.200 | REDBANK          | NJ    | (917) 418-5829 | 
| 1318085396  | CL.2-EXEMPT | ACA WASTE SERVICES INC.        | 40 EAD STREET            | WEST BABYLON     | NY    | (631) 391-9300 | 
| 1318085396  | CL.2-EXEMPT | ACE CONCRETE PAVING CORP.      | P.O. BOX 1789            | BRONX            | NY    | (718) 665-4004 | 
| 1318085396  | LICENSE     | ADVANCED WASTE SERVICES INC.   | 2400 NATIONAL DRIVE      | BROOKLYN         | NY    | (718) 251-5300 | 
| 1318085396  | CL.2-EXEMPT | ALEX FIGLIOLIA PLUMBING CO.    | 420 CARROLL STREET       | BROOKLYN         | NY    | (718) 852-8700 | 
| 1318085396  | CL.2-EXEMPT | ALL PRO CONTRACTING, LLC       | 180 HICKORY STREET       | ORANGE           | NJ    | (973) 675-9933 | 
```