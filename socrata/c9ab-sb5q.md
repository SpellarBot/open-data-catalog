# SSMMA Brownfields

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-brownfields-d3b4f) |
| Metadata | [Link](https://data.illinois.gov/api/views/c9ab-sb5q) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/c9ab-sb5q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/c9ab-sb5q/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | c9ab-sb5q |
| Name | SSMMA Brownfields |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | brownfields, epa, planning, economic development, land use |
| Created | 2012-11-27T21:03:58Z |
| Publication Date | 2012-11-27T21:05:25Z |

## Description

This dataset details the brownfields in the Chicago Southland region. The sites are all recipients of various Brownfield Assessment and Revolving Loan Funds administered by the ILEPA and SSMMA.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type     | Render Type   |
| ======== | ============== | ========== | ========== | ============= | ============= |
| Yes      | series tag     | objectid   | OBJECTID   | text          | number        |
| Yes      | series tag     | sitename   | SITENAME   | text          | text          |
| Yes      | series tag     | municipali | MUNICIPALI | text          | text          |
| Yes      | series tag     | county     | COUNTY     | text          | text          |
| Yes      | numeric metric | pin14      | PIN14      | number        | number        |
| Yes      | series tag     | brownfield | BROWNFIELD | text          | text          |
| Yes      | series tag     | brownfie_1 | BROWNFIE_1 | text          | text          |
| Yes      | series tag     | property_o | PROPERTY_O | text          | text          |
| Yes      | series tag     | property_1 | PROPERTY_1 | text          | text          |
| Yes      | series tag     | property_2 | PROPERTY_2 | text          | text          |
| Yes      | series tag     | brownfie_3 | BROWNFIE_3 | text          | text          |
| Yes      | series tag     | acreage    | ACREAGE    | text          | text          |
| Yes      | time           | record_cre | RECORD_CRE | calendar_date | calendar_date |
| Yes      | series tag     | record_upd | RECORD_UPD | text          | text          |
| Yes      | series tag     | grant      | GRANT      | text          | text          |
| Yes      | series tag     | editor     | EDITOR     | text          | text          |
| Yes      | numeric metric | propreitar | PROPREITAR | number        | number        |
| Yes      | series tag     | universali | UNIVERSALI | text          | text          |
| Yes      | numeric metric | shape_leng | SHAPE_Leng | number        | number        |
| Yes      | numeric metric | shape_area | SHAPE_Area | number        | number        |
| Yes      | series tag     | website    | WEBSITE    | text          | text          |
| Yes      | series tag     | bit_websit | BIT_WEBSIT | text          | text          |
| Yes      | series tag     | acres      | ACRES      | text          | text          |
| Yes      | series tag     | location_1 | Location 1 | text          | text          |
```

## Time Field

```ls
Value = record_cre
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:c9ab-sb5q d:2012-04-12T00:00:00.000Z t:editor=MJR t:sitename="Monarch Roofing Company" t:county=Cook t:brownfie_1="Industrial Site" t:location_1="13747 Western Avenue" t:objectid=1 t:universali=UR1 t:municipali="Blue Island" t:brownfield=Potential-Municipal m:shape_area=52609.9071664 m:shape_leng=936.575587704 m:pin14=29061060410000 m:propreitar=1

series e:c9ab-sb5q d:2012-04-12T00:00:00.000Z t:editor=MJR t:sitename="Broadway Auto Wreckers" t:county=Cook t:brownfie_1="Building Structure" t:location_1="13545 Sacramento Avenue" t:objectid=2 t:universali=UR2 t:municipali="Blue Island" t:brownfield=Potential-Municipal m:shape_area=134591.158329 m:shape_leng=1474.93431994 m:pin14=28011020110000 m:propreitar=2

series e:c9ab-sb5q d:2012-04-12T00:00:00.000Z t:editor=MJR t:sitename="G&W Electric Company" t:county=Cook t:brownfie_1="Building Structure" t:location_1="12602 Central Park Avenue" t:objectid=3 t:universali=UR3 t:municipali="Blue Island" t:brownfield=Potential-Municipal m:shape_area=286970.294662 m:shape_leng=2413.78310309 m:pin14=24264030110000 m:propreitar=3
```

## Meta Commands

```ls
metric m:pin14 p:long l:PIN14 t:dataTypeName=number

metric m:propreitar p:integer l:PROPREITAR t:dataTypeName=number

metric m:shape_leng p:double l:SHAPE_Leng t:dataTypeName=number

metric m:shape_area p:double l:SHAPE_Area t:dataTypeName=number

entity e:c9ab-sb5q l:"SSMMA Brownfields" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/c9ab-sb5q

property e:c9ab-sb5q t:meta.view v:id=c9ab-sb5q v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Brownfields" v:attribution="South Suburban Mayors and Managers Association"

property e:c9ab-sb5q t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:c9ab-sb5q t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:c9ab-sb5q t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| objectid | sitename                | municipali  | county | pin14          | brownfield          | brownfie_1         | property_o | property_1 | property_2 | brownfie_3 | acreage | record_cre          | record_upd | grant | editor | propreitar | universali | shape_leng    | shape_area    | website | bit_websit | acres | location_1                | 
| ======== | ======================= | =========== | ====== | ============== | =================== | ================== | ========== | ========== | ========== | ========== | ======= | =================== | ========== | ===== | ====== | ========== | ========== | ============= | ============= | ======= | ========== | ===== | ========================= | 
| 1        | Monarch Roofing Company | Blue Island | Cook   | 29061060410000 | Potential-Municipal | Industrial Site    |            |            |            |            |         | 2012-04-12T00:00:00 |            |       | MJR    | 1          | UR1        | 936.575587704 | 52609.9071664 |         |            |       | 13747 Western Avenue      | 
| 2        | Broadway Auto Wreckers  | Blue Island | Cook   | 28011020110000 | Potential-Municipal | Building Structure |            |            |            |            |         | 2012-04-12T00:00:00 |            |       | MJR    | 2          | UR2        | 1474.93431994 | 134591.158329 |         |            |       | 13545 Sacramento Avenue   | 
| 3        | G&W Electric Company    | Blue Island | Cook   | 24264030110000 | Potential-Municipal | Building Structure |            |            |            |            |         | 2012-04-12T00:00:00 |            |       | MJR    | 3          | UR3        | 2413.78310309 | 286970.294662 |         |            |       | 12602 Central Park Avenue | 
| 4        | Taxpayer                | Blue Island | Cook   | 28011110350000 | Potential-Municipal | Industrial Site    |            |            |            |            |         | 2012-04-12T00:00:00 |            |       | MJR    | 4          | UR4        | 916.531845214 | 19233.4082591 |         |            |       | 13745 Sacramento Avenue   | 
| 5        | Worth Steel Machinery   | Blue Island | Cook   | 29061030100000 | Potential-Municipal | Industrial Site    |            |            |            |            |         | 2012-04-12T00:00:00 |            |       | MJR    | 5          | UR5        | 954.879831231 | 29770.2016802 |         |            |       | 13550 Chatham Street      | 
| 6        | Taxpayer Of             | Blue Island | Cook   | 24254190040000 | Potential-Municipal | Building Structure |            |            |            |            |         | 2012-04-12T00:00:00 |            |       | MJR    | 6          | UR6        | 374.748130409 | 5624.87727839 |         |            |       | 12513 Maple Avenue        | 
| 7        | Frances D Lembke        | Blue Island | Cook   | 24361010100000 | Potential-Municipal | Building Structure |            |            |            |            |         | 2012-04-12T00:00:00 |            |       | MJR    | 7          | UR7        | 301.84878911  | 3157.31618892 |         |            |       | 2933 Burr Oak Avenue      | 
| 8        | Carl Gustavson          | Blue Island | Cook   | 24361010110000 | Potential-Municipal | Building Structure |            |            |            |            |         | 2012-04-12T00:00:00 |            |       | MJR    | 8          | UR8        | 301.988210461 | 3161.04180162 |         |            |       | 2923 Burr Oak Avenue      | 
| 9        | Carl Gustavson          | Blue Island | Cook   | 24361010130000 | Potential-Municipal | Building Structure |            |            |            |            |         | 2012-04-12T00:00:00 |            |       | MJR    | 9          | UR9        | 352.370929771 | 6324.36651911 |         |            |       | 2923 Burr Oak Avenue      | 
| 10       | Carl Gustavson          | Blue Island | Cook   | 24361010120000 | Potential-Municipal | Building Structure |            |            |            |            |         | 2012-04-12T00:00:00 |            |       | MJR    | 10         | UR10       | 302.007376437 | 3158.25980578 |         |            |       | 2923 W. Burr Oak Avenue   | 
```