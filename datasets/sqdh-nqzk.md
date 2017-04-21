# Draft Title V Facility Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/draft-title-v-facility-permits) |
| Metadata | [Link](https://data.ny.gov/api/views/sqdh-nqzk) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/sqdh-nqzk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/sqdh-nqzk/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | sqdh-nqzk |
| Name | Draft Title V Facility Permits |
| Attribution | New York State Department of Environmental Conservation |
| Category | Energy & Environment |
| Tags | issued permit, emissions, air pollution, title v |
| Created | 2014-07-02T21:09:44Z |
| Publication Date | 2016-01-08T23:21:57Z |

## Description

Owners or operators of emission sources that are subject to 6 NYCRR Subpart 201-6 must obtain a Title V facility permit.  

Draft permits are official versions of permits whose initial development is complete, and that are being noticed and made available for public review and comment. 

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
series e:sqdh-nqzk d:2015-10-02T00:00:00.000Z t:facility_city=HICKSVILLE t:permit_id=1-2824-00947/00004 t:url_to_permit_text=http://www.dec.ny.gov/dardata/boss/afs/permits/128240094700004_r3.pdf t:facility_name="TBG COGEN FACILITY" t:facility_zip=11801 t:facility_location="939 S BROADWAY" t:facility_state=NY m:mod=0

series e:sqdh-nqzk d:2015-09-18T00:00:00.000Z t:facility_city=RIVERHEAD t:permit_id=1-4730-00023/00030 t:url_to_permit_text=http://www.dec.ny.gov/dardata/boss/afs/permits/147300002300030_r2.pdf t:facility_name="UNITED RIVERHEAD TERMINAL" t:facility_zip=11901 t:facility_location="212 SOUND SHORE RD" t:facility_state=NY m:mod=0

series e:sqdh-nqzk d:2015-09-04T00:00:00.000Z t:facility_city=BRONX t:permit_id=2-6007-00726/00003 t:url_to_permit_text=http://www.dec.ny.gov/dardata/boss/afs/permits/260070072600003_r2.pdf t:facility_name="HARLEM RIVER YARDS PLANT" t:facility_zip=10454 t:facility_location="E 132ND ST & ROBERT F KENNEDY BRIDGE APPR|APPR 688 EAST 132ND STREET" t:facility_state=NY m:mod=0
```

## Meta Commands

```ls
metric m:mod p:integer l:MOD d:"The iteration of this revision to the active permit which is currently in the draft phase." t:dataTypeName=number

entity e:sqdh-nqzk l:"Draft Title V Facility Permits" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/sqdh-nqzk

property e:sqdh-nqzk t:meta.view v:id=sqdh-nqzk v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/dardata/boss/afs/draft_atv.html v:averageRating=0 v:name="Draft Title V Facility Permits" v:attribution="New York State Department of Environmental Conservation"

property e:sqdh-nqzk t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:sqdh-nqzk t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| facility_name                             | permit_id          | mod | url_to_permit_text                                                              | comment_end_date    | comment_begin_date  | facility_location                                                    | facility_city | facility_state | facility_zip | 
| ========================================= | ================== | === | =============================================================================== | =================== | =================== | ==================================================================== | ============= | ============== | ============ | 
| TBG COGEN FACILITY                        | 1-2824-00947/00004 | 0   | [http://www.dec.ny.gov/dardata/boss/afs/permits/128240094700004_r3.pdf, null]   | 2015-10-02T00:00:00 | 2015-09-02T00:00:00 | 939 S BROADWAY                                                       | HICKSVILLE    | NY             | 11801        | 
| UNITED RIVERHEAD TERMINAL                 | 1-4730-00023/00030 | 0   | [http://www.dec.ny.gov/dardata/boss/afs/permits/147300002300030_r2.pdf, null]   | 2015-09-18T00:00:00 | 2015-08-19T00:00:00 | 212 SOUND SHORE RD                                                   | RIVERHEAD     | NY             | 11901        | 
| HARLEM RIVER YARDS PLANT                  | 2-6007-00726/00003 | 0   | [http://www.dec.ny.gov/dardata/boss/afs/permits/260070072600003_r2.pdf, null]   | 2015-09-04T00:00:00 | 2015-08-05T00:00:00 | E 132ND ST & ROBERT F KENNEDY BRIDGE APPR|APPR 688 EAST 132ND STREET | BRONX         | NY             | 10454        | 
| NYPA JOSEPH J SEYMOUR - 23RD ST & 3RD AVE | 2-6102-00482/00006 | 0   | [http://www.dec.ny.gov/dardata/boss/afs/permits/261020048200006_r2.pdf, null]   | 2015-09-25T00:00:00 | 2015-08-26T00:00:00 | 730 3RD AVE                                                          | BROOKLYN      | NY             | 11232        | 
| NYC-HH - KINGS COUNTY HOSPITAL CENTER     | 2-6104-00249/00004 | 2   | [http://www.dec.ny.gov/dardata/boss/afs/permits/261040024900004_r2_2.pdf, null] | 2015-09-25T00:00:00 | 2015-08-26T00:00:00 | 451 CLARKSON AVE                                                     | BROOKLYN      | NY             | 11203        | 
| GLOBAL COMPANIES LLC - NEWBURGH TERMINAL  | 3-3348-00111/00023 | 0   | [http://www.dec.ny.gov/dardata/boss/afs/permits/333480011100023_r3.pdf, null]   | 2015-08-28T00:00:00 | 2015-07-29T00:00:00 | 1281 RIVER RD                                                        | NEW WINDSOR   | NY             | 12553        | 
| GLOBAL COMPANIES - SOUTH TERMINAL         | 3-3348-00197/00053 | 0   | [http://www.dec.ny.gov/dardata/boss/afs/permits/333480019700053_r3.pdf, null]   | 2015-08-28T00:00:00 | 2015-07-29T00:00:00 | 1184 RIVER RD                                                        | NEW WINDSOR   | NY             | 12553        | 
| AVERY DENNISON RIS, LLC.                  | 3-3924-00173/00010 | 0   | [http://www.dec.ny.gov/dardata/boss/afs/permits/339240017300010_r2.pdf, null]   | 2015-06-12T00:00:00 | 2015-05-13T00:00:00 | 524 ST RTE 303                                                       | ORANGEBURG    | NY             | 10962        | 
| ALGONQUIN GAS: STONY POINT COMPRESSOR STA | 3-3928-00001/00027 | 0   | [http://www.dec.ny.gov/dardata/boss/afs/permits/339280000100027_r3.pdf, null]   | 2015-08-28T00:00:00 | 2015-07-29T00:00:00 | LINDBERG RD                                                          | STONY POINT   | NY             | 10980        | 
| ALBANY LANDFILL GAS TO ENERGY FACILITY    | 4-0101-00426/00001 | 0   | [http://www.dec.ny.gov/dardata/boss/afs/permits/401010042600001_r1.pdf, null]   | 2015-10-09T00:00:00 | 2015-09-09T00:00:00 | RAPP RD                                                              | ALBANY        | NY             | 12205        | 
```