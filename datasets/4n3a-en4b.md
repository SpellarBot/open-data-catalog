# Issued Title V Facility Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/issued-title-v-facility-permits) |
| Metadata | [Link](https://data.ny.gov/api/views/4n3a-en4b) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/4n3a-en4b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/4n3a-en4b/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 4n3a-en4b |
| Name | Issued Title V Facility Permits |
| Attribution | New York State Department of Environmental Conservation |
| Category | Energy & Environment |
| Tags | issued permit, emissions, air pollution, title v |
| Created | 2014-06-30T19:41:32Z |
| Publication Date | 2016-01-08T21:31:44Z |

## Description

Owners or operators of emission sources that are subject to 6 NYCRR Subpart 201-6 must obtain a Title V facility permit.  

Draft permits are official versions of permits whose initial development is complete, and that are being noticed and made available for public review and comment. 

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
| No       |             | expiration_date    | EXPIRATION DATE    | calendar_date | calendar_date |
```

## Time Field

```ls
Value = issue_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = expiration_date
```

## Data Commands

```ls
series e:4n3a-en4b d:2009-05-15T00:00:00.000Z t:facility_city=FREEPORT t:permit_id=1-2820-00358/00002 t:url_to_permit_text=http://www.dec.ny.gov/dardata/boss/afs/permits/128200035800002_r1.pdf t:facility_name="FREEPORT POWER PLANT #2" t:facility_zip=11520 t:facility_location="289 BUFFALO AVE" t:facility_state=NY m:row_number.4n3a-en4b=1

series e:4n3a-en4b d:2013-04-24T00:00:00.000Z t:facility_city=HEMPSTEAD t:permit_id=1-2820-00457/00003 t:url_to_permit_text=http://www.dec.ny.gov/dardata/boss/afs/permits/128200045700003_r2.pdf t:facility_name="HOFSTRA UNIVERSITY" t:facility_zip=11550 t:facility_location="1000 FULTON AVE" t:facility_state=NY m:row_number.4n3a-en4b=2

series e:4n3a-en4b d:2011-02-24T00:00:00.000Z t:facility_city="ISLAND PARK" t:permit_id=1-2820-00553/00025 t:url_to_permit_text=http://www.dec.ny.gov/dardata/boss/afs/permits/128200055300025_r2_1.pdf t:facility_name="EF BARRETT POWER STATION" t:facility_zip=11558 t:facility_location="1 MCCARTHY RD" t:facility_state=NY m:row_number.4n3a-en4b=3
```

## Meta Commands

```ls
metric m:row_number.4n3a-en4b p:long l:"Row Number"

entity e:4n3a-en4b l:"Issued Title V Facility Permits" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/4n3a-en4b

property e:4n3a-en4b t:meta.view v:id=4n3a-en4b v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/dardata/boss/afs/issued_atv.html v:averageRating=0 v:name="Issued Title V Facility Permits" v:attribution="New York State Department of Environmental Conservation"

property e:4n3a-en4b t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:4n3a-en4b t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| facility_name                               | permit_id          | url_to_permit_text                                                              | facility_location       | facility_city | facility_state | facility_zip | issue_date          | expiration_date     | 
| =========================================== | ================== | =============================================================================== | ======================= | ============= | ============== | ============ | =================== | =================== | 
| FREEPORT POWER PLANT #2                     | 1-2820-00358/00002 | [http://www.dec.ny.gov/dardata/boss/afs/permits/128200035800002_r1.pdf, null]   | 289 BUFFALO AVE         | FREEPORT      | NY             | 11520        | 2009-05-15T00:00:00 | 2014-05-14T00:00:00 | 
| HOFSTRA UNIVERSITY                          | 1-2820-00457/00003 | [http://www.dec.ny.gov/dardata/boss/afs/permits/128200045700003_r2.pdf, null]   | 1000 FULTON AVE         | HEMPSTEAD     | NY             | 11550        | 2013-04-24T00:00:00 | 2018-04-23T00:00:00 | 
| EF BARRETT POWER STATION                    | 1-2820-00553/00025 | [http://www.dec.ny.gov/dardata/boss/afs/permits/128200055300025_r2_1.pdf, null] | 1 MCCARTHY RD           | ISLAND PARK   | NY             | 11558        | 2011-02-24T00:00:00 | 2016-02-23T00:00:00 | 
| ROCKVILLE CENTRE POWER PLANT                | 1-2820-00753/00008 | [http://www.dec.ny.gov/dardata/boss/afs/permits/128200075300008_r1.pdf, null]   | 110 MAPLE AVE           | ROCKVILLE CTR | NY             | 11571        | 2014-04-30T00:00:00 | 2019-04-29T00:00:00 | 
| GLOBAL COMPANIES LLC - INWOOD TERMINAL      | 1-2820-00947/00002 | [http://www.dec.ny.gov/dardata/boss/afs/permits/128200094700002_r2_1.pdf, null] | 464 DOUGHTY BLVD        | INWOOD        | NY             | 11096        | 2012-01-17T00:00:00 | 2017-01-16T00:00:00 | 
| CARBO INDUSTRIES PROPERTY                   | 1-2820-01085/00006 | [http://www.dec.ny.gov/dardata/boss/afs/permits/128200108500006_r2_1.pdf, null] | 1 BAY BLVD              | LAWRENCE      | NY             | 11559        | 2012-01-17T00:00:00 | 2017-01-16T00:00:00 | 
| Motiva Enterprises LLC Long Island Terminal | 1-2820-01549/00004 | [http://www.dec.ny.gov/dardata/boss/afs/permits/128200154900004_r2.pdf, null]   | 74 EAST AVE             | LAWRENCE      | NY             | 11559        | 2012-06-20T00:00:00 | 2017-06-19T00:00:00 | 
| HEMPSTEAD RESOURCE RECOVERY FACILITY        | 1-2820-01727/00028 | [http://www.dec.ny.gov/dardata/boss/afs/permits/128200172700028_r2_1.pdf, null] | 600 MERCHANTS CONCOURSE | WESTBURY      | NY             | 11590        | 2010-12-01T00:00:00 | 2015-11-30T00:00:00 | 
| EQUUS FREEPORT POWER GENERATING STATION     | 1-2820-04508/00005 | [http://www.dec.ny.gov/dardata/boss/afs/permits/128200450800005_r1.pdf, null]   | 289 BUFFALO AVE         | FREEPORT      | NY             | 11520        | 2015-07-07T00:00:00 | 2020-07-06T00:00:00 | 
| NORTH SHORE UNIVERSITY HOSPITAL             | 1-2822-00248/00001 | [http://www.dec.ny.gov/dardata/boss/afs/permits/128220024800001_r3.pdf, null]   | 300 COMMUNITY DR        | MANHASSET     | NY             | 11030        | 2015-07-20T00:00:00 | 2020-07-19T00:00:00 | 
```