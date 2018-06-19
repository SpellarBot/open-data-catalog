# County Emergency Management Offices

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/county-emergency-management-offices) |
| Metadata | [Link](https://data.ny.gov/api/views/jwkb-x5v6) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/jwkb-x5v6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/jwkb-x5v6/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | jwkb-x5v6 |
| Name | County Emergency Management Offices |
| Attribution | New York State Division of Homeland Security and Emergency Services (DHSES) |
| Category | Public Safety |
| Tags | emo, emergency services, oem |
| Created | 2014-12-10T18:52:15Z |
| Publication Date | 2016-02-24T16:30:57Z |

## Description

This dataset lists the County, Emergency Manager Name, Address and Office Phone Number for all Emergency Management Offices within NYS.  The New York State Office of Emergency Management (OEM) and its predecessor agencies have been responsible for coordinating the activities of all State agencies to protect New York's communities, the State's economic well-being, and the environment from natural and man-made disasters and emergencies.

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| No       | time        | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag  | county            | County            | text      | text        |
| Yes      | series tag  | emergency_manager | Emergency Manager | text      | text        |
| No       |             | address           | Address           | text      | text        |
| Yes      | series tag  | city              | City              | text      | text        |
| Yes      | series tag  | state             | State             | text      | text        |
| Yes      | series tag  | zip_code          | Zip Code          | text      | number      |
| Yes      | series tag  | business_phone    | Business Phone    | text      | text        |
| No       |             | lattitude         | Latitude          | number    | number      |
| No       |             | longitude         | Longitude         | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,lattitude,longitude
```

## Data Commands

```ls
series e:jwkb-x5v6 d:2016-02-24T08:29:53.000Z t:business_phone="(518) 720-8026" t:zip_code=12041 t:county=ALBANY t:state=NY t:emergency_manager="TOM REMMERT" t:city="NEW SCOTLAND" m:row_number.jwkb-x5v6=1

series e:jwkb-x5v6 d:2016-02-24T08:29:53.000Z t:business_phone="(585) 268-5290" t:zip_code=14813 t:county=ALLEGANY t:state=NY t:emergency_manager="JEFF LUCKEY" t:city=BELMONT m:row_number.jwkb-x5v6=2

series e:jwkb-x5v6 d:2016-02-24T08:29:53.000Z t:business_phone="(607) 778-1178" t:zip_code=13905 t:county=BROOME t:state=NY t:emergency_manager="MIKE PONTICIELLO" t:city=BINGHAMTON m:row_number.jwkb-x5v6=3
```

## Meta Commands

```ls
metric m:row_number.jwkb-x5v6 p:long l:"Row Number"

entity e:jwkb-x5v6 l:"County Emergency Management Offices" t:attribution="New York State Division of Homeland Security and Emergency Services (DHSES)" t:url=https://data.ny.gov/api/views/jwkb-x5v6

property e:jwkb-x5v6 t:meta.view v:id=jwkb-x5v6 v:category="Public Safety" v:attributionLink=http://www.dhses.ny.gov v:averageRating=0 v:name="County Emergency Management Offices" v:attribution="New York State Division of Homeland Security and Emergency Services (DHSES)"

property e:jwkb-x5v6 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:jwkb-x5v6 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:jwkb-x5v6 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | county      | emergency_manager    | address                           | city          | state | zip_code | business_phone | lattitude | longitude  | 
| =========== | =========== | ==================== | ================================= | ============= | ===== | ======== | ============== | ========= | ========== | 
| 1456302593  | ALBANY      | TOM REMMERT          | 58 VERDA AVENUE PO BOX A          | NEW SCOTLAND  | NY    | 12041    | (518) 720-8026 | 42.774883 | -73.701253 | 
| 1456302593  | ALLEGANY    | JEFF LUCKEY          | 6087 STATE ROUTE 19               | BELMONT       | NY    | 14813    | (585) 268-5290 | 42.211386 | -78.017442 | 
| 1456302593  | BROOME      | MIKE PONTICIELLO     | 153 LT VAN WINKLE DRIVE           | BINGHAMTON    | NY    | 13905    | (607) 778-1178 | 42.11418  | -75.93491  | 
| 1456302593  | CATTARAUGUS | CHRISTOPHER BAKER    | 303 COURT STREET                  | LITTLE VALLEY | NY    | 14755    | (716) 938-2240 | 42.251608 | -78.800712 | 
| 1456302593  | CAYUGA      | BRIAN DAHL           | 7445 COUNTY HOUSE ROAD            | AUBURN        | NY    | 13021    | (315) 255-1161 | 42.929799 | -76.569932 | 
| 1456302593  | CHAUTAUQUA  | JULIUS LEONE JR      | 2 ACADEMY STREET SUITE A ROOM 106 | MAYVILLE      | NY    | 14757    | (716) 753-4341 | 42.253374 | -79.50612  | 
| 1456302593  | CHEMUNG     | MARK CICORA          | 425 PENNSYLVANIA AVE PO BOX 588   | ELMIRA        | NY    | 14902    | (607) 737-2928 | 42.078162 | -76.80213  | 
| 1456302593  | CHEMUNG     | KRISTEN CARD-GRIFFEN | 425 PENNSYLVANIA AVE PO BOX 588   | ELMIRA        | NY    | 14902    | (607) 737-2095 | 42.078162 | -76.80213  | 
| 1456302593  | CHENANGO    | MATTHEW BECKWITH     | 279 COUNTY RD 46                  | NORWICH       | NY    | 13815    | (607) 337-1862 | 42.55025  | -75.56506  | 
| 1456302593  | CLINTON     | ERIC DAY             | 16 EMERGENCY SERVICES DRIVE       | PLATTSBURGH   | NY    | 12903    | (518) 565-4792 | 44.6723   | -73.45183  | 
```