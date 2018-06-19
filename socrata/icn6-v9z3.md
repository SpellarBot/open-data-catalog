# Crime

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/crime) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/icn6-v9z3) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/icn6-v9z3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/icn6-v9z3/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | icn6-v9z3 |
| Name | Crime |
| Category | Public Safety |
| Tags | crime, incidents, robberies, theft, assault, district, arson, montgomery, maryland, mdcoordinationcrime |
| Created | 2015-03-24T23:42:50Z |
| Publication Date | 2016-11-15T23:48:05Z |

## Description

Updated daily postings on Montgomery County?s open data website, dataMontgomery, provide the public with direct access to crime statistic databases - including raw data, mapping and search functions ? of reported County crime. The data presented is derived from reported crimes classified according to Maryland criminal code and documented by approved police incident reports. The data is compiled by ?EJustice?, a respected law enforcement records-management system used by the Montgomery County Police Department and many other law enforcement agencies. To protect victims? privacy, no names or other personal information are released. Residential addresses are rounded to the nearest hundred block. All data is refreshed on a quarterly basis to reflect any changes in status due to on-going police investigation. 
Data Montgomery allows the public to query the Montgomery County Police Department's database of founded crime. The information contained herein includes all founded crimes reported after July 2013 and entered to-date utilizing Incident Based Reporting (IBR) rules. Please note that under IBR rules multiple offenses may appear as part of a single founded reported incident. Please note that these crime reports are based on preliminary information supplied to the Police Department by the reporting parties. Therefore, the crime data available on this web page may reflect:
-Information not yet verified by further investigation
-Addresses that have been rounded may reflect law --enforcement sites that do not represent the incident location.
-Information that may include attempted and reported crime
-Preliminary crime classifications that may be changed at a later date based upon further investigation
-Information that may include mechanical or human error
-Arrest information [Note: all arrested persons are presumed innocent until proven guilty in a court of law

Update Frequency:  Daily

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | =========== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag  | incident_id            | Incident ID            | text          | text          |
| Yes      | series tag  | case_number            | CR Number              | text          | text          |
| Yes      | time        | date                   | Dispatch Date / Time   | calendar_date | calendar_date |
| Yes      | series tag  | incident_type          | Class                  | text          | text          |
| Yes      | series tag  | narrative              | Class Description      | text          | text          |
| Yes      | series tag  | district               | Police District Name   | text          | text          |
| No       |             | location               | Block Address          | text          | text          |
| Yes      | series tag  | city                   | City                   | text          | text          |
| Yes      | series tag  | state                  | State                  | text          | text          |
| Yes      | series tag  | zip_code               | Zip Code               | text          | number        |
| Yes      | series tag  | agency                 | Agency                 | text          | text          |
| Yes      | series tag  | place                  | Place                  | text          | text          |
| Yes      | series tag  | sector                 | Sector                 | text          | text          |
| Yes      | series tag  | beat                   | Beat                   | text          | text          |
| Yes      | series tag  | pra                    | PRA                    | text          | text          |
| No       |             | start_date             | Start Date / Time      | calendar_date | calendar_date |
| No       |             | end_date               | End Date / Time        | calendar_date | calendar_date |
| Yes      | series tag  | police_district_number | Police District Number | text          | text          |
| No       |             | address_number         | Address Number         | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = location,start_date,end_date,address_number
```

## Data Commands

```ls
series e:icn6-v9z3 d:2014-08-25T20:04:00.000Z t:sector=G t:case_number=14041165 t:beat=3G1 t:zip_code=20910 t:narrative="ALL OTHER NON-TRAFFIC CRIM OFFENSES" t:state=MD t:agency=MCPD t:pra=94 t:incident_id=200986023 t:city="SILVER SPRING" t:incident_type=2791 t:police_district_number=3D t:district="SILVER SPRING" t:place="Street - Commercial" m:row_number.icn6-v9z3=1

series e:icn6-v9z3 d:2014-09-01T13:09:00.000Z t:sector=D t:case_number=14042282 t:beat=2D3 t:zip_code=20895 t:narrative="LARCENY FROM BUILDING OVER $200" t:state=MD t:agency=MCPD t:pra=180 t:incident_id=200986810 t:city=KENSINGTON t:incident_type=617 t:police_district_number=2D t:district=BETHESDA t:place="Residence - Shed" m:row_number.icn6-v9z3=2

series e:icn6-v9z3 d:2014-08-29T22:29:00.000Z t:sector=K t:case_number=14041909 t:beat=4K2 t:zip_code=20906 t:narrative="AGG ASSLT OTHER WPN SPOUSE/PARTNER" t:state=MD t:agency=MCPD t:pra=334 t:incident_id=200986526 t:city="SILVER SPRING" t:incident_type=433 t:police_district_number=4D t:district=WHEATON t:place="Street - Residential" m:row_number.icn6-v9z3=3
```

## Meta Commands

```ls
metric m:row_number.icn6-v9z3 p:long l:"Row Number"

entity e:icn6-v9z3 l:Crime t:url=https://data.montgomerycountymd.gov/api/views/icn6-v9z3

property e:icn6-v9z3 t:meta.view v:id=icn6-v9z3 v:category="Public Safety" v:averageRating=0 v:name=Crime

property e:icn6-v9z3 t:meta.view.license v:name="Public Domain"

property e:icn6-v9z3 t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:icn6-v9z3 t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| incident_id | case_number | date                | incident_type | narrative                            | district      | location              | city          | state | zip_code | agency | place                     | sector | beat | pra | start_date          | end_date            | police_district_number | address_number | 
| =========== | =========== | =================== | ============= | ==================================== | ============= | ===================== | ============= | ===== | ======== | ====== | ========================= | ====== | ==== | === | =================== | =================== | ====================== | ============== | 
| 200986023   | 14041165    | 2014-08-25T20:04:00 | 2791          | ALL OTHER NON-TRAFFIC CRIM OFFENSES  | SILVER SPRING | 8100 GEORGIA AVE      | SILVER SPRING | MD    | 20910    | MCPD   | Street - Commercial       | G      | 3G1  | 94  | 2014-08-25T20:04:00 |                     | 3D                     | 8100           | 
| 200986810   | 14042282    | 2014-09-01T13:09:00 | 617           | LARCENY FROM BUILDING OVER $200      | BETHESDA      | 10100 CEDAR LN        | KENSINGTON    | MD    | 20895    | MCPD   | Residence - Shed          | D      | 2D3  | 180 | 2014-08-31T00:00:00 | 2014-08-31T06:30:00 | 2D                     | 10100          | 
| 200986526   | 14041909    | 2014-08-29T22:29:00 | 433           | AGG ASSLT OTHER WPN SPOUSE/PARTNER   | WHEATON       | 12500 GOODHILL RD     | SILVER SPRING | MD    | 20906    | MCPD   | Street - Residential      | K      | 4K2  | 334 | 2014-08-29T22:29:00 |                     | 4D                     | 12500          | 
| 200986382   | 14041720    | 2014-08-28T20:19:00 | 634           | LARCENY FROM AUTO UNDER $50          | GERMANTOWN    | 20400 WATERS POINT LN | GERMANTOWN    | MD    | 20874    | MCPD   | Parking Lot - Residential | N      | 5N1  | 465 | 2014-08-27T14:00:00 | 2014-08-28T08:45:00 | 5D                     | 20400          | 
| 200986341   | 14041557    | 2014-08-27T23:09:00 | 1834          | CDS-POSS MARIJUANA/HASHISH           | SILVER SPRING | 8200 GEORGIA AVE      | SILVER SPRING | MD    | 20910    | MCPD   | Street - In vehicle       | G      | 3G1  | 94  | 2014-08-27T23:09:00 | 2014-08-27T23:09:00 | 3D                     | 8200           | 
| 200986855   | 14042356    | 2014-09-01T19:39:00 | 1532          | WEAPON DISCHARGING OTHER FIREARM     | WHEATON       | 12300 CHARLES RD      | SILVER SPRING | MD    | 20906    | MCPD   | Residence - Single Family | K      | 4K2  | 307 | 2014-09-01T19:39:00 |                     | 4D                     | 12300          | 
| 200986768   | 14042243    | 2014-09-01T07:37:00 | 2946          | RECOVERED PROPERTY/MONT. CO.         | ROCKVILLE     | 600 NELSON ST         | ROCKVILLE     | MD    | 20850    | RCPD   | Street - Residential      | A      | 1A3  | 246 | 2014-09-01T08:00:00 | 2014-09-01T08:13:00 | 1D                     | 600            | 
| 200986099   | 14039293    | 2014-08-15T14:37:00 | 614           | LARCENY FROM AUTO OVER $200          | SILVER SPRING | 9500 SEMINOLE ST      | SILVER SPRING | MD    | 20901    | MCPD   | Street - Residential      | G      | 3G2  | 122 | 2014-08-12T11:50:00 | 2014-08-12T13:50:00 | 3D                     | 9500           | 
| 200986051   | 14041368    | 2014-08-26T19:51:00 | 1716          | SEX OFFENSE - 4TH DEGREE SEX OFFENSE | WHEATON       | 4300 RANDOLPH RD      | SILVER SPRING | MD    | 20906    | MCPD   | Street - Bus Stop         | K      | 4K2  | 525 | 2014-08-26T11:30:00 | 2014-08-26T12:10:00 | 4D                     | 4300           | 
| 200985558   | 14040817    | 2014-08-23T14:24:00 | 711           | AUTO THEFT - PASSENGER VEHICLE       | SILVER SPRING | 3100 AUTOMOBILE BLVD  | SILVER SPRING | MD    | 20904    | MCPD   | Auto Dealership           | I      | 3I2  | 378 | 2014-08-20T12:00:00 | 2014-08-23T14:24:00 | 3D                     | 3100           | 
```