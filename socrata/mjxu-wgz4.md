# IDOL 2015 Registered Owner Rides

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idol-2015-registered-owner-rides-8061d) |
| Metadata | [Link](https://data.illinois.gov/api/views/mjxu-wgz4) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/mjxu-wgz4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/mjxu-wgz4/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | mjxu-wgz4 |
| Name | IDOL 2015 Registered Owner Rides |
| Attribution | Illinois Department of Labor |
| Category | Labor |
| Tags | amusement ride, permit, labor, 430 ilcs 85 |
| Created | 2014-12-17T20:26:24Z |
| Publication Date | 2015-11-30T16:08:55Z |

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
| Yes      | series tag     | contactname  | ContactName  | text      | text        |
| Yes      | series tag     | contactphone | ContactPhone | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mjxu-wgz4 d:2015-01-01T00:00:00.000Z t:ownername="SIX FLAGS GREAT AMERICA" t:contactname="GARY POHLMAN" t:manufacturer=HUSS t:ridename="Top Spin" t:serialnumber=KC0404 m:permit=6087

series e:mjxu-wgz4 d:2015-01-01T00:00:00.000Z t:ownername="DRS SKINNERS' AMUSEMENTS, INC." t:contactname="PAT SKINNER" t:manufacturer="HIGH LITE RIDES INC." t:ridename="Merry Go Round #1" t:contactphone=815-943-7961 t:serialnumber=6316020 m:permit=5055

series e:mjxu-wgz4 d:2015-01-01T00:00:00.000Z t:ownername="RAGING BUFFALO SNOWBOARD SKI PARK" t:contactname="KEITH DUCK" t:manufacturer="ROCKY MOUNTAIN CONVEYOR" t:ridename="Magic Carpet" t:contactphone=847-836-7243 t:serialnumber=L0364 m:permit=5062
```

## Meta Commands

```ls
metric m:permit p:integer l:Permit t:dataTypeName=number

entity e:mjxu-wgz4 l:"IDOL 2015 Registered Owner Rides" t:attribution="Illinois Department of Labor" t:url=https://data.illinois.gov/api/views/mjxu-wgz4

property e:mjxu-wgz4 t:meta.view v:id=mjxu-wgz4 v:category=Labor v:attributionLink=http://ridesafety.illinois.gov v:averageRating=0 v:name="IDOL 2015 Registered Owner Rides" v:attribution="Illinois Department of Labor"

property e:mjxu-wgz4 t:meta.view.license v:name="Public Domain"

property e:mjxu-wgz4 t:meta.view.owner v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:displayName="IL Department of Labor"

property e:mjxu-wgz4 t:meta.view.tableauthor v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:roleName=publisher v:displayName="IL Department of Labor"
```

## Top Records

```ls
| permit | ridename                         | ownername                         | manufacturer                | serialnumber | contactname    | contactphone | 
| ====== | ================================ | ================================= | =========================== | ============ | ============== | ============ | 
| 6087   | Top Spin                         | SIX FLAGS GREAT AMERICA           | HUSS                        | KC0404       | GARY POHLMAN   |              | 
| 5055   | Merry Go Round #1                | DRS SKINNERS' AMUSEMENTS, INC.    | HIGH LITE RIDES INC.        | 6316020      | PAT SKINNER    | 815-943-7961 | 
| 5062   | Magic Carpet                     | RAGING BUFFALO SNOWBOARD SKI PARK | ROCKY MOUNTAIN CONVEYOR     | L0364        | KEITH DUCK     | 847-836-7243 | 
| 5063   | Rope Tow #2                      | RAGING BUFFALO SNOWBOARD SKI PARK | HOLIDAY PARK                | 8838         | KEITH DUCK     | 847-836-7243 | 
| 5064   | Rope Tow #1                      | RAGING BUFFALO SNOWBOARD SKI PARK | HOLIDAY PARK                | 7243         | KEITH DUCK     | 847-836-7243 | 
| 5105   | Union Pacific Classic Train      | JOLLY EXPRESS OF CHICAGO          | FALGAS                      | 31315        | JAYME ANGUIANO | 630-518-2539 | 
| 5212   | Trackless Train #3               | JOLLY EXPRESS OF CHICAGO          | TRUE AMERICAN CLASSICS, INC | TAC07272011  | JAYME ANGUIANO | 630-518-2539 | 
| 5213   | Inflatable, Fun Combo X2         | SUPER BOUNCE INFLATABLES, INC.    | MAJIC JUMP                  | 121238102    | JAYME ANGUIANO | 847-428-3211 | 
| 5214   | Inflatable, Lil Pirates          | SUPER BOUNCE INFLATABLES, INC.    | NINJA JUMP                  | INTL93102    | JAYME ANGUIANO | 847-428-3211 | 
| 5215   | Inflatable, Dora/diego Lrng Adv. | SUPER BOUNCE INFLATABLES, INC.    | NINJA JUMP INC.             | INTL93659    | JAYME ANGUIANO | 847-428-3211 | 
```