# Approved licensees and registrants for trade waste

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/approved-licensees-and-registrants-for-trade-waste-15675) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/tphb-2tdm) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/tphb-2tdm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/tphb-2tdm/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | tphb-2tdm |
| Name | Approved licensees and registrants for trade waste |
| Attribution | Business Integrity Commission (BIC) |
| Category | Business |
| Tags | wholesale, vendor, license, registration, trade waste, approved |
| Created | 2011-10-08T21:33:33Z |
| Publication Date | 2013-06-21T19:28:40Z |

## Description

Approved licensees and registrants for trade waste

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
series e:tphb-2tdm d:2011-10-08T14:33:36.000Z t:mstat=ON t:comp_phone="(201) 865-2480" t:mailing_office="2794 SOUTH SHERIDAN WAY" t:mail_city=OAKVILLE t:bus_name="SHRED-IT USA INC." t:type=LICENSE m:row_number.tphb-2tdm=1

series e:tphb-2tdm d:2011-10-08T14:33:38.000Z t:mstat=NY t:comp_phone="(718) 712-1929" t:mailing_office="PO BOX 21" t:mail_city="GLEN COVE" t:bus_name="NEIGHBORHOOD GARDENING SERVICE" t:type=CL.1 m:row_number.tphb-2tdm=2

series e:tphb-2tdm d:2011-10-08T14:33:39.000Z t:mstat=NY t:comp_phone="(718) 855-1717" t:mailing_office="BROOKLYN NAVY YARD, BLDG#7,63 FLUSHING AVE, UNT313" t:mail_city=BROOKLYN t:bus_name="AGGER FISH CORP." t:type=CL.1 m:row_number.tphb-2tdm=3
```

## Meta Commands

```ls
metric m:row_number.tphb-2tdm p:long l:"Row Number"

entity e:tphb-2tdm l:"Approved licensees and registrants for trade waste" t:attribution="Business Integrity Commission (BIC)" t:url=https://data.cityofnewyork.us/api/views/tphb-2tdm

property e:tphb-2tdm t:meta.view v:id=tphb-2tdm v:category=Business v:averageRating=0 v:name="Approved licensees and registrants for trade waste" v:attribution="Business Integrity Commission (BIC)"

property e:tphb-2tdm t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:tphb-2tdm t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```

## Top Records

```ls
| :updated_at | type        | bus_name                            | mailing_office                                     | mail_city     | mstat | comp_phone     | 
| =========== | =========== | =================================== | ================================================== | ============= | ===== | ============== | 
| 1318084416  | LICENSE     | SHRED-IT USA INC.                   | 2794 SOUTH SHERIDAN WAY                            | OAKVILLE      | ON    | (201) 865-2480 | 
| 1318084418  | CL.1        | NEIGHBORHOOD GARDENING SERVICE      | PO BOX 21                                          | GLEN COVE     | NY    | (718) 712-1929 | 
| 1318084419  | CL.1        | AGGER FISH CORP.                    | BROOKLYN NAVY YARD, BLDG#7,63 FLUSHING AVE, UNT313 | BROOKLYN      | NY    | (718) 855-1717 | 
| 1318084422  | CL.1        | A TO Z LANDSCAPING, INC             | P.O. BOX 140678                                    | STATEN ISLAND | NY    | (718) 815-2484 | 
| 1318084422  | CL.1        | A. BIANCO LANDSCAPING               | 660 GULF AVENUE                                    | STATEN ISLAND | NY    | (718) 420-0901 | 
| 1318084422  | CL.1        | A. PALMIERI LANDSCAPING CO. INC     | 820 SOUTH FULTON AVE.                              | MOUNT VERNON  | NY    | (914) 699-2257 | 
| 1318084422  | CL.1        | 3J'S LAWN MAINTENANCE & LANDSCAPING | 388 DOANE AVENUE                                   | STATEN ISLAND | NY    | (718) 966-0351 | 
| 1318084422  | CL.1        | AB GARDEN CENTER INC                | 162-24 DEPOT ROAD                                  | FLUSHING      | NY    | (718) 762-2689 | 
| 1318084422  | CL.1        | A & S WHITESTONE NURSERY INC.       | 23-02 FRANCIS LEWIS BLVD.                          | WHITESTONE    | NY    | (718) 746-0580 | 
| 1318084424  | CL.2-EXEMPT | J.B CUSTOM MASONRY & CONCRETE INC.  | 104-11 101 STREET                                  | OZONE PARK    | NY    | (718) 322-9093 | 
```