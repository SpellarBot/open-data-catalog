# Facilities Licensed by the Department of Motor Vehicles (DMV)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/facilities-licensed-by-the-department-of-motor-vehicles-dmv) |
| Metadata | [Link](https://data.ny.gov/api/views/nhjr-rpi2) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/nhjr-rpi2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/nhjr-rpi2/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | nhjr-rpi2 |
| Name | Facilities Licensed by the Department of Motor Vehicles (DMV) |
| Attribution | NYS DMV |
| Category | Transportation |
| Tags | inspection, repair, station, dealers, automobile, dismantler, boat, snowmobile, new, used, car, yacht, atv, scrap, salvage, wholesale |
| Created | 2013-05-14T19:04:14Z |
| Publication Date | 2016-12-09T16:24:15Z |

## Description

Data set containing information on the facilities licensed by DMV in accordance with Vehicle and Traffic Law.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                   | Data Type     | Render Type   |
| ======== | ============== | ======================= | ====================== | ============= | ============= |
| Yes      | numeric metric | facility                | Facility #             | number        | number        |
| Yes      | series tag     | facility_name           | Facility Name          | text          | text          |
| Yes      | series tag     | facility_name_overflow  | Facility Name Overflow | text          | text          |
| Yes      | series tag     | facility_street         | Facility Street        | text          | text          |
| Yes      | series tag     | facility_city           | Facility City          | text          | text          |
| Yes      | series tag     | facility_state          | Facility State         | text          | text          |
| Yes      | series tag     | facility_zip_code       | Facility Zip Code      | text          | text          |
| Yes      | series tag     | facility_county         | Facility County        | text          | text          |
| Yes      | series tag     | owner_name              | Owner Name             | text          | text          |
| Yes      | series tag     | owner_name_overflow     | Owner Name Overflow    | text          | text          |
| Yes      | series tag     | business_type           | Business Type          | text          | text          |
| Yes      | time           | origional_issuance_date | Original Issuance Date | calendar_date | calendar_date |
| No       |                | last_renewal_date       | Last Renewal Date      | calendar_date | calendar_date |
| No       |                | expiration_date         | Expiration Date        | text          | text          |
```

## Time Field

```ls
Value = origional_issuance_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = last_renewal_date,expiration_date
```

## Data Commands

```ls
series e:nhjr-rpi2 d:1980-10-10T00:00:00.000Z t:facility_city="PORT CRANE" t:facility_name="A 1 AUTOMOTIVE" t:owner_name="ALBERT F SPRINGSTEAD" t:facility_street="512 RT 7" t:facility_zip_code=13833 t:facility_county=BROO t:owner_name_overflow=ETAL t:business_type=RS t:facility_state=NY m:facility=4040558

series e:nhjr-rpi2 d:1980-12-30T00:00:00.000Z t:facility_city="PORT CRANE" t:facility_name="A 1 AUTOMOTIVE" t:owner_name="ALBERT F SPRINGSTEAD" t:facility_street="512 RT 7" t:facility_zip_code=13833 t:facility_county=BROO t:owner_name_overflow=ETAL t:business_type=TRS t:facility_state=NY m:facility=4040558

series e:nhjr-rpi2 d:2013-03-05T00:00:00.000Z t:facility_city="LONG ISLND CTY" t:facility_name="A 1 COLLISION INC" t:owner_name="SURJIT SINGH" t:facility_street="22-07 37TH AVENUE" t:facility_zip_code=11101 t:facility_county=QUEE t:business_type=RS t:facility_state=NY m:facility=7115599
```

## Meta Commands

```ls
metric m:facility p:integer l:"Facility #" d:"The unique numeric identifier assigned to a facility by DMV." t:dataTypeName=number

entity e:nhjr-rpi2 l:"Facilities Licensed by the Department of Motor Vehicles (DMV)" t:attribution="NYS DMV" t:url=https://data.ny.gov/api/views/nhjr-rpi2

property e:nhjr-rpi2 t:meta.view v:id=nhjr-rpi2 v:category=Transportation v:attributionLink=http://www.dmv.ny.gov/repairshop.htm v:averageRating=0 v:name="Facilities Licensed by the Department of Motor Vehicles (DMV)" v:attribution="NYS DMV"

property e:nhjr-rpi2 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:nhjr-rpi2 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:nhjr-rpi2 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| facility | facility_name       | facility_name_overflow | facility_street    | facility_city  | facility_state | facility_zip_code | facility_county | owner_name           | owner_name_overflow | business_type | origional_issuance_date | last_renewal_date   | expiration_date | 
| ======== | =================== | ====================== | ================== | ============== | ============== | ================= | =============== | ==================== | =================== | ============= | ======================= | =================== | =============== | 
| 4040558  | A 1 AUTOMOTIVE      |                        | 512 RT 7           | PORT CRANE     | NY             | 13833             | BROO            | ALBERT F SPRINGSTEAD | ETAL                | RS            | 1980-10-10T00:00:00     | 2016-10-05T00:00:00 | 10/31/2018      | 
| 4040558  | A 1 AUTOMOTIVE      |                        | 512 RT 7           | PORT CRANE     | NY             | 13833             | BROO            | ALBERT F SPRINGSTEAD | ETAL                | TRS           | 1980-12-30T00:00:00     | 2014-10-02T00:00:00 | 10/31/2016      | 
| 7115599  | A 1 COLLISION INC   |                        | 22-07 37TH AVENUE  | LONG ISLND CTY | NY             | 11101             | QUEE            | SURJIT SINGH         |                     | RS            | 2013-03-05T00:00:00     | 2015-03-11T00:00:00 | 02/28/2017      | 
| 7091751  | A 1 COLLISION       |                        | 3370 RT 112        | MEDFORD        | NY             | 11763             | SUFF            | WRECKERS SALES &     | SERVICE INC         | RSB           | 2002-02-21T00:00:00     | 2015-11-24T00:00:00 | 01/31/2018      | 
| 7095379  | A & D PRESTIGE AUTO | REPAIR INC             | 53-11 VAN DAM ST   | LONGISLANDCITY | NY             | 11101             | QUEE            | OLEG NIYAZOV         |                     | RS            | 2003-07-30T00:00:00     | 2009-06-16T00:00:00 | 06/30/2011      | 
| 7083645  | A 1 INTERNATIONAL   | TRANSMISSIONS INC      | 122-26 FARMERS BL  | SPRNGFLD GDNS  | NY             | 11413             | QUEE            | ANTHONY ELLIS        |                     | RS            | 1999-01-07T00:00:00     | 2014-11-21T00:00:00 | 12/31/2016      | 
| 7106510  | A & J 2 AUTO REPAIR | INC                    | 212-37 99TH AVENUE | QUEENS VILLAGE | NY             | 11429             | QUEE            | YEREMY DENIS         |                     | RS            | 2008-07-11T00:00:00     | 2010-05-11T00:00:00 | 06/30/2012      | 
| 7106510  | A & J 2 AUTO REPAIR | INC                    | 212-37 99TH AVENUE | QUEENS VILLAGE | NY             | 11429             | QUEE            | YEREMY DENIS         |                     | ATV           | 2010-09-17T00:00:00     |                     | 06/30/2012      | 
| 7026002  | A AUTOMOTIVE        |                        | POB 167 RT 430     | DEWITTVILLE    | NY             | 14728             | CHAU            | ROXANNA MAYTUM       |                     | DLU           | 1984-09-05T00:00:00     | 2014-10-06T00:00:00 | 09/30/2016      | 
| 7043099  | A EUROAMERICAN AUTO | REPAIRS INC            | 30-59 41ST STREET  | LONGISLANDCITY | NY             | 11103             | QUEE            | LAZAROS SEMERTSIDES  |                     | RS            | 1988-04-07T00:00:00     | 2016-01-29T00:00:00 | 03/31/2018      | 
```