# CDPH Environmental Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdph-environmental-permits-ea315) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ir7v-8mc8) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ir7v-8mc8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ir7v-8mc8/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ir7v-8mc8 |
| Name | CDPH Environmental Permits |
| Attribution | Chicago Department of Public Health |
| Category | Environment & Sustainable Development |
| Tags | environmental permits |
| Created | 2012-08-28T20:53:14Z |
| Publication Date | 2017-04-19T14:25:46Z |

## Description

Permits issued by the Department of Environment (DOE) from January 1993 to December 31, 2011 and by the Department of Public Health (CDPH) since January 1, 2012. On January 1, 2012, the DOE was disbanded and all its inspection, permitting, and enforcement authorities were transferred to the CDPH.   
Data fields requiring description are detailed below. 
APPLICATION ID:  This is the unique id of the issued permit. Permits from the historic DOE are prefixed with ?DOE.? Permits issued by CDPH are prefixed with ?ENV_?
APPLICATION NAME: This is the name of the site that is being permitted. This is usually the company/owner name, address, or building name.  
MAPPED LOCATION: Contains latitude/longitude coordinates of the site as determined through the Chicago Open Data Portal?s geocoding engine. In instances where the facility address is a range, the lower number (the value in the ?Street Number From? column) is used for geocoding. For example, for the range address 1000-1005 S Wabash Ave, the Mapped Location would be the coordinates for 1000 S Wabash Ave. 
 APPLICATION TYPE:       
"ABOVEGROUND STORAGE TANK" Permits to install or remove an Above Ground Storage Tank (AST) for dispensing and non-dispensing with a volume greater than 110 gallons. For more information go to http://tinyurl.com/bg7yrvx. 
"UNDERGROUND STORAGE TANK"  Permits to install, upgrade, repair, remove, abandon a UST or install an interior lining or Stage II vapor recovery systems in a UST. For more information go to http://tinyurl.com/bkqa8a8.
?AIR POLLUTION CONTROL PERMIT? Permits to install, operate, erect, construct, reconstruct, alter or add a piece of process equipment, process area, or air pollution control equipment and for sandblasting, grinding or chemical washing of any building, facility, statue or other architectural surface. This also includes annual certificate of operation (COO) for regulated process equipment, process area, or air pollution control equipment as defined in 11-4-610 of the Municipal Code. For more information go to http://tinyurl.com/az7ph79 .  
?RECYCLING FACILITY? Permits for recycling facilities including but not limited to junkyards, scrap metal, vehicle, vehicle parts, clean construction and demolition debris, and composting facilities. For more information go to http://tinyurl.com/azzpa93 .
?WASTE HANDLING FACILITY? Permits for solid waste transfer stations, liquid waste facilities, and permanent rock crushing facilities. For more information, refer to Chapter 11-4 Article IX and Article XIV of the Municipal Code at   http://tinyurl.com/crvyb29.  
?TEMPORARY ROCK CRUSHING? Permits to temporarily process concrete debris at the construction or demolition site. For more information go to http://tinyurl.com/a6atybq.    
APPLICATION SUBTYPE: The specific work type being permitted as applicable. 
STATUS: The current status of the permit (e.g. Open, Closed, Stop Work, etc.).
ISSUE/ENTRY DATE: For historic DOE records, this date is the issue date of the permit. For CDPH records, this is either the date the permit was issued, or the date the permit application was entered into the database. 
EXPIRATION DATE: This is the permit expiration date. Not all permits may have an expiration date. Some permits are renewed annually or every three years. If the applicant does not renew, the permit Status will be set to ?Closed.?
COMMENT: Contains general comments and permit-specific information. 
DATA SOURCE: The city department that collected the data.

## Columns

```ls
| Included | Schema Type | Field Name           | Name                | Data Type     | Render Type   |
| ======== | =========== | ==================== | =================== | ============= | ============= |
| Yes      | series tag  | permit_number        | APPLICATION ID      | text          | text          |
| Yes      | series tag  | application_name     | APPLICATION NAME    | text          | text          |
| Yes      | series tag  | street_number        | STREET NUMBER FROM  | text          | number        |
| Yes      | series tag  | street_number_to     | STREET NUMBER TO    | text          | number        |
| Yes      | series tag  | direction            | DIRECTION           | text          | text          |
| Yes      | series tag  | street_name          | STREET NAME         | text          | text          |
| Yes      | series tag  | street_type          | STREET TYPE         | text          | text          |
| Yes      | series tag  | application_type     | APPLICATION TYPE    | text          | text          |
| Yes      | series tag  | application_sub_type | APPLICATION SUBTYPE | text          | text          |
| Yes      | series tag  | status               | STATUS              | text          | text          |
| Yes      | series tag  | applicant            | APPLICANT           | text          | text          |
| Yes      | time        | issue_date           | ISSUE OR ENTRY DATE | calendar_date | calendar_date |
| No       |             | entry_date           | EXPIRATION DATE     | calendar_date | calendar_date |
| Yes      | series tag  | comment              | COMMENT             | text          | text          |
| Yes      | series tag  | data_source          | DATA SOURCE         | text          | text          |
```

## Time Field

```ls
Value = issue_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = entry_date
```

## Data Commands

```ls
series e:ir7v-8mc8 d:2017-04-19T14:12:50.000Z t:application_type="APPLICATION TYPE" t:permit_number="PERMIT NUMBER" t:application_name="APPLICATION NAME" t:status="Permit STATUS" t:direction=DIRECTION t:data_source="DATA SOURCE" t:street_name="STREET NAME" t:applicant=APPLICANT t:application_sub_type="APPLICATION SUB-TYPE" t:comment=COMMENT t:street_type="STREET TYPE" m:row_number.ir7v-8mc8=1

series e:ir7v-8mc8 d:2002-07-02T00:00:00.000Z t:application_type="AIR POLLUTION CONTROL PERMIT" t:permit_number=DOEAIR10166 t:application_name="R. R. STREETS" t:status=CLOSED t:direction=S t:data_source="HISTORIC DEPT. OF ENVIRONMENT" t:street_name=NORMAL t:application_sub_type="EQUIPMENT INSTALLATION" t:street_number=500 t:comment="QTY: 1.0 COMBUSTION EMISSION UNIT/BOILER/ LATTNER MFG/MODEL:5 HP HE FLUERNS/ MAXIMUM OUTPUT:255,000 BTU" t:street_type=AVE m:row_number.ir7v-8mc8=2

series e:ir7v-8mc8 d:2002-07-23T00:00:00.000Z t:application_type="AIR POLLUTION CONTROL PERMIT" t:permit_number=DOEAIR10212 t:application_name="ASTOR HOUSE LLC" t:status=CLOSED t:direction=W t:data_source="HISTORIC DEPT. OF ENVIRONMENT" t:street_name=PRATT t:application_sub_type="EQUIPMENT INSTALLATION" t:street_number=1246 t:comment="QTY: 1.0 ARCHITECTURAL SURFACE CLEANING/GRINDING/ DUST SUPPRESSION METHOD:TARPAULIN/ WASTE DISPOSAL METHOD:DUMPSTER" t:street_type=AVE m:row_number.ir7v-8mc8=3
```

## Meta Commands

```ls
metric m:row_number.ir7v-8mc8 p:long l:"Row Number"

entity e:ir7v-8mc8 l:"CDPH Environmental Permits" t:attribution="Chicago Department of Public Health" t:url=https://data.cityofchicago.org/api/views/ir7v-8mc8

property e:ir7v-8mc8 t:meta.view v:id=ir7v-8mc8 v:category="Environment & Sustainable Development" v:attributionLink=http://www.cityofchicago.org/city/en/depts/cdph.html v:averageRating=0 v:name="CDPH Environmental Permits" v:attribution="Chicago Department of Public Health"

property e:ir7v-8mc8 t:meta.view.owner v:id=e3v2-km8a v:screenName=Renante v:displayName=Renante

property e:ir7v-8mc8 t:meta.view.tableauthor v:id=e3v2-km8a v:screenName=Renante v:roleName=publisher v:displayName=Renante
```

## Top Records

```ls
| permit_number | application_name                | street_number | street_number_to | direction | street_name | street_type | application_type             | application_sub_type   | status        | applicant | issue_date          | entry_date          | comment                                                                                                                                                                                                                                                                                                                                                                                                                                                | data_source                   | 
| ============= | =============================== | ============= | ================ | ========= | =========== | =========== | ============================ | ====================== | ============= | ========= | =================== | =================== | ====================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ============================= | 
| PERMIT NUMBER | APPLICATION NAME                |               |                  | DIRECTION | STREET NAME | STREET TYPE | APPLICATION TYPE             | APPLICATION SUB-TYPE   | Permit STATUS | APPLICANT |                     |                     | COMMENT                                                                                                                                                                                                                                                                                                                                                                                                                                                | DATA SOURCE                   | 
| DOEAIR10166   | R. R. STREETS                   | 500           |                  | S         | NORMAL      | AVE         | AIR POLLUTION CONTROL PERMIT | EQUIPMENT INSTALLATION | CLOSED        |           | 2002-07-02T00:00:00 | 2002-12-29T00:00:00 | QTY: 1.0 COMBUSTION EMISSION UNIT/BOILER/ LATTNER MFG/MODEL:5 HP HE FLUERNS/ MAXIMUM OUTPUT:255,000 BTU                                                                                                                                                                                                                                                                                                                                                | HISTORIC DEPT. OF ENVIRONMENT | 
| DOEAIR10212   | ASTOR HOUSE LLC                 | 1246          |                  | W         | PRATT       | AVE         | AIR POLLUTION CONTROL PERMIT | EQUIPMENT INSTALLATION | CLOSED        |           | 2002-07-23T00:00:00 | 2003-01-19T00:00:00 | QTY: 1.0 ARCHITECTURAL SURFACE CLEANING/GRINDING/ DUST SUPPRESSION METHOD:TARPAULIN/ WASTE DISPOSAL METHOD:DUMPSTER                                                                                                                                                                                                                                                                                                                                    | HISTORIC DEPT. OF ENVIRONMENT | 
| DOEAIR10291   | DOWY'S MOHL CO                  | 325           |                  | W         | FULLERTON   | AVE         | AIR POLLUTION CONTROL PERMIT | EQUIPMENT INSTALLATION | CLOSED        |           | 2002-08-13T00:00:00 | 2003-02-09T00:00:00 | QTY: 2.0 COMBUSTION EMISSION UNIT/BOILER/ WEBSTER/MODEL JB-2/ MAXIMUM OUTPUT:2,650,000 BTU                                                                                                                                                                                                                                                                                                                                                             | HISTORIC DEPT. OF ENVIRONMENT | 
| DOEAIR10592   | 399 CORPORATION                 | 399           |                  | W         | FULLERTON   | AVE         | AIR POLLUTION CONTROL PERMIT | EQUIPMENT INSTALLATION | CLOSED        |           | 2002-11-18T00:00:00 | 2003-05-17T00:00:00 | QTY: 1.0 ARCHITECTURAL SURFACE CLEANING/GRINDING/ DUST SUPPRESSION METHOD:TARPAULIN/ WASTE DISPOSAL METHOD:DUMPSTER                                                                                                                                                                                                                                                                                                                                    | HISTORIC DEPT. OF ENVIRONMENT | 
| DOEAIR10616   | LAKEWOOD ENGINEERING & MFG. CO. | 501           |                  | N         | SACRAMENTO  | AVE         | AIR POLLUTION CONTROL PERMIT | EQUIPMENT INSTALLATION | CLOSED        |           | 2002-11-15T00:00:00 | 2003-05-14T00:00:00 | QTY: 1.0 PROCESS EQUIPMENT/VERTICAL MACHINE CENTER/ OKK MODEL VMS-11/DIMENSIONS 8.1'X9.6'X9.1' ,QTY: 1.0 PROCESS AREA/SHRINK TUNNEL/ MODEL:SW40A1ST 1840 DIMENSIONS:4'W X 20'L X 6' H                                                                                                                                                                                                                                                                  | HISTORIC DEPT. OF ENVIRONMENT | 
| DOEAIR10692   | RICHARD FACSTEIN                | 1900          |                  | W         | PRATT       | AVE         | AIR POLLUTION CONTROL PERMIT | EQUIPMENT INSTALLATION | CLOSED        |           | 2002-12-05T00:00:00 | 2003-06-03T00:00:00 | QTY: 1.0 ARCHITECTURAL SURFACE CLEANING/CHEMICAL WASH/ WASH WITH SOAP AND WATER/ OVER SPRAY SUPPRESSION :TARPAULIN                                                                                                                                                                                                                                                                                                                                     | HISTORIC DEPT. OF ENVIRONMENT | 
| DOEAIR10710   | CASTEN BODY SHOP INC.           | 1130          |                  | W         | DIVERSEY    | AVE         | AIR POLLUTION CONTROL PERMIT | EQUIPMENT INSTALLATION | CLOSED        |           | 2002-12-10T00:00:00 | 2003-06-08T00:00:00 | QTY: 1.0 PROCESS AREA:PREP AREA/ DIMENSIONS:25'X14'X9' ,QTY: 1.0 PROCESS AREA:MIXING AREA/ DIMENSIONS:16'X7'X7'                                                                                                                                                                                                                                                                                                                                        | HISTORIC DEPT. OF ENVIRONMENT | 
| DOEAIR10775   | LULA CAFE                       | 2537          |                  | N         | KEDZIE      | AVE         | AIR POLLUTION CONTROL PERMIT | EQUIPMENT INSTALLATION | CLOSED        |           | 2003-01-07T00:00:00 | 2003-07-06T00:00:00 | QTY: 1.0 FOOD PREPARATION UNIT/HOOD/ MODEL:GREENTECK/DIMENSIONS:3'6"X10'6" ,QTY: 1.0 COMBUSTION EMISSION UNIT/FURNACE/ AOSHITA/MODEL:BTH-150CYLE ,QTY: 1.0 FOOD PREPARATION UNIT/EXHAUST/ MODEL:GREENHECK # CUBE-180HP.15/ B VENT/DIMENSIONS:6"X14",QTY: 1.0 COMBUSTION EMISSION UNIT/BOILER/ REZNOR/MODEL:SCE 250/ MAXIMUM OUTPUT:200,000 BTU,QTY: 1.0 COMBUSTION EMISSION UNIT/WARM AIR FURNACE/ CARRIER/MODEL:58MCA04008/ MAXIMUM OUTPUT:37,000 BTU | HISTORIC DEPT. OF ENVIRONMENT | 
| DOEAIR10912   | WILLIAM COVACI                  | 1528          |                  | W         | PRATT       | AVE         | AIR POLLUTION CONTROL PERMIT | EQUIPMENT INSTALLATION | CLOSED        |           | 2003-03-13T00:00:00 | 2003-09-09T00:00:00 | QTY: 1.0 COMBUSTION EMISSION UNIT/BOILER/ WEIL MC LAIN/MODEL:6.88/ MAXIMUM OUTPUT: 1,026,000 BTU                                                                                                                                                                                                                                                                                                                                                       | HISTORIC DEPT. OF ENVIRONMENT | 
```