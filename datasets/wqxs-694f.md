# IDOL 2013 Registered Owner Rides

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idol-2013-registered-owner-rides-4abbf) |
| Metadata | [Link](https://data.illinois.gov/api/views/wqxs-694f) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/wqxs-694f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/wqxs-694f/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | wqxs-694f |
| Name | IDOL 2013 Registered Owner Rides |
| Attribution | Illinois Department of Labor |
| Category | Labor |
| Tags | amusement ride, permit, labor, 430 ilcs 85 |
| Created | 2013-07-22T21:39:47Z |
| Publication Date | 2014-04-17T19:34:00Z |

## Description

The following is a list of companies and their associated rides that have valid permits to operate amusement rides or attractions.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | numeric metric | permit       | Permit       | number    | number      |
| Yes      | series tag     | ridename     | Ridename     | text      | text        |
| Yes      | series tag     | ownername    | OwnerName    | text      | text        |
| Yes      | series tag     | manufacturer | Manufacturer | text      | text        |
| Yes      | series tag     | serialnumber | SerialNumber | text      | text        |
| No       |                | address      | Address      | text      | text        |
| No       |                | address2     | Address2     | text      | text        |
| Yes      | series tag     | city         | City         | text      | text        |
| Yes      | series tag     | state        | State        | text      | text        |
| Yes      | series tag     | zipcode      | Zipcode      | text      | text        |
| Yes      | series tag     | contactname  | ContactName  | text      | text        |
| Yes      | series tag     | contactphone | ContactPhone | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address,address2
```

## Data Commands

```ls
series e:wqxs-694f d:2013-01-01T00:00:00.000Z t:ownername="217 TERROR HAUNTED HOUSE" t:contactname="ADAM AND CHRISTINA CATHERS" t:manufacturer=HOMEMADE t:ridename="Haunted House" t:zipcode=62082- t:contactphone=217-320-4634 t:state=IL t:serialnumber=HH3204634 t:city=ROODHOUSE m:permit=11308

series e:wqxs-694f d:2013-01-01T00:00:00.000Z t:ownername="25/8 XTREME" t:contactname="JARED LEE" t:manufacturer="SPORT ROCK" t:ridename="Rock Wall" t:zipcode=61911- t:contactphone=217-259-4143 t:state=IL t:serialnumber=J9CF16262A215023 t:city=ARTHUR m:permit=11109

series e:wqxs-694f d:2013-01-01T00:00:00.000Z t:ownername="62 SPORTS/INCREDIBLE EVENTS" t:contactname="JERED CRAIG" t:manufacturer="MOONWALKER SALES" t:ridename="Inflatable, 2 Lane Bungee" t:zipcode=62084- t:contactphone=618-659-0262 t:state=IL t:serialnumber=BR-4 t:city=ROXANNA m:permit=9608
```

## Meta Commands

```ls
metric m:permit p:integer l:Permit t:dataTypeName=number

entity e:wqxs-694f l:"IDOL 2013 Registered Owner Rides" t:attribution="Illinois Department of Labor" t:url=https://data.illinois.gov/api/views/wqxs-694f

property e:wqxs-694f t:meta.view v:id=wqxs-694f v:category=Labor v:attributionLink=http://labor.illinois.gov v:averageRating=0 v:name="IDOL 2013 Registered Owner Rides" v:attribution="Illinois Department of Labor"

property e:wqxs-694f t:meta.view.license v:name="Public Domain"

property e:wqxs-694f t:meta.view.owner v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:displayName="IL Department of Labor"

property e:wqxs-694f t:meta.view.tableauthor v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:roleName=publisher v:displayName="IL Department of Labor"
```

## Top Records

```ls
| permit | ridename                         | ownername                   | manufacturer         | serialnumber     | address             | address2 | city      | state | zipcode | contactname                | contactphone | 
| ====== | ================================ | =========================== | ==================== | ================ | =================== | ======== | ========= | ===== | ======= | ========================== | ============ | 
| 11308  | Haunted House                    | 217 TERROR HAUNTED HOUSE    | HOMEMADE             | HH3204634        | 221 RAWLINGS STREET |          | ROODHOUSE | IL    | 62082-  | ADAM AND CHRISTINA CATHERS | 217-320-4634 | 
| 11109  | Rock Wall                        | 25/8 XTREME                 | SPORT ROCK           | J9CF16262A215023 | 317 E. LINCOLN      |          | ARTHUR    | IL    | 61911-  | JARED LEE                  | 217-259-4143 | 
| 9608   | Inflatable, 2 Lane Bungee        | 62 SPORTS/INCREDIBLE EVENTS | MOONWALKER SALES     | BR-4             | 4521 HEDGE ROAD     |          | ROXANNA   | IL    | 62084-  | JERED CRAIG                | 618-659-0262 | 
| 9692   | Inflatable, 24' Dual Slide - Gym | 62 SPORTS/INCREDIBLE EVENTS | AMUSEMENT SUPPLY     | 0212ABS0049      | 4521 HEDGE ROAD     |          | ROXANNA   | IL    | 62084-  | JERED CRAIG                | 618-659-0262 | 
| 9689   | Inflatable, 360 Challenge        | 62 SPORTS/INCREDIBLE EVENTS | MOONWALKER           | 4223             | 4521 HEDGE ROAD     |          | ROXANNA   | IL    | 62084-  | JERED CRAIG                | 618-659-0262 | 
| 9603   | Inflatable, Balloon Bounce       | 62 SPORTS/INCREDIBLE EVENTS | E INFLATABLES        | 4234             | 4521 HEDGE ROAD     |          | ROXANNA   | IL    | 62084-  | JERED CRAIG                | 618-659-0262 | 
| 11208  | Inflatable, Basketball Bungee    | 62 SPORTS/INCREDIBLE EVENTS | GET ZULU             | B413             | 4521 HEDGE ROAD     |          | ROXANNA   | IL    | 62084-  | JERED CRAIG                | 618-659-0262 | 
| 9341   | Inflatable, Black Ops - By       | 62 SPORTS/INCREDIBLE EVENTS | AMUSEMENT SUPPLY CO. | 0312AB0061       | 4521 HEDGE ROAD     |          | ROXANNA   | IL    | 62084-  | JERED CRAIG                | 618-659-0262 | 
| 11313  | Inflatable, Black Ops-gy         | 62 SPORTS/INCREDIBLE EVENTS | AMUSEMENT SUPPLY     | ASCBLKOB-GY      | 4521 HEDGE ROAD     |          | ROXANNA   | IL    | 62084-  | JERED CRAIG                | 618-659-0262 | 
| 9690   | Inflatable, Boulder Dash         | 62 SPORTS/INCREDIBLE EVENTS | CUTTING EDGE         | 19033            | 4521 HEDGE ROAD     |          | ROXANNA   | IL    | 62084-  | JERED CRAIG                | 618-659-0262 | 
```