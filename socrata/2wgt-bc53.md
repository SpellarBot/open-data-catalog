# Issued State Facility Air Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/issued-state-facility-air-permits) |
| Metadata | [Link](https://data.ny.gov/api/views/2wgt-bc53) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/2wgt-bc53/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/2wgt-bc53/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 2wgt-bc53 |
| Name | Issued State Facility Air Permits |
| Attribution | New York State Department of Environmental Conservation |
| Category | Energy & Environment |
| Tags | issued permit, emissions, air pollution, state facility |
| Created | 2014-06-30T20:08:13Z |
| Publication Date | 2016-01-08T21:57:52Z |

## Description

Owners or operators of emission sources that are subject to 6 NYCRR Subpart 201-5 must obtain a State facility permit.  

Draft permits are official versions of permits whose initial development is complete, public notice given, and made available for public review and comment.
  
These permits are prepared by the Division of Air Resources regional staff.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type     | Render Type   |
| ======== | =========== | ================== | ================== | ============= | ============= |
| Yes      | series tag  | facility_name      | FACILITY NAME      | text          | text          |
| Yes      | series tag  | permit_id          | PERMIT ID          | text          | text          |
| Yes      | series tag  | url_to_permit_text | URL TO PERMIT TEXT | url           | url           |
| Yes      | series tag  | facility_location  | FACILITY LOCATION  | text          | text          |
| Yes      | series tag  | facility_city      | FACILITY CITY      | text          | text          |
| Yes      | series tag  | facility_state     | FACILITY STATE     | text          | text          |
| Yes      | series tag  | facility_zip       | FACILITY ZIP       | text          | number        |
| Yes      | time        | issue_date         | ISSUE DATE         | calendar_date | calendar_date |
| No       |             | expire_date        | EXPIRE DATE        | calendar_date | calendar_date |
```

## Time Field

```ls
Value = issue_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = expire_date
```

## Data Commands

```ls
series e:2wgt-bc53 d:2006-07-18T00:00:00.000Z t:facility_city="ROCKVILLE CENTRE" t:permit_id=1-2820-00600/00004 t:url_to_permit_text=http://www.dec.ny.gov/dardata/boss/afs/permits/128200060000004.pdf t:facility_name="MERCY MEDICAL CENTER" t:facility_zip=11570 t:facility_location="1000 N VILLAGE AVE" t:facility_state=NY m:row_number.2wgt-bc53=1

series e:2wgt-bc53 d:2006-01-11T00:00:00.000Z t:facility_city=OCEANSIDE t:permit_id=1-2820-00796/00002 t:url_to_permit_text=http://www.dec.ny.gov/dardata/boss/afs/permits/128200079600002.pdf t:facility_name="SOUTH NASSAU COMMUNITIES HOSPITAL" t:facility_zip=11572 t:facility_location="1 HEALTHY WAY" t:facility_state=NY m:row_number.2wgt-bc53=2

series e:2wgt-bc53 d:2002-08-23T00:00:00.000Z t:facility_city="NORTH LAWRENCE" t:permit_id=1-2820-01873/00009 t:url_to_permit_text=http://www.dec.ny.gov/dardata/boss/afs/permits/128200187300009.pdf t:facility_name="RASON ASPHALT FACILITY" t:facility_zip=11559 t:facility_location="4 JOHNSON RD" t:facility_state=NY m:row_number.2wgt-bc53=3
```

## Meta Commands

```ls
metric m:row_number.2wgt-bc53 p:long l:"Row Number"

entity e:2wgt-bc53 l:"Issued State Facility Air Permits" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/2wgt-bc53

property e:2wgt-bc53 t:meta.view v:id=2wgt-bc53 v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/dardata/boss/afs/issued_asf_u.html v:averageRating=0 v:name="Issued State Facility Air Permits" v:attribution="New York State Department of Environmental Conservation"

property e:2wgt-bc53 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:2wgt-bc53 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| facility_name                                                  | permit_id          | url_to_permit_text                                                            | facility_location        | facility_city    | facility_state | facility_zip | issue_date          | expire_date         | 
| ============================================================== | ================== | ============================================================================= | ======================== | ================ | ============== | ============ | =================== | =================== | 
| MERCY MEDICAL CENTER                                           | 1-2820-00600/00004 | [http://www.dec.ny.gov/dardata/boss/afs/permits/128200060000004.pdf, null]    | 1000 N VILLAGE AVE       | ROCKVILLE CENTRE | NY             | 11570        | 2006-07-18T00:00:00 | 2016-07-17T00:00:00 | 
| SOUTH NASSAU COMMUNITIES HOSPITAL                              | 1-2820-00796/00002 | [http://www.dec.ny.gov/dardata/boss/afs/permits/128200079600002.pdf, null]    | 1 HEALTHY WAY            | OCEANSIDE        | NY             | 11572        | 2006-01-11T00:00:00 |                     | 
| RASON ASPHALT FACILITY                                         | 1-2820-01873/00009 | [http://www.dec.ny.gov/dardata/boss/afs/permits/128200187300009.pdf, null]    | 4 JOHNSON RD             | NORTH LAWRENCE   | NY             | 11559        | 2002-08-23T00:00:00 |                     | 
| OCEANSIDE LANDFILL GAS RECOVERY FACILITY                       | 1-2820-02479/00031 | [http://www.dec.ny.gov/dardata/boss/afs/permits/128200247900031.pdf, null]    | LONG BEACH RD & MOTT AVE | OCEANSIDE        | NY             | 11572        | 2006-10-27T00:00:00 |                     | 
| FORMED PLASTICS INC                                            | 1-2822-00111/00003 | [http://www.dec.ny.gov/dardata/boss/afs/permits/128220011100003.pdf, null]    | 207 STONEHINGE LN        | CARLE PLACE      | NY             | 11514        | 2000-02-01T00:00:00 |                     | 
| UNITED STATES MERCHANT MARINE ACADEMY                          | 1-2822-00573/00017 | [http://www.dec.ny.gov/dardata/boss/afs/permits/128220057300017.pdf, null]    | 300 STEAMBOAT RD         | KINGS POINT      | NY             | 11024        | 2001-02-14T00:00:00 |                     | 
| AIRCRAFT PROTECTIVE SYSTEMS A DIV OF TRIUMPH STRUCTURES LI LLC | 1-2822-01225/00001 | [http://www.dec.ny.gov/dardata/boss/afs/permits/128220122500001_r1.pdf, null] | 88 URBAN AVE             | WESTBURY         | NY             | 11590        | 2013-08-19T00:00:00 | 2018-08-18T00:00:00 | 
| NORTHROP GRUMMAN SYSTEMS CORPORATION                           | 1-2824-00112/00012 | [http://www.dec.ny.gov/dardata/boss/afs/permits/128240011200012.pdf, null]    | 600 GRUMMAN RD WEST      | BETHPAGE         | NY             | 11714        | 2006-02-09T00:00:00 |                     | 
| GLENWOOD BLACK START GT FACILITY                               | 1-2824-00490/00014 | [http://www.dec.ny.gov/dardata/boss/afs/permits/128240049000014.pdf, null]    | SHORE RD                 | GLENWOOD LANDING | NY             | 11547        | 2004-12-07T00:00:00 |                     | 
| TBG COGEN FACILITY                                             | 1-2824-00947/00005 | [http://www.dec.ny.gov/dardata/boss/afs/permits/128240094700005.pdf, null]    | 939 S BROADWAY           | HICKSVILLE       | NY             | 11801        | 2002-01-09T00:00:00 |                     | 
```