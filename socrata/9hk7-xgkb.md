# Draft State Facility Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/draft-state-facility-permits) |
| Metadata | [Link](https://data.ny.gov/api/views/9hk7-xgkb) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/9hk7-xgkb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/9hk7-xgkb/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 9hk7-xgkb |
| Name | Draft State Facility Permits |
| Attribution | New York State Department of Environmental Conservation |
| Category | Energy & Environment |
| Tags | draft permit, emissions, air pollution, state facility |
| Created | 2014-07-02T21:26:43Z |
| Publication Date | 2016-01-08T22:59:11Z |

## Description

Owners or operators of emission sources that are subject to 6 NYCRR Subpart 201-5 must obtain a State facility permit.  

Draft permits are official versions of permits whose initial development is complete, public notice given, and made available for public review and comment.
  
These permits are prepared by the Division of Air Resources regional staff.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | facility_name      | FACILITY NAME      | text          | text          |
| Yes      | series tag     | permit_id          | PERMIT ID          | text          | text          |
| Yes      | numeric metric | mod                | MOD                | number        | number        |
| Yes      | series tag     | url_to_permit_text | URL TO PERMIT TEXT | url           | url           |
| Yes      | time           | comment_end_date   | COMMENT END DATE   | calendar_date | calendar_date |
| No       |                | comment_begin_date | COMMENT BEGIN DATE | calendar_date | calendar_date |
| Yes      | series tag     | facility_location  | FACILITY LOCATION  | text          | text          |
| Yes      | series tag     | facility_city      | FACILITY CITY      | text          | text          |
| Yes      | series tag     | facility_state     | FACILITY STATE     | text          | text          |
| Yes      | series tag     | facility_zip       | FACILITY ZIP       | text          | number        |
```

## Time Field

```ls
Value = comment_end_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = comment_begin_date
```

## Data Commands

```ls
series e:9hk7-xgkb d:2015-10-02T00:00:00.000Z t:facility_city="NEW YORK" t:permit_id=2-6205-01784/00001 t:url_to_permit_text=http://www.dec.ny.gov/dardata/boss/afs/permits/262050178400001.pdf t:facility_name="20 HUDSON YARDS" t:facility_zip=10001 t:facility_location="500 W 33RD ST, B:702 L:4,10,125,150|501-553 W 30TH ST AND 500-560 W 33RD ST" t:facility_state=NY m:mod=0

series e:9hk7-xgkb d:2015-09-04T00:00:00.000Z t:facility_city=PLATTSBURGH t:permit_id=5-0942-00494/00001 t:url_to_permit_text=http://www.dec.ny.gov/dardata/boss/afs/permits/509420049400001.pdf t:facility_name="BFG INTERNATIONAL USA LLC - Martina" t:facility_zip=12901 t:facility_location="44 MARTINA CIR" t:facility_state=NY m:mod=0

series e:9hk7-xgkb d:2015-08-28T00:00:00.000Z t:facility_city="LITTLE FALLS" t:permit_id=6-2109-00003/00007 t:url_to_permit_text=http://www.dec.ny.gov/dardata/boss/afs/permits/621090000300007_r1.pdf t:facility_name="BURROWS PAPER CORP - MILL ST FAC" t:facility_zip=13365 t:facility_location="730 E MILL ST" t:facility_state=NY m:mod=0
```

## Meta Commands

```ls
metric m:mod p:integer l:MOD d:"The iteration of this revision to the active permit which is currently in the draft phase." t:dataTypeName=number

entity e:9hk7-xgkb l:"Draft State Facility Permits" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/9hk7-xgkb

property e:9hk7-xgkb t:meta.view v:id=9hk7-xgkb v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/dardata/boss/afs/draft_asf.html v:averageRating=0 v:name="Draft State Facility Permits" v:attribution="New York State Department of Environmental Conservation"

property e:9hk7-xgkb t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:9hk7-xgkb t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| facility_name                                  | permit_id          | mod | url_to_permit_text                                                            | comment_end_date    | comment_begin_date  | facility_location                                                           | facility_city   | facility_state | facility_zip | 
| ============================================== | ================== | === | ============================================================================= | =================== | =================== | =========================================================================== | =============== | ============== | ============ | 
| 20 HUDSON YARDS                                | 2-6205-01784/00001 | 0   | [http://www.dec.ny.gov/dardata/boss/afs/permits/262050178400001.pdf, null]    | 2015-10-02T00:00:00 | 2015-09-02T00:00:00 | 500 W 33RD ST, B:702 L:4,10,125,150|501-553 W 30TH ST AND 500-560 W 33RD ST | NEW YORK        | NY             | 10001        | 
| BFG INTERNATIONAL USA LLC - Martina            | 5-0942-00494/00001 | 0   | [http://www.dec.ny.gov/dardata/boss/afs/permits/509420049400001.pdf, null]    | 2015-09-04T00:00:00 | 2015-08-05T00:00:00 | 44 MARTINA CIR                                                              | PLATTSBURGH     | NY             | 12901        | 
| BURROWS PAPER CORP - MILL ST FAC               | 6-2109-00003/00007 | 0   | [http://www.dec.ny.gov/dardata/boss/afs/permits/621090000300007_r1.pdf, null] | 2015-08-28T00:00:00 | 2015-07-29T00:00:00 | 730 E MILL ST                                                               | LITTLE FALLS    | NY             | 13365        | 
| DEEP GREEN OF NEW YORK SOIL RECYCLING FACILITY | 3-3348-00150/00013 | 0   | [http://www.dec.ny.gov/dardata/boss/afs/permits/333480015000013_r1.pdf, null] | 2015-09-18T00:00:00 | 2015-08-19T00:00:00 | 1106 RIVER RD                                                               | NEW WINDSOR     | NY             | 12553        | 
| DRESSER-RAND COMPANY - OLEAN OPERATIONS        | 9-0412-00012/00055 | 0   | [http://www.dec.ny.gov/dardata/boss/afs/permits/904120001200055_r1.pdf, null] | 2015-09-11T00:00:00 | 2015-08-12T00:00:00 | 500 PAUL CLARK DR                                                           | OLEAN           | NY             | 14760        | 
| GE FUEL CELLS LLC                              | 5-4140-00235/00002 | 0   | [http://www.dec.ny.gov/dardata/boss/afs/permits/541400023500002.pdf, null]    | 2015-10-02T00:00:00 | 2015-09-02T00:00:00 | 107 HERMES RD                                                               | BALLSTON SPA    | NY             | 12020        | 
| HONEOYE FALLS QUARRY & ASPHALT PLANT           | 8-9908-00113/00033 | 0   | [http://www.dec.ny.gov/dardata/boss/afs/permits/899080011300033.pdf, null]    | 2015-08-28T00:00:00 | 2015-07-29T00:00:00 | HONEOYE FALLS RD #6 & DALTON RD                                             | LIMA            | NY             | 14472        | 
| IBM CORP                                       | 3-3354-00261/00013 | 0   | [http://www.dec.ny.gov/dardata/boss/afs/permits/333540026100013.pdf, null]    | 2015-08-28T00:00:00 | 2015-07-29T00:00:00 | 299 LONG MEADOW RD                                                          | STERLING FOREST | NY             | 10979        | 
| MOLDTECH INC                                   | 9-1452-00284/00001 | 2   | [http://www.dec.ny.gov/dardata/boss/afs/permits/914520028400001.pdf, null]    | 2015-08-21T00:00:00 | 2015-07-22T00:00:00 | 1900 COMMERCE PKWY                                                          | LANCASTER       | NY             | 14086        | 
| NYC-DOS EAST 91ST ST MTS                       | 2-6204-00007/00016 | 0   | [http://www.dec.ny.gov/dardata/boss/afs/permits/262040000700016_r1.pdf, null] | 2015-07-24T00:00:00 | 2015-06-24T00:00:00 | E 91ST ST & EAST RIVER                                                      | NEW YORK        | NY             | 10028        | 
```