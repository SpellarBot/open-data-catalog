# SSMMA TOD Zoning

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-tod-zoning-8f04c) |
| Metadata | [Link](https://data.illinois.gov/api/views/jtrb-dted) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/jtrb-dted/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/jtrb-dted/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | jtrb-dted |
| Name | SSMMA TOD Zoning |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | transit oriented development, tod, economic development, planning, community development |
| Created | 2012-11-27T20:49:01Z |
| Publication Date | 2012-11-27T20:50:13Z |

## Description

This dataset was compiled during the Chicago Southland Transit Corridor project in 2011. This details parcel-level zoning for a half mile around transit-oriented development areas in the Chicago Southland.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | objectid    | OBJECTID   | text      | number      |
| Yes      | numeric metric | pin14       | PIN14      | number    | number      |
| Yes      | series tag     | zoning      | ZONING     | text      | text        |
| Yes      | series tag     | gen_zone    | GEN_ZONE   | text      | text        |
| Yes      | series tag     | place       | PLACE      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:jtrb-dted d:2012-11-27T12:49:04.000Z t:gen_zone=NONE t:place="BLUE ISLAND" t:objectid=1 t:zoning=NONE m:pin14=25305000090000

series e:jtrb-dted d:2012-11-27T12:49:04.000Z t:gen_zone=NONE t:place="CALUMET PARK" t:objectid=2 t:zoning=NONE m:pin14=25305010020000

series e:jtrb-dted d:2012-11-27T12:49:04.000Z t:gen_zone=INDUSTRIAL t:place="BLUE ISLAND" t:objectid=3 t:zoning=I1 m:pin14=25304000010000
```

## Meta Commands

```ls
metric m:pin14 p:long l:PIN14 t:dataTypeName=number

entity e:jtrb-dted l:"SSMMA TOD Zoning" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/jtrb-dted

property e:jtrb-dted t:meta.view v:id=jtrb-dted v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA TOD Zoning" v:attribution="South Suburban Mayors and Managers Association"

property e:jtrb-dted t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:jtrb-dted t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:jtrb-dted t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| :updated_at | objectid | pin14          | zoning | gen_zone    | place        | 
| =========== | ======== | ============== | ====== | =========== | ============ | 
| 1354020544  | 1        | 25305000090000 | NONE   | NONE        | BLUE ISLAND  | 
| 1354020544  | 2        | 25305010020000 | NONE   | NONE        | CALUMET PARK | 
| 1354020544  | 3        | 25304000010000 | I1     | INDUSTRIAL  | BLUE ISLAND  | 
| 1354020544  | 4        | 25304000140000 | I      | INDUSTRIAL  | CALUMET PARK | 
| 1354020544  | 5        | 25304060150000 | R      | RESIDENTIAL | CALUMET PARK | 
| 1354020544  | 6        | 25304060540000 | R      | RESIDENTIAL | CALUMET PARK | 
| 1354020544  | 7        | 25304060530000 | R      | RESIDENTIAL | CALUMET PARK | 
| 1354020544  | 8        | 25304060520000 | R      | RESIDENTIAL | CALUMET PARK | 
| 1354020544  | 9        | 25304060510000 | R      | RESIDENTIAL | CALUMET PARK | 
| 1354020544  | 10       | 25304060500000 | R      | RESIDENTIAL | CALUMET PARK | 
```