# IDOL 2014 Registered Owner Rides

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idol-2014-registered-owner-rides-ce192) |
| Metadata | [Link](https://data.illinois.gov/api/views/kt8p-q5ns) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/kt8p-q5ns/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/kt8p-q5ns/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | kt8p-q5ns |
| Name | IDOL 2014 Registered Owner Rides |
| Attribution | Illinois Department of Labor |
| Category | Labor |
| Tags | amusement ride, permit, labor, 430 ilcs 85 |
| Created | 2014-04-10T22:21:41Z |
| Publication Date | 2014-12-17T20:16:02Z |

## Description

The following is a list of companies and their associated rides that have valid permits to operate amusement rides or attractions.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | numeric metric | permit       | Permit       | number    | text        |
| Yes      | series tag     | ridename     | Ridename     | text      | text        |
| Yes      | series tag     | ownername    | OwnerName    | text      | text        |
| Yes      | series tag     | manufacturer | Manufacturer | text      | text        |
| Yes      | series tag     | serialnumber | SerialNumber | text      | text        |
| No       |                | address1     | Address1     | text      | text        |
| No       |                | address2     | Address2     | text      | text        |
| Yes      | series tag     | city         | City         | text      | text        |
| Yes      | series tag     | state        | State        | text      | text        |
| Yes      | series tag     | zipcode      | Zipcode      | text      | text        |
| Yes      | series tag     | contactname  | ContactName  | text      | text        |
| Yes      | series tag     | contactphone | ContactPhone | phone     | phone       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address1,address2
```

## Data Commands

```ls
series e:kt8p-q5ns d:2014-01-01T00:00:00.000Z t:phone_number="- -- -" t:ownername="13TH FLOOR" t:contactname="JIM UPCHURCH" t:manufacturer=HOMEMADE t:ridename="Haunted House" t:zipcode=60160 t:state=IL t:serialnumber=EH05 t:city="MELROSE PARK" m:permit=15009

series e:kt8p-q5ns d:2014-01-01T00:00:00.000Z t:phone_number=217-320-4634 t:ownername="217 TERROR HAUNTED HOUSE" t:contactname="ADAM AND CHRISTINA CATHERS" t:manufacturer=HOMEMADE t:ridename="Haunted House" t:zipcode=62082 t:state=IL t:serialnumber=HH3204634 t:city=ROODHOUSE m:permit=14915

series e:kt8p-q5ns d:2014-01-01T00:00:00.000Z t:phone_number=217-259-4143 t:ownername="25/8 XTREME" t:contactname="JARED LEE" t:manufacturer="SPORT ROCK" t:ridename="Rock Wall" t:zipcode=61911 t:state=IL t:serialnumber=J9CF16262A215023 t:city=ARTHUR m:permit=14921
```

## Meta Commands

```ls
metric m:permit p:integer l:Permit t:dataTypeName=number

entity e:kt8p-q5ns l:"IDOL 2014 Registered Owner Rides" t:attribution="Illinois Department of Labor" t:url=https://data.illinois.gov/api/views/kt8p-q5ns

property e:kt8p-q5ns t:meta.view v:id=kt8p-q5ns v:category=Labor v:attributionLink=http://labor.illinois.gov v:averageRating=0 v:name="IDOL 2014 Registered Owner Rides" v:attribution="Illinois Department of Labor"

property e:kt8p-q5ns t:meta.view.license v:name="Public Domain"

property e:kt8p-q5ns t:meta.view.owner v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:displayName="IL Department of Labor"

property e:kt8p-q5ns t:meta.view.tableauthor v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:roleName=publisher v:displayName="IL Department of Labor"
```

## Top Records

```ls
| permit | ridename                       | ownername                   | manufacturer           | serialnumber     | address1            | address2 | city         | state | zipcode | contactname                | contactphone         | 
| ====== | ============================== | =========================== | ====================== | ================ | =================== | ======== | ============ | ===== | ======= | ========================== | ==================== | 
| 15009  | Haunted House                  | 13TH FLOOR                  | HOMEMADE               | EH05             | 1940 GEORGE STREET  |          | MELROSE PARK | IL    | 60160   | JIM UPCHURCH               | [- -- -, null]       | 
| 14915  | Haunted House                  | 217 TERROR HAUNTED HOUSE    | HOMEMADE               | HH3204634        | 221 RAWLINGS STREET |          | ROODHOUSE    | IL    | 62082   | ADAM AND CHRISTINA CATHERS | [217-320-4634, null] | 
| 14921  | Rock Wall                      | 25/8 XTREME                 | SPORT ROCK             | J9CF16262A215023 | 317 E. LINCOLN      |          | ARTHUR       | IL    | 61911   | JARED LEE                  | [217-259-4143, null] | 
| 13216  | Inflatable, Joust#1            | 62 SPORTS/INCREDIBLE EVENTS | HEC/MOONWALKER SALES   | 1004             | 4521 HEDGE ROAD     |          | ROXANNA      | IL    | 62084   | MIKE GILL                  | [618-659-0262, null] | 
| 13217  | Inflatable, Crayon Bounce      | 62 SPORTS/INCREDIBLE EVENTS | MOONWALKER SALES       | CBS1006          | 4521 HEDGE ROAD     |          | ROXANNA      | IL    | 62084   | MIKE GILL                  | [618-659-0262, null] | 
| 13218  | Inflatable, Dino Bounce        | 62 SPORTS/INCREDIBLE EVENTS | CUTTING EDGE           | 15085            | 4521 HEDGE ROAD     |          | ROXANNA      | IL    | 62084   | MIKE GILL                  | [618-659-0262, null] | 
| 13219  | Inflatable, Ice Age Bounce     | 62 SPORTS/INCREDIBLE EVENTS | NINJA JUMP             | RJ5171           | 4521 HEDGE ROAD     |          | ROXANNA      | IL    | 62084   | MIKE GILL                  | [618-659-0262, null] | 
| 13220  | Inflatable, Tiger Belly        | 62 SPORTS/INCREDIBLE EVENTS | CUTTING EDGE CREATIONS | TB-1             | 4521 HEDGE ROAD     |          | ROXANNA      | IL    | 62084   | MIKE GILL                  | [618-659-0262, null] | 
| 13221  | Inflatable, Bouncy Boxing      | 62 SPORTS/INCREDIBLE EVENTS | MOONWALKER SALES       | BRC1001          | 4521 HEDGE ROAD     |          | ROXANNA      | IL    | 62084   | MIKE GILL                  | [618-659-0262, null] | 
| 13222  | Inflatable, Skid Loader Bounce | 62 SPORTS/INCREDIBLE EVENTS | CUTTING EDGE           | 25501            | 4521 HEDGE ROAD     |          | ROXANNA      | IL    | 62084   | MIKE GILL                  | [618-659-0262, null] | 
```