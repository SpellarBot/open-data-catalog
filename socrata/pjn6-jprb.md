# Emergency Operation Centers 2007-07-26

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/emergency-operation-centers-2007-07-26-84d72) |
| Metadata | [Link](https://data.oregon.gov/api/views/pjn6-jprb) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/pjn6-jprb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/pjn6-jprb/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | pjn6-jprb |
| Name | Emergency Operation Centers 2007-07-26 |
| Attribution | Techni Graphic Systems, Inc. |
| Tags | emergency, eoc, centers, preparedness, gis, facilities, oregon |
| Created | 2010-11-12T21:00:38Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

Emergency Operations Centers (EOC) in Oregon

"The physical location at which the coordination of information and resources to support domestic incident management activities normally takes place. An EOC may be a temporary facility or may be located in
a more central or permanently established facility, perhaps at a higher level of organization within a jurisdiction. EOCs may be organized by major functional disciplines (e.g., fire, law enforcement, and medical services), by jurisdiction (e.g., Federal, State, regional, county, city, tribal), or some combination thereof."

(Excerpted from the National Incident Management System)

In instances where TGS could not verify the location of an Emergency Operations Center due to non-cooperation of the entity and to the exhaustion of all possible alternative resources, its location was depicted at the center of the service area. 

In cases where an Emergency Operations Center has a mobile unit, TGS captured the location of the mobile unit as a separate record.  This record represents where the mobile unit is stored.  

Text fields in this dataset have been set to all upper case to facilitate consistent database engine search results.

All diacritics (e.g., the German umlaut or the Spanish tilde) have been replaced with their closest equivalent English character to facilitate use with database systems that may not support diacritics.  

The currentness of this dataset is indicated by the [CONTDATE] attribute. Based upon this attribute, the oldest record dates from 03/27/2007 and the newest record dates from 04/23/2007.

One data point was removed at the request of the City of Portland 11/24/08.

This is a tabular representation of a geospatial dataset available from the Oregon Geospatial Enterprise Office: http://gis.oregon.gov/DAS/EISPD/GEO/sdlibrary.shtml.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag     | name                    | Name                    | text          | text          |
| Yes      | series tag     | phone_number            | Phone Number            | text          | text          |
| Yes      | series tag     | fax                     | FAX                     | text          | text          |
| No       |                | address1                | Address1                | text          | text          |
| No       |                | address2                | Address2                | text          | text          |
| Yes      | series tag     | city                    | City                    | text          | text          |
| Yes      | series tag     | state                   | State                   | text          | text          |
| Yes      | series tag     | zip_code                | Zip code                | text          | number        |
| Yes      | series tag     | zip_4                   | Zip+4                   | text          | text          |
| Yes      | series tag     | county                  | County                  | text          | text          |
| Yes      | series tag     | fips                    | FIPS                    | text          | number        |
| Yes      | series tag     | directions              | Directions              | text          | text          |
| Yes      | time           | geodate                 | GEODATE                 | calendar_date | calendar_date |
| Yes      | series tag     | geohow                  | GEOHOW                  | text          | text          |
| Yes      | series tag     | naicscode               | NAICSCODE               | text          | number        |
| Yes      | series tag     | naicsdescr              | NAICSDESCR              | text          | text          |
| Yes      | series tag     | geolinkid               | GEOLINKID               | text          | number        |
| No       |                | x                       | X                       | number        | number        |
| No       |                | y                       | Y                       | number        | number        |
| Yes      | series tag     | email                   | Email                   | email         | email         |
| Yes      | series tag     | contact_name            | Contact name            | text          | text          |
| Yes      | series tag     | contact_title           | Contact Title           | text          | text          |
| Yes      | series tag     | contact_phone           | Contact Phone           | text          | text          |
| Yes      | numeric metric | contact_phone_extension | Contact Phone Extension | number        | number        |
```

## Time Field

```ls
Value = geodate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address1,address2,x,y
```

## Data Commands

```ls
series e:pjn6-jprb d:2007-03-19T00:00:00.000Z t:fax=503-266-9316 t:phone_number=503-266-4024 t:zip_code=97013 t:naicsdescr="EMERGENCY PLANNING AND MANAGEMENT OFFICES, GOVERNMENT" t:naicscode=922190 t:state=OR t:contact_phone=503-266-4024 t:contact_title="POLICE CHIEF" t:geohow=AUTO t:city=CANBY t:county=CLACKAMAS t:email=KROEPLING@CI.CANBY.OR.US t:zip_4=97013-3730 t:name=CLACKAMAS-CANBY t:contact_name="GREG A. KROEPLIN" t:fips=41005 t:geolinkid=21346947 m:contact_phone_extension=222

series e:pjn6-jprb d:2007-03-19T00:00:00.000Z t:fax=503-463-7798 t:phone_number=503-390-3713 t:zip_code=97303 t:naicsdescr="EMERGENCY PLANNING AND MANAGEMENT OFFICES, GOVERNMENT" t:naicscode=922190 t:state=OR t:contact_phone=503-390-3713 t:contact_title="(POLICE CAPT.) EMERGENCY MANAGER" t:geohow=AUTO t:city=KEIZER t:county=MARION t:email=EM@KEIZER.ORG t:zip_4=97303-3716 t:name="KEIZER EMERGENCY SERVICES" t:contact_name="JOHN O. TEAGUE" t:fips=41047 t:geolinkid=21369230 m:contact_phone_extension=3503

series e:pjn6-jprb d:2007-03-29T00:00:00.000Z t:fax=541-396-5932 t:phone_number=541-396-3121 t:zip_code=97423 t:naicsdescr="EMERGENCY PLANNING AND MANAGEMENT OFFICES, GOVERNMENT" t:naicscode=922190 t:state=OR t:contact_phone=541-396-3121 t:contact_title="PROGRAM MANAGER" t:geohow=MANUAL t:city=COQUILLE t:directions="E SIDE OF N BAXTER ST BETWEEN E 2ND ST AND E 3RD ST" t:email=GHALES@CO.COOS.OR.US t:county=COOS t:zip_4=97423-1875 t:name="COOS COUNTY EMERGENCY MANAGEMENT" t:contact_name="GLENDA HALES" t:fips=41011 t:geolinkid=86785079 m:contact_phone_extension=312
```

## Meta Commands

```ls
metric m:contact_phone_extension p:integer l:"Contact Phone Extension" t:dataTypeName=number

entity e:pjn6-jprb l:"Emergency Operation Centers 2007-07-26" t:attribution="Techni Graphic Systems, Inc." t:url=https://data.oregon.gov/api/views/pjn6-jprb

property e:pjn6-jprb t:meta.view v:id=pjn6-jprb v:attributionLink=http://gis.oregon.gov/DAS/EISPD/GEO/sdlibrary.shtml v:averageRating=0 v:name="Emergency Operation Centers 2007-07-26" v:attribution="Techni Graphic Systems, Inc."

property e:pjn6-jprb t:meta.view.owner v:id=n7yg-3wp3 v:profileImageUrlMedium=/api/users/n7yg-3wp3/profile_images/THUMB v:profileImageUrlLarge=/api/users/n7yg-3wp3/profile_images/LARGE v:screenName="Erik Endrulat" v:profileImageUrlSmall=/api/users/n7yg-3wp3/profile_images/TINY v:displayName="Erik Endrulat"

property e:pjn6-jprb t:meta.view.tableauthor v:id=n7yg-3wp3 v:profileImageUrlMedium=/api/users/n7yg-3wp3/profile_images/THUMB v:profileImageUrlLarge=/api/users/n7yg-3wp3/profile_images/LARGE v:screenName="Erik Endrulat" v:profileImageUrlSmall=/api/users/n7yg-3wp3/profile_images/TINY v:displayName="Erik Endrulat"
```

## Top Records

```ls
| name                                           | phone_number | fax          | address1            | address2 | city        | state | zip_code | zip_4      | county     | fips  | directions                                      | geodate             | geohow | naicscode | naicsdescr                                            | geolinkid | x            | y          | email                              | contact_name          | contact_title             | contact_phone | contact_phone_extension | 
| ============================================== | ============ | ============ | =================== | ======== | =========== | ===== | ======== | ========== | ========== | ===== | =============================================== | =================== | ====== | ========= | ===================================================== | ========= | ============ | ========== | ================================== | ===================== | ========================= | ============= | ======================= | 
| SHERMAN COUNTY EMERGENCY SERVICES              | 541-565-3100 | 541-565-3024 | 309 DEWEY STREET    |          | MORO        | OR    | 97039    | 97039-     | SHERMAN    | 41055 | SE SIDE OF DEWEY ST BETWEEN 1ST ST AND MOORE ST | 2007-04-23T00:00:00 | MANUAL | 922190    | EMERGENCY PLANNING AND MANAGEMENT OFFICES, GOVERNMENT | 86450434  | -120.7320079 | 45.4815371 | EMERGENCYSERV@EARTHLINK.NET        | SHAWN PAYNE           | DIRECTOR                  | 541-565-3100  |                         | 
| CROOK COUNTY EMERGENCY MANAGEMENT              | 541-416-3880 | 541-416-0353 | 308 NE 2ND STREET   |          | PRINEVILLE  | OR    | 97754    | 97754-1912 | CROOK      | 41013 |                                                 | 2007-03-19T00:00:00 | AUTO   | 922190    | EMERGENCY PLANNING AND MANAGEMENT OFFICES, GOVERNMENT | 86633192  | -120.8442024 | 44.3017303 | CCSO.SGTWRIGHT@PSNET.US            | SGT. RUSS WRIGHT      | COORDINATOR               | 541-416-3880  |                         | 
| STAYTON EMERGENCY SERVICES                     | 503-769-3423 | 503-769-4797 | 386 N 3RD AVE       |          | STAYTON     | OR    | 97383    | 97383-1726 | MARION     | 41047 |                                                 | 2007-03-19T00:00:00 | AUTO   | 922190    | EMERGENCY PLANNING AND MANAGEMENT OFFICES, GOVERNMENT | 86548902  | -122.7918532 | 44.7975984 | DEUBANK@STAYTONPD.ORG              | DON EUBANK            | POLICE CHIEF              | 503-769-3423  |                         | 
| BENTON COUNTY EMERGENCY MANAGEMENT             | 541-766-6864 | 541-766-6052 | 180 NW 5TH ST       |          | CORVALLIS   | OR    | 97330    | 97330-4703 | BENTON     | 41003 |                                                 | 2007-03-19T00:00:00 | AUTO   | 922190    | EMERGENCY PLANNING AND MANAGEMENT OFFICES, GOVERNMENT | 86591537  | -123.2630727 | 44.5656395 | MICHAEL.BAMBERGER@CO.BENTON.OR.US  | MIKE BAMBERGER        | EMERGENCY PROGRAM MANAGER | 541-766-6864  |                         | 
| CLACKAMAS COUNTY DEPT. OF EMERGENCY MANAGEMENT | 503-655-8371 | 503-655-8531 | 2200 KAEN RD        |          | OREGON CITY | OR    | 97045    | 97045-4048 | CLACKAMAS  | 41005 |                                                 | 2007-03-19T00:00:00 | AUTO   | 922190    | EMERGENCY PLANNING AND MANAGEMENT OFFICES, GOVERNMENT | 21325524  | -122.5990249 | 45.3307666 | DANAR@CO.CLACKAMAS.OR.US           | DANA ROBINSON         | DIRECTOR                  | 503-655-8371  |                         | 
| CLACKAMAS-CANBY                                | 503-266-4024 | 503-266-9316 | 122 N HOLLY ST      |          | CANBY       | OR    | 97013    | 97013-3730 | CLACKAMAS  | 41005 |                                                 | 2007-03-19T00:00:00 | AUTO   | 922190    | EMERGENCY PLANNING AND MANAGEMENT OFFICES, GOVERNMENT | 21346947  | -122.6937729 | 45.2629296 | KROEPLING@CI.CANBY.OR.US           | GREG A. KROEPLIN      | POLICE CHIEF              | 503-266-4024  | 222                     | 
| CLACKAMAS-GLADSTONE                            | 503-557-2765 | 503-650-8938 | 535 PORTLAND AVE    |          | GLADSTONE   | OR    | 97027    | 97027-2115 | CLACKAMAS  | 41005 |                                                 | 2007-03-19T00:00:00 | AUTO   | 922190    | EMERGENCY PLANNING AND MANAGEMENT OFFICES, GOVERNMENT | 21323524  | -122.5944082 | 45.3806903 | GRACE@CI.GLADSTONE.OR.US           | FRANK GRACE           | POLICE CHIEF              | 503-557-2765  |                         | 
| GILLIAM COUNTY EMERGENCY SERVICES              | 541-384-2851 | 541-384-2878 | 221 S OREGON STREET |          | CONDON      | OR    | 97823    | 97823-     | GILLIAM    | 41021 |                                                 | 2007-03-19T00:00:00 | AUTO   | 922190    | EMERGENCY PLANNING AND MANAGEMENT OFFICES, GOVERNMENT | 86481606  | -120.1862284 | 45.2357527 | CFITZSIM@NCESD.K12.OR.US           | CHRISTINA FITZSIMMONS | COORDINATOR               | 541-384-2851  |                         | 
| HARNEY COUNTY EMERGENCY SERVICES               | 541-573-5961 | 541-573-8383 | 485 N COURT STREET  |          | BURNS       | OR    | 97720    | 97720-1524 | HARNEY     | 41025 |                                                 | 2007-03-19T00:00:00 | AUTO   | 922190    | EMERGENCY PLANNING AND MANAGEMENT OFFICES, GOVERNMENT | 86727563  | -119.0571914 | 43.5895335 | HCEMA@CO.HARNEY.OR.US              | VACANT                | COORDINATOR               | 541-573-5961  |                         | 
| HOOD RIVER COUNTY EMERGENCY MANAGEMENT         | 541-386-1213 | 541-386-3141 | 309 STATE STREET    |          | HOOD RIVER  | OR    | 97031    | 97031-2037 | HOOD RIVER | 41027 |                                                 | 2007-03-19T00:00:00 | AUTO   | 922190    | EMERGENCY PLANNING AND MANAGEMENT OFFICES, GOVERNMENT | 119699873 | -121.513698  | 45.7078577 | KTESCH@SHERIFF.CO.HOOD-RIVER.OR.US | KARL TESCH            | DIRECTOR                  | 541-386-1213  |                         | 
```