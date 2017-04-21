# CDPH Storage Tanks

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdph-storage-tanks-46e93) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ug5u-hxnx) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ug5u-hxnx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ug5u-hxnx/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ug5u-hxnx |
| Name | CDPH Storage Tanks |
| Attribution | Department of Public Health |
| Category | Environment & Sustainable Development |
| Tags | ust, ast, tanks |
| Created | 2012-08-28T16:59:51Z |
| Publication Date | 2017-04-19T14:11:26Z |

## Description

This dataset contains Aboveground Storage Tank (AST) and Underground Storage Tank (UST) information from the Department of Public Health?s (CDPH) Tank Asset Database. The Tank Asset Database contains tank information from CDPH AST and UST permit applications as well as UST records imported from the historic Department of Environment (DOE) database. This dataset also includes AST records from the historic DOE and pre-1992 UST records from the Building Department. 
Data fields requiring description are detailed below. 
MAPPED LOCATION: Contains latitude/longitude coordinates of the site as determined through the Chicago Open Data Portal?s geocoding engine. In instances where the facility address is a range, the lower number (the value in the ?Street Number From? column) is used for geocoding. For example, for the range address 1000-1005 S Wabash Ave, the Mapped Location would be the coordinates for 1000 S Wabash Ave. 
 TANK TYPE:  Specifies if the asset is an Underground Storage Tank or an Aboveground Storage Tank.  
FACILITY ID: This is the unique identifier of the facility. A UST Facility ID that is seven digits long and begins with the number ?2? is a Facility ID assigned by the Office of the State Fire Marshall (OSFM). All other IDs were assigned by the DOE or CDPH based on the facility address.   
OWNER: The owner of record for the tank. For State-regulated USTs, this is the owner registered with the OSFM. 
FACILITY NAME: This is the name given to the facility. This is usually the company/owner name, building name or address.  
TANK ID: This is a numeric ID that uniquely identifies a particular tank at the facility. 
TANK MATERIAL: Specifies the type of material the tank is made of. 
TANK PRODUCT: Specifies the type of product stored in the tank.    
TANK CAPACITY: This is the storage volume of the tank in gallons. 
INSTALLATION DATE: The date the tank was installed at the facility if known. For some records, this information is in the COMMENTS column.
REMOVAL DATE: The date the tank was removed from the facility if known.  For some records, this information is in the COMMENTS column.
LAST USED DATE: The date the tank was last in service if known.  For some records, this information is in the COMMENTS column.
COMMENT: Contains additional information on the tank that may include supplemental location information; field observations; removal, abandonment, or last used dates; permitting notes; and other miscellaneous information. 
DATA SOURCE: The city department that collected the data.

## Columns

```ls
| Included | Schema Type | Field Name             | Name               | Data Type     | Render Type   |
| ======== | =========== | ====================== | ================== | ============= | ============= |
| Yes      | series tag  | street_number          | STREET NUMBER FROM | text          | number        |
| Yes      | series tag  | street_number_to       | STREET NUMBER TO   | text          | number        |
| Yes      | series tag  | direction              | DIRECTION          | text          | text          |
| Yes      | series tag  | street_name            | STREET NAME        | text          | text          |
| Yes      | series tag  | street_type            | STREET TYPE        | text          | text          |
| Yes      | series tag  | tank_type              | TANK TYPE          | text          | text          |
| Yes      | series tag  | facility_id            | FACILITY ID        | text          | text          |
| Yes      | series tag  | applicant              | OWNER              | text          | text          |
| Yes      | series tag  | facility               | FACILITY NAME      | text          | text          |
| Yes      | series tag  | tank_id                | Tank ID            | text          | text          |
| Yes      | series tag  | tank_material          | TANK MATERIAL      | text          | text          |
| Yes      | series tag  | tank_construction      | TANK CONSTRUCTION  | text          | text          |
| Yes      | series tag  | tank_product           | TANK PRODUCT       | text          | text          |
| Yes      | series tag  | tank_capacity          | TANK CAPACITY      | text          | text          |
| Yes      | time        | installation_date      | INSTALLATION DATE  | calendar_date | calendar_date |
| No       |             | removal_abandoned_date | REMOVAL DATE       | calendar_date | calendar_date |
| No       |             | last_used_date         | LAST USED DATE     | calendar_date | calendar_date |
| Yes      | series tag  | comment                | COMMENT            | text          | text          |
| Yes      | series tag  | data_source            | DATA SOURCE        | text          | text          |
```

## Time Field

```ls
Value = installation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = removal_abandoned_date,last_used_date
```

## Data Commands

```ls
series e:ug5u-hxnx d:2017-04-19T13:59:12.000Z t:direction=Direction t:tank_construction="Tank Construction" t:street_name="Street Name" t:data_source="Data Source" t:tank_capacity="Tank Capacity" t:facility_id="Facility ID" t:tank_type="Tank Type" t:tank_material="Tank Material" t:tank_product="Tank Product" t:facility=Facility t:applicant=Applicant t:tank_id="Tank ID" t:comment=Comment t:street_type="Street Type" m:row_number.ug5u-hxnx=1

series e:ug5u-hxnx d:1966-11-30T00:00:00.000Z t:facility="FIRST CHICAGO BUILDING CORPORATION" t:street_number_to=1 t:direction=S t:data_source="HISTORIC DEPT. OF BUILDINGS" t:street_name="FIRST NATIONAL" t:street_number=1 t:comment="WORK BY: G. NEWBERG; ENCLOSE 1-5260 GAL DIESAL OIL TANK     FINAL  12/5/68" t:tank_type="UNDERGROUND STORAGE TANK" t:facility_id=0001FIR1966-11-30 m:row_number.ug5u-hxnx=2

series e:ug5u-hxnx d:1976-05-21T00:00:00.000Z t:facility="FIRST CHICAGO BUILDING CORPORATION" t:street_number_to=1 t:direction=S t:data_source="HISTORIC DEPT. OF BUILDINGS" t:street_name="FIRST NATIONAL" t:street_number=1 t:comment="WORK BY: GUST K. NEWBERG; INSTALL 1-2K GAL DIESAL OIL TANK       FINAL  5/28/76" t:tank_type="UNDERGROUND STORAGE TANK" t:facility_id=0001FIR1976-05-21 m:row_number.ug5u-hxnx=3
```

## Meta Commands

```ls
metric m:row_number.ug5u-hxnx p:long l:"Row Number"

entity e:ug5u-hxnx l:"CDPH Storage Tanks" t:attribution="Department of Public Health" t:url=https://data.cityofchicago.org/api/views/ug5u-hxnx

property e:ug5u-hxnx t:meta.view v:id=ug5u-hxnx v:category="Environment & Sustainable Development" v:attributionLink=http://www.cityofchicago.org/city/en/depts/cdph.html v:averageRating=0 v:name="CDPH Storage Tanks" v:attribution="Department of Public Health"

property e:ug5u-hxnx t:meta.view.owner v:id=e3v2-km8a v:screenName=Renante v:displayName=Renante

property e:ug5u-hxnx t:meta.view.tableauthor v:id=e3v2-km8a v:screenName=Renante v:roleName=publisher v:displayName=Renante
```

## Top Records

```ls
| street_number | street_number_to | direction | street_name    | street_type | tank_type                | facility_id       | applicant                           | facility                           | tank_id | tank_material | tank_construction   | tank_product    | tank_capacity                   | installation_date   | removal_abandoned_date | last_used_date | comment                                                                    | data_source                  | 
| ============= | ================ | ========= | ============== | =========== | ======================== | ================= | =================================== | ================================== | ======= | ============= | =================== | =============== | =============================== | =================== | ====================== | ============== | ========================================================================== | ============================ | 
|               |                  | Direction | Street Name    | Street Type | Tank Type                | Facility ID       | Applicant                           | Facility                           | Tank ID | Tank Material | Tank Construction   | Tank Product    | Tank Capacity                   |                     |                        |                | Comment                                                                    | Data Source                  | 
| 1             | 1                | S         | FIRST NATIONAL |             | UNDERGROUND STORAGE TANK | 0001FIR1966-11-30 |                                     | FIRST CHICAGO BUILDING CORPORATION |         |               |                     |                 |                                 | 1966-11-30T00:00:00 |                        |                | WORK BY: G. NEWBERG; ENCLOSE 1-5260 GAL DIESAL OIL TANK FINAL 12/5/68      | HISTORIC DEPT. OF BUILDINGS  | 
| 1             | 1                | S         | FIRST NATIONAL |             | UNDERGROUND STORAGE TANK | 0001FIR1976-05-21 |                                     | FIRST CHICAGO BUILDING CORPORATION |         |               |                     |                 |                                 | 1976-05-21T00:00:00 |                        |                | WORK BY: GUST K. NEWBERG; INSTALL 1-2K GAL DIESAL OIL TANK FINAL 5/28/76   | HISTORIC DEPT. OF BUILDINGS  | 
| 100           | 100              | E         | 65TH           | ST          | UNDERGROUND STORAGE TANK | 1E+671962-08-16   |                                     | ENGLEWOOD IRON & METAL             |         |               |                     |                 |                                 | 1962-08-16T00:00:00 |                        |                | WORK BY: ROBERT YOUNG INC.; INSTALL 1-2K GAL GSLN TK FINAL 8/28/62         | HISTORIC DEPT. OF BUILDINGS  | 
| 1000          | 1000             | W         | SHERWIN        | AVE         | UNDERGROUND STORAGE TANK | 1000SHE1963-07-23 |                                     | ROCK ISLAND RAILROAD               |         |               |                     |                 |                                 | 1963-07-23T00:00:00 |                        |                | WORK BY: P. J. HARTMANN; INSTALL 1-8K GAS                                  | HISTORIC DEPT. OF BUILDINGS  | 
| 10000         |                  | W         | IRVING PARK    | RD          | ABOVEGROUND STORAGE TANK | AMERICANEAG       | AMEIRCAN EAGLE AIRLINES             | AMERICAN EAGLE AIRLINES            |         |               | SINGLE WALLED STEEL | MOTOR OIL       | NO. OF TANKS: 1 (240 GALLON)    |                     |                        |                | DATE OF REPORT: 04/15/2004                                                 | HISTORIC DEPT.OF ENVIRONMENT | 
| 10000         |                  | W         | IRVING PARK    | RD          | ABOVEGROUND STORAGE TANK | AMFOHARE          | CITY OF CHICAGO/DEPT OF AVIATION    | AMF OHARE/AIRPORT OWNERS REPRESENT |         |               | UNKNOWN             | EMPTY           | NO. OF TANKS: 1 (1,000 GALLON)  |                     |                        |                | DATE OF REPORT: 08/01/2003                                                 | HISTORIC DEPT.OF ENVIRONMENT | 
| 10000         |                  | W         | IRVING PARK    | RD          | ABOVEGROUND STORAGE TANK | AORCOMPLEX        | CITY OF CHICAGO/DEPT OF AVIATION    | O'HARE AIRPORT/AOR COMPLEX         |         |               | STEEL               | GASOLINE        | NO. OF TANKS: 1 (1,000)         |                     |                        |                | DATE OF REPORT: 02/04/1998 4/29/98:INSTALLED 1-1K GALLON TANK OF GASOLINE. | HISTORIC DEPT.OF ENVIRONMENT | 
| 10000         |                  | W         | IRVING PARK    | RD          | ABOVEGROUND STORAGE TANK | ASR-7/OHARE       | DEPT. OF TRANSPORTATION/FAA CHI/SMO | O'HARE AIRPORT/ASR-7               |         |               | STEEL               | DIESEL          | NO. OF TANKS: 1 (1,000 GALLONS) |                     |                        |                | DATE OF REPORT: 03/24/1998 5/14/98:INSTALLED 1-1K GALLON TANK OF DIESEL.   | HISTORIC DEPT.OF ENVIRONMENT | 
| 10000         |                  | W         | IRVING PARK    | RD          | ABOVEGROUND STORAGE TANK | CARGOTRUCK        | CITY OF CHICAGO/DEPT OF AVIATION    | O'HARE AIRPORT/CARGO TRUCK FILL    |         |               | SINGLE WALL STEEL   | ETHYLENE CLYCOL | NO. OF TANKS: 1 (25,000 GALLON) |                     |                        |                | DATE OF REPORT: 11/05/1998                                                 | HISTORIC DEPT.OF ENVIRONMENT | 
```