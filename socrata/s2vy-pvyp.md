# Oregon Hospitals 2008-09-20

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-hospitals-2008-09-20-ad778) |
| Metadata | [Link](https://data.oregon.gov/api/views/s2vy-pvyp) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/s2vy-pvyp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/s2vy-pvyp/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | s2vy-pvyp |
| Name | Oregon Hospitals 2008-09-20 |
| Attribution | TechniGraphics, Inc. |
| Tags | oregon, hospitals, preparedness, emergency, facilities, health, healthcare, medical, hospital, diagnostic, care, surgical, veterans, childrens, specialty, public, psychiatric, substance |
| Created | 2010-11-12T21:29:44Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

Hospitals in Oregon
The term "hospital" ... means an institution which-
(1) is primarily engaged in providing, by or under the supervision of physicians, to inpatients

	(A) diagnostic services and therapeutic services for medical diagnosis, treatment, and care of injured, disabled, or sick persons, or 
	(B) rehabilitation services for the rehabilitation of injured, disabled, or sick persons; 

(...)
(5) provides 24-hour nursing service rendered or supervised by a registered professional nurse, and has a licensed practical nurse or registered professional nurse on duty at all times; ...
(...)
(7) in the case of an institution in any State in which State or applicable local law provides for the licensing of hospitals,

	(A) is licensed pursuant to such law or 
	(B) is approved, by the agency of such State or locality responsible for licensing hospitals, as meeting the standards established for such licensing; 

(Excerpt from Title XVIII of the Social Security Act [42 U.S.C. ? 1395x(e)], <http://www4.law.cornell.edu/uscode/html/uscode42/usc_sec_42_00001395---x000-.html>)
Included in this dataset are General Medical and Surgical Hospitals, Psychiatric and Substance Abuse Hospitals, and Specialty Hospitals (e.g., Children's Hospitals, Cancer Hospitals, Maternity Hospitals, Rehabilitation Hospitals, etc.).
TGS has made a concerted effort to include all general medical/surgical hospitals in Oregon. Other types of hospitals are included if they were represented in datasets sent by the state. Therefore, not all of the specialty hospitals in Oregon are represented in this dataset.
Hospitals operated by the Veterans Administration (VA) are included, even if the state they are located in does not license VA Hospitals.
Nursing homes and Urgent Care facilities are excluded because they are included in a separate dataset. Locations that are administrative offices only are excluded from the dataset.
Records with "-DOD" appended to the end of the [NAME] value are located on a military base, as defined by the Defense Installation Spatial Data Infrastructure (DISDI) military installations and military range boundaries.
Text fields in this dataset have been set to all upper case to facilitate consistent database engine search results.
All diacritics (e.g., the German umlaut or the Spanish tilde) have been replaced with their closest equivalent English character to facilitate use with database systems that may not support diacritics.
The currentness of this dataset is indicated by the [CONTDATE] field. Based upon this field, the oldest record dates from 08/23/2006 and the newest record dates from 05/28/2008 

For full metadata record, please refer to the Oregon Geospatial Library: http://gis.oregon.gov/DAS/EISPD/GEO/sdlibrary.shtml

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | name       | Name       | text      | text        |
| Yes      | series tag     | phone      | Phone      | phone     | phone       |
| No       |                | address    | Address    | text      | text        |
| No       |                | address2   | Address2   | text      | text        |
| Yes      | series tag     | city       | City       | text      | text        |
| Yes      | series tag     | state      | State      | text      | text        |
| Yes      | series tag     | zip        | Zip        | text      | text        |
| Yes      | series tag     | zip_4      | Zip-4      | text      | number      |
| Yes      | series tag     | county     | County     | text      | text        |
| Yes      | series tag     | directions | Directions | text      | text        |
| Yes      | series tag     | naicsdescr | NAICSDESCR | text      | text        |
| No       |                | x          | X          | number    | number      |
| No       |                | y          | Y          | number    | number      |
| Yes      | numeric metric | numbeds    | NUMBEDS    | number    | number      |
```

## Time Field

```ls
Value = 2008
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address,address2,x,y
```

## Data Commands

```ls
series e:s2vy-pvyp d:2008-01-01T00:00:00.000Z t:directions="LOCATED ON THE NORTHEAST CORNER OF 13TH ST AND MAY ST" t:zip=97031 t:phone_number=541-386-3911 t:naicsdescr="HOSPITALS, GENERAL MEDICAL AND SURGICAL" t:county="HOOD RIVER" t:zip_4=1204 t:name="PROVIDENCE HOOD RIVER MEMORIAL HOSPITAL" t:state=OR t:city="HOOD RIVER" m:numbeds=0

series e:s2vy-pvyp d:2008-01-01T00:00:00.000Z t:directions="LOC ON THE NW CORNER OF NE 49TH AVE AND NE GLISAN ST." t:zip=97213 t:phone_number=503-215-1111 t:naicsdescr="HOSPITALS, GENERAL MEDICAL AND SURGICAL" t:county=MULTNOMAH t:zip_4=2933 t:name="PROVIDENCE PORTLAND MEDICAL CENTER" t:state=OR t:city=PORTLAND m:numbeds=0

series e:s2vy-pvyp d:2008-01-01T00:00:00.000Z t:directions="ON THE S SIDE OF SE SUNNYSIDE RD BETWEEN SE STEVENS RD AND SE 40TH CT" t:zip=97015 t:phone_number=503-652-2880 t:naicsdescr="HOSPITALS, GENERAL MEDICAL AND SURGICAL" t:county=CLACKAMAS t:zip_4=9764 t:name="KAISER SUNNYSIDE MEDICAL CENTER" t:state=OR t:city=CLACKAMAS m:numbeds=0
```

## Meta Commands

```ls
metric m:numbeds p:float l:NUMBEDS t:dataTypeName=number

entity e:s2vy-pvyp l:"Oregon Hospitals 2008-09-20" t:attribution="TechniGraphics, Inc." t:url=https://data.oregon.gov/api/views/s2vy-pvyp

property e:s2vy-pvyp t:meta.view v:id=s2vy-pvyp v:attributionLink=http://gis.oregon.gov/DAS/EISPD/GEO/sdlibrary.shtml v:averageRating=0 v:name="Oregon Hospitals 2008-09-20" v:attribution="TechniGraphics, Inc."

property e:s2vy-pvyp t:meta.view.owner v:id=n7yg-3wp3 v:profileImageUrlMedium=/api/users/n7yg-3wp3/profile_images/THUMB v:profileImageUrlLarge=/api/users/n7yg-3wp3/profile_images/LARGE v:screenName="Erik Endrulat" v:profileImageUrlSmall=/api/users/n7yg-3wp3/profile_images/TINY v:displayName="Erik Endrulat"

property e:s2vy-pvyp t:meta.view.tableauthor v:id=n7yg-3wp3 v:profileImageUrlMedium=/api/users/n7yg-3wp3/profile_images/THUMB v:profileImageUrlLarge=/api/users/n7yg-3wp3/profile_images/LARGE v:screenName="Erik Endrulat" v:profileImageUrlSmall=/api/users/n7yg-3wp3/profile_images/TINY v:displayName="Erik Endrulat"
```

## Top Records

```ls
| name                                      | phone                | address                        | address2 | city       | state | zip   | zip_4 | county     | directions                                                                           | naicsdescr                              | x            | y          | numbeds | 
| ========================================= | ==================== | ============================== | ======== | ========== | ===== | ===== | ===== | ========== | ==================================================================================== | ======================================= | ============ | ========== | ======= | 
| PROVIDENCE HOOD RIVER MEMORIAL HOSPITAL   | [541-386-3911, null] | 811 13TH STREET                |          | HOOD RIVER | OR    | 97031 | 1204  | HOOD RIVER | LOCATED ON THE NORTHEAST CORNER OF 13TH ST AND MAY ST                                | HOSPITALS, GENERAL MEDICAL AND SURGICAL | -121.5243182 | 45.7048557 | 0.0     | 
| PROVIDENCE PORTLAND MEDICAL CENTER        | [503-215-1111, null] | 4805 NORTHEAST GLISAN STREET   |          | PORTLAND   | OR    | 97213 | 2933  | MULTNOMAH  | LOC ON THE NW CORNER OF NE 49TH AVE AND NE GLISAN ST.                                | HOSPITALS, GENERAL MEDICAL AND SURGICAL | -122.6137641 | 45.52742   | 0.0     | 
| KAISER SUNNYSIDE MEDICAL CENTER           | [503-652-2880, null] | 10180 SOUTHEAST SUNNYSIDE ROAD |          | CLACKAMAS  | OR    | 97015 | 9764  | CLACKAMAS  | ON THE S SIDE OF SE SUNNYSIDE RD BETWEEN SE STEVENS RD AND SE 40TH CT                | HOSPITALS, GENERAL MEDICAL AND SURGICAL | -122.5606    | 45.4312489 | 0.0     | 
| LEGACY MOUNT HOOD MEDICAL CENTER          | [503-674-1122, null] | 24800 SOUTHEAST STARK STREET   |          | GRESHAM    | OR    | 97030 | 3378  | MULTNOMAH  | LOC ON THE SW CORNER OF SW SUNDIAL AVE AND SE STARK ST ON THE S SIDE OF SE STARK ST. | HOSPITALS, GENERAL MEDICAL AND SURGICAL | -122.4070368 | 45.5166262 | 0.0     | 
| LEGACY MERIDIAN PARK HOSPITAL             | [503-692-1212, null] | 19300 SOUTHWEST 65TH AVENUE    |          | TUALATIN   | OR    | 97062 | 7706  | CLACKAMAS  | LOC LESS THAN .1 MI N OF SW BORLAND RD AND SW 65TH AVE ON THE E SIDE OF SW 65TH AVE. | HOSPITALS, GENERAL MEDICAL AND SURGICAL | -122.740804  | 45.3786716 | 0.0     | 
| PROVIDENCE SAINT VINCENT HOSPITAL         | [503-216-1234, null] | 9205 SOUTHWEST BARNES ROAD     |          | PORTLAND   | OR    | 97225 | 6603  | WASHINGTON | LOCATED ON THE NORTH SIDE OF SW BARNES RD APPROX 0.19 MILES EAST OF SW BALTIC AVE    | HOSPITALS, GENERAL MEDICAL AND SURGICAL | -122.7718284 | 45.5106612 | 0.0     | 
| LEGACY EMANUEL HOSPITAL AND HEALTH CENTER | [503-413-2200, null] | 2801 NORTH GANTENBEIN AVENUE   |          | PORTLAND   | OR    | 97227 | 1623  | MULTNOMAH  | LOC ON THE NE CORNER OF N GRAHAM ST AND N KERBY AVE.                                 | HOSPITALS, GENERAL MEDICAL AND SURGICAL | -122.6702704 | 45.5435674 | 0.0     | 
| GOOD SAMARITAN REGIONAL MEDICAL CENTER    | [541-768-5111, null] | 3600 NORTHWEST SAMARITAN DRIVE |          | CORVALLIS  | OR    | 97330 | 3737  | BENTON     | FROM NW ELKS DR, TRAVEL N ON NW SAMARITAN DR .30 MILES ON W SIDE OF NW SAMARITAN DR  | HOSPITALS, GENERAL MEDICAL AND SURGICAL | -123.2523328 | 44.6034337 | 0.0     | 
| SAINT CHARLES MEDICAL CENTER              | [541-382-4321, null] | 2500 NORTHEAST NEFF ROAD       |          | BEND       | OR    | 97701 | 6015  | DESCHUTES  | NW CORNER OF THE INTERSECTION OF NE MEDICAL CENTER DR AND NE NEFF RD                 | HOSPITALS, GENERAL MEDICAL AND SURGICAL | -121.2693136 | 44.067636  | 0.0     | 
| MID-COLUMBIA MEDICAL CENTER               | [541-296-1111, null] | 1700 EAST 19TH STREET          |          | THE DALLES | OR    | 97058 | 3317  | WASCO      | ON THE SOUTH SIDE OF E 19TH ST, BETWEEN NEDADA ST & OREGON AVE.                      | HOSPITALS, GENERAL MEDICAL AND SURGICAL | -121.1644619 | 45.5873161 | 0.0     | 
```